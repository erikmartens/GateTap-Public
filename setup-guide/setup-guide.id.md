<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: id
-->

# Panduan Pengaturan

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | 🇮🇩 Bahasa Indonesia | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Hubungkan GateTap ke pengontrol akses Anda

## Sebelum Anda mulai

Pastikan perangkat Anda terhubung ke jaringan lokal yang sama dengan pengontrol akses Anda. Misalnya, pastikan iPhone Anda memakai Wi-Fi rumah, bukan koneksi data seluler.

GateTap bekerja sepenuhnya di dalam jaringan lokal Anda dan membutuhkan:
• Alamat IP pengontrol
• Nama pengguna dan kata sandi


## Langkah 1: Temukan alamat IP pengontrol akses

Untuk menghubungkan GateTap, Anda membutuhkan alamat IP pengontrol dan kredensial login - lihat Langkah 2.

Pilih salah satu opsi berikut:


## Opsi A: Tanyakan kepada penginstal Anda (disarankan)

Jika sistem Anda dipasang oleh teknisi listrik atau teknisi, kemungkinan besar semuanya sudah dikonfigurasi.

Dalam banyak kasus:
• Pengontrol menggunakan alamat IP tetap
• Atau router menetapkan IP yang sama melalui reservasi DHCP

Mintalah alamat IP dan detail login. Ini biasanya cara termudah dan tercepat.


## Opsi B: Periksa router Anda

Buka halaman konfigurasi router Anda dan cari perangkat yang terhubung.

Untuk mengakses router, biasanya Anda memerlukan alamat lokalnya, misalnya `192.168.1.1` atau nama seperti `fritz.box`, serta kredensial login router.

Bagian ini mungkin disebut:
• Jaringan
• Perangkat Terhubung
• LAN
• Klien DHCP

Cari:
• Perangkat berkabel yang tidak dikenal
• Entri yang mungkin mewakili pengontrol Anda

Alamat IP biasanya terlihat seperti:
`192.168.x.x` atau `10.0.x.x`

![Contoh perangkat yang terhubung di router](../assets/setup-guide/id/img_01_en_US.png)


## Opsi C: Pindai jaringan Anda

Gunakan aplikasi pemindai jaringan di perangkat Anda.

Pindai jaringan Anda dan coba buka alamat IP yang ditemukan di Safari, misalnya:

`http://192.168.1.50`

Jika halaman login pengontrol akses muncul, Anda telah menemukan alamat yang benar.

![Contoh aplikasi pemindai jaringan](../assets/setup-guide/id/img_02_en_US.png)


## Langkah 2: Temukan kredensial login pengontrol akses

Beberapa pengontrol masih menggunakan kredensial login bawaan. Contoh umum adalah nama pengguna `abc` dengan kata sandi `654321`.

Nama pengguna bawaan lain yang umum digunakan adalah `user`, `admin`, atau `123`. Anda dapat mencobanya dengan kata sandi umum seperti `1234`, `user`, atau `password`, atau variasinya.

Jika sistem Anda dipasang secara profesional, tanyakan kepada penginstal apakah kredensial bawaan telah diubah.


## Langkah 3: Tambahkan pengontrol akses di GateTap

Buka GateTap dan masukkan:
• Alamat IP
• Nama pengguna Anda
• Kata sandi Anda

Gunakan kredensial yang sama seperti untuk antarmuka web pengontrol akses.


## Langkah 4: Uji koneksi

Simpan konfigurasi Anda dan coba buka pintu atau gerbang.

Jika tidak ada yang terjadi, periksa:
• Perangkat Anda berada di jaringan yang sama dengan pengontrol akses
• Alamat IP benar
• Pengontrol akses menyala dan dapat dijangkau


## Langkah 5: Jaga agar alamat IP tetap stabil

Untuk menghindari masalah nanti, pengontrol sebaiknya selalu menggunakan alamat IP yang sama.

Ini dapat dilakukan dengan:
• Menetapkan IP statis pada pengontrol
• Membuat reservasi DHCP di router Anda


## Mode demo

GateTap juga menyertakan mode demo. Anda dapat memulai server web demo lokal dari dalam aplikasi, lalu menambahkannya seperti pengontrol biasa.

Ini memberi Anda jalur pengujian yang diketahui berfungsi untuk memastikan GateTap sendiri berjalan dengan benar, meskipun saat ini Anda tidak memiliki akses ke pengontrol akses fisik.


## Keamanan

Data Anda tetap ada di perangkat Anda.

Anda juga dapat melindungi GateTap menggunakan Face ID atau Touch ID di pengaturan aplikasi.


