<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: cs
-->

# Průvodce nastavením

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | 🇨🇿 Čeština | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Připojte GateTap k vašemu přístupovému ovladači

## Než začnete

Ujistěte se, že je vaše zařízení připojeno ke stejné místní síti jako přístupový kontroler. Například zkontrolujte, že je iPhone připojen k domácí Wi-Fi a nepoužívá mobilní data.

GateTap funguje celý ve vaší místní síti a potřebuje:

- IP adresu kontroleru
- Uživatelské jméno a heslo


## Krok 1: Najděte IP adresu přístupového kontroleru

Pro připojení GateTap potřebujete IP adresu kontroleru a přihlašovací údaje - viz krok 2.

Vyberte jednu z následujících možností:


## Možnost A: Zeptejte se instalačního technika (doporučeno)

Pokud systém instaloval elektrikář nebo technik, pravděpodobně už vše nastavil.

V mnoha případech:

- Kontroler používá pevnou IP adresu
- Nebo mu router přiřazuje stejnou IP pomocí rezervace DHCP

Požádejte ho o IP adresu a přihlašovací údaje. Obvykle je to nejjednodušší a nejrychlejší cesta.


## Možnost B: Zkontrolujte router

Otevřete konfigurační stránku routeru a vyhledejte připojená zařízení.

Pro přístup k routeru obvykle potřebujete jeho místní adresu, například `192.168.1.1` nebo název jako `fritz.box`, a přihlašovací údaje routeru.

Tato část se může jmenovat:

- Síť
- Připojená zařízení
- LAN
- Klienti DHCP

Hledejte:

- Neznámá kabelová zařízení
- Položky, které by mohly představovat váš kontroler

IP adresa bude obvykle vypadat takto:
`192.168.x.x` nebo `10.0.x.x`

![Příklad připojených zařízení v routeru](../assets/setup-guide/cs/img_01_en_US.png)


## Možnost C: Prohledejte síť

Použijte na svém zařízení aplikaci pro skenování sítě.

Prohledejte síť a zkuste nalezené IP adresy otevřít v Safari, například:

`http://192.168.1.50`

Pokud se zobrazí přihlašovací stránka přístupového kontroleru, našli jste správnou adresu.

![Příklad aplikace pro skenování sítě](../assets/setup-guide/cs/img_02_en_US.png)


## Krok 2: Najděte přihlašovací údaje přístupového kontroleru

Některé kontrolery stále používají výchozí přihlašovací údaje. Běžným příkladem je uživatelské jméno `abc` s heslem `654321`.

Další často používaná tovární uživatelská jména jsou `user`, `admin` nebo `123`. Můžete je vyzkoušet s typickými hesly jako `1234`, `user` nebo `password`, případně s jejich obměnou.

Pokud byl systém instalován profesionálně, zeptejte se instalačního technika, zda byly výchozí údaje změněny.


## Krok 3: Přidejte přístupový kontroler do GateTap

Otevřete GateTap a zadejte:

- IP adresu
- Uživatelské jméno
- Heslo

Použijte stejné údaje jako pro webové rozhraní přístupového kontroleru.


## Krok 4: Otestujte připojení

Uložte konfiguraci a zkuste otevřít dveře nebo bránu.

Pokud se nic nestane, zkontrolujte:

- Že je vaše zařízení ve stejné síti jako přístupový kontroler
- Že je IP adresa správná
- Že je přístupový kontroler napájený a dostupný


## Krok 5: Udržujte IP adresu stabilní

Abyste se později vyhnuli problémům, měl by kontroler vždy používat stejnou IP adresu.

To lze provést takto:

- Nastavením statické IP adresy na kontroleru
- Vytvořením rezervace DHCP v routeru


## Demo režim

GateTap obsahuje také demo režim. V aplikaci můžete spustit místní demo webový server a potom ho přidat jako běžný kontroler.

Získáte tak známou funkční testovací cestu pro ověření, že GateTap funguje správně, i když momentálně nemáte přístup k fyzickému přístupovému kontroleru.


## Bezpečnost

Vaše data zůstanou ve vašem zařízení.

GateTap můžete volitelně chránit pomocí Face ID nebo Touch ID v nastavení aplikace.


