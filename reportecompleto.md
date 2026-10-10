<div align="center">

<img src="assets/UPC_logo_transparente.png" alt="Logo-UPC" width="150">


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

**Octubre 2026**

</div>

---

<div style="page-break-after: always;"></div>

## Registro de Versiones del Informe

| Versión | Fecha | Autores | Descripción de modificación |
| :--- | :--- | :--- | :--- |
| **AV1** | 20/9 | Pancorbo Amorós , Italo Raul <br> Guillen Chavez , Eduardo Martín <br> Salcedo Muñoz , Andy Alfredo Hipolito <br> Taza Curay , Eduardo Miguel <br> Roman Lopez , Miguel Angel Junior | Para la entrega AV1 se consolidó la estructura del informe técnico, incluyendo carátula, registro de versiones, tabla de contenidos y la definición de Student Outcomes. <br><br>Capítulo I — Introducción: Se redactó el Startup Profile y el Solution Profile (EcoRoad), detallando la propuesta de valor para la gestión y construcción de proyectos viales. <br><br>Capítulo II — Requirements Elicitation & Analysis: Se realizó el análisis de competidores y el registro de entrevistas a profundidad. Se desarrolló el Needfinding (User Personas, Task Matrix, Journey Mapping), así como el Big Picture EventStorming para identificar los eventos clave del dominio y el Ubiquitous Language basado en los Bounded Contexts definidos.<br><br>Capítulo III — Requirements Specification: Se elaboró el Product Backlog priorizando las User Stories críticas. Se aplicó la metodología de Impact Mapping para alinear las funcionalidades con los objetivos estratégicos del negocio.<br><br>Capítulo IV — Product Design: Se definieron los lineamientos de estilo general y web, junto con la arquitectura de la información del sistema. Se documentó el diseño de las interfaces de usuario a través de wireframes y mock-ups para la Landing Page y la Web Application, abarcando tanto las vistas de escritorio como las adaptaciones móviles. Además, se estableció la arquitectura de software basada en Domain-Driven Design mediante los diagramas del modelo C4 (Contexto, Contenedor y Componentes), y se detalló el diseño técnico incorporando los diagramas de clases y de base de datos para los ocho Bounded Contexts del proyecto. <br><br> Capítulo V — Product Implementation: Se documentó la gestión de configuración de software, estándares de versionamiento (GitFlow) y convenciones de código. Se incluyó la evidencia del Sprint 1, detallando el Sprint Planning, Sprint Backlog (enfocado en US001, US002, US003 y US004), líderes de aspecto, métricas de colaboración y las evidencias del despliegue inicial de la Landing Page en GitHub Pages. |
| **TB1** | 9/10 | Pancorbo Amorós , Italo Raul <br> Guillen Chavez , Eduardo Martín <br> Salcedo Muñoz , Andy Alfredo Hipolito <br> Taza Curay , Eduardo Miguel <br> Roman Lopez , Miguel Angel Junior | Para la entrega del Trabajo Parcial (TB1) se incorporaron y actualizaron los siguientes apartados clave del proyecto EcoRoad:<br><br>Capítulo IV — Product Design: Se perfeccionaron y consolidaron los diagramas de diseño orientado a objetos (clases) y de bases de datos relacionales correspondientes a cada uno de los Bounded Contexts del sistema (Project Management, Identity & Access, Device & Asset Mgmt, Environmental Monitoring, Incident & Mitigation, Document & Evidence, Reports & Compliance y Subscriptions & Payment), alineándolos al enfoque de Monolito Modular.<br><br>Capítulo V — Product Implementation, Validation & Deployment: Se documentó el desarrollo correspondiente al Sprint 2, detallando la asignación de responsabilidades mediante la distribución de Bounded Contexts a cada integrante del equipo (evidenciado en el reporte de participación). Asimismo, se realizaron las correcciones y el levantamiento de observaciones generales del informe técnico estructurado en el avance anterior, asegurando la trazabilidad y calidad de la documentación del sistema. |
| **AV2** | | | |
| **TB2** | | | |

<div style="page-break-after: always;"></div>

# Project Report Collaboration Insights

# Tabla de Contenidos

## [Capítulo I: Introducción](#introduccion)

- [1.1. Startup Profile](#1-1-startup-profile)
  - [1.1.1. Descripción de la Startup](#1-1-1-descripcion-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#1-1-2-perfiles-de-los-miembros-del-equipo)
- [1.2. Solution Profile](#1-2-solution-profile)
  - [1.2.1. Antecedentes y problemática](#1-2-1-antecedentes-y-problematica)
  - [1.2.2. Lean UX Process](#1-2-2-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1-2-2-1-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1-2-2-2-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1-2-2-3-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1-2-2-4-lean-ux-canvas)
- [1.3. Segmentos objetivo](#1-3-segmentos-objetivos)

---

## [Capítulo II: Requirements Elicitation & Analysis](#2-requirements-elicitation-analysis)

- [2.1. Competidores](#2-1-competidores)
  - [2.1.1. Análisis competitivo](#2-1-1-analisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#2-1-2-estrategias-y-tacticas-frente-a-competidores)
- [2.2. Entrevistas](#2-2-entrevistas)
  - [2.2.1. Diseño de entrevistas](#2-2-1-diseno-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#2-2-2-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#2-2-3-analisis-de-entrevistas)
- [2.3. Needfinding](#2-3-needfinding)
  - [2.3.1. User Personas](#2-3-1-user-personas)
  - [2.3.2. User Task Matrix](#2-3-2-user-task-matrix)
  - [2.3.3. User Journey Mapping](#2-3-3-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#2-3-4-empathy-mapping)
- [2.4. Big Picture Event Storming](#2-4-big-picture-eventstorming)
- [2.5. Ubiquitous Language](#2-5-ubiquitous-language)

---

## [Capítulo III: Requirements Specification](#3-requirements-specification)

- [3.1. User Stories](#3-1-user-stories)
- [3.2. Impact Mapping](#3-2-impact-mapping)
- [3.3. Product Backlog](#3-3-product-backlog)

---

## [Capítulo IV: Product Design](#4-product-design)

- [4.1. Style Guidelines](#4-1-style-guidelines)
  - [4.1.1. General Style Guidelines](#4-1-1-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#4-1-2-web-style-guidelines)
- [4.2. Information Architecture](#4-2-information-architecture)
  - [4.2.1. Organization Systems](#4-2-1-organization-systems)
  - [4.2.2. Labeling Systems](#4-2-2-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](#4-2-3-seo-tags-meta-tags)
  - [4.2.4. Searching Systems](#4-2-4-searching-systems)
  - [4.2.5. Navigation Systems](#4-2-5-navigation-systems)
- [4.3. Landing Page UI Design](#4-3-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#4-3-1-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#4-3-2-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#4-4-web-applications-ux-ui-design)
  - [4.4.1. Web Applications Wireframes](#4-4-1-web-applications-wireframes)
  - [4.4.2. Web Applications Wireflow Diagrams](#4-4-2-web-applications-wireflow-diagrams)
  - [4.4.3. Web Applications Mock-ups](#4-4-3-web-applications-mock-ups)
  - [4.4.4. Web Applications User Flow Diagrams](#4-4-4-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#4-5-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#4-6-domain-driven-software-architecture)
  - [4.6.1. Design-Level Event Storming.](#4-6-1-design-level-eventstorming)
  - [4.6.2. Software Architecture Context Diagram](#4-6-2-software-architecture-context-diagram)
  - [4.6.3. Software Architecture Container Diagrams](#4-6-3-software-architecture-container-diagrams)
  - [4.6.4. Software Architecture Components Diagrams](#4-6-4-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#4-7-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#4-7-1-class-diagrams)
- [4.8. Database Design](#4-8-database-design)
  - [4.8.1. Database Diagram](#4-8-1-database-diagrams)

---

## [Capítulo V: Product Implementation, Validation & Deployment](#product-implementation-validation-deployment)

- [5.1. Software Configuration Management](#5-1-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#5-1-1-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#5-1-2-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#5-1-3-source-code-style-guide-conventions)
  - [5.1.4. Software Deployment Configuration](#5-1-4-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#5-2-landing-page-services-applications-implementation)
  - [5.2.1. Sprint 1](#5-2-1-sprint-1)
    - [5.2.1.1. Sprint Planning 1](#5-2-1-1-sprint-planning-1)
    - [5.2.1.2. Aspect Leaders and Collaborators](#5-2-1-2-aspect-leaders-and-collaborators)
    - [5.2.1.3. Sprint Backlog 1](#5-2-1-3-sprint-backlog-1)
    - [5.2.1.4. Development Evidence for Sprint Review](#5-2-1-4-development-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](#5-2-1-5-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5-2-1-6-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5-2-1-7-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](#5-2-1-8-team-collaboration-insights-during-sprint)
  - [5.2.2. Sprint 2](#5-2-2-sprint-2)
      - [5.2.2.1. Sprint Planning 2](#5-2-2-1-sprint-planning-2)
      - [5.2.2.2. Aspect Leaders and Collaborators](#5-2-2-2-aspect-leaders-and-collaborators)
      - [5.2.2.3. Sprint Backlog 2](#5-2-2-3-sprint-backlog-2)
      - [5.2.2.4. Development Evidence for Sprint Review](#5-2-2-4-development-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review](#5-2-2-5-execution-evidence-for-sprint-review)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5-2-2-6-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5-2-2-7-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint](#5-2-2-8-team-collaboration-insights-during-sprint)

---

## [Conclusiones](#conclusiones)

- [Conclusiones y recomendaciones](#conclusiones)



## [Bibliografía](#bibliografia)

---

## [Anexos](#anexos)

# ABET – EAC - Student Outcome 5


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


# Capítulo 1

## Introducción

La presente sección introduce el proyecto EcoRoad, una propuesta tecnológica orientada a mejorar la gestión y el monitoreo ambiental en proyectos de infraestructura vial. En este capítulo se presenta el perfil de la startup, su propósito y las principales características que definen la solución propuesta.

EcoRoad surge ante la necesidad de contar con una gestión ambiental más oportuna, centralizada y trazable durante la ejecución, mantenimiento y rehabilitación de proyectos viales. La propuesta busca aprovechar tecnologías como el Internet de las Cosas (IoT) para recopilar información ambiental en tiempo 
real y transformarla en acciones que permitan atender oportunamente los riesgos identificados.

Asimismo, se presenta el enfoque de EcoRoad como una plataforma web bajo un modelo SaaS, diseñada para que las empresas puedan gestionar múltiples proyectos desde un mismo entorno digital. La solución integra el monitoreo de indicadores ambientales con la detección de riesgos, generación de alertas, gestión de incidencias, seguimiento de acciones correctivas y registro de evidencias.

De esta manera, el capítulo permite comprender la identidad y finalidad de EcoRoad, así como el valor que busca aportar a las empresas vinculadas con la ejecución y conservación de infraestructura vial.


## 1.1 Startup Profile
<a id="1-1-Startup-Profile"></a>

El perfil de la startup permite establecer las características fundamentales de EcoRoad y definir el enfoque que orienta el desarrollo de la propuesta. En esta sección se presenta la identidad de la plataforma, su propósito y 
la forma en que busca responder a las necesidades de gestión ambiental presentes en los proyectos de infraestructura vial.

EcoRoad se plantea como una solución tecnológica B2B enfocada en empresas relacionadas con la construcción, mantenimiento y rehabilitación de vías. 
Su propuesta combina una plataforma web SaaS con dispositivos IoT para centralizar información ambiental, analizar las mediciones obtenidas y facilitar la gestión de los riesgos e incidencias identificados durante las operaciones.

La propuesta de EcoRoad se centra en pasar de un enfoque basado únicamente en la recopilación y visualización de datos a uno orientado a la gestión. Para ello, 
la plataforma conecta el monitoreo ambiental con un flujo de respuesta que comprende la detección del riesgo, generación de alertas, creación y seguimiento de incidencias, ejecución de acciones correctivas, registro de evidencias y cierre de los eventos.

Este enfoque busca proporcionar a las empresas una herramienta que les permita mantener la información ambiental de sus proyectos organizada, accesible y trazable, 
facilitando la toma de decisiones y el seguimiento de las acciones realizadas frente a los riesgos detectados.


### 1.1.1 Descripción de la Startup
<a id="1-1-1-Descripción-de-la-Startup"></a>

EcoRoad es una plataforma web SaaS diseñada para transformar la gestión ambiental en el sector de infraestructura vial. A diferencia de las soluciones tradicionales que solo visualizan datos, EcoRoad integra 
dispositivos IoT en tiempo real para capturar indicadores críticos (aire, ruido, agua, vibraciones) y los convierte automáticamente en un flujo de trabajo trazable: desde la detección del 
riesgo y la emisión de alertas, hasta la asignación de acciones correctivas y el registro de evidencias en campo.

Orientada a empresas constructoras y de conservación vial, la plataforma permite centralizar múltiples proyectos en un solo lugar. Su modelo de negocio se basa en 
planes de suscripción mensuales o anuales (Starter, Professional y Enterprise) adaptados a la escala de cada cliente, complementado con un esquema flexible de alquiler independiente de sensores IoT. Así, EcoRoad no es solo una herramienta de monitoreo, sino un ecosistema integral que impulsa una ingeniería civil preventiva, transparente y sostenible.

**Misión**
Desarrollar soluciones tecnológicas robustas, eficientes y centradas en la gestión ambiental, que permitan a las empresas constructoras y de conservación vial gestionar sus operaciones de manera transparente y en tiempo real. En EcoRoad nos enfocamos en la innovación constante, la integración de tecnologías IoT y la transformación de datos en acciones correctivas trazables, con el fin de mitigar riesgos ambientales y contribuir a una gestión más sostenible de los proyectos de infraestructura vial.

**Visión**
Convertirnos en la plataforma SaaS líder en gestión y monitoreo ambiental para el sector de infraestructura vial en Latinoamérica, integrando tecnologías emergentes como el Internet de las Cosas y la analítica automatizada de datos. Aspiramos a transformar la gestión ambiental de los proyectos viales en un proceso dinámico, predictivo y preventivo, contribuyendo al desarrollo de una infraestructura vial más sostenible.


### 1.1.2. Perfiles de los Miembros del Equipo
<a id="1-1-2-perfiles-de-los-miembros-del-equipo"></a>

| Foto | Apellido y Nombre | 
| :---: | :--- | 
| ![Eduardo Martin Guillen Chavez](/assets/images/chapter1/Eduardo.png) | Eduardo Martín Guillén Chávez |
| ![Andy Alfredo Hipólito Salcedo Muñoz](/assets/images/chapter1/Andy.png) | Andy Alfredo Hipolito Salcedo Muñoz | 
| ![Italo](/assets/images/chapter1/Italo.jpeg) | Italo Raul Pancorbo Amorós |
| ![Miguel](/assets/images/chapter1/Miguel.png) | Miguel Angel Junior Roman Lopez |
| ![Eduardo](/assets/images/chapter1/Eduardo2.png) | Eduardo Miguel Taza Curay |


## 1.2 Solution Profile
<a id="1-2-solution-profile"></a>

*EcoRoad* es una plataforma digital integral basada en un modelo SaaS, diseñada para dar soporte a los procesos de monitoreo, control y auditoría ambiental en proyectos de infraestructura vial. Permite a empresas constructoras y consultoras ambientales registrar indicadores ambientales, detectar automáticamente incumplimientos normativos y visualizar en tiempo real, sobre un mapa geolocalizado, el estado de salud ambiental de sus obras.

### 1.2.1 Antecedentes y Problemática
<a id="1-2-1-antecedentes-y-problematica"></a>

La actividad constructora es uno de los motores más dinámicos de la economía peruana, con la obra pública —donde la infraestructura vial tiene un peso importante— como uno de los principales impulsores del crecimiento sectorial (CAPECO, 2025). La ejecución de estos proyectos está sujeta a un marco normativo ambiental cada vez más exigente, fiscalizado para el subsector transportes por la Dirección de Gestión Ambiental del MTC, mientras que la gestión ambiental y los planes de mitigación requeridos recaen en las propias empresas ejecutoras y de conservación vial bajo la fiscalización del MTC y OEFA., que agrupa a 1,293 consultoras habilitadas a nivel nacional (SENACE, 2024). A pesar de este marco, la digitalización del monitoreo ambiental en obra sigue siendo incipiente, mientras el OEFA avanza hacia una fiscalización más estricta apoyada en monitoreo continuo (OEFA, 2025).

#### What / ¿QUÉ?

EcoRoad busca resolver la fragmentación y el registro manual de datos ambientales durante la ejecución de proyectos viales, integrando tableros geolocalizados en tiempo real, un motor automatizado de alertas e incidencias y un dashboard de control multi-proyecto en un único sistema.

#### When / ¿CUÁNDO?

Esta necesidad es crítica en el contexto actual, en el que la fiscalización ambiental avanza hacia una mayor exigencia tecnológica y en el que la reactivación de la inversión vial incrementa el número de obras activas que requieren monitoreo simultáneo.

#### Where / ¿DÓNDE?

Ocurre principalmente en los proyectos de infraestructura vial ejecutados en el Perú, tanto en zonas urbanas como en tramos interprovinciales, así como en las oficinas centrales de las empresas constructoras y consultoras que supervisan dichos proyectos de forma remota.

#### Who / ¿QUIÉN?

Afecta principalmente a las empresas constructoras y a las empresas de mantenimiento y rehabilitación vial que ejecutan y conservan las obras viales, las cuales deben evidenciar el cumplimiento ambiental y gestionar los riesgos operativos ante entidades fiscalizadoras (MTC, OEFA).

#### Why / ¿POR QUÉ?

Porque las infracciones ambientales no detectadas a tiempo generan sanciones económicas, restricciones para participar en licitaciones públicas y daño reputacional. Centralizar el monitoreo y automatizar la detección de incumplimientos reduce el riesgo regulatorio y optimiza el tiempo dedicado a auditorías.

#### How / ¿CÓMO?

Mediante EcoRoad, una plataforma web centralizada en la nube donde el personal de campo registra los indicadores ambientales, el motor automatizado los compara contra los límites normativos y, ante una superación, genera una alerta y crea un ticket de incidencia visible en los tableros y el dashboard geolocalizados.

#### How Much / ¿CUÁNTO?

El modelo de ingresos es de tipo SaaS, mediante planes de suscripción escalables: *Base, **Profesional* y *Enterprise*, diferenciados por número de proyectos, usuarios y funcionalidades de análisis incluidas.

### 1.2.2 Lean UX Process
<a id="1-2-2-lean-ux-process"></a>

#### 1.2.2.1. Lean UX Problem Statements
<a id="1-2-2-1-lean-ux-problem-statements"></a>

El estado actual de *la gestión ambiental en proyectos de infraestructura vial* se ha enfocado principalmente en *el registro manual y disperso de indicadores ambientales, sin herramientas de análisis automatizado ni visualización centralizada, lo que provoca **detección tardía de incumplimientos normativos, mayor exposición a sanciones y auditorías lentas y costosas.* Esta situación afecta a *empresas constructoras y de mantenimiento vial*, quienes dependen de métodos desactualizados para monitorear y documentar el cumplimiento ambiental de sus proyectos.

Lo que los productos o servicios existentes no logran resolver es la *centralización digital, en tiempo real, del monitoreo ambiental y la gestión de incidencias en proyectos viales. Nuestro producto, **EcoRoad**, abordará esta brecha mediante una plataforma web SaaS que centraliza el registro de indicadores ambientales, detecta automáticamente las superaciones normativas y ofrece tableros geolocalizados para visualizar múltiples proyectos en simultáneo.

Nuestro enfoque inicial estará dirigido a *empresas constructoras y de mantenimiento vial que ejecutan y conservan proyectos viales en el Perú*. Sabremos que tenemos éxito cuando observemos una reducción medible en el tiempo de detección de incumplimientos, mayor cantidad de incidencias resueltas antes de una fiscalización externa, y una reducción en el tiempo dedicado a preparar auditorías.

#### 1.2.2.2. Lean UX Assumptions
<a id="1-2-2-2-lean-ux-assumptions"></a>

##### A. Business Assumptions

1. *Creemos que nuestros clientes necesitan:* un sistema de monitoreo ambiental centralizado y en tiempo real para sus proyectos viales.
2. *Estas necesidades se resuelven con:* una plataforma SaaS que registra indicadores ambientales, detecta automáticamente incumplimientos normativos y visualiza el estado de los proyectos en un mapa.
3. *Nuestros primeros clientes serán:* empresas constructoras y de conservación vial que operan en Lima y otras regiones del Perú.
4. *Valor #1 esperado:* reducir el riesgo de sanciones por incumplimiento normativo mediante la detección temprana de incidencias.
5. *Beneficios adicionales:* optimización del tiempo de auditoría, trazabilidad de los datos ambientales y mejora de la reputación institucional.
6. *Adquisición:* alianzas con gremios del sector construcción (CAPECO), referidos sectoriales y marketing digital dirigido a gerentes de operaciones y proyectos.
7. *Ingresos:* suscripción mensual o anual bajo planes escalables (Base, Profesional, Enterprise).
8. *Competencia principal:* hojas de cálculo, sistemas de gestión documental genéricos y soluciones de monitoreo ambiental orientadas a otros sectores (minería, hidrocarburos).
9. *Ventaja competitiva:* especialización en el dominio de proyectos viales, con motor de alertas automatizado y visualización geolocalizada nativa.
10. *Mayor riesgo de producto:* que los equipos de campo no adopten el registro digital y continúen usando métodos manuales en paralelo.
11. *Mitigación:* diseñar una interfaz simple y rápida de usar en campo, integrada con los flujos de trabajo ya existentes de los equipos de monitoreo.

###### B. User Assumptions

*- ¿Quién es el usuario?* Responsables de gestión ambiental, ingenieros residentes de obra y supervisores de campo.

*- ¿Dónde encaja el producto?* En el proceso diario de monitoreo y control ambiental de un proyecto vial en ejecución o conservación.

*- Problema a resolver:* la falta de visibilidad en tiempo real del cumplimiento normativo ambiental.

*- Uso típico:* registro de mediciones de campo, revisión de alertas, consulta de tableros y generación de reportes para auditorías.

*- Características importantes:* alertas automáticas, geolocalización, generación de reportes y acceso multiusuario por proyecto.

*- Look & feel:* interfaz simple tipo dashboard, con codificación por color según nivel de riesgo (semáforo), pensada para uso rápido en campo desde dispositivos móviles.

##### C. User Outcome & Benefit Assumptions

- Los responsables de gestión ambiental identifican incidencias antes de que escalen a una infracción formal.
- Los supervisores de obra reducen el tiempo dedicado a consolidar reportes manuales.
- Las empresas constructoras y de mantenimiento entregan informes de auditoría con mayor rapidez y respaldo de datos trazables.
- Los equipos de campo perciben la plataforma como una herramienta que simplifica su trabajo diario, no como una carga adicional.

##### D. Business Outcome Assumptions

- Incremento en el número de empresas suscritas a los planes Profesional y Enterprise.
- Reducción medible en el tiempo promedio de detección de incumplimientos normativos entre los clientes activos.
- Aumento en la tasa de renovación de suscripciones tras el primer ciclo de facturación.
- Mayor volumen de proyectos gestionados por cliente a lo largo del tiempo.

##### E. Feature Assumptions

1. *Tableros Geolocalizados en Tiempo Real:* mapean los proyectos y muestran el estado de los indicadores ambientales (aire, ruido, agua) por punto de monitoreo.
2. *Generador de Reportes de Auditoría Automático:* consolida el histórico de indicadores e incidencias en documentación exportable para fiscalizaciones.
3. *Sistema de Alertas Tempranas:* compara los datos ingresados frente a los límites normativos y crea automáticamente un ticket de incidencia ante una superación.
4. *Dashboard de Control Geolocalizado Multi-Proyecto:* consolida el estado ambiental de múltiples proyectos viales en un mismo mapa.

#### 1.2.2.3. Lean UX Hypothesis Statements
<a id="1-2-2-3-lean-ux-hypothesis-statements"></a>

##### Visualización y Control Centralizado

Creemos que lograremos una detección más temprana de superaciones normativas y una mejor priorización de los recursos de supervisión, si los responsables de gestión ambiental y supervisores de obra obtienen visibilidad inmediata y geolocalizada del estado de los indicadores ambientales de sus proyectos, con tableros geolocalizados en tiempo real.

##### Automatización de Reporteo

Creemos que lograremos una reducción en el tiempo y costo de preparación de auditorías, si los equipos de gestión ambiental y consultoras ambientales obtienen documentación consolidada y trazable del histórico de indicadores e incidencias de un proyecto, con un generador de reportes de auditoría automático.

##### Estandarización de Procesos

Creemos que lograremos una reducción en el tiempo de respuesta ante incumplimientos normativos y una gestión de incidencias más consistente entre proyectos, si los responsables de gestión ambiental reciben notificaciones inmediatas y un registro automático de incidencias ante una superación de los límites normativos, con un sistema de alertas tempranas.

##### Optimización de Recursos

Creemos que lograremos una gestión más eficiente de carteras de múltiples proyectos viales, si las empresas constructoras y consultoras ambientales que gestionan varios proyectos acceden a una visualización consolidada del estado ambiental de todos sus proyectos en un solo mapa, con un dashboard de control geolocalizado multi-proyecto.

#### 1.2.2.4. Lean UX Canvas
<a id="1-2-2-4-lean-ux-canvas"></a>

| **1. Business Problems** | **2. Business Outcomes** | **3. Users** | **4. User Outcomes** |
| :--- | :--- | :--- | :--- |
| • Registro manual y disperso de indicadores ambientales en proyectos viales.<br>• Falta de visibilidad en tiempo real y detección tardía de superaciones normativas.<br>• Exposición a sanciones severas (OEFA/MTC) y procesos de auditoría lentos y costosos.<br>• Desconfianza estructural entre empresas constructoras y supervisoras. | • Incremento en la adquisición de suscripciones corporativas (planes Profesional y Enterprise).<br>• Reducción medible en el tiempo promedio de detección de incumplimientos normativos.<br>• Aumento en la tasa de renovación y retención de clientes tras el primer ciclo.<br>• Mayor volumen de proyectos gestionados por cliente en simultáneo. | • Responsables de gestión ambiental e ingenieros residentes de obra.<br>• Supervisores de campo de empresas constructoras viales.<br>• Auditores y consultores ambientales registrados en el RNCA (SENACE).<br>• Gerentes de cartera y PMO corporativa. | • Identifican incidencias antes de que escalen a multas o paralizaciones.<br>• Reducen el tiempo operativo dedicado a consolidar planillas y reportes en papel.<br>• Generan expedientes de auditoría con datos inalterables y trazables.<br>• Perciben una herramienta que agiliza su trabajo diario en campo y oficina


# Requirements Elicitation & Analysis
<a id="2-requirements-elicitation-analysis"></a>

## 2.1 Competidores
<a id="2-1-competidores"></a>

### 2.1.1 Analisis Competitivo
<a id="2-1-1-analisis-competitivo"></a>

<table style="border: 1px solid ; border-collapse: collapse; width: 100%;">
  <thead>
    <tr>
       <th colspan="6" style="border: 1px solid ; text-align: left; padding: 8px;"><strong>Competitive Analysis Landscape</strong></th>
    </tr>
    <tr>
      <td style="font-weight: bold; width: 18%;">¿Por qué llevar a cabo este análisis?</td>
      <td colspan="5" style="text-align: justify;">
        <strong>Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</strong><br><br>
        El objetivo de este análisis es evaluar las soluciones tecnológicas existentes en el mercado de monitoreo ambiental y gestión de obras —tanto a nivel de hardware especializado como de plataformas SaaS y suites de construcción— para identificar brechas operativas en el sector de infraestructura vial. A través de este contraste, Caiman busca validar su posicionamiento estratégico basado en un modelo híbrido HaaS/SaaS neutral, automatización preventiva de incidencias y aseguramiento de datos inalterables frente a la competencia directa e indirecta.
      </td>
    </tr>
    <tr align="center">
      <th colspan="2" style="vertical-align: middle;">(En la cabecera colocar por cada competidor nombre y logo)</th>
      <th style="vertical-align: middle;"><strong>Su startup</strong><br><br><strong>EcoRoad (Caiman)</strong><br><br><img src="assets/img/Chapter2/EcoRoadLogo.png" alt="Logo EcoRoad" width="110"/></th>
      <th style="vertical-align: middle;"><strong>Competidor 1</strong><br><br><strong>SiteHive</strong><br><br><img src="assets/img/Chapter2/SiteHiveLogo.png" alt="Logo SiteHive" width="110"/></th>
      <th style="vertical-align: middle;"><strong>Competidor 2</strong><br><br><strong>Sonitus Systems</strong><br><br><img src="assets/img/Chapter2/SonitusSystemsLogo.png" alt="Logo Sonitus Systems" width="110"/></th>
      <th style="vertical-align: middle;"><strong>Competidor 3</strong><br><br><strong>Autodesk CC</strong><br><br><img src="assets/img/Chapter2/AutodeskCCLogo.png" alt="Logo Autodesk CC" width="110"/></th>
    </tr>
  </thead>
  <tbody>
    <!-- SECCIÓN PERFIL -->
    <tr>
      <td rowspan="2" align="center" style="font-weight: bold; vertical-align: middle;">Perfil</td>
      <td style="font-weight: bold;">Overview</td>
      <td>Plataforma HaaS/SaaS integrada con red propia de sensores IoT en comodato para monitoreo ambiental (aire, ruido, agua) y gestión preventiva en obras viales.</td>
      <td>Plataforma SaaS australiana especializada en monitoreo ambiental continuo (ruido, polvo, vibración) para construcción y minería.</td>
      <td>Proveedor global especializado en instrumentación y monitorización IoT de nivel de ruido y calidad del aire para monitoreo ambiental.</td>
      <td>Suite integral de software basada en la nube para la gestión de proyectos de construcción, flujos de trabajo BIM y control documental.</td>
    </tr>
    <tr>
      <td style="font-weight: bold;">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
      <td>Modelo HaaS sin inversión inicial de hardware, automatización de acciones correctivas y motor de mitigación preventiva para constructoras y empresas de mantenimiento vial.</td>
      <td>Automatización del procesamiento de datos ambientales de campo con algoritmos de reconocimiento de eventos de ruido mediante IA.</td>
      <td>Equipos de medición de alta robustez, precisión instrumental y cumplimiento estricto de estándares internacionales de calibración sonora.</td>
      <td>Integración nativa y madura con modelos BIM (Revit/Civil 3D), gestión de calidad global y amplia adopción corporativa en el sector.</td>
    </tr>
    <!-- SECCIÓN MARKETING -->
    <tr>
      <td rowspan="2" align="center" style="font-weight: bold; vertical-align: middle;">Perfil de Marketing</td>
      <td style="font-weight: bold;">Mercado objetivo</td>
      <td>Empresas constructoras viales y empresas de mantenimiento y rehabilitación vial que operan múltiples proyectos en Perú y LatAm.</td>
      <td>Contratistas generales de edificación e infraestructura pesada en Australia, Nueva Zelanda, Reino Unido y Norteamérica.</td>
      <td>Consultores acústicos, autoridades municipales, firmas ambientales y proyectos industriales a nivel internacional.</td>
      <td>Empresas constructoras de gran envergadura, consorcios de ingeniería, firmas de diseño y entidades públicas a nivel global.</td>
    </tr>
    <tr>
      <td style="font-weight: bold;">Estrategias de marketing</td>
      <td>Alianzas con gremios sectoriales (CAPECO), prospección directa B2B a gerentes de operaciones de constructoras y concesionarias viales.</td>
      <td>Inbound marketing, casos de éxito en megaproyectos urbanos, marketing de contenidos sobre sostenibilidad y webinars técnicos.</td>
      <td>Venta consultiva técnica B2B, presencia en ferias de instrumentación acústica/ambiental y red de distribuidores de hardware.</td>
      <td>Campañas masivas B2B, certificaciones profesionales oficiales, red de partners globales y promociones integradas en el ecosistema Autodesk.</td>
    </tr>
    <!-- SECCIÓN PRODUCTO -->
    <tr>
      <td rowspan="3" align="center" style="font-weight: bold; vertical-align: middle;">Perfil de Producto</td>
      <td style="font-weight: bold;">Productos & Servicios</td>
      <td>Red de sensores IoT (ruido, material particulado, calidad de agua, vibraciones), tablero geolocalizado multitramo, sistema de incidencias y reportes legales en PDF.</td>
      <td>Dispositivos de monitoreo SiteHive (Hexanode), software cloud con mapas en tiempo real, alertas por correo/SMS y reportes de cumplimiento.</td>
      <td>Equipos de medición física (sonómetros Sonitus EM2010, monitores de polvo) integrados a su plataforma web Sonitus Cloud de análisis histórico.</td>
      <td>Módulos de Autodesk Build, BIM Collaborate, Docs y Takeoff; herramientas de incidencias generales (RFI), planos y control de avance.</td>
    </tr>
    <tr>
      <td style="font-weight: bold;">Precios & Costos</td>
      <td>Suscripción dual HaaS mensual o anual (planes Starter, Professional, Enterprise) que incluye software, soporte y alquiler flexible de sensores IoT.</td>
      <td>Suscripción SaaS por dispositivo activo al mes/año; el hardware requiere alquiler por separado o compra directa del kit.</td>
      <td>Venta directa de hardware (costo de capital elevado por equipo) más suscripción periódica por acceso a la plataforma Sonitus Cloud.</td>
      <td>Licenciamiento por usuario/mes o esquema corporativo por volumen de facturación del proyecto (tarifas premium elevadas).</td>
    </tr>
    <tr>
      <td style="font-weight: bold;">Canales de distribución (Web y/o Móvil)</td>
      <td>Plataforma Web responsiva accesible vía navegador de escritorio y móvil, con despliegue de hardware directo en frentes de obra vial.</td>
      <td>Aplicación Web para navegador y versión optimizada para navegadores móviles.</td>
      <td>Plataforma Web (Sonitus Cloud) y distribución física de sensores a través de canales logísticos y representantes locales.</td>
      <td>Aplicación Web de escritorio, aplicaciones móviles dedicadas (iOS y Android) y extensiones de escritorio integradas.</td>
    </tr>
    <!-- SECCIÓN SWOT -->
    <tr>
      <td rowspan="5" align="center" style="font-weight: bold; vertical-align: middle;">Análisis SWOT</td>
      <td colspan="5"><em>Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</em></td>
    </tr>
    <tr>
      <td style="font-weight: bold;">Fortalezas</td>
      <td>Modelo de ingresos HaaS flexible (cero CapEx forzoso en sensores), flujo completo desde detección IoT hasta cierre de acciones correctivas y gestión multi-proyecto.</td>
      <td>Plataforma de software intuitiva, algoritmos avanzados de clasificación de fuentes de ruido y marca validada en mercados desarrollados.</td>
      <td>Alta precisión de hardware, sensores certificados bajo normas IEC/ISO y larga vida útil de los equipos en campo.</td>
      <td>Posición dominante del mercado global, ecosistema de software interconectado y solidez técnica/financiera corporativa.</td>
    </tr>
    <tr>
      <td style="font-weight: bold;">Debilidades</td>
      <td>Startup en etapa inicial, catálogo de parámetros físicos limitado al alcance de la primera versión y red operativa de despliegue en consolidación.</td>
      <td>Dependencia de conectividad de red celular estable, costos elevados para proyectos medianos en economías emergentes y soporte regional limitado.</td>
      <td>La plataforma de software funciona principalmente como visor pasivo de telemetría, careciendo de gestión preventiva operativa de obra.</td>
      <td>No cuenta con verticalización nativa para estándares ambientales locales (ECA Perú) ni provisión propia de hardware IoT ambiental.</td>
    </tr>
    <tr>
      <td style="font-weight: bold;">Oportunidades</td>
      <td>Normativas ambientales peruanas más rigurosas (fiscalización continua MTC/OEFA) y necesidad de mitigar riesgos de multas en constructoras y concesionarias.</td>
      <td>Expansión hacia regulaciones de descarbonización e iniciativas ESG en obras de infraestructura civil internacional.</td>
      <td>Crecimiento de proyectos de ciudades inteligentes y ordenanzas municipales de control estricto de contaminación sonora.</td>
      <td>Adquisición o integración de plugins IoT de terceros para centralizar mediciones ambientales dentro de Autodesk Construction Cloud.</td>
    </tr>
    <tr>
      <td style="font-weight: bold;">Amenazas</td>
      <td>Reticencia cultural al cambio tecnológico en obras de provincias y demoras administrativas en la adopción por parte de operadoras tradicionales.</td>
      <td>Entrada de proveedores de hardware de bajo costo con capacidades de software genéricas.</td>
      <td>Competidores locales que ofrecen calibración y alquiler de instrumental tradicional a tarifas reducidas por jornada.</td>
      <td>Desarrollo de módulos nativos de gestión ambiental y sostenibilidad dentro de la suite de Autodesk a corto plazo.</td>
    </tr>
  </tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores
<a id="2-1-2-estrategias-y-tacticas-frente-a-competidores"></a>

Para posicionar a EcoRoad frente a la competencia internacional (como SiteHive y Sonitus Systems) y a las soluciones generalistas de gestión de proyectos (como Autodesk Construction Cloud), Caiman implementa las siguientes estrategias y tácticas competitivas:

* **Estrategia de Costos y Accesibilidad (Modelo HaaS):** A diferencia de competidores que exigen la compra directa y costosa de hardware de medición (Inversión de Capital o CapEx elevado), Caiman ofrece un esquema flexible de alquiler de sensores IoT en comodato adaptado a las necesidades específicas de cada obra vial. Esto elimina la barrera financiera de entrada para empresas constructoras medianas y de conservación vial.
* **Enfoque Vertical y Operativo (Más allá del Visor Pasivo):** Mientras que los proveedores tradicionales de hardware ambiental (Sonitus Systems) actúan meramente como visores pasivos de telemetría y las herramientas BIM (Autodesk) se enfocan en diseño y control documental general, EcoRoad integra el monitoreo IoT directamente con un flujo completo de respuesta operativa: *detección de riesgo → alerta automática → creación de ticket de incidencia → asignación de acción correctiva → registro de evidencia y cierre*.
* **Gestión Multi-Proyecto para Concesionarias y Constructoras:** Se despliega una arquitectura pensada para que las empresas ejecutoras y de mantenimiento vial gestionen múltiples frentes de obra simultáneamente desde una única cuenta centralizada y un mapa geolocalizado unificado, optimizando el control que ejercen los residentes de obra y jefes de operaciones.
* **Estrategia Comercial B2B Dirigida:** La prospección se enfoca directamente en gerentes de operaciones, gerentes de proyectos y residentes de obra de constructoras y empresas de conservación vial, apoyándose en alianzas estratégicas con gremios sectoriales (como CAPECO) y demostrando una reducción directa en el riesgo de paralizaciones y sanciones regulatorias ante el MTC y el OEFA.

## 2.2. Entrevistas
<a id="2-2-entrevistas"></a>

### 2.2.1. Diseño de Entrevistas
<a id="2-2-1-diseno-de-entrevistas"></a>

Las entrevistas semiestructuradas tienen como objetivo validar las hipótesis del problema, comprender los flujos de trabajo actuales y evaluar la disposición de adopción tecnológica frente a la propuesta de EcoRoad. Las preguntas se estructuran en una fase inicial de presentación y bloques diferenciados para cada uno de los dos segmentos objetivo.

#### Preguntas de Presentación (Transversales)
* ¿Cuál es tu nombre y edad?
* ¿Cuál es tu cargo actual y hace cuánto tiempo te desempeñas en él?
* ¿Cuáles son tus principales responsabilidades del día a día en relación con la gestión o supervisión ambiental del proyecto vial?

---

#### Segmento 1: Empresas Constructoras Viales

**Preguntas Principales:**
* ¿Cómo es tu proceso actual para registrar los indicadores ambientales (aire, ruido, agua, vibraciones) en obra? ¿Qué herramientas usas hoy para ese registro (Excel, papel, planillas internas)?
* Cuéntame sobre la última vez que detectaste un posible incumplimiento normativo en la ejecución de la obra: ¿cómo te enteraste y qué pasos siguieron después?
* ¿Cuánto tiempo suele pasar entre que ocurre una superación de un límite normativo en campo y el momento en que el equipo directivo o de operaciones se entera de ella?
* Cuéntame cómo preparas la documentación ambiental cuando se aproxima una fiscalización de una entidad reguladora (como OEFA o MTC). ¿Qué parte de ese proceso te consume más tiempo o te genera mayor estrés?
* ¿Ha pasado alguna vez que un incumplimiento o riesgo ambiental en la construcción se detectara tarde? ¿Qué consecuencias operativas o económicas tuvo?
* ¿Cómo se comunica el equipo de campo con la oficina técnica cuando se necesita registrar una medición urgente o reportar una incidencia imprevista en el frente de obra?
* ¿Desde qué dispositivo sueles trabajar cuando estás recorriendo los frentes viales (celular, tablet, laptop) y qué tan confiable es la conectividad en esas zonas de trabajo?

**Preguntas Complementarias:**
* ¿Quién más en tu organización necesita ver esta información ambiental y con qué frecuencia se la compartes?
* ¿Has usado o probado alguna herramienta digital para el control de obras o cumplimiento normativo antes? ¿Qué te gustó o no te gustó de ella?

---

#### Segmento 2: Empresas de Mantenimiento y Rehabilitación Vial

**Preguntas Principales:**
* ¿Cómo registran actualmente los indicadores ambientales durante los trabajos de mantenimiento o rehabilitación de una vía? ¿Utilizan Excel, formatos físicos, fotografías u otra herramienta?
* Cuéntame sobre la última vez que durante un trabajo de mantenimiento o rehabilitación detectaron un problema ambiental, como exceso de ruido, polvo, residuos o vibraciones. ¿Cómo se dieron cuenta y qué hicieron después?
* ¿Qué tan rápido se enteran los responsables del proyecto cuando una medición ambiental supera un límite permitido durante los trabajos?
* ¿Cómo hacen actualmente el seguimiento de las acciones que deben realizar cuando se detecta un problema ambiental? ¿Cómo saben si la incidencia ya fue atendida o continúa pendiente?
* Cuando trabajan en diferentes tramos o zonas de una carretera, ¿cómo organizan y relacionan las mediciones ambientales con el lugar exacto donde fueron tomadas?
* Cuéntame cómo preparan los registros y evidencias ambientales que deben presentar al finalizar una actividad de mantenimiento o rehabilitación. ¿Qué parte del proceso les resulta más complicada?
* ¿Ha ocurrido alguna vez que una incidencia ambiental no se haya comunicado a tiempo o se haya perdido información sobre ella? ¿Qué consecuencias tuvo para el proyecto?
* Cuando el personal está trabajando directamente en la carretera, ¿cómo comunica una medición, problema o incidencia al responsable que se encuentra en la oficina?

**Preguntas Complementarias:**

* ¿Cómo almacenan actualmente las fotografías, mediciones y documentos que sirven como evidencia de las actividades realizadas?
* ¿Desde qué dispositivo suelen registrar información durante los trabajos de campo (celular, tablet, laptop) y qué dificultades tienen con la conectividad en las zonas donde trabajan?

2.2.2. Registro de entrevistas.
En esta sección, se registra cada entrevista realizada. En total, se realizaron XXX entrevistas por cada segmento objetivo. Se detalla el nombre del miembro entrevistador y el del entrevistado. Además, se redacta un resumen general del contenido de la entrevista realizada.

**Segmento 1: Empresas Constructoras Viales**


Entrevista 1

| Entrevista                                                                                                                               | Registro |
|------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![Entrevista 1](assets/img/Chapter2/entrevista1_seg1.png)                                                                                | **Entrevistado:** Sergio Cordova <br> **Edad:** 25 años <br> **Puesto:** Ingeniero Residente de Obra. |
| [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241d483_upc_edu_pe/IQCM3N-BHmX5Qqih3HWmqVQ1AebtpPmwbrZtwFOMPFHg0H8?e=952kX3&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) | **Entrevistador:** [Eduardo Taza] |
| **Timing**                                                                                                                               | **Inicio:** 00:01 |
| **Timing**                                                                                                                               | **Fin:** 10:11 |
| **Resumen**                                                                                                                              | **Perfil y Frustración:** <br> Ingeniero Residente de Obra. Ingeniero Civil con 5 años de experiencia liderando ejecuciones viales en el sector de empresas constructoras. Su principal frustración es la falta de visibilidad unificada entre el avance físico de la obra y las restricciones ambientales. La dispersión de información en carpetas físicas, tablas de Excel inconexas y mensajes sueltos de WhatsApp dificulta anticipar no conformidades, expone al proyecto a paralizaciones o multas por incumplimiento y ralentiza la toma de decisiones críticas en el frente de trabajo. <br> <br> **Comportamiento y Necesidades:** <br> Necesita una plataforma ejecutiva y técnica que le permita monitorear de forma centralizada el estado del tramo o corredor vial bajo su responsabilidad. Requiere vinculación directa entre el kilometraje/progresiva (KP) y los eventos en campo, recepción inmediata de alertas críticas sobre desviaciones normativas (aire, ruido, agua) y la capacidad de asignar acciones correctivas al equipo con trazabilidad clara para acelerar el cierre de incidencias antes de las auditorías. <br><br> **Tecnología, Marcas y Canales:** <br> Utiliza laptop en la oficina de campo, además de smartphone y tablet durante sus recorridos de inspección. Mantiene flujos de trabajo tradicionales basados en hojas de cálculo, formatos impresos y archivos en la nube. Se comunica con supervisores ambientales, jefes de frente y contratistas mediante WhatsApp y llamadas directas, requiriendo herramientas ágiles con capacidad de consulta y registro rápido para operar en tramos viales con conectividad intermitente. |



<br>
<table>
<thead>
  <tr>
    <th colspan="2">Entrevista #2</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Keler Martín</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Panduro Perez</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>26</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Santiago de Surco</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><img src="assets/img/Chapter2/EvidenciaKeler.jpeg" alt="Evidencia entrevista Keler" width="400"></td>
  </tr>
  <tr>
    <tr>
  <td>Link</td>
  <td><a href="https://1drv.ms/v/c/113B281D1AF386CE/IQCjOQL_AoaeSZHjG8hdwrqxAaD3T-ASMCIQkltoW0Mx8QI?e=tux0nT" target="_blank">Ver video</a></td>
</tr>
  </tr>
  <tr>
    <td>Duración</td>
    <td>0:00-6:23</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Keler es un residente de obra y jefe de gestión ambiental en una empresa constructora vial, encargado de supervisar el cumplimiento del Plan de Manejo Ambiental en múltiples frentes de trabajo simultáneos. Para el registro de indicadores (como polvo y ruido), las coordinaciones en campo y el envío de evidencias, utiliza una combinación de herramientas fragmentadas que incluyen hojas de Excel, archivos de Word, mensajes de WhatsApp, carpetas compartidas y reportes manuales diferidos. Busca garantizar la continuidad de la obra sin paralizaciones ni sanciones y mantener al día la documentación socioambiental. Sin embargo, enfrenta serias dificultades debido a la falta de visibilidad en tiempo real de lo que ocurre en cada tramo; al depender de mediciones manuales o informes periódicos de laboratorio, suele enterarse tarde de la superación de límites permisibles, muchas veces cuando ya existen quejas de las comunidades o penalizaciones de la supervisión. Además, la dispersión de la información le exige invertir un tiempo excesivo buscando fotos y documentos no etiquetados para consolidar a última hora los expedientes requeridos en auditorías o fiscalizaciones de organismos como el MTC o el OEFA. Keler considera que contar con una plataforma centralizada y conectada a sensores IoT telemáticos que envíen alertas preventivas en tiempo real, tendría un impacto sumamente positivo, ya que le permitiría aplicar medidas de mitigación inmediatas, evitar multas y automatizar la trazabilidad de sus operaciones en campo.</td>
  </tr>
</tbody>
</table>


**Segmento 2: Empresas de Mantenimiento y Rehabilitación Vial**


Entrevista 3

| Entrevista                                                                                                                               | Registro |
|------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![Entrevista 3](assets/img/Chapter2/entrevista3_seg2.png)                                                                                | **Entrevistado:** Rebeca Fuentes <br> **Edad:** 24 años <br> **Puesto:** Supervisora Ambiental |
| [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241d483_upc_edu_pe/IQBTUPro4f0wTYPlBLEH5owxAahO3HNbIK7KZCxPFKH4HPg?e=bO9nOh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) | **Entrevistador:** [Eduardo Taza] |
| **Timing**                                                                                                                               | **Inicio:** 00:01 |
| **Timing**                                                                                                                               | **Fin:** 07:52 |
| **Resumen**                                                                                                                              | **Perfil y Frustración:** <br> Supervisora Ambiental. Se enfrenta constantemente a la dispersión de datos ambientales repartidos en carpetas físicas, hojas de cálculo, galerías del celular y chats de WhatsApp. Esta falta de centralización entorpece la consolidación de registros, ralentiza el control de hallazgos en campo y retrasa la entrega de los informes de cumplimiento normativo. <br> <br> **Comportamiento y Necesidades:** <br> Requiere una solución digital que le permita documentar en tiempo real mediciones ambientales, fotografías y no conformidades asociadas a un tramo o punto kilométrico específico. Asimismo, necesita un sistema de alertas para priorizar las incidencias críticas y verificar la resolución de los problemas identificados en campo. <br><br> **Tecnología, Marcas y Canales:** <br> Trabaja habitualmente con smartphone, tablet y laptop. Aunque suele apoyarse en formatos en papel y plantillas de Excel, las evidencias fotográficas suelen quedar guardadas en la nube o en dispositivos móviles. Su canal de comunicación directo con la residencia de obra y el equipo de inspección es WhatsApp o llamadas telefónicas, sobre todo en zonas con cobertura limitada. |


Entrevista 4

| Entrevista                                                                                                                               | Registro |
|------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![Entrevista 5](assets/img/Chapter2/entrevista5_seg2.png)                                                                                | **Entrevistado:** Fabricio Aparicio <br> **Edad:** 25 años <br> **Puesto:** Supervisor de Campo de Mantenimiento Vial |
| [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241e417_upc_edu_pe/IQDWjE9tAPBQQYryG12pUpvYAfveHKqBOb3BwlBYgfOzjZU?e=45vPPT) | **Entrevistador:** [Andy Salcedo] |
| **Timing**                                                                                                                               | **Inicio:** 00:01 |
| **Timing**                                                                                                                               | **Fin:** 04:14 |
| **Resumen**                                                                                                                              | **Perfil y Frustración:** <br> Supervisor de Campo de Mantenimiento Vial. Su principal frustración es tener la información ambiental dispersa entre formatos físicos, Excel, fotografías y WhatsApp. Esto dificulta organizar los registros, hacer seguimiento rápido a las incidencias y preparar los informes finales. <br> <br> **Comportamiento y Necesidades:** <br> Necesita una herramienta que permita registrar mediciones, fotografías e incidencias directamente desde el lugar de trabajo, asociándolas al tramo o kilómetro correspondiente. También requiere recibir y hacer seguimiento de las alertas para saber qué problemas están pendientes o ya fueron solucionados. <br><br> **Tecnología, Marcas y Canales:** <br> Utiliza principalmente celular, tablet y laptop. Registra información mediante formatos físicos y Excel, mientras que las fotografías se almacenan en celulares o carpetas en la computadora o nube. La comunicación con la oficina se realiza principalmente mediante WhatsApp y llamadas, especialmente cuando existe poca conectividad en carretera. |


Entrevista 5

| Entrevista                                                                                                                               | Registro                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![Entrevista 3](assets/img/Chapter2/entrevista2_seg2.png)                                                                                | **Entrevistado: Luana Cotrina Ramirez**  <br> **Edad:27 años**  años <br> **Puesto: Gerente de Operaciones** <br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212897_upc_edu_pe/IQBVrZ2J8E6gT7j9l0VWxV_kAf5YpM_n9VpIV0FKFBnIHb8?e=v5mrAm) | **Entrevistador:** Miguel Ángel Junior Román López                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Timing**                                                                                                                               | **Inicio:** 00:00                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 
| **Timing**                                                                                                                               | **Fin:** 08:16                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Resumen**                                                                                                                              | **Perfil y Frustración:**Ejecutiva responsable de garantizar el avance fluido y sin penalidades de múltiples proyectos simultáneos a nivel nacional. Su frustración central es la "ceguera operativa" y la falta de estandarización: depende de reportes semanales en Excel enviados por correo, lo que hace subjetivo y lento (toma de 3 a 4 días) comparar el desempeño entre tramos. Le frustran profundamente las multas o amonestaciones sorpresivas por incidentes ocultos en campo, ya que estas dañan el récord de la empresa en licitaciones públicas.<br><br><br> **Comportamiento y Necesidades:** Gestiona las incidencias mediante un "criterio de incendio", reaccionando solo ante los riesgos inminentes de paralización. Necesita imperiosamente una visión consolidada, centralizada y en tiempo real de toda la cartera de proyectos. Requiere reducir drásticamente las horas hombre invertidas en generar reportes y asegurar que los incidentes se detecten antes de escalar al cliente comitente.<br><br><br>**Tecnología, Marcas y Canales:** Su ecosistema actual se basa en correos electrónicos, macro-archivos de Excel y reportes manuales en PDF. Está completamente dispuesta a adoptar tecnologías IoT bajo un modelo HaaS (alquiler en comodato) para evitar altas inversiones de capital (CapEx). No obstante, su principal barrera tecnológica es la ciberseguridad corporativa; exige garantías absolutas de redundancia en servidores y la posibilidad de mantener respaldos locales (offline) para mitigar el riesgo de pérdida de datos ante auditorías estatales.<br>|


2.2.3. Análisis de entrevistas.

El siguiente análisis sintetiza los datos de las **5 entrevistas registradas** en las fuentes del proyecto, agrupándolas por segmento objetivo para definir con sustento estadístico las características objetivas y subjetivas requeridas en la elaboración de los arquetipos.

---

#### **1\. Segmento 1: Empresas Constructoras Viales**

*(Muestra analizada: 2 entrevistas – Fabián García y Gianfranco Sanguineti)*

##### **A. Características Objetivas**

* **Edad y perfil profesional:**
    * **Edad promedio:** **26.5 años** (rango de 26 a 27 años).
    * **Cargos representados:** El **50% (1/2)** corresponde al rol de **Especialista Ambiental** y el **50% (1/2)** al de **Residente de Obra**.
* **Ecosistema tecnológico y herramientas:**
    * **100% (2/2)** utiliza el **teléfono celular** como dispositivo principal de trabajo en el frente de obra.
    * **100% (2/2)** realiza el control de información mediante **formatos manuales, libretas de campo y plantillas en Microsoft Excel**.
    * **100% (2/2)** emplea **WhatsApp** como canal informal predominante para enviar fotos, audios y coordinar urgencias.
    * **50% (1/2)** utiliza **laptop** en oficina y ha sustituido el uso de tablets por el smartphone.
* **Entorno operativo y conectividad:**
    * **100% (2/2)** opera en tramos de carretera con **conectividad inestable o nula**, destacando que en zonas de obra hasta un **70% del tramo carece de señal mobile/4G**.

##### **B. Características Subjetivas (Puntos de Dolor, Necesidades y Actitudes)**

* **Frustraciones y dolores principales:**
    * **100% (2/2)** manifiesta alta frustración por la **carga burocrática y la pérdida de evidencias** dispersas en chats de WhatsApp o actas físicas, lo que genera demoras (hasta 4 días) recopilando datos para responder ante auditorías.
    * **100% (2/2)** experimenta **estrés y ansiedad** debido a la brecha de tiempo entre la ocurrencia de una incidencia en campo y su reporte formal, exponiéndose a **paralizaciones de obra y sanciones** de entidades fiscalizadoras (OEFA/MTC).
* **Necesidades clave para el arquetipo:**
    * **100% (2/2)** requiere **eliminar el registro en papel** e implementar una solución digital móvil ágil directamente en terreno.
    * **50% (1/2)** requiere **funcionamiento 100% offline** (sin señal) que clasifique imágenes por fecha y progresión kilométrica.
    * **50% (1/2)** necesita un **sistema de alertas automáticas** hacia la oficina técnica ante riesgos ambientales.
* **Actitudes y temores:**
    * **50% (1/2)** muestra una actitud altamente operativa e impulsiva enfocado en auditorías en terreno.
    * **50% (1/2)** expresa **desconfianza hacia plataformas 100% en la nube** por experiencias previas con caídas de servidores que bloquearon su acceso a documentos[4].

---

#### **2\. Segmento 2: Empresas de Mantenimiento y Rehabilitación Vial**

*(Muestra analizada: 3 entrevistas – Luana Cotrina Ramirez, Renato Vega y Fabricio Aparicio)*

##### **A. Características Objetivas**

* **Edad y perfil profesional:**
    * **Edad promedio:** **25.3 años** (rango de 24 a 27 años).
    * **Cargos representados:**
        * **33.3% (1/3):** Gerente de Operaciones.
        * **33.3% (1/3):** Especialista Ambiental.
        * **33.3% (1/3):** Supervisor de Campo de Mantenimiento Vial.
* **Ecosistema tecnológico y herramientas:**
    * **100% (3/3)** utiliza el **teléfono celular** para capturar fotografías, registrar mediciones o realizar llamadas.
    * **100% (3/3)** depende de **Microsoft Excel, formatos físicos y/o reportes en PDF** para consolidar información.
    * **66.7% (2/3)** utiliza **laptop y/o tablet** como herramientas de soporte operativo y administrativo.
    * **66.7% (2/3)** utiliza **WhatsApp y llamadas telefónicas** para la comunicación entre el personal de campo y la oficina.
* **Entorno operativo:**
    * **100% (3/3)** gestiona **múltiples tramos o frentes de trabajo geográficamente dispersos** en carreteras abiertas al tráfico con problemas de señal.

##### **B. Características Subjetivas (Puntos de Dolor, Necesidades y Actitudes)**

* **Frustraciones y dolores principales:**
    * **100% (3/3)** se siente frustrado por tener la **información ambiental fragmentada** (libretas, Excel, WhatsApp, carpetas en PC), lo que complica organizar registros e informes finales.
    * **66.7% (2/3)** sufre por la **"ceguera operativa" y la falta de visibilidad en tiempo real**, causada por reportes semanales lentos o traspapeleo de fichas de campo.
    * **33.3% (1/3)** se frustra por la lentitud (3 a 4 días) en comparar el desempeño entre tramos y el impacto que las multas sorpresivas tienen sobre el récord de licitaciones de la empresa.
* **Necesidades clave para el arquetipo:**
    * **100% (3/3)** necesita un sistema que registre y **asocie las evidencias e incidencias directamente al tramo o kilómetro correspondiente**.
    * **66.7% (2/3)** requiere una **visión centralizada y en tiempo real** para dar seguimiento al estado de las alertas (pendientes vs. solucionadas).
    * **33.3% (1/3)** busca un modelo de contratación **HaaS (alquiler de sensores en comodato)** para evitar inversiones de capital inicial (CapEx).
* **Actitudes, temores y barreras:**
    * **33.3% (1/3)** opera bajo un enfoque reactivo ("criterio de incendio"), atendiendo únicamente los problemas inminentes.
    * **33.3% (1/3)** exige **garantías de ciberseguridad corporativa** y la posibilidad de mantener respaldos locales (offline) para auditorías estatales.


2.3. Needfinding.
### 2.3.1. User Personas
<a id="2-3-1-user-personas"></a>

**Segmento 1: Empresas constructoras viales**

Para las empresas constructoras se elaboró el User Persona Diego Davalos. Se consideraron factores como su edad, su rol operativo y de mitigación ambiental en proyectos viales, su experiencia en la gestión de frentes de obra y su necesidad de optimizar procesos de registro preventivo de indicadores ambientales (aire, ruido, agua). Sus principales frustraciones giran en torno a la falta de un sistema automatizado para el monitoreo en tiempo real, la dependencia de registros manuales dispersos y la dificultad para recopilar evidencia ante auditorías imprevistas. Asimismo, se tomó en cuenta su familiaridad con herramientas móviles en campo y la necesidad de contar con una solución ágil y resistente a problemas de conectividad que le permita mitigar riesgos y evitar multas o paralizaciones de obra.
<div align="center"><img src="assets/img/Chapter2/DiegoDávalos.png" alt="Gráfico Estadístico Administradores" width="80%"></div>
<br>

**Segmento 2: Empresas de mantenimiento y rehabilitación vial**

Para las empresas de mantenimiento y rehabilitación vial se elaboró el User Persona Piero Deza. Se consideraron factores como su rol de residente y supervisor de campo en la conservación de infraestructura de transporte existente, su experiencia en la gestión multisitio de frentes de trabajo dispersos y su necesidad de contar con un control operativo centralizado. Sus principales frustraciones se relacionan con la falta de visibilidad en tiempo real por la dispersión geográfica, la pérdida de tiempo en la búsqueda manual de registros fragmentados y el estrés ante imprevistos en vías abiertas al tráfico. Asimismo, se tomó en cuenta su uso de herramientas móviles y de escritorio, y la necesidad de una plataforma SaaS que permita gestionar alertas preventivas, automatizar el registro de evidencias y asegurar la eficiencia en la ejecución de los proyectos.
<div align="center"><img src="assets/img/Chapter2/PieroDezaUser.png" alt="Gráfico Estadístico Administradores" width="80%"></div>
<br>

2.3.2. User Task Matrix.

A continuación, se detalla la matriz con las actividades principales que tanto el representante del Segmento 1 como Piero Deza (Segmento 2) ejecutan en su día a día laboral, enfocadas estrictamente en sus responsabilidades de gestión y supervisión, sin depender de ninguna herramienta digital o software en particular.
<table border="1" cellpadding="8" cellspacing="0" style="border-collapse:collapse; width:100%; font-family:Arial, sans-serif; text-align:center;">
  <thead>
    <tr style="background-color:#eef3f7;">
      <th rowspan="2">Tarea (Task)</th>
      <th colspan="2">Diego Dávalos (Segmento 1)</th>
      <th colspan="2">Piero Deza (Segmento 2)</th>
    </tr>
    <tr style="background-color:#eef3f7;">
      <th>Frecuencia</th>
      <th>Importancia</th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left;">Monitorear los indicadores ambientales (aire, ruido, agua) en obra</td>
      <td>Daily</td><td>High</td>
      <td>Daily</td><td>High</td>
    </tr>
    <tr>
      <td style="text-align:left;">Registrar evidencia fotográfica y documentar acciones correctivas</td>
      <td>Frequent</td><td>High</td>
      <td>Frequent</td><td>High</td>
    </tr>
    <tr>
      <td style="text-align:left;">Preparar carpetas o reportes para auditorías y fiscalizaciones gubernamentales</td>
      <td>Periodic</td><td>High</td>
      <td>Periodic</td><td>High</td>
    </tr>
    <tr>
      <td style="text-align:left;">Consolidar el estado ambiental de múltiples frentes de trabajo de manera simultánea</td>
      <td>Rare</td><td>Medium</td>
      <td>Daily</td><td>High</td>
    </tr>
    <tr>
      <td style="text-align:left;">Integrar y unificar criterios ambientales ante la incorporación de un nuevo tramo o frente vial</td>
      <td>Rare</td><td>Medium</td>
      <td>Periodic</td><td>High</td>
    </tr>
  </tbody>
</table>

**Análisis del Task Matrix:**

Si analizamos cómo se comportan ambos perfiles a partir de la matriz, saltan a la vista ciertos contrastes interesantes entre sus rutinas:

- Las tareas más pesadas y críticas: Para los dos perfiles, armar y poner a punto los expedientes de auditoría o fiscalización gubernamental es una prioridad indiscutible. La diferencia está en el día a día: mientras Diego se la pasa revisando los medidores ambientales en la misma pista para que la obra nueva no pare, Piero prefiere levantar la vista y gestionar el panorama completo de los múltiples frentes de trabajo dispersos a lo largo de las vías en conservación.

- En qué se parecen: Los dos sufren con el mismo dolor de cabeza. Para ambos, rendir cuentas ante las entidades regulatorias es un proceso tenso donde la exigencia es máxima, y coinciden en que hoy en día lidian con demasiado papeleo suelto o información que no está conectada entre sí cuando intentan armar los reportes de obra.

- En qué se diferencian radicalmente: Todo se reduce a la perspectiva. Diego vive el día a día apagando incendios operativos en la ejecución de obra nueva: toma fotos a cada rato, documenta correcciones rápidas y actúa de inmediato ante cualquier alerta en terreno. Piero, en cambio, maneja una visión de gestión multisitio en vías abiertas al tráfico; le toca coordinar constantemente con sus cuadrillas de mantenimiento frente a las quejas de transeúntes, buscando unificar la información dispersa de sus diferentes tramos carreteros.
<div style="page-break-after: always;"></div>

2.3.3. User Journey Mapping.

**Segmento 1: Empresas constructoras viales**

El recorrido actual de Diego se centra en la ejecución física de la obra vial y comprende las siguientes etapas principales: 1. Planificación inicial y despliegue en campo, 2. Monitoreo diario de indicadores ambientales (aire, ruido, agua), 3. Detección y respuesta ante una alerta o desvío, y 4. Preparación de evidencias para auditorías o inspecciones imprevistas.
Durante este ciclo, el punto más crítico ocurre en las etapas 2 y 4. Al depender de registros manuales y planillas de Excel dispersas, Diego experimenta una alta frustración debido a la intermitencia de conectividad en zonas alejadas y al riesgo latente de enterarse tarde de una superación de límites normativos. La necesidad de recopilar papeles y fotos sueltas para armar carpetas de cumplimiento genera una carga de estrés considerable antes de cada fiscalización del Estado.
<div align="center"><img src="assets/img/Chapter2/JourneyMapDiego.png" alt="Gráfico Estadístico Administradores" width="80%"></div>
<br>

**Segmento 2: Empresas de mantenimiento y rehabilitación vial**

El recorrido de Piero abarca una perspectiva operativa de campo y control multisitio, dividida en: 1. Incorporación y configuración inicial de los tramos viales en mantenimiento, 2. Monitoreo diario de las condiciones ambientales frente a la operación de maquinaria pesada, 3. Detección temprana y atención de alertas o quejas por emisiones de polvo y ruido, y 4. Generación y consolidación de reportes ejecutivos de cumplimiento para la gerencia.

El mayor cuello de botella en el viaje de Piero se concentra en las etapas 2 y 3. Debido a la dispersión geográfica de los frentes de trabajo en vías abiertas al tráfico y a la dependencia de registros manuales fragmentados, recopilar evidencias y coordinar acciones correctivas inmediatas le demanda una sobrecarga operativa de llamadas y visitas de campo constantes. Esto lo expone a retrasos en la mitigación de riesgos y a posibles amonestaciones operativas por la falta de visibilidad centralizada en tiempo real.
<div align="center"><img src="assets/img/Chapter2/JourneyMapPiero.png" alt="Gráfico Estadístico Administradores" width="80%"></div>
<br>
2.3.4. Empathy Mapping.

Para desarrollar los Empathy Maps, se tomaron como base los hallazgos e información recopilada en el estudio previo de los User Personas. Siguiendo la metodología, se ubicó al centro de cada esquema al arquetipo correspondiente para analizar de forma integral su entorno, reacciones emocionales, conductas habituales y requerimientos clave.

**Segmento 1: Empresas constructoras viales**

En este mapa se analizó a Diego Dávalos, un ingeniero civil de campo y residente de obra con la responsabilidad de garantizar la ejecución táctica y el cumplimiento ambiental operativo en los tramos viales. Se identificó que piensa constantemente en la necesidad de simplificar su trabajo en la pista y teme cometer errores de registro que deriven en multas severas. Escucha las exigencias de la consultora supervisora y los reclamos de su cuadrilla, y observa un entorno rudo y cambiante con herramientas manuales obsoletas y carpetas desorganizadas. Diego expresa la necesidad de contar con una herramienta móvil rápida que funcione sin conexión, y actúa recorriendo los frentes, tomando notas físicas y compilando datos a última hora. Su dolor principal es la conectividad intermitente, la ausencia de un sistema centralizado y el estrés por la recopilación manual, mientras que su ganancia esperada es lograr una aplicación móvil con modo offline, alertas automáticas y mayor control operativo para las auditorías.
<div align="center"><img src="assets/img/Chapter2/EmpathyDiego.jpg" alt="Gráfico Estadístico Administradores" width="80%"></div>
<br>

**Segmento 2: Empresas de mantenimiento y rehabilitación vial**

En este mapa se analizó a Piero Deza, un residente de mantenimiento vial y supervisor de campo con la responsabilidad de gestionar múltiples frentes de trabajo y labores de conservación en vías terrestres existentes. Él piensa que una plataforma centralizada simplificaría drásticamente su trabajo diario, aunque a veces teme la resistencia al cambio del personal operativo. Escucha las quejas frecuentes de transeúntes por el polvo y ruido de la maquinaria, los reclamos de la gerencia exigiendo mayor eficiencia y las advertencias sobre normativas ambientales, y observa un entorno dinámico con frentes de trabajo dispersos, maquinaria pesada operando en vías abiertas al tráfico y un escritorio saturado de carpetas físicas y reportes fragmentados. Piero suele expresar la necesidad de contar con una visión centralizada de todos los frentes para gestionar las alertas a tiempo y evitar que los problemas escalen, y actúa recorriendo constantemente las carreteras, anotando datos en libretas bajo presión y coordinando urgencias por mensajería móvil. Su dolor principal es la falta de visibilidad centralizada debido a la dispersión geográfica y la pérdida de tiempo buscando registros manuales dispersos, mientras que su ganancia esperada es disponer de una plataforma SaaS que unifique el monitoreo de diversos frentes, automatice los reportes de campo y le otorgue mayor control operativo y tranquilidad.
<div align="center"><img src="assets/img/Chapter2/EmpathyPiero.png" alt="Gráfico Estadístico Administradores" width="80%"></div>
<br>

2.4. Big Picture Event Storming.

Step 1 – Free Exploration

En esta primera etapa, el equipo realizó una sesión de lluvia de ideas para capturar todos los eventos relevantes dentro del dominio, sin preocuparse por el orden o la jerarquía. El objetivo principal fue representar los acontecimientos reales del negocio, de manera independiente a cualquier función técnica o relacionada con un sistema.
<div align="center"><img src="assets/img/Chapter2/Step1.jpg" alt="Gráfico Estadístico Administradores" width="80%"></div>
<br>

Step 2 – Structured Organization

Después de listar los eventos, el equipo los organizó en flujos de negocio lógicos que reflejan las principales etapas en la operación de monitoreo ambiental y gestión de incidencias en proyectos de construcción y mantenimiento vial. Esta estructura ayudó a identificar los procesos clave y las áreas de mejora que posteriormente podrían abordarse mediante soluciones digitales o de gestión.
<div align="center"><img src="assets/img/Chapter2/Step2.jpg" alt="Gráfico Estadístico Administradores" width="80%"></div>
<br>



2.5. Ubiquitous Language
<a id="2-5-ubiquitous-language"></a>

Here is the Ubiquitous Language glossary for EcoRoad, presented in English with both terms and definitions fully in English, satisfying the project's domain requirements:

| Term | Definition |
|:---| :--- |
| **Company Account** | Corporate profile representing the construction company or environmental consulting/supervising company registered in the platform to manage their road operations. |
| **Subscription** | HaaS/SaaS commercial contract under a dual-revenue model that grants access to operational modules and monitoring services based on segmented plans (Base, Professional, or Enterprise). |
| **Road Project** | Terrestrial transport infrastructure work registered in the system over which environmental control and monitoring are performed. |
| **Road Section** | Specific segment geographically delimited within the planning of a highway project. |
| **Work Front** | Specific operational area within a road section where construction or maintenance tasks are actively executed. |
| **Sensor Node** | Physical hardware device deployed in the field for the automated capture of telemetry and environmental indicators. |
| **Monitoring Point** | Precise geographical location within the road infrastructure where a measurement asset is geolocated and fixed. |
| **Environmental Parameter** | Physical variable subject to study and control (such as particulate matter PM10/PM2.5, noise level, water quality, or vibration). |
| **Threshold Profile** | Set of permitted regulatory limits established to evaluate the behavior of environmental parameters on the construction site. |
| **Environmental Measurement** | Quantitative telemetry data or reading captured by sensors or entered through manual records in the field. |
| **Threshold Deviation** | Alert generated preventively when an environmental measurement exceeds or breaches the limits established in the regulatory profile. |
| **Incident** | Anomaly or critical event detected in the project representing a potential risk or an effective breach of environmental regulations. |
| **Corrective Action** | Mitigation or solution measure implemented by operational personnel to counteract an environmental incident in the field. |
| **Field Crew** | Team of operational personnel responsible for addressing incidents, executing corrective actions, and gathering verifiable evidence. |
| **Compliance Report** | Official and consolidated report based on immutable data and historical evidence, used to demonstrate regulatory compliance during audits and before regulatory bodies. |






# Requirements Specification
<a id="3-requirements-specification"></a>
## 3.1. User Stories

| ID | Título | Descripción | Criterios de Aceptación | Relacionado con |
| :--- | :--- | :--- | :--- | :--- |
| US01 | Autenticación de Usuarios | *Como* **Visitante**, *quiero* iniciar sesión en la plataforma *para* acceder a mi cuenta y perfil según mi rol. | Escenario 1: Inicio de sesión exitoso<br>Dado que el visitante ingresa credenciales válidas, cuando confirma el inicio de sesión, entonces el sistema autentica al usuario y le otorga acceso a las funcionalidades correspondientes a su rol.<br><br>Escenario 2: Credenciales inválidas<br>Dado que el visitante ingresa credenciales incorrectas, cuando intenta iniciar sesión, entonces el sistema deniega el acceso e informa que las credenciales son inválidas. | EP08: Usuario |
| US02 | Visualización de Soluciones Ambientales | *Como* **Visitante**, *quiero* conocer qué tipos de problemas ambientales mide la plataforma *para* determinar si cumple con la normativa legal aplicable a mi obra vial. | Escenario 1: Consulta de datos medidos por sector ambiental<br>Dado que el visitante consulta las soluciones ambientales disponibles, cuando revisa la información de un sector ambiental, entonces el sistema presenta los parámetros ambientales monitoreados y la normativa asociada.<br><br>Escenario 2: Consulta de certificación de los equipos de medición<br>Dado que el visitante requiere validar la confiabilidad de las mediciones, cuando solicita información sobre los instrumentos utilizados, entonces el sistema informa las certificaciones de calidad y calibración de dichos instrumentos. | EP13: Marketing |
| US03 | Solicitud de Demostración Guiada | *Como* **Visitante**, *quiero* solicitar una sesión personalizada con ingenieros *para* evaluar cómo reducir riesgos en mis proyectos viales. | Escenario 1: Registro de solicitud exitoso<br>Dado que el visitante ingresa los datos de contacto y de su empresa, cuando envía la solicitud, entonces el sistema registra la solicitud y confirma que la solicitud de demostración ha sido registrada.<br><br>Escenario 2: Validación de campos obligatorios<br>Dado que el visitante omite uno o más datos de contacto obligatorios, cuando intenta enviar la solicitud, entonces el sistema rechaza el envío e informa cuáles campos son obligatorios. | EP13: Marketing |
| US04 | Revisión de Características Tecnológicas y Cumplimiento | *Como* **Visitante**, *quiero* conocer los detalles de la arquitectura tecnológica de la plataforma *para* evaluar su viabilidad técnica en proyectos civiles mayores. | Escenario 1: Consulta de un componente tecnológico<br>Dado que el visitante selecciona un componente de la arquitectura, cuando solicita el detalle de dicho componente, entonces el sistema describe su funcionamiento y su propósito dentro del proceso de cumplimiento ambiental.<br><br>Escenario 2: Consulta de la frecuencia de transmisión de datos<br>Dado que el visitante consulta las características tecnológicas, cuando revisa la información de transmisión de datos, entonces el sistema presenta las características de actualización y transmisión de la telemetría. | EP13: Marketing |
| US05 | Visualización de Beneficios de la Plataforma | *Como* **Visitante**, *quiero* conocer las ventajas operativas y legales del sistema *para* evaluar la viabilidad de su implementación en mi proyecto vial. | Escenario 1: Consulta de beneficios de mitigación y automatización<br>Dado que el visitante requiere evaluar la eficiencia operativa del sistema, cuando solicita el detalle de las ventajas estratégicas, entonces el sistema informa los indicadores de reducción de penalizaciones regulatorias y el ahorro estimado en horas administrativas.<br><br>Escenario 2: Consulta de beneficios de supervisión y soporte legal<br>Dado que el visitante requiere validar el control de las operaciones en campo, cuando solicita el detalle de las ventajas de supervisión, entonces el sistema informa cómo se organizan las tareas del personal en obra y el acceso a asesoría de ingenieros especializados. | EP13: Marketing |
| US06 | Comparación de Planes de Suscripción | *Como* **Visitante**, *quiero* conocer los precios y las características de cada plan de suscripción *para* elegir el que mejor se adapte al presupuesto de mi empresa. | Escenario 1: Cálculo de precio según periodicidad de pago<br>Dado que el visitante selecciona la modalidad de pago (mensual o anual), cuando confirma la selección, entonces el sistema calcula el precio correspondiente al plan e indica el descuento aplicable por el pago anual.<br><br>Escenario 2: Solicitud de cotización personalizada<br>Dado que el visitante selecciona el plan Enterprise, cuando solicita una cotización personalizada, entonces el sistema deriva la solicitud al canal de atención de ventas corporativas. | EP09: Suscripción |
| US07 | Visualización de Testimonios y Opiniones | *Como* **Visitante**, *quiero* conocer las opiniones de otros profesionales del sector construcción *para* determinar la confiabilidad de la plataforma en proyectos reales. | Escenario 1: Consulta de identidad del profesional que emite la opinión<br>Dado que el visitante revisa un testimonio, cuando accede a su detalle, entonces el sistema informa el nombre, cargo, empresa y calificación del profesional que emite la opinión.<br><br>Escenario 2: Consulta del logro alcanzado por el cliente<br>Dado que el visitante revisa un testimonio específico, cuando accede a su detalle, entonces el sistema informa el logro o resultado alcanzado por el cliente en su obra. | EP13: Marketing |
| US08 | Acceso a Canales de Soporte y Datos Legales | *Como* **Visitante**, *quiero* acceder a la información de contacto institucional y al marco regulatorio soportado por la plataforma *para* resolver dudas técnicas de manera independiente. | Escenario 1: Consulta de datos institucionales y normativos<br>Dado que el visitante requiere información de contacto o del marco regulatorio soportado, cuando la solicita, entonces el sistema informa los canales de soporte disponibles (teléfono y correo electrónico) y el listado de normas internacionales de calidad ambiental soportadas. | EP13: Marketing |
| US09 | Monitoreo de Mediciones en Tiempo Real | *Como* **Ingeniero Ambiental**, *quiero* consultar las mediciones en tiempo real de los sensores IoT de un proyecto *para* identificar oportunamente el estado ambiental de cada punto de monitoreo. | Escenario 1: Consulta de medición vigente<br>Dado que el ingeniero ambiental selecciona un sensor activo dentro de un proyecto, cuando solicita la medición vigente, entonces el sistema informa el valor actual del indicador y la fecha y hora de la última actualización.<br><br>Escenario 2: Sensor sin comunicación<br>Dado que un sensor no ha enviado mediciones dentro del intervalo esperado, cuando el ingeniero ambiental consulta su estado, entonces el sistema informa que el sensor se encuentra sin comunicación y la fecha de la última medición recibida. | EP02: Indicador |
| US10 | Consulta de Estado y Ubicación de Sensores IoT | *Como* **Ingeniero Ambiental**, *quiero* consultar la ubicación y el estado operativo de los sensores instalados en un proyecto *para* verificar la cobertura del monitoreo ambiental. | Escenario 1: Listado de sensores por proyecto<br>Dado que el ingeniero ambiental selecciona un proyecto, cuando solicita el listado de sensores instalados, entonces el sistema informa la ubicación, el tipo de parámetro medido y el estado operativo de cada sensor. | EP02: Indicador |
| US11 | Visualización General de Proyectos | *Como* **Gerente de Proyecto**, *quiero* consultar el estado general de todos los proyectos a mi cargo *para* priorizar mi atención según el nivel de riesgo ambiental de cada uno. | Escenario 1: Consulta del listado de proyectos<br>Dado que el gerente de proyecto accede a la vista general de proyectos, cuando solicita el listado, entonces el sistema informa, para cada proyecto, su ubicación, tipo, estado ambiental general, cantidad de sensores activos, alertas activas e incidencias pendientes. | EP01: Proyecto |
| US12 | Consulta de Resumen de un Proyecto | *Como* **Director de Obra**, *quiero* consultar el resumen del estado ambiental de un proyecto específico *para* tomar decisiones sobre la continuidad de las actividades en obra. | Escenario 1: Consulta exitosa<br>Dado que el director de obra selecciona uno de sus proyectos, cuando solicita el resumen del proyecto, entonces el sistema informa el estado ambiental general, las alertas activas y las incidencias pendientes asociadas a dicho proyecto. | EP01: Proyecto |
| US13 | Consulta del Dashboard Ambiental de un Proyecto | *Como* **Ingeniero Ambiental**, *quiero* consultar el dashboard ambiental de un proyecto *para* visualizar de forma centralizada el estado de sus tramos y puntos de monitoreo. | Escenario 1: Consulta de indicadores por tramo<br>Dado que el ingeniero ambiental selecciona un proyecto, cuando solicita el detalle por tramo o frente de trabajo, entonces el sistema informa el estado ambiental de cada tramo según los indicadores medidos. | EP06: Dashboard |
| US14 | Consulta de Evolución Histórica de un Indicador | *Como* **Ingeniero Ambiental**, *quiero* consultar la evolución histórica de un indicador ambiental *para* analizar el comportamiento del proyecto a lo largo del tiempo. | Escenario 1: Consulta de histórico<br>Dado que el ingeniero ambiental selecciona un indicador y un rango de fechas, cuando solicita el histórico de mediciones, entonces el sistema informa la serie de valores registrados para dicho indicador durante el periodo solicitado.<br><br>Escenario 2: Rango sin mediciones<br>Dado que el rango de fechas seleccionado no contiene mediciones registradas, cuando el ingeniero ambiental solicita el histórico, entonces el sistema informa que no existen mediciones disponibles para el periodo indicado. | EP02: Indicador |
| US15 | Consulta del Nivel de Riesgo de un Indicador | *Como* **Ingeniero Ambiental**, *quiero* conocer el nivel de riesgo asociado a cada indicador ambiental medido *para* identificar qué situaciones requieren atención prioritaria. | Escenario 1: Clasificación dentro de rango óptimo<br>Dado que una medición se encuentra dentro de los umbrales establecidos para el indicador, cuando el sistema procesa la medición, entonces la clasifica en estado óptimo.<br><br>Escenario 2: Clasificación en estado crítico<br>Dado que una medición supera el umbral crítico establecido para el indicador, cuando el sistema procesa la medición, entonces la clasifica en estado crítico y la asocia al indicador y al punto de monitoreo correspondiente. | EP03: Alerta |
| US16 | Consulta de Alertas Generadas | *Como* **Ingeniero Ambiental**, *quiero* consultar las alertas generadas en un proyecto *para* identificar rápidamente dónde se está presentando un problema ambiental. | Escenario 1: Consulta de detalle de alerta<br>Dado que el ingeniero ambiental selecciona una alerta activa, cuando solicita su detalle, entonces el sistema informa el indicador afectado, el valor registrado, el nivel de riesgo, el proyecto, el tramo, el sensor que la generó y la fecha y hora de detección. | EP03: Alerta |
| US17 | Notificación de Alertas Críticas | *Como* **Gerente de Proyecto**, *quiero* ser notificado cuando se genere una alerta crítica en alguno de mis proyectos *para* actuar de manera oportuna. | Escenario 1: Generación de alerta crítica<br>Dado que una medición es clasificada en estado crítico, cuando el sistema genera la alerta correspondiente, entonces notifica al gerente de proyecto responsable del proyecto asociado. | EP03: Alerta |
| US18 | Registro de Incidencia Ambiental | *Como* **Ingeniero Ambiental**, *quiero* que se registre una incidencia cuando una medición alcance un estado crítico *para* iniciar su atención y seguimiento. | Escenario 1: Generación automática de incidencia<br>Dado que una medición es clasificada en estado crítico, cuando el sistema procesa dicha medición, entonces genera una incidencia con el problema detectado, la ubicación, el proyecto, el indicador afectado y la fecha y hora, en estado "Pendiente".<br><br>Escenario 2: Registro manual de incidencia<br>Dado que el ingeniero ambiental identifica una condición ambiental no detectada automáticamente, cuando registra una incidencia de forma manual, entonces el sistema almacena la incidencia con los datos ingresados y la asigna al estado "Pendiente". | EP04: Incidencia |
| US19 | Asignación de Responsable de Incidencia | *Como* **Director de Obra**, *quiero* asignar un responsable a una incidencia ambiental *para* garantizar que sea atendida oportunamente. | Escenario 1: Asignación exitosa<br>Dado que el director de obra selecciona una incidencia en estado "Pendiente", cuando asigna un responsable de atención, entonces el sistema registra al responsable asignado y cambia el estado de la incidencia a "En proceso". | EP04: Incidencia |
| US20 | Registro de Acción Correctiva | *Como* **Inspector Ambiental**, *quiero* registrar la acción correctiva realizada frente a una incidencia ambiental *para* documentar la respuesta ejecutada en campo. | Escenario 1: Registro exitoso<br>Dado que el inspector ambiental tiene asignada una incidencia en estado "En proceso", cuando registra la acción correctiva realizada, entonces el sistema almacena la acción, la asocia a la incidencia y actualiza su estado a "Atendida". | EP04: Incidencia |
| US21 | Actualización de Estado de Incidencia | *Como* **Ingeniero Ambiental**, *quiero* actualizar el estado de una incidencia ambiental *para* reflejar el avance real de su atención. | Escenario 1: Cierre de incidencia<br>Dado que una incidencia se encuentra en estado "Atendida" y cuenta con evidencia registrada, cuando el ingeniero ambiental confirma el cierre, entonces el sistema cambia el estado de la incidencia a "Cerrada" y registra la fecha de cierre.<br><br>Escenario 2: Intento de cierre sin evidencia<br>Dado que una incidencia en estado "Atendida" no cuenta con evidencia registrada, cuando el ingeniero ambiental intenta cerrarla, entonces el sistema rechaza el cierre e informa que se requiere registrar evidencia previamente. | EP04: Incidencia |
| US22 | Registro de Evidencia de Campo | *Como* **Inspector Ambiental**, *quiero* registrar evidencia fotográfica y descriptiva de las acciones correctivas realizadas *para* mantener la trazabilidad de la atención de incidencias. | Escenario 1: Registro exitoso<br>Dado que el inspector ambiental completa una acción correctiva en campo, cuando adjunta la evidencia fotográfica, la descripción, la fecha, hora y ubicación geográfica, entonces el sistema asocia la evidencia a la incidencia correspondiente. | EP10: Documento |
| US23 | Consulta del Historial Ambiental de un Proyecto | *Como* **Director de Obra**, *quiero* consultar el historial ambiental de un proyecto *para* analizar su comportamiento a lo largo del tiempo y sustentar decisiones ante terceros. | Escenario 1: Consulta exitosa<br>Dado que el director de obra selecciona un proyecto y un rango de fechas, cuando solicita el historial ambiental, entonces el sistema informa las mediciones, alertas, incidencias, acciones correctivas y evidencias registradas durante dicho periodo. | EP07: Reporte |
| US24 | Generación de Reporte Ambiental | *Como* **Gerente de Proyecto**, *quiero* generar un reporte con la información ambiental de un proyecto *para* presentarlo ante la empresa o las autoridades correspondientes. | Escenario 1: Generación exitosa<br>Dado que el gerente de proyecto selecciona un proyecto y un rango de fechas con información registrada, cuando solicita la generación del reporte, entonces el sistema genera un documento con los indicadores ambientales, alertas, incidencias, acciones correctivas y evidencias del periodo seleccionado.<br><br>Escenario 2: Periodo sin información<br>Dado que el rango de fechas seleccionado no contiene información registrada, cuando el gerente de proyecto solicita el reporte, entonces el sistema informa que no existe información disponible para el periodo indicado. | EP07: Reporte |
| US25 | Registro de Colaboradores y Asignación de Permisos | *Como* **Administrador de la Constructora**, *quiero* registrar a los colaboradores de mi empresa y asignarles permisos específicos *para* adaptar el acceso a la plataforma según el rol de cada uno. | Escenario 1: Registro exitoso de colaborador<br>Dado que el administrador ingresa los datos de un nuevo colaborador y selecciona los permisos correspondientes, cuando confirma el registro, entonces el sistema crea la cuenta del colaborador con los permisos asignados.<br><br>Escenario 2: Modificación de permisos existentes<br>Dado que el administrador selecciona un colaborador ya registrado, cuando modifica el nivel de permisos asignado, entonces el sistema actualiza los permisos del colaborador de forma inmediata. | EP08: Usuario |
| US26 | Restricción de Acceso según Permisos Asignados | *Como* **Administrador de la Constructora**, *quiero* que el sistema restrinja el acceso de cada colaborador según los permisos asignados *para* garantizar la seguridad de la información del proyecto. | Escenario 1: Acceso restringido<br>Dado que un colaborador cuenta únicamente con permiso de "Solo Lectura", cuando intenta registrar una acción correctiva, entonces el sistema deniega la acción e informa que no cuenta con autorización para realizarla. | EP08: Usuario || US27 | Endpoint de Ingesta de Datos IoT | *Como* **Developer**, *quiero* implementar un endpoint seguro *para* recibir las lecturas automáticas de los sensores IoT de campo (PM10, PM2.5, ruido, agua, pH) con marca de tiempo. | *Dado* que un dispositivo o gateway IoT envía una medición, *cuando* el payload cumple con el esquema validado, *entonces* la API almacena el dato asociado al sensor y al proyecto vial. | EP02: Indicador |
| US27 | CTA Segmento Constructoras Viales | Como Visitante del segmento Constructoras Viales, quiero acceder a información específica sobre gestión de monitoreo e incidencias para evaluar si la plataforma se ajusta a mis frentes de construcción. | Escenario 1: Redirección al registro<br>Dado que el visitante está en la sección dirigida a constructoras viales,<br>cuando solicita conocer la plataforma,<br>entonces el sistema lo redirige al registro de la Web Application. | EP08: Usuario |
| US28 | CTA Segmento Mantenimiento Vial | Como Visitante del segmento Mantenimiento Vial, quiero acceder a la propuesta de gestión multi-proyecto para evaluar la vista consolidada de mis tramos en conservación y rehabilitación vial. | Escenario 1: Redirección al dashboard consolidado<br>Dado que el visitante está en la sección de mantenimiento vial,<br>cuando solicita gestionar su cartera vial,<br>entonces el sistema lo redirige al dashboard consolidado tras autenticarse. | EP08: Usuario |
| US29 | Notificaciones Push en Landing | Como Visitante, quiero aceptar notificaciones del navegador para recibir avisos inmediatos de superación de límites ambientales sin estar dentro de la aplicación. | Escenario 1: Suscripción exitosa<br>Dado que el visitante ingresa al sitio web,<br>cuando el sistema solicita autorización de notificaciones y el visitante la concede,<br>entonces el sistema registra la suscripción push para alertas críticas de los sensores IoT. | EP03: Alerta |
| US30 | Creación de Proyecto Vial | Como Gerente de Proyecto, quiero registrar una obra vial definiendo ubicación, tramos y frentes de trabajo para iniciar el monitoreo ambiental centralizado. | Escenario 1: Registro exitoso<br>Dado que el gerente de proyecto ingresa los datos del proyecto y sus tramos,<br>cuando confirma el registro,<br>entonces el sistema incorpora el proyecto al portafolio y a la vista general de monitoreo.<br><br>Escenario 2: Datos incompletos<br>Dado que el gerente de proyecto omite un dato obligatorio del proyecto,<br>cuando intenta confirmar el registro,<br>entonces el sistema rechaza el registro e informa el campo faltante. | EP01: Proyecto |
| US31 | Archivado de Proyectos Viales Finalizados | Como Director de Obra, quiero archivar obras de infraestructura concluidas para mantener despejado el portafolio activo sin perder la trazabilidad histórica. | Escenario 1: Archivado exitoso<br>Dado que una obra alcanza su cierre operativo,<br>cuando el director de obra solicita archivarla,<br>entonces el sistema la retira de las vistas operativas primarias conservando su información histórica. | EP01: Proyecto |
| US32 | Búsqueda Global de Proyectos, Tramos e Incidencias | Como Director de Obra, quiero disponer de un buscador centralizado para localizar rápidamente carreteras, frentes de trabajo o incidencias específicas mediante códigos o palabras clave. | Escenario 1: Resultados encontrados<br>Dado que el director de obra ingresa un término de búsqueda,<br>cuando ejecuta la consulta,<br>entonces el sistema lista los proyectos, tramos e incidencias coincidentes de la cartera.<br><br>Escenario 2: Sin resultados<br>Dado que el término de búsqueda no coincide con ningún registro,<br>cuando el director de obra ejecuta la consulta,<br>entonces el sistema informa que no se encontraron resultados. | EP01: Proyecto |
| US33 | Asociación de Sensores IoT a Puntos de Monitoreo | Como Inspector Ambiental, quiero dar de alta puntos de monitoreo geolocalizados vinculados a sensores IoT para automatizar la captura de datos en un tramo vial. | Escenario 1: Alta exitosa<br>Dado que el inspector ambiental selecciona un tramo del proyecto e ingresa las coordenadas y el identificador del sensor IoT,<br>cuando confirma el registro,<br>entonces el sistema habilita el punto de monitoreo para recibir telemetría. | EP02: Indicador |
| US34 | Edición de Ubicación y Umbrales de un Sensor IoT | Como Ingeniero Ambiental, quiero editar la ubicación o los umbrales de alerta de un sensor para ajustarlo al avance físico de los frentes de trabajo o tramos viales. | Escenario 1: Actualización exitosa<br>Dado que el ingeniero ambiental modifica la ubicación o los umbrales de alerta de un sensor,<br>cuando confirma los cambios,<br>entonces el sistema actualiza dinámicamente los parámetros del punto de monitoreo. | EP02: Indicador |
| US35 | Gestión de Suscripción y Alquiler de Dispositivos IoT | Como Director de Obra, quiero contratar o asociar dispositivos de monitoreo IoT mediante alquiler mensual independiente del plan de suscripción para adaptarlos a mi obra. | Escenario 1: Actualización de contrato de alquiler<br>Dado que el director de obra selecciona los sensores requeridos (aire, ruido, vibraciones) del inventario disponible,<br>cuando confirma la solicitud,<br>entonces el sistema actualiza el contrato de alquiler IoT correspondiente al proyecto. | EP09: Suscripción |
| US36 | Comunicación y Trazabilidad en Incidencia | Como Inspector Ambiental, quiero registrar comentarios y notas dentro de una incidencia para coordinar las acciones correctivas entre los equipos operativos. | Escenario 1: Registro de comentario<br>Dado que el inspector ambiental accede al detalle de una incidencia,<br>cuando registra una observación,<br>entonces el sistema guarda el comentario en el historial junto con el autor y la marca de tiempo. | EP04: Incidencia |
| US37 | Alerta de Escalamiento por Incidencia Estancada | Como Gerente de Proyecto, quiero recibir una notificación de escalamiento cuando una incidencia no presente acciones correctivas en 72 horas para intervenir oportunamente. | Escenario 1: Escalamiento generado<br>Dado que transcurren 72 horas sin cambios de estado en una incidencia abierta,<br>cuando el sistema evalúa las incidencias pendientes,<br>entonces marca la incidencia como estancada y notifica al gerente de proyecto responsable. | EP03: Alerta |
| US38 | Panel Consolidado de Salud Ambiental del Portafolio | Como Director de Obra, quiero un panel general que resuma la salud ambiental de todas las carreteras en ejecución o conservación para mitigar riesgos legales y multas. | Escenario 1: Consulta del panel consolidado<br>Dado que la empresa administra múltiples obras viales,<br>cuando el director de obra consulta el panel multi-proyecto,<br>entonces el sistema presenta el estado consolidado y el nivel de riesgo de cada obra de la cartera. | EP06: Dashboard |
| US39 | Visualización de KPIs de Gestión Ambiental | Como Director de Obra, quiero revisar indicadores clave (% de incidencias cerradas, tiempo medio de atención de alertas, sensores activos) para auditar el rendimiento en obra. | Escenario 1: Consulta de métricas<br>Dado que el director de obra accede a la vista analítica del portafolio,<br>cuando los datos se procesan,<br>entonces el sistema presenta las métricas consolidadas del desempeño ambiental. | EP06: Dashboard |
| US40 | Control de Versiones de Documentos Ambientales | Como Ingeniero Ambiental, quiero gestionar versiones de los documentos ambientales subidos (PMA, DIA, EIA) para asegurar que la obra trabaje con la normativa vigente. | Escenario 1: Nueva versión detectada<br>Dado que se adjunta un nuevo archivo normativo para un tramo,<br>cuando el sistema detecta un documento previo con el mismo nombre,<br>entonces incrementa la versión conservando el historial. | EP10: Documento |
| US41 | Emisión de Tokens JWT y Permisos por Nivel de Acceso | Como Developer, quiero que la API emita tokens JWT que incluyan los permisos asignados por nivel de acceso para autorizar las solicitudes realizadas desde las aplicaciones cliente. | Escenario 1: Emisión exitosa<br>Dado que las credenciales enviadas son válidas,<br>cuando se invoca el endpoint de autenticación,<br>entonces la API retorna un Bearer token con los permisos vigentes del colaborador. | EP11: API |
| US42 | Documentación Swagger/OpenAPI de la API | Como Developer, quiero disponer de documentación Swagger/OpenAPI de la API para integrar los endpoints de sensores IoT, alertas e incidencias de forma autónoma. | Escenario 1: Consulta de documentación<br>Dado que la API está desplegada,<br>cuando se accede a la ruta de documentación,<br>entonces el sistema presenta los modelos de datos, parámetros y respuestas de cada endpoint. | EP11: API |
| US43 | CRUD de Proyectos Viales vía API | Como Developer, quiero exponer endpoints GET/POST/PUT/DELETE para gestionar la información de carreteras, tramos y frentes de trabajo de constructoras y conservadoras. | Escenario 1: Creación exitosa<br>Dado que se realiza una petición al endpoint /api/v1/projects,<br>cuando la estructura del payload es válida,<br>entonces la API procesa la solicitud y retorna el código de estado 201 junto con la entidad persistida. | EP01: Proyecto |
| US44 | Endpoint de Ingesta de Datos IoT | Como Developer, quiero implementar un endpoint seguro para recibir las lecturas automáticas de los sensores IoT de campo (PM10, PM2.5, ruido, agua, pH) con marca de tiempo. | Escenario 1: Ingesta exitosa<br>Dado que un dispositivo o gateway IoT envía una medición,<br>cuando el payload cumple con el esquema validado,<br>entonces la API almacena el dato asociado al sensor y al proyecto vial. | EP02: Indicador |
| US45 | Motor de Comparación de Umbrales Normativos | Como Developer, quiero implementar un motor que analice cada lectura entrante frente a los umbrales configurados (Óptimo, Advertencia, Crítico) para detectar condiciones de riesgo de forma automatizada. | Escenario 1: Superación de umbral<br>Dado que ingresa un dato ambiental,<br>cuando este supera el límite normativo configurado,<br>entonces la API actualiza el estado del indicador a Advertencia o Crítico según corresponda. | EP03: Alerta |
| US46 | Generador Automático de Incidencias | Como Developer, quiero que la API instancie automáticamente una incidencia ambiental cuando una lectura de sensor IoT alcance el estado Crítico. | Escenario 1: Generación automática<br>Dado que un parámetro entra en estado Crítico,<br>cuando el motor procesa el evento,<br>entonces la API crea una incidencia vinculada al tramo, al punto de monitoreo y al valor registrado. | EP04: Incidencia |
| US47 | Endpoint de Subida de Evidencias Fotográficas | Como Developer, quiero implementar un endpoint multipart/form-data para recibir y almacenar imágenes de campo y notas de acciones correctivas en la nube. | Escenario 1: Subida exitosa<br>Dado que se envía un archivo de imagen válido desde la aplicación,<br>cuando la API procesa la subida,<br>entonces retorna la URL persistida y los metadatos asociados a la evidencia. | EP10: Documento |
| US48 | Paginación y Filtrado de Peticiones | Como Developer, quiero que los listados de mediciones e incidencias soporten paginación y filtros por proyecto para mantener un buen desempeño en la interfaz. | Escenario 1: Consulta paginada<br>Dado que se consulta el endpoint /api/v1/incidents con parámetros de página, tamaño y proyecto,<br>cuando la API responde,<br>entonces retorna únicamente los registros solicitados junto con su metadata de paginación. | EP11: API |
| US49 | Cifrado de Contraseñas | Como Developer, quiero asegurar el hash de las contraseñas mediante BCrypt para proteger la información confidencial de los usuarios registrados en la plataforma. | Escenario 1: Almacenamiento cifrado<br>Dado que se registra un nuevo usuario o se actualiza su contraseña,<br>cuando el dato se persiste en la base de datos,<br>entonces la API almacena la contraseña cifrada con un factor de trabajo seguro. | EP08: Usuario |
| US50 | Rate Limiting de la API | Como Developer, quiero limitar la tasa de peticiones por IP y token para prevenir la saturación de los servidores o ataques contra la infraestructura SaaS. | Escenario 1: Límite excedido<br>Dado que un cliente excede el número máximo de peticiones permitidas por minuto,<br>cuando realiza una nueva llamada,<br>entonces la API responde con el código de estado 429 (Too Many Requests). | EP11: API |
| US51 | Configuración de Umbrales por Normativa Aplicable | Como Developer, quiero permitir la asignación de distintas tablas de umbrales según el tipo de entorno vial y las normativas ambientales peruanas (ECA, MTC). | Escenario 1: Carga de umbrales<br>Dado que se registra un proyecto vial con una clasificación determinada,<br>cuando se asignan sus sensores,<br>entonces la API carga los límites normativos correspondientes a dicha clasificación. | EP01: Proyecto |
| US52 | Validación de Cuotas por Plan de Suscripción | Como Developer, quiero verificar los límites del plan activo (Starter, Professional, Enterprise) para controlar la creación de proyectos y la cantidad de usuarios permitidos. | Escenario 1: Cuota excedida<br>Dado que una empresa intenta registrar un proyecto que sobrepasa el cupo de su suscripción,<br>cuando la API procesa la solicitud,<br>entonces la rechaza con el código de estado 403. | EP09: Suscripción |
| US53 | Generador de Estructura para Reportes de Auditoría | Como Developer, quiero compilar el historial consolidado de mediciones, alertas, incidencias, acciones correctivas y evidencias de un proyecto para disponerlo como base de los reportes de auditoría. | Escenario 1: Compilación exitosa<br>Dado que se solicita la preparación de un reporte ambiental,<br>cuando la API procesa el periodo requerido,<br>entonces retorna un payload estructurado listo para su maquetación en PDF. | EP07: Reporte |
| US54 | Endpoint de Exportación de Reportes en PDF | Como Developer, quiero implementar un endpoint que compile el archivo PDF consolidado de monitoreo e incidencias viales para permitir su descarga ante fiscalizaciones. | Escenario 1: Exportación exitosa<br>Dado que un usuario autorizado solicita el informe oficial,<br>cuando el motor genera el documento,<br>entonces la API retorna el archivo PDF resultante para su descarga. | EP07: Reporte |
| US55 | Integración con Servicio de Geolocalización de Terceros | Como Developer, quiero integrar la API con un servicio externo de mapas y geocodificación para obtener coordenadas y trazados viales precisos de los tramos registrados. | Escenario 1: Normalización de coordenadas<br>Dado que se registra un tramo vial con una dirección o referencia geográfica,<br>cuando la API consulta el servicio externo de geocodificación,<br>entonces almacena las coordenadas normalizadas devueltas para su uso en los tableros geolocalizados. | EP12: Integración |
---

### 3.2. Impact Mapping
<a id="3-2-impact-mapping"></a>

En esta sección se presenta el desglose estratégico del modelo de negocio de EcoRoad mediante la técnica de **Impact Mapping**, vinculando la meta de negocio SMART con los cambios de comportamiento requeridos en los segmentos de cliente, las soluciones funcionales provistas y las historias de usuario asociadas.

<p align="center">
  <img src="./assets/images/chapter3/ImpactMapping.png" alt="Impact Mapping Consolidado - EcoRoad" width="100%"/>
</p>

## 3.3. Product Backlog

| # Orden | User Story Id | Título | Descripción | Story Points (1/2/3/5/8) |
| :--- | :--- | :--- | :--- | :--- |
| 1 | US02 | Visualización de Soluciones Ambientales | Como Visitante, quiero conocer qué tipos de problemas ambientales mide la plataforma para determinar si cumple con la normativa legal aplicable a mi obra vial. | 2 |
| 2 | US04 | Revisión de Características Tecnológicas y Cumplimiento | Como Visitante, quiero conocer los detalles de la arquitectura tecnológica de la plataforma para evaluar su viabilidad técnica en proyectos civiles mayores. | 2 |
| 3 | US05 | Visualización de Beneficios de la Plataforma | Como Visitante, quiero conocer las ventajas operativas y legales del sistema para evaluar la viabilidad de su implementación en mi proyecto vial. | 2 |
| 4 | US07 | Visualización de Testimonios y Opiniones | Como Visitante, quiero conocer las opiniones de otros profesionales del sector construcción para determinar la confiabilidad de la plataforma en proyectos reales. | 2 |
| 5 | US06 | Comparación de Planes de Suscripción | Como Visitante, quiero conocer los precios y las características de cada plan de suscripción para elegir el que mejor se adapte al presupuesto de mi empresa. | 3 |
| 6 | US08 | Acceso a Canales de Soporte y Datos Legales | Como Visitante, quiero acceder a la información de contacto institucional y al marco regulatorio soportado por la plataforma para resolver dudas técnicas de manera independiente. | 1 |
| 7 | US03 | Solicitud de Demostración Guiada | Como Visitante, quiero solicitar una sesión personalizada con ingenieros para evaluar cómo reducir riesgos en mis proyectos viales. | 3 |
| 8 | US27 | CTA Segmento Constructoras Viales | Como Visitante del segmento Constructoras Viales, quiero acceder a información específica sobre gestión de monitoreo e incidencias para evaluar si la plataforma se ajusta a mis frentes de construcción. | 2 |
| 9 | US28 | CTA Segmento Mantenimiento Vial | Como Visitante del segmento Mantenimiento Vial, quiero acceder a la propuesta de gestión multi-proyecto para evaluar la vista consolidada de mis tramos en conservación y rehabilitación vial. | 2 |
| 10 | US29 | Notificaciones Push en Landing | Como Visitante, quiero aceptar notificaciones del navegador para recibir avisos inmediatos de superación de límites ambientales sin estar dentro de la aplicación. | 3 |
| 11 | US01 | Autenticación de Usuarios | Como Visitante, quiero iniciar sesión en la plataforma para acceder a mi cuenta y perfil según mi rol. | 3 |
| 12 | US30 | Creación de Proyecto Vial | Como Gerente de Proyecto, quiero registrar una obra vial definiendo ubicación, tramos y frentes de trabajo para iniciar el monitoreo ambiental centralizado. | 5 |
| 13 | US33 | Asociación de Sensores IoT a Puntos de Monitoreo | Como Inspector Ambiental, quiero dar de alta puntos de monitoreo geolocalizados vinculados a sensores IoT para automatizar la captura de datos en un tramo vial. | 5 |
| 14 | US44 | Endpoint de Ingesta de Datos IoT | Como Developer, quiero implementar un endpoint seguro para recibir las lecturas automáticas de los sensores IoT de campo con marca de tiempo. | 5 |
| 15 | US09 | Monitoreo de Mediciones en Tiempo Real | Como Ingeniero Ambiental, quiero consultar las mediciones en tiempo real de los sensores IoT de un proyecto para identificar oportunamente el estado ambiental de cada punto de monitoreo. | 5 |
| 16 | US10 | Consulta de Estado y Ubicación de Sensores IoT | Como Ingeniero Ambiental, quiero consultar la ubicación y el estado operativo de los sensores instalados en un proyecto para verificar la cobertura del monitoreo ambiental. | 3 |
| 17 | US45 | Motor de Comparación de Umbrales Normativos | Como Developer, quiero implementar un motor que analice cada lectura entrante frente a los umbrales configurados para detectar condiciones de riesgo de forma automatizada. | 8 |
| 18 | US51 | Configuración de Umbrales por Normativa Aplicable | Como Developer, quiero permitir la asignación de distintas tablas de umbrales según el tipo de entorno vial y las normativas ambientales peruanas (ECA, MTC). | 3 |
| 19 | US15 | Consulta del Nivel de Riesgo de un Indicador | Como Ingeniero Ambiental, quiero conocer el nivel de riesgo asociado a cada indicador ambiental medido para identificar qué situaciones requieren atención prioritaria. | 3 |
| 20 | US46 | Generador Automático de Incidencias | Como Developer, quiero que la API instancie automáticamente una incidencia ambiental cuando una lectura de sensor IoT alcance el estado Crítico. | 5 |
| 21 | US18 | Registro de Incidencia Ambiental | Como Ingeniero Ambiental, quiero que se registre una incidencia cuando una medición alcance un estado crítico para iniciar su atención y seguimiento. | 5 |
| 22 | US16 | Consulta de Alertas Generadas | Como Ingeniero Ambiental, quiero consultar las alertas generadas en un proyecto para identificar rápidamente dónde se está presentando un problema ambiental. | 3 |
| 23 | US17 | Notificación de Alertas Críticas | Como Gerente de Proyecto, quiero ser notificado cuando se genere una alerta crítica en alguno de mis proyectos para actuar de manera oportuna. | 3 |
| 24 | US19 | Asignación de Responsable de Incidencia | Como Director de Obra, quiero asignar un responsable a una incidencia ambiental para garantizar que sea atendida oportunamente. | 3 |
| 25 | US20 | Registro de Acción Correctiva | Como Inspector Ambiental, quiero registrar la acción correctiva realizada frente a una incidencia ambiental para documentar la respuesta ejecutada en campo. | 3 |
| 26 | US47 | Endpoint de Subida de Evidencias Fotográficas | Como Developer, quiero implementar un endpoint multipart/form-data para recibir y almacenar imágenes de campo y notas de acciones correctivas en la nube. | 5 |
| 27 | US22 | Registro de Evidencia de Campo | Como Inspector Ambiental, quiero registrar evidencia fotográfica y descriptiva de las acciones correctivas realizadas para mantener la trazabilidad de la atención de incidencias. | 3 |
| 28 | US21 | Actualización de Estado de Incidencia | Como Ingeniero Ambiental, quiero actualizar el estado de una incidencia ambiental para reflejar el avance real de su atención. | 3 |
| 29 | US36 | Comunicación y Trazabilidad en Incidencia | Como Inspector Ambiental, quiero registrar comentarios y notas dentro de una incidencia para coordinar las acciones correctivas entre los equipos operativos. | 2 |
| 30 | US37 | Alerta de Escalamiento por Incidencia Estancada | Como Gerente de Proyecto, quiero recibir una notificación de escalamiento cuando una incidencia no presente acciones correctivas en 72 horas para intervenir oportunamente. | 5 |
| 31 | US34 | Edición de Ubicación y Umbrales de un Sensor IoT | Como Ingeniero Ambiental, quiero editar la ubicación o los umbrales de alerta de un sensor para ajustarlo al avance físico de los frentes de trabajo o tramos viales. | 3 |
| 32 | US14 | Consulta de Evolución Histórica de un Indicador | Como Ingeniero Ambiental, quiero consultar la evolución histórica de un indicador ambiental para analizar el comportamiento del proyecto a lo largo del tiempo. | 3 |
| 33 | US11 | Visualización General de Proyectos | Como Gerente de Proyecto, quiero consultar el estado general de todos los proyectos a mi cargo para priorizar mi atención según el nivel de riesgo ambiental de cada uno. | 3 |
| 34 | US12 | Consulta de Resumen de un Proyecto | Como Director de Obra, quiero consultar el resumen del estado ambiental de un proyecto específico para tomar decisiones sobre la continuidad de las actividades en obra. | 2 |
| 35 | US13 | Consulta del Dashboard Ambiental de un Proyecto | Como Ingeniero Ambiental, quiero consultar el dashboard ambiental de un proyecto para visualizar de forma centralizada el estado de sus tramos y puntos de monitoreo. | 5 |
| 36 | US38 | Panel Consolidado de Salud Ambiental del Portafolio | Como Director de Obra, quiero un panel general que resuma la salud ambiental de todas las carreteras en ejecución o conservación para mitigar riesgos legales y multas. | 5 |
| 37 | US39 | Visualización de KPIs de Gestión Ambiental | Como Director de Obra, quiero revisar indicadores clave (% de incidencias cerradas, tiempo medio de atención de alertas, sensores activos) para auditar el rendimiento en obra. | 3 |
| 38 | US55 | Integración con Servicio de Geolocalización de Terceros | Como Developer, quiero integrar la API con un servicio externo de mapas y geocodificación para obtener coordenadas y trazados viales precisos de los tramos registrados. | 5 |
| 39 | US32 | Búsqueda Global de Proyectos, Tramos e Incidencias | Como Director de Obra, quiero disponer de un buscador centralizado para localizar rápidamente carreteras, frentes de trabajo o incidencias específicas mediante códigos o palabras clave. | 3 |
| 40 | US31 | Archivado de Proyectos Viales Finalizados | Como Director de Obra, quiero archivar obras de infraestructura concluidas para mantener despejado el portafolio activo sin perder la trazabilidad histórica. | 2 |
| 41 | US23 | Consulta del Historial Ambiental de un Proyecto | Como Director de Obra, quiero consultar el historial ambiental de un proyecto para analizar su comportamiento a lo largo del tiempo y sustentar decisiones ante terceros. | 3 |
| 42 | US53 | Generador de Estructura para Reportes de Auditoría | Como Developer, quiero compilar el historial consolidado de mediciones, alertas, incidencias, acciones correctivas y evidencias de un proyecto para disponerlo como base de los reportes de auditoría. | 5 |
| 43 | US54 | Endpoint de Exportación de Reportes en PDF | Como Developer, quiero implementar un endpoint que compile el archivo PDF consolidado de monitoreo e incidencias viales para permitir su descarga ante fiscalizaciones. | 5 |
| 44 | US24 | Generación de Reporte Ambiental | Como Gerente de Proyecto, quiero generar un reporte con la información ambiental de un proyecto para presentarlo ante la empresa o las autoridades correspondientes. | 5 |
| 45 | US40 | Control de Versiones de Documentos Ambientales | Como Ingeniero Ambiental, quiero gestionar versiones de los documentos ambientales subidos (PMA, DIA, EIA) para asegurar que la obra trabaje con la normativa vigente. | 3 |
| 46 | US35 | Gestión de Suscripción y Alquiler de Dispositivos IoT | Como Director de Obra, quiero contratar o asociar dispositivos de monitoreo IoT mediante alquiler mensual independiente del plan de suscripción para adaptarlos a mi obra. | 3 |
| 47 | US52 | Validación de Cuotas por Plan de Suscripción | Como Developer, quiero verificar los límites del plan activo (Starter, Professional, Enterprise) para controlar la creación de proyectos y la cantidad de usuarios permitidos. | 3 |
| 48 | US49 | Cifrado de Contraseñas | Como Developer, quiero asegurar el hash de las contraseñas mediante BCrypt para proteger la información confidencial de los usuarios registrados en la plataforma. | 2 |
| 49 | US41 | Emisión de Tokens JWT y Permisos por Nivel de Acceso | Como Developer, quiero que la API emita tokens JWT que incluyan los permisos asignados por nivel de acceso para autorizar las solicitudes realizadas desde las aplicaciones cliente. | 3 |
| 50 | US25 | Registro de Colaboradores y Asignación de Permisos | Como Administrador de la Constructora, quiero registrar a los colaboradores de mi empresa y asignarles permisos específicos para adaptar el acceso a la plataforma según el rol de cada uno. | 3 |
| 51 | US26 | Restricción de Acceso según Permisos Asignados | Como Administrador de la Constructora, quiero que el sistema restrinja el acceso de cada colaborador según los permisos asignados para garantizar la seguridad de la información del proyecto. | 3 |
| 52 | US42 | Documentación Swagger/OpenAPI de la API | Como Developer, quiero disponer de documentación Swagger/OpenAPI de la API para integrar los endpoints de sensores IoT, alertas e incidencias de forma autónoma. | 2 |
| 53 | US43 | CRUD de Proyectos Viales vía API | Como Developer, quiero exponer endpoints GET/POST/PUT/DELETE para gestionar la información de carreteras, tramos y frentes de trabajo de constructoras y conservadoras. | 5 |
| 54 | US48 | Paginación y Filtrado de Peticiones | Como Developer, quiero que los listados de mediciones e incidencias soporten paginación y filtros por proyecto para mantener un buen desempeño en la interfaz. | 2 |
| 55 | US50 | Rate Limiting de la API | Como Developer, quiero limitar la tasa de peticiones por IP y token para prevenir la saturación de los servidores o ataques contra la infraestructura SaaS. | 2 |


# Product Design
## 4.1. Style Guidelines.
<a id="4-1-style-guidelines"></a>
 
En esta sección, el equipo sienta las bases para contar con un repositorio central y organizado de uso común para todo el equipo, que incluye assets, fuentes tipográficas, componentes visuales, entre otros. 
Esto con el fin de mantener una presentación consistente y enfocada de la marca EcoRoad a lo largo de todos los puntos de contacto con el usuario, ya sea en campo, en oficina o en los distintos dispositivos desde los que se accede a la plataforma.

### 4.1.1. General Style Guidelines.
<a id="4-1-1-general-style-guidelines"></a>

 Construimos la identidad de EcoRoad bajo directrices visuales de Branding, Typography, Colors y Spacing, así como las dimensiones adoptadas para el tono de comunicación y lenguaje aplicado por la marca.
Estas decisiones se sustentan en el posicionamiento de EcoRoad como una plataforma que transforma el monitoreo ambiental en un flujo de gestión de detección de riesgos, alerta, incidencia, acción correctiva y evidencia, por lo que la identidad visual busca transmitir confiabilidad, precisión técnica y una ingeniería civil preventiva y sostenible.

**Branding:**

El logotipo de EcoRoad sintetiza los pilares conceptuales de la propuesta: naturaleza, infraestructura vial y monitoreo ambiental en tiempo real mediante IoT.

* **Hoja (naturaleza/sostenibilidad)**: Representa el componente ambiental que la plataforma monitorea (aire, ruido, agua, vibraciones) y la orientación hacia una gestión vial más sostenible. 
* **Carretera (infraestructura vial)**: Representa el sector de aplicación del producto, construcción, mantenimiento y rehabilitación de vías, transmite avance, trazabilidad y dirección, en línea con el seguimiento de acciones correctivas hasta el cierre de cada incidencia. 
* **Montañas y sol (contexto geográfico y monitoreo)**: Hacen referencia a los tramos, frentes de trabajo y puntos de monitoreo que la plataforma visualiza mediante dashboards geolocalizados. 
* **Contenedor circular**: Refuerza la idea de un ciclo completo de gestión ambiental (monitoreo -> alerta -> incidencia -> acción correctiva -> evidencia -> cierre), coherente con el enfoque preventivo y no solo descriptivo de la plataforma.

**Typography:**

Siguiendo la construcción geométrica y redondeada del logotipo, se adopta una familia tipográfica sans-serif geométrica como base del sistema, priorizando legibilidad en pantallas de campo (tablets, móviles con luz solar directa) y coherencia con el tono técnico y confiable de la marca.


| Uso                        | Tipografía                     | Aplicación |
|:---------------------------|:-------------------------------| :--- |
| Encabezados                | Poppins Bold / SemiBold        | Títulos de dashboard, nombres de proyecto |
| Subtítulos                 | Poppins Medium                 | Nombres de módulos, tarjetas de indicadores |
| Cuerpo de texto            | Inter Regular                  |  Tablas, formularios, descripciones |
| Datos numéricos / métricas | Inter Medium (tabular figures) |Valores de sensores, timestamps |

**Colors:**

La paleta se deriva directamente de los colores institucionales definidos para EcoRoad, con un rol funcional asignado a cada uno para su uso en interfaz:

| Color         | Hex | Rol funcional en la plataforma                                                                                          |
|:--------------| :--- |:------------------------------------------------------------------------------------------------------------------------|
| Verde         | `#2E9E7A` | Color principal de la marca; estado óptimo / sin riesgo detectado (semáforo verde)                                       |
| Azul petróleo | `#264653` | Color secundario; tipografía principal, fondos de navegación, elementos estructurales                                   |
| Crema         | `#F5F1E8` | Fondo base de la interfaz; transmite neutralidad y bajo cansancio visual en uso prolongado                              |
| Amarillo      | `#E9B44C` | Condición de advertencia (semáforo ámbar) — indicador que se acerca al umbral establecido y puede derivar en una alerta |
| Rojo          | `#C0392B` | Condición crítica (semáforo rojo) — el indicador supera el umbral y el sistema genera una incidencia                    |


**Spacing**

Se define un sistema de espaciado en base 8px (8, 16, 24, 32, 40), compatible con grillas de 12 columnas para web y facilitando la futura adaptación a interfaces móviles. 
El espaciado busca priorizar la lectura rápida de indicadores en campo, evitando el amontonamiento de datos en tableros con múltiples proyectos simultáneos.

**Lenguaje de comunicación**

Dado que los usuarios principales (responsables del monitoreo, gestión y atención de incidencias ambientales dentro de empresas constructoras y de conservación/rehabilitación vial) 
operan bajo presión de tiempo en campo y necesitan actuar con rapidez ante un riesgo, el tono de EcoRoad se posiciona de la siguiente manera:

| Posicionamiento                | Justificación |
|:-------------------------------| :--- |
| Serio                          | La plataforma respalda decisiones sobre riesgos ambientales reales en obra; el lenguaje debe transmitir precisión técnica. |
| Formal, con cercanía funcional | Se usa terminología técnica correcta (umbrales, incidencias, acciones correctivas), con instrucciones claras y directas para uso rápido en campo. |
| Respetuoso                     | El lenguaje describe condiciones y acciones sin atribuir culpas; una incidencia se comunica como un hecho a resolver, no como un señalamiento. |
| Sereno                         | Las alertas y notificaciones comunican el nivel de riesgo con claridad, priorizando que el usuario entienda qué acción tomar sobre la urgencia emocional del mensaje. |


### 4.1.2. Web Style Guidelines.
<a id="4-1-2-web-style-guidelines"></a>

<a id="4-1-2-Web-Style-Guidelines"></a>

En esta sección se explican e ilustran las decisiones sobre los estándares visuales y de interacción para las interfaces web responsive de EcoRoad, 
aplicables al panel de gestión donde una misma empresa constructora o de conservación/rehabilitación vial, administra sus proyectos, sensores IoT, alertas e incidencias.

* **Grid system:** grilla de 12 columnas con márgenes fluidos, breakpoints en 1280px (desktop), 1024px (tablet/laptop) y 768px (tablet vertical), 
priorizando el desktop como plataforma principal para el análisis multi-proyecto y la vista tablet para el registro de evidencias en campo.
* **Componentes de dashboard:** tarjetas de indicador (KPI cards) con codificación semáforo (verde/amarillo/rojo) según la paleta funcional; 
los dashboards geolocalizados usan el azul petróleo como color base del mapa y marcadores en los tres colores de estado para representar tramos, frentes de trabajo y puntos de monitoreo.
* **Navegación:** barra lateral fija en azul petróleo (
#264653) con el isotipo de EcoRoad, manteniendo contraste alto con el fondo crema (
#F5F1E8) del área de contenido para reducir fatiga visual en sesiones prolongadas de monitoreo.
* **Botones y estados interactivos:** botón primario en verde EcoRoad (
#2E9E7A) para acciones de confirmación (registrar medición, cerrar incidencia); botón de alerta en rojo (
#C0392B) reservado exclusivamente para acciones críticas (crear/escalar una incidencia), evitando el uso decorativo de este color para no diluir su significado funcional.
* **Gestión de incidencias (tipo Kanban):** columnas por estado del flujo de riesgo (Alerta -> Incidencia  -> Acción correctiva -> Evidencia registrada -> Cerrada), 
con tarjetas que muestran responsable asignado, ubicación, fecha/hora y miniatura de evidencia fotográfica, facilitando el seguimiento hasta el cierre.
* **Formularios de registro de campo:** diseñados con campos grandes y espaciado generoso, priorizando el ingreso rápido de mediciones y evidencias 
(foto, descripción, fecha, hora, ubicación) desde dispositivos móviles en obra.
* **Accesibilidad:**  contraste mínimo AA (WCAG 2.1) entre texto y fondo en todas las combinaciones de la paleta, verificado especialmente en el uso del amarillo 
(#E9B44C) sobre crema, que requiere texto oscuro (#264653) para mantener legibilidad.


## 4.2. Information Architecture.
<a id="4-2-information-architecture"></a>

La arquitectura de información de EcoRoad está diseñada para garantizar una navegación fluida, intuitiva y eficiente, permitiendo que tanto los ingenieros de campo (constructoras) como los auditores (supervisoras) accedan con rapidez al valor de la plataforma y a sus herramientas de gestión y fiscalización.

### 4.2.1. Organization Systems.
<a id="4-2-1-organization-systems"></a>

<a id="4-2-1-organization-systems"></a>

* **Jerarquía de Contenidos:** La estructura de la información fluye de lo general a lo específico. En la Landing Page pública se prioriza la propuesta de valor HaaS/SaaS y los beneficios de Caiman, mientras que en la Web Application la jerarquía organiza el portafolio global de proyectos viales hasta llegar al detalle micro de cada tramo, punto de monitoreo e incidencia.

* **Secciones Principales de la Aplicación:** La plataforma se divide en módulos funcionales clave:
    * **Dashboard Global:** Vista ejecutiva y multi-proyecto con indicadores de salud ambiental.
    * **Mapa Interactivo:** Visualización geolocalizada de tramos viales y pines semafóricos.
    * **Gestión de Proyectos:** Alta, configuración y administración de frentes de obra viales.
    * **Puntos de Monitoreo:** Registro de telemetría y parámetros físicos (aire, ruido, agua).
    * **Tablero de Incidencias:** Flujo Kanban para el seguimiento y resolución de desvíos normativos con evidencia multimedia.
    * **Reportes y Auditorías:** Generación automatizada de expedientes y exportación en formato PDF.
    * **Configuración y Suscripción:** Gestión de planes (Base, Profesional, Enterprise) y control de accesos basados en roles (RBAC).

* **Agrupación de Contenidos:** Los datos operativos se agrupan lógicamente por severidad y contexto temporal. Las alertas y tickets críticos se destacan mediante códigos de color estandarizados (semáforo), permitiendo un escaneo visual rápido sin saturar al operador de campo.


### 4.2.2. Labeling Systems.
<a id="4-2-2-labeling-systems"></a>

Para asegurar la visibilidad en motores de búsqueda y la correcta compartición en canales digitales B2B, se establecen los siguientes metadatos principales para la experiencia web de EcoRoad:



### 4.2.3. SEO Tags and Meta Tags.
<a id="4-2-3-seo-tags-meta-tags"></a>


* **Landing Page (Sitio Web Estático):**
    * **Title:** `EcoRoad by Caiman | Monitoreo y Cumplimiento Ambiental en Infraestructura Vial`
    * **Meta Description:** `Plataforma HaaS/SaaS líder en el Perú para la gestión ambiental vial. Automatiza sensores IoT en comodato, alertas de umbrales y reportes de auditoría para constructoras y supervisoras.`
    * **Meta Keywords:** `monitoreo ambiental vial, cumplimiento normativo OEFA MTC, sensores IoT construcción, gestión ambiental carreteras, auditoría ambiental RPA.`
    * **Meta Author:** `Caiman Tech Startup`

* **Web Application (Plataforma Privada):**
    * **Title:** `EcoRoad App | Gestión y Fiscalización Ambiental en Tiempo Real`
    * **Meta Description:** `Panel de control privado para el seguimiento de indicadores ambientales, mapa geolocalizado de tramos viales y resolución de incidencias operativas.`
    * **Meta Keywords:** `dashboard ambiental, tramos viales, tablero kanban incidencias, reportes PDF auditoría.`
    * **Meta Author:** `Caiman Tech Startup`


### 4.2.4. Searching Systems.
<a id="4-2-4-searching-systems"></a>

* **Barra de Búsqueda Global:** Ubicada de forma prominente en el encabezado principal de la Web Application, permitiendo localizar de inmediato proyectos por nombre o código de tramo vial, puntos de control específicos e incidencias registradas.
* **Filtros y Facetas Contextuales:** Herramientas de acotación de datos dentro de los módulos para filtrar la información por tipo de indicador ambiental (*aire, ruido, agua*), rango de fechas y niveles de severidad del riesgo.
* **Historial de Búsqueda:** Registro automatizado de consultas recientes para agilizar el flujo de trabajo de los auditores y residentes de obra que alternan entre múltiples frentes de trabajo.
* **Resultados Relevantes:** Priorización inteligente de resultados basada en los permisos de usuario (RBAC) y la cartera de proyectos activa asignada a su cuenta.


### 4.2.5. Navigation Systems.
<a id="4-2-5-navigation-systems"></a>

* **Navegación Global:** La barra superior y el menú lateral (*Sidebar*) permanente aseguran el acceso transversal a las secciones principales de la plataforma desde cualquier pantalla del sistema.
* **Navegación Contextual:** Enlaces integrados dentro de las tarjetas de proyectos y botones de acción rápida (*CTAs*) que guían al usuario desde la vista macro del portafolio hasta el detalle analítico de una incidencia o punto de monitoreo.
* **Migas de Pan (Breadcrumbs):** Elementos de rastreo ubicados en la cabecera interna (ej. *Portafolio > Autopista Norte > Tramo 3 > Punto de Control #02*) que indican la ruta de navegación actual y permiten un retroceso jerárquico inmediato.
* **Navegación Móvil:** Adaptación mediante menús colapsables tipo hamburguesa optimizados para pantallas táctiles, asegurando la usabilidad de campo en dispositivos móviles de los ingenieros residentes.


## 4.3. Landing Page UI Design.
<a id="4-3-landing-page-ui-design"></a>


4.3.1. Landing Page Wireframe.

El wireframe de nuestra página de inicio sirve como un mapa visual que define la estructura y el flujo de la información. Este esquema asegura una disposición lógica de los componentes, facilitando la navegación y destacando la propuesta de valor de EcoRoad. Las secciones del wireframe están diseñadas para contar una historia completa y persuasiva:

**Hero**

El hero de nuestra plataforma EcoRoad presenta una interfaz limpia e institucional alineada a la supervisión ambiental, destacando con un título directo: "Automated Environmental Compliance & Mitigation for Highway Construction". Una breve descripción que enfatiza el monitoreo en tiempo real y la prevención de multas, acompañada por un botón de llamado a la acción rápida y de alto contraste ("Get Started") que orienta al usuario hacia la conversión. En la parte inferior, una imagen de infraestructura vial que incluye indicadores clave sobre nodos IoT activos y porcentaje de cumplimiento normativo, como un ejemplo de la precisión técnica del sistema.

<div align="center">
  <img src="assets/images/chapter4/hero.png" alt="Hero">
</div>

**Solutions**

La sección "Solutions" presenta la oferta de valor mediante un encabezado claro ("Specialized Solutions for the Highway Construction Sector") e introduce una retícula de cuatro tarjetas interactivas que detallan las áreas clave de monitoreo: calidad del aire y polvo, nivel sonoro y ruido, supervisión de recursos hídricos y protección de fauna/hábitats sensibles. Cada tarjeta utiliza un ícono representativo, una breve descripción técnica del proceso automatizado y etiquetas que destacan los estándares normativos o de calibración correspondientes, garantizando una lectura estructurada y fluida de las capacidades de la plataforma, mostrando lo que ofrece la plataforma.

<div align="center">
  <img src="assets/images/chapter4/wf-landing-solutions.png" alt="Paso 4">
</div>

**Benefits**

La sección "Benefits" resalta las ventajas competitivas del sistema bajo el título "The EcoRoad Advantage: From Manual Logs to Real-Time Telemetry". Mediante una cuadrícula de cuatro tarjetas con apoyo visual e infográfico, detalla los beneficios clave de la plataforma: prevención de multas y paralizaciones mediante detección preventiva ("Zero Shutdowns & Fines"), consolidación automática de evidencias con encriptación SHA-256 para auditorías ("Automated Audits"), trazabilidad y flujo de trabajo de mitigación inmediata con georreferenciación GPS RTK desde la app offline ("Immediate Mitigation Workflow"), y respaldo legal/técnico continuo frente a inspecciones normativas ("Legal Peace of Mind & Expert Backing"). Cada bloque incluye métricas de impacto que refuerzan la eficiencia operativa y el cumplimiento normativo en obra.

<div align="center">
  <img src="assets/images/chapter4/wf-landing-benefits.png" alt="Paso 4">
</div>

**About Us**

La sección "About Us" resalta la propuesta tecnológica bajo el título "Advanced Management & Compliance Technology". Incluye un video explicativo en función de la plataforma junto a un menú interactivo que detalla sus capacidades clave: dashboards GIS georreferenciados, alertas regulatorias automáticas por SMS/WhatsApp/email, cadena de custodia de evidencias con metadatos forenses y exportación en un clic de reportes oficiales en formato PDF/A y GeoJSON.

<div align="center">
  <img src="assets/images/chapter4/wf-landing-aboutus.png" alt="Paso 4">
</div>

**Testimonials**

La sección presenta ejemplos de experiencias basados en casos de éxito de la plataforma. Muestra testimonios ficticios pero realistas atribuidos a roles clave del sector (directores ambientales, consultores senior y supervisores de obra) para validar el impacto técnico y operacional de EcoRoad ante potenciales clientes.

<div align="center">
  <img src="assets/images/chapter4/wf-landing-testimonials.png" alt="Paso 4">
</div>

**Pricing**

La sección "Pricing" expone el modelo de monetización bajo el título "Flexible, Scalable Subscription Plans". Estructura la oferta en tres planes SaaS escalables (Base, Professional y Enterprise), permitiendo alternar entre facturación mensual y anual con descuento. Cada tarjeta detalla el precio, el perfil de cliente objetivo, un botón directo de acción y un listado de funcionalidades clave que van desde el monitoreo básico de proyectos hasta integraciones avanzadas y soporte 24/7.

<div align="center">
  <img src="assets/images/chapter4/wf-landing-pricing.png" alt="Paso 4">
</div>

**About team**

La sección "About Team" presenta al equipo detrás de la plataforma bajo el título "Driving Innovation and Sustainability in Highway Infrastructure". Incluye un video institucional que muestra el proceso colaborativo del grupo, acompañado por un bloque explicativo que resalta su enfoque multidisciplinario, la combinación de ingeniería de software con sostenibilidad y su visión para transformar el monitoreo ambiental tradicional en una experiencia digital eficiente e intuitiva.

<div align="center">
  <img src="assets/images/chapter4/wf-landing-aboutus.png" alt="Paso 4">
</div>

**Our team**

La sección "Our Team" presenta a los integrantes del proyecto bajo el título "Meet the multidisciplinary team behind EcoRoad's environmental telemetry platform". Organiza los perfiles en tarjetas individuales que incluyen fotografía, como Software Engineers y una breve descripción profesional centrada en sus habilidades de desarrollo y contribución a la plataforma. Justo debajo, la sección concluye con un banner final de conversión enfocado en la transformación de la sostenibilidad ambiental, ofreciendo botones directos para iniciar o agendar una sesión con un especialista.

<div align="center">
  <img src="assets/images/chapter4/wf-landing-ourteam.png" alt="Paso 4">
</div>

**Footer**

El Footer (pie de página) de la plataforma cierra el sitio con una estructura institucional sobre fondo oscuro. Se divide en cuatro columnas principales: la primera incluye el logotipo, una breve descripción de la propuesta de valor y el eslogan ("Infrastructure today, a better environment"); las dos siguientes organizan enlaces rápidos hacia los módulos de telemetría y el marco regulatorio/normativo; y la última muestra los canales de contacto, soporte técnico y sedes regionales. En la franja inferior incluye los derechos de autor reservados e información de políticas de privacidad y seguridad de datos.

<div align="center">
  <img src="assets/images/chapter4/wf-landing-footer.png" alt="Paso 4">
</div>



4.3.2. Landing Page Mock-up.

Esta sección presenta los mock-ups de la landing page para versiones web de escritorio y móvil. En ambas se explica la aplicación de los principios de diseño, diseño inclusivo y arquitectura de la información.

**Hero de la aplicación**

El hero de nuestra plataforma EcoRoad presenta una interfaz limpia e institucional alineada a la supervisión ambiental, destacando con un título directo: "Automated Environmental Compliance & Mitigation for Highway Construction". Una breve descripción que enfatiza el monitoreo en tiempo real y la prevención de multas, acompañada por un botón de llamado a la acción rápida y de alto contraste ("Get Started") que orienta al usuario hacia la conversión. En la parte inferior, una imagen de infraestructura vial que incluye indicadores clave sobre nodos IoT activos y porcentaje de cumplimiento normativo, como un ejemplo de la precisión técnica del sistema.

<div align="center">
  <img src="assets/images/chapter4/hero.png" alt="Hero">
</div>

**Solutions**

La sección "Solutions" presenta la oferta de valor mediante un encabezado claro ("Specialized Solutions for the Highway Construction Sector") e introduce una retícula de cuatro tarjetas interactivas que detallan las áreas clave de monitoreo: calidad del aire y polvo, nivel sonoro y ruido, supervisión de recursos hídricos y protección de fauna/hábitats sensibles. Cada tarjeta utiliza un ícono representativo, una breve descripción técnica del proceso automatizado y etiquetas que destacan los estándares normativos o de calibración correspondientes, garantizando una lectura estructurada y fluida de las capacidades de la plataforma, mostrando lo que ofrece la plataforma.

<div align="center">
  <img src="assets/images/chapter4/solutions.png" alt="Paso 4">
</div>

**Benefits**

La sección "Benefits" resalta las ventajas competitivas del sistema bajo el título "The EcoRoad Advantage: From Manual Logs to Real-Time Telemetry". Mediante una cuadrícula de cuatro tarjetas con apoyo visual e infográfico, detalla los beneficios clave de la plataforma: prevención de multas y paralizaciones mediante detección preventiva ("Zero Shutdowns & Fines"), consolidación automática de evidencias con encriptación SHA-256 para auditorías ("Automated Audits"), trazabilidad y flujo de trabajo de mitigación inmediata con georreferenciación GPS RTK desde la app offline ("Immediate Mitigation Workflow"), y respaldo legal/técnico continuo frente a inspecciones normativas ("Legal Peace of Mind & Expert Backing"). Cada bloque incluye métricas de impacto que refuerzan la eficiencia operativa y el cumplimiento normativo en obra.

<div align="center">
  <img src="assets/images/chapter4/benefits.png" alt="Paso 4">
</div>

**About Us**

La sección "About Us" resalta la propuesta tecnológica bajo el título "Advanced Management & Compliance Technology". Incluye un video explicativo en función de la plataforma junto a un menú interactivo que detalla sus capacidades clave: dashboards GIS georreferenciados, alertas regulatorias automáticas por SMS/WhatsApp/email, cadena de custodia de evidencias con metadatos forenses y exportación en un clic de reportes oficiales en formato PDF/A y GeoJSON.

<div align="center">
  <img src="assets/images/chapter4/aboutus.png" alt="Paso 4">
</div>

**Testimonials**

La sección presenta ejemplos de experiencias basados en casos de éxito de la plataforma. Muestra testimonios ficticios pero realistas atribuidos a roles clave del sector (directores ambientales, consultores senior y supervisores de obra) para validar el impacto técnico y operacional de EcoRoad ante potenciales clientes.

<div align="center">
  <img src="assets/images/chapter4/testimonials.png" alt="Paso 4">
</div>

**Pricing**

La sección "Pricing" expone el modelo de monetización bajo el título "Flexible, Scalable Subscription Plans". Estructura la oferta en tres planes SaaS escalables (Base, Professional y Enterprise), permitiendo alternar entre facturación mensual y anual con descuento. Cada tarjeta detalla el precio, el perfil de cliente objetivo, un botón directo de acción y un listado de funcionalidades clave que van desde el monitoreo básico de proyectos hasta integraciones avanzadas y soporte 24/7.

<div align="center">
  <img src="assets/images/chapter4/plans.png" alt="Paso 4">
</div>

**About team**

La sección "About Team" presenta al equipo detrás de la plataforma bajo el título "Driving Innovation and Sustainability in Highway Infrastructure". Incluye un video institucional que muestra el proceso colaborativo del grupo, acompañado por un bloque explicativo que resalta su enfoque multidisciplinario, la combinación de ingeniería de software con sostenibilidad y su visión para transformar el monitoreo ambiental tradicional en una experiencia digital eficiente e intuitiva.

<div align="center">
  <img src="assets/images/chapter4/abouteam.png" alt="Paso 4">
</div>

**Our team**

La sección "Our Team" presenta a los integrantes del proyecto bajo el título "Meet the multidisciplinary team behind EcoRoad's environmental telemetry platform". Organiza los perfiles en tarjetas individuales que incluyen fotografía, como Software Engineers y una breve descripción profesional centrada en sus habilidades de desarrollo y contribución a la plataforma. Justo debajo, la sección concluye con un banner final de conversión enfocado en la transformación de la sostenibilidad ambiental, ofreciendo botones directos para iniciar o agendar una sesión con un especialista.

<div align="center">
  <img src="assets/images/chapter4/ourteam.jpeg" alt="Paso 4">
</div>

**Footer**

El Footer (pie de página) de la plataforma cierra el sitio con una estructura institucional sobre fondo oscuro. Se divide en cuatro columnas principales: la primera incluye el logotipo, una breve descripción de la propuesta de valor y el eslogan ("Infrastructure today, a better environment"); las dos siguientes organizan enlaces rápidos hacia los módulos de telemetría y el marco regulatorio/normativo; y la última muestra los canales de contacto, soporte técnico y sedes regionales. En la franja inferior incluye los derechos de autor reservados e información de políticas de privacidad y seguridad de datos.

<div align="center">
  <img src="assets/images/chapter4/footer.png" alt="Paso 4">
</div>

4.4. Web Applications UX/UI Design.

4.4.1. Web Applications Wireframes.

**Home**

Muestra el resumen global de la red telemática (proyectos, sensores, alertas e incidentes activos) y el estado general de los proyectos junto con un feed de lecturas recientes fuera de parámetro

<div align="center">
  <img src="assets/images/chapter4/wf-home.png" alt="Home">
</div>

**Projects**

Ofrece el listado general de obras viales indicando su estado ambiental (óptimo, bajo observación o crítico), cantidad de sensores IoT asociados y métricas de alertas e incidentes
<div align="center">
  <img src="assets/images/chapter4/wf-projects.png" alt="Projects">
</div>

**Project Dashboard**

Presenta la vista detallada de un proyecto vial específico con el porcentaje de cumplimiento normativo (ECA), estado de la red de sensores LoRaWAN, lista de incidentes pendientes y los responsables técnicos asignados.

<div align="center">
  <img src="assets/images/chapter4/wf-dashboard.png" alt="Dashboard">
</div>

**Alerts**

Gestiona las alertas telemáticas preventivas por exceso de parámetros (material particulado, ruido, calidad de agua) y detalla la ubicación, sensor y acción preventiva recomendada en un panel técnico.
<div align="center">
  <img src="assets/images/chapter4/wf-alerts.png" alt="Alerts">
</div>

**Incidents**

Proporciona un tablero Kanban organizado según el estado del flujo de trabajo (Pendiente, En Progreso, Resuelto, Cerrado) para la asignación y gestión operativa de contingencias ambientales.
<div align="center">
  <img src="assets/images/chapter4/wf-incidents.png" alt="Incidents">
</div>

**History**

Grafica la evolución temporal de los indicadores ambientales (como PM10) comparándolos contra los límites normativos del estándar ECA, incluyendo promedios del periodo y simulador de estado sin datos
<div align="center">
  <img src="assets/images/chapter4/wf-history.png" alt="History">
</div>

**Reports**

Facilita la configuración y generación de informes oficiales de cumplimiento ambiental exportables en PDF, integrando validación por firma digital y código de seguridad encriptado SHA-256.
<div align="center">
  <img src="assets/images/chapter4/wf-reportsEnv.png" alt="Reports">
</div>

**Traceability history**

Muestra la secuencia cronológica y la trazabilidad completa de un evento ambiental desde la detección de la alerta hasta el registro de evidencia e implementación de la acción correctiva.
<div align="center">
  <img src="assets/images/chapter4/wf-historyEnv.png" alt="Reports">
</div>

**Collaborators**

Permite administrar usuarios y asignar permisos granulares basados en roles (RBAC), incluyendo un área para simular la experiencia de restricciones de acceso según el perfil seleccionado
<div align="center">
  <img src="assets/images/chapter4/wf-team.png" alt="Team">
</div>

4.4.2. Web Applications Wireflow Diagrams.

4.4.3. Web Applications Mock-ups.

En esta sección se presentan los mock-ups diseñados para la aplicación web de EcoRoad. Cada pantalla responde a las funcionalidades principales del sistema.

**Home**

Panel principal con resumen de red de telemetría, métricas globales (proyectos, sensores, alertas, incidentes) y lista de proyectos activos con tarjetas de alertas recientes en tiempo real.

<div align="center">
  <img src="assets/images/chapter4/home.png" alt="Home">
</div>

**Projects**

Listado general de obras viales con filtro por estado ambiental (óptimo, observación, crítico), conteo de sensores activos y accesos directos al detalle de cada proyecto

<div align="center">
  <img src="assets/images/chapter4/projects.png" alt="Projects">
</div>

**Project Dashboard**

Vista detallada de un proyecto específico (Carretera Lima-Canta) con porcentaje de cumplimiento normativo, datos de telemetría LoRaWAN, lista de incidentes pendientes y responsables técnicos.

<div align="center">
  <img src="assets/images/chapter4/projects-dashboard.png" alt="Dashbpard">
</div>

**Alerts**

Gestor de alertas preventivas que notifica excesos de parámetros (material particulado, ruido, agua) e incluye un panel técnico con detalles y acciones de mitigación recomendadas.

<div align="center">
  <img src="assets/images/chapter4/alerts.png" alt="Alerts">
</div>

**Incidents**

Tablero tipo Kanban organizado por estado (Pendiente, En Progreso, Resuelto, Cerrado) para la trazabilidad y asignación de responsables en la atención de eventos ambientales.

<div align="center">
  <img src="assets/images/chapter4/incidents.png" alt="Incidents">
</div>

**History**

Gráfico de evolución temporal de indicadores (como PM10) comparados contra los límites normativos del estándar (ECA), con promedios y simulador de estados sin datos

<div align="center">
  <img src="assets/images/chapter4/projects-history.png" alt="History">
</div>

**Reports**

Módulo de generación de informes ambientales oficiales exportables en PDF con validación de firma digital y código de seguridad encriptado SHA-256.

<div align="center">
  <img src="assets/images/chapter4/reports.png" alt="Reports">
</div>

**Collaborators**

Panel de administración de usuarios y permisos (RBAC), con simulación de restricciones de acceso según el perfil técnico asignado.

<div align="center">
  <img src="assets/images/chapter4/team.png" alt="Team">
</div>

### Mock-ups Version Mobile

**Projects**

Listado vertical de concesiones viales que muestra métricas rápidas de estado ambiental (Critical, Observation, Optimal), sensores, alertas e incidentes por proyecto.
<div align="center">
  <img src="assets/images/chapter4/projects-mob.png" alt="Team">
</div>

**Project Dashboard**

Vista de detalle del proyecto (Carretera Lima–Canta) con porcentaje de cumplimiento normativo (ECA), métricas de red telemática LoRaWAN, incidentes pendientes y profesionales responsables
<div align="center">
  <img src="assets/images/chapter4/dashboard-mob.png" alt="Team">
</div>

**IoT Sensors**

Panel telemático de red con el mapa/perfil topográfico de nodos, estado de conexión de estaciones y tarjetas de monitoreo en tiempo real por variable (PM10, ruido ambiental).
<div align="center">
  <img src="assets/images/chapter4/iot-mob.png" alt="Team">
</div>

**Alerts**

Gestor móvil de alertas preventivas que notifica desviaciones críticas de parámetros con gráfico de tendencia, protocolo técnico y acciones preventivas recomendadas.

<div align="center">
  <img src="assets/images/chapter4/alert-mob.png" alt="Team">
</div>

**Environmental Incidents**

Tablero de seguimiento de eventos e incidentes ambientales con filtro por estado (Pending, In Progress, Resolved) y tarjetas para la asignación de responsables en campo.
<div align="center">
  <img src="assets/images/chapter4/env-inc-mob.png" alt="Team">
</div>

**Traceability History**

Línea de tiempo cronológica (Event Audit Trail) que detalla la trazabilidad desde la alerta inicial hasta el registro de evidencia fotográfica y la acción correctiva aplicada.

<div align="center">
  <img src="assets/images/chapter4/envi-mob.png" alt="Team">
</div>

**Indicator History**

Gráfico de evolución temporal de variables (PM10) frente a los límites normativos del ECA, acompañados de promedios, valores máximos/mínimos y certificado de monitoreo.

<div align="center">
  <img src="assets/images/chapter4/envi-mob.png" alt="Team">
</div>

**Environmental Reports**

Configuración y generación de informes oficiales de cumplimiento ambiental con opción de descarga en PDF, vista previa e historial con hash de seguridad SHA-256.
<div align="center">
  <img src="assets/images/chapter4/report-mob.png" alt="Team">
</div>

**Collaborators & Permissions**

Administración móvil de personal asignado al corredor y gestor de permisos por rol (RBAC) para el control de lectura, edición y exportación de datos.

<div align="center">
  <img src="assets/images/chapter4/team-mob.png" alt="Team">
</div>

**Subscription & Licensing**

Tarjetas de planes de suscripción (Starter Corridor y Enterprise Concession) que detallan costos, capacidades telemáticas e integración normativa.
<div align="center">
  <img src="assets/images/chapter4/sus-mob.png" alt="Team">
</div>

4.4.3. Web Applications User Flow Diagrams.

4.5. Web Applications Prototyping.

4.6. Domain-Driven Software Architecture.

La arquitectura de software de EcoRoad se construye a partir de los resultados obtenidos en el Big Picture EventStorming, que permitió comprender en profundidad los flujos clave del dominio de gestión y cumplimiento ambiental en infraestructura vial, así como las interacciones entre las empresas constructoras, supervisoras y los dispositivos IoT de campo. A partir de este análisis inicial, se desarrolló una visión más estructurada del dominio utilizando los principios de Domain-Driven Design (DDD).

En las siguientes secciones se presenta cada nivel del modelo, explicando la estructura, responsabilidades y comunicación entre los elementos que conforman la arquitectura de EcoRoad.

4.6.1. Design-Level Event Storming.

Para identificar los eventos de dominio y profundizar en el modelado táctico, se realizó una sesión de EventStorming. Esta técnica permite visualizar y comprender el flujo de eventos dentro del dominio, facilitando la identificación de los Bounded Contexts, los aggregates (agregados) como fronteras transaccionales, los comandos, eventos, políticas y vistas de lectura.

1. Commercial and Subscription Management

Este contexto gestiona todo el ciclo comercial y el modelo de negocio de doble ingreso (dual revenue) de EcoRoad. Administra el registro de las cuentas corporativas y los contratos de suscripción independientes tanto para las empresas constructoras como para las supervisoras/consultoras ambientales. Su propósito es validar el acceso financiero a la plataforma mediante planes segmentados (Base, Profesional y Enterprise), asegurando que las operaciones viales de los clientes estén debidamente respaldadas por una suscripción activa.
<div align="center">
  <img src="assets/images/chapter4/paso1.jpg" alt="Paso 4">
</div>

2. Identity and Access Management (IAM)

El Bounded Context IAM se encarga de la autenticación, autorización y gobernanza de credenciales dentro del ecosistema EcoRoad. Administra procesos críticos como el registro de usuarios corporativos, inicio de sesión y la asignación granular de permisos y roles (tales como administradores, residentes de obra o personal de fiscalización). Su objetivo es garantizar accesos seguros, confiables y alineados con las políticas de control de seguridad de la información.
<div align="center">
  <img src="assets/images/chapter4/paso2.jpg" alt="Paso 4">
</div>


3. Project and Road Site Management

Este contexto es el núcleo operativo para la planificación de la infraestructura vial. Permite registrar formalmente los proyectos de construcción y mantenimiento, configurar los tramos viales y establecer los frentes de trabajo donde se desarrollarán las operaciones. Su diseño valida de forma estricta que exista una cuenta y suscripción comercial activa antes de autorizar la creación y el despliegue lógico de cualquier nuevo proyecto de carretera.
<div align="center">
  <img src="assets/images/chapter4/paso3.jpg" alt="Paso 4">
</div>

4. Monitoring Asset and Deployment

Se encarga de la gestión del hardware de sensores IoT propios que provee el modelo HaaS (Hardware as a Service) de EcoRoad. Este contexto administra la geolocalización de los puntos de monitoreo, la habilitación de los dispositivos de campo, su asignación específica a los frentes de obra, así como su calibración y activación. Su propósito es asegurar que solo los sensores autorizados y debidamente vinculados puedan reportar datos al sistema.
<div align="center">
  <img src="assets/images/chapter4/paso4.jpg" alt="Paso 4">
</div>

5. Environmental Monitoring

Este contexto gestiona la captura y el procesamiento de la telemetría ambiental (indicadores de aire, ruido, agua y vibración) recopilada por la red de sensores IoT. Se encarga de configurar los parámetros ambientales y perfiles de umbrales normativos, permitiendo procesar tanto las mediciones automatizadas en tiempo real como los registros manuales efectuados en campo, reduciendo la dependencia de reportes que puedan ser alterados.
<div align="center">
  <img src="assets/images/chapter4/paso5.jpg" alt="Paso 4">
</div>

6. Alerting and Risk Evaluation

Funciona como el motor preventivo de la plataforma. Evalúa de manera continua las mediciones e indicadores ambientales frente a los límites y umbrales normativos establecidos. Su propósito es detectar desviaciones de manera temprana, confirmar riesgos ambientales críticos y emitir las alertas preventivas necesarias para que las empresas constructoras actúen antes de incurrir en incumplimientos legales o sanciones.
<div align="center">
  <img src="assets/images/chapter4/paso6.jpg" alt="Paso 4">
</div>

7. Incident and Remediation Management

Este contexto coordina la respuesta operativa ante incidentes ambientales detectados en las obras viales. Controla el ciclo de vida de los tickets de incidencia, la asignación de responsables y cuadrillas de campo, la ejecución de acciones correctivas (como riego de vías o instalación de barreras acústicas), la subida de evidencias verificables y el cierre formal de las incidencias.
<div align="center">
  <img src="assets/images/chapter4/paso7.jpg" alt="Paso 4">
</div>

8. Compliance and Reporting

Agrupa la consolidación de los datos históricos de monitoreo, alertas e incidentes para la generación de reportes regulatorios de cumplimiento. Su propósito es proveer a las empresas supervisoras y consultoras ambientales una herramienta neutral y basada en datos inalterables, facilitando los procesos de auditoría, reduciendo los costos de fiscalización y generando confianza mutua entre los ejecutores de la obra y los entes fiscalizadores.
<div align="center">
  <img src="assets/images/chapter4/paso8.jpg" alt="Paso 4">
</div>

4.6.2. Software Architecture Context Diagram.

En este nivel se presenta una vista de alto nivel de la arquitectura, donde el foco está en el sistema de software **EcoRoad** como una “caja negra” y en las interacciones que mantiene con sus usuarios, sus dispositivos de campo y con otros sistemas externos.

El *Context Diagram* muestra al **EcoRoad Software System** como un recuadro en el centro, rodeado por los principales actores y sistemas con los que se comunica:

* **Site Resident**: usuario interno principal (ingeniero residente o supervisor de obra) responsable de registrar proyectos viales, monitorear alertas ambientales en tiempo real, asignar acciones de remediación a las cuadrillas y autorizar el cierre de incidencias socioambientales.
* **Regulatory Auditor**: usuario externo o entidad fiscalizadora (MTC / OEFA) que accede a la plataforma para revisar expedientes de cumplimiento y validar el acatamiento normativo del Plan de Manejo Ambiental.
* **IoT Sensor Node**: dispositivo físico de campo distribuido en los frentes de obra que captura continuamente datos de telemetría (material particulado PM10/PM2.5, ruido, calidad de agua y vibraciones) y los transmite en tiempo real al sistema central.
* **Payment System (Stripe / Niubiz)**: sistema externo encargado de procesar las suscripciones B2B y los pagos asociados al uso de la plataforma SaaS y al arrendamiento del hardware IoT (modelo HaaS).
* **Google Maps API / GIS**: servicio de mapas utilizado para obtener la geolocalización, el trazado de tramos carreteros y la ubicación espacial de los nodos sensores en las obras.
* **Notification Service (SendGrid / Twilio)**: servicio de mensajería utilizado para enviar notificaciones e instructivos automáticos por correo electrónico y SMS ante desvíos de umbrales normativos ECA.

En el diagrama se representan las relaciones entre estos elementos, destacando que tanto los usuarios humanos (**Site Resident** y **Regulatory Auditor**) como los instrumentos de campo (**IoT Sensor Node**) interactúan directamente con **EcoRoad**, mientras que el sistema central se encarga de orquestar las integraciones con los servicios externos (pagos, mapas y notificaciones). Esta vista permite entender el alcance del sistema, los límites de responsabilidad y el ecosistema en el que se inserta **EcoRoad** antes de entrar a detalles de implementación.


<div align="center"><img src="assets/images/chapter4/ContextDiagram.png" alt="Software Architecture Context Diagram"></div>
<br>

4.6.3. Software Architecture Container Diagrams.

En el nivel de contenedores, la atención se desplaza desde “quién usa el sistema” hacia “cómo se organiza internamente el sistema en aplicaciones y fuentes de datos”. El *Container Diagram* muestra los elementos de alto nivel de la arquitectura de **EcoRoad**, sus responsabilidades principales y la forma en que se comunican entre sí y con los sistemas externos.

La arquitectura lógica de **EcoRoad** se estructura en los siguientes contenedores:

* **Landing Page**: aplicación web estática que presenta la propuesta de valor de **EcoRoad** (modelo híbrido HaaS/SaaS) para empresas constructoras y de conservación vial, guía a nuevos usuarios y redirige a la aplicación principal. Está desarrollada con tecnologías web estándar (HTML5, CSS3 y JavaScript) y se despliega en un entorno orientado a contenido estático.
* **Single Page Application (SPA)**: aplicación web principal, implementada en Angular, donde interactúan el **Site Resident** y el **Regulatory Auditor**. Este contenedor concentra la experiencia de usuario, las vistas y la lógica de presentación para los 8 contextos del dominio (*Commercial &amp; Subscription Management*, *Identity &amp; Access Management - IAM*, *Project &amp; Road Site Management*, *Monitoring Asset &amp; Deployment*, *Environmental Telemetry &amp; Monitoring*, *Alerting &amp; Risk Evaluation*, *Incident &amp; Remediation Management*, y *Compliance &amp; Audit Reporting*).
* **API Application**: backend implementado con Spring Boot, que expone una API REST, gestiona la ingesta continua de telemetría IoT y encapsula la lógica de negocio, reglas de evaluación de umbrales normativos ECA y orquestación de procesos. Este contenedor agrupa los módulos backend por contexto (*Subscription Backend*, *IAM Backend*, *Project Backend*, *Asset Management Backend*, *Telemetry Backend*, *Alert Engine Backend*, *Incident Backend* y *Compliance Reporting Backend*).
* **Database**: base de datos relacional (PostgreSQL / MySQL), donde se persiste la información estructurada del sistema: proyectos viales, tramos carreteros, nodos sensores, mediciones telemétricas (material particulado PM10/PM2.5, ruido, agua y vibraciones), reglas de alerta ECA, tickets de incidencias, evidencias fotográficas, expedientes de cumplimiento, cuentas de usuario y suscripciones.

En el diagrama se observa que:

* Los usuarios humanos (**Site Resident** y **Regulatory Auditor**) acceden primero a la **Landing Page**, la cual redirige a la **SPA** tras el proceso de autenticación.
* Los dispositivos físicos **IoT Sensor Node** transmiten lecturas telemétricas en tiempo real directamente hacia la **API Application** mediante protocolos de comunicación como MQTT o HTTPS.
* La **SPA** se comunica exclusivamente con la **API Application** mediante peticiones HTTP/HTTPS con mensajes JSON, siguiendo un estilo REST.
* La **API Application** persiste y consulta datos en la **Database** mediante JDBC y mapeo objeto–relacional (JPA/Hibernate).
* Tanto la **SPA** como la **API Application** interactúan con los sistemas externos: el **Payment System (Stripe / Niubiz)** para el cobro de suscripciones y arrendamiento de hardware, la **Google Maps API** para la geolocalización y trazado espacial de tramos viales, y el **Notification Service (SendGrid / Twilio)** para el envío automático de notificaciones de alerta por correo electrónico y SMS.

Esta vista resume la distribución de responsabilidades entre las capas de presentación (Landing Page y SPA), lógica e ingesta (API Application) y persistencia (Database), detallando sus tecnologías clave. A través de flujos unidireccionales y bidireccionales, el diagrama delimita el alcance de EcoRoad, mostrando cómo interactúan los usuarios y sensores, y cómo el sistema central orquesta las integraciones externas de pagos, mapas, notificaciones y fiscalización.
<div align="center"><img src="assets/images/chapter4/ContainerDiagram.png" alt="Incident & Remediation Management Context"></div>
<br>

4.6.4. Software Architecture Components Diagrams.

En el nivel de componentes se detalla la descomposición interna de los contenedores, mostrando los bloques estructurales que conforman cada uno y las relaciones entre ellos. Dado que la **Single Page Application** y la **Database** son descritas mediante diagramas de clases frontend y de base de datos, en esta sección se pone especial énfasis en el contenedor **API Application**, donde reside la mayor parte de la lógica de negocio y la ingesta de telemetría ambiental.

El *Component Diagram* de la **API Application** agrupa la arquitectura interna siguiendo los Bounded Contexts definidos en el dominio de **EcoRoad**. Cada módulo backend representa un componente principal dentro del contenedor:

* **Subscription Backend**: administra el modelo comercial de doble ingreso (dual revenue), gestionando los contratos de suscripción SaaS (planes Starter, Professional y Enterprise) y los acuerdos HaaS de alquiler de sensores IoT. Se integra con el **Payment System (Stripe / Niubiz)** para el procesamiento de cobros y facturación.
* **IAM Backend**: se encarga de la autenticación de usuarios, emisión y validación de tokens JWT, gestión de cuentas corporativas, roles (RBAC) y control de permisos de acceso a la plataforma.
* **Project Backend**: gestiona el alta de proyectos de infraestructura vial, la sectorización de tramos carreteros y el establecimiento de frentes de obra.
* **Asset Management Backend**: administra el inventario de dispositivos **IoT Sensor Node**, su estado operativo, la calibración de hardware y su vinculación lógica a tramos viales específicos.
* **Telemetry Backend**: gestiona la ingesta de alto rendimiento y el procesamiento en tiempo real de las lecturas telemétricas (material particulado PM10/PM2.5, ruido, calidad de agua y vibraciones) enviadas por los sensores de campo.
* **Alert Engine Backend**: evalúa continuamente las mediciones ambientales frente a los Estándares de Calidad Ambiental (ECA) para detectar desvíos e interactúa con el **Notification Service (SendGrid / Twilio)** para despachar avisos automáticos por correo electrónico y SMS.
* **Incident Backend**: coordina el flujo de trabajo de tickets de incidencia socioambiental, la asignación de tareas a cuadrillas, la carga de evidencias fotográficas en campo y la autorización de cierre.
* **Compliance Reporting Backend**: consolida el historial inmutable de telemetría, alertas e incidencias para empaquetar expedientes digitales de cumplimiento en PDF presentables ante auditorías regulatorias (MTC / OEFA).
* **Shared Backend**: provee componentes compartidos, utilidades, clases base auditables, eventos y mecanismos de infraestructura transversales reutilizados por los demás módulos backend.

En el diagrama se refleja cómo:

* La **SPA** consume los servicios expuestos por cada módulo backend a través de la **API Application**, utilizando endpoints REST específicos por contexto.
* Los dispositivos físicos **IoT Sensor Node** transmiten lecturas en tiempo real directamente hacia el **Telemetry Backend** mediante protocolos de comunicación como MQTT o HTTPS.
* Cada módulo backend accede a la **Database** para leer y escribir la información correspondiente a su contexto (por ejemplo, Telemetry Backend a tablas de mediciones, Incident Backend a tablas de tickets y evidencias, etc.).
* Algunos módulos se integran con sistemas externos: **Subscription Backend** con el sistema de pagos (Stripe / Niubiz), **Project Backend** y **Asset Management Backend** con la API de mapas (Google Maps API), e **IAM Backend** y **Alert Engine Backend** con el servicio de notificaciones (SendGrid / Twilio).
* Todos los módulos backend reutilizan capacidades comunes provistas por el **Shared Backend**, lo que favorsce la consistencia, la reutilización y la reducción de duplicación de código.

En conclusión, esta vista de componentes permite transparentar la organización interna del backend de **EcoRoad**, evidenciando la separación modular de responsabilidades según cada *Bounded Context*. Al estructurar de forma desacoplada la ingesta telemétrica, la evaluación de umbrales ECA y la gestión de incidencias, este diagrama sirve como puente entre la visión de contenedores de alto nivel y el diseño detallado de clases y persistencia del sistema.
<div align="center"><img src="assets/images/chapter4/ComponentDiagram.png" alt="Incident & Remediation Management Context"></div>
<br>



## 4.7. Software Object-Oriented Design.
<a id="4-7-software-object-oriented-design"></a>

### 4.7.1. Class Diagrams.
<a id="4-7-1-class-diagrams"></a>
Se centra en la definición de diagramas de clases, la interacción entre objetos y la aplicación de principios.

### Bounded Context 1 - Suscriptions and Payment:
![Class Diagram - EcoRoad](assets/images/chapter4/EcoRoad-CD1.png)
### Bounded Context 2 - Identity and Access Management:
![Class Diagram - EcoRoad](assets/images/chapter4/EcoRoad-CD2.png)
### Bounded Context 3 - Project and Road Site Management:
![Class Diagram - EcoRoad](assets/images/chapter4/EcoRoad-CD3.png)
### Bounded Context 4 - Monitoring Asset and Deployment:
![Class Diagram - EcoRoad](assets/images/chapter4/EcoRoad-CD4.png)
### Bounded Context 5 - Environmental Monitoring:
![Class Diagram - EcoRoad](assets/images/chapter4/EcoRoad-CD5.png)
### Bounded Context 6 - Alerting and Risk Evaluation:
![Class Diagram - EcoRoad](assets/images/chapter4/EcoRoad-CD6.png)
### Bounded Context 7 - Incident and Remediation Management:
![Class Diagram - EcoRoad](assets/images/chapter4/EcoRoad-CD7.png)
### Bounded Context 8 - Compliance and Reporting:
![Class Diagram - EcoRoad](assets/images/chapter4/EcoRoad-CD8.png)




## 4.8. Database Design.
<a id="4-8-database-design"></a>

### 4.8.1. Database Diagrams.
<a id="4-8-1-database-diagrams"></a>

### Bounded Context 1 - Suscriptions and Payment:
![Database Diagram- EcoRoad](assets/images/chapter4/DBDiagram1.jpeg)
### Bounded Context 2 - Identity and Access Management:
![Database Diagram - EcoRoad](assets/images/chapter4/DBDiagram2.jpeg)
### Bounded Context 3 - Project and Road Site Management:
![Database Diagram- EcoRoad](assets/images/chapter4/DBDiagram3.jpeg)
### Bounded Context 4 - Monitoring Asset and Deployment:
![Database Diagram- EcoRoad](assets/images/chapter4/DBDiagram4.jpeg)
### Bounded Context 5 - Environmental Monitoring:
![Database Diagram - EcoRoad](assets/images/chapter4/DBDiagram5.jpeg)
### Bounded Context 6 - Alerting and Risk Evaluation:
![Database Diagram - EcoRoad](assets/images/chapter4/DBDiagram6.png)
### Bounded Context 7 - Incident and Remediation Management:
![Database Diagram - EcoRoad](assets/images/chapter4/DBDiagram7.jpeg)
### Bounded Context 8 - Compliance and Reporting:
![Database Diagram - EcoRoad](assets/images/chapter4/DBDiagram8.jpeg)

# Product Implementation, Validation & Deployment
<a id="product-implementation-validation-deployment"></a>

## 5.1. Software Configuration Management
<a id="5-1-software-configuration-management"></a>

En esta sección el equipo establece las decisiones y convenciones que permiten mantener la consistencia durante el ciclo de vida de los productos digitales de EcoRoad: Landing Page, Frontend Web Application y Web Services.

### 5.1.1. Software Development Environment Configuration
<a id="5-1-1-software-development-environment-configuration"></a>

#### Project Management
Para la coordinación del proyecto y el seguimiento del trabajo colaborativo se utilizaron plataformas de comunicación, almacenamiento y gestión ágil. El código fuente del informe, la Landing Page y la Web Application se centralizó en una organización pública de GitHub. Las reuniones virtuales del equipo y las coordinaciones diarias se realizaron mediante Discord y WhatsApp, mientras que la planificación y asignación de tareas de cada Sprint se gestionó en Trello.

* **Coordinación de código y repositorios:** GitHub — https://github.com/
* **Reuniones virtuales y syncs:** Discord — https://discord.com/
* **Comunicación diaria:** WhatsApp — https://www.whatsapp.com/
* **Organización y seguimiento de tareas (Sprint Board):** Trello — https://trello.com/

#### Requirements Management
Durante el análisis y la especificación de requisitos se empleó UXPressia para diseñar los User Personas, Empathy Maps, Journey Maps e Impact Maps. Se utilizó Miro para la construcción de los tableros de EventStorming.

* **User Personas, Empathy Maps, Journey Maps e Impact Map:** UXPressia — https://uxpressia.com/
* **EventStorming:** Miro — https://miro.com/
* **Gestión de User Stories y Sprint Backlog:** Trello — https://trello.com/

#### Product UX/UI Design
Para la concepción visual de la Landing Page y de la Web Application, el equipo empleó Figma. Se elaboraron wireframes, mock-ups y prototipos para validar la estructura visual, la paleta de colores y la disposición de las secciones antes de su implementación.

* **Wireframes, Mock-ups y Prototypes:** Figma — https://www.figma.com/

#### Software Development
La Landing Page se implementó con HTML5, CSS3 y JavaScript. La Frontend Web Application se implementa con Vue 3, Vue Router y la biblioteca de componentes PrimeVue, utilizando Vite como herramienta de construcción y Node.js como entorno de ejecución para las tareas de desarrollo y para la Fake API utilizada durante el Sprint 2. Los Web Services se implementarán con ASP.NET Core y Entity Framework Core en C#.

* **IDEs y editores:** Visual Studio Code — https://code.visualstudio.com/ ; WebStorm — https://www.jetbrains.com/webstorm/ ; JetBrains Rider (para C#) — https://www.jetbrains.com/rider/
* **Gestor de IDEs:** JetBrains Toolbox — https://www.jetbrains.com/toolbox-app/
* **Entorno de ejecución:** Node.js LTS — https://nodejs.org/
* **Framework y bibliotecas frontend:** Vue 3 — https://vuejs.org/ ; PrimeVue — https://primevue.org/ ; Vite — https://vite.dev/
* **Framework backend:** ASP.NET Core / .NET SDK — https://dotnet.microsoft.com/download
* **Control de versiones:** Git — https://git-scm.com/downloads

#### Software Documentation
El informe del proyecto se redacta en archivos Markdown (.md) dentro del repositorio del informe en GitHub, siguiendo el flujo de trabajo GitFlow. La documentación de los Web Services se elaborará con OpenAPI Specification vía Swagger.

* **Informe:** Markdown en GitHub — https://github.com/Aplicaciones-Web-1ASI0730-2620-8130/Grupo1---Report
* **Documentación de Web Services:** Swagger / OpenAPI — https://swagger.io/

#### Software Deployment
La Landing Page se publica en GitHub Pages y la Frontend Web Application en Vercel, ambas con despliegue continuo desde su repositorio de GitHub.

* **Landing Page:** GitHub Pages — https://pages.github.com/
* **Frontend Web Application:** Vercel — https://vercel.com/

### 5.1.2. Source Code Management
<a id="5-1-2-source-code-management"></a>

El equipo gestiona el código fuente mediante **GitHub** como plataforma de control de versiones, organizado bajo una organización pública que agrupa los repositorios de cada producto digital del proyecto.

| Producto | Repositorio | Despliegue |
| :--- | :--- | :--- |
| Project Report | https://github.com/Aplicaciones-Web-1ASI0730-2620-8130/Grupo1---Report | — |
| Landing Page | https://github.com/Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | https://aplicaciones-web-1asi0730-2620-8130.github.io/EcoRoad-LandingPage/ |
| Frontend Web Application | https://github.com/Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | https://ecoroad-frontend-ddli-peach.vercel.app/ |
| Web Services | Se creará en el Sprint 3 | Se desplegará en el Sprint 3 |

#### GitFlow Workflow

El equipo implementa **GitFlow** como modelo de ramificación para gestionar el ciclo de vida del código. Las ramas definidas son:

- **`main`**: rama principal que contiene la versión estable publicada. Solo recibe merges desde `release` o `hotfix`.
- **`develop`**: rama de integración donde se consolidan los features completados antes de pasar a producción.
- **Feature branches**: se crean desde `develop` y se integran de vuelta a `develop` mediante Pull Request. Convenciones:
  - Project Report: `featureNN/Chapter-<número>-<nombre-del-capítulo>`, por ejemplo `feature50/Chapter-V-product-implementation-validation-and-deployment`.
  - Landing Page: `feature/<nombre-sección>`, por ejemplo `feature/hero-section`.
  - Frontend Web Application: `ft-<Bounded-Context>`, una rama por bounded context, por ejemplo `ft-Project-and-Road-Site-Management` o `ft-Incident-and-Remediation-Management`.
- **`release/<versión>`**: rama de preparación de una nueva versión. Se crea desde `develop` al cierre del Sprint. Ejemplo: `release/1.0.0`.
- **`hotfix/<descripción>`**: rama para correcciones críticas en producción. Se crea desde `main`. Ejemplo: `hotfix/fix-cta-redirect`.

#### Semantic Versioning

Para el nombramiento de versiones se aplica **Semantic Versioning 2.0.0** con el formato `MAJOR.MINOR.PATCH`:
- `MAJOR`: cambios incompatibles con versiones anteriores.
- `MINOR`: nuevas funcionalidades compatibles con versiones anteriores.
- `PATCH`: correcciones de errores compatibles con versiones anteriores.

| Producto | Sprint 1 | Sprint 2 |
| :--- | :--- | :--- |
| Landing Page | `v1.0.0` | `v1.1.0` (enlace del call-to-action de inicio de sesión hacia la Web Application) |
| Frontend Web Application | — | `v1.0.0` |

#### Conventional Commits

Para los mensajes de commit, el equipo aplica la especificación **Conventional Commits**, usando el formato:

```
<type>(<scope>): <description>
```

Los tipos permitidos son:
- `feat`: nueva funcionalidad.
- `fix`: corrección de error.
- `docs`: cambios en documentación.
- `style`: cambios de formato que no afectan la lógica.
- `refactor`: reestructuración de código sin cambio funcional.
- `chore`: tareas de mantenimiento (dependencias, configuración).
- `test`: adición o modificación de pruebas.

Ejemplos aplicados al proyecto:
```
docs(chapter5): add sprint 2 development evidence
feat(projects): manage road sections and work fronts
feat(incidents): add incident lifecycle and remediation board
fix(deploy): serve demo API and authentication on Vercel
feat(landing): link sign-in to deployed frontend
```

### 5.1.3. Source Code Style Guide & Conventions
<a id="5-1-3-source-code-style-guide-conventions"></a>

El equipo adopta las siguientes guías de estilo y convenciones de codificación para garantizar uniformidad y legibilidad en todos los productos. Toda nomenclatura en el código se redacta en **inglés**.

#### HTML5 & CSS3 (Landing Page y templates de la Web Application)
- Se aplica la guía **W3Schools HTML Style Guide and Coding Conventions**: estructura semántica, indentación con 2 espacios, elementos y atributos en minúsculas y uso de comillas dobles.
- Se aplica la guía **Google HTML/CSS Style Guide**: nombres de clases en `kebab-case`, se evita el uso de selectores de ID en CSS y se priorizan las propiedades abreviadas.
- El lenguaje de diseño se basa en **Material Design**.

#### JavaScript & Vue (Frontend Web Application)
- Se aplica la **Vue Style Guide** oficial: componentes con nombres multi-palabra, archivos de componentes en `kebab-case` (por ejemplo `project-list.vue`, `incident-board.vue`) y props declaradas de forma detallada.
- Se aplican **Google JavaScript Style Guide**, **MDN JavaScript guidelines** y **W3C JavaScript Style Guide**: `camelCase` para variables y funciones, `PascalCase` para clases, `const`/`let` en lugar de `var` y módulos ES.
- El código se organiza por bounded context y por capas: `domain`, `application`, `infrastructure` y `presentation` (por ejemplo `src/projects/presentation/views/project-list.vue`).
- Los componentes de interfaz se construyen con **PrimeVue**.

#### C# & ASP.NET Core (Web Services)
- Se aplican las **C# Coding Conventions** de Microsoft: `PascalCase` para clases, métodos y propiedades públicas; `camelCase` para parámetros y variables locales; prefijo `I` para interfaces.
- Se aplican las **Microsoft ASP.NET Core Coding Guidelines**: controladores con sufijo `Controller`, rutas REST en minúsculas y en plural (por ejemplo `/api/v1/projects`) e inyección de dependencias por constructor.

#### Gherkin (Acceptance Criteria)
- Se aplican las **Gherkin Conventions for Readable Specifications**: un solo nivel de indentación para `Given/When/Then`, escenarios redactados en tercera persona y en tiempo presente, sin referencias a detalles de interfaz.

### 5.1.4. Software Deployment Configuration
<a id="5-1-4-software-deployment-configuration"></a>

En esta sección se describe la configuración de despliegue de los productos digitales publicados hasta el Sprint 2.

#### Landing Page — GitHub Pages

El Landing Page de EcoRoad se despliega como sitio web estático mediante **GitHub Pages**, directamente desde su repositorio.

1. Asegurarse de que la rama `main` contiene los archivos del Landing Page (`index.html`, carpetas `css/`, `js/`, `assets/`).
2. Ingresar al repositorio en GitHub y navegar a **Settings > Pages**.
3. En la sección **Source**, seleccionar la rama `main` y la carpeta `/ (root)`.
4. Hacer clic en **Save**. GitHub Pages genera automáticamente la URL de despliegue.
5. Verificar el sitio desplegado en https://aplicaciones-web-1asi0730-2620-8130.github.io/EcoRoad-LandingPage/

Cualquier push a la rama `main` actualiza automáticamente el sitio desplegado.

#### Frontend Web Application — Vercel

La Web Application de EcoRoad (Vue 3 + Vite) se despliega en **Vercel**, conectado al repositorio `EcoRoad-FrontEnd`.

1. Ingresar a https://vercel.com/ con la cuenta de GitHub del equipo y seleccionar **Add New > Project**.
2. Importar el repositorio `Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd`.
3. Configurar el proyecto: **Root Directory** `./`, **Build Command** `npm run build` y **Output Directory** `dist`.
4. El archivo `vercel.json` del repositorio define las reglas de *rewrite*: las rutas `/api/*` se dirigen a la función serverless `api/index.js`, que expone la Fake API, y el resto de rutas se dirige a `index.html` para que Vue Router resuelva la navegación de la SPA.
5. Hacer clic en **Deploy**. Vercel construye la aplicación y publica la URL https://ecoroad-frontend-ddli-peach.vercel.app/
6. Cada push a la rama configurada genera un nuevo despliegue de forma automática.

## 5.2. Landing Page, Services & Applications Implementation
<a id="5-2-landing-page-services-applications-implementation"></a>

### 5.2.1. Sprint 1
<a id="5-2-1-sprint-1"></a>

#### 5.2.1.1. Sprint Planning 1
<a id="5-2-1-1-sprint-planning-1"></a>

El Sprint 1 se planificó con el propósito de implementar y desplegar la primera versión del Landing Page de EcoRoad. A continuación se resume la reunión de Sprint Planning.

| Sprint # | Sprint 1 |
| :--- | :--- |
| **Sprint Planning Background** | |
| Date | 2026-09-16 |
| Time | 07:00 PM |
| Location | Reunión virtual vía Discord |
| Prepared By | Pancorbo Amorós, Italo Raul |
| Attendees | Taza Curay, Eduardo Miguel / Roman Lopez, Miguel Angel Junior / Guillen Chavez, Eduardo Martín / Salcedo Muñoz, Andy Alfredo Hipolito / Pancorbo Amorós, Italo Raul |
| Sprint 0 Review Summary | Al ser el primer Sprint del proyecto, no existe un Sprint anterior. Se parte del Product Backlog inicial y de los artefactos de diseño elaborados en los capítulos previos. |
| Sprint 0 Retrospective Summary | El equipo acordó establecer estándares de trabajo desde el inicio: aplicar GitFlow, Conventional Commits y dividir las responsabilidades de implementación del Landing Page por secciones entre los miembros. |
| **Sprint Goal & User Stories** | |
| Sprint 1 Goal | Our focus is on delivering a fully deployed and navigable Landing Page for EcoRoad. We believe it delivers a clear understanding of the value proposition to potential clients from both target segments (road construction companies and road maintenance and rehabilitation companies). This will be confirmed when visitors can navigate all sections of the Landing Page, identify the environmental monitoring features, compare subscription plans, and access the call-to-action buttons for each segment. |
| Sprint 1 Velocity | 20 Story Points |
| Sum of Story Points | 19 Story Points |

#### 5.2.1.2. Aspect Leaders and Collaborators
<a id="5-2-1-2-aspect-leaders-and-collaborators"></a>

Para el Sprint 1, los aspectos de trabajo se organizan en torno a las secciones del Landing Page y la configuración del entorno de desarrollo y despliegue. Cada aspecto cuenta con un líder responsable de su implementación y uno o más colaboradores de apoyo.

| Team Member | GitHub Username | Hero & Navbar | Plans Section | Features Section | Contact Form | Deployment & Config |
|:---|:---|:---:|:---:|:---:|:---:|:---:|
| Taza Curay, Eduardo Miguel | Edutaza10 | L | C | | | C |
| Roman Lopez, Miguel Angel Junior | MiguelRomn | C | | L | C | C |
| Guillen Chavez, Eduardo Martín | Eduardox30-wq | C | | C | L | |
| Salcedo Muñoz, Andy Alfredo Hipolito | Andy777sdw | | L | C | | C |
| Pancorbo Amorós, Italo Raul | pancorboitalo-design | | C | C | | L |

*L = Leader | C = Collaborator*

#### 5.2.1.3. Sprint Backlog 1
<a id="5-2-1-3-sprint-backlog-1"></a>

El objetivo principal de este Sprint es implementar y desplegar la primera versión del Landing Page de EcoRoad, cubriendo las secciones de presentación de valor, funcionalidades, planes de suscripción, testimonios y formulario de contacto, con call-to-action diferenciados para cada segmento objetivo.

<img src="assets/images/trello.jpeg" alt="Sprint Board - Sprint 1">

[Tablero de Trello: Organización del Sprint - EcoRoad](https://trello.com/invite/b/6ab0928cab1e6c824069d8ae/ATTI8217aefaf5493c7dc99f935bc7566209F12E82AE/sprint-ecoroad)

| US / TS / Task ID | Título | Descripción de Tarea | Estimación (Horas) | Integrante Asignado | Estado |
| :--- | :--- | :--- | :---: | :--- | :---: |
| **US001 / CC01** | Header y Navbar Responsivos | Maquetación y estilos responsive del encabezado y menú de navegación. | 4 | Pancorbo Amorós, Italo Raul | Done |
| **US001 / CC02** | Sección Hero & About Us | Maquetación visual de la sección principal y presentación de la empresa. | 4 | Pancorbo Amorós, Italo Raul | Done |
| **US002 / CC03** | Sección de Servicios y Producto | Maquetación de tarjetas informativas con las funcionalidades del SaaS. | 3 | Salcedo Muñoz, Andy Alfredo Hipolito | Done |
| **US003 / CC04** | Sección de Contacto | Maquetación de la sección informativa de canales de comunicación. | 2 | Taza Curay, Eduardo Miguel | Done |
| **US004 / CC05** | Formulario de Contacto UI | Desarrollo de la interfaz del formulario y validaciones en tiempo real. | 3 | Taza Curay, Eduardo Miguel | Done |
| **TS001 / CC06** | Footer & Enlaces Sociales | Maquetación del pie de página y enlaces a redes de la plataforma. | 2 | Roman Lopez, Miguel Angel Junior | Done |
| **TS001 / CC07** | Despliegue en GitHub Pages | Configuración del despliegue continuo desde la rama `main`. | 2 | Roman Lopez, Miguel Angel Junior | Done |
| **DOC01** | Informe Capítulo I | Introducción, problema, objetivos, justificación y restricciones. | 5 | Pancorbo Amorós, Italo Raul | Done |
| **DOC02** | Informe Capítulo II | Análisis del dominio, entrevistas, User Personas, Empathy Maps. | 6 | Salcedo Muñoz, Andy Alfredo Hipolito | Done |
| **DOC03** | Informe Capítulo III | Impact Mapping, User Stories y Product Backlog. | 8 | Guillen Chavez, Eduardo Martín / Taza Curay, Eduardo Miguel | Done |
| **DOC04** | Informe Capítulo IV | Arquitectura de Software, Domain-Driven Design y diagramas C4. | 6 | Roman Lopez, Miguel Angel Junior | Done |
| **DOC05** | Informe Capítulo V | Configuration Management, Sprint Planning 1 y evidencias de Sprint. | 5 | Guillen Chavez, Eduardo Martín | Done |

#### 5.2.1.4. Development Evidence for Sprint Review
<a id="5-2-1-4-development-evidence-for-sprint-review"></a>

En esta sección se presentan las evidencias correspondientes al desarrollo realizado durante el Sprint 1 del proyecto EcoRoad. Durante este Sprint, el equipo se enfocó en la implementación de la Landing Page, considerando la estructura visual, la navegación, la presentación de la propuesta de valor, los beneficios, las funcionalidades, los planes de suscripción, el equipo de trabajo y los elementos de contacto. Asimismo, se adaptó la interfaz a diferentes dispositivos, se incorporó un selector de idioma inglés/español y se publicó la Landing Page mediante GitHub Pages.

**Repository:** https://github.com/Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage

**Deployed Landing Page:** https://aplicaciones-web-1asi0730-2620-8130.github.io/EcoRoad-LandingPage/

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| --- | --- | --- | --- | --- | --- |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | d4db12f | feat: implement EcoRoad landing page | Implementación inicial de la Landing Page de EcoRoad, incluyendo su estructura principal, navegación y secciones informativas. | 19/09/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | ea5e78f | fix: rename index file for GitHub Pages | Renombrado del archivo principal a `index.html` para su publicación en GitHub Pages. | 19/09/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | 910f5d4 | fix: improve EcoRoad footer layout | Mejora de la estructura del footer: módulos, marco regulatorio, información de contacto y enlaces adicionales. | 19/09/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | 51b5e02 | feat: add EcoRoad call to action section | Incorporación del call-to-action para solicitar demostraciones o contactar con especialistas. | 19/09/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | 2525e7f | feat: improve responsive design for mobile devices | Adaptación de la Landing Page para su correcta visualización en computadoras, tablets y dispositivos móviles. | 19/09/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | f37feac | feat: add English and Spanish language switcher | Incorporación del selector de idioma inglés/español (i18n). | 19/09/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | 0fb8717 | Add team member profiles | Incorporación de los perfiles de los integrantes del equipo. | 20/09/2026 |

#### 5.2.1.5. Execution Evidence for Sprint Review
<a id="5-2-1-5-execution-evidence-for-sprint-review"></a>

Durante el presente Sprint se logró implementar y desplegar una primera versión funcional de la Landing Page de EcoRoad, orientada a presentar la propuesta de valor de la solución, sus principales funcionalidades, beneficios y planes de suscripción.

La Landing Page fue desarrollada utilizando HTML, CSS y JavaScript, incorporando una estructura responsive que permite su correcta visualización tanto en computadoras como en dispositivos móviles. Asimismo, se implementaron diferentes componentes interactivos que mejoran la experiencia de navegación del usuario.

**Resumen de logros**

- **Implementación de la Landing Page:** se desarrolló una primera versión funcional de EcoRoad, presentando de manera clara su propuesta de valor orientada al monitoreo y la gestión ambiental en proyectos de infraestructura vial.
- **Presentación de soluciones y beneficios:** se incorporaron secciones que muestran las principales soluciones de monitoreo ambiental, así como beneficios relacionados con reducción de riesgos, automatización de auditorías y trazabilidad georreferenciada.
- **Presentación de funcionalidades y modelo SaaS:** se implementaron secciones para mostrar funcionalidades como dashboards georreferenciados, alertas ambientales, trazabilidad de evidencias y generación de reportes, además de los planes de suscripción de la plataforma.
- **Secciones de equipo y contacto:** se añadieron las secciones de presentación del equipo y call-to-action, permitiendo al usuario conocer a los integrantes del proyecto y acceder a opciones de contacto o solicitud de demostración.
- **Diseño responsive e internacionalización:** la Landing Page fue adaptada para computadoras, tablets y smartphones, e incorpora un selector de idioma que permite alternar el contenido principal entre inglés y español.
- **Despliegue mediante GitHub Pages:** la solución fue publicada en un entorno web público, permitiendo validar su funcionamiento desde distintos dispositivos.

Video de demostración y navegación: [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241d483_upc_edu_pe/IQAkn3u2kvFiTqMHYbNb0IjtAX7jKxhOE-uMBPIxo2_Q5Ys?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Aga9p0)

Screenshot de la implementación:

<img src="assets/images/chapter5/Landing page .png" alt="Landing Page EcoRoad - Sprint 1">

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
<a id="5-2-1-6-services-documentation-evidence-for-sprint-review"></a>

En este Sprint no se desarrollaron endpoints REST ni Web Services propios, debido a que el alcance estuvo enfocado en la implementación del Landing Page con HTML, CSS y JavaScript. Por ello, no existe documentación OpenAPI asociada a este Sprint. Se registra a continuación el recurso publicado y el repositorio que contiene su código fuente.

| Recurso | Acción implementada | HTTP | URL | Repositorio |
| :--- | :--- | :---: | :--- | :--- |
| Landing Page | Vista inicial y navegación de EcoRoad | GET | https://aplicaciones-web-1asi0730-2620-8130.github.io/EcoRoad-LandingPage/ | https://github.com/Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage |

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
<a id="5-2-1-7-software-deployment-evidence-for-sprint-review"></a>

Durante el Sprint 1 el despliegue se centró en la publicación del Landing Page como sitio web estático en GitHub Pages. Las actividades realizadas fueron:

1. **Creación del repositorio** `EcoRoad-LandingPage` dentro de la organización pública `Aplicaciones-Web-1ASI0730-2620-8130`.
2. **Preparación de la estructura del proyecto:** el archivo principal se renombró a `index.html` (commit `ea5e78f`) para que GitHub Pages lo reconozca como página de inicio.
3. **Configuración de GitHub Pages:** en **Settings > Pages** se seleccionó como origen la rama `main` y la carpeta `/ (root)`.
4. **Verificación del despliegue:** se comprobó el acceso al sitio publicado en https://aplicaciones-web-1asi0730-2620-8130.github.io/EcoRoad-LandingPage/ desde navegadores de escritorio y móviles.

> **[Pendiente: insertar captura de Settings > Pages del repositorio EcoRoad-LandingPage y captura del sitio publicado.]**

#### 5.2.1.8. Team Collaboration Insights during Sprint
<a id="5-2-1-8-team-collaboration-insights-during-sprint"></a>

Durante el Sprint 1 el trabajo de implementación del Landing Page y de elaboración del informe se distribuyó entre los integrantes según la matriz de Aspect Leaders and Collaborators. La integración de los aportes al informe se realizó mediante Pull Requests desde las ramas de cada capítulo hacia la rama `develop`, siguiendo GitFlow, y la coordinación técnica se mantuvo a través de Discord y WhatsApp. A continuación se presentan los analíticos de colaboración de GitHub.

**Analíticos de GitHub — Report**

![commits-report](assets/images/commits-report.jpeg)

**Analíticos de GitHub — Landing Page**

![commits-landing](assets/images/commits-landing.jpeg)

| Integrante | Usuario GitHub | Commits (Report) |
|---|---|---|
| Guillen Chavez, Eduardo Martín | Eduardox30-wq | 9 |
| Pancorbo Amorós, Italo Raul | pancorboitalo-design | 66 |
| Roman Lopez, Miguel Angel Junior | MiguelRomn | 0 |
| Taza Curay, Eduardo Miguel | Edutaza10 | 11 |
| Salcedo Muñoz, Andy Alfredo Hipolito | Andy777sdw | 11 |

### 5.2.2. Sprint 2
<a id="5-2-2-sprint-2"></a>

#### 5.2.2.1. Sprint Planning 2
<a id="5-2-2-1-sprint-planning-2"></a>

El Sprint 2 se planificó con el propósito de implementar y desplegar la primera versión de la Frontend Web Application de EcoRoad, cubriendo los ocho bounded contexts del dominio, y de actualizar el Landing Page para que su call-to-action dirija a la Web Application desplegada. A continuación se resume la reunión de Sprint Planning.

| Sprint # | Sprint 2 |
| :--- | :--- |
| **Sprint Planning Background** | |
| Date | 2026-10-08 |
| Time | 08:00 PM |
| Location | Reunión virtual vía Discord |
| Prepared By | Pancorbo Amorós, Italo Raul |
| Attendees | Taza Curay, Eduardo Miguel / Roman Lopez, Miguel Angel Junior / Guillen Chavez, Eduardo Martín / Salcedo Muñoz, Andy Alfredo Hipolito / Pancorbo Amorós, Italo Raul |
| Sprint 1 Review Summary | Durante el Sprint 1 se entregó la Landing Page completa y responsive de EcoRoad desplegada en GitHub Pages, con selector de idioma inglés/español, junto con la documentación técnica de los Capítulos I al V del informe. |
| Sprint 1 Retrospective Summary | El equipo mantuvo una sólida coordinación. Se identificó la necesidad de estandarizar las convenciones de arquitectura en Vue, definir una estructura uniforme por bounded context (domain, application, infrastructure, presentation), organizar la API simulada y sus relaciones de datos, y unificar el flujo GitFlow mediante nombres de ramas estandarizados por bounded context. |
| **Sprint Goal & User Stories** | |
| Sprint 2 Goal | Our focus is on delivering the first version of the EcoRoad Web Application, so that road construction and road maintenance companies can register their road projects, deploy monitoring points and IoT sensors, follow environmental indicators and alerts, manage incidents until their closure and generate compliance reports. We believe it delivers centralized and traceable visibility of environmental compliance to environmental engineers, site directors and project managers of both target segments. This will be confirmed when a user, coming from the Landing Page call-to-action, signs in to the deployed Web Application, registers a road project with its sections, reviews the environmental dashboard and the generated alerts, takes an incident from "Pendiente" to "Cerrada" with registered evidence, and generates a compliance report for a selected period. |
| Sprint 2 Velocity | 75 Story Points |
| Sum of Story Points | 72 Story Points |

#### 5.2.2.2. Aspect Leaders and Collaborators
<a id="5-2-2-2-aspect-leaders-and-collaborators"></a>

Para el Sprint 2, los aspectos de trabajo corresponden a los ocho bounded contexts implementados en la Frontend Web Application, más la actualización y el despliegue del Landing Page y de la Web Application. Cada aspecto cuenta con un líder responsable y colaboradores de apoyo.

| Team Member | GitHub Username | Commercial & Subscription | IAM | Project & Road Site | Monitoring Asset & Deployment | Environmental Monitoring | Alerting & Risk Evaluation | Incident & Remediation | Compliance & Reporting | Landing Page & Deployment |
|:---|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Taza Curay, Eduardo Miguel | Edutaza10 | | | L | L | | | | C | |
| Roman Lopez, Miguel Angel Junior | MiguelRomn | L | L | | | | | C | | C |
| Guillen Chavez, Eduardo Martín | Eduardox30-wq | | | | C | L | L | | | |
| Salcedo Muñoz, Andy Alfredo Hipolito | Andy777sdw | | C | | L | | | L | | |
| Pancorbo Amorós, Italo Raul | pancorboitalo-design | C | | L | | C | | | L | L |

*L = Leader | C = Collaborator*

#### 5.2.2.3. Sprint Backlog 2
<a id="5-2-2-3-sprint-backlog-2"></a>

El objetivo principal de este Sprint es implementar y desplegar la primera versión de la Frontend Web Application de EcoRoad con Vue 3 y PrimeVue, consumiendo una Fake API que simula los futuros Web Services, y actualizar el Landing Page para redirigir a la aplicación desplegada.

> **[Pendiente: insertar captura del tablero del Sprint 2 en Trello y su URL pública.]**

| Sprint # | Sprint 2 | | | | | | |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :---: |
| **Story Id** | **Story Title** | **Task Id** | **Task Title** | **Task Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
| US27 | CTA Segmento Constructoras Viales | T2-01 | Enlace de CTA hacia la Web Application | Actualizar los call-to-action del Landing Page para redirigir al inicio de sesión de la Web Application desplegada. | 1 | Pancorbo Amorós, Italo Raul | Done |
| US28 | CTA Segmento Mantenimiento Vial | T2-02 | Redirección al portafolio tras autenticación | Configurar la redirección del visitante hacia la vista de proyectos después de iniciar sesión. | 1 | Pancorbo Amorós, Italo Raul | Done |
| US01 | Autenticación de Usuarios | T2-03 | Vista de inicio de sesión | Implementar la vista de inicio de sesión, la sesión de usuario y la protección de rutas. | 4 | Salcedo Muñoz, Andy Alfredo Hipolito | Done |
| US25 | Registro de Colaboradores y Asignación de Permisos | T2-04 | Gestión de colaboradores | Implementar la vista de colaboradores con invitación, asignación de rol y permisos. | 4 | Salcedo Muñoz, Andy Alfredo Hipolito | Done |
| US26 | Restricción de Acceso según Permisos Asignados | T2-05 | Vista de acceso denegado y guardas de ruta | Restringir el acceso a vistas según los permisos del colaborador e implementar la vista de acceso denegado. | 3 | Salcedo Muñoz, Andy Alfredo Hipolito | Done |
| US30 | Creación de Proyecto Vial | T2-06 | Registro de proyectos viales | Implementar el formulario de registro de proyecto vial con validación de campos obligatorios. | 4 | Pancorbo Amorós, Italo Raul | Done |
| US30 | Creación de Proyecto Vial | T2-07 | Gestión de tramos y frentes de trabajo | Implementar el alta, edición y eliminación de tramos y frentes de trabajo de un proyecto. | 4 | Pancorbo Amorós, Italo Raul | Done |
| US11 | Visualización General de Proyectos | T2-08 | Listado de proyectos | Implementar la vista de listado de proyectos con estado ambiental, sensores, alertas e incidencias. | 3 | Pancorbo Amorós, Italo Raul | Done |
| US12 | Consulta de Resumen de un Proyecto | T2-09 | Detalle de proyecto | Implementar la vista de detalle de un proyecto con sus tramos. | 2 | Pancorbo Amorós, Italo Raul | Done |
| US33 | Asociación de Sensores IoT a Puntos de Monitoreo | T2-10 | Puntos de monitoreo y asignación de sensores | Implementar el registro de puntos de monitoreo geolocalizados y la asignación, calibración y activación de sensores. | 5 | Guillen Chavez, Eduardo Martín | Done |
| US10 | Consulta de Estado y Ubicación de Sensores IoT | T2-11 | Inventario de sensores | Implementar el inventario de sensores con filtros por proyecto, estado y búsqueda. | 3 | Guillen Chavez, Eduardo Martín | Done |
| US09 | Monitoreo de Mediciones en Tiempo Real | T2-12 | Lecturas actuales por tramo | Mostrar las lecturas actuales de los sensores y el estado ambiental por tramo. | 4 | Pancorbo Amorós, Italo Raul | Done |
| US13 | Consulta del Dashboard Ambiental de un Proyecto | T2-13 | Dashboard ambiental e histórico | Implementar el dashboard ambiental del proyecto y el gráfico histórico de indicadores. | 5 | Pancorbo Amorós, Italo Raul | Done |
| US15 | Consulta del Nivel de Riesgo de un Indicador | T2-14 | Evaluación de riesgo | Clasificar las mediciones en óptimo, advertencia o crítico según los umbrales configurados. | 3 | Guillen Chavez, Eduardo Martín | Done |
| US16 | Consulta de Alertas Generadas | T2-15 | Bandeja de alertas | Implementar la bandeja de alertas con filtros, detalle y registro de atención (acknowledgment). | 4 | Guillen Chavez, Eduardo Martín | Done |
| US18 | Registro de Incidencia Ambiental | T2-16 | Apertura de incidencias | Implementar la apertura de una incidencia a partir de una alerta. | 3 | Roman Lopez, Miguel Angel Junior | Done |
| US19 | Asignación de Responsable de Incidencia | T2-17 | Asignación de responsable | Permitir asignar un colaborador responsable a una incidencia. | 2 | Roman Lopez, Miguel Angel Junior | Done |
| US20 | Registro de Acción Correctiva | T2-18 | Registro de acciones correctivas | Permitir registrar acciones correctivas sobre una incidencia en proceso. | 2 | Roman Lopez, Miguel Angel Junior | Done |
| US22 | Registro de Evidencia de Campo | T2-19 | Registro de evidencias | Permitir registrar evidencias con nota y archivo adjunto. | 3 | Roman Lopez, Miguel Angel Junior | Done |
| US21 | Actualización de Estado de Incidencia | T2-20 | Tablero de ciclo de vida de incidencias | Implementar el tablero de incidencias con resolución y cierre formal, validando acción y evidencia. | 4 | Roman Lopez, Miguel Angel Junior | Done |
| US24 | Generación de Reporte Ambiental | T2-21 | Configuración y vista previa de reportes | Implementar la configuración del reporte por proyecto, periodo y secciones, con vista previa. | 4 | Taza Curay, Eduardo Miguel | Done |
| US23 | Consulta del Historial Ambiental de un Proyecto | T2-22 | Historial de reportes generados | Implementar la generación del reporte y el historial de reportes del proyecto. | 3 | Taza Curay, Eduardo Miguel | Done |
| — | Commercial and Subscription Management | T2-23 | Registro de empresa y suscripción | Implementar el registro de la cuenta de empresa y la selección y activación del plan de suscripción. | 5 | Pancorbo Amorós, Italo Raul | Done |
| — | Despliegue | T2-24 | Despliegue en Vercel | Configurar `vercel.json`, la función serverless de la Fake API y el despliegue de la Web Application. | 4 | Roman Lopez, Miguel Angel Junior | Done |
| — | Informe | T2-25 | Informe: Capítulo V – Sprint 2 | Documentar el Sprint 2 en el informe del proyecto. | 4 | Taza Curay, Eduardo Miguel / Pancorbo Amorós, Italo Raul | Done |

#### 5.2.2.4. Development Evidence for Sprint Review
<a id="5-2-2-4-development-evidence-for-sprint-review"></a>

Durante el Sprint 2 el equipo implementó la primera versión de la Frontend Web Application de EcoRoad con Vue 3, Vue Router y PrimeVue. El código se organizó por bounded context, cada uno con sus capas `domain`, `application`, `infrastructure` y `presentation`, y se desarrolló en una rama `ft-<Bounded-Context>` por contexto, integrada a `develop` mediante Pull Requests. Cada contexto consume una Fake API en Node.js que simula los futuros Web Services. Además, se actualizó el Landing Page para que su call-to-action de inicio de sesión dirija a la Web Application desplegada.

**Repositorio Frontend Web Application:** https://github.com/Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd

**Repositorio Landing Page:** https://github.com/Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| --- | --- | --- | --- | --- | --- |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | develop | cb4a256 | Initial commit | Creación del repositorio de la Web Application. | 08/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Commercial-and-Subscription-Management | 7b825b6 | feat(commercial): scaffold company registration and subscription demo | Estructura inicial del registro de empresa y de la suscripción. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Commercial-and-Subscription-Management | 708084c | feat(commercial): scaffold company registration and subscription demo | Vistas de registro de empresa y de planes de suscripción. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Commercial-and-Subscription-Management | 1537151 | feat(commercial): integrate fake API for subscription flows | Integración de los flujos de suscripción con la Fake API. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Project-and-Road-Site-Management | a9e3024 | feat(projects): add road project listing and registration | Listado y registro de proyectos viales. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Project-and-Road-Site-Management | da8d9b5 | fix(projects): set projects as default route. | Vista de proyectos como ruta por defecto. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Project-and-Road-Site-Management | b423996 | feat(projects): manage road sections and work fronts | Gestión de tramos y frentes de trabajo. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Environmental-Monitoring | 44fd045 | wip: preserve project API and environmental monitoring | Integración de la API de proyectos con el monitoreo ambiental. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Environmental-Monitoring | 1e71d66 | feat(monitoring): connect environmental views to fake api | Dashboard ambiental e histórico de indicadores conectados a la Fake API. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Alerting-and-Risk-Evaluation | a8d5031 | feat(alerting): add risk evaluation and alert inbox | Evaluación de riesgo y bandeja de alertas. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Alerting-and-Risk-Evaluation | fa92cd6 | feat(alerting): connect alert inbox and acknowledgments to fake API | Bandeja de alertas y registro de atención conectados a la Fake API. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Monitoring-Asset-and-Deployment | 313ab8c | feat(assets): implement monitoring asset and deployment context | Puntos de monitoreo, inventario, asignación, calibración y activación de sensores. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Compliance-and-Reporting | ed65bd7 | feat(compliance): add report configuration and preview | Configuración y vista previa de reportes ambientales. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Compliance-and-Reporting | 7536be3 | feat(compliance): integrate fake API for report generation and history | Generación e historial de reportes con la Fake API. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Identity-and-Access-Management-(IAM) | 4d3920a | add collaborator access model and management UI | Modelo de acceso de colaboradores y vista de gestión. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Identity-and-Access-Management-(IAM) | e415434 | feat(iam): completar autenticación y gestión de accesos con fake API | Autenticación y gestión de accesos conectadas a la Fake API. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Incident-and-Remediation-Management | 1d2864b | feat(incidents): add incident lifecycle and remediation board | Ciclo de vida de incidencias y tablero de remediación. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | ft-Incident-and-Remediation-Management | 269161f | feat(incidents): connect remediation workflow to fake API | Flujo de remediación conectado a la Fake API. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | develop | 6da08f2 | feat(develop): add vercel.json for deploy | Configuración de despliegue en Vercel. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | develop | 99ae049 | fix(deploy): resolve merge errors in router and fake API | Corrección de errores de integración en el router y la Fake API. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd | develop | 4039d15 | fix(deploy): serve demo API and authentication on Vercel | Publicación de la Fake API y la autenticación como función serverless en Vercel. | 09/10/2026 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | 24d6680 | feat(landing): link sign-in to deployed frontend | Enlace del call-to-action de inicio de sesión hacia la Web Application desplegada. | 09/10/2026 |

#### 5.2.2.5. Execution Evidence for Sprint Review
<a id="5-2-2-5-execution-evidence-for-sprint-review"></a>

En el Sprint 2 se logró desplegar la primera versión de la Frontend Web Application de EcoRoad en https://ecoroad-frontend-ddli-peach.vercel.app/, accesible desde el call-to-action del Landing Page. Las vistas implementadas por bounded context son:

| Bounded Context | Vistas implementadas | Ruta |
| :--- | :--- | :--- |
| Identity and Access Management | Inicio de sesión, gestión de colaboradores, acceso denegado | `/iam/login`, `/iam/collaborators`, `/iam/forbidden` |
| Commercial and Subscription Management | Registro de empresa, planes y suscripción | `/commercial/...` |
| Project and Road Site Management | Listado de proyectos, nuevo proyecto, detalle de proyecto con tramos y frentes | `/projects`, `/projects/new`, `/projects/:id` |
| Monitoring Asset and Deployment | Puntos de monitoreo e inventario de sensores | `/assets/...` |
| Environmental Monitoring | Dashboard ambiental e histórico de indicadores | `/monitoring/...` |
| Alerting and Risk Evaluation | Bandeja de alertas con detalle y atención | `/alerts` |
| Incident and Remediation Management | Tablero de incidencias con asignación, acciones, evidencias, resolución y cierre | `/incidents` |
| Compliance and Reporting | Configuración, vista previa e historial de reportes | `/compliance/...` |

![EvidenciaFront](assets/images/EvidenciaWeb1.jpeg)

![EvidenciaFront](assets/images/EvidenciaWeb2.jpeg)

![EvidenciaFront](assets/images/EvidenciaWeb3.jpeg)

![EvidenciaFront](assets/images/EvidenciaWeb4.jpeg)

Video de evidencia:

https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241d483_upc_edu_pe/IQBKnDlvgrUBTrm0ubp8ziwsAXeVyuD1lsqVZ1qMBecqAkw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=rMrp5C

#### 5.2.2.6. Services Documentation Evidence for Sprint Review
<a id="5-2-2-6-services-documentation-evidence-for-sprint-review"></a>

En el Sprint 2 todavía no se implementaron los Web Services en ASP.NET Core, por lo que no existe documentación OpenAPI desplegada. Para permitir la integración de la Web Application, el equipo definió contratos HTTP provisionales por bounded context (carpeta `docs/` del repositorio `EcoRoad-FrontEnd`) y los implementó en una Fake API en Node.js, publicada como función serverless en Vercel bajo la ruta `/api`. Estos contratos sirven de base para los endpoints que se implementarán en ASP.NET Core en el Sprint 3.

**URL base:** `https://ecoroad-frontend-ddli-peach.vercel.app/api` — **Repositorio:** https://github.com/Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd

Las respuestas exitosas devuelven el recurso en JSON; los errores devuelven `{ code, message, errors? }` con el código HTTP correspondiente (por ejemplo 403 `SUBSCRIPTION_REQUIRED`, 404 `NOT_FOUND`, 409 conflicto de estado, 422 validación).

| Bounded Context | HTTP | Endpoint | Parámetros / Body | Response |
| :--- | :---: | :--- | :--- | :--- |
| IAM | POST | `/api/iam/sessions` | Credenciales del usuario | Token de sesión y datos del usuario |
| IAM | GET | `/api/iam/sessions/current` | — | Usuario de la sesión actual |
| IAM | GET | `/api/iam/users` | — | Colaboradores de la empresa |
| IAM | POST | `/api/iam/invitations` | Datos del colaborador | Colaborador invitado |
| IAM | PUT | `/api/iam/users/{id}/role` | `{ roleId }` | Colaborador con rol actualizado |
| IAM | PUT | `/api/iam/users/{id}/permissions` | Permisos | Colaborador con permisos actualizados |
| IAM | POST | `/api/iam/users/{id}/grant` · `/revoke` | — | Colaborador con acceso habilitado o revocado |
| Commercial | POST | `/api/company-accounts` | Razón social, RUC, tipo de empresa, contacto administrador | Identificador de la empresa |
| Commercial | GET | `/api/company-accounts/{companyId}/subscription` | — | Plan, estado, fecha de activación y vencimiento |
| Commercial | PUT | `/api/company-accounts/{companyId}/subscription/plan` | `{ planId: "base" \| "professional" \| "enterprise" }` | Suscripción con el plan seleccionado |
| Commercial | POST | `/api/company-accounts/{companyId}/subscription/activation-requests` | — | Solicitud de activación |
| Projects | GET | `/api/projects` | — | Lista de proyectos de la empresa |
| Projects | POST | `/api/projects` | Datos del proyecto | Proyecto creado (201) |
| Projects | GET | `/api/projects/{projectId}` | — | Proyecto con sus tramos |
| Projects | POST | `/api/projects/{projectId}/sections` | Datos del tramo | Tramo creado (201) |
| Projects | PUT · DELETE | `/api/projects/{projectId}/sections/{sectionId}` | Datos del tramo (PUT) | Tramo actualizado · `{ "deleted": true }` |
| Assets | GET | `/api/assets/points?projectId=` | `projectId` opcional | Puntos de monitoreo |
| Assets | POST | `/api/assets/points` | `{ projectId, sectionId, name, pk, latitude, longitude }` | Punto creado |
| Assets | GET | `/api/assets/sensors?projectId=&status=&search=` | Filtros opcionales | Inventario de sensores |
| Assets | POST | `/api/assets/sensors` | `{ name, serialNumber, type }` | Sensor registrado |
| Assets | POST | `/api/assets/sensors/{id}/assignment` · `/calibration` · `/activation` | `{ pointId }` · `{ validUntil }` · — | Sensor actualizado |
| Monitoring | GET | `/api/monitoring/projects/{projectId}/dashboard` | — | Indicadores, lecturas actuales y estado por tramo |
| Monitoring | GET | `/api/monitoring/projects/{projectId}/history?sectionId=&parameterId=&from=&to=` | Tramo, parámetro y rango de fechas | Lecturas históricas filtradas |
| Alerting | GET | `/api/alerts?projectId=&risk=&status=&search=` | Filtros opcionales | Alertas de la empresa |
| Alerting | GET | `/api/alerts/{id}` | — | Detalle de la alerta |
| Alerting | POST | `/api/alerts/{id}/acknowledgments` | `{ acknowledgedBy }` | Alerta atendida |
| Incidents | GET | `/api/incidents?status=&projectId=&search=` | Filtros opcionales | Incidencias de la empresa |
| Incidents | POST | `/api/incidents` | `{ alertId, description }` | Incidencia creada |
| Incidents | POST | `/api/incidents/{id}/assignment` | `{ userId }` | Incidencia con responsable |
| Incidents | POST | `/api/incidents/{id}/actions` | `{ description }` | Incidencia con acción correctiva |
| Incidents | POST | `/api/incidents/{id}/evidence` | `{ note, attachment? }` | Incidencia con evidencia |
| Incidents | POST | `/api/incidents/{id}/resolution` · `/closure` | — | Incidencia resuelta · cerrada |
| Compliance | POST | `/api/compliance/previews` | `{ projectId, from, to, sections }` | Consolidación para vista previa |
| Compliance | POST | `/api/compliance/reports` | `{ projectId, from, to, sections }` | Reporte generado (201) |
| Compliance | GET | `/api/compliance/reports?projectId=` | `projectId` | Reportes generados del proyecto |

**Commits relacionados con los contratos y la Fake API:** `1537151`, `44fd045`, `1e71d66`, `fa92cd6`, `313ab8c`, `7536be3`, `e415434`, `269161f`, `4039d15`.

#### 5.2.2.7. Software Deployment Evidence for Sprint Review
<a id="5-2-2-7-software-deployment-evidence-for-sprint-review"></a>

Durante el Sprint 2 se realizó el primer despliegue de la Frontend Web Application en Vercel y se publicó una nueva versión del Landing Page en GitHub Pages. Las actividades realizadas fueron:

1. **Importación del repositorio en Vercel:** desde la cuenta de Vercel del equipo se creó un nuevo proyecto importando el repositorio `Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-FrontEnd`, con el nombre `ecoroad-frontend`.

![deploy-evidence-1](assets/images/DeployEvidence1.jpeg)

2. **Configuración del despliegue:** se agregó el archivo `vercel.json` (commit `6da08f2`) con las reglas de *rewrite* para la SPA y para la Fake API como función serverless (`api/index.js`), y se corrigieron los errores de integración del router y de la API (commits `99ae049` y `4039d15`).

![deploy-evidence-2](assets/images/DeployEvidence2.jpeg)

3. **Verificación del despliegue:** Vercel muestra el despliegue en estado *Ready* desde la rama `develop`, publicado en https://ecoroad-frontend-ddli-peach.vercel.app/

![deploy-evidence-3](assets/images/DeployEvidence3.jpeg)

4. **Nueva versión del Landing Page:** se publicó en GitHub Pages el commit `24d6680`, que enlaza el call-to-action de inicio de sesión con la Web Application desplegada.

#### 5.2.2.8. Team Collaboration Insights during Sprint
<a id="5-2-2-8-team-collaboration-insights-during-sprint"></a>

Durante el Sprint 2 cada integrante implementó al menos un bounded context de la Web Application en su propia rama `ft-<Bounded-Context>`. Las ramas se integraron a `develop` mediante Pull Requests revisados por el Team Leader, y los conflictos de integración del router y de la Fake API se resolvieron antes del despliegue en Vercel. La coordinación se realizó en sesiones por Discord y mensajes por WhatsApp. La siguiente tabla resume la contribución por integrante en el repositorio de la Web Application según GitHub (incluye los commits de merge de Pull Requests).

| Integrante | Usuario GitHub | Bounded Context implementado | Commits (FrontEnd) |
|---|---|---|---|
| Pancorbo Amorós, Italo Raul | pancorboitalo-design | Commercial & Subscription, Project & Road Site, Environmental Monitoring, Landing Page | 22 |
| Roman Lopez, Miguel Angel Junior | MiguelRomn | Incident & Remediation, despliegue en Vercel | 5 |
| Guillen Chavez, Eduardo Martín | Eduardox30-wq | Alerting & Risk Evaluation, Monitoring Asset & Deployment | 3 |
| Salcedo Muñoz, Andy Alfredo Hipolito | Andy777sdw | Identity and Access Management | 2 |
| Taza Curay, Eduardo Miguel | Edutaza10 | Compliance & Reporting | 2 |

![insights front](assets/images/InsightsFront.jpeg)
