<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: fi
-->

# Asennusopas

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | 🇫🇮 Suomi | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Yhdistä GateTap pääsyohjaimeen

## Ennen kuin aloitat

Varmista, että laitteesi on yhdistetty samaan paikallisverkkoon kuin kulunvalvontaohjain. Varmista esimerkiksi, että iPhone on kodin Wi-Fi-verkossa eikä mobiilidatayhteydessä.

GateTap toimii kokonaan paikallisverkossasi ja tarvitsee:
• Ohjaimen IP-osoitteen
• Käyttäjätunnuksen ja salasanan


## Vaihe 1: Etsi kulunvalvontaohjaimen IP-osoite

GateTapin yhdistämiseen tarvitset ohjaimen IP-osoitteen ja kirjautumistiedot - katso vaihe 2.

Valitse jokin seuraavista vaihtoehdoista:


## Vaihtoehto A: Kysy asentajalta (suositus)

Jos järjestelmän asensi sähköasentaja tai teknikko, hän on todennäköisesti jo määrittänyt kaiken.

Monissa tapauksissa:
• Ohjain käyttää kiinteää IP-osoitetta
• Tai reititin antaa sille saman IP:n DHCP-varauksella

Pyydä IP-osoite ja kirjautumistiedot. Tämä on yleensä helpoin ja nopein tapa.


## Vaihtoehto B: Tarkista reitittimesi

Avaa reitittimen asetussivu ja etsi yhdistetyt laitteet.

Reitittimeen kirjautumiseen tarvitset yleensä sen paikallisen osoitteen, esimerkiksi `192.168.1.1` tai nimen kuten `fritz.box`, sekä reitittimen kirjautumistiedot.

Tämän osion nimi voi olla:
• Verkko
• Yhdistetyt laitteet
• LAN
• DHCP-asiakkaat

Etsi:
• Tuntemattomia langallisia laitteita
• Merkintöjä, jotka voisivat olla ohjaimesi

IP-osoite näyttää yleensä tältä:
`192.168.x.x` tai `10.0.x.x`

![Esimerkki reitittimen yhdistetyistä laitteista](../assets/setup-guide/fi/img_01_en_US.png)


## Vaihtoehto C: Tarkista verkkosi

Käytä verkkoskannerisovellusta laitteellasi.

Skannaa verkko ja kokeile avata löydettyjä IP-osoitteita Safarissa, esimerkiksi:

`http://192.168.1.50`

Jos kulunvalvontaohjaimen kirjautumissivu tulee näkyviin, löysit oikean osoitteen.

![Esimerkki verkkoskannerisovelluksesta](../assets/setup-guide/fi/img_02_en_US.png)


## Vaihe 2: Etsi kulunvalvontaohjaimen kirjautumistiedot

Jotkin ohjaimet käyttävät edelleen oletuskirjautumistietoja. Yleinen esimerkki on käyttäjätunnus `abc` ja salasana `654321`.

Muita yleisiä tehdaskäyttäjätunnuksia ovat `user`, `admin` tai `123`. Voit kokeilla niitä tyypillisten salasanojen, kuten `1234`, `user` tai `password`, tai niiden muunnelmien kanssa.

Jos järjestelmäsi asennettiin ammattilaisen toimesta, kysy asentajalta, onko oletustiedot muutettu.


## Vaihe 3: Lisää kulunvalvontaohjain GateTapiin

Avaa GateTap ja syötä:
• IP-osoite
• Käyttäjätunnus
• Salasana

Käytä samoja kirjautumistietoja kuin kulunvalvontaohjaimen verkkokäyttöliittymässä.


## Vaihe 4: Testaa yhteys

Tallenna määritys ja kokeile avata ovi tai portti.

Jos mitään ei tapahdu, tarkista:
• Että laitteesi on samassa verkossa kuin kulunvalvontaohjain
• Että IP-osoite on oikein
• Että kulunvalvontaohjaimessa on virta ja siihen saa yhteyden


## Vaihe 5: Pidä IP-osoite vakaana

Ongelmien välttämiseksi myöhemmin ohjaimen tulisi aina käyttää samaa IP-osoitetta.

Tämä voidaan tehdä:
• Asettamalla ohjaimeen staattinen IP
• Luomalla DHCP-varaus reitittimeen


## Demotila

GateTap sisältää myös demotilan. Voit käynnistää paikallisen demo-verkkopalvelimen sovelluksesta ja lisätä sen sitten tavallisen ohjaimen tavoin.

Näin saat tunnetusti toimivan testipolun varmistaaksesi, että GateTap toimii oikein, vaikka sinulla ei juuri nyt olisi pääsyä fyysiseen kulunvalvontaohjaimeen.


## Turvallisuus

Tietosi pysyvät laitteessasi.

Voit halutessasi suojata GateTapin Face ID:llä tai Touch ID:llä sovelluksen asetuksissa.


