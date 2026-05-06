<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: sv
-->

# Installationsguide

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | 🇸🇪 Svenska | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Anslut GateTap till din åtkomstkontroll

## Innan du börjar

Se till att din iPhone är ansluten till samma lokala nätverk som din åtkomstkontroll.

GateTap fungerar helt inom ditt lokala nätverk och behöver:
• Styrenhetens IP-adress
• Ett användarnamn och lösenord


## Steg 1: Hitta kontrollens adress och användaruppgifter

För att ansluta GateTap behöver du kontrollenhetens IP-adress och inloggningsuppgifter.

Välj ett av följande alternativ:


## Alternativ A: Fråga din installatör (rekommenderas)

Om ditt system installerades av en elektriker eller tekniker, har de förmodligen redan konfigurerat allt.

I många fall:
• Styrenheten använder en fast IP-adress
• Eller så tilldelar routern samma IP via reservation

Fråga dem om IP-adressen och inloggningsuppgifter. Detta är vanligtvis det enklaste och snabbaste sättet.


## Alternativ B: Kontrollera din router

Öppna din routers konfigurationssida och leta efter anslutna enheter.

För att komma åt din router behöver du vanligtvis dess lokala adress (t.ex. `192.168.1.1` eller ett namn som `fritz.box`) och routerns inloggningsuppgifter.

Detta avsnitt kan kallas:
• Anslutna enheter
• LAN
• DHCP-klienter

Leta efter:
• Okända trådbundna enheter
• Poster som kan representera din styrenhet

IP-adressen ser vanligtvis ut så här:
`192.168.x.x` eller `10.0.x.x`.

![Exempel på routeranslutna enheter](../assets/setup-guide/sv/img_01.png)


## Alternativ C: Skanna ditt nätverk

Använd en nätverksskannerapp på din iPhone eller dator.

Skanna ditt nätverk och försök öppna upptäckta IP-adresser i Safari, till exempel:

`http://192.168.1.50`.

Om kontrollenhetens inloggningssida visas har du hittat rätt adress.

![Exempel på nätverksskanner](../assets/setup-guide/sv/img_02.png)


## Steg 2: Lägg till kontrollern i GateTap

Öppna GateTap och skriv in:
• IP-adressen
• Ditt användarnamn
• Ditt lösenord

Använd samma referenser som för kontrollenhetens webbgränssnitt.


## Steg 3: Testa anslutningen

Spara din konfiguration och försök öppna en dörr eller grind.

Om inget händer, kontrollera:
• Din iPhone är på samma nätverk
• IP-adressen är korrekt
• Styrenheten är strömförsörjd och kan nås


## Steg 4: Håll IP-adressen stabil

För att undvika problem senare bör styrenheten alltid använda samma IP-adress.

Detta kan göras genom att:
• Ställa in en statisk IP på styrenheten
• Skapa en DHCP-reservation i din router


## Säkerhet

Din data finns kvar på din enhet.

Du kan valfritt skydda GateTap med Face ID eller Touch ID i appinställningarna.


