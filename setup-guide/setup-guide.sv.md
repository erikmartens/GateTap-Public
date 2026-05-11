<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: sv
-->

# Installationsguide

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | 🇸🇪 Svenska | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Anslut GateTap till din åtkomstkontroll

## Innan du börjar

Se till att din enhet är ansluten till samma lokala nätverk som din åtkomstkontroller. Kontrollera till exempel att din iPhone är på hemmets Wi-Fi och inte på mobildata.

GateTap fungerar helt inom ditt lokala nätverk och behöver:
• Kontrollerns IP-adress
• Ett användarnamn och lösenord


## Steg 1: Hitta åtkomstkontrollerns IP-adress

För att ansluta GateTap behöver du kontrollerns IP-adress och inloggningsuppgifter - se steg 2.

Välj ett av följande alternativ:


## Alternativ A: Fråga din installatör (rekommenderas)

Om systemet installerades av en elektriker eller tekniker har de troligen redan konfigurerat allt.

I många fall:
• Använder kontrollern en fast IP-adress
• Eller routern tilldelar samma IP via DHCP-reservation

Be om IP-adressen och inloggningsuppgifterna. Det är oftast det enklaste och snabbaste sättet.


## Alternativ B: Kontrollera din router

Öppna routerns konfigurationssida och leta efter anslutna enheter.

För att komma åt routern behöver du vanligtvis dess lokala adress, till exempel `192.168.1.1` eller ett namn som `fritz.box`, och routerns inloggningsuppgifter.

Det här avsnittet kan heta:
• Nätverk
• Anslutna enheter
• LAN
• DHCP-klienter

Leta efter:
• Okända trådbundna enheter
• Poster som kan motsvara din kontroller

IP-adressen ser vanligtvis ut så här:
`192.168.x.x` eller `10.0.x.x`

![Exempel på anslutna enheter i routern](../assets/setup-guide/sv/img_01_en_US.png)


## Alternativ C: Skanna ditt nätverk

Använd en nätverksskanner-app på din enhet.

Skanna nätverket och försök öppna hittade IP-adresser i Safari, till exempel:

`http://192.168.1.50`

Om åtkomstkontrollerns inloggningssida visas har du hittat rätt adress.

![Exempel på nätverksskanner-app](../assets/setup-guide/sv/img_02_en_US.png)


## Steg 2: Hitta åtkomstkontrollerns inloggningsuppgifter

Vissa kontroller använder fortfarande standardinloggning. Ett vanligt exempel är användarnamnet `abc` med lösenordet `654321`.

Andra vanliga fabriksanvändarnamn är `user`, `admin` eller `123`. Du kan prova dem med typiska lösenord som `1234`, `user` eller `password`, eller en variant av dem.

Om systemet installerades professionellt, fråga installatören om standarduppgifterna ändrades.


## Steg 3: Lägg till åtkomstkontrollern i GateTap

Öppna GateTap och ange:
• IP-adressen
• Ditt användarnamn
• Ditt lösenord

Använd samma uppgifter som för åtkomstkontrollerns webbgränssnitt.


## Steg 4: Testa anslutningen

Spara konfigurationen och försök öppna en dörr eller grind.

Om inget händer, kontrollera:
• Att din enhet är på samma nätverk som åtkomstkontrollern
• Att IP-adressen är korrekt
• Att åtkomstkontrollern har ström och kan nås


## Steg 5: Håll IP-adressen stabil

För att undvika problem senare bör kontrollern alltid använda samma IP-adress.

Det kan göras genom att:
• Ställa in en statisk IP på kontrollern
• Skapa en DHCP-reservation i routern


## Demoläge

GateTap innehåller också ett demoläge. Du kan starta en lokal demo-webbserver från appen och sedan lägga till den som en vanlig kontroller.

Det ger dig en känd fungerande testväg för att kontrollera att GateTap själv fungerar korrekt, även om du för tillfället inte har tillgång till en fysisk åtkomstkontroller.


## Säkerhet

Din data finns kvar på din enhet.

Du kan valfritt skydda GateTap med Face ID eller Touch ID i appinställningarna.


