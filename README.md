# lbp-modem

## Đăng ký mạng ở Việt nam, qua các bước:

1. Tìm nhà cung cấp

Bạn có thể lên mạng tìm kiếm thông tin nhà cung cấp gói cước Internet cho khu vực của bạn, sau khi gọi điện tư vấn Nhà cung cấp sẽ cử người xuống nhà bạn để lắp đặt thiết bị.

Mình đã từng sử dụng:
- Viettel
- FPT
- VNPT

2. Nhân viên hỗ trợ

Nhà cung cấp cử nhân viên tới hỗ trợ để lắp đặt mạng cho nhà của bạn. Ban đầu, họ sẽ kiểm tra khu vực xung quanh bạn có sẵn hạ tầng của NCC đó chưa? Nếu có thì quá dễ, họ chỉ cần kéo dây từ trụ hạ tầng đó và nối vào nhà bạn (bạn dễ thấy trong 1 xóm thường xài chung 1 nhà cung cấp là vậy đó).

Các bước
- Kéo dây, kéo cáp
- Lắp đặt thiết bị: modem
- Cài đặt, cấu hình.

3. Kiểm tra thông tin

Sau khi cấu hình xong thiết bị, nhân viên hỗ trợ sẽ giúp bạn kiểm tra đường truyền và chất lượng Internet.

DONE.

## Tự cài đặt, cấu hình modem

Bạn có thể tự cấu hình, cài đặt modem trong nhà của bạn. Tuy nhiên, bạn chỉ kiểm soát được 5/10 phần còn 5 phần còn lại phụ thuộc vào nhà cung cấp.

> Với VNPT ngoài quê, họ kiểm soát 100%.

1. Vào Gateway của Router

Thông thường, bạn sẽ thấy các địa chỉ IP như 192.168.0.1 , 192.168.1.1

2. Reboot modem

Chọn button Reboot.

3. Reset modem

Chọn Restore default / Reset.

## Dịch vụ Dynamic DNS

Bạn có một máy tính có kết nối mạng. Bạn muốn truy cập vào địa chỉ IP của nhà bạn.

> Như bạn đã biết, có 2 loại IP là IP tĩnh và IP động. IP tĩnh là gán cứng khi nhà cung cấp bán cho bạn. IP động là IP mà nhà cung cấp sẽ thay đổi thường xuyên. Thông thường, NCC sẽ cấp cho bạn là IP public là IP động.

Vì nó là IP động nên nó không ở yên 1 chỗ, vậy nên làm sao để IP khi thay đổi thì bạn sẽ nhận biết chúng. Có rất nhiều cách và Dyn DNS ra đời để làm điều đó.

> DNS là đổi từ IP thành một tên miền dễ nhớ. Dyn DNS là một dịch vụ tự động cập nhật IP khi nó thay đổi và gán cứng cho 1 tên miền. Cool!