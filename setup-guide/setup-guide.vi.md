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

## Bộ điều khiển truy cập là gì?

Bộ điều khiển truy cập là thiết bị quản lý việc mở cửa, cổng, gara hoặc rào chắn — ví dụ như kích hoạt chuông mở cửa hoặc động cơ cổng.
Thiết bị này thường nhận tín hiệu mở từ:

- hệ thống liên lạc nội bộ
- bàn phím
- chìa khóa điện tử hoặc thẻ truy cập

Nhiều hệ thống kiểm soát truy cập hiện đại được kết nối với mạng nội bộ và có thể vận hành qua giao diện web trong trình duyệt. GateTap kết nối trực tiếp với hệ thống đó để bạn có thể điều khiển thuận tiện từ thiết bị của mình.


## Trước khi bạn bắt đầu

Hãy đảm bảo thiết bị của bạn được kết nối với cùng mạng nội bộ với bộ điều khiển truy cập. Ví dụ, hãy chắc chắn rằng iPhone đang kết nối Wi‑Fi ở nhà và không dùng dữ liệu di động.

GateTap hoạt động hoàn toàn trong mạng nội bộ của bạn và cần:

- Địa chỉ IP của bộ điều khiển
- Tên người dùng và mật khẩu


## Bước 1: Tìm địa chỉ IP của bộ điều khiển truy cập

Để kết nối GateTap, bạn cần địa chỉ IP của bộ điều khiển và thông tin đăng nhập — xem Bước 2.

Chọn một trong các tùy chọn sau:


## Tùy chọn A: Hỏi người lắp đặt của bạn (được khuyến nghị)

Nếu hệ thống của bạn do thợ điện hoặc kỹ thuật viên lắp đặt, có khả năng họ đã cấu hình mọi thứ.

Trong nhiều trường hợp:

- Bộ điều khiển sử dụng địa chỉ IP cố định
- Hoặc bộ định tuyến cấp cùng một IP thông qua đặt trước DHCP

Hãy hỏi họ địa chỉ IP và thông tin đăng nhập. Đây thường là cách dễ nhất và nhanh nhất.


## Tùy chọn B: Kiểm tra bộ định tuyến của bạn

Để truy cập bộ định tuyến, bạn thường cần địa chỉ cục bộ của nó, ví dụ `192.168.1.1` hoặc tên như `fritz.box`, cùng với thông tin đăng nhập của bộ định tuyến.

Mở trang cấu hình của bộ định tuyến và tìm các thiết bị đã kết nối.

Mục này có thể được gọi là:

- Mạng
- Thiết bị đã kết nối
- LAN
- Máy khách DHCP

Hãy tìm:

- Thiết bị có dây không xác định
- Các mục có thể là bộ điều khiển của bạn

Địa chỉ IP thường trông như:
`192.168.x.x` hoặc `10.0.x.x`

![Ví dụ thiết bị đã kết nối trong bộ định tuyến](../assets/setup-guide/vi/img_01_en_US.png)


## Tùy chọn C: Quét mạng của bạn

Dùng ứng dụng quét mạng trên thiết bị của bạn.

Quét mạng và tìm:

- Thiết bị có dây không xác định
- Các mục có thể là bộ điều khiển của bạn

Địa chỉ IP thường trông như:
`192.168.x.x` hoặc `10.0.x.x`


## Kiểm tra địa chỉ IP

Thử mở địa chỉ IP tìm được trong Safari, ví dụ:

`http://192.168.1.50`

Nếu trang đăng nhập của bộ điều khiển truy cập xuất hiện, bạn đã tìm đúng địa chỉ.


## Bước 2: Tìm thông tin đăng nhập của bộ điều khiển truy cập

Một số bộ điều khiển truy cập vẫn dùng thông tin đăng nhập mặc định. Ví dụ phổ biến là tên người dùng `abc` với mật khẩu `654321`.

Các tên người dùng mặc định phổ biến khác gồm `user`, `admin` hoặc `123`. Bạn có thể thử chúng với các mật khẩu thường gặp như `1234`, `user` hoặc `password`, hoặc một biến thể tương tự.

Nếu hệ thống được lắp đặt chuyên nghiệp, hãy hỏi người lắp đặt xem thông tin đăng nhập mặc định đã được thay đổi chưa.


## Bước 3: Thêm bộ điều khiển truy cập trong GateTap

Mở GateTap. Nếu trang thêm bộ điều khiển không tự động xuất hiện, hãy chuyển sang tab "Controller" và chạm vào nút "+" trên thanh điều hướng ở góc trên bên phải.

Trên trang xuất hiện, nhập:

- Địa chỉ IP
- Tên người dùng
- Mật khẩu

Dùng cùng thông tin đăng nhập như giao diện web của bộ điều khiển truy cập.


## Bước 4: Kiểm tra kết nối

Lưu cấu hình. Ứng dụng sẽ tự động thử kết nối.

Nếu không thể thiết lập kết nối, hãy kiểm tra:

- Thiết bị của bạn đang ở cùng mạng với bộ điều khiển truy cập
- Địa chỉ IP chính xác
- Bộ điều khiển truy cập có nguồn điện và có thể truy cập được


## Bước 5: Giữ địa chỉ IP ổn định

Để tránh sự cố sau này, bộ điều khiển nên luôn dùng cùng một địa chỉ IP.

Có thể thực hiện bằng cách:

- Đặt IP tĩnh trên bộ điều khiển
- Tạo đặt trước DHCP trong bộ định tuyến


## Chế độ demo

GateTap cũng có chế độ demo. Bạn có thể khởi động một bộ điều khiển truy cập ảo ngay trong ứng dụng, cung cấp giao diện quản trị giống như một hệ thống kiểm soát truy cập thật. Sau đó, bạn có thể thêm nó như một bộ điều khiển bình thường bằng địa chỉ IP và thông tin đăng nhập được hiển thị.

Điều này mang lại một lộ trình thử nghiệm đã biết là hoạt động để khám phá các tính năng của GateTap, ngay cả khi hiện tại bạn chưa có bộ điều khiển truy cập vật lý.


## Bảo mật

Dữ liệu của bạn vẫn còn trên thiết bị của bạn.

Bạn có thể tùy chọn bảo vệ GateTap bằng Face ID hoặc Touch ID trong cài đặt ứng dụng.


