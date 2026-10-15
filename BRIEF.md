# Brief de proyecto — Memento:

## 1. Problema que resuelve:

Memento surge de la necesidad de facilitar la organización de las tareas cotidianas y reducir los olvidos relacionados con responsabilidades que deben realizarse en momentos determinados.

Durante la entrevista realizada a Inmaculada Aznar, de 54 años, se identificaron dos situaciones concretas: olvidar alimentar a su mascota después de una jornada de trabajo y tener dificultades para seguir los horarios de medicación de su madre.

La entrevistada explica que debe estar pendiente de varias responsabilidades y que le preocupa olvidar alguna de ellas. También indica que utiliza un móvil Samsung, dispone de conexión de fibra en casa y considera que podría utilizar la aplicación tanto en su móvil como en su tableta.

Estos hallazgos orientan el diseño hacia una aplicación que permita centralizar las tareas, consultar cuándo deben realizarse, recibir recordatorios y comprobar cuáles se han completado. Aunque la investigación incluye un caso relacionado con la medicación, Memento se plantea como una herramienta de organización cotidiana, no como una aplicación exclusivamente sanitaria.


## 2. Alcance del proyecto:

El producto mínimo viable (MVP) permitirá a los usuarios gestionar sus propias tareas desde una interfaz adaptable a dispositivos móviles y ordenadores.

### Funcionalidades incluidas

- Crear una cuenta e iniciar sesión.
- Consultar un resumen de las tareas previstas para el día.
- Crear tareas con nombre, descripción opcional, fecha y hora.
- Configurar la repetición de las tareas y sus recordatorios.
- Consultar el listado de tareas y acceder al detalle de cada una.
- Editar y eliminar tareas.
- Marcar las tareas como realizadas y consultar su estado.
- Acceder al perfil personal y a los ajustes básicos de la aplicación.

### Funcionalidades fuera del MVP

Para mantener el alcance asumible, inicialmente no se desarrollarán:

- Gestión compartida de tareas entre usuarios.
- Integraciones con hospitales u otros servicios sanitarios.
- Funcionalidades de inteligencia artificial.
- Clasificación mediante categorías personalizadas.

Las funcionalidades adicionales podrán valorarse en futuras versiones si las necesidades detectadas lo justifican.


## 3. Personas:

La persona principal del proyecto es [Inmaculada Aznar](https://www.figma.com/board/pzA1Icv7SfQCwVgC9IZSlG/User-flow--User-person-y-SiteMap?node-id=0-1&t=paBk811AvBpZvz0z-1), cuya ficha y entrevista se encuentran en el archivo de FigJam del proyecto.

**Inmaculada Aznar, 54 años.** Trabaja como limpiadora y necesita organizar varias responsabilidades cotidianas, recordar tareas importantes y gestionar horarios que pueden resultar difíciles de memorizar. Utiliza un móvil Samsung y dispone de conexión de fibra en casa. Sus necesidades orientan el diseño hacia una interfaz clara, accesible y adaptable a distintos dispositivos.

La ficha se utilizará como referencia para tomar decisiones de diseño y preparar las pruebas de usabilidad.

## 4. Criterios de éxito

Los siguientes criterios son objetivos de diseño que deberán comprobarse mediante pruebas de usabilidad durante la Órbita 5. No representan resultados de pruebas ya realizadas.

1. **Creación de tareas:** Inmaculada puede crear una tarea con nombre, fecha y hora en menos de un minuto, sin ayuda externa.
2. **Consulta de tareas:** Inmaculada puede localizar la próxima tarea pendiente desde la página principal en menos de 10 segundos.
3. **Recordatorios:** Inmaculada puede configurar un recordatorio para una tarea sin ayuda y comprender cuándo recibirá el aviso.
4. **Seguimiento:** Inmaculada puede marcar una tarea como realizada e identificar su nuevo estado en menos de 15 segundos.
5. **Edición y eliminación:** Inmaculada puede localizar una tarea, acceder a sus opciones y modificarla o eliminarla sin ayuda.
6. **Claridad de la interfaz:** Inmaculada puede identificar las secciones principales y acceder a ellas mediante la navegación sin necesitar instrucciones externas.

Los tiempos se medirán durante las pruebas y servirán para identificar dificultades y realizar mejoras en el diseño.


## 5. Restricciones:

### Tecnológicas:

El proyecto se desarrollará utilizando el stack MERN, de acuerdo con los requisitos académicos:

- **MongoDB:** almacenamiento de los datos.
- **Express.js:** desarrollo de la API del servidor.
- **React:** construcción de la interfaz.
- **Node.js:** ejecución del servidor.

La implementación deberá ajustarse a los requisitos de los módulos de Diseño de Interfaces Web, Desarrollo Web en Entorno Cliente, Desarrollo Web en Entorno Servidor y Despliegue de Aplicaciones Web.

### Temporales:

El proyecto está condicionado por el calendario académico y las entregas de los módulos implicados. Por ello, se priorizarán las funcionalidades del MVP antes de abordar mejoras secundarias.

### Relacionadas con las personas:

La investigación disponible se basa en la entrevista y ficha de Inmaculada Aznar. Se ha identificado el uso de un móvil Samsung, una tableta como posible dispositivo adicional y conexión de fibra en el domicilio. La aplicación deberá contemplar diferentes tamaños de pantalla y facilitar la consulta de tareas con una navegación comprensible.

No se han validado todavía todas las condiciones de uso, por lo que será necesario comprobar la facilidad de utilización mediante pruebas con la persona.

### Ambientales y sostenibilidad

Se priorizarán interfaces ligeras, imágenes optimizadas, recursos reutilizables y una carga eficiente de las páginas.

Como objetivo técnico inicial, el peso transferido en la primera carga de la página principal no deberá superar **1,5 MB**, medido en recursos comprimidos y sin contar contenido introducido posteriormente por el usuario. Este límite se revisará durante la implementación para equilibrar rendimiento, funcionalidad y calidad visual.


## Documentación relacionada:

- [Investigación, persona, user flow y sitemap (FigJam)](https://www.figma.com/board/pzA1Icv7SfQCwVgC9IZSlG/User-flow--User-person-y-SiteMap?node-id=0-1&t=paBk811AvBpZvz0z-1)
- [Wireframes del proyecto (Figma Design)](https://www.figma.com/design/vVABDLa5WE39g6ro31ITc6/WireFrame-Memento?node-id=0-1&t=9XetLVAGtd48GO4d-1)
- [README del proyecto](README.md)
- [Registro de cambios y uso de IA](CHANGELOG.md)