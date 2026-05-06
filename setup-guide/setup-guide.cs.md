<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: cs
-->

# Průvodce nastavením

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | 🌐 cs | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

---

Připojte GateTap k vašemu přístupovému ovladači

## Než začnete

Ujistěte se, že je váš iPhone připojen ke stejné místní síti jako váš přístupový ovladač.

GateTap funguje zcela v rámci vaší místní sítě a potřebuje:
• IP adresa ovladače
• Uživatelské jméno a heslo


## Krok 1: Najděte adresu ovladače a přihlašovací údaje

Pro připojení GateTap potřebujete IP adresu ovladače a přihlašovací údaje.

Vyberte jednu z následujících možností:


## Možnost A: Zeptejte se svého instalačního technika (doporučeno)

Pokud váš systém instaloval elektrikář nebo technik, pravděpodobně již vše nakonfiguroval.

V mnoha případech:
• Ovladač používá pevnou IP adresu
• Nebo router přiřadí stejnou IP prostřednictvím rezervace

Požádejte je o IP adresu a přihlašovací údaje. To je obvykle nejjednodušší a nejrychlejší způsob.


## Možnost B: Zkontrolujte router

Otevřete konfigurační stránku routeru a vyhledejte připojená zařízení.

Pro přístup k routeru obvykle potřebujete jeho místní adresu (např. `192.168.1.1` nebo název jako `fritz.box`) a přihlašovací údaje routeru.

Tato sekce se může jmenovat:
• Připojená zařízení
• LAN
• Klienti DHCP

Hledejte:
• Neznámá kabelová zařízení
• Položky, které mohou představovat váš ovladač

IP adresa bude obvykle vypadat takto:
`192.168.x.x` nebo `10.0.x.x`

![Příklad zařízení připojených k routeru](../assets/setup-guide/cs/img_01.png)


## Možnost C: Prohledejte síť

Použijte aplikaci síťového skeneru na vašem iPhone nebo počítači.

Prohledejte svou síť a zkuste otevřít nalezené IP adresy v Safari, například:

`http://192.168.1.50`

Pokud se zobrazí přihlašovací stránka ovladače, našli jste správnou adresu.

![Příklad síťového skeneru](../assets/setup-guide/cs/img_02.png)


## Krok 2: Přidejte ovladač do GateTap

Otevřete GateTap a zadejte:
• IP adresa
• Vaše uživatelské jméno
• Vaše heslo

Použijte stejné přihlašovací údaje jako pro webové rozhraní ovladače.


## Krok 3: Otestujte připojení

Uložte konfiguraci a zkuste otevřít dveře nebo bránu.

Pokud se nic nestane, zkontrolujte:
• Váš iPhone je ve stejné síti
• IP adresa je správná
• Ovladač je napájen a dosažitelný


## Krok 4: Udržujte IP adresu stabilní

Aby se předešlo problémům později, měl by řadič vždy používat stejnou IP adresu.

To lze provést takto:
• Nastavení statické IP na ovladači
• Vytvoření rezervace DHCP ve vašem routeru


## Bezpečnost

Vaše data zůstanou ve vašem zařízení.

GateTap můžete volitelně chránit pomocí Face ID nebo Touch ID v nastavení aplikace.


