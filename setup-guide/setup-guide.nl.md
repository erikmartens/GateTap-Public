<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: nl
-->

# Installatiehandleiding

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | 🌐 nl | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

---

Sluit GateTap aan op uw toegangscontroller

## Voordat je begint

Zorg ervoor dat uw iPhone is verbonden met hetzelfde lokale netwerk als uw toegangscontroller.

GateTap werkt volledig binnen uw lokale netwerk en heeft het volgende nodig:
• Het IP-adres van de controller
• Een gebruikersnaam en wachtwoord


## Stap 1: Vind het controlleradres en de inloggegevens

Om GateTap te verbinden, hebt u het IP-adres en de inloggegevens van de controller nodig.

Kies een van de volgende opties:


## Optie A: Vraag uw installateur (aanbevolen)

Als uw systeem door een elektricien of technicus is geïnstalleerd, heeft deze waarschijnlijk alles al geconfigureerd.

In veel gevallen:
• De controller gebruikt een vast IP-adres
• Of de router wijst via reservering hetzelfde IP-adres toe

Vraag hen om het IP-adres en de inloggegevens. Dit is meestal de gemakkelijkste en snelste manier.


## Optie B: Controleer uw router

Open de configuratiepagina van uw router en zoek naar aangesloten apparaten.

Om toegang te krijgen tot uw router heeft u doorgaans het lokale adres nodig (bijvoorbeeld `192.168.1.1` of een naam als `fritz.box`) en de inloggegevens van de router.

Dit gedeelte kan heten:
• Verbonden apparaten
• LAN
• DHCP-clients

Zoek naar:
• Onbekende bekabelde apparaten
• Vermeldingen die mogelijk uw controller vertegenwoordigen

Het IP-adres ziet er meestal als volgt uit:
`192.168.x.x` of `10.0.x.x`

![Voorbeeld van met router verbonden apparaten](../assets/setup-guide/nl/img_01.png)


## Optie C: Scan uw netwerk

Gebruik een netwerkscanner-app op uw iPhone of computer.

Scan uw netwerk en probeer ontdekte IP-adressen in Safari te openen, bijvoorbeeld:

`http://192.168.1.50`

Als de inlogpagina van de controller verschijnt, heeft u het juiste adres gevonden.

![Voorbeeld netwerkscanner](../assets/setup-guide/nl/img_02.png)


## Stap 2: Voeg de controller toe in GateTap

Open GateTap en voer in:
• Het IP-adres
• Uw gebruikersnaam
• Uw wachtwoord

Gebruik dezelfde inloggegevens als voor de webinterface van de controller.


## Stap 3: Test de verbinding

Sla uw configuratie op en probeer een deur of poort te openen.

Als er niets gebeurt, controleer dan:
• Uw iPhone bevindt zich op hetzelfde netwerk
• Het IP-adres is correct
• De controller is voorzien van stroom en is bereikbaar


## Stap 4: Houd het IP-adres stabiel

Om later problemen te voorkomen, moet de controller altijd hetzelfde IP-adres gebruiken.

Dit kan gedaan worden door:
• Een statisch IP-adres instellen op de controller
• Een DHCP-reservering aanmaken in uw router


## Beveiliging

Uw gegevens blijven op uw apparaat.

U kunt GateTap optioneel beveiligen met Face ID of Touch ID in de app-instellingen.


