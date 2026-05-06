<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: vi
-->

# Hướng dẫn thiết lập

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | 🇻🇳 Tiếng Việt | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Kết nối GateTap với bộ điều khiển truy cập của bạn

## Trước khi bạn bắt đầu

Đảm bảo iPhone của bạn được kết nối với cùng mạng cục bộ với bộ điều khiển truy cập của bạn.

GateTap hoạt động hoàn toàn trong mạng cục bộ và nhu cầu của bạn:
• Địa chỉ IP của bộ điều khiển
• Tên người dùng và mật khẩu


## Bước 1: Tìm địa chỉ và thông tin xác thực của bộ điều khiển

Để kết nối GateTap, bạn cần có địa chỉ IP của bộ điều khiển và thông tin đăng nhập.

Chọn một trong các tùy chọn sau:


## Tùy chọn A: Hỏi trình cài đặt của bạn (được khuyến nghị)

Nếu hệ thống của bạn được lắp đặt bởi thợ điện hoặc kỹ thuật viên, họ có thể đã cấu hình mọi thứ.

Trong nhiều trường hợp:
• Bộ điều khiển sử dụng địa chỉ IP cố định
• Hoặc bộ định tuyến gán cùng một IP thông qua việc đặt trước

Hỏi họ địa chỉ IP và chi tiết đăng nhập. Đây thường là cách dễ nhất và nhanh nhất.


## Tùy chọn B: Kiểm tra bộ định tuyến của bạn

Mở trang cấu hình bộ định tuyến của bạn và tìm các thiết bị được kết nối.

Để truy cập bộ định tuyến của mình, bạn thường cần địa chỉ cục bộ của nó (ví dụ: `192.168.1.1` hoặc tên như `fritz.box`) và thông tin đăng nhập của bộ định tuyến.

Phần này có thể được gọi là:
• Thiết bị được kết nối
• Mạng LAN
• Máy khách DHCP

Hãy tìm:
• Thiết bị có dây không xác định
• Các mục có thể đại diện cho bộ điều khiển của bạn

Địa chỉ IP thường sẽ có dạng:
`192.168.x.x` hoặc `10.0.x.x`

![Ví dụ về thiết bị được kết nối với bộ định tuyến](../assets/setup-guide/vi/img_01.png)


## Tùy chọn C: Quét mạng của bạn

Sử dụng ứng dụng quét mạng trên iPhone hoặc máy tính của bạn.

Quét mạng của bạn và thử mở các địa chỉ IP được phát hiện trong Safari, ví dụ:

`http://192.168.1.50`

Nếu trang đăng nhập của bộ điều khiển xuất hiện thì bạn đã tìm đúng địa chỉ.

![Ví dụ về trình quét mạng](../assets/setup-guide/vi/img_02.png)


## Bước 2: Thêm bộ điều khiển vào GateTap

Mở GateTap và nhập:
• Địa chỉ IP
• Tên người dùng của bạn
• Mật khẩu của bạn

Sử dụng thông tin xác thực tương tự như đối với giao diện web của bộ điều khiển.


## Bước 3: Kiểm tra kết nối

Lưu cấu hình của bạn và thử mở một cánh cửa hoặc cổng.

Nếu không có gì xảy ra, hãy kiểm tra:
• iPhone của bạn nằm trên cùng một mạng
• Địa chỉ IP đúng
• Bộ điều khiển được cấp nguồn và có thể truy cập được


## Bước 4: Giữ địa chỉ IP ổn định

Để tránh các sự cố sau này, bộ điều khiển phải luôn sử dụng cùng một địa chỉ IP.

Điều này có thể được thực hiện bằng cách:
• Đặt IP tĩnh trên bộ điều khiển
• Tạo đặt chỗ DHCP trong bộ định tuyến của bạn


## Bảo mật

Dữ liệu của bạn vẫn còn trên thiết bị của bạn.

Bạn có thể tùy chọn bảo vệ GateTap bằng Face ID hoặc Touch ID trong cài đặt ứng dụng.


