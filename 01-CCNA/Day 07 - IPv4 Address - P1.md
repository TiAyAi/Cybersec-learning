# 📅 [2026-06-02] — [IPv4 Address - P1]

## 🧠 Học được gì hôm nay
- Giới thiệu về địa chỉ IPv4 :
  + IP address là 1 con số dùng để định danh thiết bị mạng trong Network, mỗi thiết bị mạng ứng với 1 NIC sẽ có 1 IP duy nhất.
  + Ví dụ :   192.168.128.1/24
 
- Địa chỉ IPv4 gồm 4 phần cách nhau bởi dấu chấm, mỗi phần gọi là Octet ( Octet-1 . Octet-2 . Octet-3 . Octet-4 )
- Mỗi Octet là 8bit => 1 IP address là 32bit.
- **/24** : được gọi là  **prefix length** = số bit phần mạng
- **Octet-1** sẽ quyết định địa chỉ IP đó thuộc lớp nào :
    | **Lớp**  | Dải octet đầu | Dải IP                        | Subnet mask mặc định       | Prefix mặc định | Mục đích                  |
    | -------  | ------------: | ----------------------------- | -------------------------- | --------------- | ------------------------- |
    | Class A  |       `1–126` | `1.0.0.0 → 126.255.255.255`   | `255.0.0.0`                | `/8`            | Mạng rất lớn              |
    | Class B  |     `128–191` | `128.0.0.0 → 191.255.255.255` | `255.255.0.0`              | `/16`           | Mạng vừa                  |
    | Class C  |     `192–223` | `192.0.0.0 → 223.255.255.255` | `255.255.255.0`            | `/24`           | Mạng nhỏ                  |
    | Class D  |     `224–239` | `224.0.0.0 → 239.255.255.255` | Không dùng như host thường | Không có        | Multicast (gửi nhóm)      |
    | Class E  |     `240–255` | `240.0.0.0 → 255.255.255.255` | Không dùng thông thường    | Không có        | Experimental (thử nghiệm) |

 
- Địa chỉ IP còn được chia 2 phần: Net và Host ( Network portion + Host portion )
  + Net  : là phần cho biết IP đó thuộc **mạng nào**.
  + Host : là phần cho biết **thiết bị nào** trong mạng đó.
- <img width="242" height="113" alt="image" src="https://github.com/user-attachments/assets/5798cec2-2a30-4702-9829-82b87c2f320e" />
  


## ❓ Chỗ nào còn chưa hiểu
- 
- 

## 💡 Ví dụ thực tế / cách nhớ
- <img width="425" height="135" alt="image" src="https://github.com/user-attachments/assets/d4973ffd-aea2-457c-88c4-0d2f7cc03531" />



## ✅ Bài tập /
- 

## 🔗 Tài liệu tham khảo
- 

---
⏱ Thời gian học hôm nay: ___ phút
