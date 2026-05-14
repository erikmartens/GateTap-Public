<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: ca
-->

# Guia de configuració

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | 🇪🇸 Català | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Connecteu GateTap al vostre controlador d'accés

## Què és un controlador d’accés?

Un controlador d’accés és un dispositiu que gestiona l’obertura de portes, portals, garatges o barreres — per exemple activant un porter automàtic o el motor d’un portal.
Normalment rep el senyal d’obertura de:

- un sistema d’interfonia
- un teclat
- un clauer electrònic o una targeta d’accés

Molts sistemes moderns de control d’accés estan connectats a la xarxa local i es poden utilitzar mitjançant una interfície web en un navegador. GateTap es connecta directament al teu sistema de control d’accés perquè el puguis fer servir còmodament des del dispositiu.


## Abans de començar

Assegura’t que el dispositiu estigui connectat a la mateixa xarxa local que el controlador d’accés. Per exemple, comprova que l’iPhone estigui connectat a la Wi-Fi de casa i no faci servir dades mòbils.

GateTap funciona completament dins de la teva xarxa local i necessita:

- L’adreça IP del controlador
- Un nom d’usuari i una contrasenya


## Pas 1: troba l’adreça IP del controlador d’accés

Per connectar GateTap, necessites l’adreça IP del controlador i les credencials d’inici de sessió — consulta el pas 2.

Tria una de les opcions següents:


## Opció A: pregunta al teu instal·lador (recomanat)

Si el sistema el va instal·lar un electricista o un tècnic, probablement ja ho va configurar tot.

En molts casos:

- El controlador utilitza una adreça IP fixa
- O l’encaminador li assigna la mateixa IP mitjançant una reserva DHCP

Demana-li l’adreça IP i les dades d’inici de sessió. Normalment és la manera més fàcil i ràpida.


## Opció B: comprova l’encaminador

Per accedir a l’encaminador, normalment necessites la seva adreça local, per exemple `192.168.1.1` o un nom com `fritz.box`, i les credencials de l’encaminador.

Obre la pàgina de configuració de l’encaminador i busca els dispositius connectats.

Aquest apartat es pot anomenar:

- Xarxa
- Dispositius connectats
- LAN
- Clients DHCP

Busca:

- Dispositius cablejats desconeguts
- Entrades que puguin representar el controlador

L’adreça IP normalment tindrà aquest aspecte:
`192.168.x.x` o `10.0.x.x`

![Exemple de dispositius connectats a l’encaminador](../assets/setup-guide/ca/img_01_ca.png)


## Opció C: escaneja la teva xarxa

Utilitza una app d’escaneig de xarxa al dispositiu.

Escaneja la xarxa i busca:

- Dispositius cablejats desconeguts
- Entrades que puguin representar el controlador

L’adreça IP normalment tindrà aquest aspecte:
`192.168.x.x` o `10.0.x.x`


## Prova l’adreça IP

Prova d’obrir l’adreça IP trobada a Safari, per exemple:

`http://192.168.1.50`

Si apareix la pàgina d’inici de sessió del controlador d’accés, has trobat l’adreça correcta.


## Pas 2: troba les credencials del controlador d’accés

Alguns controladors d’accés encara utilitzen credencials predeterminades. Un exemple habitual és el nom d’usuari `abc` amb la contrasenya `654321`.

Altres noms d’usuari predeterminats habituals són `user`, `admin` o `123`. Pots provar-los amb contrasenyes típiques com `1234`, `user` o `password`, o alguna variació.

Si el sistema es va instal·lar professionalment, pregunta a l’instal·lador si es van canviar les credencials predeterminades.


## Pas 3: afegeix el controlador d’accés a GateTap

Obre GateTap. Si la pàgina per afegir un controlador no apareix automàticament, canvia a la pestanya "Controller" i toca el botó "+" de la barra de navegació a la part superior dreta.

A la pàgina que apareix, introdueix:

- L’adreça IP
- El nom d’usuari
- La contrasenya

Fes servir les mateixes credencials que per a la interfície web del controlador d’accés.


## Pas 4: prova la connexió

Desa la configuració. L’app intentarà connectar-se automàticament.

Si no es pot establir la connexió, comprova:

- Que el dispositiu sigui a la mateixa xarxa que el controlador d’accés
- Que l’adreça IP sigui correcta
- Que el controlador d’accés tingui alimentació i sigui accessible


## Pas 5: mantén estable l’adreça IP

Per evitar problemes més endavant, el controlador hauria d’utilitzar sempre la mateixa adreça IP.

Això es pot fer així:

- Configurant una IP estàtica al controlador
- Creant una reserva DHCP a l’encaminador


## Mode demo

GateTap també inclou un mode demo. Pots iniciar un controlador d’accés virtual des de dins de l’app, que serveix la interfície d’administració com ho faria un sistema real. Després el pots afegir com un controlador normal utilitzant l’adreça IP i les credencials mostrades.

Això et dona un camí de prova conegut que funciona per explorar les funcions de GateTap, encara que ara mateix no tinguis cap controlador d’accés físic.


## Seguretat

Les teves dades es mantenen al teu dispositiu.

Opcionalment, podeu protegir GateTap mitjançant Face ID o Touch ID a la configuració de l'aplicació.


