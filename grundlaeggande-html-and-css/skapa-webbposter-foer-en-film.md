---
description: Träna på bakgrundsbilder och margin/padding
---

# Skapa webbposter för en film

## **Resultatet**

![](../.gitbook/assets/image%20%2812%29.png)

## Förberedelser - webbrot

* Skapa en mapp som heter "space-odyssey"
* Skapa en webbsida som heter **space.html**
* Skapa en CSS-fil som heter **style.css**
* Skapa en mapp **bilder**

## Genomgång

{% embed url="https://youtu.be/pF-AeeBIvzo" %}



{% embed url="https://youtu.be/1PxUbAFQKoY" %}

## **Bilden på jorden**

### **Ladda ned fri bild från Wikipedia**

* url: [https://upload.wikimedia.org/wikipedia/commons/9/97/The\_Earth\_seen\_from\_Apollo\_17.jpg](https://upload.wikimedia.org/wikipedia/commons/9/97/The_Earth_seen_from_Apollo_17.jpg)

[![Earth.jpg](https://twiggy.smutje.se/images/thumb/Earth.jpg/400px-Earth.jpg)](https://twiggy.smutje.se/index.php/Fil:Earth.jpg)

### **Bearbeta bilden i Photoshop**

* Öppna bilden i Photoshop och förminska den till 600px bredd

## **Skapa webbsidan**

![](../.gitbook/assets/image%20%2827%29.png)

### **CSS-regler**

* Vi använder bilden som bakgrundsbild
* Texten som ligger i **&lt;h1&gt;** får också lite CSS för utseendet

```css
body {
    background: #000 url(earth.jpg) no-repeat 750px 0;
    background-size: 1000px 1000px;
}
h1 {
    font: bold 140px sans-serif;
    color: #FFF;
    width: 500px;
}
```

### **Hur man styr textens placering**

* CSS margin kan användas till att flytta texte**n**

### **CSS shorthand**

* Kolla på [https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand\_properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties)

## **Variationer**

### **Bakgrundsbilden ovan**

```css
body {
    background: #000 url(earth.jpg) no-repeat 50px -750px; 

```

![](../.gitbook/assets/image%20%283%29.png)

### **Bakgrundsbilden nedan**

```css
body {
    background: #000 url(earth.jpg) no-repeat 50px 600px;

```

![](../.gitbook/assets/image%20%282%29.png)

