# Hệ thống hệ số

## Glicko-2

HungKings tính hệ số riêng cho từng thể loại thời gian và từng biến thể, dùng
**Glicko-2** — hệ thống do Mark Glickman thiết kế để kế tục Elo.

Glicko-2 theo dõi hai con số về bạn chứ không phải một:

- **hệ số** — ước lượng sức cờ của bạn
- **độ lệch hệ số (RD)** — mức độ chưa chắc chắn của ước lượng đó

Tài khoản mới bắt đầu quanh 1500 với độ lệch rất cao, vì hệ thống chưa biết gì về
bạn. Mỗi ván lại thu hẹp nó. Đó là lý do vài kết quả đầu tiên làm hệ số nhảy rất
mạnh, còn ván thứ một trăm gần như không xê dịch.

## Hệ số tạm

Khi độ lệch còn cao, hệ số của bạn hiện kèm dấu **?**. Nó có nghĩa "con số này
mới là phỏng đoán". Hệ số tạm không lên bảng xếp hạng, và thắng một người đang ở
hệ số tạm làm hệ số của bạn thay đổi ít hơn thắng một người đã ổn định.

Chơi khoảng mười ván ở một thể loại thời gian là nó ổn định.

## Vì sao hệ số trôi xuống khi bạn nghỉ chơi

Độ lệch lớn dần trở lại theo thời gian. Sau một quãng nghỉ dài, hệ thống bớt chắc
chắn về bạn, nên các kết quả kế tiếp có trọng số cao hơn theo cả hai chiều. Bản
thân con số hệ số không bị trừ vì không hoạt động.

## Vì sao nó khác hệ số của bạn ở nơi khác

Hệ số chỉ có ý nghĩa bên trong một nhóm người chơi. Hệ số FIDE đo bạn so với
những người thi đấu trực tiếp ở thể thức dài; hệ số cờ chớp ở đây đo bạn so với
những ai chơi cờ chớp ở đây, trong ba phút, không trọng tài. Không có tỉ giá quy
đổi, và việc một con số cao hơn ở trang này so với trang kia không nói lên điều
gì về cả hai.

Ngay trong cùng trang này, cờ siêu chớp, cờ chớp, cờ nhanh, cờ tiêu chuẩn và từng
biến thể đều là các nhóm riêng. Chúng vốn không nhằm khớp nhau.

## Điều gì làm hệ số thay đổi

Chỉ các ván có tính hệ số. Ván thường, câu đố và ván với máy không bao giờ ảnh
hưởng. Thắng người cao hơn nhiều thì được nhiều; thắng người thấp hơn nhiều thì
gần như không được gì, mà thua họ thì mất nhiều. Sự bất đối xứng đó là hệ thống
đang làm đúng việc, không phải hệ thống đang phạt bạn.
