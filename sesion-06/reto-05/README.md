# Cambiando el contenido del carousel

## REQUISITOS


- Tener Git Bash si usas Windows.
- Conocer como instalar Bootstrap.

Una vez revisado la estructura del ejemplo de Bootstrap, debemos de cambiar el contenido del carousel para que contenga lo que nosotros teníamos. No te preocupes si los estilos no quedan perfecto, de momento solo nos enfocaremos en que en vez de imágenes rotas girando en el carousel, debe de ser el contenido que nosotros estamos esperando ver al final.

>**TIP**
>
>Recuerda en qué sección del código del ejemplo se ponen los elementos del carousel para que pongas el código que hemos comentado previamente. Por último, recuerda que nosotros solo teníamos las imágenes y texto de uno de los elementos del carousel, usa tus habilidades del manejo de las herramientas de desarrollo del desarrollo para obtener las imágenes.

<details>
  <summary>Posible solución</summary>

Se debe de reemplazar las imágenes dentro de cada contenedor con clase carousel-item por el contenido que tenemos comentado.

```html
<div class="carousel-inner">
  <div class="carousel-item active">
    <div class="card">
      <div class="card-media">
        <figure>
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/05/profile-headshot-square.png"
            alt="Everly worker"
          />
        </figure>
        <div class="company">
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/05/everly_logo_blue_v3_x60@2x.png"
            alt="Everly"
          />
        </div>
      </div>
      <div class="card-body">
        <h4>Everly</h4>
        <h3>
          Early-Stage CPG Brand Increases Lead Conversion 20x, Ecommerce Revenue
          20%
        </h3>
        <div class="results">
          <img
            src="https://getmatcha.com/wp-content/themes/getmatcha/img/icon_cart.png"
            alt="Cart icon"
          />
          <p>22% of monthly revenue influenced by content</p>
        </div>
      </div>
      <div class="card-footer">
        <button>See Case Study</button>
      </div>
    </div>
  </div>
  <div class="carousel-item">
    <div class="card">
      <div class="card-media">
        <figure>
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/05/profile-headshot-square.png"
            alt="Everly worker"
          />
        </figure>
        <div class="company">
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/05/everly_logo_blue_v3_x60@2x.png"
            alt="Everly"
          />
        </div>
      </div>
      <div class="card-body">
        <h4>Everly</h4>
        <h3>
          Early-Stage CPG Brand Increases Lead Conversion 20x, Ecommerce Revenue
          20%
        </h3>
        <div class="results">
          <img
            src="https://getmatcha.com/wp-content/themes/getmatcha/img/icon_cart.png"
            alt="Cart icon"
          />
          <p>22% of monthly revenue influenced by content</p>
        </div>
      </div>
      <div class="card-footer">
        <button>See Case Study</button>
      </div>
    </div>
  </div>
  <div class="carousel-item">
    <div class="card">
      <div class="card-media">
        <figure>
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/05/profile-headshot-square.png"
            alt="Everly worker"
          />
        </figure>
        <div class="company">
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/05/everly_logo_blue_v3_x60@2x.png"
            alt="Everly"
          />
        </div>
      </div>
      <div class="card-body">
        <h4>Everly</h4>
        <h3>
          Early-Stage CPG Brand Increases Lead Conversion 20x, Ecommerce Revenue
          20%
        </h3>
        <div class="results">
          <img
            src="https://getmatcha.com/wp-content/themes/getmatcha/img/icon_cart.png"
            alt="Cart icon"
          />
          <p>22% of monthly revenue influenced by content</p>
        </div>
      </div>
      <div class="card-footer">
        <button>See Case Study</button>
      </div>
    </div>
  </div>
</div>
```

Y luego cambiar el texto e imágenes de los siguientes elementos en el carousel:

```html
<div class="carousel-inner">
  <div class="carousel-item active">
    <div class="card">
      <div class="card-media">
        <figure>
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/05/profile-headshot-square.png"
            alt="Everly worker"
          />
        </figure>
        <div class="company">
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/05/everly_logo_blue_v3_x60@2x.png"
            alt="Everly"
          />
        </div>
      </div>
      <div class="card-body">
        <h4>Everly</h4>
        <h3>
          Early-Stage CPG Brand Increases Lead Conversion 20x, Ecommerce Revenue
          20%
        </h3>
        <div class="results">
          <img
            src="https://getmatcha.com/wp-content/themes/getmatcha/img/icon_cart.png"
            alt="Cart icon"
          />
          <p>22% of monthly revenue influenced by content</p>
        </div>
      </div>
      <div class="card-footer">
        <button>See Case Study</button>
      </div>
    </div>
  </div>
  <div class="carousel-item">
    <div class="card">
      <div class="card-media">
        <figure>
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/08/0.jpg"
            alt="Seato Summit worker"
          />
        </figure>
        <div class="company">
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/08/SeatoSummitLogo.png"
            alt="Seato Summit Logo"
          />
        </div>
      </div>
      <div class="card-body">
        <h4>Sea to Summit</h4>
        <h3>
          Sea to Summit’s Ecommerce Site Traffic Climbs 189%, New Subscribers
          820%
        </h3>
        <div class="results">
          <img
            src="https://getmatcha.com/wp-content/themes/getmatcha/img/icon_audiences.png"
            alt="Audience icon"
          />
          <p>500% increase in traffic from social media</p>
        </div>
      </div>
      <div class="card-footer">
        <button>See Case Study</button>
      </div>
    </div>
  </div>
  <div class="carousel-item">
    <div class="card">
      <div class="card-media">
        <figure>
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/06/matt-and-margaret_headshot.png"
            alt="Mambe workers"
          />
        </figure>
        <div class="company">
          <img
            src="https://getmatcha.com/wp-content/uploads/2019/06/mambe-logo-1.png"
            alt="Mambe"
          />
        </div>
      </div>
      <div class="card-body">
        <h4>Mambe Waterproof Blankets</h4>
        <h3>
          How Mambe Increased Conversions by 327%, Reduced CPL by 60%
        </h3>
        <div class="results">
          <img
            src="https://getmatcha.com/wp-content/themes/getmatcha/img/icon_target.png"
            alt="Target icon"
          />
          <p>+327% more popup conversions at a 60% lower cost</p>
        </div>
      </div>
      <div class="card-footer">
        <button>See Case Study</button>
      </div>
    </div>
  </div>
</div>
```

Luego de aplicado los cambios debería quedarr algo similar a:

![1c](../assets/1c.png)

Con esto, podemos detectar ciertos detalles que debemos corregir en la apariencia:

La flecha de siguiente se sale de la tarjeta y probablemente no la necesitamos.
Los indicadores no se logran ver aunque no los hemos borrado del código.
La tarjeta tiene espacios en blanco en la parte superior e inferior.
El color del botón para ver el caso de estudio tiene un color de fondo que antes no tenía.
Procedamos a corregir estos detalles 😎.

  </details>