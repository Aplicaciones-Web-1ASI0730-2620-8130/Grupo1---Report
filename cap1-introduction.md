# Capítulo 1

## Introducción

El presente proyecto tiene como finalidad el diseño, desarrollo e implementación de una solución **HaaS/SaaS** (Hardware as a Service + Software as a Service), compuesta por un RESTful API de elaboración interna y una Web Application integrada con dicho API, con el objetivo de resolver problemáticas reales del sector de infraestructura vial en el ámbito de la gestión y el cumplimiento ambiental. Esta solución se construye bajo un enfoque de ingeniería de software moderna, incorporando metodologías ágiles, diseño centrado en el usuario (Lean UX) y una arquitectura orientada a servicios.

En el contexto actual, las empresas constructoras y las consultoras/supervisoras ambientales que participan en proyectos viales enfrentan desafíos relacionados con el registro, procesamiento y control en tiempo real de indicadores ambientales (aire, ruido, agua), especialmente en obras donde aún predominan procesos manuales, semi-digitalizados o dependientes de reportes que pueden ser alterados o entregados fuera de tiempo. Estas limitaciones generan retrasos en la detección de incumplimientos normativos, mayor exposición a sanciones, procesos de auditoría lentos y costosos, y una desconfianza estructural entre quien ejecuta la obra y quien la fiscaliza.

Frente a este escenario, el presente proyecto propone el desarrollo de **EcoRoad**, un ecosistema digital que centraliza —mediante una red propia de sensores IoT— el registro de indicadores ambientales, automatiza la detección de incumplimientos normativos mediante un motor de alertas preventivas, y visualiza en tiempo real el estado ambiental de múltiples proyectos viales, contribuyendo a la mejora de la eficiencia operativa de las constructoras y a la reducción del riesgo regulatorio y de esfuerzo de fiscalización de las supervisoras ambientales.

## 1.1 Startup Profile

La presente sección describe el contexto general de la startup responsable del desarrollo de la solución propuesta. Se presenta una visión general de la organización, su enfoque tecnológico y propuesta de valor, así como la caracterización de los integrantes del equipo, destacando sus perfiles y roles dentro del proyecto.

### 1.1.1 Descripción de la Startup

**Kaimán** es una startup tecnológica enfocada en el desarrollo de soluciones digitales bajo un modelo híbrido **HaaS/SaaS**, orientadas a la gestión y el cumplimiento ambiental en el sector de infraestructura vial. Su propuesta de valor se centra en transformar el registro manual, disperso y potencialmente manipulable de datos ambientales en un ecosistema automatizado en tiempo real, alimentado por una red propia de sensores IoT, accesible, escalable y adaptable a distintos tamaños de operación empresarial.

El nombre **Kaimán** hace alusión al caimán como especie bioindicadora: su presencia y bienestar reflejan el equilibrio ambiental del ecosistema que habita, de la misma manera en que la plataforma desarrollada por la startup busca reflejar, en tiempo real y con datos inalterables, el estado de salud ambiental de cada proyecto vial que monitorea, actuando como un observador neutral entre las partes.

El modelo de negocio de Kaimán es inherentemente escalable y de **doble ingreso (dual revenue)**: la plataforma vende suscripciones independientes a los dos actores que operan sobre una misma obra vial —la empresa constructora y la empresa supervisora/consultora ambiental— cada una con un módulo exclusivo, financieramente separado, sostenido mediante planes segmentados (Base, Profesional y Enterprise) que permiten el crecimiento de la startup a la par del crecimiento de sus clientes, sin incrementos proporcionales en los costos operativos.

En el marco de este proyecto, la startup desarrolla **EcoRoad**, una plataforma HaaS/SaaS que provee tanto el hardware de sensores ambientales como el software de gestión, dirigida principalmente a empresas constructoras y empresas supervisoras/consultoras ambientales que buscan, respectivamente, evitar infracciones normativas y automatizar la fiscalización de obras viales.

#### Misión

Desarrollar soluciones tecnológicas que permitan a las empresas constructoras y a las empresas supervisoras ambientales del sector vial optimizar el monitoreo, control y cumplimiento de sus obligaciones ambientales, mediante datos captados por sensores IoT propios, en tiempo real, automatización de alertas preventivas y visualización geolocalizada, actuando como árbitro tecnológico neutral entre ambas partes.

#### Visión

Ser la plataforma HaaS/SaaS de referencia en Latinoamérica para la gestión y fiscalización ambiental de proyectos de infraestructura vial, destacando por su innovación, escalabilidad, y por ofrecer datos ambientales inalterables que generan confianza mutua entre constructoras y entes fiscalizadores.

### 1.1.2. Perfiles de los Miembros del Equipo

| Foto | Apellido y Nombre |
| --- | --- |
| | Eduardo Martín Guillén Chávez |
| | Andy Alfredo Hipolito Salcedo Muñoz |
| | |
| | |

## 1.2 Solution Profile

**EcoRoad** es una plataforma digital integral basada en un modelo **HaaS/SaaS**, diseñada para dar soporte a los procesos de monitoreo, control, mitigación y auditoría ambiental en proyectos de infraestructura vial. A través de una red propia de sensores IoT (calidad del aire, ruido y agua/suelo), permite a las empresas constructoras recibir alertas preventivas y gestionar su mitigación operativa, y a las empresas supervisoras/consultoras ambientales fiscalizar el cumplimiento normativo con datos inalterables y generar reportes oficiales, todo visualizado en tiempo real sobre un mapa geolocalizado.

### 1.2.1 Antecedentes y Problemática

La actividad constructora es uno de los motores más dinámicos de la economía peruana, con la obra pública —donde la infraestructura vial tiene un peso importante— como uno de los principales impulsores del crecimiento sectorial (CAPECO, 2025). La ejecución de estos proyectos está sujeta a un marco normativo ambiental cada vez más exigente, fiscalizado para el subsector transportes por la Dirección de Gestión Ambiental del MTC, mientras que la elaboración de los instrumentos de gestión ambiental requeridos recae en consultoras inscritas en el Registro Nacional de Consultoras Ambientales (RNCA) de SENACE, que agrupa a 1,293 consultoras habilitadas a nivel nacional (SENACE, 2024). A pesar de este marco, la digitalización del monitoreo ambiental en obra sigue siendo incipiente —y donde existe, suele depender de reportes entregados por la propia constructora, lo cual introduce un problema de confianza en los datos—, mientras el OEFA avanza hacia una fiscalización más estricta apoyada en monitoreo continuo (OEFA, 2025).

#### What / ¿QUÉ?

EcoRoad busca resolver la fragmentación, el registro manual y la falta de confiabilidad de los datos ambientales durante la ejecución de proyectos viales, integrando una red de sensores IoT propios, tableros geolocalizados en tiempo real, un motor automatizado de alertas preventivas e incidencias, y un dashboard de control multi-proyecto, todo en un único sistema con módulos independientes para constructoras y supervisoras.

#### When / ¿CUÁNDO?

Esta necesidad es crítica en el contexto actual, en el que la fiscalización ambiental avanza hacia una mayor exigencia tecnológica, la reactivación de la inversión vial incrementa el número de obras activas que requieren monitoreo simultáneo, y crece la exigencia de trazabilidad y confiabilidad de los datos ambientales presentados ante entidades reguladoras.

#### Where / ¿DÓNDE?

Ocurre principalmente en los proyectos de infraestructura vial ejecutados en el Perú, tanto en zonas urbanas como en tramos interprovinciales —donde se instala la red de sensores IoT—, así como en las oficinas centrales de las empresas constructoras y supervisoras que gestionan y auditan dichos proyectos de forma remota.

#### Who / ¿QUIÉN?

Afecta principalmente a las **empresas constructoras** que ejecutan las obras viales y deben evidenciar el cumplimiento ambiental ante entidades fiscalizadoras (MTC, OEFA), y a las **empresas supervisoras/consultoras ambientales**, usualmente contratadas por el Estado, encargadas de auditar de forma independiente el cumplimiento de dichas obras.

#### Why / ¿POR QUÉ?

Porque las infracciones ambientales no detectadas a tiempo generan sanciones económicas, restricciones para participar en licitaciones públicas y daño reputacional para las constructoras; y porque la falta de datos confiables e inalterables obliga a las supervisoras a invertir tiempo y personal en verificación de campo. Centralizar el monitoreo con sensores propios, automatizar la mitigación preventiva y garantizar la inalterabilidad de los datos reduce el riesgo regulatorio de unos y optimiza el esfuerzo de fiscalización de los otros.

#### How / ¿CÓMO?

Mediante EcoRoad, una plataforma HaaS/SaaS centralizada en la nube: la startup instala y calibra su propia red de sensores IoT en la obra vial, estos transmiten datos en tiempo real, el motor automatizado los compara contra los límites normativos y, ante una superación o una tendencia de riesgo, genera una alerta preventiva y crea automáticamente un ticket de incidencia visible en el módulo operativo de la constructora, mientras la supervisora accede en paralelo a un módulo de fiscalización con el historial inalterable de esos mismos datos.

#### How Much / ¿CUÁNTO?

El modelo de ingresos es de **doble suscripción (dual revenue) HaaS/SaaS**: EcoRoad cobra planes escalables (Base, Profesional y Enterprise) tanto a la empresa constructora como a la empresa supervisora de un mismo proyecto, de forma independiente. El costo del hardware de sensores IoT está incluido dentro de la suscripción y los equipos se devuelven a EcoRoad al finalizar la obra, diferenciándose los planes por número de proyectos, usuarios y funcionalidades de análisis incluidas.

### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

El estado actual de **la gestión ambiental en proyectos de infraestructura vial** se ha enfocado principalmente en **el registro manual, disperso y no verificable de indicadores ambientales, sin herramientas de análisis automatizado, visualización centralizada ni garantía de que los datos no hayan sido alterados**, lo que provoca **detección tardía de incumplimientos normativos, mayor exposición a sanciones, auditorías lentas y costosas, y desconfianza entre la empresa que ejecuta la obra y la que la fiscaliza.** Esta situación afecta a **empresas constructoras y a empresas supervisoras/consultoras ambientales**, quienes dependen de métodos desactualizados o de reportes potencialmente sesgados para monitorear y documentar el cumplimiento ambiental de los proyectos.

Lo que los productos o servicios existentes no logran resolver es la **captura automatizada e inalterable de datos ambientales en campo, junto con la centralización digital en tiempo real del monitoreo y la gestión de incidencias en proyectos viales**. Nuestro producto, **EcoRoad**, abordará esta brecha mediante una plataforma HaaS/SaaS que despliega su propia red de sensores IoT, detecta automáticamente las superaciones normativas, dispara mitigación preventiva y ofrece tableros geolocalizados independientes para cada segmento de cliente.

Nuestro enfoque inicial estará dirigido a **empresas constructoras medianas y grandes que ejecutan proyectos viales en el Perú**, así como a **empresas supervisoras y consultoras ambientales registradas en el RNCA** que fiscalizan dichos proyectos. Sabremos que tenemos éxito cuando observemos una reducción medible en el tiempo de detección de incumplimientos, mayor cantidad de incidencias mitigadas antes de una fiscalización externa, y una reducción en el tiempo dedicado por las supervisoras a preparar y verificar auditorías.

#### 1.2.2.2. Lean UX Assumptions

##### A. Business Assumptions

1. **Creemos que nuestros clientes necesitan:** un sistema de monitoreo ambiental automatizado, confiable e inalterable para sus proyectos viales, sin depender de la compra o gestión propia de sensores.
2. **Estas necesidades se resuelven con:** una plataforma HaaS/SaaS que provee sensores IoT propios, registra indicadores ambientales automáticamente, detecta incumplimientos normativos, dispara mitigación preventiva y visualiza el estado de los proyectos en un mapa.
3. **Nuestros primeros clientes serán:** empresas constructoras medianas y empresas supervisoras/consultoras ambientales que ejecutan o fiscalizan proyectos viales en Lima y otras regiones del Perú.
4. **Valor #1 esperado:** para la constructora, reducir el riesgo de sanciones mediante mitigación preventiva antes de la infracción; para la supervisora, reducir el esfuerzo y costo de fiscalización mediante datos inalterables y automatizados.
5. **Beneficios adicionales:** trazabilidad de los datos ambientales, mejora de la reputación institucional de la constructora, y automatización del reporteo oficial para la supervisora.
6. **Adquisición:** alianzas con gremios del sector construcción (CAPECO), referidos entre consultoras/supervisoras ambientales registradas en el RNCA, y marketing digital dirigido a gerentes de operaciones y jefes de fiscalización.
7. **Ingresos:** doble suscripción HaaS/SaaS mensual o anual, cobrada de forma independiente a constructora y a supervisora, bajo planes escalables (Base, Profesional, Enterprise).
8. **Competencia principal:** proveedores de sensores IoT ambientales sin capa de software integrada (ej. Sonitus Systems), plataformas de monitoreo pasivo (ej. SiteHive, Enablon), software de gestión de construcción genérico (ej. Autodesk Construction Cloud) y hojas de cálculo.
9. **Ventaja competitiva:** modelo HaaS/SaaS donde EcoRoad es dueña y calibradora de los sensores, actuando como árbitro neutral cuyos datos son confiables para ambas partes; motor de mitigación preventiva (no solo monitoreo pasivo); y arquitectura de datos separada por Bounded Contexts sobre una misma red de hardware.
10. **Mayor riesgo de producto:** que el despliegue, calibración y mantenimiento físico de los sensores IoT en campo no sea operativamente escalable, o que alguna de las dos partes (constructora o supervisora) desconfíe de la neutralidad de EcoRoad como proveedor común.
11. **Mitigación:** garantizar aislamiento total de datos por Bounded Contexts (RBAC estricto), imposibilitar la edición de lecturas históricas por parte de la constructora, y ofrecer trazabilidad completa de calibración de sensores como evidencia de neutralidad.

##### B. User Assumptions

**- ¿Quién es el usuario?** Dos perfiles diferenciados: (1) ingenieros de operaciones/responsables de mitigación ambiental dentro de la empresa constructora, y (2) auditores/consultores de la empresa supervisora ambiental.

**- ¿Dónde encaja el producto?** En el proceso diario de mitigación operativa de la constructora (módulo preventivo) y en el proceso de fiscalización remota de la supervisora (módulo de auditoría), ambos sobre el mismo proyecto vial en ejecución.

**- Problema a resolver:** la falta de datos ambientales automatizados, confiables e inalterables que permitan, por un lado, mitigar a tiempo, y por otro, fiscalizar sin desplazamiento constante a campo.

**- Uso típico:** revisión de alertas y cierre de tickets de mitigación con evidencia fotográfica (constructora); consulta de historial inalterable de lecturas y generación de reportes oficiales (supervisora).

**- Características importantes:** ingesta automática vía sensores IoT, alertas preventivas por niveles (Verde/Amarillo/Rojo), geolocalización, aislamiento total de datos entre módulos, y generación de reportes en PDF/Excel con formato legal.

**- Look & feel:** interfaz tipo dashboard con codificación por color según nivel de riesgo (semáforo), con dos experiencias visualmente diferenciadas: un panel operativo/preventivo para la constructora y un panel de auditoría/lectura para la supervisora, pensada para uso rápido desde campo y oficina.

##### C. User Outcome & Benefit Assumptions

- Los ingenieros de la constructora mitigan incidencias antes de que escalen a una infracción formal, gracias a alertas preventivas automatizadas.
- Las empresas constructoras reducen el gasto en compra de sensores propios al recibirlos incluidos en la suscripción HaaS.
- Las supervisoras/consultoras ambientales reducen su necesidad de desplazamiento a campo al confiar en datos inalterables generados por sensores neutrales.
- Las supervisoras entregan informes de auditoría con mayor rapidez y respaldo de datos trazables e inalterables.

##### D. Business Outcome Assumptions

- Incremento en el número de proyectos viales con doble suscripción activa (constructora + supervisora).
- Reducción medible en el tiempo promedio de detección y mitigación de incumplimientos normativos entre los clientes activos.
- Aumento en la tasa de renovación de suscripciones tras el primer ciclo de facturación, en ambos segmentos.
- Mayor volumen de proyectos gestionados por cliente, y mayor tasa de retención de hardware IoT reutilizado en nuevas obras.

##### E. Feature Assumptions

1. **Red de Sensores IoT (HaaS):** kits físicos de sensores (aire PM10/PM2.5, sonómetros de ruido, turbidez/pH de agua-suelo) provistos, instalados y calibrados por EcoRoad, incluidos en la suscripción.
2. **Motor de Umbrales de Riesgo:** algoritmo que clasifica automáticamente cada lectura en tres niveles (Verde/Amarillo/Rojo) según el límite normativo correspondiente.
3. **Panel de Control Preventivo (Constructora):** tablero geolocalizado que resalta tramos en riesgo antes de que se conviertan en infracción, con generación automática de tickets de mitigación y cierre con evidencia fotográfica.
4. **Dashboard de Fiscalización (Supervisora):** mapa multitramo con historial de lecturas inalterable y generador automatizado de reportes oficiales (PDF/Excel) con formato legal.
5. **Aislamiento de Datos por Bounded Contexts (RBAC):** garantiza que la constructora no pueda editar ni ver los borradores de la supervisora, y viceversa.

#### 1.2.2.3. Lean UX Hypothesis Statements

##### Confianza mediante Datos Inalterables (Árbitro Neutral)

Creemos que lograremos mayor confianza y adopción por parte de las empresas supervisoras, si estas acceden a un historial de lecturas ambientales capturado por sensores IoT propios de EcoRoad —imposibles de editar por la constructora—, con un módulo de fiscalización de datos inalterables.

##### Mitigación Preventiva vs. Monitoreo Pasivo

Creemos que lograremos una reducción medible en sanciones y paralizaciones de obra, si las empresas constructoras reciben alertas automáticas ante una tendencia de riesgo (Estado Amarillo) y no solo ante la infracción consumada, con un motor de mitigación preventiva que genera tickets de acción antes de la violación normativa.

##### Automatización de Reporteo

Creemos que lograremos una reducción en el tiempo y costo de preparación de auditorías, si las empresas supervisoras obtienen documentación consolidada, trazable y con formato legal del histórico de indicadores e incidencias de un proyecto, con un generador automatizado de reportes gubernamentales.

##### Optimización de Recursos Multi-Proyecto

Creemos que lograremos una gestión más eficiente de carteras de múltiples proyectos viales, si las empresas constructoras y supervisoras que gestionan varios proyectos acceden a una visualización consolidada del estado ambiental de todos ellos en un solo mapa, con un dashboard de control geolocalizado multi-proyecto.

#### 1.2.2.4. Lean UX Canvas

*(Sección pendiente de incorporar el canvas visual; el contenido narrativo que lo alimenta ya fue actualizado en los puntos 1.2.2.1 a 1.2.2.3.)*

## 1.3 Segmentos Objetivos

### Segmento 1: Empresas Constructoras Viales (Módulo Operativo)

Compañías contratadas para ejecutar la obra física de infraestructura vial, representadas por sus ingenieros de operaciones y responsables de mitigación ambiental. Utilizan EcoRoad como un "escudo de protección" interno: reciben alertas preventivas ante tendencias de riesgo ambiental (aire, ruido, agua) y gestionan la mitigación operativa en tiempo real —documentando evidencia fotográfica de sus acciones correctivas— para evitar multas gubernamentales o paralizaciones de obra. El sector constructor peruano ha mostrado una recuperación sostenida en 2024-2025, impulsada por la obra pública vial (CAPECO, 2025), lo que evidencia un mercado amplio de constructoras con proyectos viales activos que requieren monitoreo continuo.

### Segmento 2: Empresas Supervisoras Ambientales / Consultoras (Módulo de Fiscalización)

Firmas externas e independientes —usualmente contratadas por el Estado— encargadas de auditar el cumplimiento de las leyes ambientales en proyectos viales, representadas por sus consultores y auditores ambientales. Utilizan EcoRoad para automatizar la fiscalización y generar reportes oficiales sin necesidad de trasladar personal diariamente al campo, confiando en el historial inalterable de datos capturado por la red de sensores IoT de EcoRoad. Para el subsector transportes, la fiscalización ambiental de estos proyectos está a cargo de la Dirección de Gestión Ambiental del MTC (SPDA, 2024), y el Registro Nacional de Consultoras Ambientales agrupa a 1,293 consultoras habilitadas a nivel nacional (SENACE, 2024), lo que evidencia un mercado amplio de organizaciones con potencial de fiscalizar múltiples proyectos a la vez.