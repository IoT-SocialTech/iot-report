<div align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="logo"  width="20%"/>

**Universidad Peruana de Ciencias Aplicadas** <br>
**Ingeniería de Software** <br>
**Ciclo 2024-2** <br>

<h4>Desarrollo de Soluciones IoT</h4>

**Sección:** WS71
**Profesor:** Angel Augusto Velasquez Nuñez

<h3>INFORME DEL TRABAJO FINAL</h3>

**Startup:** SocialTech

**Producto:** MIAM (Monitoreo Inteligente para Adultos Mayores)

**Integrantes:**

Achamizo Huamani, Jean Carlos <br>
Aliaga Trevejo, Lucía Guadalupe <br>
Raymundo Guevara, Rodrigo Alejandro <br>
Siancas Reategui, Luis Alberto <br>
Trujillo Lopez, Luis Alberto <br>

**Setiembre, 2024**

</div>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| ------- | ----- | ----- | ------------------------------ |
|   1.0     |   06/09/2024   |  Achamizo Huamani Jean Carlos,  Aliaga Trevejo Lucía Guadalupe, Raymundo Guevara Rodrigo Alejandro, Siancas Reategui Luis Alberto, Trujillo Lopez Luis Alberto  |   Se añadieron los elementos correspondientes al entregable de la TB1 (capítulos 1 al 4)|

---

# Project Report Collaboration Insights

URL del repositorio: https://github.com/IoT-SocialTech/iot-report

---


# Contenido

## Tabla de Contenidos

- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3 Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Mapping](#234-empathy-mapping)
    - [2.3.5 As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4 Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2 User Stories](#32-user-stories)
  - [3.3 Impact Mapping](#33-impact-mapping)
  - [3.4 Product Backlog](#34-product-backlog)

- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1 Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1 EventStorming](#411-eventstorming)
      - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2 Context Mapping](#412-context-mapping)
    - [4.1.3 Software Architecture](#413-software-architecture)
      - [4.1.3.1 Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2 Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.3 Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
      - [4.1.3.4 Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
  - [4.2 Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.1 Bounded Context: <Bounded Context Name>](#421-bounded-context-bounded-context-name)
      - [4.2.1.1 Domain Layer](#4211-domain-layer)
      - [4.2.1.2 Interface Layer](#4212-interface-layer)
      - [4.2.1.3 Application Layer](#4213-application-layer)
      - [4.2.1.4 Infrastructure Layer](#4214-infrastructure-layer)
      - [4.2.1.5 Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6 Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.1.6.1 Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
        - [4.2.1.6.2 Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
    - [4.2.2 Bounded Context: <Bounded Context Name>](#422-bounded-context-bounded-context-name)
      - [4.2.2.1 Domain Layer](#4221-domain-layer)
      - [4.2.2.2 Interface Layer](#4222-interface-layer)
      - [4.2.2.3 Application Layer](#4223-application-layer)
      - [4.2.2.4 Infrastructure Layer](#4224-infrastructure-layer)
      - [4.2.2.5 Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.2.6 Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.2.6.1 Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
        - [4.2.2.6.2 Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
    - [4.2.3 Bounded Context: <Bounded Context Name>](#423-bounded-context-bounded-context-name)
      - [4.2.3.1 Domain Layer](#4231-domain-layer)
      - [4.2.3.2 Interface Layer](#4232-interface-layer)
      - [4.2.3.3 Application Layer](#4233-application-layer)
      - [4.2.3.4 Infrastructure Layer](#4234-infrastructure-layer)
      - [4.2.3.5 Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.3.6 Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.3.6.1 Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
        - [4.2.3.6.2 Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
    - [4.2.4 Bounded Context: <Bounded Context Name>](#424-bounded-context-bounded-context-name)
      - [4.2.4.1 Domain Layer](#4241-domain-layer)
      - [4.2.4.2 Interface Layer](#4242-interface-layer)
      - [4.2.4.3 Application Layer](#4243-application-layer)
      - [4.2.4.4 Infrastructure Layer](#4244-infrastructure-layer)
      - [4.2.4.5 Bounded Context Software Architecture Component Level Diagrams](#4245-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.4.6 Bounded Context Software Architecture Code Level Diagrams](#4246-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.4.6.1 Bounded Context Domain Layer Class Diagrams](#42461-bounded-context-domain-layer-class-diagrams)
        - [4.2.4.6.2 Bounded Context Database Design Diagram](#42462-bounded-context-database-design-diagram)

  
---

# Student Outcome

| Criterio específico                                              | Acciones realizadas                                                                 | Conclusiones |
|------------------------------------------------------------------|-------------------------------------------------------------------------------------|--------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | *Achamizo Huamani Jean Carlos* <br> TB1: <br> Escribir outcome <br><br> *Aliaga Trevejo Lucía Guadalupe* <br> TB1: <br> Escribir outcome <br><br> *Raymundo Guevara Rodrigo Alejandro* <br> TB1: <br> Escribir outcome <br><br> *Siancas Reategui Luis Alberto* <br> TB1: <br> Escribir outcome <br><br> *Trujillo Lopez Luis Alberto* <br> TB1: <br> Escribir outcome <br><br>|  *TB1* <br>            |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos | *Achamizo Huamani Jean Carlos* <br> TB1: <br> Escribir outcome <br><br> *Aliaga Trevejo Lucía Guadalupe* <br> TB1: <br> Escribir outcome <br><br> *Raymundo Guevara Rodrigo Alejandro* <br> TB1: <br> Escribir outcome <br><br> *Siancas Reategui Luis Alberto* <br> TB1: <br> Escribir outcome <br><br> *Trujillo Lopez Luis Alberto* <br> TB1: <br> Escribir outcome <br><br>|   *TB1* <br>               |


---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup


### 1.1.2. Perfiles de integrantes del equipo


<table>
    <tr>
        <td>Perfil</td>
        <td>Foto</td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Achamizo Huamani, Jean Carlos<br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Como estudiante de Ingeniería de Software en la Universidad UPC, mi entusiasmo por el aprendizaje constante me impulsa a buscar siempre nuevas maneras de perfeccionar mis habilidades académicas y aplicarlas en situaciones prácticas, también poseo aptitudes en comunicación asertiva y escucha activa. Reconozco la importancia de una comunicación clara y efectiva en cualquier proyecto de software, y cuento con la capacidad de escuchar de manera atenta para comprender las necesidades y expectativas de los clientes y colegas de equipo.  
        <td><img src="./assets/JeanFoto.jpg" alt="Jean Achamizo" width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Aliaga Trevejo, Lucía Guadalupe <br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy una estudiante de Ingeniería de Software, actualmente interesada en el desarrollo web front y back end. Me gusta crear interfaces intuitivas y llamativas para mejorar la experiencia de usuario. Me considero una persona responsable y centrada. Mis habilidades blandas incluyen comunicación efectiva, trabajo en equipo, liderazgo y adaptabilidad. Aspiro a contribuir de manera significativa en proyectos innovadores para seguir expandiendo mis conocimientos técnicos y capacidades. 
        <td><img src="./assets/Lucia-Aliaga.jpg" alt="Lucía Aliaga"  width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Raymundo Guevara, Rodrigo Alejandro <br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy estudiante de la carrera de Ingeniería de Software y un apasionado de la tecnología. Me gusta descubrir nuevas formas de solucionar problemas con diversos frameworks y algoritmos. Me considero una persona responsable y empática. Me gusta mucho trabajar en equipo y ayudar a mis compañeros 
        <td><img src="./assets/RodrigoFoto.jpg" alt="Rodrigo Raymundo"  width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Siancas Reategui, Luis Alberto<br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy estudiante de la carrera de Ingeniería de Software enfocado en el desarrollo backend. Me gusta crear API’s las cuales uso para mis proyectos, por otro lado, me gusta realizar el despliegue de mis aplicaciones así como también usar diferentes diseños de arquitectura para que mi aplicación tenga un funcionamiento estable y tenga alta disponibilidad. En cuanto a mis habilidades blandas, soy empático y tengo escucha activa, esto me ayuda en gran parte a la hora de trabajar en equipos ya que facilita la comunicación y por ende los resultados son mejores. 
        <td><img src="./assets/luis_siancas.png" alt="Luis Siancas" width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Trujillo Lopez, Luis Alberto<br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Descripción 
        <td><img src="" alt="Luis Trujillo" width="600"></td>
    </tr>
   <table>

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

Los adultos mayores representan una población vulnerable no solo a enfermedades relacionadas con el envejecimiento, sino también a lesiones que pueden deteriorar significativamente su calidad de vida (Dorri, Zabolinezhad, & Sattari, 2023). De acuerdo con la Organización Mundial de la Salud, las caídas son la principal causa de lesiones y mortalidad en personas mayores de 75 años (Giulianelli et al., 2017). Ante este panorama, es esencial proporcionarles un entorno seguro que contribuya a prevenir discapacidades y complicaciones en su salud (Dorri, Zabolinezhad, & Sattari, 2023).

A continuación, se presenta un análisis detallado de esta problemática empleando la metodología ‘5W2H’.

**Who** <br>
Los adultos mayores en Perú, especialmente aquellos que viven en casas de reposo o en sus propios domicilios, representan una población vulnerable debido a las limitaciones propias del envejecimiento, como la pérdida de reflejos y del equilibrio (Suárez et al., 2020). Por otro lado, los cuidadores, tanto formales (como enfermeros y técnicos) como informales (familiares), son los responsables de brindar atención diaria. Estos cuidadores a menudo enfrentan desafíos adicionales como las exigencias de su trabajo y los recursos limitados. Esta situación puede dificultar la supervisión y la atención constante que los adultos mayores necesitan.

**What** <br>
La principal problemática es la alta incidencia de caídas entre los adultos mayores, que no solo provoca lesiones físicas como fracturas y traumatismos, sino que también tiene consecuencias psicológicas como el miedo a caer de nuevo, lo cual reduce aún más su movilidad e independencia. Para los cuidadores, cada caída significa un aumento significativo en la carga de trabajo, implicando cuidados adicionales.

**Where** <br>
Las caídas ocurren principalmente en las casas de reposo y domicilios de los adultos mayores. En las casas de reposo, la falta de personal y la infraestructura deficiente pueden contribuir al riesgo de caídas. En los domicilios, los adultos mayores a menudo se enfrentan a condiciones peligrosas como escaleras sin barandas, pisos resbaladizos, y la ausencia de dispositivos de asistencia como andadores o bastones.

**When** <br>
Las caídas pueden suceder en cualquier momento del día, pero son más comunes durante actividades cotidianas como levantarse de la cama, caminar al baño, o asearse. Las noches y madrugadas son momentos críticos debido a la disminución de la visibilidad y la menor capacidad de reacción tanto de los adultos mayores como de los cuidadores.

**Why** <br>
Las caídas suelen suceder por una combinación de factores, como la fragilidad del adulto mayor y una supervisión insuficiente. 

**How** <br>
Los adultos mayores pueden perder el equilibrio al realizar actividades diarias sin la asistencia adecuada. Los cuidadores no son capaces de realizar supervisión constante debido a que tienen varios pacientes a cargo, en especial en las casas de reposo, lo que puede llevar a descuidos involuntarios, aumentando el riesgo de caídas.

**How Much** <br>
Uno de cada tres adultos mayores de 65 años sufre caídas, de las cuales el 68% resultan en lesiones, incluyendo fracturas. Además, el 60% de las caídas ocurren en el hogar, 30% en sitios públicos y 10% en instituciones de salud, teniendo consecuencias físicas y psicológicas para el adulto mayor (Ministerio de Salud, 2018). 


### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

El estado actual de la seguridad para adultos mayores se ha centrado principalmente en productos como botones de emergencia y sensores de movimiento básicos. Sin embargo, estos productos no logran ofrecer una supervisión continua ni adaptarse a los entornos específicos en los que viven los adultos mayores. Esto deja una brecha crítica en la prevención de caídas, lo que resulta en lesiones físicas y una reducción en la calidad de vida de los adultos mayores. Los cuidadores se enfrentan a la dificultad de supervisar constantemente y gestionar los riesgos sin herramientas adecuadas para ser más proactivos.

Nuestro producto abordará esta brecha mediante el desarrollo de un sistema innovador de monitoreo basado en IoT, diseñado para ofrecer una supervisión continua y alertas en tiempo real adaptadas a los entornos específicos de cada adulto mayor. Nuestro enfoque inicial serán los cuidadores y dueños de casas de reposo, con el objetivo de mejorar la seguridad y la calidad de vida de los adultos mayores.

Sabremos que tenemos éxito cuando veamos una reducción en los incidentes de caídas, una mayor satisfacción de los cuidadores y una mejora significativa en la calidad de vida de los adultos mayores.


#### 1.2.2.2. Lean UX Assumptions
#### Assumptions worksheet

**¿Quién es el usuario?**
El usuario principal son los dueños de casas de reposo y cuidadores de adultos mayores que buscan mejorar la seguridad y bienestar de los residentes.

**¿Qué problemas tiene nuestro producto? ¿Resolver?**
MIAM resuelve la necesidad de un monitoreo constante y efectivo de los adultos mayores, ayudando a prevenir caídas, detectar cambios en signos vitales y garantizar que los residentes estén en áreas seguras y obtengan un mejor cuidado.

**¿Qué características son importantes?**
Monitoreo en tiempo real de movimientos y signos vitales.
Alertas instantáneas en caso de caídas o presencia en zonas riesgosas.
Interfaz fácil de usar en la plataforma web y aplicación móvil.
Botón de alerta para solicitar asistencia

**¿Dónde encaja nuestro producto en su trabajo o vida?**
MIAM se integra en el trabajo diario de los administradores y cuidadores como una herramienta de software esencial para supervisar la salud y en los adultos se presentarán pulseras para su monitoreo de estado, minimizando riesgos y mejorando la calidad del cuidado.
**¿Cuándo y cómo es nuestro producto? ¿Usado?**
El producto es utilizado como una pulsera continuamente a lo largo del día para monitorear en tiempo real la ubicación y salud de los residentes. Los cuidadores y administradores lo  administran tanto desde dispositivos móviles como desde la plataforma web.
**¿Cómo debe verse nuestro producto y cómo comportarse?**
El producto software debe tener una interfaz intuitiva y accesible, con gráficos claros que muestren el estado de los residentes y notificaciones visibles para alertas urgentes. Debe ser confiable, fácil de usar y responder rápidamente a cualquier evento crítico y en los residentes la pulsera debe ser ligera y de un diseño simple que no incomode a los residentes.

**Creo que mis clientes necesitan** un sistema fiable y fácil de usar para monitorear la seguridad y salud de los adultos mayores.
**Estas necesidades se pueden resolver con** una combinación de tecnología de sensores, monitoreo de signos vitales y una plataforma accesible para la gestión de datos y alertas.
**Mis clientes iniciales son (o serán)** dueños de casas de reposo y cuidadores de adultos mayores que valoran la seguridad y calidad de vida de sus residentes.
**El valor #1**que un cliente quiere de mi servicio es la capacidad de prevenir accidentes y responder rápidamente a emergencias, garantizando la seguridad de los residentes.
**El cliente también puede obtener estos beneficios adicionales** como la tranquilidad de los familiares, una mayor eficiencia en la gestión del cuidado y una reducción en los incidentes graves.
**Voy a adquirir la mayoría de mis clientes a través de** estrategias de marketing directo a casas de reposo y promociones en eventos de la industria geriátrica.
**Haré dinero a través de** la venta de los equipos  de pulsera y la suscripción al sistema de monitoreo.
**Mi competencia principal en el mercado serán** otros proveedores de sistemas de monitoreo para adultos mayores, así como dispositivos de salud y seguridad específicos.
Los venceremos debido a nuestra integración completa de sensores de movimiento, monitoreo de signos vitales y una plataforma fácil de usar que ofrece alertas en tiempo real.
**Mi mayor riesgo de producto es** la posibilidad de que los sensores o la plataforma no funcionen correctamente en situaciones críticas.
Resolveremos esto a través de pruebas exhaustivas, mantenimiento regular y la implementación de redundancias en el sistema para asegurar su fiabilidad.
**¿Qué otras suposiciones tenemos? ¿Eso, si se prueba que es falso, causará que nuestro negocio/proyecto no funcione?**
Asumimos que los clientes estarán dispuestos a pagar una suscripción mensual para mantener el servicio. Si no es así, podríamos enfrentar dificultades financieras.

#### 1.2.2.3. Lean UX Hypothesis Statements
#### Features Hypothesis
**Statement 1:**
Creemos que la incorporación de un botón de alerta en la banda de monitoreo que los residentes puedan activar manualmente reducirá el tiempo de reacción en situaciones de emergencia.
Sabremos que hemos tenido éxito cuando el 90% de las alertas manuales se respondan en menos de 2 minutos durante los primeros 6 meses de uso.
**Statement 2:** 											Creemos que el incluir alertas instantáneas en la aplicación móvil para notificar a los cuidadores sobre caídas o cambios anómalos en signos vitales mejorará la respuesta a emergencias.
Sabremos que hemos tenido éxito cuando veamos una reducción del 30% en el tiempo de respuesta ante emergencias registradas en los primeros 3 meses de uso.
**Statement 3:**
Creemos que la integración de un historial de salud y actividad en la plataforma web permitirá a los cuidadores tomar decisiones más informadas sobre el bienestar de los residentes.
Sabremos que hemos tenido éxito cuando el 80% de los usuarios informen que revisan el historial de salud al menos una vez por semana para ajustar el plan de cuidado.

#### Business Hypothesis

**Statement 1:**
Creemos que el alquiler de equipos junto con la suscripción al sistema de monitoreo MIAM será la mejor estrategia para obtener ingresos sostenibles.
Sabremos que esto es cierto cuando el 70% de las casas de reposo que prueben el sistema opten por continuar con la suscripción después del periodo de prueba inicial.
**Statement 2:**
Creemos que ofrecer un periodo de prueba gratuito de 30 días aumentará la tasa de adopción inicial de nuestro sistema entre nuevas casas de reposo.
Sabremos que esto es cierto cuando al menos el 60% de los usuarios que completen el periodo de prueba decidan suscribirse al servicio.
**Statement 3:**
Creemos que al asociarnos con organizaciones de cuidado geriátrico y hospitales locales podremos ampliar nuestro mercado objetivo y generar más leads calificados.
Sabremos que esto es cierto cuando el 50% de las nuevas suscripciones provengan de referencias o asociaciones con estas instituciones dentro de los primeros 6 meses

#### 1.2.2.4. Lean UX Canvas


## 1.3. Segmentos objetivo

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

| Nombre del Competidor | Descripción |
| :-------------------: | :---------- |
| Competidor 1 | Descripcion |
| Competidor 2 | Descripcion |
| Competidor 3 | Descripcion |

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
  </tr>
  <tr>
    <td colspan="5">Comparar las características y funcionalidades clave de nuestra solución con las de la competencia para identificar ventajas competitivas y posibles áreas de mejora.</td>
  </tr>
  <tr>
    <td colspan="3">Competidores</td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center">
        Nuestro producto
        <div style="text-align: center; margin-top: 10px;">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center">
        Competidor1
        <div style="text-align: center; margin-top: 10px;">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center" >
        Competidor2
        <div style="text-align: center; margin-top: 10px;">
        </div>
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center" >
        Competidor3
        <div style="text-align: center; margin-top: 10px;">
        </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Precios y Costos</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top"> Nuestro producto
    </td>
    <td colspan="1" valign="top">Competidor1
    </td>
    <td colspan="1" valign="top">Competidor2
    </td>
    <td colspan="1" valign="top">Competidor3
    </td>
  </tr>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores

<table>
  <tr>
    <th colspan="3" valign="top"></th>
    <th colspan="4" valign="top"><b>OPORTUNIDADES</b></th>
    <th colspan="4" valign="top"><b>AMENAZAS</b></th>
  </tr>
  <tr>
    <th colspan="3" valign="top"></th>
    <td colspan="4" valign="top">
        Colocar oportunidades
        </td>
    <td colspan="4" valign="top">
        Colocar amenazas
    </td>
  </tr>

  <tr>
    <th colspan="3" valign="top"><b>FORTALEZAS</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS FO (Ofensivas)</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS FA (Defensiva)</b></th>
  </tr>
  <tr>
    <td colspan="3" valign="top">
    Colocar fortalezas
    </td>
    <td colspan="4" valign="top">
    Colocar estrategias FO
    </td>
    <td colspan="4" valign="top">
    Colocar estrategias FA
    </td>
  </tr>

  <tr>
    <th colspan="3" valign="top"><b>DEBILIDADES</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS DO (Reorientación)</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS DA (Supervivencia)</b></th>
  </tr>
  <tr>
    <td colspan="3" valign="top">
    Colocar debilidades
    </td>
    <td colspan="4" valign="top">
    Colocar estrategias DO
    </td>
    <td colspan="4" valign="top">
    Colocar estrategias DA
    </td>

  </tr>

</table>

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

<table border=1>
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Nombre<br>
      <b>Edad: </b> años <br>
      <b>Distrito:</b> distrito <br>
      <b>Timing:</b> 0:00 - 0:00 minutos
      <b>Duración:</b>  minutos
    </td>
    <td align=center>
      <img src="./assets/Entrevista_PieroValverde.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a></a>
      <br>
      <b>Resumen:</b> resumen
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Nombre<br>
      <b>Edad: </b> años <br>
      <b>Distrito:</b> distrito <br>
      <b>Timing:</b> 0:00 - 0:00 minutos
      <b>Duración:</b>  minutos
    </td>
    <td align=center>
      <img src="./assets/Entrevista_PieroValverde.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a></a>
      <br>
      <b>Resumen:</b> resumen
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Nombre<br>
      <b>Edad: </b> años <br>
      <b>Distrito:</b> distrito <br>
      <b>Timing:</b> 0:00 - 0:00 minutos
      <b>Duración:</b>  minutos
    </td>
    <td align=center>
      <img src="./assets/Entrevista_PieroValverde.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a></a>
      <br>
      <b>Resumen:</b> resumen
    </td>
  </tr>
</table>

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

<table border=1>
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Nombre<br>
      <b>Edad: </b> años <br>
      <b>Distrito:</b> distrito <br>
      <b>Timing:</b> 0:00 - 0:00 minutos
      <b>Duración:</b>  minutos
    </td>
    <td align=center>
      <img src="./assets/Entrevista_PieroValverde.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a></a>
      <br>
      <b>Resumen:</b> resumen
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Nombre<br>
      <b>Edad: </b> años <br>
      <b>Distrito:</b> distrito <br>
      <b>Timing:</b> 0:00 - 0:00 minutos
      <b>Duración:</b>  minutos
    </td>
    <td align=center>
      <img src="./assets/Entrevista_PieroValverde.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a></a>
      <br>
      <b>Resumen:</b> resumen
    </td>
  </tr>
</table>

<table border=1>
  <tr>
    <td>
      <b>Nombres y <br>apellidos:</b> Nombre<br>
      <b>Edad: </b> años <br>
      <b>Distrito:</b> distrito <br>
      <b>Timing:</b> 0:00 - 0:00 minutos
      <b>Duración:</b>  minutos
    </td>
    <td align=center>
      <img src="./assets/Entrevista_PieroValverde.png" alt="img"  width="80%"/>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <b>Enlace:</b> <a></a>
      <br>
      <b>Resumen:</b> resumen
    </td>
  </tr>
</table>

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

![User Persona](./assets/user-persona.png)

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

![User Persona](./assets/user-persona-.png)


### 2.3.2. User Task Matrix

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

<table>
  <tr>
    <th>User Task</th>
    <th colspan="2">Nombre</th>
  </tr>
  <tr>
    <th></th>
    <th>Frequency</th>
    <th>Importance</th>
  </tr>
  <tr>
    <td>Task 1</td>
    <td>SIEMPRE</td>
    <td>ALTA</td>
  </tr>
  
</table>

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

<table>
  <tr>
    <th>User Task</th>
    <th colspan="2">Nombre</th>
  </tr>
  <tr>
    <th></th>
    <th>Frequency</th>
    <th>Importance</th>
  </tr>
  <tr>
    <td>Task 1</td>
    <td>USUALMENTE</td>
    <td>ALTA</td>
  </tr>
</table>

### 2.3.3. User Journey Mapping

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

![User Journey Mapping](./assets/user-journey-mapping.png)

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

![User Journey Mapping](./assets/user-journey-mapping-.png)

### 2.3.4. Empathy Mapping

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

![Empathy Mapping](./assets/empathy-mapping.png)

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

![Empathy Mapping](./assets/empathy-mapping-.png)

### 2.3.5. As-is Scenario Mapping

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

![As-Is Scenario Mapping](./assets/asis-scenario-mapping.png)

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

![As-Is Scenario Mapping](./assets/asis-scenario-mapping.png)

## 2.4. Ubiquitous Language

---

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**Segmento 1:** Cuidadores de adultos mayores (Caregivers)

![To-Be Scenario Mapping](./assets/tobe-scenario-mapping.png)

**Segmento 2:** Dueños de casas de reposo (Nursing Home Owners)

![To-Be Scenario Mapping](./assets/tobe-scenario-mapping.png)

## 3.2. User Stories

| **Epic / User Story ID** | **Título**                                    | **Descripción**                                                                                                                                                                                                                             | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                          | **Relacionado con (Epic ID)** |
|---------------------------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **EP01**                  | **Nombre Epic 01**          | Descripción epic 1                        |                                                                                                                                                                                                                                                                                                                |                               |
| **US01**                  | **Nombre de US01**            | Descripción de US01                                                                                              | - **Scenario 1:** US scenario 1 <br> - **Scenario 2:** US scenario 2             | EP01 |



## 3.3. Impact Mapping

![Impact Mapping](./assets/impactmapping.svg)

## 3.4. Product Backlog

# Product Backlog

## Tabla de Product Backlog

| **Orden** | **User Story Id** | **Título**                                    | **Descripción**                                                                                                                                                                                                                             | **Story Points** |
|-----------|----------------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| 1         | US01| Nombre US01   | Descripción US01                                                                          | Story points              |


# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Event Storming

#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2 Domain Message Flows Modeling

#### 4.1.1.3 Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3..4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

#### 4.2.1. Bounded Context: <Bounded Context Name>

##### 4.2.1.1. Domain Layer

##### 4.2.1.2. Interface Layer

##### 4.2.1.3. Application Layer

##### 4.2.1.4. Infrastructure Layer

##### 4.2.1.6. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.1.7. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.1.7.1. Bounded Context Domain Layer Class Diagrams

###### 4.2.1.7.2. Bounded Context Database Design Diagram

#### 4.2.2. Bounded Context: <Bounded Context Name>

##### 4.2.2.1. Domain Layer

##### 4.2.2.2. Interface Layer

##### 4.2.2.3. Application Layer

##### 4.2.2.4. Infrastructure Layer

##### 4.2.2.6. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.2.7. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.2.7.1. Bounded Context Domain Layer Class Diagrams

###### 4.2.2.7.2. Bounded Context Database Design Diagram

#### 4.2.3. Bounded Context: <Bounded Context Name>

##### 4.2.3.1. Domain Layer

##### 4.2.3.2. Interface Layer

##### 4.2.3.3. Application Layer

##### 4.2.3.4. Infrastructure Layer

##### 4.2.3.6. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.3.7. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.3.7.1. Bounded Context Domain Layer Class Diagrams

###### 4.2.3.7.2. Bounded Context Database Design Diagram

#### 4.2.4. Bounded Context: <Bounded Context Name>

##### 4.2.4.1. Domain Layer

##### 4.2.4.2. Interface Layer

##### 4.2.4.3. Application Layer

##### 4.2.4.4. Infrastructure Layer

##### 4.2.4.6. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.4.7. Bounded Context Software Architecture Code Level Diagrams

###### 4.2.4.7.1. Bounded Context Domain Layer Class Diagrams

###### 4.2.4.7.2. Bounded Context Database Design Diagram

---

# Conclusiones

--- 

# Bibliografía
 
 Dorri, S., Zabolinezhad, H., & Sattari, M. (2023). *The application of Internet of Things for the elderly health safety: A systematic review*. Advances in Biomedical Research, 12, 109. https://doi.org/10.4103/abr.abr_197_22 

Giulianelli, D., De Luca, G., De Luca, S., García, G., Carnuccio, E., Valiente, W., & Volker, M. (2017). *Diseño de sistema IoT de monitoreo y alarma para personas mayores*. Repositorio institucional de la UNLP, Universidad Nacional de La Plata.  https://sedici.unlp.edu.ar/handle/10915/62406 

Ministerio de Salud. (2018, 13 de diciembre). *Uno de cada tres adultos mayores de 65 años sufre una caída*. https://www.gob.pe/institucion/minsa/noticias/23629-uno-de-cada-tres-adultos-mayores-de-65-anos-sufre-una-caida

Suárez, G., Velasco, V., Limones, M. , Reyes, H., & Delgado, V. (2020). *Caídas en el adulto mayor y factores de riesgo*. European Journal of Child Development, Education and Psychopathology, 8(1), 47–56. https://doi.org/10.30552/ejpad.v8i1.130 

--- 

# Anexos