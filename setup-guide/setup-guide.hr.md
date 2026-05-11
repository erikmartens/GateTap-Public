<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: hr
-->

# Vodič za postavljanje

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | 🇭🇷 Hrvatski | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Spojite GateTap na svoj kontroler pristupa

## Prije nego počnete

Provjerite je li vaš uređaj povezan s istom lokalnom mrežom kao i vaš kontroler pristupa. Primjerice, provjerite je li iPhone na kućnoj Wi-Fi mreži, a ne na mobilnoj podatkovnoj vezi.

GateTap u potpunosti radi unutar vaše lokalne mreže i treba:
• IP adresu kontrolera
• Korisničko ime i lozinku


## Korak 1: Pronađite IP adresu kontrolera pristupa

Za povezivanje GateTapa potrebna vam je IP adresa kontrolera i podaci za prijavu - pogledajte korak 2.

Odaberite jednu od sljedećih mogućnosti:


## Opcija A: Pitajte svog instalatera (preporučeno)

Ako je sustav instalirao električar ili tehničar, vjerojatno je već sve konfigurirao.

U mnogim slučajevima:
• Kontroler koristi fiksnu IP adresu
• Ili usmjerivač dodjeljuje istu IP adresu putem DHCP rezervacije

Zatražite IP adresu i podatke za prijavu. To je obično najlakši i najbrži način.


## Opcija B: Provjerite svoj usmjerivač

Otvorite konfiguracijsku stranicu usmjerivača i potražite povezane uređaje.

Za pristup usmjerivaču obično trebate njegovu lokalnu adresu, npr. `192.168.1.1` ili naziv poput `fritz.box`, te podatke za prijavu na usmjerivač.

Ovaj se odjeljak može zvati:
• Mreža
• Povezani uređaji
• LAN
• DHCP klijenti

Potražite:
• Nepoznate žičane uređaje
• Unose koji bi mogli predstavljati vaš kontroler

IP adresa obično izgleda ovako:
`192.168.x.x` ili `10.0.x.x`

![Primjer povezanih uređaja u usmjerivaču](../assets/setup-guide/hr/img_01_en_US.png)


## Opcija C: Skenirajte svoju mrežu

Upotrijebite aplikaciju za skeniranje mreže na svom uređaju.

Skenirajte mrežu i pokušajte otvoriti pronađene IP adrese u Safariju, na primjer:

`http://192.168.1.50`

Ako se pojavi stranica za prijavu kontrolera pristupa, pronašli ste ispravnu adresu.

![Primjer aplikacije za skeniranje mreže](../assets/setup-guide/hr/img_02_en_US.png)


## Korak 2: Pronađite podatke za prijavu kontrolera pristupa

Neki kontroleri još uvijek koriste zadane podatke za prijavu. Čest primjer je korisničko ime `abc` s lozinkom `654321`.

Druga često korištena tvornička korisnička imena su `user`, `admin` ili `123`. Možete ih isprobati s tipičnim lozinkama kao što su `1234`, `user` ili `password`, ili nekom njihovom varijacijom.

Ako je sustav profesionalno instaliran, pitajte instalatera jesu li zadani podaci promijenjeni.


## Korak 3: Dodajte kontroler pristupa u GateTap

Otvorite GateTap i unesite:
• IP adresu
• Korisničko ime
• Lozinku

Koristite iste podatke za prijavu kao za web sučelje kontrolera pristupa.


## Korak 4: Testirajte vezu

Spremite konfiguraciju i pokušajte otvoriti vrata ili kapiju.

Ako se ništa ne dogodi, provjerite:
• Je li vaš uređaj na istoj mreži kao kontroler pristupa
• Je li IP adresa ispravna
• Je li kontroler pristupa uključen i dostupan


## Korak 5: Održavajte IP adresu stabilnom

Kako biste izbjegli kasnije probleme, kontroler bi uvijek trebao koristiti istu IP adresu.

To se može učiniti tako da:
• Postavite statičku IP adresu na kontroleru
• Izradite DHCP rezervaciju u usmjerivaču


## Demo način

GateTap uključuje i demo način. Možete pokrenuti lokalni demo web-poslužitelj iz aplikacije i zatim ga dodati kao običan kontroler.

Tako dobivate poznat ispravan testni put za provjeru radi li GateTap pravilno, čak i ako trenutno nemate pristup fizičkom kontroleru pristupa.


## Sigurnost

Vaši podaci ostaju na vašem uređaju.

Opcionalno možete zaštititi GateTap koristeći Face ID ili Touch ID u postavkama aplikacije.


