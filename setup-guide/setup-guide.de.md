<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: de
-->

# Einrichtungsanleitung

---

🌍 **Dieses Dokument ist in anderen Sprachen verfügbar:**  
[🇺🇸 English](setup-guide.en.md) | 🇩🇪 Deutsch | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

GateTap mit deinem Zutritts-Controller verbinden

## Bevor du beginnst

Stelle sicher, dass dein Gerät mit demselben Netzwerk verbunden ist wie dein Zutritts-Controller. Achte beispielsweise darauf, dass dein iPhone mit deinem Heim-WLAN verbunden ist und nicht nur mit dem mobilen Datennetz.

GateTap benötigt:

- Die IP-Adresse des Controllers
- Benutzername und Passwort


## Schritt 1: IP-Adresse finden

Um GateTap zu verbinden, benötigst du die IP-Adresse (und die Login-Daten des Controllers - siehe Schritt 2).

Wähle eine der folgenden Möglichkeiten:


## Option A: Installateur fragen (empfohlen)

Wenn dein System von einem Elektriker oder Techniker eingerichtet wurde, ist der Zutritts-Controller meist bereits konfiguriert.

Oft gilt:

- Feste IP-Adresse ist vergeben
- Oder im Router reserviert

Frage nach der IP-Adresse und den Login-Daten. Das ist meist der einfachste Weg.


## Option B: Router prüfen

Öffne die Benutzeroberfläche deines Routers und suche nach verbundenen Geräten.

Um auf den Router zuzugreifen, benötigst du in der Regel dessen lokale IP-Adresse (z. B. `192.168.1.1`) sowie die Login-Daten für den Router.

Dieser Bereich kann heißen:

- Heimnetzwerk
- Verbundene Geräte
- LAN
- DHCP-Clients

Suche nach:

- Unbekannten kabelgebundenen Geräten
- Einträgen, die deinem Controller entsprechen könnten

Die IP-Adresse sieht meist so aus:
`192.168.x.x` oder `10.0.x.x`

![Beispiel für verbundene Geräte im Router](../assets/setup-guide/de/img_01_de_de.png)


## Option C: Netzwerk scannen

Verwende eine Netzwerk-Scanner-App auf deinem Gerät.

Scanne dein Netzwerk und öffne gefundene IP-Adressen im Browser, z. B.:

`http://192.168.1.50`

Wenn die Login-Seite erscheint, hast du die richtige IP-Adresse gefunden.

![Beispiel für eine Netzwerk-Scanner-App](../assets/setup-guide/de/img_02_de_de.png)


## Schritt 2: Login-Daten finden

Es kann sein, dass auf deinem Zutritts-Controller noch Standard-Login-Daten hinterlegt sind. Ein häufiges Beispiel ist der Benutzername `abc` mit dem Passwort `654321`.

Weitere häufig verwendete Standard-Benutzernamen sind `user`, `admin` oder `123`. Du kannst sie mit typischen Passwörtern wie `1234`, `user` oder `password` bzw. einer Abwandlung davon ausprobieren.

Wenn dein System professionell installiert wurde, frage deinen Installateur, ob die Standard-Zugangsdaten geändert wurden.


## Schritt 3: Controller in GateTap hinzufügen

Öffne GateTap und gib ein:

- IP-Adresse
- Benutzername
- Passwort

Verwende die gleichen Login-Daten wie für die Weboberfläche.


## Schritt 4: Verbindung testen

Speichere die Konfiguration und teste eine Tür oder ein Tor.

Wenn nichts passiert, prüfe:

- Gerät mit der App im gleichen Netzwerk
- IP-Adresse korrekt
- Zutritts-Controller eingeschaltet und erreichbar


## Schritt 5: Feste IP-Adresse verwenden

Damit es später keine Probleme gibt, sollte der Zutritts-Controller immer die gleiche IP-Adresse verwenden.

Das erreichst du durch:

- Statische IP im Gerät
- DHCP-Reservierung im Router


## Demo Modus

GateTap enthält außerdem einen Demo Modus. Du kannst direkt in der App einen lokalen Demo-Webserver starten und ihn anschließend wie einen normalen Controller hinzufügen.

So hast du einen zuverlässig funktionierenden Testweg, um zu prüfen, ob GateTap selbst korrekt funktioniert – auch wenn du gerade keinen physischen Zugangs-Controller zur Verfügung hast.


## Sicherheit

Deine Daten bleiben auf deinem Gerät.

Optional kannst du GateTap mit Face ID oder Touch ID schützen.


