# 🍰 Cake Tower - Phiên Bản Tuỳ Chỉnh Độc Lập (Custom All-in-One Edition)

Phiên bản game **Cake Tower (Thả Bánh Xếp Tháp)** được tái đóng gói và nâng cấp toàn diện thành **1 file HTML duy nhất**, tích hợp sẵn toàn bộ Engine Phaser 3, âm thanh Web Audio Live Synthesizer, font chữ Fredoka, và hình ảnh độ nét cao dưới dạng Base64 Data URI.

## 🚀 Cách Chơi Ngay Lập Tức
- Không cần cài đặt bất kỳ phần mềm nào (Node.js, Web Server, Python...).
- Mở trực tiếp file [`index.html`](./index.html) hoặc [`CakeTower_Custom.html`](./CakeTower_Custom.html) bằng bất kỳ trình duyệt web nào (Chrome, Edge, Firefox, Cốc Cốc, Safari...).
- Hoạt động **100% Offline**, dễ dàng copy 1 file duy nhất gửi sang máy khác hoặc điện thoại để chơi mượt mà.

---

## ⚙️ 3 Tính Năng Tuỳ Chọn Đặc Biệt Đã Tích Hợp

Bạn có thể nhấn vào nút **⚙️ Cài Đặt Tuỳ Chỉnh** trên màn hình chính (Title) hoặc nút bánh răng ở góc trên bên phải màn hình bất cứ lúc nào:

### 1. Cho phép các loại bánh nào được xuất hiện trong game
- Hỗ trợ đầy đủ **8 hương vị bánh đặc trưng** với hình ảnh minh hoạ trực quan:
  - 🍓 **Dâu Hồng** (Pink)
  - 🌿 **Bạc Hà** (Mint)
  - 💜 **Oải Hương** (Lavender)
  - 🍋 **Chanh Vàng** (Yellow)
  - 🍫 **Sô-cô-la** (Chocolate)
  - 🍑 **Đào Kem** (Peach)
  - 🌊 **Việt Quất** (Blue)
  - 🍦 **Vani Sữa** (Vanilla)
- Bạn có thể **bật/tắt bất kỳ loại bánh nào**, hoặc dùng nút **"Chọn hết"** / **"Ngẫu nhiên 1"** để thử thách bản thân với chỉ duy nhất 1 loại bánh yêu thích.

### 2. Tuỳ chọn tốc độ bay ngang của bánh
- **Bật / Tắt tăng tốc độ theo độ cao**:
  - Khi **BẬT**: Càng lên tầng cao, bánh bay càng nhanh (theo mô hình hàm mũ tăng dần).
  - Khi **TẮT**: Bánh giữ nguyên tốc độ ổn định từ đầu đến cuối ván chơi (thích hợp cho người mới luyện phản xạ hoặc thư giãn nhẹ nhàng).
- **Tuỳ chọn mức tốc độ ban đầu**:
  - `0.75x`: Chậm rãi, thư giãn
  - `1.0x`: Tốc độ chuẩn mực
  - `1.4x`: Tốc độ nhanh
  - `1.8x`: Siêu tốc thử thách phản xạ

### 3. Cho phép bánh giữ nguyên kích thước hoặc tự cắt phần bị thả lệch
- **✂️ Tự cắt phần bị thả lệch (Cổ Điển)**:
  - Bánh rơi xuống nếu bị lệch mép thì phần chìa ra ngoài sẽ bị cắt rơi xuống. Bánh trên tháp sẽ hẹp dần theo từng tầng. Xếp được 3 lần Perfect liên tiếp bánh sẽ nở to trở lại.
- **🛡️ Giữ nguyên kích thước 100% (Thoải Mái)**:
  - Bánh không bao giờ bị cắt xén hay thu nhỏ. Dù thả lệch nhẹ hay mạnh (miễn là còn chạm vào bề mặt tầng dưới), bánh vẫn **giữ nguyên 100% kích thước ban đầu**, giúp bạn tự tin xây tháp bánh khổng lồ mà không sợ bị teo nhỏ!

---

## 💾 Lưu Trữ Cấu Hình
- Toàn bộ cài đặt tuỳ chỉnh của bạn sẽ được tự động lưu vào trình duyệt (`localStorage`) và áp dụng cho các lần chơi kế tiếp.
- Có nút **"Khôi Phục Mặc Định"** nếu bạn muốn quay lại luật chơi nguyên bản.
