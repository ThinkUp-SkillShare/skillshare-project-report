<!-- 
    CARATULA
-->

<p align="center"> <img src="https://imgur.com/IFP8FSt.png" alt="UPC Logo" width="100"> </p><div align="center"> 

<strong><h4>Universidad Peruana de Ciencias Aplicadas</h4></strong> </div>
<div align="center"> <strong>Ingeniería de Software</strong> </div>
<br>
<div align="center"> <strong>Periodo: 202520</strong> </div>

<div align="center">1ACC0238 | Aplicaciones Para Dispositivos Móviles</div><div align="center">NRC: 12614</div>

<br>
<div align="center"> <strong>Docente:</strong> Quevedo Velasco, David Gerardo </div>
<br>

<div align="center"> <strong>Informe de Trabajo Final</strong> </div>
<br>
<div align="center"> <strong>StartUp:</strong> <strong>ThinkUp</strong>  </div><div align="center"></div>
<div align="center"> <strong>Producto:</strong> <strong>SkillShare</strong>  </div><div align="center"></div>

<br>
<div align="center"> <strong>Integrantes:</strong></div>

<div align="center">U20231D978 - Argomedo Camacho, Jhosep Jamil</div>
<div align="center">U202020230 - González Custodio, Carlos Alberto</div>
<div align="center">U202121579 - Julca Cruz, Renso Anthony</div>
<div align="center">U202316122 - Ramírez Tello, Sebastian</div>

<br>
<br>
<div align="center"> <strong>Noviembre, 2025</strong> </div>

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
| TB1         | 18/09/25     | Argomedo, Jhosep; <br> González, Carlos; <br> Julca, Renso; <br> Ramírez, Sebastian. | Adición de secciones: <br> **Capítulo I:** Presentación <br> **Capítulo II:** Requirements Development and Software Solution Design |
| TP1         | 18/09/25     | Argomedo, Jhosep; <br> González, Carlos; <br> Julca, Renso; <br> Ramírez, Sebastian. | Adición de secciones: <br> **Capítulo III:** Requirements Specification <br> **Capítulo IV:** Solution Software Design |
| TB2         | 14/11/25     | Argomedo, Jhosep; <br> González, Carlos; <br> Julca, Renso; <br> Ramírez, Sebastian. | Adición de secciones: <br> **Capítulo V:** Solution UI/UX Design <br> **Capítulo VI:** Product Implementation, Validation & Deployment |

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
![Commits grupales](assets/images/team/contributors.jpg)
<br>
<br>
![Commits grupales](assets/images/team/commits.jpg)

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
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
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

## [Capítulo 5: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
- [5.1. Product Design](#51-product-design)
  - [5.1.1. Style Guidelines](#511-style-guidelines)
    - [5.1.1.1. General Style Guidelines](#5111-general-style-guidelines)
  - [5.1.2. Information Architecture](#512-information-architecture)
    - [5.1.2.1. Organization Systems](#5121-organization-systems)
    - [5.1.2.2. Labeling Systems](#5122-labeling-systems)
    - [5.1.2.3. SEO Tags and Meta Tags](#5123-seo-tags-and-meta-tags)
    - [5.1.2.4. Searching Systems](#5124-searching-systems)
    - [5.1.2.5. Navigation Systems](#5125-navigation-systems)
  - [5.1.3. Landing Page UI Design](#513-landing-page-ui-design)
    - [5.1.3.1. Landing Page Wireframe](#5131-landing-page-wireframe)
    - [5.1.3.2. Landing Page Mock-up](#5132-landing-page-mock-up)
  - [5.1.4. Mobile Applications UX/UI Design](#514-mobile-applications-uxui-design)
    - [5.1.4.1. Mobile Applications Wireframes](#5141-mobile-applications-wireframes)
    - [5.1.4.2. Mobile Applications Wireflow Diagrams](#5142-mobile-applications-wireflow-diagrams)
    - [5.1.4.3. Mobile Applications Mock-ups](#5143-mobile-applications-mock-ups)
    - [5.1.4.4. Mobile Applications User Flow Diagrams](#5144-mobile-applications-user-flow-diagrams)
    - [5.1.4.5. Mobile Applications Prototyping](#5145-mobile-applications-prototyping)

## [Capítulo 6: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
- [6.1. Software Configuration Management](#61-software-configuration-management)
  - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
  - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
  - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)

- [6.2. Landing Page & Mobile Application Implementation](#62-landing-page--mobile-application-implementation)
  - [6.2.1. Sprint 1](#621-sprint-1)
    - [6.2.1.1. Sprint Planning 1](#6211-sprint-planning-1)
    - [6.2.1.2. Sprint Backlog 1](#6212-sprint-backlog-1)
    - [6.2.1.3. Development Evidence for Sprint Review](#6213-development-evidence-for-sprint-review)
    - [6.2.1.4. Execution Evidence for Sprint Review](#6214-execution-evidence-for-sprint-review)
    - [6.2.1.5 Services Documentation Evidence for Sprint Review](#6215-services-documentation-evidence-for-sprint-review)
    - [6.2.1.6. Team Collaboration Insights during Sprint](#6216-team-collaboration-insights-during-sprint)

  - [6.2.2. Sprint 2](#621-sprint-2)
    - [6.2.2.1. Sprint Planning 2](#6221-sprint-planning-2)
    - [6.2.2.2. Sprint Backlog 2](#6222-sprint-backlog-2)
    - [6.2.2.3. Development Evidence for Sprint Review](#6223-development-evidence-for-sprint-review)
    - [6.2.2.4. Testing Suite Evidence for Sprint Review](#6224-testing-suite-evidence-for-sprint-review)
    - [6.2.2.5 Execution Evidence for Sprint Review](#6225-execution-evidence-for-sprint-review)
    - [6.2.2.6. Services Documentation Evidence for Sprint Review](#6226-services-documentation-evidence-for-sprint-review)
    - [6.2.2.7. Software Deployment Evidence for Sprint Review](#6227-software-deployment-evidence-for-sprint-review)
    - [6.2.2.8. Team Collaboration Insights during Sprint](#6228-team-collaboration-insights-during-sprint)

  - [6.2.3. Sprint 3](#623-sprint-3)
    - [6.2.3.1. Sprint Planning 3](#6231-sprint-planning-3)
    - [6.2.3.2. Sprint Backlog 3](#6232-sprint-backlog-3)
    - [6.2.3.3. Development Evidence for Sprint Review](#6233-development-evidence-for-sprint-review)
    - [6.2.3.4. Testing Suite Evidence for Sprint Review](#6234-testing-suite-evidence-for-sprint-review)
    - [6.2.3.5 Execution Evidence for Sprint Review](#6235-execution-evidence-for-sprint-review)
    - [6.2.3.6. Services Documentation Evidence for Sprint Review](#6236-services-documentation-evidence-for-sprint-review)
    - [6.2.3.7. Software Deployment Evidence for Sprint Review](#6237-software-deployment-evidence-for-sprint-review)
    - [6.2.3.8. Team Collaboration Insights during Sprint](#6238-team-collaboration-insights-during-sprint)

- [6.3. Validation Interviews](#63-validation-interviews)
- [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
- [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
- [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-segun-heurísticas)

---

- [Conclusiones](#conclusiones)
- [Recomendaciones](#recomendaciones)
- [Video App Validation](#video-app-validation)
- [Video About the product](#video-about-the-product)
- [Video About the team](#video-about-the-team)
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
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.** | - **Argomedo Camacho, Jhosep Jamil (TB1):** <br> • Investigué y apliqué metodologías Lean UX Canvas.<br> • Desarrollé análisis competitivo con matrices de comparación.<br> • Creé user personas completas con journey maps y empathy mapping.<br><br> - **Argomedo Camacho, Jhosep Jamil (TB2):** <br>• Aprendí e integré nuevas prácticas de desarrollo móvil en Flutter para optimizar navegación y manejo de estados.<br>• Apliqué conocimientos actualizados para integrar el backend con la aplicación móvil.<br>• Profundicé en Kotlin para mejorar la comunicación entre servicios y la arquitectura del proyecto.<br><br>- **Ramirez Tello, Sebastian (TB1):** <br> • Apliqué técnicas de design thinking para discovery.<br> • Desarrollé entrevistas cualitativas y análisis de resultados.<br> • Implementé specification requirements con user stories.<br><br>- **Ramirez Tello, Sebastian (TB2):** <br>• Actualicé conocimientos en diseño UI/UX para crear prototipos funcionales en Figma para el Sprint 2.<br>• Aprendí nuevos widgets y estructuras avanzadas de Flutter para implementar interfaces del proyecto.<br>• Apliqué buenas prácticas de diseño centrado en el usuario para mejorar la usabilidad de las vistas.<br><br>- **Julca Cruz, Renso Anthony (TB1):** <br> • Realicé dos entrevistas: una a una estudiante universitaria y otra a una persona autodidacta, recopilando experiencias sobre métodos de aprendizaje, retos y estrategias.<br> • Apliqué actividades de Strategic-Level Domain-Driven Design (DDD): EventStorming, Candidate Context Discovery, Domain Message Flows Modeling, Bounded Context Canvases. <br><br>-**Julca Cruz, Renso Anthony (TB2):** <br>• Actualicé y reestructuré todo el documento, mejorando la coherencia técnica y la redacción del Sprint 2.<br>• Apliqué nuevas técnicas de documentación ágil y reporting profesional.<br>• Aprendí métodos modernos para la elaboración y mejora continua de documentación técnica en proyectos de software. <br><br>- **Gonzalez Custodio, Carlos Alberto (TB1)** <br> • Realice 2 entrevistas para el segmento Docente, para poder conocer más las necesidades de los usuarios. <br> • Presente los diagramas C4 que permite comprender de manera más clara como se organiza la solución.  Dichos diagramas son: Context Level Diagram, Container Level Diagram y Deployment <br><br>- **Gonzalez Custodio, Carlos Alberto (TB2):** <br>• Implementé nuevas funcionalidades en el backend y amplié mis conocimientos en Kotlin.<br>• Apliqué buenas prácticas de arquitectura para mejorar la interacción entre servicios y la app móvil.<br>• Aprendí nuevas estrategias para diseñar controladores, endpoints y lógica de negocio en el proyecto. | - **Argomedo Camacho, Jhosep Jamil (TB1):** Actualicé mis conocimientos en metodologías ágiles y de diseño, aplicando con éxito Lean UX y DDD al proyecto. Mi investigación en análisis competitivo permitió identificar ventajas diferenciales para la solución.<br><br>- **Argomedo Camacho, Jhosep Jamil (TB2):** <br>• Consolidé nuevos conocimientos en desarrollo móvil y backend, aplicándolos directamente en la implementación del Sprint 2.<br>• El aprendizaje en Flutter y Kotlin permitió mejorar la calidad técnica del producto y avanzar de manera eficiente en las funcionalidades desarrolladas.<br><br>- **Ramirez Tello, Sebastian (TB1):** Actualicé mis conocimientos en técnicas de discovery y engineering de requisitos, aplicando metodologías de design thinking y especificación ágil para el proyecto.<br><br>- **Ramirez Tello, Sebastian (TB2):** <br>• Apliqué conocimientos nuevos en diseño y desarrollo móvil, fortaleciendo la capacidad del equipo para entregar interfaces funcionales y centradas en la experiencia del usuario.<br>• Se evidenció crecimiento técnico al adoptar herramientas y conceptos avanzados en Figma y Flutter.<br><br>- **Julca Cruz, Renso Anthony (TB1):** La aplicación de los conocimientos adquiridos en el curso, junto con la información de entrevistas, permitió actualizar y reforzar habilidades en el diseño de soluciones de software basadas en DDD. Esto evidencia la capacidad del grupo para adquirir nuevos conocimientos y adaptarlos al contexto del proyecto.  <br><br>- **Julca Cruz, Renso Anthony (TB2):** <br>• La actualización del documento reforzó mis habilidades en redacción técnica y documentación profesional, aplicando estándares más avanzados de claridad y organización.<br>• El proceso evidenció la importancia de mejorar continuamente las prácticas de documentación para soportar el desarrollo del proyecto.<br><br>- **Gonzalez Custodio, Carlos Alberto (TB1):** Logré adquirir nuevas habilidades y conocimientos al comprender como elaborar Diagramas C4 ademas de poder entender las necesidades del usuario mediantes las entrevistas realizadas.<br><br>- **Gonzalez Custodio, Carlos Alberto (TB2):** <br>• La implementación del backend y el uso avanzado de Kotlin permitieron adquirir habilidades nuevas esenciales para el avance del proyecto.<br>• El aprendizaje aplicado fortaleció la arquitectura del sistema y la calidad de las funcionalidades desarrolladas. |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.** | - **Argomedo Camacho, Jhosep Jamil (TB1):** <br> • Aprendí técnicas avanzadas de needfinding.<br> • Investigué arquitecturas software escalables.<br> • Apliqué strategic modeling techniques.<br> • Desarrollé habilidades en competitive analysis. <br><br>-**Argomedo Camacho, Jhosep Jamil (TB2):** <br>• Fortalecí mi comprensión sobre buenas prácticas de integración entre Flutter y backend.<br>• Investigué estrategias modernas para mejorar la comunicación entre servicios.<br>• Reconocí la importancia de seguir aprendiendo arquitectura y patrones de diseño para desarrollo móvil.<br><br>- **Ramirez Tello, Sebastian (TB1):** <br> • Investigué best practices para startup profiling.<br> • Aprendí técnicas de problem framing y solution positioning.<br> • Desarrollé habilidades en qualitative research. <br><br> **Ramirez Tello, Sebastian (TB2):** <br>• Reforcé la importancia de actualizar técnicas de diseño UI/UX para mantener la calidad del producto.<br>• Investigué patrones modernos de experiencia de usuario para mejorar la app.<br>• Reconocí que el aprendizaje continuo es clave para el desarrollo móvil profesional.<br><br>- **Julca Cruz, Renso Anthony (TB1):** <br> • Durante el desarrollo de las actividades de EventStorming y modelado de flujos de mensajes de dominio, se identificó la importancia de comprender de manera continua los cambios en los requerimientos del negocio y en las prácticas modernas de desarrollo de software. <br> • En las entrevistas se resaltó la relevancia de la autoformación y la actualización constante como factores clave para el crecimiento profesional. <br><br> **Julca Cruz, Renso Anthony (TB2):** <br>• Identifiqué la importancia de mantener al día las prácticas de documentación técnica y metodologías ágiles.<br>• Reforcé habilidades de redacción profesional y organización de información técnica.<br>• Comprendí que la mejora constante es esencial para producir documentación alineada a estándares profesionales.<br><br>- **González Custodio, Carlos Alberto (TB1):** <br> • Aprendí Software Architecture y creacion de modelos C4 para un mayor comprensión y entendimiento de como esta organizado todo siguiendo las buenas practicas.<br><br>-  **Gonzalez Custodio, Carlos Alberto (TB2):** <br>• Aprendí nuevas prácticas de arquitectura backend y manipulación de servicios en Kotlin.<br>• Reconocí la importancia del aprendizaje continuo para mantener sistemas escalables y robustos.<br>• Incorporé nuevos conocimientos para optimizar el backend y mejorar su calidad general. | - **Argomedo Camacho, Jhosep Jamil (TB1):** Demostré comprensión de que el aprendizaje continuo es esencial, investigando constantemente nuevas metodologías para mejorar la calidad del proyecto y su desarrollo profesional.<br><br>- **Argomedo Camacho, Jhosep Jamil (TB2):** <br>• El Sprint 2 reafirmó que el aprendizaje continuo es esencial para adaptar el desarrollo móvil y backend a las necesidades del proyecto.<br>• Investigar nuevas técnicas permitió mejorar el rendimiento y la escalabilidad de la aplicación.<br><br>- **Ramirez Tello, Sebastian (TB1):** Mostré reconocimiento de la necesidad de aprendizaje continuo, investigando constantemente nuevos approaches para validación de negocio y desarrollo de soluciones software efectivas. <br><br>- **Ramirez Tello, Sebastian (TB2):** <br>• Reafirmé la importancia de mantener actualizadas las prácticas de diseño y desarrollo móvil para mejorar usabilidad y eficiencia.<br>• El aprendizaje permanente es clave para sostener la calidad del diseño UI/UX en productos reales.<br><br>- **Julca Cruz, Renso Anthony (TB1):** El grupo reconoce que el aprendizaje no concluye con el curso, sino que debe mantenerse activo en la investigación y práctica de nuevas metodologías de diseño y arquitectura. Esto refuerza la visión de aprendizaje permanente como parte esencial del desempeño profesional en ingeniería de software. <br><br> **Julca Cruz, Renso Anthony (TB2):** <br>• La mejora constante en documentación técnica evidencia la necesidad de seguir aprendiendo y actualizando metodologías de ingeniería de software.<br>• La experiencia refuerza que la documentación profesional es un proceso iterativo que requiere actualización continua.<br><br> **Gonzalez Custodio, Carlos Alberto (TB2):** <br>• La integración de nuevas técnicas de desarrollo backend reforzó la importancia del aprendizaje continuo para asegurar sistemas robustos.<br>• El reconocimiento de nuevas prácticas y herramientas permitió mejorar la calidad técnica del backend y su escalabilidad.<br><br> **González Custodio, Carlos Alberto (TB1):** Logré adquirir nuevos conocimientos y experiencia que me servirán para futuros trabajos y además para la conclusión del presente proyecto. |

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

![Comparison of failure rates and exam score improvements between traditional lecturing and active learning in STEM education](assets/images/C2/stem-learning_method_comparison.jpg)

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

1. Creemos que la posibilidad de unirse y colaborar en grupos de estudio temáticos permitirá a los estudiantes organizar mejor su aprendizaje y encontrar compañeros con intereses similares.Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado:

   - **Cualitativo:** usuarios expresan que la función de grupos les facilita organizar su aprendizaje y encontrar compañeros con intereses similares.

   - **Cuantitativo:** al menos el 70% de los usuarios registrados se unan a un grupo dentro de su primera semana.

   - **Indicador clave:** aumento en el número de publicaciones y materiales compartidos en grupos activos.

<br>

2. Creemos que una interfaz intuitiva y fácil de usar facilitará la adopción de la aplicación por estudiantes de diferentes edades y niveles tecnológicos. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado:

   - **Cualitativo:** usuarios reportan que la app es clara y no requiere tutorial extenso.

   - **Cuantitativo:** reducción del 30% en el abandono durante el registro o primer uso.

   - **Indicador clave:** aumento en la tasa de retención de usuarios después de las primeras 2 semanas.

<br>

3. Creemos que ofrecer un espacio centralizado para compartir materiales de estudio (PDF, apuntes, links, videos) incrementará la utilidad de la aplicación. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado:

   - **Cualitativo:** los usuarios destacan la biblioteca como una de las funciones más útiles.

   - **Cuantitativo:** al menos el 60% de los grupos creen o suban un recurso en su primer mes.

   - **Indicador clave:** incremento en descargas y consultas de materiales compartidos.

<br>

4. Creemos que incorporar un sistema de recomendación de grupos y materiales basados en intereses mejorará la personalización y el engagement del usuario. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado:

   - **Cualitativo:** usuarios expresan que las recomendaciones son relevantes y útiles

   - **Cuantitativo:** al menos el 50% de los usuarios interactúen con una recomendación sugerida.

   - **Indicador clave:** incremento en el tiempo promedio de sesión dentro de la app.

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

<br>
<br>
<br>
<br>
<br>
<br>

<!--
   CAPÍTULO 2
-->

# 2. Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores

### 2.1.1 Análisis Competitivo

**¿Por qué realizar este análisis?**

El mercado de plataformas digitales para aprendizaje colaborativo está dominado por herramientas generalistas y algunas soluciones educativas con componentes de interacción. Entre los principales competidores de **SkillShare** se identifican: **Discord, Google Classroom y Quizlet**.

<br>

| | Nombre | SkillShare | Discord | Classroom | Quizlet |
| ------------------------ | ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
|                          |                              | <p align="center"><img src="assets/images/common/logo.png" alt="skillshare" width="400"></p>  | <p align="center"><img src="https://logos-world.net/wp-content/uploads/2020/12/Discord-Logo.png" alt="discord" width="400"></p>             | <p align="center"><img src="https://logos-world.net/wp-content/uploads/2021/08/Google-Classroom-Logo-2014-2016.png" alt="classroom" width="400"></p> | <p align="center"><img src="https://logos-world.net/wp-content/uploads/2021/03/Quizlet-Emblem.png" alt="quizlet" width="400"></p> |
| **Perfil**               | **Overview**                 | Plataforma diseñada para estudiantes que buscan organizar grupos de estudio colaborativos, con chat, videollamadas y recursos compartidos en un solo lugar. | Herramienta de comunicación en tiempo real, diseñada para comunidades, con chat, voz y videollamadas. | Plataforma educativa que facilita la gestión de clases, tareas y evaluaciones.              | Plataforma de estudio basada en flashcards y quizzes interactivos.                        |
|                          | **Ventaja competitiva**      | Enfoque exclusivo en aprendizaje colaborativo estructurado, integrando chat, videollamadas y recursos en un solo espacio, con un modelo freemium accesible. | Gran comunidad y facilidad de uso; ya es adoptada masivamente por estudiantes.                        | Integración oficial con instituciones educativas y ecosistema de Google.                    | Herramientas efectivas de memorización con amplia base de usuarios.                       |
| **Plan de Marketing**    | **Mercado objetivo**         | Estudiantes de secundaria, universidad y autodidactas.                                                                                                      | Jóvenes y comunidades online, principalmente gamers y estudiantes.                                    | Instituciones educativas (colegios, universidades, docentes).                               | Estudiantes individuales que buscan memorizar y repasar contenidos.                       |
|                          | **Estrategias de marketing** | Promoción en redes sociales, convenios con universidades y modelo freemium.                                                                                 | Marketing comunitario y boca a boca, impulsado por gamers.                                            | Integración con ecosistema Google y acuerdos institucionales.                               | Viralidad entre estudiantes y asociaciones con docentes.                                  |
| **Plan de Producto**     | **Productos y servicios**    | Grupos de estudio, chat en tiempo real, videollamadas, recursos compartidos.                                                                                | Servidores, canales de voz/texto, videollamadas, bots y comunidades temáticas.                        | Gestión de cursos, tareas, evaluaciones, integración con Google Drive.                      | Flashcards digitales, quizzes, juegos interactivos.                                       |
|                          | **Precios y costos**         | Modelo freemium (gratis + premium educativo \~USD 10/mes).                                                                                                  | Gratis; versión Nitro (USD 9.99/mes).                                                                 | Gratis con cuenta Google; planes pagados en Google Workspace for Education.                 | Gratis con anuncios; Quizlet Plus (\~USD 3/mes).                                          |
|                          | **Canales de distribución**  | App móvil (Android/iOS), web, redes sociales, alianzas con universidades.                                                                                   | App de escritorio, móvil y web; crecimiento orgánico comunitario.                                     | Integrado en Google Workspace; acceso web y app móvil.                                      | App móvil y web, difusión entre estudiantes y docentes.                                   |
| **Análisis FODA / SWOT** | **Fortalezas**               | Enfoque 100 % académico, integración de chat + videollamadas + recursos, modelo freemium accesible.                                                         | Comunidad activa, alta personalización, uso masivo entre jóvenes.                                     | Respaldo de Google, integración con Drive, adopción institucional.                          | Herramientas de memorización efectivas, fácil de usar, base de usuarios amplia.           |
|                          | **Debilidades**              | Marca nueva y poco conocida, riesgo de baja adopción frente a competidores.                                                                                 | No diseñado para educación, exceso de distracciones.                                                  | Experiencia centrada en docentes, poca flexibilidad para grupos autónomos.                  | Enfoque limitado a memorización, funciones colaborativas reducidas.                       |
|                          | **Oportunidades**            | Crecimiento del e-learning en LATAM, alianzas universitarias, alta dependencia móvil en estudiantes.                                                        | Expansión hacia comunidades educativas y profesionales.                                               | Digitalización acelerada en colegios y universidades.                                       | Mayor demanda de autoestudio online y repaso rápido.                                      |
|                          | **Amenazas**                 | Preferencia por plataformas ya consolidadas, posible copia de funciones por grandes competidores.                                                           | Saturación con usos no académicos, aparición de apps especializadas en educación.                     | Competencia con plataformas más colaborativas, dependencia de Google.                       | Aparición de herramientas de IA que reemplacen flashcards tradicionales.                  |

<br>
<br>

### 2.1.2. Estrategias y tácticas frente a competidores

#### 1. Fortaleza de los competidores
- **Gran comunidad de Discord, respaldo de Google, popularidad de Quizlet**

**Estrategias:** Diferenciar a SkillShare como la única app 100 % enfocada en grupos de estudio colaborativos.

**Táctica:** Campañas en universidades y redes sociales que muestren casos reales de mejora académica con SkillShare.

#### 2. Debilidades de los competidores
- **Distracciones en Discord, rigidez en Classroom, limitaciones de Quizlet**

**Estrategias:** Posicionar a SkillShare como la opción más práctica y académica.

**Táctica:** Ofrecer onboarding sencillo, pruebas premium gratuitas y recursos gamificados para retención de usuarios.

#### 3. Oportunidades en el mercado
- **Crecimiento del e-learning, digitalización en la región, uso masivo de celulares**

**Estrategias:** Expandir presencia en Latinoamérica mediante convenios con universidades y asociaciones estudiantiles.

**Táctica:** Programas de embajadores universitarios y licencias institucionales a bajo costo para acelerar la adopción.

#### 4. Amenazas de los competidores
- **Adopción masiva de WhatsApp/Discord, posibles imitaciones de funciones**

**Estrategias:** Innovación continua y desarrollo de funciones educativas exclusivas

---

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Con el fin de comprender mejor los hábitos, necesidades y dificultades de nuestros segmentos objetivo, diseñamos entrevistas cualitativas dirigidas a cuatro perfiles:

* Estudiantes de educación superior.
* Estudiantes de secundaria.
* Estudiantes autodidactas.
* Docentes.

El objetivo es recoger insights que permitan construir una aplicación más cercana a las expectativas reales de los usuarios.

---

### Segmento 1: Estudiantes de educación superior (universidad o institutos)

**Preguntas principales**

1. ¿Cuáles son tus principales desafíos cuando estudias en grupo en la universidad?
2. ¿Qué herramientas usas actualmente para organizar o participar en grupos de estudio? (ejemplo: WhatsApp, Discord, Google Drive, etc.)
3. ¿Qué te resulta incómodo o poco práctico de esas herramientas?
4. ¿Qué características valoras más en una aplicación que apoye tu aprendizaje en grupo?
5. ¿Con qué frecuencia estudias en grupo y para qué materias lo haces más seguido?
6. ¿Qué tan cómodo te resulta estudiar usando solo una aplicación móvil?
7. ¿Qué tan importante sería para ti contar con recordatorios o agendas de estudio integradas en la aplicación?
8. Si tuvieras que elegir, ¿qué sería más importante: mejor comunicación, más recursos compartidos o motivación (gamificación)?
9. ¿Has pagado o pagarías por un servicio digital que mejore tu rendimiento académico?

**Preguntas secundarias**

1. ¿Qué dispositivos usas con mayor frecuencia para estudiar (PC, laptop, celular, tablet)?
2. ¿Qué tanto influye la compatibilidad con tu dispositivo en la decisión de usar una aplicación?
3. ¿Qué esperas en cuanto a diseño visual y facilidad de uso en una app de estudio?
4. ¿Hay marcas, aplicaciones o plataformas educativas que admires y que te gustaría que SkillShare se parezca a ellas?

---

### Segmento 2: Estudiantes de secundaria (o preparatoria)

**Preguntas principales**

1. ¿Con qué frecuencia estudias en grupo para tareas o exámenes?
2. ¿Qué problemas tienes cuando intentas organizar un grupo de estudio con tus compañeros?
3. ¿Qué aplicaciones o redes sociales usas más para estudiar en grupo?
4. ¿Qué cosas te gustaría que una aplicación de estudio en grupo te facilitara?
5. ¿Usarías una aplicación solo desde el celular o preferirías también acceso en computadora?
6. ¿Te motivaría más estudiar si una aplicación te diera recompensas o logros por participar?
7. ¿Qué tan importante es para ti que la aplicación sea gratuita o tenga bajo costo?
8. ¿Crees que tus padres o profesores apoyarían el uso de una aplicación como esta?

**Preguntas secundarias**

1. ¿Qué tan seguido compartes materiales digitales (PDF, links, videos) con tus compañeros?
2. ¿Qué tanto influye la velocidad y facilidad de uso de una aplicación en tu decisión de seguir utilizándola?
3. ¿Qué tipo de diseño prefieres: más juvenil/divertido o más serio/profesional?
4. ¿Qué canal prefieres para recibir notificaciones importantes: dentro de la aplicación, correo o mensajes?

---

### Segmento 3: Estudiantes autodidactas

**Preguntas principales**

1. ¿Qué métodos utilizas actualmente para aprender de forma autodidacta?
2. ¿Qué tan importante es para ti conectarte con otras personas que estudian lo mismo?
3. ¿Qué problemas encuentras cuando buscas materiales o tratas de mantener una rutina de estudio?
4. ¿Qué funcionalidades te ayudarían más: recordatorios, agenda de estudio, foros, chat en tiempo real?
5. ¿Usarías una aplicación 100% móvil para organizar tu aprendizaje? ¿O prefieres computadora?
6. ¿Qué tan cómodo te resulta compartir tus avances o proyectos en un grupo?
7. ¿Qué te motivaría más: acceso a recursos, contacto con otros autodidactas, o medir tu progreso?
8. ¿Estarías dispuesto a pagar por una versión premium si ofrece mejores recursos o conexiones con expertos?

**Preguntas secundarias**

1. ¿Qué tan relevante es para ti el diseño visual (limpio, minimalista vs. atractivo, dinámico)?
2. ¿Qué tipo de notificaciones valoras más para mantener la constancia?
3. ¿Qué marcas, influencers o aplicaciones te inspiran en tu camino de aprendizaje?
4. ¿Qué tan importante es que la aplicación consuma poco espacio y funcione en celulares de gama baja?

---

### Segmento 4: Docentes

**Preguntas principales**

1. ¿Qué dificultades enfrentas al organizar y dar seguimiento a los grupos de estudio de tus estudiantes?
2. ¿Qué herramientas digitales usas actualmente para coordinar actividades académicas (ejemplo: WhatsApp, Classroom, Zoom, Drive)?
3. ¿Qué limitaciones encuentras en esas herramientas al momento de fomentar el trabajo colaborativo?
4. ¿Qué funcionalidades valoras más en una aplicación que te permita apoyar a tus estudiantes (ejemplo: gestión de grupos, seguimiento de participación, recursos compartidos)?
5. ¿Qué tan importante es para ti poder monitorear el progreso y la constancia de tus estudiantes dentro de la aplicación?
6. ¿Qué opinas sobre integrar chats y videollamadas directamente en una aplicación de estudio en grupo?
7. ¿Qué tan cómodo te resultaría usar una aplicación móvil para coordinar con tus estudiantes? ¿Preferirías también acceso desde computadora?

**Preguntas secundarias**

1. ¿Qué tipo de dispositivos usas más para tu labor docente digital (celular, laptop, PC, tablet)?
2. ¿Qué tipo de diseño visual prefieres en una aplicación educativa dirigida a estudiantes: más juvenil/divertido o más formal/profesional?
3. ¿Qué tanto influiría la seguridad y privacidad de datos (chats, videollamadas, materiales) en tu decisión de recomendar la aplicación?
4. ¿Qué tanto valoras que la aplicación te permita diferenciar entre tu rol como docente y el rol de estudiante dentro de los grupos?

---

## 2.2.2. Registro de entrevistas

### Segmento 1: Estudiantes de Educación Superior

#### Entrevista 1

| **Campo** | **Detalle** |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Entrevista 1](assets/images/C2/interviews/s1-e1.png) | Enlace: [Video](https://youtu.be/nsrOvXc6Tcs)  |
| **Entrevistada**      | Rivera Quispe, Allison Milagros |
| **Edad**              | 21 años  |
| **Rubro**             | Estudiante de Administración |
| **Ubicación**         | Lima, San Martín de Porres |
| **Medio**             | Discord  |
| **Entrevistador**     | Julca Cruz, Renso Anthony  |
| **Instante inicio**   | 00:00:05   |
| **Duración**          | 04 min 01 seg |
| **Resumen**           | Allison señaló que sus principales desafíos al estudiar en grupo son coordinar horarios, mantener el enfoque y lidiar con compañeros poco preparados. Usa WhatsApp, Google Drive, Discord y Meet, pero encuentra desorden en archivos y distracciones. Considera clave una app que brinde comunicación clara, materiales organizados y recordatorios. Prefiere laptop, estudia en grupo en cursos exigentes (finanzas, estadística) y pagaría por una app útil y accesible. |

#### Entrevista 2

| **Campo** | **Detalle**  |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![Entrevista 1](assets/images/C2/interviews/s1-e2.png) | Enlace: [Video](https://youtu.be/YWwc3DlUQVs)|
| **Entrevistado**      | Hanco, Keyner |
| **Edad**              | 20 años  |
| **Rubro**             | Estudiante universitario |
| **Ubicación**         | Lima, Magdalena del Mar |
| **Medio**             | Meet |
| **Entrevistador**     | Ramírez Tello, Sebastián |
| **Instante inicio**   | 00:00:45  |
| **Duración**          | 04 min 24 seg |
| **Resumen**           | Keyner indicó que las diferencias en ritmo de aprendizaje y distracciones con amigos dificultan el estudio en grupo. Usa Discord por practicidad, pero no está pensado para educación. Valora notas compartidas, PDFs, videos, recordatorios y agenda. Prefiere celular por comodidad, estudia en grupo sobre todo en exámenes. Considera esenciales comunicación y recursos, y pagaría por una app que mejore su rendimiento. |

---

### Segmento 2: Estudiantes de Secundaria

#### Entrevista 1

| **Campo**  | **Detalle**  |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![Entrevista 1](assets/images/C2/interviews/s2-e1.png) | Enlace: [Video](https://drive.google.com/file/d/1FuK5_IBT6OWCcFcUV1BB2kZx4zTx04GY/view?usp=drive_link)  |
| **Entrevistada**      | DoCampo, Luciana  |
| **Edad**              | 14 años  |
| **Rubro**             | Estudiante colegio, 3er grado |
| **Ubicación**         | Lima, San Isidro  |
| **Medio**             | Zoom  |
| **Entrevistador**     | Andrés García  |
| **Instante inicio**   | 00:05  |
| **Duración**          | 07 min 43 seg   |
| **Resumen**           | Luciana comentó que enfrenta problemas porque no todos colaboran igual en proyectos escolares. Usa WhatsApp, pero considera que no es suficiente. Quiere una app que motive y se adapte a diferentes estilos de aprendizaje. Prefiere laptop, aunque usa celular. Desea recompensas y un diseño juvenil, con notificaciones al celular o correo. |

#### Entrevista 2

| **Campo**  | **Detalle**  |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Entrevista 1](assets/images/C2/interviews/s2-e2.png) | Enlace: [Video](https://drive.google.com/file/d/1Ler1MximkUI4TBXodpxHMTDuBSM2J7ZF/view?usp=drive_link)  |
| **Entrevistada**      | Lozano, Mariana |
| **Edad**              | 15 años  |
| **Rubro**             | Estudiante colegio, 4to grado  |
| **Ubicación**         | Bogotá, Colombia  |
| **Medio**             | Zoom |
| **Entrevistador**     | Andrés García  |
| **Instante inicio**   | 00:05 |
| **Duración**          | 06 min 12 seg   |
| **Resumen**           | Mariana señaló que estudia en grupo en trabajos largos, pero algunos no cumplen. Usan WhatsApp, pero quiere una app que integre chat, calendario, recordatorios y espacios para ideas. Prefiere celular, con opción de PC. Le gustaría que sea gratuita o de bajo costo, con recompensas y diseño juvenil. Sus padres/profesores apoyarían su uso. |

---

### Segmento 3: Estudiantes Autodidactas

#### Entrevista 1

| **Campo**  | **Detalle**  |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Entrevista 1](assets/images/C2/interviews/s3-e1.png) | Enlace: [Video](https://youtu.be/Yi41aLH-Zzs)  |
| **Entrevistada**      | Vilca Valverde, Fiorella Angela  |
| **Edad**              | 22 años  |
| **Rubro**             | Estudiante autodidacta |
| **Ubicación**         | Lima, San Martín de Porres  |
| **Medio**             | Discord  |
| **Entrevistador**     | Julca Cruz, Renso Anthony   |
| **Instante inicio**   | 00:00:05   |
| **Duración**          | 04 min 00 seg   |
| **Resumen**           | Fiorella estudia con YouTube, blogs y PDFs. Busca conectar con otros para motivarse y resolver dudas. Dificultades: exceso de información, falta de constancia y horarios. Quiere recordatorios, agenda y chat en tiempo real. Prefiere celular, se siente cómoda compartiendo avances. Le motiva medir progreso y estaría dispuesta a pagar por una versión premium con expertos. |

#### Entrevista 2

| **Campo**             | **Detalle**   |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![Entrevista 1](assets/images/C2/interviews/s3-e2.png) | Enlace: [Video](https://drive.google.com/file/d/11-2en9KWlYKJZ-ya2PDRXrReMPWwj3ms/view?usp=drive_link) |
| **Entrevistada**      | Sol, Lily  |
| **Edad**              | 24 años  |
| **Rubro**             | Viajera  |
| **Ubicación**         | Lima, Miraflores |
| **Medio**             | Zoom   |
| **Entrevistador**     | Andrés García  |
| **Instante inicio**   | 00:05   |
| **Duración**          | 04 min 54 seg     |
| **Resumen**           | Lily estudia de forma autodidacta con YouTube, artículos y cursos cortos. Problemas: filtrar información y mantener constancia. Valora agenda con recordatorios y chat en tiempo real. Quiere diseño limpio y que funcione en celulares gama media/baja. Pagará premium si incluye expertos o contenido exclusivo. |

#### Entrevista 3

| **Campo**  | **Detalle**  |
| --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Entrevista 1](assets/images/C2/interviews/s3-e3.png) | Enlace: [Video](https://drive.google.com/file/d/1D-maDUL9Pzv_XaV8RW3GaaU8Q52LEZ-t/view?usp=drive_link)  |
| **Entrevistado**      | Wolf, Carlos  |
| **Edad**              | 21 años   |
| **Rubro**             | Viajero, trabajador hotelero    |
| **Ubicación**         | Lima, Jesús María  |
| **Medio**             | Zoom  |
| **Entrevistador**     | Andrés García  |
| **Instante inicio**   | 00:05  |
| **Duración**          | 05 min 24 seg  |
| **Resumen**           | Carlos estudia con cursos online y apps móviles. Problemas: falta de tiempo y exceso de información. Prefiere app 100% móvil, ligera y minimalista. Valora agenda con recordatorios y seguimiento de progreso. No prioriza compartir avances, pero sí conversar con alguien con experiencia. Pagará premium si ofrece contenido aplicable profesionalmente. |

---

### Segmento 4: Docentes

#### Entrevista 1

| **Campo**| **Detalle** |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![Entrevista 1](assets/images/C2/interviews/s4-e1.png) | Enlace: [Video](https://youtu.be/0608y_ujm0A)  |
| **Entrevistado**      | Villareal, José Manuel |
| **Edad**              | 27 años  |
| **Rubro**             | Docente secundaria   |
| **Ubicación**         | Monsefú, Lambayeque   |
| **Medio**             | Zoom    |
| **Entrevistador**     | González Custodio, Carlos Alberto  |
| **Instante inicio**   | 00:01:00  |
| **Duración**          | 05 min 27 seg    |
| **Resumen**           | José Manuel señaló dificultades por baja participación y coordinación de horarios. Usa Classroom y Meet, pero no fomentan colaboración. Quiere una app con materiales compartidos, retroalimentación y reportes de progreso. Prefiere diseño formal-amigable con seguridad y diferenciación de roles docente-estudiante. |

#### Entrevista 2

| **Campo**  | **Detalle**   |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Entrevista 1](assets/images/C2/interviews/s4-e2.png) | Enlace: [Video](https://youtu.be/J2UVr4sQtAs) |
| **Entrevistada**      | Salon, Merly  |
| **Edad**              | 25 años  |
| **Rubro**             | Docente secundaria   |
| **Ubicación**         | Lima, San Martín de Porres   |
| **Medio**             | Meet   |
| **Entrevistador**     | González Custodio, Carlos Alberto   |
| **Instante inicio**   | 00:01:01   |
| **Duración**          | 06 min 14 seg   |
| **Resumen**           | Merly señaló que la dispersión de alumnos en varias plataformas dificulta el seguimiento. Usa Classroom, Drive y WhatsApp, pero no integran funciones. Quiere app que centralice materiales, organice grupos y muestre estadísticas claras. Valora integración de chat/videollamadas, diseño juvenil-profesional y alta seguridad. Insiste en diferenciar rol docente-estudiante. |

---
<br>

## 2.2.3. Análisis de entrevistas

### Segmento 1: Estudiantes de educación superior (universidad o institutos)  
**Tamaño de la Muestra (n):** 2 entrevistas  
**Base de Cálculo:** Todas las estadísticas y porcentajes se calculan sobre la base de las 2 entrevistas realizadas. Cada entrevistado representa el 50% del segmento analizado.

---

### 1. Análisis de Características Objetivas (Datos Demográficos y Observables)

| Característica             | Allison (50%)                  | Keyner (50%)               | Análisis y Sustento                                                                 |
|-----------------------------|--------------------------------|----------------------------|-------------------------------------------------------------------------------------|
| Edad                        | 21 años                        | 22 años                    | Ambos entrevistados se encuentran en el rango etario típico de estudiantes universitarios de pregrado. |
| Nivel de estudio            | Universidad                    | Universidad                | El segmento está compuesto exclusivamente por estudiantes universitarios.           |
| Carrera                     | Administración                 | Ingeniería de Sistemas     | Muestra una diversidad de áreas de estudio (negocios y tecnología), lo que sugiere que las necesidades son transversales. |
| Dispositivo principal       | Laptop                         | Celular                    | Existe una división clara en la preferencia del dispositivo, indicando la necesidad de una aplicación multiplataforma (web y móvil) para cubrir ambos usos. |
| Frecuencia de estudio grupal| Antes de exámenes y en cursos difíciles | En épocas de exámenes | Ambos coinciden en que la modalidad grupal se intensifica en periodos de alta demanda académica (exámenes, cursos complejos). |

---

### 2. Análisis de Características Subjetivas (Necesidades, Dolores y Motivaciones)

**a. Desafíos y Dolores Principales en el Estudio Grupal (¿Qué problemas enfrentan?)**

| Dolor                      | Manifestación en las Entrevistas                                                                 |
|----------------------------|--------------------------------------------------------------------------------------------------|
| Coordinación y Logística   | "Coordinar horarios" (Allison), "Agendas de estudio integradas" (Keyner).                        |
| Falta de Enfoque y Distracciones | "Mantener el enfoque", "lidiar con compañeros poco preparados" (Allison), "falta de concentración... se distraen" (Keyner). |
| Problemas con Herramientas Actuales | "Mezcla de mensajes personales, desorden en archivos" (Allison), "no diseñado para el aprendizaje" (Keyner). |
| Diferencias en el Compromiso | "Compañeros poco preparados" (Allison), "diferencias en el ritmo de aprendizaje" (Keyner). |

**Sustento:** El 100% de los entrevistados identificó problemas de coordinación, distracción y las limitaciones de las aplicaciones genéricas (como WhatsApp o Discord) como sus principales obstáculos. Esto indica que estos no son problemas aislados, sino dolores universales para el segmento.

**Insight**: Los problemas de organización y las constantes distracciones no son situaciones puntuales ni excepcionales; forman parte de una realidad estructural que atraviesa a todo el segmento analizado. Esta falta de enfoque y planificación no solo dificulta el cumplimiento de metas personales o académicas, sino que también genera una sensación continua de estrés, pérdida de tiempo y baja productividad. El hecho de que este patrón se repita de forma consistente entre distintos usuarios indica que no se trata de un problema individual, sino de una necesidad colectiva no satisfecha. En consecuencia, se evidencia una oportunidad clara de diseño para crear soluciones que ayuden a gestionar el tiempo, priorizar tareas y reducir la dispersión, promoviendo hábitos más eficientes y sostenibles en la rutina diaria.

---

**b. Comportamiento Actual y Herramientas Utilizadas (¿Qué usan ahora?)**

| Herramienta/Comportamiento | Manifestación en las Entrevistas                                                                 |
|-----------------------------|--------------------------------------------------------------------------------------------------|
| Uso de Múltiples Apps       | WhatsApp, Drive, Discord, Meet (Allison); Discord (Keyner).                                      |
| Discord como Herramienta Principal | "Actualmente usa Discord" (Allison), "Utiliza Discord" (Keyner).                        |
| Reconocimiento de Limitaciones | Ambas entrevistas critican la falta de enfoque específico para el estudio de las herramientas que usan. |

**Sustento:** Hay una coincidencia del 100% en el uso de Discord por su practicidad en comunicación y compartición de pantalla. Sin embargo, también hay un consenso total (100%) en que estas herramientas no están optimizadas para su caso de uso, creando una oportunidad clara para una solución especializada.

**Insight**: Si bien los usuarios recurren a plataformas como Discord como una solución “parche” para coordinar actividades académicas y comunicarse en grupo, esta herramienta no logra cubrir de manera efectiva sus necesidades reales. Su uso responde más a la falta de alternativas adecuadas que a una verdadera satisfacción con la experiencia que ofrece. Discord, al estar diseñado principalmente para comunidades de entretenimiento o gaming, carece de funciones orientadas a la gestión de tareas, organización de proyectos o seguimiento académico. Esta adaptación forzada revela una brecha clara en el mercado: la ausencia de una plataforma especializada que combine la interacción social con herramientas de productividad educativa. Por tanto, existe una oportunidad significativa para diseñar una solución que se alinee con las dinámicas y requerimientos específicos del entorno académico.

---

**c. Necesidades y Expectativas Deseadas (¿Qué solución buscan?)**

| Necesidad                  | Manifestación en las Entrevistas                                                                 |
|-----------------------------|--------------------------------------------------------------------------------------------------|
| Organización Centralizada   | "Materiales organizados por temas" (Allison), "compartir materiales... tomar notas" (Keyner).   |
| Comunicación Clara y Enfocada | "Comunicación clara" (Allison), "buena comunicación dentro de la app" (Keyner).               |
| Funciones de Planificación  | "Recordatorios de reuniones" (Allison), "recordatorios y agendas de estudio" (Keyner).          |
| Disponibilidad Multiplataforma | Prefiere laptop (Allison), prefiere celular (Keyner).                                        |

**Sustento:** Las necesidades clave son universales (100%): un espacio organizado, comunicación dedicada al estudio y herramientas integradas de planificación. La divergencia en el dispositivo preferido refuerza la necesidad de que la solución funcione perfectamente en ambos.

**Insight**: El estudiante universitario actual no se conforma únicamente con tener canales de comunicación; su necesidad va mucho más allá del simple intercambio de mensajes. Busca un espacio integral, un verdadero “hub académico digital” que concentre en un solo lugar herramientas para organizar sus tareas, planificar actividades y colaborar de manera efectiva con sus compañeros. Esta necesidad surge de la fragmentación que experimentan al utilizar múltiples aplicaciones con fines distintos —una para comunicarse, otra para gestionar proyectos y otra para almacenar materiales— lo que genera dispersión, pérdida de tiempo y falta de cohesión en el trabajo académico. Por ello, el diseño de una plataforma centralizada que unifique comunicación, planificación y productividad se presenta como una oportunidad clave para optimizar la experiencia del estudiante y responder a las dinámicas reales de su entorno universitario.

---

**d. Disposición al Pago (¿Invertirían en una solución?)**

| Aspecto                    | Manifestación en las Entrevistas                                                                 |
|-----------------------------|--------------------------------------------------------------------------------------------------|
| Nunca han pagado            | "Nunca ha pagado por aplicaciones de estudio" (Allison). Se infiere lo mismo para Keyner.       |
| Disposición Condicional     | Ambas expresaron que pagarían si la aplicación demuestra valor tangible.                        |
| Condiciones para pagar      | "Costo accesible" (Allison), "mejora su rendimiento académico" (Keyner).                       |

**Sustento:** El segmento es 100% sensible al precio y al valor. No están acostumbrados a pagar, pero están abiertos a hacerlo si la aplicación resuelve sus problemas principales (organización, ahorro de tiempo, mejora de rendimiento) de manera evidente y a un costo que se ajuste a su presupuesto como estudiantes.

**Insight**: Aunque los estudiantes universitarios muestran una baja disposición inicial a pagar por herramientas académicas, sí reconocen el valor tangible que tendría una solución capaz de reducir su nivel de estrés, optimizar su tiempo y contribuir a mejorar su rendimiento académico. Esta percepción indica que su decisión de pago no está condicionada únicamente por el precio, sino por el impacto real que la herramienta pueda generar en su bienestar y resultados. En ese sentido, se evidencia una oportunidad estratégica para implementar un modelo freemium, en el que las funciones básicas sean accesibles de forma gratuita, mientras que los beneficios avanzados —como estadísticas personalizadas, recordatorios inteligentes o integración con otras plataformas— puedan ofrecerse a bajo costo. Este enfoque permite captar a un público amplio, generar confianza y luego incentivar la conversión hacia planes premium a través del valor percibido.

---

### Conclusión para la Construcción del Arquetipo
El análisis estadístico de las entrevistas revela un perfil de segmento muy coherente y con necesidades claramente identificadas:
- El Arquetipo Principal es un estudiante universitario de 20-21 años que forma grupos de estudio para preparar exámenes y cursos difíciles.  
- Sus mayores frustraciones (100% de coincidencia) son la logística, las distracciones y el desorden que generan las herramientas de comunicación generalistas.  
- Valoran profundamente (100% de coincidencia) la organización, la comunicación enfocada y la planificación integrada.  
- Su disposición al pago no es nula, pero es pragmática: necesitan ver resultados claros (ahorro de tiempo, menos estrés, mejores notas) a un precio muy competitivo.  

<br>
<br>

### Segmento 2: Estudiantes de secundaria o preparatoria
**Tamaño de la Muestra (n):** 2 entrevistas  
**Base de Cálculo:** Todas las estadísticas y porcentajes se calculan sobre la base de las 2 entrevistas realizadas. Cada entrevistado representa el 50% del segmento analizado.

---

#### 1. Análisis de Características Objetivas (Datos Demográficos y Observables)

| Característica              | Luciana (50%) | Mariana (50%) | Análisis y Sustento |
|-----------------------------|---------------|---------------|---------------------|
| Edad                        | 15 años       | 14 años       | Ambos entrevistados se encuentran en el rango etario típico de estudiantes de secundaria. |
| Nivel de estudio            | Secundaria    | Secundaria    | El segmento está definido por su nivel educativo, lo que implica dinámicas de trabajo y supervisión específicas. |
| Frecuencia de estudio grupal| Proyectos escolares | Trabajos extensos | La formación de grupos es reactiva, impulsada por requisitos específicos de sus tareas y proyectos académicos. |
| Dispositivo principal       | Laptop        | Celular       | Prefieren la multifuncionalidad. El celular es práctico y siempre a mano, mientras que el computador/laptop se prefiere para trabajos más profundos. |
| Herramienta actual principal| WhatsApp      | WhatsApp      | Coincidencia total en el uso de WhatsApp como herramienta principal de coordinación, a pesar de reconocer sus limitaciones. |

---

#### 2. Análisis de Características Subjetivas (Necesidades, Dolores y Motivaciones)

**a. Desafíos y Dolores Principales en el Estudio Grupal (¿Qué problemas enfrentan?)**

| Dolor                        | Manifestación en las Entrevistas |
|------------------------------|----------------------------------|
| Desigualdad en la Colaboración | "No todos los compañeros colaboran de la misma forma" (L), "algunos compañeros se distraen o no cumplen" (M). |
| Limitaciones de las Herramientas Actuales | "WhatsApp no siempre es clara ni suficiente para organizarse" (L), "debería integrar todo en un mismo lugar" (M). |
| Problemas de Distracción y Enfoque | Implícito en la falta de colaboración (L), "algunos compañeros se distraen" (M). |

**Sustento:** Las dificultades de colaboración y las limitaciones de WhatsApp son dolores universales (100%) para este segmento. La dinámica de grupo desigual es su principal desafío interpersonal.

**Insight:** Los estudiantes de secundaria necesitan un espacio controlado que limite distracciones y organice automáticamente el contenido académico.

---

**b. Comportamiento Actual y Herramientas Utilizadas (¿Qué usan ahora?)**

| Herramienta/Comportamiento | Manifestación en las Entrevistas |
|-----------------------------|----------------------------------|
| Uso de WhatsApp como Eje   | Usan WhatsApp para coordinar (L, M). |
| Reconocimiento de su Insuficiencia | Ambas critican abiertamente a WhatsApp por no ser una herramienta adecuada para la organización del trabajo estudiantil. |

**Sustento:** Existe una coincidencia del 100% en el uso de una herramienta que reconocen como insuficiente. Esto indica una necesidad no satisfecha y una oportunidad clara para una solución diseñada para su contexto.

**Insight:** La dependencia de una sola herramienta informal muestra que no han explorado alternativas; esto abre la oportunidad de introducir una plataforma sencilla pero académicamente enfocada.

---

**c. Necesidades y Expectativas Deseadas (¿Qué solución buscan?)**

| Necesidad                 | Manifestación en las Entrevistas |
|----------------------------|----------------------------------|
| Integración y Centralización | "Integrar todo en un mismo lugar: chat, calendario, recordatorios" (M). "Diferentes métodos de aprendizaje" (L). |
| Motivación y Gamificación   | "Ofrecer motivación... recompensas o logros" (L), "recompensas por participación" (M). |
| Diseño Juvenil y Atractivo  | "Diseño juvenil y divertido" (L), "diseño juvenil y atractivo" (M). |
| Funciones de Organización   | "Recordatorios" (M), "organizarse" (L). |
| Aprobación Adulta           | "Sus padres y profesores apoyarían el uso..." (M). |

**Sustento:** Las necesidades son absolutamente unánimes (100%) en los aspectos clave: quieren una herramienta integrada, que los motive mediante gamificación y que tenga un diseño que les hable directamente (juvenil). La mención a la aprobación adulta (50%) sugiere que la validación de figuras de autoridad es un factor positivo para al menos una parte del segmento.

**Insight:** Los estudiantes de secundaria buscan una solución práctica que los ayude a organizarse y mantenerse enfocados sin sentirlo como “otra carga escolar”.

---

**d. Disposición al Pago (¿Invertirían en una solución?)**

| Aspecto                   | Manifestación en las Entrevistas |
|----------------------------|----------------------------------|
| Preferencia por Gratuidad  | "Le gustaría que la aplicación sea gratuita" (L), "debería ser gratuita o de bajo costo" (M). |
| Modelo Aceptable: Freemium con Gamificación | "Recompensas o logros" (L), "recompensas por participación" (M). |

**Sustento:** Existe una preferencia universal (100%) por aplicaciones gratuitas. Su disposición a interactuar con mecanismos de recompensas y logros (100%) indica que un modelo freemium (gratuito con funcionalidades premium o sistemas de recompensas integrados) sería el camino más efectivo para este segmento, que probablemente depende de subsidios de padres o la institución educativa.

**Insight:** Para este segmento, el modelo gratuito es esencial; un esquema freemium puede funcionar solo si el plan base cubre sus necesidades básicas.

---

### Conclusión para la Construcción del Arquetipo
El análisis estadístico de las entrevistas revela un perfil de segmento muy claro y consistente:  
- El Arquetipo Principal es una estudiante de secundaria/preparatoria que se agrupa obligatoriamente por proyectos escolares y sufre por la desigual participación de sus compañeros.  
- Sus mayores frustraciones (100% de coincidencia) son la falta de colaboración y el uso de herramientas inadecuadas (WhatsApp) que no resuelven sus necesidades de organización.  
- Valoran enormemente (100% de coincidencia) una solución que sea integral (todo-en-uno), motivadora (gamificación) y con un diseño atractivo y juvenil que se diferencie de las herramientas "aburridas" de los adultos.  
- Su disposición al pago es nula o muy baja. El modelo de negocio debe girar en torno a la gratuidad, potencialmente con publicidad contextual, o un modelo freemium donde la escuela o los padres paguen por una licencia grupal o funcionalidades avanzadas de seguimiento para los docentes.

<br>
<br>

### Segmento 3: Estudiantes autodidactas
**Tamaño de la Muestra (n):** 3 entrevistas  
**Base de Cálculo:** Todas las estadísticas y porcentajes se calculan sobre la base de las 3 entrevistas realizadas. Cada entrevistado representa aproximadamente el 33.3% del segmento analizado.

---

#### 1. Análisis de Características Objetivas (Datos Demográficos y Observables)

| Característica        | Fiorella (33.3%) | Lily (33.3%) | Carlos (33.3%) | Análisis y Sustento |
|-----------------------|------------------|--------------|----------------|---------------------|
| Modalidad de Aprendizaje | Autodidacta | Autodidacta | Autodidacta | La característica definitoria del segmento es el aprendizaje auto-gestionado y no formal. |
| Dispositivo Principal | Celular | Celular | Celular | Coincidencia total en la preferencia y practicidad del dispositivo móvil para estudiar en cualquier momento y lugar. |
| Fuentes de Estudio    | YouTube, blogs, PDF | YouTube, artículos web | Cursos online, artículos | Todos utilizan predominantemente recursos gratuitos y disponibles en internet (videos, artículos, cursos). |

---

#### 2. Análisis de Características Subjetivas (Necesidades, Dolores y Motivaciones)

**a. Desafíos y Dolores Principales (¿Qué problemas enfrentan?)**

| Dolor                    | Manifestación en las Entrevistas |
|---------------------------|----------------------------------|
| Sobrecarga de Información | "Exceso de información disponible" (F), "dificultad para filtrar información útil" (L), "sobrecarga de información" (C). |
| Falta de Constancia y Rutina | "Falta de constancia", "ausencia de un horario fijo" (F), "constancia en la rutina" (L), "falta de tiempo... rutina estable" (C). |
| Aislamiento y Necesidad de Comunidad | "Importante conectarse con otras personas" (F), "importancia de la comunidad" (L). |
| Falta de Tiempo          | "Falta de tiempo" (Carlos). |

**Sustento:** Los dolores son muy consistentes. La sobrecarga de información y la dificultad para mantener una rutina son problemas universales (100%) para este segmento. La necesidad de comunidad es mayoritaria (66.7%), pero no unánime, lo que sugiere la existencia de sub-perfiles dentro del segmento.

**Insight:** Los autodidactas no fracasan por falta de recursos, sino por exceso de ellos y por falta de estructura. Una solución que organice y filtre puede ser más valiosa que más contenido.

---

**b. Comportamiento Actual y Herramientas Utilizadas (¿Qué usan ahora?)**

| Herramienta/Comportamiento | Manifestación en las Entrevistas |
|-----------------------------|----------------------------------|
| Uso de Plataformas de Contenido Gratuito | YouTube, blogs (F, L, C) |
| Búsqueda de Organización   | "Aplicaciones para tomar notas y organizarse" (L), "resúmenes organizados" (F). |
| Valoración de la Aplicabilidad | "Contenido... aplicable profesionalmente" (C). |

**Sustento:** El segmento es 100% dependiente de contenido online gratuito. Además, una mayoría significativa (66.7%) actively busca métodos y herramientas para organizar su aprendizaje de manera efectiva.

**Insight:** Su principal reto no es el acceso al contenido, sino cómo darle continuidad. Necesitan una plataforma que transforme consumo desordenado en aprendizaje planificado.

---

**c. Necesidades y Expectativas Deseadas (¿Qué solución buscan?)**

| Necesidad                 | Manifestación en las Entrevistas |
|----------------------------|----------------------------------|
| Planificación y Recordatorios | "Recordatorios, una agenda organizada" (F), "agenda con recordatorios" (L), "agendas de estudio con recordatorios" (C). |
| Comunidad y Chat en Tiempo Real | "Chat en tiempo real" (F), "chat en tiempo real para conectarse" (L). |
| Seguimiento de Progreso   | "Medir su progreso" (F), "seguimiento de progreso" (C). |
| Conexión con Expertos     | "Acceso a expertos" (F, L), "conversar con alguien con más experiencia" (C). |

**Sustento:** La necesidad de herramientas de planificación (agenda/recordatorios) y la valoración del acceso a expertos son universales (100%). Otras necesidades como la comunidad, el seguimiento de progreso y un diseño simple son mayoritarias (66.7%), lo que las convierte en críticas.

**Insight:** Más allá de estudiar solos, buscan sentirse acompañados y guiados. Una herramienta que combine agenda + comunidad + mentoría tiene alto potencial de adopción.

---

**d. Disposición al Pago (¿Invertirían en una solución?)**

| Aspecto                   | Manifestación en las Entrevistas |
|----------------------------|----------------------------------|
| Disposición Condicional    | Los tres expresaron que pagarían bajo condiciones específicas. |
| Razón Principal para Pagar: Acceso a Expertos/Contenido Premium | "Acceso a expertos" (F, L), "contenido de calidad y aplicable" (C). |
| Condición: Precio Razonable | "A un precio razonable" (F), implícito en L y C. |

**Sustento:** Existe una disposición unánime (100%) a considerar una versión premium, pero está supeditada a que la aplicación entregue valor tangible en forma de contenido exclusivo de calidad y acceso a orientación experta. Son sensibles al precio, pero priorizan la calidad.

**Insight:** Para este segmento, el valor no está en la plataforma en sí, sino en el capital humano y el contenido exclusivo. Están dispuestos a pagar si sienten que acceden a algo que no consiguen gratis.

---

### Conclusión para la Construcción del Arquetipo
El análisis estadístico de las entrevistas revela dos sub-perfiles o arquetipos dentro del segmento autodidacta:  

- **El Autodidacta Social (66.7%)**: Representado por Fiorella y Lily. Su motivación y aprendizaje se ven fuertemente potenciados por la comunidad. Necesita sentirse parte de un grupo, compartir dudas y avances para mantenerse motivado y superar bloqueos.  
- **El Autodidacta Pragmático (33.3%)**: Representado por Carlos. Su foco principal es la eficiencia y la aplicabilidad del conocimiento. Aunque puede ver valor en contactar con expertos, la interacción grupal no es una prioridad. Valora el contenido de calidad y las herramientas que se adaptan a su limitado tiempo.  

<br>
<br>

## Segmento 4: Docentes

**Tamaño de la Muestra (n):** 2 entrevistas
**Base de Cálculo:** Todas las estadísticas y porcentajes se calculan sobre la base de las 2 entrevistas realizadas. Cada entrevistado representa el **50% del segmento**.

---

### 1. Análisis de Características Objetivas (Datos Demográficos y Observables)

| Característica        | JM (50%)            | M (50%)                    | Análisis y Sustento                                                                                   |
| --------------------- | ------------------- | -------------------------- | ----------------------------------------------------------------------------------------------------- |
| Nivel Educativo       | Secundaria          | Secundaria                 | Ambos ejercen en el mismo nivel, lo que genera un contexto de uso muy específico.                     |
| Rol                   | Docente             | Docente                    | El segmento está definido por su rol de facilitadores del aprendizaje.                                |
| Contexto Geográfico   | Monsefú (Provincia) | Lima (Capital)             | Incluyen realidades socioeconómicas distintas, pero con necesidades comunes.                          |
| Herramientas Actuales | Classroom, Meet     | Classroom, Drive, WhatsApp | Coincidencia total en el uso de Google Classroom, pero complementado con apps externas no integradas. |

---

### 2. Análisis de Características Subjetivas (Necesidades, Dolores y Motivaciones)

**a. Desafíos y Dolores Principales**

| Dolor                                     | Manifestación en las Entrevistas                                                              |
| ----------------------------------------- | --------------------------------------------------------------------------------------------- |
| Falta de Colaboración e Integración       | “No fomentan del todo el trabajo colaborativo” (JM); “dispersos en varias plataformas” (M).   |
| Dificultad de Seguimiento y Monitoreo     | “Monitorear el progreso” (JM); “dificulta el seguimiento de la participación” (M).            |
| Problemas de Coordinación y Participación | “Baja participación, complejidad de coordinar horarios” (JM); implícito en la dispersión (M). |

**Sustento:** Los dolores son universales (100%). Todos refieren a fragmentación y baja colaboración.

**Insight:** El verdadero dolor del docente no es la enseñanza en sí, sino la logística digital. Necesitan una herramienta que reduzca complejidad y devuelva tiempo para enseñar.

---

**b. Comportamiento Actual y Herramientas Utilizadas**

| Herramienta/Comportamiento                 | Manifestación en las Entrevistas                                            |
| ------------------------------------------ | --------------------------------------------------------------------------- |
| Uso de Múltiples Plataformas no Integradas | Classroom + Meet (JM); Classroom + Drive + WhatsApp (M).                    |
| Reconocimiento de Limitaciones             | Ambos señalan la falta de colaboración e integración como problema crítico. |

**Sustento:** Coincidencia total (100%) en que el ecosistema actual es un “parche” poco funcional.

**Insight:** No es que falten herramientas, es que ninguna está pensada integralmente para educación. Aquí hay una oportunidad de diferenciarse con centralización real.

---

**c. Necesidades y Expectativas Deseadas**

| Necesidad                      | Manifestación en las Entrevistas                                                                |
| ------------------------------ | ----------------------------------------------------------------------------------------------- |
| Centralización y Organización  | “Compartir materiales” (JM); “centralice materiales, organice grupos” (M).                      |
| Monitoreo y Reportes           | “Monitorear progreso mediante reportes” (JM); “estadísticas claras de progreso” (M).            |
| Diferenciación de Roles        | “Roles docente-estudiante” (JM); “diferenciar el rol docente” (M).                              |
| Comunicación Integrada         | “Retroalimentación” (JM); “integración de chat y videollamadas” (M).                            |
| Seguridad, Privacidad y Diseño | “Diseño amigable, altos estándares de seguridad” (JM); “juvenil pero profesional y seguro” (M). |

**Sustento:** Necesidades unánimes (100%). Buscan una **plataforma integral, segura y con diferenciación de roles**.

**Insight:** El docente busca una plataforma que funcione como “aula digital completa”: un espacio que organice, mida y facilite, más que otro repositorio de tareas.

---

**d. Modelo de Negocio y Disposición al Pago**

| Aspecto                    | Manifestación en las Entrevistas                                   |
| -------------------------- | ------------------------------------------------------------------ |
| Valor Percibido            | Todas las funcionalidades clave (centralización, reportes, roles). |
| Experiencia del Estudiante | “Diseño amigable” (JM); “diseño que motive a estudiantes” (M).     |

**Sustento:** Aunque no se declara explícitamente el pago, el **valor percibido es muy alto (100%)**. La adopción dependerá de que la solución sea robusta para el docente y atractiva para el alumno.

**Insight:** Aunque no declaran disposición clara al pago, si la plataforma resuelve su dolor crítico y mejora la experiencia del estudiante, las instituciones podrían adoptarla sin resistencia.

---

### Conclusión para la Construcción del Arquetipo

* **Arquetipo Principal:** Docente de secundaria que busca fomentar la colaboración y monitorear el progreso en un ecosistema fragmentado.
* **Dolores universales (100%):** dispersión de plataformas, baja colaboración, dificultad de seguimiento.
* **Valoran (100%):** una plataforma **todo-en-uno**, con **centralización, roles diferenciados, comunicación integrada, reportes y seguridad confiable**.
* **Criterio de adopción:** robustez para el docente y facilidad/atractivo para el estudiante.

---

<br>
<br>

## 2.3. Needfinding

### 2.3.1. User Personas

Los artefactos de **User Persona** presentados a continuación sintetizan los hallazgos clave obtenidos del análisis de entrevistas y del benchmarking competitivo. Su propósito es transformar los datos crudos en representaciones empáticas y tangibles de nuestros usuarios objetivo, sirviendo como referentes constantes para la toma de decisiones de diseño y estrategia.

**Características consideradas en su construcción:**

* **Pain Points y Necesidades:** Se priorizaron los desafíos recurrentes, como la desorganización, la dificultad de coordinación y las distracciones en herramientas actuales.
* **Comportamiento y Contexto de Uso:** Se analizó cómo, cuándo y por qué los estudiantes forman grupos de estudio, identificando patrones como el uso intensivo antes de exámenes y en cursos específicos.
* **Herramientas y Brechas:** Se mapeó el ecosistema de aplicaciones actualmente utilizadas (WhatsApp, Drive, etc.) y las deficiencias detectadas, que definen la oportunidad para nuestra solución.
* **Sensibilidad al Precio y Valor Percibido:** Se incluyó la disposición condicional a pagar por una solución que demuestre valor claro en **ahorro de tiempo y reducción de estrés**, siempre que sea accesible económicamente.

**Enlace:** [Clic aquí](https://www.canva.com/design/DAGP0hCxEz8/Pn2qn9YD-xUK92feuYKBMA/edit?utm_content=DAGP0hCxEz8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

## Segmento 1: Estudiantes universitarios o de instituto

![User Persona 1](assets/images/C2/user_personas/up1.jpg)

## Segmento 2: Estudiantes de secundaria o preparatoria

![User Persona 2](assets/images/C2/user_personas/up2.jpg)

## Segmento 3: Estudiantes autodidactas

![User Persona 3](assets/images/C2/user_personas/up3.jpg)

## Segmento 4: Docentes

![User Persona 4](assets/images/C2/user_personas/up4.jpg)

<br>
<br>

## 2.3.2. User Task Matrix

| User Task                                                                             | Segmento 1 <br> (Frecuencia / Importancia) | Segmento 2 <br> (Frecuencia / Importancia) | Segmento 3 <br> (Frecuencia / Importancia) | Segmento 4 <br> (Frecuencia / Importancia) |
| ------------------------------------------------------------------------------------- | ------------------------------------------ | ------------------------------------------ | ------------------------------------------ | ------------------------------------------ |
| Coordinar horarios y reuniones de estudio/trabajo. | Alta / Alta | Media / Media | Baja / Baja | Media / Media |
| Compartir y organizar materiales de estudio (apuntes, links, archivos).               | Alta / Alta | Alta / Alta | Alta / Alta | Alta / Alta  |
| Realizar seguimiento del progreso y cumplimiento de tareas individuales.              | Media / Alta | Media / Alta  | Alta / Alta  | Alta / Alta  |
| Comunicarse de forma síncrona (videollamadas) o asíncrona (chat) con el grupo/mentor. | Alta / Media | Alta / Media | Baja / Media | Media / Media  |
| Establecer y dar seguimiento a metas y plazos de aprendizaje personal/grupal.         | Media / Media | Baja / Baja  | Alta / Alta  | Alta / Alta  |
| Mantener la motivación y el engagement con el estudio o el proyecto.                  | Media / Media  | Alta / Alta  | Alta / Alta  | Alta / Alta  |
| Evaluar la contribución y participación de los miembros de un grupo.                  | Alta / Alta | Alta / Alta  | N/A  | Alta / Alta    |
| Buscar y curar contenido de estudio confiable y de calidad.                           | Media / Media   | Baja / Baja | Alta / Alta  | Alta / Alta   |
| Garantizar un entorno seguro y con roles claros para la colaboración.                 | Media / Baja | Baja / Baja  | Baja / Baja  | Alta / Alta  |

---

### Análisis del User Task Matrix

El análisis revela coincidencias cruciales y diferencias notorias entre los segmentos, lo que guiará el diseño de las **funcionalidades core** y **secundarias** de la aplicación.

**Tareas Críticas (Alta Frecuencia & Alta Importancia):**

* **Task #2 (Compartir y organizar materiales):** Es la tarea más crítica y universal en todos los segmentos. Nuestra solución debe ofrecer un **repositorio centralizado, robusto e intuitivo**.
* **Task #7 (Evaluar contribución):** Vital para universitarios, escolares y docentes. Implica la necesidad de **analíticas de participación** o herramientas de seguimiento de contribuciones.
* **Task #3 (Seguimiento de progreso) y Task #5 (Establecer metas):** De alta importancia para autodidactas y docentes; media para universitarios. Esto sugiere que la **planificación y tracking** deben ser adaptativas según el contexto (individual vs. grupal).
* **Task #6 (Mantener motivación):** Alta en tres segmentos, aunque con motivaciones distintas (gamificación para escolares, progreso tangible para autodidactas, engagement grupal para docentes).

**Principales Diferencias:**

* **Coordinar (Task #1):** Crítico en universidad, menos relevante en secundaria y casi irrelevante para autodidactas.
* **Comunicación (Task #4):** Frecuente pero de importancia media; debe integrarse pero no ser el eje central.
* **Curar contenido (Task #8):** Core para autodidactas y docentes, no prioritario para estudiantes tradicionales.
* **Seguridad y roles (Task #9):** Casi exclusivo de docentes, quienes necesitan mantener **control y autoridad** en el entorno digital.

<br>
<br>

### 2.3.3. User Journey Mapping

**Enlace:** [Clic aquí](https://www.canva.com/design/DAGQAPY8rrQ/c860ppQIoPP1z4IgUXKyrQ/edit?utm_content=DAGQAPY8rrQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

Esta sección ilustra la experiencia end-to-end actual (As-Is) de nuestros User Personas al intentar formar y gestionar grupos de estudio sin la existencia de nuestra solución, SkillShare. El propósito de estos mapas es visualizar de manera clara y empática las interacciones, puntos de dolor, emociones y oportunidades de mejora que surgen a lo largo de todo el proceso, desde que identifican la necesidad de estudiar en grupo hasta que concluyen su proyecto. Estos journey maps validan los pain points identificados y sirven como base fundamental para diseñar la experiencia futura (To-Be).

---

#### Primer segmento: Allison Rivera – Estudiantes universitarios o de instituto

![User Journey Mapping 1](assets/images/C2/user_journey_mapping/ujm1.jpg)

**Explicación**
El journey de María García refleja los desafíos de los estudiantes universitarios al buscar colaboración académica. Actualmente, enfrenta procesos desorganizados y dependientes del azar, como redes sociales y conversaciones informales.

* **Reconocimiento:** se da cuenta de que estudiar sola no es suficiente para temas complejos, especialmente en materias densas.
* **Investigación:** enfrenta la falta de canales estructurados para encontrar compañeros compatibles, con métodos ineficientes que no garantizan calidad.
* **Decisión:** se arriesga al unirse a grupos sin conocer el compromiso o la compatibilidad, lo que genera frustración.
* **Uso Continuo:** revela problemas como dificultades para coordinar horarios, falta de herramientas colaborativas y ausencia de estructura que mantenga el enfoque.
* **Logros y Mantenimiento:** aunque obtiene beneficios académicos, carece de herramientas de evaluación para optimizar la experiencia y mantener grupos efectivos.

Este journey resalta oportunidades clave para SkillShare, como identificación automatizada de necesidades, herramientas colaborativas avanzadas y sistemas de evaluación continua.

---

#### Segundo segmento: Luciana DoCampo – Estudiantes de secundaria

![User Journey Mapping 2](assets/images/C2/user_journey_mapping/ujm2.jpg)

**Explicación**
El journey de Luciana DoCampo refleja los retos de los estudiantes de secundaria de la Generación Z al trasladar sus habilidades sociales al ámbito académico colaborativo.

* **Reconocimiento:** Luciana reacciona negativamente a los trabajos grupales debido a experiencias frustrantes, compartiendo su frustración con sus amigas.
* **Investigación:** usa herramientas digitales como Instagram y conversaciones cara a cara, pero estas no son efectivas para encontrar colaboradores académicos, lo que la lleva a elegir grupos por afinidad social, no por compatibilidad académica.
* **Decisión:** toma decisiones rápidas basadas en factores sociales, creando grupos cómodos pero desorganizados, sin conocer los estilos de trabajo de sus compañeros.
* **Uso Continuo:** la incompatibilidad entre las herramientas sociales que usa y las necesidades académicas genera distracción, desorganización e inequidad en la carga de trabajo.
* **Logros y Mantenimiento:** aunque obtiene buenos resultados, el proceso le causa estrés y fatiga, y la falta de reconocimiento dificulta mejorar en futuras colaboraciones.

Este journey resalta oportunidades para SkillShare: gamificación, reconocimiento visual, herramientas organizacionales adaptadas a sus hábitos digitales y sistemas que aseguren un trabajo colaborativo justo.

---

#### Tercer segmento: Carlos Wolf – Profesionales autodidactas

![User Journey Mapping 1](assets/images/C2/user_journey_mapping/ujm3.jpg)

**Explicación**
El journey de Carlos Wolf muestra los desafíos de los profesionales autodidactas en un entorno laboral competitivo, con limitaciones de tiempo y atención.

* **Reconocimiento:** su motivación es práctica, impulsada por necesidades profesionales, lo que genera presión sobre su aprendizaje.
* **Investigación:** la abundancia de recursos lo sobrecarga, gastando demasiado tiempo evaluando opciones en lugar de aprender.
* **Decisión:** toma decisiones basadas en criterios prácticos, pero la falta de información lo lleva a elegir múltiples recursos, aumentando la dispersión.
* **Uso Continuo:** la falta de un sistema unificado para gestionar su aprendizaje genera frustración y dificulta medir su progreso.
* **Logros y Mantenimiento:** aunque adquiere conocimientos, la falta de estructura y métricas claras limita la aplicación práctica y el impacto de su esfuerzo.

Este journey resalta oportunidades para SkillShare: curaduría inteligente, gestión móvil-first, microlearning y métricas que conecten el aprendizaje con resultados profesionales.

---

#### Cuarto segmento: Merly Salón – Docentes emprendedores

![User Journey Mapping 1](assets/images/C2/user_journey_mapping/ujm4.jpg)

**Explicación**
El journey de Merly Salón refleja los desafíos de los docentes emprendedores que buscan monetizar su experiencia educativa a través de grupos de estudio pagados.

* **Reconocimiento:** Merly experimenta una tensión entre su vocación educativa y la necesidad de generar ingresos, lo que genera conflicto sobre la comercialización de la educación.
* **Investigación:** enfrenta la falta de recursos específicos para docentes emprendedores, lo que crea incertidumbre y lleva a decisiones subóptimas.
* **Decisión:** toma decisiones empresariales sin experiencia, lo que complica la gestión de precios, contenido, plataformas y marketing.
* **Uso Continuo:** revela la sobrecarga de roles: educadora, administradora y gestora tecnológica. Esto reduce la calidad educativa y la viabilidad económica debido a la falta de herramientas integradas y la gestión manual de tareas.
* **Logros y Mantenimiento:** aunque obtiene ingresos, la falta de métricas claras y herramientas de escalamiento dificulta el crecimiento sostenible.

<br>
<br>

### 2.3.4. Empathy Mapping

**Enlace:** [Clic aquí](https://www.canva.com/design/DAGQBbdACcc/WlnrXEAvgDj_dwFa25M9Kg/edit?utm_content=DAGQBbdACcc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

**Segmento 1: Estudiantes universitarios o de instituto**

![Empathy Mapping 1](assets/images/C2/empathy_mapping/em1.jpg)

**Segmento 2: Estudiantes de secundaria o preparatoria**

![Empathy Mapping 1](assets/images/C2/empathy_mapping/em2.jpg)

**Segmento 3: Estudiantes autodidactas**

![Empathy Mapping 1](assets/images/C2/empathy_mapping/em3.jpg)

**Segmento 4: Docentes**

![Empathy Mapping 1](assets/images/C2/empathy_mapping/em4.jpg)

<br>
<br>

### 2.3.5. Ubiquitous Language

| **Término (Inglés)** | **Definición** |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Study Group (Grupo de Estudio)**                  | Conjunto organizado de estudiantes o aprendices que se reúnen regularmente para estudiar temas específicos, intercambiar conocimientos y apoyarse mutuamente en su proceso de aprendizaje.     |
| **Facilitator (Facilitador)**   | Persona que guía y coordina las actividades de aprendizaje dentro de un grupo de estudio, proporcionando estructura, contenido educativo y orientación metodológica. Puede ser un docente, tutor o experto en la materia. |
| **Learner (Aprendiz)**                              | Individuo que participa activamente en un proceso de aprendizaje, ya sea como estudiante formal, autodidacta o profesional en desarrollo continuo.                                                                        |
| **Study Session (Sesión de Estudio)**               | Período estructurado de tiempo dedicado al aprendizaje colaborativo donde los miembros de un grupo trabajan juntos en temas específicos, realizan actividades educativas o resuelven problemas académicos.     |
| **Learning Path (Ruta de Aprendizaje)**             | Secuencia organizada y progresiva de contenidos, actividades y objetivos de aprendizaje diseñada para guiar a los participantes desde un nivel inicial hasta el dominio de un tema específico.                            |
| **Peer Learning (Aprendizaje entre Pares)**         | Proceso educativo donde individuos del mismo nivel académico o profesional se enseñan y aprenden mutuamente, compartiendo experiencias y conocimientos de manera horizontal.    |
| **Learning Analytics (Analíticas de Aprendizaje)**  | Medición, recopilación y análisis de datos sobre el progreso, participación y rendimiento de los aprendices para optimizar la experiencia educativa y tomar decisiones informadas.                                        |
| **Educational Content (Contenido Educativo)**       | Material didáctico, recursos de aprendizaje, ejercicios, lecturas y cualquier información estructurada utilizada para facilitar el proceso de enseñanza-aprendizaje dentro de los grupos de estudio. |
| **Learning Objective (Objetivo de Aprendizaje)**    | Meta específica y medible que define qué conocimientos, habilidades o competencias deben adquirir los participantes al completar una actividad, sesión o programa de aprendizaje.                                         |
| **Study Schedule (Cronograma de Estudio)**          | Planificación temporal que organiza las sesiones de estudio, establece fechas límite y coordina la disponibilidad de los miembros del grupo para maximizar la participación y efectividad. |
| **Learning Progress (Progreso de Aprendizaje)**     | Avance medible de un aprendiz hacia el cumplimiento de sus objetivos educativos, evaluado a través de métricas como completación de actividades, mejora en evaluaciones y desarrollo de competencias.                     |
| **Study Material (Material de Estudio)**            | Recursos educativos específicos utilizados durante las sesiones de aprendizaje colaborativo, incluyendo documentos, presentaciones, ejercicios, videos y cualquier contenido relevante para los temas de estudio. |
| **Group Dynamics (Dinámicas Grupales)**             | Patrones de interacción, comunicación y colaboración que emergen entre los miembros de un grupo de estudio, incluyendo roles, liderazgo, participación y resolución de conflictos.  |
| **Learning Engagement (Compromiso de Aprendizaje)** | Nivel de participación activa, motivación y dedicación que demuestra un aprendiz en sus actividades educativas y interacciones grupales.  |
| **Skill Development (Desarrollo de Habilidades)**   | Proceso mediante el cual los participantes adquieren, mejoran y aplican competencias específicas a través de la práctica colaborativa y el aprendizaje estructurado.  |
| **Educational Assessment (Evaluación Educativa)**   | Proceso sistemático de medición y valoración del aprendizaje, progreso y desempeño de los participantes en relación con los objetivos educativos establecidos. |
| **Learning Community (Comunidad de Aprendizaje)**   | Red de individuos unidos por intereses educativos comunes que comparten conocimientos, experiencias y recursos para el beneficio mutuo y el crecimiento colectivo. |

---


<br>
<br>
<br>
<br>
<br>
<br>

<!--
   CAPÍTULO 3
-->

# 3. Capítulo III: Requirements Specification

## 3.1. User Stories


### Epics

| **Epic ID** | **Epic Name** |
|--------------|----------------|
| EP-01 | Autenticación y gestión de perfil |
| EP-02 | Grupos de estudio y colaboración académica |
| EP-03 | Comunicación y herramientas colaborativas |
| EP-04 | Gamificación y experiencia para estudiantes de secundaria |
| EP-05 | Aprendizaje autodidacta y progreso personal |
| EP-06 | Recursos y analítica docente |
| EP-07 | Experiencia del visitante y landing page |

### User Stories

| USID        | US-01               |
|-------------|---------------------|
| Epic ID     | EP-01               |
| Priority    | 8                   |
| User        | Visitante (Cliente potencial) |
| Title       | Registrar usuario |
| Descripción | Como visitante quiero registrarme desde la landing page para crear mi cuenta en la plataforma SkillShare. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Navegación a la creación de cuenta**<br>Dado que el visitante está en nuestra landing page<br>Cuando selecciona la opción para registrarse<br>Entonces el sistema le presenta la pantalla de creación de cuenta<br><br>**Escenario 02: Registro exitoso (Ruta principal)**<br>Dado que el visitante ha proporcionado información válida en la pantalla de creación de cuenta<br>Cuando confirma su solicitud de registro<br>Entonces el sistema debe validar la información ingresada<br>Y registrar los datos del usuario de forma segura<br>Y mostrar un mensaje de confirmación en pantalla<br>Y enviar un email de verificación a la dirección registrada<br><br>**Escenario 03: Registro fallido (Datos inválidos)**<br>Dado que el visitante está en la pantalla de creación de cuenta<br>Cuando intenta confirmar el registro con datos inválidos o incompletos<br>Entonces el sistema debe mostrar mensajes de error claros indicando los campos a corregir |

<br>
<br>

| USID        | US-02               |
|-------------|---------------------|
| Epic ID     | EP-07               |
| Prioridad   | 5                   |
| User        | Visitante (Cliente potencial) |
| Title       | Ver banner "Cómo funciona" |
| Descripción | Como visitante quiero ver en la landing page un resumen visual en 3 pasos de cómo usar SkillShare para entender rápidamente el flujo de la aplicación. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Visualización del resumen del proceso**<br>Dado que el visitante accede a la página principal<br>Cuando navega hasta el resumen de "Cómo funciona"<br>Entonces observa 3 pasos ilustrados con texto explicativo<br>Y tiene disponibles las opciones para "Ver demo" o "Registrarse"<br><br>**Escenario 02: Adaptación a móvil (Responsive)**<br>Dado que el visitante accede desde un dispositivo móvil<br>Cuando visualiza el resumen del proceso<br>Entonces el contenido se adapta y muestra de forma legible en la pantalla |

<br>
<br>

| USID        | US-03               |
|-------------|---------------------|
| Epic ID     | EP-07               |
| Prioridad   | 3                   |
| User        | Reproducir video demostrativo  |
| Title       | Reproducir video demostrativo  |
| Descripción | Como visitante quiero reproducir un video demo en la landing page para visualizar las funciones clave como grupos de estudio, chat y recursos compartidos. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Iniciar la reproducción del video**<br>Dado que el visitante se encuentra en el área del video demostrativo<br>Cuando inicia la reproducción del video<br>Entonces el video se carga y reproduce correctamente<br>Y no requiere la instalación de software adicional (plugins)<br><br>**Escenario 02: Interactuar con los controles del video**<br>Dado que el video está reproduciéndose<br>Cuando el visitante interactúa con los controles (pausa, adelanta, volumen)<br>Entonces el reproductor responde adecuadamente<br><br>**Escenario 03: Finalización del video**<br>Dado que el visitante completa la visualización del video<br>Cuando la reproducción termina<br>Entonces se le muestran opciones de siguiente paso (ej. "Probar gratis", "Ver más funciones") |

<br>
<br>

| USID       | US-04               |
|-------------|---------------------|
| Epic ID     | EP-07               |
| Prioridad   | 5                   |
| User        | Visitante (Cliente potencial)  |
| Title       | Visualizar lista de funcionalidades  |
| Descripción | Como visitante quiero ver las funcionalidades principales organizadas visualmente para evaluar si el producto satisface mis necesidades de estudio colaborativo. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Revisión de funcionalidades clave**<br>Dado que el visitante navega por nuestra landing page<br>Cuando llega al área de funcionalidades<br>Entonces ve descripciones claras de las funciones clave (chat, videollamadas, recursos)<br>Y encuentra una opción clara y visible para iniciar su registro<br><br>**Escenario 02: Obtener más detalles de una funcionalidad**<br>Dado que el visitante está en el área de funcionalidades<br>Cuando selecciona una funcionalidad específica para ver más detalles<br>Entonces se muestra información adicional sobre esa función (texto o capturas de pantalla) |

<br>
<br>

| USID        | US-05               |
|-------------|---------------------|
| Epic ID     | EP-07               |
| Prioridad   | 3                   |
| User        | Visitante (Cliente potencial)  |
| Title       | Leer testimonios y casos de éxito |
| Descripción | Como visitante quiero leer testimonios de usuarios reales y ver estadísticas de éxito para generar confianza en la efectividad de la plataforma. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Revisar testimonios y casos de éxito**<br>Dado que el visitante está en el área de testimonios<br>Cuando lee los testimonios<br>Entonces ve la información del usuario (nombre, foto, institución)<br>Y puede seleccionar un testimonio para ver más detalles del caso de éxito<br><br>**Escenario 02: Revisar estadísticas de éxito**<br>Dado que el visitante revisa el área de estadísticas<br>Cuando observa los datos de éxito<br>Entonces ve métricas claras (ej. "95% mejora...") con sus fuentes o contexto |

<br>
<br>

| USID        | US-06               |
|-------------|---------------------|
| Epic ID     | EP-07               |
| Prioridad   | 5                   |
| User        | Visitante (Cliente potencial)  |
| Title       | Probar buscador |
| Descripción | Como visitante quiero ver cómo funciona la búsqueda de compañeros y grupos para entender la facilidad de conexión en la plataforma. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Visualizar la demostración del buscador**<br>Dado que el visitante navega hasta el área del buscador<br>Cuando observa la demostración visual (captura, video o demo)<br>Entonces comprende visualmente cómo funciona la búsqueda<br><br>**Escenario 02: Interactuar con la demo del buscador**<br>Dado que el visitante utiliza la demo interactiva del buscador<br>Cuando simula una búsqueda con términos de ejemplo<br>Entonces el sistema de demo muestra resultados de ejemplo relevantes<br><br>**Escenario 03: Proceder al registro desde el buscador**<br>Dado que el visitante ha entendido la funcionalidad del buscador<br>Cuando desea probar la función real<br>Entonces el sistema le ofrece una opción clara para iniciar su registro |

<br>
<br>

| USID        | US-07               |
|-------------|---------------------|
| Epic ID     | EP-07               |
| Prioridad   | 3                   |
| User        | Visitante (Cliente potencial)   |
| Title       | Enviar formulario de contacto |
| Descripción | Como visitante quiero usar un formulario de contacto intuitivo para enviar consultas específicas al equipo de SkillShare. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Envío exitoso de consulta**<br>Dado que el visitante ha proporcionado información válida (nombre, email, mensaje) en la pantalla de contacto<br>Cuando confirma el envío de la consulta<br>Entonces el sistema procesa la consulta<br>Y muestra un mensaje de confirmación en pantalla<br>Y envía un email automático de recepción al visitante<br><br>**Escenario 02: Envío fallido (Datos inválidos)**<br>Dado que el visitante está en la pantalla de contacto<br>Cuando intenta confirmar el envío con datos incompletos o inválidos<br>Entonces el sistema muestra mensajes de error claros indicando los campos a corregir<br><br>**Escenario 03: Validación de campos (en tiempo real)**<br>Dado que el visitante está en la pantalla de contacto<br>Cuando proporciona su nombre, email y mensaje<br>Entonces el sistema valida el formato de la información a medida que se ingresa (o al salir del campo) |

<br>
<br>

| USID        | US-08               |
|-------------|---------------------|
| Epic ID     | EP-07               |
| Prioridad   | 3                   |
| User        | Visitante (Cliente potencial)   |
| Title       | Consultar FAQ interactiva     |
| Descripción | Como visitante quiero acceder a preguntas frecuentes organizadas para resolver dudas comunes sin necesidad de contactar soporte. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Consultar una pregunta**<br>Dado que el visitante está en el área de Preguntas Frecuentes<br>Cuando selecciona una pregunta de la lista<br>Entonces la respuesta correspondiente se muestra de forma expandida<br><br>**Escenario 02: Buscar en Preguntas Frecuentes**<br>Dado que el visitante está en el área de Preguntas Frecuentes<br>Cuando ingresa términos de búsqueda<br>Entonces la lista se filtra para mostrar solo las preguntas relevantes<br><br>**Escenario 03: Opción de contacto desde FAQ**<br>Dado que el visitante está revisando las Preguntas Frecuentes<br>Cuando no encuentra la respuesta que busca<br>Entonces el sistema le ofrece una opción visible para contactar a soporte |

<br>
<br>

| USID        | US-09               |
|-------------|---------------------|
| Epic ID     | EP-07               |
| Prioridad   | 1                   |
| User        | Visitante (Cliente potencial)   |
| Title       | Conocer al equipo   |
| Descripción | Como visitante quiero conocer al equipo fundador para generar confianza en las personas responsables del proyecto. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Revisar perfiles del equipo**<br>Dado que el visitante accede al área sobre el equipo<br>Cuando revisa los perfiles de los miembros<br>Entonces ve sus fotos, nombres y roles<br>Y puede leer una breve biografía de cada uno<br>Y encuentra enlaces a sus perfiles profesionales verificables (ej. LinkedIn) |

<br>
<br>

| USID        | US-10               |
|-------------|---------------------|
| Epic ID     | EP-07               |
| Prioridad   | 2                   |
| User        | Visitante (Cliente potencial)   |
| Title       | Revisar política de privacidad |
| Descripción | Como visitante quiero acceder fácilmente a la política de privacidad para entender cómo se manejarán mis datos personales. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Consultar la política de privacidad**<br>Dado que el visitante desea consultar la política de privacidad<br>Cuando selecciona la opción para verla (ej. desde el pie de página)<br>Entonces accede a la información de la política, la cual muestra su fecha de última actualización<br>Y el contenido está organizado en secciones claras<br>Y dispone de un índice para navegar por dichas secciones<br>Y encuentra información de contacto para consultas sobre privacidad |

<br>
<br>

| USID        | US-11               |
|-------------|---------------------|
| Epic ID     | EP-07               |
| Prioridad   | 1                   |
| User        | Visitante (Cliente potencial)   |
| Title       | Navegar footer completo     |
| Descripción | Como visitante quiero un footer organizado con todos los enlaces importantes para navegar fácilmente a información relevante. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Visualización de enlaces del pie de página**<br>Dado que el visitante está en el pie de página de cualquier página<br>Cuando revisa los enlaces disponibles<br>Entonces encuentra organizados: términos, privacidad, contacto, redes sociales y mapa del sitio<br><br>**Escenario 02: Funcionalidad de los enlaces**<br>Dado que el visitante selecciona un enlace del pie de página<br>Cuando activa el enlace<br>Entonces es dirigido al destino correcto<br>Y el enlace se abre en la ventana o pestaña apropiada<br><br>**Escenario 03: Adaptación a móvil (Responsive)**<br>Dado que el visitante accede desde un dispositivo móvil<br>Cuando visualiza el pie de página<br>Entonces todos los enlaces son legibles y fácilmente accesibles |

<br>
<br>

| USID        | US-12               |
|-------------|---------------------|
| Epic ID     | EP-07               |
| Prioridad   | 8                   |
| User        | Visitante (Cliente potencial)  |
| Title       | Comparar precios y planes |
| Descripción | Como visitante quiero ver claramente los diferentes planes disponibles para tomar una decisión informada sobre qué opción elegir. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Comparación de planes**<br>Dado que el visitante está en el área de precios<br>Cuando compara los planes disponibles<br>Entonces ve claramente las opciones (ej. freemium, premium)<br>Y observa las características destacadas de cada plan<br><br>**Escenario 02: Ver detalles del plan**<br>Dado que el visitante está comparando los planes<br>Cuando solicita más detalles de un plan específico<br>Entonces obtiene información completa sobre límites, funcionalidades y beneficios<br><br>**Escenario 03: Selección de un plan**<br>Dado que el visitante ha decidido qué plan elegir<br>Cuando selecciona un plan para continuar<br>Entonces es dirigido al proceso de registro o pago correspondiente |

<br>
<br>

| USID        | US-13               |
|-------------|---------------------|
| Epic ID     | EP-01               |
| Prioridad   | 5                   |
| User        | Estudiante universitario |
| Title       | Personalizar perfil de estudiante universitario |
| Descripción | Como estudiante universitario quiero crear y configurar mi perfil académico para que otros usuarios puedan conocer mis intereses de estudio y nivel académico. |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Creación de perfil académico (durante el registro)**<br>Dado que el usuario está en el proceso de registro<br>Cuando proporciona la información académica requerida (nombre, universidad, carrera, semestre)<br>Entonces el sistema crea su perfil<br>Y lo redirige al panel principal (dashboard)<br><br>**Escenario 02: Edición de perfil académico**<br>Dado que el usuario tiene un perfil creado<br>Cuando accede a la configuración de su perfil<br>Entonces puede editar su información académica y preferencias de estudio |

<br>
<br>

| USID        | US-14               |
|-------------|---------------------|
| Epic ID     | EP-02               |
| Prioridad   | 8                   |
| User        | Estudiante universitario |
| Title       | Buscar grupos de estudio |
| Descripción | Como estudiante universitario quiero buscar grupos de estudio por materia y universidad para encontrar compañeros compatibles con mi nivel académico |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Búsqueda de grupos por filtro**<br>Dado que el usuario está en la función de búsqueda de grupos<br>Cuando aplica filtros de búsqueda (ej. materia, universidad)<br>Entonces el sistema muestra una lista de grupos que coinciden con los criterios<br><br>**Escenario 02: Ver detalles de un grupo**<br>Dado que se muestran los resultados de la búsqueda de grupos<br>Cuando el usuario selecciona un grupo de la lista<br>Entonces puede ver información detallada del grupo y sus miembros |

<br>
<br>

| USID        | US-15               |
|-------------|---------------------|
| Epic ID     | EP-02               |
| Prioridad   | 8                   |
| User        | Estudiante universitario |
| Title       | Crear grupos de estudio |
| Descripción | Como estudiante universitario quiero crear un grupo de estudio especificando materia, objetivos y horarios para organizar sesiones colaborativas |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Creación exitosa de un grupo**<br>Dado que el usuario inicia el proceso de creación de grupo<br>Cuando proporciona la información requerida (nombre, materia, descripción, horarios)<br>Entonces el sistema crea el nuevo grupo<br>Y establece al usuario creador como administrador del grupo<br><br>**Escenario 02: Gestión de solicitudes de unión**<br>Dado que el usuario es administrador de un grupo creado<br>Cuando otros usuarios solicitan unirse al grupo<br>Entonces el administrador recibe notificaciones para aprobar o rechazar dichas solicitudes |

<br>
<br>

| USID        | US-16               |
|-------------|---------------------|
| Epic ID     | EP-04               |
| Prioridad   | 3                   |
| User        | Estudiante secundaria |
| Title       | Explorar interfaz intuitiva |
| Descripción | Como estudiante de secundaria quiero una interfaz con elementos lúdicos y coloridos para mantenerme motivada durante el uso de la aplicación |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Navegación en interfaz lúdica**<br>Dado que el estudiante de secundaria accede a la aplicación<br>Cuando navega por las diferentes secciones<br>Entonces la interfaz muestra elementos visuales atractivos (colores vibrantes, animaciones)<br><br>**Escenario 02: Recepción de recompensas visuales**<br>Dado que el estudiante completa actividades de estudio<br>Cuando alcanza objetivos o metas predefinidas<br>Entonces recibe recompensas visuales (ej. badges, puntos) |

<br>
<br>

| USID        | US-17               |
|-------------|---------------------|
| Epic ID     | EP-04               |
| Prioridad   | 2                   |
| User        | Estudiante secundaria |
| Title       | Ganar badges |
| Descripción | Como estudiante de secundaria quiero ganar badges por mi participación para sentir reconocimiento por mis contribuciones al grupo |
| Criterios de aceptación | **Escenario 01: Acumulación de puntos por participación**<br>Dado que el estudiante participa en actividades grupales<br>Cuando completa tareas, asiste a sesiones o ayuda a compañeros<br>Entonces el sistema acumula puntos en su perfil<br><br>**Escenario 02: Desbloqueo de badges por hitos**<br>Dado que el estudiante ha acumulado puntos<br>Cuando cumple los criterios específicos para un hito (ej. "Colaborador Nivel 1")<br>Entonces el sistema desbloquea un badge especial<br>Y el badge se muestra visible en su perfil |

<br>
<br>

| USID        | US-18               |
|-------------|---------------------|
| Epic ID     | EP-03               |
| Prioridad   | 5                   |
| User        | Estudiante secundaria |
| Title       | Usar chat grupal organizado |
| Descripción | Como estudiante de secundaria quiero un sistema de chat que separe contenido académico de social para evitar que se pierda información importante |
| Criterios de aceptación | **Escenario 01: Separación de canales de chat**<br>Dado que el estudiante está en un grupo de estudio<br>Cuando accede al chat grupal<br>Entonces puede alternar entre el canal "Académico" y el canal "Social"<br><br>**Escenario 02: Destacar mensajes en canal académico**<br>Dado que un miembro del grupo está en el canal académico<br>Cuando envía un mensaje y utiliza la función de "destacar"<br>Entonces el mensaje se fija en la parte superior del canal académico para todos los miembros |

<br>
<br>

| USID        | US-19               |
|-------------|---------------------|
| Epic ID     | EP-05               |
| Prioridad   | 3                   |
| User        | Estudiante autodidacta |
| Title       | Sincronizar archivos offline |
| Descripción | Como autodidacta quiero acceder a contenido sin conexión durante mis viajes para estudiar en cualquier momento y lugar |
| Criterios de aceptación | **Escenario 01: Descarga de contenido para modo offline**<br>Dado que el usuario tiene conexión a internet<br>Cuando selecciona contenido (archivos, videos) para acceso offline<br>Entonces el material queda descargado y disponible en su dispositivo sin conexión<br><br>**Escenario 02: Sincronización de progreso post-offline**<br>Dado que el usuario ha estudiado o avanzado en modo offline<br>Cuando recupera la conexión a internet<br>Entonces el progreso realizado se sincroniza automáticamente con su cuenta en la nube |

<br>
<br>

| USID        | US-20               |
|-------------|---------------------|
| Epic ID     | EP-05               |
| Prioridad   | 5                   |
| User        | Estudiante autodidacta |
| Title       | Visualizar métricas de progreso |
| Descripción | Como autodidacta quiero ver métricas detalladas de mi progreso para medir tangiblemente mi desarrollo profesional |
| Criterios de aceptación | **Escenario 01: Visualización de estadísticas de progreso**<br>Dado que el usuario ha completado actividades de aprendizaje<br>Cuando accede a su panel de estadísticas<br>Entonces ve gráficos de tiempo invertido<br>Y visualiza los temas completados<br>Y observa su nivel de progreso general<br><br>**Escenario 02: Recepción de recomendaciones basadas en objetivos**<br>Dado que el usuario ha establecido objetivos de aprendizaje<br>Cuando revisa su progreso semanal<br>Entonces recibe recomendaciones para mantener o mejorar su ritmo de estudio |

<br>
<br>

| USID        | US-21               |
|-------------|---------------------|
| Epic ID     | EP-02               |
| Prioridad   | 8                   |
| User        | Docente             |
| Title       | Gestionar grupos pagados |
| Descripción | Como docente quiero crear y gestionar grupos de estudio con tarifas personalizadas para monetizar mi expertise educativa |
| Criterios de aceptación | **Escenario 01: Creación de grupo pagado**<br>Dado que el usuario tiene un perfil verificado de docente<br>Cuando inicia la creación de un nuevo grupo de estudio<br>Entonces puede configurar el precio<br>Y la duración (si aplica)<br>Y el número máximo de participantes<br><br>**Escenario 02: Procesamiento de inscripción a grupo pagado**<br>Dado que un estudiante solicita unirse a un grupo pagado<br>Cuando el pago del estudiante es procesado exitosamente<br>Entonces el sistema confirma la inscripción al estudiante<br>Y notifica al docente sobre el nuevo miembro |

<br>
<br>

| USID        | US-22               |
|-------------|---------------------|
| Epic ID     | EP-06               |
| Prioridad   | 5                   |
| User        | Docente             |
| Title       | Compartir materiales educativos |
| Descripción | Como docente quiero compartir materiales educativos y realizar sesiones en vivo para brindar valor educativo a mis estudiantes |
| Criterios de aceptación | **Escenario 01: Compartir material de estudio**<br>Dado que el docente está en su grupo (pagado o gratuito)<br>Cuando comparte material educativo (ej. archivos, enlaces)<br>Entonces todos los miembros suscritos al grupo pueden acceder a ese contenido<br><br>**Escenario 02: Iniciar sesión en vivo**<br>Dado que el docente ha programado una sesión en vivo<br>Cuando inicia la sesión (videollamada)<br>Entonces los participantes del grupo reciben una notificación<br>Y pueden unirse a la sesión |

<br>
<br>

| USID        | US-23               |
|-------------|---------------------|
| Epic ID     | EP-06               |
| Prioridad   | 3                   |
| User        | Docente             |
| Title       | Revisar analytics de negocio |
| Descripción | Como docente quiero ver estadísticas de mis grupos para optimizar mis servicios educativos y aumentar mis ingresos |
| Criterios de aceptación | **Escenario 01: Consulta de métricas de rendimiento**<br>Dado que el docente tiene grupos activos<br>Cuando accede al panel de analíticas<br>Entonces puede ver métricas de ingresos<br>Y métricas de retención de estudiantes<br>Y métricas de satisfacción<br><br>**Escenario 02: Revisión de reportes periódicos**<br>Dado que ha transcurrido un período de tiempo (ej. mensual)<br>Cuando el docente revisa los reportes generados<br>Entonces recibe información sobre tendencias y recomendaciones de mejora |

<br>
<br>

| USID        | US-24               |
|-------------|---------------------|
| Epic ID     | EP-03               |
| Prioridad   | 8                   |
| User        | Usuario general     |
| Title       | Comunicar mediante chat integrado      |
| Descripción | Como usuario quiero comunicarme con los miembros de mi grupo a través de chat en tiempo real para coordinar actividades de estudio |
| Criterios de aceptación | **Escenario 01: Interacción en chat en tiempo real**<br>Dado que el usuario pertenece a un grupo<br>Cuando accede al chat grupal<br>Entonces puede enviar y recibir mensajes en tiempo real<br><br>**Escenario 02: Recepción de notificaciones push**<br>Dado que el usuario recibe un nuevo mensaje de chat<br>Cuando no está activo en la aplicación<br>Entonces recibe una notificación push en su dispositivo |

<br>
<br>

| USID        | US-25               |
|-------------|---------------------|
| Epic ID     | EP-03               |
| Prioridad   | 5                   |
| User        | Usuario general     |
| Title       | Realizar videollamadas grupales |
| Descripción | Como usuario quiero realizar videollamadas con mi grupo de estudio para tener sesiones de aprendizaje cara a cara |
| Criterios de aceptación | **Escenario 01: Iniciar videollamada grupal**<br>Dado que el usuario está en un grupo activo<br>Cuando inicia una videollamada<br>Entonces los demás miembros del grupo reciben una invitación para unirse<br><br>**Escenario 02: Compartir pantalla durante la videollamada**<br>Dado que varios usuarios están en una videollamada<br>Cuando uno de ellos comparte su pantalla<br>Entonces todos los demás participantes pueden ver el contenido compartido |

<br>
<br>

| USID        | US-26               |
|-------------|---------------------|
| Epic ID     | EP-03               |
| Prioridad   | 8                   |
| User        | Usuario general     |
| Title       | Compartir recursos  |
| Descripción | Como usuario quiero subir y compartir materiales de estudio para contribuir al aprendizaje colaborativo del grupo |
| Criterios de aceptación | **Escenario 01: Compartir y consumir recursos**<br>Dado que el usuario está en un grupo<br>Cuando comparte un recurso (documento, imagen, enlace)<br>Entonces el recurso queda disponible para los miembros del grupo<br>Y los otros miembros pueden descargarlo o visualizarlo |

<br>
<br>

| USID        | US-27               |
|-------------|---------------------|
| Epic ID     | EP-03               |
| Prioridad   | 3                   |
| User        | Usuario general     |
| Title       | Crear y responder quizzes  |
| Descripción | Como usuario quiero crear y responder quizzes sobre los temas de estudio para evaluar mi comprensión y la del grupo |
| Criterios de aceptación | **Escenario 01: Crear y publicar un quiz**<br>Dado que el usuario está en un grupo de estudio<br>Cuando crea un quiz sobre un tema<br>Entonces los otros miembros del grupo reciben una notificación<br>Y pueden responder el quiz<br><br>**Escenario 02: Responder un quiz y recibir retroalimentación**<br>Dado que el usuario va a responder un quiz disponible<br>Cuando finaliza el quiz<br>Entonces recibe retroalimentación inmediata sobre su desempeño<br>Y puede ver sus resultados |

<br>
<br>

| USID        | US-28               |
|-------------|---------------------|
| Epic ID     | EP-03               |
| Prioridad   | 5                   |
| User        | Usuario general     |
| Title       | Programar calendario de sesiones |
| Descripción | Como usuario quiero programar y gestionar sesiones de estudio para coordinar horarios con los miembros del grupo |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Proponer y confirmar una sesión**<br>Dado que el usuario está en un grupo<br>Cuando propone una nueva sesión de estudio (con fecha y hora)<br>Entonces los otros miembros pueden confirmar su participación o sugerir horarios alternativos<br><br>**Escenario 02: Recibir recordatorios de sesión**<br>Dado que una sesión está programada y confirmada<br>Cuando se acerca la hora de inicio<br>Entonces todos los participantes confirmados reciben un recordatorio |

<br>
<br>

| USID        | US-29               |
|-------------|---------------------|
| Epic ID     | EP-03               |
| Prioridad   | 5                   |
| User        | Usuario general     |
| Title       | Recibir notificaciones push |
| Descripción | Como usuario quiero recibir notificaciones relevantes para mantenerme actualizado sobre actividades de mis grupos |
| **Criterios de aceptación (Escenarios)** | **Escenario 01: Recepción de notificaciones de actividad**<br>Dado que el usuario pertenece a grupos activos<br>Cuando ocurre una actividad relevante en un grupo (ej. nuevo mensaje, próxima sesión, etc.)<br>Entonces el sistema envía una notificación push personalizada al dispositivo del usuario (siempre que las tenga activadas)<br><br>**Escenario 02: Configuración de preferencias de notificación**<br>Dado que el usuario está en la configuración de su cuenta<br>Cuando ajusta sus preferencias de notificación (ej. activa/desactiva tipos de alertas)<br>Entonces el sistema guarda sus preferencias<br>Y el usuario solo recibe las notificaciones que ha seleccionado recibir |

<br>
<br>

### Spike Stories – Integración de Chat y Videollamadas
#### Spike Story 1 — Investigación de Integración de Chat en Android y Backend C#

La aplicación móvil SkillShare está siendo desarrollada de forma nativa en Android Studio, con código en Kotlin. 
El backend se está desarrollando en C# (ASP.NET Core) con servicios RESTful y base de datos MySQL. 
El equipo desea implementar un chat grupal en tiempo real que permita la comunicación entre miembros de un grupo de estudio. 
Para ello, se evaluarán diferentes soluciones tecnológicas como Firebase Realtime Database, Firebase Firestore, SignalR (para C#), o WebSockets nativos, 
considerando compatibilidad, escalabilidad, facilidad de integración y sincronización en tiempo real.

##### Spike Story

Como equipo de desarrollo móvil y backend, quiero investigar y prototipar la integración de un chat grupal en tiempo real entre la app Android y el backend en C#, 
para determinar la mejor solución técnica, los requerimientos de integración, riesgos y esfuerzo estimado para su implementación completa.

##### Criterios de Aceptación (Given–When–Then) <br>
• Revisar tecnologías disponibles: Documentar ventajas, desventajas, costos y compatibilidad con Android + backend C#.<br>
• Evaluar la integración con Android: Documentar configuración, dependencias y manejo del ciclo de vida del chat.<br>
• Evaluar la integración con backend C#: Documentar requisitos de implementación, autenticación y sincronización de mensajes.<br>
• Prototipo de prueba funcional (PoC): Implementar envío/recepción de mensajes en tiempo real entre dos usuarios simulados.<br>
• Evaluar seguridad y persistencia: Analizar autenticación segura, cifrado y almacenamiento de datos.<br>
• Estimar esfuerzo de implementación: Desglosar tareas y estimar tiempo o puntos de historia.<br>
• Documentar hallazgos: Incluir resultados, comparación de tecnologías y recomendación final.

##### Definition of Done (DoD)

- Documento técnico con hallazgos, ventajas y desventajas de las opciones evaluadas.
- PoC funcional de chat entre dos usuarios en Android y backend C#.
- Resumen de riesgos, costos, tiempos estimados y arquitectura recomendada.
- Spike completado en máximo 24–48 horas dentro del sprint.

#### Spike Story 2 — Investigación de Integración de Videollamadas Grupales

El equipo busca implementar videollamadas grupales dentro de la aplicación Android SkillShare para sesiones de estudio colaborativas. 
El backend en C# debe gestionar la autenticación, creación de salas y registro de sesiones. 
Se evaluarán servicios de terceros y SDKs como WebRTC (open source), Agora.io, Twilio Video, o Daily.co,  considerando facilidad de integración, costo, escalabilidad, calidad de audio/video y compatibilidad con backend C#.

##### Spike Story

Como equipo de desarrollo móvil y backend, quiero investigar y prototipar la integración de videollamadas grupales usando Android y backend C#, 
para determinar la viabilidad técnica, librerías más adecuadas y el esfuerzo necesario para la implementación completa.

##### Criterios de Aceptación (Given–When–Then)
• Analizar SDKs y APIs disponibles: Documentar requerimientos técnicos, compatibilidad y costos.<br>
• Evaluar integración Android: Documentar configuración, permisos (micrófono, cámara) y rendimiento.<br>
• Evaluar integración backend C#: Documentar endpoints requeridos y flujos de autorización.<br>
• Prototipo funcional (PoC): Implementar videollamada entre dos usuarios con audio y video funcionales.<br>
• Evaluar seguridad y rendimiento: Registrar métricas y medidas de protección como cifrado TLS.<br>
• Documentar hallazgos y recomendaciones: Incluir opción recomendada, riesgos, costos y propuesta técnica.

##### Definition of Done (DoD)

- Informe técnico con comparación entre SDKs de videollamada (WebRTC, Agora, Twilio, etc.).
- PoC funcional con conexión básica entre dos usuarios desde Android.
- Análisis de seguridad, rendimiento y estimación de esfuerzo incluidos.
- Spike completado en 24–48 horas dentro del sprint.

## 3.2. Technical Stories

| USID        | TS-01               |
|-------------|---------------------|
| Epic ID     | EP-08               |
| Prioridad   | 8                   |
| User        | Developer           |
| Title       | API de Autenticación |
| Descripción | Como developer necesito implementar endpoints de autenticación para gestionar sesiones seguras de usuario |
| Criterios de aceptación | Given se envía request POST a /api/auth/login con credenciales válidas<br>When el sistema valida la información<br>Then retorna status 200 con JWT token<br><br>Given se envía request con credenciales inválidas<br>When el sistema procesa la request<br>Then retorna status 401 con mensaje de error |

<br>
<br>

| USID        | TS-02               |
|-------------|---------------------|
| Epic ID     | EP-09               |
| Prioridad   | 5                   |
| User        | Developer           |
| Title       | API de Gestión de Grupos |
| Descripción | Como developer necesito endpoints para CRUD de grupos de estudio para soportar la funcionalidad principal |
| Criterios de aceptación | Given se envía request POST a /api/groups con datos válidos<br>When el usuario autenticado crea un grupo<br>Then retorna status 201 con información del grupo creado<br><br>Given se envía request GET a /api/groups con filtros<br>When existen grupos que coinciden<br>Then retorna status 200 con lista paginada de grupos |

<br>
<br>

| USID        | TS-03               |
|-------------|---------------------|
| Epic ID     | EP-10               |
| Prioridad   | 5                   |
| User        | Developer           |
| Title       | API de chat         |
| Descripción | Como developer, necesito un endpoint WebSocket para enviar y recibir mensajes en tiempo real. |
| Criterios de aceptación | Given que el cliente se conecta al WebSocket, <br>When envía a mensaje, <br>Then todos los miembros conectados reciben el mensaje instantáneamente. |

<br>
<br>

| USID        | TS-04               |
|-------------|---------------------|
| Epic ID     | EP-11               |
| Prioridad   | 5                   |
| User        | Developer           |
| Title       | API de Gestión de Recursos |
| Descripción | Como developer necesito endpoints para subir, listar, y descargar recursos compartidos en los grupos de estudio. |
| Criterios de aceptación | Given se envía request POST /api/resources con archivo válido y metadata<br>When el usuario está autenticado<br>Then retorna 201 con metadata del recurso almacenado.<br><br>Given se envía request GET /api/resources?groupId=xxx<br>When existen recursos asociados al grupo<br>Then retorna 200 con lista paginada de archivos.<br><br>Given se envía request GET /api/resources/{id}/download<br>When el recurso existe<br>Then retorna 200 y descarga el archivo. |

<br>
<br>

| USID        | TS-05               |
|-------------|---------------------|
| Epic ID     | EP-12               |
| Prioridad   | 3                   |
| User        | Developer           |
| Title       | API de Quizzes      |
| Descripción | Como developer necesito endpoints RESTful para crear quizzes, responderlos y calcular resultados. |
| Criterios de aceptación | Given se envía request POST /api/quizzes con preguntas válidas<br>When el usuario autenticado lo envía<br>Then retorna 201 con detalles del quiz.<br><br>Given se envía request POST /api/quizzes/{id}/answers con respuestas del usuario<br>When las respuestas son válidas<br>Then retorna 200 con puntaje calculado.<br><br>Given se envía request GET /api/quizzes/{id}/results<br>When el usuario ya resolvió el quiz<br>Then retorna 200 con historial de intentos y resultados. |

<br>
<br>

| USID        | TS-06               |
|-------------|---------------------|
| Epic ID     | EP-13               |
| Prioridad   | 5                   |
| User        | Developer           |
| Title       | API de Perfil y Verificación de Docente |
| Descripción | Como developer necesito endpoints para registrar y verificar docentes, incluyendo documentación y reseñas de alumnos. |
| Criterios de aceptación | Given se envía request POST /api/teachers/verify con credenciales/documentos<br>When la solicitud es válida<br>Then retorna 202 indicando que está en proceso de verificación.<br><br>Given se envía request GET /api/teachers/{id}/reviews<br>When existen reseñas registradas<br>Then retorna 200 con lista de reseñas y promedio de calificación. |

<br>
<br>

| USID        | TS-07               |
|-------------|---------------------|
| Epic ID     | EP-14               |
| Prioridad   | 3                   |
| User        | Developer           |
| Title       | Sistema de Notificaciones Push |
| Descripción | Como developer necesito un servicio de notificaciones push para avisar a los usuarios sobre nuevos mensajes, recursos, o eventos. |
| Criterios de aceptación | Given que un evento relevante ocurre en un grupo (nuevo recurso, mensaje, videollamada programada)<br>When se dispara el evento<br>Then el sistema envía una notificación push a todos los miembros suscritos.<br><br>Given se envía request POST /api/notifications/test<br>When el token del dispositivo es válido<br>Then retorna 200 confirmando la entrega. |

<br>
<br>

## 3.3. Impact Mapping

![Impact Mapping](assets/images/C2/impact_mapping.jpg)

<br>
<br>

## 3.4. Product Backlog

**Link de Trello:** [Dar click aquí: Trello](https://trello.com/invite/b/690bdd91d282e86e007089d9/ATTI64316a1085fd5a5da7786e31540f4c205376F47A/thinkup-skillshare)

| Orden | User Story ID |                Título                   | Story Points |
|-------|---------------|-----------------------------------------|--------------|
| 1     | USID-01       | Registrar usuario                       |      8       |
| 2     | USID-12       | Mostrar sección de precios y planes     |      8       |
| 3     | USID-14       | Buscar grupos de estudio                |      8       |
| 4     | USID-15       | Crear grupos de estudio                 |      8       |
| 5     | USID-21       | Gestionar grupos pagados                |      8       |
| 6     | USID-24       | Integrar chat                           |      8       |
| 7     | USID-26       | Compartir recursos                      |      8       |
| 8     | USID-13       | Personalizar perfil                     |      5       |
| 9     | USID-20       | Mostrar métricas de progreso de estudio |      5       |
| 10    | USID-22       | Proporcionar herramientas de enseñanza  |      5       |
| 11    | USID-25       | Realizar videollamadas grupales         |      5       |
| 12    | USID-28       | Gestionar calendario de sesiones        |      5       |
| 13    | USID-29       | Enviar notificaciones push              |      5       |
| 14    | USID-02       | Mostrar banner "Cómo funciona"          |      5       |
| 15    | USID-04       | Listar funcionalidades                  |      5       |
| 16    | USID-06       | Demostrar buscador                      |      5       |
| 17    | USID-18       | Organizar chat grupal                   |      5       |
| 18    | USID-16       | Diseñar interfaz intuitiva              |      3       |
| 19    | USID-19       | Sincronizar datos offline               |      3       |
| 20    | USID-23       | Analizar métricas de negocio            |      3       |
| 21    | USID-27       | Implementar sistema de quizzes          |      3       |
| 22    | USID-03       | Mostrar video demostrativo              |      3       |
| 23    | USID-05       | Mostrar testimonios y casos de éxito    |      3       |
| 24    | USID-07       | Crear formulario de contacto            |      3       |
| 25    | USID-08       | Mostrar FAQ interactiva                 |      3       |
| 26    | USID-17       | Asignar insignias mediante logros       |      2       |
| 27    | USID-10       | Publicar política de privacidad         |      2       |
| 28    | USID-09       | Mostrar página del equipo               |      1       |
| 29    | USID-11       | Diseñar footer completo                 |      1       |

<br>
<br>

| Orden | TS-ID  | Título                                     | Story Points |
|-------|--------|--------------------------------------------|--------------|
| 1     | TS-01  | Desarrollar API de autenticación           |       8      |
| 2     | TS-02  | Desarrollar API de gestión de grupos       |       5      |
| 3     | TS-04  | Desarrollar API de gestión de recursos     |       5      |
| 4     | TS-03  | Desarrollar API de chat                    |       5      |
| 5     | TS-06  | Desarrollar API de perfil de docente       |       5      |
| 6     | TS-05  | Implementar API de quizzes                 |       3      |
| 7     | TS-07  | Implementar sistema de notificaciones push |       3      |

<br>
<br>
<br>
<br>
<br>
<br>


<!--  
   CAPÍTULO 4: SOLUTION SOFTWARE DESING
-->

# Capítulo IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. EventStorming
Con el objetivo de comprender y modelar el dominio de SkillShare, realizamos una sesión de EventStorming. Esta dinámica permitió al equipo visualizar los eventos más relevantes, los actores involucrados, las reglas de negocio y los sistemas externos relacionados, logrando así una primera aproximación estructurada al funcionamiento de la aplicación.
La sesión se llevó a cabo en la herramienta digital Miro, con una duración aproximada de 1 hora y 30 minutos. Durante el proceso seguimos los 9 pasos propuestos en la metodología.

**Step 1: Unstructured Exploration** <br>
En esta primera etapa, el equipo se centró en identificar y registrar todos los eventos que ocurren en la aplicación, sin ningún orden ni restricción. La dinámica consistió en que cada miembro del equipo propusiera eventos en forma de post-its naranjas en Miro, generando un panorama amplio de lo que sucede en el dominio de SkillShare.  

<div align="center">>

![step-01](assets/images/C4/step-01.png)

</div>

**Step 2: Timelines** <br>
En este paso ya no listamos eventos de manera desordenada (como en Step 1), sino que los ordenamos cronológicamente siguiendo el flujo natural que tendría un estudiante al usar la plataforma.

<div align="center">

![step-02](assets/images/C4/step-02.png)

</div>

**Step 3: Pain Points** <br>
En este paso identificamos los problemas, fricciones o dificultades que pueden surgir en el flujo que vimos en el Step 2 (Timelines). Los pain points sirven para descubrir áreas críticas que necesitan mejoras en diseño, funcionalidad o experiencia de usuario.

<div align="center">

![step-03](assets/images/C4/step-03.png)

</div>

**Step 4: Pain Points** <br>
Identificación de eventos comerciales importantes que indiquen un cambio en el contexto o la fase, se marcan con una barra vertical que face los eventos antes y después del evento fundamental.

<div align="center">

![step-04](assets/images/C4/step-04.png)

</div>

**Step 5: Commands** <br>
Son las acciones explícitas que un usuario o actor envía al sistema para provocar un evento.

<div align="center">

![step-05-01](assets/images/C4/step-05-01.png)
![step-05-02](assets/images/C4/step-05-02.png)

</div>

#### 4.1.1.1. Candidate Context Discovery

A partir del dominio previamente modelado mediante EventStorming, llevamos a cabo la sesión de Candidate Context Discovery con el propósito de identificar los bounded contexts de nuestro dominio.
A continuación, se presentan las imágenes de los cambios progresivos realizados sobre el EventStorming y la identificación de los contextos candidatos:

1. **Contexto de Gestión de Usuarios:** Incluye todo lo relacionado con el registro, autenticación y manejo de perfiles de los estudiantes

<div align="center">
<img src="assets/images/C4/contexto-gestion_usuarios.png" alt="Contexto de Comunicación" width="500">
</div>

2. **Contexto de Grupos de Estudio:** Se centra en la creación, administración y participación en grupos académicos.

<div align="center">
<img src="assets/images/C4/contexto-gestion_grupo.png" alt="Contexto de Grupos de Estudio" width="500">
</div>

3. **Contexto de Recursos Compartidos:** Gestiona el almacenamiento y acceso a materiales de estudio (apuntes, PDFs, presentaciones, links, etc.).

<div align="center">
<img src="assets/images/C4/contexto-gestion_recursos_compartidos.png" alt="Contexto de Recursos Compartidos" width="500">
</div>

4. **Contexto de Comunicación (chat):** Abarca los mensajes y la interacción en tiempo real entre los miembros de un grupo.

<div align="center">

<img src="assets/images/C4/contexto-comunicacion.png" alt="Contexto de Comunicación" width="500">

</div>

5. **Contexto de Evaluaciones (quizzes):** Permite la creación y resolución de cuestionarios dentro de los grupos.

<div align="center">

<img src="assets/images/C4/contexto-gestion_quizz.png" alt="Contexto de Evaluciones" width="500">

</div>

**Resultado de la identificación de Bounded Context** <br>
Contextos resultados del análisis y realización de cambios cambios progresivos en los resultados del EventStorm.

<div align="center">
<img src="assets/images/C4/resultado_identificacion_bounded_context.png" alt="Resultado de la identificación de Bounded Context" width="500">
</div>

#### 4.1.1.2. Domain Message Flows Modeling

En esta sección se presenta de manera gráfica la definición de los bounded contexts de nuestro dominio, con el objetivo de resolver los casos de uso que se presentan en el negocio para los usuarios del sistema. Para ello, se ha aplicado la técnica de Domain Storytelling. A continuación, se describen algunos de los principales flujos identificados.

**Escenario: Registro de estudiantes y creación de grupos** <br>
**Actores** <br>
En este proceso intervienen principalmente dos tipos de usuarios:
  - **Estudiante:** usuario que accede a la plataforma por primera vez y busca crear o unirse a comunidades de estudio.
  - **Administrador de grupo:** inicialmente también es un estudiante, pero adquiere permisos adicionales al crear un grupo.

**Explicación del proceso y definición de los eventos**
- El estudiante accede a la aplicación SkillShare desde su dispositivo y es dirigido a la sección de registro.
- Completa sus datos personales básicos (nombre, correo electrónico, contraseña, intereses académicos).
- El sistema valida la información ingresada y confirma el registro exitoso del estudiante.
- Una vez registrado, el estudiante tiene la posibilidad de crear un nuevo grupo de estudio.
- El sistema recibe la solicitud, genera el evento **“Grupo creado”** y asigna automáticamente al creador como **administrador del grupo.**
- Posteriormente, el grupo queda disponible para que otros estudiantes puedan visualizarlo y unirse.
- Finalmente, el contexto de **Comunicación** emite una notificación en el chat grupal: **“Se ha creado un nuevo grupo de estudio”.**

**Relación entre usuario con bounded contexts y reglas de negocio**

- En el **Contexto de Gestión de Usuarios**, se garantiza la validación y autenticación de los datos personales del estudiante para mantener la seguridad en el acceso.
- En el **Contexto de Grupos de Estudio**, se definen las reglas de negocio relacionadas con la creación de grupos, asignación automática de roles (administrador del grupo) y visibilidad del nuevo grupo para otros usuarios.
- En el **Contexto de Comunicación**, se manejan las notificaciones que informan a los demás estudiantes sobre la creación del grupo, asegurando la colaboración y dinamismo en la plataforma

**Visualización del flujo**

<div align="center">
<img src="assets/images/C4/flujo.png" alt="Registro de usuario">
</div>

<br>
<br>

**Escenario: Unión de estudiantes a un grupo de estudio**

**Actores**

En este proceso participan principalmente dos actores:
- **Estudiante**: usuario que busca integrarse a un grupo de estudio existente.
- **Administrador de grupo**: responsable de aprobar o rechazar solicitudes de ingreso.

**Explicación del proceso y definición de los eventos**

- El estudiante navega por la sección de grupos disponibles en SkillShare y selecciona uno que coincide con sus intereses académicos.

- Envía una solicitud de unión al grupo elegido.

- El sistema registra la solicitud y la asocia al grupo correspondiente.

- El administrador del grupo recibe la notificación de la nueva solicitud y procede a revisarla.

- El administrador aprueba la solicitud, lo cual genera el evento **“Estudiante agregado al grupo”**.

- El sistema actualiza la lista de miembros del grupo y asigna al nuevo integrante los permisos básicos de participación.

- Finalmente, el **Contexto de Comunicación** emite un mensaje en el chat grupal notificando: **“Un nuevo miembro se ha unido al grupo”.**

**Relación entre usuario con bounded contexts y reglas de negocio**

- En el **Contexto de Grupos de Estudio**, se gestionan las reglas de aceptación de miembros, garantizando que solo los estudiantes aprobados por el administrador puedan ingresar.

- En el **Contexto de Gestión de Usuarios**, se mantiene la identidad y datos del estudiante para vincularlos correctamente al grupo.

- En el **Contexto de Comunicación**, se generan los avisos que mantienen informados a los miembros activos del grupo sobre nuevas incorporaciones.

**Visualización del flujo**

<div align="center">
<img src="assets/images/C4/flujo-01.png" alt="Unión de estudiante a grupo de estudio">
</div>

<br>
<br>

**Escenario: Compartir recurso académico en un grupo de estudio**

**Actores**

En este proceso participan principalmente dos actores:
- **Estudiante:** miembro de un grupo que desea compartir un recurso académico (apuntes, PDF, enlace, presentación).
- **Miembros del grupo:** estudiantes que reciben y pueden interactuar con el recurso compartido.

**Explicación del proceso y definición de los eventos**

- El estudiante accede a la sección de su grupo de estudio dentro de SkillShare.

- Selecciona la opción **“Compartir recurso”** e indica el tipo de material (documento, enlace, video, etc.).

- El sistema valida el recurso (formato, tamaño, permisos de acceso).

- Se registra el recurso en el grupo y se asocia al perfil del estudiante que lo compartió.

- El sistema genera el evento **“Recurso compartido en grupo”.**

- El **Contexto de Comunicación** envía una notificación a todos los miembros: **“Un nuevo recurso ha sido compartido en el grupo”.**

- Los demás miembros pueden visualizar, descargar o comentar el recurso compartido.

**Relación entre usuario con bounded contexts y reglas de negocio**

- En el **Contexto de Grupos de Estudio**, se mantiene la asociación del recurso al grupo y se gestiona quién puede compartir contenido (solo miembros activos)

- En el **Contexto de Gestión de Usuarios**, se relaciona el recurso con el perfil del estudiante que lo publica.

- En el **Contexto de Comunicación**, se garantiza que todos los integrantes reciban la notificación correspondiente.

- Reglas de negocio:
  - Solo miembros activos pueden compartir recursos.
  - El recurso debe cumplir con validaciones de formato y tamaño.
  - Los recursos se almacenan con trazabilidad para saber quién los compartió.

**Visualización del flujo**

<div align="center">

![flujo-02](assets/images/C4/flujo-02.png)

</div>

#### 4.1.1.3. Bounded Context Canvases

<div align="center">

<img src="assets/images/C4/profile.jpg" alt="Profile" width="600">
<br>
<br>
<img src="assets/images/C4/chat.jpg" alt="Chat" width="600">
<br>
<br>
<img src="assets/images/C4/quizzes.jpg" alt="Quizzes" width="600">
<br>
<br>
<img src="assets/images/C4/shared-resources.jpg" alt="Shared Resources" width="600">
<br>
<br>
<img src="assets/images/C4/study-groups.jpg" alt="Study Groups" width="600">

</div

<br>
<br>


### 4.1.3. Software Architecture

En esta sección, se presentan los diagramas C4 que describen la arquitectura del sistema de estudio colaborativo. Estos diagramas permiten comprender de manera clara cómo se organiza la solución, cómo interactúan los usuarios y sistemas externos con la aplicación, cómo se estructuran los principales contenedores de software y, finalmente, cómo se despliegan los componentes en el entorno de ejecución.

#### 4.1.3.1. Software Architecture Context Level Diagrams

El Diagrama de Contexto muestra la interacción de la aplicación de estudio colaborativo con los actores externos, principalmente docentes y estudiantes, quienes son los usuarios principales del sistema. Este diagrama ofrece una visión de alto nivel de cómo la aplicación se conecta con su entorno, facilitando la comprensión de su papel dentro del ecosistema educativo digital.

<div align="center">
<img src="assets/images/C4/software_architecture_context_level_diagrams.png" alt="Profile" width="600">
</div>

#### 4.1.3.2. Software Architecture Container Level Diagrams

El Diagrama de Contenedores ofrece una visión más detallada de la arquitectura de la aplicación de estudio colaborativo.
Este nivel describe los principales contenedores que conforman el sistema y cómo interactúan entre sí, así como con los sistemas externos.

<div align="center">
<img src="assets/images/C4/software_architecture_container_level_diagrams.png" alt="Profile" width="600">
</div>

#### 4.1.3.3. Software Architecture Deployment Diagrams

Los Diagramas de Despliegue (Deployment Diagrams) permiten visualizar cómo la aplicación se distribuye en la infraestructura tecnológica que soporta su funcionamiento. Estos diagramas muestran la relación entre los diferentes artefactos de software y los nodos físicos o virtuales en los que se ejecutan.

<div align="center">
<img src="assets/images/C4/software_architecture_deployment_diagrams.png" alt="Profile" width="600">
</div>

<br>
<br>

## 4.2. Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context

Este contexto abarca todo lo relacionado con el registro, autenticación y gestión de usuarios, así como la creación, administración y participación en grupos de estudio. Es un núcleo del dominio, ya que sin estas funcionalidades no existe la dinámica principal de SkillShare.

#### 4.2.1.1. Domain Layer

El Domain Layer define la lógica central del negocio relacionada a la gestión de usuarios, grupos de estudio y recursos compartidos.
En esta capa se modelan los conceptos fundamentales como usuarios, grupos, membresías y recursos académicos, así como las reglas y comportamientos que regulan su funcionamiento.

Este nivel captura la esencia del dominio de manera independiente a la tecnología, asegurando coherencia, reutilización y alineación con los objetivos del negocio.

**Entidades Principales**

| Clase | Tipo     | Propósito   | Atributos  |
|---------------|----------|---------------------------------------------------------------------------|-------------------------------|
| Usuario       | Entity   | Representa a un estudiante dentro de la red social académica. Puede crear o unirse a grupos de estudio y compartir recursos. | id, nombre, email, contraseña hash, rol, intereses académicos |
| GrupoEstudio  | Entity   | Representa un grupo de estudio creado por usuarios en torno a una materia o tema específico. | Id, nombre, descripción, materia, fecha de creación, estado |
| Membresía     | Entity   | Relaciona a un usuario con un grupo de estudio, definiendo su rol dentro de este. | Usuario_id, grupo_id, rol en el grupo (admin/miembro) |
| Recurso       | Entity   | Representa materiales compartidos dentro de un grupo de estudio (apuntes, notas, quizzes, enlaces). | id, grupoId, usuarioId, tipo (pdf, link, quiz, imagen), título, contenido, fechaSubida |

**Value Objects**

| Clase  | Tipo | Propósito   | Atributos        |
|-----------|--------------|---------------------------------------------------|------------------|
| Email     | Value Object | Garantiza el formato válido y único de correo electrónico. | dirección        |
| Password  | Value Object | Asegura que la contraseña cumpla con reglas de seguridad (mínima longitud, caracteres especiales, hash). | valorHasheado    |

**Agregados**

| Agregado  | Entidades Asociadas        | Propósito |
|------------------|----------------------------|---------------------------------------------------------------------------|
| Usuario          | Usuario, Perfil            | Centraliza la gestión de identidad, intereses y autenticación de usuarios. |
| Grupo de Estudio | GrupoEstudio, Membresías, recursos | Coordina las entidades relacionadas con un grupo: creación, invitación de miembros, asignación de roles y manejo de recursos compartidos. |

**Servicios de Dominio**

| Servicio  | Propósito    | Métodos principales  |
|---------------------|-------------------------------------------------------|-----------------------------------|
| GrupoEstudioService | Encargado de validar las reglas al momento de crear y gestionar grupos. | validarNombreUnico, asignarAdministrador, cerrarGrupo |
| RecursoService      | Administra la validación y publicación de recursos compartidos dentro de los grupos. | validarFormato, publicarRecurso  |
| MembresíaService    | Gestiona la relación entre usuarios y grupos.         | agregarMiembro, cambiarRol, removerMiembro |

#### 4.2.1.2. Interface Layer

Expone las funcionalidades a través de APIs o pantallas en Flutter.

**Componentes principales**

| Clase  | Tipo | Propósito  | Atributos             |
|-----------------|------|-----------------------------------------------|-----------------------|
| Login           | UI   | Permite que el usuario ingrese sus credenciales y se autentique. | email, password       |
| Register        | UI   | Pantalla para registrar nuevos usuarios.      | nombre, email, password |
| GroupsScreen    | UI   | Lista los grupos de estudio disponibles para explorar y unirse. | listGroup             |
| GroupDetail     | UI   | Muestra detalles de un grupo (miembros, recursos, chat). | Miembros, recurso     |
| FilesScreen     | UI   | Visualiza los recursos compartidos.           | recursos              |
| ProfileScreen   | UI   | Permite gestionar la información del perfil del usuario. | Id, nombre, descripción |

**APIs REST / GraphQL**

| Endpoint                  | Propósito                              |
|---------------------------|----------------------------------------|
| POST /usuarios/registrar  | Crear un nuevo usuario con datos validados. |
| POST /usuarios/login      | Autenticar y generar sesión/token.     |
| GET /grupos               | Obtener lista de grupos disponibles    |
| POST /grupos              | Crear un nuevo grupo de estudio.       |
| GET /grupos/{id}          | Obtener información detallada de un grupo específico. |
| POST /grupos/{id}/unirse  | Solicitar unirse a un grupo            |
| POST /grupos/{id}/recursos | Subir un recurso (archivo, link, quiz). |
| GET /grupos/{id}/recursos | Listar recursos del grupo.             |

#### 4.2.1.3. Application Layer

Orquesta los casos de uso y coordina dominio e infraestructura.

| Clase               | Tipo           | Propósito                              |
|---------------------|----------------|----------------------------------------|
| Registrar usuario   | Command        | Representa la intención de registrar un usuario |
| Iniciar sesion      | Command        | Solicitud de autenticación de usuario  |
| Crear grupo de estudio | Command     | Encapsula la creación de un grupo de estudio |
| Unirse a grupo      | Command        | Representa la intención de unirse a un grupo |
| Asignar roles       | Command        | Cambiar el rol de un miembro dentro de un grupo |
| Compartir recursos  | Command        | Acción de compartir un recurso académico |
| Notifica al usuario | Domain Event   | Notifica que un usuario fue registrado |
| Grupo creado        | Domain Event   | Indica que un grupo fue creado         |
| Recurso compartido  | Domain Event   | Señala que un recurso fue compartido   |

#### 4.2.1.4. Infrastructure Layer

Implementa persistencia, integración y frameworks.

| Clase                    | Tipo               | Propósito   |
|--------------------------|--------------------|----------------------------------------|
| UserRepositorylmpl       | Repository lmpl    | userId, nombre, email, passwordHash    |
| GroupRepositoryImpl      | Repository lmpl    | groupId, nombre, descripción, materia, creadorId |
| MembershipRepositoryImpl | Repository lmpl    | membershipId, usuarioId, groupId, rol  |
| AuthService              | External Service   | provider, token, refreshToken          |
| FirestoreService         | External Service   | colección, documentoId, payload        |
| NotificationService      | External Service   | userId, mensaje, canal                 |
| EventBusImpl             | External Service   | eventId, tipoEvento, payload           |
| FileStorageService       | External Service   | Manejo de archivos compartidos en grupos |
| FlutterFramework         | Framework          | Soporte para la interfaz de usuario multiplataforma |

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

El Component Level Diagrams representa los principales componentes de SkillShare. Permite visualizar la interacción entre la aplicación móvil, el backend, la base de datos y los servicios externos.

<div align="center">
<img src="assets/images/C4/diagrama_components.png" alt="Bounded Context Software Architecture Component Level Diagrams" width="600">
</div>

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

Este diagrama de clases representa los elementos principales del Domain Layer en SkillShare.

<div align="center">
<img src="assets/images/C4/bounded_context_domain_layer_class_diagrams.png" alt="Bounded Context Domain Layer Class Diagrams" width="600">
</div>

##### 4.2.1.6.2. Bounded Context Database Design Diagram

El Database Design Diagram representa la estructura de la base de datos para el contexto de SkillShare. Este diseño asegura la persistencia de los datos de acuerdo con la lógica del dominio, permitiendo mantener la integridad, consistencia y eficiencia en las operaciones de la plataforma, desde la gestión de usuarios hasta la interacción en grupos y el intercambio de recursos.

<div align="center">
<img src="assets/images/C4/bounded_context_database_design_diagram.png" alt="Bounded Context Database Design Diagram" width="600">
</div>


<br>
<br>
<br>
<br>
<br>
<br>

<!--
   CAP V
-->

# Capítulo V: Solution UI/UX Design

## 5.1. Product Design

### 5.1.1. Style Guidelines

En esta sección se definirán las guías visuales clave para el diseño de SkillShare, incluyendo colores, tipografía, logotipo y tono de comunicación. Estos lineamentos asegurarán una identidad coherente y profesional que refleje los valores de confianza e innovación de la marca.

#### 5.1.1.1. General Style Guidelines

[**Dar clic aquí (Figma)**](https://www.figma.com/design/sAUImMuHosMP8dkamF4UP6/General-Style-Guidelines-%7C-SkillShare?node-id=0-1&t=HGpVgCSldWQVk4rr-1)

**Branding:**
Nuestra marca busca transmitir confianza, accesibilidad y modernidad, reflejando un espacio de aprendizaje digital en el que estudiantes universitarios, escolares y autodidactas puedan desarrollarse.

El branding se enfoca en tres pilares:
1. **Cercanía:** una app que no se siente rígida ni académica en exceso, sino amigable y fácil de usar.
2. **Confianza:** un diseño claro y organizado que genere credibilidad en los usuarios.
3. **Inspiración:** una marca que motive a los usuarios a superarse, reflejando energía y entusiasmo.

<br>

**Logo:**

<p align="center">
<img src="assets/images/C5/logo.png">
</p>

Nuestro logo consiste en un círculo con degradado en los tres tonos de azul, dentro del cual se ubican tres nodos blancos conectados entre sí.

1. **Forma circular:** Representa la unidad, continuidad y colaboración entre los estudiantes, reflejando que el aprendizaje es un proceso en comunidad.
2. **Degradado en azules:** Transmite profundidad, dinamismo y confianza, simbolizando la transición natural del aprendizaje individual hacia el colectivo.
3. **Nodos interconectados en blanco:** Evocan la relación entre estudiantes, el intercambio de conocimientos y la construcción de una red de apoyo académico.

*Este logo es un reflejo de nuestra misión: conectar personas para potenciar su aprendizaje.*

**Favicon:**
El favicon es una representación simplificada de nuestro logo, manteniendo la esencia de la conexión y colaboración entre los estudiantes. En este diseño minimalista, se conservan únicamente los tres nodos interconectados en color blanco, eliminando el degradado de azules y la forma circular para garantizar una visualización clara y eficiente a pequeña escala.

Para asegurar una visualización óptima en diferentes entornos, hemos creado dos versiones del favicon: una para navegadores con tema claro y otra para aquellos con tema oscuro. En ambas, los nodos destacan sobre el fondo correspondiente, garantizando que el ícono sea siempre visible y representativo de nuestra misión, sin importar el entorno de visualización.

<br>

**Tipografía: Sarabun**

<p align="center">
<img src="assets/images/C5/typografhy-sarabun.png">
</p>

La tipografía seleccionada para nuestra marca es Sarabun. Esta fuente fue elegida por su legibilidad, versatilidad y estilo moderno, lo que la hace ideal para una aplicación orientada a estudiantes de distintos niveles (secundaria, universitarios y autodidactas).

Su diseño limpio y equilibrado permite diferenciar jerarquías de información con facilidad, asegurando una experiencia de lectura clara en pantallas pequeñas de dispositivos móviles. 

Sarabun combina un estilo moderno y accesible que se adapta tanto a títulos llamativos como a cuerpos de texto explicativos, lo que facilita la comunicación en contextos académicos y colaborativos. Además, refuerza la percepción de confianza y profesionalismo, sin perder la cercanía con los usuarios jóvenes y diversos que forman parte de nuestra comunidad.

<br>

**Colores:**

<p align="center">
<img src="assets/images/C5/color-palette.png">
</p>

Nuestra paleta de colores está conformada por tres tonos principales de azul y dos neutros, que juntos construyen una identidad visual coherente, confiable y moderna:

1. **#182438 – Azul profundo:** Representa la seriedad, concentración y estabilidad, transmitiendo confianza y un ambiente propicio para el estudio.
2. **#1E2F50 – Azul intermedio:** Simboliza la colaboración y el conocimiento compartido, siendo el tono que equilibra la seriedad con la cercanía.
3. **#324779 – Azul claro:** Refleja la dinámica, la motivación y el entusiasmo de los estudiantes que participan en grupos de aprendizaje.
4. **#FAFAFA – Blanco cálido:** Actúa como color base, transmitiendo claridad, limpieza y accesibilidad. Facilita la lectura y contrasta con los tonos azules.
5.**#FFFFFF – Blanco puro:** Complementa el diseño con una sensación de espacio, simplicidad y modernidad, evitando la sobrecarga visual.

<br>

**Tonos de comunicación:**
Para comunicarnos con nuestra audiencia, hemos definido un tono que equilibra profesionalismo con cercanía, tomando en cuenta que nuestros usuarios principales son estudiantes jóvenes:

1. **Divertido, pero no infantil:** Buscamos transmitir dinamismo y energía, evitando un tono demasiado formal, pero sin caer en la informalidad excesiva.
2. **Casual y accesible:** El lenguaje debe ser fácil de entender, cercano y natural, conectando con estudiantes de secundaria, universitarios y autodidactas.
3. **Respetuoso y motivador:** Siempre mostraremos respeto por las metas académicas de los usuarios, brindando un tono alentador que refuerce la idea de que aprender en comunidad es posible.
4. **Entusiasta y positivo:** Queremos transmitir la sensación de que la aplicación es un espacio donde el aprendizaje es colaborativo, enriquecedor y hasta divertido, alejándonos de la idea de que estudiar es aburrido o solitario.

<br>

### 5.1.2. Information Architecture

#### 5.1.2.1. Organization Systems

Para el sistema de organización de contenido en nuestra aplicación de gestión de grupos de estudio universitarios, se aplicarán diferentes enfoques de organización visual y categorización, en función de la naturaleza de la información y la interacción esperada de los usuarios.

**Organización visual (Visual hierarchy)**

- **Jerárquica:**
    Será utilizada en la estructura principal de la aplicación. Desde la pantalla inicial, los usuarios podrán navegar entre las secciones clave:
    1. Explorar grupos de estudio.
    2. Mis grupos.
    3. Recursos compartidos.
    4. Perfil y configuración.

    Este enfoque jerárquico permitirá que los estudiantes ubiquen fácilmente las funcionalidades principales y prioricen su interacción.
    
<br>

- **Secuencial (Step-by-step):**
    Aplicado en los procesos que requieren un flujo guiado, como:
    1. **Registro y creación de perfil:** paso a paso para completar información personal y académica.
    2. **Creación de un grupo de estudio:** desde definir el tema, establecer objetivos, invitar participantes, hasta programar la primera reunión.

<br>

- **Matricial:**
    Este sistema se aplicará en secciones que necesiten comparación y cruce de información. Por ejemplo:
    1. Visualizar diferentes grupos disponibles, organizados por materia en filas y nivel de avance académico en columnas.
    2. Comparación de recursos o materiales compartidos en los grupos, según tipo de documento (PDF, video, link, apuntes).

<br>

**Sistemas de categorización de contenido**

- **Alfabético:**
    Aplicado en glosarios de términos académicos, listas de autores o materiales compartidos con títulos largos. Esto ayudará a los estudiantes a encontrar rápidamente información puntual.

- **Por tópicos:**
    Se aplicará para organizar los grupos de estudio y los recursos académicos compartidos. Por ejemplo, un grupo puede clasificarse por asignatura ("Cálculo", "Programación", "Literatura"), y los materiales estarán categorizados por tipo de tema.

- **Según audiencia:**
    Este esquema será clave para diferenciar el contenido de acuerdo a los usuarios:
    1. **Estudiantes:** acceso a grupos, recursos y actividades.
    2. **Moderadores/Administradores de grupo:** herramientas para gestionar participantes, asignar tareas, y moderar discusiones.
    3. **Docentes o mentores invitados:** acceso restringido a grupos con posibilidad de compartir recursos y evaluar avances.

<br>

#### 5.1.2.2. Labeling Systems

En nuestra aplicación de grupos de estudio universitarios, los datos y funcionalidades se representarán con etiquetas cortas, consistentes y familiares para el usuario, evitando tecnicismos innecesarios. El diseño busca transmitir con una sola palabra (o frase breve) el contenido o acción disponible, reduciendo la confusión y mejorando la experiencia de navegación.

**Principios de etiquetado:**
- **Claridad:** usar términos simples y directos.
- **Consistencia:** las mismas acciones tendrán siempre la misma etiqueta en toda la aplicación.
- **Brevedad:** se limitarán a una o dos palabras por etiqueta.
- **Asociación:** cada etiqueta estará ligada a un conjunto de datos o acciones que el usuario asocia de manera intuitiva.

<br>

**Etiquetas principales y asociaciones:**
- **Inicio:** Acceso al panel principal con accesos directos a grupos, recursos y calendario.
- **Explorar:** Buscar y descubrir nuevos grupos de estudio por tema o nivel.
- **Mis grupos:** Sección con los grupos en los que el usuario participa.
- **Recursos:** Archivos, enlaces y materiales compartidos dentro de los grupos.
- **Chat:** Comunicación directa entre miembros de un grupo.
- **Perfil:** Información personal, académica y de configuración del usuario.
- **Config. (Configuración):** Preferencias de la aplicación: notificaciones, privacidad, idioma.
- **Ayuda:** Preguntas frecuentes, tutoriales y contacto con soporte.

<br>

**Ejemplos de micro-etiquetas contextuales:**
- **Botón "Unirse":** Asociado a la acción de integrarse a un grupo de estudio.
- **Botón "Crear":** Asociado a iniciar un nuevo grupo.
- **Etiqueta "Activo":** Indica grupos en funcionamiento.
- **Etiqueta "Finalizado":** Asociada a grupos que ya completaron sus actividades.
- **Etiqueta "Nuevo":** Marca recursos o grupos recién creados.

<br>

#### 5.1.2.3. SEO Tags and Meta Tags

Para garantizar la visibilidad de la aplicación en buscadores y plataformas digitales, se han definido los siguientes elementos de SEO (para la web) y ASO (para la aplicación móvil).

**Landing Page (sitio estático de presentación)**
- **Title (HTML ```<title>```):** SkillShare – Conecta con tu grupo de estudio fácilmente
- **Meta Description (```<meta name="description"```>):** SkillShare es la red social educativa que conecta a estudiantes universitarios, de secundaria y autodidactas en grupos de estudio. Comparte materiales, organiza reuniones y aprende colaborativamente desde tu móvil o navegador.
- **Meta Keywords (```<meta name="keywords">```):** grupos de estudio, red social educativa, estudiantes universitarios, secundaria, autodidactas, colaboración, aprendizaje en línea, app de estudio
- **Meta Author (```<meta name="author">```):** Equipo SkillShare
- **Meta Robots:** index, follow

<br>

**Mobile App (ASO – App Store Optimization)**
- **App Title:** SkillShare – Grupos de estudio
- **App Subtitle (iOS):** Aprende en comunidad, comparte y colabora
- **App Description:** SkillShare es una red social educativa que conecta a estudiantes universitarios, de secundaria y autodidactas. Únete a grupos de estudio, comparte recursos, chatea con tus compañeros y organiza tu aprendizaje de forma sencilla y práctica. Disponible en iOS y Android.
- **App Keywords (para iOS y Play Store tags):** grupos de estudio, app de aprendizaje, estudiantes, chat académico, red social educativa, recursos educativos, autodidactas
- **Developer / Author:** SkillShare Team
- **Category:** Education
- **App Icon & Screenshots:** (Diseñados con estilo juvenil y académico para captar la atención del segmento objetivo).

<br>

#### 5.1.2.4. Searching Systems

Para garantizar que los estudiantes encuentren de manera rápida y sencilla la información que necesitan, el producto digital contará con los siguientes sistemas de búsqueda y filtrado:

**1. Barra de Búsqueda Global**
- **Ubicación:** En la parte superior de la aplicación.
- **Funcionalidad:** Permite al usuario introducir palabras clave (ejemplo: "matemáticas cálculo", "programación Java", "grupo de ciencias sociales").
- **Resultados mostrados:** Listado jerárquico dividido en:
    - **Grupos de Estudio** (nombre del grupo, breve descripción, cantidad de miembros).
    - **Usuarios** (nombre, nickname, universidad o nivel educativo).
    - **Recursos** (documentos compartidos, enlaces, materiales).
- **Representación visual:** Resultados agrupados por categoría con etiquetas claras ("Grupos", "Usuarios", "Recursos"), evitando confusión.

<br>

**2. Búsqueda con Filtros Específicos**
Los usuarios podrán refinar su búsqueda mediante filtros contextuales:
- **Por Tipo de Usuario:** Universitario, Secundaria, Autodidacta.
- **Por Área de Conocimiento:** Ciencias, Ingeniería, Humanidades, Lenguas, Artes, etc.
- **Por País / Centro Educativo:** Para encontrar compañeros cercanos o del mismo entorno.
- **Por Popularidad:** Grupos con más actividad, usuarios con más interacciones.
- **Por Fecha:** Recursos compartidos recientemente (orden cronológico).

<br>

**3. Exploración Temática (sin búsqueda manual)**
Además de búsqueda textual, la aplicación ofrecerá un sistema de exploración por categorías:
- **Tópicos predefinidos:** Matemáticas, Programación, Literatura, Biología, Idiomas.
- **Organización visual matricial:** Íconos con colores diferenciados para cada tema.
- **Navegación secuencial:** Dentro de cada tema, el usuario puede acceder a grupos activos, recursos compartidos y eventos relacionados.

<br>

**4. Presentación de Resultados**
- **Grupos:** Tarjetas con nombre, foto de portada, descripción corta, cantidad de miembros, botón "Unirse".
- **Usuarios:** Tarjetas con nombre completo, nickname, universidad/escuela, botón "Conectar".
- **Recursos:** Lista con título, autor que lo compartió, tipo de archivo (PDF, link, imagen), botón "Ver/Descargar".

<br>

#### 5.1.2.5. Navigation Systems

El sistema de navegación de SkillShareApp se diseña bajo principios de simplicidad, consistencia y orientación clara, permitiendo a los usuarios recorrer la plataforma sin fricción y alcanzar sus metas (crear grupos, compartir materiales, conectar con otros estudiantes).

**1. Navegación en la Landing Page**
-  Menú principal (Top Navigation Bar): fijo en la parte superior con accesos directos a:
    - Inicio
    - Cómo Funciona
    - Características
    - Costo
    - Sobre Nosotros
    - Testimonios
    - Contáctanos
    - Obtener la aplicación

- **Call-to-Action destacado:** Botón "Empieza Ahora" ubicado en el hero banner, guiando a los usuarios a registrarse.
-  **Navegación secuencial (scroll):** Contenido dispuesto en orden jerárquico descendente (qué es la app → beneficios → pasos de uso → registro).
-  **Footer con navegación secundaria:** incluye enlaces a Contacto, Preguntas Frecuentes, Políticas de Privacidad, Redes Sociales.

<br>

**2. Navegación en la Web Application / App Móvil**
Se usarán tres técnicas de navegación principales:

**1. Navegación Jerárquica (Menú Principal)**
- Menú persistente con los apartados clave:
    - Inicio (feed con actividades recientes).
    - Grupos (Ingresar a tus grupos).
    - Buscar (Explorar, crear, unirse)
    - Recursos (biblioteca compartida).
    - Perfil (configuración del usuario).
    
- Íconos reconocibles + etiquetas de texto (ejemplo: un ícono de chat acompañado de la palabra Mensajes).

<br>

**2. Navegación Secuencial (Flujos de Usuario)**
- Para procesos que requieren pasos, como:
    - Registro → Completar perfil → Unirse a un grupo → Publicar/Compartir.
- Se guiará con indicadores visuales (paso 1 de 4, check verde al completar cada etapa).

<br>

**3. Navegación Contextual (Deep Links y Atajos)**
- Botones de acción rápida dentro del contenido:
    - "Unirse al grupo" desde la tarjeta de grupo.
    - "Descargar" directamente desde la vista previa de un recurso.
    - "Enviar mensaje" desde el perfil de un usuario.

- Uso de enlaces contextuales dentro de notificaciones push o correos electrónicos, llevando al usuario directamente a la sección relevante (ejemplo: "Alguien te mencionó en Grupo de Matemáticas → botón Ver ahora").

<br>

**4. Elementos de Orientación**
- **Breadcrumbs (migas de pan):** en vistas profundas de recursos y grupos, para volver fácilmente al nivel anterior.
- **Highlight del ítem activo:** el menú principal resalta la sección donde se encuentra el usuario.
- **Búsqueda accesible desde cualquier pantalla:** refuerzo de navegación interna.

<br>
<br>

### 5.1.3. Landing Page UI Design

#### 5.1.3.1. Landing Page Wireframe
Para la creación del wireframe de nuestra landing page, utilizamos Figma y diversos complementos que agilizaron el proceso de diseño. Esta combinación de herramientas facilitó una producción rápida y precisa del esquema inicial.

[**Dar clic aquí (Figma)**](https://www.figma.com/design/EbuU8tEUQMAOkmI9ajlICX/Landing-Page-%7C-SkillShare?node-id=0-1&t=Sh0jbwJxMCACKE8h-1)

<br>

**Landing Page (Desktop)**



<br>

**Landing Page (Mobile web)**


<br>

#### 5.1.3.2. Landing Page Mock-up

Los mockups de la landing page de SkillShare muestran una mayor fidelización de la interfaz final del sitio, integrando los elementos visuales definidos en la guía de estilo. Esta representación busca validar la propuesta estética y funcional de los wireframes en una experiencia clara y atractiva para el usuario.

#### **Pantalla: Home**

La pantalla de inicio del mockup de la Landing Page de SkillShare presenta un encabezado con las secciones principales del sitio y un bloque introductorio con la propuesta de valor. Incluye imágenes sobre la app, mostrando grupos, materias populares y archivos organizados, todo en una paleta de colores moderna.

<div align="center">
<img src="assets/images/C6/mock_up-home.png">
</div>

#### **Pantalla: Cómo funciona**

La pantalla muestra el proceso de cómo funciona SkillShare en tres pasos: crear un perfil personalizado, unirse o formar un grupo, y compartir recursos. A la izquierda, se ve un perfil de usuario con estadísticas de grupos, documentos y amigos. A la derecha, se detallan los pasos con íconos y texto explicativo, todo en una interfaz limpia y moderna.

<div align="center">
<img src="assets/images/C6/mock_up-how_it_works.png">
</div>

#### **Pantalla: Funcionalidades**

La pantalla destaca las principales funcionalidades de SkillShare, enfocándose en los **Study Groups** o grupos de estudio personalizados. Los usuarios pueden unirse o crear grupos según sus intereses, con características como colaboración en tiempo real, gestión de miembros y horarios flexibles. A la izquierda, iconos representan funciones adicionales como seguimiento de progreso, videollamadas, compartir documentos y más.

<div align="center">
<img src="assets/images/C6/mock_up-features.png">
</div>

#### **Pantalla: Planes**

La pantalla del mockup muestra dos bloques diferenciados por color: el plan gratuito a la izquierda y el premium a la derecha. El bloque premium tiene un fondo más oscuro y una etiqueta de **"Más popular"**. Ambos incluyen iconos y un botón para descargar la app.

<div align="center">
<img src="assets/images/C6/mock_up-pricing.png">
</div>

#### **Pantalla: Sobre nosotros**

La pantalla de "Sobre nosotros" tiene una imagen a la izquierda y un bloque de texto a la derecha. En la parte superior, hay botones de colores para navegar entre las secciones. El fondo es oscuro y los botones destacan con colores vibrantes.

<div align="center">
<img src="assets/images/C6/mock_up-about_us.png">
</div>

#### **Pantalla: Testimonios**

La pantalla de "Testimonios" presenta un testimonio destacado con la foto del usuario, su valoración y una breve descripción. Además, incluye un carrusel de imágenes para mostrar otros testimonios.

<div align="center">
<img src="assets/images/C6/mock_up-testimonials.png">
</div>

#### **Pantalla: Contáctanos**

El mockup de la pantalla muestra, en la sección de "Contáctanos", un formulario con campos para nombre, correo y mensaje, acompañado de botones para enviar la información. En el pie de página se incluyen los accesos a Navegación, Legal y Soporte en color azul, junto con los logos de las redes sociales.

<div align="center">
<img src="assets/images/C6/mock_up-contact_us.png">
</div>


### 5.1.4. Mobile Applications UX/UI Design
#### 5.1.4.1. Mobile Applications Wireframes

Los wireframes de skillshare representan una primera aproximación estructural al diseño de la plataforma, enfocándose en la organización del contenido y la disposición de los elementos clave en cada pantalla. Esta etapa busca definir cómo interactuarán los usuarios con las principales funcionalidades del sistema sin distraer con aspectos estéticos aún no definidos. Al priorizar la usabilidad y claridad en esta fase inicial, los wireframes permiten optimizar la experiencia del usuario y sentar las bases para el desarrollo de un diseño visual coherente y funcional.

#### **Pantalla: Login y Registro**

<div align="center">
<img src="assets\images\C5\LoginRegistro.png">
</div>

Las primeras pantallas del wireframe corresponden a las secciones de login y registro del usuario. Se muestran los elementos básicos para el proceso de registro, como campos para nombre, apellido y fecha de nacimiento. El diseño es simple y funcional, sin detalles visuales finales, enfocado en la disposición y estructura de los elementos clave para una fácil navegación.

#### **Pantalla: Registro**

<div align="center">
<img src="assets\images\C5\Registro.png">
</div>

Las siguientes pantallas del wireframe corresponden a la continuación del proceso de registro, donde el usuario ingresa datos más personales, como país, centro educativo y correo universitario. También se incluye un paso de verificación para asegurar la autenticidad de la información. El diseño sigue siendo limpio y funcional, con una disposición clara de los campos para facilitar el proceso de registro sin distracciones.

#### **Pantalla: Pantalla principal y grupos**

<div align="center">
<img src="assets\images\C5\PantallaPrincipal.png">
</div>

A continuación, se muestran los wireframes de la pantalla principal de la aplicación. En ella, se disponen elementos clave como los grupos destacados y los cursos populares en posiciones estratégicas. También se incluye una sección donde el usuario puede ver sus grupos actuales, en un diseño minimalista que destaca los grupos a los que pertenece. Además, se presenta una sección para contenido patrocinado, visible de manera clara pero sin sobrecargar la interfaz, manteniendo la estructura funcional y fácil de navegar.

#### **Pantalla: Perfil y configuracion**

<div align="center">
<img src="assets\images\C5\PerfilConfig.png">
</div>

A continuación, se muestran los wireframes para la visualización del perfil, donde el usuario puede ver información relevante como la cantidad de grupos, publicaciones y amigos. También se incluyen las insignias obtenidas y los grupos a los que pertenece. La siguiente pantalla corresponde a la edición de perfil, donde el usuario puede modificar sus datos personales, como nombre, usuario, fecha de nacimiento, centro educativo, teléfono, país y sexo, todo en un diseño claro y fácil de usar.

#### **Pantalla: Creación grupo y Grupos**

<div align="center">
<img src="assets\images\C5\CreacionGrupo.png">
</div>

A continuación, se muestran los wireframes para la creación de un grupo. En el primero, se detalla el formulario para crear un grupo, con campos como nombre, curso, tema, descripción y privacidad del grupo. En el segundo, se muestra cómo se visualizará un grupo dentro de la aplicación, con la foto del grupo, su descripción y otros elementos visuales, proporcionando una vista clara de la estructura del grupo una vez creado.

#### **Pantalla: Chats y llamadas**

<div align="center">
<img src="assets\images\C5\ChatsLlamadas.png">
</div>

Finalmente, se muestran los wireframes de las pantallas de chats y llamadas. En ellos, se puede ver la disposición de los elementos clave, como las conversaciones en los chats y las opciones para realizar o recibir llamadas, todo en un diseño simple y accesible para facilitar la interacción del usuario.

#### 5.1.4.2. Mobile Applications Wireflow Diagrams

### **User goal para Segmento: Docentes**
Como docente, quiero contar con un método de registro diferenciado del resto de los usuarios, que solicite información específica relacionada con mi rol, como institución educativa, área de enseñanza, nivel académico, etc.

<div align="center">
<img src="assets\images\C5\Diagram1.png">
</div>

Para que un docente pueda registrarse en la aplicación, se debe seguir una secuencia de pasos específicos diseñados para su rol. En primer lugar, al iniciar el proceso desde la pantalla de bienvenida, el usuario debe presionar el botón Start para comenzar el registro. A continuación, se le solicita completar información básica personal, como su nombre, apellido y fecha de nacimiento.
Luego, se accede a una sección donde el docente debe ingresar el nombre de su centro educativo, seguido de una pantalla destinada a la verificación de su profesión, permitiendo seleccionar el tipo de documento a presentar. Después de esto, se le solicita su correo institucional o universitario, el cual servirá para validar su pertenencia a una entidad académica.
Posteriormente, el docente debe subir un documento que acredite su rol educativo, como una constancia de trabajo o credencial docente. Luego, se completa el perfil con información adicional, como el nombre de usuario y el género.
Una vez completados todos los pasos, se muestra una pantalla final de confirmación indicando que el perfil ha sido configurado exitosamente, y se ofrece la opción de ir a la pantalla principal de la aplicación.

### **User goal para Segmento: Estudiantes**

Como estudiante, quiero contar con la opción de modificar mi perfil dentro de la aplicación, para poder editar datos personales como mi nombre, nombre de usuario, fecha de nacimiento, centro educativo, número de teléfono, país y género, en caso de que necesite actualizar o corregir mi información en cualquier momento.

<div align="center">
<img src="assets\images\C5\Diagram2.png">
</div>

Para que el estudiante pueda modificar su perfil, primero debe acceder a la pantalla principal de la aplicación. Desde ahí, debe seleccionar el ícono de configuración ubicado en la parte superior derecha, lo que lo llevará a la pantalla de su perfil. En esta pantalla, el estudiante podrá visualizar su información actual, como su nombre de usuario, los grupos a los que pertenece, sus publicaciones y sus insignias.
A continuación, debe presionar el ícono de editar perfil (el lápiz) para ingresar a la pantalla de edición. En esta pantalla, podrá modificar sus datos personales, tales como su nombre, apellido, fecha de nacimiento, centro educativo, teléfono, país y sexo. Una vez realizados los cambios deseados, el estudiante deberá presionar el botón Guardar Cambios para actualizar su perfil con la nueva información.
Este flujo permite al estudiante gestionar y actualizar su información de manera sencilla y clara.


#### 5.1.4.3. Mobile Applications Mock-ups

<div align="center">
<img src="assets\images\C5\Mockup1.png">
</div>

Este mockup muestra el proceso de registro en la plataforma SkillShare. En la primera pantalla, se presenta un formulario donde el usuario debe ingresar su correo electrónico, contraseña y confirmación de la contraseña. También ofrece la opción de registrarse con Google a través de un botón accesible.
En la siguiente pantalla, se solicita al usuario completar su perfil personal proporcionando su nombre, apellido, fecha de nacimiento y país. Esto permite personalizar la experiencia según la información del usuario.
En la tercera pantalla, el usuario debe configurar su nombre de usuario o apodo y seleccionar su género, para establecer su identidad en la plataforma.
Finalmente, en la última pantalla, el proceso se completa y se le notifica al usuario que su perfil ha sido creado con éxito. Se le invita a explorar la plataforma y unirse a grupos de estudio o compartir materiales con la comunidad.

<div align="center">
<img src="assets\images\C5\Mockup2.png">
</div>

<div align="center">
<img src="assets\images\C5\Mockup3.png">
</div>

Este mockup muestra el proceso de registro de un docente en SkillShare. Comienza con la solicitud de datos básicos como nombre, apellido, fecha de nacimiento y país. Luego, el docente completa su información académica, indicando su centro educativo y país. A continuación, se valida su profesión docente, permitiendo la verificación a través de un correo universitario o documento. Si opta por el correo, se valida con una confirmación de éxito.
El siguiente paso requiere cargar un documento universitario adicional para completar la validación profesional. Finalmente, el docente crea un nombre de usuario y selecciona su género, terminando el registro con un mensaje de éxito que confirma la creación de su perfil.

<div align="center">
<img src="assets\images\C5\Mockup4.png">
</div>

Este mockup muestra la página de inicio de SkillShare, enfocándose en la visualización de grupos y materias. En la parte superior, se destacan los "Featured Groups" (Grupos Destacados), donde se muestra la categoría, número de miembros y su fecha de inicio. Abajo, están los "Popular Subjects" (Materias Populares), con el número de estudiantes por materia.
En la siguiente pantalla, la sección "My Groups" (Mis Grupos) permite ver los grupos a los que el usuario está suscrito, con opciones para explorar más detalles. También incluye contenido patrocinado en un área separada. La interfaz está diseñada para facilitar la navegación y participación en grupos relacionados con el interés del usuario.

<div align="center">
<img src="assets\images\C5\Mockup5.png">
</div>

Este mockup muestra el perfil de usuario en SkillShare. A la izquierda, se presenta el nombre de usuario, foto de perfil, y estadísticas sobre los grupos a los que pertenece, publicaciones y amigos. También se destacan las insignias del usuario. Abajo, se muestran los grupos a los que el usuario está unido.
El siguiente es la interfaz permite editar el perfil, donde el usuario puede actualizar su información personal como nombre, apellidos, apodo, fecha de cumpleaños, centro educativo, teléfono, país y sexo. Al finalizar los cambios, puede guardarlos con el botón "Guardar Cambios".

<div align="center">
<img src="assets\images\C5\Mockup6.png">
</div>

Este mockup muestra el proceso para crear y gestionar un grupo de estudio en una aplicación. En la pantalla izquierda, el usuario llena los campos requeridos para crear un grupo: nombre, asignatura, tema y descripción. También se selecciona la privacidad del grupo, eligiendo entre "Público" o "Privado". Una vez completados estos pasos, el usuario puede hacer clic en "Crear Grupo".
El siguiente mockup se muestra el perfil del grupo ya creado. Incluye el nombre del grupo, una breve descripción del propósito, y los miembros activos. En la parte inferior, se encuentran los accesos a diferentes secciones del grupo: "Chat", "Recursos", "Quizzes" y "Llamadas", permitiendo gestionar la interacción y el contenido del grupo. Este flujo facilita la creación y administración de grupos de estudio dentro de la aplicación.

<div align="center">
<img src="assets\images\C5\Mockup7.png">
</div>

Este mockup muestra la interacción dentro de un grupo de estudio en la aplicación. A la izquierda, el chat de grupo permite a los miembros compartir mensajes.
El siguiente se muestra la sección de llamadas, donde los usuarios pueden iniciar una videollamada o una llamada de audio. También se incluyen las llamadas programadas, lo que permite a los miembros ver y unirse a sesiones de estudio o discusiones futuras. Este flujo facilita tanto la colaboración en tiempo real como la planificación de sesiones de estudio.


#### 5.1.4.4. Mobile Applications User Flow Diagrams

##### **User Goal 1: Registrarse en la plataforma**

Como usuario nuevo, quiero registrarme en la plataforma para acceder a los grupos de estudio y funciones personalizadas.

<div align="center">
<img src="assets\images\user_flow_diagrams\GOAL 01.png">
</div>

##### **User Goal 2: Buscar grupos de estudio**

Como estudiante, quiero buscar grupos de estudio según mi materia o nivel educativo para unirme a aquellos que coincidan con mis intereses.

<div align="center">
<img src="assets\images\user_flow_diagrams\GOAL 2.png">
</div>

##### **User Goal 3: Crear grupo de estudio**

Como docente o estudiante avanzado, quiero crear un grupo de estudio para organizar sesiones y compartir recursos con otros usuarios.

<div align="center">
<img src="assets\images\user_flow_diagrams\GOAL 2.png">
</div>

##### **User Goal 4: Participar en chat grupal**

Como miembro de un grupo, quiero enviar y recibir mensajes en el chat grupal para comunicarme en tiempo real con otros participantes.

<div align="center">
<img src="assets\images\user_flow_diagrams\GOAL 4.png">
</div>

##### **User Goal 5: Compartir y acceder a recursos**

Como estudiante o docente, quiero subir y descargar materiales en los grupos de estudio para compartir recursos de aprendizaje con los demás.

<div align="center">
<img src="assets\images\user_flow_diagrams\GOAL 5.png">
</div>

----

#### **Segmento 1: Estudiantes de educación superior**

Como usuario, quiero poder crear un grupo de estudio especificando la asignatura, el tema, la descripción y la privacidad del grupo para poder organizar sesiones de estudio con otros estudiantes.


<div align="center">
<img src="assets\images\C5\Diagram3.png">
</div>


#### **Segmento 2: Estudiantes de secundaria**

Como usuario, quiero poder cambiar entre el chat y las llamadas dentro de la aplicación para poder interactuar con mis amigos o compañeros de estudio de manera más dinámica.

<div align="center">
<img src="assets\images\C5\Diagram4.png">
</div>

#### 5.1.4.5. Mobile Applications Prototyping

[Texto del enlace](URL "Título opcional")

<br><br><br><br><br><br>


<!--
   CAP VI
-->

# Capítulo VI: Product Implementation, Validation & Deployment
## 6.1. Software Configuration Management
### 6.1.1. Software Development Environment Configuration

**1. Project Management**

La gestión de proyectos es fundamental en el desarrollo de software, ya que permite la organización y estructuración de las tareas necesarias para completar un proyecto. Las herramientas de gestión de proyectos permiten planificar, asignar y realizar un seguimiento de tareas, así como mejorar la colaboración en equipo y la comunicación.

| **Campo** | **Valor** |
|-----------|-----------|
| **Categoría** | Project Management |
| **Herramienta** | Jira (SaaS) |
| **Logo** | <img src="https://logolook.net/wp-content/uploads/2023/04/Jira-Logo-2017.png" width="150"> |
| **Descripción** | Jira es una plataforma de gestión de proyectos ampliamente utilizada, especialmente en proyectos de desarrollo de software que siguen metodologías ágiles como Scrum o Kanban. Esta herramienta permite la planificación de sprints, seguimiento de tareas en tiempo real, y la creación de reportes de rendimiento, facilitando la organización y optimización del trabajo en equipo. |
| **URL** | <a href="https://www.atlassian.com/es/software/jira" target="_blank">https://www.atlassian.com/es/software/jira</a> |

<br>

**2. Product UX/UI Design**

El diseño de interfaces de usuario (UI) y experiencia de usuario (UX) es esencial para crear aplicaciones y software intuitivos, estéticamente agradables y funcionales. Las herramientas de diseño UX/UI permiten la creación de prototipos visuales, wireframes y diseños interactivos, que pueden validarse con usuarios antes de la implementación. 

| **Campo** | **Valor** |
|-----------|-----------|
| **Categoría** | Product UX/UI Design |
| **Herramienta** | Figma |
| **Logo** | <img src="https://vectorseek.com/wp-content/uploads/2023/07/Figma-Logo-Png-Vector.svg-.png" width="60"> |
| **Descripción** | Figma es una herramienta de diseño colaborativo basada en la nube, ideal para la creación de prototipos de interfaces y diseños interactivos. Al estar en línea, permite la edición y revisión en tiempo real, facilitando la colaboración entre miembros del equipo desde cualquier lugar. Es especialmente útil en entornos ágiles donde el diseño y el desarrollo avanzan de manera simultánea. |
| **URL** | <a href="https://www.figma.com/es-la/" target="_blank">https://www.figma.com/es-la/</a> |

<br>

**3. Software Development**

El desarrollo de aplicaciones móviles requiere entornos y editores de código donde los desarrolladores puedan escribir, depurar y probar el código para diversas plataformas. Android Studio es la herramienta principal para el desarrollo de aplicaciones nativas de Android, mientras que Flutter, un framework de Google, permite crear aplicaciones multiplataforma con un solo código base. Visual Studio Code es utilizado para la creación de la landing page debido a su ligereza y capacidad para personalizar el entorno de desarrollo con extensiones específicas.

| **Campo** | **Valor** |
|-----------|-----------|
| **Categoría** | Desarrollo de Software Móvil |
| **Herramienta** | Android Studio |
| **Logo** | <img src="https://keycheck.dev/app-icons/android-studio.png" width="100"> |
| **Descripción** | Android Studio es el entorno de desarrollo integrado (IDE) oficial para el desarrollo de aplicaciones Android. Permite la creación de interfaces nativas usando Kotlin, y también es compatible con Flutter para el desarrollo multiplataforma con Dart. Android Studio incluye herramientas avanzadas de depuración, simuladores de dispositivos y análisis de rendimiento. |
| **Lenguajes** | Kotlin (para interfaces Android), Dart (para Flutter) |
| **URL** | <a href="https://developer.android.com/studio" target="_blank">https://developer.android.com/studio</a> |

<br>

| **Campo** | **Valor** |
|-----------|-----------|
| **Herramienta** | Visual Studio Code (VS Code) |
| **Logo** | <img src="https://i.pinimg.com/originals/24/42/f8/2442f8e6dbd772f0cf1dad8d803399bc.png" width="100"> |
| **Descripción** | Visual Studio Code es un editor de código ligero y potente, ideal para la creación de landing pages y aplicaciones web. Ofrece soporte para HTML, CSS, JavaScript y frameworks como React. Cuenta con integraciones para depuración, control de versiones y extensiones personalizadas, facilitando el trabajo en el desarrollo de la parte front-end de un proyecto. |
| **Usos** | Creación de landing page (HTML, CSS, JavaScript) |
| **URL** | <a href="https://code.visualstudio.com/Download" target="_blank"> https://code.visualstudio.com/Download</a> |

<br>

**4. Version Control**

El control de versiones es un componente esencial en el desarrollo de software, ya que permite gestionar y realizar un seguimiento de los cambios en el código fuente. Facilita la colaboración entre desarrolladores, ya que cada miembro del equipo puede trabajar en una copia del código y posteriormente fusionar los cambios. Esto es especialmente importante en proyectos con múltiples colaboradores, evitando conflictos y manteniendo un historial completo de modificaciones.

| **Campo** | **Valor** |
|-----------|-----------|
| **Categoría** | Version Control |
| **Herramienta** | Git (CLI/GUI) |
| **Logo** | <img src="https://creazilla-store.fra1.digitaloceanspaces.com/icons/3253808/git-icon-icon-md.png" width="100"> |
| **Descripción** | Git es un sistema de control de versiones es distribuido que permite gestionar el código localmente y compartirlo en repositorios remotos. Ofrece la posibilidad de crear ramas para trabajar en diferentes funcionalidades de manera simultánea, y posteriormente unirlas mediante operaciones como merge o rebase. |
| **URL** | <a href="https://git-scm.com/downloads" target="_blank">https://git-scm.com/downloads</a> |

<br>

| **Campo** | **Valor** |
|-----------|-----------|
| **Categoría** | Version Control |
| **Herramienta** | GitHub |
| **Logo** | <img src="https://th.bing.com/th/id/R.d3c974f05804e0b1e6eb7ff2564944e8?rik=xjfUeUs1lMo8FA&pid=ImgRaw&r=0" width="100"> |
| **Descripción** | GitHub es una plataforma basada en la nube que utiliza Git para la gestión de repositorios y facilita la colaboración entre equipos de desarrollo. Además de su funcionalidad de control de versiones, GitHub ofrece herramientas adicionales para la revisión de código, seguimiento de problemas y proyectos, e integración continua. |
| **URL** | <a href="https://github.com/" target="_blank">https://github.com/</a> |

<br>

### 6.1.2. Source Code Management

La gestión del código fuente es fundamental para el desarrollo colaborativo de cualquier proyecto de software. En esta sección, se establecerá un esquema claro de organización y control de versiones utilizando GitHub y el modelo de GitFlow. Esto garantizará una estructura organizada, controlada y accesible del código, con pautas para el seguimiento y manejo de cambios. Además, se definirán las convenciones para nombres de ramas, mensajes de commits, y se utilizará Semantic Versioning para las versiones del proyecto.

## 1. Establecimiento de repositorios en GitHub

Para organizar el código y pruebas de manera eficiente, se crearán repositorios específicos en GitHub, cada uno con una función concreta en el desarrollo y control de calidad del proyecto:

| **Repositorio** | **Descripción** | **URL** |
|-----------------|-----------------|---------|
| **Landing Page** | Este repositorio estará destinado exclusivamente al código de la página de aterrizaje (Landing Page), donde se registrará todo el desarrollo de la interfaz y los recursos Front-End. | https://github.com/ThinkUp-SkillShare/skillshare.github.io |
| **Pruebas de Aceptación** | En este repositorio se almacenarán los archivos .feature, que definen las pruebas de aceptación en formato Gherkin, permitiendo validar que las funcionalidades desarrolladas cumplen con los requisitos especificados. | https://github.com/ThinkUp-SkillShare/acceptance-tests |
| **Backend Mobile Application** | Este repositorio contendrá el código del backend de la aplicación móvil, implementado en Java y utilizando APIs RESTful. Incluirá la lógica de negocio, el procesamiento de datos y la comunicación con la base de datos necesaria para la interacción con los servicios móviles. | https://github.com/ThinkUp-SkillShare/backend-mobile-application |
| **Kotlin Mobile Application** | Este repositorio albergará el código de la aplicación móvil desarrollada en Kotlin. Se centrará en la interfaz de usuario, funcionalidades específicas para Android y la integración con los servicios backend a través de APIs RESTful. | https://github.com/ThinkUp-SkillShare/kotlin-mobile-application |
| **Flutter Mobile Application** | Este repositorio almacenará el código de la aplicación móvil desarrollada en Flutter. Contendrá la lógica de interfaz de usuario y la integración de la aplicación con los servicios backend, ofreciendo soporte tanto para Android como para iOS. | https://github.com/ThinkUp-SkillShare/flutter-mobile-application |
| **Project Report** | Este repositorio centralizará toda la documentación del proyecto, incluyendo el modelo de negocio, Lean UX, definición de la problemática, entrevistas a usuarios, hipótesis, validaciones y demás artefactos de diseño. Su objetivo es mantener un registro formal del proceso de ideación y definición del producto. | https://github.com/ThinkUp-SkillShare/skillshare-project-report |

<br>

## 2. Workflow de control de versiones

Para garantizar que el flujo de trabajo y la integración de cambios sean efectivos y organizados, se implementará el modelo GitFlow. Este modelo establece una estructura de ramas específica que facilita el desarrollo paralelo y la administración de versiones.

### Estructura de ramas en GitFlow:

| **Nombre de la rama** | **Descripción** |
|-----------------------|-----------------|
| **Main Branch (master)** | Es la rama principal que contiene el código en estado de producción. Solo los cambios completamente probados y listos para ser liberados en producción se integrarán aquí. |
| **Develop Branch (develop)** | En esta rama se integran las funcionalidades en desarrollo. Sirve como base para el trabajo en curso antes de ser incorporado a la master. |
| **Feature Branches (feature/\*)** | Para cada nueva funcionalidad o cambio importante, se debe crear una rama de funcionalidad derivada de develop. Esto permite que las funcionalidades se desarrollen de forma aislada. Ejemplo: feature/nueva-funcionalidad |
| **Release Branches (release/\*)** | Estas ramas se crean para preparar versiones próximas a lanzarse. Facilitan la corrección de errores menores y las pruebas antes de liberar la versión en master. Ejemplo: release/v1.0.0 |
| **Hotfix Branches (hotfix/\*)** | Ramas utilizadas para aplicar correcciones urgentes en el código de producción. Se crean a partir de master y se integran de vuelta en main y develop. Ejemplo: hotfix/urgent-fix |

### Convenciones para nombres de ramas

| **Tipo de Rama** | **Formato** | **Ejemplo** |
|------------------|-------------|-------------|
| **Feature Branches** | feature/nombre-descriptivo | feature/user-authentication |
| **Release Branches** | release/x.y.z | release/v1.0.0 |
| **Hotfix Branches** | hotfix/nombre-descriptivo | hotfix/login-error |

<br>

## 3. Versionado semántico (Semantic Versioning)

Para mantener un control claro y estructurado de las versiones liberadas, se empleará Semantic Versioning 2.0.0. Esta convención de nomenclatura consiste en tres números: Major.Minor.Patch:

| **Componente** | **Descripción** |
|----------------|-----------------|
| **Major** | Indica una versión con cambios que pueden ser incompatibles con versiones anteriores. |
| **Minor** | Utilizado para nuevas funcionalidades que sean compatibles con versiones previas. |
| **Patch** | Para modificaciones menores o correcciones de errores que no alteran la funcionalidad. |

**Ejemplos:**
- v1.0.0 – Primera versión estable lanzada al público
- v1.1.0 – Nueva funcionalidad añadida
- v1.1.1 – Pequeña corrección de errores

<br>

## 4. Convenciones de commits (Conventional Commits)

Para mantener claridad y consistencia en los mensajes de commit, se utilizará el estándar Conventional Commits. Este sistema ayuda a identificar fácilmente el tipo de cambio realizado en cada commit, lo cual facilita la revisión del historial de cambios y la integración continua.

| **Tipo de Cambio** | **Descripción** | **Ejemplo** |
|--------------------|-----------------|-------------|
| **feat** | Indica la implementación de una nueva funcionalidad. | `feat: agregar barra de navegación a la página de inicio` |
| **fix** | Para resolver un error. | `fix: corregir error de validación en formulario de contacto` |
| **docs** | Modificaciones en la documentación. | `docs: actualizar guía de instalación` |
| **style** | Cambios de estilo que no afectan el código funcional. | `style: mejorar el formato de los archivos CSS` |
| **refactor** | Cambios de código que no agregan funcionalidades nuevas ni corrigen errores. | `refactor: optimizar la lógica de la función de búsqueda` |
| **test** | Añadir o modificar pruebas. | `test: añadir pruebas unitarias para la función de autenticación` |

<br><br>

### 6.1.3. Source Code Style Guide & Conventions

En nuestro proyecto SkillShare, hemos adoptado un stack tecnológico moderno y robusto que incluye tecnologías para el backend, la aplicación móvil y el desarrollo de la landing page. La organización y estandarización del código aseguran que el desarrollo sea consistente, fácil de mantener y comprensible para cualquier miembro del equipo que trabaje en el proyecto.

## Stack Tecnológico

| **Área** | **Tecnologías** | **Propósito** |
|----------|-----------------|---------------|
| **Backend - API RESTful** | Java, Spring Boot, Spring Security, Spring Data JPA | Servicios backend para gestión de usuarios, grupos de estudio, chat y recursos compartidos |
| **Aplicación Móvil - Android** | Kotlin, Jetpack Compose, Retrofit, Room | Aplicación nativa Android con interfaz moderna y eficiente |
| **Aplicación Móvil - Multiplataforma** | Flutter, Dart, Provider/Bloc | Aplicación multiplataforma para iOS y Android con UI consistente |
| **Landing Page** | HTML5, CSS3, JavaScript | Página de aterrizaje estática con diseño responsive e interactividad |

<br>

## Convenciones para Java Spring Boot (Backend)

### Estructura de Proyecto Spring Boot

| **Paquete** | **Propósito** |
|-------------|---------------|
| `com.thinkup.skillshare.config/` | Configuraciones de la aplicación |
| `com.thinkup.skillshare.controller/` | Controladores REST |
| `com.thinkup.skillshare.service/` | Lógica de negocio |
| `com.thinkup.skillshare.repository/` | Acceso a datos |
| `com.thinkup.skillshare.model/` | Entidades JPA |
| `com.thinkup.skillshare.dto/` | Data Transfer Objects |
| `com.thinkup.skillshare.exception/` | Manejo de excepciones |
| `com.thinkup.skillshare.security/` | Configuración de seguridad |
| `com.thinkup.skillshare.util/` | Utilidades |

### Nomenclatura Java Spring Boot

| **Tipo** | **Convención** | **Ejemplo** |
|----------|----------------|-------------|
| **Controladores** | PascalCase con sufijo Controller | `StudyGroupController` |
| **Servicios** | PascalCase con sufijo Service | `StudyGroupService` |
| **Entidades** | PascalCase | `StudyGroup`, `User`, `Resource` |
| **Repositorios** | PascalCase con sufijo Repository | `StudyGroupRepository` |
| **DTOs** | PascalCase con sufijo Dto | `CreateStudyGroupRequestDto` |
| **Métodos** | camelCase descriptivo | `findGroupsBySubject()` |

#### Ejemplo

*Controladores*
```java
@RestController
@RequestMapping("/api/v1/study-groups")
@Validated
public class StudyGroupController {
    
    private final StudyGroupService studyGroupService;
    
    @Autowired
    public StudyGroupController(StudyGroupService studyGroupService) {
        this.studyGroupService = studyGroupService;
    }
    
    @GetMapping
    public ResponseEntity<List<StudyGroupDto>> getAllStudyGroups(
            @RequestParam(required = false) String subject) {
        List<StudyGroupDto> groups = studyGroupService.findGroupsBySubject(subject);
        return ResponseEntity.ok(groups);
    }
    
    @PostMapping
    public ResponseEntity<StudyGroupDto> createStudyGroup(
            @Valid @RequestBody CreateStudyGroupRequestDto request,
            @AuthenticationPrincipal UserDetails userDetails) {
        StudyGroupDto created = studyGroupService.createStudyGroup(request, userDetails.getUsername());
        return ResponseEntity.status(HttpStatus.CREATED).body(created);
    }
}
```

*Servicios*
```java
@Service
@Transactional
public class StudyGroupService {
    
    private final StudyGroupRepository studyGroupRepository;
    private final UserService userService;
    
    @Autowired
    public StudyGroupService(StudyGroupRepository studyGroupRepository, 
                            UserService userService) {
        this.studyGroupRepository = studyGroupRepository;
        this.userService = userService;
    }
    
    public List<StudyGroupDto> findGroupsBySubject(String subject) {
        if (subject != null && !subject.isEmpty()) {
            return studyGroupRepository.findBySubjectAndActiveTrue(subject)
                    .stream()
                    .map(this::convertToDto)
                    .collect(Collectors.toList());
        }
        return studyGroupRepository.findAllByActiveTrue()
                .stream()
                .map(this::convertToDto)
                .collect(Collectors.toList());
    }
    
    @Transactional
    public StudyGroupDto createStudyGroup(CreateStudyGroupRequestDto request, String username) {
        User creator = userService.findByUsername(username);
        StudyGroup studyGroup = new StudyGroup();
        studyGroup.setName(request.getName());
        studyGroup.setSubject(request.getSubject());
        studyGroup.setCreator(creator);
        studyGroup.setActive(true);
        
        StudyGroup saved = studyGroupRepository.save(studyGroup);
        return convertToDto(saved);
    }
    
    private StudyGroupDto convertToDto(StudyGroup studyGroup) {
        // Implementation
        return new StudyGroupDto();
    }
}
```

*Entidades*
```java
@Entity
@Table(name = "study_groups")
public class StudyGroup {
    
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;
    
    @Column(nullable = false, length = 100)
    private String name;
    
    @Column(nullable = false, length = 50)
    private String subject;
    
    @ManyToOne(fetch = FetchType.LAZY)
    @JoinColumn(name = "creator_id", nullable = false)
    private User creator;
    
    @ManyToMany
    @JoinTable(
        name = "study_group_members",
        joinColumns = @JoinColumn(name = "study_group_id"),
        inverseJoinColumns = @JoinColumn(name = "user_id")
    )
    private Set<User> members = new HashSet<>();
    
    @Column(nullable = false)
    private Boolean active = true;
    
    @CreatedDate
    @Column(nullable = false, updatable = false)
    private LocalDateTime createdAt;
    
    // Getters and Setters
}
```

### Anotaciones Spring Boot

| **Anotación** | **Propósito** |
|---------------|---------------|
| `@RestController` | Define controladores REST |
| `@Service` | Define servicios de negocio |
| `@Repository` | Define repositorios de datos |
| `@Entity` | Define entidades JPA |
| `@Transactional` | Manejo de transacciones |
| `@Validated` | Validación de parámetros |
| `@AuthenticationPrincipal` | Inyectar usuario autenticado |

### Convenciones de Código Java

| **Aspecto** | **Convención** |
|-------------|----------------|
| **Inyección de Dependencias** | Constructor injection preferido |
| **Manejo de Excepciones** | Usar `@ControllerAdvice` para manejo global |
| **Logging** | Usar SLF4J con niveles apropiados |
| **Validación** | Usar Bean Validation (Jakarta) |

<br>

## Convenciones para Kotlin (Aplicación Android)

### Estructura de Proyecto Kotlin

| **Paquete** | **Propósito** |
|-------------|---------------|
| `com.thinkup.skillshare.ui/` | Componentes de UI (Activities, Fragments, Composables) |
| `com.thinkup.skillshare.viewmodel/` | ViewModels para arquitectura MVVM |
| `com.thinkup.skillshare.data/` | Capa de datos (repositories, data sources) |
| `com.thinkup.skillshare.domain/` | Casos de uso y lógica de dominio |
| `com.thinkup.skillshare.model/` | Modelos de datos |
| `com.thinkup.skillshare.network/` | Cliente API y servicios de red |
| `com.thinkup.skillshare.database/` | Base de datos local (Room) |
| `com.thinkup.skillshare.util/` | Utilidades y extensiones |

### Nomenclatura Kotlin

| **Tipo** | **Convención** | **Ejemplo** |
|----------|----------------|-------------|
| **Activities** | PascalCase con sufijo Activity | `StudyGroupListActivity` |
| **Fragments** | PascalCase con sufijo Fragment | `GroupDetailFragment` |
| **Composables** | PascalCase sin sufijo | `StudyGroupCard`, `ChatScreen` |
| **ViewModels** | PascalCase con sufijo ViewModel | `StudyGroupViewModel` |
| **Repositorios** | PascalCase con sufijo Repository | `StudyGroupRepository` |
| **Clases** | PascalCase | `StudyGroup`, `Message` |
| **Funciones** | camelCase descriptivo | `loadStudyGroups()`, `sendMessage()` |
| **Propiedades** | camelCase | `studyGroups`, `isLoading` |
| **Constantes** | UPPER_SNAKE_CASE | `MAX_GROUP_SIZE` |

<br>

#### Ejemplo

*Composables (Jetpack Compose)*
```kotlin
@Composable
fun StudyGroupCard(
    studyGroup: StudyGroup,
    onCardClick: (StudyGroup) -> Unit,
    modifier: Modifier = Modifier
) {
    Card(
        modifier = modifier
            .fillMaxWidth()
            .clickable { onCardClick(studyGroup) }
            .padding(8.dp),
        elevation = CardDefaults.cardElevation(defaultElevation = 4.dp)
    ) {
        Column(
            modifier = Modifier.padding(16.dp)
        ) {
            Text(
                text = studyGroup.name,
                style = MaterialTheme.typography.titleMedium,
                fontWeight = FontWeight.Bold
            )
            
            Spacer(modifier = Modifier.height(4.dp))
            
            Text(
                text = studyGroup.subject,
                style = MaterialTheme.typography.bodyMedium,
                color = MaterialTheme.colorScheme.secondary
            )
            
            Spacer(modifier = Modifier.height(8.dp))
            
            Row(
                horizontalArrangement = Arrangement.SpaceBetween,
                modifier = Modifier.fillMaxWidth()
            ) {
                Text(
                    text = "${studyGroup.members.size} miembros",
                    style = MaterialTheme.typography.bodySmall
                )
                Text(
                    text = studyGroup.createdAt.format(DateTimeFormatter.ofPattern("dd/MM/yyyy")),
                    style = MaterialTheme.typography.bodySmall
                )
            }
        }
    }
}
```

*ViewModels*
```kotlin
@HiltViewModel
class StudyGroupViewModel @Inject constructor(
    private val studyGroupRepository: StudyGroupRepository,
    private val savedStateHandle: SavedStateHandle
) : ViewModel() {
    
    private val _studyGroups = MutableStateFlow<List<StudyGroup>>(emptyList())
    val studyGroups: StateFlow<List<StudyGroup>> = _studyGroups.asStateFlow()
    
    private val _isLoading = MutableStateFlow(false)
    val isLoading: StateFlow<Boolean> = _isLoading.asStateFlow()
    
    private val _error = MutableStateFlow<String?>(null)
    val error: StateFlow<String?> = _error.asStateFlow()
    
    init {
        loadStudyGroups()
    }
    
    fun loadStudyGroups(subject: String? = null) {
        viewModelScope.launch {
            _isLoading.value = true
            try {
                studyGroupRepository.getStudyGroups(subject)
                    .collect { result ->
                        when (result) {
                            is Result.Success -> {
                                _studyGroups.value = result.data
                                _error.value = null
                            }
                            is Result.Error -> {
                                _error.value = result.exception.message
                            }
                        }
                    }
            } catch (e: Exception) {
                _error.value = e.message
            } finally {
                _isLoading.value = false
            }
        }
    }
    
    fun joinStudyGroup(groupId: Long) {
        viewModelScope.launch {
            try {
                studyGroupRepository.joinGroup(groupId)
                loadStudyGroups()
            } catch (e: Exception) {
                _error.value = "Error al unirse al grupo: ${e.message}"
            }
        }
    }
}
```

*Repositorios*
```kotlin
class StudyGroupRepository @Inject constructor(
    private val apiService: StudyGroupApiService,
    private val studyGroupDao: StudyGroupDao
) {
    
    fun getStudyGroups(subject: String? = null): Flow<Result<List<StudyGroup>>> = flow {
        try {
            // Try to get from local database first
            val localGroups = studyGroupDao.getGroups(subject).first()
            emit(Result.Success(localGroups))
            
            // Fetch from API
            val response = if (subject != null) {
                apiService.getStudyGroupsBySubject(subject)
            } else {
                apiService.getAllStudyGroups()
            }
            
            if (response.isSuccessful) {
                response.body()?.let { groups ->
                    studyGroupDao.insertAll(groups)
                    emit(Result.Success(groups))
                }
            }
        } catch (e: Exception) {
            emit(Result.Error(e))
        }
    }
    
    suspend fun joinGroup(groupId: Long) {
        val response = apiService.joinStudyGroup(groupId)
        if (!response.isSuccessful) {
            throw Exception("Error al unirse al grupo")
        }
    }
}
```

<br>

### Convenciones de Código Kotlin

| **Aspecto** | **Convención** |
|-------------|----------------|
| **Null Safety** | Usar operadores `?.`, `?:`, y `!!` apropiadamente |
| **Data Classes** | Preferir para modelos simples |
| **Extension Functions** | Usar para funcionalidad reutilizable |
| **Coroutines** | Usar para operaciones asíncronas |
| **StateFlow/SharedFlow** | Preferir sobre LiveData en nuevos proyectos |

<br>

## Convenciones para Flutter (Aplicación Multiplataforma)

### Estructura de Proyecto Flutter

| **Directorio** | **Propósito** |
|----------------|---------------|
| `lib/main.dart` | Punto de entrada de la aplicación |
| `lib/screens/` | Pantallas principales de la aplicación |
| `lib/widgets/` | Widgets reutilizables |
| `lib/models/` | Modelos de datos |
| `lib/providers/` | Providers para gestión de estado |
| `lib/services/` | Servicios (API, local storage) |
| `lib/utils/` | Utilidades y constantes |
| `lib/theme/` | Configuración de tema y estilos |
| `assets/` | Recursos estáticos |

<br>

### Nomenclatura Flutter/Dart

| **Tipo** | **Convención** | **Ejemplo** |
|----------|----------------|-------------|
| **Archivos** | snake_case | `study_group_screen.dart` |
| **Clases** | PascalCase | `StudyGroupScreen`, `GroupCard` |
| **Funciones/Métodos** | camelCase | `loadStudyGroups()`, `onGroupSelected()` |
| **Variables** | camelCase | `studyGroups`, `isLoading` |
| **Constantes** | lowerCamelCase | `primaryColor`, `apiBaseUrl` |
| **Privados** | Prefijo `_` | `_loadData()`, `_controller` |

<br>

#### Ejemplo

*Screens*
```dart
class StudyGroupListScreen extends StatefulWidget {
  const StudyGroupListScreen({Key? key}) : super(key: key);

  @override
  State<StudyGroupListScreen> createState() => _StudyGroupListScreenState();
}

class _StudyGroupListScreenState extends State<StudyGroupListScreen> {
  late final StudyGroupProvider _studyGroupProvider;
  bool _isLoading = false;
  String? _errorMessage;

  @override
  void initState() {
    super.initState();
    _studyGroupProvider = Provider.of<StudyGroupProvider>(context, listen: false);
    _loadStudyGroups();
  }

  Future<void> _loadStudyGroups() async {
    setState(() {
      _isLoading = true;
      _errorMessage = null;
    });

    try {
      await _studyGroupProvider.fetchStudyGroups();
    } catch (e) {
      setState(() {
        _errorMessage = 'Error al cargar grupos: $e';
      });
    } finally {
      setState(() {
        _isLoading = false;
      });
    }
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text('Grupos de Estudio'),
        actions: [
          IconButton(
            icon: const Icon(Icons.filter_list),
            onPressed: _showFilterDialog,
          ),
        ],
      ),
      body: _buildBody(),
      floatingActionButton: FloatingActionButton(
        onPressed: _navigateToCreateGroup,
        child: const Icon(Icons.add),
      ),
    );
  }

  Widget _buildBody() {
    if (_isLoading) {
      return const Center(child: CircularProgressIndicator());
    }

    if (_errorMessage != null) {
      return Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            Text(_errorMessage!),
            const SizedBox(height: 16),
            ElevatedButton(
              onPressed: _loadStudyGroups,
              child: const Text('Reintentar'),
            ),
          ],
        ),
      );
    }

    return Consumer<StudyGroupProvider>(
      builder: (context, provider, child) {
        final studyGroups = provider.studyGroups;

        if (studyGroups.isEmpty) {
          return const Center(
            child: Text('No hay grupos disponibles'),
          );
        }

        return RefreshIndicator(
          onRefresh: _loadStudyGroups,
          child: ListView.builder(
            padding: const EdgeInsets.all(8),
            itemCount: studyGroups.length,
            itemBuilder: (context, index) {
              return StudyGroupCard(
                studyGroup: studyGroups[index],
                onTap: () => _navigateToGroupDetail(studyGroups[index]),
              );
            },
          ),
        );
      },
    );
  }

  void _showFilterDialog() {
    // Implementation
  }

  void _navigateToCreateGroup() {
    Navigator.push(
      context,
      MaterialPageRoute(builder: (context) => const CreateStudyGroupScreen()),
    );
  }

  void _navigateToGroupDetail(StudyGroup group) {
    Navigator.push(
      context,
      MaterialPageRoute(
        builder: (context) => StudyGroupDetailScreen(studyGroup: group),
      ),
    );
  }
}
```

*Widgets*
```dart
class StudyGroupCard extends StatelessWidget {
  final StudyGroup studyGroup;
  final VoidCallback onTap;

  const StudyGroupCard({
    Key? key,
    required this.studyGroup,
    required this.onTap,
  }) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return Card(
      margin: const EdgeInsets.symmetric(vertical: 4, horizontal: 8),
      elevation: 2,
      child: InkWell(
        onTap: onTap,
        child: Padding(
          padding: const EdgeInsets.all(16),
          child: Column(
            crossAxisAlignment: CrossAxisAlignment.start,
            children: [
              Text(
                studyGroup.name,
                style: Theme.of(context).textTheme.titleMedium?.copyWith(
                      fontWeight: FontWeight.bold,
                    ),
              ),
              const SizedBox(height: 4),
              Text(
                studyGroup.subject,
                style: Theme.of(context).textTheme.bodyMedium?.copyWith(
                      color: Theme.of(context).colorScheme.secondary,
                    ),
              ),
              const SizedBox(height: 12),
              Row(
                mainAxisAlignment: MainAxisAlignment.spaceBetween,
                children: [
                  Row(
                    children: [
                      const Icon(Icons.people, size: 16),
                      const SizedBox(width: 4),
                      Text(
                        '${studyGroup.memberCount} miembros',
                        style: Theme.of(context).textTheme.bodySmall,
                      ),
                    ],
                  ),
                  Text(
                    _formatDate(studyGroup.createdAt),
                    style: Theme.of(context).textTheme.bodySmall,
                  ),
                ],
              ),
            ],
          ),
        ),
      ),
    );
  }

  String _formatDate(DateTime date) {
    return '${date.day}/${date.month}/${date.year}';
  }
}
```

*Providers*
```dart
class StudyGroupProvider with ChangeNotifier {
  final StudyGroupService _studyGroupService;
  
  List<StudyGroup> _studyGroups = [];
  bool _isLoading = false;
  String? _error;
  
  StudyGroupProvider(this._studyGroupService);
  
  List<StudyGroup> get studyGroups => List.unmodifiable(_studyGroups);
  bool get isLoading => _isLoading;
  String? get error => _error;
  
  Future<void> fetchStudyGroups({String? subject}) async {
    _isLoading = true;
    _error = null;
    notifyListeners();
    
    try {
      _studyGroups = await _studyGroupService.getStudyGroups(subject: subject);
      _error = null;
    } catch (e) {
      _error = e.toString();
      _studyGroups = [];
    } finally {
      _isLoading = false;
      notifyListeners();
    }
  }
  
  Future<void> createStudyGroup(CreateStudyGroupRequest request) async {
    try {
      final newGroup = await _studyGroupService.createStudyGroup(request);
      _studyGroups.add(newGroup);
      notifyListeners();
    } catch (e) {
      _error = e.toString();
      notifyListeners();
      rethrow;
    }
  }
  
  Future<void> joinStudyGroup(int groupId) async {
    try {
      await _studyGroupService.joinGroup(groupId);
      await fetchStudyGroups();
    } catch (e) {
      _error = e.toString();
      notifyListeners();
      rethrow;
    }
  }
}
```

<br>

### Convenciones de Código Flutter

| **Aspecto** | **Convención** |
|-------------|----------------|
| **Widget Keys** | Usar `Key` para identificar widgets cuando sea necesario |
| **Const Constructors** | Usar `const` para widgets inmutables |
| **BuildContext** | No guardar referencias, pasar como parámetro |
| **State Management** | Usar Provider, Bloc o Riverpod consistentemente |
| **Async Operations** | Usar `async`/`await` y `Future`/`Stream` |

<br>

## Convenciones para Landing Page

### Estructuración HTML

| **Elemento** | **Convención** |
|--------------|----------------|
| **Etiquetas Semánticas** | Usar `<header>`, `<main>`, `<nav>`, `<footer>`, `<section>` |
| **Atributos ARIA** | Implementar `role`, `aria-label`, `aria-expanded` |
| **Encabezados** | Jerarquía adecuada H1-H6 |
| **Formularios** | Etiquetas `label` asociadas a inputs |

#### Ejemplo
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="SkillShare - Red social para estudiantes que facilita el aprendizaje colaborativo y la formación de grupos de estudio">
    <title>SkillShare - Conecta, Aprende, Colabora</title>
    <link rel="stylesheet" href="styles/main.css">
</head>
<body>
    <header class="main-header">
        <nav class="main-nav" role="navigation" aria-label="Navegación Principal">
            <div class="nav-container">
                <a href="#" class="logo">
                    <img src="assets/logo.svg" alt="SkillShare Logo">
                </a>
                <ul class="nav-menu">
                    <li><a href="#features">Características</a></li>
                    <li><a href="#how-it-works">Cómo Funciona</a></li>
                    <li><a href="#testimonials">Testimonios</a></li>
                    <li><a href="#contact">Contacto</a></li>
                </ul>
                <button class="nav-toggle" aria-label="Abrir menú de navegación" aria-expanded="false">
                    <span></span>
                    <span></span>
                    <span></span>
                </button>
            </div>
        </nav>
    </header>
    
    <main class="main-content">
        <section class="hero-section" aria-labelledby="hero-title">
            <div class="hero-container">
                <h1 id="hero-title">Aprende Mejor en Comunidad</h1>
                <p class="hero-subtitle">
                    Únete a grupos de estudio, comparte recursos y alcanza tus metas académicas con SkillShare
                </p>
                <div class="hero-cta">
                    <a href="#download" class="cta-button cta-button--primary">Descargar App</a>
                    <a href="#how-it-works" class="cta-button cta-button--secondary">Conocer Más</a>
                </div>
            </div>
        </section>
        
        <section class="features-section" id="features" aria-labelledby="features-title">
            <div class="section-container">
                <h2 id="features-title">Características de SkillShare</h2>
                <div class="features-grid">
                    <article class="feature-card">
                        <div class="feature-card__icon">
                            <img src="assets/icons/groups.svg" alt="">
                        </div>
                        <h3 class="feature-card__title">Grupos de Estudio</h3>
                        <p class="feature-card__description">
                            Crea o únete a grupos según tus materias de interés
                        </p>
                    </article>
                    
                    <article class="feature-card">
                        <div class="feature-card__icon">
                            <img src="assets/icons/video.svg" alt="">
                        </div>
                        <h3 class="feature-card__title">Videollamadas Integradas</h3>
                        <p class="feature-card__description">
                            Estudia en tiempo real con tus compañeros
                        </p>
                    </article>
                    
                    <article class="feature-card">
                        <div class="feature-card__icon">
                            <img src="assets/icons/resources.svg" alt="">
                        </div>
                        <h3 class="feature-card__title">Recursos Compartidos</h3>
                        <p class="feature-card__description">
                            Accede a apuntes, quizzes y materiales de estudio
                        </p>
                    </article>
                </div>
            </div>
        </section>
    </main>
    
    <footer class="main-footer" role="contentinfo">
        <div class="footer-container">
            <div class="footer-section">
                <h3>SkillShare</h3>
                <p>by ThinkUp</p>
            </div>
            <div class="footer-section">
                <h4>Enlaces</h4>
                <ul>
                    <li><a href="#features">Características</a></li>
                    <li><a href="#download">Descargar</a></li>
                    <li><a href="#contact">Contacto</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <p>&copy; 2025 ThinkUp. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>
    
    <script src="scripts/main.js"></script>
</body>
</html>
```

<br>

### Convenciones CSS

| **Aspecto** | **Convención** |
|-------------|----------------|
| **Metodología** | BEM (Block Element Modifier) |
| **Variables CSS** | Definir en `:root` |
| **Responsive Design** | Mobile-first approach |
| **Organización** | Modular por componentes |

<br>

#### Ejemplo
```css
/* CSS Variables */
:root {
  /* Colors */
  --primary-color: #6366F1;
  --secondary-color: #8B5CF6;
  --accent-color: #EC4899;
  --text-primary: #1F2937;
  --text-secondary: #6B7280;
  --background-light: #F9FAFB;
  --background-white: #FFFFFF;
  
  /* Spacing */
  --spacing-xs: 8px;
  --spacing-sm: 16px;
  --spacing-md: 24px;
  --spacing-lg: 32px;
  --spacing-xl: 48px;
  
  /* Typography */
  --font-primary: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
  --font-size-base: 16px;
  --font-size-lg: 18px;
  --font-size-xl: 24px;
  --font-size-2xl: 32px;
  --font-size-3xl: 48px;
  
  /* Effects */
  --border-radius: 8px;
  --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  --transition: all 0.3s ease;
}

/* BEM Methodology for Naming Convention */
.hero-section {
  padding: var(--spacing-xl) var(--spacing-md);
  background: linear-gradient(135deg, var(--primary-color) 0%, var(--secondary-color) 100%);
  color: var(--background-white);
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero-section__title {
  font-size: var(--font-size-3xl);
  font-weight: 700;
  margin-bottom: var(--spacing-md);
  text-align: center;
}

.hero-section__subtitle {
  font-size: var(--font-size-lg);
  margin-bottom: var(--spacing-lg);
  text-align: center;
  opacity: 0.9;
}

.hero-section__cta {
  display: flex;
  gap: var(--spacing-sm);
  justify-content: center;
  flex-wrap: wrap;
}

/* Feature Cards */
.feature-card {
  background-color: var(--background-white);
  border-radius: var(--border-radius);
  padding: var(--spacing-lg);
  box-shadow: var(--box-shadow);
  transition: var(--transition);
  text-align: center;
}

.feature-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
}

.feature-card__icon {
  width: 64px;
  height: 64px;
  margin: 0 auto var(--spacing-md);
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: var(--background-light);
  border-radius: 50%;
}

.feature-card__title {
  font-size: var(--font-size-xl);
  color: var(--text-primary);
  margin-bottom: var(--spacing-sm);
}

.feature-card__description {
  font-size: var(--font-size-base);
  color: var(--text-secondary);
  line-height: 1.6;
}

/* CTA Buttons */
.cta-button {
  display: inline-block;
  padding: var(--spacing-sm) var(--spacing-lg);
  border-radius: var(--border-radius);
  font-weight: 600;
  text-decoration: none;
  transition: var(--transition);
  cursor: pointer;
  border: 2px solid transparent;
}

.cta-button--primary {
  background-color: var(--accent-color);
  color: var(--background-white);
}

.cta-button--primary:hover {
  background-color: #DB2777;
  transform: scale(1.05);
}

.cta-button--primary:focus {
  outline: 3px solid var(--accent-color);
  outline-offset: 2px;
}

.cta-button--secondary {
  background-color: transparent;
  color: var(--background-white);
  border-color: var(--background-white);
}

.cta-button--secondary:hover {
  background-color: var(--background-white);
  color: var(--primary-color);
}

/* Responsive Design - Mobile First */
@media (min-width: 768px) {
  .hero-section__title {
    font-size: 56px;
  }
  
  .features-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: var(--spacing-lg);
  }
}

@media (min-width: 1024px) {
  .features-grid {
    grid-template-columns: repeat(3, 1fr);
  }
  
  .hero-section {
    padding: var(--spacing-xl) var(--spacing-xl);
  }
}
```

<br>

### Convenciones JavaScript

| **Aspecto** | **Convención** |
|-------------|----------------|
| **Variables** | `const` para valores fijos, `let` para variables |
| **Funciones** | Nombres descriptivos en camelCase |
| **Event Listeners** | Usar event delegation cuando sea posible |
| **Módulos** | Organizar funcionalidad en módulos |
| **Comentarios** | JSDoc para funciones principales |

<br>

#### Ejemplo
```js
// Application Configuration
const APP_CONFIG = {
  selectors: {
    navigationToggle: '.nav-toggle',
    mobileMenu: '.nav-menu',
    ctaButtons: '.cta-button',
    contactForm: '#contact-form',
    featureCards: '.feature-card',
    heroSection: '.hero-section'
  },
  classes: {
    active: 'active',
    hidden: 'hidden',
    loading: 'loading',
    visible: 'visible'
  },
  breakpoints: {
    mobile: 768,
    tablet: 1024,
    desktop: 1280
  }
};

/**
 * Navigation Module
 * Handles mobile menu toggle and navigation interactions
 */
const NavigationModule = {
  /**
   * Initialize the navigation module
   */
  init() {
    this.bindEvents();
    this.setupSmoothScroll();
  },

  /**
   * Bind event listeners for navigation
   */
  bindEvents() {
    const toggleButton = document.querySelector(APP_CONFIG.selectors.navigationToggle);
    const mobileMenu = document.querySelector(APP_CONFIG.selectors.mobileMenu);

    if (toggleButton && mobileMenu) {
      toggleButton.addEventListener('click', () => {
        this.toggleMobileMenu(toggleButton, mobileMenu);
      });

      // Close menu when clicking outside
      document.addEventListener('click', (event) => {
        if (!event.target.closest('.main-nav')) {
          this.closeMobileMenu(toggleButton, mobileMenu);
        }
      });

      // Close menu on window resize
      window.addEventListener('resize', () => {
        if (window.innerWidth >= APP_CONFIG.breakpoints.mobile) {
          this.closeMobileMenu(toggleButton, mobileMenu);
        }
      });
    }
  },

  /**
   * Toggle mobile menu visibility
   * @param {HTMLElement} button - Toggle button element
   * @param {HTMLElement} menu - Menu element
   */
  toggleMobileMenu(button, menu) {
    const isActive = menu.classList.toggle(APP_CONFIG.classes.active);
    button.classList.toggle(APP_CONFIG.classes.active);
    
    // Update ARIA attributes for accessibility
    button.setAttribute('aria-expanded', isActive.toString());
    menu.setAttribute('aria-hidden', (!isActive).toString());
  },

  /**
   * Close mobile menu
   * @param {HTMLElement} button - Toggle button element
   * @param {HTMLElement} menu - Menu element
   */
  closeMobileMenu(button, menu) {
    menu.classList.remove(APP_CONFIG.classes.active);
    button.classList.remove(APP_CONFIG.classes.active);
    button.setAttribute('aria-expanded', 'false');
    menu.setAttribute('aria-hidden', 'true');
  },

  /**
   * Setup smooth scrolling for anchor links
   */
  setupSmoothScroll() {
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        
        if (target) {
          target.scrollIntoView({
            behavior: 'smooth',
            block: 'start'
          });
        }
      });
    });
  }
};

/**
 * Form Module
 * Handles form submissions and validation
 */
const FormModule = {
  /**
   * Initialize the form module
   */
  init() {
    this.bindEvents();
  },

  /**
   * Bind event listeners for forms
   */
  bindEvents() {
    const contactForm = document.querySelector(APP_CONFIG.selectors.contactForm);
    
    if (contactForm) {
      contactForm.addEventListener('submit', (event) => {
        this.handleFormSubmission(event);
      });
    }
  },

  /**
   * Handle form submission
   * @param {Event} event - Form submit event
   */
  async handleFormSubmission(event) {
    event.preventDefault();
    
    const form = event.target;
    const formData = new FormData(form);
    
    // Validate form
    if (!this.validateForm(form)) {
      this.showErrorMessage('Por favor completa todos los campos requeridos');
      return;
    }
    
    try {
      form.classList.add(APP_CONFIG.classes.loading);
      
      const response = await this.submitForm(formData);
      
      if (response.ok) {
        this.showSuccessMessage('¡Mensaje enviado exitosamente!');
        form.reset();
      } else {
        this.showErrorMessage('Error al enviar el mensaje. Intenta nuevamente.');
      }
    } catch (error) {
      console.error('Error submitting form:', error);
      this.showErrorMessage('Error de conexión. Verifica tu internet.');
    } finally {
      form.classList.remove(APP_CONFIG.classes.loading);
    }
  },

  /**
   * Validate form fields
   * @param {HTMLFormElement} form - Form to validate
   * @returns {boolean} - Validation result
   */
  validateForm(form) {
    const requiredFields = form.querySelectorAll('[required]');
    let isValid = true;
    
    requiredFields.forEach(field => {
      if (!field.value.trim()) {
        field.classList.add('error');
        isValid = false;
      } else {
        field.classList.remove('error');
      }
    });
    
    return isValid;
  },

  /**
   * Submit form data to API
   * @param {FormData} formData - Form data to submit
   * @returns {Promise<Response>} - Fetch response
   */
  async submitForm(formData) {
    return fetch('/api/contact', {
      method: 'POST',
      body: formData,
      headers: {
        'Accept': 'application/json'
      }
    });
  },

  /**
   * Show success notification
   * @param {string} message - Success message
   */
  showSuccessMessage(message) {
    this.showNotification(message, 'success');
  },

  /**
   * Show error notification
   * @param {string} message - Error message
   */
  showErrorMessage(message) {
    this.showNotification(message, 'error');
  },

  /**
   * Show notification to user
   * @param {string} message - Notification message
   * @param {string} type - Notification type (success, error)
   */
  showNotification(message, type) {
    const notification = document.createElement('div');
    notification.className = `notification notification--${type}`;
    notification.textContent = message;
    notification.setAttribute('role', 'alert');
    
    document.body.appendChild(notification);
    
    // Show notification
    setTimeout(() => {
      notification.classList.add(APP_CONFIG.classes.visible);
    }, 100);
    
    // Remove notification after 5 seconds
    setTimeout(() => {
      notification.classList.remove(APP_CONFIG.classes.visible);
      setTimeout(() => {
        notification.remove();
      }, 300);
    }, 5000);
  }
};

/**
 * Animation Module
 * Handles scroll-based animations and interactions
 */
const AnimationModule = {
  /**
   * Initialize the animation module
   */
  init() {
    this.setupIntersectionObserver();
  },

  /**
   * Setup Intersection Observer for scroll animations
   */
  setupIntersectionObserver() {
    const observerOptions = {
      threshold: 0.1,
      rootMargin: '0px 0px -100px 0px'
    };

    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('animate-in');
          observer.unobserve(entry.target);
        }
      });
    }, observerOptions);

    // Observe feature cards
    const featureCards = document.querySelectorAll(APP_CONFIG.selectors.featureCards);
    featureCards.forEach(card => {
      observer.observe(card);
    });
  }
};
```

<br>

## Formato del Código General

| **Lenguaje** | **Sangría** | **Límite Línea** | **Comillas** | **Puntos y Coma** |
|--------------|-------------|------------------|--------------|-------------------|
| **Java** | 4 espacios | 120 caracteres | Doble (`"`) | Obligatorio |
| **Kotlin** | 4 espacios | 120 caracteres | Doble (`"`) | Opcional (no usar) |
| **Dart/Flutter** | 2 espacios | 80 caracteres | Simple (`'`) | Obligatorio |
| **HTML/CSS/JS** | 2 espacios | 80 caracteres | HTML: Doble, JS: Simple | JS: Obligatorio |

<br>

## Organización de Archivos

### Estructura General del Proyecto

| **Directorio** | **Contenido** |
|----------------|---------------|
| `backend/` | API Spring Boot (Java) |
| `mobile-android/` | Aplicación Android (Kotlin) |
| `mobile-flutter/` | Aplicación multiplataforma (Flutter) |
| `landing-page/` | Landing page estática |
| `docs/` | Documentación del proyecto |

<br>

### Nomenclatura de Archivos

| **Tecnología** | **Convención** | **Ejemplo** |
|----------------|----------------|-------------|
| **Java** | PascalCase | `StudyGroupController.java` |
| **Kotlin** | PascalCase | `StudyGroupViewModel.kt` |
| **Dart/Flutter** | snake_case | `study_group_screen.dart` |
| **HTML/CSS/JS** | kebab-case | `main-styles.css`, `navigation.js` |

<br>

## Accesibilidad y SEO

| **Área** | **Requisitos** |
|----------|----------------|
| **Accesibilidad** | Contraste 4.5:1, ARIA labels, navegación por teclado, soporte para lectores de pantalla |
| **SEO** | Meta tags descriptivos, estructura semántica HTML5, Open Graph tags |
| **Performance** | Optimización de imágenes (WebP), lazy loading, minificación de recursos |
| **Mobile** | Diseño responsive, touch-friendly (mínimo 44x44px para botones) |
| **Internacionalización** | Soporte para múltiples idiomas (es, en) |

<br>

## Gestión de Estado

| **Plataforma** | **Herramienta** | **Uso** |
|----------------|-----------------|---------|
| **Kotlin (Android)** | StateFlow, ViewModel | Gestión de estado en arquitectura MVVM |
| **Flutter** | Provider, Bloc, Riverpod | Gestión centralizada de estado |
| **Backend** | Spring Context, JPA | Gestión de sesiones y transacciones |

<br>

## Manejo de Errores

| **Plataforma** | **Estrategia** |
|----------------|----------------|
| **Backend** | `@ControllerAdvice`, excepciones personalizadas, logging con SLF4J |
| **Kotlin** | Try-catch, Result sealed class, error states en ViewModel |
| **Flutter** | Try-catch, Either pattern, error widgets |
| **Landing Page** | Try-catch, user-friendly error messages, fallback UI |

<br>

## Uso de Gherkin

### Convenciones Gherkin

| **Aspecto** | **Convención** |
|-------------|----------------|
| **Idioma** | Español para todos los escenarios |
| **Palabras Clave** | `Given`, `When`, `Then`, `And`, `But` |
| **Estructura** | Background para configuración común |
| **Datos** | Tablas para múltiples datos de entrada |
| **Claridad** | Descripciones simples y directas |
| **Enfoque** | Centrado en el comportamiento del usuario |

<br>

### Ejemplo de Escenario Gherkin

```gherkin
Feature: Gestión de Grupos de Estudio
  Como estudiante registrado en SkillShare
  Quiero poder crear y unirme a grupos de estudio
  Para colaborar con otros estudiantes en mis materias

  Background:
    Given el usuario "juan@student.com" está autenticado en SkillShare
    And está en la pantalla principal de grupos de estudio

  Scenario: Crear nuevo grupo de estudio exitosamente
    Given el estudiante está en la página de gestión de grupos
    When selecciona la opción "Crear Grupo"
    And completa el formulario con los siguientes datos:
      | Campo     | Valor                    |
      | Nombre    | Cálculo I - Grupo Tarde  |
      | Materia   | Matemáticas              |
      | Horario   | Lunes y Miércoles 4-6pm  |
    And hace clic en "Crear Grupo"
    Then el sistema debe mostrar el mensaje "Grupo creado exitosamente"
    And el nuevo grupo debe aparecer en la lista de grupos
    And el estudiante debe ser el administrador del grupo

  Scenario: Unirse a un grupo de estudio existente
    Given existe un grupo de estudio llamado "Programación Web - Proyecto Final"
    And el grupo tiene 5 miembros activos
    When el estudiante busca "Programación Web"
    And selecciona el grupo "Programación Web - Proyecto Final"
    And hace clic en "Unirse al Grupo"
    Then el sistema debe mostrar "Te has unido al grupo exitosamente"
    And el estudiante debe aparecer en la lista de miembros del grupo
    And debe recibir una notificación de bienvenida

  Scenario: Filtrar grupos por materia
    Given existen los siguientes grupos de estudio:
      | Nombre              | Materia       |
      | Álgebra Avanzada    | Matemáticas   |
      | Física Cuántica     | Física        |
      | Química Orgánica    | Química       |
    When el estudiante selecciona el filtro de materia "Matemáticas"
    Then solo debe ver el grupo "Álgebra Avanzada"
    And no debe ver los grupos de otras materias

  Scenario: Intentar crear grupo sin completar campos obligatorios
    Given el estudiante está en el formulario de crear grupo
    When intenta crear un grupo sin completar el campo "Nombre"
    And hace clic en "Crear Grupo"
    Then el sistema debe mostrar el mensaje "El nombre del grupo es obligatorio"
    And el grupo no debe ser creado
```

<br><br>

### 6.1.4. Software Deployment Configuration

#### Landing Page

1. Se creó la organización del proyecto con el nombre ThinkUp.

<div align="center">

![organización](assets/images/deployment/organizacion.jpg)

</div>

2. Se generó un repositorio en GitHub para alojar la landing page del proyecto.

<div align="center">

![repositorio](assets/images/deployment/repositorio.jpg)

</div>

3. Se nombró el repositorio siguiendo la convención: debe finalizar en .github.io para habilitar GitHub Pages.

<div align="center">

![convension](assets/images/deployment/convension.jpg)

</div>

4. En la sección **Settings > Pages**, se configuró la rama de despliegue (Deployment Branch), y se obtuvo el enlace público para acceder a la landing page.

<div align="center">

![configuracion](assets/images/deployment/configuracion.jpg)

</div>

5. Se registraron las evidencias de los commits realizados y subidos al repositorio.

<div align="center">

![commits](assets/images/deployment/commits.jpg)

</div>

**LINK:** https://thinkup-skillshare.github.io/skillshare.github.io/

#### Web Services

<!-- COLOCAR DESPLIEGUE  -->

#### Mobile Applications

<!-- COLOCAR DESPLIEGUE  -->

<br><br>

## 6.2. Landing Page & Mobile Application Implementation
### 6.2.1. Sprint 1
#### 6.2.1.1. Sprint Planning 1
Claro, aquí tienes la sección completa con el **Sprint Review** y la **Retrospectiva** redactadas como si el Sprint 1 ya se hubiera completado.

---

**5.2. Landing Page, Services & Applications Implementation**

**5.2.1. Sprint 1**

**5.2.1.1. Sprint Planning**

El Sprint Planning es la reunión que da inicio al sprint y define qué se va a construir y cómo se logrará. Reúne al equipo Scrum para establecer un objetivo claro (Sprint Goal), seleccionar las historias de usuario más relevantes y descomponerlas en tareas concretas. Esta planificación asegura un enfoque común, organiza el trabajo de forma eficiente y alinea al equipo con la entrega de valor al usuario.

A continuación se mostrará la tabla del Sprint Planning:

| **Sprint #** | Sprint 1 |
| :--- | :--- |
| **Sprint Planning Background** | |
| **Date** | 2025-10-04 |
| **Hour** | 10:30 a. m. |
| **Location** | Virtual |
| **Prepared By** | Jhosep Jamil Argomedo Camacho |
| **Attendees (to planning meeting)** | Jhosep Jamil Argomedo Camacho, Carlos Alberto González Custodio, Renso Anthony Julca Cruz, Sebastian Ramirez Tello |
| **Sprint n - 1 Review Summary** | Durante el Sprint 1, el equipo logró con éxito la implementación de los cimientos de la plataforma SkillShare. Se desarrolló y desplegó completamente la Landing Page, incluyendo todas las secciones planificadas (Hero, How it works?, Features, Pricing, About us, Testimonials, Contact us y Footer). En el backend, se implementaron con éxito los módulos de IAM (Login y Registro) y las entidades base (Teacher, Student, File, Group), estableciendo una base de código sólida y segura. En el frontend móvil, se completaron las pantallas core de Login, Register, Profile, Groups, Group Details y Chat para el segmento Docente, cumpliendo con los criterios de aceptación definidos. El equipo de desarrollo destacó la eficacia de la arquitectura inicial para facilitar la integración entre frontend y backend. |
| **Sprint n - 1 Retrospective Summary** | El equipo identificó varios aspectos positivos durante la retrospectiva del Sprint 1. Se destacó la excelente comunicación y colaboración en la resolución de bloqueos técnicos, particularmente durante la integración entre el backend y el frontend móvil. La definición clara de las historias de usuario y la utilización de herramientas de gestión como Jira fueron clave para mantener el flujo de trabajo. Como áreas de mejora, se señaló que la estimación inicial para la configuración del entorno de desarrollo backend fue demasiado optimista, lo que generó una pequeña demora inicial. Además, se acordó incrementar la frecuencia de los commits al repositorio para evitar conflictos de integración grandes y se propuso crear una guía de estilos de código más detallada para el frontend móvil para agilizar las revisiones de código en los próximos sprints. |
| **Sprint Goal & User Stories** | |
| **Sprint Goal** | Nuestro objetivo es establecer los cimientos técnicos y de presentación de SkillShare. Esto incluye el desarrollo de una Landing Page atractiva e informativa que comunique nuestro valor, junto con la implementación del sistema central de autenticación (IAM) y las pantallas móviles core para el segmento Docente. Creemos que esto proporciona una base sólida para la plataforma, permitiendo a los usuarios entender el servicio y a los docentes comenzar a interactuar con el sistema. <br><br> Esto se confirmará cuando: <br> 1. Un usuario visitante pueda navegar por la Landing Page y comprender los servicios de SkillShare a través de las secciones Hero, How it works?, Features, Pricing, About us, Testimonials, Contact us y Footer. <br> 2. Un usuario docente pueda registrarse e iniciar sesión de forma segura en la aplicación móvil. <br> 3. El backend exponga de manera segura y eficiente los endpoints críticos para el IAM (Login, Registro) y la gestión de entidades base (Teacher, Student, File, Group). |
| **Sprint Velocity** |  |
| **Sum of Story Points** |  |

<br>

#### 6.2.1.2. Sprint Backlog 1

Durante el Sprint 1, el objetivo principal fue sentar las bases técnicas y de presentación de SkillShare. Esto incluyó el desarrollo de una Landing Page atractiva e informativa para comunicar el valor de la plataforma a los visitantes, junto con la implementación del sistema central de autenticación (IAM) y las pantallas móviles core para el segmento Docente. Este trabajo establece una base sólida para el desarrollo futuro, permitiendo a los usuarios entender el servicio y a los docentes comenzar a interactuar con el sistema.

A continuación, se detalla la tabla de control de estado para el Sprint 1:

| User Story ID | Id | Title | Description | Estimation (Hours) | Assigned To | Status (To-do / In-Process / To-Review / Done) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **US-01** | **T-101** | **Desarrollar Formulario de Registro Frontend** | Implementar la interfaz de usuario del formulario de registro en la Landing Page con validaciones en tiempo real. | 5 | Frontend Dev | **Done** |
| | **T-102** | **Implementar Endpoint de Registro Backend** | Crear el endpoint POST `/api/auth/register` para recibir y validar datos del usuario, y crear la cuenta en la base de datos. | 6 | Backend Dev | **Done** |
| **US-02** | **T-104** | **Maquetar Sección "Cómo Funciona"** | Crear la estructura HTML y CSS para la sección con 3 pasos ilustrados, asegurando que sea responsive. | 4 | UX/UI Designer | **Done** |
| **US-04** | **T-105** | **Implementar Sección de Funcionalidades** | Desarrollar la sección que muestra íconos y descripciones de las funcionalidades principales (chat, videollamadas, etc.). | 5 | Frontend Dev | **Done** |
| **US-07** | **T-106** | **Desarrollar Formulario de Contacto** | Implementar el formulario de contacto frontend con validación y el endpoint backend para el envío de emails. | 4 | Full-Stack Dev | **Done** |
| **US-12** | **T-107** | **Construir Sección de Planes y Precios** | Maquetar y desarrollar la sección de precios con los planes Freemium, Premium e Institucional. | 6 | Frontend Dev | **Done** |
| **US-11** | **T-108** | **Implementar Footer Completo** | Desarrollar el footer con todos los enlaces organizados (Términos, Privacidad, Contacto, Redes Sociales). | 3 | Frontend Dev | **Done** |
| **EP-01 (Backend)** | **T-109** | **Modelar e Implementar Entidad 'User'** | Diseñar el esquema de base de datos y crear el modelo para la entidad 'User' (docente/estudiante). | 4 | Backend Dev | **Done** |
| | **T-110** | **Implementar Endpoint de Login** | Crear el endpoint POST `/api/auth/login` para autenticar usuarios y generar un token JWT. | 5 | Backend Dev | **Done** |
| | **T-111** | **Modelar e Implementar Entidad 'Group'** | Diseñar el esquema y crear el modelo para la entidad 'Group', incluyendo sus relaciones. | 5 | Backend Dev | **Done** |
| **US-21** | **T-112** | **Desarrollar Pantalla de Login (Móvil Docente)** | Implementar la pantalla de inicio de sesión para la app móvil del segmento docente. | 4 | Mobile Dev | **Done** |
| | **T-113** | **Desarrollar Pantalla de Registro (Móvil Docente)** | Implementar la pantalla de registro para la app móvil del segmento docente. | 5 | Mobile Dev | **Done** |
| **US-13** | **T-114** | **Desarrollar Pantalla de Perfil (Móvil Docente)** | Crear la pantalla donde el docente puede ver y editar la información de su perfil. | 6 | Mobile Dev | **Done** |
| **US-14** | **T-115** | **Desarrollar Pantalla de Lista de Grupos (Móvil Docente)** | Implementar la pantalla principal que lista los grupos a los que pertenece el docente. | 5 | Mobile Dev | **Done** |
| **US-15** | **T-116** | **Desarrollar Pantalla de Detalles de Grupo (Móvil Docente)** | Crear la pantalla que muestra la información detallada de un grupo específico y sus miembros. | 7 | Mobile Dev | **Done** |
| **US-24** | **T-117** | **Desarrollar Pantalla de Chat (Móvil Docente)** | Implementar la interfaz del chat integrado para que los docentes se comuniquen con sus grupos. | 8 | Mobile Dev | **Done** |

<br>

#### 6.2.1.3. Development Evidence for Sprint Review

He aquí la sección "Development Evidence for Sprint Review" con una presentación de los avances y un ejemplo de commit, siguiendo la estructura solicitada.

Esta sección documenta la evidencia tangible de los avances de implementación logrados durante el Sprint 1. Los principales avances incluyen la finalización de una Landing Page completamente funcional y receptiva que presenta los servicios de SkillShare, la implementación de los endpoints críticos del backend para la autenticación de usuarios (IAM) y la gestión de grupos, y el desarrollo de las pantallas móviles core para el segmento docente, incluyendo flujos de autenticación, gestión de perfil y navegación principal. El trabajo se gestionó a través de múltiples ramas de características en los repositorios correspondientes, integrándose finalmente a la rama principal tras su revisión y aprobación.

A continuación, se presenta una tabla con los commits representativos de esta implementación:

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| https://github.com/ThinkUp-SkillShare/skillshare.github.io | feature/add-core-sections | 43d49b5 | docs: add project documentation and license | --- | 06-10-25 |
| https://github.com/ThinkUp-SkillShare/skillshare.github.io | feature/add-core-sections | ec23d1a | feat: add navbar, hero and how-it-works sections | --- | 06-10-25 |
| https://github.com/ThinkUp-SkillShare/skillshare.github.io | feature/add-core-sections | 119cbb9 | feat: add features and pricing sections | --- | 07-10-25 |
| https://github.com/ThinkUp-SkillShare/skillshare.github.io | feature/add-core-sections | e8e8f23 | feat: add about us and testimonials section | --- | 08-10-25 |
| https://github.com/ThinkUp-SkillShare/skillshare.github.io | feature/add-core-sections | 999bf2d | feat: add contact form and footer | --- | 08-10-25 |
| https://github.com/ThinkUp-SkillShare/skillshare.github.io | feature/add-core-sections | 7ccabfb | feat: add language functionality and bug fixes | --- | 08-10-25 |
| https://github.com/ThinkUp-SkillShare/backend-mobile-application | main | 77a595a | feat: add the first version of the backend with core business endpoints | important endpoints: <br> ->  IAM <br> ->  Login <br> ->  Register <br> ->  Teacher <br> ->  Student | 10-10-25 |
| https://github.com/ThinkUp-SkillShare/kotlin-mobile-application | main | a244059 | feat: add core screens for the fourth segment (teachers) | Important screens: <br> log in <br> register <br> profile <br> edit <br> profile <br> groups <br> group details <br> chat | 10-10-25 |

<br>

#### 6.2.1.4. Execution Evidence for Sprint Review

He aquí la presentación para la sección "Execution Evidence for Sprint Review" del informe, lista para ser incluida como un capítulo.

El Sprint 1 culminó con éxito, logrando la implementación y entrega de los componentes fundamentales de la plataforma SkillShare. Se alcanzó el **Sprint Goal** al establecer una base sólida que incluye una **Landing Page completamente funcional**, el **sistema de autenticación (IAM)** en el backend y las **pantallas móviles core para el segmento docente**.

Como evidencia concreta de la ejecución, se han implementado y probado las siguientes vistas y funcionalidades:

*   **Landing Page de SkillShare:** Se desarrollaron todas las secciones clave, incluyendo Hero, How it works?, Features, Pricing, About us, Testimonials, Contact us y un Footer completo, ofreciendo una experiencia informativa y atractiva para el usuario visitante.
*   **Autenticación de Usuarios:** Se implementaron los endpoints de Login y Registro, permitiendo la creación segura de cuentas y el acceso a la plataforma.
*   **Aplicación Móvil Docente:** Se construyeron las pantallas esenciales para el flujo principal de un docente: Login, Registro, Perfil, Lista de Grupos, Detalles de Grupo y Chat integrado.

A continuación, se presentan capturas de pantalla que demuestran estos avances:

**Landing Page - Sección Hero y Navegación**

![Hero Section](assets/images/C6/landing_page-hero.png)

**Landing Page - Sección Download**

![Download Section](assets/images/C6/landing_page-download.png)

**Landing Page - Sección How it Works**

![How it works Section](assets/images/C6/landing_page-how_it_works.png)

**Landing Page - Sección Features**

![Features Section](assets/images/C6/landing_page-features.png)

**Landing Page - Sección Pricing**

![Pricing Section](assets/images/C6/landing_page-pricing.png)

**Landing Page - Sección About us**

![About us Section](assets/images/C6/landing_page-about_us.png)

**Landing Page - Sección Testimonials**

![Testimonials Section](assets/images/C6/landing_page-testimonials.png)

**Landing Page - Sección Contact us**

![Contact us Section](assets/images/C6/landing_page-contact_us.png)

**Landing Page - Sección Footer**

![Footer Section](assets/images/C6/landing_page-footer.png)

<br>

**Backend de los bounded context de SkillShare:**

![Backend 1](assets/images/C6/backend_1.png)
![Backend 2](assets/images/C6/backend_2.png)

<br>

**Mobile Application - Login**

<div align="center">
  <img src="assets/images/C6/mobile_application-login.png" width="350">
</div>

<br>

**Mobile Application - Register**

<div align="center">
  <img src="assets/images/C6/mobile_application-register-welcome.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-register-about_yourself.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-register-academic_world.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-register-verification_profession.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-register-university_document.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-register-university_email.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-register-validation_successful.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-register-personal_identity.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-register-all_done.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-profile_1.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-profile_2.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-profile-edit_profile.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-groups-groups_list.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-groups-groups_list.png" width="350">
</div>

<br>

<div align="center">
  <img src="assets/images/C6/mobile_application-register-chat.png" width="350">
</div>

<br> 

#### 6.2.1.5 Services Documentation Evidence for Sprint Review

Durante el Sprint 1, se implementaron y documentaron los servicios web fundamentales para el funcionamiento de SkillShare, estableciendo los cimientos del sistema de autenticación, gestión de usuarios, perfiles académicos y grupos de estudio. La documentación se ha elaborado utilizando la especificación OpenAPI, proporcionando una referencia clara y estandarizada para el consumo de los servicios por parte del frontend y las aplicaciones móviles.

A continuación se detallan los endpoints principales implementados en este sprint:

## **Endpoints de Autenticación (Auth)**

| Endpoint | Acción | Verbo HTTP | Sintaxis | Parámetros | Request Body | Response | Explicación |
|----------|--------|------------|----------|------------|---------------|----------|-------------|
| `/api/Auth/register` | Registrar nuevo usuario | POST | `POST /api/Auth/register` | Ninguno | `{ "name": "string", "email": "string", "passwordHash": "string", "studentProfile": {...} }` | `200 OK` | Endpoint para registro de nuevos usuarios con perfil de estudiante integrado |
| `/api/Auth/login` | Iniciar sesión | POST | `POST /api/Auth/login` | Ninguno | `{ "email": "string", "passwordHash": "string" }` | `200 OK` | Autenticación de usuarios existentes en la plataforma |

## **Endpoints de Gestión de Grupos**

| Endpoint | Acción | Verbo HTTP | Sintaxis | Parámetros | Request Body | Response | Explicación |
|----------|--------|------------|----------|------------|---------------|----------|-------------|
| `/api/Group` | Obtener todos los grupos | GET | `GET /api/Group` | Ninguno | - | `[{"id": 0, "name": "string", "tag": "string", ...}]` | Lista todos los grupos disponibles en el sistema |
| `/api/Group` | Crear nuevo grupo | POST | `POST /api/Group` | Ninguno | `{"name": "string", "tag": "string", ...}` | `{"id": 0, "name": "string", ...}` | Crea un nuevo grupo de estudio |
| `/api/Group/{id}` | Obtener grupo específico | GET | `GET /api/Group/{id}` | `id` (entero) | - | `{"id": 0, "name": "string", ...}` | Obtiene detalles de un grupo específico por ID |
| `/api/Group/{id}` | Actualizar grupo | PUT | `PUT /api/Group/{id}` | `id` (entero) | `{"name": "string", "tag": "string", ...}` | `200 OK` | Actualiza la información de un grupo existente |
| `/api/Group/{id}` | Eliminar grupo | DELETE | `DELETE /api/Group/{id}` | `id` (entero) | - | `200 OK` | Elimina un grupo del sistema |

## **Endpoints de Gestión de Archivos**

| Endpoint | Acción | Verbo HTTP | Sintaxis | Parámetros | Request Body | Response | Explicación |
|----------|--------|------------|----------|------------|---------------|----------|-------------|
| `/api/File` | Obtener archivos | GET | `GET /api/File` | Ninguno | - | `200 OK` | Lista los archivos disponibles |
| `/api/File/upload` | Subir archivo | POST | `POST /api/File/upload` | Ninguno | `multipart/form-data` | `200 OK` | Endpoint para subir archivos a la plataforma |
| `/api/File/{id}` | Obtener archivo | GET | `GET /api/File/{id}` | `id` (UUID) | - | `200 OK` | Descarga un archivo específico |
| `/api/File/{id}` | Eliminar archivo | DELETE | `DELETE /api/File/{id}` | `id` (UUID) | - | `200 OK` | Elimina un archivo del sistema |

## **Endpoints de Perfiles Académicos**

| Endpoint | Acción | Verbo HTTP | Sintaxis | Parámetros | Request Body | Response | Explicación |
|----------|--------|------------|----------|------------|---------------|----------|-------------|
| `/api/Student` | Obtener estudiantes | GET | `GET /api/Student` | Ninguno | - | `[{"id": 0, "name": "string", ...}]` | Lista todos los perfiles de estudiantes |
| `/api/Student` | Crear perfil estudiante | POST | `POST /api/Student` | Ninguno | `{"name": "string", "university": "string", ...}` | `{"id": 0, "name": "string", ...}` | Crea un perfil de estudiante |
| `/api/Student/{id}` | Obtener estudiante | GET | `GET /api/Student/{id}` | `id` (entero) | - | `{"id": 0, "name": "string", ...}` | Obtiene perfil específico de estudiante |
| `/api/Teaching` | Obtener docentes | GET | `GET /api/Teaching` | Ninguno | - | `[{"id": 0, "firstName": "string", ...}]` | Lista todos los perfiles de docentes |
| `/api/Teaching` | Crear perfil docente | POST | `POST /api/Teaching` | Ninguno | `{"firstName": "string", "institution": "string", ...}` | `{"id": 0, "firstName": "string", ...}` | Crea un perfil de docente verificado |

<br>

#### 6.2.1.6. Team Collaboration Insights during Sprint

Durante el Sprint 1, el equipo se enfocó en el desarrollo paralelo de tres componentes fundamentales: la Landing Page, los Web Services del backend y la aplicación móvil para el segmento docente. Utilizando GitHub como plataforma de control de versiones y colaboración, se logró mantener un flujo de trabajo organizado mediante el uso de branches de características y revisiones de código (pull requests).

## **Actividades de Implementación:**

### **Landing Page Development**
El equipo frontend implementó una landing page completa y responsive utilizando tecnologías web modernas. Se desarrollaron todas las secciones críticas incluyendo:
- **Hero Section** con llamado a la acción principal
- **How it Works** con los 3 pasos fundamentales de la plataforma
- **Features** mostrando las funcionalidades principales
- **Pricing** con los planes Freemium, Premium e Institucional
- Secciones de **About Us, Testimonials, Contact Us y Footer**

### **Backend Web Services**
El equipo backend construyó los servicios fundamentales utilizando .NET y Entity Framework:
- **Sistema de Autenticación (IAM)**: Endpoints de registro y login seguros
- **Gestión de Grupos**: CRUD completo para grupos de estudio
- **Gestión de Archivos**: Upload, download y eliminación de recursos
- **Perfiles Académicos**: Entidades para estudiantes y docentes
- **Documentación OpenAPI**: Especificación completa con Swagger UI

### **Aplicación Móvil Docente**
El equipo móvil desarrolló las pantallas core para el segmento docente:
- **Autenticación**: Pantallas de login y registro
- **Perfil**: Gestión de información del docente
- **Grupos**: Lista y detalles de grupos de estudio
- **Chat**: Interfaz de mensajería integrada

<br>

## **Analítica de Colaboración en GitHub:**

### Landing Page

**Comits**

![Landing Page](assets/images/C6/landing_page-commits.png)

**Colaboradores**

![Landing Page](assets/images/C6/landing_page-contributors.png)

### Backend

**Comits**

![Backend evidence](assets/images/C6/backend-commits.png)

**Colaboradores**

![Backend evidence](assets/images/C6/backend-contributors.png)

### Kotlin Mobile Application

**Comits**

![Mobile Application evidence](assets/images/C6/mobile_application-commits.png)

**Colaboradores**

![Mobile Application evidence](assets/images/C6/mobile_application-contributors.png)


## 6.2.2. Sprint 2
### 6.2.2.1. Sprint Planning 2

| **Sprint #** | Sprint 2 |
| :--- | :--- |
| **Sprint Planning Background** | |
| **Date** | 2025-11-24 |
| **Hour** | 10:30 p. m. |
| **Location** | Virtual |
| **Prepared By** | Jhosep Jamil Argomedo Camacho |
| **Attendees (to planning meeting)** | Jhosep Jamil Argomedo Camacho, Carlos Alberto González Custodio, Renso Anthony Julca Cruz, Sebastian Ramirez Tello |
| **Sprint 2 - 1 Review Summary** | Durante el Sprint Review 1, el equipo presentó los avances alcanzados, destacando la implementación completa de la landing page con diseño responsive, la integración del sistema de autenticación (IAM) y el avance significativo en la aplicación móvil del segmento docente, incluyendo pantallas de Login, Registro, Perfil, Grupos y Chat. Se demostró el funcionamiento de los endpoints de registro y login conectados a la base de datos, así como la estructura base para la gestión de usuarios y grupos. Los stakeholders validaron que los entregables cumplen con el objetivo del sprint y aportan valor directo al producto, resaltando la solidez del avance y la coherencia con la visión del proyecto. |
| **Sprint 2 - 1 Retrospective Summary** | En la retrospectiva del Sprint 1, el equipo identificó como principales fortalezas la comunicación fluida, la colaboración constante entre frontend, backend y mobile, y el uso disciplinado de herramientas como GitHub y Trello, lo cual facilitó la integración de funcionalidades clave. Sin embargo, también se reconocieron oportunidades de mejora, como la subestimación del esfuerzo inicial para configurar el backend y la necesidad de estandarizar estilos de código y aumentar la frecuencia de commits para evitar conflictos. Como acciones concretas para el siguiente sprint, se acordó mejorar la precisión en las estimaciones, definir una guía de buenas prácticas y mantener una mayor cadencia en la integración del código. |
| **Sprint Goal & User Stories** |
| **Sprint 2 Goal** | En este sprint nos enfocamos en habilitar funcionalidades clave orientadas a que estudiantes, docentes y visitantes puedan interactuar de forma más completa con la plataforma. Nuestro objetivo fue implementar características que permitan personalizar perfiles, buscar y crear grupos de estudio, explorar la interfaz y acceder a una demostración del buscador, fortaleciendo así la experiencia inicial de los usuarios dentro del sistema. <br> Creemos que la incorporación de estas funcionalidades incrementa significativamente el valor percibido del producto. Los estudiantes ahora pueden configurar su perfil académico, explorar e inscribirse en grupos de estudio, crear sus propios espacios colaborativos y programar sesiones en el calendario. Los docentes, por su parte, pueden gestionar grupos pagados, mientras que los visitantes tienen acceso a una demostración interactiva del buscador que facilita su transición hacia el registro. <br> Esto se confirmará cuando los usuarios logren navegar la aplicación de forma intuitiva, personalizar su perfil, interactuar con los grupos de estudio, acceder a las funciones principales del sistema y utilizar las APIs de soporte implementadas durante este sprint, validando que la plataforma avanza hacia un ecosistema más funcional y cohesionado. |
| **Sprint Velocity** |  |
| **Sum of Story Points** |  |

### 6.2.2.2. Sprint Backlog 2

Durante el Sprint 2, el objetivo principal fue completar las funcionalidades definidas en las US y TS priorizadas, garantizando que cada módulo avanzara de forma ordenada según el alcance planificado. El equipo se enfocó en cumplir con los entregables técnicos y funcionales establecidos, asegurando que cada tarea pasara por su flujo correspondiente: To-do, In-Process, To-Review y Done. Como resultado, se logró consolidar el progreso del sprint y obtener una visión clara del estado de cada historia y tarea, permitiendo mantener el control del avance y la calidad de las entregas.

A continuación, se detalla la tabla de control de estado para el Sprint 2:

| User Story ID | Task ID | Title | Description | Estimation (Hours) | Assigned To | Status |
|--------------|---------|--------|-------------|---------------------|-------------|--------|
| US-06 | **T-118** | Probar buscador | Como visitante quiero ver cómo funciona la búsqueda de compañeros y grupos para entender la facilidad de conexión en la plataforma. | 3 | Mobile Dev | **Done** |
| US-13 | **T-119** | Personalizar perfil de estudiante universitario | Como estudiante universitario quiero crear y configurar mi perfil académico para que otros usuarios puedan conocer mis intereses y nivel académico. | 3 | Mobile Dev | **Done** |
| US-14 | **T-120** | Buscar grupos de estudio | Como estudiante universitario quiero buscar grupos por materia y universidad para encontrar compañeros compatibles. | 2 | Mobile Dev | **Done** |
| US-15 | **T-121** | Crear grupos de estudio | Como estudiante universitario quiero crear un grupo de estudio especificando materia, objetivos y horarios. | 5 | Mobile Dev | **Done** |
| US-16 | **T-122** | Explorar interfaz intuitiva | Como estudiante secundaria quiero una interfaz con elementos lúdicos y coloridos para mantenerme motivada. | 3 | Mobile Dev | **Done** |
| US-21 | **T-123** | Gestionar grupos pagados | Como docente quiero crear y gestionar grupos pagados con tarifas personalizadas. | 4 | Mobile Dev | **Done** |
| US-28 | **T-124** | Programar calendario de sesiones | Como usuario quiero programar y gestionar sesiones de estudio dentro de cada grupo. | 2 | Mobile Dev | **Done** |
| TS-01 | **T-125** | API de Autenticación | Implementar endpoints de autenticación (login, JWT) para gestionar sesiones de usuario. | 4 | Backend Dev | **Done** |
| TS-02 | **T-126** | API de Gestión de Grupos | Endpoints CRUD para grupos de estudio, incluyendo filtros y paginación. | 4 | Backend Dev | **Done** |
| TS-03 | **T-127** | API de Chat | Endpoint WebSocket para enviar y recibir mensajes en tiempo real. | 5 | Backend Dev | **Done** |
| TS-04 | **T-128** | API de Gestión de Recursos | Endpoints para subir, listar y descargar archivos dentro de los grupos. | 5 | Backend Dev | **Done** |
| TS-06 | **T-129** | API de Perfil y Verificación de Docente | Endpoints para registro, verificación y reseñas de docentes. | 5 | Backend Dev | **Done** |

### 6.2.2.3. Development Evidence for Sprint Review

He aquí la sección "Development Evidence for Sprint Review" con una presentación de los avances y un ejemplo de commit, siguiendo la estructura solicitada.

A continuación, se presenta una tabla con los commits representativos de esta implementación:

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| https://github.com/ThinkUp-SkillShare/flutter-mobile-application-backend | main | c1c9095 | feat: add the first version of the backend for the Flutter application | --- | 14-11-25 |
| https://github.com/ThinkUp-SkillShare/flutter-mobile-application | main | 80629f3 | feat: adding the first version of the student app to Flutter | --- | 14-11-25 |

### 6.2.2.5. Execution Evidence for Sprint Review

El Sprint culminó satisfactoriamente, logrando el desarrollo y entrega de las funcionalidades planificadas tanto a nivel de frontend, backend como experiencia de usuario. Se alcanzó el Sprint Goal, centrado en avanzar las capacidades esenciales de la plataforma SkillShare relacionadas con exploración de grupos, creación de perfiles, gestión académica, funcionalidades colaborativas y el conjunto de APIs base que soportan el ecosistema completo.

Durante este sprint, se implementaron las principales vistas, flujos y servicios críticos que permiten a los usuarios —visitantes, estudiantes, docentes y miembros de grupos— interactuar con la plataforma de manera fluida. Además, se construyeron las APIs fundamentales que sostienen las operaciones del sistema, incluyendo autenticación, gestión de grupos, chat, recursos y perfiles de docentes.

A continuación, se describen las principales entregas logradas durante el sprint:

* **Interacción del Visitante:** Se desarrolló la funcionalidad de demostración de búsqueda (US-06), permitiendo al visitante visualizar y probar cómo funciona la conexión con compañeros y grupos antes de registrarse.
* **Gestión del Perfil del Estudiante:** Se implementó la creación y edición del perfil académico del estudiante universitario (US-13), facilitando la personalización del perfil dentro de la plataforma.
* **Búsqueda y Creación de Grupos:**Se desarrollaron las funciones para buscar grupos mediante filtros (US-14), así como la creación de grupos de estudio con control administrativo y manejo de solicitudes (US-15).
* **Interfaz para Estudiantes de Secundaria:** Se entregaron componentes visuales y elementos lúdicos destinados a mejorar la motivación y navegabilidad de estudiantes más jóvenes (US-16).
* **Gestión de Grupos Pagados para Docentes:** Se implementó la capacidad para que los docentes creen y administren grupos con tarifas personalizadas (US-21), incluyendo configuración de precios e inscripción mediante pago.
* **Calendario y Programación de Sesiones:** Se habilitó la funcionalidad para programar sesiones de estudio, proponer horarios y enviar recordatorios a los miembros del grupo (US-28).

* **APIs Base del Sistema:**
  * **Autenticación de Usuarios (TS-01):** Endpoints de login con validación y emisión de tokens JWT.
  * **Gestión de Grupos (TS-02):** CRUD completo con creación, filtros y paginación.
  * **Chat en Tiempo Real (TS-03):** Implementación de WebSocket para mensajería instantánea.
  * **Gestión de Recursos (TS-04):** Subida, listado y descarga de archivos dentro de los grupos.
  * **Verificación de Docentes (TS-06):** Registro, envío de documentación y acceso a reseñas y calificaciones.


**Mobile Application - Interacción del Visitante:**

![Visitante](assets/images/C7/visitante.png)

**Mobile Application - Gestión del Perfil del Estudiante:**

![Perfil Estudiante](assets/images/C7/perfil.png)

**Mobile Application - Búsqueda y Creación de Grupos:**

![Grupos](assets/images/C7/grupos.png)

**Mobile Application - Interfaz para Estudiantes de Secundaria:**

![Interfaz](assets/images/C7/interfaz.png)

**Mobile Application - Gestión de Grupos Pagados para Docentes:**

![Docentes](assets/images/C7/docente.png)

**Mobile Application - Calendario y Programación de Sesiones:**

![Calendario](assets/images/C7/sesiones.png)

### 6.2.2.6. Services Documentation Evidence for Sprint Review



### 6.2.2.7. Software Deployment Evidence for Sprint Review



### 6.2.2.8. Team Collaboration Insights during Sprint

Durante el Sprint, el equipo trabajó de forma organizada y colaborativa para implementar los módulos centrales de SkillShare, abarcando el diseño, desarrollo y validación de funcionalidades tanto del frontend web, backend y la aplicación móvil. El uso de GitHub permitió mantener un flujo de trabajo ordenado, aplicando branches por feature, buenas prácticas de integración continua y revisiones de código mediante pull requests, garantizando calidad y consistencia entre los entregables. Las actividades se coordinaron en base a las User Stories y Technical Stories priorizadas, enfocándose en experiencia de usuario, seguridad, gestión de información académica y soporte a los flujos de docentes y estudiantes dentro de la plataforma.

### **Backend**

- **API de Autenticación** con endpoints de Login, Registro y manejo seguro de sesiones.

- **Gestión de Perfiles** para estudiantes y docentes, con operaciones de consulta y actualización.

- **Módulo de Grupos de Estudio**, permitiendo crear, listar y gestionar grupos académicos.

- **Servicios de Archivos y Recursos**, incluyendo carga, visualización y administración.

- **Documentación OpenAPI (Swagger)** para facilitar la integración con frontend y mobile.

### **Mobile Application**

- **Gestión de Perfil del Docente**, permitiendo editar información personal.

- **Dashboard de Grupos Académicos**, donde se muestran los grupos asignados.

- **Vista de Detalle del Grupo**, con acceso a alumnos, archivos y actividades.

- **Integración del Chat**, basada en las US asociadas al flujo de comunicación.


<br>

## **Analítica de Colaboración en GitHub:**

### Backend

**Comits**

![Backend evidence](assets/images/C7/colaboradores.png)

**Colaboradores**

![Backend evidence](assets/images/C7/commits.png)

### Kotlin Mobile Application

**Comits**

![Mobile Application evidence](assets/images/C7/ktlin_commit.png)

**Colaboradores**

![Mobile Application evidence](assets/images/C7/ktlin_colaboration.png)

### Flutter Mobile Application

**Comits**

![Mobile Application evidence](assets/images/C7/commits-flutter.png)

**Colaboradores**

![Mobile Application evidence](assets/images/C7/colaboration.png)

## 6.2.3. Sprint 3
### 6.2.3.1. Sprint Planning 3
### 6.2.3.2. Sprint Backlog 3
### 6.2.3.3. Development Evidence for Sprint Review
### 6.2.3.4. Testing Suite Evidence for Sprint Review
### 6.2.3.5. Execution Evidence for Sprint Review
### 6.2.3.6. Services Documentation Evidence for Sprint Review
### 6.2.3.7. Software Deployment Evidence for Sprint Review
### 6.2.3.8. Team Collaboration Insights during Sprint

<!-- 
  Interviews 
  -->

# 6.3. Validation Interviews
## 6.3.1. Diseño de Entrevistas

### Segmento 1: Estudiantes de Secundaria/Preparatoria
**Objetivo:** Validar que la propuesta de valor es clara y atractiva, y que la navegación es intuitiva y segura para un público joven.

#### Tareas y Preguntas de Evaluación:

1. **Landing Page**
   - **Tarea:** “Mira esta página web de SkillShare.”
   - **Preguntas clave:**  
     - “Sin scrollear mucho, ¿puedes decirme qué crees que podrías hacer en esta app?”  
     - “¿Qué te llama más la atención?”  
     - “¿La descargarías? ¿Por qué sí o por qué no?”

2. **Onboarding y Descubrimiento (Home/Explorer)**
   - **Tarea:** “Regístrate/entra en la app y explora la pantalla de inicio y la sección de ‘Explorar’.”
   - **Preguntas clave:**  
     - “¿El diseño te parece aburrido o interesante?”  
     - “¿Encuentras fácilmente grupos de tus materias (Matemáticas, Historia)?”  
     - “¿Ves alguna diferencia entre un grupo ‘destacado’ y uno normal?”

3. **Unión y Gestión de Grupos**
   - **Tarea:** “Ve a la sección de ‘Mis Grupos’.”
   - **Preguntas clave:**  
     - “Antes de ingresar, ¿la información del grupo te dio confianza?”  
     - “Al verlo en ‘Mis Grupos’, ¿queda claro que ya eres miembro?”  
     - “¿Qué esperarías encontrar dentro del grupo ahora?”


### Segmento 2: Estudiantes Universitarios
**Objetivo:** Validar la eficiencia para encontrar grupos especializados y la utilidad para gestionar el aprendizaje autónomo.

#### Tareas y Preguntas de Evaluación:

1. **Landing Page**
   - **Tarea:** “Evalúa la página de inicio de SkillShare.”
   - **Preguntas clave:**  
     - “¿Logra comunicar que es una herramienta útil a nivel universitario?”  
     - “¿En qué se diferencia esto de un foro tradicional o un grupo de WhatsApp?”

2. **Búsqueda Eficiente (Explorer)**
   - **Tarea:** “Usa la app para buscar un grupo específico para una asignatura de tu carrera.”
   - **Preguntas clave:**  
     - “¿Los resultados son relevantes?”  
     - “¿Los filtros o categorías son útiles para afinar tu búsqueda?”  
     - “¿La información de cada grupo (miembros, descripción) es suficiente para evaluar su calidad?”

3. **Perfil y Organización**
   - **Tarea:** “Ingresa a ‘Tu perfil’.”
   - **Preguntas clave:**  
     - “¿Tu perfil refleja bien tu actividad de aprendizaje?”  
     - “Desde ‘Mis Grupos’, ¿es rápido acceder a los grupos a los que te uniste?”  
     - “¿Echas en falta alguna forma de organizar o priorizar tus grupos?”

### Segmento 3: Autodidactas
**Objetivo:** Validar la capacidad de la app para conectar intereses diversos y fomentar el descubrimiento de habilidades fuera del ámbito académico formal.

#### Tareas y Preguntas de Evaluación:

1. **Landing Page**
   - **Tarea:** “Como alguien que aprende por su cuenta, ¿esta página te motiva a probar SkillShare?”
   - **Preguntas clave:**  
     - “¿Ves reflejados tus intereses en cuanto a grupos de estudio?”  
     - “¿Sientes que es un lugar para gente como tú?”

2. **Descubrimiento e Intereses (Home/Explorer)**
   - **Tarea:** “Explora la app sin buscar algo en específico. Simplemente descubre qué hay.”
   - **Preguntas clave:**  
     - “¿Las ‘categorías populares’ se alinean con tus intereses?”  
     - “¿Encuentras grupos sobre temas que no esperabas?”  
     - “¿El sistema te ayuda a descubrir nuevas habilidades?”

3. **Identidad y Pertenencia (Perfil/Mis Grupos)**
   - **Duración estimada:** 6 min
   - **Tarea:** “Ingresar a un par de grupos a los que pertenezcas.”
   - **Preguntas clave:**  
     - “¿Te gusta cómo tu perfil muestra tus intereses de aprendizaje?”  
     - “Al ver ‘Mis Grupos’, ¿sientes que formas parte de una comunidad?”

### Segmento 4: Docentes
**Objetivo:** Validar la percepción de los docentes sobre la utilidad de SkillShare para sus estudiantes y la claridad de la interfaz para la gestión académica.

#### Tareas y Preguntas de Evaluación:

1. **Impresión general**
   - **Tarea:** “Después de ver esta demostración de SkillShare, comparta su primera impresión sobre la aplicación y el concepto de una red social enfocada en el estudio.”
   - **Preguntas clave:**  
     - “¿Cuál es su impresión general sobre SkillShare?”  
     - “¿Cree que el concepto de red social enfocada en el estudio es atractivo y útil?”

2. **Navegación**
   - **Tarea:** “Explore la aplicación, prestando atención a la barra inferior (Inicio, Grupos, Archivos, Calendario, Perfil).”
   - **Preguntas clave:**  
     - “¿Qué tan fácil o difícil le resultó navegar por la app?”  
     - “¿Los íconos y su orden le parecen claros y lógicos?”

3. **Diseño de los grupos**
   - **Tarea:** “Revise las tarjetas de cada grupo en la sección ‘Grupos’.”
   - **Preguntas clave:**  
     - “¿Qué le parece el diseño de las tarjetas?”  
     - “¿La información mostrada es suficiente, o considera que falta o sobra algo?”

4. **Funcionalidad de calendario**
   - **Tarea:** “Observe la función de agregar eventos manualmente al calendario.”
   - **Preguntas clave:**  
     - “¿Cree que esta función manual es útil?”  
     - “¿Considera que los estudiantes solo la usarían si se sincronizara automáticamente con sus calendarios universitarios?”

5. **Diseño visual**
   - **Tarea:** “Analice el diseño general de la aplicación (colores, tipografía, espacios).”
   - **Preguntas clave:**  
     - “¿El diseño le transmite un ambiente profesional y enfocado en el estudio?”  
     - “¿Le parece demasiado simple o, por el contrario, sobrecargado?”

## 6.3.2. Registro de Entrevistas

### Segmento 1: Estudiantes de Educación Superior

#### Entrevista

| **Campo** | **Detalle** |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Entrevista 1](assets/images/C2/validation-interviews/allison_validation.png) | Enlace: [Video](https://www.youtube.com/watch?v=mYfaAI4ii-8)  |
| **Entrevistado(a)**      | Rivera Quispe, Allison Milagros |
| **Edad**              | 21 años  |
| **Rubro**             | Estudiante de Administración de Empresas |
| **Ubicación**         | Lima, San Martín de Porres |
| **Medio**             | Discord  |
| **Entrevistador**     | Julca Cruz, Renso Anthony  |
| **Instante inicio**   | 00:00:05   |
| **Duración**          | 03 min 44 seg |
| **Resumen**           | Durante la entrevista se muestra la demostración de una aplicación de grupos de estudio. La entrevistada visualiza los grupos a los que pertenece, los cursos populares y la opción de crear nuevos grupos asignando nombre, curso, descripción e imagen. También se exploran grupos mediante buscador y filtros, revisando los populares, en tendencia y recién creados. Se explica la sección de archivos, donde se pueden ver y subir documentos compartidos. En el perfil se observa la actividad del usuario, grupos unidos, documentos compartidos y amigos. Al revisar un grupo específico, se muestra información de miembros, chat, archivos, quizzes, llamadas, compartir grupo y notificaciones. La entrevistada considera suficiente la información disponible para evaluar los grupos, aunque sugiere incluir calificaciones de calidad y la opción de ordenar o priorizar grupos según favoritos o nivel de interacción. |

### Segmento 2: Estudiantes de Secundaria

#### Entrevista

| **Campo** | **Detalle** |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Entrevista 2](assets/images/C2/validation-interviews/argomedo.png) | Enlace: [Video]()  |
| **Entrevistado(a)**      | Luis Diaz |
| **Edad**              | 19 años |
| **Rubro**             | Estudiante |
| **Ubicación**         | San Isidro |
| **Medio**             | Google Meet |
| **Entrevistador**     | Argomedo Camacho, Jhosep Jamil |
| **Instante inicio**   | 00:00:05 |
| **Duración**          | 09 min 22 seg |
| **Resumen**           | Durante la demostración se presenta una nueva aplicación llamada Skill Short, enfocada en el aprendizaje colaborativo mediante grupos de estudio. El usuario navega por la página de inicio, donde observa secciones como funciones, precios, testimonios e información de contacto. También recorre las opciones para unirse a grupos, visualizar documentos compartidos y realizar un seguimiento del progreso dentro de la comunidad de aprendizaje. Además, revisa la navegación general de la aplicación, evaluando la limpieza del diseño y la organización visual de cada apartado. En el recorrido se muestran las herramientas principales, como la posibilidad de acceder a grupos existentes, participar en conversaciones y consultar el historial de contribuciones. También se describen las funciones destinadas al aprendizaje colectivo, incluyendo el intercambio de recursos y la interacción entre miembros. Durante la experiencia, el usuario identifica áreas de mejora y señala que, aunque la interfaz es atractiva, sería conveniente optimizar la paleta de colores para mejorar la accesibilidad de personas con dificultades visuales. En general, el usuario considera que la aplicación ofrece información suficiente para comprender su funcionamiento y evaluar la utilidad de cada sección. Sin embargo, sugiere reforzar los aspectos de accesibilidad para garantizar una experiencia inclusiva y cómoda para todo tipo de usuarios. |

### Segmento 3: Estudiantes Autodidactas

#### Entrevista

| **Campo** | **Detalle** |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Entrevista 3](assets/images/C2/validation-interviews/ramirez.png) | Enlace: [Video](https://www.youtube.com/watch?v=ew0vbQglMlw)  |
| **Entrevistado(a)**      | Keynner Hanco |
| **Edad**              | 20 |
| **Rubro**             | Estudiantes Autodidacta |
| **Ubicación**         | Lima |
| **Medio**             | Zoom |
| **Entrevistador**     | Ramírez Tello, Sebastián |
| **Instante inicio**   | 00:00:05 |
| **Duración**          | 07 min 55 seg |
| **Resumen**           | Durante la revisión en video se presenta la página de inicio y el prototipo de una plataforma de aprendizaje en línea. El revisor, Keiner, recorre la interfaz observando elementos como los planes disponibles, uno gratuito y otro de pago con funciones adicionales, así como el diseño general del sitio y la claridad de la información mostrada. También explora las opciones principales del prototipo, donde identifica herramientas para crear grupos, desarrollar cursos y utilizar un chat integrado para la interacción entre usuarios. En el recorrido se destacan las funciones orientadas a conectar a estudiantes con intereses similares, mostrando cómo la plataforma busca construir comunidades mediante la creación de espacios compartidos y recursos colaborativos. Keiner analiza la facilidad de navegación, señalando que el diseño es limpio, intuitivo y organizado. Además, revisa las herramientas de búsqueda y filtrado, y sugiere incluir una función que permita a los usuarios encontrar grupos relevantes según sus intereses específicos.En general, el revisor considera que la plataforma brinda suficiente información para comprender su propósito y funcionamiento. Sin embargo, recomienda mejorar la experiencia de descubrimiento de comunidades para que los usuarios puedan integrarse de manera más rápida y efectiva a grupos alineados con sus preferencias de aprendizaje. |

### Segmento 4: Docentes

#### Entrevista 1

| **Campo** | **Detalle** |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Entrevista 4](assets/images/C2/validation-interviews/carlos_validaton.png) | Enlace: [Video](https://www.youtube.com/watch?v=y-plup-XcXE&feature=youtu.be)  |
| **Entrevistado(a)**      | Merly Salon |
| **Edad**              | 25 años |
| **Rubro**             | Docente de Secundaria |
| **Ubicación**         | San Martin de Porres |
| **Medio**             | Google Meet |
| **Entrevistador**     | González Custodio, Carlos Alberto |
| **Instante inicio**   | 00:00:05 |
| **Duración**          | 09 min 29 seg |
| **Resumen**           | Durante la entrevista se muestra la demostración de una aplicación académica orientada a la organización entre docentes y estudiantes. La entrevistada observa la pantalla de inicio, donde aparecen asignaturas populares, grupos sugeridos y la opción de crear nuevos grupos ingresando nombre, asignatura y una breve descripción. También se presentan secciones para explorar grupos disponibles, programar eventos y visualizar un calendario con actividades académicas. Se explica además la sección de archivos, donde el docente puede revisar materiales organizados por cursos, identificar el tipo de archivo y subir nuevos documentos o notas. En el perfil se muestran estadísticas del usuario, los grupos a los que pertenece, reseñas recibidas y configuraciones como idioma, tema visual y notificaciones. Al ingresar a un grupo específico, se visualiza información sobre sus miembros, el chat, los archivos disponibles, los quizzes programados y las opciones para compartir el grupo o ajustar notificaciones. La entrevistada considera que la idea de una red social enfocada en estudios es adecuada y necesaria, valorando la navegación intuitiva y la organización de las secciones. Sugiere incluir indicadores de mensajes no leídos en las tarjetas de grupos y resalta que la función de eventos sería más útil si se sincronizara automáticamente con el calendario universitario. Finalmente, destaca que el diseño es moderno y profesional, aunque menciona que las insignias del perfil pueden percibirse como un elemento más social o lúdico. |

# Conclusiones

- **Validación de la Necesidad del Mercado**
El análisis exhaustivo realizado confirma la existencia de una necesidad real y significativa en el mercado educativo. Las entrevistas con 8 usuarios de diferentes segmentos revelaron patrones consistentes de dolor en la organización de grupos de estudio, con un 100% de los entrevistados universitarios reportando dificultades en la coordinación de horarios y el manejo de herramientas dispersas. La investigación académica citada respalda estos hallazgos, demostrando que el aprendizaje colaborativo puede mejorar las calificaciones hasta en 6 puntos porcentuales y reducir las tasas de deserción del 32% al 21%.

- **Diferenciación Competitiva Clara**
SkillShare se posiciona exitosamente en un nicho específico dentro del mercado de herramientas educativas. A diferencia de competidores como Discord (orientado al gaming), Google Classroom (centrado en docentes) o Quizlet (enfocado en memorización), nuestra propuesta integra funcionalidades específicamente diseñadas para el estudio colaborativo estudiantil. El análisis SWOT identificó ventajas competitivas clave: enfoque 100% académico, integración de comunicación y recursos en una sola plataforma, y modelo freemium accesible para estudiantes.

- **Arquitectura Técnica Robusta y Escalable**
El diseño de software basado en Domain-Driven Design (DDD) proporciona una base sólida para el desarrollo. La identificación de 5 bounded contexts claramente definidos (Gestión de Usuarios, Grupos de Estudio, Recursos Compartidos, Comunicación, y Evaluaciones) permite una arquitectura modular y mantenible. Los diagramas C4 demuestran una separación clara de responsabilidades entre la aplicación móvil Flutter, el backend con APIs RESTful, y la infraestructura en la nube, garantizando escalabilidad para el crecimiento proyectado.

- **Viabilidad del Modelo de Negocio**
El modelo freemium propuesto se alinea con las expectativas y capacidad de pago de los usuarios. Las entrevistas revelaron que, aunque los estudiantes prefieren servicios gratuitos, existe disposición condicional a pagar por valor tangible (ahorro de tiempo, mejores calificaciones). El segmento de docentes presenta mayor potencial de monetización a través de grupos pagados y herramientas premium.

- **Proceso de Desarrollo Fundamentado**
La aplicación de metodologías como Lean UX, EventStorming y entrevistas estructuradas proporcionó una base empírica sólida para las decisiones de diseño. Las 29 User Stories identificadas cubren comprehensivamente las necesidades de los usuarios, priorizadas según impacto en el negocio y esfuerzo de desarrollo.

- **Alineamiento Estratégico del Producto con las Épicas Identificadas**
El conjunto de 7 épicas definidas garantiza una cobertura integral del ecosistema de SkillShare. Cada epic aborda un aspecto esencial del ciclo de aprendizaje colaborativo —desde la adquisición de usuarios (Landing Page) hasta la evaluación del progreso (Evaluaciones y Analítica Docente)— asegurando coherencia entre la visión del producto, las funcionalidades implementadas y la experiencia del usuario final.
## Recomendaciones

- **Estrategia de Lanzamiento Gradual**
  - Recomendación: Implementar un lanzamiento por fases comenzando con el segmento universitario como early adopters.
  - Justificación: Este segmento mostró mayor disposición al cambio y capacidad de articular necesidades específicas. Su adopción exitosa generará testimonios y casos de uso que facilitarán la expansión a otros segmentos.
  - Implementación:
    - Fase 1: MVP con funcionalidades core para estudiantes universitarios
    - Fase 2: Incorporación de elementos de gamificación para secundaria
    - Fase 3: Herramientas avanzadas para autodidactas y docentes

- **Priorización de Desarrollo Basada en Value Proposition**
  - Recomendación: Desarrollar primero las funcionalidades que generan mayor diferenciación competitiva.
  - Según el análisis del Product Backlog, priorizar:
    - Sistema de registro y autenticación (HU-01)
    - Búsqueda y creación de grupos (HU-14, HU-15)
    - Chat integrado y compartir recursos (HU-24, HU-26)
    - Funcionalidades premium para docentes (HU-21, HU-22)

- **Métricas de Éxito y Validación Continua**
  - Recomendación: Implementar un sistema de métricas que valide las hipótesis de negocio identificadas en el Lean UX Canvas.
  - Métricas clave a monitorear:
    - Tasa de conversión de registro a primer grupo creado/joinedo (objetivo: 70% en primera semana)
    - Engagement mensual activo por segmento
    - Net Promoter Score por funcionalidad
    - Tiempo promedio de permanencia en grupos de estudio
    - Tasa de conversión freemium a premium

- **Enfoque en la Experiencia del Usuario y Retención Temprana**
  - Recomendación: Implementar mejoras continuas en la interfaz y experiencia de usuario basadas en retroalimentación real obtenida durante las pruebas del MVP.

  - Una interfaz intuitiva y fluida es determinante para que los usuarios perciban valor desde el primer uso. Las pruebas iniciales de usabilidad pueden revelar puntos de fricción que afecten la retención y el engagement en las primeras semanas de lanzamiento.
  
  - Implementación:
    - Realizar pruebas de usabilidad con al menos 10 estudiantes por iteración.
    - Incorporar herramientas de analítica (como Firebase Analytics) para medir flujos y abandonos.
    - Refinar la navegación, tiempos de carga y accesibilidad visual del MVP.
    - Diseñar mejoras basadas en métricas de retención (por ejemplo, mantener un 60% de usuarios activos durante la primera semana).

<br>
<br>
<br>
<br>


# Bibliografía

- Brown, A., Nguyen, T., & Williams, D. (2023). *Impact of online collaborative learning on student performance during remote education*. Journal of Educational Technology, 18(2), 125-139.  
- Fiorella, L., & Mayer, R. E. (2019). *The relative benefits of learning by teaching and teaching expectancy*. Contemporary Educational Psychology, 59, 51-59.  
- Garcia, M., & Martinez, L. (2022). *Barriers and enablers in collaborative study practices: A mixed-methods approach*. Educational Research Review, 34, 100411.  
- Johnson, D. W., & Barker, B. (2024). *The role of extracurricular engagement in student retention and academic success*. Higher Education Quarterly, 78(1), 45-62.  
- Johnson, D. W., Johnson, R. T., & Smith, K. A. (2022). *Cooperative learning: Improving university academics and interpersonal skills*. Review of Educational Research, 92(1), 1-28.  
- Kim, S., Park, J., & Lee, H. (2020). *Small group learning and academic achievement in higher education: A meta-analysis*. Studies in Higher Education, 45(2), 249-264.  
- Lopez, C., & Kim, Y. (2024). *Social network analysis and academic performance: Influence of centrality in peer groups*. Journal of Educational Psychology, 116(3), 650-664.  
- Martínez, F., & Gómez, R. (2023). *Active learning strategies in STEM education: Effects on course success rates*. International Journal of STEM Education, 10(1), 15.  
- Nguyen, M., & Carroll, J. (2021). *Trust and collaboration in online secondary education: Longitudinal effects on student achievement*. Computers & Education, 167, 104176.  
- Smith, J., & Lee, A. (2021). *Group study participation and academic outcomes: Insights from a large university sample*. Journal of College Student Development, 62(4), 453-468.  
- Thompson, R., Garcia, M., & Chung, S. (2021). *Sense of belonging and student retention in higher education*. Journal of Student Affairs Research and Practice, 58(3), 236-252.  

<br>
<br>

<!--
   ANEXOS
-->

# Anexos

**Enlace Organización en GitHub:** https://github.com/ThinkUp-SkillShare
**Enlace a nuestra Landing Page** https://thinkup-skillshare.github.io/skillshare.github.io/