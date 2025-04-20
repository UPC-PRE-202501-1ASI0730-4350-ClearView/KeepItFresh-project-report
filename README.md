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

[Capítulo II: Requirements Elicitation & Analysi](#capítulo-ii-requirements-elicitation--analysis)  

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

[Capítulo III: Requirements Specificatio](#capítulo-iii-requirements-specification)  

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
|------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta</td>                           | Escribir aqui | Escribir aqui |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos | Escribir aquí | Escribir aquí |




# Capítulo I: Introduccion
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

ClearView es una startup dedicada a soluciones digitales enfocadas en restaurantes. Utilizamos tecnologías IoT para agilizar la gestión de restaurantes. Nuestro enfoque es preventivo, proporcionando sensores y herramientas para evitar problemas tales como la desposesión de alimentos. No ofrecemos servicios de intervención, ni de acción inmediata.

***Mision:***
Facilitar la gestión de los restaurantes a través de tecnologías las cuales permiten el monitoreo continuo del restaurante, al igual que optimizan la atención de los trabajadores, para que estos puedan ofrecer un mejor servicio a sus consumidores.

***Visión:***
Ser la empresa más importante en Perú, en el ámbito de gestión y optimización de restaurantes con el uso de soluciones tecnológicas.

### 1.1.2. Perfiles de integrantes del equipo

|                                                                   | Apellido y Nombre               | Carrera                | Acerca de                                                                                                                                                                                                                                                                                                                                                                      | Habilidades                                                                                             |
|-------------------------------------------------------------------|---------------------------------|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| | Briceño Llanos, Ayrton Omar | Ingeniería de Software | Escribir aqui | Escribir aqui |
| | Guia Carrasco, Pedro Andre | Ingeniería de Software | Escribir aqui | Escribir aqui |
| | Lang Nassi, Werner Khalil | Ingeniería de Software | Escribir aqui | Escribir aqui |
| | Nakasone Gomes, Marco Antonio | Ingeniería de Software | Escribir aqui | Escribir aqui |
| | Rodas Sotomayor, Ernesto | Ingeniería de Software | Escribir aqui | Escribir aqui |

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

La gestión del inventario de un restaurante suele llegar a consumir muchos recursos y tiempo. Además también es muy complicado estar al tanto de la fecha de vencimiento por producto, al igual que la temperatura idónea de los mismos. También cuando un restaurante tiene una gran cantidad de clientela se le suele dificultar a los mozos darse cuenta cuando un cliente requiere de atención.


**What**
* El problema es la mala gestión del inventario en los restaurantes, lo que genera desperdicio de alimentos y un alto consumo de recursos debido al vencimiento de productos y a la falta de control eficiente.Además, el personal de atención enfrenta dificultades para identificar cuándo un cliente requiere asistencia, lo que puede afectar la calidad del servicio y la experiencia del cliente.

**Why: ¿Por qué es importante que se gestione el inventario en los restaurantes?**

**Who: ¿Quienes se ven afectados?**
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

# Capitulo II: Requeriments Elicitation & Analysis

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

# Capitulo III: Requeriments Specification

## 3.1. To-Be Scenario Mapping 
## 3.2. User Stories

| EPIC/ USER STORY ID | Título                                      | Descripción                                                                                                                                                                                   | Criterio de aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Relacionado a la épica # |
|---------------------|---------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|
| E01                 | Registro y Autenticación                    | Como usuario de KeepItFresh (dueño de restaurante o trabajador), quiero poder registrarme e iniciar sesión en la plataforma para acceder a las funcionalidades específicas asignadas a mi rol. |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                          |
| E02                 | Monitoreo de Sensores IoT                   | Como dueño de restaurante, quiero poder monitorear en tiempo real las lecturas de los sensores IoT instalados para controlar temperatura, gases y otros factores críticos.                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                          |
| E03                 | Gestión de Inventario                      | Como dueño de restaurante, quiero poder gestionar el inventario de mis productos alimenticios para optimizar su uso y evitar pérdidas.                                                      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                          |
| E04                 | Sistema de Atención al Cliente             | Como dueño o trabajador de restaurante, quiero administrar eficientemente la atención al cliente mediante el sistema de botones IoT.                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                          |
| E05                 | XXXXXXX             | Lorem ipsum                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                          |
| E06                 | XXXXXXX             | Lorem ipsum                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                          |
| E07                 | XXXXXXX             | Lorem ipsum                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                          |
| E08                 | XXXXXXX             | Lorem ipsum                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                          |
| US01                | Registro de usuario                         | **Como** dueño o trabajador de restaurante <br>**Quiero** poder crear una cuenta en la plataforma <br>**Para** acceder a sus funcionalidades según mi rol.                                                                   | Escenario 1: Registro exitoso. Dado que el usuario proporciona datos válidos, cuando envía el formulario de registro, entonces el sistema confirma el registro y permite iniciar sesión.<br>Escenario 2: Registro fallido por correo ya existente. Dado que el usuario usa un correo registrado, cuando intenta enviar el formulario, entonces se muestra un mensaje de error. | E01                      |
| US02                | Inicio de sesión                            | **Como** dueño o trabajador de restaurante <br>**Quiero** poder iniciar sesión con mis credenciales <br>**Para** acceder a las funciones específicas asignadas a mi rol.                                             | Escenario 1: Inicio exitoso. Dado que el usuario está registrado, cuando envía las credenciales correctas, entonces accede al sistema.<br>Escenario 2: Error por credenciales inválidas. Dado que las credenciales son incorrectas, entonces el sistema muestra un mensaje de error.                                                                                                                              | E01                      |
| US03                | Visualización en tiempo real                | **Como** dueño de restaurante <br>**Quiero** ver los datos actuales de sensores IoT <br>**Para** monitorear condiciones del inventario.                                                                         | Escenario 1: Muestra lecturas en tiempo real de temperatura, humedad y gases.<br>Escenario 2: Sensor desconectado muestra advertencia.                                                                                                                                                                                                                      | E02                      |
| US04                | Configuración de alertas IoT               | **Como** dueño de restaurante <br>**Quiero** configurar alertas cuando los valores de los sensores estén fuera del rango ideal <br>**Para** poder reaccionar a tiempo ante condiciones críticas.                                                                        | Escenario 1: Usuario define umbrales máximos/mínimos.<br>Escenario 2: Sistema genera notificación en app cuando se supera un umbral.                                                                                                                                                                                                                      | E02                      |
| US05                | Registro de productos                      | **Como** dueño de restaurante <br>**Quiero** registrar nuevos productos con su fecha de vencimiento y condiciones de almacenamiento <br>**Para** llevar un mejor control del inventario.                                                                   | Escenario 1: Producto agregado con fecha de expiración válida.<br>Escenario 2: Fecha inválida muestra mensaje de error.                                                                                                                                                                                                                      | E03                      |
| US06                | Consulta de inventario                     | **Como** dueño de restaurante <br>**Quiero** consultar el inventario actualizado <br>**Para** tomar decisiones sobre compras y uso.                                                                            | Escenario 1: Muestra lista de productos, fechas de vencimiento, cantidad.<br>Escenario 2: Permite búsqueda por nombre/categoría.                                                                                                                                                                                                                      | E03                      |
| US07                | Alertas de vencimiento                     | **Como** dueño de restaurante <br>**Quiero** recibir notificaciones cuando un producto está por vencer <br>**Para** evitar pérdidas económicas.                                                                                                | Escenario 1: Sistema genera alerta X días antes del vencimiento.<br>Escenario 2: Producto vencido aparece resaltado.                                                                                                                                                                                                                      | E03                      |
| US08                | Solicitud de atención                      | **Como** comensal <br>**Quiero** presionar un botón para solicitar atención <br>**Para** que el personal reciba una notificación inmediata.                                                                                 | Escenario 1: Botón presionado activa notificación.<br>Escenario 2: Personal recibe alerta en dashboard o app móvil.                                                                                                                                                                                                                      | E04                      |
| US09                | Registro de tiempo de respuesta            | **Como** administrador <br>**Quiero** medir cuánto tiempo tarda el personal en atender una solicitud <br>**Para** evaluar la eficiencia del servicio.                                                                          | Escenario 1: Se registra timestamp de solicitud y atención.<br>Escenario 2: Se genera reporte de eficiencia.                                                                                                                                                                                                                      | E04                      |
| TS01                | Endpoint de Registro                        | **Como** desarrollador <br>**Quiero** crear el endpoint POST  <br>**Para** permitir a nuevos usuarios registrarse en la plataforma.                                                       | Escenario 1: Registro exitoso devuelve status 201.<br>Escenario 2: Registro con email duplicado devuelve status 400 con mensaje de error.                                                                                                                                                                                                                      | E01                      |
| TS02                | Endpoint de Autenticación                   | **Como** desarrollador <br>**Quiero** crear el endpoint POST  <br>**Para** autenticar a los usuarios y devolver un token de acceso.                                                                   | Escenario 1: Autenticación válida devuelve status 200 y token.<br>Escenario 2: Credenciales inválidas devuelve status 401 con mensaje de error.                                                                                                                                                                                                                      | E01                      |
| TS03                | Lectura en tiempo real                      | **Como** desarrollador <br>**Quiero** implementar WebSocket o polling  <br>**Para** mostrar lecturas en tiempo real en la interfaz.                                                                 | Escenario 1: Conexión activa transmite lecturas cada X segundos.<br>Escenario 2: Error de red lanza mensaje de reconexión.                                                                                                                                                                                                                      | E02                      |
| TS04                | Configuración de alertas                   | **Como** desarrollador <br>**Quiero** crear el endpoint POST  <br>**Para** permitir a los usuarios configurar alertas personalizadas.                                                                    | Escenario 1: Umbrales válidos se guardan correctamente (status 201).<br>Escenario 2: Faltan campos y retorna error 400.                                                                                                                                                                                                                      | E02                      |
| TS05                | CRUD de inventario                         | **Como** desarrollador <br>**Quiero** implementar endpoints CRUD  <br>**Para** permitir la gestión completa del inventario.                                                                     | Escenario 1: Endpoints permiten crear, leer, actualizar y eliminar productos.<br>Escenario 2: Validaciones en campos obligatorios y duplicados.                                                                                                                                                                                                                      | E03                      |
| TS06                | Notificaciones de vencimiento              | **Como** desarrollador <br>**Quiero** crear una tarea programada que revise fechas de caducidad <br>**Para** generar alertas de productos próximos a vencer.                                                                                    | Escenario 1: La tarea se ejecuta diariamente y detecta productos próximos a caducar.<br>Escenario 2: El sistema notifica vía email o app según configuración.                                                                                                                                                                                                                      | E03                      |
| TS07                | Integración con botón IoT                  | **Como** desarrollador <br>**Quiero** recibir eventos de los botones IoT en el backend <br>**Para** notificar al personal de atención.                                                                             | Escenario 1: POST enviado al endpoint con ID de mesa.<br>Escenario 2: Solicitud almacenada y notificación enviada al staff.                                                                                                                                                                                                                      | E04                      |
| TS08                | Dashboard de atención                      | **Como** desarrollador <br>**Quiero** mostrar las solicitudes de atención pendientes en un panel web <br>**Para** que el personal pueda gestionarlas en tiempo real.                                                                                        | Escenario 1: Panel muestra lista cronológica de solicitudes activas.<br>Escenario 2: Permite marcar solicitudes como atendidas.                                                                                                                                                                                                                      | E04                      |


## 3.3. Impact Mapping
## 3.4. Product Backlog

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
