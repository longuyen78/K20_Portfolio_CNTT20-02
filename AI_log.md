# AI LOG – BUỔI 7, TIẾT 3

> Ghi ngắn gọn quá trình dùng AI để tìm và sửa lỗi website.

## Thông tin sinh viên

- Họ và tên: [ Đinh Công Quang Chí ]
- Mã sinh viên – Lớp: [ 2071020029 – CNTT 20-02 ]
- Ngày thực hiện: [ 30/10/2026 ]
- Link repository: [ https://github.com/quangchi20888/K20_Portfolio_CNTT20-02.git ]
- URL website: [ https://quangchi20888.github.io/K20_Portfolio_CNTT20-02/ ]
- Tình huống: [x] Website của tôi  [ ] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: [ Trang Portfolio bị mất CSS. ]
- Mong muốn và hiện tượng thực tế: [ Muốn giao diện đẹp, nhưng trang chỉ hiện chữ và ảnh mặc định. ]
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): [ HTML và ảnh vẫn hiện; chưa kiểm tra mã Status. ]
- Tôi nghi nguyên nhân là: [ Sai đường dẫn đến file CSS. ]
- Vì sao tôi nhận định như vậy: [ Nội dung vẫn có nhưng không được định dạng. ]

## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [x] Công cụ AI: [ GitHub Copilot ]  [ ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  [ Tôi có URL [https://quangchi20888.github.io/K20_Portfolio_CNTT20-02/].
Tôi dự đoán [lỗi liên kết css]
Hãy nêu giả thuyết, dữ kiện cần kiểm tra và bản sửa tối thiểu.
Chỉ tư vấn, không sửa tệp. Không kết luận đã sửa thành công ]

- Gợi ý chính của AI:

  [ Đổi riêng giá trị href thành đường dẫn tương đối với index.html: <link rel="stylesheet" href="css/style.css" /> ]

## 3. Quyết định của tôi

- [x] Chấp nhận gợi ý
- [ ] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: [ Kiểm tra và sửa đường dẫn CSS. ]
- Lý do, dựa trên dữ kiện nào: [ Trang có nội dung nhưng bị mất giao diện. ]

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): [ index.html ]
- Nội dung thay đổi hoặc cách xử lý khác: [ Sửa đường dẫn trong thẻ link CSS. ]
- Commit của bản sửa, nếu có: [ Chưa commit ]
- Bản sửa đã deploy: [x] Có  [ ] Chưa  [ ] Không phát sinh bản sửa

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | CSS không tải | CSS hoạt động |
| Giao diện/chức năng trên URL website | Mất định dạng, ảnh quá to | Hiển thị đúng bố cục |

- Cách thử lại và kết quả thực tế: [ Tải lại trang bằng Ctrl + F5, giao diện bình thường. ]
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): [ So sánh giao diện trước và sau khi sửa. ]

## 5. Kết luận

- [x] Đã xử lý được  [ ] Xử lý được một phần  [ ] Chưa xử lý được
- Điều tôi rút ra hoặc việc cần làm tiếp: [ Biết kiểm tra đường dẫn CSS và dùng AI để hỗ trợ sửa lỗi. ]

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng.*
