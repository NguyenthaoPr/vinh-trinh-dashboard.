# Giám sát hồ Vĩnh Trinh – THỦY LỢI AI

Ứng dụng HTML tĩnh, triển khai trực tiếp trên Vercel.

## Triển khai GitHub → Vercel
1. Tạo repository GitHub mới, ví dụ `vinh-trinh-dashboard`.
2. Tải `index.html`, `vercel.json`, `README.md` lên thư mục gốc repository.
3. Vào Vercel → Add New → Project → Import Git Repository.
4. Chọn repository; Framework Preset chọn `Other`; không cần Build Command; Deploy.

## Dữ liệu Google Sheets
- Spreadsheet ID: `1wSqXIT819YCZQEkb3CXxCaBhJU-rVs0d_W6tsulrPfk`
- GID: `0` (tab DuLieu)
- Ứng dụng chỉ đọc cột A (Thời gian) và cột G (Mực nước thực tế).
- Tự thử đồng bộ khi mở trang và lặp lại mỗi 5 phút; có nút đồng bộ thủ công.
- Google Sheets cần chia sẻ `Bất kỳ ai có đường liên kết` với quyền `Người xem`.
- Trình duyệt truy cập Google GViz trực tiếp; nếu bị chặn bởi chính sách CORS/quyền chia sẻ, trạng thái sẽ báo lỗi và vẫn giữ dữ liệu mẫu để xem giao diện.

## Tính toán
- Bảng Z–F–V hiện nhập theo ảnh Bảng 4.7, cao trình +10 đến +34 m.
- Dung tích được nội suy tuyến tính giữa hai cao trình liền kề.

## Lưu ý
Đây là công cụ giám sát/mô phỏng ban đầu. Cần đối chiếu toàn bộ bảng Z–F–V gốc, mốc cao độ cảm biến và kết quả đồng bộ thực tế trước khi dùng làm căn cứ điều hành hồ.
