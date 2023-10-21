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

### Minuta de Daily Scrum 5:

**Fecha**: 10 de octubre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Hemos iniciado el desarrollo de los prototipos utilizando la herramienta Framer. 
- Cada miembro del equipo ha comenzado a explorar y crear las primeras propuestas para el MVP.

**¿Qué planificamos hacer?**
- Continuar con el desarrollo de los prototipos, asegurándonos de que cada solución propuesta esté siendo representada adecuadamente en la herramienta.

**¿Qué impedimentos tenemos?**
- Algunos miembros del equipo están experimentando una curva de aprendizaje con Framer.

### Minuta de Daily Scrum 6:

**Fecha**: 12 de octubre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Hemos continuado el desarrollo de los prototipos en Framer, incorporando nuevas soluciones para el MVP.

**¿Qué planificamos hacer?**
- Continuar el desarrollo de las historias de usuario.
- Realizar pruebas de integración dentro de los miembros del equipo.

**¿Qué impedimentos tenemos?**
- Algunos miembros del equipo están experimentando dificultades técnicas que pueden retrasar el desarrollo, estamos buscando soluciones.

### Minuta de Daily Scrum 7:

**Fecha**: 17 de octubre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Hemos avanzado en el desarrollo de los prototipos.

**¿Qué planificamos hacer?**
- Continuar el desarrollo.

**¿Qué impedimentos tenemos?**
- No hay impedimentos en este momento.

### Minuta de Daily Scrum 8:

**Fecha**: 19 de octubre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Finalizamos el desarrollo.
- Preparamos la reunión de revisión del sprint.

**¿Qué planificamos hacer?**
- Planificar y priorizar el próximo sprint en base a los comentarios recibidos.

**¿Qué impedimentos tenemos?**
- Estamos experimentando algunos desafíos en la coordinación de horarios para la próxima iteración.

### Reporte de horas

En este sprint pudimos cumplir mejor la capacidad pactada, superando las del sprint pasado. Sobre todo en la segunda semana del Sprint el equipo dedicó mayor cantidad de tiempo para lograr cumplir con los objetivos.

<img width="1285" alt="Screenshot 2023-10-21 at 20 31 19" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/1953e93b-8d60-4a84-8c17-04d55bb8e943">

<img width="1283" alt="Screenshot 2023-10-21 at 20 31 40" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/3644aec1-1906-44c1-893f-5da4da3d042f">

### Burndown chart

Sobre la mitad del sprint se vió que el equipo debía dedicarle más tiempo para cumplir los Story Points pautados.

<img width="1275" alt="Screenshot 2023-10-21 at 20 33 07" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/69ac7da2-83b5-451d-aebe-2da96ef1c5c9">


## Inspección y adaptación del proceso

### Minuta de la Retrospectiva: Sprint 2
**Fecha**: 20 de octubre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**Dinámica Utilizada**:
Para la retrospectiva de este Sprint, utilizamos la técnica "Estrella de Mar". Cada miembro del equipo compartió aspectos que consideraba que habían funcionado bien durante la iteración y también aquellos que consideraban que podrían mejorar.

<img width="962" alt="Screenshot 2023-10-21 at 20 36 45" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/8018e46b-730c-4194-a281-e0b2452bdc52">

**Principales Resultados**:

**Funcionó Bien**:
- Iniciar el desarrollo de prototipos temprano permitió explorar diversas soluciones.
- Las sesiones de usability testing brindaron valioso feedback de los usuarios.
- La colaboración y el apoyo entre los miembros del equipo se mantuvo efectiva.

**A Mejorar**:
- La curva de aprendizaje con la herramienta Framer generó algunos desafíos.
- La comunicación sobre impedimentos podría ser más proactiva.

**Planificación y Seguimiento de Acciones de Mejora**:
- Curva de Aprendizaje con Framer:
  - Acción: Programar sesiones de entrenamiento adicionales y proporcionar recursos de apoyo.
  - Responsable: Scrum Master y miembros del equipo.
  - Fecha de Implementación: Del 23 al 26 de octubre de 2023.
  - Fecha de Seguimiento: 30 de octubre de 2023.
- Comunicación sobre Impedimentos:
  - Acción: Establecer una práctica de actualización diaria sobre posibles impedimentos en la reunión de Daily Scrum.
  - Responsable: Todos los miembros del equipo.
  - Fecha de Implementación: A partir del 23 de octubre de 2023
  - Fecha de Seguimiento: Continua.

**Conclusiones y Cierre de la Retrospectiva**:

Se identificaron áreas de mejora clave para optimizar el flujo de trabajo y la colaboración en el equipo. Estamos comprometidos a implementar las acciones definidas y esperamos una iteración más productiva en el futuro.

# Construir y validar posibles soluciones del MVP a través de prototipos

## Prototipos con posibles soluciones

En el siguiente enlace se puede visualizar el prototipo interactivo, para su mejor visualización recomendamos abrirlo en un dispositivo móvil, o achicar la pantalla del navegador ya que el prototipo fue pensado para una aplicación móvil:

[https://mvpvideogames.framer.website](https://mvpvideogames.framer.website) 

### Épica 1: Registro y Autenticación de Usuario

**User Story 1**: Como usuario, quiero poder registrarme utilizando mi email, nombre de usuario, contraseña, avatar y seleccionar 3 juegos que me gusten.

**Criterios de Aceptación**: 
- Debe haber campos para email, nombre de usuario, contraseña y selección de juegos.
- Debe haber una validación de email única.
- Debe mostrar un mensaje de éxito después del registro.

<img width="305" alt="Screenshot 2023-10-21 at 16 26 14" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/07fdc61b-2bd7-4629-b703-574ce442020a">
<img width="311" alt="Screenshot 2023-10-21 at 16 26 53" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/a3301c9a-0a03-4e71-a688-c65c255abef0">
<img width="311" alt="Screenshot 2023-10-21 at 16 27 35" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/ca576a48-d3e0-4a3b-afe3-2c6ef4e05725">
<img width="314" alt="Screenshot 2023-10-21 at 16 27 55" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/bfae9e3a-dd53-49ac-b22d-09aeef9a9fcc">
<img width="315" alt="Screenshot 2023-10-21 at 16 28 18" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/b0a577c7-01be-4885-86f1-b89dc943e38c">

**User Story 2**: Como usuario, quiero poder autenticarse con mi nombre de usuario y contraseña.

**Criterios de aceptación**: 
- Debe haber campos para nombre de usuario y contraseña.
- Debe proporcionar un mensaje de error en caso de credenciales incorrectas.

<img width="303" alt="Screenshot 2023-10-21 at 16 48 00" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/3ccb2366-e765-4cdf-bae2-ab7c2d4512c7">
<img width="301" alt="Screenshot 2023-10-21 at 16 48 26" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/9bd295b0-5523-4efe-a61e-93cc35cda683">

### Épica 2: Creación de Partidas y Búsqueda de Partidas

**User Story  3**: Como usuario, quiero poder crear una partida amistosa o competitiva, seleccionando el juego y la cantidad de jugadores.

**Criterios de Aceptación**: 
- Debe haber opciones para elegir el tipo de partida (amistosa o competitiva), seleccionar un juego y definir la cantidad de jugadores.
- La partida debe aparecer en la lista de partidas disponibles.

<img width="314" alt="Screenshot 2023-10-21 at 16 50 59" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/291731a7-1306-4c08-90cf-6929568aa01f">
<img width="305" alt="Screenshot 2023-10-21 at 16 51 26" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/53dccc59-bfe8-4b3d-8a4f-dc40d93f2094">
<img width="291" alt="Screenshot 2023-10-21 at 16 52 00" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/4f2a4143-ca4f-48ba-91fe-18cca18aeb90">
<img width="291" alt="Screenshot 2023-10-21 at 16 52 18" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/a65a69e3-5317-4881-a814-90224c172f89">

**User Story 4**: Como usuario, quiero poder buscar partidas disponibles para unirse, filtrando por juego y tipo de partida.

**Criterios de Aceptación**: 
- Debe haber filtros para elegir el juego y el tipo de partida.
- Debe mostrar una lista de partidas disponibles según los filtros.

<img width="303" alt="Screenshot 2023-10-21 at 16 57 07" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/f7b73c7c-071a-4aa2-bdf3-cca15aa2f695">
<img width="301" alt="Screenshot 2023-10-21 at 16 58 23" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/2b3d8ac5-3080-4f8d-a1dc-28281cf73f14">
<img width="316" alt="Screenshot 2023-10-21 at 16 58 51" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/cc0e724a-ace8-4d6a-850f-6e7aef29dfaa">
<img width="311" alt="Screenshot 2023-10-21 at 16 59 11" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/652414d6-a861-44c6-8b20-0bc0851bf38e">


## Inspección y adaptación del producto

_[Existe evidencia de instancias de inspección y validación del producto con usuarios y la recolección de su feedback con ajustes finales a los prototipos.]_

### Artefactos principales

- Minutas de sprint review.
- Evidencia de los usability testing con usuarios finales.
  - Descripción de las tareas propuestas a los usuarios finales.
  - Cobertura obtenida de validación de los usuarios de la aplicación.
- Feedback recibido de los usuarios finales con la priorización de las propuestas de cambio.
