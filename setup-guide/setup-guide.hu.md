<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: hu
-->

# Beállítási útmutató

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | 🇭🇺 Magyar | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Csatlakoztassa a GateTap-ot a hozzáférés-vezérlőhöz

## Mielőtt elkezdené

Győződjön meg róla, hogy az eszköze ugyanahhoz a helyi hálózathoz csatlakozik, mint a hozzáférés-vezérlő. Például ellenőrizze, hogy az iPhone az otthoni Wi-Fi-n van, nem pedig mobiladat-kapcsolaton.

A GateTap teljes egészében a helyi hálózaton működik, és ezekre van szüksége:

- A vezérlő IP-címe
- Felhasználónév és jelszó


## 1. lépés: Keresse meg a hozzáférés-vezérlő IP-címét

A GateTap csatlakoztatásához szüksége van a vezérlő IP-címére és a bejelentkezési adatokra - lásd a 2. lépést.

Válasszon az alábbi lehetőségek közül:


## A lehetőség: Kérdezze meg a telepítőt (ajánlott)

Ha a rendszert villanyszerelő vagy technikus telepítette, valószínűleg már mindent beállított.

Sok esetben:

- A vezérlő fix IP-címet használ
- Vagy a router DHCP-foglalással mindig ugyanazt az IP-t osztja ki

Kérje el tőle az IP-címet és a bejelentkezési adatokat. Ez általában a legegyszerűbb és leggyorsabb mód.


## B lehetőség: Ellenőrizze az útválasztót

Nyissa meg az útválasztó beállítási oldalát, és keresse meg a csatlakoztatott eszközöket.

Az útválasztó eléréséhez általában szükség van a helyi címére, például `192.168.1.1` vagy egy névre, például `fritz.box`, valamint az útválasztó bejelentkezési adataira.

Ez a szakasz ilyen néven szerepelhet:

- Hálózat
- Csatlakoztatott eszközök
- LAN
- DHCP-kliensek

Keresse:

- Ismeretlen vezetékes eszközök
- Olyan bejegyzések, amelyek a vezérlőt jelenthetik

Az IP-cím általában így néz ki:
`192.168.x.x` vagy `10.0.x.x`

![Példa az útválasztó csatlakoztatott eszközeire](../assets/setup-guide/hu/img_01_en_US.png)


## C lehetőség: Ellenőrizze a hálózatot

Használjon hálózati szkenner alkalmazást az eszközén.

Vizsgálja át a hálózatot, és próbálja megnyitni a talált IP-címeket Safariban, például:

`http://192.168.1.50`

Ha megjelenik a hozzáférés-vezérlő bejelentkezési oldala, megtalálta a megfelelő címet.

![Példa hálózati szkenner alkalmazásra](../assets/setup-guide/hu/img_02_en_US.png)


## 2. lépés: Keresse meg a hozzáférés-vezérlő bejelentkezési adatait

Egyes vezérlők még mindig alapértelmezett bejelentkezési adatokat használnak. Gyakori példa a `abc` felhasználónév és a `654321` jelszó.

Más gyakori gyári felhasználónevek: `user`, `admin` vagy `123`. Kipróbálhatja őket tipikus jelszavakkal, például `1234`, `user` vagy `password`, illetve ezek valamelyik változatával.

Ha a rendszert szakember telepítette, kérdezze meg a telepítőt, hogy módosították-e az alapértelmezett adatokat.


## 3. lépés: Adja hozzá a hozzáférés-vezérlőt a GateTaphez

Nyissa meg a GateTapet, és adja meg:

- Az IP-címet
- A felhasználónevet
- A jelszót

Ugyanazokat az adatokat használja, mint a hozzáférés-vezérlő webes felületén.


## 4. lépés: Tesztelje a kapcsolatot

Mentse a konfigurációt, és próbáljon meg kinyitni egy ajtót vagy kaput.

Ha semmi sem történik, ellenőrizze:

- Az eszköz ugyanazon a hálózaton van, mint a hozzáférés-vezérlő
- Az IP-cím helyes
- A hozzáférés-vezérlő áram alatt van és elérhető


## 5. lépés: Tartsa stabilan az IP-címet

A későbbi problémák elkerülése érdekében a vezérlőnek mindig ugyanazt az IP-címet kell használnia.

Ezt így lehet megoldani:

- Statikus IP beállítása a vezérlőn
- DHCP-foglalás létrehozása az útválasztóban


## Demó mód

A GateTap demó módot is tartalmaz. Az alkalmazásból elindíthat egy helyi demó webszervert, majd hozzáadhatja úgy, mint egy normál vezérlőt.

Ez egy ismerten működő tesztelési utat ad annak ellenőrzésére, hogy maga a GateTap megfelelően működik-e, még akkor is, ha jelenleg nincs hozzáférése fizikai hozzáférés-vezérlőhöz.


## Biztonság

Adatai az eszközön maradnak.

Opcionálisan védheti a GateTap-et Face ID vagy Touch ID használatával az alkalmazás beállításaiban.


