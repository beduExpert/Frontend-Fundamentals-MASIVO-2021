## Reto 05 - Cambia los colores

Los colores que van a aplicar son los siguientes:

- Texto que va debajo del título: `#46484c`
- Texto promocional: `#8b8b8bcc`
- Texto del botón: `#fff`

<br/>

Ahora te toca buscar, ¿qué propiedad usarías para cambiar el color de fondo?
¿Qué selector usarías para cambiar el color de fondo de toda la página?

- Color de fondo de la página: `#fffbf7`
- Color de fondo del botón: `#025157`

<br/>

<details><summary>Posible solución</summary>
<p>

```html
<head>
    <title>Matcha</title>
    <!-- Desde el mismo html -->
    <style>
        body {
            background-color: #fffbf7;
        }

        h1 {
            color: #46484c;
            text-align: center;
        }

        p {
            color: #8b8b8bcc;
            font-family: verdana;
            font-size: 20px;
        }

        button {
            color: #fff;
            background-color: #025157;
        }
    </style>
    <!-- Desde archivo externo -->
    <link rel="stylesheet" href="styles.css">
</head>
```

</p>
</details>

<br/>

[Siguiente](../Ejemplo%2006)