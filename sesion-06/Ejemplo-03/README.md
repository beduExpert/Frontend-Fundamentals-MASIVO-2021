# Ej. 03 - Recuperando los estilos de la barra de navegación

Resulta que Bootstrap utiliza una clase llamada navbar para ponerle sus propios estilos, y nosotros coincidentemente usamos el mismo hombre, sin embargo, al momento de nosotros poner los estilos de Bootstrap antes que el nuestro (al momento que pusimos las etiquetas <link /> en el HTML), nuestros estilos terminan predominando sobre los de Bootstrap a pesar de tener el mismo nombre.

<br/>

Eliminando el ancho de la clase `.navbar` quedaría así:

```css
.navbar {
  text-align: center;
  color: #025157;
  font-weight: 500;
   background-color: black; 
}

.navbar {
  text-align: center;
  color: #025157;
  font-weight: 500;
   /* background-color: black;  */
}
```

> TIP: Si deseas saber que otras clases relacionadas con los colores de fondo existen en Bootstrap, puedes consultar [esta sección de la documentación](https://getbootstrap.com/docs/4.4/utilities/colors/#background-color).

<br/>

Ahora procedamos a corregir el alineamiento del menú de navegación, ya que
aparece apegada al logo en la parte izquierda de la pantalla y debería de estar
alineado al centro del espacio disponible del contenedor. Para esto, debemos de
modificar los estilos de la etiqueta `<ul></ul`. Dicha etiqueta en estos
momentos tiene 2 clases (`navbar-nav` y `mr-auto`), la primera clase `navbar-nav`
es importante para poder indicar que los elementos de dicha lista son los que
conformarán el menú de navegación, mientras que la segunda clase `mr-auto` indica
que dicha lista debe tener un margen derecho automático, y dado que los elementos
de la lista Bootstrap les asigna un `display: block;` podemos alinear su
contenido aplicando un margen automático a cada lado, Bootstrap nos permite hacer
dicho comportamiento a través de una clase llamada `mx-auto`. Por lo tanto,
reemplazaremos la clase `mr-auto` por `mx-auto`:

```html
<ul class="navbar-nav mx-auto">
  <!-- lista del menú de navegación -->
</ul>
```

Resultando en:

![Menú de navegación centrado](../assets/navbar-centered.png)

<br/>

> TIP: Si deseas saber qué otras clases utilitarias relacionas a espaciado que tiene Bootstrap para ti, puedes revisar [esta sección de la documentación](https://getbootstrap.com/docs/4.4/utilities/spacing/).

<br/>

[Siguiente](../reto-03)