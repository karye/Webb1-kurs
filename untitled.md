---
description: Träna på att använda div-boxen för att skapa en kontainer
---

# Skapa ett visitkort

## Resultat

![](.gitbook/assets/image%20%2851%29.png)

## Genomgång

* Hur använder man Chrome utvecklarverktyg

{% embed url="https://youtu.be/09XV2psDAZ4" %}



## Steg 1 - förberedelser - webbrot

* Skapa en mapp som heter **visitkort**
* Skapa en webbsida som heter **visitkort.html**
* Skapa en CSS-fil som heter **style.css**
* Skapa en mapp **bilder**

## Steg 2 - skapa HTML-sidan <a id="steg-2-skapa-html-sida"></a>

* Börja med grundkoden
* Fyll i alla HTML-element som bygger upp sidan

![](.gitbook/assets/image%20%2852%29.png)

## **Steg 3 - snygga till sidan med CSS** <a id="steg-3-snygga-till-sidan-med-css"></a>

### CSS-reglerna <a id="css-reglerna"></a>

* Infoga alla CSS-regler som motsvarar de taggar vi använder
* Skapa en ruta med **div**-elementet genom att låsa bredd och höjd

![](.gitbook/assets/image%20%2853%29.png)

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

