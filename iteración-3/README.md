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

### Minuta de la Sprint Planning: Iteración 3

**Fecha**: 9 octubre 

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**Agenda**:

1. Bienvenida y Objetivo de la Reunión: La reunión se inicia con una breve bienvenida y una revisión del objetivo de la reunión, que es discutir el feedback de los clientes sobre la aplicación del juego y planificar las mejoras.
2. Feedback de Clientes: Se compartieron y discutieron los comentarios y sugerencias recibidos de los clientes con respecto a la aplicación del juego. Se destacaron los puntos clave y las áreas de mejora identificadas.
3. Creación de User Stories: Se crearon historias de usuario basadas en el feedback de los clientes. Estas historias representan las funcionalidades y mejoras específicas que se deben abordar en la iteración.
4. Priorización de User Stories: Se priorizaron las historias de usuario de acuerdo con su importancia y valor para los clientes. Se acordó cuáles se abordarán en esta iteración.
5. Asignación de Tareas: Se asignaron las historias de usuario a los miembros del equipo de desarrollo. Cada miembro se hizo responsable de la implementación de ciertas funcionalidades.
6. Conclusiones y Cierre de la Reunión: Se resumieron los acuerdos alcanzados, se establecieron los próximos pasos y se dio por concluida la reunión.


**Actividades y Resultados**:
- Se recopiló y analizó el feedback de los clientes.
- Se crearon user stories basadas en el feedback.
- Las historias de usuario se priorizaron de acuerdo con su importancia.
- Se asignaron tareas a los miembros del equipo.
- Se planificó la creación de prototipos para las mejoras identificadas.


### Objetivos de la iteración 

1. Prototipos y Diversidad de Soluciones: Durante la Iteración 3, se generarán prototipos que propondrán una variedad de soluciones para mejorar la aplicación. Se utilizarán figma y frame para explorar distintos enfoques.
2. Priorización Basada en el Feedback: Se dará prioridad a las soluciones según el feedback de los usuarios recopilado. Esto garantiza que las áreas críticas y de alto valor se aborden de manera prioritaria.

### Sprint backlog con historias de usuarios y tareas asociadas

**Épica 3: Gestión de Torneos**

- **Crear Torneo**: Como usuario, quiero poder crear un torneo, seleccionando el juego y enviando invitaciones a otros usuarios.
  - **Criterios de Aceptación**:
    - Debe haber una opción para crear un torneo, seleccionar el juego y enviar invitaciones.
    - Debe mostrar el podio con los ganadores al final del torneo.
  - **Tareas**:
    1. Diseño ventana de creación del torneo
    2. Animación


- **Participar en Torneos**: Como usuario, quiero poder participar en torneos a los que he sido invitado.
  - **Criterios de aceptación**: 
    - Debe mostrar notificaciones de invitación a torneos.
    - Debe permitir la aceptación o rechazo de invitaciones.
  - **Tareas**:
    1. Incorporar ícono de notificaciones al Home
    2. Diseñar ventana de notificaciones
    3. Animación


**Épica 4: Perfil de Usuario y Estadísticas**
- **Perfil de Usuario**: Como usuario, quiero poder ver mi perfil de usuario con información como nombre de usuario y avatar.
  - **Criterios de Aceptación**: 
    - Debe mostrar la información del perfil de usuario, incluyendo nombre de usuario, avatar y una opción para cerrar sesión.
  - **Tareas**:
    1. Diseño
    2. Animación


- **Ranking**: Como usuario, quiero ver el ranking por juego con información sobre mi posición y puntajes.
  - **Criterios de Aceptación**: 
    - Debe mostrar el ranking por juego con información de posición y puntajes.
  - **Tareas**:
    1. Diseño
    2. Animación

**Épica 5: Notificaciones y Comunicación**
- **Notificaciones**: Como usuario, quiero recibir notificaciones sobre el estado de las partidas y torneos.
  - **Criterios de Aceptación**: 
    - Debe mostrar notificaciones cuando las partidas estén listas o cuando se reciban invitaciones a torneos.
  - **Tareas**:
    1. Diseño
    2. Animación


- **Notificación en cambio en ranking**: Como usuario, quiero recibir notificaciones cuando suba en el ranking de un juego.
  - **Criterios de Aceptación**: 
    - Debe mostrar notificaciones cuando haya mejoras en el ranking de juegos.
  - **Tareas**:
    1. Diseño
    2. Animación

**Épica 6: Sistema de puntos y mercado de objetos**
- **Acumular puntos**: Como usuario, quiero acumular puntos al ganar torneos, para poder canjearlos por objetos en el mercado.
  - **Criterios de Aceptación**: 
    - Deben asignarse puntos al usuario al ganar un torneo.
    - Debe haber una sección de mercado donde los usuarios puedan canjear puntos por objetos.
  - **Tareas**:
    1. Diseño
    2. Animación


- **Visualizar Market**: Como usuario, quiero poder ver la lista de objetos disponibles en el mercado y su costo en puntos.
  - **Criterios de Aceptación**: 
    - Debe mostrar una lista de objetos disponibles en el mercado con sus respectivos costos en puntos.
  - **Tareas**:
    1. Diseño
    2. Animación

**Épica 7: Mejoras**
- **Posibilidad de jugar**: Como usuario, quiero tener la posibilidad de jugar para disfrutar de la experiencia de la aplicación.
  - **Criterios de Aceptación**: 
    - La aplicación debe permitir a los usuarios iniciar una partida.
  - **Tareas**:
    1. Desarrollar la funcionalidad de inicio de partida.
    2. Diseñar una interfaz clara y atractiva para el inicio del juego.


- **Mostrar el nombre de cada juego en la lista**: Como usuario, quiero ver el nombre de cada juego en la lista del mercado para poder identificarlos fácilmente.
  - **Criterios de Aceptación**: 
    - La lista del mercado debe mostrar claramente el nombre de cada juego disponible.
    - Los nombres de los juegos deben ser legibles y estar presentados de forma organizada.
  - **Tareas**:
    1. Modificar la interfaz de la lista del mercado para incluir el nombre de cada juego.
    2. Asegurarse de que los nombres de los juegos se muestren correctamente y sean legibles.

- **Seleccionar un solo juego a la vez**: Como usuario, quiero poder seleccionar un solo juego a la vez en la lista del mercado para obtener más información sobre él
  - **Criterios de Aceptación**: 
    - Solo se puede seleccionar un juego a la vez en la lista del mercado.
    - Al seleccionar un juego, se debe mostrar información detallada sobre ese juego.
  - **Tareas**:
    1. Implementar la funcionalidad de selección de juegos en la lista del mercado.
    2. Diseñar una interfaz que muestre la información detallada del juego seleccionado.

- **Estandarizar botones y mensajes**: Como usuario, quiero que los botones y mensajes en la aplicación sigan un estándar de diseño y comunicación para una experiencia coherente.
  - **Criterios de Aceptación**: 
    - Todos los botones en la aplicación deben tener un diseño y tamaño consistentes.
    - Los mensajes y notificaciones deben seguir una tonalidad y estilo uniformes.
  - **Tareas**:
    1. Revisar y actualizar el diseño de los botones en toda la aplicación para que sigan un estándar.
    2. Asegurarse de que los mensajes y notificaciones tengan una comunicación coherente y clara.

Muestra de Épica en azure con sus User Stories y tareas asociadas:
![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/3e7e744d-f3e0-49ee-b47d-0d711bcdae77)

### Planificación de acuerdo a la capacidad del equipo.
Para este sprint, el equipo evaluó su capacidad y se comprometió a abordar un total de 20 story points. Dada la experiencia previa de algunos miembros con Framer, se optó por iniciar el proceso de prototipado en esta herramienta. Esta decisión permitiría contar con campos de texto editables y botones animables, lo cual era fundamental para la funcionalidad del prototipo.
Una vez que se logró un prototipo más estable en Framer, se asignó a otra parte del equipo la tarea de animar los prototipos, brindando interactividad a los botones y elementos de la interfaz.
Finalmente, los prototipos resultantes se sometieron a pruebas para recopilar feedback valioso que guiará las futuras iteraciones del proyecto.

### Técnicas de priorización y estimación utilizada
En base a todas las user stories presentadas, el equipo decidió priorizar algunas frente a otras. Está priorización se basó en aquellas funcionalidades que nos parecían más importantes y en aquellas que iban a ser requeridas en futuras funcionalidades.

### Métricas del equipo
El equipo obtuvo una velocity de 13 story points. (10 SP del primer sprint, 10 SP del anterior y 20 de este)

## Seguimiento de la iteración

### Minuta de Daily Scrum 9:

**Fecha**: 24 de octubre de 2023 

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Arrancamos más motivados y más rápido que la vez anterior, porque ya conocíamos mejor la herramienta.
- Iniciamos el desarrollo de los prototipos utilizando Framer.
- Cada miembro del equipo ha comenzado a explorar y crear las primeras propuestas para el MVP.


**¿Qué planificamos hacer?**
- Continuar con el desarrollo de los prototipos, asegurándonos de que cada solución propuesta esté siendo representada adecuadamente en la herramienta.

**¿Qué impedimentos tenemos?**
- No se presentaron impedimentos

### Minuta de Daily Scrum 10:

**Fecha**: 26 de octubre de 2023 

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Continuamos con el desarrollo de los prototipos utilizando Framer.
- Se resolvieron algunos problemas identificados durante el proceso.

**¿Qué planificamos hacer?**
- Revisar las tareas pendientes y ajustar las prioridades según el avance.

**¿Qué impedimentos tenemos?**
- No se progresó mucho porque no hubo tiempo de parte del equipo por otros proyectos

### Minuta de Daily Scrum 11:

**Fecha**: 31 de octubre de 2023 

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Avanzamos en la creación de prototipos y soluciones utilizando figma y framer.
- Se realizó una revisión detallada de los prototipos generados y se hicieron ajustes según el feedback del equipo.

**¿Qué planificamos hacer?**
- Discutir posibles mejoras y adiciones a las funcionalidades propuestas.

**¿Qué impedimentos tenemos?**
- La necesidad de ajustes en los prototipos nos llevó a utilizar más tiempo del previsto, lo que impactó en la planificación inicial.

### Minuta de Daily Scrum 12:

**Fecha**: 2 de noviembre de 2023 

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Finalizamos la creación de prototipos y soluciones para abordar las mejoras identificadas.
- Se llevaron a cabo pruebas internas para validar la efectividad de los prototipos.

**¿Qué planificamos hacer?**
- Preparar los entregables para la siguiente fase del proyecto.

**¿Qué impedimentos tenemos?**
- A pesar del estancamiento a mitad del sprint, logramos acelerar sobre el final y completar los objetivos de la iteración con éxito.

### Reporte de horas

**Semana 1:**
<img width="1216" alt="Screenshot 2023-11-04 at 10 47 23" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/5d46ff26-acb1-4777-bd94-d528e4cf5c5b">

**Semana 2:**
<img width="1211" alt="Screenshot 2023-11-04 at 10 47 57" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/a5afcdb5-8c02-4640-ac4e-8ecd37f50729">

En los primeros días del sprint, el equipo estaba motivado y logró dedicarle más del tiempo pactado y avanzar con el proyecto. Cerca de la mitad del sprint el equipo no pudo dedicar el tiempo pautado, por lo que el progreso se vió estancado y se generaron retrasos. Por esta razón el equipo debió concentrar sus esfuerzos al final del sprint, dedicando más tiempo que el estimado en esos días, para poder alcanzar los objetivos. Se podría pensar que el empujón inicial del sprint tal vez agotó demasiado los recursos, lo que generó el estancamiento intermedio. De todas maneras, el equipo logró balancear los esfuerzos.

### Burndown chart
<img width="1010" alt="Screenshot 2023-11-04 at 10 44 50" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/d7c4d46b-246b-440d-91fb-f1caf16e4c11">

La Burndown Chart muestra las User Stories completadas a lo largo del sprint. Se pueden notar varias cosas:
1. Al principio del sprint el equipo avanzó en muchas tareas, pero no se indicaron como completadas las user stories, por lo que el chart se muestra plano en la primera parte de la iteración.
2. Posteriormente se puso al día el estado de las user stories.
3. En la  mitad del sprint se generó un fuerte estancamiento por falta de dedicación de tiempo del equipo hacia el proyecto
4. En el último tramo el equipo marcó como completas todas las historias realizadas
5. Se visualiza también que un par de historias fueron quitadas del alcance de la iteración, las mismas eran de baja prioridad y se trataba de mejoras sobre las cuales se realizó un spike y se evaluó que su dificultad no permitía incluirlas en este sprint.

<img width="1014" alt="Screenshot 2023-11-04 at 10 45 23" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/1d26c992-1cfc-48ef-96d3-5bfa7afe773d">

En la Burndown Chart de Tareas podemos observar lo siguiente:
1. Como se mencionó anteriormente, hubo un gran avance en las tareas los primeros días del sprint.
2. Posteriormente se produjeron avances menos pronunciados, pero por debajo de la línea ideal.
3. El gran estancamiento a la mitad del sprint generó que las tareas se acumularan por encima de la línea ideal
4. Finalmente se logró cumplir el objetivo, así como se eliminaron del alcance las tareas relacionadas a las user stories mencionadas anteriormente.

## Inspección y adaptación del proceso

### Minuta de la Retrospectiva: Sprint 3
**Fecha**: 3 de noviembre de 2023 

**Asistentes**: Scrum Master: Clara Casaretto Product Owner: Fernando Spillere Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**Dinámica Utilizada**: En esta retrospectiva, hemos optado por utilizar la técnica "Matriz de Priorización". Cada miembro del equipo tuvo la oportunidad de asignar puntos a las áreas que consideraban más relevantes para mejorar.

**Principales Resultados:** 

**Funcionó Bien:**
- Iniciar el desarrollo de prototipos temprano permitió explorar diversas soluciones.
- Las sesiones de usability testing brindaron valioso feedback de los usuarios.
- La colaboración y el apoyo entre los miembros del equipo se mantuvo efectiva.

**A Mejorar:**
- La necesidad de ajustes en los prototipos impactó en la planificación inicial.
- La comunicación sobre impedimentos podría ser más proactiva.
- La gestión del tiempo en la segunda mitad del sprint requiere mayor eficiencia.

**Planificación y Seguimiento de Acciones de Mejora:**

**Ajustes en Prototipos:**

**Acción:** Establecer un proceso de revisión de prototipos para identificar y abordar ajustes de manera más eficiente.

**Responsable:** Equipo de Desarrollo y Product Owner.

**Fecha de Implementación:** Del 4 al 8 de noviembre de 2023.

**Fecha de Seguimiento:** 10 de noviembre de 2023.


**Comunicación sobre Impedimentos:**

**Acción**: Continuar la práctica de actualización diaria sobre posibles impedimentos en la reunión de Daily Scrum.

**Responsable**: Todos los miembros del equipo.

**Fecha de Implementación**: A partir del 4 de noviembre de 2023.

**Fecha de Seguimiento**: Continua.


**Gestión del Tiempo:**

**Acción**: Implementar técnicas de gestión del tiempo y planificación más efectivas en la segunda mitad del sprint.

**Responsable**: Scrum Master y Equipo de Desarrollo.

**Fecha de Implementación**: A partir del 4 de noviembre de 2023.

**Fecha de Seguimiento**: 15 de noviembre de 2023.


**Conclusiones y Cierre de la Retrospectiva:** 
Hemos identificado áreas clave para mejorar y hemos definido acciones concretas para abordarlas. Estamos comprometidos a implementar estos cambios y esperamos una iteración más eficiente y productiva en el próximo sprint.


# Construir y validar posibles soluciones del MVP a través de prototipos

## Prototipos con posibles soluciones

En el siguiente enlace se puede visualizar el prototipo interactivo, para su mejor visualización recomendamos abrirlo en un dispositivo móvil, o achicar la pantalla del navegador ya que el prototipo fue pensado para una aplicación móvil:

[https://mvpvideogames.framer.website](https://mvpvideogames.framer.website) 

### Épica 3: Gestión de Torneos

**Crear Torneo**: Incorporación de opción de crear torneo en Home: 

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/36a49050-2d2c-4269-a769-a9c018a31b92)

Flujo de creación de torneo:

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/13689722-0d60-415e-adae-70dc7a85946e)

1. Opción Programar para después:
   
![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/8fb311fb-d53a-43d6-a77e-e85ce971f2f7)

3. Opción Jugar ahora: 

a. Pantalla de simulación de juego

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/644a4e40-62e1-486a-826c-706fdfee517c)


b. Pantalla posterior al juego con podio 

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/266a44f3-9eca-44d3-8e5c-91d0b1bcdfd8)


**Participar en Torneos**: Centro de notificaciones accesible desde ícono en el Home:

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/9cfcdcde-a5f6-4210-b89c-36e64bc76d3f)

### Épica 4:  Perfil de Usuario y Estadísticas

**Perfil de Usuario**: Incorporación de opción de acceder a Mi perfil en Home: 

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/e579c809-bcb0-4609-ac08-51f8ef036069)

**Ranking**: Incorporación de opción de Consultar ranking en Home: 

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/721ac4f8-0f54-4379-829b-b4c2668aa0fd)

### Épica 5: Notificaciones y Comunicación

**Notificaciones:** Centro de notificaciones accesible desde ícono en el Home:

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/22fd8e94-c48d-4071-ac64-5ca067b5e86c)

**Notificación en cambio en ranking**

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/32db38ed-9400-4c36-b2ca-43436d2ae861)

### Épica 6: Sistema de puntos y mercado de objetos

**Acumular puntos**

Se visualizan los puntos acumulados por cada usuario al finalizar el juego: 

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/8d3f24a1-9473-4183-b3a9-d32b7e148e50)

**Visualizar Market**

Incorporación de opción de Canjear puntos en Home:

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/254091c0-0468-4d8f-a586-85e1b56a5234)

### Épica 7: Mejoras

**Posibilidad de jugar**: Se incorpora mejora en mensaje de ingreso a juego por feedback obtenido de usuarios. 

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/25d58c40-f591-4f4d-8ad0-032d72b281cd)

Se incorpora pantalla de simulación de juego, en la que se visualiza un video del juego para hacer la experiencia más real. Se agrega ícono de flecha para salir del modo de simulación de juego. Se agrega podio de jugadores al terminar el juego.

**Mostrar el nombre de cada juego en la lista**: Se agrega el nombre de los juegos en las ventanas en las que se debe seleccionar un juego. Esta mejora se obtuvo de feedback con usuarios.

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/78adc4b7-a004-46bd-9fb1-e979c9ebc6dc)

**Seleccionar un solo juego a la vez**:

Se realizó un spike para investigar qué tan sencillo o difícil sería agregar esta validación, y se llegó a la conclusión de que no sería una solución sencilla y que tampoco aportaba demasiado valor a la experiencia de los usuarios, por lo tanto esta historia de usuario no se implementó.

**Estandarizar botones y mensajes**:

Se revisaron todas las pantallas, existentes y nuevas, y se realizaron pequeños cambios en aquellas que se consideró necesario.



## Inspección y adaptación del producto

_[Existe evidencia de instancias de inspección y validación del producto con usuarios y la recolección de su feedback con ajustes finales a los prototipos.]_

### Artefactos principales

- Minutas de sprint review.
- Evidencia de los usability testing con usuarios finales.
  - Descripción de las tareas propuestas a los usuarios finales.
  - Cobertura obtenida de validación de los usuarios de la aplicación.
- Feedback recibido de los usuarios finales con la priorización de las propuestas de cambio.
