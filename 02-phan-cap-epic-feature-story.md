# Phân cấp thẻ đặt xe ghép

| Thẻ | Cấp đúng | Vy ghi | Căn cứ |
|---|---|---|---|
| K1 | Epic | Sai | Mục tiêu lớn 60–120 SP, kéo dài nhiều Sprint và khó ước lượng chính xác. |
| K2 | Feature | Đúng | Chức năng cụ thể, ước lượng thô và cần 2–3 Sprint. |
| K3 | Feature | Sai | Gồm nhiều chức năng chia và hoàn tiền, kéo dài khoảng hai Sprint. |
| K4 | User Story | Đúng | Có ba vế theo góc nhìn khách, 3 SP và làm trong vài ngày. |
| K5 | Công việc kỹ thuật | Sai | Tạo bảng dữ liệu là cách triển khai nội bộ, không phải nhu cầu người dùng. |
| K6 | User Story | Sai | Có ba vế, 3 SP và hoàn thành trong vài ngày. |

## Cây phân rã

- K1 Epic: Đặt xe ghép
  - K2 Feature: Ghép khách cùng tuyến
    - K4 Story: Xem số chỗ trống.
    - K5 Story viết lại: Là khách đi ghép, tôi muốn xem danh sách khách trong chuyến của mình để biết những người sẽ đi cùng.
    - Công việc kỹ thuật hỗ trợ K5: tạo bảng dữ liệu lưu danh sách khách.
  - K3 Feature: Chia tiền cho các khách đi ghép
    - K6 Story: Xem số tiền phải trả trước khi xác nhận ghép.

K1 không đúng khi nằm trong Sprint Backlog vì là Epic quá lớn. Chuyển K1 về Product Backlog, gắn nhãn tím và chỉ đưa các User Story đã đủ nhỏ vào Sprint Backlog.
