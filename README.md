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

## Sử dụng

- Người thi: mở link trang, nhập họ tên, chọn lĩnh vực, làm bài, nộp bài. Kết quả tự gửi về Google Sheet của người tổ chức (khi đã khai báo máy chủ trong `config.js`).
- Người thiết lập: bấm ⚙ góc trên, nhập khóa quản trị (hoặc mã PIN khi chạy ngoại tuyến), sửa cuộc thi/câu hỏi, bấm **Công bố lên máy chủ**.
- Không đưa nội dung mật lên kho này (kho công khai).
