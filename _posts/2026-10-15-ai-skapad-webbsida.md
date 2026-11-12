---
layout: post
kategori: uppgift
title: "Hemsidor: AI-skapad webbsida"
amne: "Hemsidor"
del: "Hemsidor 1"
nr: "07"
ordning: "07d"
namn: "AI-skapad webbsida"
ingress: "En webbsida som jag skapade med AI – och min granskning av koden."
---

<div class="uppgiften">
<p><strong>Uppgiften</strong></p>
<p>Skapa en webbsida med hjälp av AI och granska sedan vad du fick. Poängen är inte att få en snygg sida, utan att se hur prompten styr resultatet och att kunna läsa kod som någon annan har skrivit.</p>
<p>Alla fick samma prompt och bytte ut några ord mot egna: rubrik, text, bildmotiv och stil. Sidan skulle ha en animerad rubrik, en kort presentation och tre bilder från picsum.photos som ligger på en rad på stor skärm och bryts på mindre skärmar. Sedan skulle man ändra något ord, köra prompten igen och jämföra.</p>
<p>Till sist svarade man på fem frågor om sidan.</p>
</div>

<p><a class="knapp" href="{{ '/demos/ai-website/index.html' | relative_url }}" target="_blank" rel="noopener">Första versionen ↗</a> <a class="knapp" href="{{ '/demos/ai-website/index%20(neon).html' | relative_url }}" target="_blank" rel="noopener">Andra versionen: neon ↗</a></p>

<figure class="uppg-bild"><img src="{{ '/assets/img/uppgifter/ai-nordisk.webp' | relative_url }}" alt="Första versionen: Hannahs värld i mjuka naturfärger." width="1000" height="583" loading="lazy"><figcaption>Första versionen</figcaption></figure>

<figure class="uppg-bild"><img src="{{ '/assets/img/uppgifter/ai-neon.webp' | relative_url }}" alt="Andra versionen: Hannahs värld med neonfärger på mörk bakgrund." width="1000" height="583" loading="lazy"><figcaption>Andra versionen: neon</figcaption></figure>

## 1. Vilken AI-tjänst och modell använde du?

Jag använde Claude, modellen Opus 5.5, den 15 oktober 2026.

## 2. Tre kodutdrag och förklaringar

**1. CSS-variabler – :root**

```css
:root {
  --lime: #39ff14;
  --gul: #fff01f;
  --orange: #ff8c00;
  --rod: #ff073a;
  --magenta: #ff00e6;
  --violett: #9d00ff;
  --cyan: #00e5ff;
  --turkos: #00ffc3;
  --bg: #050310;
  --text: #f2f2ff;
  --radie: 28px;
}
```

Förklaring: Här finns färger som används på hela webbsidan. Varje färg har ett eget namn. Om jag ändrar en färg här, ändras den på alla ställen där den används.

**2. Animerade färglister – body::before och body::after**

```css
body::before,
body::after {
  content: "";
  position: fixed;
  left: 0;
  right: 0;
  height: 5px;
  background: var(--spektrum);
  background-size: 200% 100%;
  animation: gradientFlode 4s linear infinite;
}
```

Förklaring: Den här koden skapar två smala färgade linjer, en högst upp och en längst ner på sidan. Färgerna rör sig hela tiden med hjälp av en animation.

**3. Färgad text – .undertitel**

```css
.undertitel {
  font-size: 1.1rem;
  font-weight: 700;
  letter-spacing: 0.35em;
  text-transform: uppercase;
  background: linear-gradient(90deg,
    var(--gul), var(--orange),
    var(--rod), var(--magenta));
  background-clip: text;
  color: transparent;
}
```

Förklaring: Den här koden ändrar utseendet på underrubriken. Texten får stora bokstäver, större mellanrum mellan bokstäverna och flera färger som går över i varandra.

## 3. Vad ändrade du i prompten, och vad blev skillnaden i resultatet?

Först valde jag en modern skandinavisk design med naturfärger och mjuka former. Sedan ändrade jag stilen till en futuristisk design med neonfärger och mörk bakgrund. Resultatet blev först mest blått och rosa, så jag ändrade prompten igen och beskrev exakt vilka färger jag ville ha. Då fick webbsidan en bredare färgpalett med grönt, gult, orange, rött, turkos och violett. Innehållet var samma, men utseendet blev mycket mer färgstarkt och lekfullt.

## 4. Granskning av AI-skapad webbsida

Jag kontrollerade HTML-koden med W3C Validator. Resultatet var noll fel och en varning. Claude använde en `<section>` utan rubrik. Jag ändrade den till `<div>` och ändrade också den avslutande taggen.

Alla tre bilderna har alt-texter och sidan har `lang="sv"`. Det är bra, men jag behöver också kontrollera att alt-texterna beskriver bilderna rätt.

Bilderna hämtas från picsum.photos. I Claudes förhandsvisning syntes de inte, men när jag öppnade sidan med Live Server fungerade de. Om jag skulle publicera webbsidan skulle jag använda egna bilder i mappen bilder.

Jag såg också att vissa färgade texter kan ha för låg kontrast mot bakgrunden. Det behöver kontrolleras med WebAIM Contrast Checker och vid behov ändras.

Claude skapade flera animationer och dekorativa former. De gör sidan mer levande, men en del av dem är inte nödvändiga. Jag skulle kunna ta bort dem för att göra koden enklare.

## 5. Jämförelse mellan min egen webbsida och AI-sidan

Med AI gick det mycket snabbare att skapa webbsidan. Claude skrev HTML och CSS, valde färger och skapade animationer. Jag behövde bara beskriva vad jag ville ha.

När jag gjorde min egen webbsida i uppgift 7c skrev jag koden själv. Därför vet jag bättre vad som finns i koden, var jag kan ändra något och hur det fungerar. Det var också lättare för mig att hitta fel.

AI-sidan har mycket mer avancerad kod. Jag förstår hur sidan fungerar, men jag förstår inte alla delar i CSS och alla animationer. Jag måste läsa koden och lära mig vad de betyder.

AI sparar mycket tid, men när jag skriver koden själv vet jag mer exakt vad jag har gjort och har bättre kontroll över min webbsida.
