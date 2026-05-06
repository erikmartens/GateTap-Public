<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: de
-->

# Einrichtungsanleitung

---

🌍 **Dieses Dokument ist in anderen Sprachen verfügbar:**  
[🇺🇸 English](setup-guide.en.md) | 🇩🇪 Deutsch | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

---

GateTap mit deinem Zutrittscontroller verbinden

## Bevor du beginnst

Stelle sicher, dass dein iPhone mit demselben Netzwerk verbunden ist wie dein Zutrittscontroller.

GateTap benötigt:
• Die IP-Adresse des Controllers
• Benutzername und Passwort


## Schritt 1: Adresse und Zugangsdaten finden

Um GateTap zu verbinden, benötigst du die IP-Adresse und die Zugangsdaten des Controllers.

Wähle eine der folgenden Möglichkeiten:


## Option A: Installateur fragen (empfohlen)

Wenn dein System von einem Elektriker oder Techniker eingerichtet wurde, ist der Controller meist bereits konfiguriert.

Oft gilt:
• Feste IP-Adresse ist vergeben
• Oder im Router reserviert

Frage nach der IP-Adresse und den Zugangsdaten. Das ist meist der einfachste Weg.


## Option B: Router prüfen

Öffne die Benutzeroberfläche deines Routers und suche nach verbundenen Geräten.

Um auf den Router zuzugreifen, benötigst du in der Regel dessen lokale Adresse (z. B. `192.168.1.1` oder `fritz.box`) sowie die Zugangsdaten für den Router.

Dieser Bereich kann heißen:
• Verbundene Geräte
• LAN
• DHCP-Clients

Suche nach:
• Unbekannten kabelgebundenen Geräten
• Einträgen, die deinem Controller entsprechen könnten

Die IP-Adresse sieht meist so aus:
`192.168.x.x` oder `10.0.x.x`

![Beispiel für verbundene Geräte im Router](../assets/setup-guide/de/img_01.png)


## Option C: Netzwerk scannen

Verwende eine Netzwerk-Scanner-App auf deinem iPhone oder Computer.

Scanne dein Netzwerk und öffne gefundene IP-Adressen im Browser, z. B.:

`http://192.168.1.50`

Wenn die Login-Seite erscheint, hast du die richtige Adresse gefunden.

![Beispiel für eine Netzwerk-Scanner-App](../assets/setup-guide/de/img_02.png)


## Schritt 2: Controller in GateTap hinzufügen

Öffne GateTap und gib ein:
• IP-Adresse
• Benutzername
• Passwort

Verwende die gleichen Zugangsdaten wie für die Weboberfläche.


## Schritt 3: Verbindung testen

Speichere die Konfiguration und teste eine Tür oder ein Tor.

Wenn nichts passiert, prüfe:
• iPhone im gleichen Netzwerk
• IP-Adresse korrekt
• Controller eingeschaltet und erreichbar


## Schritt 4: Feste IP-Adresse verwenden

Damit es später keine Probleme gibt, sollte der Controller immer die gleiche IP-Adresse verwenden.

Das erreichst du durch:
• Statische IP im Gerät
• DHCP-Reservierung im Router


## Sicherheit

Deine Daten bleiben auf deinem Gerät.

Optional kannst du GateTap mit Face ID oder Touch ID schützen.


