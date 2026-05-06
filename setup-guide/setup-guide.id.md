<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: id
-->

# Panduan Pengaturan

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | 🌐 id | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

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


