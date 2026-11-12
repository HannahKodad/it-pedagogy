---
layout: post
kategori: uppgift
title: "Hemsidor: Vad är HTML?"
amne: "Hemsidor"
del: "Hemsidor 1"
nr: "07"
ordning: "07b"
namn: "Vad är HTML?"
ingress: "De viktigaste HTML-taggarna och attributen – förklarade med egna ord."
---

<div class="uppgiften">
<p><strong>Uppgiften</strong></p>
<p>I denna deluppgift b) ska ni förklara vad respektive html-tagg betyder.<br>Börja med att skapa ett nytt Google dokument. Dokumentet ska ha ett försättsblad och sidnumrering. Kopiera in listan nedan och skriv en kort förklaring efter varje tagg. En eller två meningar räcker. Spara dokumentet med ditt för- och efternamn.</p>
</div>

## Sidans grundstruktur

- `<!DOCTYPE html>` – Visar att dokumentet är skrivet i HTML5. Den ska stå först i dokumentet.
- `<html>` – Visar var HTML-dokumentet börjar och slutar.
- `<head>` – Innehåller information om webbsidan som inte visas direkt på sidan.
- `<title>` – Bestämmer sidans titel som visas i webbläsarens flik.
- `<meta charset="utf-8">` – Gör att webbläsaren kan visa olika tecken rätt, till exempel å, ä och ö.
- `<meta name="viewport">` – Hjälper webbsidan att visas rätt på olika skärmar, till exempel på mobilen.
- `<body>` – Innehåller allt som besökaren ser på webbsidan, till exempel text, bilder och länkar.
- `<link>` – Kopplar HTML-dokumentet till en annan fil, till exempel en CSS-fil som bestämmer sidans utseende.

## Text och innehåll

- `<h1>` till `<h6>` – Används för rubriker. `<h1>` är den viktigaste rubriken och `<h6>` är den minst viktiga.
- `<p>` – Används för att skriva ett stycke text.
- `<strong>` – Markerar viktig text. Texten visas oftast med fet stil.
- `<em>` – Används för att betona ett ord eller en text. Texten visas oftast med kursiv stil.
- `<q>` – Används för korta citat. Webbläsaren lägger vanligtvis till citationstecken.
- `<ul>` och `<li>` – `<ul>` skapar en lista med punkter och `<li>` används för varje punkt i listan.
- `<br>` – Skapar en ny rad i texten utan att börja ett nytt stycke.

## Länkar, bilder och media

- `<a>` – Används för att skapa länkar till andra webbsidor eller filer.
- `<img>` – för att visa bilder på webbsidan.
- `<iframe>` – för att visa innehåll från en annan webbsida, till exempel en karta eller en YouTube-video.
- `<video>` – Används för att spela upp videor direkt på webbsidan.

## Struktur och layout

- `<div>` – Delar upp webbsidan i olika delar och grupperar innehåll.
- `<span>` – Med den här taggen kan man markera en del av texten, till exempel för att ändra färg med CSS.
- `<header>` – Här finns ofta sidans rubrik, logotyp eller meny.
- `<nav>` – Är en navigeringsmeny med länkar till olika delar av webbsidan eller andra sidor.
- `<main>` – Innehåller det viktigaste innehållet på webbsidan.
- `<section>` – Delar upp innehållet i olika avsnitt.
- `<footer>` – Här hittar man ofta kontaktuppgifter eller copyright, vanligtvis längst ner på sidan.

## Inmatning och tabeller

- `<form>` – Är ett formulär.
- `<button>` – Skapar en knapp som man kan klicka på, till exempel för att skicka ett formulär.
- `<table>` – Visar information i en tabell med rader och kolumner.

## Attribut

- `href` – Anger adressen som en länk leder till, till exempel en annan webbsida.
- `src` – Visar var en fil finns, till exempel en bild eller video.
- `alt` – Beskriver en bild med text. Det hjälper personer som inte kan se bilden.
- `lang` – Anger vilket språk som används på webbsidan, till exempel `lang="sv"` för svenska.
- `class` – Ger ett eller flera element samma namn så att man kan ändra deras utseende med CSS.

## Historiefrågan

**`<font>` – den här taggen ska du inte använda. Ta reda på varför den inte längre finns i HTML, och vad man använder i stället.**

Användes tidigare för att ändra textens färg, storlek och typsnitt. Idag använder man CSS i stället, eftersom HTML ska beskriva innehållet och CSS ska bestämma utseendet.
