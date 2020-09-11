---
description: Träna på att använda div-boxen för att skapa en kontainer
---

# Skapa ett visitkort

## Resultat

![](.gitbook/assets/image%20%2851%29.png)

## Steg 1 - förberedelser - webbrot

* Skapa en mapp som heter **visitkort**
* Skapa en webbsida som heter **visitkort.html**
* Skapa en CSS-fil som heter **style.css**
* Skapa en mapp **bilder**

## Steg 2 - skapa HTML-sidan <a id="steg-2-skapa-html-sida"></a>

* Börja med grundkoden
* Fyll i alla HTML-element som bygger upp sidan

```markup
<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Min presentation</title>
    <link rel="stylesheet" href="./visitkort.css">
</head>
<body>
    <div>
        <h1>Karim Ryde</h1>
        <h2>Webblärare</h2>
        <p>Mingata 99<br>
        123 45 Stockholm</p>
    </div>
</body>
</html>
```

## **Steg 3 - snygga till sidan med CSS** <a id="steg-3-snygga-till-sidan-med-css"></a>

### CSS-reglerna <a id="css-reglerna"></a>

* Infoga alla CSS-regler som motsvarar de taggar vi använder
* Skapa en ruta med **div**-elementet genom att låsa bredd och höjd

```css
/* Enkel CSS-reset */


body {
    background: rgb(182, 182, 182);
}
div {
    width: 500px;
    height: 300px;

}
h1 {

}
h2 {

}
p {

}
```

### Välj två typsnitt

* Gå till [Google Fonts](https://fonts.google.com) och välj två typsnitt
  * Ett typsnitt för **&lt;h1&gt;** och **&lt;h2&gt;**
  * Ett typsnitt för **&lt;p&gt;**
* Ställ in texternas storlek med **font-size**

### Ställ in bakgrundsbilden

* Välj ut ett foto på [unsplash.com](https://unsplash.com/)
* Ladda ned fotot i mappen **bilder**
* Anpassa fotot storlek till ca 2000px bredd
* Använd **background-image** på **body**-elementet

### Anpassa mellanrum

* Använd **margin** på elementen

### Infoga en CSS-reset

* CSS-reset används för att göra lättare att koda en snygg sida

```css
/* Enkel CSS-reset */
html {
    box-sizing: border-box;
}
*, *:before, *:after {
    box-sizing: inherit;
}
body, h1, h2, h3, h4, h5, h6, p, ul {
    margin: 0;
    padding: 0;
}
```

