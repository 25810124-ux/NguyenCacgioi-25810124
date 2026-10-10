# BẢN ĐẶC TẢ WEBSITE: GREENLIFE

## 1. Tên website và mục đích
- **Tên:** GreenLife – Cửa hàng cây xanh.
- **Mục đích:** Giới thiệu và trưng bày các loại cây cảnh trong nhà, cây để bàn, chậu cây và phụ kiện chăm sóc cây; giúp người xem tìm hiểu sản phẩm và thông tin cửa hàng.
- **Phạm vi phiên bản:** Website tĩnh phục vụ bài thực hành. Chưa có giỏ hàng, thanh toán, đăng nhập hay cơ sở dữ liệu.

## 2. Đối tượng người dùng
- Học sinh, sinh viên, nhân viên văn phòng và người yêu cây.
- Người muốn tìm cây trang trí bàn học, bàn làm việc hoặc góc sinh hoạt.
- Người truy cập bằng máy tính hoặc điện thoại, cần nội dung dễ đọc và điều hướng đơn giản.

## 3. Danh sách trang

| Trang | Tên file | Nội dung chính |
|---|---|---|
| Trang chủ | `index.html` | Giới thiệu thương hiệu, thông điệp sống xanh, 4 sản phẩm nổi bật, lợi ích khi chọn GreenLife và thông tin liên hệ. |
| Sản phẩm | `san-pham.html` | Danh sách 8 sản phẩm minh họa, mô tả ngắn, giá tham khảo và liên kết quay lại trang chủ. |

Tổng số trang: **2**, không vượt quá giới hạn tối đa 4 trang của bài thực hành.

## 4. Bố cục chung
- **Đầu trang (header):** Logo chữ GreenLife bên trái; menu Trang chủ, Sản phẩm và Liên hệ bên phải.
- **Khối giới thiệu (hero):** Tiêu đề, đoạn mô tả ngắn, nút xem sản phẩm và ảnh minh họa.
- **Khu sản phẩm:** Các thẻ sản phẩm có ảnh, tên, mô tả ngắn và giá tham khảo.
- **Khối thông điệp:** Nhấn mạnh việc đưa thiên nhiên vào không gian sống.
- **Chân trang (footer):** Tên cửa hàng, thông tin liên hệ minh họa và điều hướng.
- Hai trang sử dụng chung một file CSS là `public/css/style.css`.

## 5. Phong cách
- **Màu chủ đạo:** Xanh lá đậm `#2e7d32`.
- **Màu phụ:** Xanh lá nhạt `#e8f5e9`, kem `#f7f5ed`, chữ xanh đen `#203127`.
- **Phông chữ:** Arial, sans-serif; dễ đọc trên màn hình.
- **Phong cách:** Tươi mát, tối giản, nhiều khoảng trắng, thẻ sản phẩm bo góc và bóng đổ nhẹ.
- Ảnh hiện là ảnh minh họa từ `https://placehold.co/400x300?text=...`.

## 6. Yêu cầu hiển thị trên điện thoại
- Có thẻ meta viewport để trình duyệt điều chỉnh theo chiều rộng thiết bị.
- Menu có thể xuống dòng khi màn hình hẹp.
- Lưới 4 sản phẩm trên máy tính chuyển thành 2 cột ở màn hình trung bình và 1 cột trên điện thoại hẹp.
- Hình ảnh không vượt khỏi thẻ; chữ dễ đọc; nút bấm có vùng bấm đủ lớn.
- Không dùng JavaScript hoặc framework ở phiên bản này.
