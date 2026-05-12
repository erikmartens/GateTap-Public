<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: tr
-->

# Kurulum Kılavuzu

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | 🇹🇷 Türkçe | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

GateTap'i erişim denetleyicinize bağlayın

## Erişim denetleyicisi nedir?

Erişim denetleyicisi, kapıların, bahçe kapılarının, garajların veya bariyerlerin açılmasını yöneten bir cihazdır — örneğin kapı zili kilidini veya kapı motorunu etkinleştirir.
Açma sinyalini genellikle şunlardan alır:

- interkom sistemi
- tuş takımı
- anahtarlık veya erişim kartı

Birçok modern erişim kontrol sistemi yerel ağa bağlıdır ve tarayıcıdaki web arayüzü üzerinden kullanılabilir. GateTap bu sisteme doğrudan bağlanır, böylece cihazınızdan kolayca kontrol edebilirsiniz.


## Başlamadan önce

Cihazınızın erişim denetleyicisiyle aynı yerel ağa bağlı olduğundan emin olun. Örneğin iPhone’unuzun ev Wi‑Fi ağına bağlı olduğunu ve mobil veri kullanmadığını kontrol edin.

GateTap tamamen yerel ağınız içinde çalışır ve şunlara ihtiyaç duyar:

- Denetleyicinin IP adresi
- Kullanıcı adı ve parola


## 1. Adım: Erişim denetleyicisinin IP adresini bulun

GateTap’i bağlamak için denetleyicinin IP adresine ve oturum açma bilgilerine ihtiyacınız var — 2. adıma bakın.

Aşağıdaki seçeneklerden birini seçin:


## Seçenek A: Montajcınıza sorun (önerilir)

Sisteminiz bir elektrikçi veya teknisyen tarafından kurulduysa, muhtemelen her şeyi zaten yapılandırmıştır.

Çoğu durumda:

- Denetleyici sabit bir IP adresi kullanır
- Ya da yönlendirici DHCP rezervasyonu ile ona aynı IP adresini verir

IP adresini ve oturum açma bilgilerini isteyin. Bu genellikle en kolay ve en hızlı yöntemdir.


## Seçenek B: Yönlendiricinizi kontrol edin

Yönlendiricinize erişmek için genellikle `192.168.1.1` gibi yerel adresine veya `fritz.box` gibi bir adına ve yönlendiricinin oturum açma bilgilerine ihtiyacınız vardır.

Yönlendiricinin yapılandırma sayfasını açın ve bağlı cihazları arayın.

Bu bölüm şu adlarla geçebilir:

- Ağ
- Bağlı cihazlar
- LAN
- DHCP istemcileri

Şunlara bakın:

- Bilinmeyen kablolu cihazlar
- Denetleyicinizi temsil edebilecek kayıtlar

IP adresi genellikle şöyle görünür:
`192.168.x.x` veya `10.0.x.x`

![Yönlendiricide bağlı cihazlar örneği](../assets/setup-guide/tr/img_01_en_US.png)


## Seçenek C: Ağınızı tarayın

Cihazınızda bir ağ tarayıcı uygulaması kullanın.

Ağınızı tarayın ve şunları arayın:

- Bilinmeyen kablolu cihazlar
- Denetleyicinizi temsil edebilecek kayıtlar

IP adresi genellikle şöyle görünür:
`192.168.x.x` veya `10.0.x.x`


## IP adresini test edin

Bulunan IP adresini Safari’de açmayı deneyin, örneğin:

`http://192.168.1.50`

Erişim denetleyicisinin oturum açma sayfası görünürse doğru adresi buldunuz.


## 2. Adım: Erişim denetleyicisinin oturum açma bilgilerini bulun

Bazı erişim denetleyicileri hâlâ varsayılan oturum açma bilgilerini kullanır. Yaygın bir örnek, `abc` kullanıcı adı ve `654321` parolasıdır.

Diğer yaygın varsayılan kullanıcı adları `user`, `admin` veya `123` olabilir. Bunları `1234`, `user` veya `password` gibi tipik parolalarla ya da bir varyasyonuyla deneyebilirsiniz.

Sistem profesyonel olarak kurulduysa, varsayılan bilgilerin değiştirilip değiştirilmediğini kurulum yapan kişiye sorun.


## 3. Adım: Erişim denetleyicisini GateTap’e ekleyin

GateTap’i açın. Denetleyici ekleme sayfası otomatik olarak görünmezse "Controller" sekmesine geçin ve sağ üstteki gezinme çubuğunda bulunan "+" düğmesine dokunun.

Görünen sayfada şunları girin:

- IP adresi
- Kullanıcı adı
- Parola

Erişim denetleyicisinin web arayüzü için kullandığınız aynı oturum açma bilgilerini kullanın.


## 4. Adım: Bağlantıyı test edin

Yapılandırmayı kaydedin. Uygulama otomatik olarak bağlanmayı deneyecektir.

Bağlantı kurulamıyorsa şunları kontrol edin:

- Cihazınız erişim denetleyicisiyle aynı ağda
- IP adresi doğru
- Erişim denetleyicisi açık ve erişilebilir


## 5. Adım: IP adresini sabit tutun

Daha sonra sorun yaşamamak için denetleyici her zaman aynı IP adresini kullanmalıdır.

Bunu şu şekilde yapabilirsiniz:

- Denetleyicide statik IP ayarlamak
- Yönlendiricide DHCP rezervasyonu oluşturmak


## Demo modu

GateTap ayrıca demo modu içerir. Uygulama içinden sanal bir erişim denetleyicisi başlatabilirsiniz; bu denetleyici gerçek bir erişim kontrol sisteminin sunduğu yönetim arayüzünü sunar. Ardından gösterilen IP adresi ve oturum açma bilgileriyle normal bir denetleyici gibi ekleyebilirsiniz.

Bu, şu anda fiziksel bir erişim denetleyiciniz olmasa bile GateTap’in özelliklerini keşfetmek için çalıştığı bilinen bir test yolu sağlar.


## Güvenlik

Verileriniz cihazınızda kalır.

GateTap'i isteğe bağlı olarak uygulama ayarlarında Face ID veya Touch ID kullanarak koruyabilirsiniz.


