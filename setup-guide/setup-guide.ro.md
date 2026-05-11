<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: ro
-->

# Ghid de instalare

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | 🇷🇴 Română | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Conectați GateTap la controlerul dvs. de acces

## Înainte de a începe

Asigurați-vă că dispozitivul este conectat la aceeași rețea locală ca și controlerul de acces. De exemplu, verificați ca iPhone-ul să fie pe Wi-Fi-ul de acasă, nu pe conexiunea de date mobile.

GateTap funcționează integral în rețeaua locală și are nevoie de:
• Adresa IP a controlerului
• Un nume de utilizator și o parolă


## Pasul 1: Găsiți adresa IP a controlerului de acces

Pentru a conecta GateTap, aveți nevoie de adresa IP a controlerului și de datele de autentificare - consultați Pasul 2.

Alegeți una dintre următoarele opțiuni:


## Opțiunea A: Întrebați instalatorul dvs. (recomandat)

Dacă sistemul a fost instalat de un electrician sau tehnician, probabil că acesta a configurat deja totul.

În multe cazuri:
• Controlerul folosește o adresă IP fixă
• Sau routerul îi atribuie același IP prin rezervare DHCP

Cereți adresa IP și datele de autentificare. De obicei, acesta este cel mai simplu și rapid mod.


## Opțiunea B: verificați routerul

Deschideți pagina de configurare a routerului și căutați dispozitivele conectate.

Pentru a accesa routerul, de obicei aveți nevoie de adresa locală, de exemplu `192.168.1.1` sau un nume precum `fritz.box`, și de datele de autentificare ale routerului.

Această secțiune se poate numi:
• Rețea
• Dispozitive conectate
• LAN
• Clienți DHCP

Căutați:
• Dispozitive cu fir necunoscute
• Intrări care ar putea reprezenta controlerul dvs.

Adresa IP va arăta de obicei astfel:
`192.168.x.x` sau `10.0.x.x`

![Exemplu de dispozitive conectate în router](../assets/setup-guide/ro/img_01_en_US.png)


## Opțiunea C: Scanați-vă rețeaua

Folosiți o aplicație de scanare a rețelei pe dispozitiv.

Scanați rețeaua și încercați să deschideți adresele IP găsite în Safari, de exemplu:

`http://192.168.1.50`

Dacă apare pagina de autentificare a controlerului de acces, ați găsit adresa corectă.

![Exemplu de aplicație de scanare a rețelei](../assets/setup-guide/ro/img_02_en_US.png)


## Pasul 2: Găsiți datele de autentificare ale controlerului de acces

Unele controlere încă folosesc date de autentificare implicite. Un exemplu comun este numele de utilizator `abc` cu parola `654321`.

Alte nume de utilizator din fabrică frecvent folosite sunt `user`, `admin` sau `123`. Le puteți încerca împreună cu parole tipice precum `1234`, `user` sau `password`, ori o variație a acestora.

Dacă sistemul a fost instalat profesional, întrebați instalatorul dacă datele implicite au fost schimbate.


## Pasul 3: Adăugați controlerul de acces în GateTap

Deschideți GateTap și introduceți:
• Adresa IP
• Numele de utilizator
• Parola

Folosiți aceleași date ca pentru interfața web a controlerului de acces.


## Pasul 4: Testați conexiunea

Salvați configurația și încercați să deschideți o ușă sau o poartă.

Dacă nu se întâmplă nimic, verificați:
• Dispozitivul este în aceeași rețea cu controlerul de acces
• Adresa IP este corectă
• Controlerul de acces este alimentat și accesibil


## Pasul 5: Păstrați adresa IP stabilă

Pentru a evita problemele mai târziu, controlerul ar trebui să folosească mereu aceeași adresă IP.

Acest lucru se poate face prin:
• Setarea unui IP static pe controler
• Crearea unei rezervări DHCP în router


## Mod demo

GateTap include și un mod demo. Puteți porni un server web demo local din aplicație și apoi îl puteți adăuga ca pe un controler normal.

Astfel aveți o cale de test cunoscută și funcțională pentru a verifica dacă GateTap funcționează corect, chiar dacă momentan nu aveți acces la un controler de acces fizic.


## Securitate

Datele tale rămân pe dispozitivul tău.

Puteți proteja opțional GateTap folosind Face ID sau Touch ID în setările aplicației.


