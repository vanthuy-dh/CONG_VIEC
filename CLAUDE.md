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
2. Số liệu **thực hiện** chỉ lấy từ thư mục `3_TONG_HOP_KLM/`.
   Số liệu **kế hoạch** chỉ lấy từ thư mục `2_LAP_KE_HOACH_TKV/`.
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
- Không sửa, không ghi đè file gốc trong `3_TONG_HOP_KLM/` và `2_LAP_KE_HOACH_TKV/`.
- PowerPoint: trình bày chuyên nghiệp, có dashboard, biểu đồ, số liệu cụ thể và phần phân tích.
- Excel: dùng công thức (không gõ số cứng) để người dùng kiểm tra lại được.

## 6. Cấu trúc thư mục (khớp 1–1 với 8 dự án trên claude.ai)

| Thư mục | Dự án trên claude.ai | Nội dung |
|---|---|---|
| `1_BAO_CAO_CAC_LOAI/` | 1. BÁO CÁO CÁC LOẠI | Báo cáo gửi Tập đoàn, Giám đốc, sở ban ngành – dùng làm mẫu văn phong |
| `2_LAP_KE_HOACH_TKV/` | 2. LẬP KẾ HOẠCH TKV | Kế hoạch tháng, quý, năm, 5 năm, dài hạn – **nguồn số liệu kế hoạch** |
| `3_TONG_HOP_KLM/` | 3. TỔNG HỢP KLM | Tổng hợp khối lượng mỏ – **nguồn số liệu thực hiện** |
| `4_QUY_TRINH_QUY_DINH/` | 4. CÁC QUY TRÌNH, QUY ĐỊNH | Quy trình, quy định kỹ thuật, an toàn |
| `5_PHUONG_AN_KY_THUAT_1051/` | 5. PHƯƠNG ÁN KỸ THUẬT 1051 | Hồ sơ phương án kỹ thuật 1051 |
| `6_THEO_DOI_CV_GIAO_VIEC_LD_GIAO/` | 6. THEO DÕI CV, GIAO VIỆC LĐ GIAO | Theo dõi công việc lãnh đạo giao |
| `7_QUAN_LY_GIAO_VIEC/` | 7. QUẢN LÝ, GIAO VIỆC | Quản lý nhân viên, giao việc |
| `8_TH_NGHIEM_THU_VT_DM/` | 8. TH NGHIỆM THU, VT, ĐM | Tổng hợp nghiệm thu, định mức, vật tư |
| `99_KET_QUA/` | — | File Claude tạo ra |

Mỗi thư mục có file `README.md` mô tả nội dung; đọc file đó trước khi làm việc với thư mục.
