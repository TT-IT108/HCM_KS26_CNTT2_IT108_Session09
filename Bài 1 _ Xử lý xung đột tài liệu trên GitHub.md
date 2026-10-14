**Bài 1 : Xử lý xung đột tài liệu trên GitHub**   
**Phần 1\. Phân tích:**

Chỉ ra 2 sai lầm trong tư duy của Nam về việc dùng file Word cho lưu trữ mã nguồn. Giải thích tại sao Markdown lại an toàn và nhẹ hơn.

Nam mắc hai sai lầm:

**\+Thứ nhất:** Nam cho rằng Word tốt hơn Markdown vì có nhiều công cụ định dạng. Thực tế, Word phù hợp để trình bày văn bản, còn Markdown đơn giản, nhẹ và phù hợp để viết tài liệu dự án trên GitHub.

**\+Thứ hai:** Nam chưa nhận ra khó khăn khi quản lý file Word bằng Git. File `.docx` có cấu trúc phức tạp nên khó so sánh nội dung thay đổi. Markdown là văn bản thuần nên Git Diff dễ hiển thị các dòng được thêm, sửa hoặc xóa.

Markdown thường nhẹ hơn Word và dễ đọc bằng trình soạn thảo văn bản. Nếu mất một phần dữ liệu, phần văn bản còn lại thường vẫn đọc được, nhưng không có nghĩa Markdown hoàn toàn không thể bị hỏng.

## **2\. Phần 2: Hoàn thiện bằng StackEdit**

Ví dụ nội dung Markdown:

\# Giới thiệu dự án

Dự án xây dựng ứng dụng hỗ trợ người dùng.

\#\# Chức năng chính

\- Giao diện dễ sử dụng.

\- Hiển thị thông tin rõ ràng.

\- Quản lý dữ liệu thuận tiện.

