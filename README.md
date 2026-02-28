<div align="center">
  <img src="https://img.upanh.tv/2025/05/22/Screenshot-2025-05-22-154810b90ede21fb12bd34.png" alt="Dino Tool Banner" width="600"/>

  <h1>🦖 Dino Tool - Locket Spammer 🦖</h1>

  <p><strong>Công cụ tăng tương tác & kết bạn ảo cho Locket cực mạnh mẽ</strong></p>

  <p>
    <a href="https://python.org"><img src="https://img.shields.io/badge/Python-3.12+-blue.svg?logo=python&logoColor=white" alt="Python Version"/></a>
    <a href="https://t.me/dinostore01"><img src="https://img.shields.io/badge/Telegram-Hỗ_Trợ-blue.svg?logo=telegram&logoColor=white" alt="Telegram Support"/></a>
    <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License"/>
    <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg" alt="Platform"/>
  </p>
</div>

<hr />

## 🌟 Giới Thiệu

**Dino Tool** là công cụ tối ưu giúp bạn tăng số lượng bạn bè / người theo dõi ảo hàng loạt trên nền tảng mạng xã hội Locket. Bằng cách tự động khởi tạo các tài khoản rác (Ghost Accounts) siêu tốc và gửi yêu cầu kết bạn đến UID Locket được chỉ định, tool giúp bạn kéo tương tác hoặc *warm-up* tài khoản nhanh chóng.

> [!WARNING]
> Việc gửi quá nhiều yêu cầu kết bạn cùng lúc có thể gây ra hiện tượng **Overload (quá tải) thông báo** và làm crash ứng dụng trên thiết bị mục tiêu. Hãy sử dụng có chừng mực!

---

## ✨ Tính Năng Nổi Bật

- 🚀 **Tốc độ siêu nhanh:** Tích hợp đa luồng (Multi-threading) hỗ trợ tạo hàng ngàn request mỗi phút.
- 🛡️ **Bypass xịn sò:** Tích hợp giả mạo Analytics, Bypass Firebase AppCheck mới nhất.
- 🔗 **Tự động xử lý URL:** Xử lý và tự sửa các link Locket (redirects, short link) thông minh.
- 🔁 **Xoay Proxy tự động:** Tool tự động lấy hàng ngàn Proxy Live miễn phí trên mạng để tránh bị Block IP.
- 🧹 **Tính năng tiện ích đi kèm:** Không chỉ Spam kết bạn, tool còn hỗ trợ "Xoá Yêu Cầu Kết Bạn" cực mạnh để làm sạch tài khoản.

---

## 💻 Hướng Dẫn Cài Đặt (PC/Windows)

### 1️⃣ Yêu Cầu Hệ Thống

- [Tải và cài đặt Python 3.12+ tại đây](https://www.python.org/downloads/) *(Khi cài đặt nhớ tích vào ô **"Add Python to PATH"**)*.

### 2️⃣ Cài Đặt Thư Viện

Mở Terminal/CMD ở thư mục chứa tool và chạy lệnh sau để cài đặt môi trường:

```bash
pip install -r requirements.txt
```

*(Nếu cài thủ công: `pip install requests tqdm colorama pystyle urllib3`)*

### 3️⃣ Cấu Hình Token (Quan Trọng)

Dino Tool yêu cầu **Firebase AppCheck Token** thực để qua mặt lớp bảo mật của Locket.

1. Dùng ứng dụng bắt gói tin (Stream trên iOS hoặc HTTPCanary, PC dùng Burp Suite).
2. Bật VPN phần mềm bắt gói tin -> Mở App Locket.
3. Trong app bắt gói tin, tìm các gói tin POST gửi tới `api.locketcamera.com`.
4. Tìm trong phần **Request Headers** dòng `x-firebase-appcheck`.
5. Copy toàn bộ đoạn mã đằng sau (bắt đầu bằng `eyJ...`).
6. Dán mã token vừa lấy vào file `token.txt` cùng thư mục với tool. *(Nếu chưa có file hãy tự tạo file mới).*

### 4️⃣ Khởi Chạy Tool

Mở file `start.bat` (nhấp đúp chuột) hoặc chạy lệnh sau trong Terminal:

```bash
python dino-tool.py
```

---

## 🍏 Hướng Dẫn Chạy Trên Cloud Shell (Sài qua Web/Điện thoại)

Bạn có thể chạy trực tiếp trên **Google Cloud Shell** mà không cần cấu hình máy tính:

1. Mở [Google Cloud Shell](https://shell.cloud.google.com).
2. Chạy lệnh cài đặt hệ thống: `sudo apt install -y python3-pip`.
3. Clone repo về máy ảo: `git clone <LINK_GITHUB_CỦA_BẠN>`
4. Truy cập thư mục tool: `cd <TÊN_THƯ_MỤC>`
5. Cài đặt thư viện: `pip install -r requirements.txt`
6. Khởi chạy: `python3 dino-tool.py`

---

## 🛠️ Một Số Lưu Ý

- **Proxy:** Mặc định tool đã tự lấy list proxy miễn phí và ghim vào vòng lặp. Tuy nhiên proxy quét trên mạng sẽ chết dần. Nếu thấy tốc độ tạo acc chậm đi, hãy tắt tool mở lại. Nếu có Proxy Private Xịn, bạn dán thẳng Proxy vào file `proxy.txt`.
- **Token Expiry:** Mỗi Firebase Token chỉ sống khoảng 30 đến 60 phút. Khi tool báo Token hết hạn hoặc có lỗi bất thường, bạn cần lặp lại "Bước 3" để lấy Token mới gắn vào Tool.

---

## 📞 Liên Hệ & Hỗ Trợ

Gặp lỗi khi sử dụng? Cần mua bản Custom siêu cấp VIP pro? Liên hệ ngay:

<a href="https://t.me/dinostore01">
  <img src="https://img.shields.io/badge/Telegram-%40dinostore01-blue.svg?logo=telegram&style=for-the-badge" alt="Telegram Support"/>
</a>

<div align="center">
  <i>Được phát triển với 💖 bởi Dino Team</i>
</div>
