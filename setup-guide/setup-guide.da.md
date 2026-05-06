<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: da
-->

# Opsætningsvejledning

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | 🇩🇰 Dansk | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Tilslut GateTap til din adgangscontroller

## Før du starter

Sørg for, at din iPhone er forbundet til det samme lokale netværk som din adgangscontroller.

GateTap fungerer udelukkende inden for dit lokale netværk og har behov for:
• Controllerens IP-adresse
• Et brugernavn og en adgangskode


## Trin 1: Find controlleradresse og legitimationsoplysninger

For at forbinde GateTap skal du bruge controllerens IP-adresse og loginoplysninger.

Vælg en af følgende muligheder:


## Mulighed A: Spørg din installatør (anbefales)

Hvis dit system blev installeret af en elektriker eller tekniker, har de sandsynligvis allerede konfigureret alt.

I mange tilfælde:
• Controlleren bruger en fast IP-adresse
• Eller routeren tildeler den samme IP via reservation

Bed dem om IP-adressen og loginoplysninger. Dette er normalt den nemmeste og hurtigste måde.


## Mulighed B: Tjek din router

Åbn din routers konfigurationsside og se efter tilsluttede enheder.

For at få adgang til din router skal du normalt bruge dens lokale adresse (f.eks. `192.168.1.1` eller et navn som `fritz.box`) og routerens loginoplysninger.

Dette afsnit kan kaldes:
• Tilsluttede enheder
• LAN
• DHCP-klienter

Se efter:
• Ukendte kablede enheder
• Indgange, der kan repræsentere din controller

IP-adressen vil normalt se sådan ud:
`192.168.x.x` eller `10.0.x.x`.

![Eksempel på routerforbundne enheder](../assets/setup-guide/da/img_01.png)


## Mulighed C: Scan dit netværk

Brug en netværksscanner-app på din iPhone eller computer.

Scan dit netværk, og prøv at åbne opdagede IP-adresser i Safari, for eksempel:

`http://192.168.1.50`

Hvis controllerens login-side vises, har du fundet den korrekte adresse.

![Netværksscannereksempel](../assets/setup-guide/da/img_02.png)


## Trin 2: Tilføj controlleren i GateTap

Åbn GateTap og indtast:
• IP-adressen
• Dit brugernavn
• Din adgangskode

Brug de samme legitimationsoplysninger som til controllerens webgrænseflade.


## Trin 3: Test forbindelsen

Gem din konfiguration og prøv at åbne en dør eller låge.

Hvis der ikke sker noget, så tjek:
• Din iPhone er på det samme netværk
• IP-adressen er korrekt
• Controlleren er strømforsynet og tilgængelig


## Trin 4: Hold IP-adressen stabil

For at undgå problemer senere bør controlleren altid bruge den samme IP-adresse.

Dette kan gøres ved at:
• Indstilling af en statisk IP på controlleren
• Oprettelse af en DHCP reservation i din router


## Sikkerhed

Dine data forbliver på din enhed.

Du kan valgfrit beskytte GateTap ved hjælp af Face ID eller Touch ID i appindstillingerne.


