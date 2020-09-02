---
description: Träna radbrytning och att styla med CSS
---

# Skapa en sida "All You Need is Love" av Beatles

## Förberedelser - webbrot

* Vi skall skapa en webbsida om Beatles låten "All You Need is Love"
* Skapa en **mapp** som heter "love"

## Videor

{% embed url="https://youtu.be/rXr3vq-iGns?list=PLWjCJDeWfDdc0Sp\_DinOWnodw3KnWCwc1" %}

{% embed url="https://youtu.be/JuwYg\_54b6c" %}

{% embed url="https://youtu.be/qmMtoBrg5gI" %}



## **Klistra in låttexten**

* Hämta texten från [http://www.lyricsfreak.com/b/beatles/all+you+need+is+love\_10026698.htm](http://www.lyricsfreak.com/b/beatles/all+you+need+is+love_10026698.html)

![](.gitbook/assets/image%20%2814%29.png)

### **Formatera låttexten**

* Använd  **&lt;h1&gt;** till rubriken
* Använd **&lt;p&gt;** till hela versen
* Men en radbrytning behövs för att läsa låten rätt **&lt;br&gt;**, se bilden:

![](.gitbook/assets/image%20%2828%29.png)

## **Infoga och formatera Wikipedia-text om låten**

* Text om låten finns på Wikipedia: [https://sv.wikipedia.org/wiki/All\_You\_Need\_Is\_Love](https://sv.wikipedia.org/wiki/All_You_Need_Is_Love)

![](.gitbook/assets/image%20%2813%29.png)

### **Infoga källor för att tacka upphovsmännen/kvinnor**

* Texterna har vi kopierat, så då måste vi berätta vad de kommer ifrån

![](.gitbook/assets/image%20%285%29.png)

## **Snygga till sidan med CSS**

### Skapa en CSS-sida

* Skapa en ny fil som heter **style.css**
* Infoga tre CSS-regler som motsvarar de taggar vi använder

![](.gitbook/assets/image%20%2821%29.png)

### Skapa CSS-regler 

* Börja med att välja typsnitt på Google Fonts: [https://www.google.com/fonts](https://www.google.com/fonts#).

![](.gitbook/assets/image%20%2822%29.png)

* Välj två typsnitt
  * Ett "Display" för rubriken
  * Ett "Serif" för stycken

![](.gitbook/assets/image%20%2826%29.png)

* Koden för att bädda in typsnitten

![](.gitbook/assets/image%20%286%29.png)

```markup
<link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Noto+Serif&display=swap" rel="stylesheet">
```

* Klistra länkkoden i **&lt;head&gt;:**

![](.gitbook/assets/image%20%287%29.png)

### Fyll på reglerna

* Klistra in CSS för typsnitt
* Välj textstorlek
* Välj textfärg

![](.gitbook/assets/image%20%2815%29.png)

