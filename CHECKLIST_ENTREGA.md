# Checklist de Entrega para Sistemas Desarrollados por Estudiantes

|Versión|Autor|Descripción|
|---|---|---|
|24.04.1|lherrera@dcc.uchile.cl|creación del documento inicial en gdocs|
|24.05.1|jarriagada@dcc.uchile.cl|reestructuración y ajustes en base a requisitos de gobernabilidad de sistemas|

___

## Contenidos

### Sobre este checklist

En el DCC es común que se desarrolle software en el contexto de trabajos de memoria o tesis de estudiantes. Estos sistemas, cuando son para el DCC, generalmente buscan resolver o comprender problemáticas complejas o procesos con la finalidad de encontrar una primera alternativa para darles soporte. 

En este contexto, comprender el nivel de madurez de estos sistemas desde una perspectiva de Gobernabilidad se vuelve fundamental. Para esto se usa como base el documento de [Requisitos de Gobernabilidad e Integración de Sistemas del DCC](REQUISITOS_GOBERNABILIDAD.md).

Se han definido los siguientes niveles de madurez: [básico](#nivel-básico), [intermedio](#nivel-intermedio) y [avanzado](#nivel-avanzado). Un sistema puede cumplir indistintamente puntos relacionados con diferentes niveles de medurez no obstante, para alcanzar un nivel de madurez superior, debe cumplir con todos los requisitos obligatorios del nivel específico.

Para la evaluación de madurez o evolución de la misma se entrega un checklist que el/la memorista o tesista puede incluir en su informe a modo de evaluación de su trabajo o comparar el estado de madurez actual de un sistema respecto de su estado actual. Esta evaluación puede ser realizada por parte del **ADS** o como trabajo de la persona responsable.

### Nivel básico:

En un nivel básico, el sistema debe poseer de manera obligatoria:

1. [Descripción del problema](REQUISITOS_GOBERNABILIDAD.md#descripción-del-proceso-que-apoya) o proceso que busca resolver/abordar. _Se recomienda utilizar la herramienta de Tablero Digital (IS2), BPMN o al menos una descripción en texto plano._
2. [Objetivo y alcance del sistema](REQUISITOS_GOBERNABILIDAD.md#objetivo-y-alcance-del-sistema). _Se recomienda utilizar la herramienta de Tablero Digital (IS2) o al menos una descripción en texto plano._
3. [Arquitectura del software](REQUISITOS_GOBERNABILIDAD.md#arquitectura-del-software). _Se recomienda utilizar un framework de especificación de arquitectura como C4model o al menos una descripción clara en texto plano acompañada por diagramas que faciliten su comprensión)._
4. [Stack tecnológico](REQUISITOS_GOBERNABILIDAD.md#stack-tecnológico-utilizado). _Debe incluir lenguajes de programación, plataformas, frameworks, sus versiones y configuraciones necesarias._
5. [Modelo de datos](REQUISITOS_GOBERNABILIDAD.md#modelo-de-datos). _Se recomienda utilizar una herramienta de modelado como MySQL Workbench que permita revisar la coherencia de las relaciones._
6. [Indicaciones para el deployment](REQUISITOS_GOBERNABILIDAD.md#indicaciones-para-el-deployment). _Debe incluir los pasos y requisitos necesarios para que un tercero pueda levantar un ambiente de desarrollo y recomendaciones para su puesta en producción._
7. Existe evidencia de validación de la funcionalidad por parte de un tercero. _Usualmente, la validación del profesor guia es suficiente_.

De manera opcional:

8. [APIs que disponibiliza](REQUISITOS_GOBERNABILIDAD.md#api-para-acceder-a-servicios-o-datos-que-ofrece-el-sistema), en caso de que posea.

### Nivel intermedio:

En un nivel intermedio, el sistema debe poseer de manera obligatoria:

1. El código sigue y se ajusta a algún estándar de codificación (por ejemplo, PEP8).
2. El código utiliza y cumple con las recomendaciones de un linter (por ejemplo, flake8).
3. El README.md incluye: título y una descripción del proyecto.
4. El README.md u otro archivo/documento en el repositorio contiene información detallada sobre cómo desplegar el sistema de forma local.
5. El README.md u otro archivo/documento en el repositorio incluye instrucciones sobre la configuración necesaria para el sistema, incluyendo las variables de entorno necesarias, dependencias y servicios externos necesarios y cómo instalar cualquier dependencia externa.
6. El sistema fue probado en un ambiente de testing con características similares a las de producción.
7. Existe evidencia de que se ha realizado pruebas exhaustivas de todas las funcionalidades del sistema.

De manera opcional:

8. El código se encuentra disponible en un VCS de propiedad del **ADS**.
9. El sistema fue probado en un ambiente de testing provisto por el **ADS**.

### Nivel avanzado:

1. [Arquitectura del ecosistema](REQUISITOS_GOBERNABILIDAD.md#arquitectura-del-ecosistema). _Se recomienda utilizar un framework de especificación de arquitectura como C4model o al menos una descripción clara en texto plano acompañada por diagramas que faciliten su comprensión)._
2. El README.md u otro archivo/documento en el repositorio incluye un resumen conciso que describa qué hace el programa y para quién está destinado.
3. El README.md u otro archivo/documento en el repositorio incluye una sección sobre mejoras futuras tales como nuevas integraciones de API, optimizaciones de rendimiento y/o mejoras de interfaz, destacando también ideas no implementadas en la versión actual pero valiosas para desarrollos futuros.
4. El README.md u otro archivo/documento en el repositorio contiene indicaciones sobre archivos de configuración, variables de entorno y/o servicios externos que deben ser configurados previo a su puesta en test/producción.
5. Es posible levantar un ambiente de desarrollo desde cero en menos de 30 minutos.

De manera opcional:

6. El sistema disponibiliza [APIs](REQUISITOS_GOBERNABILIDAD.md#api-para-acceder-a-servicios-o-datos-que-ofrece-el-sistema) que permiten a otros sistemas integrarse con él.
7. El sistema fue probado en un ambiente de testing provisto por el **ADS**.

### Checklist para memorias y tesis

Este checklist corresponde a la versión 24.05.1

|Ítem|Evaluación|Cumplimiento|
|---|---|---|
|B1|Breve descripción de la evaluación realizada.|[Cumple/No Cumple]|
|B2|||
|B3|||
|B4|||
|B5|||
|B6|||
|B7|||
|B8*|Este ítem es opcional.||
|I1|||
|I2|||
|I3|||
|I4|||
|I5|||
|I6|||
|I7|||
|I8*|Este ítem es opcional.||
|I9*|Este ítem es opcional.||
|A1|||
|A2|||
|A3|||
|A4|||
|A5|||
|A6*|Este ítem es opcional.||
|A7*|Este ítem es opcional.||
