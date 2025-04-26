
# COURSE PROJECT

---

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas (UPC)</strong><br>    
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Carrera de Ingeniería de Software - Ciclo V</strong><br><br>
    <strong>Aplicaciónes Web - 4370</strong><br>
    <br><strong>Profesor: Alberto Wilmer Sanchez Seña</strong><br>
    <br><strong><b>INFORME DEL TRABAJO FINAL</strong></b><br>
</p>

<p align="center">
    <strong>Startup del Proyecto: WebWarriors</strong><br>
    <strong>Producto: Pet Nova</strong><br>
</p>

<div>
    <h3 align="center">Team Members:</h3>
</div>

<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Bastidas Bastidas, Diego Martin</td>
            <td>U20221A301</td>
        </tr>
        <tr>
            <td>Belahonia Miranda, Fabrisio  </td>
            <td>U202220219</td>
        </tr>
        <tr>
            <td>Choquehuanca Núñez, Luciana Carolina</td>
            <td>U202319431</td>
        </tr>
        <tr>
            <td>Escobar Palomino, Sebastian Matias</td>
            <td>U202220219</td>
        </tr>
        <tr>
            <td>Prado Vargas, Mario Benjamín</td>
            <td>U202115357</td>
        </tr>
    </table>
    </div>
</body>

<p align="center">
<br><strong>2025-01</strong></p>
<br>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
|----|----|----|----|
| TB1 | 26/04/2025 | WebWarriors | Redacción de los Capítulos I: Introduction, II: Requirements Elicitation & Analysis, III: Requirements Specification, IV: Product Design, V: Product Implementation, Validation & Deployment. |

# Project Report Collaboration Insights

**TB1** Las tareas correspondientes a la TB1 han sido completadas y están debidamente documentadas en el repositorio de GitHub para Pawfect Care-Report. Puedes acceder al repositorio a través del siguiente enlace: [https://github.com/1ASI0730-2510-4370-G4-PetNova/Report-Pet-Nova](https://github.com/1ASI0730-2510-4370-G4-PetNova/Report-Pet-Nova)

Durante la fase de elaboración del informe, se realizaron las siguientes actividades:

- Se crearon y redactaron los contenidos asignados a cada miembro utilizando formato Markdown, y se realizaron "Conventional Commits" para registrar el progreso en el repositorio.

-  Se generaron los recursos necesarios y agregaron las imagenes al repositorio en la carpeta "assets" en cada rama del informe.

- Se organizaron reuniones para coordinar el avance de los componentes del informe y para proporcionar actualizaciones sobre los progresos del Sprint 1, que se centró en el desarrollo de la Landing Page.

![Insight1](./assets/Chapter01/insight1.png)
![Insight2](./assets/Chapter01/insight2.png)
![Insight4](./assets/Chapter01/insight4.png)
![Insight3](./assets/Chapter01/insight3.png)
![Insight5](./assets/Chapter01/insight5.png)

# Contenido
## Tabla de contenidos
- [**Registro de Versiones del Informe**](#registro-de-versiones-del-informe)
- [**Project Report Collaboration Insights**](#project-report-collaboration-insights)
- [**Contenido**](#contenido)
    - [Tabla de contenidos](#tabla-de-contenidos)
- [**Student Outcome**](#student-outcome)
- ## [ **Capítulo I: Introducción** ](#-capítulo-i-introducción-)
  - [**1.1. Startup Profile**](#11-startup-profile)
    - [**1.1.1. Descripción de la Startup**](#111-descripción-de-la-startup)
    - [**1.1.2. Perfiles de integrantes del equipo**](#112-perfiles-de-integrantes-del-equipo)
  - [**1.2. Solution Profile**](#12-solution-profile)
    - [**1.2.1 Antecedentes y problemática**](#121-antecedentes-y-problemática)
    - [What (¿Qué?)](#what-qué)
    - [Who (¿Quién?)](#who-quién)
    - [Where (¿Dónde?)](#where-dónde)
    - [When (¿Cuándo?)](#when-cuándo)
    - [Why (¿Por qué?)](#why-por-qué)
    - [How (¿Cómo?)](#how-cómo)
    - [How much (¿Cuánto?)](#how-much-cuánto)
    - [**1.2.2 Lean UX Process**](#122-lean-ux-process)
    - [**1.2.2.1. Lean UX Problem Statements**](#1221-lean-ux-problem-statements)
    - [**1.2.2.2. Lean UX Assumptions**](#1222-lean-ux-assumptions)
    - [**1.2.2.3. Lean UX Hypothesis Statements**](#1223-lean-ux-hypothesis-statements)
    - [**1.2.2.4. Lean UX Canvas**](#1224-lean-ux-canvas)
  - [**1.3. Segmentos objetivo**](#13-segmentos-objetivo)
- ## [ **Capítulo II: Requirements Elicitation \& Analysis**](#-capítulo-ii-requirements-elicitation--analysis)
  - [**2.1. Competidores**](#21-competidores)
    - [**2.1.1. Análisis competitivo**](#211-análisis-competitivo)
    - [**2.1.2. Estrategias y tácticas frente a competidores**](#212-estrategias-y-tácticas-frente-a-competidores)
  - [**2.2. Entrevistas**](#22-entrevistas)
    - [**2.2.1. Diseño de entrevistas**](#221-diseño-de-entrevistas)
    - [**2.2.2. Registro de entrevistas**](#222-registro-de-entrevistas)
    - [**2.2.3. Análisis de entrevistas**](#223-análisis-de-entrevistas)
  - [**2.3. Needfinding**](#23-needfinding)
    - [**2.3.1. User Personas**](#231-user-personas)
    - [**2.3.2. User Task Matrix**](#232-user-task-matrix)
    - [**2.3.3. User Journey Mapping**](#233-user-journey-mapping)
    - [**2.3.4. Empathy Mapping**](#234-empathy-mapping)
    - [**2.3.5. As-is Scenario Mapping**](#235-as-is-scenario-mapping)
  - [**2.4. Ubiquitous Language**](#24-ubiquitous-language)
- ## [ **Capítulo III: Requirements Specification**](#-capítulo-iii-requirements-specification)
  - [**3.1. To-Be Scenario Mapping**](#31-to-be-scenario-mapping)
  - [**3.2. User Stories**](#32-user-stories)
  - [**3.3. Impact Mapping**](#33-impact-mapping)
  - [**3.4. Product Backlog**](#34-product-backlog)
- ## [**Capítulo IV: Product Design**](#capítulo-iv-product-design)
  - [**4.1. Style Guidelines**](#41-style-guidelines)
    - [**4.1.1. General Style Guidelines**](#411-general-style-guidelines)
    - [**4.1.2. Web Style Guidelines**](#412-web-style-guidelines)
  - [**4.2. Information Architecture**](#42-information-architecture)
    - [**4.2.1. Organization Systems**](#421-organization-systems)
    - [**4.2.2. Labeling Systems**](#422-labeling-systems)
    - [**4.2.3. SEO Tags and Meta Tags**](#423-seo-tags-and-meta-tags)
    - [**4.2.4. Searching Systems**](#424-searching-systems)
    - [**4.2.5. Navigation Systems**](#425-navigation-systems)
  - [**4.3. Landing Page UI Design**](#43-landing-page-ui-design)
    - [**4.3.1. Landing Page Wireframe**](#431-landing-page-wireframe)
    - [**4.3.2. Landing Page Mock-up**](#432-landing-page-mock-up)
  - [**4.4. Web Applications UX/UI Design**](#44-web-applications-uxui-design)
    - [**4.4.1. Web Applications Wireframes**](#441-web-applications-wireframes)
    - [**4.4.2. Web Applications Wireflow Diagrams**](#442-web-applications-wireflow-diagrams)
    - [**4.4.3. Web Applications Mock-ups**](#443-web-applications-mock-ups)
    - [**4.4.4. Web Applications User Flow Diagrams**](#444-web-applications-user-flow-diagrams)
  - [**4.5. Web Applications Prototyping**](#45-web-applications-prototyping)
  - [**4.6. Domain-Driven Software Architecture**](#46-domain-driven-software-architecture)
    - [**4.6.1. Software Architecture Context Diagram**](#461-software-architecture-context-diagram)
    - [**4.6.2. Software Architecture Container Diagrams**](#462-software-architecture-container-diagrams)
    - [**4.6.3. Software Architecture Components Diagrams**](#463-software-architecture-components-diagrams)
  - [**4.7. Software Object-Oriented Design**](#47-software-object-oriented-design)
    - [**4.7.1. Class Diagrams**](#471-class-diagrams)
    - [**4.7.2. Class Dictionary**](#472-class-dictionary)
  - [**4.8. Database Design**](#48-database-design)
    - [**4.8.1. Database Diagram**](#481-database-diagram)
- ## [**Capítulo V: Product Implementation, Validation \& Deployment**](#capítulo-v-product-implementation-validation--deployment)
  - [**5.1. Software Configuration Management**](#51-software-configuration-management)
    - [**5.1.1. Software Development Environment Configuration**](#511-software-development-environment-configuration)
    - [**5.1.2. Source Code Management**](#512-source-code-management)
    - [**5.1.3. Source Code Style Guide \& Conventions**](#513-source-code-style-guide--conventions)
    - [**5.1.4. Software Deployment Configuration**](#514-software-deployment-configuration)
  - [**5.2. Landing Page, Services \& Applications Implementation**](#52-landing-page-services--applications-implementation)
    - [**5.2.1. Sprint 1**](#521-sprint-1)
    - [**5.2.1.1. Sprint Planning 1**](#5211-sprint-planning-1)
    - [**5.2.1.2. Sprint Backlog 1**](#5212-sprint-backlog-1)
    - [**5.2.1.3. Development Evidence for Sprint Review**](#5213-development-evidence-for-sprint-review)
    - [**5.2.1.4. Testing Suite Evidence for Sprint Review**](#5214-testing-suite-evidence-for-sprint-review)
    - [**5.2.1.5. Execution Evidence for Sprint Review**](#5215-execution-evidence-for-sprint-review)
    - [**5.2.1.6. Services Documentation Evidence for Sprint Review**](#5216-services-documentation-evidence-for-sprint-review)
    - [**5.2.1.7. Software Deployment Evidence for Sprint Review**](#5217-software-deployment-evidence-for-sprint-review)
    - [**5.2.1.8. Team Collaboration Insights during Sprint**](#5218-team-collaboration-insights-during-sprint)
    
# Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
|----|----|----|
|Trabaja en equipo para proporcionar liderazgo en forma conjunta.| **Bastidas Bastidas, Diego Martin**<br>*TB1*<br> Como líder del equipo, coordiné el desarrollo del proyecto, personalmente centrándome en los Capítulos I al III. Para la introducción y análisis de la problemática, facilitamos sesiones colaborativas donde definimos el perfil de la startup, los miembros y aplicamos Lean UX. Aseguré la alineación grupal mediante revisiones y retroalimentación continua.También organicé talleres para estructurar el Impact Mapping, las User Stories y el Product Backlog, integrando múltiples perspectivas. Además hice la primera versión de la Landing Page. Finalmente, gestioné la documentación en Markdown como recurso abierto para su mejora colectiva. <br></br>**Belahonia Miranda, Fabrisio**<br>*TB1*<br>Desarrolle el Capítulo IV, centrado en el diseño de la landing page y el prototipo de la aplicación. Coordiné con diseñadores, desarrolladores y miembros no técnicos para ajustar wireframes, mockups y sistemas de etiquetado, asegurando un contenido claro y accesible para toda la audiencia. A través de revisiones iterativas, mejoramos el flujo de navegación y la presentación visual, logrando un diseño alineado con los objetivos técnicos y comunicativos del proyecto.<br></br>**Choquehuanca Núñez, Luciana Carolina**<br>*TB1*<br>Trabajé en el Capítulo IV en la parte del Figma realizando los wireframes, mockups y sistemas de etiquetado para diferentes niveles de audiencia también realice la arquitectura de software y el diseño orientado a objetos. Redacté los diagramas de contexto, contenedores y componentes, así como los diagramas de clases y la base de datos. Utilicé un lenguaje técnico adecuado para los ingenieros, pero también me aseguré de que los conceptos complejos fueran comprensibles para una audiencia más amplia.<br></br>**Escobar Palomino, Sebastian Matias**<br>*TB1*<br>Me encargué del Capítulo V, que trataba sobre la implementación y validación del producto. Redacté la configuración del entorno de desarrollo y la gestión del código de la Landing Page, utilizando un lenguaje técnico pero comprensible para audiencias menos familiarizadas con estos temas. Realice las modificacines debidas al Landing Page llegando así a su ultima versión.<br></br> **Prado Vargas, Mario Benjamín**<br>*TB1*<br>En el Capítulo V, apoyé la implementación del Sprint y la gestión del Product Backlog, priorizando tareas y clarificando responsabilidades con el equipo. Lideré la creación de los Acceptance Tests, validando criterios de aceptación. También coordiné mejoras en la Landing Page con mi compañero, integrando feedback y métricas para optimizar la usabilidad y alinear el diseño con los objetivos de negocio. <br>| TB1: Como equipo, demostramos que el liderazgo compartido y la colaboración transversal fueron claves para el éxito del proyecto. Cada integrante aportó desde su especialidad con visión alineada: Diego coordinó el uso de Lean UX y lideró talleres de Impact Mapping y User Stories; Fabrisio dirigió el prototipado y aseguró la accesibilidad del diseño; Luciana estructuró la arquitectura del sistema, simplificando conceptos técnicos; y Sebastián y Mario implementaron el Sprint, gestionaron el Product Backlog y validaron las funcionalidades, mejorando además la Landing Page con feedback y métricas.|

| Criterio específico | Acciones realizadas | Conclusiones |
|----|----|----|
|Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos| **Bastidas Bastidas, Diego Martin**<br>*TB1*<br>Como líder del equipo, creé un entorno colaborativo mediante sesiones participativas para desarrollar los Capítulos I al III. Definimos el perfil de la startup, los roles del equipo y aplicamos Lean UX, integrando distintas perspectivas. Implementé revisiones continuas, organicé talleres inclusivos para construir el Impact Mapping, las User Stories y el Product Backlog, y lancé la Landing Page como base para iteraciones colectivas. También gestioné la documentación en Markdown como recurso abierto para mejoras continuas.<br></br>**Belahonia Miranda, Fabrisio**<br>*TB1*<br>En el Capítulo IV, promoví la colaboración activa en el diseño de la Landing Page y el prototipo. Definimos objetivos de usabilidad y claridad, iterando semanalmente sobre wireframes, mockups y sistemas de etiquetado. Traducimos necesidades técnicas a lenguaje accesible y, tras pruebas de usuario y ajustes basados en feedback, logramos un diseño alineado con los objetivos del proyecto.<br></br>**Choquehuanca Núñez, Luciana Carolina**<br>*TB1*<br>En el Capítulo IV, fomenté la colaboración interdisciplinaria en el desarrollo de wireframes, mockups y la arquitectura de software. Definimos criterios comunes para el diseño orientado a objetos y los diagramas (contexto, contenedores, clases y base de datos), y planifiqué sesiones explicativas para asegurar que tanto ingenieros como no técnicos comprendieran los conceptos. Los entregables técnicos se validaron en equipo, integrando los ajustes de todos los miembros.<br></br>**Escobar Palomino, Sebastian Matias**<br>*TB1*<br>En el Capítulo V, coordiné un entorno de desarrollo inclusivo, explicando la configuración técnica y el código de la Landing Page en un lenguaje accesible. Planifiqué tareas con metas escalables y prioricé la accesibilidad. Cumplimos los objetivos mediante pruebas colaborativas y ajustes iterativos, logrando la versión final de la Landing Page con aportes de diseñadores, desarrolladores y el área de negocio.<br></br>**Prado Vargas, Mario Benjamín**<br>*TB1*<br>En el Capítulo V, facilité la colaboración en la implementación del Sprint y la gestión del Product Backlog, definiendo metas claras y asignando tareas según habilidades. Organicé sesiones diarias para alinear prioridades y validar los Acceptance Tests con el equipo. Junto a Sebastián, optimizamos la Landing Page, integrando métricas y feedback transversal para cumplir con los plazos y estándares de calidad establecidos.| TB1: Como equipo TB1, logramos el éxito gracias a la colaboración activa, inclusión y objetivos comunes. Cada miembro lideró su área, trabajando de manera transversal. Definimos metas claras, utilizamos herramientas abiertas y validamos entregables en equipo. La diversidad de habilidades fue clave, y aprendimos que el liderazgo compartido, la inclusión y la comunicación clara son esenciales. Replicaremos este modelo en futuros proyectos, documentando buenas prácticas colaborativas. <br>|

----

