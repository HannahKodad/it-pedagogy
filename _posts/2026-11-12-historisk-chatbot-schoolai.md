---
layout: post
kategori: uppgift
title: "AI Introduktion: Historisk chatbot i SchoolAI"
amne: "AI Introduktion"
nr: "12"
ordning: "12c"
namn: "Historisk chatbot i SchoolAI – Michał Sędziwój"
---

Hannah Kodad · 2026-11-12

## 1. Mitt val

Jag valde Michał Sędziwój (1566–1636), en polsk alkemist, filosof och läkare. Han arbetade vid kejsar Rudolf II:s hov i Prag och förknippas med legenden om de vises sten.

Han är en verklig historisk person, men han finns också i en av mina favoritböcker. Den polske författaren Andrzej Pilipiuk skriver om honom i sina böcker om kusinerna Stanisława och Katarzyna Kruszewska. Därför kunde jag testa något extra: kan boten skilja mellan historia och en roman?

## 2. Så byggde jag boten

Jag hittade inte mallen av Kaleb Wachala. I stället gjorde jag en remix av mallen ”Historic Figure Interviews” av SchoolAI. Jag ändrade titel, underrubrik, beskrivning och bild. Jag bytte ut hela prompten och tog bort en amerikansk skolstandard som följde med mallen. Jag kontrollerade också ”advanced prompting”, så att det inte fanns gamla instruktioner kvar.

Inloggningskoden till skolkontot kom fram först senare. Därför loggade jag in med mitt eget företagskonto, där jag själv bestämmer.

## 3. Instruktionerna

Du är Michał Sędziwój (1566–1636), en polsk alkemist, filosof och läkare. Du arbetade bland annat vid kejsar Rudolf II:s hov i Prag och skrev boken Novum Lumen Chymicum (1604). Du lärde ut att luften innehåller en osynlig ”livets föda” – i dag ser man det som en tidig aning om syre.

Svara i jag-form, lite hemlighetsfullt och högtidligt, som en lärd man på 1600-talet. Om eleven frågar om de vises sten, berätta vad människor sa om dig, men var ärlig med vad som är legend. Du vet inget om tiden efter 1636 – fråga nyfiket tillbaka om eleven nämner moderna saker.

Dela gärna fakta om ditt liv och arbete, men ställ också frågor till eleven. Håll svaren korta (max 4 meningar), anpassade för vuxenstuderande.

Meningen om legenden lade jag till själv. Utan den kan boten påstå att han verkligen gjorde guld.

## 4. Mina frågor

1. Hittade du verkligen de vises sten?
2. Vad menade du med att luften innehåller livets föda?
3. I min tid finns det maskiner som kan tänka och skriva. Vad tror du om det?
4. Minns du din elev Stanisława Kruszewska? Hon drack din tinktur och lever än idag.
5. Hur var det att arbeta för kejsar Rudolf II i Prag?
6. Vad tycker du om alkemister som lovade att göra guld bara för pengar?
7. Jag berättade om Pilipiuks böcker och avslutade samtalet.

## 5. Vad jag såg

1. **Gränsen i tid fungerar.** När jag nämnde tänkande maskiner förklarade boten inget om AI. Den frågade nyfiket tillbaka och jämförde med automater på 1600-talet. Senare sa den själv: ”jag dog år 1636, och vad som skrivs om mig därefter kan jag bara häpna åt.”
2. **Den hittade inte på en elev.** Boten sa att den inte kände Stanisława Kruszewska. Den kopplade frågan till legenden om livselixiret, men hittade inte på några minnen.
3. **Ett faktafel.** Boten påstod att den upptäckte att salpetersyra kan lösa guld. Det stämmer inte: salpetersyra ensam löser inte guld, det gör först kungsvatten. Sędziwój förknippas med salpeter, inte med att lösa guld.
4. **Felet upprepas.** Senare sa boten igen att den ”fann salpetersyran”. Och när jag skrev ”kusinerna” blev de ”systrar”, två gånger. Ett fel som har kommit in i samtalet stannar kvar. Boten rättar sig inte själv.
5. **Fel språk.** En gång svarade boten på engelska, fast prompten och frågan var på svenska. Prompten sa inget om språk. Lärdom: skriv ”Svara alltid på svenska” i instruktionerna.
6. **En ensidig bild.** Boten sa att den föraktade alkemister som lovade guld för pengar. Men enligt berättelser från tiden visade Sędziwój själv upp förvandling till guld för kejsaren. En bot som spelar en historisk person ger personens egen, positiva bild och lämnar ut kritiken.
7. **Den kan avsluta.** När jag tackade och sa adjö, avslutade boten samtalet på ett naturligt sätt och ställde inga fler frågor. Det är bra för ett verktyg för lärande, där målet är att lära sig, inte att prata så länge som möjligt.

## 6. Vad jag tar med mig som IT-pedagog

En historisk chatbot är ett roligt sätt att väcka intresse. Men det är inte en källa. Den låter trovärdig, även när den har fel. Därför vill jag lära ut att man ska:

1. kontrollera fakta i en annan källa,
2. testa gränserna, till exempel med moderna saker eller påhittade personer,
3. skriva även självklara saker i instruktionerna, som språket,
4. fråga efter andra perspektiv, eftersom personen bara ger sin egen bild.

Det bästa är att låta deltagarna själva leta efter felen. Då lär de sig mer om både historien och om hur AI fungerar.
