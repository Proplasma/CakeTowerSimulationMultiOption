# Cake Tower - Custom Edition (All-in-One Standalone)

> **Source Code Reference:** [https://github.com/GianneAngely/cake-tower](https://github.com/GianneAngely/cake-tower) by Gianne Angely.

An enhanced, fully self-contained single-file edition of **Cake Tower**, featuring live Web Audio synthesis, embedded Fredoka typography, high-resolution Base64 textures, and customized gameplay rules.


## Key Enhancements

- **30% Smaller Cake Proportions**:
  The default cake tier width has been scaled down by 30% (`TIER_W = 280px` instead of `400px`). This provides significantly more vertical and horizontal screen headroom, creating a delicate, aesthetically pleasing pastry aesthetic and making it much more fun to build gigantic sky-high towers.

- **100% Offline & Zero Setup**:
  Packaged entirely into a single HTML file (~3.8 MB). Double-click [`index.html`](./index.html) or [`CakeTower_Custom.html`](./CakeTower_Custom.html) to play immediately in Chrome, Edge, Firefox, Safari, or mobile browsers without web servers or Node.js.


## Core Custom Gameplay Options

Access the in-game settings modal at any time via the **Settings (Gear Icon)** button:

1. **Selectable Cake Flavors**:
   Choose which of the 8 cake tiers appear during gameplay:
   - Pink (Strawberry)
   - Mint (Peppermint)
   - Lavender (Floral)
   - Yellow (Lemon)
   - Chocolate (Cocoa)
   - Peach (Cream)
   - Blue (Blueberry)
   - Vanilla (Custard)
   Includes "Select All" and "Pick 1 Random" quick-select buttons.

2. **Horizontal Flight Speed Options**:
   - Progressive Speed Increase: Toggle ON to make cakes fly faster as the tower rises, or toggle OFF to maintain a steady, relaxed speed from the bottom to the moon.
   - Base Speed Presets: Choose between 0.75x (Relaxed), 1.0x (Standard), 1.4x (Fast), or 1.8x (Hyper Speed).

3. **Overhang Trim & Sizing Mode**:
   - Automatic Trim (Classic): Any portion hanging over the edge is sliced off and falls away. The tower narrows as you climb, rewarding consecutive Perfect streaks.
   - 100% Fixed Width Mode: Cakes never shrink or get sliced. Land anywhere overlapping the previous tier and keep your full cake width for maximum tower-building comfort.

4. **Custom Spawn Height (Elevation Offset)**:
   - Configure how high new cakes fly above the current tower top:
   - Slider & quick presets: 0.25x (Very Low / Near Top), 0.40x (Low), 0.55x (Standard Default), 0.85x (High), 1.25x (Very High / Distant).

5. **Balloon Cake Toggle**:
   Toggle swinging pendulum balloon cakes (appearing from tier 40+) on or off.

6. **Persistent Preferences**:
   All customized settings are automatically saved to `localStorage` for future sessions.


---


# Cake Tower - Phiên Bản Tuỳ Chỉnh Độc Lập (Đóng Gói Một Tệp Duy Nhất)

> **Tham khảo mã nguồn từ:** [https://github.com/GianneAngely/cake-tower](https://github.com/GianneAngely/cake-tower) của tác giả Gianne Angely.

Phiên bản nâng cấp và đóng gói toàn diện của trò chơi **Cake Tower (Thả Bánh Xếp Tháp)** trong một tệp HTML duy nhất, tích hợp sẵn engine đồ hoạ Phaser 3, bộ tổng hợp âm thanh Web Audio Live Synthesizer, font chữ Fredoka, và toàn bộ texture đồ hoạ độ phân giải cao dưới dạng Base64 Data URI.


## Các Điểm Nâng Cấp Đáng Chú Ý

- **Kích Thước Bánh Nhỏ Hơn 30%**:
  Độ rộng bánh đã được điều chỉnh thu nhỏ 30% so với bản gốc (`TIER_W = 280px` thay vì `400px`). Điều này giúp góc nhìn tổng thể thoáng đãng hơn, bánh nhìn nhỏ nhắn, tinh tế và tạo không gian rộng rãi để bạn thoải mái xây tháp bánh cao vút lên tận trời xanh.

- **Chạy Hoàn Toàn Offline & Tiện Lợi**:
  Toàn bộ game được gói gọn trong 1 file HTML duy nhất (~3.8 MB). Mở trực tiếp [`index.html`](./index.html) hoặc [`CakeTower_Custom.html`](./CakeTower_Custom.html) trên bất kỳ trình duyệt web nào (Chrome, Edge, Cốc Cốc, Safari...) mà không cần cài đặt phần mềm phụ trợ hay kết nối internet.


## 3 Tính Năng Tuỳ Chọn Trọng Tâm

Bạn có thể mở bảng cài đặt bất kỳ lúc nào bằng nút **Cài Đặt Tuỳ Chỉnh (Biểu tượng bánh răng ⚙️)**:

1. **Tuỳ Chọn Các Loại Bánh Xuất Hiện**:
   Cho phép bật/tắt tự do bất kỳ loại bánh nào trong số 8 hương vị:
   - Dâu Hồng (Pink)
   - Bạc Hà (Mint)
   - Oải Hương (Lavender)
   - Chanh Vàng (Yellow)
   - Sô-cô-la (Chocolate)
   - Đào Kem (Peach)
   - Việt Quất (Blue)
   - Vani Sữa (Vanilla)
   Có nút "Chọn hết" và "Ngẫu nhiên 1" nếu bạn muốn thử thách bản thân với chỉ 1 loại bánh duy nhất.

2. **Tuỳ Chọn Tốc Độ Bay Ngang**:
   - Tốc độ tăng dần theo độ cao: Bật để bánh bay nhanh dần khi lên cao, hoặc Tắt để giữ nguyên tốc độ ổn định từ đầu đến cuối ván chơi (thích hợp cho luyện phản xạ hoặc thư giãn nhẹ nhàng).
   - Mức tốc độ ban đầu: Cho phép chọn giữa các mức 0.75x (Chậm), 1.0x (Chuẩn), 1.4x (Nhanh), hoặc 1.8x (Siêu tốc).

3. **Quy Cách Cắt Gọt Khi Thả Lệch**:
   - Tự cắt phần bị thả lệch (Cổ điển): Phần bánh thừa ngoài mép sẽ bị xén đứt rơi rụng. Bánh trên đỉnh tháp hẹp dần theo từng tầng (nếu đạt chuỗi Perfect 3 lần liên tiếp bánh sẽ nở to trở lại).
   - Giữ nguyên kích thước 100% (Thoải mái): Bánh không bao giờ bị cắt xén hay thu nhỏ; luôn giữ nguyên kích thước ban đầu giúp bạn thoải mái xây tháp bánh khổng lồ.

4. **Tuỳ Chỉnh Vị Trí / Độ Cao Xuất Hiện Của Bánh Mới**:
   - Tự do tinh chỉnh khoảng cách bánh bay ngang cao lên hoặc thấp xuống so với đỉnh tháp bánh hiện tại.
   - Hỗ trợ thanh trượt linh hoạt kèm các nút bấm nhanh: 0.25x (Rất thấp / Sát đỉnh tháp), 0.40x (Thấp), 0.55x (Chuẩn gốc), 0.85x (Cao), hoặc 1.25x (Rất cao).

5. **Bóng Bay Đung Đưa**:
   Có thể bật hoặc tắt tính năng bánh treo khinh khí cầu đung đưa xuất hiện từ tầng 40 trở lên.

6. **Tự Động Lưu Cấu Hình**:
   Toàn bộ cấu hình cài đặt sẽ tự động lưu vào `localStorage` của trình duyệt và áp dụng cho các lần chơi tiếp theo.
