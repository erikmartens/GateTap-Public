<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: sk
-->

# Sprievodca nastavením

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | 🇸🇰 Slovenčina | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Pripojte GateTap k ovládaču prístupu

## Skôr ako začnete

Uistite sa, že váš iPhone je pripojený k rovnakej lokálnej sieti ako váš ovládač prístupu.

GateTap funguje úplne v rámci vašej lokálnej siete a potrebuje:
• IP adresa ovládača
• Používateľské meno a heslo


## Krok 1: Nájdite adresu ovládača a poverenia

Na pripojenie GateTap potrebujete IP adresu ovládača a prihlasovacie údaje.

Vyberte jednu z nasledujúcich možností:


## Možnosť A: Opýtajte sa svojho inštalatéra (odporúča sa)

Ak váš systém nainštaloval elektrikár alebo technik, pravdepodobne už všetko nakonfigurovali.

V mnohých prípadoch:
• Riadiaca jednotka používa pevnú IP adresu
• Alebo router pridelí rovnakú IP cez rezerváciu

Požiadajte ich o IP adresu a prihlasovacie údaje. Toto je zvyčajne najjednoduchší a najrýchlejší spôsob.


## Možnosť B: Skontrolujte smerovač

Otvorte konfiguračnú stránku smerovača a vyhľadajte pripojené zariadenia.

Na prístup k smerovaču zvyčajne potrebujete jeho lokálnu adresu (napr. `192.168.1.1` alebo názov ako `fritz.box`) a prihlasovacie údaje smerovača.

Táto sekcia sa môže volať:
• Pripojené zariadenia
• LAN
• Klienti DHCP

Hľadajte:
• Neznáme káblové zariadenia
• Záznamy, ktoré môžu predstavovať váš ovládač

IP adresa bude zvyčajne vyzerať takto:
`192.168.x.x` alebo `10.0.x.x`.

![Príklad zariadení pripojených k smerovaču](../assets/setup-guide/sk/img_01.png)


## Možnosť C: Skenovanie siete

Použite aplikáciu sieťového skenera na vašom iPhone alebo počítači.

Skenujte svoju sieť a skúste nájsť nájdené adresy IP v prehliadači Safari, napríklad:

`http://192.168.1.50`

Ak sa zobrazí prihlasovacia stránka ovládača, našli ste správnu adresu.

![Príklad sieťového skenera](../assets/setup-guide/sk/img_02.png)


## Krok 2: Pridajte ovládač do GateTap

Otvorte GateTap a zadajte:
• IP adresa
• Vaše používateľské meno
• Vaše heslo

Použite rovnaké prihlasovacie údaje ako pre webové rozhranie ovládača.


## Krok 3: Otestujte pripojenie

Uložte svoju konfiguráciu a skúste otvoriť dvere alebo bránu.

Ak sa nič nestane, skontrolujte:
• Váš iPhone je v rovnakej sieti
• IP adresa je správna
• Ovládač je napájaný a dostupný


## Krok 4: Udržujte stabilnú IP adresu

Aby sa predišlo neskorším problémom, ovládač by mal vždy používať rovnakú IP adresu.

Môžete to urobiť takto:
• Nastavenie statickej IP na ovládači
• Vytvorenie rezervácie DHCP vo vašom smerovači


## Bezpečnosť

Vaše údaje zostanú vo vašom zariadení.

GateTap môžete voliteľne chrániť pomocou Face ID alebo Touch ID v nastaveniach aplikácie.


