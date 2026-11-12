---
layout: post
kategori: uppgift
title: "Hemsidor: Min egen webbsida"
amne: "Hemsidor"
del: "Hemsidor 1"
nr: "07"
ordning: "07c"
namn: "Min egen webbsida"
ingress: "Min första webbsida, skriven för hand i HTML och CSS. Den har tre sidor: Start, Om mig och Hannah guide."
---

<div class="uppgiften">
<p><strong>Uppgiften</strong></p>
<p>Bygg en liten webbplats med tre HTML-sidor och en CSS-fil:</p>
<ul>
<li><strong>index.html</strong> – en rubrik och en centrerad bild under rubriken.</li>
<li><strong>about.html</strong> – en rubrik, en kort beskrivning av dig själv och en bild, högst 400 pixlar.</li>
<li><strong>video.html</strong> – en rubrik och två inbäddade videoklipp, var och en med en underrubrik.</li>
<li><strong>styles.css</strong> – h1 i 38 px, h3 i 20 px och egna färger.</li>
</ul>
<p>Alla sidor ska ha <code>lang="sv"</code>, <code>meta charset</code>, en titel, en länk till styles.css, en meny till alla tre sidorna och alt-text på bilderna. Bilderna ligger i mappen bilder/ och länkas med relativ sökväg.</p>
</div>

<p><a class="knapp" href="{{ '/demos/own-website/index.html' | relative_url }}" target="_blank" rel="noopener">Öppna min webbsida ↗</a></p>

<figure class="uppg-bild"><img src="{{ '/assets/img/uppgifter/egen-start.webp' | relative_url }}" alt="Startsidan: rubriken Hannah Kodad, menyn och en bild på vildgäss vid en sjö." width="1000" height="583" loading="lazy"><figcaption>Start</figcaption></figure>

<figure class="uppg-bild"><img src="{{ '/assets/img/uppgifter/egen-om-mig.webp' | relative_url }}" alt="Sidan Om mig med text och ett porträtt av Hannah." width="1000" height="583" loading="lazy"><figcaption>Om mig</figcaption></figure>

Sidorna:

- [Start]({{ '/demos/own-website/index.html' | relative_url }})
- [Om mig]({{ '/demos/own-website/about.html' | relative_url }})
- [Hannah guide]({{ '/demos/own-website/video.html' | relative_url }})
