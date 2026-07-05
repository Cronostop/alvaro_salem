## 1. Problema o pregunta de trabajo
- **Problemática abordada:** La desconexión entre las nuevas generaciones y el conocimiento de la biodiversidad amazónica.  
- **Relevancia:** La Amazonía es uno de los ecosistemas más importantes del planeta, pero enfrenta amenazas como la deforestación y la pérdida de especies.  
- **Destinatarios:** Estudiantes de primaria y secundaria, docentes de ciencias y público general interesado en educación ambiental.  
- **Contexto:** Proyecto desarrollado en el marco de la Maestría en Fabricación Digital, integrando tecnologías de prototipado y diseño interactivo.  


---

## 2. Marco conceptual y antecedentes
- **Referencias relevantes:** Educación ambiental, gamificación y aprendizaje experiencial.  
- **Proyectos similares:** Tableros didácticos de biodiversidad, juegos de mesa educativos, experiencias de Fab Labs.  
- **Tecnologías vinculadas:** CNC, corte láser, impresión 3D, microcontroladores (ESP32/Arduino).  
- **Estado del arte:** Educación STEM combinada con conciencia ecológica mediante dispositivos interactivos.  
- **Antecedentes metodológicos:** Diseño paramétrico, iconografía amazónica (Shipibo-Konibo), biomateriales aplicados.  

### Tabla comparativa de proyectos similares

| Proyecto              | Año | Tecnología        | Enfoque educativo              |
|-----------------------|-----|------------------|--------------------------------|
| Juego de mesa “EcoFauna” | 2018 | Impresión 3D     | Conciencia sobre fauna local   |
| Fab Lab Biodiversidad en Perú | 2020 | CNC + IoT        | Educación STEM ambiental       |
| Aventura Amazónica    | 2026 | Corte láser + IoT| Educación amazónica cultural   |

---

## 3. Metodología y proceso
- **Investigación:** Revisión bibliográfica sobre educación ambiental y tecnologías de fabricación digital.  
- **Exploración:** Bocetos iniciales de tableros tipo chacana.  
- **Diseño:** Modelado en AutoCAD, CorelDraw.
- **Iteraciones:** Ajustes en tamaño, materiales y mecánicas de juego.  
- **Prototipado:** Producción de fichas y tablero mediante corte láser y 3D printing.  
- **Validación:** Pruebas con estudiantes y retroalimentación de docentes.  
- **Toma de decisiones:** Selección de materiales resistentes e integración de electrónica básica.  

---

## 4. Desarrollo técnico y materialización
- **Prototipo desarrollado:** Tablero tipo chacana con 32 casillas y fichas de animales amazónicos.  
- **Fabricación:**  
  - Procesos aditivos: impresión 3D de fichas.  
  - Procesos sustractivos: corte láser de tablero en MDF/acrílico.  
  - Otros: ensamblaje manual.  
- **Electrónica y programación:** Arduino.  
- **Funcionamiento:**  Aventura Amazónica se juega sobre un tablero tiene 32 casillas distribuidas en cinco niveles ecológicos,  La mecánica es sencilla: se lanza un dado y, según la casilla, se toma una cartilla. Puede ser un dato de biodiversidad, una prueba, un avance o un retroceso. Al llegar a un nuevo nivel, se activan retos grupales mediante botones integrados en el tablero. El ganador es quien alcanza la cima y se convierte en Guardián de la Amazonía.  Los jugadores deben cumplir el reto sin moverse durante 20 segundos, y un sensor de movimiento determina si lo lograron o no. Si tienen éxito, continúan; de lo contrario, retroceden una casilla. 
- **Tecnologías utilizadas:** AutoCAD, corte láser, impresión 3D, Arduino IDE.  

### Tabla de materiales y componentes

| Componente       | Proceso       | Material | Herramienta   |
|------------------|--------------|----------|---------------|
| Base  | Corte láser  | MDF 9 mm | Trottec  |
| Tablero plegable | Corte láser  | Liner | Trottec  |
| Fichas animales  | Impresión 3D | PLA      | BambuLab A1      |
| Botones/Parlantes  | Ensamblaje | Electrónica |  Arduino IDE |
| Respaldar inluminado     | Corte láser| Acrílico y LED RBG | Trottec           |
| Audio  | Arduino  | Arduino UNO + DF Player + Parlantes| --- |

---

## 5. Validación y análisis crítico
- **Evaluación de resultados:** El prototipo logró captar la atención de estudiantes y generar interés en la fauna amazónica.  
- **Limitaciones:** Alcance limitado en número de especies representadas; integración electrónica básica.  
- **Errores y dificultades:** Ajustes en tolerancias de corte, calibración de sensores, compatibilidad de software, Pasar a placas con cableado soldado para facilitar la manipulación.  
- **Reflexión:** La combinación de fabricación digital y educación ambiental es potente, pero requiere mayor desarrollo pedagógico.  
- **Aprendizajes:** Importancia de iterar prototipos, validar con usuarios reales y equilibrar estética con funcionalidad.  

---

## 6. Conclusiones y proyección
1. **Aportes del proyecto:** Herramienta educativa innovadora que combina juego, diseño amazónico y tecnología digital.  
2. **Conocimientos compartidos:** Integración de fabricación digital con educación ambiental.  
3. **Aprendizajes surgidos:** Valor de la iteración, necesidad de vincular diseño con pedagogía.  
4. **Aspectos a continuar:** Ampliar especies representadas, mejorar la interfaz digital, integrar realidad aumentada.  
5. **Impacto potencial:** Sensibilización ambiental en estudiantes y comunidades.  
6. **Nuevas preguntas:** ¿Cómo escalar el proyecto a mayor número de usuarios?  
7. **Próximos pasos:** Desarrollo de versión digital interactiva, alianzas con instituciones educativas.  
8. **Innovación:** Fusión de iconografía amazónica con fabricación digital y electrónica educativa.  
9. **Estado actual:** Prototipo funcional con tablero físico y fichas, integración básica de sensores y plataforma IoT.  

---

## 7. Referencias bibliográficas

---

## 8. Anexos
- Planos CAD del tablero.  
- Fotografías del prototipo.  
- Capturas de ARDUINO  
