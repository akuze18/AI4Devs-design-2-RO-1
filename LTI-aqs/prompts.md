# Inicio de entrega de diseño 2
* Asistente usado   :   Github Copilot en VSC
## Prompt 1: User Stories
```
Analiza el contexto del producto que está en la carpeta content, para que entiendas en lo que estamos trabajando.
Vamos a generar User Stories para este producto tiendo en cuenta los roles de Product Manager y Business Analyst

La plantilla para las User Stories con el formato esperado es:
# [Título de la Historia de Usuario:]
Como [rol del usuario],
quiero [acción que desea realizar el usuario],
para que [beneficio que espera obtener el usuario].

# Criterios de Aceptación:
* [Detalle específico de funcionalidad]
* [Detalle específico de funcionalidad]
* [Detalle específico de funcionalidad]

# Notas Adicionales:
* [Cualquier consideración adicional]

# Historias de Usuario Relacionadas: (Solo si las hubiera, no inventar nada aca)
* [Relaciones con otras historias de usuario]

Plantea diferentes User Stories que pudieran darse para este producto, mínimo 2, máximo 5, considerando que estamos iniciando el proyecto y no tenemos nada implementado, solo están las definiciones.

El resultado se guardará en el archivo UserStories-aqs.md
```

## Prompt 2: User Stories
```
Esto no es lo que esperaba. Las historias de usuario que esperaba, era sobre cuestiones que un usuario regular o administrativo del sistema pudiera tener. Luego desde los enfoques de Product Manager y Business Analyst, se pudieran aterrizar estas historias, y las entregaras en el formato indicado, vuelve a intentarlo por favor.
```

## Prompt 3: Backlog del producto
```
Perfecto, estas user stories están excelente. Ahora necesito convertirlas en backlog de producto, para ello necesito que me expliques cual sería la forma de realizar esto, y hazme las preguntas que consideres necesarias para realizar un buen trabajo.
```

### Respusta 3
Para convertir estas User Stories en un backlog de producto, el proceso implica organizar, priorizar y detallar las tareas necesarias para implementar cada historia. Aquí está el enfoque:

Pasos para convertir User Stories en un backlog de producto:
1. Priorizar las User Stories:  
Clasifica las historias según su impacto en el negocio, urgencia y dependencia de otras funcionalidades. Por ejemplo:
    * Historias críticas como "Gestión de Usuarios" y "Auditoría de Actividades" podrían tener mayor prioridad.
    * Historias como "Notificaciones Automáticas" podrían ser secundarias si no son esenciales para el MVP (Producto Mínimo Viable).

2. Dividir las historias en tareas más pequeñas:  
Cada historia debe desglosarse en tareas técnicas y funcionales. Por ejemplo:  
    * Para "Gestión de Usuarios":
    * Crear la interfaz para agregar usuarios.
    * Implementar la lógica de asignación de roles.
    * Configurar el historial de cambios.

3. Estimar el esfuerzo de cada tarea:  
Asigna estimaciones de tiempo o puntos de esfuerzo a cada tarea usando técnicas como Planning Poker o T-Shirt Sizing.

4. Definir dependencias:  
Identifica qué tareas dependen de otras. Por ejemplo, "Auditoría de Actividades" podría depender de la implementación de "Gestión de Usuarios".

5. Organizar el backlog:  
Usa herramientas como Jira, Trello, o Azure DevOps para estructurar el backlog. Agrupa las tareas por sprint o fase del proyecto.

6. Revisar y ajustar:  
Colabora con el equipo para validar el backlog y ajustarlo según los recursos disponibles y los objetivos del proyecto.
---

Preguntas para realizar un buen trabajo:
1. ¿Cuál es el objetivo principal del sistema en esta fase del proyecto? (MVP, funcionalidades críticas, etc.)
2. ¿Existen restricciones técnicas o de tiempo que debamos considerar?
3. ¿Qué herramientas de gestión de proyectos se utilizarán para organizar el backlog?
4. ¿Hay algún estándar o metodología específica que debamos seguir (Scrum, Kanban, etc.)?
5. ¿Quiénes serán los responsables de validar las prioridades y estimaciones del backlog?
6. ¿Se requiere documentación adicional para cada tarea del backlog?

Con estas respuestas, puedo ayudarte a estructurar el backlog de manera más precisa. ¿Cómo deseas proceder?

## Prompt 4: Backlog del producto (v1)
```
Perfecto, entonces respondo las preguntas para proceder a estructurar el backlog considerando las historias de usuario ya definidas.  
1. El objetivo del proyecto está en la fase inicial MVP.
2. Contamos con 4 semanas para la entrega.
3. Se utilizará Jira para la gestión del proyecto
4. No hay ninguna metodología en especifico, utiliza la que consideres más adecuada
5. Yo me encargaré de validar las prioridades
6. La documentación necesaria está en este proyecto
```
## Prompt 5: Backlog del producto (v2)
```
Considerando las historias de usuario definidas haz lo siguiente:
1. Prioriza las user stories, utiliza la escala de poca prioridad a alta prioridad, valorizala como consideres pertinente.
2. Divide las historias de usuario en tareas pequeñas, sobre todo cuando son muy grandes.
3. Estima el esfuerzo de cada tarea, utilizando la ténica de t-shirt size-
4. Define las dependencia de las historias de usuario, si corresponden.
5. Dame el listado por order de prioridad, indicando las tareas por historia, esfuerzo estimado y dependencias si aplican.
Realiza todas estas labores juntas entregame el listado final
```
## Comentarios sobre los prompt usados para generación de backlog de producto  
Considerando que no tengo mucho conocimiento sobre metodologías ágiles y como es su funcionamiento, ambos prompt han generado cosas diferentes, y los resultados nos entregan información diferente, no considero que una sea mejor que otra, ya que dependerá de como se quiera trabajar, ya que una da el orden de los sprints, mientras que la otra hace un deglose granular, para poder hacer la ordenación en sprints posteriormente. Para mí el segundo prompt me dio un resultado que es más utilizable, ya que deja el paso a que un equipo pueda ordenar y priorizar segun sus propios criterios.

## Prompt 6: Generar Tickets
```
Considerando las User Stories definidas y el backlog v2 como el que vamos a usar, genera los tickets de trabajo para user storie 1, y detallalo como si fuera un reunión de planificación.
```

# Comentarios finales del ejercicio
* No conozco mucho sobre el uso de metodologías agiles, y se me hizo muy complicado por ir resolviendo los puntos pedidos, porque no sabía muy bien que pedir ni que esperar de la IA en su resultado.
* Me apoye en Chat GPT (free) para ir resolviendo dudas sobre el tema, de modo de no ir "ensuciando" el chat en donde estaba realizando las tareas.
* Este ejercicio me ayudó a explorar un mundo desconocido para mi, que son las metodologías agiles, las cuales nunca practiqué, porque en donde trabajo no son requeridas.