# Curso de Fontend Developer

Este es el repositorio del curso de frontend developer de Platzi con Estefany Aguilar. Es un curso práctico para profundizar en aspectos más profesionales. Por tanto, se necesita tener conocimientos básicos de HTML y CSS. En este curso no se usa JavaScript.

Se trata de maquetar un proyecto que recibimos con unas especificaciones de pantallas, colores, tipografías, iconos e imágenes. El proyecto incluye las pantallas de sobremesa y de móvil.

## Preparación del entorno

Creamos en nuestra carpeta de trabajo un archivo básico, `html` con el nombre de `index.html`.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

En este archivo colocaremos los enlaces a las fuentes que usaremos, en este caso _Quicksand_. Estos enlaces los proporciona _Google Fonts_.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat&family=Quicksand:wght@300;500;700&display=swap"
      rel="stylesheet"
    />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

Aquí, también colocamos los estilos básicos para usar las fuentes y definimos los colores del proyecto.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat&family=Quicksand:wght@300;500;700&display=swap"
      rel="stylesheet"
    />
    <title>Document</title>
    <style>
      :root {
        --white: #fff;
        --black: #000;
        --very-light-pink: #c7c7c7;
        --text-input-field: #f7f7f7;
        --hospital-green: #acd8b2;
      }
      body {
        font-family: "Quicksand", sans-serif;
      }
    </style>
  </head>
  <body></body>
</html>
```

Obtenemos los iconos y logos especificados y guardamos en sus carpetas correspondientes.

ya tenemos todo listo para empezar a maquetar nuestro proyecto. Cada pantalla se maquetará en un único archivo que incluirá los estilos.
