# Day 03 — OSI Model P1
**Ngày học:** 2026-05-07  
**Nguồn:**  NEO Training Center  
**Trạng thái:** 🟡 Đang học (4/7 tầng)

---

## 7 Tầng OSI — Tên & Thứ tự

| Tầng | Tên | Ghi nhớ |
|---|---|---|
| 7 | Application | Ứng dụng người dùng |
| 6 | Presentation | Trình bày, định dạng |
| 5 | Session | Phiên kết nối |
| 4 | Transport | Vận chuyển dữ liệu |
| 3 | Network | Định tuyến |
| 2 | Data Link | Kết nối thiết bị kề nhau |
| 1 | Physical | Vật lý, dây cáp |

**Câu ghi nhớ (7 → 1):**
> All People Seem To Need Data Processing

---

## Chức năng 4 tầng trên (đã học hôm nay)

### Tầng 7 — Application
- Tầng giao tiếp trực tiếp với người dùng
- Nơi data được **tạo ra** — từ hành động của con người thông qua App, Services, Protocol
- Ví dụ giao thức: HTTP, FTP, DNS, SMTP

### Tầng 6 — Presentation
- **Định dạng** dữ liệu mạng để tầng Application hiểu được
- **Mã hóa / giải mã** (encryption/decryption)
- **Nén** dữ liệu (compression)
- Ví dụ: SSL/TLS, JPEG, MP4,Docx,MP3

### Tầng 5 — Session
- ** Khởi tạo, duy trì, Kết thúc ** phiên kết nối giữa 2 thiết bị
- Quản lý việc **ai nói, ai nghe** trong một phiên
- Ví dụ: Login session, API session

### Tầng 4 — Transport
- **Chia nhỏ** dữ liệu thành các Segment
- Lựa chọn cơ chế truyền dữ liệu
- **TCP** — tin cậy, có xác nhận, chậm hơn
- **UDP** — không xác nhận, nhanh hơn
- Tên dữ liệu ở tầng này: **Segment**

---

## Còn lại — Học buổi sau
- [ ] Tầng 3 — Network
- [ ] Tầng 2 — Data Link  
- [ ] Tầng 1 — Physical
- [ ] Encapsulation / De-encapsulation
- [ ] PDU của từng tầng

---

## Câu hỏi / Thắc mắc chưa rõ
*(Ghi lại những gì chưa hiểu để hỏi sau)*
Tìm hiểu thêm về :
1. MTU ?  1500 byte.
2. Các khái niệm : byte, bit , GB, MB ..
3. Port Number 

---

## Tự đánh giá hôm nay
- Hiểu được: 🟢 Tên 7 tầng, chức năng tầng 7-4
- Cần ôn lại: 🟡 Phân biệt rõ tầng 6 và 7
- Chưa học: 🔴 Tầng 3, 2, 1 và Encapsulation
