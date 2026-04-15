<h2 style="text-align: center;"> Universidad Peruana de Ciencias Aplicadas </h2>

<h4 style="text-align: center"> Ingeniería de Software </h4>

<h4 style="text-align: center"> Periodo: 202610 </h4>
<br>
 <p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="upc-logo" width="80px" height="80px"/>
</p>


<h4 style="text-align: center"> Fundamentos de Arquitectura de Software </h4>

<h4 style="text-align: center"> Sección: 7944 </h4>

<h4 style="text-align: center"> Docente: Abel Nehemias Rosales Caururu </h4>

<h3 style="text-align: center;"> Informe de Trabajo Final </h3>

<h4 style="text-align: center"> Startup: COMPLETAR </h4>

<h4 style="text-align: center"> Producto: COMPLETAR </h4>

<h4 style="text-align: center">Integrantes:</h4>

<div style="text-align:center; margin-top: 10px; font-size: 90%; line-height: 1.6;">
   <table style="margin-left: auto; margin-right: auto;">
      <tr>
         <th>Código</th>
         <th>Apellidos y Nombres</th>
      </tr>
      <tr>
         <td>[COMPLETAR]</td>
         <td>[COMPLETAR]</td>
      </tr>
      <tr>
         <td>u202312966</td>
         <td>Gonzales Alvarado, Javier Sebastian</td>
      </tr>
      <tr>
         <td>[COMPLETAR]</td>
         <td>[COMPLETAR]</td>
      </tr>
      <tr>
         <td>[COMPLETAR]</td>
         <td>[COMPLETAR]</td>
      </tr>
      <tr>
         <td>[COMPLETAR]</td>
         <td>[COMPLETAR]</td>
      </tr>
   </table>
</div>

<br>

<h5 style="text-align: center; font-style: italic;"> Abril 2026 </h5>

<hr class="page-break">

# Registro de Versiones del Informe

| Version | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
|         |       |       |                             |

<hr class="page-break">

# Contenido

- [Capítulo I: Introducción](#capítulo-i-introducción)
   - [1.1. Startup Profile](#11-startup-profile)
      - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
      - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
   - [1.2. Solution Profile](#12-solution-profile)
      - [1.2.1. Nombre del producto](#121-nombre-del-producto)
      - [1.2.2. Antecedentes y problemática](#122-antecedentes-y-problemática)
      - [1.2.3. Lean UX Process](#123-lean-ux-process)
         - [1.2.3.1. Lean UX Problem Statement](#1231-lean-ux-problem-statement)
         - [1.2.3.2. Lean UX Assumptions](#1232-lean-ux-assumptions)
         - [1.2.3.3. Lean UX Hypothesis](#1233-lean-ux-hypothesis)
         - [1.2.3.4. Lean UX Canvas](#1234-lean-ux-canvas)
   - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements & Analysis](#capítulo-ii-requirements--analysis)
   - [2.1. Competidores](#21-competidores)
   - [2.2. Entrevistas](#22-entrevistas)
   - [2.3. Needfinding](#23-needfinding)
      - [2.3.1. User Personas](#231-user-personas)
      - [2.3.2. User Task Matrix](#232-user-task-matrix)
      - [2.3.3. Empathy Maps](#233-empathy-maps)
      - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
   - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
   - [3.2. User Stories](#32-user-stories)
   - [3.3. Impact Map](#33-impact-map)
   - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Product Architecture Design](#capítulo-iv-product-architecture-design)
   - [4.1. Design Concepts, ViewPoints & ER Diagrams](#41-design-concepts-viewpoints--er-diagrams)
      - [4.1.1. Principles Statements](#411-principles-statements)
      - [4.1.2. Approaches Statements Architectural Styles & Patterns](#412-approaches-statements-architectural-styles--patterns)
      - [4.1.3. Context Diagram](#413-context-diagram)
      - [4.1.4. Approach driven ViewPoints Diagrams](#414-approach-driven-viewpoints-diagrams)
      - [4.1.5. Relational/Non Relational Database Diagram](#415-relationalnon-relational-database-diagram)
      - [4.1.6. Design Patterns](#416-design-patterns)
      - [4.1.7. Tactics](#417-tactics)
   - [4.2. Architectural Drivers](#42-architectural-drivers)
      - [4.1.8. Design Purpose](#418-design-purpose)
      - [4.1.9. Primary Functionality (Primary User Stories)](#419-primary-functionality-primary-user-stories)
      - [4.1.10. Quality Attribute Scenarios](#4110-quality-attribute-scenarios)
      - [4.1.11. Constraints](#4111-constraints)
      - [4.1.12. Architectural Concerns](#4112-architectural-concerns)
   - [4.3. ADD Iterations](#43-add-iterations)
      - [4.2.X. Iteration N: Iteration Name](#42x-iteration-n-iteration-name)
         - [4.2.X.1. Architectural Design Backlog N](#42x1-architectural-design-backlog-n)
         - [4.2.X.2. Establish Iteration Goal by Selecting Drivers](#42x2-establish-iteration-goal-by-selecting-drivers)
         - [4.2.X.3. Choose One or More Elements of the System to Refine](#42x3-choose-one-or-more-elements-of-the-system-to-refine)
         - [4.2.X.4. Choose One or More Design Concepts That Satisfy the Selected Drivers](#42x4-choose-one-or-more-design-concepts-that-satisfy-the-selected-drivers)
         - [4.2.X.5. Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces](#42x5-instantiate-architectural-elements-allocate-responsibilities-and-define-interfaces)
         - [4.2.X.6. Sketch Views (C4 & UML) and Record Design Decisions](#42x6-sketch-views-c4--uml-and-record-design-decisions)
         - [4.2.X.7. Analysis of Current Design and Review Iteration Goal (Kanban Board)](#42x7-analysis-of-current-design-and-review-iteration-goal-kanban-board)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
   - [5.1. Testing Suites & General Patterns](#51-testing-suites--general-patterns)
      - [5.1.1. Backend Application Core Testing Suite](#511-backend-application-core-testing-suite)
      - [5.1.2. Pattern Based Backend Application(s)](#512-pattern-based-backend-applications)
      - [5.1.3. Pattern Based Custom Software Library](#513-pattern-based-custom-software-library)
      - [5.1.4. Framework Pattern Driven Refactoring Report](#514-framework-pattern-driven-refactoring-report)
   - [5.2. Software Configuration Management](#52-software-configuration-management)
      - [5.2.1. Software Development Environment Configuration](#521-software-development-environment-configuration)
      - [5.2.2. Source Code Management](#522-source-code-management)
      - [5.2.3. Source Code Style Guide & Conventions](#523-source-code-style-guide--conventions)
      - [5.2.4. Software Deployment Configuration](#524-software-deployment-configuration)
   - [5.3. Microservices Implementation](#53-microservices-implementation)
      - [5.3.1. Sprint 1](#531-sprint-1)
         - [5.3.1.1. Sprint Backlog 1](#5311-sprint-backlog-1)
         - [5.3.1.2. Development Evidence for Sprint Review](#5312-development-evidence-for-sprint-review)
         - [5.3.1.3. Testing Suite Evidence for Sprint Review](#5313-testing-suite-evidence-for-sprint-review)
         - [5.3.1.4. Execution Evidence for Sprint Review](#5314-execution-evidence-for-sprint-review)
         - [5.3.1.5. Microservices Documentation Evidence for Sprint Review](#5315-microservices-documentation-evidence-for-sprint-review)
         - [5.3.1.6. Software Deployment Evidence for Sprint Review](#5316-software-deployment-evidence-for-sprint-review)
         - [5.3.1.7. Team Collaboration Insights during Sprint](#5317-team-collaboration-insights-during-sprint)
         - [5.3.1.8. Kanban Board](#5318-kanban-board)
      - [5.3.2. Sprint 2](#532-sprint-2)
         - [5.3.2.1. Sprint Backlog 2](#5321-sprint-backlog-2)
         - [5.3.2.2. Development Evidence for Sprint Review](#5322-development-evidence-for-sprint-review)
         - [5.3.2.3. Testing Suite Evidence for Sprint Review](#5323-testing-suite-evidence-for-sprint-review)
         - [5.3.2.4. Execution Evidence for Sprint Review](#5324-execution-evidence-for-sprint-review)
         - [5.3.2.5. Microservices Documentation Evidence for Sprint Review](#5325-microservices-documentation-evidence-for-sprint-review)
         - [5.3.2.6. Software Deployment Evidence for Sprint Review](#5326-software-deployment-evidence-for-sprint-review)
         - [5.3.2.7. Team Collaboration Insights during Sprint](#5327-team-collaboration-insights-during-sprint)
         - [5.3.2.8. Kanban Board](#5328-kanban-board)
      - [5.3.3. Sprint 3](#533-sprint-3)
         - [5.3.3.1. Sprint Backlog 3](#5331-sprint-backlog-3)
         - [5.3.3.2. Development Evidence for Sprint Review](#5332-development-evidence-for-sprint-review)
         - [5.3.3.3. Testing Suite Evidence for Sprint Review](#5333-testing-suite-evidence-for-sprint-review)
         - [5.3.3.4. Execution Evidence for Sprint Review](#5334-execution-evidence-for-sprint-review)
         - [5.3.3.5. Microservices Documentation Evidence for Sprint Review](#5335-microservices-documentation-evidence-for-sprint-review)
         - [5.3.3.6. Software Deployment Evidence for Sprint Review](#5336-software-deployment-evidence-for-sprint-review)
         - [5.3.3.7. Team Collaboration Insights during Sprint](#5337-team-collaboration-insights-during-sprint)
         - [5.3.3.8. Kanban Board](#5338-kanban-board)
      - [5.3.4. Sprint 4](#534-sprint-4)
         - [5.3.4.1. Sprint Backlog 4](#5341-sprint-backlog-4)
         - [5.3.4.2. Development Evidence for Sprint Review](#5342-development-evidence-for-sprint-review)
         - [5.3.4.3. Testing Suite Evidence for Sprint Review](#5343-testing-suite-evidence-for-sprint-review)
         - [5.3.4.4. Execution Evidence for Sprint Review](#5344-execution-evidence-for-sprint-review)
         - [5.3.4.5. Microservices Documentation Evidence for Sprint Review](#5345-microservices-documentation-evidence-for-sprint-review)
         - [5.3.4.6. Software Deployment Evidence for Sprint Review](#5346-software-deployment-evidence-for-sprint-review)
         - [5.3.4.7. Team Collaboration Insights during Sprint](#5347-team-collaboration-insights-during-sprint)
         - [5.3.4.8. Kanban Board](#5348-kanban-board)
   - [5.4. Microservices Deployment](#54-microservices-deployment)
      - [5.4.1. Cloud Architecture Diagram](#541-cloud-architecture-diagram)
      - [5.4.2. Cloud Architecture Deployment](#542-cloud-architecture-deployment)

- [Conclusiones](#conclusiones)
- [Referencias Bibliográficas](#referencias-bibliográficas)
- [Anexos](#anexos)

<hr class="page-break">

# Student Outcome

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome.

<table>
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5"><strong>[COMPLETAR: Criterio 1]</strong></td>
      <td><strong>[COMPLETAR: Integrante 1]</strong><br><b>TB1:</b></td>
      <td rowspan="5"><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 2]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 3]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 4]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 5]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td rowspan="5"><strong>[COMPLETAR: Criterio 2]</strong></td>
      <td><strong>[COMPLETAR: Integrante 1]</strong><br><b>TB1:</b></td>
      <td rowspan="5"><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 2]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 3]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 4]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 5]</strong><br><b>TB1:</b></td>
    </tr>
  </tbody>
</table>

<hr class="page-break">

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Pafi Solutions es una startup tecnológica enfocada en el desarrollo de soluciones digitales en el sector salud. Está conformada por estudiantes de Ingeniería de Software de séptimo ciclo comprometidos con la innovación y el uso de tecnologías modernas para resolver problemas en la realidad peruana. La startup busca aplicar principios de arquitectura de software, desarrollo ágil y buenas prácticas de ingeniería para crear productos digitales escalables y de alto impacto.

Misión: Desarrollar soluciones de software que permitan mejorar procesos relacionados a la salud.

Visión: Convertirse en la startup referente en el desarrollo de soluciones tecnológicas que contribuyan a mejorar la salud de las personas. 

Alcance del proyecto: Pafi Solutions tiene como alcance el diseño y desarrollo de soluciones digitales enfocadas en el sector salud, inicialmente centradas en la gestión y seguimiento de tratamientos médicos. La startup busca validar su propuesta mediante el desarrollo de un producto mínimo viable, con el objetivo de escalar hacia soluciones más completas dentro del ámbito de la salud digital.


### 1.1.2. Perfiles de integrantes del equipo

<table>
  <thead>
    <tr>
      <th>Perfil</th>
      <th>Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>[COMPLETAR: Apellidos, Nombres]</strong><br>[COMPLETAR: descripción]</td>
      <td><img src="assets/images/photos/[COMPLETAR].jpg" alt="[COMPLETAR]" width="200"></td>
    </tr>
    <tr>
      <td><strong>Gonzales Alvarado, Javier Sebastian</strong><br>Mi nombre es Javier Gonzales, soy estudiante de Ingeniería de Software de séptimo ciclo. Tengo conocimientos en diversos lenguajes de programación como C++, Python y JavaScript, entre otros. Además, he desarrollado proyectos de software utilizando distintos frameworks como Angular y Vue. Me considero una persona responsable, empática y analítica. Mi objetivo personal es desarrollar soluciones tecnológicas que contribuyan a mejorar la calidad de vida de las personas y aportar a la construcción de un mundo más innovador y conectado</td>
      <td><img src="assets/images/photos/gonzales.jpeg" alt="[COMPLETAR]" width="200"></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Apellidos, Nombres]</strong><br>[COMPLETAR: descripción]</td>
      <td><img src="assets/images/photos/[COMPLETAR].jpg" alt="[COMPLETAR]" width="200"></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Apellidos, Nombres]</strong><br>[COMPLETAR: descripción]</td>
      <td><img src="assets/images/photos/[COMPLETAR].jpg" alt="[COMPLETAR]" width="200"></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Apellidos, Nombres]</strong><br>[COMPLETAR: descripción]</td>
      <td><img src="assets/images/photos/[COMPLETAR].jpg" alt="[COMPLETAR]" width="200"></td>
    </tr>
  </tbody>
</table>

<hr class="page-break">

## 1.2. Solution Profile

### 1.2.1. Nombre del producto

MediTrack es una aplicación móvil que busca ayudar a pacientes a cumplir con sus tratamientos médicos. La solución busca reducir los olvidos y errores en la toma de medicamentos mediante la generación de recordatorios inteligentes, así como facilitar el seguimiento de citas médicas y exámenes. De este modo se prevenimos los olvidos de pacientes, errores de dosis, falta de segumiento, abandono del tratamiento, etc.

### 1.2.2. Antecedentes y problemática

#### WHAT (Qué)

¿Cuál es el problema?

En el Perú, muchas personas no siguen correctamente sus tratamientos médicos, especialmente quienes tienen enfermedades crónicas. Esto ocurre porque olvidan tomar sus medicamentos, se confunden con las dosis o no cumplen con los horarios indicados. Según un estudio sobre adherencia terapéutica en pacientes con enfermedades crónicas en Lima, existe un nivel importante de incumplimiento en los tratamientos, lo cual afecta directamente la calidad de vida de los pacientes (Vargas Rodríguez, 2022). Esta situación representa un problema relevante en el sistema de salud, ya que puede empeorar las enfermedades si no se controla adecuadamente.


#### WHEN (Cuándo)

¿Cuándo sucede el problema?

Este problema ocurre principalmente durante el día a día del tratamiento, especialmente cuando los pacientes deben seguir rutinas constantes por largos periodos. Es común que el incumplimiento se presente con el paso del tiempo, cuando los pacientes olvidan sus dosis o dejan de seguir las indicaciones médicas de manera continua. Según un estudio de la universidad cayetano heredia, el incumplimiento del tratamiento es un fenómeno frecuente a lo largo del proceso de atención médica, sobre todo en tratamientos prolongados (Luzeve Gutiérrez, 2019).


#### WHERE (Dónde)

¿Dónde surge el problema?

El problema se presenta en el sistema de salud peruano, tanto en hospitales como, principalmente, en el entorno cotidiano del paciente, debido a la falta de supervisión constante. Como evidencia, en el año 2022 se registraron más de 5.5 millones de personas con hipertensión arterial en el Perú. Según el Dr. Chuquiruna, el 56.7% de estos pacientes no se adhiere al tratamiento por diversos motivos, entre los cuales destaca el olvido de tomar uno o más medicamentos (Consultor Salud, 2023).


#### WHO (Quién)

¿Quiénes son los afectados?

Los principales afectados son los pacientes con enfermedades crónicas, como diabetes, hipertensión o problemas cardíacos, quienes deben seguir tratamientos de forma constante. En muchos casos, estos pacientes presentan dificultades para cumplir correctamente con sus medicamentos y controles.

Adicionalmente, esta solución también beneficia al sistema de salud, ya que puede funcionar como un canal de comunicación entre médicos y pacientes. Los médicos podrán registrar o subir las recetas desde un portal, mientras que los pacientes recibirán automáticamente los recordatorios en sus dispositivos móviles, facilitando el seguimiento del tratamiento.


#### WHY (Por qué)

¿Cuál es la causa del problema?

Este problema se debe principalmente a factores como el olvido, la falta de información y la complejidad de los tratamientos médicos. Muchos pacientes no siguen correctamente sus indicaciones porque deben tomar varios medicamentos en distintos horarios, lo que genera confusión. En el Perú, esta situación se agrava por factores como la desorganización en los tratamientos y la ausencia de herramientas que ayuden a los pacientes a cumplir sus horarios. 

#### HOW (Cómo)

¿Cómo se utilizará el producto?

El producto se utilizará a través de una aplicación móvil donde el paciente podrá visualizar y gestionar su tratamiento de manera sencilla. Los médicos podrán registrar o subir la receta desde un portal web, la cual será procesada para generar automáticamente los horarios y recordatorios de medicación. A partir de ello, el paciente recibirá notificaciones en su celular que le indicarán cuándo tomar sus medicamentos, asistir a citas o realizar exámenes, facilitando así el seguimiento continuo del tratamiento en su vida diaria.


#### HOW MUCH (Cuánto)

¿Cuánto costará implementar la solución?

Para esta primera versión de la aplicación, el costo será relativamente bajo, ya que se desarrollará utilizando tecnologías accesibles. Se emplearán frameworks modernos y servicios cloud gratuitos, como Azure for Students. Por el momento, nos concentraremos en el contexto académico, pero con la visión de expandirnos en el futuro hacia un ámbito más profesional.

### 1.2.3. Lean UX Process

#### 1.2.3.1. Lean UX Problem Statement

El propósito de MediTrack es brindar a los pacientes con enfermedades crónicas en el Perú una herramienta digital accesible que les permita llevar un seguimiento adecuado de sus tratamientos médicos, recordándoles la toma de medicamentos y ayudándolos a mantener una mejor adherencia, con el fin de mejorar su calidad de vida.

El problema se presenta en el sistema de salud peruano, principalmente fuera de los entornos hospitalarios, donde los pacientes no cuentan con una supervisión constante. Esto provoca que muchos de ellos olviden tomar sus medicamentos o no sigan correctamente las indicaciones médicas.

Hemos observado que esta situación genera complicaciones en la salud de los pacientes, incrementa el riesgo de enfermedades graves y reduce la efectividad de los tratamientos. Además, evidencia una falta de herramientas tecnológicas simples y accesibles que acompañen al paciente en su vida diaria, fuera del entorno clínico. Esta desconexión entre la indicación médica y el seguimiento real del tratamiento representa una brecha importante en el cuidado de la salud.

Y ante esta problemática nos surge la siguiente pregunta: ¿Cómo podríamos ayudar a los pacientes a cumplir correctamente sus tratamientos médicos en su día a día, mediante una solución accesible, simple y efectiva?

+ **Domain:** Salud digital y monitoreo de tratamientos médicos.

+ **Customer Segments:** Pacientes peruanos con enfermedades crónicas.

+ **Pain Points:** 

  + Olvido de medicamentos
  + Falta de seguimiento continuo
  + Ausencia de supervisión médica diaria
  + Falta de comunicación o entendimiento entre el doctor y paciente

+ **Gap:** No existe una solución accesible y enfocada en el contexto peruano que ayude a los pacientes a gestionar y cumplir sus tratamientos de manera constante.

+ **Vision/Strategy:** Desarrollar una aplicación que permita a los pacientes llevar un control de sus tratamientos mediante recordatorios, alertas y seguimiento, mejorando su adherencia y reduciendo riesgos de salud.

+ **Initial Segment:** Pacientes con hipertensión en Lima Metropolitana que cuentan con acceso a smartphones.

#### 1.2.3.2. Lean UX Assumptions

##### Business Assumptions

1. **Creo nuestros usuarios tienen la necesidad** de recordar y cumplir correctamente sus tratamientos médicos en su vida diaria.

2. **Estas necesidades se pueden satisfacer** mediante una aplicación móvil con recordatorios, alertas y seguimiento personalizado.

3. **Nuestros clientes iniciales serán** serán pacientes con enfermedades crónicas en Lima Metropolitana, especialmente con hipertensión.

4. **El valor más importante que un cliente quiere de nuestros servicios es** la facilidad para no olvidar tomar sus medicamentos.

5. **El cliente también va a obtener** mayor control de su salud y reducción de riesgos asociados a su enfermedad.

6. **Vamos a obtener la mayoría de los clientes mediante** recomendaciones médicas, integrandonos en clínicas y hospitales, donde se recomendará la aplicación a los pacientes como apoyo para el seguimiento de sus tratamientos.

7. **Vamos a obtener ingresos mediante** suscripciones premium (para los centros de salud) y alianzas con clínicas o hospitales. 

8. **Nuestra competencia en el mercado serán** aplicaciones de salud genéricas y recordatorios de medicamentos existentes.

9. **Vamos a tener ventaja frente a nuestra competencia debido a** nuestra simplicidad, enfoque en el contexto peruano y facilidad de uso.

10. **El mayor riesgo del servicio es** que los usuarios no adopten o abandonen la aplicación con el tiempo.

11. **Lo resolveremos realizando** mejoras continuas en la experiencia de usuario y funcionalidades de valor.

12. **Otro riesgo que debemos considerar es que** los usuarios no confíen en la aplicación para gestionar información de salud.


##### User Assumptions

1. ¿Quién es el usuario? 

Pacientes con enfermedades crónicas que necesitan seguir un tratamiento médico constante, y también clínicas y hospitales que gestionan el historial clínico y recetas del paciente para generar recordatorios y dar seguimiento al tratamiento.

2. ¿Dónde encaja nuestro producto en su vida? 

Encaja en la rutina diaria del paciente como una herramienta de apoyo para el cuidado de su salud. Para las clínicas y hospitales, encaja como un complemento digital que extiende el seguimiento del tratamiento más allá de la consulta médica.

3. ¿Qué problemas resuelve nuestro producto? 

Resuelve el olvido en la toma de medicamentos, la falta de organización en los tratamientos y la ausencia de seguimiento continuo. Además, ayuda a reducir errores en la medicación y mejora la comunicación indirecta entre paciente y centro de salud.

4. ¿Cuándo y cómo se usa nuestro producto? 

Se utiliza diariamente en momentos clave, como horarios de medicación o revisiones del tratamiento. Funciona mediante notificaciones automáticas, alertas y una interfaz donde el usuario puede registrar el cumplimiento de su tratamiento de forma sencilla.

5. ¿Qué características son importantes? 

Son importantes la facilidad de uso, recordatorios automáticos y configurables, registro del cumplimiento del tratamiento, integración con información médica (recetas e historial médico) y notificaciones claras.

6. ¿Cómo debería lucir y comportarse el producto?

Debe tener un diseño simple, intuitivo y accesible para todo tipo de usuarios, incluyendo personas mayores. Su comportamiento debe ser confiable, rápido y amigable, brindando información clara y precisa, así evitando generar confusión o sobrecarga de notificaciones.


##### Feature Assumptions

+ Creemos que los usuarios necesitan recordatorios automáticos de medicamentos que se ajusten a los horarios indicados en su tratamiento.

+ Creemos que los usuarios necesitan un sistema de registro digital de recetas médicas accesible desde su dispositivo móvil, para poder consultar en cualquier momento las indicaciones de su tratamiento sin depender de documentos físicos.

+ Creemos que las clínicas y hospitales necesitan una funcionalidad que les permita subir recetas e historiales clínicos directamente a la plataforma, de modo que el paciente reciba información confiable y centralizada desde su médico.

+ Creemos que los usuarios necesitan notificaciones personalizadas basadas en su tipo de tratamiento, frecuencia y rutina diaria, para mejorar la adherencia y evitar interrupciones en su medicación.

+ Creemos que los usuarios necesitan visualizar el progreso de su tratamiento mediante indicadores claros de cumplimiento, lo que les permitirá mantenerse motivados y conscientes de su avance.

#### 1.2.3.3. Lean UX Hypothesis

1. Hypothesis Statement 01:

**Creemos que** implementar recordatorios automáticos de medicamentos para pacientes resultará en un mayor cumplimiento de sus tratamientos médicos.

**Sabremos que** hemos tenido éxito

**Cuando** al menos el 80% de las dosis programadas sean marcadas como completadas por los usuarios.

2. Hypothesis Statement 02:

**Creemos que** permitir a clínicas y hospitales subir recetas e historiales clínicos directamente en la plataforma para pacientes resultará en un incremento en la cantidad de usuarios activos en la aplicación.

**Sabremos que** esto es cierto

**Cuando** al menos el 60% de los nuevos usuarios registrados provengan de instituciones de salud afiliadas.

3. Hypothesis Statement 03:

**Creemos que** enviar notificaciones personalizadas según el tratamiento de cada paciente resultará en un mayor nivel de interacción de los usuarios con la aplicación.

**Sabremos que** esto es cierto

**Cuando** más del 70% de los usuarios interactúen con las notificaciones recibidas.



#### 1.2.3.4. Lean UX Canvas

<p align="center">
    <img src="assets/images/Lean Ux Canvas - Fundamentos.png" alt="upc-logo" width="1000px" height="560px"/>
</p>

<hr class="page-break">

## 1.3. Segmentos objetivo

#### Segmento 1: Pacientes

Este segmento está conformado por personas que siguen tratamientos médicos de corta, mediana o larga duración y requieren apoyo para cumplir correctamente con la toma de sus medicamentos y el seguimiento de indicaciones médicas. Incluye pacientes con enfermedades crónicas, tratamientos postoperatorios o cualquier condición que implique una medicación constante. Estos usuarios buscan herramientas que les faciliten organizar su tratamiento, reducir olvidos y mejorar su salud.

+ Características Demográficas:

  + Edad: 18 a más de 65 años
  + Género: Masculino y femenino
  + Nivel socioeconómico: Medio
  + Nivel educativo: Secundaria completa y superior.
  + Ocupación: Estudiantes, trabajadores dependientes e independientes.
  + Condición: Personas con tratamientos médicos activos (crónicos o temporales).

+ Características Geográficas:

  + Ubicación: Principalmente zonas urbanas.
  + Región: Lima Metropolitana (fase inicial), expansión a nivel nacional (a futuro)
  + Entorno: Ciudades con acceso a servicios de salud.


+ Sustento estadístico:

En el Perú, la adherencia a tratamientos médicos representa un problema relevante, ya que diversos estudios indican que entre el 59% y 69% de los pacientes no cumplen adecuadamente sus tratamientos farmacológicos, especialmente en enfermedades crónicas como la hipertensión  . Asimismo, investigaciones evidencian que aproximadamente el 71% de los pacientes ha olvidado tomar su medicación al menos una vez, lo que refleja una alta incidencia de incumplimiento terapéutico . Estos datos demuestran la necesidad de soluciones tecnológicas que ayuden a mejorar la adherencia, reducir olvidos y optimizar el seguimiento de tratamientos en la población.

#### Segmento 2: Personal técnico de centros médicos

Este segmento está conformado por el personal técnico y el área de sistemas de clínicas, hospitales y centros médicos, responsables de gestionar, implementar y mantener las soluciones tecnológicas dentro de la institución. Estos usuarios buscan herramientas que permitan digitalizar procesos, mejorar la gestión de información médica y facilitar la integración de sistemas que optimicen el seguimiento de los tratamientos de los pacientes.

+ Características Organizacionales:

  + Entidades: Clínicas privadas, hospitales públicos y centros médicos.
  + Tamaño: Pequeñas, medianas y grandes instituciones.
  + Sector: Salud
  + Personal: Ingenieros de sistemas, técnicos de TI, soporte tecnológico.

+ Características Geográficas:

  + Ubicación: Zonas urbanas
  + Región: Lima Metropolitana (fase inicial)
  + Infraestructura: Centros con acceso a sistemas digitales e internet


+ Sustento estadístico:

En el contexto del sistema de salud peruano, se ha identificado que problemas en la gestión y seguimiento de tratamientos afectan directamente a los pacientes, evidenciándose que hasta el 25% de personas con enfermedades graves como cáncer experimentan retrasos o interrupciones en sus tratamientos, en parte debido a fallas en la coordinación y disponibilidad de información médica. Además, la creciente digitalización del sector salud impulsa a clínicas y hospitales a adoptar soluciones tecnológicas que mejoren la comunicación con pacientes y el control de tratamientos, lo que posiciona a estas instituciones como actores clave en la implementación de plataformas digitales orientadas al seguimiento médico.



<hr class="page-break">

# Capítulo II: Requirements & Analysis

## 2.1. Competidores

<table>
  <tr>
    <th colspan="6">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2" align="center"><b>¿Por qué llevar a cabo este análisis?</b></td>
    <td colspan="4">Es importante analizar a la competencia para entender las necesidades y expectativas de los clientes, así como las fortalezas y debilidades de las competencias. Esto ayudará a identificar oportunidades de mejora y desafíos para la empresa.</td>
  </tr>
  <tr>
    <th colspan="2">Nombre</th>
    <th>MediTrack</th>
    <th>MyTherapy</th>
    <th>CareClinic</th>
    <th>Medisafe</th>
  </tr>
  <tr>
    <td colspan="2" align="center"><b>Logo</b></td>
    <td align="center"><img src="assets/images/competidores/Meditrack.png" alt="Talki logo" width="100"></td>
    <td align="center"><img src="assets/images/competidores/mytherapy.png" alt="[Competidor 1]" width="100"></td>
    <td align="center"><img src="assets/images/competidores/careClinic.png" alt="[Competidor 2]" width="100"></td>
    <td align="center"><img src="assets/images/competidores/R.jpeg" alt="[Competidor 2]" width="100"></td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td>Es una app diseñada para cerrar la brecha entre la indicación médica y el cumplimiento real del paciente-</td>
    <td>Es como un "compañero diario" para la gestión de medicación y diario de salud, enfocado en simplicidad.</td>
    <td>Es una plataforma de gestión de salud basada en marcos clínicos para el autocuidado proactivo.</td>
    <td>Es el lider en gestión de medicación con alertas inteligentes y soporte para cuidadores.</td>
  </tr>
  <tr>
    <td><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td>
    <td>Automatización del flujo de información médico-paciente. Elimina la carga manual de datos, reduciendo el riesgo de errores de dosis y olvidos.</td>
    <td>Simplicidad de la app y en los reportes de salud gratuitos listos para entregar al médico tratante.</td>
    <td>Análisis avanzado de patrones; correlaciona hábitos, síntomas y clima con la salud.</td>
    <td>Red de seguridad mediante "Medfriends" y alertas de interacciones medicamentosas</td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td>Pacientes en Lima Metropolitana y personal técnico de clínicas y hospitales privados/públicos.</td>
    <td>Pacientes crónicos (Diabetes, Esclerosis Múltiple, TDAH) que requieren diarios de salud.</td>
    <td>Usuarios que buscan "biohacking" o gestión compleja de enfermedades crónicas.</td>
    <td>Adultos mayores y familias que requieren supervisar la toma de medicamentos a distancia.</td>
  </tr>
  <tr>
    <td><b>Estrategias de Marketing</b></td>
    <td>Convenios de digitalización con clínicas para reducir sus retrasos operativos.</td>
    <td>Alianzas con sociedades médicas (ej. Sociedad de Diabetes) y blogs de salud científica..</td>
    <td>Marketing de contenidos sobre protocolos médicos (Stanford/Mayo Clinic) y SEO técnico.</td>
    <td>Recomendaciones en farmacias (Walgreens/CVS) y pauta en buscadores médicos.</td>
  </tr>
  <tr>
    <td rowspan="3"><b>Perfil de Producto</b></td>
    <td><b>Productos &amp; Servicios</b></td>
    <td>App móvil centrada para el Paciente y portal web para clínicas donde pueden gestionar de recetas y monitoreo.</td>
    <td>Alarmas de pastillas, registro de síntomas y contador de pasos integrado.</td>
    <td>Rastreador de dolor, diario de humor, planes de nutrición y sincronización con Apple Health.</td>
    <td>Recordatorios de dosis, aviso de reabastecimiento y base de datos de fármacos.</td>
  </tr>
  <tr>
    <td><b>Precios y Costos</b></td>
    <td>Modelo de suscripción para instituciones y versión gratuita para pacientes con opciones de reportes avanzados (Freemium).</td>
    <td>100% Gratuito (sin publicidad ni compras dentro de la app).</td>
    <td>Freemium (Versión Pro para análisis de datos avanzados).</td>
    <td>Gratis con opción Premium (aprox. $4.99/mes) para más voces y temas.</td>
  </tr>
  <tr>
    <td><b>Canales de distribución</b></td>
    <td>Implementación directa en sistemas de clínicas, Google Play, App Store.</td>
    <td>App Store, Google Play y pagina web oficial.</td>
    <td>App Store, Google Play y pagina web oficial.</td>
    <td>App Store, Google Play y pagina web oficial.</td>
  </tr>
  <tr>
    <td rowspan="4"><b>Análisis SWOT</b></td>
    <td><b>Fortalezas</b></td>
    <td>Conocimiento del sistema de salud local y capacidad de integración técnica con centros médicos peruanos.</td>
    <td>Alta privacidad de datos y avalada por estudios de investigación en Europa.</td>
    <td>Basada en protocolos clínicos reales; alta capacidad de personalización.</td>
    <td>Posee la mayor base de datos de medicamentos y gran reconocimiento de marca.</td>
  </tr>
  <tr>
    <td><b>Oportunidades</b></td>
    <td>Alta tasa de incumplimiento en Perú (59%-69%) y la necesidad de digitalización post-pandemia en el sector salud.</td>
    <td>Convertirse en la app estándar para investigaciones clínicas a nivel global.</td>
    <td>Integración con sistemas de farmacia (PMS) para pedidos de recetas en tiempo real.</td>
    <td>Alianzas con compañías de seguros de salud para monitorear pacientes en riesgo.</td>
  </tr>
  <tr>
    <td><b>Debilidades</b></td>
    <td>Dependencia inicial de la adopción por parte del personal técnico de las clínicas.</td>
    <td>El diseño es muy austero y puede resultar poco motivador para usuarios jóvenes.</td>
    <td>Curva de aprendizaje elevada; puede ser difícil de usar para personas mayores.</td>
    <td>La mayoría de funciones de valor (como el Medfriend ilimitado) son de pago.</td>
  </tr>
  <tr>
    <td><b>Amenazas</b></td>
    <td>Resistencia al cambio en procesos burocráticos de hospitales públicos y competencia de apps gratuitas globales.</td>
    <td>Riesgo de sostenibilidad financiera al no cobrar al usuario final.</td>
    <td>Competencia de apps de nicho que se enfocan en una sola enfermedad.</td>
    <td>Regulaciones estrictas de privacidad de datos (HIPAA/GDPR) que limiten el uso de datos.</td>
  </tr>
</table>

#### Estrategias y tácticas frente a competidores

Para Meditrack, nos enfocaremos en la mayor ventaja: la unificación. Mientras los competidores obligan al usuario a saltar entre la app de la farmacia, el calendario de Google y un diario de salud, ofreceremos un ecosistema cerrado.

Ademas, aplicaremos las siguientes estrategias y tácticas frente a los competidores:

- **Estrategia de Doble Valor** Se buscar diferenciarse de Medisafe y MyTherapy atacando simultáneamentea los problemas del paciente y del centro médico.

  - **Táctica de Integración para TI:** A diferencia de la competencia que es aislada, MediTrack ofrecerá una API de Carga Masiva para el personal técnico de clínicas. Esto reduce el retraso en tratamientos por fallas de coordinación.
  
  - **Táctica de Receta Digital Automática:** El paciente no configura su tratamiento; el centro médico lo hace por él. Esto ataca directamente el 71% de olvidos por falta de organización.

En resumen, nuestra real ventaja es la desorganización sistémica. Nosotros al incluir al Personal Técnico, convertimos a las clínicas en nuestro principal promotor, asegurando que el paciente use la app por recomendación de su propia institución de salud, lo que garantiza la confianza y la retención a largo plazo.

<hr class="page-break">


## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas


### 2.2.3. Análisis de entrevistas


<hr class="page-break">

## 2.3. Needfinding
En esta sección, el equipo presenta el análisis detallado de las necesidades, dolores y comportamientos de nuestros segmentos objetivo.

### 2.3.1. User Personas
En esta sección, se presentan las fichas de User Persona diseñadas para representar a nuestros dos segmentos objetivo. Estos perfiles son el resultado de la síntesis de las entrevistas a profundidad realizadas y el análisis comparativo de la competencia.

#### Segmento 1: Pacientes

<td align="center"><img src="assets/images/Ricardo Alberto Luján.png" alt="User persona 2"></td>

#### Segmento 2: Personal técnico de centros médicos

<td align="center"><img src="assets/images/Claudia Valdivia.png" alt="User persona 1" ></td>


### 2.3.2. User Task Matrix

Para la sección del User Task Matrix, es fundamental separar las actividades cotidianas de los usuarios de las funciones específicas del software. Aquí analizamos cómo Ricardo y Claudia gestionan sus responsabilidades actuales, lo que nos permitirá identificar dónde MediTrack puede aportar el mayor valor.

<table>
  <thead>
    <tr>
      <th rowspan="2">Tareas</th>
      <th colspan="2">Pacientes </th>
      <th colspan="2">Personal técnico de centros médicos</th>
    </tr>
    <tr>
      <th>Frecuencia</th>
      <th>Importancia</th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Tomar los medicamentos en el horario indicado</td>
      <td>Alta</td>
      <td>Critica</td>
      <td>N/A</td>
      <td>N/A</td>
    </tr>
    <tr>
      <td>Contar manualmente las pastillas que le quedan</td>
      <td>Media</td>
      <td>Alta</td>
      <td>N/A</td>
      <td>N/A</td>
    </tr>
    <tr>
      <td>Leer las instrucciones de la receta física</td>
      <td>Media</td>
      <td>Alta</td>
      <td>N/A</td>
      <td>N/A</td>
    </tr>
    <tr>
      <td>Preparar requisitos para exámenes</td>
      <td>Baja</td>
      <td>Alta</td>
      <td>N/A</td>
      <td>N/A</td>
    </tr>
    <tr>
      <td>Trasladarse al hospital para agendar citas</td>
      <td>Baja</td>
      <td>Media</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Transcribir datos del paciente al archivo físico</td>
      <td>N/A</td>
      <td>N/A</td>
      <td>Alta</td>
      <td>Crítica</td>
    </tr>
    <tr>
      <td>Informar al paciente sobre su próximo control</td>
      <td>N/A</td>
      <td>N/A</td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Revisar el inventario de citas del día</td>
      <td>N/A</td>
      <td>N/A</td>
      <td>Alta</td>
      <td>Media</td>
    </tr>
  </tbody>
</table>

#### Análisis de la Matriz
Al observar las tareas que realizan Ricardo y Claudia en su entorno natural, sin asistencia digital especializada, se identifican los siguientes puntos clave:

**Tareas con mayor carga (Frecuencia e Importancia):**
- Para Ricardo, la tarea diaria y crítica es la ingesta de medicamentos. Al depender de su memoria o de alarmas genéricas de reloj, el riesgo de error es máximo. 
- Para Claudia, la transcripción de datos y la búsqueda de expedientes consumen la mayor parte de su tiempo, siendo tareas críticas para evitar errores administrativos en el hospital.

**Principales Contradicciones:**
- Las tareas de Ricardo son logísticas y de autocuidado (contar pastillas, recordar horarios, leer papeles). 
- Las tareas de Claudia son organizacionales y de archivo (gestionar expedientes físicos, transcribir información). 
- Ricardo sufre por la memoria individual, mientras que Claudia sufre por el caos del volumen de información.

**Principales Coincidencias:**
- Ambos segmentos coinciden en la alta importancia de la coordinación de citas y controles. 
- Ambos consideran que la pérdida de una cita rompe la continuidad del tratamiento.

**Puntos de Dolor Identificados:**
La matriz revela que el proceso actual es altamente manual. Tareas como "contar pastillas" o "buscar expedientes físicos" son ineficientes y propensas al error humano. Esta es precisamente la brecha que MediTrack vendrá a digitalizar para transformar estas tareas pesadas en procesos automáticos.

### 2.3.3. Empathy Maps

Los Empathy Maps son herramientas de diseño efectivas, que responder a la realidad humana y psicológica de cada segmento. A continuación, se presentan los Empathy Maps para los dos segmentos objetivo.

#### Segmento 1: Pacientes

<td align="center"><img src="assets/images/Empathy map - Pacientes.png" alt="Empathy Map - Pacientes" ></td>

#### Segmento 2: Personal técnico de centros médicos

<td align="center"><img src="assets/images/Empathy map - Tecnicos.png" alt="Empathy Map - Tecnicos" ></td>

### 2.3.4. As-is Scenario Mapping
En esta sección se presenta un análisis detallado de la situación actual (AS-IS) para los diferentes segmentos. A través de este mapeo, identificamos los procesos, las interacciones y las emociones clave, proporcionando una visión clara de los puntos críticos.

Para tener una visión más clara de los escenarios, puede revisar el siguiente link: https://lucid.app/lucidspark/a26b2a1e-0c17-4428-aba7-c0949b7349e3/edit?viewport_loc=-141%2C-63%2C2265%2C1035%2C0_0&invitationId=inv_5a727633-905e-446c-bbfc-4069c628a26c

#### Segmento 1: Pacientes

<td align="center"><img src="assets/images/AS-IS-pacientes.png" alt="AS IS PACIENTES" ></td>

#### Segmento 2: Personal técnico de centros médicos

<td align="center"><img src="assets/images/AS-IS-tecnicos.png" alt="AS IS TECNICOS" ></td>

<hr class="page-break">

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

En esta sección se presenta un análisis detallado de la situación futura (TO-BE) para los diferentes segmentos. A través de este mapeo, proyectamos los procesos automatizados, las interacciones digitales y los factores de éxito clave, ofreciendo una visión clara de los puntos de mejora resueltos.

Para tener una visión más clara de los escenarios, puede revisar el siguiente link: https://lucid.app/lucidspark/a26b2a1e-0c17-4428-aba7-c0949b7349e3/edit?viewport_loc=-141%2C-63%2C2265%2C1035%2C0_0&invitationId=inv_5a727633-905e-446c-bbfc-4069c628a26c


#### Segmento 1: Pacientes

<td align="center"><img src="assets/images/TO-BE-pacientes.png" alt="TO BE PACIENTES" ></td>

#### Segmento 2: Personal técnico de centros médicos

<td align="center"><img src="assets/images/TO-BE-tecnicos.png" alt="TO BE TECNICOS" ></td>


<hr class="page-break">

## 3.2. User Stories

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------|--------|-------------|-------------------------|---------------------------|
|                 |        |             |                         |                           |

<hr class="page-break">

## 3.3. Impact Map



<hr class="page-break">

## 3.4. Product Backlog

| # Orden | User Story ID | Título | Descripción | Story Points |
|---------|---------------|--------|-------------|--------------|
|         |               |        |             |              |

<hr class="page-break">

# Capítulo IV: Product Architecture Design

## 4.1. Design Concepts, ViewPoints & ER Diagrams

### 4.1.1. Principles Statements



### 4.1.2. Approaches Statements Architectural Styles & Patterns



### 4.1.3. Context Diagram



### 4.1.4. Approach driven ViewPoints Diagrams



### 4.1.5. Relational/Non Relational Database Diagram



### 4.1.6. Design Patterns



### 4.1.7. Tactics



<hr class="page-break">

## 4.2. Architectural Drivers

### 4.1.8. Design Purpose



### 4.1.9. Primary Functionality (Primary User Stories)

| ID | Título | Descripción |
|----|--------|-------------|
|    |        |             |

### 4.1.10. Quality Attribute Scenarios

| ID | Atributo de Calidad | Fuente | Estímulo | Artefacto | Entorno | Respuesta | Medida de Respuesta |
|----|---------------------|--------|----------|-----------|---------|-----------|---------------------|
|    |                     |        |          |           |         |           |                     |

### 4.1.11. Constraints

| ID | Restricción |
|----|-------------|
|    |             |

### 4.1.12. Architectural Concerns

| ID | Concern | Descripción |
|----|---------|-------------|
|    |         |             |

<hr class="page-break">

## 4.3. ADD Iterations

### 4.2.1. Iteration 1: [Nombre de la Iteración]

#### 4.2.1.1. Architectural Design Backlog 1

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Decisión de Diseño</th>
      <th>Estado</th>
      <th>Driver(s) Relacionados</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### 4.2.1.2. Establish Iteration Goal by Selecting Drivers



#### 4.2.1.3. Choose One or More Elements of the System to Refine



#### 4.2.1.4. Choose One or More Design Concepts That Satisfy the Selected Drivers



#### 4.2.1.5. Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces

| Elemento | Responsabilidad | Interfaces |
|----------|-----------------|------------|
|          |                 |            |

#### 4.2.1.6. Sketch Views (C4 & UML) and Record Design Decisions



#### 4.2.1.7. Analysis of Current Design and Review Iteration Goal (Kanban Board)

<table>
  <thead>
    <tr>
      <th>Por hacer</th>
      <th>En progreso</th>
      <th>Hecho</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

<hr class="page-break">

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Testing Suites & General Patterns

### 5.1.1. Backend Application Core Testing Suite



### 5.1.2. Pattern Based Backend Application(s)



### 5.1.3. Pattern Based Custom Software Library



### 5.1.4. Framework Pattern Driven Refactoring Report



<hr class="page-break">

## 5.2. Software Configuration Management

### 5.2.1. Software Development Environment Configuration



### 5.2.2. Source Code Management

Se utilizó **GitHub** como plataforma de control de versiones y colaboración en equipo.

Los integrantes del equipo y sus nombres de usuario en GitHub son los siguientes:

| Integrantes | Nombre en GitHub |
|-------------|------------------|
|             |                  |
|             |                  |
|             |                  |
|             |                  |
|             |                  |

### 5.2.3. Source Code Style Guide & Conventions



### 5.2.4. Software Deployment Configuration



<hr class="page-break">

## 5.3. Microservices Implementation

### 5.3.1. Sprint 1

#### 5.3.1.1. Sprint Backlog 1

| Sprint # | User Story | Work-Item / Task | Descripción | Estimación (horas) | Asignado a | Estado |
|----------|------------|------------------|-------------|-------------------|------------|--------|
| Sprint 1 |            |                  |             |                   |            |        |

#### 5.3.1.2. Development Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 5.3.1.3. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 5.3.1.4. Execution Evidence for Sprint Review



#### 5.3.1.5. Microservices Documentation Evidence for Sprint Review

| Microservicio | Verbo | Endpoint | Parámetros | Response |
|---------------|-------|----------|------------|----------|
|               |       |          |            |          |

#### 5.3.1.6. Software Deployment Evidence for Sprint Review



#### 5.3.1.7. Team Collaboration Insights during Sprint

| Integrantes | Tarea asignada |
|-------------|----------------|
|             |                |

#### 5.3.1.8. Kanban Board

<hr class="page-break">

### 5.3.2. Sprint 2

#### 5.3.2.1. Sprint Backlog 2

| Sprint # | User Story | Work-Item / Task | Descripción | Estimación (horas) | Asignado a | Estado |
|----------|------------|------------------|-------------|-------------------|------------|--------|
| Sprint 2 |            |                  |             |                   |            |        |

#### 5.3.2.2. Development Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 5.3.2.3. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 5.3.2.4. Execution Evidence for Sprint Review



#### 5.3.2.5. Microservices Documentation Evidence for Sprint Review

| Microservicio | Verbo | Endpoint | Parámetros | Response |
|---------------|-------|----------|------------|----------|
|               |       |          |            |          |

#### 5.3.2.6. Software Deployment Evidence for Sprint Review



#### 5.3.2.7. Team Collaboration Insights during Sprint

| Integrantes | Tarea asignada |
|-------------|----------------|
|             |                |

#### 5.3.2.8. Kanban Board

<hr class="page-break">

### 5.3.3. Sprint 3

#### 5.3.3.1. Sprint Backlog 3

| Sprint # | User Story | Work-Item / Task | Descripción | Estimación (horas) | Asignado a | Estado |
|----------|------------|------------------|-------------|-------------------|------------|--------|
| Sprint 3 |            |                  |             |                   |            |        |

#### 5.3.3.2. Development Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 5.3.3.3. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 5.3.3.4. Execution Evidence for Sprint Review



#### 5.3.3.5. Microservices Documentation Evidence for Sprint Review

| Microservicio | Verbo | Endpoint | Parámetros | Response |
|---------------|-------|----------|------------|----------|
|               |       |          |            |          |

#### 5.3.3.6. Software Deployment Evidence for Sprint Review



#### 5.3.3.7. Team Collaboration Insights during Sprint

| Integrantes | Tarea asignada |
|-------------|----------------|
|             |                |

#### 5.3.3.8. Kanban Board

<hr class="page-break">

### 5.3.4. Sprint 4

#### 5.3.4.1. Sprint Backlog 4

| Sprint # | User Story | Work-Item / Task | Descripción | Estimación (horas) | Asignado a | Estado |
|----------|------------|------------------|-------------|-------------------|------------|--------|
| Sprint 4 |            |                  |             |                   |            |        |

#### 5.3.4.2. Development Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 5.3.4.3. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 5.3.4.4. Execution Evidence for Sprint Review



#### 5.3.4.5. Microservices Documentation Evidence for Sprint Review

| Microservicio | Verbo | Endpoint | Parámetros | Response |
|---------------|-------|----------|------------|----------|
|               |       |          |            |          |

#### 5.3.4.6. Software Deployment Evidence for Sprint Review



#### 5.3.4.7. Team Collaboration Insights during Sprint

| Integrantes | Tarea asignada |
|-------------|----------------|
|             |                |

#### 5.3.4.8. Kanban Board

<hr class="page-break">

## 5.4. Microservices Deployment

### 5.4.1. Cloud Architecture Diagram



### 5.4.2. Cloud Architecture Deployment (AWS, Microsoft Azure o Google Cloud)



<hr class="page-break">

# Conclusiones

## Conclusiones y recomendaciones



## Video About-The-Team



<hr class="page-break">

# Referencias Bibliográficas

- CareClinic. (s.f.). Health Tracker: Symptoms, Meds, and Chronic Illness. Recuperado el 14 de abril de 2026, de https://careclinic.io/

- Medisafe. (s.f.). Digital Health Platform: Adherence, Persistence, and Solutions. Recuperado el 14 de abril de 2026, de https://www.medisafe.com

- MyTherapy. (s.f.). Aplicación de recordatorio de medicación y gestión de la salud. Recuperado el 14 de abril de 2026, de https://www.mytherapyapp.com/es

<hr class="page-break">

# Anexos

## Links
