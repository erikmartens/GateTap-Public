<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: da
-->

# Opsætningsvejledning

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | 🌐 da | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

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


