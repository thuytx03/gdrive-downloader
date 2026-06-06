<p align="center">
  <img src="docs/assets/logo.png" width="160" height="160" alt="GDrive Downloader Logo">
</p>

<h1 align="center">GDrive Downloader</h1>

<p align="center">
  <strong>Giải pháp tải dữ liệu từ Google Drive nhanh nhất và ổn định nhất.</strong><br>
  Tốc độ vượt trội, độ tin cậy tuyệt đối và giao diện hiện đại.
</p>

<p align="center">
  <a href="#tai-xuong">Tải xuống</a> •
  <a href="#tinh-nang">Tính năng</a> •
  <a href="#cai-dat">Cài đặt</a> •
  <a href="#huong-dan">Hướng dẫn nhanh</a> •
  <a href="#lich-su-cap-nhat">Lịch sử cập nhật</a>
</p>

---

<h2 id="tai-xuong">⬇️ Tải xuống</h2>

### Phiên bản mới nhất: v1.0.0 (06/06/2026)

| Nền tảng | Kiến trúc | File | Tải xuống |
|---|---|---|---|
| macOS | Apple Silicon (M1/M2/M3/M4) | `.dmg` | [GDrive.Downloader_1.0.0_aarch64.dmg](https://github.com/thuytx03/gdrive-downloader/releases/download/v1.0.0/GDrive.Downloader_1.0.0_aarch64.dmg) |
| Windows | 64-bit (x64) | `.exe` | [GDrive.Downloader_1.0.0_x64-setup.exe](https://github.com/thuytx03/gdrive-downloader/releases/download/v1.0.0/GDrive.Downloader_1.0.0_x64-setup.exe) |

> Xem toàn bộ lịch sử phát hành tại [Releases](https://github.com/thuytx03/gdrive-downloader/releases).

---

## Tại sao chọn GDrive Downloader?

Google Drive rất tuyệt vời, nhưng việc tải xuống các file hoặc thư mục lớn thường gặp lỗi "liên kết hết hạn" hoặc "phiên làm việc bị ngắt". **GDrive Downloader** giải quyết triệt để vấn đề này bằng cách tích hợp trực tiếp với trình duyệt của bạn, đảm bảo quá trình tải không bao giờ bị gián đoạn, ngay cả khi cookie hết hạn.

### ✨ Tính năng nổi bật

- 🚀 **Tải xuống Turbo**: Công cụ đa luồng (multi-threading) giúp tối đa hóa băng thông internet của bạn.
- 🍪 **Xác thực thông minh**: Tự động nhận diện phiên đăng nhập từ **Chrome, Brave, Edge hoặc Firefox**.
- 🔄 **Tự động làm mới**: Phát hiện cookie hết hạn và tự động làm mới trong nền mà không làm gián đoạn quá trình tải.
- 📂 **Hỗ trợ Thư mục**: Tải toàn bộ thư mục Google Drive chỉ với một cú nhấp chuột, giữ nguyên cấu trúc cây thư mục.
- 💾 **Lưu phiên làm việc**: Ghi nhớ trình duyệt và profile bạn đã chọn. Mở app lên là dùng được ngay.
- 🎨 **Giao diện Cao cấp**: Thiết kế tối giản, hiện đại lấy cảm hứng từ những xu hướng mới nhất, hỗ trợ đầy đủ Chế độ tối (Dark Mode).
- 👥 **Quản lý nhiều tài khoản**: Lưu nhiều tài khoản Google (theo từng trình duyệt và profile) — khi một tài khoản gặp lỗi xác thực, hệ thống tự động thử tài khoản khác mà không cần bạn can thiệp.
- 📄 **Hỗ trợ mọi loại file**: Tải được cả **Video, PDF, Image, Zip, Google Docs, Sheets, Slides** (xuất file) và mọi định dạng file thông thường.
- 📋 **Lịch sử tải xuống**: Xem lại toàn bộ lịch sử, tìm kiếm theo tên file hoặc lọc theo ngày, xóa từng mục hoặc xóa toàn bộ.

---

<h2 id="cai-dat">📦 Cài đặt</h2>

### Cho macOS
1. Tải file `.dmg` hoặc `.app` mới nhất từ trang [Releases](https://github.com/thuytx03/gdrive-downloader/releases).
2. Kéo biểu tượng **GDrive Downloader** vào thư mục `Applications`.
3. Mở ứng dụng. Nếu gặp lỗi **"Damaged and can't be opened"**, hãy mở Terminal và chạy lệnh:
   `sudo xattr -rd com.apple.quarantine "/Applications/GDrive Downloader.app"`

### Cho Windows
1. Tải file cài đặt `.exe` mới nhất từ trang [Releases](https://github.com/thuytx03/gdrive-downloader/releases).
2. Chạy file cài đặt. Nếu hiện thông báo "Windows protected your PC", hãy nhấn **More info** -> **Run anyway**.
3. Khởi chạy ứng dụng từ Desktop hoặc Start Menu.

---

<h2 id="huong-dan">🚀 Hướng dẫn nhanh trong 3 bước</h2>

1. **Dán liên kết**: Sao chép URL file hoặc thư mục Google Drive và dán vào thanh tìm kiếm.
2. **Chọn trình duyệt**: Chọn trình duyệt mà bạn đã đăng nhập Google Drive.
3. **Bắt đầu tải**: Nhấn nút Tải xuống và tận hưởng tốc độ vượt trội.

---

## 🛠 Công nghệ sử dụng

Được xây dựng trên nền tảng công nghệ hiện đại và hiệu suất cao:
- **Lõi**: [Tauri v2](https://tauri.app/) (Rust)
- **Backend**: [FastAPI](https://fastapi.tiangolo.com/) (Python)
- **Frontend**: [React](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Giao diện**: [Tailwind CSS](https://tailwindcss.com/) + [shadcn/ui](https://ui.shadcn.com/)
- **Cơ sở dữ liệu**: [SQLite](https://sqlite.org/) với SQLModel

---

<h2 id="lich-su-cap-nhat">📋 Lịch sử cập nhật</h2>

### v1.0.0 — 06/06/2026 (Phát hành lần đầu)

#### ✨ Tính năng mới
- **Tải xuống Turbo**: Đa luồng (multi-threading) tối đa hóa băng thông, tốc độ tải vượt trội so với trình duyệt.
- **Xác thực thông minh qua Cookie trình duyệt**: Tự động đọc phiên đăng nhập từ Chrome, Brave, Edge và Firefox — không cần nhập mật khẩu.
- **Tự động làm mới Cookie**: Phát hiện và làm mới cookie hết hạn trong nền, không làm gián đoạn quá trình tải.
- **Hỗ trợ tải Thư mục**: Tải toàn bộ thư mục Google Drive, giữ nguyên cấu trúc cây thư mục gốc.
- **Quản lý nhiều tài khoản Google**: Lưu nhiều tài khoản (theo trình duyệt và profile), tự động chuyển sang tài khoản khác khi gặp lỗi xác thực.
- **Hỗ trợ mọi định dạng file**: Video, PDF, Image, Zip, Google Docs, Sheets, Slides (xuất file), và tất cả định dạng thông thường.
- **Lịch sử tải xuống**: Xem, tìm kiếm theo tên file, lọc theo ngày, xóa từng mục hoặc xóa toàn bộ.
- **Lưu phiên làm việc**: Ghi nhớ trình duyệt và profile đã chọn, mở app lên là dùng ngay.
- **Giao diện cao cấp**: Thiết kế tối giản, hiện đại, hỗ trợ đầy đủ Chế độ tối (Dark Mode).
- **Xác thực API Key**: Hệ thống xác thực tài khoản tích hợp với API key để quản lý quyền truy cập.

#### 🖥️ Nền tảng được hỗ trợ
- macOS — Apple Silicon (aarch64)
- Windows — 64-bit (x64)

---

## 📄 Bản quyền

Dự án này được cấp phép theo Giấy phép MIT - xem file [LICENSE](LICENSE) để biết thêm chi tiết.

<p align="center">
  Phát triển với Trịnh Xuân Thủy
</p>
