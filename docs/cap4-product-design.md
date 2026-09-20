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


### 4.3.1. Landing Page Wireframe.
<a id="4-3-1-landing-page-wireframe"></a>

**LADING PAGE WEB**



**Barra de Navegación**:

**Título Principal**:

**Texto**:

**Llamados a la Acción**:

**Elemento Visual**:

**Sección de Pilares de Gestión**:
- **Pilar 1**:
- **Pilar 2**:
- **Pilar 3**:

**Contenido**:

**Flujo de Onboarding**:

- 1:
- 2:
- 3:

**Logotipos**:

**Pie de Página**:


**LADING PAGE MOBILE**



**Cabecera y Navegación**:

**Headline**:

**Imagen de Soporte**:


1. **Pilares de Gestión**:

2. **Beneficios Enumerados**:

3. **Sección de Autoridad Técnica**:


**Flujo de Usuario y Conversión**:

**Testimonios**:

**Logos de Respaldo**:

**Cierre**:

**Newsletter**:


### 4.3.2. Landing Page Mock-up.
<a id="4-3-2-landing-page-mock-up"></a>

**LADING PAGE MOCK-UP WEB**



**Barra de Navegación**:

**Título Principal**:

**Cuerpo de Texto**:

**Llamados a la Acción**:

**Elemento Visual Principal**:

**Sección de Pilares de Gestión**:
- **Pilar 1**:
- **Pilar 2**:
- **Pilar 3**:

**Sección de Transformación y Beneficios**:
- **01. Control**:
- **02. Alineación**:
- **03. Comunicación**:
- **04. Datos**:

**Testimonios**:

**Logotipos**:

**Final**:

**Newsletter**:

**Pie de Página**:


**LADING PAGE MOCK-UP MOBILE**



**Header y Navegación**:

**Título (H1)**:
**Texto**:

**Opciones**:

**Elemento Visual**:

**Cuerpo de Contenidos**:
1. **Pilares de Gestión**:
2. **Beneficios Enumerados (01-04)**:
3. **Autoridad y Respaldo**:

**Onboarding en Pasos**:

**Testimonios**:

**Logos de Respaldo**:

**Cierre**:

**Newsletter**:

**Footer Organizado**:


## 4.4. Web Applications UX/UI Design.
<a id="4-4-web-applications-ux-ui-design"></a>


### 4.4.1. Web Applications Wireframes.
<a id="4-4-1-web-applications-wireframes"></a>

**Web applications** 

 Wireframe - Team Chat Hub (Desktop) 


Wireframe - Quick Reports (Desktop)


Wireframe - Profile & Settings (Desktop)


Wireframe - My Projects (Desktop)


Wireframe - Home Leader Hub (Desktop)


Wireframe - Team Board (Desktop)


Wireframe - Meetings & Agreements (Desktop)


Wireframe - Profile (Desktop)


Wireframe - Resource Planning (Desktop)


Wireframe - Risk & Compliance (Desktop)


Wireframe - Advanced Analytics (Desktop)


Wireframe - Settings (Desktop)


Wireframe - Portfolio Master (Desktop)


Wireframe - Home Leader Hub (Desktop)


**Web applications mobil** 

Wireframe - Team Chat Hub (Mobile)


Wireframe - Quick Reports (Mobile)


Wireframe - My Projects (Mobile)


Wireframe - Profile & Settings (Mobile)


Wireframe - Leader Hub Home (Mobile)


Wireframe - Team Board (Mobile)


Wireframe - Meetings & Agreements (Mobile)


Wireframe - Admin & System (Mobile)


Wireframe - Portfolio Master (Mobile)


Wireframe - Resource Planning (Mobile)


Wireframe - Risk & Compliance (Mobile)


Wireframe - Advanced Analytics (Mobile)


Wireframe - Admin Settings (Mobile)


Wireframe - Executive Profile (Mobile)


## 4.4.2. Web Applications Wireflow Diagrams.
<a id="4-4-2-web-applications-wireflow-diagrams"></a>


## 4.4.3. Web Applications Mock-ups.
<a id="4-4-3-web-applications-mock-ups"></a>

**Versión Desktop Mockups - Líderes y Jefes de Gestión de Proyectos** 

**El usuario inicia con el Login correspondiente colocando sus datos**

**El siguiente paso es escoger el workspace que se adapta mejor al usuario**

**El usuario puede olvidar su contraseña y decide cambiar su contraseña**

**El usuario entra y lo primero que se observa es el Home de la aplicación web**

**Después de presionar Apply Optimization aparece el mensaje Optimization Applied Successfully**

**El usuario se dirige a la sección de su perfil donde puede ver sus datos**

**El usuario desplega la sección Team Board en la cual se observa la función Operativa**

**El usuario despliega la sección Reports donde puede exportar diferentes proyectos**

**El usuario despliega la sección ChatHub donde puede ver los canales de sus compañeros**

**El usuario despliega la sección My Projects donde puede contemplar sus diversos proyectos**

**Aquí el usuario puede ir a Team Heatmap de un proyecto y ver el Resource Management**

**El usuario también puede ver los Quick Reports en la plataforma**

**El usuario despliega la sección Budgets y contempla la función Executive Health Summary**

**El usuario despliega la sección Meetings y en ella puede ver los Meetings y Agreements**

**El usuario puede exportar minutos de reuniones en los formatos visibles**

**El usuario se dirige a Schedule New Meeting para programar alguna reunión**


**Versión Desktop Mockups - Empresas Medianas y Grandes con Múltiples Portafolios**

**El usuario inicia con el Login correspondiente colocando sus datos**

**El siguiente paso es escoger el workspace que se adapta mejor al usuario**

**El usuario puede olvidar su contraseña y decide cambiar su contraseña**

**El usuario decide ir a la sección de Projects y seleccionar su Portafolio**

**El usuario se dirige a la seccipin de Resource Planning donde mira el Team Bandwidth Analysis**

**El usuario también se puede dirigir a la sección de Team Optimization para ver los resultados**

**El usuario entra y lo primero que se observa es el Home de la aplicación web**

**El usuario se dirige a la sección de Portfolio Results y contempla su análisis**

**El usuario se dirige a la sección de Risk & Compliance donde contempla el Heatmap**

**El usuario se dirige a Action Plans para la mitigación de riesgos**

**El usuario se dirige a la sección de analytics donde aprecia el Advanced Analytics**

**El usuario puede compartir su perfil a través de su configuración**

**El usuario se dirige a la sección de su Perfil y puede ver su información personal**

**El usuario se dirige a la herramienta de Settings**

**Puede dirigirse a la configuración de integraciones**

**Puede dirigirse a la configuración de los miembros del equipo**

**Puede dirigirse a la configuración de notificaciones**


**Versión Mobile Mockups - Líderes y Jefes de Gestión de Proyectos** 

**El usuario inicia con el Login correspondiente colocando sus datos**

**El siguiente paso es escoger el workspace que se adapta mejor al usuario**

**El usuario puede olvidar su contraseña y decide cambiar su contraseña**

**El usuario desplega la sección Board en la cual se observa la función Operativa**

**El usuario puede añadir una nueva tarea si el lo desea**

**El usuario se dirige a la sección de Meetings y puede acceder a múltiples funcionalidades**

**En la sección Log el usuario puede elaborar una nota rápida del registro para un proyecto**

**El usuario puede acceder a Calendar donde se puede apreciar mejor el calendario del equipo**

**El usuario se dirige a la sección de Chat donde puede acceder a la funcionalidad de Chat Hub**

**El usuario al presionar Attach Files puede subir archivos de manera adjunta**

**El usuario al desplegar la sección Reports puede realizar un generador de reportes**

**El usuario puede seleccionar un proyecto de la lista en donde puede seleccionar un proyecto de la lista**

**El usuario puede descargar el reporte en formato PDF**

**El usuario se dirige a la sección de su perfil y puede gestionar su información**

**El usuario puede dirigirse a la sección de Security y ver el tema de la autenticación**

**El usuario puede ver los detalles en su cuenta y a la vez puede gestionarlos**

**El usuario se dirige a Notifications Preferences para ver si quiere o no recibir estas mismas**

**El usuario despliega la opción de ver sus proyectos donde se aprecia mejor su organización**

**El usuario al entrar en la sección Calendar puede ver el calendario del equipo**

**El usuario entra y lo primero que se observa es el Home de la aplicación mobile**


**Versión Mobile Mockups - Empresas Medianas y Grandes con Múltiples Portafolios** 

**El usuario inicia con el Login correspondiente colocando sus datos**

**El siguiente paso es escoger el workspace que se adapta mejor al usuario**

**El usuario puede olvidar su contraseña y decide cambiar su contraseña**

**El usuario puede dirigirse a la sección del Portfolio Govemance**

**El usuario se dirige a la sección de Admin & Systems Control**

**El usuario puede añadir una entidad para dicho portafolio que seleccione**

**El usuario se dirige a la función de Advanced Analytics**

**En base a lo que el usuario selecciono se genera un pronóstico**

**El usuario se dirige a la sección de Resources y va a la planificación de recursos**

**El usuario selecciona la sección de Risks y selecciona la función Risk & Compliance**

**El usuario por otro lado puede iniciar una auditoría para los proyectos**

**El usuario se dirige a la sección de Strategy y puede seleccionar la función del informe de la estrategia de contratación**

**El usuario visita su cuenta mobile y selecciona Account Settings**

**El usuario puede apreciar mejor su perfil y gestionarlo**

**El usuario puede visualizar a los Team Members de cada proyecto**

**El usuario se dirige a la sección Integrations de los proyectos**


<div style="text-align: left; max-width: 900px; margin: 0 auto;">

# 4.4.4. Web Applications User Flow Diagrams.
<a id="4-4-4-web-applications-user-flow-diagrams"></a>

## Segmento 1: Líderes y Jefes de Gestión de Proyectos
**User Flow Web**<br>

**El usuario valida sus credenciales al ingresar a Vantage PMO**

**El usuario escoge su espacio de trabajo a su comodidad**

**El usuario puede ir a su perfil para gestionar alguna característica**

**El usuario puede acceder a la sección del Team Board y sus funciones**

**El usuario accede tanto al Chat Hub de los proyectos y Team Headmap**

**El usuario puede ver sus proyectos activos y a detalle**

**El usuario accede a las secciones tanto de Quick Reports y Budgets**

**El usuario puede acceder a la sección de Meetings & Agreements**

**También puede optar por presionar el botón Schedule Meeting**


**User Flow Mobile**<br>

**El usuario valida sus credenciales al ingresar a Vantage PMO**

**El usuario escoge su espacio de trabajo a su comodidad**

**Este es el menú para el usuario donde aparecen múltiples opciones**

**Aquí el usuario accede a la sección Board la cual permite añadir tareas**

**El usuario puede acceder a la sección del chat y visita su perfil**

**El usuario accede a algunas opciones del System Settings**

**El usuario presiona Notification Preferences, otra función de System Settings**

**El usuario puede acceder a la sección de Reports donde hay diversas funcionalidades**

**El usuario accede a la sección Projects donde se observa el Team Bandwidth**

**El usuario puede acceder a la sección Meetings & Agreements**

**El usuario puede acceder a la sección Log Quick Note y Attach Files**

**El usuario puede acceder a la sección Schedule New junto con la de Projects**


## Segmento 2: Empresas Medianas y Grandes con Múltiples Portafolios
**User Flow Web**<br>

**El usuario valida sus credenciales al ingresar a Vantage PMO**

**El usuario escoge su espacio de trabajo a su comodidad y aparece la pantalla principal**

**El usuario puede acceder a la sección de Resource Planning**

**El usuario puede acceder a la sección Account y el usuario puede compartir su perfil**

**El usuario puede acceder a la sección de Settings**

**El usuario puede acceder a más funciones de la sección Settings**

**El usuario puede acceder a la sección de Analysis y se dirige a su Portafolio**

**El usuario puede acceder a la sección Projects**

**El usuario puede acceder a la sección Risk & Compliance, el usuario accede a más funciones**


**User Flow Mobile**<br>

**El usuario valida sus credenciales al ingresar a Vantage PMO**

**El usuario escoge su espacio de trabajo a su comodidad**

**El usuario se encuentra en la pantalla de inicio**

**El usuario puede acceder a la sección Healthy, también a otras funciones**

**El usuario al presionar Add Entity, continua con las Advanced Analytics**

**El usuario puede seleccionar Generate Forecast**

**El usuario puede acceder a Capacity & Bandwidth Analysis**

**El usuario presiona Initiate Audit y se va a Hiring Strategy Report**

**El usuario se dirige a la configuración de la cuenta, para seleccionar su información**

**El usuario puede ver a los Team Members, tambien el architect de si mismo**

## 4.5. Web Applications Prototyping.
<a id="4-5-web-applications-prototyping"></a>



## 4.6. Domain-Driven Software Architecture.
<a id="4-6-domain-driven-software-architecture"></a>

### 4.6.1. Design-Level EventStorming.
<a id="4-6-1-design-level-eventstorming"></a>

**Global**



*Leyenda*
<table align="center">
  <tr>
    <td align="center">
      Aggregate
    </td>
    <td align="center">
      Command
    </td>
    <td align="center">
      Domain Event
    </td>
    <td align="center">
      External System
    </td>
  </tr>
  <tr>
    <td align="center">
      Policy
    </td>
    <td align="center">
      Question / Risk
    </td>
    <td align="center">
      User Actor
    </td>
    <td align="center">
      View / Read Model
    </td>
  </tr>
</table>

**IAM(Identity and Access Management)**



**Project Management**



**Task & Collaboration**



**Governance & Risk**



**Resource & Capacity**



**Document Management**



**Profile Management**



**System Administration**



**Analytics & Reporting**



<div style="text-align: left; max-width: 900px; margin: 0 auto;">

### 4.6.2. Software Architecture Context Diagram.
El Diagrama de Contexto representa la vista de más alto nivel de EcoRoad, detallando cómo el sistema interactúa con los usuarios y sistemas externos sin profundizar en detalles técnicos.
<a id="4-6-2-software-architecture-context-diagram"></a>

#### Sistema Central



* **EcoRoad**: Solución integral para la gestión y monitoreo ambiental de proyectos de infraestructura vial, orientada a centralizar la información, detectar riesgos ambientales y facilitar el cumplimiento de las normativas.

#### Usuarios

##### Segmento A: Empresas Constructoras Viales


* Gestionan proyectos de construcción y mantenimiento de carreteras.
* Supervisan las condiciones ambientales de sus proyectos.
* Identifican y atienden riesgos e incidentes ambientales.
* Realizan seguimiento de medidas de mitigación y cumplimiento normativo.

##### Segmento B: Consultoras y Supervisoras Ambientales



* Supervisan el cumplimiento ambiental de múltiples proyectos.
* Realizan inspecciones y monitoreo de indicadores ambientales.
* Validan evidencias y acciones de mitigación.
* Elaboran reportes y dan seguimiento a las incidencias detectadas.

#### Sistemas Externos



* **Servicio de Mapas y Geolocalización**
  Permite visualizar proyectos, puntos de monitoreo e incidencias ambientales mediante información geográfica.

* **Servicio Meteorológico**
  Proporciona información climática que permite relacionar las condiciones ambientales con posibles riesgos dentro de los proyectos.

* **Servicio de Notificaciones**
  Permite enviar alertas automáticas a los responsables cuando se detectan riesgos, incidencias o condiciones que requieren atención.

#### Resumen de Interacción



* Los usuarios (Segmento A y B) interactúan directamente con **EcoRoad**.
* **EcoRoad** centraliza la información ambiental y gestiona:

  * Monitoreo de indicadores ambientales.
  * Registro y seguimiento de incidencias.
  * Acciones de mitigación y responsables.
  * Evidencias y trazabilidad de las actividades.
* **EcoRoad** integra servicios externos para:

  * Geolocalización mediante servicios de mapas.
  * Consulta de condiciones meteorológicas.
  * Envío de notificaciones y alertas.
* Los dispositivos **IoT** pueden enviar datos de sensores ambientales a EcoRoad, permitiendo detectar automáticamente condiciones fuera de los parámetros establecidos y generar alertas o incidencias para su atención.


### 4.6.3. Software Architecture Container Diagrams.
Este nivel desglosa el sistema EcoRoad en aplicaciones y componentes independientes, especificando las tecnologías y responsabilidades principales de cada contenedor que conforma la solución.

Web Application


Aplicación web desarrollada con Vue.js, encargada de proporcionar una interfaz interactiva para empresas constructoras viales y consultoras ambientales.

Permite:

Visualizar dashboards de monitoreo ambiental.
Gestionar proyectos y puntos de monitoreo.
Consultar incidencias y alertas.
Registrar y supervisar acciones de mitigación.
Visualizar información geolocalizada.
Consultar evidencias y generar reportes.

La aplicación se comunica con el backend mediante peticiones HTTPS hacia la API RESTful.

API Application


Construida en C# utilizando ASP.NET Core, constituye el núcleo de EcoRoad y centraliza la lógica de negocio y el procesamiento de la información ambiental.

Este componente se encarga de:

Gestionar proyectos y puntos de monitoreo.
Procesar información proveniente de los dispositivos IoT.
Analizar los valores de los indicadores ambientales.
Comparar los datos recibidos con umbrales configurados.
Generar automáticamente alertas e incidencias.
Gestionar acciones de mitigación y responsables.
Exponer endpoints RESTful para la Web Application.
Integrarse con servicios externos de mapas, clima y notificaciones.
IoT Monitoring


Componente encargado de recibir y gestionar los datos provenientes de sensores ambientales instalados en los proyectos viales.

Los dispositivos IoT pueden monitorear variables como:

Calidad del aire.
Nivel de ruido.
Temperatura.
Humedad.
Calidad del agua.

Los datos recopilados son enviados hacia la API Application, donde son procesados y evaluados según los parámetros ambientales establecidos. Cuando se detecta un valor fuera del rango permitido, EcoRoad puede generar automáticamente una alerta e incidencia para su atención.

Database


Motor de base de datos relacional basado en MySQL, responsable de almacenar de forma persistente la información generada por EcoRoad.

Garantiza:

Integridad de la información de los proyectos.
Persistencia de los datos de monitoreo ambiental.
Registro histórico de incidencias y alertas.
Trazabilidad de las acciones de mitigación.
Almacenamiento de responsables, evidencias y estados.
Consulta histórica para la generación de reportes.

La API Application es responsable de gestionar las operaciones de lectura y escritura sobre la base de datos, evitando que la Web Application acceda directamente a ella.


### 4.6.4. Software Architecture Components Diagrams.
<a id="4-6-4-software-architecture-components-diagrams"></a>

En el nivel de componentes se detalla la descomposición interna de los contenedores de EcoRoad, mostrando los bloques estructurales que conforman la solución y las relaciones entre ellos. Debido a que la Web Application y la Database pueden ser complementadas mediante diagramas específicos de frontend y base de datos, esta sección pone especial énfasis en el contenedor API Application, donde se concentra la lógica de negocio y el procesamiento de la información ambiental.

El diagrama de componentes de la API Application organiza la arquitectura interna de EcoRoad de acuerdo con los principales contextos funcionales del dominio. Cada módulo backend representa un componente encargado de una responsabilidad específica:

Project Management Backend: administra los proyectos viales, sus datos generales, ubicaciones, estados y puntos de monitoreo asociados. Permite crear, consultar, actualizar y gestionar la información de los proyectos.
Environmental Monitoring Backend: procesa y administra los indicadores ambientales registrados en los proyectos, permitiendo consultar mediciones históricas y actuales de variables como calidad del aire, ruido, temperatura, humedad y calidad del agua.
IoT Integration Backend: gestiona la comunicación entre EcoRoad y los dispositivos IoT instalados en los proyectos. Recibe los datos provenientes de los sensores, valida las mediciones y las incorpora al sistema para su posterior análisis.
Risk & Incident Backend: analiza las mediciones ambientales y las compara con los parámetros establecidos. Cuando identifica condiciones que superan los límites permitidos, genera alertas e incidencias ambientales de manera automática.
Mitigation Backend: administra las acciones correctivas y medidas de mitigación asociadas a las incidencias. Permite asignar responsables, establecer fechas límite, actualizar estados y realizar el seguimiento hasta la resolución del problema.
Evidence Backend: gestiona las evidencias relacionadas con inspecciones, incidencias y acciones de mitigación, permitiendo registrar fotografías, documentos y otros archivos que respalden las actividades realizadas.
Reports Backend: centraliza la generación de reportes ambientales y de cumplimiento, utilizando la información almacenada de proyectos, mediciones, incidencias, acciones y evidencias.
Geolocation Backend: administra la información geográfica de proyectos, puntos de monitoreo e incidencias, integrándose con el servicio externo de mapas y geolocalización para representar visualmente la información.
Weather Backend: obtiene información meteorológica mediante el servicio externo correspondiente, permitiendo complementar el análisis de las condiciones ambientales y riesgos asociados a cada proyecto.
Notification Backend: gestiona el envío de alertas y notificaciones a los responsables cuando se generan incidencias, se detectan valores fuera de los parámetros establecidos o existen acciones de mitigación pendientes.
Shared Backend: proporciona componentes comunes, utilidades, validaciones, clases base, manejo de errores y mecanismos de infraestructura reutilizados por los demás módulos de la API.

En el diagrama se refleja cómo:

La Web Application consume los servicios expuestos por los componentes de la API Application mediante endpoints RESTful, permitiendo gestionar proyectos, monitoreo, incidencias, acciones de mitigación, evidencias y reportes.
El IoT Integration Backend recibe las mediciones provenientes del IoT Monitoring, validando y procesando los datos antes de almacenarlos.
El Environmental Monitoring Backend administra las mediciones ambientales y trabaja junto con el Risk & Incident Backend para identificar valores que excedan los umbrales establecidos.
El Risk & Incident Backend genera incidencias automáticamente cuando se detectan condiciones ambientales fuera de los parámetros permitidos y comunica estos eventos al Notification Backend.
El Mitigation Backend gestiona las acciones necesarias para resolver las incidencias, mientras que el Evidence Backend permite registrar evidencias que demuestren el cumplimiento de dichas acciones.
El Project Management Backend, Environmental Monitoring Backend, Risk & Incident Backend, Mitigation Backend, Evidence Backend y Reports Backend acceden a la Database para leer y escribir la información correspondiente a sus responsabilidades.
El Geolocation Backend se integra con el Servicio de Mapas y Geolocalización para obtener información geográfica y representar proyectos, puntos de monitoreo e incidencias.
El Weather Backend se comunica con el Servicio Meteorológico para obtener información climática utilizada como complemento para el monitoreo y análisis de riesgos.
El Notification Backend se integra con el Servicio de Notificaciones para enviar alertas a los responsables de los proyectos.
Todos los componentes backend pueden reutilizar las capacidades proporcionadas por el Shared Backend, favoreciendo la consistencia, reutilización de código y reducción de duplicidad.

De esta manera, el Component Diagram complementa los diagramas de clases y de base de datos de EcoRoad, mostrando cómo la API Application se divide en componentes coherentes con las funcionalidades principales del dominio y cómo estos colaboran entre sí para implementar el monitoreo ambiental, la detección de riesgos, la gestión de incidencias y las acciones de mitigación dentro de los proyectos viales.



## 4.7. Software Object-Oriented Design.
<a id="4-7-software-object-oriented-design"></a>

### 4.7.1. Class Diagrams.
<a id="4-7-1-class-diagrams"></a>
Se centra en la definición de diagramas de clases, la interacción entre objetos y la aplicación de principios.

### Bounded Context 1 - Suscriptions and Payment:
![Class Diagram - EcoRoad](/assets/images/chapter4/EcoRoad-CD1.png)
### Bounded Context 2 - Identity and Access Management:
![Class Diagram - EcoRoad](/assets/images/chapter4/EcoRoad-CD2.png)
### Bounded Context 3 - Project and Road Site Management:
![Class Diagram - EcoRoad](/assets/images/chapter4/EcoRoad-CD3.png)
### Bounded Context 4 - Monitoring Asset and Deployment:
![Class Diagram - EcoRoad](/assets/images/chapter4/EcoRoad-CD4.png)
### Bounded Context 5 - Environmental Monitoring:
![Class Diagram - EcoRoad](/assets/images/chapter4/EcoRoad-CD5.png)
### Bounded Context 6 - Alerting and Risk Evaluation:
![Class Diagram - EcoRoad](/assets/images/chapter4/EcoRoad-CD6.png)
### Bounded Context 7 - Incident and Remediation Management:
![Class Diagram - EcoRoad](/assets/images/chapter4/EcoRoad-CD7.png)
### Bounded Context 8 - Compliance and Reporting:
![Class Diagram - EcoRoad](/assets/images/chapter4/EcoRoad-CD8.png)




## 4.8. Database Design.
<a id="4-8-database-design"></a>

### 4.8.1. Database Diagrams.
<a id="4-8-1-database-diagrams"></a>

### Bounded Context 1 - Suscriptions and Payment:
![Database Diagram- EcoRoad](/assets/images/chapter4/DBDiagram1.jpeg)
### Bounded Context 2 - Identity and Access Management:
![Database Diagram - EcoRoad](/assets/images/chapter4/DBDiagram2.jpeg)
### Bounded Context 3 - Project and Road Site Management:
![Database Diagram- EcoRoad](/assets/images/chapter4/DBDiagram3.jpeg)
### Bounded Context 4 - Monitoring Asset and Deployment:
![Database Diagram- EcoRoad](/assets/images/chapter4/DBDiagram4.jpeg)
### Bounded Context 5 - Environmental Monitoring:
![Database Diagram - EcoRoad](/assets/images/chapter4/DBDiagram5.jpeg)
### Bounded Context 6 - Alerting and Risk Evaluation:
![Database Diagram - EcoRoad](/assets/images/chapter4/DBDiagram6.png)
### Bounded Context 7 - Incident and Remediation Management:
![Database Diagram - EcoRoad](/assets/images/chapter4/DBDiagram6.jpeg)
### Bounded Context 8 - Compliance and Reporting:
![Database Diagram - EcoRoad](/assets/images/chapter4/DBDiagram8.jpeg)


