# Đua Thuyền Tri Thức

Game trắc nghiệm đua thuyền 4 đội, thiết kế responsive cho điện thoại, máy tính bảng và máy tính.

## Chạy thử
Mở `index.html` bằng trình duyệt hoặc bật GitHub Pages cho repository.

## Cấu hình giáo viên
- Mở **Giáo viên** để đổi tên đội, màu thuyền, âm thanh và câu hỏi.
- Có thể tải ảnh nền gốc lên tại mục Ảnh nền. Ảnh được lưu trong bộ nhớ trình duyệt của thiết bị đang cấu hình.
- Excel: dòng đầu là tiêu đề; cột A câu hỏi, B–E đáp án A–D, F đáp án đúng (A/B/C/D hoặc 1/2/3/4), G giải thích (không bắt buộc).
- Nhấn **Lưu & Xác nhận**, sau đó mới nhấn **Bắt đầu cuộc đua**.
- Mỗi lượt có 15 giây. Đúng +100 điểm và chuyển lượt sang đội tiếp theo; sai/hết giờ không cộng điểm và đội đó được trả lời câu kế tiếp.
- Mỗi đội cần đạt 5 câu đúng để hoàn thành; game cũng kết thúc sau 20 lượt trả lời.

## Lưu ý quan trọng về đồng bộ nhiều thiết bị
Phiên bản hiện tại lưu cấu hình và điểm bằng localStorage trên trình duyệt đang mở. Vì vậy dữ liệu được giữ lại trên cùng thiết bị/trình duyệt, nhưng **chưa đồng bộ trực tiếp giữa nhiều điện thoại/máy tính** và chưa có danh sách học sinh tham gia theo thời gian thực. Để triển khai lớp học nhiều thiết bị, cần kết nối một dịch vụ backend realtime (ví dụ Firebase hoặc Supabase) và cấu hình quyền truy cập an toàn.

## Ảnh nền
Tải ảnh đua thuyền vào mục Giáo viên > Ảnh nền trên thiết bị trình chiếu. Để ảnh có sẵn cho tất cả người dùng, đặt ảnh trong thư mục `dua-thuyen-tri-thuc/assets/` với tên `dua-thuyen.jpg`.
