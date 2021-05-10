# Reto 3.1 - Grid 2 filas con alto de `330px`

## REQUISITOS
- Tener Git Bash si usas Windows.
- Tener conocimientos de CSS (Flexbox)
- Conocer el modelo de caja 

## INSTRUCCIONES

Regresa la cantidad de columnas a las que realmente necesitamos (2) y agrega
la cantidad de filas que usaremos (2) teniendo en cuenta que el alto será de
`330px`. Una vez logrado, ¿cómo se te ocurre que podrías usar la unidad de `fr`
para indicar el alto de las filas?

<br/>

<details>
  <summary>Posible Solución</summary>

```css
.features {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(2, 330px);
}
```

Una forma de poder usar la unidad `fr` para asignar el alto de las filas sería
indicando un tamaño fijo al elemento contenedor, en nuestro caso, podríamos 
hacer:

```css
.features {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  height: 660px;
  grid-template-rows: repeat(2, 1fr);
}
```

</details>

<br/>

# Reto 3.2 (Opcional) - Grid con 2 filas y 2 columnas

## REQUISITOS
- Tener Git Bash si usas Windows.
- Tener conocimientos de CSS (Flexbox)
- Tener conocimientos de CSS (Gid)
- Conocer el modelo de caja 

## INSTRUCCIONES

Como en la mayoría de propiedades de CSS, existen muchos atajos para poner
propiedades relacionadas en una sola. Las columnas y filas de CSS Grid no son la
excepción, por lo cual, este reto consiste en obtener el mismo resultado de las
columnas y filas del grid usando la propiedad de atajo.


<details>
  <summary>Posible Solución</summary>

```css
.features {
  display: grid;
  grid-template: repeat(2, 1fr) / repeat(2, 330px);
}
```

</details>

<br/>

[Siguiente](../reto-04)