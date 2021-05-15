# Reto 02 - Agregando segunda y tercera fila de características de Matcha

## REQUISITOS
- Tener Git Bash si usas Windows.
- Tener una cuenta de Netifly

## INSTRUCCIONES

Genial, ahora que ya hemos visto como distribuir en 2 columnas las
características principales de Matcha, agrega la segunda fila para terminar esta sección.

<br/>

<details>
  <summary>Posible solución</summary>

  <br/>

En este caso tenemos que agregar 2 celdas a la segunda fila y ponerle los mismos
estilos a las imágenes y las celdas para que queden distribuidas tal cual las
primeras:

```html
<table
  style="width: 100%; max-width: 600px; text-align: center; background-color: #fffbf7; color: #025157;"
>
  <tr>
    <!-- Aquí está el logo de Matcha -->
  </tr>
  <tr>
    <!-- Aquí está la imagen descriptiva de Matcha -->
  </tr>
  <tr>
    <!-- Aquí está el texto de bienvenida a Matcha -->
    <td>
      <main class="container">
        <header class="header">
          <h1>Hi, there</h1>
          <p style="font-size: 18px; padding: 0px 20px 0px 20px; color: #000000;">
            Thanks for cheking out Marcha, Instantly publish articles, drive more traffic, grow
            your email list, and see your blog's impact on sales.
          </p>
          <a href="https://getmatcha.com/">
            <button style="
            background-color: #025157;
            padding: 15px;
            font-weight: 600;
            margin-bottom: 20px;
            color: #ffffff;">EXPLORE MATCHA</button>
            </button>
      </main>
    </td>
  </tr>
  <tr>
    <!-- Aquí irá las características que Matcha provee -->
    <td
      style="
        border-top: 1px solid #999999d1;
        border-bottom: 1px solid #999999d1;
        padding-top: 35px;
        padding-bottom: 35px;
      "
    >
      <table
        style="
          text-align: center;
          width: 100%;
          color: #025157;
          font-family: Arial, Helvetica, sans-serif;
        "
      >
        <tr>
          <td style="width: 50%">
            <img
              style="height: 300px;"
              src="https://getmatcha.com/wp-content/themes/getmatcha/img/ill-publish.png"
              alt="Publish"
            />
            <h2>Publish</h2>
          </td>
          <td style="width: 50%">
            <img
              style="height: 300px;"
              src="https://getmatcha.com/wp-content/themes/getmatcha/img/ill-promote.png"
              alt="Promote"
            />
            <h2>Promote</h2>
          </td>
        </tr>
        <tr>
          <td>
            <img
              style="height: 300px;"
              src="https://getmatcha.com/wp-content/themes/getmatcha/img/ill-capture.png"
              alt="Capture"
            />
            <h2>Capture</h2>
          </td>
          <td>
            <img
              style="height: 300px;"
              src="https://getmatcha.com/wp-content/themes/getmatcha/img/ill-measure.png"
              alt="Measure"
            />
            <h2>Measure</h2>
          </td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <!-- Aquí irá el pie de página con enlaces a redes sociales -->
  </tr>
</table>
```

</details>

<br/>

[Siguiente](../reto-03)