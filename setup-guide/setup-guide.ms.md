<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: ms
-->

# Panduan Persediaan

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | 🇲🇾 Bahasa Melayu | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Sambungkan GateTap kepada pengawal akses anda

## Sebelum anda bermula

Pastikan peranti anda disambungkan ke rangkaian tempatan yang sama seperti pengawal akses anda. Contohnya, pastikan iPhone anda berada pada Wi-Fi rumah dan bukan sambungan data mudah alih.

GateTap berfungsi sepenuhnya dalam rangkaian tempatan anda dan memerlukan:

- Alamat IP pengawal
- Nama pengguna dan kata laluan


## Langkah 1: Cari alamat IP pengawal akses

Untuk menyambungkan GateTap, anda memerlukan alamat IP pengawal dan bukti kelayakan log masuk - lihat Langkah 2.

Pilih salah satu pilihan berikut:


## Pilihan A: Tanya pemasang anda (disyorkan)

Jika sistem anda dipasang oleh juruelektrik atau juruteknik, mereka mungkin sudah mengkonfigurasi semuanya.

Dalam banyak kes:

- Pengawal menggunakan alamat IP tetap
- Atau penghala memberikan IP yang sama melalui tempahan DHCP

Minta alamat IP dan butiran log masuk. Ini biasanya cara paling mudah dan pantas.


## Pilihan B: Semak penghala anda

Buka halaman konfigurasi penghala anda dan cari peranti yang disambungkan.

Untuk mengakses penghala, anda biasanya memerlukan alamat tempatannya, contohnya `192.168.1.1` atau nama seperti `fritz.box`, serta bukti kelayakan log masuk penghala.

Bahagian ini mungkin dipanggil:

- Rangkaian
- Peranti Disambungkan
- LAN
- Klien DHCP

Cari:

- Peranti berwayar yang tidak dikenali
- Entri yang mungkin mewakili pengawal anda

Alamat IP biasanya kelihatan seperti:
`192.168.x.x` atau `10.0.x.x`

![Contoh peranti disambungkan dalam penghala](../assets/setup-guide/ms/img_01_en_US.png)


## Pilihan C: Imbas rangkaian anda

Gunakan aplikasi pengimbas rangkaian pada peranti anda.

Imbas rangkaian anda dan cuba buka alamat IP yang ditemui dalam Safari, contohnya:

`http://192.168.1.50`

Jika halaman log masuk pengawal akses muncul, anda telah menemui alamat yang betul.

![Contoh aplikasi pengimbas rangkaian](../assets/setup-guide/ms/img_02_en_US.png)


## Langkah 2: Cari bukti kelayakan log masuk pengawal akses

Sesetengah pengawal masih menggunakan bukti kelayakan log masuk lalai. Contoh biasa ialah nama pengguna `abc` dengan kata laluan `654321`.

Nama pengguna kilang lain yang lazim digunakan ialah `user`, `admin` atau `123`. Anda boleh mencubanya bersama kata laluan biasa seperti `1234`, `user` atau `password`, atau variasinya.

Jika sistem anda dipasang secara profesional, tanya pemasang sama ada bukti kelayakan lalai telah ditukar.


## Langkah 3: Tambah pengawal akses dalam GateTap

Buka GateTap dan masukkan:

- Alamat IP
- Nama pengguna anda
- Kata laluan anda

Gunakan bukti kelayakan yang sama seperti antara muka web pengawal akses.


## Langkah 4: Uji sambungan

Simpan konfigurasi anda dan cuba buka pintu atau pagar.

Jika tiada apa-apa berlaku, semak:

- Peranti anda berada pada rangkaian yang sama seperti pengawal akses
- Alamat IP adalah betul
- Pengawal akses dihidupkan dan boleh dicapai


## Langkah 5: Pastikan alamat IP stabil

Untuk mengelakkan masalah kemudian, pengawal harus sentiasa menggunakan alamat IP yang sama.

Ini boleh dilakukan dengan:

- Menetapkan IP statik pada pengawal
- Membuat tempahan DHCP dalam penghala anda


## Mod demo

GateTap juga menyertakan mod demo. Anda boleh memulakan pelayan web demo setempat dari dalam aplikasi dan kemudian menambahkannya seperti pengawal biasa.

Ini memberi anda laluan ujian yang diketahui berfungsi untuk mengesahkan bahawa GateTap sendiri berfungsi dengan betul, walaupun anda tiada akses kepada pengawal akses fizikal pada masa ini.


## Keselamatan

Data anda kekal pada peranti anda.

Anda boleh melindungi GateTap secara pilihan menggunakan Face ID atau Touch ID dalam tetapan apl.


