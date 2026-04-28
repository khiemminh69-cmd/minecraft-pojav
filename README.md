# 🎮 Hướng Dẫn Cài Đặt Minecraft Java (Fabric 1.21.4) Trên Android

![Status Ready](https://img.shields.io/badge/Status-Ready-brightgreen?style=for-the-badge)
![MC Version](https://img.shields.io/badge/Version-1.21.4-blue?style=for-the-badge&logo=minecraft)
![Fabric](https://img.shields.io/badge/Loader-Fabric-orange?style=for-the-badge)

Bộ hướng dẫn này sẽ giúp bạn cài đặt hoàn chỉnh môi trường chơi Minecraft Java Edition với đầy đủ các mod tối ưu hóa và công cụ hỗ trợ điều khiển từ xa.

---

### 📥 Bước 1: Tải Các Tệp Cần Thiết
Bạn cần tải về đủ 4 tệp sau đây để bắt đầu:
* **PojavLauncher.apk**: Trình khởi chạy Minecraft Java.
* **MT_Manager.apk**: Công cụ quản lý tệp và giải nén (khuyên dùng).
* **RustDesk.apk**: Ứng dụng chia sẻ màn hình để nhận hỗ trợ hoặc điều khiển từ xa.
* **MinecraftMods.zip**: Gói dữ liệu gồm `.minecraft` và `controlmap`.

---

### 🛠️ Bước 2: Cài Đặt Ứng Dụng
Sau khi tải về, tiến hành cài đặt lần lượt các file có đuôi `.apk`:
1. Cài đặt **PojavLauncher**.
2. Cài đặt **MT Manager**.
3. Cài đặt **RustDesk**.

---

### 🎮 Bước 3: Khởi Tạo PojavLauncher
Trước khi bỏ mod, bạn cần tạo "bộ khung" cho game:
1. Mở ứng dụng **PojavLauncher**.
2. **Nhập tên người chơi:** Nhập nickname bạn muốn sử dụng.
3. **Chọn phiên bản:** Tìm và chọn đúng dòng **`Fabric Loader 1.21.4`**.
4. Nhấn **Chơi** để ứng dụng tải dữ liệu gốc (Sau khi vào đến menu game thì có thể thoát ra để làm bước tiếp theo).

---

### 📂 Bước 4: Giải Nén & Ghi Đè Dữ Liệu (Quan Trọng)
Sử dụng **MT Manager** để cài đặt Mod và sơ đồ phím:
1. Mở **MT Manager**.
2. **Cửa sổ bên trái:** Tìm đến file `MinecraftMods.zip`. Nhấn vào và chọn **Giải nén**.
3. **Cửa sổ bên phải:** Truy cập theo đường dẫn:
   `Android/data/net.kdt.pojavlaunch/files/`
4. **Thao tác:** Kéo toàn bộ các thư mục bên trong file zip đã giải nén (thư mục `.minecraft` và `controlmap`) từ bên trái **Ghi đè** sang bên phải.
   * *Nếu máy hỏi, chọn "Ghi đè tất cả" (Replace all).*

---

### 🖥️ Bước 5: Kết Nối & Trải Nghiệm
1. **Chia sẻ màn hình:** Mở app **RustDesk**, thiết lập ID để chia sẻ màn hình.
2. **Vào Game:** Quay lại **PojavLauncher** và bấm **Chơi**.

---

> **Lưu ý:** Nếu không thấy thư mục `.minecraft`, hãy vào cài đặt MT Manager bật "Show hidden files".
