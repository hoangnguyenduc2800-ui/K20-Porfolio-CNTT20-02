# AI LOG – BUỔI 7, TIẾT 3

> Điền vào `[ ... ]`, tích `[x]` vào lựa chọn phù hợp. Ghi đúng việc đã làm; chưa kiểm tra thì ghi “Chưa kiểm tra”. Không cần chép toàn bộ cuộc trò chuyện AI.

## Thông tin sinh viên

- Họ và tên: [ Nguyễn Đức Hoàng ... ]
- Mã sinh viên – Lớp: [ ..2071020081 - CNTT20-02. ]
- Ngày thực hiện: [ ..30/10/2026. ]
- Link repository: [ ..https://github.com/hoangnguyenduc2800-ui/K20-Porfolio-CNTT20-02.git. ]
- URL website: [ .https://hoangnguyenduc2800-ui.github.io/K20-Porfolio-CNTT20-02/.. ]
- Tình huống: [ x] Website của tôi  [ ] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: [ .[index.html – trang hiển thị chưa có định dạng CSS].. ]
- Mong muốn và hiện tượng thực tế: [ .Muốn trang portfolio hiển thị đầy đủ kiểu dáng; trước khi sửa, tôi thấy ...]
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): [ .Cấu trúc có css/style.css; Network ghi nhận URL trang chính ... với Status 200. Chưa kiểm tra Status của yêu cầu CSS.. ]
- Tôi nghi nguyên nhân là: [ .Đường dẫn stylesheet trong index.html có thể chưa đúng định dạng đường dẫn URL.. ]
- Vì sao tôi nhận định như vậy: [ .Status 200 của trang chính chỉ xác nhận HTML được tải, chưa chứng minh CSS đã tải.. ]

## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [x ] Công cụ AI: [ .copilot.. ]  [ ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  [ .PROMPT MẪU
Tôi có URL [https://hoangnguyenduc2800-ui.github.io/K20-Porfolio-CNTT20-02/], cấu trúc [main].
Network: Request URL [https://hoangnguyenduc2800-ui.github.io/K20-Porfolio-CNTT20-02/], Status [200].
Tôi dự đoán [chưa có css].
Hãy nêu giả thuyết, dữ kiện cần kiểm tra và bản sửa tối thiểu... ]

- Gợi ý chính của AI:
  [ .Kiểm tra yêu cầu css/style.css trong Network. Nếu đường dẫn CSS sai, đổi href sang css/style.css rồi deploy và kiểm tra lại yêu cầu CSS cùng giao diện.. ]

## 3. Quyết định của tôi

- [x ] Chấp nhận gợi ý
- [x ] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: [ .Đổi đường dẫn stylesheet thành css/style.css .. ]
- Lý do, dựa trên dữ kiện nào: [ .Trong dự án có tệp css/style.css; cần kiểm tra đường dẫn tới tệp này thay vì chỉ dựa vào Status 200 của trang chính... ]

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): [ .index.html – thẻ link stylesheet: href="css/style.css" .. ]
- Nội dung thay đổi hoặc cách xử lý khác: [ .Đổi href từ css\style.css thành css/style.css .. ]
- Commit của bản sửa, nếu có: [ ... ]
- Bản sửa đã deploy: [ x ] Có  [ ] Chưa  [ ] Không phát sinh bản sửa

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | [ .Nếu chưa lưu hoặc chưa xem lại, ghi .. ] | [ .không tự điền.. ] |
| Giao diện/chức năng trên URL website | [ ... ] | [ ... ] |

- Cách thử lại và kết quả thực tế: [ .Tải lại website, lọc Network theo CSS, kiểm tra URL/Status của style.css và quan sát giao diện: ... ]
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): [ .URL stylesheet trong Network, ảnh chụp hoặc thông tin commit nếu có.. ]

## 5. Kết luận

- [ x ] Đã xử lý được  [ ] Xử lý được một phần  [ ] Chưa xử lý được
- Điều tôi rút ra hoặc việc cần làm tiếp: [ Chỉ giữ [x] Đã xử lý được và [x] Có ở mục deploy nếu bạn đã deploy và thử lại website sau deploy, xác nhận stylesheet tải được và giao diện đúng. Nếu chưa xác nhận, hãy đổi sang trạng thái phù hợp và ghi rõ Chưa kiểm tra ở kết quả còn thiếu.... ]

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng. Nếu có tình huống khác, sao chép mục 1–5 để ghi thêm.*
