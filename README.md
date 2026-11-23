# ⚖ Đấu trường Pháp luật

Ứng dụng thi trắc nghiệm tìm hiểu pháp luật trực tuyến.
Người phát triển: **Trần_Huy_VKSND khu vực Đắk Lắk**

| File | Vai trò |
|---|---|
| `index.html` | Toàn bộ ứng dụng (giao diện người thi + người thiết lập) |
| `config.js` | Địa chỉ máy chủ ghi kết quả (Google Apps Script) – sửa trực tiếp trên GitHub |

## Bộ câu hỏi có sẵn (800 câu)

| Cuộc thi | Số câu trong ngân hàng | Mỗi lượt thi |
|---|---|---|
| Thi hành án dân sự | 200 | 20 câu / 30 phút |
| Kiểm sát giải quyết vụ án dân sự liên quan đến đất đai | 200 | 20 câu / 30 phút |
| Thí điểm VKS khởi kiện vụ án dân sự (NQ 205/2025/QH15) | 200 | 20 câu / 30 phút |
| Chuyển đổi số, an ninh mạng, kỹ năng số | 200 | 20 câu / 30 phút |

## Cuộc thi đánh giá nhận thức (học tập nghị quyết)

| Cuộc thi | Câu hỏi | Mỗi lượt |
|---|---|---|
| Đánh giá nhận thức Nghị quyết Hội nghị Trung ương 4 khóa XIV | 77 câu – **không lưu trên kho này**, người thiết lập nạp từ file nội bộ | 20 câu / 30 phút, rút ngẫu nhiên chia đều theo 6 văn bản; đạt yêu cầu khi đúng từ 70% số câu (≥ 14/20) |

Chế độ đánh giá nhận thức: giữ nguyên thứ tự câu, phương án; không quy đổi điểm, không xếp loại, không trò chơi; không hiện đáp án; chưa đạt được làm lại; đạt thì khai và in phiếu xác nhận 3 nội dung. Khi máy chủ dùng Code.gs bản 4, đáp án chỉ lưu trên máy chủ và máy chủ chấm bài.

## Sử dụng

- Người thi: mở link trang, nhập họ tên, chọn lĩnh vực, làm bài, nộp bài. Kết quả tự gửi về Google Sheet của người tổ chức (khi đã khai báo máy chủ trong `config.js`).
- Người thiết lập: bấm ⚙ góc trên, nhập khóa quản trị (hoặc mã PIN khi chạy ngoại tuyến), sửa cuộc thi/câu hỏi, bấm **Công bố lên máy chủ**.
- Không đưa nội dung mật, file đáp án lên kho này (kho công khai).
