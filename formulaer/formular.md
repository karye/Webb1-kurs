---
description: Hur man bygger ett formulär med alla dess delar.
---

# Kontaktformulär

## Resultat

![](../.gitbook/assets/image%20%2872%29.png)

## Genomgång

{% embed url="https://youtu.be/UoSh5xoz6fg" %}

## Steg 1 - förberedelser - webbrot

* Skapa en mapp som heter **formular**
* Skapa en webbsida som heter **kontakt.html**
* Skapa en CSS-fil som heter **kontakt.css**
* Skapa en mapp **bilder**

## Steg 2 - skapa HTML-sidan <a id="steg-2-skapa-html-sida"></a>

### Grundkoden

* Börja med grundkoden
* Fyll i alla HTML-element som bygger upp sidan
* Så här ett formulär ut: [https://devdocs.io/html/element/form](https://devdocs.io/html/element/form)

## **Steg 3 - snygga till sidan med CSS** <a id="steg-3-snygga-till-sidan-med-css"></a>

### CSS-reglerna <a id="css-reglerna"></a>

* Infoga först CSS-reset
* Infoga alla CSS-regler som motsvarar de taggar vi använder
* **Välj typsnitt**
* Gå till [Google Fonts](https://fonts.google.com) och välj två typsnitt

## Extra uppgift

### Egen stil på radioknappar och kryssrutor

![](../.gitbook/assets/image%20%2882%29.png)

* Prova styla enligt CSS nedan

```markup
<div>
  <label>
    <input type="checkbox" class="option-input checkbox" checked />
    Checkbox
  </label>
  <label>
    <input type="checkbox" class="option-input checkbox" />
    Checkbox
  </label>
  <label>
    <input type="checkbox" class="option-input checkbox" />
    Checkbox
  </label>
</div>

<div>
  <label>
    <input type="radio" class="option-input radio" name="example" checked />
    Radio option
  </label>
  <label>
    <input type="radio" class="option-input radio" name="example" />
    Radio option
  </label>
  <label>
    <input type="radio" class="option-input radio" name="example" />
    Radio option
  </label>
</div>
```

```css
@keyframes click-wave {
  0% {
    height: 40px;
    width: 40px;
    opacity: 0.35;
    position: relative;
  }
  100% {
    height: 200px;
    width: 200px;
    margin-left: -80px;
    margin-top: -80px;
    opacity: 0;
  }
}

.option-input {
  appearance: none;
  position: relative;
  top: 13.33333px;
  right: 0;
  bottom: 0;
  left: 0;
  height: 40px;
  width: 40px;
  transition: all 0.15s ease-out 0s;
  background: #cbd1d8;
  border: none;
  color: #fff;
  cursor: pointer;
  display: inline-block;
  margin-right: 0.5rem;
  outline: none;
  position: relative;
  z-index: 1000;
}
.option-input:hover {
  background: #9faab7;
}
.option-input:checked {
  background: #40e0d0;
}
.option-input:checked::before {
  height: 40px;
  width: 40px;
  position: absolute;
  content: "✔";
  display: inline-block;
  font-size: 26.66667px;
  text-align: center;
  line-height: 40px;
}
.option-input:checked::after {
  animation: click-wave 0.65s;
  background: #40e0d0;
  content: "";
  display: block;
  position: relative;
  z-index: 100;
}
.option-input.radio {
  border-radius: 50%;
}
.option-input.radio::after {
  border-radius: 50%;
}

body label {
  display: block;
  line-height: 40px;
}

```

