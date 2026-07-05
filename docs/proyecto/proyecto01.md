## 1. Problema o pregunta de trabajo
- **Problemática abordada:** La desconexión entre las nuevas generaciones y el conocimiento de la biodiversidad amazónica, así como la falta de herramientas educativas interactivas que promuevan conciencia ambiental.  
- **Relevancia:** La Amazonía es uno de los ecosistemas más importantes del planeta, pero enfrenta amenazas como la deforestación y la pérdida de especies. Educar sobre su valor es clave para la sostenibilidad. 
- **Destinatarios:** Estudiantes de primaria y secundaria, docentes de ciencias y público general interesado en educación ambiental.  
- **Contexto:** Proyecto desarrollado en el marco de la Maestría en Fabricación Digital, integrando tecnologías de prototipado y diseño interactivo para crear un juego de mesa educativo.  

---

## 2. Marco conceptual y antecedentes

- **Referencias relevantes:** Educación ambiental, gamificación y aprendizaje experiencial.  
- **Proyectos similares:** Tableros didácticos de biodiversidad, juegos de mesa educativos, experiencias de Fab Labs en conservación ambiental.  
- **Tecnologías vinculadas:** CNC, corte láser, impresión 3D, microcontroladores (Arduino).  
- **Estado del arte:** La tendencia actual combina educación STEM con conciencia ecológica mediante dispositivos interactivos.  
- **Antecedentes metodológicos:**  

  - **🎮 Juegos educativos ambientales**  
    **Referencia:**  
    *Educación ambiental a partir de juegos serios. Una revisión sistemática de literatura.*  
    Pérez Arriaga, J. C., Acosta-Flores, E., Maldonado González, A. L., & Acuña Bustamante, B. L. (2022)  

    - **Metodología:** Revisión sistemática de estudios sobre videojuegos educativos aplicados a la educación ambiental, identificando enfoques de gamificación y su impacto en jóvenes.  
    - **Relevancia:** Respaldar el uso de dinámicas lúdicas en el tablero amazónico.  

  - **🛠️ Fabricación digital aplicada a educación**  
    **Referencia:**  
    *Digital fabrication and making in education.*  
    Blikstein, P. (2013, 2018)  

    - **Metodología:** Integración de FabLabs y tecnologías como impresión 3D y corte láser en entornos educativos, con enfoque en aprendizaje activo y democratización tecnológica.  
    - **Relevancia:** Justifica el uso de CNC, láser y 3D printing en la construcción del tablero amazónico.  

---

## 3. Metodología y proceso
- **Investigación:** Revisión bibliográfica sobre educación ambiental y tecnologías de fabricación digital.  
- **Exploración:** Bocetos iniciales de tableros tipo chacana.  
- **Diseño:** Modelado en AutoCAD, CorelDraw.
- **Iteraciones:** Ajustes en tamaño, materiales y mecánicas de juego.  
- **Prototipado:** Producción de fichas y tablero mediante corte láser y 3D printing.  
- **Validación:** Pruebas con estudiantes y retroalimentación de docentes.  
- **Toma de decisiones:** Selección de materiales resistentes e integración de electrónica básica. Originalmente se tenia previsto integrar un PIR (sensor de movimiento) pero la programación no estuvo lista para la entrega. En próximas versiones se va a explorar su reposición. 

---

## 4. Desarrollo técnico y materialización
- **Prototipo desarrollado:** Tablero tipo chacana con 32 casillas y fichas de animales amazónicos.  
- **Fabricación:**  
  - Procesos aditivos: impresión 3D de fichas.  
  - Procesos sustractivos: corte láser de tablero en MDF/acrílico.  
  - Otros: ensamblaje manual.  
- **Electrónica y programación:** Arduino.  
- **Funcionamiento:**  Aventura Amazónica se juega sobre un tablero tiene 32 casillas distribuidas en cinco niveles ecológicos amazónicos: Rio, Raíces, Tronco Ramas y Canopy,  La mecánica es sencilla: se lanza un dado y, según la casilla, se toma una cartilla. Puede ser un dato de biodiversidad, una prueba, un avance o un retroceso. Al llegar a un nuevo nivel, se activan retos grupales mediante botones integrados en el tablero. El ganador es quien alcanza la cima y se convierte en Guardián de la Amazonía.  
- **Tecnologías utilizadas:** AutoCAD, corte láser, impresión 3D, Arduino IDE.  

### Tabla de materiales y componentes

| Componente       | Proceso       | Material | Herramienta   |
|------------------|--------------|----------|---------------|
| Base  | Corte láser  | MDF 9 mm | Trottec  |
| Tablero plegable | Corte láser  | Liner | Trottec  |
| Fichas animales  | Impresión 3D | PLA      | BambuLab A1      |
| Botones/Parlantes  | Ensamblaje | Electrónica |  Arduino IDE |
| Respaldar iluminado     | Corte láser| Acrílico y LED RBG | Trottec           |
| Audio  | Arduino  | Arduino UNO + DF Player + Parlantes| --- |

---

## 5. Validación y análisis crítico
- **Evaluación de resultados:** El prototipo logró captar la atención de estudiantes y generar interés en la fauna amazónica.  
- **Limitaciones:** Alcance limitado en número de especies representadas; integración electrónica básica.  
- **Errores y dificultades:** Ajustes en tolerancias de corte, calibración de sensores, compatibilidad de software. Pasar a placas con cableado soldado para facilitar la manipulación y transporte.  
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
- **Blikstein, P. (2013, 2018)**  
  *Digital fabrication and making in education.*  

- **Pérez Arriaga, J. C., Acosta-Flores, E., Maldonado González, A. L., & Acuña Bustamante, B. L. (2022)**  
  *Educación ambiental a partir de juegos serios. Una revisión sistemática de literatura.*  
