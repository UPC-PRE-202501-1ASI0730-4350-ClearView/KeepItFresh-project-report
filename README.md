# <center>COURSE PROJECT<center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Aplicaciones Web - SV51</strong><br>
    <strong>Profesor: Angel Augusto Velasquez Nuñez </strong><br>
    <br>INFORME TB1
</p>

<center>

#### Startup: **ClearView**
#### Product: **KeepItFresh**

</center>

### <center>Team Members</center>
<center>

| Member                       | Code       |
|------------------------------|------------|
| Briceño Llanos, Ayrton Omar          | U202311077 |
| Guia Carrasco, Pedro Andre | U202212010 |
| Lang Nassi, Werner Khalil    | U202310003 |
| Nakasone Gomes, Marco Antonio     | U202210790 |
| Rodas Sotomayor, Ernesto        | U202312443 |

<br> ABRIL 2025
</center>

<center>

# Registro de Versiones del Informe

| Version | Fecha      | Autor                           | Descripción de Modificación                                                    |
|---------|------------|---------------------------------|--------------------------------------------------------------------------------|
| 0.0.1   | 04/04/2025 |  | Desarrollo Capítulo (1) APARTADO 1.1 - 1.2 - 1.3                               |
| 0.0.2   | 04/04/2025 |        | Desarrollo Capítulo (2) APARTADO 2.1 - 2.2 - 2.3 - 2.4                            |
| 0.0.3   | 04/04/2025 |     | Desarrollo Capítulo (3) APARTADO 3.1 - 3.2 - 3.3 - 3.4                         |

</center>

# Project Report Collaboration Insights
Analiza cómo la colaboración y la gestión de tareas influyeron en los resultados del proyecto, destacando fortalezas y áreas de mejora para optimizar futuras estrategias.

Reporte:  
Organización:  
Landing Page: 
# Contenido
[Registro de Versiones del Informe](#registro-de-versiones-del-informe)  
[Project Report Collaboration Insights](#project-report-collaboration-insights)  
[Student Outcome](#student-outcome)  

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)  

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)  

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)  

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo](#211-análisis-competitivo)  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)  

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)  
[2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)  
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping) 

[2.4. Ubiquitous Language](#24-ubiquitous-language)  

[Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)  

[3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)    
[3.2. User Stories](#32-user-stories)  
[3.3. Impact Mapping](#33-impact-mapping)  
[3.4. Product Backlog](#34-product-backlog)  

[Capítulo IV: Product Design](#capítulo-iv-product-design)  

[4.1. Style Guidelines.](#41-style-guidelines)  
[4.1.1. General Style Guidelines.](#411-general-style-guidelines)  
[4.1.2. Web Style Guidelines.](#412-web-style-guidelines)  

[4.2. Information Architecture.](#42-information-architecture)  
[4.2.1. Organization Systems.](#421-organization-systems)  
[4.2.2. Labeling Systems.](#422-labeling-systems)  
[4.2.3. SEO Tags and Meta Tags.](#423-seo-tags-and-meta-tags)  
[4.2.4. Searching Systems.](#424-searching-systems)  
[4.2.5. Navigation Systems.](#425-navigation-systems)  

[4.3. Landing Page UI Design.](#43-landing-page-ui-design)  
[4.3.1. Landing Page Wireframe.](#431-landing-page-wireframe)  
[4.3.2. Landing Page Mock-up.](#432-landing-page-mock-up)  

[4.4. Web Applications UX/UI Design.](#44-web-applications-ux-ui-design)  
[4.4.1. Web Applications Wireframes.](#441-web-applications-wireframes)  
[4.4.2. Web Applications Wireflow Diagrams.](#442-web-applications-wireflow-diagrams)  
[4.4.3. Web Applications Mock-ups.](#443-web-applications-mock-ups)  
[4.4.4. Web Applications User Flow Diagrams.](#444-web-applications-user-flow-diagrams)  

[4.5. Web Applications Prototyping.](#45-web-applications-prototyping)  

[4.6. Domain-Driven Software Architecture.](#46-domain-driven-software-architecture)  
[4.6.1. Software Architecture Context Diagram.](#461-software-architecture-context-diagram)  
[4.6.2. Software Architecture Container Diagrams.](#462-software-architecture-container-diagrams)  
[4.6.3. Software Architecture Components Diagrams.](#463-software-architecture-components-diagrams)  

[4.7. Software Object-Oriented Design.](#47-software-object-oriented-design)  
[4.7.1. Class Diagrams.](#471-class-diagrams)  
[4.7.2. Class Dictionary.](#472-class-dictionary)  

[4.8. Database Design.](#48-database-design)  
[4.8.1. Database Diagram.](#481-database-diagram)  

[Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation-deployment)  

[5.1. Software Configuration Management.](#51-software-configuration-management)  
[5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)  
[5.1.2. Source Code Management.](#512-source-code-management)  
[5.1.3. Source Code Style Guide & Conventions.](#513-source-code-style-guide--conventions)
[5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)  

[5.2. Landing Page, Services & Applications Implementation.](#52-landing-page-services--applications-implementation)
[5.2.1. Sprint n.](#521-sprint-n)  
[5.2.1.1. Sprint Planning n.](#5211-sprint-planning-n)  
[5.2.1.2. Aspect Leaders and Collaborators.](#5212-aspect-leaders-and-collaborators)  
[5.2.1.3. Sprint Backlog n.](#5213-sprint-backlog-n)  
[5.2.1.4. Development Evidence for Sprint Review.](#5214-development-evidence-for-sprint-review)  
[5.2.1.5. Execution Evidence for Sprint Review.](#5215-execution-evidence-for-sprint-review)  
[5.2.1.6. Services Documentation Evidence for Sprint Review.](#5216-services-documentation-evidence-for-sprint-review)  
[5.2.1.7. Software Deployment Evidence for Sprint Review.](#5217-software-deployment-evidence-for-sprint-review)  
[5.2.1.8. Team Collaboration Insights during Sprint.](#5218-team-collaboration-insights-during-sprint)  

[Conclusiones](#conclusiones)
[Conclusiones y recomendaciones.](#conclusiones-y-recomendaciones)  
[Video About-the-Team.](#video-about-the-team)  

[Bibliografía](#bibliografía)  

[Anexos](#anexos)

# Student Outcome
El curso contribuye al cumplimiento del **Student Outcome ABET:ABET – EAC - Student Outcome 5** Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

| Criterio Especifico                                                                            | Acciones Realizadas | Conclusiones |
|------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta</td>                           | Escribir aquí | Escribir aquí |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos | Escribir aquí | Escribir aquí |




# Capítulo I: Introducción
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

ClearView es una startup dedicada a soluciones digitales enfocadas en restaurantes. Utilizamos tecnologías IoT para agilizar la gestión de restaurantes. Nuestro enfoque es preventivo, proporcionando sensores y herramientas para evitar problemas tales como la desposesión de alimentos. No ofrecemos servicios de intervención, ni de acción inmediata.

***Misión:***
Facilitar la gestión de los restaurantes a través de tecnologías las cuales permiten el monitoreo continuo del restaurante, al igual que optimizan la atención de los trabajadores, para que estos puedan ofrecer un mejor servicio a sus consumidores.

***Visión:***
Ser la empresa más importante en Perú, en el ámbito de gestión y optimización de restaurantes con el uso de soluciones tecnológicas.

### 1.1.2. Perfiles de integrantes del equipo

|                                                                   | Apellido y Nombre               | Carrera                | Acerca de                                                                                                                                                                                                                                                                                                                                                                 | Habilidades                                                                                        |
|-------------------------------------------------------------------|---------------------------------|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| | Briceño Llanos, Ayrton Omar | Ingeniería de Software | Escribir aquí | Escribir aquí |
| | Guia Carrasco, Pedro Andre | Ingeniería de Software | Escribir aquí | Escribir aquí |
| | Lang Nassi, Werner Khalil | Ingeniería de Software | Escribir aquí | Escribir aquí |
| | Nakasone Gomes, Marco Antonio | Ingeniería de Software | Escribir aquí | Escribir aquí |
| | Rodas Sotomayor, Ernesto | Ingeniería de Software | Escribir aquí | Escribir aquí |

## 1.2. Solution Profile

Product Name: KeepItFresh

Description: KeepItFresh, es una Web App que tiene como objetivo optimizar la gestión de los restaurantes. Para ello, esta permite al usuario monitorear los IoT que este tiene, mostrando información útil, ayudando con la gestión de inventarios y agilizando el trabajo de los trabajadores en la tienda. Los dueños de los restaurantes pueden usar KeepItFresh con el fin de optimizar varios procesos.

Monetización: KeepItFresh funciona mediante un modelo de suscripción mensual o anual, en el cual se alquilan los diferentes dispositivos IoT.

### 1.2.1. Antecedentes y problemática
**Antecedentes:**


Estudios recientes han analizado los factores que impulsan el desperdicio de alimentos en restaurantes informales de gama media, diferenciado entre el desperdicio generado por el cliente y el generado en la cocina. Una investigación en destinos turísticos de Lituania (Morkunas et al, 2025), empleo entrevistas con gerentes y un Proceso Analítico Jerárquico (AHP) difuso para priorizar las causas, revelando hallazgos clave:

* Cliente: Destacaron el sentimiento de vergüenza, barrera lingüística, presentación inadecuada de platos tradicionales, tanto en destinos locales e internacionales.

* Cocina: Asociado a fallas en la planificación de demanda, ineficiencias operativas y limitaciones en infraestructura de almacenamiento.

Dicho estudio, propone soluciones adaptadas a cada factor identificado, ofreciendo un marco relevante para abordar problemáticas similares en contextos gastronómicos. 

**Problematicas:**

La gestión del inventario de un restaurante suele llegar a consumir muchos recursos y tiempo, además también es muy complicado estar al tanto de la fecha de vencimiento por producto, al igual que la temperatura idónea de los mismos. También cuando un restaurante tiene una gran cantidad de clientela se le suele dificultar a los mozos darse cuenta cuando un cliente requiere de atención.


**What**
* El problema es la mala gestión del inventario en los restaurantes, lo que genera desperdicio de alimentos y un alto consumo de recursos debido al vencimiento de productos y a la falta de control eficiente. Además, el personal de atención enfrenta dificultades para identificar cuándo un cliente requiere asistencia, lo que puede afectar la calidad del servicio y la experiencia del cliente.

**Why: ¿Por qué es importante que se gestione el inventario en los restaurantes?**

**Who: ¿Quiénes se ven afectados?**
* Los dueños o gerentes y trabajadores de un restaurante.

**When: ¿Cuándo sucede la problemática?**
* La problemática sucede en cualquier momento del día, ya que los restaurantes operan constantemente y deben gestionar su inventario y atención al cliente en todo momento.

**Where: ¿Dondé implementaríamos nuestra solución?**
* En restaurantes nacionales e internacionales.

**How: ¿Cómo ayudará nuestra solución?**

**How much: ¿Cúanto costará?**

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas.

## 1.3. Segmentos Objetivos

# Capitulo II: Requirements Elicitation & Analysis

## 2.1. Competidores 

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding 

### 2.3.1. User Personas
### 2.3.2. User Task Matrix 
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-Is Scenario Mapping

## 2.4. Ubiquitous Language

# Capitulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**Segmento 1**

| Fases       | Verificación de mesas          | Gestión de inventario        | Asignación de tareas      | Comunicación con equipo    |
|-------------|--------------------------------|------------------------------|---------------------------|---------------------------|
| **Doing**   | Consulta sistema de reservas en tiempo real | Recibe alertas automáticas de bajo stock | Asigna tareas mediante plataforma digital | Coordina mediante chat integrado |
| **Thinking**| "Tengo visibilidad completa del estado del restaurante" | "El sistema me avisa antes de quedarnos sin ingredientes" | "Puedo balancear mejor las cargas de trabajo" | "Todos reciben las actualizaciones al instante" |
| **Feeling** | Tranquilo y en control | Confiado en los suministros | Satisfecho con la distribución | Conectado con el equipo |

**Segmento 2**

| Fases       | Ejecución de tareas            | Reporte de progreso           | Verificación de recursos  | Comunicación con supervisores |
|-------------|--------------------------------|------------------------------|---------------------------|------------------------------|
| **Doing**   | Registra tareas completadas en app móvil | Notifica completado mediante sistema | Consulta niveles de ingredientes en tablet | Envía solicitudes por plataforma |
| **Thinking**| "Ahora trabajo de manera organizada" | "Mis reportes quedan registrados adecuadamente" | "Sé exactamente qué productos están disponibles" | "Puedo comunicar necesidades fácilmente" |
| **Feeling** | Satisfecho con la eficiencia | Seguro en sus reportes     | Tranquilo por visibilidad | Apoyado por la comunicación clara |

## 3.2. User Stories

| EPIC/ USER STORY ID | Título                                      | Descripción                                                                                                                                                                                                                                                                                                                         | Criterio de aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Relacionado a la épica # |
|---------------------|---------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|
| E01                 | Registro y Autenticación                    | Como usuario de KeepItFresh (dueño de restaurante o trabajador), quiero poder registrarme e iniciar sesión en la plataforma para acceder a las funcionalidades específicas asignadas a mi rol.                                                                                                                                      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                          |
| E02                 | Monitoreo de Sensores IoT                   | Como dueño de restaurante, quiero poder monitorear en tiempo real las lecturas de los sensores IoT instalados para controlar temperatura, gases y otros factores críticos.                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                          |
| E03                 | Gestión de Inventario                      | Como dueño de restaurante, quiero poder gestionar el inventario de mis productos alimenticios para optimizar su uso y evitar pérdidas.                                                                                                                                                                                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                          |
| E04                 | Sistema de Atención al Cliente             | Como dueño o trabajador de restaurante, quiero administrar eficientemente la atención al cliente mediante el sistema de botones IoT.                                                                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                          |
| E05                 | Dashboard y Visualización de Datos         | Como dueño de restaurante, quiero tener un apartado en la aplicación que me permita tener una vista general de todos los datos para así visualizar los datos que quiero más fácil y rápido.                                                                                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                          |
| E06                 | Sistema de Alertas y Notificaciones        | Como dueño de restaurante, quiero recibir notificaciones y alertas de la aplicación que me muestre cuando suceda algo.                                                                                                                                                                                                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                          |
| E07                 | Configuración y Onboarding                 | Como dueño de restaurante, quiero modificar la configuración de la aplicación a mi gusto para así tenerlo personalizado a mi preferencia                                                                                                                                                                                            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                          |
| E08                 | Reportes y Analítica                        | Como dueño de restaurante, quiero reportes y analíticas que me muestren información y estadísticas importantes que la aplicación haya calculado para poder tenerlos guardados y tener la información poder tomar decisiones informadas sobre ventas, desempeño del personal, productos más vendidos y horarios con mayor actividad. |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |                          |
| US03                | Visualización en tiempo real                | **Como** dueño de restaurante <br>**Quiero** ver los datos actuales de sensores IoT <br>**Para** monitorear condiciones del inventario.                                                                                                                                                                                             | Escenario 1: **Given:** Muestra lecturas en tiempo real de temperatura, humedad y gases.<br>Escenario 2: Sensor desconectado muestra advertencia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | E02                      |
| US04                | Configuración de alertas IoT               | **Como** dueño de restaurante <br>**Quiero** configurar alertas cuando los valores de los sensores estén fuera del rango ideal <br>**Para** poder reaccionar a tiempo ante condiciones críticas.                                                                                                                                    | Escenario 1: Usuario define umbrales máximos/mínimos.<br>Escenario 2: Sistema genera notificación en app cuando se supera un umbral.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | E02                      |
| US05                | Registro de productos                      | **Como** dueño de restaurante <br>**Quiero** registrar nuevos productos con su fecha de vencimiento y condiciones de almacenamiento <br>**Para** llevar un mejor control del inventario.                                                                                                                                            | Escenario 1: Producto agregado con fecha de expiración válida.<br>Escenario 2: Fecha inválida muestra mensaje de error.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | E03                      |
| US06                | Consulta de inventario                     | **Como** dueño de restaurante <br>**Quiero** consultar el inventario actualizado <br>**Para** tomar decisiones sobre compras y uso.                                                                                                                                                                                                 | Escenario 1: Muestra lista de productos, fechas de vencimiento, cantidad.<br>Escenario 2: Permite búsqueda por nombre/categoría.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | E03                      |
| US07                | Alertas de vencimiento                     | **Como** dueño de restaurante <br>**Quiero** recibir notificaciones cuando un producto está por vencer <br>**Para** evitar pérdidas económicas.                                                                                                                                                                                     | Escenario 1: Sistema genera alerta X días antes del vencimiento.<br>Escenario 2: Producto vencido aparece resaltado.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | E03                      |
| US08                | Solicitud de atención                      | **Como** comensal <br>**Quiero** presionar un botón para solicitar atención <br>**Para** que el personal reciba una notificación inmediata.                                                                                                                                                                                         | Escenario 1: Botón presionado activa notificación.<br>Escenario 2: Personal recibe alerta en dashboard o app móvil.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | E04                      |
| US09                | Registro de tiempo de respuesta            | **Como** administrador <br>**Quiero** medir cuánto tiempo tarda el personal en atender una solicitud <br>**Para** evaluar la eficiencia del servicio.                                                                                                                                                                               | Escenario 1: Se registra timestamp de solicitud y atención.<br>Escenario 2: Se genera reporte de eficiencia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | E04                      |
| US10                | Resumen general para dueños            | **Como** dueño de restaurante <br>**Quiero** ver un resumen general de las ventas, pedidos y desempeño del local en el dashboard <br>**Para** conocer el rendimiento de mi restaurante.                                                                                                                                             | Escenario 1: El dueño inicia su sesión, Accede al dashboard y ve un resumen con ventas, pedidos y desempeño general.<br>Escenario 2: La aplicación muestra en rojo si hubo ventas, pedidos o desempeño por debajo del promedio.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | E05                      |
| US11                | Alertas visuales en dashboard            | **Como** dueño de restaurante <br>**Quiero** que el dashboard me muestre alertas si hay demoras <br>**Para** saber en qué momento del día hay más movimiento.                                                                                                                                                                       | Escenario 1: El sistema detecta un retraso en la atención y genera una nota que muestra la hora en la que ocurrió.<br>Escenario 2: La aplicación coloca la nota como una notificación en el dashboard.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | E05                      |
| US12                | Alerta de inventario bajo            | **Como** dueño de restaurante <br>**Quiero** alertas cuando el inventario esté bajo <br>**Para** llamar a la distribuidora antes que se acabe el stock.                                                                                                                                                                             | Escenario 1: El sistema detecta un producto por debajo del stock mínimo y le envía una alerta al encargado.<br>Escenario 2: El sistema coloca la alerta en notificaciones de la aplicación.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | E06                      |
| US13                | Notificación diaria de resumen            | **Como** dueño de restaurante <br>**Quiero** recibir un resumen diario de ventas <br>**Para** llamar a la distribuidora antes que se acabe el stock.                                                                                                                                                                                | Escenario 1: Cuando termina el día, el sistema genera un resumen que muestra las ganancias y ventas y lo envía al dueño vía notificación.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | E06                      |
| US14                | Historial de alertas            | **Como** dueño de restaurante <br>**Quiero** ver un historial de alertas pasadas <br>**Para** saber lo ocurrido en ciertos días.                                                                                                                                                                                                    | Escenario 1: El dueño accede a alertas y selecciona el historial de alertas y la aplicación muestra una lista de alertas pasadas.<br>Escenario 2: Las alertas más peligrosas son resaltadas por la aplicación para dar a entender que son más importantes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | E06                      |
| US15                | Exportar reportes            | **Como** dueño de restaurante <br>**Quiero** exportar reportes en PDF o Excel <br>**Para** poder tener mis reportes en mi formato favorito.                                                                                                                                                                                         | Escenario 1: La aplicación termina de generar el reporte y le da la opción al usuario de exportarlo en PDF o Excel.<br>Escenario 2: El usuario decide no guardar el reporte y entonces se queda en una papelera de la aplicación hasta que pasen 30 días o lo borre.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | E07                      |
| US16                | Reportes de ventas            | **Como** dueño de restaurante <br>**Quiero** generar reportes de ventas diarios, semanales y mensuales <br>**Para** saber el rendimiento de mi local.                                                                                                                                                                               | Escenario 1:  El dueño entra a reportes de la aplicación, elige el rango de fechas y el sistema le muestra el reporte correspondiente.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | E08                      |
| TS01                | Crear Registro de Inventario                        | **Como** desarrollador <br>**Quiero** implementar el endpoint POST para crear registros de inventario <br>**Para** permitir a los gerentes del restaurante agregar nuevos productos a su inventario.                                                                                                                                | Escenario 1: <br>Creación exitosa de un registro de inventario<br>Dado que el endpoint /api/v1/inventory esta disponible, <br>Cuando se envía una solicitud POST con valores para productId y supplierId, <br>Entonces se recibe una respuesta con estado 201, <br>Y el recurso de Inventario está incluido en el cuerpo de la respuesta, con un nuevo ID y los valores registrados. <br>Escenario 2<br> Creación duplicada de un registro de inventario <br> Dado que el endpoint /api/v1/inventory está disponible, <br> Cuando se envía una solicitud POST con valores que ya existen para productId y supplierId, <br> Entonces se recibe una respuesta con estado 400, <br>  Y se incluye un mensaje en el cuerpo de la respuesta, con el valor "No se cumplen todas las restricciones para el inventario: Ya existe un registro de inventario para este producto." | E05                      |
| TS02                | Leer Registro de Inventario                   | **Como** desarrollador <br>**Quiero** implementar el endpoint GET para leer registros de inventario <br>**Para** permitir a los usuarios recuperar los detalles de los elementos del inventario.                                                                                                                                    | Escenario 1: <br>Recuperación exitosa de un registro de inventario<br>Dado que el endpoint /api/v1/inventory/{id} está disponible,<br>Cuando se envía una solicitud GET con un id válido,<br>Entonces se recibe una respuesta con estado 200,<br>Y el recurso de Inventario está incluido en el cuerpo de la respuesta con los detalles del id especificado. <br>Escenario 2<br>Recuperación de un registro de inventario inexistente <br>Dado que el endpoint /api/v1/inventory/{id} está disponible,<br>Cuando se envía una solicitud GET con un id inválido,<br>Entonces se recibe una respuesta con estado 404,<br>Y se incluye un mensaje en el cuerpo de la respuesta, con el valor "Registro de inventario no encontrado."                                                                                                                                        | E05                      |
| TS03                | Actualizar Registro de Inventario                      | **Como** desarrollador <br>**Quiero** implementar el endpoint PUT para actualizar registros de inventario <br>**Para** permitir a los usuarios modificar detalles existentes del inventario.                                                                                                                                        | Escenario 1: <br>Actualización exitosa de un registro de inventario<br>Dado que el endpoint /api/v1/inventory/{id} está disponible,<br>Cuando se envía una solicitud PUT con el id y los valores actualizados para productId y supplierId,<br>Entonces se recibe una respuesta con estado 200,<br>Y el recurso de Inventario actualizado está incluido en el cuerpo de la respuesta con los nuevos valores para productId y cantidad.<br>Escenario 2: <br>Actualización de un registro de inventario inexistente<br>Dado que el endpoint /api/v1/inventory/{id} está disponible,<br>Cuando se envía una solicitud PUT con un id inválido y valores actualizados,<br>Entonces se recibe una respuesta con estado 404,<br>Y se incluye un mensaje en el cuerpo de la respuesta, con el valor "Registro de inventario no encontrado para actualizar."                       | E05                      |
| TS04                | Eliminar Registro de Inventario                   | **Como** desarrollador <br>**Quiero** implementar el endpoint DELETE para eliminar registros de inventario <br>**Para** permitir a los usuarios eliminar elementos del inventario de sus registros.                                                                                                                                 | Escenario 1: <br>Eliminación exitosa de un registro de inventario<br>Dado que el endpoint /api/v1/inventory/{id} está disponible,<br>Cuando se envía una solicitud DELETE con un id válido,<br>Entonces se recibe una respuesta con estado 200,<br>Y se incluye un mensaje en el cuerpo de la respuesta, con el valor "Registro de inventario eliminado con éxito.".<br>Escenario 2: <br>Eliminación de un registro de inventario inexistente<br>Dado que el endpoint /api/v1/inventory/{id} está disponible,<br>Cuando se envía una solicitud DELETE con un id inválido,<br>Entonces se recibe una respuesta con estado 404,<br>Y se incluye un mensaje en el cuerpo de la respuesta, con el valor "Registro de inventario no encontrado para eliminar."                                                                                                                                                                                                                                        | E05                      |


## 3.3. Impact Mapping
## 3.4. Product Backlog

|     #Orden    |     User Story Id    |                   Título                 |                                                                                          Descripción                                                                                        |     Story Points (1/2/3/5/8)    |
|:-------------:|:--------------------:|:----------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------:|
|        1      |          US03        |        Visualización en tiempo real      |                                   Como dueño de restaurante    Quiero ver los datos actuales de sensores IoT    Para monitorear condiciones del inventario.                                 |                 8               |
|        2      |          US04        |        Configuración de alertas IoT      |     Como dueño de restaurante    Quiero configurar alertas cuando los valores de los sensores   estén fuera del rango ideal    Para poder reaccionar a tiempo ante condiciones críticas.    |                 8               |
|        3      |          US05        |           Registro de productos          |         Como dueño de restaurante    Quiero registrar nuevos productos con su fecha de vencimiento y   condiciones de almacenamiento    Para llevar un mejor control del inventario.        |                 3               |
|        4      |          US06        |           Consulta de inventario         |                                     Como dueño de restaurante    Quiero consultar el inventario actualizado    Para tomar decisiones sobre compras y uso.                                   |                 3               |
|        5      |          US07        |           Alertas de vencimiento         |                               Como dueño de restaurante    Quiero recibir notificaciones cuando un producto está por vencer    Para evitar pérdidas económicas.                             |                 2               |
|        6      |          US12        |         Alerta de inventario bajo        |                           Como dueño de restaurante    Quiero alertas cuando el inventario esté bajo    Para llamar a la distribuidora antes que se acabe el stock.                         |                 2               |
|        7      |          US13        |       Notificación diaria de resumen     |                            Como dueño de restaurante    Quiero recibir un resumen diario de ventas    Para llamar a la distribuidora antes que se acabe el stock.                           |                 2               |
|        8      |          US10        |        Resumen general para dueños       |          Como dueño de restaurante    Quiero ver un resumen general de las ventas, pedidos y desempeño   del local en el dashboard    Para conocer el rendimiento de mi restaurante.        |                 5               |
|        9      |          US16        |             Reportes de ventas           |                            Como dueño de restaurante    Quiero generar reportes de ventas diarios, semanales y mensuales    Para saber el rendimiento de mi local.                          |                 5               |
|       10      |          US15        |             Exportar reportes            |                                 Como dueño de restaurante    Quiero exportar reportes en PDF o Excel    Para poder tener mis reportes en mi formato favorito.                               |                 3               |
|       11      |          US14        |            Historial de alertas          |                                      Como dueño de restaurante    Quiero ver un historial de alertas pasadas    Para saber lo ocurrido en ciertos días.                                     |                 1               |
|       12      |          US11        |       Alertas visuales en dashboard      |                        Como dueño de restaurante    Quiero que el dashboard me muestre alertas si hay demoras    Para saber en qué momento del día hay más movimiento.                      |                 1               |
|       13      |          US08        |           Solicitud de atención          |                                 Como comensal    Quiero presionar un botón para solicitar atención    Para que el personal reciba una notificación inmediata.                               |                 2               |
|       14      |          US09        |     Registro   de tiempo de respuesta    |                           Como administrador    Quiero medir cuánto tiempo tarda el personal en atender una   solicitud    Para evaluar la eficiencia del servicio.                         |                 2               |

# Capítulo IV: Product Design

## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary

## 4.8. Database Design
### 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint n
#### 5.2.1.1. Sprint Planning n
#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog n
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

# Conclusiones
## Conclusiones y recomendaciones

## Video About-the-Team

## Bibliografía

## Anexos
