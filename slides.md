---
theme: default
title: Girls' Day 2026 – Deine Website mit KI
highlighter: shiki
lineNumbers: false
css: unocss
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Source+Serif+4:ital,wght@0,400;0,700;1,400&display=swap');

:root {
  --innoq-blue: #24244c;
  --innoq-apricot: #ff9c66;
  --innoq-petrol: #004153;
  --innoq-green: #55cdaf;
  --innoq-red: #ff4d67;
  --innoq-yellow: #fff019;
  --innoq-gray: #242424;
  --innoq-gray-light: #f4f4f4;
  --innoq-gray-mid: #d8d8d8;
}

.slidev-layout {
  font-family: 'Source Serif 4', Georgia, serif;
  color: var(--innoq-blue);
}

h1, h2, h3 {
  font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
  font-weight: 700;
  color: var(--innoq-blue);
}

.accent { color: var(--innoq-apricot); }
.petrol { color: var(--innoq-petrol); }

.innoq-badge {
  display: inline-block;
  background: var(--innoq-apricot);
  color: var(--innoq-blue);
  font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
  font-weight: 700;
  font-size: 0.75rem;
  padding: 0.2rem 0.6rem;
  border-radius: 2px;
  letter-spacing: 0.05em;
  text-transform: uppercase;
}

.agenda-section-label {
  font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
  font-size: 0.7rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  color: var(--innoq-apricot);
  margin-bottom: 0.4rem;
}

.agenda-item {
  display: flex;
  align-items: baseline;
  gap: 1rem;
  padding: 0.32rem 0;
  border-bottom: 1px solid var(--innoq-gray-mid);
  font-size: 0.9rem;
}

.agenda-item:last-child {
  border-bottom: none;
}

.agenda-item.break {
  color: #888;
  font-size: 0.82rem;
}

.agenda-time {
  font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
  font-weight: 700;
  font-size: 0.78rem;
  color: var(--innoq-petrol);
  min-width: 4rem;
}

.praxis-badge {
  font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
  font-size: 0.65rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  background: var(--innoq-apricot);
  color: var(--innoq-blue);
  padding: 0.1rem 0.4rem;
  border-radius: 2px;
  margin-left: 0.5rem;
  vertical-align: middle;
}
</style>

---
layout: cover
background: '#24244c'
---

<div style="display:flex; flex-direction:column; height:100%; justify-content:space-between;">

<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.85rem; font-weight:700; color:#ff9c66; letter-spacing:0.1em; text-transform:uppercase;">
  Girls' Day 2026
</div>

<div>
  <h1 style="color:white; font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size:2.8rem; line-height:1.1; margin-bottom:1rem;">
    Deine Website –<br>
    <span style="color:#ff9c66;">gebaut mit KI</span>
  </h1>
  <p style="color:#bfcfd4; font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size:1rem; margin:0;">
    23. April 2026
  </p>
</div>

<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size:0.8rem; color:#9191a5;">
  INNOQ · Girls' Day 2026
</div>

</div>

---
layout: default
---

# Willkommen!

<div style="margin-top: 1.5rem; display: grid; grid-template-columns: 1fr 1fr; gap: 2rem;">

<div>

**Wer sind wir?**

INNOQ ist ein Technologie- und Beratungsunternehmen. Wir helfen anderen Unternehmen, gute Software zu bauen – und denken dabei viel darüber nach, wie Technologie dem Menschen nützen kann.

</div>

<div>

**Was machen wir heute?**

Du baust heute deine **eigene Website** – ganz ohne Programmierkenntnisse. Stattdessen arbeitest du mit **KI als Werkzeug**, um deine Idee zum Leben zu erwecken.

</div>

</div>

<div style="margin-top: 2rem; padding: 1rem 1.25rem; background: var(--innoq-gray-light); border-left: 3px solid var(--innoq-apricot); font-size: 0.95rem;">
  Am Ende ist deine Website <strong>live und öffentlich erreichbar</strong>.
</div>

---
layout: default
---

# Agenda

<div style="margin-top: 1rem; display: grid; grid-template-columns: 1fr 1fr; gap: 0 3rem;">

<div>
<div class="agenda-section-label">Vormittag</div>

<div class="agenda-item">
  <span>Ankommen & Begrüßung</span>
</div>
<div class="agenda-item">
  <span>Grundkenntnisse Webtechnologien</span>
</div>
<div class="agenda-item">
  <span>Wie funktioniert eine KI?</span>
</div>
<div class="agenda-item">
  <span>Wie funktioniert ein Agent?</span>
</div>
<div class="agenda-item">
  <span>Produktentwicklung</span>
</div>
<div class="agenda-item">
  <span>Website planen <span class="praxis-badge">Praxis</span></span>
</div>
</div>

<div>
<div class="agenda-section-label">Nachmittag</div>

<div class="agenda-item">
  <span>Website iterativ mit Copilot entwickeln <span class="praxis-badge">Praxis</span></span>
</div>
<div class="agenda-item break">
  <span>Agents & Skills kennenlernen <em style="font-size:0.8em;">(falls Zeit)</em> <span class="praxis-badge">Praxis</span></span>
</div>
<div class="agenda-item">
  <span>Website online stellen <span class="praxis-badge">Praxis</span></span>
</div>
<div class="agenda-item">
  <span>Demo – eure Websites!</span>
</div>
<div class="agenda-item">
  <span>Ende & Verabschiedung</span>
</div>
</div>

</div>

---
layout: cover
background: '#004153'
---

<div style="display:flex; flex-direction:column; height:100%; justify-content:space-between;">
<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.85rem; font-weight:700; color:#ff9c66; letter-spacing:0.1em; text-transform:uppercase;">Grundkenntnisse</div>
<div>
  <h1 style="color:white; font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size:2.8rem; line-height:1.1; margin-bottom:1rem;">
    Wie ist eine Website<br><span style="color:#ff9c66;">aufgebaut?</span>
  </h1>
</div>
<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size:0.8rem; color:#80a0a9;">INNOQ · Girls' Day 2026</div>
</div>

---
layout: default
---

# Eine Website hat drei Schichten

<div style="margin-top: 2rem; display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 1.5rem; text-align: center;">

<div style="padding: 1.5rem 1rem; background: #f4f4f4; border-top: 4px solid #ff9c66;">
  <div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 1.4rem; font-weight: 800; color: #24244c; margin-bottom: 0.5rem;">HTML</div>
  <div style="font-size: 2rem; margin-bottom: 0.75rem;">🏗️</div>
  <div style="font-size: 0.88rem;">Die <strong>Struktur</strong> –<br>was auf der Seite steht</div>
</div>

<div style="padding: 1.5rem 1rem; background: #f4f4f4; border-top: 4px solid #55cdaf;">
  <div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 1.4rem; font-weight: 800; color: #24244c; margin-bottom: 0.5rem;">CSS</div>
  <div style="font-size: 2rem; margin-bottom: 0.75rem;">🎨</div>
  <div style="font-size: 0.88rem;">Das <strong>Aussehen</strong> –<br>wie es aussieht</div>
</div>

<div style="padding: 1.5rem 1rem; background: #f4f4f4; border-top: 4px solid #fff019;">
  <div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 1.4rem; font-weight: 800; color: #24244c; margin-bottom: 0.5rem;">JavaScript</div>
  <div style="font-size: 2rem; margin-bottom: 0.75rem;">⚡</div>
  <div style="font-size: 0.88rem;">Das <strong>Verhalten</strong> –<br>was passiert beim Klicken</div>
</div>

</div>

<div style="margin-top: 2rem; font-size: 0.9rem; color: #646465; text-align: center;">
  Jede Website im Internet besteht aus genau diesen drei Teilen.
</div>

---
layout: two-cols
---

# HTML – die Struktur

HTML beschreibt, **was** auf einer Seite ist – mit sogenannten **Tags**.  
Ein Tag ist wie ein Label, das dem Browser sagt: „Das hier ist eine Überschrift", „Das hier ist ein Bild".

Tags haben immer einen Anfang und ein Ende:

```html
<h1>Meine Katze Mimi</h1>
```

<div style="margin-top: 1rem; font-size: 0.85rem; color: #646465;">
  <code style="background:#f4f4f4; padding: 0.1rem 0.3rem;">&lt;h1&gt;</code> öffnet den Tag,
  <code style="background:#f4f4f4; padding: 0.1rem 0.3rem;">&lt;/h1&gt;</code> schließt ihn wieder.
</div>

::right::

<div style="padding-left: 2rem; padding-top: 3rem;">

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Meine Website</title>
  </head>
  <body>
    <h1>Meine Katze Mimi</h1>
    <p>Mimi ist 3 Jahre alt
       und liebt Schlafen.</p>
    <img src="mimi.jpg">
  </body>
</html>
```

<div style="margin-top: 1rem; font-size: 0.82rem; color: #646465; line-height: 1.6;">
  <code style="background:#f4f4f4; padding: 0.1rem 0.3rem;">h1</code> = große Überschrift<br>
  <code style="background:#f4f4f4; padding: 0.1rem 0.3rem;">p</code> = Absatz (Paragraph)<br>
  <code style="background:#f4f4f4; padding: 0.1rem 0.3rem;">img</code> = Bild
</div>

</div>

---
layout: two-cols
---

# CSS – das Aussehen

CSS legt fest, **wie** etwas aussieht – Farben, Schriften, Abstände.  
Man wählt ein HTML-Element aus und beschreibt seinen Stil:

```css
h1 {
  color: hotpink;
  font-size: 48px;
}
```

<div style="margin-top: 1rem; font-size: 0.85rem; color: #646465;">
  Links steht <em>was</em> gestaltet wird, in den geschweiften Klammern <em>wie</em>.
</div>

::right::

<div style="padding-left: 2rem; padding-top: 3rem;">

```css
body {
  background-color: #fff0e8;
  font-family: Arial;
}

h1 {
  color: hotpink;
  font-size: 48px;
}

p {
  color: #333;
  line-height: 1.6;
}

img {
  width: 300px;
  border-radius: 12px;
}
```

</div>

---
layout: default
---

# JavaScript – das Verhalten

JavaScript macht eine Website **lebendig**. Damit kann man auf Klicks reagieren, Dinge ein- und ausblenden oder Inhalte verändern.

<div style="margin-top: 1.5rem; display: grid; grid-template-columns: 1fr 1fr; gap: 2rem;">

<div>

```html
<!-- In der HTML-Datei -->
<button onclick="begrueße()">
  Klick mich!
</button>

<p id="nachricht"></p>
```

</div>

<div>

```js
// In der JavaScript-Datei
function begrueße() {
  document.getElementById("nachricht")
    .innerText = "Hallo! 👋"
}
```

</div>

</div>

<div style="margin-top: 1.5rem; padding: 0.9rem 1.25rem; background: #f4f4f4; border-left: 3px solid #fff019; font-size: 0.88rem;">
  Beim Girls' Day werden wir <strong>kaum selbst JavaScript schreiben</strong> – das übernimmt die KI für uns. Aber gut zu wissen, was dahintersteckt!
</div>

---
layout: default
---

# Alles zusammen

Die drei Dateien arbeiten gemeinsam – jede hat ihre Aufgabe.

<div style="margin-top: 1.5rem; display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 1rem; font-size: 0.82rem;">

<div>

**`index.html`**
```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet"
          href="style.css">
  </head>
  <body>
    <h1>Meine Katze Mimi</h1>
    <button onclick="zeige()">
      Mehr erfahren
    </button>
    <p id="info"></p>
    <script src="script.js">
    </script>
  </body>
</html>
```

</div>

<div>

**`style.css`**
```css
body {
  background: #fff0e8;
  font-family: Arial;
}

h1 {
  color: hotpink;
}

button {
  background: hotpink;
  color: white;
  border: none;
  padding: 8px 16px;
  border-radius: 8px;
}
```

</div>

<div>

**`script.js`**
```js
function zeige() {
  document.getElementById("info")
    .innerText =
      "Mimi ist 3 Jahre alt!"
}
```

<div style="margin-top: 1.5rem; padding: 0.75rem; background: #f4f4f4; border-left: 3px solid #ff9c66; line-height: 1.6;">
  HTML bindet CSS über <code>link</code> ein und JavaScript über <code>script</code>.<br>
  Die drei Dateien liegen im selben Ordner.
</div>

</div>

</div>

---
layout: default
---

# Wie kommt eine Website zu dir?

<div style="display: flex; justify-content: center; margin-top: 1rem;">
  <img src="/assets/internet-1.png" style="max-height: 420px;" />
</div>

---
layout: default
---

<div style="display: flex; justify-content: center; align-items: center; height: 100%;">
  <img src="/assets/internet-2.png" style="max-height: 480px;" />
</div>

---
layout: cover
background: '#24244c'
---

<div style="display:flex; flex-direction:column; height:100%; justify-content:space-between;">
<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.85rem; font-weight:700; color:#ff9c66; letter-spacing:0.1em; text-transform:uppercase;">Theorie</div>
<div>
  <h1 style="color:white; font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size:2.8rem; line-height:1.1; margin-bottom:1rem;">
    Wie funktioniert<br><span style="color:#ff9c66;">eine KI?</span>
  </h1>
</div>
<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size:0.8rem; color:#9191a5;">INNOQ · Girls' Day 2026</div>
</div>

---
layout: default
---

# KI hat ganz viel gelesen

<div style="margin-top: 1.5rem; display: grid; grid-template-columns: 1fr 1fr; gap: 2.5rem; align-items: center;">

<div>

Eine KI wie ChatGPT oder Copilot wurde mit **riesigen Mengen Text** trainiert – Bücher, Websites, Wikipedia, Artikel, Foren ...

Dabei hat sie gelernt: **Welche Wörter kommen häufig zusammen vor?** Was folgt typischerweise auf was?

<div style="margin-top: 1.25rem; padding: 0.9rem 1.25rem; background: #f4f4f4; border-left: 3px solid #ff9c66; font-size: 0.88rem;">
  Sie hat nicht „verstanden" was sie gelesen hat – sie hat <strong>Muster erkannt</strong>.
</div>

</div>

<div style="text-align: center;">

<div style="font-size: 3.5rem; margin-bottom: 1rem;">📚</div>

<div style="display: flex; flex-wrap: wrap; gap: 0.4rem; justify-content: center; font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.75rem;">
  <span style="background:#f4f4f4; padding: 0.2rem 0.5rem; border-radius: 2px;">Wikipedia</span>
  <span style="background:#f4f4f4; padding: 0.2rem 0.5rem; border-radius: 2px;">Bücher</span>
  <span style="background:#f4f4f4; padding: 0.2rem 0.5rem; border-radius: 2px;">Nachrichten</span>
  <span style="background:#f4f4f4; padding: 0.2rem 0.5rem; border-radius: 2px;">Websites</span>
  <span style="background:#f4f4f4; padding: 0.2rem 0.5rem; border-radius: 2px;">Foren</span>
  <span style="background:#f4f4f4; padding: 0.2rem 0.5rem; border-radius: 2px;">Code</span>
  <span style="background:#f4f4f4; padding: 0.2rem 0.5rem; border-radius: 2px;">Rezepte</span>
  <span style="background:#f4f4f4; padding: 0.2rem 0.5rem; border-radius: 2px;">Gedichte</span>
</div>

</div>

</div>

---
layout: default
---

# KI ist wie sehr gutes Autocomplete

Du kennst das vom Handy: Wenn du tippst, schlägt es das nächste Wort vor.

<div style="margin-top: 1.5rem; display: grid; grid-template-columns: 1fr 1fr; gap: 2rem;">

<div>

<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #646465; margin-bottom: 0.75rem;">Handy-Autocomplete</div>

<div style="background: #f4f4f4; border-radius: 8px; padding: 1rem 1.25rem; font-size: 0.95rem; line-height: 2;">
  Ich esse gerne <span style="background: #d8d8d8; padding: 0.1rem 0.4rem; border-radius: 4px;">Pizza</span>
</div>
<div style="margin-top: 0.5rem; display: flex; gap: 0.5rem;">
  <span style="background: white; border: 1px solid #d8d8d8; padding: 0.3rem 0.7rem; border-radius: 4px; font-size: 0.82rem;">und</span>
  <span style="background: white; border: 1px solid #d8d8d8; padding: 0.3rem 0.7rem; border-radius: 4px; font-size: 0.82rem;">mit</span>
  <span style="background: white; border: 1px solid #d8d8d8; padding: 0.3rem 0.7rem; border-radius: 4px; font-size: 0.82rem;">!</span>
</div>

<div style="margin-top: 1rem; font-size: 0.85rem; color: #646465;">
  Schlägt das nächste <em>einzelne</em> Wort vor.
</div>

</div>

<div>

<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #646465; margin-bottom: 0.75rem;">KI (LLM)</div>

<div style="background: #f4f4f4; border-radius: 8px; padding: 1rem 1.25rem; font-size: 0.95rem; line-height: 2;">
  Schreib mir eine Website über <span style="background: #ffd5c2; padding: 0.1rem 0.4rem; border-radius: 4px;">meine Katze</span>
</div>
<div style="margin-top: 0.5rem; background: white; border: 1px solid #d8d8d8; padding: 0.5rem 0.75rem; border-radius: 4px; font-size: 0.82rem; color: #646465;">
  Erstellt eine ganze HTML-Seite mit Überschrift, Text, Styles …
</div>

<div style="margin-top: 1rem; font-size: 0.85rem; color: #646465;">
  Schlägt <em>tausende</em> Wörter auf einmal vor – sinnvoll und zusammenhängend.
</div>

</div>

</div>

---
layout: default
---

# Wie die KI Sprache versteht

<div style="margin-top: 1.25rem; display: grid; grid-template-columns: 1fr 1fr; gap: 2.5rem;">

<div>

<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #004153; margin-bottom: 0.75rem;">Tokens – Wörter in Stücke zerlegt</div>

Die KI liest keinen Text wie wir. Sie zerlegt alles zuerst in kleine Einheiten – **Tokens**.

<div style="margin-top: 0.75rem; background: #f4f4f4; border-radius: 6px; padding: 0.9rem 1rem; font-size: 0.88rem; line-height: 2.2;">
  <span style="background: #ffd5c2; padding: 0.15rem 0.4rem; border-radius: 3px; margin-right: 2px;">Mei</span><span style="background: #c8f5ea; padding: 0.15rem 0.4rem; border-radius: 3px; margin-right: 2px;">ne</span> <span style="background: #ffd5c2; padding: 0.15rem 0.4rem; border-radius: 3px; margin-right: 2px;">Kat</span><span style="background: #c8f5ea; padding: 0.15rem 0.4rem; border-radius: 3px; margin-right: 2px;">ze</span> <span style="background: #ffd5c2; padding: 0.15rem 0.4rem; border-radius: 3px; margin-right: 2px;">heißt</span> <span style="background: #c8f5ea; padding: 0.15rem 0.4rem; border-radius: 3px;">Mimi</span>
</div>

<div style="margin-top: 0.75rem; font-size: 0.82rem; color: #646465;">
  Ein Token ist meist ein Wort oder ein Wortteil. GPT-4 verarbeitet bis zu 128.000 Tokens auf einmal.
</div>

</div>

<div>

<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #004153; margin-bottom: 0.75rem;">Vektoren – Tokens als Punkte im Raum</div>

Jedes Token wird in eine **Zahl-Liste** umgewandelt (einen Vektor). Ähnliche Tokens landen dabei nah beieinander.

<div style="margin-top: 0.75rem; background: #f4f4f4; border-radius: 6px; padding: 0.75rem 1rem; display: flex; justify-content: space-between; align-items: flex-start;">
  <div style="display: flex; flex-direction: column; gap: 0.3rem;">
    <span style="background: #55cdaf; color: #004153; padding: 0.2rem 0.6rem; border-radius: 4px; font-size: 0.82rem; font-weight: 600; width: fit-content;">Katze</span>
    <span style="background: #55cdaf; color: #004153; padding: 0.2rem 0.6rem; border-radius: 4px; font-size: 0.82rem; font-weight: 600; width: fit-content;">Hund</span>
    <span style="background: #55cdaf; color: #004153; padding: 0.2rem 0.6rem; border-radius: 4px; font-size: 0.82rem; font-weight: 600; width: fit-content;">Vogel</span>
  </div>
  <div style="display: flex; flex-direction: column; gap: 0.3rem; align-items: flex-end;">
    <span style="background: #ff9c66; color: #24244c; padding: 0.2rem 0.6rem; border-radius: 4px; font-size: 0.82rem; font-weight: 600; width: fit-content;">Pizza</span>
    <span style="background: #ff9c66; color: #24244c; padding: 0.2rem 0.6rem; border-radius: 4px; font-size: 0.82rem; font-weight: 600; width: fit-content;">Pasta</span>
    <span style="background: #ff9c66; color: #24244c; padding: 0.2rem 0.6rem; border-radius: 4px; font-size: 0.82rem; font-weight: 600; width: fit-content;">Burger</span>
  </div>
</div>

<div style="font-size: 0.78rem; color: #646465; margin-top: 0.5rem;">
  Tokens aus derselben Gruppe landen nah beieinander – Tokens aus verschiedenen Gruppen sind weit voneinander entfernt. Zur Vereinfachung zeigen wir hier ganze Wörter als Tokens.
</div>

</div>

</div>

---
layout: default
---

# Was eine KI kann – und was nicht

<div style="margin-top: 1.5rem; display: grid; grid-template-columns: 1fr 1fr; gap: 2rem;">

<div>

<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #55cdaf; margin-bottom: 0.75rem;">✓ Das kann sie gut</div>

<ul style="font-size: 0.9rem; line-height: 2; list-style: none; padding: 0; margin: 0;">
  <li>📝 Texte schreiben und umformulieren</li>
  <li>💻 Code schreiben und erklären</li>
  <li>💡 Ideen vorschlagen</li>
  <li>🌍 Übersetzen</li>
  <li>❓ Fragen beantworten</li>
</ul>

</div>

<div>

<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #ff4d67; margin-bottom: 0.75rem;">✗ Das kann sie nicht</div>

<ul style="font-size: 0.9rem; line-height: 2; list-style: none; padding: 0; margin: 0;">
  <li>🧠 Wirklich „denken" oder verstehen</li>
  <li>📅 Aktuelle Infos kennen</li>
  <li>🔢 Zuverlässig rechnen</li>
  <li>😶 Gefühle haben</li>
  <li>✅ Immer die Wahrheit sagen</li>
</ul>

</div>

</div>

<div style="margin-top: 2rem; padding: 0.9rem 1.25rem; background: #f4f4f4; border-left: 3px solid #ff9c66; font-size: 0.88rem;">
  Eine KI kann sich Dinge <strong>ausdenken</strong>, die falsch sind – aber sehr überzeugend klingen. Deshalb: immer kritisch mitdenken!
</div>

---
layout: cover
background: '#24244c'
---

<div style="display:flex; flex-direction:column; height:100%; justify-content:space-between;">
<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.85rem; font-weight:700; color:#ff9c66; letter-spacing:0.1em; text-transform:uppercase;">Theorie</div>
<div>
  <h1 style="color:white; font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size:2.8rem; line-height:1.1; margin-bottom:1rem;">
    Wie funktioniert<br><span style="color:#ff9c66;">ein Agent?</span>
  </h1>
</div>
<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size:0.8rem; color:#9191a5;">INNOQ · Girls' Day 2026</div>
</div>

---
layout: default
---

# Ein Agent ist eine KI in einer Schleife

Ein Agent ist ein Programm, das **immer wieder dasselbe tut** – bis die Aufgabe erledigt ist:

<div style="margin-top: 1.75rem; display: flex; flex-direction: column; align-items: center;">

  <div style="display: flex; align-items: center; gap: 0;">
    <div style="text-align: center; padding: 0.9rem 1.1rem; background: #f4f4f4; border-top: 3px solid #ff9c66; width: 8rem;">
      <div style="font-size: 1.5rem; margin-bottom: 0.3rem;">🤔</div>
      <div style="font-family: Helvetica Neue, Arial, sans-serif; font-weight: 700; font-size: 0.85rem; color: #24244c;">Nachdenken</div>
      <div style="font-size: 0.75rem; color: #646465; margin-top: 0.25rem;">Was ist der nächste Schritt?</div>
    </div>
    <div style="font-size: 1.5rem; color: #d8d8d8; padding: 0 0.25rem;">→</div>
    <div style="text-align: center; padding: 0.9rem 1.1rem; background: #f4f4f4; border-top: 3px solid #55cdaf; width: 8rem;">
      <div style="font-size: 1.5rem; margin-bottom: 0.3rem;">🔧</div>
      <div style="font-family: Helvetica Neue, Arial, sans-serif; font-weight: 700; font-size: 0.85rem; color: #24244c;">Handeln</div>
      <div style="font-size: 0.75rem; color: #646465; margin-top: 0.25rem;">Ein Programm aufrufen</div>
    </div>
    <div style="font-size: 1.5rem; color: #d8d8d8; padding: 0 0.25rem;">→</div>
    <div style="text-align: center; padding: 0.9rem 1.1rem; background: #f4f4f4; border-top: 3px solid #004153; width: 8rem;">
      <div style="font-size: 1.5rem; margin-bottom: 0.3rem;">👀</div>
      <div style="font-family: Helvetica Neue, Arial, sans-serif; font-weight: 700; font-size: 0.85rem; color: #24244c;">Beobachten</div>
      <div style="font-size: 0.75rem; color: #646465; margin-top: 0.25rem;">Was kam zurück?</div>
    </div>
    <div style="font-size: 1.5rem; color: #d8d8d8; padding: 0 0.25rem;">→</div>
    <div style="text-align: center; padding: 0.9rem 1.1rem; background: #fff0e8; border-top: 3px solid #ff9c66; border: 1px dashed #ff9c66; width: 8rem;">
      <div style="font-size: 1.5rem; margin-bottom: 0.3rem;">✅</div>
      <div style="font-family: Helvetica Neue, Arial, sans-serif; font-weight: 700; font-size: 0.85rem; color: #24244c;">Fertig?</div>
      <div style="font-size: 0.75rem; color: #646465; margin-top: 0.25rem;">Sonst: von vorne</div>
    </div>
  </div>

  <div style="width: 37rem; height: 1.4rem; border-left: 2px solid #d8d8d8; border-bottom: 2px solid #d8d8d8; border-right: 2px solid #d8d8d8; border-top: none; box-sizing: border-box;">
    <div style="font-size: 0.65rem; color: #d8d8d8; line-height: 1; margin-left: -0.35rem; margin-top: -0.5rem;">▲</div>
  </div>

</div>

<div style="margin-top: 1.75rem; font-family: Helvetica Neue, Arial, sans-serif; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #646465; margin-bottom: 0.5rem;">Zugriff auf andere Programme</div>
<div style="display: flex; gap: 0.5rem; flex-wrap: wrap;">
  <span style="background: #f4f4f4; padding: 0.25rem 0.65rem; border-radius: 4px; font-size: 0.82rem;">🔍 Suchen</span>
  <span style="background: #f4f4f4; padding: 0.25rem 0.65rem; border-radius: 4px; font-size: 0.82rem;">📝 Dateien lesen & schreiben</span>
  <span style="background: #f4f4f4; padding: 0.25rem 0.65rem; border-radius: 4px; font-size: 0.82rem;">🌐 Websites aufrufen</span>
  <span style="background: #f4f4f4; padding: 0.25rem 0.65rem; border-radius: 4px; font-size: 0.82rem;">🖥️ Code ausführen</span>
  <span style="background: #f4f4f4; padding: 0.25rem 0.65rem; border-radius: 4px; font-size: 0.82rem;">💬 Andere KIs fragen</span>
</div>

---
layout: cover
background: '#55cdaf'
---

<div style="display:flex; flex-direction:column; height:100%; justify-content:space-between;">
<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 0.85rem; font-weight:700; color:#004153; letter-spacing:0.1em; text-transform:uppercase;">Produktentwicklung</div>
<div>
  <h1 style="color:#24244c; font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size:2.8rem; line-height:1.1; margin-bottom:1rem;">
    Wie entsteht<br><span style="color:#004153;">Software?</span>
  </h1>
</div>
<div style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif; font-size:0.8rem; color:#004153;">INNOQ · Girls' Day 2026</div>
</div>

---
layout: default
---

# Wer ist eigentlich beteiligt?

Alle, die ein Interesse am Produkt haben, nennt man **Stakeholder** – das sind ganz verschiedene Rollen.

<div style="margin-top: 1.75rem; display: grid; grid-template-columns: 1fr 1fr; gap: 1.25rem;">

<div style="padding: 1rem 1.25rem; background: #f4f4f4; border-left: 4px solid #ff9c66;">
  <div style="font-family: Helvetica Neue, Arial, sans-serif; font-weight: 700; font-size: 0.9rem; color: #24244c; margin-bottom: 0.4rem;">👩‍💼 Auftraggeber</div>
  <div style="font-size: 0.85rem; color: #646465; line-height: 1.6;">Die Person oder Organisation, die das Produkt <strong>bezahlt und in Auftrag gibt</strong> – z. B. eine Chefin, ein Verein, ein Unternehmen.</div>
</div>

<div style="padding: 1rem 1.25rem; background: #f4f4f4; border-left: 4px solid #55cdaf;">
  <div style="font-family: Helvetica Neue, Arial, sans-serif; font-weight: 700; font-size: 0.9rem; color: #24244c; margin-bottom: 0.4rem;">👩‍🎨 Designerin</div>
  <div style="font-size: 0.85rem; color: #646465; line-height: 1.6;">Überlegt, wie die App <strong>aussieht und sich anfühlt</strong> – damit sie einfach zu benutzen ist.</div>
</div>

<div style="padding: 1rem 1.25rem; background: #f4f4f4; border-left: 4px solid #004153;">
  <div style="font-family: Helvetica Neue, Arial, sans-serif; font-weight: 700; font-size: 0.9rem; color: #24244c; margin-bottom: 0.4rem;">👩‍💻 Entwicklerin</div>
  <div style="font-size: 0.85rem; color: #646465; line-height: 1.6;">Schreibt den <strong>Code</strong>, der das Produkt zum Leben erweckt.</div>
</div>

<div style="padding: 1rem 1.25rem; background: #f4f4f4; border-left: 4px solid #fff019;">
  <div style="font-family: Helvetica Neue, Arial, sans-serif; font-weight: 700; font-size: 0.9rem; color: #24244c; margin-bottom: 0.4rem;">🙋 Nutzerin</div>
  <div style="font-size: 0.85rem; color: #646465; line-height: 1.6;">Die Person, die das Produkt am Ende <strong>wirklich benutzt</strong> – und deren Bedürfnisse am wichtigsten sind.</div>
</div>

</div>

---
layout: default
---

# User Stories – Was soll die Software können?

Bevor eine Zeile Code geschrieben wird, muss klar sein: **Was soll das Programm überhaupt tun?**  
Dafür schreibt man **User Stories** – kurze Sätze aus Sicht der Nutzerin.

<div style="margin-top: 1.5rem; padding: 1.25rem 1.5rem; background: #f4f4f4; border-left: 4px solid #ff9c66; font-size: 1rem; line-height: 1.8;">
  <strong>Als</strong> <em>[wer?]</em> möchte ich <em>[was?]</em>, damit <em>[warum?]</em>.
</div>

<div style="margin-top: 1.5rem; display: grid; grid-template-columns: 1fr 1fr; gap: 1.25rem; font-size: 0.88rem;">

<div style="padding: 1rem 1.25rem; background: white; border: 1px solid #d8d8d8; border-radius: 4px;">
  <div style="font-family: Helvetica Neue, Arial, sans-serif; font-size: 0.72rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #ff9c66; margin-bottom: 0.5rem;">Beispiel 1</div>
  <div style="line-height: 1.7;">Als <strong>Schülerin</strong> möchte ich meinen Stundenplan online sehen, damit ich immer weiß, was als nächstes kommt.</div>
</div>

<div style="padding: 1rem 1.25rem; background: white; border: 1px solid #d8d8d8; border-radius: 4px;">
  <div style="font-family: Helvetica Neue, Arial, sans-serif; font-size: 0.72rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #ff9c66; margin-bottom: 0.5rem;">Beispiel 2</div>
  <div style="line-height: 1.7;">Als <strong>Vereinsmitglied</strong> möchte ich Termine eintragen können, damit alle Bescheid wissen.</div>
</div>

</div>

<div style="margin-top: 1.25rem; padding: 0.9rem 1.25rem; background: #f4f4f4; border-left: 3px solid #55cdaf; font-size: 0.88rem;">
  User Stories helfen dem ganzen Team, das <strong>gleiche Ziel</strong> vor Augen zu haben – ohne technisches Kauderwelsch.
</div>

---
layout: default
---

# Specs – Was soll gebaut werden?

Eine User Story sagt **was** gebaut werden soll. Eine **Spec** beschreibt **wie genau** – für Entwicklerinnen und für KI-Coding-Agents.

<div style="margin-top: 1.25rem; display: grid; grid-template-columns: 1fr 1fr; gap: 1.5rem;">

<div>

<div style="font-family: Helvetica Neue, Arial, sans-serif; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #646465; margin-bottom: 0.75rem;">User Story</div>

<div style="padding: 1rem 1.25rem; background: #f4f4f4; border-left: 4px solid #ff9c66; font-size: 0.88rem; line-height: 1.7;">
  Als Nutzerin möchte ich mich einloggen können, damit nur ich meine Daten sehe.
</div>

<div style="margin-top: 1rem; font-family: Helvetica Neue, Arial, sans-serif; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #646465; margin-bottom: 0.75rem;">Spec (Ausschnitt)</div>

<div style="padding: 1rem 1.25rem; background: #f4f4f4; border-left: 4px solid #55cdaf; font-size: 0.82rem; line-height: 1.8;">
  <ul style="margin: 0; padding-left: 1.2rem;">
    <li>Formular mit E-Mail und Passwort</li>
    <li>Passwort mindestens 8 Zeichen</li>
    <li>Fehlermeldung bei falschem Passwort</li>
    <li>Nach Login: Weiterleitung zur Startseite</li>
  </ul>
</div>

</div>

<div>

<div style="font-family: Helvetica Neue, Arial, sans-serif; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #646465; margin-bottom: 0.75rem;">Wer liest die Spec?</div>

<div style="display: flex; flex-direction: column; gap: 0.75rem;">

<div style="padding: 0.9rem 1.1rem; background: #f4f4f4; border-left: 4px solid #004153; font-size: 0.85rem; line-height: 1.6;">
  <strong>👩‍💻 Entwicklerin</strong><br>
  <span style="color: #646465;">Versteht, was zu bauen ist – und kann nachfragen, wenn etwas unklar ist.</span>
</div>

<div style="padding: 0.9rem 1.1rem; background: #f4f4f4; border-left: 4px solid #ff9c66; font-size: 0.85rem; line-height: 1.6;">
  <strong>🤖 KI-Coding-Agent</strong><br>
  <span style="color: #646465;">Kann <strong>nicht nachfragen</strong> – braucht eine klare, vollständige Beschreibung, sonst erfindet er einfach etwas.</span>
</div>

</div>

<div style="margin-top: 0.75rem; padding: 0.75rem 1rem; background: #fff0e8; border-left: 3px solid #ff9c66; font-size: 0.82rem; line-height: 1.6;">
  Je präziser die Spec, desto besser das Ergebnis – besonders wichtig, wenn eine KI den Code schreibt.
</div>

</div>

</div>

---
layout: default
---

# Git – Gemeinsam am Code arbeiten

Stell dir vor, ihr schreibt alle gleichzeitig an demselben Word-Dokument. Chaos!  
**Git** löst dieses Problem für Code.

<div style="margin-top: 1.5rem; display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; align-items: start;">

<div>

<div style="font-size: 0.88rem; line-height: 1.7; margin-bottom: 1rem;">
  Git ist ein <strong>Versionsverwaltungs-System</strong>. Es speichert jeden Schritt des Codes – wie ein Speicherstand in einem Videospiel.
</div>

<div style="display: flex; flex-direction: column; gap: 0.6rem; font-size: 0.85rem;">
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.6rem 0.9rem; background: #f4f4f4; border-radius: 4px;">
    <span style="font-size: 1.1rem;">💾</span>
    <span><strong>commit</strong> – einen Speicherstand anlegen</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.6rem 0.9rem; background: #f4f4f4; border-radius: 4px;">
    <span style="font-size: 1.1rem;">🌿</span>
    <span><strong>branch</strong> – einen eigenen Bereich ausprobieren</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.6rem 0.9rem; background: #f4f4f4; border-radius: 4px;">
    <span style="font-size: 1.1rem;">🔀</span>
    <span><strong>merge</strong> – Änderungen zusammenführen</span>
  </div>
</div>

</div>

<div>

<div style="font-family: Helvetica Neue, Arial, sans-serif; font-size: 0.72rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #646465; margin-bottom: 0.75rem;">Verlauf im Team</div>

<div style="display: flex; flex-direction: column; gap: 0;">
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.5rem 0.9rem; background: white; border: 1px solid #d8d8d8; border-bottom: none; font-size: 0.8rem;">
    <span style="color: #55cdaf; font-weight: 700;">●</span>
    <span style="color: #646465; font-size: 0.72rem; font-family: monospace;">v3</span>
    <span>Anna: Kontaktformular hinzugefügt</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.5rem 0.9rem; background: white; border: 1px solid #d8d8d8; border-bottom: none; font-size: 0.8rem;">
    <span style="color: #55cdaf; font-weight: 700;">●</span>
    <span style="color: #646465; font-size: 0.72rem; font-family: monospace;">v2</span>
    <span>Lena: Farben angepasst</span>
  </div>
  <div style="display: flex; align-items: center; gap: 0.75rem; padding: 0.5rem 0.9rem; background: white; border: 1px solid #d8d8d8; font-size: 0.8rem;">
    <span style="color: #d8d8d8; font-weight: 700;">●</span>
    <span style="color: #646465; font-size: 0.72rem; font-family: monospace;">v1</span>
    <span style="color: #646465;">Startseite erstellt</span>
  </div>
</div>

<div style="margin-top: 0.75rem; padding: 0.75rem 1rem; background: #f4f4f4; border-left: 3px solid #ff9c66; font-size: 0.82rem; line-height: 1.6;">
  Man kann jederzeit zu einem alten Stand zurückspringen – kein Fehler ist für immer!
</div>

</div>

</div>
