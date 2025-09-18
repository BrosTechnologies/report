# COURSE PROJECT

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <br>
    <strong>Carrera de Ingeniería de Software</strong><br>
    <strong>Ciclo 2025-2</strong>
</p>

<p align="center">
  <strong>Curso: </strong>Aplicaciones para Dispositivos Móviles<br>
  <strong>Sección: </strong>1795
</p>

<p align="center">
    <strong>Profesor: </strong>Jorge Luis Mayta Guillermo
</p>

<p align="center">
    <strong>Informe de Trabajo Final</strong>
</p>

<p align="center">
    <strong>Nombre del startup: </strong> [Startup]
</p>

<p align="center">
    <strong>Nombre del producto:</strong> [Producto]
</p>

<div>
    <h3 align="center">Integrantes del equipo:</h3>
    </div>
<div>
     <table align="center">
        <tr>
            <th style="text-align:center;">Código</th>
            <th style="text-align:center;">Nombre</th>
        </tr>
        <tr>
            <td>u202310931</td>
            <td>Bellido Salas, Raúl</td>
        </tr>
        <tr>
            <td>u202310680</td>
            <td>Castro Sanchez, Amir Gabriel</td>
        </tr>
        <tr>
            <td>u202314130</td>
            <td>Gonzales Valverde, Carlos Matthew</td>
        </tr>
        <tr>
            <td>u202115357</td>
            <td>Prado Vargas, Mario Benjamín</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Agosto, 2025</strong>
</p>

---

# Registro de Versiones del Informe

| **Versión** | **Fecha** | **Autor** | **Descripción de modificación** |
|     ---     |     ---   |     ---   |             ---                 |
| 1.0 | 26/08/2025 | Anónimo | Se implementó el diseño/esqueleto del informe sobre todas las secciones|

---

# Project Report Collaboration Insights
**URL del repositorio para el Project Report:** [https://github.com/BrosTechnologies/report](https://github.com/BrosTechnologies/report)

Temporal => *En esta sección el equipo indica el URL del repositorio para el Project Report en la
organización de GitHub del equipo. Adicionalmente, para cada entrega explica cómo
se han desarrollado las actividades de elaboración del informe y se presenta
capturas en imagen de los analíticos de colaboración y commits en GitHub para el
repositorio del informe, realizados por los miembros del equipo. Todos los miembros
del equipo deben tener participación en la elaboración del informe. Esta sección
debe ir expandiéndose con descripciones y evidencias en cada entrega. Lo descrito y
evidenciado debe tener coherencia con el Registro de Versiones del Informe.*

---

<div style="page-break-after: always;">

# Contenido

- [Carátula](#course-project)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Objetivos SMART](#objetivos-smart)
- [Capítulo I: Presentación](#capítulo-i-presentación)
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
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
  - [2.4. Requirements specification](#24-requirements-specification)
    - [2.4.1. User Stories](#241-user-stories)
    - [2.4.2. Impact Mapping](#242-impact-mapping)
    - [2.4.3. Product Backlog](243-product-backlog)
  - [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)
    - [2.5.1. EventStorming](#251-eventstorming)
      - [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)
      - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
      - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)
    - [2.5.2. Context Mapping](#252-context-mapping)
    - [2.5.3. Software Architecture](#253-software-architecture)
      - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
      - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
      - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
  - [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
    - [2.6.1. Bounded Context: Gestión de Proyectos](#261-bounded-context-gestión-de-proyectos)
      - [2.6.1.1. Domain Layer](#2611-domain-layer)
      - [2.6.1.2. Interface Layer](#2612-interface-layer)
      - [2.6.1.3. Application Layer](#2613-application-layer)
      - [2.6.1.4. Infrastructure Layer](#2614-infrastructure-layer)
      - [2.6.1.5. Bounded Context Software Architecture Component Level Diagrams](#2615-bounded-context-software-architecture-component-level-diagrams)
      - [2.6.1.6. Bounded Context Software Architecture Code Level Diagrams](#2616-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.1.6.1. Bounded Context Domain Layer Class Diagrams](#26161-bounded-context-domain-layer-class-diagrams)
        - [2.6.1.6.2. Bounded Context Database Design Diagram](#26162-bounded-context-database-design-diagram)
  - [2.6.2. Bounded Context: Control de Inventario](#262-bounded-context-control-de-inventario)
    - [2.6.2.1. Domain Layer](#2621-domain-layer)
    - [2.6.2.2. Interface Layer](#2622-interface-layer)
    - [2.6.2.3. Application Layer](#2623-application-layer)
    - [2.6.2.4. Infrastructure Layer](#2624-infrastructure-layer)
    - [2.6.2.5. Bounded Context Software Architecture Component Level Diagrams](#2625-bounded-context-software-architecture-component-level-diagrams)
    - [2.6.2.6. Bounded Context Software Architecture Code Level Diagrams](#2626-bounded-context-software-architecture-code-level-diagrams)
      - [2.6.2.6.1. Bounded Context Domain Layer Class Diagrams](#26261-bounded-context-domain-layer-class-diagrams)
      - [2.6.2.6.2. Bounded Context Database Design Diagram](#26262-bounded-context-database-design-diagram)
  - [2.6.3. Bounded Context: Control de Trabajadores](#263-bounded-context-control-de-trabajadores)
    - [2.6.3.1. Domain Layer](#2631-domain-layer)
    - [2.6.3.2. Interface Layer](#2632-interface-layer)
    - [2.6.3.3. Application Layer](#2633-application-layer)
    - [2.6.3.4. Infrastructure Layer](#2634-infrastructure-layer)
    - [2.6.3.5. Bounded Context Software Architecture Component Level Diagrams](#2635-bounded-context-software-architecture-component-level-diagrams)
    - [2.6.3.6. Bounded Context Software Architecture Code Level Diagrams](#2636-bounded-context-software-architecture-code-level-diagrams)
      - [2.6.3.6.1. Bounded Context Domain Layer Class Diagrams](#26361-bounded-context-domain-layer-class-diagrams)
      - [2.6.3.6.2. Bounded Context Database Design Diagram](#26362-bounded-context-database-design-diagram)
  - [2.6.4. Bounded Context: Control de Incidentes](#264-bounded-context-control-de-incidentes)
    - [2.6.4.1. Domain Layer](#2641-domain-layer)
    - [2.6.4.2. Interface Layer](#2642-interface-layer)
    - [2.6.4.3. Application Layer](#2643-application-layer)
    - [2.6.4.4. Infrastructure Layer](#2644-infrastructure-layer)
    - [2.6.4.5. Bounded Context Software Architecture Component Level Diagrams](#2645-bounded-context-software-architecture-component-level-diagrams)
    - [2.6.4.6. Bounded Context Software Architecture Code Level Diagrams](#2646-bounded-context-software-architecture-code-level-diagrams)
      - [2.6.4.6.1. Bounded Context Domain Layer Class Diagrams](#26461-bounded-context-domain-layer-class-diagrams)
      - [2.6.4.6.2. Bounded Context Database Design Diagram](#26462-bounded-context-database-design-diagram)
  - [2.6.5. Bounded Context: Control de Maquinaria](#265-bounded-context-control-de-maquinaria)
    - [2.6.5.1. Domain Layer](#2651-domain-layer)
    - [2.6.5.2. Interface Layer](#2652-interface-layer)
    - [2.6.5.3. Application Layer](#2653-application-layer)
    - [2.6.5.4. Infrastructure Layer](#2654-infrastructure-layer)
    - [2.6.5.5. Bounded Context Software Architecture Component Level Diagrams](#2655-bounded-context-software-architecture-component-level-diagrams)
    - [2.6.5.6. Bounded Context Software Architecture Code Level Diagrams](#2656-bounded-context-software-architecture-code-level-diagrams)
      - [2.6.5.6.1. Bounded Context Domain Layer Class Diagrams](#26561-bounded-context-domain-layer-class-diagrams)
      - [2.6.5.6.2. Bounded Context Database Design Diagram](#26562-bounded-context-database-design-diagram)
   
    

- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
  - [5.1. Product design](#51-product-design)
    - [5.1.1. Style Guidelines](#511-style-guidelines)
      - [5.1.1.1. General Style Guidelines](#5111-general-style-guidelines)
    - [5.1.2. Information Architecture](#512-information-architecture)
      - [5.1.2.1. Organization Systems](#5121-organization-systems)
      - [5.1.2.2. Labelling Systems](#5122-labelling-systems)
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
- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
- [6.1. Software Configuration Management](#61-software-configuration-management)
    - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
    - [6.1.2. Source Code Management](#612-source-code-management)
    - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
    - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
  - [6.2. Landing Page & Mobile Application Implementation](#62-landing-page--mobile-application-implementation)
    - [6.2.X. Sprint n](#62x-sprint-n)
      - [6.2.X.1. Sprint Planning n](#62x1-sprint-planning-n)
      - [6.2.X.2. Sprint Backlog n](#62x2-sprint-backlog-n)
      - [6.2.X.3. Development Evidence for Sprint Review](#62x3-development-evidence-for-sprint-review)
      - [6.2.X.4. Testing Suite Evidence for Sprint Review](#62x4-testing-suite-evidence-for-sprint-review)
      - [6.2.X.5. Execution Evidence for Sprint Review](#62x5-execution-evidence-for-sprint-review)
      - [6.2.X.6. Services Documentation Evidence for Sprint Review](#62x6-services-documentation-evidence-for-sprint-review)
      - [6.2.X.7. Software Deployment Evidence for Sprint Review](#62x7-software-deployment-evidence-for-sprint-review)
      - [6.2.X.8. Team Collaboration Insights during Sprint](#62x8-team-collaboration-insights-during-sprint)
  - [6.3. Validation Interviews](#63-validation-interviews)
    - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
    - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
    - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
  - [6.4. Video About-the-Product](#64-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

</div>

---

# Student Outcome

<div style="page-break-after: always;">

El curso contribuye al cumplimiento del Student Outcome ABET:<br>
**ABET – EAC - Student Outcome 3**

**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3.

<div style="page-break-after: always;">

---

# Objetivos SMART

---

# Capítulo I: Presentación

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

**Brostechnologies** es una startup fundada por jóvenes universitarios de la Universidad Peruana de Ciencias Aplicadas (UPC), enfocada en ofrecer soluciones para la gestión eficiente de proyectos de construcción dirigidos a pequeñas y medianas empresas constructoras, así como a trabajadores administrativos. A través de nuestra plataforma digital, ***Engitrack***, los usuarios pueden realizar solicitudes de servicios, además de supervisar el progreso y los gastos de cada obra.

Nuestra meta es simplificar la administración y garantizar mayor transparencia en los procesos constructivos. Entre las principales funciones que gestionamos se encuentran: la administración de personal, el control de materiales, la gestión presupuestal, el seguimiento de plazos de ejecución y el monitoreo en tiempo real del avance de los proyectos.

En **Brostechnologies** consideramos esencial optimizar los procesos de construcción para que nuestros clientes incrementen sus ganancias, reduzcan tiempos de ejecución y puedan tomar decisiones basadas en información confiable. Apostamos por la tecnología como un recurso clave para transformar el sector, facilitando que incluso las pequeñas y medianas empresas accedan a una gestión profesional, organizada y eficiente de sus obras.

**Misión:** Ofrecer soluciones digitales innovadoras que optimicen la gestión de proyectos de construcción en pequeñas y medianas empresas, permitiendo una mejor administración de recursos, seguimiento de avances, control de gastos y otros procesos, con el propósito de impulsar la eficiencia, la transparencia y la toma de decisiones estratégicas en el sector.

**Visión:** Convertirnos en la plataforma líder en Latinoamérica en la digitalización de procesos constructivos para pequeñas y medianas empresas, transformando la gestión de obras mediante tecnología accesible, eficiente y orientada a las necesidades de nuestros usuarios.


## **Fase 1: Identificación de Áreas (30 minutos)**
[Contenido]
### 1.1.2. Perfiles de integrantes del equipo
| Foto | Nombre y Apellidos | Código de Estudiante | Carrera | Resumen de Conocimientos y Habilidades |
|------|--------------------|----------------------|---------|----------------------------------------|
|  |  |  | Ingeniería de Software | EJEMPLO DE IA XDD (CAMBIARLO A TU GUSTO): Experto en desarrollo web con Vue.js, dominio de bases de datos relacionales y metodologías ágiles. Aporta habilidades en programación, documentación técnica y liderazgo de equipo. |
| ![Foto 2](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSz01csRLpbqGIyVwHlDMGyrk1jJ0VKkgej5A&s) |  |  | Ingeniería de Software | EJEMPLO DE IA (CAMBIARLO A TU GUSTO): Conocimientos en ciberseguridad, análisis de sistemas y modelado UML. Aporta al equipo su capacidad de análisis crítico y estructuración de soluciones escalables. |
|  |  |  | Ingeniería de Software | EJEMPLO DE IA (CAMBIARLO A TU GUSTO): Especialista en machine learning y ciencia de datos. Aporta experiencia en análisis estadístico, programación en Python y visualización de datos. |
|  |  |  | Ingeniería de Software | EJEMPLO DE IA (CAMBIARLO A TU GUSTO): Conocimientos en gestión de proyectos y optimización de procesos. Aporta al equipo su enfoque en eficiencia, coordinación y manejo de recursos. |

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

#### Segmento objetivo #1: Supervisores de obra
**Introducción y contexto** 
- ¿Cuál es tu nombre?
- ¿Cuántos años tiene?
- ¿En qué distrito reside?
- ¿Puedes contarme sobre tu rol como supervisor? ¿Qué haces en un día típico?
- ¿Cuántos obreros y qué tipo de materiales gestionas en una obra promedio?

**Procesos actuales** 
- ¿Cómo confirmas la asistencia de los obreros cada día? 
- ¿Qué haces si alguien falta?
- ¿Cómo llevas el control del inventario de materiales? ¿Qué herramientas usas?
- ¿Cómo registras los avances de la obra y preparas reportes? ¿Cuánto tiempo te toma?

**Puntos de dolor**
- ¿Qué es lo más frustrante o lento en la gestión de obreros o materiales? Dame un ejemplo reciente.
- ¿Alguna vez has tenido problemas por errores en inventario o reportes? ¿Qué pasó?
- ¿Qué tan fácil o difícil es coordinar con otros roles, como asistentes administrativos?

**Necesidades y expectativas**
- Si tuvieras una herramienta que centralizará asistencia, inventario y reportes ¿te ayudaría? ¿de qué manera?
- ¿Qué tan importante es tener información en tiempo real desde la obra? ¿Por qué?
- ¿Qué te haría confiar en una nueva plataforma digital? ¿Qué te preocuparía?

**Cierre**
- ¿Hay algo que no hayamos tocado que te gustaría que una herramienta como esta resolviera?
- ¿Estarías dispuesto a probar una plataforma como ArquiTech? ¿Qué necesitarías para convencerte?


### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. Ubiquitous Language


## 2.4. Requirements specification

### 2.4.1. User Stories
### 2.4.2. Impact Mapping
### 2.4.3. Product Backlog

## 2.5. Strategic-Level Domain-Driven Design

### 2.5.1. EventStorming
#### 2.5.1.1. Candidate Context Discovery

## **Fase 1: Identificación de Áreas (30 minutos)**

Se analizó el **EventStorming completo** y se buscaron las áreas del dominio que generan mayor valor.  
 Áreas detectadas:

* **Gestión de Inventario**: alta criticidad porque sin materiales no hay avance en obra (entradas, uso, alertas, historial).

* **Gestión de Proyectos**: define el inicio y estructura del trabajo (ingresar proyecto, asignar maquinaria, vincular trabajadores).

* **Control de Trabajadores**: garantiza que las tareas se ejecuten (registro, asignación, asistencia, roles).

* **Control de Maquinaria**: asegurar disponibilidad y uso adecuado en cada obra.

* **Reportes / Incidentes**: seguimiento del avance y visibilidad hacia stakeholders (reportes diarios/semanales, evidencias, notificaciones).

## **Fase 2: Identificación de Eventos Pivotales (45 minutos)**

Aquí se destacaron eventos que **marcan transiciones claras entre contextos**:

* **Proyecto registrado** → activa la necesidad de registrar trabajadores, asignar maquinaria, y preparar inventario (transición hacia otros contextos).

* **Trabajador registrado** → habilita asignación de roles/tareas y control de asistencia.

* **Material entry registered** → puede derivar en alerta de bajo inventario, afecta la continuidad de proyectos.

* **Daily report generated** → comunica a otros contextos el estado de avance, puede disparar notificaciones e incidentes.

* **Incident registered** (ejemplo extendido dentro de control de incidentes) → dispara procesos de seguridad, reasignación de recursos, notificaciones.

## **Fase 3: Agrupación y Refinamiento (15 minutos)**

Con los eventos pivotales, se agruparon los elementos dentro de los **bounded contexts definidos**:

### **Control de Trabajadores**

* Worker registered

* Task/role assigned to worker

* Attendance controlled

* Workers list per project consulted

### **Gestión de Proyectos**

* Project registered

* Machinery assigned to project

* Workers associated with project

* Select project to view reports

### **Control de Inventario**

* Material entry registered

* Material usage registered

* Low inventory alert received

* Inventory transactions consulted

### **Control de Incidentes**

* Incident registered (extensión futura de “reportes”)

* Incident resolved

* Notifications triggered by incidents

### **Control de Maquinaria**

* Machinery assigned to project registered

* Machinery usage logged

* Machinery availability updated  
  

## **Evolución del event storming**

<p align="center">
  <img src="images/event_step1.jpg" alt="PB" width="1000">
</p> 

<p align="center">
  <img src="images/event_step2.jpg" alt="PB" width="1000">
</p> 

<p align="center">
  <img src="images/event_step3.jpg" alt="PB" width="1000">
</p> 

<p align="center">
  <img src="images/event_step4.jpg" alt="PB" width="1000">
</p> 

<p align="center">
  <img src="images/event_step5.jpg" alt="PB" width="1000">
</p> 

<p align="center">
  <img src="images/event_step6.jpg" alt="PB" width="1000">
</p> 

<p align="center">
  <img src="images/event_step7.jpg" alt="PB" width="1000">
</p> 

<p align="center">
  <img src="images/event_step8.jpg" alt="PB" width="1000">
</p> 

<p align="center">
  <img src="images/event_step9.jpg" alt="PB" width="1000">
</p> 

<p align="center">
  <img src="images/event_step10.jpg" alt="PB" width="1000">
</p> 


## **Fase 4: Criterios de Separación de Contextos**

Se aplicaron los siguientes criterios para validar los límites de cada contexto:

* **Autonomía funcional**: cada bounded context debe tener lógica de negocio propia sin depender de otros.

* **Alta cohesión interna**: eventos, comandos y reglas de un contexto deben estar estrechamente relacionados.

* **Baja dependencia externa**: la interacción con otros contextos ocurre solo a través de eventos publicados o APIs bien definidas.

* **Diferentes usuarios/roles**: inventario es gestionado por un rol distinto al de proyectos o recursos humanos.

* **Evolución independiente**: se espera que cada contexto pueda escalar y evolucionar de manera separada.

## **Resultados y Recomendaciones**

* El dominio queda dividido en **5 bounded contexts claros** (trabajadores, proyectos, inventario, incidentes, maquinaria).

* **Eventos pivotales** como *Proyecto registrado*, *Trabajador registrado* y *Material entry registered* funcionan como conectores clave entre contextos.

* **Recomendación**: usar *event-driven integration* entre contextos (ej: cuando se registra un proyecto, se publican eventos que disparan flujos en trabajadores, inventario y maquinaria).

* **Siguiente paso**: diseñar los *ubiquitous language* de cada contexto y documentar las *context maps* (relaciones entre bounded contexts: partnership, customer-supplier, conformist, etc.).



#### 2.5.1.2. Domain Message Flows Modeling
#### 2.5.1.3. Bounded Context Canvases

### 2.5.2. Context Mapping

### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams
#### 2.5.3.2. Software Architecture Container Level Diagrams

<p align="center">
  <img src="images/context.png" alt="PB" width="1000">
</p> 


#### 2.5.3.3. Software Architecture Deployment Diagrams

## 2.6. Tactical-Level Domain-Driven Design

### 2.6.1. Bounded Context: Gestión de Proyectos
#### 2.6.1.1. Domain Layer
#### 2.6.1.2. Interface Layer
#### 2.6.1.3. Application Layer
#### 2.6.1.4 Infrastructure Layer
#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.1.6.2. Bounded Context Database Design Diagram

### 2.6.2. Bounded Context: Control de Inventario
#### 2.6.2.1. Domain Layer
#### 2.6.2.2. Interface Layer
#### 2.6.2.3. Application Layer
#### 2.6.2.4 Infrastructure Layer
#### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.2.6.2. Bounded Context Database Design Diagram


### 2.6.3. Bounded Context: Control de Trabajadores
#### 2.6.3.1. Domain Layer
#### 2.6.3.2. Interface Layer
#### 2.6.3.3. Application Layer
#### 2.6.3.4 Infrastructure Layer
#### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.3.6.2. Bounded Context Database Design Diagram

### 2.6.4. Bounded Context: Control de Incidentes
#### 2.6.4.1. Domain Layer
#### 2.6.4.2. Interface Layer
#### 2.6.4.3. Application Layer
#### 2.6.4.4 Infrastructure Layer
#### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.4.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.4.6.2. Bounded Context Database Design Diagram

### 2.6.5. Bounded Context: Control de Maquinaria
#### 2.6.5.1. Domain Layer
#### 2.6.5.2. Interface Layer
#### 2.6.5.3. Application Layer
#### 2.6.5.4 Infrastructure Layer
#### 2.6.5.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.5.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.5.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.5.6.2. Bounded Context Database Design Diagram




---

# Capítulo V: Solution UI/UX Design ( ESTO YA ES PARA LA TP )

## 5.1. Product design

### 5.1.1. Style Guidelines
#### 5.1.1.1. General Style Guidelines

### 5.1.2. Information Architecture
#### 5.1.2.1. Organization Systems
#### 5.1.2.2. Labelling Systems
#### 5.1.2.3. SEO Tags and Meta Tags
#### 5.1.2.4. Searching Systems
#### 5.1.2.5. Navigation Systems

### 5.1.3. Landing Page UI Design
#### 5.1.3.1. Landing Page Wireframe
#### 5.1.3.2. Landing Page Mock-up

### 5.1.4. Mobile Applications UX/UI Design
#### 5.1.4.1. Mobile Applications Wireframes
#### 5.1.4.2. Mobile Applications Wireflow Diagrams
#### 5.1.4.3. Mobile Applications Mock-ups
#### 5.1.4.4. Mobile Applications User Flow Diagrams
#### 5.1.4.5. Mobile Applications Prototyping

---

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management
### 6.1.1. Software Development Environment Configuration
### 6.1.2. Source Code Management
### 6.1.3. Source Code Style Guide & Conventions
### 6.1.4. Software Deployment Configuration

## 6.2. Landing Page & Mobile Application Implementation
### 6.2.X. Sprint n
#### 6.2.X.1. Sprint Planning n
#### 6.2.X.2. Sprint Backlog n
#### 6.2.X.3. Development Evidence for Sprint Review
#### 6.2.X.4. Testing Suite Evidence for Sprint Review
#### 6.2.X.5. Execution Evidence for Sprint Review
#### 6.2.X.6. Services Documentation Evidence for Sprint Review
#### 6.2.X.7. Software Deployment Evidence for Sprint Review
#### 6.2.X.8. Team Collaboration Insights during Sprint

## 6.3. Validation Interviews
### 6.3.1. Diseño de Entrevistas
### 6.3.2. Registro de Entrevistas
### 6.3.3. Evaluaciones según heurísticas

## 6.4. Video About-the-Product

---

# Conclusiones
## Conclusiones y recomendaciones
## Video About-the-team

---

# Bibliografía

# Anexos




