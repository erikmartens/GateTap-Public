<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: nb
-->

# Oppsettveiledning

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | 🇳🇴 Norsk Bokmål | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Koble GateTap til tilgangskontrolleren

## Før du begynner

Sørg for at enheten din er koblet til det samme lokale nettverket som tilgangskontrolleren. Kontroller for eksempel at iPhone er på hjemmets Wi-Fi, ikke på mobildata.

GateTap fungerer helt innenfor det lokale nettverket ditt og trenger:

- Kontrollerens IP-adresse
- Et brukernavn og et passord


## Trinn 1: Finn IP-adressen til tilgangskontrolleren

For å koble til GateTap trenger du kontrollerens IP-adresse og innloggingsopplysninger - se trinn 2.

Velg ett av følgende alternativer:


## Alternativ A: Spør installatøren (anbefalt)

Hvis systemet ble installert av en elektriker eller tekniker, har de sannsynligvis allerede konfigurert alt.

I mange tilfeller:

- Bruker kontrolleren en fast IP-adresse
- Eller ruteren tildeler samme IP via DHCP-reservasjon

Be om IP-adressen og innloggingsopplysningene. Dette er vanligvis den enkleste og raskeste måten.


## Alternativ B: Sjekk ruteren din

Åpne ruterens konfigurasjonsside og se etter tilkoblede enheter.

For å få tilgang til ruteren trenger du vanligvis den lokale adressen, for eksempel `192.168.1.1` eller et navn som `fritz.box`, og ruterens innloggingsopplysninger.

Denne delen kan hete:

- Nettverk
- Tilkoblede enheter
- LAN
- DHCP-klienter

Se etter:

- Ukjente kablede enheter
- Oppføringer som kan representere kontrolleren

IP-adressen ser vanligvis slik ut:
`192.168.x.x` eller `10.0.x.x`

![Eksempel på tilkoblede enheter i ruteren](../assets/setup-guide/nb/img_01_en_US.png)


## Alternativ C: Skann nettverket ditt

Bruk en nettverksskanner-app på enheten din.

Skann nettverket og prøv å åpne IP-adresser som blir funnet i Safari, for eksempel:

`http://192.168.1.50`

Hvis innloggingssiden til tilgangskontrolleren vises, har du funnet riktig adresse.

![Eksempel på nettverksskanner-app](../assets/setup-guide/nb/img_02_en_US.png)


## Trinn 2: Finn innloggingsopplysningene til tilgangskontrolleren

Noen kontrollere bruker fortsatt standard innloggingsopplysninger. Et vanlig eksempel er brukernavnet `abc` med passordet `654321`.

Andre vanlige fabrikkbrukernavn er `user`, `admin` eller `123`. Du kan prøve dem sammen med typiske passord som `1234`, `user` eller `password`, eller en variant av disse.

Hvis systemet ble installert profesjonelt, spør installatøren om standardopplysningene ble endret.


## Trinn 3: Legg til tilgangskontrolleren i GateTap

Åpne GateTap og skriv inn:

- IP-adressen
- Brukernavnet ditt
- Passordet ditt

Bruk de samme opplysningene som for tilgangskontrollerens webgrensesnitt.


## Trinn 4: Test tilkoblingen

Lagre konfigurasjonen og prøv å åpne en dør eller port.

Hvis ingenting skjer, sjekk:

- At enheten din er på samme nettverk som tilgangskontrolleren
- At IP-adressen er riktig
- At tilgangskontrolleren har strøm og kan nås


## Trinn 5: Hold IP-adressen stabil

For å unngå problemer senere bør kontrolleren alltid bruke samme IP-adresse.

Dette kan gjøres ved å:

- Angi en statisk IP på kontrolleren
- Opprette en DHCP-reservasjon i ruteren


## Demomodus

GateTap har også en demomodus. Du kan starte en lokal demo-webserver fra appen og deretter legge den til som en vanlig kontroller.

Dette gir deg en kjent fungerende testvei for å bekrefte at GateTap selv fungerer riktig, selv om du for øyeblikket ikke har tilgang til en fysisk tilgangskontroller.


## Sikkerhet

Dataene dine forblir på enheten din.

Du kan eventuelt beskytte GateTap med Face ID eller Touch ID i appinnstillingene.


