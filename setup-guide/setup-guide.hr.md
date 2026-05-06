<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: hr
-->

# Vodič za postavljanje

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | 🌐 hr | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

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


