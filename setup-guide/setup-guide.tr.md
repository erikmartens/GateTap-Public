<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: tr
-->

# Kurulum Kılavuzu

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | 🇹🇷 Türkçe | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

GateTap'i erişim denetleyicinize bağlayın

## Başlamadan önce

iPhone'unuzun erişim denetleyicinizle aynı yerel ağa bağlı olduğundan emin olun.

GateTap tamamen yerel ağınız ve ihtiyaçlarınız dahilinde çalışır:
• Denetleyicinin IP adresi
• Kullanıcı adı ve şifre


## 1. Adım: Denetleyici adresini ve kimlik bilgilerini bulun

GateTap'i bağlamak için denetleyicinin IP adresine ve oturum açma kimlik bilgilerine ihtiyacınız vardır.

Aşağıdaki seçeneklerden birini seçin:


## Seçenek A: Montajcınıza sorun (önerilir)

Sisteminiz bir elektrikçi veya teknisyen tarafından kurulduysa, muhtemelen her şeyi zaten yapılandırmışlardır.

Birçok durumda:
• Denetleyici sabit bir IP adresi kullanır
• Veya yönlendirici aynı IP'yi rezervasyon yoluyla atar

Onlardan IP adresini ve giriş bilgilerini isteyin. Bu genellikle en kolay ve en hızlı yoldur.


## Seçenek B: Yönlendiricinizi kontrol edin

Yönlendiricinizin yapılandırma sayfasını açın ve bağlı cihazları arayın.

Yönlendiricinize erişmek için genellikle yerel adresine (örneğin, `192.168.1.1` veya `fritz.box` gibi bir ad) ve yönlendiricinin oturum açma kimlik bilgilerine ihtiyacınız vardır.

Bu bölüm şu şekilde adlandırılabilir:
• Bağlı Cihazlar
• Yerel Ağ
• DHCP İstemcileri

Şunu arayın:
• Bilinmeyen kablolu cihazlar
• Denetleyicinizi temsil edebilecek girişler

IP adresi genellikle şöyle görünecektir:
`192.168.x.x` veya `10.0.x.x`

![Yönlendiriciye bağlı cihazlar örneği](../assets/setup-guide/tr/img_01.png)


## Seçenek C: Ağınızı tarayın

iPhone'unuzda veya bilgisayarınızda bir ağ tarayıcı uygulaması kullanın.

Ağınızı tarayın ve keşfedilen IP adreslerini Safari'de açmayı deneyin, örneğin:

`http://192.168.1.50`

Kontrolörün oturum açma sayfası görünürse doğru adresi buldunuz demektir.

![Ağ tarayıcısı örneği](../assets/setup-guide/tr/img_02.png)


## Adım 2: Denetleyiciyi GateTap'e ekleyin

GateTap'i açın ve şunu girin:
• IP adresi
• Kullanıcı adınız
• Şifreniz

Denetleyicinin web arayüzüyle aynı kimlik bilgilerini kullanın.


## 3. Adım: Bağlantıyı test edin

Yapılandırmanızı kaydedin ve bir kapıyı veya geçidi açmayı deneyin.

Hiçbir şey olmazsa şunları kontrol edin:
• iPhone'unuz aynı ağda
• IP adresi doğrudur
• Denetleyiciye güç veriliyor ve erişilebilir durumda


## 4. Adım: IP adresini sabit tutun

Daha sonra sorun yaşamamak için denetleyicinin her zaman aynı IP adresini kullanması gerekir.

Bu şu şekilde yapılabilir:
• Denetleyicide statik IP ayarlama
• Yönlendiricinizde DHCP rezervasyonu oluşturma


## Güvenlik

Verileriniz cihazınızda kalır.

GateTap'i isteğe bağlı olarak uygulama ayarlarında Face ID veya Touch ID kullanarak koruyabilirsiniz.


