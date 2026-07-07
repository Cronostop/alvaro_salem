# Anexo II

##  1. Modelado en Autocad

![](../images/ENTREGA%20FINAL/anexos/06.%20AUTOCAD.jpg)

##  2. Modelado en Corel draw para impresión laser
![](../images/ENTREGA%20FINAL/anexos/07.%20COREL.jpg)

##  3. impresión 3d de fichas de animales
![](../images/ENTREGA%20FINAL/anexos/08.%20IMPRESION%203D.jpg)

##  4. Elementos
![](../images/ENTREGA%20FINAL/anexos/10a.%20ELEMENTOS.jpg)

##  5. Instalación sistemas eléctricos
![](../images/ENTREGA%20FINAL/anexos/09.%20ELCTRONICA.jpg)

##  6. Flow Chart para el Arduino de 2 botones
![](../images/ENTREGA%20FINAL/anexos/11.%20flowchart%20arduino.jpg)


#### Propósito

Controlar 2 botones, una tira de LEDs y un reproductor de audio (**DFPlayer Mini**), de forma que cada botón dispare una pista de sonido distinta con su propio color de LED, sin que se interrumpan entre sí.

---

#### 1. Setup (configuración inicial)

- Inicializa el puerto serie (para depuración).
- Configura los pines de los botones como entradas con pull-up.
- Configura el pin `BUSY` del DFPlayer como entrada.
- Inicializa la tira de LEDs (17 LEDs) y la apaga.
- Inicializa el DFPlayer y fija el volumen en 20.

---

#### 2. Loop principal (se repite sin parar)

En cada vuelta del `loop()` ocurren dos cosas:

##### a) `manejarBotones()`

Revisa los dos botones por **flanco de subida** (detecta el momento exacto en que se presionan, no mientras se mantienen presionados), con anti-rebote de 50 ms:

- Si se presiona el **botón 1** *y el sistema está en `IDLE`*:
  - Reproduce la pista 1
  - LED en **rojo**
  - Estado cambia a `REPRODUCIENDO_1`
- Si se presiona el **botón 2** *y el sistema está en `IDLE`*:
  - Reproduce la pista 2
  - LED en **verde**
  - Estado cambia a `REPRODUCIENDO_2`
- Si el sistema **no** está en `IDLE`, ambos botones se ignoran — esto evita que se mezclen o interrumpan los audios.

##### b) `switch(estadoActual)`

Según el estado actual:

| Estado | Acción |
|---|---|
| `IDLE` | No hace nada, sigue esperando un botón |
| `REPRODUCIENDO_1` / `REPRODUCIENDO_2` | Revisa si la pista terminó usando el pin `BUSY` del DFPlayer (`LOW` = reproduciendo, `HIGH` = libre). Si terminó, apaga los LEDs y regresa el estado a `IDLE` |

---

#### Idea central

Es una **máquina de estados de 3 posiciones**:

```
IDLE → REPRODUCIENDO_1 / REPRODUCIENDO_2 → IDLE
```

Esto garantiza que:

- Solo se reproduzca **un audio a la vez**.
- El audio esté siempre **sincronizado** con su color de LED correspondiente.
- El sistema sepa **exactamente cuándo** volver a estar disponible para aceptar un nuevo botón.

##  7. Iteraciones anteriores del tablero y las fichas

![](../images/ENTREGA%20FINAL/anexos/12.%20iteraciones.jpg)

##  8. Referencias de juguetes con temática similar

![](../images/ENTREGA%20FINAL/anexos/13.%20referencias.jpg)
