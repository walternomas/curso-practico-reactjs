# Conceptos
## JSX
Esta extensión hace referencia a JS y XML, lo cual es un sistema que podemos denominar de plantillas. Podemos hacer HTML dentro de JS, con este recurso React y su API entienden qué elementos están en esta estructura y los transformará a código JS.

## Virtual DOM
Es una copia y representación del Real DOM. Cuando suceda un cambio se va a comparar lo que hay en el Virtual DOM con lo que ha pasado dentro del estado o que nuestra aplicación está reaccionando a diferentes eventos que vamos a poder desencadenar por medio de un click, por medio del cambio del estado o el llamado a una API. 


Una vez que tenemos estos nuevos cambios que queremos representar en la parte gráfica o en la interfaz, comparamos el Real DOM con los cambios que van a suceder para saber exactamente dónde va a hacer estos cambios. De esta forma no hacemos un render completo de nuestra aplicación sino solamente de una pieza específica de nuestro componente.

De esta forma añadimos mucho dinamismo a nuestras aplicaciones y no tener que refrescar nuestra página web completa.

Antes de React para manejar nuestras páginas web lo que se hacía era manipular el DOM, una abstracción de nuestro código en forma de árbol, donde se encontraban todos los nodos de HTML. Sin embargo con la salida de JSX y React ya no nos hace falta buscar en el DOM de manera directa, porque al escribir las etiquetas HTML en JavaScript tenemos un acceso más directo y rápido, lo que se conoce como VDOM. Además una de las ventajas del VDOM es que solo volvemos a renderizar la parte que cambio, por lo que no debemos volver a renderizar toda la página como pasa con la manipulación del DOM.

## Ciclo de vida
Todas las aplicaciones que creemos, desde componentes hasta la combinación de estos tendrán un ciclo de vida. Desde que se inician en nuestro estado, habrán actualizaciones para finalmente morir, es decir, desaparecer dentro de la estructura del Virtual DOM.
Permite que nuestra aplicación tenga diferentes fases y entre ellas poder hacer diferentes eventualidades de lo que necesitamos.

## Estado
Cómo mantener una pieza de código que nos permita comunicarnos con diferentes estados de nuestra aplicación. Desde el evento desencadenado por la acción del usuario, cómo vamos a conservar cierta información para transmitir a un componente y cómo este va a reaccionar con esa información.
El uso del estado es clave para mantener o transmitir información entre componentes.

## Eventos
Estos eventos se desencadenan según las necesidades de nuestra aplicación: desde un click, mover el mouse, activar la página, etc.

## Hooks
Son otra manera de escribir los componentes con estado, si usar clases. No se pretenden reemplazar, sin embargo, usar funciones para los componentes puede facilitar el entendimiento de la aplicación.

Los hooks salieron en la versión 16.8 de React en Febrero de 2019. Son funciones especiales que existen en React que nos permiten manejar el ciclo de vida dentro de los componentes funcionales, esto hace que no sean necesarias las clases. Las clases pueden llegar a confundirnos, porque realmente no son clases como tal, son prototipos, y éstas además suponen un peor rendimiento a ti aplicación. Todos los hooks por convención empiezan con use. React te ofrece una serie de hooks de forma nativa, pero puedes usar hooks de librerías externas o incluso crear tus propios hooks.

## QUIZ: Introducción a React

### ¿Qué es el estado en React.js?
El lugar donde almacenamos y actualizamos dinámicamente información de los usuarios y la aplicación.

### ¿Por qué React.js trabaja con el Virtual DOM?
Porque es una copia del DOM real con la que puede hacer cálculos y comparaciones más rápido.

### ¿Por qué React.js recomienda usar JSX?
Porque es una sintaxis que combina JavaScript con XML, agiliza nuestro desarrollo y mejora la legibilidad de nuestro código.

### Al desarrollar el frontend de una aplicación podemos aplicar el patrón MVC o Modelo, Vista, Controlador. ¿De cuál capa / letra se encarga React.js?
Vista.
