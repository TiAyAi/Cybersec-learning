# 📅 [2026-05-14] — [Packet Delivery - P1]

## 🧠 Học được gì hôm nay
- Packet Delivery là gì ?
    + là quá trình đưa gói tin(packet) từ máy nguồn đến máy đích qua mạng.
    +💡 Ví dụ thực tế :  Khi máy A gửi dữ liệu cho máy B, dữ liệu được chia thành các gói tin(packet),
                          việc Mạng đưa các packet đó đến đúng máy B gọi là Packet Delivery.

- Packet delivery chủ yếu là chức năng của tầng 3 – Network layer (tầng Mạng).
- Packet delivery có 2 kiểu chính : Same Subnet & Different Subnet

## Lưu ý :  
            1. Bất kỳ loại dữ liệu nào khi gửi ra khỏi thiết bị mạng đều phải có đầy đủ 4 địa chỉ :
            + Source IP  _ Destination IP
            + Source Mac _ Destination Mac
            
##          2. Dữ liệu mạng luôn luôn là con đường 2 chiều (có hỏi thì phải nhận được phản hồi)
##          3. Dữ liệu chiều đi và chiều về sẽ swap thông tin vị trí cho nhau           
    
## I.  SAME SUBNET 
- ARP Table là gì ? Cơ chế hoạt động ?
- Address Resolution Protocol Table : là bảng ánh xạ địa chỉ Mac tương ứng với địa chỉ IP, được lưu trữ trên RAM, hoạt động trên cơ chế Broadcast.
- ARP request / ARP reply.


## ❓ Chỗ nào còn chưa hiểu
- 
- 

## 💡 Ví dụ thực tế / cách nhớ
- 

## ✅ Bài tập / Lab đã làm

- 4 loại địa chỉ của gói tin ARP request ?
    Trả lời :  sẽ bao gồm :    Broadcast Mac - Mac Source - IP Destination - IP Source
- Broadcast Mac là (địa chỉ MAC quảng bá), gửi cho tất cả thiết bị trong LAN. thường được quy định đặt là 12 chữ F (FF:FF:FF:FF:FF:FF)

## 🔗 Tài liệu tham khảo
- Youtube: Neo Tranning Center

---
⏱ Thời gian học hôm nay: ___ phút
