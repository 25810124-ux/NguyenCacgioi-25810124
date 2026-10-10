# NHẬT KÝ PROMPT

- Họ tên: [Nguyễn Các Giỏi]
- MSSV: [123456789]
- Công cụ AI: ChatGPT, CANVA AI

> Nhật ký dưới đây là bản dự thảo tổng hợp quá trình xây dựng bộ mã. Sau khi chạy trên máy, hãy cập nhật giờ, kết quả quan sát và lỗi thực tế của chính bạn; không ghi rằng đã chụp màn hình nếu chưa chụp.

## Lần 1 – Bước 1 và 2: Khung ngữ cảnh, đặc tả
- Mục đích: Chốt phạm vi website GreenLife và yêu cầu kỹ thuật cho người mới học.
- Prompt đã dùng: Prompt mẫu 0 (điều chỉnh tên website, chủ đề và hệ điều hành Windows); Prompt mẫu 1 để xây dựng đặc tả.
- Kết quả: Xác định hai trang `index.html`, `san-pham.html`, dùng chung CSS và không thêm tính năng ngoài phạm vi.
- Vấn đề gặp phải: Ban đầu tên website chưa xác định; đã chốt GreenLife theo lựa chọn của người dùng.
- Điều tôi học được: Cần nêu rõ công nghệ, cấu trúc file và giới hạn tính năng.

## Lần 2 – Bước 3: Phác thảo bố cục
- Mục đích: Phác thảo trang chủ cho máy tính và điện thoại trước khi viết code.
- Prompt đã dùng: Prompt mẫu 2 – yêu cầu wireframe bằng ký tự, chưa viết HTML.
- Kết quả: Lưu hai sơ đồ bố cục trong `WIREFRAME.md`.
- Vấn đề gặp phải: Cần bảo đảm thứ tự các khối nhất quán giữa bản desktop và mobile.
- Điều tôi học được: Phác thảo giúp xác định vị trí header, hero, sản phẩm và footer trước khi dựng giao diện.

## Lần 3 – Bước 4: Dựng trang chủ
- Mục đích: Tạo trang chủ đúng đặc tả.
- Prompt đã dùng: Prompt mẫu 3 – HTML5/CSS3 thuần, đúng đường dẫn file, responsive và chú thích CSS bằng tiếng Việt.
- Kết quả: Tạo `public/index.html` và `public/css/style.css`; trang chủ có giới thiệu, bốn sản phẩm nổi bật và chân trang.
- Vấn đề gặp phải: Ảnh dùng URL minh họa nên cần kết nối Internet.
- Điều tôi học được: HTML tạo cấu trúc, CSS tạo cách trình bày; thẻ `link` kết nối hai file.

## Lần 4 – Bước 5: Chỉnh giao diện lần 1
- Mục đích: Tăng khoảng cách và độ rõ của các thẻ sản phẩm.
- Prompt đã dùng: Prompt mẫu 4 – yêu cầu chỉnh riêng khoảng cách thẻ, bo góc và bóng đổ nhẹ.
- Kết quả: CSS dùng `gap`, `border-radius` và `box-shadow` để thẻ dễ phân biệt hơn.
- Vấn đề gặp phải: Cần xem trên trình duyệt để xác nhận khoảng cách phù hợp.
- Điều tôi học được: Một lượt chỉnh nên có mục tiêu nhỏ, cụ thể và kiểm tra được.

## Lần 5 – Bước 5: Chỉnh giao diện lần 2
- Mục đích: Làm màu đầu trang nhất quán với màu xanh chủ đạo.
- Prompt đã dùng: Prompt mẫu 4 – yêu cầu dùng xanh lá đậm `#2e7d32` cho đầu trang và chữ tương phản rõ.
- Kết quả: Header, nút và liên kết dùng bảng màu thống nhất với đặc tả.
- Vấn đề gặp phải: Cần bảo đảm chữ vẫn dễ đọc trên nền xanh.
- Điều tôi học được: Dùng biến CSS và bảng màu nhất quán giúp sửa giao diện dễ hơn.

## Lần 6 – Bước 5: Chỉnh giao diện lần 3
- Mục đích: Cải thiện menu và lưới sản phẩm trên màn hình hẹp.
- Prompt đã dùng: Prompt mẫu 4 – yêu cầu menu xuống dòng gọn và lưới sản phẩm chuyển thành một cột trên điện thoại.
- Kết quả: CSS có `flex-wrap` và media query để điều chỉnh bố cục.
- Vấn đề gặp phải: Cần kiểm tra thực tế ở khoảng rộng 375 px.
- Điều tôi học được: Media query giúp đổi bố cục theo kích thước màn hình.

## Lần 7 – Bước 6: Thêm trang phụ
- Mục đích: Tạo trang danh sách sản phẩm.
- Prompt đã dùng: Prompt mẫu 5 – dựa trên đặc tả, giữ chung CSS, liên kết menu và cung cấp ít nhất 8 sản phẩm.
- Kết quả: Tạo `public/san-pham.html` với 8 sản phẩm minh họa và liên kết quay lại trang chủ.
- Vấn đề gặp phải: Cần kiểm tra từng đường dẫn tương đối và tên file.
- Điều tôi học được: Các trang có thể dùng chung một file CSS bằng cùng đường dẫn tương đối.

## Lần 8 – Bước 7: Kiểm thử
- Mục đích: Rà soát liên kết, thuộc tính alt, tiếng Việt và responsive.
- Prompt đã dùng: Prompt mẫu 6 – yêu cầu AI đóng vai tester, liệt kê vấn đề theo mức độ ưu tiên trước khi sửa.
- Kết quả: Tạo `CHECKLIST_NOP_BAI.md` để tự kiểm tra liên kết, ảnh, bố cục desktop/mobile và cách mở file.
- Vấn đề gặp phải: Kết quả kiểm thử cuối cùng cần được xác nhận bằng cách chạy trên máy thật.
- Điều tôi học được: AI có thể gợi ý lỗi, nhưng người làm cần tự kiểm chứng trong trình duyệt.

## Bổ sung sau khi chạy thực tế
- Ngày/giờ chạy thử: [Điền sau khi thực hiện]
- Kết quả desktop: [Điền kết quả thực tế]
- Kết quả mobile: [Điền kết quả thực tế]
- Lỗi phát hiện và cách sửa: [Điền nếu có]
