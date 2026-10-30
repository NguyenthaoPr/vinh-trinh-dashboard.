# Giám sát hồ Vĩnh Trinh – THỦY LỢI AI

Ứng dụng HTML tĩnh, sẵn sàng triển khai lên Vercel.

## Triển khai nhanh
1. Giải nén thư mục này.
2. Tạo repository GitHub mới, ví dụ `vinh-trinh-dashboard`.
3. Đưa `index.html`, `vercel.json`, `README.md` lên thư mục gốc repository.
4. Vào Vercel → Add New → Project → Import Git Repository.
5. Chọn repository vừa tạo.
6. Framework Preset: Other; Build Command và Output Directory để trống/mặc định; Deploy.

## Dữ liệu
- Đọc mẫu từ Excel đã cung cấp (được nhúng trong ứng dụng).
- Có nút thử đồng bộ Google Sheets qua GViz; bảng tính cần cho phép truy cập bằng liên kết ở chế độ Người xem.
- Chỉ sử dụng cột A (Thời gian) và G (Mực nước thực tế).
- Bảng Z–F–V từ ảnh Bảng 4.7, cao trình +10 đến +34 m.

## Lưu ý vận hành
Đây là phiên bản mô phỏng/giám sát ban đầu. Cần kiểm chứng mốc cao độ cảm biến, toàn bộ bảng Z–F–V gốc và kết nối Google Sheets trực tuyến trước khi dùng làm căn cứ điều hành hồ.
