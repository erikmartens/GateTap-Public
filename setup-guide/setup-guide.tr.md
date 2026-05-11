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

## Başlamadan önce

Cihazınızın erişim denetleyicinizle aynı yerel ağa bağlı olduğundan emin olun. Örneğin iPhone’unuzun mobil veri bağlantısında değil, ev Wi-Fi ağınızda olduğundan emin olun.

GateTap tamamen yerel ağınız içinde çalışır ve şunlara ihtiyaç duyar:

- Denetleyicinin IP adresi
- Kullanıcı adı ve parola


## 1. Adım: Erişim denetleyicisinin IP adresini bulun

GateTap’i bağlamak için denetleyicinin IP adresine ve oturum açma bilgilerine ihtiyacınız vardır - bkz. 2. Adım.

Aşağıdaki seçeneklerden birini seçin:


## Seçenek A: Montajcınıza sorun (önerilir)

Sisteminiz bir elektrikçi veya teknisyen tarafından kurulduysa, büyük olasılıkla her şeyi zaten yapılandırmıştır.

Birçok durumda:

- Denetleyici sabit bir IP adresi kullanır
- Ya da yönlendirici DHCP rezervasyonu ile aynı IP’yi atar

IP adresini ve oturum açma bilgilerini isteyin. Bu genellikle en kolay ve en hızlı yoldur.


## Seçenek B: Yönlendiricinizi kontrol edin

Yönlendiricinizin yapılandırma sayfasını açın ve bağlı cihazları arayın.

Yönlendiriciye erişmek için genellikle `192.168.1.1` gibi yerel adresine veya `fritz.box` gibi bir adına ve yönlendiricinin oturum açma bilgilerine ihtiyaç duyarsınız.

Bu bölüm şu adlarla görünebilir:

- Ağ
- Bağlı Cihazlar
- LAN
- DHCP İstemcileri

Şunları arayın:

- Bilinmeyen kablolu cihazlar
- Denetleyicinizi temsil edebilecek kayıtlar

IP adresi genellikle şöyle görünür:
`192.168.x.x` veya `10.0.x.x`

![Yönlendiricide bağlı cihaz örneği](../assets/setup-guide/tr/img_01_en_US.png)


## Seçenek C: Ağınızı tarayın

Cihazınızda bir ağ tarayıcı uygulaması kullanın.

Ağınızı tarayın ve bulunan IP adreslerini Safari’de açmayı deneyin, örneğin:

`http://192.168.1.50`

Erişim denetleyicisinin giriş sayfası görünürse doğru adresi buldunuz.

![Ağ tarayıcı uygulaması örneği](../assets/setup-guide/tr/img_02_en_US.png)


## 2. Adım: Erişim denetleyicisinin oturum açma bilgilerini bulun

Bazı denetleyiciler hâlâ varsayılan oturum açma bilgilerini kullanır. Yaygın bir örnek, `abc` kullanıcı adı ve `654321` parolasıdır.

Sık kullanılan diğer fabrika kullanıcı adları `user`, `admin` veya `123` şeklindedir. Bunları `1234`, `user` veya `password` gibi tipik parolalarla ya da bunların bir varyasyonuyla deneyebilirsiniz.

Sisteminiz profesyonel olarak kurulduysa, varsayılan bilgilerin değiştirilip değiştirilmediğini montajcınıza sorun.


## 3. Adım: Erişim denetleyicisini GateTap’e ekleyin

GateTap’i açın ve şunları girin:

- IP adresi
- Kullanıcı adınız
- Parolanız

Erişim denetleyicisinin web arayüzündekiyle aynı oturum açma bilgilerini kullanın.


## 4. Adım: Bağlantıyı test edin

Yapılandırmanızı kaydedin ve bir kapıyı veya geçidi açmayı deneyin.

Hiçbir şey olmazsa şunları kontrol edin:

- Cihazınız erişim denetleyicisiyle aynı ağda mı
- IP adresi doğru mu
- Erişim denetleyicisi açık ve erişilebilir mi


## 5. Adım: IP adresini sabit tutun

Daha sonra sorun yaşamamak için denetleyici her zaman aynı IP adresini kullanmalıdır.

Bu şu şekilde yapılabilir:

- Denetleyicide statik IP ayarlayarak
- Yönlendiricide DHCP rezervasyonu oluşturarak


## Demo modu

GateTap ayrıca bir demo modu içerir. Uygulamanın içinden yerel bir demo web sunucusu başlatabilir ve ardından bunu normal bir denetleyici gibi ekleyebilirsiniz.

Bu, şu anda fiziksel bir erişim denetleyicisine erişiminiz olmasa bile GateTap’in doğru çalıştığını doğrulamak için bilinen çalışan bir test yolu sağlar.


## Güvenlik

Verileriniz cihazınızda kalır.

GateTap'i isteğe bağlı olarak uygulama ayarlarında Face ID veya Touch ID kullanarak koruyabilirsiniz.


