# KennyPhoto Culling — bản phát hành macOS

Bộ cài và cập nhật OTA chính thức của KennyPhoto Culling cho **macOS 14 trở lên, Apple Silicon (arm64)**.

Tải DMG mới nhất tại [Releases](https://github.com/kennyhoangxx/kenny-photo-culling-releases/releases/latest). Cài lần đầu: mở DMG rồi kéo **KennyPhoto Culling.app** vào **Applications**.

Trong ứng dụng, mở **Kiểm tra cập nhật… → Cập nhật ngay…** để tải, xác minh chữ ký, cài đặt và khởi động lại. Có thể bật **Tự tải và cài bản mới khi thoát ứng dụng** để cập nhật trong nền. Từ build 18, OTA ưu tiên bản vá nhỏ để không tải lại các mô hình AI đã có; bộ cài DMG đầy đủ dùng cho cài mới hoặc khi bản vá không áp dụng được. OTA xác minh chữ ký Ed25519 của feed, bản vá và bộ cài.

Ứng dụng hoạt động local-first; ảnh và dữ liệu lọc nằm trên máy. Bản phát hành hiện dùng chữ ký ad hoc, chưa Apple-notarized.

Các asset `updates.json`, `appcast.xml`, `.delta` và file `.dmg.sha256` là metadata cập nhật và kiểm tra toàn vẹn. Mỗi bản có số build riêng và URL tải cố định.
