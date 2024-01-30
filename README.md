# <h1  style="color: #2878f0;"> Figma Library 📚</h1>

Esta es una librería creada por tu coach [keyner de la hoz](https://github.com/Mp-keyner) que te permite integrar imágenes SVG en tu sitio web para que puedas replicar la pagina de [Figma Store](https://store.figma.com/). Además, ofrece algunas funcionalidades adicionales, como animaciones para una imagen específica 'img6' y la generacion de colores aleatorios del footer y imagenes aleatorias, que tiene el footer de [Figma Store](https://store.figma.com/).

## <h2 style="color: #2878f0;">Instalación</h2>

Para utilizar esta librería, simplemente agrega el siguiente link de estilos y script en el head de tu documento HTML:

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- ... -->
    <link
      rel="stylesheet"
      href="https://mp-keyner.github.io/figma/index.css"
    />
    <script src="https://mp-keyner.github.io/figma/index_Library.js"></script>
  </head>
  <body>
    <!-- ... -->
  </body>
</html>
```

## <h2 style="color: #2878f0;">Integración de Imágenes SVG</h2>

Para integrar una de la imagenes SVG en tu página, agrega un **div** con la clase **"img"** y un número del 1 al 10, por ejemplo **"img1"**:

```html
<div class="img1"></div>
```

Por defecto, la imagen SVG se ajustará al <span style="color: #2878f0;">**100% del contenedor**</span>. Si deseas cambiar el tamaño de la imagen, simplemente ajusta el tamaño del div con la clase correspondiente (por ejemplo, ".img1").

## <h2 style="color: #2878f0;">Animaciones para la Imagen 6</h2>

La imagen "img6" tiene animaciones especiales. Para activarlas, asegúrate de haber incluido el link de estilos en el head de tu documento, como se mostró en la sección de Instalación.

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- ... -->
    <link
      rel="stylesheet"
      href="https://mp-keyner.github.io/Library/index.css"
    />
  </head>
  <body>
    <!-- ... -->
  </body>
</html>
```

## <h2 style="color: #2878f0;">Footer Figma Store</h2>

Para agregar un footer con las funcionalidades de la pagina de Figma Store copia y pega la sigiente estructura:

```html
<footer id="footer">
  <div id="randomElement"></div>
</footer>
```

Al recargar la página, el color y la imagen cambiarán, y nunca coincidirán.

¡Listo! Ahora puedes disfrutar de las funcionalidades de esta librería y ahorrar mucho tiempo.

**si tienes problemas solo escribeme y te ayudo**

---

Creado por [Steam Academy](https://www.steamacademy.com.co/) bajo la superbision de [Keyner de la hoz](https://github.com/Mp-keyner)
