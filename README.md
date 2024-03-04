React.js: Una biblioteca para interfaces de usuario
React.js, o simplemente React, es una biblioteca de código abierto de JavaScript para crear interfaces de usuario interactivas y eficientes. No es un framework completo, sino que se centra en la capa de vista de las aplicaciones web.

Diferencias en React.js versión 18:

Routing:

Se introduce la API useRoutes para una gestión más sencilla de rutas.
Se admite el anidamiento de rutas para una mejor organización.
Rendering:

Se actualiza el algoritmo de reconciliación para mejorar el rendimiento.
Se introduce el modo concurrente para renderizar partes de la interfaz de usuario en paralelo.
Data Fetching:

Se introduce la API useSWR para la recuperación de datos con suspensión y revalidación automática.
Styling:

Se integra con el sistema de estilos CSS-in-JS de Emotion.
Optimizaciones:

Se introducen nuevas herramientas para la detección y eliminación de código muerto.
Typescript:

Se mejora la integración con Typescript para una mejor experiencia de desarrollo.
Conceptos clave de React:

Componentes:

Los componentes son unidades reutilizables de código que encapsulan la lógica y la presentación de una parte de la interfaz de usuario.

JSX:

JSX es una extensión de la sintaxis de JavaScript que permite mezclar código HTML y JavaScript dentro de los componentes.

Props:

Las props son propiedades que se pasan de un componente padre a un componente hijo para personalizar su comportamiento.

State:

El state es un objeto que almacena datos dinámicos que cambian con el tiempo y que son específicos de un componente.

Patrones de diseño:

Composite:

El patrón Composite permite crear estructuras jerárquicas de componentes donde cada componente puede tener hijos. En React, este patrón se implementa naturalmente con la anidación de componentes.

State:

El patrón State permite encapsular el estado interno de un componente y proporcionar métodos para actualizarlo. En React, este patrón se implementa con el hook useState.
