<!-- 
    CARATULA
-->

<p align="center"> <img src="https://imgur.com/IFP8FSt.png" alt="UPC Logo" width="100"> </p><div align="center"> 

<strong><h4>Universidad Peruana de Ciencias Aplicadas</h4></strong> </div>
<div align="center"> <strong>Ingeniería de Software</strong> </div>
<br>
<div align="center"> <strong>SEXTO CICLO</strong> </div>

<div align="center"> Aplicaciones Para Dispositivos Móviles – CC238 </div><div align="center"> 12614 </div>

<br>
<div align="center"> <strong>Docente:</strong> Quevedo Velasco, David Gerardo </div>
<br>

<div align="center"> <strong>INFORME TB1</strong> </div>
<br>
<div align="center"> <strong>ThinkUp</strong> </div><div align="center"> <strong>SkillShare</strong> </div>

<br>
<div align="center"> Argomedo Camacho, Jhosep Jamil (U20231D978) </div>
<div align="center"> García Salamanca, Andrés Felipe (U202523463) </div>
<div align="center"> González Custodio, Carlos Alberto (U202020230) </div>
<div align="center"> Julca Cruz, Renso Anthony (U202121579) </div>
<div align="center"> Ramírez Tello, Sebastian (U202316122) </div>

<br>
<br>
<div align="center"> <strong>Septiembre, 2025</strong> </div>

<br>
<br>
<br>
<br>
<br>
<br>

<!-- 
    REGISTRO DE VERSIONES DEL INFORME 
-->

# Registro de versiones del Informe

| **Versión** | **Fecha**   | **Autor**  | **Descripción de modificación**    |
|-------------|-------------|---------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| TB1         | 1809/25     | Argomedo, Jhosep; <br> García, Andrés; <br> González, Carlos; <br> Julca, Renso; <br> Ramírez, Sebastian. | Adición de secciones: <br> **Capítulo I:** Presentación <br> **Capítulo II:** Requirements Development and Software Solution Design |

<br>
<br>
<br>
<br>
<br>
<br>

<!-- 
    PROJECT REPORT COLLABORATION INSIGTHS
-->

# Project Report Collaboration Insights

## Repositorio de Informe del Proyecto:
El informe del proyecto se ha desarrollado de manera colaborativa en el repositorio de GitHub. Cada miembro del equipo fue responsable de diferentes secciones del informe, y se utilizó el control de versiones para realizar commits y revisiones de manera constante.

- ***Distribución de Tareas:***
El equipo dividió el informe en secciones específicas, asignando responsabilidades a cada miembro. Las tareas se distribuyeron según las fortalezas de cada uno.

- ***Colaboración Continua:***
Cada miembro realizó commits y revisiones mediante pull requests, asegurando la integración de las aportaciones de todos. La redacción se revisó y mejoró iterativamente a lo largo del proyecto.

- ***Finalización del Informe:***
Una vez completadas todas las secciones, el informe se revisó en conjunto antes de realizar el commit final con la versión de entrega.

## Evidencias de la Colaboración
A continuación, se muestran evidencias gráficas que ilustran la participación de cada miembro:

### Captura de Commits:
![Commits grupales](assets/images/prci/)


<br>
<br>
<br>
<br>
<br>
<br>
<!-- 
    CONTENIDO
-->

# Contenido

- [Registro de versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)

## [Capítulo 1: Presentación](#capítulo-i-presentación)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2. Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

## [Capítulo 2: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. Ubiquitous Language](#235-ubiquitous-language)

## [Capítulo 3: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. User Stories](#31-user-stories)
- [3.2. Technical Stories](#32-technical-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

## [Capítulo 4: Solution Software Design](#capítulo-iv-solution-software-design)
- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
  - [4.1.1. EventStorming](#411-eventstorming)
    - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
    - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
    - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
  - [4.1.2. Context Mapping](#412-context-mapping)
  - [4.1.3. Software Architecture](#413-software-architecture)
    - [4.1.3.1. Software Architecture Context Level Diagrams](#4131-software-architecture-context-level-diagrams)
    - [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
    - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)

- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
   - [4.2.1. Bounded Context:](#421-bounded-context)
      - [4.2.1.1. Domain Layer](#4211-domain-layer)
      - [4.2.1.2.Interface Layer](#4212-interface-layer)
      - [4.2.1.3. Application Layer](#4213-application-layer)
      - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
      - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
         - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
         - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)

---

- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<br>
<br>
<br>
<br>
<br>
<br>
<!-- 
    STUDENT OUTCOME
-->

# Student Outcome

**ABET – EAC - Student Outcome 7**  
*Criterio: La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.*

<br>

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
|:------------------------|:------------------------|:-----------------|
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.** | - **Argomedo Camacho, Jhosep Jamil (TB1):** <br> • Investigué y apliqué metodologías Lean UX Canvas.<br> • Desarrollé análisis competitivo con matrices de comparación.<br> • Creé user personas completas con journey maps y empathy mapping.<br><br>- **Ramirez Tello, Sebastian (TB1):** <br> • Apliqué técnicas de design thinking para discovery.<br> • Desarrollé entrevistas cualitativas y análisis de resultados.<br> • Implementé specification requirements con user stories.<br><br>- **Julca Cruz, Renso Anthony (TB1):** <br> • Realicé dos entrevistas: una a una estudiante universitaria y otra a una persona autodidacta, recopilando experiencias sobre métodos de aprendizaje, retos y estrategias.<br> • Apliqué actividades de Strategic-Level Domain-Driven Design (DDD): EventStorming, Candidate Context Discovery, Domain Message Flows Modeling, Bounded Context Canvases. <br><br>- **Gonzalez Custodio, Carlos Alberto (TB1)** <br> • Realice 2 entrevistas para el segmento Docente, para poder conocer más las necesidades de los usuarios. <br> • Presente los diagramas C4 que permite comprender de manera más clara como se organiza la solución.  Dichos diagramas son: Context Level Diagram, Container Level Diagram y Deployment Diagra| - **Argomedo Camacho, Jhosep Jamil (TB1):** Actualicé mis conocimientos en metodologías ágiles y de diseño, aplicando con éxito Lean UX y DDD al proyecto. Mi investigación en análisis competitivo permitió identificar ventajas diferenciales para la solución.<br><br>- **Ramirez Tello, Sebastian (TB1):** Actualicé mis conocimientos en técnicas de discovery y engineering de requisitos, aplicando metodologías de design thinking y especificación ágil para el proyecto.<br><br>- **Julca Cruz, Renso Anthony (TB1):** La aplicación de los conocimientos adquiridos en el curso, junto con la información de entrevistas, permitió actualizar y reforzar habilidades en el diseño de soluciones de software basadas en DDD. Esto evidencia la capacidad del grupo para adquirir nuevos conocimientos y adaptarlos al contexto del proyecto. <br><br>- **Gonzalez Custodio, Carlos Alberto (TB1):** Logré adquirir nuevas habilidades y conocimientos al comprender como elaborar Diagramas C4 ademas de poder entender las necesidades del usuario mediantes las entrevistas realizadas. |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.** | - **Argomedo Camacho, Jhosep Jamil (TB1):** <br> • Aprendí técnicas avanzadas de needfinding.<br> • Investigué arquitecturas software escalables.<br> • Apliqué strategic modeling techniques.<br> • Desarrollé habilidades en competitive analysis.<br><br>- **Ramirez Tello, Sebastian (TB1):** <br> • Investigué best practices para startup profiling.<br> • Aprendí técnicas de problem framing y solution positioning.<br> • Desarrollé habilidades en qualitative research. <br><br>- **Julca Cruz, Renso Anthony (TB1):** <br> • Durante el desarrollo de las actividades de EventStorming y modelado de flujos de mensajes de dominio, se identificó la importancia de comprender de manera continua los cambios en los requerimientos del negocio y en las prácticas modernas de desarrollo de software. <br> • En las entrevistas se resaltó la relevancia de la autoformación y la actualización constante como factores clave para el crecimiento profesional. <br><br>- **González Custodio, Carlos Alberto (TB1):** <br> • Aprendí Software Architecture y creacion de modelos C4 para un mayor comprensión y entendimiento de como esta organizado todo siguiendo las buenas practicas. | - **Argomedo Camacho, Jhosep Jamil (TB1):** Demostré comprensión de que el aprendizaje continuo es esencial, investigando constantemente nuevas metodologías para mejorar la calidad del proyecto y su desarrollo profesional.<br><br>- **Ramirez Tello, Sebastian (TB1):** Mostré reconocimiento de la necesidad de aprendizaje continuo, investigando constantemente nuevos approaches para validación de negocio y desarrollo de soluciones software efectivas. <br><br> - **Julca Cruz, Renso Anthony (TB1):** El grupo reconoce que el aprendizaje no concluye con el curso, sino que debe mantenerse activo en la investigación y práctica de nuevas metodologías de diseño y arquitectura. Esto refuerza la visión de aprendizaje permanente como parte esencial del desempeño profesional en ingeniería de software. <br><br>- **González Custodio, Carlos Alberto (TB1):** Logré adquirir nuevos conocimientos y experiencia que me servirán para futuros trabajos y además para la conclusión del presente proyecto. |

<br>
<br>
<br>
<br>
<br>
<br>
<!-- 
    CAPÍTULO 1 - PRESENTACIÓN
-->

# Capítulo I: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Somos **ThinkUp**, una startup fundada por estudiantes apasionados por la innovación educativa y la tecnología, comprometidos en transformar la manera en que los jóvenes aprenden y colaboran.  

Creemos que el conocimiento crece cuando se comparte, y por ello hemos desarrollado **SkillShare**, una aplicación de red social enfocada en conectar estudiantes con intereses académicos similares para formar grupos de estudio dinámicos y efectivos.  

**SkillShare** permite a los estudiantes:  
- Crear y unirse a grupos según materias o temas específicos.  
- Acceder a chats y videollamadas integradas.  
- Compartir recursos como apuntes, notas, quizzes y materiales de estudio.  

Con esta herramienta buscamos reducir el aislamiento académico, facilitar la preparación para exámenes y promover un aprendizaje colaborativo más enriquecedor.  

---

### Misión, Visión y Valores

| **Elemento** | **Descripción** |
|--------------|-----------------|
| **Misión**   | Impulsar el aprendizaje colaborativo mediante la tecnología, brindando a los estudiantes una plataforma que conecte personas con los mismos objetivos académicos, fomente la cooperación y facilite el acceso a recursos de estudio compartidos para mejorar el rendimiento académico. |
| **Visión**   | Convertirnos en la **red social educativa líder en Latinoamérica y el mundo**, donde millones de estudiantes encuentren en SkillShare un espacio seguro, dinámico y confiable para aprender juntos, potenciar sus capacidades y construir comunidades académicas sólidas que trasciendan las aulas. |
| **Valores**  | - **Colaboración**: Creemos que el conocimiento se multiplica cuando se comparte y trabajamos para fortalecer la cooperación entre estudiantes.<br>- **Innovación**: Apostamos por el uso de la tecnología para transformar la manera en que las personas aprenden y se relacionan académicamente.<br>- **Accesibilidad**: Buscamos que todos los estudiantes, sin importar su lugar de origen o nivel socioeconómico, puedan acceder a herramientas de calidad para mejorar su aprendizaje.<br>- **Compromiso con la educación**: Nos motiva la mejora continua del proceso educativo, impulsando el desarrollo personal y colectivo. |

### 1.1.2. Perfiles de integrantes del equipo  

| **Integrante** | **Perfil** | **Foto** |
|----------------|------------|----------|
| **Jhosep J. Argomedo Camacho** <br><br> **Código:** U20231D978 <br><br> **Carrera:** Ingeniería de Software <br><br> **Rol:** Líder | Soy estudiante de Ingeniería de Software en la UPC (6to ciclo) con experiencia básica en desarrollo de aplicaciones móviles utilizando Flutter. Manejo herramientas como Git, GitHub y Figma, así como lenguajes de programación como HTML, CSS, Python, JavaScript, y bases de datos SQL y NoSQL. Con conocimientos en SCRUM y en la creación de User Stories, me destaco por mi liderazgo, responsabilidad y habilidad para coordinar equipos, enfocándome en el logro de objetivos comunes. | <img src="assets/images/team/jhosep_argomedo.jpg" width="1500"> |
| **Andrés Felipe García Salamanca** <br><br> **Código:** U202523463 <br><br> **Carrera:** Ingeniería de Software <br><br> **Rol:** Miembro | Soy estudiante de Ingeniería de Sistemas en la CUN (Colombia) y actualmente curso el 4to ciclo como parte de un programa de intercambio en la UPC. Mi formación se orienta al área de infraestructura tecnológica, con bases en redes y en la gestión de entornos digitales aplicados a la educación. Me interesa comprender cómo la tecnología puede mejorar los procesos de aprendizaje y fortalecer el trabajo colaborativo entre estudiantes. A través de este intercambio busco ampliar mi perspectiva académica, participar en proyectos que integren innovación y educación, y continuar desarrollando mis competencias profesionales en el ámbito de la ingeniería. | ![Foto Andrés](assets/images/team/andres_garcia.jpg) |
| **Renso Anthony Julca Cruz** <br><br> **Código:** U202121579 <br><br> **Carrera:** Ingeniería de Software <br><br> **Rol:** Miembro | Estudiante de Ingeniería de Software, actualmente curso el 6to ciclo de esta carrera. Me apasiona programar y ser autodidacta para poder mejorar mis habilidades en el desarrollo de software, quisiera dedicarme a la parte de gestión bancaria. | ![Foto Renso](assets/images/team/renso_julca.jpg) |
| **Carlos Alberto González Custodio** <br><br> **Código:** U202020230 <br><br> **Carrera:** Ingeniería de Software <br><br> **Rol:** Miembro | Soy estudiante de Ingeniería de Software, me encuentro actualmente cursando el 6to ciclo. Me encanta enriquecer mis conocimientos con nuevos desafíos y tengo un gran interés por el desarrollo web. | ![Foto Carlos](assets/images/team/carlos_gonzales.jpg) |
| **Sebastian Ramirez Tello** <br><br> **Código:** U202316122 <br><br> **Carrera:** Ingeniería de Software <br><br> **Rol:** Miembro | Soy estudiante de 6to ciclo de la carrera de Ingeniería de Software. Me gusta mucho emplear soluciones creativas y que busquen eficiencia para poder abordar de esta forma cualquier desafío de la mejor manera.| ![Foto Sebastian](assets/images/team/sebastian_ramirez.png) |

<br>
<br>

# 1.2. Solution Profile  

En esta sección, se presenta en detalle el perfil de la solución, respaldado por un sólido fundamento de antecedentes y desarrollado de manera metódica, siguiendo el proceso de Lean UX.  

---

## 1.2.1. Antecedentes y problemática  

El estudio colaborativo ha demostrado ser una estrategia pedagógica altamente eficaz para mejorar el rendimiento académico y la experiencia estudiantil. Según un metaanálisis de 39 estudios, los estudiantes que participan en grupos de estudio obtienen calificaciones significativamente mejores y desarrollan una comprensión más profunda del material en comparación con quienes estudian de forma individual (Johnson et al., 2022).  

Por ejemplo, una investigación realizada en la UCLA encontró que estudiantes que formaban parte de grupos de estudio tenían un 10% más de probabilidades de obtener una A o B en sus cursos (Smith & Lee, 2021). Asimismo, entornos de aprendizaje activo que incluyen actividades grupales han demostrado reducir las tasas de desaprobación en áreas STEM y elevar las calificaciones en aproximadamente seis puntos porcentuales (Martínez & Gómez, 2023).  

En el ámbito de la educación colaborativa, se ha observado que los estudiantes en equipos pequeños, ideales de tres a cuatro miembros, superan significativamente en rendimiento académico a quienes estudian solos. Además, estos entornos fomentan una mayor retención de información a través de discusiones, desarrollo de pensamiento crítico, motivación, asistencia y disfrute del aprendizaje (Kim et al., 2020).  

El mecanismo del *peer teaching*, donde un estudiante explica un concepto a sus pares, genera una retención y entendimiento más sólidos del contenido. Este fenómeno, conocido como *efecto del protegido* (*protégé effect*), ha sido cuantificado como un factor clave para reforzar la propia comprensión mediante la enseñanza (Fiorella & Mayer, 2019).  

Más allá del rendimiento académico, los grupos de estudio contribuyen a una experiencia educativa más satisfactoria y a una mayor permanencia estudiantil. Estudiantes involucrados en actividades extracurriculares, como sociedades estudiantiles o deportes, tienen hasta cinco veces más probabilidades de continuar sus estudios que aquellos que no participan (Johnson & Barker, 2024).  

Un sentido de pertenencia, que se fortalece en dinámicas colaborativas, se ha vinculado a una mayor motivación, mejor ajuste académico y emocional, y menores tasas de deserción (Thompson et al., 2021).  

No obstante, se identifican retos en la práctica del estudio colaborativo. Investigaciones recientes muestran que, aunque entre el 41% y el 78% de los estudiantes participan al menos alguna vez en grupos de estudio, un 55% nunca lo ha hecho, y alrededor del 22% abandona el grupo durante el semestre. Las dificultades para coordinar horarios, las distracciones, la participación desigual y las estructuras grupales poco efectivas son las principales razones detrás de estas problemáticas (García & Martínez, 2022).  

En contextos de enseñanza remota o híbrida, el componente tecnológico ha generado nuevas dinámicas. Algunos estudios indican que estudiantes que colaboran mediante foros o redes de apoyo académico, especialmente aquellos con rendimiento previo bajo, mejoran significativamente su GPA final (Brown et al., 2023).  

Sin embargo, en secundaria, el efecto positivo de la colaboración sólo se manifiesta después de un tiempo prolongado, principalmente cuando se establecen vínculos de confianza entre los estudiantes (Nguyen & Carroll, 2021).  

Finalmente, el rol que cada estudiante ocupa dentro de su red social académica influye en su rendimiento: quienes están en posiciones centrales, conectados con muchos pares, tienden a presentar mejor desempeño, mientras que los estudiantes aislados tienen peores resultados (López & Kim, 2024).  

---

## The 5W’s  

### 1. What? (¿Qué?)  
**¿Cuál es el problema?**  
Muchos estudiantes enfrentan dificultades para organizarse y encontrar compañeros de estudio con intereses y necesidades académicas similares. Esto genera preparación individual poco efectiva, desmotivación y, en algunos casos, mayor riesgo de bajo rendimiento académico o abandono. La falta de espacios digitales estructurados para formar grupos de estudio limita el potencial del aprendizaje colaborativo. 

**¿Cuál es la relación con la persona en cuestión?**  
Los estudiantes dependen de una preparación adecuada para aprobar sus cursos y mejorar su rendimiento académico. La aplicación SkillShare les ofrece un espacio accesible y seguro para crear grupos de estudio, conectarse con pares que comparten las mismas materias o intereses, y colaborar mediante chats, videollamadas y recursos compartidos. 

---

### 2. When? (¿Cuándo?)  
**¿Cuándo sucede el problema?**  
El problema ocurre durante el ciclo académico, especialmente en periodos de evaluaciones parciales y finales, cuando los estudiantes necesitan reforzar sus conocimientos y se ven limitados por la falta de espacios adecuados para estudiar en grupo. También se presenta al inicio de un curso, cuando los estudiantes aún no han formado redes de apoyo académico y se sienten aislados en su preparación. 

**¿Cuándo utiliza el cliente el producto?**  
Los estudiantes utilizan SkillShare en momentos clave del ciclo de aprendizaje:  
- Al organizar sesiones de estudio previas a exámenes.  
- Al buscar apoyo para entender un tema complejo.  
- Al compartir apuntes y recursos después de clases.  

Además, pueden recurrir a la aplicación como complemento a su rutina académica diaria y semanal.  

---

### 3. Where? (¿Dónde?)  
**¿Dónde está el cliente cuando usa el producto?**  
El cliente (estudiante) utiliza la aplicación desde su hogar, la universidad, bibliotecas, cafeterías o cualquier espacio donde estudie, ya que SkillShare es una aplicación accesible desde dispositivos móviles. 

**¿A dónde se dirige?**  
El estudiante se dirige hacia un entorno de estudio más organizado y colaborativo, donde puede conectarse con compañeros, compartir recursos y mejorar su preparación académica. 

**¿Dónde surge el problema?**  
El problema surge en contextos educativos donde los estudiantes carecen de redes de apoyo efectivas:  
- Aulas con grupos numerosos.  
- Ambientes de estudio poco flexibles.  
- Modalidades virtuales con poca interacción entre pares.  

---

### 4. Who? (¿Quién?)  
**¿Quiénes están involucrados?**  
Los principales involucrados son los estudiantes de educación superior, pero también participan docentes que promueven el aprendizaje colaborativo, instituciones educativas interesadas en mejorar el rendimiento de sus alumnos y desarrolladores de tecnología que diseñan la plataforma. 

**¿A quiénes les sucede el problema?**  
El problema afecta principalmente a estudiantes universitarios y escolares de niveles avanzados que necesitan reforzar sus conocimientos, pero que carecen de espacios o herramientas adecuadas para conectar con compañeros de estudio. 

**¿Quién lo utilizará?**  
La aplicación será utilizada por estudiantes de diferentes niveles y carreras que buscan formar grupos de estudio, compartir materiales y organizar sesiones colaborativas. A futuro, también puede ser usada por instituciones educativas como complemento a sus programas académicos. 

---

### 5. Why? (¿Por qué?)  
**¿Cuál es la causa del problema?**  
La causa principal radica en la falta de herramientas accesibles y estructuradas para organizar el estudio en grupo. Muchos estudiantes dependen de métodos informales (como chats dispersos en WhatsApp o reuniones improvisadas) que dificultan la coordinación, la constancia y el aprovechamiento del aprendizaje colaborativo. A ello se suma la falta de tiempo, diferencias en horarios y la ausencia de plataformas que integren comunicación, recursos y organización académica en un solo espacio. 

---

## The 2H’s  

### 1. How? (¿Cómo?)  
**¿En qué condiciones los clientes usan nuestro producto?**  
Los estudiantes utilizan SkillShare en contextos académicos que requieren organización y colaboración, como preparación para exámenes, desarrollo de proyectos grupales o repaso de contenidos complejos. Lo hacen desde sus dispositivos móviles, en casa, en la universidad, en la biblioteca o incluso de forma remota en entornos híbridos. 

**¿Cómo nos conocieron los compradores?**  
Los estudiantes conocen SkillShare principalmente a través de campañas en redes sociales, recomendaciones boca a boca entre compañeros, alianzas con instituciones educativas y presencia en ferias o eventos universitarios relacionados con tecnología y educación. 

**¿Cómo prefieren acceder al contenido?**  
Prefieren acceder al contenido de manera rápida y sencilla desde la aplicación móvil, con notificaciones en tiempo real sobre actividades del grupo, acceso directo a materiales compartidos y recordatorios de sesiones de estudio programadas. También valoran la disponibilidad multiplataforma para poder continuar su aprendizaje desde cualquier dispositivo. 

**¿Qué los llevó a esta situación?**  
La necesidad de optimizar el tiempo de estudio, mejorar su rendimiento académico y superar la dificultad de coordinar con sus pares a través de medios dispersos (grupos de WhatsApp, correos electrónicos, redes sociales no académicas) llevó a los estudiantes a buscar una herramienta centralizada y eficiente que fomente el aprendizaje colaborativo. 

### 2. How much? (¿Cuánto?)  
**¿Cuánto afecta este problema a los usuarios?**  

El aprendizaje activo —que incluye el trabajo en pequeños grupos— mejora significativamente los resultados académicos: los estudiantes tienen un 6 % más de puntaje en exámenes y son 1,5 veces menos propensos a reprobar en cursos de Ciencias, Tecnología, Ingeniería y Matemática (STEM) comparados con métodos tradicionales. 

Un meta-análisis mostró que el aprendizaje en pequeños grupos reduce la tasa de fracaso del 32 % al 21 %, y aumenta el rendimiento en evaluaciones en 0,47 desviaciones estándar, un efecto estadísticamente robusto. 

Otra revisión comprobó que el aprendizaje colaborativo (peer-led team learning, PLTL) conduce a un incremento promedio del 15 % más estudiantes que logran notas de ABC, en comparación con clases tradicionales. 

<br>
<div align="center">

![Comparison of failure rates and exam score improvements between traditional lecturing and active learning in STEM education](assets\images\C2\stem-learning_method_comparison.jpg)

*Comparison of failure rates and exam score improvements between traditional lecturing and active learning in STEM education*

</div>


**¿Cuánto cuesta realizar el proyecto?**  
El costo de desarrollar una plataforma como SkillShare, que incluye funciones como chat, videollamadas, grupos y recursos compartidos, varía según la complejidad y las funcionalidades requeridas. Según fuentes como Crowdbotics, el costo para un MVP (producto mínimo viable) puede oscilar entre USD 25,000 y USD 50,000, siendo USD 37,500 el promedio. Otros estiman que el rango va de USD 30,000 a USD 250,000, dependiendo de la sofisticación de las características, como videollamadas o feeds personalizados. Un enfoque progresivo sugiere iniciar con un MVP entre USD 20,000 y USD 30,000, para luego escalar hacia versiones más avanzadas que pueden superar los USD 120,000 o USD 150,000. Estudios adicionales indican que una versión básica podría costar entre USD 20,000 y USD 50,000, mientras que una aplicación más robusta podría superar los USD 100,000. 

<br>
<br>

# 1.2.2. Lean UX Process  

## 1.2.2.1. Lean UX Problem Statements  

### Declaración del problema  
Muchos estudiantes enfrentan dificultades para organizar grupos de estudio efectivos, lo que limita sus oportunidades de aprendizaje colaborativo y afecta su rendimiento académico. Aunque existen herramientas digitales para la comunicación, estas no están diseñadas específicamente para coordinar y gestionar espacios de estudio, lo que genera falta de constancia, dispersión de recursos y menor motivación en los estudiantes. 

### Estado actual del mercado  
En el contexto educativo actual, el aprendizaje colaborativo se reconoce como una estrategia clave para mejorar los resultados académicos y reducir la deserción estudiantil. Sin embargo, la mayoría de los estudiantes en educación superior y secundaria avanzada dependen de plataformas generalistas (como WhatsApp, Facebook o Discord) que no fueron creadas para la gestión estructurada de grupos de estudio. Esto genera problemas de coordinación, pérdida de materiales y baja eficiencia en el aprovechamiento de estas dinámicas. 

### Oportunidad a aprovechar  
Existe la oportunidad de crear un entorno digital diseñado específicamente para organizar, coordinar y facilitar grupos de estudio. Al centrarse en las necesidades reales de los estudiantes —comunicación académica, organización de sesiones y recursos compartidos— se puede mejorar significativamente su preparación y experiencia educativa. 

### Restricciones  
El proyecto debe considerar limitaciones como la conectividad desigual entre estudiantes, la necesidad de ofrecer una interfaz simple y amigable para usuarios con diferentes niveles de familiaridad tecnológica, y la importancia de mantener el acceso gratuito a funcionalidades esenciales.

### Pregunta  
**¿Cómo puede SkillShare proporcionar un entorno digital accesible, intuitivo y centrado en los estudiantes que facilite la organización de grupos de estudio y potencie el aprendizaje colaborativo?**  

---

## 1.2.2.2. Lean UX Assumptions  

### a. User Profile and Product Context  

1. **¿Quién es el usuario?**  
   El usuario principal son estudiantes de educación superior (universitarios e institutos), en menor medida, estudiantes de secundaria avanzada que buscan reforzar sus conocimientos. También incluyen a jóvenes profesionales que desean aprender colaborativamente para certificaciones o capacitaciones, así como autodidactas que buscan expandir sus conocimientos de manera independiente y flexible. 

2. **¿Dónde encaja nuestro producto en su vida?**  
   SkillShare encaja en la rutina académica del estudiante como una herramienta central para coordinar sus estudios grupales, acceder a recursos compartidos y mantenerse conectado con compañeros que cursan las mismas materias. Forma parte de su vida diaria al integrarse en los momentos de preparación para clases, exámenes y proyectos académicos. 

3. **¿Qué problemas resuelve nuestro producto?**  
   - Dificultad para encontrar compañeros de estudio con intereses o cursos en común. 
   - Falta de coordinación en horarios y constancia de las sesiones de estudio. 
   - Dispersión de materiales académicos en múltiples plataformas (WhatsApp, Google Drive, Discord, etc.). 
   - Falta de motivación y acompañamiento durante el ciclo académico. 

4. **¿Cuándo y cómo es usado?**  
   - Antes de exámenes.  
   - Durante el ciclo académico (repaso semanal).  
   - En proyectos grupales.  
   - Acceso desde dispositivos móviles con chat, videollamadas, notificaciones y recursos.  

5. **¿Qué características son importantes?**  
   - Creación/gestión de grupos por materia o tema.  
   - Chat en tiempo real y videollamadas.  
   - Espacio para compartir apuntes y documentos.  
   - Notificaciones de sesiones programadas.  
   - Búsqueda de compañeros de estudio.  
   - Experiencia multiplataforma.  

6. **¿Cómo debe verse y comportarse el producto?**  
   - **Visualmente:** interfaz limpia, moderna, intuitiva, con un estilo académico-profesional pero amigable, similar a una red social adaptada al contexto de estudio.
   - **Comportamiento:** debe ser fluido, confiable, rápido en la comunicación y con herramientas fáciles de usar. Debe fomentar la interacción positiva y mantener un entorno seguro para los estudiantes. 

---

### b. Business Plan and Market Strategy  

1. **Necesidad de clientes:** una plataforma centralizada para coordinar grupos de estudio.  
2. **Solución:** app móvil con chat, gestión de horarios, recursos compartidos y colaboración académica.  
3. **Clientes iniciales:** estudiantes de educación superior en Perú y Latinoamérica.  
4. **Valor #1 esperado:** optimizar tiempo y evitar dispersión entre múltiples apps.  
5. **Beneficios adicionales:**  
   - Acceso a comunidades de aprendizaje.  
   - Recursos y guías de estudio organizadas.  
   - Notificaciones y recordatorios.  
   - Recomendaciones de grupos/cursos afines.  
6. **Adquisición de clientes:**  
   - Redes sociales (Instagram, TikTok, Facebook).  
   - Convenios con universidades.  
   - Marketing de boca a boca.  
7. **Monetización:**  
   - Modelo freemium (básico gratis, premium avanzado).  
   - Publicidad segmentada (cursos, libros, academias).  
8. **Competencia:** Discord, Google Classroom, StudyBuddy, Quizlet.  
9. **Ventaja competitiva:** enfoque exclusivo en estudio en grupo, simplicidad, accesibilidad en costo.  
10. **Riesgo:** estudiantes prefieren usar apps consolidadas (WhatsApp, Discord).  
11. **Cómo mitigarlo:**  
    - Diferenciación clara en funciones educativas.  
    - Beneficios inmediatos (pruebas premium, recomendaciones automáticas).  
    - Onboarding simple y atractivo.  
12. **Suposiciones críticas:**  
    - Estudiantes están dispuestos a usar una nueva plataforma.  
    - Modelo freemium será sostenible.  
    - Los estudiantes valoran organización sobre comodidad de apps conocidas.  

---

## 1.2.2.3. Lean UX Hypothesis Statements  

1. Creemos que los usuarios valoran la posibilidad de unirse y colaborar en grupos de estudio temáticos. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado:

   - **Cualitativo:** usuarios expresan que la función de grupos les facilita organizar su aprendizaje y encontrar compañeros con intereses similares.

   - **Cuantitativo:** al menos el 70% de los usuarios registrados se unan a un grupo dentro de su primera semana.

   - **Indicador clave:** aumento en el número de publicaciones y materiales compartidos en grupos activos.

<br>

2. Creemos que una interfaz intuitiva y fácil de usar mejorará la adopción de la aplicación por estudiantes de diferentes edades y niveles tecnológicos. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado:

   - **Cualitativo:** usuarios reportan que la app es clara y no requiere tutorial extenso.

   - **Cuantitativo:** reducción del 30% en el abandono durante el registro o primer uso.

   - **Indicador clave:** aumento en la tasa de retención de usuarios después de las primeras 2 semanas.

<br>

3. Creemos que ofrecer un espacio centralizado para compartir materiales de estudio (PDF, apuntes, links, videos) incrementará la utilidad de la aplicación. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado:

   - **Cualitativo:** los usuarios destacan la biblioteca como una de las funciones más útiles.

   - **Cuantitativo:** al menos el 60% de los grupos creen o suban un recurso en su primer mes.

   - **Indicador clave:** incremento en descargas y consultas de materiales compartidos.

<br>

4. Creemos que ofrecer un espacio centralizado para compartir materiales de estudio (PDF, apuntes, links, videos) incrementará la utilidad de la aplicación. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado:

   - **Cualitativo:** los usuarios destacan la biblioteca como una de las funciones más útiles.

   - **Cuantitativo:** al menos el 60% de los grupos creen o suban un recurso en su primer mes.

   - **Indicador clave:** incremento en descargas y consultas de materiales compartidos.

<br>

5. Creemos que habilitar un chat en tiempo real fortalecerá la interacción y el sentido de comunidad entre los estudiantes. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado:

   - **Cualitativo:** los usuarios mencionan que el chat les ayuda a resolver dudas más rápido y mantenerse conectados.

   - **Cuantitativo:** al menos el 50% de los usuarios activos envíen un mensaje dentro de sus primeros 3 días.

   - **Indicador clave:** incremento en la frecuencia de uso diario de la app.

<br>

6. Creemos que incorporar notificaciones inteligentes (recordatorios de actividades, avisos de nuevos recursos, menciones en grupos) aumentará la participación continua.
Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado:

   - **Cualitativo:** los usuarios mencionan que las notificaciones les ayudan a no perder información importante.

   - **Cuantitativo:** incremento del 40% en el retorno de usuarios semanales después de activar notificaciones.

   - **Indicador clave:** disminución de la tasa de inactividad (churn) en el primer mes.

<br>
<br>

## 1.2.2.4. Lean UX Canvas  

**Enlace:** [Clic aquí](https://www.canva.com/design/DAGxLsVu32E/-PnYg-pOm_MuW6ghYslDvw/edit?utm_content=DAGxLsVu32E&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)  

![Lean UX Canvas](assets/images/C2/lean_ux-canvas.jpg)


<br>
<br>

# 1.3. Segmentos objetivo

En esta sección se describen los segmentos clave a considerar en nuestra propuesta de solución para la problemática planteada.

---

### **Segmento 1: Estudiantes de educación superior (universidad o institutos)**

Este segmento incluye a estudiantes matriculados en programas de pregrado o técnicos que buscan herramientas de apoyo para estudiar de manera colaborativa, organizar grupos y mejorar su rendimiento académico.

| **Aspecto** | **Detalle** |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Rango de edad** | 17 – 28 años |
| **Geografía**     | Zonas urbanas y periurbanas de Perú y Latinoamérica |
| **Estadísticas**  | - 1.3 millones de universitarios y 740 mil en institutos superiores (SUNEDU & MINEDU, 2023). <br> - 63% de universitarios trabaja y estudia al mismo tiempo (INEI, 2022). <br> - 45% de estudiantes LATAM tienen dificultades para organizarse en grupo (UNESCO). |
| **Problema**      | Dificultad para coordinar y mantener grupos de estudio, debido al uso disperso de plataformas no académicas (WhatsApp, Drive, etc.).                                                                                                                              |

---

### **Segmento 2: Estudiantes de secundaria (o preparatoria)**

Incluye a adolescentes que buscan reforzar materias, prepararse para exámenes de admisión universitaria o recibir apoyo escolar mediante grupos organizados.

| **Aspecto** | **Detalle** |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Rango de edad** | 14 – 18 años |
| **Geografía** | Zonas urbanas y semiurbanas, con conectividad básica |
| **Estadísticas**  | - 2.4 millones de estudiantes de secundaria en Perú (MINEDU, 2023). <br> - 68% usa el celular como principal herramienta escolar (INEI, 2022). <br> - 55% de estudiantes peruanos tienen problemas para organizar grupos fuera del aula (PISA, 2022). |
| **Problema**      | No cuentan con un entorno digital especializado para organizarse en grupos, lo que afecta preparación escolar y admisión universitaria.                                                                                                               |

---

### **Segmento 3: Estudiantes autodidactas**

Personas que aprenden de forma independiente a través de cursos online, recursos digitales y comunidades educativas.

| **Aspecto** | **Detalle** |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Rango de edad** | 17 – 35 años  |
| **Geografía**     | Principalmente zonas urbanas con internet estable |
| **Estadísticas**  | - 38% de jóvenes peruanos (18–29) ha llevado un curso online no formal (INEI, 2022). <br> - 58% de usuarios de e-learning en LATAM son autodidactas (Statista, 2023). <br> - Más de 750 mil usuarios peruanos en Coursera (2022). |
| **Problema**      | Suelen carecer de comunidad y refuerzo social, lo que genera desmotivación y abandono en cursos online.                                                                                                                           |

---

### **Segmento 4: Docentes**

Profesores de colegios, institutos y universidades que buscan dinamizar el aprendizaje y organizar a los estudiantes en grupos de estudio con seguimiento académico.

| **Aspecto** | **Detalle** |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Rango de edad** | 25 – 55 años |
| **Geografía** | Zonas urbanas y semiurbanas con conectividad estable  |
| **Estadísticas**  | - 67% de docentes LATAM considera vitales las plataformas digitales para aprendizaje colaborativo (UNESCO, 2022). <br> - 54% de docentes reporta dificultades para motivar a estudiantes en clases híbridas (OEI, 2021). |
| **Problema**      | Carecen de una plataforma integrada para colaboración académica, dependiendo de múltiples apps dispersas (WhatsApp, Drive, Zoom). |

---
