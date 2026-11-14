# MultiTVOS — Ứng Dụng Truyền Hình Đa Màn Hình Cho Apple TV (tvOS)

**MultiTVOS v1.2.1** là trung tâm truyền hình & thể thao đa màn hình dành cho **Apple TV 4K / HD (tvOS 17.0+)**, kết hợp 3 module truyền hình độc lập cùng khả năng phát song song **2 luồng cùng lúc** trên một màn hình TV (đã khóa chống nháy đen HDMI khi đổi kênh / đa màn hình).

---

## ✨ Tính Năng Nổi Bật

1. **Chế Độ Đa Màn Hình Linh Hoạt (`1 Màn` & `Màn 1+2`)**
   - **1 Màn Hình (100% Fullscreen):** Xem trọn vẹn một ứng dụng hoặc một kênh truyền hình toàn màn hình.
   - **50 / 50 (Side-by-Side):** Chia đôi hai khung hình ngang nhau để theo dõi đồng thời 2 trận cầu hoặc 2 kênh tin tức.
   - **75 / 25 (Chính + Phụ):** Khung hình chính lớn kèm khung hình phụ góc phải.
   - **PiP Nổi 4 Góc:** Toàn màn hình chính kết hợp khung hình phụ thu gọn xoay linh hoạt 4 góc, tự động chuyển âm thanh theo khung hình đang chọn (Smart Audio Focus).

2. **3 Module Tích Hợp Sẵn**
   - **FPT Play (FTVOS):** Đăng nhập OTP tài khoản cá nhân, xem trực tiếp Thể thao, Ngoại Hạng Anh 4K UHD 50fps, Truyền hình VTV/HTV/Địa phương & Kho Phim VOD (Hỗ trợ Apple FairPlay phần cứng).
   - **Viettel TV360:** Đăng nhập nhanh qua Mã QR / Mã 6 số / Số điện thoại, xem 180+ kênh truyền hình, sự kiện TV360+ Thể thao, Cúp Châu Âu & Phim bộ VIP.
   - **IPTV (Giao diện chuẩn iSTB 3 Cột):**
     - Lưu trữ độc lập **3 cấu hình M3U / M3U8 / UDP** và **3 cổng Stalker Portal (MAC Address)** để chuyển đổi tức thì chỉ bằng 1 chạm.
     - Tích hợp bộ giải mã kép **AVPlayer Hardware + KSPlayer (FFmpeg + VideoToolbox)**.
     - Tự động thu luồng **UDP / RTP Multicast** trực tiếp trên mạng LAN, hỗ trợ cấu hình **UDPXY Router Proxy** tùy chọn, và tự động chuyển đổi dự phòng sang luồng **HLS Quốc tế & Việt Nam đa CDN** (CNN, BBC News, Bloomberg, HBO, Cinemax, Warner TV, AXN, Discovery, Cartoon Network, VTV, HTV, THVL...) không cần đăng nhập.

---

## 📥 Tải Về & Cài Đặt (`.ipa` Cho Apple TV)

- **Bản phát hành mới nhất (GitHub Releases):**
  `https://github.com/hongson117/MultiTVOS/releases/latest/download/MultiTVOS.ipa`
- **Link trực tiếp nhánh `Multitvos`:**
  `https://github.com/hongson117/MultiTVOS/raw/Multitvos/MultiTVOS.ipa`

### Hướng dẫn cài đặt nhanh
- **Qua 4AppleTV / LiveContainerTV (Khuyên dùng trên iPhone/iPad & Apple TV):** Dán trực tiếp một trong hai đường dẫn `.ipa` ở trên vào mục Cài đặt URL để ký và cài không dây lên Apple TV.
- **Qua Sideloadly / Feather / AltStore:** Tải tệp `MultiTVOS.ipa` về máy và ký bằng Apple ID cá nhân hoặc chứng chỉ Developer cho Apple TV (`tvOS arm64`).

---

## 📄 Thông Tin Phiên Bản
- **Phiên bản:** `1.2.1` (Build `2`)
- **Nền tảng:** `tvOS 17.0+` (`arm64` — Apple TV HD / Apple TV 4K Gen 1, 2, 3)
- **Phân phối:** Chỉ phát hành gói cài đặt `.ipa` đã đóng gói sẵn trên nhánh `Multitvos`.
