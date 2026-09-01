# Requirements Specification
<a id="3-requirements-specification"></a>
## 3.1. User Stories
<a id="3-1-user-stories"></a>

## 1. Landing Page (Presentación y Conversión)
| ID | Título | Descripción | Criterios de Aceptación | Relacionado con |
| :--- | :--- | :--- | :--- | :--- |
|US01 |Autenticación (acceso) |Como usuario de EcoRoad, quiero poder inicar sesión para accdeder a mis cuentas y perfiles | Dado que el usuario ingresa credenciales, cuando son válidas, entonces se redirige al dashboard.| EP08: Usuario|
| US02| Demo de Tablero Geolocalizado| Como responsable de gestión ambiental, quiero ver una vista previa del mapa de indicadores para entender cómo se visualizaría mi obra.|Dado que el usuario navega la landing, cuando llega a "Funciones", entonces observa un mapa demo con puntos de monitoreo simulados. | EP05: Mapa|
| US03| Explicación de planes| Como gerente de carrera de proyectos quiero comparar los planes Base, Profesional y Enterprise para elegir el que se ajuste a mi empresa. | Dado que el usuario llega a la sección "Planes", cuando la visualiza, entonces se muestra una tabla comparativa de funcionalidades por plan.| EP09: Suscripción|
| US04|CTA Segmento Consultora | Como responsable de gestión ambiental quiero un botón claro para probar la plataforma, para evaluar si resuelve mi problema de monitoreo.| Dado que el usuario está en la sección dirigida a consultoras, cuando hace clic en "Monitorea tu proyecto", entonces es redirigido al registro/login de la Web App.|EP08: Usuario |
| US05|CTA Segmento Empresa Multi-Proyecto  | Como gerente de carrera de proyectos quiero un botón dirigido a gestión multi-proyecto para acceder a la vista que necesito. |Dado que el usuario está en la sección dirigida a empresas con múltiples proyectos, cuando hace clic en "Gestiona tu cartera", entonces es redirigido al dashboard multiproyecto después de haber sido logeado. | EP06: Dashboard|
| US06| Caso de Uso / Testimonio| Como usuario de EcoRoead quiero ver un caso de éxito o cifra de impacto para confiar en la efectividad de la plataforma.| Dado que el usuario hace scroll en la landing, cuando llega a la sección de impacto, entonces ve métricas ilustrativas.|EP07: Reporte |
|US07 | Notificaciones Push Landing| Como usuario de EcoRoad quiero aceptar notificaciones del navegador para recibir alertas de incumplimientos sin ingresar a la plataforma.| Dado que el usuario entra al sitio, cuando aparece el prompt de permiso, entonces el sistema registra la suscripción push.| EP03: Alerta|
| US08|Formulario de Contacto Comercial |Como gerente de carrera de proyectos quiero dejar mis datos de contacto para que ventas me contacte con una propuesta personalizada. | Dado que el usuario completa el formulario, cuando lo envía, entonces se registra el lead y se muestra confirmación.| EP09: Suscripción|


---

## 2. Web Application (Frontend Interactivo)
| ID | Título | Descripción | Criterios de Aceptación | Relacionado con |
| :--- | :--- | :--- | :--- | :--- |
| US09|Formulario de Registro de Indicador | Como responsable de gestión ambiental quiero llenar un formulario validado para registrar mediciones sin enviar errores al servidor.| Dado que un campo numérico es obligatorio, cuando se deja vacío o fuera de rango, entonces el botón "Guardar" se deshabilita.|EP02: Indicador |
| US10| Tarjetas de Proyecto (Cards)| Como usuario de EcoRoad quiero ver tarjetas visuales de cada proyecto para entender su estado ambiental de un vistazo.|Dado que se carga el portafolio, cuando llegan los datos, entonces se renderiza una Card por proyecto con semáforo de estado (verde/amarillo/rojo). | EP06: Dashboard|
| US11|	Tablero Kanban de Incidencias |Como responsable de gestión ambiental, quiero mover incidencias entre columnas (Abierta/En revisión/Resuelta) para gestionar mi flujo visualmente. |Dado que se arrastra una incidencia, cuando se suelta en otra columna, entonces el estado cambia y se persiste | EP04: Incidencia|
|US12 |	Vista de Mapa Interactivo |Como responsable de gestión ambiental quiero ver un mapa con pines de colores por punto de monitoreo para identificar zonas críticas rápidamente. | Dado que se cargan los puntos del proyecto, cuando el mapa renderiza, entonces cada pin muestra color según nivel de riesgo del indicador.| EP05: Mapa|
| US13|	Filtro por Tipo de Indicador | Como responsable de gestión ambiental quiero filtrar el mapa/dashboard por tipo de indicador (aire, ruido, agua) para enfocar mi revisión.|Dado que hay indicadores de varios tipos, cuando se selecciona un filtro, entonces la vista se actualiza al instante. | EP02: Indicador|
|US14 |	Adjuntar Evidencia Fotográfica |Como responsable de gestión ambiental quiero arrastrar fotos al navegador para adjuntarlas como evidencia de una medición. | Dado que el archivo está en el dispositivo, cuando se suelta o selecciona, entonces inicia la barra de progreso de subida.| EP10: Documento|
|US15 | Barra de Progreso de Cumplimiento|Como jefe de proyecto, quiero ver una barra de progreso del % de indicadores dentro de norma para medir el avance rápidamente. | Dado que se actualizan indicadores, cuando cambia el estado, entonces la barra se recalcula.| EP06: Dashboard|
| US16| Feed de Comentarios en Incidencia| Como usuario de EcoRoad quiero ver el historial de comentarios de una incidencia para entender el contexto de su seguimiento.| Dado que hay mensajes previos, cuando se abre la incidencia, entonces se visualizan en formato de burbujas de texto con fecha y autor.| EP04: Incidencia|
|US17 | Alertas y Notificaciones| Como usuario de EcoRoad quiero un icono de notificaciones para ver alertas de incumplimientos recientes.| Dado que llega una nueva alerta, cuando el usuario ve el header, entonces la campana muestra un punto rojo con el conteo.|EP03: Alerta |
|US18 |Tabla de Incidencias Críticas | Como gerente de carrera de proyectos quiero una tabla con filas resaltadas para identificar las incidencias críticas de un vistazo.|Dado que la severidad es alta, cuando se renderiza la fila, entonces el fondo se pinta de rojo. | EP04: Incidencia|
| US19| Selector de Rango de Fechas| Como usuario de EcoRoad, quiero elegir un rango de fechas para revisar el histórico de mediciones de un periodo específico.| Dado que se abre el selector, cuando se elige un rango, entonces el dashboard filtra los datos a ese periodo.| EP06: Dashboard|
| US20|Edición Visual de Punto de Monitoreo | Como responsable de gestión ambiental quiero un botón de editar en cada punto de monitoreo para corregir su ubicación o umbral normativo.| Dado que el usuario presiona "Editar", cuando guarda, entonces la UI se actualiza sin recargar la página. | EP01: Proyecto|
|US21 | Login Minimalista|Como usuario de EcoRoad quiero una interfaz de login minimalista para reducir la fricción al entrar a la plataforma. | Dado que el usuario carga la URL, cuando no hay sesión activa, entonces ve un login centrado y limpio.| EP08: Usuario|
|US22 |	Vista de Lista de Proyectos |Como gerente de carrera de proyectos quiero una vista de lista compacta para ver más proyectos en una sola pantalla. | Dado que el usuario cambia la vista, cuando se activa "Lista", entonces las tarjetas se convierten en filas. |EP01: Proyecto |
| US23| Selector de Color de Marca|Como administrador de cuenta Enterprise, quiero elegir el color corporativo para que el dashboard refleje la identidad de mi empresa. | Dado que se abre configuración, cuando se elige un color, entonces los elementos de UI cambian de tono.| EP09: Suscripción|


---

## 3. RESTful API (Backend & Lógica de Negocio)
| ID | Título | Descripción | Criterios de Aceptación| Relacionado con |
| :--- | :--- | :--- | :--- | :--- |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |

---

## 4. Requerimientos de Negocio Compartidos (Fullstack)
| ID | Título | Descripción | Criterios de Aceptación| Relacionado con |
| :--- | :--- | :--- | :--- | :--- |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |

---

### 3.2. Impact Mapping
<a id="3-2-impact-mapping"></a>

## IMPACT MAPPING 1


## IMPACT MAPPING 2


### 3.3. Product Backlog
<a id="3-3-product-backlog"></a>

| # Orden | User Story Id | Título | Descripción | Story Points (1/2/3/5/8) |
| :--- | :--- | :--- | :--- | :--- |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |