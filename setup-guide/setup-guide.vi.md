<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: vi
-->

# Hướng dẫn thiết lập

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | 🌐 vi | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

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


