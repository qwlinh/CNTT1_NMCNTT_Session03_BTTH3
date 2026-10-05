## Bài 3 : Thiết kế hệ thống IoT thông minh và quản lý cấu hình

---
MÔ TẢ KIẾN TRÚC 4 TẦNG DIKW - TRANG TRẠI LAN THÔNG MINH Plaintext


[ Wisdom ]  ---> Tối ưu hóa lượng nước tưới dựa trên dự báo thời tiết dài hạn
     
     
   ↑


[Knowledge] ---> Tự động kích hoạt bật máy bơm khi nhiệt độ > 35°C
  
     
   ↑


[Information] -> Cảnh báo, thông báo tình trạng vườn gửi đến chủ vườn
  
     
   ↑


[   Data    ] ---> Dữ liệu cảm biến thô (độ ẩm đất, nhiệt độ không khí)

1. Tầng Data (Dữ liệu thô): Các cảm biến IoT đặt quanh trang trại thực hiện đo đạc liên tục và thu thập các giá trị số học nguyên thủy chưa qua xử lý logic.


2. Tầng Information (Thông tin): Hệ thống thu nhận dữ liệu thô từ tầng Data, tiến hành gán ngữ cảnh, tổng hợp và hiển thị trực quan lên giao diện hoặc gửi thông báo cảnh báo đến thiết bị của chủ vườn.


3. Tầng Knowledge (Tri thức): Hệ thống vận dụng các quy tắc, thuật toán hoặc kịch bản điều khiển đã được lập trình sẵn dựa trên thông tin thu nhận được để đưa ra hành động tự động xử lý tình huống ngay lập tức.


4. Tầng Wisdom (Sự khôn ngoan): Cấp độ cao nhất của hệ thống, thực hiện phân tích xu hướng dài hạn, tích hợp thêm các nguồn dữ liệu bên ngoài (như dữ liệu dự báo thời tiết từ API khí tượng) để đưa ra các quyết định chiến lược tối ưu hóa toàn diện tài nguyên.
