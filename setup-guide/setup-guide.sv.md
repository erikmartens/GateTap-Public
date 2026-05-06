<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: sv
-->

# Installationsguide

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | 🌐 sv | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

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


