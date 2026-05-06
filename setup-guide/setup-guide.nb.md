<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: nb
-->

# Oppsettveiledning

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | 🌐 nb | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

---

Koble GateTap til tilgangskontrolleren

## Før du begynner

Sørg for at iPhone er koblet til det samme lokale nettverket som tilgangskontrolleren.

GateTap fungerer utelukkende innenfor ditt lokale nettverk og trenger:
• Kontrollerens IP-adresse
• Et brukernavn og passord


## Trinn 1: Finn kontrolleradresse og legitimasjon

For å koble til GateTap trenger du kontrollerens IP-adresse og påloggingsinformasjon.

Velg ett av følgende alternativer:


## Alternativ A: Spør installatøren (anbefalt)

Hvis systemet ditt ble installert av en elektriker eller tekniker, har de sannsynligvis allerede konfigurert alt.

I mange tilfeller:
• Kontrolleren bruker en fast IP-adresse
• Eller ruteren tildeler samme IP via reservasjon

Spør dem om IP-adressen og påloggingsdetaljer. Dette er vanligvis den enkleste og raskeste måten.


## Alternativ B: Sjekk ruteren din

Åpne ruterens konfigurasjonsside og se etter tilkoblede enheter.

For å få tilgang til ruteren din trenger du vanligvis dens lokale adresse (f.eks. `192.168.1.1` eller et navn som `fritz.box`) og ruterens påloggingsinformasjon.

Denne delen kan kalles:
• Tilkoblede enheter
• LAN
• DHCP-klienter

Se etter:
• Ukjente kablede enheter
• Oppføringer som kan representere kontrolleren din

IP-adressen vil vanligvis se slik ut:
`192.168.x.x` eller `10.0.x.x`.

![Eksempel på rutertilkoblede enheter](../assets/setup-guide/nb/img_01.png)


## Alternativ C: Skann nettverket ditt

Bruk en nettverksskanner-app på iPhone eller datamaskin.

Skann nettverket ditt og prøv å åpne oppdagede IP-adresser i Safari, for eksempel:

`http://192.168.1.50`

Hvis kontrollerens påloggingsside vises, har du funnet riktig adresse.

![Nettverksskannereksempel](../assets/setup-guide/nb/img_02.png)


## Trinn 2: Legg til kontrolleren i GateTap

Åpne GateTap og skriv inn:
• IP-adressen
• Brukernavnet ditt
• Ditt passord

Bruk samme legitimasjon som for kontrollerens nettgrensesnitt.


## Trinn 3: Test tilkoblingen

Lagre konfigurasjonen og prøv å åpne en dør eller port.

Hvis ingenting skjer, sjekk:
• iPhone er på samme nettverk
• IP-adressen er riktig
• Kontrolleren har strøm og kan nås


## Trinn 4: Hold IP-adressen stabil

For å unngå problemer senere, bør kontrolleren alltid bruke samme IP-adresse.

Dette kan gjøres ved å:
• Stille inn en statisk IP på kontrolleren
• Opprette en DHCP-reservasjon i ruteren


## Sikkerhet

Dataene dine forblir på enheten din.

Du kan eventuelt beskytte GateTap med Face ID eller Touch ID i appinnstillingene.


