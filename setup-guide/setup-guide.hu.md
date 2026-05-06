<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: hu
-->

# Beállítási útmutató

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | 🇭🇺 Magyar | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Csatlakoztassa a GateTap-ot a hozzáférés-vezérlőhöz

## Mielőtt elkezdené

Győződjön meg arról, hogy iPhone-ja ugyanahhoz a helyi hálózathoz csatlakozik, mint a hozzáférés-vezérlő.

A GateTap teljes mértékben a helyi hálózaton belül működik, és a következőkre van szüksége:
• A vezérlő IP-címe
• Felhasználónév és jelszó


## 1. lépés: Keresse meg a vezérlő címét és hitelesítő adatait

A GateTap csatlakoztatásához szüksége van a vezérlő IP-címére és bejelentkezési adataira.

Válasszon az alábbi lehetőségek közül:


## A lehetőség: Kérdezze meg a telepítőt (ajánlott)

Ha a rendszert villanyszerelő vagy technikus telepítette, valószínűleg már mindent beállítottak.

Sok esetben:
• A vezérlő rögzített IP-címet használ
• Vagy az útválasztó ugyanazt az IP-t rendeli hozzá foglaláson keresztül

Kérje meg tőlük az IP-címet és a bejelentkezési adatokat. Általában ez a legegyszerűbb és leggyorsabb módja.


## B lehetőség: Ellenőrizze az útválasztót

Nyissa meg az útválasztó konfigurációs oldalát, és keresse meg a csatlakoztatott eszközöket.

Az útválasztó eléréséhez általában szüksége van a helyi címére (pl. `192.168.1.1` vagy egy névre, például `fritz.box`) és az útválasztó bejelentkezési adataira.

Ennek a szakasznak a neve:
• Csatlakoztatott eszközök
• LAN
• DHCP kliensek

Keresse meg:
• Ismeretlen vezetékes eszközök
• Bejegyzések, amelyek az Ön vezérlőjét képviselhetik

Az IP-cím általában így néz ki:
`192.168.x.x` vagy `10.0.x.x`.

![Példa a routerhez csatlakoztatott eszközökre](../assets/setup-guide/hu/img_01.png)


## C lehetőség: Ellenőrizze a hálózatot

Használjon hálózati szkenner alkalmazást iPhone-ján vagy számítógépén.

Vizsgálja meg hálózatát, és próbálja meg megnyitni a felfedezett IP-címeket a Safariban, például:

`http://192.168.1.50`.

Ha megjelenik a vezérlő bejelentkezési oldala, akkor a megfelelő címet találta.

![Példa a hálózati szkennerre](../assets/setup-guide/hu/img_02.png)


## 2. lépés: Adja hozzá a vezérlőt a GateTap-hez

Nyissa meg a GateTap-et, és írja be:
• Az IP-cím
• Az Ön felhasználóneve
• Az Ön jelszava

Használja ugyanazokat a hitelesítő adatokat, mint a vezérlő webes felületén.


## 3. lépés: Tesztelje a kapcsolatot

Mentse el a konfigurációt, és próbáljon kinyitni egy ajtót vagy kaput.

Ha nem történik semmi, ellenőrizze:
• Az iPhone ugyanazon a hálózaton van
• Az IP-cím helyes
• A vezérlő áram alatt van és elérhető


## 4. lépés: Tartsa stabilan az IP-címet

A későbbi problémák elkerülése érdekében a vezérlőnek mindig ugyanazt az IP-címet kell használnia.

Ez megtehető:
• Statikus IP beállítása a vezérlőn
• DHCP-foglalás létrehozása az útválasztóban


## Biztonság

Adatai az eszközön maradnak.

Opcionálisan védheti a GateTap-et Face ID vagy Touch ID használatával az alkalmazás beállításaiban.


