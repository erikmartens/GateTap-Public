<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: hr
-->

# Vodič za postavljanje

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | 🇭🇷 Hrvatski | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Spojite GateTap na svoj kontroler pristupa

## Prije nego počnete

Provjerite je li vaš iPhone spojen na istu lokalnu mrežu kao i vaš kontroler pristupa.

GateTap u potpunosti radi unutar vaše lokalne mreže i treba mu:
• IP adresa kontrolera
• Korisničko ime i lozinka


## Korak 1: Pronađite adresu i vjerodajnice kontrolora

Za povezivanje GateTap-a potrebna vam je IP adresa kontrolera i vjerodajnice za prijavu.

Odaberite jednu od sljedećih opcija:


## Opcija A: Pitajte svog instalatera (preporučeno)

Ako je vaš sustav instalirao električar ili tehničar, oni su vjerojatno već sve konfigurirali.

U mnogim slučajevima:
• Kontroler koristi fiksnu IP adresu
• Ili usmjerivač dodjeljuje isti IP putem rezervacije

Pitajte ih za IP adresu i podatke za prijavu. Ovo je obično najlakši i najbrži način.


## Opcija B: Provjerite svoj usmjerivač

Otvorite konfiguracijsku stranicu svog usmjerivača i potražite povezane uređaje.

Za pristup vašem usmjerivaču obično vam je potrebna njegova lokalna adresa (npr. `192.168.1.1` ili naziv poput `fritz.box`) i vjerodajnice za prijavu na usmjerivač.

Ovaj odjeljak može se zvati:
• Povezani uređaji
• LAN
• DHCP klijenti

Potražite:
• Nepoznati žični uređaji
• Unosi koji bi mogli predstavljati vaš upravljač

IP adresa obično izgleda ovako:
`192.168.x.x` ili `10.0.x.x`

![Primjer uređaja povezanih s usmjerivačem](../assets/setup-guide/hr/img_01.png)


## Opcija C: skenirajte svoju mrežu

Koristite aplikaciju mrežnog skeniranja na svom iPhoneu ili računalu.

Skenirajte svoju mrežu i pokušajte otvoriti otkrivene IP adrese u Safariju, na primjer:

`http://192.168.1.50`

Ako se pojavi stranica za prijavu kontrolera, pronašli ste ispravnu adresu.

![Primjer mrežnog skenera](../assets/setup-guide/hr/img_02.png)


## Korak 2: Dodajte kontroler u GateTap

Otvorite GateTap i unesite:
• IP adresa
• Vaše korisničko ime
• Vaša lozinka

Koristite iste vjerodajnice kao za web sučelje kontrolera.


## Korak 3: Testirajte vezu

Spremite svoju konfiguraciju i pokušajte otvoriti vrata ili vrata.

Ako se ništa ne dogodi, provjerite:
• Vaš iPhone je na istoj mreži
• IP adresa je točna
• Kontroler je napajan i dostupan


## Korak 4: Održavajte IP adresu stabilnom

Kako biste izbjegli kasnije probleme, kontroler bi uvijek trebao koristiti istu IP adresu.

To se može učiniti na sljedeći način:
• Postavljanje statičke IP adrese na kontroleru
• Stvaranje DHCP rezervacije u vašem usmjerivaču


## Sigurnost

Vaši podaci ostaju na vašem uređaju.

Opcionalno možete zaštititi GateTap koristeći Face ID ili Touch ID u postavkama aplikacije.


