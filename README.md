# 3D CYBER-NEON CONTINUOUS DIGITAL SCENOGRAPHY — "TÔI TRƯỞNG THÀNH" (LỚP 12A2)

> **Trải Nghiệm Thị Giác Sân Khấu Liền Mạch (Continuous Cinematic Scenography)**  
> Dành cho toàn thể Thầy Cô và Học sinh toàn trường theo dõi trên Màn hình LED 4K từ khoảng cách **30 – 50 mét**.  
> 🌐 **Website Trực Tuyến (Live Demo):** [https://phamducvinh106.github.io/toi-truong-thanh-12a2/](https://phamducvinh106.github.io/toi-truong-thanh-12a2/)

---

## 💎 CÁC NÂNG CẤP ĐỘT PHÁ TRIỆT TIÊU SỰ RỜI RẠC

1. **Xóa Bỏ 100% MC Clue & Tinh Gọn HUD Đáy Tuyệt Đối:**
   - Xóa bỏ hoàn toàn các nút bấm điều khiển vụn vặt và text đếm slide ở thanh đáy. Thanh HUD bên dưới giờ đây **chỉ hiển thị duy nhất Đồng hồ thời gian thực (HH:MM:SS) và Thanh tiến độ Laser**, đem lại màn hình LED 100% tinh khiết, đẳng cấp chuẩn sân khấu sự kiện lớn.
   - Toàn bộ thao tác vận hành được chuyển hóa thành **hệ thống phím tắt chuyên nghiệp (Keyboard-First)**, tương thích hoàn hảo với Remote Clicker trình chiếu.

2. **Trục Năng Lượng 3D Xuyên Suốt (Continuous Energy Spine):**
   - Một dải tơ laser 3D (`continuousEnergySpine`) uốn lượn liên tục qua toàn bộ 17 slide, biến không gian thành một vũ trụ liền mạch duy nhất thay vì 17 trang web chắp vá.
   - Sợi dây năng lượng đổi màu đa sắc theo từng slide và thở theo nhịp hữu cơ phi tuyến.

3. **Bẻ Cong Không-Thời Gian khi Chuyển Cảnh (Hyperdrive Warp Speed):**
   - Khi bấm chuyển slide:
     * Góc nhìn Camera (**FOV**) đột ngột phóng giãn từ `50°` lên `82°` tạo gia tốc phi thuyền không gian cực đại.
     * Vệt lóe sáng lượng tử (**Warp Flash**) bùng nổ ở tâm màn hình.
     * Vật thể cũ thu nhỏ lùi sâu vào vũ trụ, vật thể mới bay vút từ chiều không gian siêu tốc ra tiền cảnh.

4. **Khóa Tọa Độ Không Gian 3D Cho Chữ (Spatial 3D Tilt Fusion):**
   - Typography không còn phẳng: Chữ được đồng bộ trực tiếp với góc nghiêng `rotateX` và `rotateY` của camera 3D (`--cam-tilt-x`, `--cam-tilt-y`), tạo cảm giác các khối chữ đứng sừng sững giữa không gian 3 chiều.

5. **Khung Kính Mờ Quang Học Duy Nhất (Single Frosted Glass Backdrop Monolith):**
   - Một khối kính cường lực mờ nguyên khối duy nhất bao quanh toàn bộ nội dung, giải quyết triệt để vấn đề chữ bị lẫn vào phông nền 3D động.
   - 4 góc vát hình bát giác công nghệ cao (`clip-path` đa giác 8 cạnh), ngàm quang học phát sáng đổi màu theo neon của từng slide.
   - Tùy chỉnh độ mờ đục / trong suốt (`glass_alpha`) linh hoạt trực tiếp trong `content.txt`.

6. **Âm Thanh Nền Ngoài (External BGM Audio Engine) & Triệt Tiếng Ồn Synth Drone:**
   - Tắt hoàn toàn tiếng u u synth nhân tạo gây ồn (`synth_drone_enabled = false`, `synth_drone_volume = 0.0`).
   - Tự động nạp file nhạc nền ngoài nhẹ nhàng, ấm áp chỉ định qua `bgm_file` (ví dụ `bgm.mp3`).
   - Hỗ trợ **kéo thả trực tiếp file âm thanh (.mp3, .wav, .ogg, .m4a)** vào màn hình trình chiếu để phát ngay lập tức.
   - Hòa quyện cùng tiếng **Sub-bass Drop 30Hz** và **Laser Lock-on** khi tương tác Minigame.

7. **Trình Phát Nhạc & Video Tương Tác Sân Khấu (Cyber Music & Native Aspect Video Players):**
   - **Nút Play Tam Giác Neon (▶):** Tích hợp nút tam giác phát sáng chuyển động nhịp nhàng tại các slide tiết mục:
     * **Slide 02:** Tiết mục Hát *Hò Vươn Mình*
     * **Slide 05:** Tiểu phẩm kịch *Tôi Của Ngày Hôm Qua*
     * **Slide 16:** Tiết mục Hát bế mạc *Rực Rỡ*
   - **Phần mềm nghe nhạc Cyber:** Khi click nút Play ở Slide 02 hoặc Slide 16, toàn bộ giao diện chuyển thành giao diện phần mềm nghe nhạc tương lai với:
     * Đĩa than Hologram Holographic Vinyl Disc xoay tròn mượt mà khi phát nhạc.
     * Cột sóng âm tần số động (Cyber Equalizer Visualizer Bars).
     * Bảng điều khiển đầy đủ: Nút Play/Pause, thanh tua bài (timeline scrubber rail), tua nhanh/lùi 10 giây (`-10s` / `+10s`), thanh kéo âm lượng.
   - **Trình phát Video Tràn Viền Chuẩn Tỉ Lệ (Slide 05):**
     * Phát video tràn viền kích thước cực đại (`min(96vw, 1750px)` × `min(88vh, 880px)`).
     * **Bảo toàn 100% tỉ lệ khung hình gốc của video (`object-fit: contain`)**, tuyệt đối không bị méo hình (letterbox viền đen điện ảnh tự nhiên theo chuẩn 16:9, 4:3, 21:9).
     * Hỗ trợ nút phóng to toàn màn hình (Fullscreen), tua $\pm 10\text{s}$, âm lượng, thanh tiến độ.
   - **Cơ chế nạp file tinh gọn & bảo mật sân khấu ("file được load sau"):**
     * Giao diện player tinh khiết chuẩn sân khấu, triệt tiêu hoàn toàn nút chọn file và dòng trạng thái kỹ thuật "đã nạp file" trên màn hình.
     * Khai báo trước đường dẫn file trong `content.txt` (`music_file` / `video_file`).
     * Hoặc **kéo thả trực tiếp file audio (.mp3, .wav, .ogg, .m4a) hoặc video (.mp4, .webm, .mov, .mkv)** vào thẳng slide để phát ngay!
   - **Logic ngắt âm thông minh (Audio Ducking):**
     * Tự động tạm dừng nhạc nền BGM khi mở trình phát nhạc/video để không bị lẫn tiếng.
     * Tự động bật lại nhạc nền BGM khi đóng trình phát hoặc chuyển slide.

8. **Độc Lập Ngoại Tuyến Hoàn Toàn 100% (Air-Gapped Offline Independence):**
   - **Tự chủ thư viện cốt lõi:** Thư mục `lib/` lưu trữ cục bộ toàn bộ thư viện Three.js r128 (`lib/three.min.js`) và GSAP 3.12 (`lib/gsap.min.js`), triệt tiêu 100% rủi ro mất mạng Internet tại hội trường.
   - **Không phụ thuộc font từ xa:** Typography sử dụng trực tiếp font hệ thống cao cấp (`SF Pro Display`, `Segoe UI`, `Roboto`), hiển thị sắc nét tức thì mà không cần mạng.
   - **Cơ chế dự phòng kép (Failsafe CDN Fallback):** Nếu file cục bộ bị di chuyển, trang web tự động chuyển hướng nạp từ CDN đám mây.
   - **Đóng gói USB tiện lợi:** Bạn có thể copy toàn bộ thư mục dự án ra USB, cắm vào bất kỳ máy tính nào của trường và chạy ngay lập tức mà không cần kết nối Wi-Fi hay Internet!

---

## 🎮 HỆ THỐNG PHÍM TẮT ĐIỀU KHIỂN SÂN KHẤU (KEYBOARD-FIRST)

| Phím Tắt | Thao Tác / Thiết Bị Tương Thích | Chức Năng Chi Tiết |
| :--- | :--- | :--- |
| **`Space`** / **`➔`** / **`🠗`** / **`Enter`** | Nút **Tiến** trên Bàn phím & **Clicker** | Chuyển sang Slide tiếp theo (khi Player đang mở: `Space` sẽ Play / Pause nhạc/video) |
| **`PageDown`** | Nút **Next** tiêu chuẩn trên Chuột trình chiếu | Tương thích hoàn hảo mọi loại Clicker sự kiện |
| **`🠔`** / **`🠕`** / **`Backspace`** | Nút **Lùi** trên Bàn phím | Quay lại Slide liền trước (khi Player đang mở: `🠔` lùi 10s, `➔` tiến 10s) |
| **`PageUp`** | Nút **Prev** tiêu chuẩn trên Chuột trình chiếu | Lùi slide tức thì từ xa |
| **`Escape`** | Phím **Thoát** | Đóng ngay lập tức Trình phát nhạc/video, bảng danh mục hoặc bảng phím tắt |
| **`F`** / **`F11`** | Phím **Fullscreen** | Bật / Tắt chế độ **Toàn Màn Hình LED** (hoặc toàn màn hình video khi đang xem kịch) |
| **`M`** | Phím **Mute / Audio** | Bật / Tắt dải âm thanh nền Ambient Drone & FX |
| **`O`** / **`G`** / **`Tab`** | Phím **Overview / Grid** | Bật / Tắt danh mục lưới 17 phân cảnh sân khấu |
| **`H`** hoặc **`?`** | Phím **Help** | Bật / Tắt **Bảng tra cứu phím tắt** trực tiếp trên màn hình |
| **`T`** | Phím **Text Source** | Mở hộp thoại chọn file `content.txt` để nạp lại |
| **Kéo thả chuột** | Thả file `content.txt`, audio hoặc video | Thả trực tiếp vào màn hình để nạp văn bản, nhạc nền, bài hát hoặc video tiểu phẩm tức thì |
| **`A` `B` `C` `D`** hoặc **`1` `2` `3` `4`** | Phím chọn đáp án Minigame | Khóa mục tiêu tương tác Minigame Đúng / Sai (Slide 8 – 13) |
| **`Home`** / **`End`** | Phím nhảy nhanh | Về ngay Cảnh 01 (Khai màn) / Tới Cảnh 17 (Bế mạc) |

---

## 📄 QUẢN LÝ VĂN BẢN & CẤU HÌNH 3D / KÍNH MỜ / NHẠC NỀN (`content.txt`)

Toàn bộ câu chữ, tiêu đề, câu hỏi, 4 phương án trắc nghiệm, thông điệp triết lý, **cấu hình độ nghiêng 3D**, **khung kính mờ** và **nhạc nền ngoài** đều được quản lý tập trung trong:
- **Tệp nguồn:** [`content.txt`](file:///c:/Users/phamd/OneDrive/Documents/.Tr%C3%ACnh%20chi%E1%BA%BFu/content.txt)
- **Tùy chỉnh trong mục `[SETTINGS]` (Mở bằng Notepad để sửa):**
  * **Âm thanh nền ngoài (External BGM & Synth Drone Control):**
    - `bgm_file`: Tên file hoặc đường dẫn nhạc nền ngoài (ví dụ: `bgm.mp3`, `audio/ambient.mp3`). Bạn chỉ cần để file mp3 vào cùng thư mục với `index.html`. Ngoài ra, bạn cũng có thể **kéo thả trực tiếp file nhạc (.mp3, .wav, .ogg, .m4a) vào màn hình trình diễn** để phát ngay lập tức!
    - `bgm_volume`: Âm lượng nhạc nền (`0.0` đến `1.0`, mặc định `0.35` êm dịu, dễ chịu).
    - `bgm_loop`: `true` (lặp lại liên tục) / `false` (phát 1 lần).
    - `synth_drone_enabled`: `false` (đã tắt tiếng u u synth nhân tạo để triệt tiêu tiếng ồn) / `true`.
    - `synth_drone_volume`: Âm lượng tiếng synth nhân tạo (mặc định `0.0`).
  * **Độ nghiêng 3D (Spatial Tilting):**
    - `tilt_max_deg`: Góc nghiêng tối đa (độ, mặc định `12`, có thể tăng giảm tùy ý).
    - `tilt_multiplier`: Hệ số nhạy theo camera Three.js (mặc định `20`).
    - `perspective_px`: Tiêu cự phối cảnh (mặc định `1700`, càng nhỏ hiệu ứng 3D càng sâu).
    - Đặt góc nghiêng riêng cho từng slide bằng `tilt_x` và `tilt_y` trong từng `[SLIDE_X]`.
  * **Khung kính mờ duy nhất (Single Frosted Glass Backdrop):**
    - `glass_enabled`: `true` (bật khung kính) / `false` (tắt).
    - `glass_alpha`: Độ mờ đục / trong suốt của kính (`0.0` = trong suốt tuyệt đối, `1.0` = đục đặc). Mặc định `0.25` (khuyến nghị `0.15` - `0.35` để nhìn xuyên thấu hậu cảnh 3D lấp lánh phía sau mà chữ vẫn sắc nét).
    - `glass_blur_px`: Độ mờ nhòe khúc xạ của kính (`14px`, khuyến nghị 8 - 20 để tạo độ nhòe kính mờ thanh thoát).
    - `glass_border_glow`: Độ sáng viền quang học (`0.30`, khuyến nghị 0.20 - 0.50).
    - `glass_width_vw`: Chiều rộng khung kính (% màn hình, mặc định `94`).
    - `glass_height_vh`: Chiều cao khung kính (% màn hình, mặc định `82`).
  * **Đường dẫn tệp biểu diễn (Performance Media Paths):**
    - `[SLIDE_2]` -> `music_file = audio/ho_vuon_minh.mp3`: Tệp bài hát cho tiết mục Hò Vươn Mình.
    - `[SLIDE_5]` -> `video_file = video/tieu_pham.mp4`: Tệp video tiểu phẩm kịch "Tôi Của Ngày Hôm Qua".
    - `[SLIDE_16]` -> `music_file = audio/ruc_ro.mp3`: Tệp bài hát bế mạc "Rực Rỡ".
    - *Lưu ý:* File phương tiện được nạp tự động thông qua `content.txt` hoặc kéo thả file trực tiếp vào màn hình. Giao diện trình phát đã được tinh gọn sạch sẽ, loại bỏ nút chọn file và chữ trạng thái để tối ưu tuyệt đối cho hiển thị sân khấu.
- **Cách chỉnh sửa:** 
  1. Mở file `content.txt` bằng **Notepad** (hoặc bất kỳ trình soạn thảo nào).
  2. Chỉnh sửa câu từ hoặc các thông số trong `[SETTINGS]` hoặc bên dưới từng slide.
  3. Lưu file (`Ctrl + S`).
  4. Nếu chạy qua web server: Trình chiếu tự động nạp lại.
  5. Nếu mở trực tiếp dạng `file://`: Nhấn phím **`T`** hoặc **kéo thả file `content.txt`** vào màn hình trình chiếu để cập nhật tức thì.

---

## 🚀 KHỞI CHẠY TRÊN MÁY TÍNH HỘI TRƯỜNG

- Mở trực tiếp file `index.html` bằng **Google Chrome**, **Microsoft Edge**, hoặc **Apple Safari**.
- Nhấn phím **`F`** để vào chế độ toàn màn hình không viền cho màn LED sân khấu.
- Nhấn **`H`** hoặc **`?`** bất kỳ lúc nào để xem nhanh bảng phím tắt.
