<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: fi
-->

# Asennusopas

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | 🌐 fi | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

---

Yhdistä GateTap pääsyohjaimeen

## Ennen kuin aloitat

Varmista, että iPhonesi on yhdistetty samaan paikallisverkkoon kuin pääsynohjain.

GateTap toimii täysin paikallisessa verkossasi ja tarvitsee:
• Ohjaimen IP-osoite
• Käyttäjätunnus ja salasana


## Vaihe 1: Etsi ohjaimen osoite ja tunnistetiedot

GateTap-yhteyttä varten tarvitset ohjaimen IP-osoitteen ja kirjautumistiedot.

Valitse yksi seuraavista vaihtoehdoista:


## Vaihtoehto A: Kysy asentajalta (suositus)

Jos järjestelmäsi on asentanut sähköasentaja tai teknikko, he ovat todennäköisesti jo määrittäneet kaiken.

Monissa tapauksissa:
• Ohjain käyttää kiinteää IP-osoitetta
• Tai reititin määrittää saman IP:n varauksen kautta

Pyydä heiltä IP-osoite ja kirjautumistiedot. Tämä on yleensä helpoin ja nopein tapa.


## Vaihtoehto B: Tarkista reitittimesi

Avaa reitittimesi määrityssivu ja etsi liitetyt laitteet.

Reitittimen käyttämiseen tarvitaan yleensä sen paikallinen osoite (esim. `192.168.1.1` tai nimi, kuten `fritz.box`) ja reitittimen kirjautumistiedot.

Tämän osion nimi voi olla:
• Kytketyt laitteet
• LAN
• DHCP-asiakkaat

Etsi:
• Tuntemattomat langalliset laitteet
• Merkinnät, jotka saattavat edustaa ohjaintasi

IP-osoite näyttää yleensä tältä:
`192.168.x.x` tai `10.0.x.x`.

![Reitittimeen liitettyjen laitteiden esimerkki](../assets/setup-guide/fi/img_01.png)


## Vaihtoehto C: Tarkista verkkosi

Käytä verkkoskannerisovellusta iPhonessa tai tietokoneessa.

Tarkista verkkosi ja yritä avata löydetyt IP-osoitteet Safarissa, esimerkiksi:

`http://192.168.1.50`.

Jos ohjaimen kirjautumissivu tulee näkyviin, olet löytänyt oikean osoitteen.

![Verkkoskannerin esimerkki](../assets/setup-guide/fi/img_02.png)


## Vaihe 2: Lisää ohjain GateTapissa

Avaa GateTap ja kirjoita:
• IP-osoite
• Käyttäjätunnuksesi
• Salasanasi

Käytä samoja tunnistetietoja kuin ohjaimen verkkokäyttöliittymässä.


## Vaihe 3: Testaa yhteys

Tallenna määritykset ja yritä avata ovi tai portti.

Jos mitään ei tapahdu, tarkista:
• iPhonesi on samassa verkossa
• IP-osoite on oikea
• Ohjaimessa on virta ja se on tavoitettavissa


## Vaihe 4: Pidä IP-osoite vakaana

Myöhempien ongelmien välttämiseksi ohjaimen tulee aina käyttää samaa IP-osoitetta.

Tämä voidaan tehdä seuraavasti:
• Staattisen IP:n asettaminen ohjaimelle
• Luodaan DHCP-varaus reitittimeen


## Turvallisuus

Tietosi pysyvät laitteessasi.

Voit halutessasi suojata GateTapin Face ID:llä tai Touch ID:llä sovelluksen asetuksissa.


