# Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
<a id="5-1-software-configuration-management"></a>


### 5.1.1. Software Development Environment Configuration
<a id="5-1-1-software-development-environment-configuration"></a>
#### Gestión del Proyecto
Para la coordinación del proyecto y el seguimiento del trabajo colaborativo se utilizaron plataformas de comunicación, almacenamiento y gestión ágil. El código fuente de la Landing Page y del informe se centralizó en una organización de GitHub. Las reuniones virtuales del equipo y coordinaciones diarias se realizaron mediante Discord y WhatsApp, mientras que la planificación y asignación de tareas se gestionó a través de Zoho Sprints.

* **Coordinación de código y repositorios:** GitHub
* **Reuniones virtuales y syncs:** Discord
* **Comunicación diaria:** WhatsApp
* **Organización y seguimiento de tareas (Agile):** Zoho Sprints

#### Gestión de Requerimientos
Durante la fase de análisis y estructuración de requerimientos, se empleó UXPressia para diseñar las User Personas, Mapas de Empatía e Impact Maps. Se utilizó Miro para la construcción de escenarios As-Is / To-Be y los tableros de Event Storming.

* **Diseño UX y Mapas de Impacto:** UXPressia
* **Event Storming y Escenarios:** Miro
* **Gestión de User Stories:** Zoho Sprints / GitHub Projects

#### Diseño de Experiencia e Interfaz del Producto
Para la concepción visual de la Landing Page y la maquetación preliminar de las interfaces de la plataforma, el equipo empleó Figma. Se elaboraron wireframes y maquetas de alta fidelidad para validar la estructura visual, paleta de colores y la disposición de las secciones informativas antes de su codificación.

* **Diseño de Interfaz y Prototipado:** Figma

#### Desarrollo de Software
El desarrollo de la Landing Page responsiva se realizó utilizando tecnologías web estándar (HTML5, CSS3 y JavaScript). El informe del proyecto se redactó en formato Markdown (.md). Para el desarrollo del código y del informe se emplearon editores e IDEs como Visual Studio Code, WebStorm e IntelliJ IDEA, administrados mediante JetBrains Toolbox para mantener la homogeneidad del entorno.

* **IDEs y Editores:** Visual Studio Code, WebStorm, IntelliJ IDEA
* **Gestor de IDEs:** JetBrains Toolbox

#### Documentación de Software
La documentación técnica del informe se gestionó en archivos Markdown (.md) sincronizados con el repositorio central del grupo en GitHub mediante la metodología Git Flow, asegurando un trabajo colaborativo ordenado.

#### Despliegue de Software
Para la publicación de la Landing Page como primer entregable accesible al público, se utilizó GitHub Pages (o Vercel), plataforma que permite el alojamiento continuo desde la rama correspondiente del repositorio.

* **Hosting y Despliegue Continuo:** GitHub Pages / Vercel

<div style="text-align: left; max-width: 900px; margin: 0 auto;">

### 5.1.2. Source Code Management
<a id="5-1-2-source-code-management"></a>

---

El equipo gestiona el código fuente mediante **GitHub** como plataforma de control de versiones, organizado bajo una organización pública que agrupa los repositorios de cada producto digital del proyecto.


**Landing Page — GitHub Pages**


Enlace de despliegue: 

**Landing Page — Repositorio GitHub**

Enlace del repositorio: 


#### GitFlow Workflow

El equipo implementa **GitFlow** como estrategia de ramificación para gestionar el ciclo de vida del código. Las ramas definidas son:

- **`main`**: Rama principal que contiene el código de producción estable. Solo recibe merges desde `release` o `hotfix`.
- **`develop`**: Rama de integración continua donde se consolidan los features completados antes de pasar a producción.
- **`feature/<nombre-feature>`**: Rama individual para el desarrollo de cada funcionalidad. Se crea desde `develop` y se integra de vuelta a `develop` al completarse. Ejemplo: `feature/hero-section`, `feature/navbar`, `feature/contact-form`.
- **`release/<versión>`**: Rama de preparación de una nueva versión de producción. Se crea desde `develop` cuando el Sprint está completo. Ejemplo: `release/1.0.0`.
- **`hotfix/<descripción>`**: Rama para correcciones críticas en producción. Se crea desde `main`. Ejemplo: `hotfix/fix-cta-redirect`.

#### Semantic Versioning

Para el nombramiento de versiones se aplica **Semantic Versioning 2.0.0** con el formato `MAJOR.MINOR.PATCH`:
- `MAJOR`: cambios incompatibles con versiones anteriores.
- `MINOR`: nuevas funcionalidades compatibles con versiones anteriores.
- `PATCH`: correcciones de errores compatibles con versiones anteriores.

La primera versión del Landing Page se etiqueta como `v1.0.0`.

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
docs(chapter2): add user empathy map
docs(chapter3): update user stories
fix(landing): correct mobile layout for plans section
docs(readme): update cover
style(landing): apply Material Design color tokens
```

### 5.1.3. Source Code Style Guide & Conventions

El equipo adopta las siguientes guías de estilo y convenciones de codificación para garantizar uniformidad y legibilidad en todos los productos. Toda nomenclatura se redacta en **inglés**.

#### HTML5 & CSS3 (Landing Page)
- Se aplica la guía **W3Schools HTML Style Guide** para estructura semántica, indentación con 2 espacios, atributos en minúsculas y uso de comillas dobles.
- Se aplica la guía **Google HTML/CSS Style Guide** para nomenclatura de clases en `kebab-case`, evitar el uso de selectores de ID en CSS y priorizar propiedades abreviadas.
- El diseño visual se basa en **Material Design** como sistema de diseño de referencia.

#### TypeScript & Angular (Frontend Web Application)
- Se aplica la **Angular Coding Style Guide** oficial: componentes con sufijo `Component`, servicios con sufijo `Service`, módulos con sufijo `Module`.
- Nombres de archivos en `kebab-case`: `project-list.component.ts`.
- Se aplica la **Google TypeScript Style Guide** para tipado estricto y gestión de imports.

#### Java & Spring Boot (Web Services)
- Se sigue la convención de **Spring Boot** para controladores (`@RestController`), servicios (`@Service`) y repositorios (`@Repository`).

#### Gherkin (Acceptance Criteria)
- Se aplican las **Gherkin Conventions for Readable Specifications**: un solo nivel de indentación para `Given/When/Then`, escenarios en inglés, descripciones en tercera persona.

---

### 5.1.4. Software Deployment Configuration

En esta sección se describe la configuración de despliegue para el Landing Page, único producto desplegado en el Sprint 1.

#### Landing Page — GitHub Pages

El Landing Page de EcoRoad se despliega como sitio web estático mediante **GitHub Pages**, directamente desde el repositorio:  

**Pasos para el despliegue:**

1. Asegurarse de que la rama `main` contiene los archivos del Landing Page (`index.html`, carpetas `css/`, `js/`, `assets/`).
2. Ingresar al repositorio en GitHub y navegar a **Settings > Pages**.
3. En la sección **Source**, seleccionar la rama `main` y la carpeta `/ (root)`.
4. Hacer clic en **Save**. GitHub Pages genera automáticamente la URL de despliegue.
5. Verificar el sitio desplegado en la URL generada por GitHub Pages.

Cualquier push a la rama `main` actualiza automáticamente el sitio desplegado.



## 5.2. Landing Page, Services & Applications Implementation.

<a id="5-2-landing-page-services-applications-implementation"></a>

### 5.2.1. Sprint 1
<a id="5-2-1-sprint-1"></a>

#### 5.2.1.1. Sprint Planning 1



## Imágen de evidencia:

| Sprint # | Sprint 1 |
| :--- | :--- |
| **Sprint Planning Background** | |
| Date | 2026-09-16 |
| Time | 07:00 PM |
| Location | Reunión virtual vía Discord |
| Prepared By | Pancorbo Amorós, Italo Raul |
| Attendees | Eduardo Miguel Taza Curay / Miguel Angel Junior Roman Lopez / Eduardo Martín Guillen Chavez / Andy Alfredo Hipolito Salcedo Muñoz / Pancorbo Amorós, Italo Raul |
| Sprint 0 Review Summary | Al ser el primer Sprint del proyecto, no existe un Sprint anterior. Se parte del Product Backlog inicial definido y de los artefactos arquitectónicos (Domain-Driven Design, ERDs) elaborados en los capítulos previos. |
| Sprint 0 Retrospective Summary | El equipo acordó establecer estándares de trabajo desde el inicio: aplicar GitFlow, Conventional Commits y dividir las responsabilidades de implementación del Landing Page por secciones entre los miembros. |
| **Sprint Goal & User Stories** | |
| Sprint 1 Goal | Our focus is on delivering a fully deployed and navigable Landing Page for EcoRoad. We believe it delivers a clear understanding of the value proposition to potential clients from both target segments (construction companies and environmental supervisors). This will be confirmed when visitors can navigate all sections of the Landing Page, identify the environmental monitoring features, compare subscription plans, and access the call-to-action buttons for each segment. |
| Sprint 1 Velocity | 20 Story Points |
| Sum of Story Points | 19 Story Points |

##### 5.2.1.2. Aspect Leaders and Collaborators
<a id="5-2-1-2-aspect-leaders-and-collaborators"></a>



#### 5.2.1.2. Aspect Leaders and Collaborators

Para el Sprint 1, los aspectos de trabajo se organizan en torno a las secciones del Landing Page y la configuración del entorno de desarrollo y despliegue. Cada aspecto cuenta con un líder responsable de liderar la implementación y uno o más colaboradores de apoyo.

| Team Member | GitHub Username | Hero & Navbar | Plans Section | Features Section | Contact Form | Deployment & Config |
|:---|:---|:---:|:---:|:---:|:---:|:---:|
| Eduardo Miguel Taza Curay | *Edutaza10* | L | C | | | C |
| Miguel Angel Junior Roman Lopez | *miguelromanl* | C | | L | C | C |
| Eduardo Martín Guillen Chavez | *Eduardox30-wq* | C | | C | L | |
| Andy Alfredo Hipolito Salcedo Muñoz | *Andy777sdw* | | L | C | | C |
| Pancorbo Amorós, Italo Raul | *pancorboitalo-design* | | C | C | | L |

*L = Líder | C = Colaborador*

##### 5.2.1.3. Sprint Backlog 1
<a id="5-2-1-3-sprint-backlog-1"></a>

El objetivo principal de este Sprint es implementar y desplegar la primera versión del Landing Page de Ecoroad, cubriendo las secciones de presentación de valor, funcionalidades, planes de suscripción, testimonios y formulario de contacto, con CTAs diferenciados para cada segmento objetivo.



Imágen de envidencia: <img src="../assets/images/trello.jpeg">

[Tablero de Trello: Organización del Sprint - EcoRoad](https://trello.com/invite/b/6ab0928cab1e6c824069d8ae/ATTI8217aefaf5493c7dc99f935bc7566209F12E82AE/sprint-ecoroad)

| US / TS / Task ID | Título | Descripción de Tarea | Estimación (Horas) | Integrante Asignado | Estado |
| :--- | :--- | :--- | :---: | :--- | :---: |
| **US001 / CC01** | Header y Navbar Responsivos | Maquetación y estilos responsive del encabezado y menú de navegación. | 4 | Pancorbo Amorós, Italo Raul | Done |
| **US001 / CC02** | Sección Hero & About Us | Maquetación visual de la sección principal y presentación de la empresa. | 4 | Italo Raul Pancorbo Amorós | Done |
| **US002 / CC03** | Sección de Servicios y Producto | Maquetación de tarjetas informativas con las funcionalidades del SaaS. | 3 | Andy Alfredo Hipolito Salcedo Muñoz | Done |
| **US003 / CC04** | Sección de Contacto | Maquetación de la sección informativa de canales de comunicación. | 2 | Taza Curay, Eduardo Miguel | Done |
| **US004 / CC05** | Formulario de Contacto UI | Desarrollo de la interfaz del formulario y validaciones en tiempo real. | 3 | Taza Curay, Eduardo Miguel | Done |
| **TS001 / CC06** | Footer & Enlaces Sociales | Maquetación del pie de página y enlaces a redes de la plataforma. | 2 | Roman Lopez, Miguel Angel Junior  | Done |
| **TS001 / CC07** | Despliegue en GitHub Pages | Configuración del pipeline de despliegue continuo desde la rama `main`. | 2 | Miguel Angel Junior Roman Lopez | Done |
| **DOC01** | Informe Capítulo I | Introducción, problema, objetivos, justificación y restricciones. | 5 | Pancorbo Amorós, Italo Raul | Done |
| **DOC02** | Informe Capítulo II | Análisis del dominio, entrevistas, User Personas, Empathy Maps. | 6 | Salcedo Muñoz ,Andy Alfredo Hipolito  | Done |
| **DOC03** | Informe Capítulo III | Impact Mapping, Event Storming, 40 US + 12 TS y Product Backlog. | 8 | Guillén Chávez, Eduardo Martín / Taza Curay, Eduardo M. | Done |
| **DOC04** | Informe Capítulo IV | Arquitectura de Software, Estilo de Arquitectura y Vista de Contexto C4. | 6 | Miguel Angel Junior Roman Lopez | Done |
| **DOC05** | Informe Capítulo V | Configuration Management, Sprint Planning 1 y Evidencias de Sprint. | 5 | Eduardo Martín Guillén Chávez | Done |

---



---
### 5.2.1.4. Development Evidence for Sprint Review

En esta sección se presentan las evidencias correspondientes al desarrollo realizado durante el Sprint 1 del proyecto EcoRoad. Durante este sprint, el equipo se enfocó principalmente en la implementación de la Landing Page, considerando la estructura visual, navegación, presentación de la propuesta de valor, beneficios, funcionalidades, planes de suscripción, equipo de trabajo y elementos de contacto.

Asimismo, se implementaron mejoras relacionadas con la adaptación de la interfaz para diferentes dispositivos, la incorporación de recursos gráficos y la publicación de la Landing Page mediante GitHub Pages.

El desarrollo se encuentra registrado en el repositorio oficial del equipo mediante commits que permiten evidenciar los principales avances realizados durante el sprint.

**Repository:**  
https://github.com/Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage

**Deployed Landing Page:**  
https://aplicaciones-web-1ASI0730-2620-8130.github.io/EcoRoad-LandingPage/

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| --- | --- | --- | --- | --- | --- |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | [Commit ID] | feat: implement EcoRoad landing page | Implementación inicial de la Landing Page de EcoRoad, incluyendo su estructura principal, navegación y secciones informativas. | 17/09/26 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | [Commit ID] | feat: add benefits and visual resources | Incorporación de imágenes, beneficios y recursos gráficos relacionados con el monitoreo y la gestión ambiental de proyectos viales. | 17/09/26 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | [Commit ID] | feat: add team and call to action sections | Incorporación de la sección del equipo de EcoRoad y del Call to Action para solicitar demostraciones o contactar con especialistas. | 18/09/26 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | [Commit ID] | fix: improve footer layout | Mejora de la estructura y presentación del footer, incluyendo módulos, marco regulatorio, información de contacto y enlaces adicionales. | 18/09/26|
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | [Commit ID] | feat: improve responsive design | Adaptación de la Landing Page para su correcta visualización en computadoras, tablets y dispositivos móviles. | 19/09/26 |
| Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage | main | [Commit ID] | feat: add language selector | Incorporación del selector de idioma inglés/español para mejorar la accesibilidad e internacionalización de la Landing Page. | 19/09/26 |

##### 5.2.1.5. Execution Evidence for Sprint Review
<a id="5-2-1-5-execution-evidence-for-sprint-review"></a>

Durante el presente Sprint se logró implementar y desplegar una primera versión funcional de la Landing Page de EcoRoad, orientada a presentar la propuesta de valor de la solución, sus principales funcionalidades, beneficios y planes de suscripción.

La Landing Page fue desarrollada utilizando HTML, CSS y JavaScript, incorporando una estructura responsive que permite su correcta visualización tanto en computadoras como en dispositivos móviles. Asimismo, se implementaron diferentes componentes interactivos que permiten mejorar la experiencia de navegación del usuario.

Como parte del Sprint, la solución fue publicada mediante GitHub Pages, permitiendo acceder a la Landing Page desde un entorno web público y validar su correcto funcionamiento.

#### Resumen de logros

- **Implementación de la Landing Page:** Se desarrolló una primera versión funcional de EcoRoad, presentando de manera clara su propuesta de valor orientada al monitoreo y gestión ambiental en proyectos de infraestructura vial.

- **Presentación de soluciones y beneficios:** Se incorporaron secciones que muestran las principales soluciones de monitoreo ambiental, así como beneficios relacionados con reducción de riesgos, automatización de auditorías y trazabilidad georreferenciada.

- **Presentación de funcionalidades y modelo SaaS:** Se implementaron secciones para mostrar funcionalidades como dashboards georreferenciados, alertas ambientales, trazabilidad de evidencias y generación de reportes, además de los planes de suscripción de la plataforma.

- **Secciones de equipo y contacto:** Se añadieron las secciones de presentación del equipo y Call to Action, permitiendo al usuario conocer a los integrantes del proyecto y acceder a opciones de contacto o solicitud de demostración.

- **Diseño responsive e internacionalización:** La Landing Page fue adaptada para computadoras, tablets y smartphones, e incorpora un selector de idioma que permite alternar el contenido principal entre inglés y español.

- **Despliegue mediante GitHub Pages:** La solución fue publicada en un entorno web público, permitiendo validar su funcionamiento y acceder a la Landing Page desde distintos dispositivos.



Video de Demostración y Navegación: [Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241d483_upc_edu_pe/IQAkn3u2kvFiTqMHYbNb0IjtAX7jKxhOE-uMBPIxo2_Q5Ys?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Aga9p0)


Screenshots de la Implementación: <img src="..//assets/images/chapter5/Landing page .png">



##### 5.2.1.6. Services Documentation Evidence for Sprint Review
<a id="5-2-1-6-services-documentation-evidence-for-sprint-review"></a>

Durante este sprint se llevó a cabo el desarrollo e implementación de la Landing Page de EcoRoad, la cual funciona como punto principal de presentación de la solución y permite mostrar la propuesta de valor, funcionalidades, beneficios, planes de suscripción y características principales de la plataforma.

En este Sprint no se desarrollaron endpoints REST ni servicios backend propios, debido a que el alcance estuvo enfocado en la implementación de una Landing Page utilizando HTML, CSS y JavaScript. Sin embargo, se documenta la URL pública donde se encuentra desplegada la solución y el repositorio que contiene el código fuente desarrollado.

La Landing Page fue desplegada mediante GitHub Pages, permitiendo validar su correcta ejecución y acceder a ella desde diferentes dispositivos.

**Descripción del logro:**

- Desarrollo e implementación de la Landing Page de EcoRoad, incluyendo las secciones principales de presentación, soluciones, beneficios, funcionalidades, planes SaaS, equipo y Call to Action.

- Implementación de diseño responsive, selector de idioma inglés/español y despliegue público mediante GitHub Pages.

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th>Recurso</th>
    <th>Acción implementada</th>
    <th>HTTP</th>
    <th>URL / Endpoint</th>
    <th>Link de repositorio</th>
  </tr>

  <tr>
    <td>Landing Page</td>
    <td>Vista inicial y navegación de EcoRoad</td>
    <td>GET</td>
    <td>
      <a href="https://aplicaciones-web-1asi0730-2620-8130.github.io/EcoRoad-LandingPage/">
        EcoRoad Landing Page
      </a>
    </td>
    <td>
      <a href="https://github.com/Aplicaciones-Web-1ASI0730-2620-8130/EcoRoad-LandingPage">
        EcoRoad-LandingPage Repository
      </a>
    </td>
  </tr>
</table>

##### 5.2.1.7. Software Deployment Evidence for Sprint Review
<a id="5-2-1-7-software-deployment-evidence-for-sprint-review"></a>



##### 5.2.1.8. Team Collaboration Insights during Sprint
<a id="5-2-1-8-team-collaboration-insights-during-sprint"></a>



La finalización de este Sprint es el resultado de un esfuerzo coordinado para transformar los requerimientos de Vantage PMO en componentes de software funcionales. El equipo adoptó un flujo de trabajo ágil y riguroso, caracterizado por los siguientes puntos clave:

La carga de trabajo se distribuyó estratégicamente, permitiendo que cada desarrollador liderara áreas críticas según su especialidad, desde la lógica de internacionalización hasta la optimización del diseño responsivo y multimedia.

La evolución del proyecto se documentó a través de un historial de cambios continuo y granular. La unión de los módulos se realizó mediante procesos de Pull Request hacia la rama de integración, asegurando que cada nueva funcionalidad cumpliera con los estándares del proyecto antes de ser consolidada.

Mantuvimos un canal de comunicación técnica constante para gestionar la integración de APIs y estilos, logrando resolver discrepancias de diseño o lógica de manera inmediata y colaborativa.

El éxito de la entrega se fundamentó en la aplicación de buenas prácticas de desarrollo, asegurando un código limpio, mantenible y alineado con los objetivos de negocio de la plataforma.

Este enfoque metodológico no solo permitió cumplir con el Sprint Goal, sino que garantizó una contribución equilibrada y de alto impacto por parte de todos los miembros del equipo en la construcción de la Landing Page.

Métricas de Actividad en el Repositorio

Como evidencia del dinamismo y la colaboración técnica, se adjuntan los indicadores de actividad (commits, merges y contribuciones) extraídos de GitHub:


**Métricas de Actividad en el Repositorio**


### Analíticos de GitHub — Report

![commits-report](/assets/images/commits-report.jpeg)

#### Analíticos de GitHub — Landing Page
![commits-report](/assets/images/commits-landing.jpeg)


| Integrante | Usuario GitHub | Commits |
|---|---|---|
| Eduardo Martín Guillen Chavez| Eduardox30-wq| 9 |
| Pancorbo Amorós, Italo Raul   |pancorboitalo-design | 66|
|Román López, Miguel Ángel Junior |MiguelRomn | 0|
| Taza Curay, Eduardo Miguel| Edutaza10 | 11|
| Andy Alfredo Hipolito Salcedo Muñoz| Andy777sdw| 11|


</div>

### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2

| Campo | Detalle |
| :--- | :--- |
| **Sprint #** | Sprint 2 |
| **Date** | 2026-10-8 |
| **Time** | 08:00 PM |
| **Location** | Reunión virtual mediante Discord |
| **Prepared By** | Pancorbo Amorós, Italo Raul |
| **Attendees** | Eduardo Miguel Taza Curay / Miguel Angel Junior Roman Lopez / Eduardo Martín Guillen Chavez / Andy Alfredo Hipolito Salcedo Muñoz / Pancorbo Amorós, Italo Raul |
| **Sprint 1 Review Summary** | Durante el Sprint 1 se entregó satisfactoriamente la Landing Page completa y responsiva de Ecoroad desplegada en GitHub Pages, junto con la documentación técnica inicial correspondiente a los Capítulos I al V del informe. |
| **Sprint 1 Retrospective Summary** | El equipo mantuvo una sólida coordinación durante el desarrollo de EcoRoad. Se identificó la necesidad de estandarizar las convenciones de arquitectura en Vue.js, definir una estructura uniforme para componentes, views, services y recursos compartidos, organizar correctamente la API simulada y sus relaciones de datos, y unificar el flujo de trabajo en Git Flow mediante nombres de ramas estandarizados por funcionalidad del proyecto. |
| **Sprint 2 Goal** | Desarrollar, integrar y desplegar la primera versión funcional (v1.0) de la aplicación Web Frontend de EcoRoad en Vue.js, implementando las interfaces y funcionalidades principales de los Bounded Contexts de Commercial and Subscription Management, Identity and Access Management (IAM), Project and Road Site Management, Monitoring Asset and Deployment, Environmental Monitoring, Alerting and Risk Evaluation, Incident and Remediation Management y Compliance and Reporting. |
| **Sprint 2 Velocity** | Por definir según las User Stories seleccionadas para el Sprint 2 |
| **Sum of Story Points** | Por definir según las User Stories seleccionadas para el Sprint 2 |

---


#### 5.2.2.2. Aspect Leaders and Collaborators

| Integrante | Rol / Bounded Contexts Asignados | Responsabilidades Principales en Sprint 2 |
| :--- | :--- | :--- |
| **Taza Curay, Eduardo Miguel** | Frontend Developer / Bounded Context Leader | Liderazgo de **Project and Road Site Management** y co-liderazgo de **Monitoring Asset and Deployment**. Desarrollo de las interfaces de registro y administración de proyectos viales, gestión de tramos y frentes de trabajo, así como la visualización de sensores IoT asociados a cada proyecto. |
| **Roman Lopez, Miguel Angel Junior** | Frontend Developer / Bounded Context Leader | Liderazgo de **Identity and Access Management (IAM)** y **Commercial and Subscription Management**. Desarrollo de las interfaces de inicio de sesión, autenticación de usuarios, gestión de roles y permisos, visualización de planes de suscripción y administración de cuentas corporativas. |
| **Guillen Chavez, Eduardo Martín** | Frontend Developer / Bounded Context Leader | Liderazgo de **Environmental Monitoring** y **Alerting and Risk Evaluation**. Desarrollo del dashboard de monitoreo ambiental, visualización de mediciones de sensores IoT, indicadores ambientales, evaluación de niveles de riesgo y presentación de alertas críticas según los umbrales normativos. |
| **Hipolito Salcedo Muñoz, Andy Alfredo** | UX/UI Lead / Bounded Context Leader | Liderazgo de **Incident and Remediation Management** y co-liderazgo de **Monitoring Asset and Deployment**. Desarrollo del tablero de incidencias ambientales, asignación de responsables, seguimiento de acciones correctivas, registro de evidencias fotográficas y actualización del estado de las incidencias. |
| **Pancorbo Amorós, Italo Raul** | Team Lead / Bounded Context Leader | Liderazgo general del equipo y coordinación del desarrollo del Sprint 2. Liderazgo de **Compliance and Reporting** y co-liderazgo de **Project and Road Site Management**. Supervisión de la integración de los módulos, seguimiento de las tareas y gestión de ramas en GitHub. Desarrollo de las interfaces de consulta del historial ambiental, visualización de indicadores de cumplimiento y generación de reportes ambientales en PDF. |

#### 5.2.2.3. Sprint Backlog 2

El siguiente Sprint Backlog presenta las historias de usuario y tareas planificadas para el Sprint 2, orientado a la implementación del frontend en VUE, la integración con el backend, la mejora de la experiencia de usuario y la consistencia visual de la landing page.

| Sprint # | Sprint 2 | | | | | | |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **User Story** | | **Work-Item / Task** | | | | | |
| **Id** | **Title** | **Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status (To-do / In-Process / To-Review / Done)** |
| **US01** | Autenticación de Usuarios | T001 | Maquetación de vista Login/Auth | Crear la interfaz de inicio de sesión responsiva en Vue.js con soporte para credenciales de usuario. | 3h | Roman Lopez, Miguel Angel Junior | Done |
| **US01** | Autenticación de Usuarios | T002 | Manejo de sesión y almacenamiento local | Implementar la gestión de estado de autenticación (tokens/sesión) y validación de campos obligatorios. | 3h | Roman Lopez, Miguel Angel Junior | Done |
| **US01** | Autenticación de Usuarios | T003 | Redirección por roles | Configurar el enrutamiento según el perfil del usuario autenticado (Gerente, Ingeniero, Inspector). | 2h | Roman Lopez, Miguel Angel Junior | Done |
| **US25** | Registro de Colaboradores y Permisos | T004 | Formulario de registro de colaboradores | Implementar la interfaz para ingresar datos del nuevo colaborador y seleccionar su nivel de acceso. | 3h | Roman Lopez, Miguel Angel Junior | Done |
| **US25** | Registro de Colaboradores y Permisos | T005 | Gestión y modificación de permisos | Desarrollar el componente de tabla con opciones para actualizar los permisos asignados de forma inmediata. | 3h | Roman Lopez, Miguel Angel Junior | Done |
| **US26** | Restricción de Acceso | T006 | Navigation Guards en Vue Router | Implementar guardias de navegación para bloquear rutas no autorizadas según el rol asignado. | 3h | Roman Lopez, Miguel Angel Junior | Done |
| **US26** | Restricción de Acceso | T007 | Renderizado condicional en UI | Deshabilitar u ocultar botones y acciones de escritura para usuarios con permiso "Solo Lectura". | 2h | Roman Lopez, Miguel Angel Junior | Done |
| **US06** | Comparación de Planes de Suscripción | T008 | Vista interactiva de planes SaaS | Maquetar la tabla comparativa de planes (Starter, Professional, Enterprise) con selector de pago mensual/anual. | 3h | Roman Lopez, Miguel Angel Junior | Done |
| **US30** | Creación de Proyecto Vial | T009 | Formulario de alta de obra vial | Diseñar la interfaz para registrar proyectos viales definiendo ubicación, tramos y frentes de trabajo. | 4h | Taza Curay, Eduardo Miguel | Done |
| **US30** | Creación de Proyecto Vial | T010 | Validaciones de formulario de proyecto | Implementar alertas de campos faltantes y validación de coordenadas de tramos viales. | 3h | Taza Curay, Eduardo Miguel | Done |
| **US11** | Visualización General de Proyectos | T011 | Vista de portafolio de proyectos | Maquetar el listado general con estado ambiental, sensores activos, alertas e incidencias pendientes por proyecto. | 4h | Taza Curay, Eduardo Miguel | Done |
| **US12** | Consulta de Resumen de Proyecto | T012 | Modal de resumen ejecutivo | Implementar la vista modal con indicadores consolidados del proyecto seleccionado. | 3h | Taza Curay, Eduardo Miguel | Done |
| **US32** | Búsqueda Global de Proyectos e Incidencias | T013 | Barra de búsqueda centralizada | Desarrollar el buscador global con filtros por código de carretera, frente de trabajo o palabra clave. | 3h | Taza Curay, Eduardo Miguel | Done |
| **US33** | Asociación de Sensores IoT | T014 | Formulario de alta de puntos IoT | Implementar la vista para vincular sensores IoT geolocalizados a tramos viales específicos. | 4h | Taza Curay, Eduardo Miguel | Done |
| **US10** | Consulta de Estado de Sensores IoT | T015 | Listado e indicadores de sensores | Diseñar la vista con estado operativo, ubicación y tipo de parámetro medido por cada sensor. | 3h | Hipolito Salcedo Muñoz, Andy Alfredo | Done |
| **US10** | Consulta de Estado de Sensores IoT | T016 | Detección de sensores sin comunicación | Añadir alertas visuales cuando un sensor no reporte datos dentro del intervalo esperado. | 2h | Hipolito Salcedo Muñoz, Andy Alfredo | Done |
| **US34** | Edición de Ubicación y Umbrales IoT | T017 | Modal de edición de parámetros IoT | Crear la interfaz para ajustar ubicación geográfica y umbrales normativos de alerta del sensor. | 3h | Hipolito Salcedo Muñoz, Andy Alfredo | Done |
| **US09** | Monitoreo de Mediciones en Tiempo Real | T018 | Widgets de telemetría en tiempo real | Implementar tarjetas interactivas que muestren el valor vigente e indicador de última actualización. | 4h | Guillen Chavez, Eduardo Martín | Done |
| **US13** | Dashboard Ambiental de Proyecto | T019 | Layout del Dashboard centralizado | Diseñar el panel de control ambiental organizando tramos y puntos de monitoreo. | 5h | Guillen Chavez, Eduardo Martín | Done |
| **US13** | Dashboard Ambiental de Proyecto | T020 | Gráficos interactivos de indicadores | Integrar gráficos de tendencias para parámetros de aire, ruido, agua y vibraciones. | 4h | Guillen Chavez, Eduardo Martín | Done |
| **US14** | Evolución Histórica de Indicadores | T021 | Filtro por rango de fechas | Implementar controles de selección de fechas y visualización de la serie histórica registrada. | 3h | Guillen Chavez, Eduardo Martín | Done |
| **US15** | Nivel de Riesgo de Indicadores | T022 | Semaforización de riesgo ambiental | Desarrollar componentes visuales para clasificar mediciones en estado Óptimo, Advertencia o Crítico. | 3h | Guillen Chavez, Eduardo Martín | Done |
| **US16** | Consulta de Alertas Generadas | T023 | Bandeja de alertas del proyecto | Implementar la vista detallada de alertas con valor registrado, tramo, sensor y timestamp. | 3h | Guillen Chavez, Eduardo Martín | Done |
| **US17** | Notificación de Alertas Críticas | T024 | Centro de notificaciones en la UI | Desarrollar banners y avisos automáticos para informar inmediatamente al Gerente de Proyecto sobre estados críticos. | 3h | Guillen Chavez, Eduardo Martín | Done |
| **US18** | Registro de Incidencia Ambiental | T025 | Tablero de incidencias | Crear el formulario para registro manual e ingreso automático de incidencias en estado "Pendiente". | 4h | Hipolito Salcedo Muñoz, Andy Alfredo | Done |
| **US19** | Asignación de Responsable | T026 | Modal de asignación de personal | Diseñar la interfaz para asignar responsable a una incidencia y cambiar su estado a "En proceso". | 3h | Hipolito Salcedo Muñoz, Andy Alfredo | Done |
| **US20** | Registro de Acción Correctiva | T027 | Formulario de acciones correctivas | Implementar la vista para registrar la respuesta en campo y actualizar la incidencia a "Atendida". | 3h | Hipolito Salcedo Muñoz, Andy Alfredo | Done |
| **US21** | Actualización de Estado de Incidencia | T028 | Flujo de cierre de incidencias | Desarrollar la validación que exige evidencia previa antes de permitir el estado "Cerrada". | 3h | Hipolito Salcedo Muñoz, Andy Alfredo | Done |
| **US22** | Registro de Evidencia de Campo | T029 | Carga de evidencias fotográficas | Diseñar el módulo para adjuntar fotografías, descripción, fecha, hora y ubicación de la acción. | 4h | Hipolito Salcedo Muñoz, Andy Alfredo | Done |
| **US36** | Comunicación en Incidencias | T030 | Módulo de comentarios e historial | Implementar el timeline de notas y observaciones internas para coordinar equipos en obra. | 3h | Hipolito Salcedo Muñoz, Andy Alfredo | Done |
| **US23** | Historial Ambiental de Proyecto | T031 | Vista cronológica del proyecto | Maquetar el historial consolidado con mediciones, alertas, incidencias y evidencias de un periodo. | 4h | Pancorbo Amorós, Italo Raul | Done |
| **US24** | Generación de Reporte Ambiental | T032 | Módulo de configuración de reportes | Diseñar la vista de selección de rango de fechas y generación del documento de reporte. | 3h | Pancorbo Amorós, Italo Raul | Done |
| **US24** | Generación de Reporte Ambiental | T033 | Previsualización y descarga PDF | Implementar la integración para previsualizar y exportar el informe consolidado oficial. | 4h | Pancorbo Amorós, Italo Raul | Done |
| **US38** | Panel Consolidado de Salud | T034 | Dashboard multi-proyecto | Diseñar el tablero consolidado con el nivel de riesgo global de todas las carreteras en cartera. | 4h | Pancorbo Amorós, Italo Raul | Done |
| **US39** | Visualización de KPIs Ambientales | T035 | Tarjetas analíticas de rendimiento | Implementar indicadores clave (% incidencias cerradas, tiempo de atención de alertas, sensores activos). | 3h | Pancorbo Amorós, Italo Raul | Done |
| **US40** | Control de Versiones de Documentos | T036 | Módulo de gestión documental | Crear la interfaz para subir y gestionar versiones históricas de archivos normativos (PMA, DIA, EIA). | 3h | Pancorbo Amorós, Italo Raul | Done |




#### 5.2.2.7. Software Deployment Evidence for Sprint Review.
<a id="5-2-2-7-software-deployment-evidence-for-sprint-review"></a>


![deploy-evidence](/assets/images/DeployEvidence1.jpeg)

![deploy-evidence](/assets/images/DeployEvidence2.jpeg)

![deploy-evidence](/assets/images/DeployEvidence3.jpeg)


