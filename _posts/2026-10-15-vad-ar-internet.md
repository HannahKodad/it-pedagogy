---
layout: post
kategori: uppgift
title: "Hemsidor: Vad är internet?"
amne: "Hemsidor"
del: "Hemsidor 1"
nr: "07"
ordning: "07a"
namn: "Vad är internet?"
ingress: "Mina svar med egna ord: ARPANET, DNS, TCP/IP, HTTPS, IPv6, VPN, molnet, cookies och mer."
---

**1. Vilket år togs ARPANET i drift, och vad var det ursprungliga syftet med nätverket?**

ARPANET togs i drift år 1969 för att koppla samman fyra forskningsinstitutioner, så att forskare kunde dela på dyra datorer och deras datorkapacitet.

Från början bestod nätverket av fyra datornoder vid amerikanska universitet och forskningsinstitutioner.

Projektet finansierades av den amerikanska myndigheten ARPA.

**2. Beskriv steg för steg vad som händer från att du skriver in en webbadress i webbläsaren till att sidan visas på skärmen. Ta med minst fem steg. Detta är kursens viktigaste fråga.**

1. Först skriver jag webbadressen i webbläsarens adressfält.
2. Datorn frågar DNS vilken IP-adress som hör till webbadressen.
3. DNS svarar och skickar tillbaka IP-adressen.
4. Webbläsaren kopplar upp sig mot servern. Vid HTTPS skapas en krypterad anslutning.
5. Webbläsaren skickar en begäran till servern om att få webbsidan.
6. Servern svarar och skickar tillbaka en HTML-fil.
7. Webbläsaren hämtar också andra filer som behövs, till exempel CSS, bilder och JavaScript.
8. Till slut läser webbläsaren filerna och visar webbsidan på skärmen.

Informationen skickas över internet i små datapaket.

**3. Vad är TCP/IP-protokollet och varför är det avgörande för att datorer över hela världen kan kommunicera med varandra?**

TCP/IP är en samling regler som gör att datorer kan kommunicera med varandra via internet.

- TCP (Transmission Control Protocol) ser till att datapaketen kommer fram i rätt ordning och att information som saknas skickas igen.
- IP (Internet Protocol) ansvarar för adressering och att datapaket skickas till rätt destination.

TCP/IP gör det möjligt för olika datorer och nätverk över hela världen kommunicera med varandra, även om de använder olika operativsystem.

**4. Vad innebär DNS (Domain Name System) och varför behövs det för att kunna surfa på nätet?**

DNS (Domain Name System) är ett system som översätter domännamn, till exempel www.google.se, till IP-adresser.

Vi skriver en vanlig webbadress och DNS omvandlar den till en IP-adress som datorn kan använda.

DNS fungerar som en telefonbok för internet.

**5. Vad är skillnaden mellan HTTP och HTTPS? Vilken port används vid HTTPS-kommunikation? Nämn också en sak som HTTPS inte skyddar dig mot.**

HTTP och HTTPS är protokoll som används för kommunikation mellan webbläsaren och webbservern.

Skillnaden är att HTTPS krypterar informationen, medan HTTP inte gör det. Det betyder att HTTPS skyddar informationen under överföringen. HTTPS använder normalt port 443.

HTTPS skyddar oss inte mot falska eller bedrägliga webbplatser. En webbsida kan vara farlig även om den använder HTTPS.

**6. Hur många adresser finns det i IPv4, och varför behövs IPv6?**

IPv4 använder 32-bitars adresser och har ungefär 4,3 miljarder möjliga IP-adresser.

Men eftersom finns det väldigt många datorer, mobiltelefoner och andra enheter som är anslutna till internet, därför räcker inte IPv4-adresserna till för alla.

IPv6 använder 128-bitars adresser och erbjuder ett mycket större antal IP-adresser. Det gör att fler enheter kan få egna IP-adresser och kommunicera via internet.

**7. Vad innebär det att surfa via en VPN, och varför kan det vara användbart? Nämn också minst en sak ett VPN inte skyddar dig mot.**

VPN är som en krypterad tunnel mellan min dator och en server på distans.

VPN kan vara användbart när jag använder offentligt Wi-Fi eller vill skydda min integritet på internet.

Men VPN skyddar mig inte mot virus, falska webbplatser eller bedrägerier. VPN gör mig inte heller helt anonym på internet.

**8. Vad innebär "molnet" och var lagras våra filer rent fysiskt när vi använder tjänster som Google Drive eller OneDrive?**

Molnet är stora datalagringssystem på distans där jag kan lagra mina filer via internet. Till exempel Google Drive, iCloud och andra tjänster. Det handlar om fysiska datacenter som kan finnas på olika platser runt om i världen.

Jag kan komma åt mina filer i molnet från olika enheter, till exempel mobiltelefon, dator och surfplatta.

**9. Vad är skillnaden mellan ett domännamn, ett webbhotell och en webbplats? Ta reda på vad ett .se-domännamn och ett enkelt webbhotell kostar per år idag, och ange var du hittade priset.**

Ett domännamn är webbsidans adress på internet, till exempel www.tarna.fhsk.se. Webbhotellet är utrymmet på en server där webbplatsen lagras. Domännamnet är webbplatsens adress på internet och webbplatsen är själva innehållet.

Jag hittade följande priser hos one.com:

- En .se-domän kostar 9 kr första året och sedan 269 kr per år.
- Ett enkelt webbhotell, Starter, kostar 348 kr första året (29 kr/månad). Vid förnyelse kostar det 948 kr per år.

**10. Varför väljer de flesta att bygga sin webbplats i ett CMS som WordPress i stället för att handkoda allt själva? Nämn en fördel och en nackdel.**

De flesta använder CMS, till exempel WordPress och andra plattformar, eftersom de inte kan skriva kod eller inte vill lägga tid på det. De föredrar att använda ett färdigt system för att hantera sin webbplats.

När jag skriver koden själv vet jag exakt vad som finns var och hur allt fungerar. Jag har också större kontroll över webbplatsen. När jag använder WordPress eller en annan plattform måste jag anpassa mina krav efter systemets möjligheter.

Fördelen med CMS är att det sparar tid och gör det enklare att hantera en webbplats. Nackdelen är de begränsningar som plattformen har.

**11. Vad är en kaka (cookie), och varför måste svenska webbplatser fråga om ditt samtycke innan de sätter vissa kakor?**

En cookie (kaka) är en liten textfil som en webbplats sparar i min webbläsare. Cookies används till exempel för att komma ihåg mina inställningar, hålla mig inloggad eller samla information om hur jag använder webbplatsen.

I Sverige och andra EU-länder måste användaren ge sitt samtycke till cookies som inte är nödvändiga för att webbplatsen ska fungera. Genom samtycket kan användaren också godkänna att vissa personuppgifter behandlas. Användaren kan välja vilka cookies som ska tillåtas och begränsa användningen av dem.

**12. Ge ett exempel på en ny teknik eller trend (till exempel AI, 5G eller sakernas internet) som påverkar hur vi använder internet idag. Förklara kort varför den är viktig – och nämn också ett problem som tekniken skapar.**

Stora språkmodeller (LLM) används oftast via internet och behöver en internetanslutning för att användas som molntjänster. Dessutom kräver de enorma mängder energi för sina beräkningar. Det är en stor nackdel med tekniken.
