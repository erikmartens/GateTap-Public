<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: ca
-->

# Guia de configuració

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | 🇪🇸 Català | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Connecteu GateTap al vostre controlador d'accés

## Abans de començar

Assegureu-vos que el vostre iPhone estigui connectat a la mateixa xarxa local que el controlador d'accés.

GateTap funciona completament a la vostra xarxa local i necessita:
• L'adreça IP del controlador
• Un nom d'usuari i una contrasenya


## Pas 1: cerqueu l'adreça i les credencials del controlador

Per connectar GateTap, necessiteu l'adreça IP del controlador i les credencials d'inici de sessió.

Trieu una de les opcions següents:


## Opció A: pregunteu al vostre instal·lador (recomanat)

Si el vostre sistema l'ha instal·lat un electricista o tècnic, és probable que ja ho hagin configurat tot.

En molts casos:
• El controlador utilitza una adreça IP fixa
• O l'encaminador assigna la mateixa IP mitjançant reserva

Demaneu-los l'adreça IP i les dades d'inici de sessió. Aquesta sol ser la manera més fàcil i ràpida.


## Opció B: comproveu el vostre encaminador

Obriu la pàgina de configuració del vostre encaminador i cerqueu els dispositius connectats.

Per accedir al vostre encaminador, normalment necessiteu la seva adreça local (per exemple, `192.168.1.1` o un nom com `fritz.box`) i les credencials d'inici de sessió de l'encaminador.

Aquesta secció es pot anomenar:
• Dispositius connectats
• LAN
• Clients DHCP

Busca:
• Dispositius cablejats desconeguts
• Entrades que poden representar el vostre controlador

L'adreça IP normalment sembla:
`192.168.x.x` o `10.0.x.x`.

![Exemple de dispositius connectats a l'encaminador](../assets/setup-guide/ca/img_01.png)


## Opció C: escaneja la teva xarxa

Utilitzeu una aplicació d'escàner de xarxa al vostre iPhone o ordinador.

Escaneja la teva xarxa i prova d'obrir les adreces IP descobertes a Safari, per exemple:

`http://192.168.1.50`

Si apareix la pàgina d'inici de sessió del controlador, heu trobat l'adreça correcta.

![Exemple d'escàner de xarxa](../assets/setup-guide/ca/img_02.png)


## Pas 2: afegiu el controlador a GateTap

Obriu GateTap i introduïu:
• L'adreça IP
• El vostre nom d'usuari
• La teva contrasenya

Utilitzeu les mateixes credencials que per a la interfície web del controlador.


## Pas 3: prova la connexió

Deseu la vostra configuració i proveu d'obrir una porta o una porta.

Si no passa res, comproveu:
• El vostre iPhone està a la mateixa xarxa
• L'adreça IP és correcta
• El controlador està alimentat i es pot accedir


## Pas 4: manteniu l'adreça IP estable

Per evitar problemes més endavant, el controlador ha d'utilitzar sempre la mateixa adreça IP.

Això es pot fer mitjançant:
• Configuració d'una IP estàtica al controlador
• Creació d'una reserva DHCP al vostre encaminador


## Seguretat

Les teves dades es mantenen al teu dispositiu.

Opcionalment, podeu protegir GateTap mitjançant Face ID o Touch ID a la configuració de l'aplicació.


