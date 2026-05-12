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

## Apa itu pengontrol akses?

Pengontrol akses adalah perangkat yang mengelola pembukaan pintu, gerbang, garasi, atau palang — misalnya dengan mengaktifkan buzzer pintu atau motor gerbang.
Biasanya perangkat ini menerima sinyal pembuka dari:

- sistem interkom
- keypad
- key fob atau kartu akses

Banyak sistem kontrol akses modern terhubung ke jaringan lokal dan dapat dioperasikan melalui antarmuka web di browser. GateTap terhubung langsung ke sistem tersebut sehingga Anda dapat mengoperasikannya dengan mudah dari perangkat Anda.


## Sebelum Anda mulai

Pastikan perangkat Anda tersambung ke jaringan lokal yang sama dengan pengontrol akses. Misalnya, pastikan iPhone tersambung ke Wi‑Fi rumah dan tidak menggunakan data seluler.

GateTap bekerja sepenuhnya di dalam jaringan lokal Anda dan membutuhkan:

- Alamat IP pengontrol
- Nama pengguna dan kata sandi


## Langkah 1: Temukan alamat IP pengontrol akses Anda

Untuk menghubungkan GateTap, Anda membutuhkan alamat IP pengontrol dan kredensial login — lihat Langkah 2.

Pilih salah satu opsi berikut:


## Opsi A: Tanyakan kepada penginstal Anda (disarankan)

Jika sistem Anda dipasang oleh teknisi listrik atau teknisi, kemungkinan mereka sudah mengonfigurasi semuanya.

Dalam banyak kasus:

- Pengontrol menggunakan alamat IP tetap
- Atau router memberikan alamat IP yang sama melalui reservasi DHCP

Mintalah alamat IP dan informasi login kepada mereka. Ini biasanya cara paling mudah dan cepat.


## Opsi B: Periksa router Anda

Untuk mengakses router, Anda biasanya memerlukan alamat lokalnya, misalnya `192.168.1.1` atau nama seperti `fritz.box`, serta kredensial login router.

Buka halaman konfigurasi router dan cari perangkat yang terhubung.

Bagian ini mungkin bernama:

- Jaringan
- Perangkat terhubung
- LAN
- Klien DHCP

Cari:

- Perangkat kabel yang tidak dikenal
- Entri yang mungkin mewakili pengontrol Anda

Alamat IP biasanya terlihat seperti:
`192.168.x.x` atau `10.0.x.x`

![Contoh perangkat terhubung di router](../assets/setup-guide/id/img_01_en_US.png)


## Opsi C: Pindai jaringan Anda

Gunakan aplikasi pemindai jaringan di perangkat Anda.

Pindai jaringan Anda dan cari:

- Perangkat kabel yang tidak dikenal
- Entri yang mungkin mewakili pengontrol Anda

Alamat IP biasanya terlihat seperti:
`192.168.x.x` atau `10.0.x.x`


## Uji alamat IP

Coba buka alamat IP yang ditemukan di Safari, misalnya:

`http://192.168.1.50`

Jika halaman login pengontrol akses muncul, Anda telah menemukan alamat yang benar.


## Langkah 2: Temukan kredensial login pengontrol akses

Sebagian pengontrol akses masih menggunakan kredensial login bawaan. Contoh umum adalah nama pengguna `abc` dengan kata sandi `654321`.

Nama pengguna bawaan lain yang umum adalah `user`, `admin`, atau `123`. Anda dapat mencobanya dengan kata sandi umum seperti `1234`, `user`, atau `password`, atau variasinya.

Jika sistem Anda dipasang secara profesional, tanyakan kepada pemasang apakah kredensial bawaan telah diubah.


## Langkah 3: Tambahkan pengontrol akses di GateTap

Buka GateTap. Jika halaman untuk menambahkan pengontrol tidak muncul otomatis, buka tab "Controller" dan ketuk tombol "+" di bilah navigasi kanan atas.

Pada halaman yang muncul, masukkan:

- Alamat IP
- Nama pengguna
- Kata sandi

Gunakan kredensial login yang sama dengan antarmuka web pengontrol akses.


## Langkah 4: Uji koneksi

Simpan konfigurasi Anda. Aplikasi akan otomatis mencoba terhubung.

Jika koneksi tidak dapat dibuat, periksa:

- Perangkat Anda berada di jaringan yang sama dengan pengontrol akses
- Alamat IP benar
- Pengontrol akses menyala dan dapat dijangkau


## Langkah 5: Jaga agar alamat IP tetap stabil

Untuk menghindari masalah nanti, pengontrol harus selalu menggunakan alamat IP yang sama.

Ini dapat dilakukan dengan:

- Mengatur IP statis pada pengontrol
- Membuat reservasi DHCP di router


## Mode demo

GateTap juga menyertakan mode demo. Anda dapat memulai pengontrol akses virtual dari dalam aplikasi, yang menyajikan antarmuka administrasi seperti sistem kontrol akses nyata. Setelah itu Anda dapat menambahkannya seperti pengontrol biasa menggunakan alamat IP dan kredensial yang ditampilkan.

Ini memberi Anda jalur pengujian yang diketahui berfungsi untuk menjelajahi fitur GateTap, meskipun saat ini Anda tidak memiliki pengontrol akses fisik.


## Keamanan

Data Anda tetap ada di perangkat Anda.

Anda juga dapat melindungi GateTap menggunakan Face ID atau Touch ID di pengaturan aplikasi.


