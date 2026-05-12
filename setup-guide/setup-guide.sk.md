<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: sk
-->

# Sprievodca nastavením

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | 🇸🇰 Slovenčina | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Pripojte GateTap k ovládaču prístupu

## Čo je prístupový kontrolér?

Prístupový kontrolér je zariadenie, ktoré riadi otváranie dverí, brán, garáží alebo závor — napríklad aktivovaním dverového bzučiaka alebo motora brány.
Zvyčajne prijíma signál na otvorenie z:

- interkomového systému
- klávesnice
- prívesku alebo prístupovej karty

Mnohé moderné systémy kontroly prístupu sú pripojené k lokálnej sieti a dajú sa ovládať cez webové rozhranie v prehliadači. GateTap sa pripája priamo k tomuto systému, aby ste ho mohli pohodlne ovládať zo svojho zariadenia.


## Skôr ako začnete

Uistite sa, že vaše zariadenie je pripojené k rovnakej lokálnej sieti ako prístupový kontrolér. Napríklad skontrolujte, že iPhone je pripojený k domácej Wi‑Fi a nepoužíva mobilné dáta.

GateTap funguje výhradne vo vašej lokálnej sieti a potrebuje:

- IP adresu kontroléra
- Používateľské meno a heslo


## Krok 1: Nájdite IP adresu prístupového kontroléra

Na pripojenie GateTap potrebujete IP adresu kontroléra a prihlasovacie údaje — pozrite krok 2.

Vyberte jednu z nasledujúcich možností:


## Možnosť A: Opýtajte sa svojho inštalatéra (odporúča sa)

Ak systém inštaloval elektrikár alebo technik, pravdepodobne už všetko nakonfiguroval.

V mnohých prípadoch:

- Kontrolér používa pevnú IP adresu
- Alebo mu router prideľuje rovnakú IP adresu cez rezerváciu DHCP

Požiadajte ich o IP adresu a prihlasovacie údaje. Zvyčajne je to najjednoduchší a najrýchlejší spôsob.


## Možnosť B: Skontrolujte smerovač

Na prístup k routeru zvyčajne potrebujete jeho lokálnu adresu, napríklad `192.168.1.1` alebo názov ako `fritz.box`, a prihlasovacie údaje routera.

Otvorte konfiguračnú stránku routera a vyhľadajte pripojené zariadenia.

Táto sekcia sa môže volať:

- Sieť
- Pripojené zariadenia
- LAN
- DHCP klienti

Hľadajte:

- Neznáme káblové zariadenia
- Položky, ktoré môžu predstavovať váš kontrolér

IP adresa zvyčajne vyzerá takto:
`192.168.x.x` alebo `10.0.x.x`

![Príklad pripojených zariadení v routeri](../assets/setup-guide/sk/img_01_en_US.png)


## Možnosť C: Skenovanie siete

Použite aplikáciu na skenovanie siete vo svojom zariadení.

Preskenujte sieť a hľadajte:

- Neznáme káblové zariadenia
- Položky, ktoré môžu predstavovať váš kontrolér

IP adresa zvyčajne vyzerá takto:
`192.168.x.x` alebo `10.0.x.x`


## Otestujte IP adresu

Skúste otvoriť nájdenú IP adresu v Safari, napríklad:

`http://192.168.1.50`

Ak sa zobrazí prihlasovacia stránka prístupového kontroléra, našli ste správnu adresu.


## Krok 2: Nájdite prihlasovacie údaje prístupového kontroléra

Niektoré prístupové kontroléry stále používajú predvolené prihlasovacie údaje. Bežným príkladom je používateľské meno `abc` s heslom `654321`.

Ďalšie bežné predvolené používateľské mená sú `user`, `admin` alebo `123`. Môžete ich skúsiť s typickými heslami ako `1234`, `user` alebo `password`, prípadne s ich variantom.

Ak bol systém nainštalovaný profesionálne, opýtajte sa inštalatéra, či boli predvolené údaje zmenené.


## Krok 3: Pridajte prístupový kontrolér do GateTap

Otvorte GateTap. Ak sa stránka na pridanie kontroléra nezobrazí automaticky, prejdite na kartu "Controller" a klepnite na tlačidlo "+" v navigačnom paneli vpravo hore.

Na zobrazenej stránke zadajte:

- IP adresu
- Používateľské meno
- Heslo

Použite rovnaké prihlasovacie údaje ako pre webové rozhranie prístupového kontroléra.


## Krok 4: Otestujte pripojenie

Uložte konfiguráciu. Aplikácia sa automaticky pokúsi pripojiť.

Ak sa pripojenie nepodarí vytvoriť, skontrolujte:

- Zariadenie je v rovnakej sieti ako prístupový kontrolér
- IP adresa je správna
- Prístupový kontrolér je napájaný a dostupný


## Krok 5: Udržujte stabilnú IP adresu

Aby ste predišli problémom neskôr, kontrolér by mal vždy používať rovnakú IP adresu.

Dá sa to urobiť takto:

- Nastaviť statickú IP na kontroléri
- Vytvoriť rezerváciu DHCP v routeri


## Demo režim

GateTap obsahuje aj demo režim. Z aplikácie môžete spustiť virtuálny prístupový kontrolér, ktorý poskytuje administračné rozhranie tak, ako by to robil skutočný systém kontroly prístupu. Potom ho môžete pridať ako bežný kontrolér pomocou zobrazenej IP adresy a prihlasovacích údajov.

Získate tak overenú testovaciu cestu na preskúmanie funkcií GateTap, aj keď momentálne nemáte fyzický prístupový kontrolér.


## Bezpečnosť

Vaše údaje zostanú vo vašom zariadení.

GateTap môžete voliteľne chrániť pomocou Face ID alebo Touch ID v nastaveniach aplikácie.


