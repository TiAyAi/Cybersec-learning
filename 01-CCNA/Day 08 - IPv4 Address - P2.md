# 📅 [2026-06-11] — [IPv4 Address - P2]

## 🧠 Học được gì hôm nay  :  
## SUBNET MASK
- là công cụ dùng để phân định ip mà t/bị mạng đang sở hữu có bao nhiêu bit thuộc phần Net, b/nhiêu Bit thuộc phần Host.
- số Bit thuộc phần Net bao nhiêu thì nó sẽ qui đổi thành bấy nhiêu Bit 1.
  
- CLASSFUL  / CLASSLESS
    Classful  = chia IP theo lớp A/B/C cố định
    Classless = chia IP linh hoạt bằng prefix /8 /16 /24 /25...
  
So sánh dễ hiểu  
| Tiêu chí     | Classful               | Classless                               |
| ------------ | ---------------------- | --------------------------------------- |
| Cách chia    | Theo lớp A/B/C         | Theo prefix `/x`                        |
| Subnet mask  | Cố định theo lớp       | Linh hoạt                               |
| Ví dụ        | Class C mặc định `/24` | `192.168.1.0/25`, `/26`, `/27` đều được |
| Hiện nay     | Kiểu cũ                | Đang dùng phổ biến                      |
| Tiết kiệm IP | Kém hơn                | Tốt hơn                                 |

## IPv4 Address Public / Private 
- Tổ chức "IANA" đã suy nghĩ ra 02 cách để tiết kiệm không gian địa chỉ IPv4
1. Public (IANA chia ra 5 phân vùng toàn cầu cho các ISPs -> Clients)
    - Định danh các mạng LAN trong môi trường mạng WAN
2. Private : phân ra các lớp mạng trong mạng LAN



## NAT ( Network Address Translation )
- Chuyển đổi địa chỉ mạng.
- Là cơ chế giúp các máy tính trong mạng Lan có thể dùng chung 01 IP Public để đi ra mạng Internet.
- 

## 💡 Ví dụ thực tế / cách nhớ
- 

## ✅ Bài tập / Lab đã làm
- 

## 🔗 Tài liệu tham khảo
- 

---
⏱ Thời gian học hôm nay: ___ phút
