---
layout: post
kategori: uppgift
title: "AI Introduktion: AI-modeller, AI-tjänster och upphovsrätt"
amne: "AI Introduktion"
nr: "12"
ordning: "12a"
namn: "AI-modeller, AI-tjänster och upphovsrätt"
---

Hannah Kodad · 2026-11-11

## 1. Vad är skillnaden mellan en AI-modell och en AI-tjänst?

En AI-modell är själva motorn. Den är tränad på stora mängder data, men den har inget eget gränssnitt. Ett exempel är Claude Opus 5.5 från företaget Anthropic.

En AI-tjänst är byggd ovanpå en modell. Den har ett gränssnitt och egna instruktioner, och ibland är den kopplad till dokument eller andra program.

Jag använder själv flera AI-tjänster. Varje morgon får jag en rapport om nya mejl och om allt jag behöver göra för mina kunder. Jag har också en AI-agent som läser mina mejl och skriver utkast till svar. Båda tjänsterna bygger på Claude, men de gör olika saker. Andra exempel på AI-tjänster är AI-funktionerna i Slido och Canva.

## 2. Vilket företag och land ligger bakom en modell du själv väljer, och är den öppen eller stängd?

Jag har valt Claude. Anthropic är ett amerikanskt företag. Det grundades 2021 och ligger i San Francisco. Alla Claude-modeller har stängda vikter. Därför kan man bara använda Claude via Anthropics API eller deras appar. Man kan inte köra modellen lokalt på sin egen dator. Företaget säger att det handlar om säkerhet. Enligt Anthropic kan öppna modeller vara mer riskfyllda. Det är svårare att lägga in skydd i dem och svårare att följa hur de används. När vikterna har publicerats går det inte heller att ta tillbaka dem.

Källa: Anthropic, ”Our position on open-weights models”, 27 juli 2026, <https://www.anthropic.com/news/position-open-weights-models>

## 3. Vad är skillnaden mellan äldre regelbaserad AI och dagens generativa AI-modeller?

Äldre AI byggde på regler som människor skrev för hand, till exempel ”om A, gör B”, och systemet fungerade inte i situationer där det saknades en regel. Dagens generativa AI är ett neuralt nätverk som själv lär sig mönster från enorma mängder data, även bilder, och transformer-tekniken gör att modellen förstår sammanhanget mellan orden. Därför kan den skapa nytt innehåll, och vi säger att den genererar det, men vi vet inte varför modellen svarade just på det sättet. Svaret är en statistisk gissning som inte alltid överensstämmer med den information vi vill ha, och då säger vi att modellen hallucinerar eller hittar på.

## 4. Vem äger resultatet när en AI genererar en bild eller text?

Enligt Anthropics villkor får jag alla rättigheter till det som Claude skapar, ”om det finns några”. Men enligt upphovsrätten i Sverige och EU kan bara en människa vara upphovsperson. Material som AI har skapat helt själv har därför ingen upphovsrätt. Det räcker oftast inte att bara skriva en prompt. Om jag själv arbetar mycket med resultatet, till exempel ger bra instruktioner, ändrar, väljer och skriver om, kan det bli ett AI-assisterat verk som skyddas. Det är min egen insats som räknas.

När jag använder AI-material i undervisning ska jag skriva tydligt att det är skapat med AI. Jag ska inte sätta mitt namn på det som om jag hade gjort allt själv. Jag ska också kontrollera att materialet inte kopierar någon annans verk och följa skolans riktlinjer för AI.

*Apropo: Därför skriver jag direkt här att jag alltid arbetar tillsammans med AI när jag svarar på uppgifter i skolan. AI hjälper mig att formulera mina tankar och att söka källor. Den rättar mina fel och förklarar var och varför jag har gjort dem. Framför allt hjälper den mig att formulera allt rätt på svenska.*

Källor:

- Anthropic, Consumer Terms of Service:
  - <https://www.anthropic.com/legal/consumer-terms>
- KLYS, AI-rekommendationer (2025):
  - <https://klys.se/wp-content/uploads/2025/06/KLYS-AI-Rekommendationer-FINAL.pdf>
- Skolverket, Råd om AI:
  - <https://www.skolverket.se/ai>

## 5. Vilka tre olika inlärningsmodeller finns det, och vad skiljer dem åt?

**Övervakad inlärning (supervised learning):** Modellen lär sig från exempel där det rätta svaret redan finns. Ett exempel är min app för svenska. Om jag ger modellen många av mina gamla svar, där varje svar är märkt som rätt eller fel, kan den lära sig vilka ord jag ofta gör fel på.

**Oövervakad inlärning (unsupervised learning):** Modellen får data utan rätta svar och hittar själv grupper och mönster. Ett exempel är Babička na treku. Modellen kan läsa svaren från anmälningsformuläret och själv dela in deltagarna i grupper, till exempel de som vill gå korta dagsturer och de som vill gå långa vandringar.

**Förstärkningsinlärning (reinforcement learning):** Modellen provar olika saker och får belöning när det går bra. Belöningen är en signal, till exempel en siffra, som används när modellen tränas. Ett exempel är tummen upp under ett svar i Claude. Anthropic kan använda den återkopplingen när de tränar nästa version av modellen, så att den lär sig vilka svar människor tycker är bra. Men om jag skriver ”bra jobbat, tack” i chatten, lär sig modellen ingenting av det. Den ser mitt beröm i samtalet, men den ändras inte.
