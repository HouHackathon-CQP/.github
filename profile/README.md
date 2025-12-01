<div align="center">
  <img src="assets/logo.png" alt="GreenMap Logo" width="160" />
  <h1>🌿 GreenMap Hanoi</h1>
  <h3>Đánh thức "Màu Xanh" trong lòng Hà Nội</h3>
  
  <p>
    <em>Một dự án tâm huyết kết hợp giữa Dữ liệu, AI và Cộng đồng để kiến tạo một thủ đô trong lành hơn.</em>
  </p>

  <p>
    <a href="https://github.com/HouHackathon-CQP/GreenMap-Mobile-App">
      <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-blue?style=for-the-badge&logo=android" alt="Platform" />
    </a>
    <a href="https://goo.gl/maps/hanoi">
      <img src="https://img.shields.io/badge/Location-Hanoi%2C%20Vietnam-red?style=for-the-badge&logo=google-maps" alt="Location" />
    </a>
    <img src="https://img.shields.io/badge/Status-Active%20Development-success?style=for-the-badge" alt="Status" />
  </p>
</div>

---

## 👋 Lời nói đầu: Tại sao lại là GreenMap?

Hà Nội của chúng ta rất đẹp, mang đậm nét văn hóa ngàn năm văn hiến, nhưng cũng đang phải "thở dốc".

Mỗi sáng thức dậy, câu hỏi đầu tiên của nhiều người không còn đơn thuần là "Hôm nay ăn gì?" mà là "Hôm nay bụi mịn thế nào?". Tiếng ồn, khói bụi và sự thiếu hụt những mảng xanh đang dần trở thành một phần bình thường mới đáng buồn của cuộc sống đô thị.

Chúng tôi – **HouHackathon CQP** – là những người trẻ không muốn chấp nhận thực tại đó. Chúng tôi tin rằng công nghệ sinh ra không chỉ để phục vụ giải trí hay thương mại, mà còn phải gánh vác trách nhiệm "chữa lành" môi trường sống.

**GreenMap Hanoi** ra đời với sứ mệnh:
1.  **Minh bạch hóa** dữ liệu môi trường (AQI, tiếng ồn) ngay tại nơi bạn đứng theo thời gian thực.
2.  **Định hướng** lối sống xanh thông qua việc gợi ý những con đường rợp bóng cây thay vì những nút giao kẹt cứng khói bụi.
3.  **Kết nối** sức mạnh cộng đồng, biến mỗi người dân thành một "cảm biến sống", cùng nhau báo cáo điểm nóng và bảo vệ thành phố.

---

## 🏗 Kiến trúc hệ thống: "Bộ máy" vận hành thế nào?

Để giải quyết một bài toán lớn về dữ liệu đô thị, chúng tôi chia nhỏ hệ thống thành các mảnh ghép chuyên biệt (Microservices), hoạt động nhịp nhàng với nhau như một cơ thể sống.

Dưới đây là bản đồ mã nguồn (Source Code Map) của tổ chức để bạn dễ dàng điều hướng và tham gia đóng góp:

| Repository | Vai trò & Câu chuyện công nghệ | Công nghệ lõi |
| :--- | :--- | :--- |
| **[GreenMap-Mobile-App](https://github.com/HouHackathon-CQP/GreenMap-Mobile-App)** | 📱 **Trái tim của trải nghiệm người dùng**<br>Nơi người dân tương tác hàng ngày. Chúng tôi chọn **Kotlin** (Native) để tối ưu hóa hiệu năng và trải nghiệm mượt mà nhất. App tích hợp module AI để hiển thị dự báo và tính năng Gamification khuyến khích lối sống xanh. | ![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?logo=kotlin&logoColor=white) |
| **[GreenMap-AI](https://github.com/HouHackathon-CQP/GreenMap-AI)** | 🧠 **Nhà tiên tri (Forecasting)**<br>Sử dụng các model Machine Learning (**TensorFlow/Scikit-learn**) để "học" từ dữ liệu lịch sử. Nó giúp trả lời câu hỏi: *"Ngày mai 7h sáng ở Cầu Giấy bụi hay sạch?"* để người dân chủ động lên kế hoạch bảo vệ sức khỏe. | ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white) |
| **[GreenMap-Backend](https://github.com/HouHackathon-CQP/GreenMap-Backend)** | ⚙️ **Bộ não trung tâm**<br>Được xây dựng bằng **FastAPI (Python)** vì chúng tôi cần tốc độ xử lý cao và khả năng tích hợp mạnh mẽ với dữ liệu lớn. Đây là nơi điều phối mọi luồng dữ liệu API, quản lý người dùng và lưu trữ báo cáo ô nhiễm. | ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white) |
| **[GreenMap-Frontend](https://github.com/HouHackathon-CQP/GreenMap-Frontend)** | 💻 **Đài chỉ huy (Dashboard)**<br>Giao diện quản trị trực quan dành cho Admin. Viết bằng **ReactJS**. Tại đây, dữ liệu môi trường được vẽ thành các biểu đồ, đồ thị và thống kê chi tiết giúp dễ dàng quản lý mạng lưới. | ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black) |

---

## 🚀 Những tính năng chúng tôi tâm đắc

### 1. Dành cho Người dân (The Citizen) - Người bạn đồng hành
* **🌤 Dự báo thời tiết & AQI "siêu cục bộ":** Không chỉ báo chung chung cho cả Hà Nội, AI của chúng tôi cố gắng dự báo chi tiết theo khu vực bạn sống trong 24h-48h tới. Hệ thống sẽ đưa ra lời khuyên thiết thực: *"Chiều nay nên chạy bộ công viên"* hay *"Sáng mai ra đường nhớ đeo khẩu trang N95"*.
* **🌳 Bản đồ "Lối đi xanh":** Thay vì chỉ tìm đường ngắn nhất, GreenMap gợi ý lộ trình "trong lành" nhất: có chỉ số AQI thấp, nhiều cây xanh che phủ, hoặc đi qua các trạm sạc xe điện và điểm "nghỉ mát".
* **📢 Mạng xã hội môi trường:** Thấy một bãi rác tự phát? Một cống nước đen ngòm? Chụp ảnh và báo cáo ngay trên app (Report). Cộng đồng sẽ biết để tránh, và cơ quan chức năng sẽ có dữ liệu để xử lý.
* **🏆 Gamification - Sống xanh cũng cần vui:** Mỗi bước chân đi bộ, mỗi lần đi xe đạp thay vì xe máy, bạn đều được tích điểm. Điểm này dùng để đổi quà hoặc thăng hạng "Hiệp sĩ xanh" trên bảng xếp hạng người dùng.

### 2. Dành cho Quản trị (The Admin) - Cái nhìn toàn cảnh
* **Dashboard thời gian thực:** Giám sát "sức khỏe" của hệ thống cảm biến, lưu lượng truy cập và trạng thái server.
* **Kiểm duyệt nội dung:** Công cụ xác thực các báo cáo từ người dân để đảm bảo dữ liệu trên bản đồ là chính xác và văn minh (loại bỏ spam/fake news).
* **Phân tích dữ liệu:** Xuất các báo cáo xu hướng ô nhiễm theo tháng/quý để phục vụ nghiên cứu hoặc gửi tới các cơ quan chức năng.

---

## 🗺 Tương lai chúng tôi hướng đến (Roadmap)

Dự án này không dừng lại ở khuôn khổ một cuộc thi hay một bài tập lớn. Chúng tôi mơ lớn hơn cho cộng đồng:

1.  **Open API Initiative:** Mở cổng kết nối dữ liệu miễn phí. Các startup khác, sinh viên nghiên cứu khoa học có thể dùng dữ liệu sạch của GreenMap để phát triển ứng dụng của riêng họ.
2.  **IoT Everywhere:** Kết nối với các thiết bị cảm biến vật lý giá rẻ (Arduino/ESP32) do chính cộng đồng lắp đặt tại ban công nhà họ, tạo nên mạng lưới giám sát dày đặc đến từng ngõ ngách (Crowdsourcing Data).
3.  **Vươn xa hơn:** Mang mô hình GreenMap đến Đà Nẵng, TP.HCM và Huế - những thành phố cũng đang khao khát giữ gìn màu xanh du lịch và sức khỏe người dân.

---

## 🤝 Đội ngũ phát triển

Chúng tôi là những sinh viên công nghệ, code bằng đam mê và mang trong mình tình yêu lớn với Hà Nội.

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Quan03082004">
        <img src="https://avatars.githubusercontent.com/u/125746822?v=4" width="120px;" style="border-radius: 50%"/><br>
        <sub><b>Trần Anh Quân</b></sub>
      </a><br>
      <small><i>Mobile Lead & AI Engineer</i></small>
    </td>
    <td align="center">
      <a href="https://github.com/ChienTran16">
        <img src="https://avatars.githubusercontent.com/u/168514215?v=4" width="120px;" style="border-radius: 50%"/><br>
        <sub><b>Trần Trọng Chiến</b></sub>
      </a><br>
      <small><i>Backend Specialist & System Architect</i></small>
    </td>
    <td align="center">
      <a href="https://github.com/haphuong21">
        <img src="https://avatars.githubusercontent.com/u/100331812?v=4" width="120px;" style="border-radius: 50%"/><br>
        <sub><b>Nguyễn Hà Phương</b></sub>
      </a><br>
      <small><i>Frontend Developer & Data Viz</i></small>
    </td>
  </tr>
</table>

---

## 💌 Lời mời hợp tác (Contribution)

GreenMap là một dự án **Mã nguồn mở (Open Source)** và hướng tới **Dữ liệu mở (Open Data)**. Chúng tôi không thể làm điều này một mình.

Nếu bạn là:
* **Mobile Dev:** Hãy giúp chúng tôi tối ưu hiệu năng App Kotlin, làm cho nó mượt mà hơn trên các dòng máy phổ thông.
* **Data Scientist:** Model AI của chúng tôi cần thông minh hơn. Nếu bạn có ý tưởng về thuật toán dự báo mới, hãy Pull Request!
* **Cơ quan/Tổ chức:** Nếu bạn có dữ liệu quan trắc (Sở TNMT, WHO, AirVisual...), hãy chia sẻ API để chúng tôi tích hợp.

Đừng ngần ngại mở một **Issue** để góp ý hoặc gửi **Pull Request**. Mỗi dòng code của bạn đều góp phần làm không khí Hà Nội trong lành hơn.

*Vui lòng đọc kỹ file `CONTRIBUTING.md` trong từng repository con để bắt đầu nhé!*

---
<div align="center">
  <h3>Code for Hanoi. Code for Life. 🌿</h3>
  <sub>© 2024 GreenMap Hanoi Project. Made with ❤️ and lots of ☕ in Hanoi.</sub>
</div>
