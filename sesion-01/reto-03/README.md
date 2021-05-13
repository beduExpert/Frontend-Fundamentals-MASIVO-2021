# Reto 03 - Creando mi formulario

1. Utiliza los elementos que vimos para crear un formulario donde pueda poner: Nombre, Apellido, Edad, Email y Contraseña.

<br/>

> TIP: No dudes en googlear o preguntar a tus compañeros como puedes ocultar
> los caracteres cuando sea contraseña, la edad solo acepte números.

<br/>

<details><summary>Posible solución</summary>
<p>

```html
<form>
    <label for="name">Nombre</label>
    <input type="text" id="name" name="fname"><br><br>
    <input type="text" id="lastname" name="lastname" placeholder="Apellido"><br><br>
    <input type="number" id="age" name="age" placeholder="Edad" min="18" max="35"><br><br>
    <input type="email" id="email" name="email" placeholder="Correo"><br><br>
    <input type="password" id="password" name="password" placeholder="Contraseña"><br><br>
    <button type="submit">Enviar</button>
</form>
```

</p>
</details>

<br/>

[Siguiente](../reto-04)