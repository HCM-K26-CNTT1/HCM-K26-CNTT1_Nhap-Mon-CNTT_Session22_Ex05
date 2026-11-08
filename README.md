# BÀI 5: TỐI ƯU QUY TRÌNH HỖ TRỢ KỸ THUẬT NỘI BỘ

## 1. Mục tiêu

Xây dựng quy trình hỗ trợ kỹ thuật nội bộ giúp các thành viên chủ động tìm cách xử lý lỗi, cung cấp thông tin rõ ràng khi cần trợ giúp và hạn chế việc hỏi trùng lặp trong nhóm.

## 2. Thiết kế Bug Report Template

Trước khi gửi câu hỏi lên nhóm chat, mỗi thành viên phải điền đủ 4 thông tin sau:

### Mẫu báo cáo lỗi (Bug Report Template)

```text
TIÊU ĐỀ: [Tên lỗi gặp phải]

1. CONTEXT (Bối cảnh)
- Đang sử dụng phần mềm/công cụ nào?
- Phiên bản phần mềm:
- Hệ điều hành:
- Đang thực hiện thao tác gì khi gặp lỗi?

2. EXPECTED (Kết quả mong đợi)
- Tôi muốn chương trình hoạt động như thế nào?

3. ACTUAL (Kết quả thực tế)
- Điều gì đã xảy ra?
- Lỗi xuất hiện như thế nào?

4. LOG (Nhật ký lỗi)
- Nội dung thông báo lỗi:
- Ảnh chụp màn hình hoặc đoạn log:
- Các cách đã thử xử lý:
```

### Ý nghĩa của 4 mảnh ghép

- **Context:** Giúp người hỗ trợ hiểu hoàn cảnh và môi trường xảy ra lỗi.
- **Expected:** Cho biết kết quả mà người dùng mong muốn.
- **Actual:** Mô tả kết quả thực tế đang gặp phải.
- **Log:** Cung cấp thông báo lỗi để tìm nguyên nhân và hướng xử lý.

## 3. Quy trình 3 bước tra cứu bắt buộc

Trước khi nhờ người khác hỗ trợ, thành viên cần thực hiện 3 bước:

### Bước 1: Googling (Tìm kiếm Google)

- Sao chép nội dung lỗi và tìm kiếm trên Google.
- Sử dụng từ khóa cụ thể, ví dụ: `Docker port already allocated`.
- Ưu tiên kết quả từ trang chủ phần mềm và tài liệu chính thức.

### Bước 2: Community Search (Tìm kiếm cộng đồng)

- Tìm lỗi trên Stack Overflow hoặc GitHub Issues.
- Đọc các câu trả lời và bình luận của người dùng.
- Ưu tiên giải pháp phù hợp với phiên bản phần mềm và hệ điều hành đang sử dụng.
- Không thực hiện những lệnh chưa hiểu rõ chức năng.

### Bước 3: AI Translation (Nhờ AI giải thích)

- Sao chép thông báo lỗi hoặc giải pháp tìm được vào AI.
- Yêu cầu AI giải thích nguyên nhân và hướng dẫn cách xử lý bằng ngôn ngữ dễ hiểu.
- Yêu cầu AI phân tích chức năng và rủi ro của câu lệnh trước khi thực hiện.
- Kiểm tra lại thông tin từ nguồn đáng tin cậy.

## 4. Quy trình hỗ trợ nội bộ

Sau khi thực hiện 3 bước tra cứu nhưng vẫn chưa xử lý được, thành viên mới gửi Bug Report vào nhóm hỗ trợ.

Quy trình thực hiện:

```text
THÀNH VIÊN GẶP LỖI
        |
        v
ĐIỀN BUG REPORT TEMPLATE
        |
        v
BƯỚC 1: GOOGLE
        |
        v
BƯỚC 2: COMMUNITY SEARCH
        |
        v
BƯỚC 3: AI TRANSLATION
        |
        v
ĐÃ GIẢI QUYẾT ĐƯỢC?
       / \
     CÓ   KHÔNG
     |      |
     v      v
 GHI LẠI   GỬI BUG REPORT
 CÁCH SỬA  VÀO NHÓM HỖ TRỢ
     |      |
     v      v
 CHIA SẺ   NHÓM KIỂM TRA
 CHO NHÓM  VÀ HƯỚNG DẪN
```

## 5. Lợi ích của quy trình

- Hạn chế các câu hỏi thiếu thông tin như "Máy em bị lỗi rồi".
- Giúp người hỗ trợ hiểu vấn đề nhanh hơn.
- Tránh nhiều thành viên hỏi cùng một lỗi.
- Khuyến khích thành viên tự tìm hiểu trước khi nhờ giúp đỡ.
- Lưu lại các lỗi và cách xử lý để những người khác tham khảo.

**Mục tiêu:** Giúp thành viên tự xử lý khoảng 80% lỗi thông thường trước khi nhờ hỗ trợ. Đây là mục tiêu đề xuất để nhóm theo dõi, không phải kết quả đã được kiểm chứng.

## 6. Kết luận

Qua bài tập, em hiểu rằng việc hỗ trợ kỹ thuật không chỉ là tìm cách sửa lỗi mà còn cần có quy trình rõ ràng. Sử dụng Bug Report Template kết hợp với 3 bước tra cứu Google, Community Search và AI Translation sẽ giúp nhóm làm việc hiệu quả hơn, tiết kiệm thời gian và hạn chế hỏi trùng lặp.
