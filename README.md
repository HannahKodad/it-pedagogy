# Hannah Kodad – skolwebbplats (IT-pedagog, Tärna folkhögskola)

Byggd med Jekyll och publicerad på GitHub Pages. Ren HTML och CSS, inga skript, inga cookies, typsnitten ligger på webbplatsen.

## Var ändrar jag vad?
| Vad | Fil |
|---|---|
| Färger, typsnitt, former | `assets/css/farger.css` |
| Layout och komponenter | `assets/css/style.css` |
| Menyn | `_data/meny.yml` |
| E-post och sociala medier | `_data/kontakt.yml` |
| Länksidan | `_data/lankar.yml` |
| Sidhuvud, sidfot, SEO | `_includes/` |
| Sidornas text | `index.html`, `_includes/hero.html`, `om-mig.md` |

## Ny uppgift (inlägg)
Skapa en fil i `_posts`, t.ex. `2026-11-13-slido-och-pic-rat.md`:
```
---
layout: post
kategori: uppgift
title: "Slido och PIC-RAT"
kurs: Pedagogik och digitala verktyg
ingress: "En mening som sammanfattar."
---
Texten här.
```
Med `kategori: skapar` (och gärna `typ: Haiku`, `bild: /assets/img/namn.webp`, `bildtext: ...`) visas inlägget i stället som "Senaste" på startsidan.

## Google och AI
`sitemap.xml`, `robots.txt`, `llms.txt`, metabeskrivning och Open Graph på varje sida, strukturerad data (schema.org) i `_includes/head.html`.

## Språk
Svenska först. Tjeckiska kommer i mappen `cs/`, engelska i `en/`.
