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
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Finalizamos la documentación y preparamos todos los artefactos para la entrega.
- Realizamos una revisión interna exhaustiva para garantizar la calidad de los entregables.


**¿Qué planificamos hacer?**
- Coordinar la entrega formal del proyecto.
- Programar una reunión de cierre interno para reflexionar sobre el proceso.


**¿Qué impedimentos tenemos?**
- La revisión interna llevó más tiempo del esperado, pero aseguró la calidad de los entregables.

### Minuta de Daily Scrum 16:

**Fecha**: 16 de noviembre de 2023

**Asistentes**:
- Scrum Master: Clara Casaretto
- Product Owner: Fernando Spillere
- Miembros del Equipo de Desarrollo: Carmela Sotuyo, Ignacio Malamud, Alejandro Ruiz, Javier Gonzalez

**¿Qué logramos hacer?**
- Coordinamos la entrega formal del proyecto al cliente de manera exitosa.
- Celebramos el cierre del proyecto y compartimos las lecciones aprendidas.


**¿Qué planificamos hacer?**
- Programar una reunión de cierre con el cliente para recibir feedback final.
- Documentar las lecciones aprendidas y cerrar formalmente el proyecto.


**¿Qué impedimentos tenemos?**
- No se presentaron impedimentos en la etapa final del proyecto.

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

_[Se evidencian los prototipos finales con las validaciones de los usuarios. Los prototipos deberán ser exportados en algún formato de imagen (como png o jpg) a efectos de poder ser visualizados fácilmente dentro del propio repo de github.]_

### Artefactos principales

- Prototipos interactivos finales con el feedback de las validaciones.
- Prototipos asociados como bocetos a las historias de usuario.
- Lista de mejoras sugeridas de las validaciones con usuarios finales.
  - Se explicita que mejoras fueron implementadas en los prototipos y cuales quedaron fuera del alcance del proyecto.
