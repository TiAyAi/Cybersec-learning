# Day 04 — OSI Model P2
**Ngày học:** 2026-05-09  
**Nguồn:**  NEO Training Center  
**Trạng thái:** 🟢 Học Xong (7/7 tầng)

---

## 7 Tầng OSI — Tên & Thứ tự

| Tầng | Tên | Ghi nhớ |
|---|---|---|
| 7 | Application     | Ứng dụng người dùng      |
| 6 | Presentation    | Trình bày, định dạng     |
| 5 | Session         | Phiên kết nối            |
| 4 | Transport       | Vận chuyển dữ liệu       |
| 3 | Network         | Định tuyến               |
| 2 | Data Link       | Kết nối thiết bị kề nhau |
| 1 | Physical        | Vật lý, dây cáp          |

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

### Tầng 3 — Network
- **Xử lý IP và định tuyến** 
- Gắn IP nguồn và IP đích
- Chọn đường đi qua router
- Chuyển packet (gói tin) giữa các mạng khác nhau
- Protocol (giao thức) thường gặp:
    IP
    ICMP
    OSPF
    RIP
  
### Tầng 2 — Data link - Liên kết dữ liệu
- Tầng này xử lý truyền dữ liệu trong cùng một mạng nội bộ LAN.
- Chức năng:
    Dùng MAC address (địa chỉ vật lý)
    Đóng gói dữ liệu thành frame (khung dữ liệu)
    Phát hiện lỗi cơ bản  
- Protocol/công nghệ thường gặp: 
    Ethernet
    Wi-Fi
    ARP
    VLAN
  
### Tầng 1: Physical — Vật lý
Tầng thấp nhất, xử lý tín hiệu thật sự.
- Chức năng:
    Truyền bit 0 và 1
    Qua dây mạng, cáp quang, sóng Wi-Fi
    Quy định điện áp, tốc độ truyền, đầu cắm
- Thiết bị/vật liệu:
    Cáp mạng
    Cáp quang
    Sóng radio Wi-Fi
    Hub
    Repeater
    
---

##  — Học buổi sau
- Packet Delivery

---

## Câu hỏi / Thắc mắc chưa rõ
*(Ghi lại những gì chưa hiểu để hỏi sau)*
Tìm hiểu thêm về : Packet Delivery


---

## Tự đánh giá hôm nay
- Hiểu được: 🟢 Tên 7 tầng, chức năng tầng 3-1
- Cần ôn lại: 🟡 Ôn lại tất cả các tầng
