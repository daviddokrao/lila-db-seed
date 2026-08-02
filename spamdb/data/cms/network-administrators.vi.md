# Mạng của bạn đang chặn tài nguyên của HungKings

Nếu bạn đang đọc dòng này, nghĩa là trang đã tải được nhưng các tệp làm nó hoạt
động — kiểu dáng, mã lệnh, hình quân cờ — thì không. Trang sẽ trông vỡ và bàn cờ
không phản hồi.

Chuyện này gần như không bao giờ do lỗi bên chúng tôi. Có thứ gì đó nằm giữa bạn
và chúng tôi đang chặn một phần kết nối.

## Thử những cách này trước

**Tắt các tiện ích mở rộng.** Trình chặn quảng cáo và tiện ích bảo mật đôi khi
chặn tên miền tài nguyên theo mẫu chứ không theo tên cụ thể. Hãy mở trang trong
cửa sổ ẩn danh với tiện ích đã tắt và xem nó chạy thế nào.

**Thử một mạng khác.** Nếu nó chạy trên mạng di động mà không chạy trên mạng nhà
hay mạng công ty, thì chỗ chặn nằm ở mạng đó.

**Kiểm tra VPN hoặc bộ lọc DNS** bạn đang dùng. Bộ lọc gia đình và các trình chặn
kiểu pi-hole là nguyên nhân thường gặp.

## Nếu bạn là người quản trị mạng

Trang tải giao diện từ chính máy chủ mà bạn vốn đã cho qua, nhưng còn cần các kết
nối tài nguyên và websocket. Xin hãy cho phép:

- **Chính máy chủ của trang**, qua HTTPS
- **Kết nối WebSocket** tới cùng máy chủ đó. Chặn tiêu đề `Upgrade` là nguyên
  nhân phổ biến nhất khiến bàn cờ hiện ra nhưng không bao giờ đi được nước nào
- Trang này chỉ có cờ. Không có video, không quảng cáo, không có thành phần theo
  dõi của bên thứ ba nào để phải lọc

Nếu bạn chặn vì lý do đây là trò chơi, thì chặn websocket thay vì chặn cả tên
miền sẽ để lại cho người dùng một trang trông vẫn bình thường mà hỏng âm thầm —
và việc đó sinh ra yêu cầu hỗ trợ cho chính bạn. Hãy chặn thẳng máy chủ.

## Vẫn hỏng

Hãy báo cho chúng tôi qua [trang liên hệ](/contact), nói rõ bạn đang dùng mạng
nào và bảng điều khiển trình duyệt báo gì. Một tài nguyên bị chặn hầu như luôn
để lại ở đó một dòng lỗi nêu đích danh thứ đã bị từ chối.
