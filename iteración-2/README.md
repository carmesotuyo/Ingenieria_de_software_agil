# Indice

- [Gestión de la iteración](#gestión-de-la-iteración)
  - [Definición del marco de trabajo](#definición-del-marco-de-trabajo)
  - [Planificación de la iteración](#planificación-de-la-iteración)
  - [Seguimiento de la iteración](#seguimiento-de-la-iteración)
  - [Inspección y adaptación del proceso](#inspección-y-adaptación-del-proceso)
- [Construir y validar posibles soluciones del MVP a través de prototipos](#construir-y-validar-posibles-soluciones-del-mvp-a-través-de-prototipos)
  - [Prototipos con posibles soluciones](#prototipos-con-posibles-soluciones)
  - [Inspección y adaptación del producto](#inspección-y-adaptación-del-producto)

# Gestión de la iteración

## Definición del marco de trabajo

Al igual que en la iteración anterior, mantenemos del marco de trabajo SCRUM los roles principales y ceremonias para llevar adelante las tareas de prototipado y evaluación del proceso de trabajo.

Mantenemos los mismos roles:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

Mantenemos la agenda de actividades, con la única modificación de que pasamos a realizar la Daily Scrum flexible, es decir quienes no se pueden unir en el tiempo definido pueden enviar su update por escrito al grupo de whatsapp del equipo. De esta manera no generamos pérdida de tiempo durante las meetings, y a su vez mantenemos la planificación actualizada.

- Sprint Planning: primer lunes de cada sprint
- Daily Scrum: martes y jueves
- Sprint Review: último viernes del sprint
- Sprint Retrospective: último viernes del sprint, posterior a la Review

## Definiciones del equipo

Mejoramos las definiciones previamente establecidas.

### Definition of Done (DoD): 

- El prototipo es interactivo y permite simular todas las funcionalidades planteadas.
- Se realizaron pruebas de aceptación sobre el prototipo y las mismas pasaron.
- La documentación del trabajo realizado en cada iteración se realiza en una rama separada de main
- La rama de trabajo es revisada por otro miembro del equipo, diferente a quien la trabajó
- Una vez aprobada y finalizado el trabajo de la iteración, el mismo es mergeado a Main

### Definition of Ready (DoR):

- La descripción es clara y comprensible para todos los interesados.
- Cuenta con criterios de aceptación definidos.
- Cumple con las características INVEST, es decir es independiente, negociable, aporta valor, es estimable, pequeña y testeable.

## Planificación de la iteración

### Minuta de la Sprint Planning: Iteración 2

**Fecha**: 9 octubre 

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**Agenda**:

1. Bienvenida y Revisión del Objetivo de la Iteración: Iniciamos la reunión revisando el objetivo de la segunda iteración, que es "Construir y validar posibles soluciones del MVP a través de prototipos."
2. Identificación de Principales Épicas e Historias de Usuario a Realizar: Identificamos las épicas y las historias de usuario clave que serán abordadas durante las iteraciones de prototipado y su prioridad.
3. Definición del Product Backlog: Creamos y actualizamos el Product Backlog con las épicas e historias de usuario identificadas.
4. Priorización de Prototipos a Idear y Validar: Priorizamos los prototipos que se deben desarrollar y validar en el ciclo de descubrimiento. Estos se realizan mediante Figma y se animan mediante Framer.
5. Asignación de Tareas y Estimaciones: Asignamos tareas específicas a los miembros del equipo y estimamos el esfuerzo requerido para completarlas.
6. Conclusiones y Cierre de la Reunión: Resumimos los acuerdos alcanzados, los próximos pasos y cerramos la reunión de Sprint Planning.

**Actividades y Resultados**:
- Se definió claramente el objetivo de la iteración.
- Se identificaron las épicas e historias de usuario relevantes para esta fase.
- Se actualizó y priorizó el Product Backlog.
- Se acordó trabajar en la creación y validación de prototipos usando Figma y Framer
- Se asignaron tareas a los miembros del equipo y se realizaron estimaciones.

### Objetivos de la iteración 

- **Construir prototipos**:
Durante esta iteración, el equipo se enfocará en desarrollar prototipos que representan posibles soluciones para el Producto Mínimo Viable (MVP). Se utilizará la herramienta Figma para el diseño de los prototipos, ya que algunos miembros del equipo ya han trabajado con ella, y se importarán los diseños a framer para crear las animaciones de los prototipos.
- **Validar prototipos**: Al final de la iteración se presentarán los prototipos realizados a usuarios finales y se analizará su feedback para incorporar mejoras en las próximas iteraciones.

### Sprint backlog con historias de usuarios y tareas asociadas

**Épica 1: Registro y Autenticación de Usuario**

- **Registro**: Como usuario, quiero poder registrarme utilizando mi email, nombre de usuario, contraseña, avatar y seleccionar 3 juegos que me gusten.
  - **Criterios de Aceptación**:
    - Debe haber campos para email, nombre de usuario, contraseña y selección de juegos.     
    - Debe mostrar un mensaje de éxito después del registro.
  - **Tareas**:
    1. Crear campos de texto (Email o nombre de usuario y contraseña)
    2. Crear ventana de selección de avatar.
    3. Selección de videojuegos favoritos.
    4. Agregar navegación entre layers.

- **Autenticación**: Como usuario, quiero poder autenticarse con mi nombre de usuario y contraseña.
  - **Criterios de aceptación**: 
    - Debe haber campos para nombre de usuario y contraseña. 
    - Debe proporcionar un mensaje de error en caso de credenciales incorrectas.
  - **Tareas**:
    1. Hacer pantalla de login.
    2. Hacer pantalla de error para campos incorrectos.
    3. Hacer campos tipeables.

**Épica 2: Creación de Partidas y Búsqueda de Partidas**
- **Crear partida**: Como usuario, quiero poder crear una partida amistosa o competitiva, seleccionando el juego y la cantidad de jugadores.
  - **Criterios de Aceptación**: 
    - Debe haber opciones para elegir el tipo de partida (amistosa o competitiva), seleccionar un juego y definir la cantidad de jugadores. 
    - La partida debe aparecer en la lista de partidas disponibles.
  - **Tareas**:
    1. Hacer form para los datos de la partida
    2. Seleccionar número de jugadores.
    3. Seleccionar juego.

- **Buscar partida**: Como usuario, quiero poder buscar partidas disponibles para unirse, filtrando por juego y tipo de partida.
  - **Criterios de Aceptación**: 
    - Debe haber filtros para elegir el juego y el tipo de partida. 
    - Debe mostrar una lista de partidas disponibles según los filtros.
  - **Tareas**:
    1. Barra de búsqueda tipeable
    2. Agregar filtro por tipo de partida
    3. Mostrar lista de partidas

Muestra de Épica en azure con sus User Stories y tareas asociadas:

<img width="803" alt="Screenshot 2023-10-21 at 19 45 53" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/62d1c7cc-9917-49ba-b9d2-384a54fb5627">

### Planificación de acuerdo a la capacidad del equipo.

Algunos miembros del equipo tenían experiencia previa utilizando Figma (herramienta de prototipado) por lo que en primer lugar se hizo un boceto utilizando esta herramienta por aquellos miembros con experiencia del equipo.

Luego el equipo llegó a la conclusión que esta herramienta no era lo suficientemente completa como para hacer el 100% del prototipo allí por lo que otra parte del equipo se encargó de migrar el boceto inicial a la herramienta de prototipado sugerida por la cátedra, Framer, la cual nos iba a permitir, a diferencia de Figma, tener campos de textos editables y una mejor animación e interacción entre los elementos del diseño.

Luego de tener un prototipo más estable en Framer, la otra parte del equipo se encargó de animar estos prototipos, darle vida a los botones e interacciones.

En cuanto a la documentación, se optó por asignar esta responsabilidad a quienes menos conocimiento de las herramientas de prototipado tenían, de manera de acelerar el proceso. De todas maneras todos los miembros contribuyeron a la documentación en distinta medida.

### Técnicas de priorización y estimación utilizada

En base a todas las user stories presentadas, el equipo realizó una votación para priorizarlas. Se presentó el Story Map generado en la iteración anterior y se discutió en grupo votando cuáles historias debían ser generadas en este sprint.

El equipo decidió priorizar por un lado aquellas funcionalidades que nos parecían más importantes y que añadían mayor valor al proyecto, como son las de Creación y Búsqueda de partidas para iniciar a jugar, y por otro aquellas que iban a ser requeridas en futuras funcionalidades, como por ejemplo todo lo relacionado con la autenticación del usuario (registro, inicio de sesión e inicio de sesión con Google). Estas funcionalidades tuvieron una alta prioridad ya que eran necesarias para cualquier otra interacción que el usuario deseara realizar.

Para las estimaciones se realizó una dinámica similar de votación, partiendo de una User Story se debatió en el equipo y se le asignó un valor relativo de Story Points, el cual sirvió de medición para votar el valor del historias siguientes.

### Métricas del equipo

El equipo obtuvo una velocity de 10 story points por Sprint en lo que va del proyecto.

## Seguimiento de la iteración

_[Existe evidencia sobre el registro de actividades y horas de cada integrante del equipo con el seguimiento general de cada iteración del proyecto sobre lo planificado inicialmente.]_

### Artefactos principales

- Minuta de daily scrum describiendo la coordinación del trabajo de cada integrante del equipo.
  - ¿Que logramos hacer?
  - ¿Qué planificamos hacer?
  - ¿Qué impedimentos tenemos?
- Registro y reporte de horas de cada integrante del equipo con sus actividades principales.
- Seguimiento visual de la iteración con burndown y/o burnup charts.

## Inspección y adaptación del proceso

_[Existe evidencia sobre la inspección del proceso con aprendizajes principales y acciones de mejora implementadas durante el desarrollo del proyecto.]_

### Artefactos principales

- Minuta de la retrospectiva con la dinámica utilizada y sus principales resultados.
- Planificación y seguimiento de las acciones de mejora.

# Construir y validar posibles soluciones del MVP a través de prototipos

## Prototipos con posibles soluciones

_[Existen diferentes propuestas de solución para entregar valor y resolver el problema identificado implementado a través de prototipos. Los prototipos deberán ser exportados en algún formato de imagen (como png o jpg) a efectos de poder ser visualizados fácilmente dentro del propio repo de github.]_

### Artefactos principales

- Prototipos interactivos para ser navegados.
- Prototipos asociados como bocetos a las historias de usuario.

## Inspección y adaptación del producto

_[Existe evidencia de instancias de inspección y validación del producto con usuarios y la recolección de su feedback con ajustes finales a los prototipos.]_

### Artefactos principales

- Minutas de sprint review.
- Evidencia de los usability testing con usuarios finales.
  - Descripción de las tareas propuestas a los usuarios finales.
  - Cobertura obtenida de validación de los usuarios de la aplicación.
- Feedback recibido de los usuarios finales con la priorización de las propuestas de cambio.
