# Reto 04 - Volviendo la barra de navegación fija

## REQUISITOS
- Tener Git Bash si usas Windows.
- Saber que es responsive design

<br/>

## INSTRUCCIONES

Recuerdas que la barra de navegación tenía un posicionamiento fijo para que esta
nos acompañe cuando hagamos scroll dentro de la página. ¿Has notado que este
comportamiento ya no está presente? ¿Puedes solucionarlo?

<br/>

> TIP: Al ser este un caso común, Bootstrap tiene clases utilitarias que pueden ayudar a lograr este comportamiento. Revisa [esta sección de navbar de la documentación](https://getbootstrap.com/docs/4.4/components/navbar/#placement) para que te des una idea de qué podrías usar.

<br/>

<details>
  <summary>Posible solución</summary>

La clase `fixed-top` de Bootstrap nos ayuda a solucionar este problema:

```html
<nav class="navbar navbar-expand-lg navbar-light fixed-top">
  <!-- Contenido de la barra de navegación -->
</nav>
```

</details>

<br/>

[Siguiente](../Ejemplo-05)