---
description: 'Träna på HTML tabell, och styla med CSS'
---

# Din veckomeny

## Resultatet

![](../.gitbook/assets/image%20%2831%29.png)

## Förberedelser - webbrot

* Skapa en mapp som heter "veckomeny"
* Skapa en webbsida som heter **meny.html**
* Skapa en CSS-fil som heter **style.css**
* Skapa en mapp **bilder**

## Genomgång

{% embed url="https://youtu.be/XG\_RicH7TLY" %}

{% embed url="https://youtu.be/6PZAfgb2ApU" %}

## Grundkoden för tabell

* Enklaste formen av tabell ser ut som följer:

```markup
<table>
  <tr>
    <td>John</td>
    <td>Doe</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Doe</td>
  </tr>
</table>
```

## Skapa tabellen

### Välj rätter från [https://www.ica.se/recept/buffe](https://www.ica.se/recept/buffe/)

![](../.gitbook/assets/image%20%2832%29.png)

### Skapa en första rad för veckodagarna

* Börja med vanliga celler **&lt;td&gt;**

![](../.gitbook/assets/image%20%2837%29.png)

### Skapa en till rad för rätterna

* Duplicera raden

![](../.gitbook/assets/image%20%2829%29.png)

### Skapa en 3:e rad för bilderna

* Skapa en ny rad celler
* För att komma åt bilden klicka på receptet 
* Högerklicka på bilden och välj **Spara som...** ned i mappen **bilder**
* Infoga sen bilderna med **&lt;img&gt;** i varje cell
* Omvandla första radens celler till kolumnrubriker **&lt;th&gt;**
* Infoga en tabellrubrik med **&lt;caption&gt;**

![](../.gitbook/assets/image%20%2838%29.png)

## Styla tabellen med CSS

### Infoga alla tomma CSS-regler

![](../.gitbook/assets/image%20%2833%29.png)

### Styla tabellen och texten

* Välj 2 typsnitt från [Google Font](https://fonts.google.com/)
* Styla rubrik och text med typsnitten
* Ställ in tabellens bredd
* Och bildernas bredd för att de inte skall bli så stora
* Välj en bakgrundsfärg på sidan

![](../.gitbook/assets/image%20%2836%29.png)

### Styla cellerna

* Gör cellerna lite luftigare med CSS **padding**
* Lägg till kanter med **border**

![](../.gitbook/assets/image%20%2834%29.png)

