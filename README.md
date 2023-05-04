![Proyecto Tienda de porductos deportivos](https://raw.githubusercontent.com/raquelgm88/easy-sports-shop/main/src/images/readme.png)

# Tienda online de productos deportivos

¡Hola! Este proyecto es el resultado de la evaluación final del módulo 1 del **Bootcamp de Programación Web de Adalab**, de la promoción **Salas**. Desarrollado con HTML5 y CSS3 (SASS).

## Requisitos

Para desarrollar este proyecto había que cumplir con una serie de criterios:

1. El botón del menú (en la esquina superior izquierda) debe estar fijo en la parte superior de la pantalla y no debe desaparecer al hacer scroll. El icono de la hamburguesa debe ser un enlace a la página de Adalab.

2. El primer módulo (hero - Hasta un 50% de descuento) debe estar maquetado con Flexbox y debe ocupar tanto como el alto de la ventana del navegador.

3. El segundo módulo (Conecta Contigo) se puede maquetar usando las propiedades de CSS que se deseen.

4. En el tercer módulo (Año nuevo, movimientos nuevos) los tres elementos del listado deben estar maquetados con CSS Grid en todos los tamaños de pantalla en los que se necesite.

5. El cuarto módulo (footer) se debe maquetar usando flexbox. Todos los textos de la columna "ZAPATILLAS" y todos los textos de la columna "TWITTER" deben ser enlaces a la página de Adalab.

Además, había que resolver varias interacciones. A parte de las propuestas, yo he hecho que los botones de "Comprar" y "Empezar ahora" funcionen como links a a página de Adalab.

1. El botón de flecha del primer módulo (el hero) debe enlazar a la sección "Año nuevo, movimientos nuevos".

2. El botón de flecha que está sobre el footer debe enlazar al inicio de la página.

3. Todos los links del pie deben ir a https://adalab.es.

4. Como BONUS, investigar: En el :hover de los botones ("Comprar" y "Empezar ahora") se debe incluir una
   propiedad transform que dejamos a vuestra elección (y, como idea, hacer la transform junto con
   transition, para investigar la propiedad transition).

## Estructura del proyecto

1. Un header, con position: fixed maquetado con Flexbox. Al hacer scroll siempre se queda fijo el botón del menú en la esquina superior izquierda.

2. Un body, en el que hay diferenciadas tres secciones:

- Una image hero maquetada con Flexbox, con un botón que al clickar nos lleva a la tercera sección.
- Una sección "conect-yourself" ,maquetada con Flexbox con un botón de "Comprar" que nos redirige a la página de Adalab.
- Una tercera sección, "new-year", maquetada con Grid con otro botón que enlaza a la web de Adalab. Todos los elementos se muestran en una sola columna en la versión mobile, y en las versiones de tablet y desktop los tres articles se muestran en una sola fila.
- He utilizado la pseudoclase hover en los botones "Comprar" y "Empezar ahora" de las secciones segunda y tercera poniendo la propiedades transform: scale y transform: rotate para, y una transition: transform en sus respectivas clases para indicar la duración de las transiciones.

3. Un footer maquetado con Flexbox con un botón en la parte superior, colocado con la propiedad translate y que redirige a la parte superior de la página. Cada elemento de los dos nav nos enlaza a la web de Adalab. En la versión móvil están los tres bloques del footer en columna, y en las versiones de tablet y desktop se distribuyen en tres columnas, en las que he usado la propiedad order para cambiar cada bloque de elementos de lugar según la maqueta dada.

## Herramientas utilizadas

- HTML5
- CSS3, SCSS
- NPM
- NodeJS
- Gulp
- Git

## Cómo arrancar el proyecto

Necesitas tener instalado [Node JS](https://nodejs.org/en) para poder arrancar este proyecto.

1. Instala las dependecias locales ejecutando en la terminal el comando:

```
npm install
```

2. Arranca el proyecto ejecutando a continuación en la terminal:

```
npm start
```

Se abrirá [http://localhost:3000 ](http://localhost:3000)para ver el proyecto en el navegador en modo desarrollo.
