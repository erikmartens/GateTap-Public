<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: id
-->

# Panduan Pengaturan

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | 🇮🇩 Bahasa Indonesia | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Hubungkan GateTap ke pengontrol akses Anda

## Sebelum Anda mulai

Pastikan iPhone Anda terhubung ke jaringan lokal yang sama dengan pengontrol akses Anda.

GateTap berfungsi sepenuhnya dalam jaringan lokal Anda dan membutuhkan:
• Alamat IP pengontrol
• Nama pengguna dan kata sandi


## Langkah 1: Temukan alamat pengontrol dan kredensial

Untuk menghubungkan GateTap, Anda memerlukan alamat IP pengontrol dan kredensial login.

Pilih salah satu opsi berikut:


## Opsi A: Tanyakan kepada penginstal Anda (disarankan)

Jika sistem Anda dipasang oleh teknisi listrik atau teknisi, kemungkinan besar mereka sudah mengonfigurasi semuanya.

Dalam banyak kasus:
• Pengontrol menggunakan alamat IP tetap
• Atau router memberikan IP yang sama melalui reservasi

Tanyakan kepada mereka alamat IP dan detail login. Ini biasanya merupakan cara termudah dan tercepat.


## Opsi B: Periksa router Anda

Buka halaman konfigurasi router Anda dan cari perangkat yang terhubung.

Untuk mengakses router, Anda biasanya memerlukan alamat lokalnya (misalnya `192.168.1.1` atau nama seperti `fritz.box`) dan kredensial login router.

Bagian ini dapat disebut:
• Perangkat yang Terhubung
• LAN
• Klien DHCP

Carilah:
• Perangkat berkabel tidak dikenal
• Entri yang mungkin mewakili pengontrol Anda

Alamat IP biasanya akan terlihat seperti:
`192.168.x.x` atau `10.0.x.x`

![Contoh perangkat yang terhubung dengan router](../assets/setup-guide/id/img_01.png)


## Opsi C: Pindai jaringan Anda

Gunakan aplikasi pemindai jaringan di iPhone atau komputer Anda.

Pindai jaringan Anda dan coba buka alamat IP yang ditemukan di Safari, misalnya:

`http://192.168.1.50`

Jika halaman login pengontrol muncul, Anda telah menemukan alamat yang benar.

![Contoh pemindai jaringan](../assets/setup-guide/id/img_02.png)


## Langkah 2: Tambahkan pengontrol di GateTap

Buka GateTap dan masukkan:
• Alamat IP
• Nama pengguna Anda
• Kata sandi Anda

Gunakan kredensial yang sama seperti untuk antarmuka web pengontrol.


## Langkah 3: Uji koneksi

Simpan konfigurasi Anda dan coba buka pintu atau gerbang.

Jika tidak terjadi apa-apa, periksa:
• iPhone Anda berada di jaringan yang sama
• Alamat IP sudah benar
• Pengontrol diberi daya dan dapat dijangkau


## Langkah 4: Jaga agar alamat IP tetap stabil

Untuk menghindari masalah di kemudian hari, pengontrol harus selalu menggunakan alamat IP yang sama.

Hal ini dapat dilakukan dengan:
• Mengatur IP statis pada pengontrol
• Membuat reservasi DHCP di router Anda


## Keamanan

Data Anda tetap ada di perangkat Anda.

Anda juga dapat melindungi GateTap menggunakan Face ID atau Touch ID di pengaturan aplikasi.


