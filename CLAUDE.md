# CLAUDE.md – Hướng dẫn làm việc cho Claude Code

File này được Claude Code tự động đọc mỗi khi mở phiên làm việc trong kho `CONG_VIEC`.
Mọi quy tắc dưới đây là bắt buộc.

## 1. Người sử dụng

- Nguyễn Văn Thúy – Trưởng phòng Kỹ thuật công nghệ mỏ (KCM), Công ty than Dương Huy - TKV (từ 12/2025).
- Kỹ sư khai thác mỏ (ĐH Mỏ - Địa chất 2005), thạc sĩ khai thác mỏ (2016).
- Tin học: Excel, Word, AutoCAD mức cơ bản, không biết lập trình.

## 2. Đơn vị

- Phòng KCM: 27 nhân sự (1 trưởng phòng, 4 phó phòng: thông gió - thoát nước - khí mỏ; lập kế hoạch; khai thác mỏ; đào lò và vận tải mỏ; còn lại là chuyên viên kỹ thuật).
- Công ty: 11 phân xưởng khai thác, 6 phân xưởng đào lò; phân xưởng phụ trợ: vận tải lò 1, vận tải lò 2, thông gió - thoát nước, sàng tuyển, tuyển.

## 3. Quy tắc về số liệu (quan trọng nhất)

1. Số liệu phải chính xác tuyệt đối, cụ thể. Không viết chung chung.
2. Số liệu **thực hiện** chỉ lấy từ thư mục `01_KHOI_LUONG_MO/`.
   Số liệu **kế hoạch** chỉ lấy từ thư mục `02_KE_HOACH/`.
3. Không tìm thấy hoặc chưa chắc chắn → **hỏi lại**, không tự điền, không ước lượng.
4. Mọi phép tính (tỷ lệ % hoàn thành, tăng/giảm so với cùng kỳ, lũy kế...) phải tính lại lần hai trước khi đưa vào báo cáo; ghi rõ công thức đã dùng.
5. Ghi rõ nguồn của từng số liệu (tên file, sheet, ô) khi trình bày.
6. Đơn vị tính chuẩn: sản lượng than – tấn; mét lò đào – m; tỷ lệ – %, làm tròn 1 chữ số thập phân trừ khi được yêu cầu khác.

## 4. Cách trả lời

- Luôn dùng tiếng Việt, rõ ràng, có cấu trúc, đi thẳng vào vấn đề.
- Chưa chắc chắn thì nói rõ là chưa chắc chắn.
- Ưu tiên ví dụ thực tế áp dụng ngay được.
- Có nhiều phương án thì lập bảng so sánh ưu, nhược điểm và nêu phương án đề xuất.
- Báo cáo viết theo văn phong hành chính - kỹ thuật của ngành than (TKV): logic, có số liệu, có đánh giá nguyên nhân và giải pháp.
- Hướng dẫn Excel: chỉ từng bước (bấm vào đâu, gõ gì), vì người dùng chỉ dùng Excel cơ bản.

## 5. Quy định về file đầu ra

- File kết quả lưu vào `99_KET_QUA/`, đặt tên: `YYYY-MM-DD_Ten-noi-dung.đuôi`
  (ví dụ `2026-10-23_Bao-cao-thang-10.docx`).
- Không sửa, không ghi đè file gốc trong `01_KHOI_LUONG_MO/` và `02_KE_HOACH/`.
- PowerPoint: trình bày chuyên nghiệp, có dashboard, biểu đồ, số liệu cụ thể và phần phân tích.
- Excel: dùng công thức (không gõ số cứng) để người dùng kiểm tra lại được.

## 6. Cấu trúc thư mục

| Thư mục | Nội dung |
|---|---|
| `01_KHOI_LUONG_MO/` | Số liệu thực hiện: sản lượng, mét lò, khối lượng theo tháng/quý/năm |
| `02_KE_HOACH/` | Kế hoạch tháng, quý, năm, 5 năm, dài hạn |
| `03_BAO_CAO/` | Báo cáo đã gửi (Tập đoàn, Giám đốc, sở ban ngành) – dùng làm mẫu văn phong |
| `04_THIET_KE/` | Hồ sơ thiết kế: khai thác, đào lò, thông gió, thoát nước, khí mỏ, phòng chống mưa bão |
| `05_MAU_BIEU/` | Mẫu biểu, mẫu báo cáo chuẩn của công ty/TKV |
| `06_NHAN_SU/` | Phân công nhiệm vụ, đánh giá nhân viên phòng KCM |
| `99_KET_QUA/` | File Claude tạo ra |
