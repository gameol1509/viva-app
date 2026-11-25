# VIVA Smart – App quản lý công việc & báo cáo

Bản **demo web** (dùng trên máy tính) theo tài liệu *Đề xuất App Quản lý Công việc VIVA* (24/11/2026).
Dữ liệu giả, chưa có đăng nhập/database. Mục đích: trình Giám đốc duyệt trước khi làm bản thật.

**Cách xem:** tải file `index.html` về rồi mở bằng trình duyệt (Chrome, Edge…).

## Có gì trong demo
- **Tổng quan (dashboard):** doanh số ngày/tuần/tháng so kỳ trước; việc đang làm/tồn/quá hạn theo phòng; tỉ lệ nộp báo cáo đúng hạn; thu chi, công nợ; khiếu nại chưa xử lý.
- **Công việc:** giao việc (tiêu đề, người nhận, hạn, ưu tiên, khách hàng); 5 trạng thái; cập nhật tiến độ kèm file; nhắc hạn; lọc theo phòng, người, trạng thái, khách; xuất Excel.
- **Báo cáo:** nộp báo cáo cuối ngày (chọn việc đã xong, việc tồn + lý do, kế hoạch mai, đính kèm, chỉ số theo phòng, hạn 18h); trưởng phòng/Giám đốc duyệt hoặc trả lại kèm ghi chú; thấy ai chưa nộp, nộp trễ; tổng hợp tuần/tháng; xuất Excel.
- **Khách hàng:** hồ sơ, nguồn khách, lịch sử mua/lắp đặt/bảo hành, nhắc hết hạn bảo hành, lịch chăm sóc, khiếu nại, công việc liên quan.
- **Phân quyền:** đổi “Xem với vai trò” ở góc trên (Giám đốc, trưởng phòng, nhân viên, kế toán) để thấy mỗi người xem/làm được gì, theo Mục 7 của đề xuất.

Bản điện thoại sẽ làm sau. Công nghệ dự kiến cho bản thật: Supabase + Cloudflare Pages.
