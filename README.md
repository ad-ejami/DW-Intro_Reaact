<div align="center">
    <h1>Curso de introducción a React.js</h1>
</div>

# ¿Cuándo usar React.js?

Hay dos flujos de trabajo para crear aplicaciones web

## Modelo en cascada:

Cuando cada equipo tiene un tiempo para hacer todo su respectivo trabajo para construir una app. Por ejemplo: el equipo de diseño diseña la aplicación, el de desarrollo programa todo lo diseñado y finalmente se lanza la app recogiendo el feedback de los usuarios y se vuelve a empezar tomando en cuenta lo dicho por los usuarios. Es problemático porque el esfuerzo puede ser en vano porque no se tiene un feedback hasta que se termina de construir la app.

## Modelo del ciclo imperativo:

Se refiere a que cada equipo se enfocará en ciclos pequeños para construir partes más pequeñas de una app que en conjunto se puedan ir ensamblando para hacer la app completa. Resuelve el problema del modelo anterior, aquí se recibe el feedback al terminar cada pequeño ciclo, recibiendo así el feedback de manera más inmediata que antes.

## MVP’s o :

Se refiere a construir funcionalidades pequeñas que sean completas para que podamos lanzarla y medir su impacto y decidir si seguir ese camino o probar otra cosa.

Hay que escoger el problema más crucial que debe resolver la app.

## Análisis: Componentes y comportamientos

**Componentes**: Son la forma de estructurar las piezas de nuestra página web para hacerlas escalables, nos ahorran tiempo y esfuerzo. Son abstracciones de los elementos de nuestra página web para ser reusados las veces que necesitemos. Trabajan de manera independiente a los demás. Con react todos los componentes tienen una conexión con el resto de componentes de la app para que en conjunto reaccionen a los comportamientos del usuario.

**Comportamiento**: Las interacciones de los usuarios.

React es muy bueno cuando queremos construir rápidamente la primera versión funcional de una app web sin sacrificar su escalabilidad. Si no queremos escalarla después, no usar react, podemos usar JS simple.
# Instalación con Create React App
Se pueden importar los scripts del código fuente de react directamente en el html o creando un entorno de desarrollo completo con empaquetadores y otras herramientas.

Hay varias versiones que podemos usar como lo son la de desarrollo o la de producción que están más optimizadas.

Para hacer el ambiente de desarrollo usamos create react app, el cual podemos personalizar manualmente. En el dado caso de que queramos usar una configuración predeterminada usamos

`npx create-react-app` (npx instala temporalmente nuestras herramientas para ejecutarlas y luego borrarlas, eso permite tener siempre la última versión actualizada de la herramienta que queramos ejecutar). Además de esto, actualiza automáticamente los cambios hechos en el código

**react-scripts** es la configuración que hizo create-react-app por nosotros. Es un paquete que acelera el proceso de trabajo con react, pero no está tan optimizado a diferencia de hacerlo manualmente.

`div id=“root”` es donde se va a renderizar el código escrito en JS con react.

`ReactDOM.render` es donde enviaremos los componentes que queremos renderizar

**Babel** es el que hace la traducción que nos facilita la escritura de código de una manera más cómoda.

`npm start` para ejecutar el servidor de desarrollo.