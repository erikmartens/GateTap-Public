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

## Skôr ako začnete

Uistite sa, že vaše zariadenie je pripojené k rovnakej miestnej sieti ako prístupový kontrolér. Napríklad skontrolujte, že iPhone je na domácej Wi-Fi, nie na mobilných dátach.

GateTap funguje úplne v rámci vašej miestnej siete a potrebuje:

- IP adresu kontroléra
- Používateľské meno a heslo


## Krok 1: Nájdite IP adresu prístupového kontroléra

Na pripojenie GateTap potrebujete IP adresu kontroléra a prihlasovacie údaje - pozrite krok 2.

Vyberte jednu z nasledujúcich možností:


## Možnosť A: Opýtajte sa svojho inštalatéra (odporúča sa)

Ak systém nainštaloval elektrikár alebo technik, pravdepodobne už všetko nakonfiguroval.

V mnohých prípadoch:

- Kontrolér používa pevnú IP adresu
- Alebo smerovač prideľuje rovnakú IP cez rezerváciu DHCP

Požiadajte ho o IP adresu a prihlasovacie údaje. Zvyčajne je to najjednoduchší a najrýchlejší spôsob.


## Možnosť B: Skontrolujte smerovač

Otvorte konfiguračnú stránku smerovača a vyhľadajte pripojené zariadenia.

Na prístup k smerovaču zvyčajne potrebujete jeho miestnu adresu, napríklad `192.168.1.1` alebo názov ako `fritz.box`, a prihlasovacie údaje smerovača.

Táto sekcia sa môže volať:

- Sieť
- Pripojené zariadenia
- LAN
- DHCP klienti

Hľadajte:

- Neznáme káblové zariadenia
- Položky, ktoré by mohli predstavovať váš kontrolér

IP adresa zvyčajne vyzerá takto:
`192.168.x.x` alebo `10.0.x.x`

![Príklad pripojených zariadení v smerovači](../assets/setup-guide/sk/img_01_en_US.png)


## Možnosť C: Skenovanie siete

Použite aplikáciu na skenovanie siete vo svojom zariadení.

Preskenujte sieť a skúste otvoriť nájdené IP adresy v Safari, napríklad:

`http://192.168.1.50`

Ak sa zobrazí prihlasovacia stránka prístupového kontroléra, našli ste správnu adresu.

![Príklad aplikácie na skenovanie siete](../assets/setup-guide/sk/img_02_en_US.png)


## Krok 2: Nájdite prihlasovacie údaje prístupového kontroléra

Niektoré kontroléry stále používajú predvolené prihlasovacie údaje. Bežným príkladom je používateľské meno `abc` s heslom `654321`.

Ďalšie často používané továrenské používateľské mená sú `user`, `admin` alebo `123`. Môžete ich vyskúšať s typickými heslami ako `1234`, `user` alebo `password`, prípadne s ich obmenou.

Ak bol systém nainštalovaný profesionálne, opýtajte sa inštalatéra, či boli predvolené údaje zmenené.


## Krok 3: Pridajte prístupový kontrolér do GateTap

Otvorte GateTap a zadajte:

- IP adresu
- Používateľské meno
- Heslo

Použite rovnaké údaje ako pre webové rozhranie prístupového kontroléra.


## Krok 4: Otestujte pripojenie

Uložte konfiguráciu a skúste otvoriť dvere alebo bránu.

Ak sa nič nestane, skontrolujte:

- Vaše zariadenie je v rovnakej sieti ako prístupový kontrolér
- IP adresa je správna
- Prístupový kontrolér je napájaný a dostupný


## Krok 5: Udržujte stabilnú IP adresu

Aby ste sa neskôr vyhli problémom, kontrolér by mal vždy používať rovnakú IP adresu.

Dá sa to urobiť takto:

- Nastavením statickej IP na kontroléri
- Vytvorením rezervácie DHCP v smerovači


## Demo režim

GateTap obsahuje aj demo režim. Z aplikácie môžete spustiť miestny demo webový server a potom ho pridať ako bežný kontrolér.

Získate tak známy funkčný testovací postup na overenie, že samotný GateTap funguje správne, aj keď momentálne nemáte prístup k fyzickému prístupovému kontroléru.


## Bezpečnosť

Vaše údaje zostanú vo vašom zariadení.

GateTap môžete voliteľne chrániť pomocou Face ID alebo Touch ID v nastaveniach aplikácie.


