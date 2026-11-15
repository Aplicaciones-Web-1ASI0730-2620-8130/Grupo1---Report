<div align="center">

<img src="assets/UPC_logo_transparente.png" alt="Logo-UPC" width="150">
![Estructura de carpeta readm3](/assets/images/readm3/UPC_logo_transparente.png)

**Universidad Peruana de Ciencias Aplicadas**<br>
**Carrera de Ingeniería de Software**

**1ASI0730**<br>
**Aplicaciones Web**<br>
NRC<br>
**8130**<br>
**Informe del Trabajo Final**<br>
Docente<br>
**Villafuerte Bazan, Oscar Ivan**<br>
<br>
    <strong>Nombre del Startup:</strong> Caiman
    <br><br>
    <strong>Nombre del Producto:</strong> EcoRoad
    <br><br>

<br>**Integrantes**
| Código      | Apellidos y Nombres                  |
|-------------|--------------------------------------|
| U202418029  | Pancorbo Amorós , Italo Raul         |
| U202421413  | Guillen Chavez , Eduardo Martín      |
| U20241E417  | Salcedo Muñoz , Andy Alfredo Hipolito|
| U20241D483  | Taza Curay , Eduardo Miguel          | 
| U202212897  | Roman Lopez , Miguel Angel Junior    |

**Período 202620**

**Noviembre 2026**

</div>

---

<div style="page-break-after: always;"></div>

## Registro de Versiones del Informe

| Versión | Fecha | Autores | Descripción de modificación |
| :--- | :--- | :--- | :--- |
| **AV1** | 20/9 | Pancorbo Amorós , Italo Raul <br> Guillen Chavez , Eduardo Martín <br> Salcedo Muñoz , Andy Alfredo Hipolito <br> Taza Curay , Eduardo Miguel <br> Roman Lopez , Miguel Angel Junior | Para la entrega AV1 se consolidó la estructura del informe técnico, incluyendo carátula, registro de versiones, tabla de contenidos y la definición de Student Outcomes. <br><br>Capítulo I — Introducción: Se redactó el Startup Profile y el Solution Profile (EcoRoad), detallando la propuesta de valor para la gestión y construcción de proyectos viales. <br><br>Capítulo II — Requirements Elicitation & Analysis: Se realizó el análisis de competidores y el registro de entrevistas a profundidad. Se desarrolló el Needfinding (User Personas, Task Matrix, Journey Mapping), así como el Big Picture EventStorming para identificar los eventos clave del dominio y el Ubiquitous Language basado en los Bounded Contexts definidos.<br><br>Capítulo III — Requirements Specification: Se elaboró el Product Backlog priorizando las User Stories críticas. Se aplicó la metodología de Impact Mapping para alinear las funcionalidades con los objetivos estratégicos del negocio.<br><br>Capítulo IV — Product Design: Se definieron los lineamientos de estilo general y web, junto con la arquitectura de la información del sistema. Se documentó el diseño de las interfaces de usuario a través de wireframes y mock-ups para la Landing Page y la Web Application, abarcando tanto las vistas de escritorio como las adaptaciones móviles. Además, se estableció la arquitectura de software basada en Domain-Driven Design mediante los diagramas del modelo C4 (Contexto, Contenedor y Componentes), y se detalló el diseño técnico incorporando los diagramas de clases y de base de datos para los ocho Bounded Contexts del proyecto. <br><br> Capítulo V — Product Implementation: Se documentó la gestión de configuración de software, estándares de versionamiento (GitFlow) y convenciones de código. Se incluyó la evidencia del Sprint 1, detallando el Sprint Planning, Sprint Backlog (enfocado en US001, US002, US003 y US004), líderes de aspecto, métricas de colaboración y las evidencias del despliegue inicial de la Landing Page en GitHub Pages. |
| **TB1** | 9/10 | Pancorbo Amorós , Italo Raul <br> Guillen Chavez , Eduardo Martín <br> Salcedo Muñoz , Andy Alfredo Hipolito <br> Taza Curay , Eduardo Miguel <br> Roman Lopez , Miguel Angel Junior | Para la entrega del Trabajo Parcial (TB1) se incorporaron y actualizaron los siguientes apartados clave del proyecto EcoRoad:<br><br>Capítulo IV — Product Design: Se perfeccionaron y consolidaron los diagramas de diseño orientado a objetos (clases) y de bases de datos relacionales correspondientes a cada uno de los Bounded Contexts del sistema (Project Management, Identity & Access, Device & Asset Mgmt, Environmental Monitoring, Incident & Mitigation, Document & Evidence, Reports & Compliance y Subscriptions & Payment), alineándolos al enfoque de Monolito Modular.<br><br>Capítulo V — Product Implementation, Validation & Deployment: Se documentó el desarrollo correspondiente al Sprint 2, detallando la asignación de responsabilidades mediante la distribución de Bounded Contexts a cada integrante del equipo (evidenciado en el reporte de participación). Asimismo, se realizaron las correcciones y el levantamiento de observaciones generales del informe técnico estructurado en el avance anterior, asegurando la trazabilidad y calidad de la documentación del sistema. |
| **AV2** | 15/11/2026 | Pancorbo Amorós, Italo Raul (con aportes del equipo EcoRoad) | Se incorporó la versión actualizada del Capítulo V: Sprint 2 con la aplicación conectada a la Fake API y Sprint 3 con servicios ASP.NET Core, persistencia MySQL e integración con el frontend. Se documentaron el backlog y tablero de Trello del Sprint 3, la participación técnica por ramas y commits, la referencia OpenAPI/Scalar, los despliegues en Railway y GitHub Pages, las evidencias de ejecución, el diseño de entrevistas por segmentos y el video About-the-Product. Se actualizaron el índice, el Outcome 5 y los anexos. Las evaluaciones y datos señalados como pendientes conservan ese estado. |
| **TB2** | | | |

<div style="page-break-after: always;"></div>

# Project Report Collaboration Insights
<a id="project-report-collaboration-insights"></a>

En el Sprint 3, el equipo distribuyó el trabajo por contextos funcionales e integró los servicios con la aplicación web. La reunión de planificación del 13/10/2026 fue organizada por Italo Pancorbo y contó con los cinco integrantes por Discord. El [tablero del Sprint 3](https://trello.com/invite/b/6af96cc3b31b2f3ac6f7858d/ATTI06b3af4493183313e4c1b7fd9cdafe8cD3C2DA79/sprint-3-ecoroad) muestra 13 tarjetas en Done. El capítulo 5 presenta la distribución técnica por integrante, la metodología del recuento de commits y las limitaciones de esa métrica. Los acuerdos de retrospectiva y las horas por tarea siguen pendientes de verificación.

# Tabla de Contenidos

- [Project Report Collaboration Insights](#project-report-collaboration-insights)

## [Capítulo I: Introducción](docs/cap1-introduction.md#introduccion)

- [1.1. Startup Profile](docs/cap1-introduction.md#1-1-startup-profile)
  - [1.1.1. Descripción de la Startup](docs/cap1-introduction.md#1-1-1-descripcion-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](docs/cap1-introduction.md#1-1-2-perfiles-de-los-miembros-del-equipo)
- [1.2. Solution Profile](docs/cap1-introduction.md#1-2-solution-profile)
  - [1.2.1. Antecedentes y problemática](docs/cap1-introduction.md#1-2-1-antecedentes-y-problematica)
  - [1.2.2. Lean UX Process](docs/cap1-introduction.md#1-2-2-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](docs/cap1-introduction.md#1-2-2-1-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](docs/cap1-introduction.md#1-2-2-2-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](docs/cap1-introduction.md#1-2-2-3-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](docs/cap1-introduction.md#1-2-2-4-lean-ux-canvas)
- [1.3. Segmentos objetivo](docs/cap1-introduction.md#1-3-segmentos-objetivos)

---

## [Capítulo II: Requirements Elicitation & Analysis](docs/cap2-Requirements%20Elicitation%20%26%20Analysis.md#2-requirements-elicitation-analysis)

- [2.1. Competidores](docs/cap2-Requirements%20Elicitation%20%26%20Analysis.md#2-1-competidores)
  - [2.1.1. Análisis competitivo](docs/cap2-Requirements%20Elicitation%20%26%20Analysis.md#2-1-1-analisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](docs/cap2-Requirements%20Elicitation%20%26%20Analysis.md#2-1-2-estrategias-y-tacticas-frente-a-competidores)
- [2.2. Entrevistas](docs/cap2-Requirements%20Elicitation%20%26%20Analysis.md#2-2-entrevistas)
  - [2.2.1. Diseño de entrevistas](docs/cap2-Requirements%20Elicitation%20%26%20Analysis.md#2-2-1-diseno-de-entrevistas)
- [2.3.1. User Personas](docs/cap2-Requirements%20Elicitation%20%26%20Analysis.md#2-3-1-user-personas)
- [2.5. Ubiquitous Language](docs/cap2-Requirements%20Elicitation%20%26%20Analysis.md#2-5-ubiquitous-language)

---

## [Capítulo III: Requirements Specification](docs/cap3-requirements-specification.md#3-requirements-specification)

- [3.1. User Stories](docs/cap3-requirements-specification.md#3-1-user-stories)
- [3.2. Impact Mapping](docs/cap3-requirements-specification.md#3-2-impact-mapping)
- [3.3. Product Backlog](docs/cap3-requirements-specification.md#3-3-product-backlog)

---

## [Capítulo IV: Product Design](docs/cap4-product-design.md#4-product-design)

- [4.1. Style Guidelines](docs/cap4-product-design.md#4-1-style-guidelines)
  - [4.1.1. General Style Guidelines](docs/cap4-product-design.md#4-1-1-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](docs/cap4-product-design.md#4-1-2-web-style-guidelines)
- [4.2. Information Architecture](docs/cap4-product-design.md#4-2-information-architecture)
  - [4.2.1. Organization Systems](docs/cap4-product-design.md#4-2-1-organization-systems)
  - [4.2.2. Labeling Systems](docs/cap4-product-design.md#4-2-2-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](docs/cap4-product-design.md#4-2-3-seo-tags-meta-tags)
  - [4.2.4. Searching Systems](docs/cap4-product-design.md#4-2-4-searching-systems)
  - [4.2.5. Navigation Systems](docs/cap4-product-design.md#4-2-5-navigation-systems)
- [4.3. Landing Page UI Design](docs/cap4-product-design.md#4-3-landing-page-ui-design)
- [4.7. Software Object-Oriented Design](docs/cap4-product-design.md#4-7-software-object-oriented-design)
  - [4.7.1. Class Diagrams](docs/cap4-product-design.md#4-7-1-class-diagrams)
- [4.8. Database Design](docs/cap4-product-design.md#4-8-database-design)
  - [4.8.1. Database Diagram](docs/cap4-product-design.md#4-8-1-database-diagrams)

---

## [Capítulo V: Product Implementation, Validation & Deployment](docs/cap5-product-implementation-validation-and-deployment.md#product-implementation-validation-deployment)

- [5.1. Software Configuration Management](docs/cap5-product-implementation-validation-and-deployment.md#5-1-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](docs/cap5-product-implementation-validation-and-deployment.md#5-1-1-software-development-environment-configuration)
  - [5.1.2. Source Code Management](docs/cap5-product-implementation-validation-and-deployment.md#5-1-2-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](docs/cap5-product-implementation-validation-and-deployment.md#5-1-3-source-code-style-guide-conventions)
  - [5.1.4. Software Deployment Configuration](docs/cap5-product-implementation-validation-and-deployment.md#5-1-4-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](docs/cap5-product-implementation-validation-and-deployment.md#5-2-landing-page-services-applications-implementation)
  - [5.2.1. Sprint 1](docs/cap5-product-implementation-validation-and-deployment.md#5-2-1-sprint-1)
    - [5.2.1.1. Sprint Planning 1](docs/cap5-product-implementation-validation-and-deployment.md#5-2-1-1-sprint-planning-1)
    - [5.2.1.2. Aspect Leaders and Collaborators](docs/cap5-product-implementation-validation-and-deployment.md#5-2-1-2-aspect-leaders-and-collaborators)
    - [5.2.1.3. Sprint Backlog 1](docs/cap5-product-implementation-validation-and-deployment.md#5-2-1-3-sprint-backlog-1)
    - [5.2.1.4. Development Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-1-4-development-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-1-5-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-1-6-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-1-7-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](docs/cap5-product-implementation-validation-and-deployment.md#5-2-1-8-team-collaboration-insights-during-sprint)
  - [5.2.2. Sprint 2](docs/cap5-product-implementation-validation-and-deployment.md#5-2-2-sprint-2)
      - [5.2.2.1. Sprint Planning 2](docs/cap5-product-implementation-validation-and-deployment.md#5-2-2-1-sprint-planning-2)
      - [5.2.2.2. Aspect Leaders and Collaborators](docs/cap5-product-implementation-validation-and-deployment.md#5-2-2-2-aspect-leaders-and-collaborators)
      - [5.2.2.3. Sprint Backlog 2](docs/cap5-product-implementation-validation-and-deployment.md#5-2-2-3-sprint-backlog-2)
      - [5.2.2.4. Development Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-2-4-development-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-2-5-execution-evidence-for-sprint-review)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-2-6-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-2-7-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint](docs/cap5-product-implementation-validation-and-deployment.md#5-2-2-8-team-collaboration-insights-during-sprint)
  - [5.2.3. Sprint 3](docs/cap5-product-implementation-validation-and-deployment.md#5-2-3-sprint-3)
    - [5.2.3.1. Sprint Planning 3](docs/cap5-product-implementation-validation-and-deployment.md#5-2-3-1-sprint-planning-3)
    - [5.2.3.2. Aspect Leaders and Collaborators](docs/cap5-product-implementation-validation-and-deployment.md#5-2-3-2-aspect-leaders-and-collaborators)
    - [5.2.3.3. Sprint Backlog 3](docs/cap5-product-implementation-validation-and-deployment.md#5-2-3-3-sprint-backlog-3)
    - [5.2.3.4. Development Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-3-4-development-evidence-for-sprint-review)
    - [5.2.3.5. Execution Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-3-5-execution-evidence-for-sprint-review)
    - [5.2.3.6. Services Documentation Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-3-6-services-documentation-evidence-for-sprint-review)
    - [5.2.3.7. Software Deployment Evidence for Sprint Review](docs/cap5-product-implementation-validation-and-deployment.md#5-2-3-7-software-deployment-evidence-for-sprint-review)
    - [5.2.3.8. Team Collaboration Insights during Sprint](docs/cap5-product-implementation-validation-and-deployment.md#5-2-3-8-team-collaboration-insights-during-sprint)
- [5.3. Validation Interviews](docs/cap5-product-implementation-validation-and-deployment.md#5-3-validation-interviews)
  - [5.3.1. Diseño de Entrevistas](docs/cap5-product-implementation-validation-and-deployment.md#5-3-1-diseno-de-entrevistas)
  - [5.3.2. Registro de Entrevistas](docs/cap5-product-implementation-validation-and-deployment.md#5-3-2-registro-de-entrevistas)
  - [5.3.3. Evaluaciones según heurísticas](docs/cap5-product-implementation-validation-and-deployment.md#5-3-3-evaluaciones-segun-heuristicas)
- [5.4. Video About-the-Product](docs/cap5-product-implementation-validation-and-deployment.md#5-4-video-about-the-product)

---

## [Student Outcome 5](#abet-eac-student-outcome-5)

- [Evidencia AV2](#evidencia-av2-del-student-outcome-5)

---

## [Conclusiones](#conclusiones-y-recomendaciones)

- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)

---

## [Bibliografía](#bibliografia)

---

## [Anexos](#anexos)

# ABET – EAC - Student Outcome 5
<a id="abet-eac-student-outcome-5"></a>


Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros 
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, 
establecen objetivos, planifican tareas y cumplen objetivos.

En el siguiente cuadro se describe las acciones realizadas y enunciados de 
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro 
del ABET – EAC - Student Outcome 5



| Criterio específico | Acciones realizadas | Conclusiones |
| :---- | :---- | :---- |
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta.** | **Eduardo Martín Guillen Chavez**<br>**AV1:** Lideró la definición arquitectónica desarrollando el Big Picture Event Storming, los diagramas C4 y la Domain Driving Architecture. Además, orientó la visión del producto colaborando en el needfinding, la task matrix y el Ubiquitous Language, participando también en el video del equipo.<br>**TB1:** Lideró el desarrollo de los Bounded Contexts "Alert and Risk Evaluation" y "Monitoring Asset and Deployement". Apoyó activamente en el Sprint 2 y en las correcciones conjuntas del informe.<br><br>**Pancorbo Amorós, Italo Raul**<br>**AV1:** Ejerció el rol de Team Leader gestionando la organización de ramas y merges del repositorio. Guió el diseño técnico mediante el desarrollo de diagramas ERD y de clase, y coordinó esfuerzos colaborando en el Capítulo 1, Capítulo V, las User Stories (US), el Ubiquitous Language, además de realizar 1 entrevista y participar en el video.<br>**TB1:** Mantuvo su rol de Team Leader. Lideró el desarrollo técnico de los Bounded Contexts "Project Road Site Management", "Environmental Monitoring" y "Commercial and Sucription Management". Además, colaboró en el Sprint 2 y en las correcciones del informe.<br><br>**Román López, Miguel Ángel Junior**<br>**AV1:** Lideró la ejecución técnica y visual inicial colaborando estrechamente con el desarrollo de los Mockups y wireframes, y responsabilizándose por el despliegue de la landing page.<br>**TB1:** Asumió el liderazgo del Bounded Context "Incident and Remediation Management", contribuyendo también al Sprint 2 y a las correcciones del informe.<br><br>**Taza Curay, Eduardo Miguel**<br>**AV1:** Apoyó en la dirección del diseño de interfaces colaborando en el Figma y en el repositorio de la landing page. Aportó a la investigación y documentación desarrollando 2 entrevistas, colaborando en el Capítulo V y participando en el video.<br>**TB1:** Lideró el desarrollo del Bounded Context "Compliance and Reporting". Apoyó en las tareas del Sprint 2 y en el levantamiento de correcciones del informe.<br><br>**Andy Alfredo Hipolito Salcedo Muñoz**<br>**AV1:** Dirigió la investigación de mercado mediante el desarrollo de competidores y análisis competitivo. Lideró la redacción del Capítulo 1 y Capítulo 3, desarrolló 1 entrevista y colaboró en la task matrix, además de participar en el video.<br>**TB1:** Se encargó de liderar el Bounded Context "IAM", sumado a su colaboración en el desarrollo del Sprint 2 y la corrección general del informe. | **AV1:** Durante el primer avance (AV1), el equipo Kaimán demostró un claro liderazgo compartido para el desarrollo del producto EcoRoad. Cada miembro asumió el liderazgo en áreas clave según sus fortalezas: arquitectura de software, gestión de repositorio, diseño de interfaces (Figma/Mockups) y análisis de mercado/competencia. La correcta organización de ramas bajo la guía del Team Leader y la toma de decisiones conjuntas en artefactos críticos como el Event Storming y el Ubiquitous Language reflejan un esfuerzo coordinado donde todos aportaron al direccionamiento del proyecto y cumplieron sus responsabilidades a tiempo y con calificación perfecta.<br><br>**TB1:** Durante el Trabajo Parcial (TB1), el equipo mantuvo la constancia en el liderazgo compartido. Se delegaron responsabilidades específicas de arquitectura mediante la asignación de Bounded Contexts a cada integrante, permitiendo que todos lideraran una porción crítica del sistema de forma equitativa. La colaboración unánime en el desarrollo del Sprint 2 y en las correcciones del informe refleja un gran trabajo conjunto bajo la gestión continua del Team Leader. |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.** | **Eduardo Martín Guillen Chavez**<br>**AV1:** Fomentó la integración de los requisitos del usuario con la arquitectura técnica cumpliendo con sus tareas de needfinding y diagramas en los plazos establecidos. Su participación en el video evidenció su compromiso con las dinámicas integradoras del grupo.<br>**TB1:** Cumplió a tiempo y con máxima calificación (20) sus metas de desarrollo de Bounded Contexts, colaborando asertivamente en las correcciones y el Sprint 2.<br><br>**Pancorbo Amorós, Italo Raul**<br>**AV1:** Planificó el entorno de trabajo colaborativo al establecer el flujo de control de versiones (ramas y merges) para el equipo. Cumplió los objetivos técnicos y documentales asignados, facilitando un entorno donde se pudieron integrar las entrevistas y las User Stories de manera fluida.<br>**TB1:** Logró cumplir a tiempo con sus tres Bounded Contexts asignados y apoyó proactivamente en el Sprint 2, obteniendo nota de 20.<br><br>**Román López, Miguel Ángel Junior**<br>**AV1:** Estableció y cumplió sus metas operativas logrando el despliegue funcional de la landing page. Creó un entorno de trabajo conjunto al colaborar directamente en los wireframes y mockups necesarios para el avance del grupo.<br>**TB1:** Logró todos sus objetivos a tiempo con calificación de 20, demostrando compromiso con su asignación documental y apoyando al equipo en el Sprint 2.<br><br>**Taza Curay, Eduardo Miguel**<br>**AV1:** Apoyó activamente a sus compañeros colaborando en repositorios compartidos y herramientas de diseño cooperativo como Figma. Cumplió su meta de recopilación de datos al realizar 2 entrevistas a tiempo y colaboró en la redacción del Capítulo V.<br>**TB1:** Fomentó un entorno colaborativo al cumplir oportunamente con sus entregables y apoyar transversalmente a sus compañeros en el Sprint 2 y en el informe (alcanzando calificación de 20).<br><br>**Andy Alfredo Hipolito Salcedo Muñoz**<br>**AV1:** Planificó y cumplió oportunamente con la entrega documental estructurando los Capítulos 1 y 3. Mantuvo una actitud colaborativa apoyando en la task matrix, realizando su entrevista correspondiente y uniéndose a sus compañeros en la grabación del video.<br>**TB1:** Cumplió puntualmente con sus responsabilidades asignadas (nota 20), integrándose al esfuerzo común del equipo para solventar las correcciones del informe y avanzar el Sprint 2. | **AV1:** El equipo logró consolidar un entorno inclusivo y orientado al cumplimiento de metas, evidenciado en la calificación máxima obtenida por todos los integrantes debido a la entrega puntual de sus asignaciones. La planificación de tareas fue efectiva, permitiendo que responsabilidades complejas —como el despliegue web, la elaboración de diagramas C4 y el desarrollo documental— se integraran exitosamente mediante una correcta gestión de repositorio. La activa participación de todo el equipo en las entrevistas, el diseño colaborativo en Figma y la grabación conjunta del video demuestran un fuerte compromiso con el trabajo en equipo y los objetivos del AV1.<br><br>**TB1:** Se mantuvo un entorno altamente productivo y colaborativo, logrando que el 100% de los integrantes cumpliera "a tiempo" con las responsabilidades planificadas. Esto se reflejó en la calificación perfecta unánime (20) para la entrega del TB1, evidenciando un firme compromiso con los plazos, la mejora continua grupal (mediante las correcciones en el informe) y el soporte mutuo para la ejecución del Sprint 2. |

## Evidencia AV2 del Student Outcome 5

La evidencia de AV2 se presenta por criterio y se basa en la reunión informada por el organizador, el tablero, los commits y el despliegue descritos en el [Capítulo V](docs/cap5-product-implementation-validation-and-deployment.md). Los aportes técnicos observados no sustituyen una evaluación individual ni prueban por sí solos la calidad de la colaboración.

### Liderazgo compartido

- **Pancorbo Amorós, Italo Raul:** organizó la reunión de planificación del Sprint 3 y desarrolló o integró proyectos, suscripciones, frontend, despliegue y enlace de la landing, según los commits registrados.
- **Roman Lopez, Miguel Angel Junior:** implementó la base del backend y los contextos de identidad, activos, monitoreo e incidencias.
- **Guillen Chavez, Eduardo Martín:** integró los contextos comercial, proyectos, alertas y cumplimiento, y publicó la referencia de la API en Scalar.
- **Taza Curay, Eduardo Miguel:** desarrolló en su rama la base del contexto de cumplimiento y reportes.
- **Salcedo Muñoz, Andy Alfredo Hipolito (`Andy777sdw`):** desarrolló en su rama la base del contexto de alertas.

### Metas, planificación y cumplimiento

El objetivo del Sprint 3 fue sustituir los datos simulados por servicios reales y publicar una versión integrada. El tablero de Trello facilitado por el equipo muestra **13 tarjetas en Done** y cero en las otras listas. La aplicación web, los servicios y MySQL aparecen desplegados en Railway; la landing está publicada en GitHub Pages. Los commits y las capturas respaldan entregables concretos, mientras que las horas estimadas, el acta de retrospectiva y parte de la validación funcional siguen pendientes en el capítulo 5. Por ello, el outcome se sustenta en planificación y aportes verificables, sin afirmar una evaluación completa de todos los escenarios de usuario.

## Conclusiones y recomendaciones
<a id="conclusiones-y-recomendaciones"></a>

EcoRoad avanzó desde la landing y la aplicación con API simulada hacia una versión integrada con frontend Vue, servicios ASP.NET Core y persistencia MySQL. La publicación en Railway y GitHub Pages, la documentación OpenAPI en Scalar y el proyecto vial mostrado en la aplicación respaldan el avance técnico del Sprint 3. El tablero registra 13 tareas terminadas; ese estado no equivale a validar todos los criterios de aceptación de las historias relacionadas.

La integración mostró que los contratos de datos entre componentes, la persistencia y las rutas de acceso deben comprobarse en el entorno publicado. Se recomienda completar un recorrido funcional registrado desde la landing hasta el reporte, repetirlo después de cerrar y abrir sesión, cotejar las estimaciones con Trello y documentar los defectos encontrados. Las entrevistas por segmento y la evaluación heurística deberán cerrar las conclusiones de validación sin anticipar respuestas de participantes.

## Video About-the-Team
<a id="video-about-the-team"></a>

[Enlace de OneDrive proporcionado por el equipo para el material About-the-Team](https://1drv.ms/u/c/113B281D1AF386CE/IQDIA62u6t2kR66h-7Q64BZfAUKamVKIwUIPtTvyU2wQ8io?e=v8ttgn). Antes de la entrega, verificar que el archivo compartido sea la versión final y que incluya escenas de trabajo real, narración del proceso y testimonios ante cámara de los cinco integrantes sobre sus actividades, outcomes y competencias.

## Bibliografía
<a id="bibliografia"></a>

- Equipo EcoRoad. (2026). *Capítulo V: Product Implementation, Validation & Deployment*. [Documento del proyecto](docs/cap5-product-implementation-validation-and-deployment.md).
- Equipo EcoRoad. (2026). *Tablero Sprint 3 – EcoRoad*. [Trello](https://trello.com/invite/b/6af96cc3b31b2f3ac6f7858d/ATTI06b3af4493183313e4c1b7fd9cdafe8cD3C2DA79/sprint-3-ecoroad).
- Equipo EcoRoad. (2026). *Video About-the-Product*. [OneDrive](https://1drv.ms/u/c/113B281D1AF386CE/IQDXJvOAgkOKTq1vVjRrzu_YAdsxD2o1nmj0KN3a8zEGrZE?e=CgGgNs).

## Anexos
<a id="anexos"></a>

- **Anexo A — Tablero del Sprint 3:** [Trello](https://trello.com/invite/b/6af96cc3b31b2f3ac6f7858d/ATTI06b3af4493183313e4c1b7fd9cdafe8cD3C2DA79/sprint-3-ecoroad) y [captura conservada en el repositorio](assets/images/chapter5/Sprint3-Trello-Board.png).
- **Anexo B — Aplicación y servicios publicados:** [landing](https://aplicaciones-web-1asi0730-2620-8130.github.io/EcoRoad-LandingPage/), [aplicación web](https://ecoroad-frontend-production.up.railway.app/) y [referencia de API](https://ecoroad-back-end-production.up.railway.app/scalar).
- **Anexo C — Evidencias de despliegue y ejecución:** imágenes y explicación en las secciones [5.2.3.5–5.2.3.7](docs/cap5-product-implementation-validation-and-deployment.md#5-2-3-5-execution-evidence-for-sprint-review).
- **Anexo D — Video About-the-Product:** [grabación en OneDrive](https://1drv.ms/u/c/113B281D1AF386CE/IQDXJvOAgkOKTq1vVjRrzu_YAdsxD2o1nmj0KN3a8zEGrZE?e=CgGgNs) y [captura inicial](assets/images/chapter5/EcoRoad-About-the-Product-Video.png).
- **Anexo E — Entrevistas de validación:** guion, registros y estado del análisis en [5.3](docs/cap5-product-implementation-validation-and-deployment.md#5-3-validation-interviews). Los enlaces a grabaciones individuales figuran en los registros correspondientes.
- **Anexo F — Material About-the-Team:** [enlace facilitado por el equipo](https://1drv.ms/u/c/113B281D1AF386CE/IQDIA62u6t2kR66h-7Q64BZfAUKamVKIwUIPtTvyU2wQ8io?e=v8ttgn); verificar el archivo final y sus permisos de acceso.
