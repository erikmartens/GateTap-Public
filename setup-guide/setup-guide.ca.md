<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: ca
-->

# Guia de configuració

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | 🌐 ca | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

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


