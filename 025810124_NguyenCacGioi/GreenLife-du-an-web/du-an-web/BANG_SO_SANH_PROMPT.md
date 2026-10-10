# BÀI 1 – SO SÁNH PROMPT A VÀ PROMPT B

> Lưu ý: Kết quả cụ thể có thể khác tùy công cụ AI. Bảng dưới đây là phần dự kiến để hiểu sự khác nhau; nếu giảng viên yêu cầu minh chứng trực tiếp, hãy gửi Prompt A và Prompt B trong hai cuộc trò chuyện mới, rồi cập nhật theo kết quả bạn thực sự nhận được.

## Prompt A – hỏi kém
`Làm cho tôi trang web bán hàng.`

## Prompt B – hỏi tốt
Bạn là giảng viên lập trình web. Tôi là người mới học, đang làm đồ án web bán đồ dùng thân thiện môi trường, chỉ dùng HTML và CSS thuần. Hãy viết trang chủ gồm: đầu trang có logo và menu, khối giới thiệu, lưới 4 sản phẩm, chân trang. Không dùng React hay thư viện ngoài. Gửi đầy đủ 2 file index.html và css/style.css, mỗi file có tên ở dòng đầu.

## Bảng so sánh

| Câu hỏi | Prompt A – hỏi kém | Prompt B – hỏi tốt |
|---|---|---|
| AI dùng công nghệ gì? | Không quy định, AI có thể tự chọn công nghệ và có thể đưa ra giải pháp phức tạp hơn nhu cầu. | Nêu rõ chỉ dùng HTML và CSS thuần, không dùng React hay thư viện ngoài. |
| AI đưa bao nhiêu file? Có ghi tên không? | Không nói rõ số lượng hay tên file; kết quả có thể không thống nhất. | Yêu cầu đủ 2 file: `index.html` và `css/style.css`. |
| Có yêu cầu cài đặt thêm gì không? | Không có ràng buộc; tùy câu trả lời AI, có thể đề xuất công cụ hoặc cài đặt. | Không dùng thư viện ngoài, nên trang tĩnh cơ bản không cần `npm install`. |
| Có thể mở bằng cách nhấp đúp file không? | Chưa chắc, tùy công nghệ AI tự chọn. | Có thể mở trực tiếp `index.html` vì dùng HTML/CSS thuần. |
| AI có hỏi lại không? | Có thể hỏi thêm hoặc tự đoán vì yêu cầu quá chung. | Đã nêu khá rõ bố cục và định dạng, nên thường ít cần hỏi lại. |

## Kết luận
AI không tự biết trình độ, công nghệ và cấu trúc dự án của người dùng. Prompt càng rõ vai trò, bối cảnh, nhiệm vụ, ràng buộc và định dạng đầu ra thì kết quả càng dễ kiểm tra và chạy được.
