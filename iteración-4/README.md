# Indice

- [Gestión de la iteración](#gestión-de-la-iteración)
  - [Definición del marco de trabajo](#definición-del-marco-de-trabajo)
  - [Planificación de la iteración](#planificación-de-la-iteración)
  - [Seguimiento de la iteración](#seguimiento-de-la-iteración)
  - [Inspección y adaptación del proceso](#inspección-y-adaptación-del-proceso)
- [Construir y validar posibles soluciones del MVP a través de prototipos.](#construir-y-validar-posibles-soluciones-del-mvp-a-través-de-prototipos)
  - [Prototipos finales](#prototipos-finales)

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

### Minuta de la Sprint Planning: Iteración 4

**Fecha**: 6 de noviembre 

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**Agenda**:

1. Bienvenida y Objetivo de la Reunión:
Inicio de la reunión con una breve bienvenida.
Objetivo: Reflexionar sobre el feedback final de los clientes y planificar las actividades de cierre del proyecto.

2. Feedback de Clientes:
Compartir y discutir los comentarios finales de los clientes sobre la aplicación del juego.
Destacar los puntos clave y áreas de éxito identificadas por los clientes.

3. Creación de User Stories:
Identificar las últimas funcionalidades y mejoras necesarias para cerrar el proyecto de manera integral.
Crear user stories basadas en los comentarios finales de los clientes.

4. Priorización de User Stories:
Priorizar las user stories de acuerdo con su importancia para cerrar el proyecto de manera satisfactoria.
Acordar cuáles serán abordadas en esta última iteración.

5. Asignación de Tareas:
Asignar las últimas tareas a los miembros del equipo de desarrollo.
Establecer responsabilidades específicas para la implementación de funcionalidades y actividades de cierre.

6. Conclusiones y Cierre de la Reunión:
Resumir los acuerdos alcanzados.
Establecer los próximos pasos y actividades de cierre.
Concluir la reunión con un enfoque claro en la finalización exitosa del proyecto.



**Actividades y Resultados**:
- Reflexión sobre el feedback final de los clientes.
- Identificación de las últimas mejoras y funcionalidades para cerrar el proyecto.
- Priorización de actividades de cierre.
- Asignación de tareas específicas a los miembros del equipo.
- Planificación de las últimas acciones para cerrar el proyecto de manera efectiva.

La reunión fue productiva y permitió al equipo de desarrollo abordar de manera efectiva las últimas mejoras y funcionalidades necesarias para concluir el proyecto de manera satisfactoria, basándose en el feedback final de los clientes.


### Objetivos de la iteración 

En la Iteración 4, nuestro enfoque se centra en las reflexiones finales y en cerrar de manera integral el proyecto, consolidando las mejoras realizadas y preparándonos para la fase de entrega. Este resumen destaca los puntos clave relacionados con los objetivos, resultados, actividades y el enfoque de esta última etapa del desarrollo.

- Cierre Integral del Proyecto:
  
En la Iteración 4, nos centraremos en completar todas las funcionalidades y actividades restantes para cerrar el proyecto de manera satisfactoria.
Se revisarán las user stories creadas en respuesta al feedback final de los clientes, asegurando su implementación y resolviendo posibles problemas pendientes.

- Reflexiones y Aprendizajes Finales:

Durante esta iteración, dedicaremos tiempo a reflexionar sobre el proyecto en su totalidad.
Se realizará un análisis de los aprendizajes obtenidos a lo largo del desarrollo y se documentarán las lecciones aprendidas para futuros proyectos.

- Preparación para la Entrega:

Se prepararán los entregables finales, incluyendo documentación, prototipos finales y cualquier otro artefacto necesario.
Se garantizará que todas las herramientas utilizadas estén debidamente archivadas y que el código fuente esté organizado y disponible para futuras referencias.


### Sprint backlog con historias de usuarios y tareas asociadas
**Épica 7: Mejoras**
- **Seleccionar un solo juego a la vez**: Como usuario, quiero poder seleccionar un solo juego a la vez.
  - **Criterios de Aceptación**: 
    - Solo se puede seleccionar un juego a la vez en la lista del mercado.
  - **Tareas**:
    1. Implementar la funcionalidad de selección de juegos en la lista del mercado

- **Estandarizar botones y mensajes**: Como usuario, quiero que los botones y mensajes en la aplicación sigan un estándar de diseño y comunicación para una experiencia coherente.
  - **Criterios de Aceptación**: 
    - Todos los botones en la aplicación deben tener un diseño y tamaño consistentes.
    - Los mensajes y notificaciones deben seguir una tonalidad y estilo uniformes.
  - **Tareas**:
    1. Revisar y actualizar el diseño de los botones en toda la aplicación para que sigan un estándar.
    2. Asegurarse de que los mensajes y notificaciones tengan una comunicación coherente y clara.
   
### Planificación de acuerdo a la capacidad del equipo.
Para este sprint, se tomaron las historias de usuario generadas a partir del feedback de los clientes, las cuales resultaron en 2 con un esfuerzo estimado en 4 story points. Es un número menor al que se viene trabajando pero esas eran todas las que teníamos en el backlog.

### Técnicas de priorización y estimación utilizada
En este caso especial al haber únicamente 2 historias de usuarios, se decidió realizarlas todas. No hubo una técnica de priorización específica. La estimación la hicimos en base al esfuerzo realizado anteriormente.

### Métricas del equipo
El equipo obtuvo una velocity de 4 story points en este Sprint, inferior a los 10 SP alcanzados en los sprints pasados, pero teniendo en cuenta que se tomaron todas las historias de usuarios habidas en el backlog.

## Seguimiento de la iteración

### Minuta de Daily Scrum 13:

**Fecha**: 7 de noviembre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Iniciamos la iteración 4 con un enfoque claro en las actividades de cierre del proyecto.
- Revisamos los entregables finales y confirmamos la conclusión de las funcionalidades pendientes.

**¿Qué planificamos hacer?**
- Realizar una última revisión integral de todas las funcionalidades y asegurarnos de que estén completamente implementadas.
Iniciar la documentación final y preparar todos los artefactos necesarios para la entrega.

**¿Qué impedimentos tenemos?**
- No se presentaron impedimentos

### Minuta de Daily Scrum 14:

**Fecha**: 9 de noviembre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Progresamos en la revisión integral de las funcionalidades implementadas.
- Iniciamos la documentación final y organizamos los entregables para la entrega.


**¿Qué planificamos hacer?**
- Finalizar la documentación y confirmar que todos los artefactos estén listos para la entrega.
- Coordinar una revisión final interna antes de la entrega al cliente.


**¿Qué impedimentos tenemos?**
- No se progresó mucho porque no hubo tiempo de parte del equipo por otros proyectos

### Minuta de Daily Scrum 15:

**Fecha**: 14 de noviembre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Finalizamos la documentación y preparamos todos los artefactos para la entrega.
- Realizamos una revisión interna exhaustiva para garantizar la calidad de los entregables.


**¿Qué planificamos hacer?**
- Coordinar la entrega formal del proyecto.
- Programar una reunión de cierre interno para reflexionar sobre el proceso.


**¿Qué impedimentos tenemos?**
- Contamos con una integrante menos en el equipo por unos días ya que se fue de viaje.

### Minuta de Daily Scrum 16:

**Fecha**: 16 de noviembre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Nos acercamos a la completitud del trabajo.


**¿Qué planificamos hacer?**
- Documentar las lecciones aprendidas y cerrar formalmente el proyecto.


**¿Qué impedimentos tenemos?**
- No se presentaron impedimentos en la etapa final del proyecto.

### Reporte de horas

En la etapa final del proyecto, el equipo se vió un poco más reducido, lo cual impactó en la dedicación en horas al proyecto. A su vez se sintió menos presión por la cantidad de esfuerzo requerido, lo cual también explica la reducción en cantidad de horas dedicadas.

Primera semana de la iteración:
<img width="1225" alt="Screenshot 2023-11-18 at 00 07 40" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/725f6d5c-4780-4403-a660-9a7c41fe07b6">

Segunda semana de la iteración:
<img width="1222" alt="Screenshot 2023-11-18 at 00 07 50" src="https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/6e49909d-ca69-4cad-b682-766f74a02bb0">

### Burndown chart

En la última iteración el equipo abandonó un poco el seguimiento dentro de la herramienta Azure. Esto se explica por varias razones, por ejemplo el hecho de que se contaban con pocas historias de usuario para implementar en esta iteración, así como cierta desorganización y cansacio por parte de los integrantes en esta última etapa del proyecto. Si bien las tareas y pendientes se fueron realizando durante la iteración, no se realizó un buen registro en la herramienta. Es por esto que el burndown chart se ve sin cambios hasta que se marcan como terminadas todas las tareas sobre el final de la iteración.

![WhatsApp Image 2023-11-18 at 00 36 04](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/101828758/3971f9ba-9e16-4421-b383-9e5717b802be)


## Inspección y adaptación del proceso

### Minuta de la Retrospectiva: Sprint 4
**Fecha**: 17 de noviembre de 2023

**Asistentes**: Scrum Master: Clara Casaretto Product Owner: Fernando Spillere Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**Dinámica Utilizada**: En esta retrospectiva, hemos decidido emplear la técnica "Estrella de Mar". Cada miembro del equipo ha compartido aspectos que considera que funcionaron bien durante la iteración y áreas que podrían mejorarse.

**Principales Resultados:** 

**Funcionó Bien:**
- Finalización exitosa de la documentación y entrega de los prototipos.
- Celebración y cierre positivo del proyecto.


**A Mejorar:**
- Ajustes finales tomaron más tiempo del esperado.
- Descoordinación en la revisión final interna.

**Conclusiones y Cierre de la Retrospectiva:** 
Hemos identificado áreas para mejorar y definido acciones concretas para abordarlas. Estamos comprometidos a implementar estos cambios y esperamos una conclusión del proyecto sin contratiempos y con aprendizajes valiosos.

# Construir y validar posibles soluciones del MVP a través de prototipos

## Prototipos finales
 
### Prototipos interactivos finales con el feedback de las validaciones

En el siguiente enlace se puede visualizar el prototipo interactivo, para su mejor visualización recomendamos abrirlo en un dispositivo móvil, o adaptar la pantalla del navegador ya que el prototipo fue pensado para una aplicación móvil:
https://mvpvideogames.framer.website/

#### Feedback de las validaciones finales

Durante las validaciones del prototipo final, se obtuvieron comentarios valiosos que proporcionarán insights clave para mejorar aún más la aplicación.

- Posibilidad de Jugar:
  - Aunque se introdujo un intento de simular la conexión con un juego mediante un video, los usuarios aún expresaron deseos de una opción más interactiva.
- Claridad en la Elección de Juegos:
  - Mostrar el nombre de cada juego debajo de los íconos mejoró la comprensión, pero algunos usuarios sugirieron un formato más llamativo.
- Selección de Juegos:
  - La corrección de la posibilidad de seleccionar múltiples juegos fue bien recibida por los usuarios.
- Mejora de Mensajes Toast:
  - Los ajustes propuestos en los mensajes toast contribuyeron a una mejor comprensión de las acciones del usuario.
- Invitar Amigos en Creación de Partida:
  - Los usuarios expresaron su deseo de una función de invitación de amigos, lo cual se considera una adición valiosa.
- Vistas Específicas para Cada Juego:
  - La sugerencia de proporcionar vistas específicas para cada juego fue respaldada positivamente por los usuarios.

**Conclusiones:**

El feedback de las validaciones del prototipo final reafirma el interés de los usuarios y destaca áreas clave para mejoras adicionales.

### Prototipos asociados como bocetos a las historias de usuario

**Seleccionar un solo juego a la vez**: Como usuario, quiero poder seleccionar un solo juego a la vez.
- Criterios de Aceptación: 
  - Solo se puede seleccionar un juego a la vez en la lista del mercado.
- Tareas:
  - Implementar la funcionalidad de selección de juegos en la lista del mercado.

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/c8d519a8-8264-4200-9d19-0f03311a996c)

**Estandarizar botones y mensajes**: Como usuario, quiero que los botones y mensajes en la aplicación sigan un estándar de diseño..
- Criterios de Aceptación: 
  - Todos los botones en la aplicación deben tener un diseño y tamaño consistentes.
  - Los mensajes y notificaciones deben seguir una tonalidad y estilo uniformes.
- Tareas:
  - Revisar y actualizar el diseño de los botones en toda la aplicación para que sigan un estándar.
  - Asegurarse de que los mensajes y notificaciones tengan una comunicación coherente y clara.

![image](https://github.com/IngSoft-ISA1-2023-2/N6A-AN-mini-proyecto-casaretto-gonz-malam-ruiz-sot-spil/assets/72991161/8a70e8d8-00e4-4690-bc26-3cebf8a9ff2d)

### Lista de mejoras sugeridas de las validaciones con usuarios finales

**Mejoras Logradas en el Prototipo Final:**

- Posibilidad de Jugar:
  - Descripción: Se exploraron opciones para simular la conexión con un juego mediante un video.
- Claridad en la Elección de Juegos:
  - Descripción: Se mejoró la identificación de los juegos al mostrar el nombre debajo de los íconos en la pantalla de elección de juegos.
- Selección de Juegos:
  - Descripción: Se corrigió la posibilidad de seleccionar múltiples juegos simultáneamente.
- Botones sin Interacción:
  - Descripción: Se añadió interactividad a los íconos de menú y notificaciones en la pantalla de inicio.
- Campo Cantidad de Jugadores:
  - Descripción: Se reevaluó la necesidad de asignar recursos a este ajuste y se priorizó según la importancia para la experiencia del usuario.
- Mejora de Mensajes Toast:
  - Descripción: Se refinaron los mensajes toast para una comunicación más clara y consistente.
- Contraseña Visible:
  - Descripción: Se evaluó la necesidad de cambiar esta funcionalidad en base a futuros hallazgos de seguridad.
- Invitar Amigos en Creación de Partida:
  - Descripción: Se consideró como una adición valiosa y se priorizó para futuras iteraciones.
- Vistas Específicas para Cada Juego:
  - Descripción: Se respaldó positivamente la sugerencia de proporcionar vistas específicas para cada juego.

**Mejoras Fuera del Alcance del Proyecto:**

- Jugar de Verdad:
  - Descripción: Permitir una experiencia de juego real dentro de la aplicación.
- Mostrar Géneros de Juegos y Juegos Específicos:
  - Descripción: Proporcionar información sobre géneros de juegos y permitir la selección de juegos específicos.
- Chat Entre Amigos:
  - Descripción: Integrar una función de chat para la comunicación entre amigos dentro de la aplicación.
