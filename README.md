<div align="center">

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

**Período 202610**

**Julio 2026**

</div>

---

<div style="page-break-after: always;"></div>

## Registro de Versiones del Informe

| Versión | Fecha | Autores | Descripción de modificación |
| :--- | :--- | :--- | :--- |
| **AV1** | 20/9|  Pancorbo Amorós , Italo Raul <br> Guillen Chavez , Eduardo Martín <br> Salcedo Muñoz , Andy Alfredo Hipolito <br> Taza Curay , Eduardo Miguel <br> Roman Lopez , Miguel Angel Junior  |Para la entrega AV1 se consolidó la estructura del informe técnico, incluyendo carátula, registro de versiones, tabla de contenidos y la definición de Student Outcomes. <br><br>Capítulo I — Introducción: Se redactó el Startup Profile y el Solution Profile (EcoRoad), detallando la propuesta de valor para la gestión y construcción de proyectos viales. <br><br>Capítulo II — Requirements Elicitation & Analysis: Se realizó el análisis de competidores y el registro de entrevistas a profundidad. Se desarrolló el Needfinding (User Personas, Task Matrix, Journey Mapping), así como el Big Picture EventStorming para identificar los eventos clave del dominio y el Ubiquitous Language basado en los Bounded Contexts definidos.<br><br>Capítulo III — Requirements Specification: Se elaboró el Product Backlog priorizando las User Stories críticas. Se aplicó la metodología de Impact Mapping para alinear las funcionalidades con los objetivos estratégicos del negocio.<br><br>Capítulo IV — Product Design: Se definieron los lineamientos de estilo general y web, junto con la arquitectura de la información del sistema. Se documentó el diseño de las interfaces de usuario a través de wireframes y mock-ups para la Landing Page y la Web Application, abarcando tanto las vistas de escritorio como las adaptaciones móviles. Además, se estableció la arquitectura de software basada en Domain-Driven Design mediante los diagramas del modelo C4 (Contexto, Contenedor y Componentes), y se detalló el diseño técnico incorporando los diagramas de clases y de base de datos para los ocho Bounded Contexts del proyecto. <br><br> Capítulo V — Product Implementation: Se documentó la gestión de configuración de software, estándares de versionamiento (GitFlow) y convenciones de código. Se incluyó la evidencia del Sprint 1, detallando el Sprint Planning, Sprint Backlog (enfocado en US001, US002, US003 y US004), líderes de aspecto, métricas de colaboración y las evidencias del despliegue inicial de la Landing Page en GitHub Pages.  |
| **TB1** | | | |
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
  

---

## [Conclusiones](#conclusiones)

- [Conclusiones y recomendaciones](#conclusiones)
- [Video About-the-Team](#recomendaciones)

---

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
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta.** | Eduardo Martín Guillen Chavez AV1: Lideró la definición arquitectónica desarrollando el Big Picture Event Storming, los diagramas C4 y la Domain Driving Architecture. Además, orientó la visión del producto colaborando en el needfinding, la task matrix y el Ubiquitous Language, participando también en el video del equipo.Pancorbo Amorós, Italo Raul AV1: Ejerció el rol de Team Leader gestionando la organización de ramas y merges del repositorio. Guió el diseño técnico mediante el desarrollo de diagramas ERD y de clase, y coordinó esfuerzos colaborando en el Capítulo 1, Capítulo V, las User Stories (US), el Ubiquitous Language, además de realizar 1 entrevista y participar en el video.Román López, Miguel Ángel Junior AV1: Lideró la ejecución técnica y visual inicial colaborando estrechamente con el desarrollo de los Mockups y wireframes, y responsabilizándose por el despliegue de la landing page.Taza Curay, Eduardo Miguel AV1: Apoyó en la dirección del diseño de interfaces colaborando en el Figma y en el repositorio de la landing page. Aportó a la investigación y documentación desarrollando 2 entrevistas, colaborando en el Capítulo V y participando en el video.Andy Alfredo Hipolito Salcedo Muñoz AV1: Dirigió la investigación de mercado mediante el desarrollo de competidores y análisis competitivo. Lideró la redacción del Capítulo 1 y Capítulo 3, desarrolló 1 entrevista y colaboró en la task matrix, además de participar en el video.| AV1: Durante el primer avance (AV1), el equipo Kaimán demostró un claro liderazgo compartido para el desarrollo del producto EcoRoad. Cada miembro asumió el liderazgo en áreas clave según sus fortalezas: arquitectura de software, gestión de repositorio, diseño de interfaces (Figma/Mockups) y análisis de mercado/competencia. La correcta organización de ramas bajo la guía del Team Leader y la toma de decisiones conjuntas en artefactos críticos como el Event Storming y el Ubiquitous Language reflejan un esfuerzo coordinado donde todos aportaron al direccionamiento del proyecto y cumplieron sus responsabilidades a tiempo y con calificación perfecta.|
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.** |Eduardo Martín Guillen Chavez AV1: Fomentó la integración de los requisitos del usuario con la arquitectura técnica cumpliendo con sus tareas de needfinding y diagramas en los plazos establecidos. Su participación en el video evidenció su compromiso con las dinámicas integradoras del grupo.Pancorbo Amorós, Italo Raul AV1: Planificó el entorno de trabajo colaborativo al establecer el flujo de control de versiones (ramas y merges) para el equipo. Cumplió los objetivos técnicos y documentales asignados, facilitando un entorno donde se pudieron integrar las entrevistas y las User Stories de manera fluida.Román López, Miguel Ángel Junior AV1: Estableció y cumplió sus metas operativas logrando el despliegue funcional de la landing page. Creó un entorno de trabajo conjunto al colaborar directamente en los wireframes y mockups necesarios para el avance del grupo.Taza Curay, Eduardo Miguel AV1: Apoyó activamente a sus compañeros colaborando en repositorios compartidos y herramientas de diseño cooperativo como Figma. Cumplió su meta de recopilación de datos al realizar 2 entrevistas a tiempo y colaboró en la redacción del Capítulo V.Andy Alfredo Hipolito Salcedo Muñoz AV1: Planificó y cumplió oportunamente con la entrega documental estructurando los Capítulos 1 y 3. Mantuvo una actitud colaborativa apoyando en la task matrix, realizando su entrevista correspondiente y uniéndose a sus compañeros en la grabación del video | AV1: El equipo logró consolidar un entorno inclusivo y orientado al cumplimiento de metas, evidenciado en la calificación máxima obtenida por todos los integrantes debido a la entrega puntual de sus asignaciones. La planificación de tareas fue efectiva, permitiendo que responsabilidades complejas —como el despliegue web, la elaboración de diagramas C4 y el desarrollo documental— se integraran exitosamente mediante una correcta gestión de repositorio. La activa participación de todo el equipo en las entrevistas, el diseño colaborativo en Figma y la grabación conjunta del video demuestran un fuerte compromiso con el trabajo en equipo y los objetivos del AV1|
