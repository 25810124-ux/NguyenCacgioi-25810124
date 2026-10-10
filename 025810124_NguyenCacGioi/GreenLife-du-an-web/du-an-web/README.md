# GREENLIFE – CỬA HÀNG CÂY XANH
Bài thực hành 02 – Học phần Lập trình Web WEPR330479

## 1. Giới thiệu
GreenLife là website tĩnh giới thiệu cửa hàng cây cảnh, chậu cây và phụ kiện chăm sóc cây. Dự án dùng HTML5 và CSS3 thuần, không dùng framework, không cần cài npm hay chạy máy chủ.

## 2. Cấu trúc dự án
```text
du-an-web/
├── DAC_TA.md
├── KHUNG_NGU_CANH.txt
├── NHAT_KY_PROMPT.md
├── README.md
├── WIREFRAME.md
├── BANG_SO_SANH_PROMPT.md
├── CHECKLIST_NOP_BAI.md
└── public/
    ├── index.html
    ├── san-pham.html
    └── css/
        └── style.css
```

## 3. Chạy website trên Windows bằng VS Code
1. Giải nén `GreenLife-du-an-web.zip`.
2. Mở VS Code.
3. Chọn **File > Open Folder...** và mở thư mục `GreenLife-du-an-web` (thư mục có `DAC_TA.md` và `public`).
4. Trong Explorer, mở `public/index.html`.
5. Nhấp chuột phải trong file và chọn **Open in Default Browser** nếu máy có lệnh này; nếu không, mở File Explorer, vào `public`, nhấp đúp `index.html` để mở bằng Chrome hoặc Edge.
6. Bấm `Ctrl + F5` để tải lại trang sau khi sửa code. Không cần `npm install`, không cần terminal.
7. Kiểm tra trang phụ bằng cách nhấp mục **Sản phẩm** trên menu.

> Ảnh sản phẩm hiện là ảnh minh họa từ `placehold.co` theo yêu cầu bài thực hành, nên cần có Internet để ảnh hiển thị. Khi làm tiếp đồ án, có thể thay bằng ảnh thật.

## 4. Kiểm tra giao diện trên điện thoại
1. Mở trang bằng Chrome.
2. Bấm `F12`, sau đó `Ctrl + Shift + M` để bật chế độ thiết bị.
3. Chọn một thiết bị điện thoại hoặc đặt chiều rộng khoảng 375 px.
4. Kiểm tra menu, phần giới thiệu, các thẻ sản phẩm và chân trang; không nên có thanh cuộn ngang.
5. Chụp màn hình desktop và mobile bằng `Windows + Shift + S`, lưu ảnh vào thư mục nộp bài theo yêu cầu giảng viên.

## 5. Lưu ý trước khi nộp
- Thay `[HỌ TÊN]` và `[MSSV]` trong `NHAT_KY_PROMPT.md` bằng thông tin thật của sinh viên.
- Nhật ký là bản dự thảo dựa trên các bước và prompt dùng để tạo dự án. Bổ sung kết quả kiểm tra thực tế, lỗi thực tế và thời gian bạn đã làm.
- Thực hiện checklist trong `CHECKLIST_NOP_BAI.md`, đặc biệt là chụp ảnh màn hình thực tế. Không nộp ảnh minh họa giả làm ảnh chụp trình duyệt.
