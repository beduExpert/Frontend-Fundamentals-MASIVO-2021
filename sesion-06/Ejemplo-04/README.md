# Ej. 04 - Revisando el responsive del navbar

Si activamos el emulador de responsive para nuestra web veremos que un
comportamiento diferente sucede en nuestra barra de navegación:

![Responsive navbar mostrándose otra vez](../assets/responsive-navbar-2.png)

Notaremos que ahora tenemos una especie de ícono (comunmente llamado
_menú hamburguesa_) que al darle click debería de mostrarnos el menú, pero dicha
característica aun no funciona. ¿A qué se puede deber?

```html
<body>
  <!-- Todo el código de nuestro HTML viene aquí -->
  <script
    src="https://code.jquery.com/jquery-3.4.1.slim.min.js"
    integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n"
    crossorigin="anonymous"
  ></script>
  <script
    src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
    integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
    crossorigin="anonymous"
  ></script>
  <script
    src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"
    integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6"
    crossorigin="anonymous"
  ></script>
</body>
```

<br/>

> TIP: Si quieres conocer los fundamentos de porqué es mejor ingresar la etiqueta
`<script></script>` antes de cerrar el body del HTML, puedes leer esta
[pregunta y respuesta de Stack Overflow](https://es.stackoverflow.com/questions/25088/cu%C3%A1l-es-el-mejor-lugar-para-colocar-los-tag-scripts-src-en-html).

<br/>

[Siguiente](../reto-04)