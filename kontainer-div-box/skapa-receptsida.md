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

```text
Äppelscones
Portioner: 12-15 scones
Tid: 15 minuter + 15 minuter i ugn
2,5 dl (150 g) vetemjöl
1,5 dl (80 g) dinkelfullkornsmjöl eller grahamsmjöl
0,5 dl strösocker
2 tsk bakpulver
1 tsk kanel
1 krm salt
75 g kylskåpskallt smör
1 medelstort äpple, cirka 125 g
1 ägg
```

## **Steg 3 - snygga till sidan med CSS** <a id="steg-3-snygga-till-sidan-med-css"></a>

### CSS-reglerna <a id="css-reglerna"></a>

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

### Infoga en CSS-reset

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

