# Fonts

## **Introducción**

Edita un fichero de estilos para aplicarle .myTitle una fuente diferente. Estas fuentes las podemos obtener de Google Fonts.

[Google Fonts](https://fonts.google.com/)

## **Autoevaluación**

- Escoger una fuente de Google Fonts.
- Aplicar el font-family correspondiente a la clase .myTitle.

## **Html code**

```html
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />

    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Delicious+Handrawn&display=swap"
      rel="stylesheet"
    />

    <link rel="stylesheet" type="text/css" href="./styles.css" />
    <title>Fuentes en linea</title>
  </head>
  <body>
    <h1 class="myTitle">Mi nueva fuente</h1>
  </body>
</html>
```

## **Css code**

```css
.myTitle {
  font-family: "Delicious Handrawn", cursive;
}
```
