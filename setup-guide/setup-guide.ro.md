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

## Ce este un controler de acces?

Un controler de acces este un dispozitiv care gestionează deschiderea ușilor, porților, garajelor sau barierelor — de exemplu prin activarea unei sonerii electrice sau a motorului unei porți.
De obicei primește semnalul de deschidere de la:

- un sistem de interfon
- o tastatură
- un breloc sau card de acces

Multe sisteme moderne de control al accesului sunt conectate la rețeaua locală și pot fi operate printr-o interfață web în browser. GateTap se conectează direct la acel sistem pentru a-l putea controla comod de pe dispozitivul tău.


## Înainte de a începe

Asigură-te că dispozitivul tău este conectat la aceeași rețea locală ca și controlerul de acces. De exemplu, verifică dacă iPhone-ul este conectat la Wi‑Fi-ul de acasă și nu folosește date mobile.

GateTap funcționează complet în rețeaua ta locală și are nevoie de:

- Adresa IP a controlerului
- Un nume de utilizator și o parolă


## Pasul 1: Găsiți adresa IP a controlerului de acces

Pentru a conecta GateTap, ai nevoie de adresa IP a controlerului și de datele de autentificare — vezi Pasul 2.

Alege una dintre opțiunile următoare:


## Opțiunea A: Întrebați instalatorul dvs. (recomandat)

Dacă sistemul a fost instalat de un electrician sau tehnician, probabil că acesta a configurat deja totul.

În multe cazuri:

- Controlerul folosește o adresă IP fixă
- Sau routerul îi atribuie aceeași adresă IP printr-o rezervare DHCP

Cere-i adresa IP și datele de autentificare. Aceasta este de obicei cea mai simplă și rapidă metodă.


## Opțiunea B: verificați routerul

Pentru a accesa routerul, de obicei ai nevoie de adresa lui locală, de exemplu `192.168.1.1` sau un nume precum `fritz.box`, și de datele de autentificare ale routerului.

Deschide pagina de configurare a routerului și caută dispozitivele conectate.

Această secțiune se poate numi:

- Rețea
- Dispozitive conectate
- LAN
- Clienți DHCP

Caută:

- Dispozitive cablate necunoscute
- Intrări care ar putea reprezenta controlerul tău

Adresa IP arată de obicei astfel:
`192.168.x.x` sau `10.0.x.x`

![Exemplu de dispozitive conectate în router](../assets/setup-guide/ro/img_01_en_US.png)


## Opțiunea C: Scanați-vă rețeaua

Folosește o aplicație de scanare a rețelei pe dispozitivul tău.

Scanează rețeaua și caută:

- Dispozitive cablate necunoscute
- Intrări care ar putea reprezenta controlerul tău

Adresa IP arată de obicei astfel:
`192.168.x.x` sau `10.0.x.x`


## Testați adresa IP

Încearcă să deschizi în Safari adresa IP găsită, de exemplu:

`http://192.168.1.50`

Dacă apare pagina de autentificare a controlerului de acces, ai găsit adresa corectă.


## Pasul 2: Găsiți datele de autentificare ale controlerului de acces

Unele controlere de acces folosesc încă date de autentificare implicite. Un exemplu comun este numele de utilizator `abc` cu parola `654321`.

Alte nume de utilizator implicite frecvente sunt `user`, `admin` sau `123`. Le poți încerca împreună cu parole tipice precum `1234`, `user` sau `password`, ori cu o variantă.

Dacă sistemul a fost instalat profesional, întreabă instalatorul dacă datele implicite au fost schimbate.


## Pasul 3: Adăugați controlerul de acces în GateTap

Deschide GateTap. Dacă pagina pentru adăugarea unui controler nu apare automat, mergi la fila "Controller" și atinge butonul "+" din bara de navigare din dreapta sus.

În pagina care apare, introdu:

- Adresa IP
- Numele de utilizator
- Parola

Folosește aceleași date de autentificare ca pentru interfața web a controlerului de acces.


## Pasul 4: Testați conexiunea

Salvează configurația. Aplicația va încerca automat să se conecteze.

Dacă nu se poate stabili conexiunea, verifică:

- Dispozitivul tău este în aceeași rețea cu controlerul de acces
- Adresa IP este corectă
- Controlerul de acces este alimentat și accesibil


## Pasul 5: Păstrați adresa IP stabilă

Pentru a evita problemele mai târziu, controlerul ar trebui să folosească întotdeauna aceeași adresă IP.

Acest lucru se poate face prin:

- Setarea unui IP static pe controler
- Crearea unei rezervări DHCP în router


## Mod demo

GateTap include și un mod demo. Poți porni din aplicație un controler de acces virtual, care oferă interfața de administrare așa cum ar face un sistem real de control al accesului. Apoi îl poți adăuga ca pe un controler normal folosind adresa IP și datele de autentificare afișate.

Astfel ai o cale de test cunoscută și funcțională pentru a explora funcțiile GateTap, chiar dacă momentan nu ai un controler de acces fizic.


## Securitate

Datele tale rămân pe dispozitivul tău.

Puteți proteja opțional GateTap folosind Face ID sau Touch ID în setările aplicației.


