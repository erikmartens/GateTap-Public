<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: vi
-->

# Hướng dẫn thiết lập

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | 🇻🇳 Tiếng Việt | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Kết nối GateTap với bộ điều khiển truy cập của bạn

## Trước khi bạn bắt đầu

Hãy đảm bảo thiết bị của bạn được kết nối với cùng mạng cục bộ như bộ điều khiển truy cập. Ví dụ, hãy chắc chắn iPhone đang dùng Wi-Fi tại nhà chứ không phải kết nối dữ liệu di động.

GateTap hoạt động hoàn toàn trong mạng cục bộ của bạn và cần:

- Địa chỉ IP của bộ điều khiển
- Tên người dùng và mật khẩu


## Bước 1: Tìm địa chỉ IP của bộ điều khiển truy cập

Để kết nối GateTap, bạn cần địa chỉ IP của bộ điều khiển và thông tin đăng nhập - xem Bước 2.

Chọn một trong các tùy chọn sau:


## Tùy chọn A: Hỏi người lắp đặt của bạn (được khuyến nghị)

Nếu hệ thống của bạn do thợ điện hoặc kỹ thuật viên lắp đặt, có thể họ đã cấu hình mọi thứ.

Trong nhiều trường hợp:

- Bộ điều khiển dùng địa chỉ IP cố định
- Hoặc bộ định tuyến gán cùng một IP thông qua đặt trước DHCP

Hãy hỏi họ địa chỉ IP và thông tin đăng nhập. Đây thường là cách dễ nhất và nhanh nhất.


## Tùy chọn B: Kiểm tra bộ định tuyến của bạn

Mở trang cấu hình của bộ định tuyến và tìm các thiết bị đang kết nối.

Để truy cập bộ định tuyến, bạn thường cần địa chỉ cục bộ của nó, ví dụ `192.168.1.1` hoặc tên như `fritz.box`, cùng thông tin đăng nhập của bộ định tuyến.

Mục này có thể được gọi là:

- Mạng
- Thiết bị đã kết nối
- LAN
- Máy khách DHCP

Hãy tìm:

- Thiết bị có dây không xác định
- Mục có thể là bộ điều khiển của bạn

Địa chỉ IP thường có dạng:
`192.168.x.x` hoặc `10.0.x.x`

![Ví dụ thiết bị đã kết nối trong bộ định tuyến](../assets/setup-guide/vi/img_01_en_US.png)


## Tùy chọn C: Quét mạng của bạn

Sử dụng ứng dụng quét mạng trên thiết bị của bạn.

Quét mạng và thử mở các địa chỉ IP tìm thấy trong Safari, ví dụ:

`http://192.168.1.50`

Nếu trang đăng nhập của bộ điều khiển truy cập xuất hiện, bạn đã tìm đúng địa chỉ.

![Ví dụ ứng dụng quét mạng](../assets/setup-guide/vi/img_02_en_US.png)


## Bước 2: Tìm thông tin đăng nhập của bộ điều khiển truy cập

Một số bộ điều khiển vẫn dùng thông tin đăng nhập mặc định. Ví dụ phổ biến là tên người dùng `abc` với mật khẩu `654321`.

Các tên người dùng mặc định thường gặp khác là `user`, `admin` hoặc `123`. Bạn có thể thử chúng với các mật khẩu phổ biến như `1234`, `user` hoặc `password`, hoặc một biến thể của chúng.

Nếu hệ thống của bạn được lắp đặt chuyên nghiệp, hãy hỏi người lắp đặt xem thông tin mặc định đã được thay đổi chưa.


## Bước 3: Thêm bộ điều khiển truy cập trong GateTap

Mở GateTap và nhập:

- Địa chỉ IP
- Tên người dùng của bạn
- Mật khẩu của bạn

Sử dụng cùng thông tin đăng nhập như giao diện web của bộ điều khiển truy cập.


## Bước 4: Kiểm tra kết nối

Lưu cấu hình và thử mở cửa hoặc cổng.

Nếu không có gì xảy ra, hãy kiểm tra:

- Thiết bị của bạn ở cùng mạng với bộ điều khiển truy cập
- Địa chỉ IP chính xác
- Bộ điều khiển truy cập có nguồn điện và có thể truy cập được


## Bước 5: Giữ địa chỉ IP ổn định

Để tránh sự cố về sau, bộ điều khiển nên luôn dùng cùng một địa chỉ IP.

Có thể thực hiện bằng cách:

- Đặt IP tĩnh trên bộ điều khiển
- Tạo đặt trước DHCP trong bộ định tuyến


## Chế độ demo

GateTap cũng có chế độ demo. Bạn có thể khởi động một máy chủ web demo cục bộ từ trong ứng dụng rồi thêm nó như một bộ điều khiển thông thường.

Điều này cung cấp một đường kiểm thử đã biết là hoạt động để xác minh rằng chính GateTap đang hoạt động đúng, ngay cả khi hiện bạn không có quyền truy cập vào bộ điều khiển truy cập vật lý.


## Bảo mật

Dữ liệu của bạn vẫn còn trên thiết bị của bạn.

Bạn có thể tùy chọn bảo vệ GateTap bằng Face ID hoặc Touch ID trong cài đặt ứng dụng.


