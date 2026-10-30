# Giám sát hồ Vĩnh Trinh – V1.4 bản đồ tích hợp

- Dashboard đọc dữ liệu Google Sheets, chỉ cột A và G.
- Tự thử đồng bộ khi mở trang và mỗi 5 phút.
- Bản đồ Leaflet tích hợp ngay trong Dashboard.
- Nền vệ tinh Esri World Imagery.
- Có nút bật/tắt Satellite, GIS, Sensor.
- Có thể nạp lớp GeoJSON từ file trên máy.
- Chưa gắn tọa độ cảm biến thực và chưa nạp GIS Master/KMZ gốc; không dùng điểm tham chiếu gần đúng làm vị trí công trình chính xác.

## Deploy
Thay `index.html` và `vercel.json` trong repository GitHub hiện tại bằng hai file cùng tên ở đây, commit, Vercel tự triển khai.


V1.4: Nâng cấp đường biểu đồ bằng nội suy Catmull–Rom/Bezier, đường cong đi qua các điểm đo; tăng độ phân giải canvas theo màn hình Retina. Chỉ làm mượt phần hiển thị, không làm thay đổi dữ liệu gốc.
