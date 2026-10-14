**Bài 7: Gỡ Lỗi Trang Hướng Dẫn Nộp Bài Của Giảng Viên**   
***Phần 1: Phân tích lỗi***

**1\.** Liệt kê từng lỗi cú pháp tìm được trong đoạn Markdown trên (ghi rõ dòng nào bị lỗi, lỗi gì).

**\+Lỗi 1:** Dòng \#\#\#Lưu ý quan trọng thiếu dấu cách sau dấu \#. Cú pháp đúng là \#\#\# Lưu ý quan trọng.

**\+Lỗi 2:** Các dòng \-Bước 1, \-Bước 2, \-Bước 3, \-Bước 4 thiếu dấu cách sau dấu gạch ngang. Cần sửa thành \- Bước 1, \- Bước 2, ...

**\+Lỗi 3:** Liên kết GitHub viết sai cú pháp do lồng hai cách viết liên kết. Cần sửa thành \[GitHub\](https\://github.com/).

**\+Lỗi 4:** Tên repository ở Bước 2 mở dấu \*\* nhưng chưa đóng dấu \*\*, khiến phần in đậm không đúng.

**\+Lỗi 5:** Phần Deadline sử dụng dấu \* không cân bằng, làm định dạng chữ nghiêng và chữ đậm không đúng.

**2\.** Giải thích hậu quả của mỗi lỗi khi hệ thống render — trang web sẽ hiển thị sai như thế nào?  
Heading thiếu dấu cách có thể không được nhận diện là tiêu đề.

\+Danh sách thiếu dấu cách có thể hiển thị thành văn bản thông thường.

\+Liên kết sai cú pháp có thể không bấm được hoặc hiển thị không đúng.

\+Dấu in đậm và in nghiêng không cân bằng khiến định dạng văn bản không như mong muốn.

\+Dấu trích dẫn sai khiến dòng Deadline không hiển thị dưới dạng khối trích dẫn.

***Phần 2: Sửa lỗi***

3\. Viết lại toàn bộ đoạn Markdown đã sửa đúng cú pháp, đảm bảo khi render sẽ hiển thị đúng ý định của giảng viên.

# **Hướng Dẫn Nộp Bài Tập \- Session 08**

### **Lưu ý quan trọng**

Các bước nộp bài:

* Bước 1: Tạo tài khoản GitHub tại [GitHub](https://github.com/).  
* Bước 2: Tạo repository mới đặt tên theo định dạng **HNKS25CNTT1\_IT101\_Session08**.  
* Bước 3: Upload file .md của bài làm lên repository.  
* Bước 4: Copy đường dẫn và nộp lên *Portal*.

> *Deadline: Chủ nhật 23:59* — **Nộp muộn sẽ bị trừ 50% điểm\!**

**4\.** Bẫy dữ liệu: Nếu sinh viên paste đường link GitHub mà quên gõ https\:// ở đầu, điều gì sẽ xảy ra với link đó khi render?

Trình duyệt có thể hiểu github.com là đường dẫn tương đối so với trang hiện tại, thay vì mở trang GitHub chính thức. Vì vậy, nên sử dụng \[GitHub\](https\://github.com/) để liên kết hoạt động chính xác.

