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
