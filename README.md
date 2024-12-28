# NETWORK
## Network Basic
#### Mô hình OSI, TCP/IP
Mô hình OSI (Open Systems Interconnection): gồm 7 tầng từ cao(Application) đến thấp(physical):
1. **Application** (Tầng Ứng Dụng): gần với người sử dụng nhất. Chúng ta nhập thông điệp cần gửi (EX: Telnet để quản trị máy tính từ xa). 
2. **Presentation** (Tầng Trình Diễn): Chuyển đổi, mã hóa và nén dữ liệu. Nhiệm vụ: Chuyển đổi dữ liệu ↔ dãy nhị phân (0,1) hoặc văn bản ↔ ASCII(giúp máy tính hiểu).
3. **Session** (Tầng Phiên): Thiết lập, duy trì,  phục hồi và hủy phiên làm việc giữa hai máy tính. Máy A và máy B trao đổi dữ liệu trong một phiên giao tiếp.
4. **Transport** (Tầng giao vận): Đóng gói dữ liệu thành tệp dữ liệu (segment). Sử dụng giao thức TCP hoặc UDP để quản lý.
5. **Network** (Tầng Mạng): Dùng địa chỉ IP để xác định các máy trong mạng. Nhiệm vụ: Tìm các đường đi tối ưu và hiệu quả cho dữ liệu (Ex: A → 192.168.1.1 gửi dữ liệu đến máy B → 192.168.1.2). 
6. **Data Link** (Tầng dữ liệu liên kết): Quản lý luồng dữ liệu, chia nhỏ thành các khung (frame) và phát hiện lỗi khi truyền.
7. **Physical** (Tầng Vật lý): Xử lý việc truyền dữ liệu qua các tín hiệu vật lý (Ex: Cáp, sóng vô tuyến, USB)

Mô hình TCP/IP (Transmission Control Protocol): gồm 4 tầng từ cao (Application) đến thấp(Data Link) được rút gọn từ mô hình OSI.
1. **Application** (Tầng Ứng Dụng): giao tiếp giữa các ứng dụng
 - Giao thức: HTTP, FTP, POP3, SMTPM, SNMP 
   - HTTP (Hypertext Transfer Protocol): Truyền tải tài liệu web.
   - FTP (File Transfer Protocol): Chuyển tập tin giữa các máy tính.
   - POP3 (Post Office Protocol 3): Lấy thư từ máy chủ mail.
   - SMTP (Simple Mail Transfer Protocol): Gửi thư điện tử.
   - SNMP (Simple Network Management Protocol): Quản lý và giám sát mạng.
2. **Transport** (Tầng giao vận): Đảm bảo truyền tải tin cậy
 - Giao thức: TCP, UDP
   - TCP (Transmission Control Protocol): Đảm bảo độ tin cậy, kiểm soát luồng, tái truyền gói tin nếu bị mất.
   - UDP (User Datagram Protocol): Gửi dữ liệu nhanh hơn nhưng không đảm bảo độ tin cậy.
3. **Network** (Tầng Mạng): Định tuyến, xử lí gói tin
 - Giao thức: IP, ICMP
   - IP (Internet Protocol): Định tuyến và giao tiếp giữa các thiết bị trong mạng.
   - ICMP (Internet Control Message Protocol): Báo lỗi và gửi thông điệp kiểm tra kết nối mạng.
4. **Data Link** (Tầng dữ liệu liên kết): truyền dữ liệu qua kết nối
 - Giao thức: 
   - Ethernet: Kết nối các máy tính trong mạng LAN.
   - ARP (Address Resolution Protocol): Tìm địa chỉ MAC từ địa chỉ IP.
