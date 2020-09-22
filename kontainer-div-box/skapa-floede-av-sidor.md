---
description: Hur man enkelt skapar flera sidor med samma grundsstilar.
---

# Skapa flera sidor

## Resultat

![arbete1.html](../.gitbook/assets/image%20%2856%29.png)

![arbete2.html](../.gitbook/assets/image%20%2855%29.png)

## Genomgång

{% embed url="https://youtu.be/Oo1FhkvshRo" caption="Hur man använder mönster på snyggt sätt" %}

## Steg 1 - förberedelser - webbrot

* Skapa en mapp som heter **arbete**
* Skapa en webbsida som heter **arbete1.html**
* Skapa en CSS-fil som heter **style.css**
* Skapa en mapp **bilder**

## Steg 2 - skapa HTML-sidan <a id="steg-2-skapa-html-sida"></a>

{% hint style="warning" %}
Viktigt! Skapa _bara_ **arbete1.html**  
De andra sidorna skapas senare
{% endhint %}

### Grundkoden till arbete1.html

* Börja med grundkoden
* Fyll i alla HTML-element som bygger upp sidan
* Länka pil-framåt till sidan efter: **arbete2.html**

### Dikten av Ulf Lundell

```text
Arbete av Ulf Lundell

Om jag inte arbetade
vad i helvete skulle jag
göra då?

Knarka kanske
Men det är ju också ett jobb
Ett jävla flängande med
inbrott och själva köpandet av
skiten och sen om igen
så det utesluter vi

Jag kunde leva på andra
men risken finns ju
att också det är ett rätt så hårt
arbete

Jag kunde lägga in mig på
sjukhus och bara ligga där
blickstilla
men jag kan ge mej fan på
att det också med tiden skulle kännas som ett
arbete

Så jag arbetar väl på då
Jag har väl inget val

Men någonting säger mej
att Gud från början
inte alls menade att vi skulle
syssla med nåt satans
arbete
```

![](../.gitbook/assets/image%20%2863%29.png)

## **Steg 3 - snygga till sidan med CSS** <a id="steg-3-snygga-till-sidan-med-css"></a>

### CSS-reglerna <a id="css-reglerna"></a>

* Infoga överst CSS-reset
* Infoga alla CSS-regler som motsvarar de taggar vi använder
* Skapa en ruta med **div**-elementet genom att låsa bredd och höjd

### Välj typsnitt

* Gå till [Google Fonts](https://fonts.google.com) och välj två typsnitt
  * Ett typsnitt för **&lt;h1&gt;** och **&lt;h2&gt;**
  * Ett typsnitt för **&lt;p&gt;**
  * Ett typsnitt för **&lt;ul&gt;**
* Ställ in texternas storlek med **font-size**

### Ställ in bakgrundsbilden på första sidan

* Välj ut ett mönster som kan repeteras från [https://www.freepik.com/free-photos-vectors/seamless-pattern](https://www.freepik.com/free-photos-vectors/seamless-pattern)
* Ladda ned mönstret i mappen **bilder**
* Använd **background-image** på **body**-elementet
* Använd padding, **margin** och **border** på elementen

## Skapa nu nästa HTML-sida

{% hint style="warning" %}
1. Spara **arbete1.html**
2. I menyn **File** välj **Save as...**
3. Spara nu en ny kopia **arbete2.html**
{% endhint %}

### Ställ in en ny bakgrund mha class

* Välj ut ett till mönster som kan repeteras från [https://www.freepik.com/free-photos-vectors/seamless-pattern](https://www.freepik.com/free-photos-vectors/seamless-pattern)
* Länka pil-framåt tillbaka till sidan före: **arbete1.html**
* Länka pil-bakåt till sidan efter: **arbete2.html**

![](../.gitbook/assets/image%20%2864%29.png)

