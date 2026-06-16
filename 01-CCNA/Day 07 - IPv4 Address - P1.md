# 📅 [2026-06-02] — [IPv4 Address - P1]

## 🧠 Học được gì hôm nay
- Giới thiệu về địa chỉ IPv4 :
  + IP address là 1 con số dùng để định danh thiết bị mạng trong Network, mỗi thiết bị mạng ứng với 1 NIC sẽ có 1 IP duy nhất.
  + Ví dụ :   192.168.128.1/24
 
- Địa chỉ IPv4 gồm 4 phần cách nhau bởi dấu chấm, mỗi phần gọi là Octet ( Octet-1 . Octet-2 . Octet-3 . Octet-4 )
- Mỗi Octet là 8bit => 1 IP address là 32bit.
- **/24** : được gọi là  **prefix length** = số bit phần mạng.
- Ký hiệu CIDR (Ký hiệu xuyệt /) = Classless Inter-Domain Routing(Định tuyến liên tên miền không phân lớp)
- Địa chỉ IP còn được chia 2 phần: Net và Host ( Network portion + Host portion )
  + Net  : là phần cho biết IP đó thuộc **mạng nào**.
  + Host : là phần cho biết **thiết bị nào** trong mạng đó.

- 
- **Octet-1** sẽ quyết định địa chỉ IP đó thuộc lớp nào :
    | **Lớp**  | Dải octet đầu | Dải IP                        | Subnet mask mặc định       | Prefix mặc định | Mục đích                  |
    | -------  | ------------: | ----------------------------- | -------------------------- | --------------- | ------------------------- |
    |       A  |       `1–126` | `1.0.0.0 → 126.255.255.255`   | `255.0.0.0`                | `/8`            | Mạng rất lớn              |
    |       B  |     `128–191` | `128.0.0.0 → 191.255.255.255` | `255.255.0.0`              | `/16`           | Mạng vừa                  |
    |       C  |     `192–223` | `192.0.0.0 → 223.255.255.255` | `255.255.255.0`            | `/24`           | Mạng nhỏ                  |
    |       D  |     `224–239` | `224.0.0.0 → 239.255.255.255` | Không dùng như host thường | Không có        | Multicast (gửi nhóm)      |
    |       E  |     `240–255` | `240.0.0.0 → 255.255.255.255` | Không dùng thông thường    | Không có        | Experimental (thử nghiệm) |


  - Địa chỉ IP ở **Lớp D** được dùng để đại diện cho 1 nhóm thiết bị mạng. Công nghệ Multicast này được sử dụng nhiều nhất cho IP Tivi.
    Được dùng để đại diện cho các kênh truyền hình ...

## ❓ Chỗ nào còn chưa hiểu

## 💡 Ví dụ thực tế / cách nhớ
- <img width="425" height="135" alt="image" src="https://github.com/user-attachments/assets/d4973ffd-aea2-457c-88c4-0d2f7cc03531" />



## ✅ Bài tập /

- Subnet Mask là gì , phương thức hoạt động ?

 + Subnet mask dùng để xác định phần nào của IP là phần mạng (Net Portion), phần nào là phần host (Host Portion), từ đó biết IP đích cùng mạng hay khác mạng.

 + Subnet mask giúp tìm Network Address.
    Cùng Network Address → gửi trực tiếp.
    Khác Network Address → gửi qua default gateway.
   
 + Cơ chế tìm Network Address bằng Subnet Mask của Máy tính là:
     * sử dụng phép AND giữa IP address và Subnet Mask  ( IP Address **AND** Subnet Mask **=** Network Address )
  

## 🔗 Tài liệu tham khảo

-----------------------------------------------------------------------------------------------------------
⏱ Thời gian học hôm nay: ___ phút
