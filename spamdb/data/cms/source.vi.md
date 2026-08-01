# Mã nguồn

HungKings là phần mềm tự do, phát hành theo giấy phép
[GNU Affero General Public License v3](https://www.gnu.org/licenses/agpl-3.0.html).

Giấy phép này có một điều kiện mà phần lớn giấy phép khác không có: vì chúng tôi
chạy mã nguồn dưới dạng dịch vụ mạng, chúng tôi buộc phải cung cấp cho bạn mã
nguồn của đúng phiên bản đang chạy, kể cả phần chúng tôi tự sửa. Nó đây.

## Các kho mã của chúng tôi

| Kho mã | Là gì |
| --- | --- |
| [daviddokrao/lila](https://github.com/daviddokrao/lila) | Máy chủ và giao diện web |
| [daviddokrao/lila-ws](https://github.com/daviddokrao/lila-ws) | Máy chủ websocket cho phần chơi trực tiếp |
| [daviddokrao/lila-fishnet](https://github.com/daviddokrao/lila-fishnet) | Chia việc phân tích cho các máy tính cờ |
| [daviddokrao/lila-db-seed](https://github.com/daviddokrao/lila-db-seed) | Dữ liệu mẫu để dựng cơ sở dữ liệu ban đầu |
| [daviddokrao/lila-docker](https://github.com/daviddokrao/lila-docker) | Cách toàn bộ hệ thống được dựng và triển khai |

Mỗi kho đều là một bản fork, và đều giữ một remote tên `upstream` trỏ về
[lichess-org](https://github.com/lichess-org). Nhờ vậy bạn thấy được chính xác
chỗ nào chúng tôi sửa và chỗ nào chỉ là thừa hưởng — `git diff upstream/master`
là câu trả lời trung thực cho câu hỏi "HungKings thật ra đã làm gì?".

## Ghi công

Phần lớn áp đảo mã nguồn này do cộng đồng Lichess viết, không phải chúng tôi.
Chúng tôi cũng gửi ngược một số bản sửa lên upstream khi chúng đủ tổng quát để
có ích cho mọi người.

Máy tính cờ dùng cho phân tích và cho phần chơi với máy là
[Stockfish](https://stockfishchess.org/), cũng là phần mềm tự do.

## Báo lỗi

Mở một issue ở [kho mã chính](https://github.com/daviddokrao/lila/issues), hoặc
xem trang [liên hệ](/contact).
