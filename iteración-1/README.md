# Indice

- [Gestión de la iteración](#gestión-de-la-iteración)
  - [Definición del marco de trabajo](#definición-del-marco-de-trabajo)
  - [Planificación de la iteración](#planificación-de-la-iteración)
  - [Seguimiento de la iteración](#seguimiento-de-la-iteración)
  - [Inspección y adaptación del proceso](#inspección-y-adaptación-del-proceso)
- [Identificar y definir el problema a resolver](#identificar-y-definir-el-problema-a-resolver)
  - [Identificación del problema a resolver](#identificación-del-problema-a-resolver)
  - [Definición del problema/solución](#definición-del-problema/solución)

# Gestión de la iteración

## Definición del marco de trabajo

SCRUM es un marco de trabajo ágil que se utiliza comúnmente en el desarrollo de software y proyectos complejos para mejorar la colaboración, la flexibilidad y la entrega de valor de manera incremental. Se basa en una serie de roles, eventos y artefactos que trabajan juntos para lograr estos objetivos. Partimos de este marco para adaptarlo al actual proyecto, -descubrir, idear y prototipar un MVP de una aplicación de gestión de juegos y torneos móvil-. A continuación mencionamos los roles y acuerdos principales del equipo que adoptamos para el desarrollo del mismo:


### Roles
1. **Scrum Master**: Es el facilitador del equipo, responsable de asegurarse de que se sigan las prácticas de SCRUM y de eliminar cualquier obstáculo que impida el progreso del equipo. Su objetivo es asegurar que el equipo pueda trabajar de manera eficiente y productiva.
Asignado a: Clara Casaretto
2. **Product Owner**: Es el representante del cliente o del negocio. Define y prioriza los elementos del producto en el Product Backlog y trabaja en estrecha colaboración con el equipo de desarrollo para garantizar que se estén construyendo las características más valiosas.
Asignado a: Fernando Spillere
3. **Equipo de Desarrollo**: Son los profesionales que realizan el trabajo real de desarrollo. Son autoorganizados y multifuncionales, y se comprometen a entregar incrementos de producto al final de cada iteración (Sprint).
Asignado a: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

### Acuerdos Principales del Equipo
A continuación presentamos los principales eventos de SCRUM utilizados en el desarrollo del proyecto y su planificación en la iteración:

1. **Sprint Planning**: Al comienzo de cada Sprint, el equipo se reúne para seleccionar los elementos del Product Backlog que se comprometen a completar durante el Sprint. Esto se hace en base a la capacidad del equipo y la priorización del Product Owner.

Cuando: el primer lunes de cada sprint

2. **Daily Scrum**: El equipo realiza reuniones diarias cortas para compartir el progreso, identificar obstáculos y planificar el trabajo para el día siguiente. En nuestro caso, debido al alcance del proyecto y que es poco probable contar con suficientes avances que justifiquen reuniones diarias, decidimos realizar estas reuniones 2 veces por semana.

Cuando: todos los martes y jueves

3. **Sprint Review**: Al final de cada Sprint, el equipo demuestra el trabajo completado al Product Owner y otras partes interesadas y obtiene retroalimentación. 

Cuando: el último viernes de cada sprint

4. **Sprint Retrospective**: Después de la revisión del Sprint, el equipo reflexiona sobre su desempeño y busca formas de mejorar en el siguiente Sprint.

Cuando: el último viernes de cada sprint, posterior a la Sprint Review

### Definiciones del Equipo

**Definition of Done (DoD)**: La Definition of Done es un conjunto de criterios que debe cumplir un elemento de trabajo (como una historia de usuario o una tarea) para considerarse completamente terminado y listo para ser entregado al cliente o usuario final. La DoD garantiza que el trabajo cumpla con los estándares de calidad y funcionalidad del equipo y esté listo para su entrega. A continuación se establece la DoD definida por el equipo:

- El prototipo es interactivo y permite simular todas las funcionalidades planteadas.
- Se realizaron pruebas de aceptación sobre el prototipo y las mismas pasaron.

**Definition of Ready (DoR)**: La Definition of Ready es un conjunto de criterios que deben cumplir los elementos de trabajo antes de que puedan ser seleccionados y planificados para una iteración o Sprint. La DoR asegura que los elementos de trabajo estén lo suficientemente preparados y definidos para que el equipo pueda comenzar a trabajar en ellos sin confusiones ni interrupciones. A continuación se establece la DoR definida por el equipo:

- La descripción es clara y comprensible para todos los interesados.
- Cuenta con criterios de aceptación definidos.
- Cumple con las características INVEST, es decir es independiente, negociable, aporta valor, es estimable, pequeña y testeable.



## Planificación de la iteración

### Objetivos de la Iteración
- Identificar a los interesados y sus necesidades.
- Crear una lista de funcionalidades priorizadas.
- Realizar un estudio de competidores para comprender el mercado.
- Establecer la estructura inicial del producto a través del Story Map.
- Definir el Product Backlog con las historias de usuario y épicas.
- Priorizar los prototipos para el ciclo de descubrimiento.

### Minuta de la Sprint Planning
**Fecha**: 18 de setiembre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**Agenda**:
1. Bienvenida y revisión del objetivo de la iteración.
2. Identificación de principales épicas e historias de usuario a realizar
3. Definición del Product Backlog.
4. Priorización de prototipos a idear y validar.
5. Asignación de tareas y estimaciones.
6. Conclusiones y cierre de la reunión.

**Actividades y Resultados**:
- Se revisó el objetivo de la iteración: "Identificar y definir el problema a resolver".
- Se identificaron los interesados clave y se creó una lista de funcionalidades solicitadas.
- Se definió el Product Backlog con las épicas y las historias de usuario iniciales.
- Se priorizaron los prototipos que se trabajarán en el ciclo de descubrimiento.
- Se asignaron tareas a los miembros del equipo y se realizó la estimación de las mismas.

### Sprint Backlog
****
**Historia de Usuario 1**: Identificación de Interesados Como un miembro del equipo de desarrollo, quiero identificar a los interesados clave para comprender sus necesidades.

**Criterios de Aceptación**:

- **Escenario**: Interesados identificados
  - Dado que los interesados fueron identificados
  - Cuando se cuente con información suficiente sobre sus necesidades
  - Entonces se deberá completar un listado con las funcionalidades identificadas para sus necesidades

**Tareas Asociadas**:
1. Listar posibles interesados clave
2. Investigar necesidades de los interesados
3. Listar funcionalidades requeridas por cada interesado

**Estimación**: 1 Story Points

****
**Historia de Usuario 2**: Estudio de Competidores Como un miembro del equipo de desarrollo, quiero realizar un estudio de competidores para comprender las soluciones similares en el mercado y encontrar posibles ventajas competitivas.

**Criterios de Aceptación**:

- **Escenario**: Interesados identificados
  - Dado que el equipo identificó al menos 5 posibles competidores
  - Cuando se cuente con información suficiente sobre los mismos
  - Entonces se deberá identificar y llegar a un acuerdo del equipo sobre la ventaja competitiva que se buscará desarrollar en el proyecto

**Tareas Asociadas**:
1. Investigar y recopilar una lista de aplicaciones competidoras.
2. Listar las características de cada aplicación.
3. Realizar un análisis comparativo de las aplicaciones.
4. Listar posibles ventajas competitivas que se podrían implementar en base al análisis realizado.
5. Debatir y seleccionar una sobre la cual hacer foco en próximas iteraciones

**Estimación**: 3 Story Points

****
**Historia de Usuario 3**: Definición del Product Backlog Como un miembro del equipo de desarrollo, quiero definir el Product Backlog con épicas e historias de usuario del proyecto para visualizar y organizar el trabajo a realizar.

**Criterios de Aceptación**:
- **Escenario**: Creación del Product Backlog
  - Dado que el Product Owner cuenta con información necesaria sobre los interesados y sus necesidades
  - Cuando se lance el proyecto
  - Entonces deberá crear las épicas e historias de usuario para conformar el Product Backlog siguiendo la Definition of Ready establecida por el equipo

- **Escenario**: Priorización del Product Backlog
  - Dado que el Product Backlog está definido
  - Cuando se complete el Product Backlog
  - Entonces el Product Owner deberá priorizarlo

**Tareas Asociadas**:
1. Generar User Stories iniciales.
2. Organizar visualmente las historias en formato de Story Map.
3. Priorizar las historias.

**Estimación**: 2 Story Points

****
### Técnicas de Priorización y Estimación Utilizadas

El Product Owner, una vez definido el Product Backlog utilizó la técnica de Story Map para facilitar la priorización de las mismas. Luego, junto con todo el equipo durante la reunión de Sprint Planning, se utilizaron Story Points para estimar las historias de usuario.

### Tablero de Azure con Backlog y progreso

Vista de User Stories con sus Tareas:

<img width="1177" alt="Screenshot 2023-10-07 at 18 43 41" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/c27a0b24-5abc-4f7e-b42c-9159222f6018">

Vista de Epicas:

<img width="1176" alt="Screenshot 2023-10-07 at 18 43 03" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/6fa8fe5f-aa63-4fd9-a426-d40dbe30bfad">

## Seguimiento de la iteración

### Minutas de las Daily Scrum
****
**Minuta de Daily Scrum 1**:

**Fecha**: 26 de setiembre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Identificamos a los interesados clave.
- Recopilamos información sobre las necesidades de los interesados.
- Listamos las funcionalidades requeridas por cada interesado.

**¿Qué planificamos hacer?**
- Continuar investigando a los interesados para obtener información adicional.
- Iniciar la investigación de posibles competidores para la próxima historia de usuario.

**¿Qué impedimentos tenemos?**
- Ninguno por el momento.

****

**Minuta de Daily Scrum 2**:

**Fecha**: 28 de setiembre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Completamos la investigación de los interesados y finalizamos la lista de funcionalidades requeridas.
- Comenzamos a investigar a los posibles competidores.

**¿Qué planificamos hacer?**
- Continuar la investigación de los competidores y debatir sobre posibles ventajas competitivas.

**¿Qué impedimentos tenemos?**
- Nos acercamos a fechas de parciales y entregas, por lo que la disponibilidad del equipo se verá reducida, para lo que planeamos dedicarle más tiempo con antelación para evitar cuellos de botella sobre el final de la iteración.

****

**Minuta de Daily Scrum 3**:

**Fecha**: 3 de octubre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Identificamos a cinco competidores clave y recopilamos información sobre sus características
- Definimos las épicas e historias de usuario iniciales para el Product Backlog.

**¿Qué planificamos hacer?**
- Comenzar a analizar comparativamente las características de los competidores.
- Organizar visualmente las historias en formato de Story Map.
- Priorizar el Product Backlog.

**¿Qué impedimentos tenemos?**
- Ninguno por el momento.

****
**Minuta de Daily Scrum 4**:

**Fecha**: 5 de octubre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Seleccionamos una ventaja competitiva en la que nos enfocaremos en próximas iteraciones.
- Priorizamos el Product Backlog.

**¿Qué planificamos hacer?**
- Completar la documentación de la iteración.
- Finalizar entregables.

**¿Qué impedimentos tenemos?**
- Ninguno por el momento.

### Registro de horas

Utilizamos la herramienta Clockify para realizar el registro de horas dedicadas al proyecto, tanto en actividades de gestión, como en ceremonias Agile, como en investigación y trabajo en sí del proyecto.

![horas3](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/fa5ec59e-e38c-4402-80a2-4e7540840471)
![horas2](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/c16291ed-1d84-4e47-a89b-28b6653cfd3f)
![horas 1](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/f5c58f91-7eb5-45c9-a32c-0b47b8e0aa0c)



## Inspección y adaptación del proceso

### Minuta de Retrospectiva de Iteración

**Fecha**: 20 de octubre de 2023

**Dinámica utilizada**: Tablero en MetroRetro

**Participantes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

<img width="1437" alt="Screenshot 2023-10-07 at 17 41 56" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/e387f5c7-47b5-41ac-9902-00ca95657c20">

Durante esta retrospectiva, reflexionamos sobre lo que sucedió durante la iteración y los comentarios recopilados en el tablero de retro. Se destacaron varios aspectos importantes:

**Cosas buenas**:
- El equipo se lleva bien y existe un ambiente positivo y divertido en el grupo. Esto contribuye a un entorno de trabajo agradable.

**Cosas malas**:
- Los parciales consumieron mucho tiempo del equipo, lo que impactó en la coordinación y la disponibilidad para el proyecto.

**Cosas que se podrían haber hecho mejor**:
- La coordinación de los tiempos de todos para las reuniones fue un desafío. Además, llegar a tiempo a las reuniones fue un problema en algunas ocasiones.

**Objetivos que estamos buscando**:
- Identificamos una buena ventaja competitiva para el proyecto, lo cual nos motiva a seguir adelante.
- El equipo tiene como objetivo generar espacios de interacción por fuera de lo estrictamente establecido por el proyecto para fomentar el vínculo del grupo.

### Aprendizajes Principales:
- La gestión del tiempo durante la época de parciales es esencial para mantener la eficiencia del equipo.
- La puntualidad y la coordinación de las reuniones son áreas de mejora identificadas por el equipo.

### Acciones de Mejora:
- Se establecerá un calendario de reuniones con suficiente antelación para permitir una mejor coordinación de los tiempos de todos los miembros.
- Se implementarán recordatorios de reuniones para fomentar la puntualidad.
- Se aceptarán updates asincrónicos por mensaje al grupo de whatsapp para aquellos integrantes que por razón justificada no puedan atender a la Daily en tiempo, de manera de no demorar el comienzo de la misma para quienes sí asisten.

# Identificar y definir el problema a resolver

## Identificación del problema a resolver

### Identificación de Interesados

- **Usuarios Finales** (Edades 12-40): Son los usuarios principales de la aplicación. Están interesados en una experiencia de juego social, creación de partidas y torneos, y seguimiento de su progreso y ranking en juegos.
- **Administradores de Torneos**: Personas encargadas de organizar y gestionar torneos en la plataforma. Están interesados en funciones de creación de torneos, invitaciones a jugadores y seguimiento de resultados.
- **Desarrolladores de la Aplicación**: Aquellos que diseñan y desarrollan la aplicación. Están interesados en la implementación técnica de las características y en mantener la escalabilidad.
- **Equipo de Diseño de Interfaz de Usuario**: Responsables de la apariencia y experiencia del usuario en la aplicación. Están interesados en garantizar una interfaz amigable y coherente con las guías de diseño de iOS y Android.
- **Inversionistas o Patrocinadores**: Personas o entidades que financian el proyecto y están interesadas en el éxito y la rentabilidad de la aplicación.

### Lista de Funcionalidades por Interesado

**Usuarios Finales**:
1. Registro de usuario con email, nombre de usuario, contraseña, avatar y juegos favoritos.
2. Inicio de sesión con opciones de nombre de usuario/contraseña, Google y Discord.
3. Creación y edición de perfil de usuario.
4. Creación de partidas amistosas o competitivas.
5. Creación y participación en torneos.
6. Búsqueda de partidas disponibles.
7. Visualización de perfil de usuario y estadísticas.
8. Consulta de ranking por juego.
9. Recepción de notificaciones relevantes.

**Administradores de Torneos**:
1. Creación de torneos y envío de invitaciones.
2. Gestión de participantes y resultados de torneos.
3. Visualización de resultados y podio.

**Desarrolladores de la Aplicación**:
1. Implementación técnica de todas las características.
2. Escalabilidad y rendimiento de la aplicación.

**Equipo de Diseño de Interfaz de Usuario**:
1. Diseño de una interfaz de usuario atractiva y fácil de usar.
2. Adherencia a las guías de diseño de iOS y Android.

**Inversionistas o Patrocinadores**:
1. Interés en la viabilidad y rentabilidad del proyecto.

### Estudio de Competidores

El proyecto propuesto busca desarrollar un MVP de una aplicación de gestión de juegos y torneos móvil, dirigida principalmente a personas de entre 12 y 
40 años que juegan semanalmente más de tres horas a juegos en línea como usuarios finales. Para realizar un análisis de posibles competidores, debemos considerar las características y funciones esenciales que esta aplicación debe ofrecer. Es importante analizar la competencia existente en el mercado de aplicaciones de gestión de juegos y torneos móviles. 

A continuación realizamos un análisis de algunos posibles competidores con su UI y algunas opiniones de los usuarios que utilizan cada plataforma. 

Algunos competidores potenciales podrían incluir:

#### Discord:
Aunque Discord es reconocido principalmente como una plataforma de comunicación, ha integrado funciones de organización de comunidades de juego y eventos. A pesar de ello, carece de características específicas para la gestión de partidas, torneos y seguimiento de estadísticas de juego, las cuales son fundamentales en la aplicación que proponemos.

Es importante mencionar que, para los jugadores, Discord se ha convertido en una herramienta esencial para la coordinación y la comunicación durante las sesiones de juego en línea. Por lo tanto, la aplicación que proponemos debe ofrecer ventajas distintivas y características adicionales para atraer a los usuarios de Discord y otras plataformas de comunicación. Debe proporcionar una experiencia de usuario atractiva y adaptada a la población objetivo. Si cumple con todas las funcionalidades propuestas, podría competir eficazmente con Discord en su nicho de mercado.

<img width="977" alt="Screenshot 2023-10-07 at 21 05 15" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/209a9ce5-2e27-4898-afc9-a0c494305772">

Además, investigamos diversas reseñas y opiniones de usuarios que utilizan Discord. Esto nos ha permitido identificar aspectos a mejorar, así como características apreciadas por la comunidad, que tendremos en cuenta en el desarrollo de nuestra aplicación.

<img width="723" alt="Screenshot 2023-10-07 at 21 06 21" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/bf9224b6-e22b-439e-bfb2-7cf1c2453207">

<img width="649" alt="Screenshot 2023-10-07 at 21 06 31" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/aeb24847-1c17-466f-a95a-94ff30df592b">


#### Battlefy: 
Plataforma popular dedicada a la organización de torneos y competencias de juegos en línea. Aunque no se perfila como un competidor directo de nuestra aplicación propuesta, su relevancia radica en su papel como competidor indirecto en el ámbito de la organización de torneos.

Battlefy se ha ganado una considerable base de usuarios gracias a su enfoque en la gestión y organización de torneos virtuales. Esto nos indica que existe una demanda y una comunidad activa en torno a la participación en competencias de juegos en línea. Es crucial, por tanto, que nuestra aplicación se diferencie ofreciendo una experiencia aún más completa y adaptada que satisfaga las necesidades tanto de organizadores de torneos como de equipos de eSports, así como de jugadores individuales, especialmente en un contexto local.

Para superar a Battlefy, nuestra aplicación debe destacarse en áreas como la facilidad de uso, la personalización de torneos, la gestión de equipos y jugadores, así como la integración de funciones sociales para fomentar la participación y la interacción entre los usuarios. Además, la posibilidad de ofrecer herramientas analíticas y de seguimiento de rendimiento a nivel individual y de equipo podría ser un factor diferenciador clave.

Es fundamental que nuestra aplicación proporcione una experiencia intuitiva y eficiente, permitiendo a los usuarios crear y administrar torneos de manera fluida y rápida. Asimismo, debe brindar una plataforma que facilite la comunicación entre organizadores, equipos y jugadores, promoviendo así una comunidad sólida y colaborativa.

 <img width="738" alt="Screenshot 2023-10-07 at 21 06 55" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/15c7bd5b-be89-49b2-98fc-0ac72a3f564f">


### Toornament: 

Se presenta como una plataforma especializada en la creación y gestión de torneos de deportes electrónicos. Aunque no se configura como un competidor directo de nuestra aplicación propuesta, su relevancia radica en su papel como competidor indirecto en el ámbito de la organización de torneos. Al analizar Toornament, reconocemos la importancia de abordar la organización de torneos de manera especializada y enfocada en los deportes electrónicos.

Si bien Toornament se concentra en torneos de eSports, nuestra aplicación propuesta tiene un enfoque más amplio al abordar tanto la organización de torneos como la gestión de partidas casuales y actividades sociales en línea. Esta estrategia nos permite ofrecer una solución más integral para la comunidad de jugadores, lo que podría ser una ventaja competitiva significativa.

Además, la capacidad de adaptarnos a las necesidades específicas de la población uruguaya podría ser otro factor diferenciador clave. Al comprender y responder a las particularidades y preferencias de los jugadores en Uruguay, nuestra aplicación se posiciona para ofrecer una experiencia más cercana y relevante para este mercado.

Para competir con Toornament, es esencial que nuestra aplicación se destaque en áreas como la personalización de torneos, la gestión de equipos y jugadores, así como la facilitación de la participación en actividades sociales en línea. Asimismo, la integración de funciones sociales y herramientas analíticas podría ser un factor determinante para atraer y retener a los usuarios.

<img width="1047" alt="Screenshot 2023-10-07 at 21 07 28" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/a822232b-404f-43c5-a074-a1fe64d1dd9e">


## PlayVS: 

Se destaca por su enfoque en la organización de torneos de deportes electrónicos dirigidos a escuelas y colegios. Aunque su ámbito de actuación es específico, es importante considerar a PlayVS como un competidor indirecto en el ámbito de los torneos de eSports a nivel educativo.

Para competir con PlayVS, nuestra aplicación propuesta debería ampliar su alcance para incluir herramientas y funcionalidades que abarquen tanto la organización de torneos escolares como la gestión de partidas casuales y actividades sociales en línea para un público más amplio. Esta expansión permitiría a nuestra aplicación ofrecer una solución más completa y versátil que atienda tanto las necesidades de las instituciones educativas como las de los jugadores individuales.

Además, adaptarse a las particularidades del sistema educativo uruguayo y ofrecer funcionalidades que fomenten la participación y el aprendizaje a través de los juegos electrónicos podría ser una ventaja competitiva clave. Esto podría incluir características como herramientas de seguimiento del progreso académico, integración con planes de estudio y recursos educativos, y la posibilidad de fomentar habilidades transversales a través de la participación en torneos y actividades en línea.

<img width="747" alt="Screenshot 2023-10-07 at 21 08 06" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/30a7a9f3-dd28-4364-bcc8-053897185921">


### Steam: 

Reconocida como una de las principales plataformas de juegos a nivel mundial, no solo ofrece una amplia gama de juegos, sino que también incluye características sociales y herramientas de organización de eventos.

Si bien Steam no se presenta como un competidor directo en el ámbito de la organización de torneos, su presencia en la comunidad de jugadores es innegable. Para diferenciarnos de Steam, nuestra aplicación propuesta debe centrarse en proporcionar una experiencia más especializada y completa en términos de organización de torneos, gestión de partidas y actividades sociales en línea.

Además, es esencial destacar que la aplicación propuesta puede complementar y enriquecer la experiencia de los usuarios de Steam al ofrecer herramientas y funcionalidades específicas para la organización y gestión de torneos, así como la interacción social en línea. Esta sinergia entre ambas plataformas puede brindar a los usuarios una experiencia más enriquecedora y personalizada.

Asimismo, al considerar el mercado uruguayo, nuestra aplicación debe adaptarse a las preferencias y necesidades de los jugadores locales, ofreciendo características que resuenen con la comunidad de jugadores en este contexto específico.

<img width="827" alt="Screenshot 2023-10-07 at 21 08 42" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/d7b96bfb-c871-4584-8cb0-178f58ef0de5">


## Definición del problema/solución

**Priorización de Prototipos Principales**:
1. Prototipo de Registro y Autenticación de Usuario
2. Prototipo de Creación de Partidas y Búsqueda de Partidas
3. Prototipo de Gestión de Torneos
4. Prototipo de Perfil de Usuario y Estadísticas
5. Prototipo de Notificaciones y Comunicación

### Product Backlog:
****

**Épica 1**: Registro y Autenticación de Usuario

**User Story 1**: Como usuario, quiero poder registrarme utilizando mi email, nombre de usuario, contraseña, avatar y seleccionar 3 juegos que me gusten.
  **Criterios de Aceptación**: 
    - Debe haber campos para email, nombre de usuario, contraseña y selección de juegos. 
    - Debe haber una validación de email única. 
    - Debe mostrar un mensaje de éxito después del registro.

**User Story 2**: Como usuario, quiero poder autenticarme con mi nombre de usuario y contraseña.
  **Criterios de aceptación**: 
    - Debe haber campos para nombre de usuario y contraseña. 
    - Debe proporcionar un mensaje de error en caso de credenciales incorrectas.

****
**Épica 2**: Creación de Partidas y Búsqueda de Partidas

**User Story  3**: Como usuario, quiero poder crear una partida amistosa o competitiva, seleccionando el juego y la cantidad de jugadores.
  **Criterios de Aceptación**: 
  - Debe haber opciones para elegir el tipo de partida (amistosa o competitiva), seleccionar un juego y definir la cantidad de jugadores.
  - La partida debe aparecer en la lista de partidas disponibles.

**User Story 4**: Como usuario, quiero poder buscar partidas disponibles para unirse, filtrando por juego y tipo de partida.
  **Criterios de Aceptación**: 
  - Debe haber filtros para elegir el juego y el tipo de partida.
  - Debe mostrar una lista de partidas disponibles según los filtros.

****
**Épica 3**: Gestión de Torneos

**User Story 5**: Como usuario, quiero poder crear un torneo, seleccionando el juego y enviando invitaciones a otros usuarios.
  **Criterios de Aceptación**: 
  - Debe haber una opción para crear un torneo, seleccionar el juego y enviar invitaciones.
  - Debe mostrar el podio con los ganadores al final del torneo.

**User Story  6**: Como usuario, quiero poder participar en torneos a los que he sido invitado.
  **Criterios de Aceptación**: 
  - Debe mostrar notificaciones de invitación a torneos.
  - Debe permitir la aceptación o rechazo de invitaciones.

****
**Épica 4**: Perfil de Usuario y Estadísticas

**User Story 7**: Como usuario, quiero poder ver mi perfil de usuario con información como nombre de usuario, avatar, juegos favoritos y estadísticas.
  **Criterios de Aceptación**: 
  - Debe mostrar la información del perfil de usuario, incluyendo nombre de usuario, avatar, juegos favoritos y estadísticas.

**User Story 8**: Como usuario, quiero ver el ranking por juego con información sobre mi posición y puntajes.
  **Criterios de Aceptación**: 
  - Debe mostrar el ranking por juego con información de posición y puntajes.

****
**Épica 5**: Notificaciones y Comunicación

**User Story 9**: Como usuario, quiero recibir notificaciones sobre el estado de las partidas y torneos.
  **Criterios de Aceptación**: 
  - Debe mostrar notificaciones cuando las partidas estén listas o cuando se reciban invitaciones a torneos.

**User Story 10**: Como usuario, quiero recibir notificaciones cuando suba en el ranking de un juego.
  **Criterios de Aceptación**: 
  - Debe mostrar notificaciones cuando haya mejoras en el ranking de juegos.

****
**Épica 6**: Sistema de Puntos y Mercado de Objetos

**User Story 11**: Como usuario, quiero acumular puntos al ganar torneos, para poder canjearlos por objetos en el mercado.
  **Criterios de Aceptación**: 
  - Deben asignarse puntos al usuario al ganar un torneo.
  - Debe haber una sección de mercado donde los usuarios puedan canjear puntos por objetos.

**User Story 12**: Como usuario, quiero poder ver la lista de objetos disponibles en el mercado y su costo en puntos.
  **Criterios de Aceptación**: 
  - Debe mostrar una lista de objetos disponibles en el mercado con sus respectivos costos en puntos.

### Story Map

A continuación se muestra el story map generado para la priorización de las historias de usuarios:

<img width="613" alt="Screenshot 2023-10-07 at 21 00 27" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/3b973f43-ed65-405c-994f-59ceb7780f4f">
