---
description: Använda <div> för att skapa en snygg ruta
---

# Skapa receptsida

## Resultat

![](../.gitbook/assets/image%20%2855%29.png)

## Genomgång



## Steg 1 - förberedelser - webbrot

* Skapa en mapp som heter **scones**
* Skapa en webbsida som heter **scones.html**
* Skapa en CSS-fil som heter **style.css**
* Skapa en mapp **bilder**

## Steg 2 - skapa HTML-sidan <a id="steg-2-skapa-html-sida"></a>

### Grundkoden

* Börja med grundkoden
* Fyll i alla HTML-element som bygger upp sidan

### Scones receptet

* Receptet hämtas från [http://www.scones.se/scones-med-apple-och-kanel](http://www.scones.se/scones-med-apple-och-kanel)

## **Steg 3 - snygga till sidan med CSS** <a id="steg-3-snygga-till-sidan-med-css"></a>

### CSS-reglerna <a id="css-reglerna"></a>

* Infoga först CSS-reset
* Infoga alla CSS-regler som motsvarar de taggar vi använder
* Skapa en ruta med **div**-elementet genom att låsa bredd och höjd

### Välj två typsnitt

* Gå till [Google Fonts](https://fonts.google.com) och välj två typsnitt
  * Ett typsnitt för **&lt;h1&gt;** och **&lt;p&gt;**
  * Ett typsnitt för **&lt;ul&gt;**
* Ställ in texternas storlek med **font-size**

### Ställ in bakgrundsbilden

* Välj ut ett foto på [unsplash.com](https://unsplash.com/)
* Ladda ned fotot i mappen **bilder**
* Anpassa fotot storlek till ca 2000px bredd
* Använd **background-image** på **body**-elementet
* Använd **margin** på elementen

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

