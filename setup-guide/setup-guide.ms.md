<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: ms
-->

# Panduan Persediaan

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | 🌐 ms | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

---

Sambungkan GateTap kepada pengawal akses anda

## Sebelum anda bermula

Pastikan iPhone anda disambungkan ke rangkaian tempatan yang sama dengan pengawal akses anda.

GateTap berfungsi sepenuhnya dalam rangkaian dan keperluan tempatan anda:
• Alamat IP pengawal
• Nama pengguna dan kata laluan


## Langkah 1: Cari alamat pengawal dan bukti kelayakan

Untuk menyambungkan GateTap, anda memerlukan alamat IP pengawal dan bukti kelayakan log masuk.

Pilih salah satu daripada pilihan berikut:


## Pilihan A: Tanya pemasang anda (disyorkan)

Jika sistem anda dipasang oleh juruelektrik atau juruteknik, mereka mungkin telah mengkonfigurasi segala-galanya.

Dalam banyak kes:
• Pengawal menggunakan alamat IP tetap
• Atau penghala memberikan IP yang sama melalui tempahan

Minta mereka alamat IP dan butiran log masuk. Ini biasanya cara yang paling mudah dan cepat.


## Pilihan B: Semak penghala anda

Buka halaman konfigurasi penghala anda dan cari peranti yang disambungkan.

Untuk mengakses penghala anda, anda biasanya memerlukan alamat setempatnya (cth. `192.168.1.1` atau nama seperti `fritz.box`) dan bukti kelayakan log masuk penghala.

Bahagian ini boleh dipanggil:
• Peranti Bersambung
• LAN
• Pelanggan DHCP

Cari:
• Peranti berwayar tidak diketahui
• Entri yang mungkin mewakili pengawal anda

Alamat IP biasanya akan kelihatan seperti:
`192.168.x.x` atau `10.0.x.x`

![Contoh peranti yang disambungkan penghala](../assets/setup-guide/ms/img_01.png)


## Pilihan C: Imbas rangkaian anda

Gunakan apl pengimbas rangkaian pada iPhone atau komputer anda.

Imbas rangkaian anda dan cuba buka alamat IP yang ditemui dalam Safari, contohnya:

`http://192.168.1.50`

Jika halaman log masuk pengawal muncul, anda telah menemui alamat yang betul.

![Contoh pengimbas rangkaian](../assets/setup-guide/ms/img_02.png)


## Langkah 2: Tambahkan pengawal dalam GateTap

Buka GateTap dan masukkan:
• Alamat IP
• Nama pengguna anda
• Kata laluan anda

Gunakan kelayakan yang sama seperti untuk antara muka web pengawal.


## Langkah 3: Uji sambungan

Simpan konfigurasi anda dan cuba buka pintu atau pagar.

Jika tiada apa-apa berlaku, semak:
• iPhone anda berada pada rangkaian yang sama
• Alamat IP adalah betul
• Pengawal dikuasakan dan boleh dicapai


## Langkah 4: Pastikan alamat IP stabil

Untuk mengelakkan masalah kemudian, pengawal hendaklah sentiasa menggunakan alamat IP yang sama.

Ini boleh dilakukan dengan:
• Menetapkan IP statik pada pengawal
• Membuat tempahan DHCP dalam penghala anda


## Keselamatan

Data anda kekal pada peranti anda.

Anda boleh melindungi GateTap secara pilihan menggunakan Face ID atau Touch ID dalam tetapan apl.


