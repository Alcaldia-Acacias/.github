### 1. Introducción

El propósito de esta organización es servir como plataforma central para los miembros del equipo de desarrollo de la oficina TIC de la alcaldía de Acacías. Su objetivo principal es facilitar la trazabilidad y el seguimiento de los proyectos mediante el uso de repositorios. Además, busca evidenciar el trabajo individual mediante las asignaciones dentro de la herramienta de proyecto "Gobierno Digital", así como destacar los esfuerzos colaborativos del equipo en su conjunto. Al hacerlo, esta organización aspira a mejorar las comunicaciones internas y establecer un orden claro en las contribuciones de cada integrante, optimizando así la eficiencia y efectividad del equipo.

### 2. Código de Conducta

#### Código de Conducta de la Comunidad

**Nuestro Compromiso**

En el interés de fomentar un ambiente abierto y acogedor, nosotros, como contribuyentes y mantenedores, nos comprometemos a hacer de la participación en nuestro proyecto y nuestra comunidad una experiencia libre de acoso para todos, independientemente de la edad, tamaño corporal, discapacidad, etnia, características sexuales, identidad y expresión de género, nivel de experiencia, educación, estatus socioeconómico, nacionalidad, apariencia personal, raza, religión, o identidad y orientación sexual.

**Nuestros Estándares**

Ejemplos de comportamiento que contribuyen a crear un ambiente positivo incluyen:
- Usar un lenguaje acogedor e inclusivo.
- Ser respetuoso de los diferentes puntos de vista y experiencias.
- Aceptar críticas constructivas de buena fe.
- Enfocarse en lo que es mejor para la comunidad.
- Mostrar empatía hacia otros miembros de la comunidad.

Ejemplos de comportamiento inaceptable por parte de los participantes incluyen:
- El uso de lenguaje o imágenes sexualizadas, y atención o avances sexuales no deseados.
- Trollear, insultar/comentarios despectivos, y ataques personales o políticos.
- Acoso público o privado.
- Publicar información privada de otros, como una dirección física o electrónica, sin permiso explícito.
- Otras conductas que razonablemente podrían considerarse inapropiadas en un entorno profesional.

**Nuestras Responsabilidades**

Los mantenedores del proyecto son responsables de aclarar los estándares de comportamiento aceptable y se espera que tomen medidas correctivas apropiadas y justas en respuesta a cualquier caso de comportamiento inaceptable.

Los mantenedores del proyecto tienen el derecho y la responsabilidad de eliminar, editar o rechazar comentarios, commits, código, ediciones de páginas de wiki, issues, y otras contribuciones que no estén alineadas con este Código de Conducta, o de prohibir temporal o permanentemente a cualquier contribuyente por otros comportamientos que consideren inapropiados, amenazantes, ofensivos, o dañinos.

**Alcance**

Este Código de Conducta aplica tanto dentro de los espacios del proyecto como en espacios públicos cuando un individuo está representando al proyecto o a su comunidad. Ejemplos de representación del proyecto o la comunidad incluyen el uso de una dirección de correo electrónico oficial del proyecto, publicar a través de una cuenta oficial de redes sociales, o actuar como un representante designado en un evento en línea o fuera de línea.

**Cumplimiento**

Se espera que los casos de comportamiento abusivo, acosador, o de otro modo inaceptable sean reportados a los líderes del proyecto responsables de hacer cumplir el código. Todos los reclamos serán revisados e investigados de manera oportuna y justa.

Los mantenedores del proyecto están obligados a respetar la privacidad y la seguridad de quien reporte cualquier incidente.

**Directrices de Cumplimiento**

Los mantenedores del proyecto seguirán estas Directrices de Cumplimiento en la determinación de las consecuencias para cualquier acción que consideren en violación de este Código de Conducta:

1. Corrección: Influencia en la comunidad para entender la naturaleza de la comunidad inclusiva.
2. Advertencia: Una advertencia formal a dejar de comportarse de manera inaceptable.
3. Suspensión temporal: Un aviso indicando que el individuo no puede interactuar con el proyecto durante un período de tiempo especificado.
4. Expulsión permanente: Indicando que el individuo no puede volver a interactuar con el proyecto.

**Atribución**

Este Código de Conducta es adaptado del Contributor Covenant, versión 2.0, disponible en [https://www.contributor-covenant.org/version/2/0/code_of_conduct.html](https://www.contributor-covenant.org/version/2/0/code_of_conduct.html).

Fecha de efectividad: [14/02/2024]

### 3. Guía de Contribución

#### 3.1 Configuración Inicial

- @SantiagoV323 y @alxBlues tendrán roles de administradores y supervisores de la organización. Las solicitudes que se realicen deberán primero ser revisadas y aprobadas por los mencionados.
- Es importante crear un README.md detallando información relevante en cada repositorio al que un miembro vaya a aportar, para que los demás miembros puedan contextualizarse y familiarizarse con el contenido del repo, así como seguir recomendaciones acerca de entorno de desarrollo, dependencias, etc.
- Es importante crear un archivo .gitignore acorde al contenido del proyecto.

#### 3.2 Cómo Contribuir

- Se deben manejar buenas prácticas de programación, esto incluye:
  - Documentar bien el código para que sea fácil de revisar y dar mantenimiento en el futuro.
  - Realizar commits con frecuencia.
  - Documentar bien los commits con un mensaje corto pero descriptivo que permita contextualizar el cambio respecto al anterior commit.
- Está prohibido realizar push a main. Se insta a los miembros a realizar push a ramas alternativas.
- Después de hacer un push, este se clasificará como pull request en GitHub y deberá ser revisado y aprobado por un administrador para hacerlo efectivo y hacer merge con la rama alternativa.

##### PARA ADMINS:

**Instrucciones para aceptar un pull request y hacer merge a la rama alternativa**

1. Cambiar la rama base del PR antes de la fusión:
   - Ve al pull request en GitHub.
   - Haz clic en el botón "Edit" (Editar) que está al lado del título del PR.
   - En la sección "base branch" (rama base), selecciona la rama a la cual deseas que se haga el merge. Esta será la rama alternativa en lugar de main o master.
   - Haz clic en "Save" (Guardar) para confirmar el cambio.
2. Crear el PR directamente para la rama alternativa:
   - Cuando estés creando un nuevo pull request, puedes seleccionar directamente la rama destino (la que recibirá los cambios) en el menú desplegable "base repository" (repositorio base) y "base" (base) antes de crear el pull request. Asegúrate de elegir la rama alternativa en lugar de main o master.
3. Fusionar el PR en la rama alternativa:
   - Una vez que el PR está configurado para fusionarse en la rama alternativa correcta, simplemente sigue el proceso de revisión y fusión como lo harías normalmente. Asegúrate de que todos los conflictos (si los hay) estén resueltos.

### 4. Políticas de Branching

- Se insta a todos los miembros a crear ramas alternativas luego de clonar un repo, o luego de crear un repo para no afectar a la rama main. Esta será responsabilidad solo de los administradores, los cuales realizarán merge con la rama que el desarrollador haya definido que será la segunda principal para tener los cambios implementados y actualizados. Por lo tanto, main será solo rama de producción.
- Siempre que se cree una rama, se debe documentar la razón y función de la misma.
- Siempre que se vea la necesidad de eliminar una rama, se debe documentar e informar sobre esta acción antes de llevarla a cabo.

### 5. Manejo de Issues

#### 5.1 Creación de Issues

**¿Cuándo Crear un Issue?**

Debes considerar crear un issue en los siguientes casos:
- Reporte de errores (bugs): Si encuentras un error en el proyecto, crea un issue para documentarlo.
- Solicitud de nuevas características: Si tienes una idea para una nueva característica o una mejora, los issues son el lugar para proponerla.
- Tareas y mejoras: Para cualquier tarea específica o mejora que creas necesaria.
- Preguntas y discusiones: Utiliza issues para hacer preguntas o iniciar discusiones sobre temas relacionados con el proyecto.

**Cómo Crear un Issue Efectivo**

- Busca issues existentes: Antes de crear un nuevo issue, busca en los issues existentes para evitar duplicados. Si encuentras un issue similar, considera comentar en él en lugar de abrir uno nuevo.
- Utiliza una plantilla adecuada: Si el proyecto tiene plantillas de issue, úsalas. Las plantillas proporcionan una estructura para tu reporte, lo que ayuda a los mantenedores a entender y actuar sobre el issue de manera más eficiente.
- Sé claro y conciso en el título: El título del issue debe ser descriptivo pero conciso. Debe dar una idea clara de qué trata el issue.
- Proporciona una descripción detallada: En la descripción, explica el problema o la solicitud en detalle. Incluye toda la información relevante como pasos para reproducir un error, comportamiento esperado versus comportamiento actual, capturas de pantalla o logs si son aplicables, y posibles soluciones o ideas que tienes en mente.
- Usa etiquetas (labels) adecuadamente: Las etiquetas ayudan a categorizar y priorizar los issues. Utiliza las etiquetas proporcionadas por el proyecto para marcar tu issue adecuadamente (por ejemplo, bug, mejora, pregunta).

#### 5.2 Asignación de Issues

Se puede auto asignar un issue o solicitar que se asigne un issue a otro miembro.

### 6. Proceso de Revisión de Pull Requests

- Solo se aceptarán pull requests que cumplan con los criterios de documentación mencionados. El aporte debe estar previamente probado, y el pull request no debe ser de la rama main.
- El proceso de revisión debe verificar que cumpla con los requisitos mencionados para poder realizar aportes al repo.
- Es importante revisar el pull request con frecuencia para estar al tanto de comentarios o realizar comentarios que complementen o se consideren pertinentes aportando más información al revisor del pull request.

### 7. Políticas de Merge

- Solo se realizará merge a main por componentes y cuando estos hayan pasado pruebas unitarias y de integración en la rama alternativa.

### 8. Comunicación y Colaboración (pendiente)

Herramientas y plataformas recomendadas para la comunicación entre los colaboradores (por ejemplo, Slack, Discord, reuniones regulares).
Expectativas sobre la disponibilidad y respuesta de los colaboradores.
