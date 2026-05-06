<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: nb
-->

# Oppsettveiledning

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | 🇳🇴 Norsk Bokmål | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

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


