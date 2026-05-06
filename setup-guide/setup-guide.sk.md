<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: sk
-->

# Sprievodca nastavením

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | 🌐 sk | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

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


