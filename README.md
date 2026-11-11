# XTool — bản cài đặt

Kho này chứa **bản cài đặt và các bản cập nhật** của XTool. Mã nguồn nằm ở https://github.com/kienztrn/X-Tool-seeding.

## Cài lần đầu (Windows 10/11 64-bit)

1. Vào tab **Releases**, tải tệp **`XTool-Setup-<phiên bản>.exe`** của bản mới nhất.
2. Chạy tệp đó. XTool tự cài (không cần quyền quản trị), tạo biểu tượng ở Desktop và Start Menu rồi mở app.

> Bộ cài chưa được ký số, nên Windows có thể hiện cảnh báo **"Windows protected your PC"**. Bấm **More info → Run anyway** để tiếp tục.

Dữ liệu và key của bạn nằm ở `%APPDATA%\XTool`, không bị ảnh hưởng khi cài lại, cập nhật hay gỡ app.

## Cập nhật

Trong app: **Cài đặt → Cập nhật ứng dụng → Kiểm tra cập nhật → Cập nhật và mở lại**. App tải gói `xtool-app.zip` của bản mới nhất ở đây, kiểm tra mã SHA-256 trong `xtool-app.json`, cài đè rồi tự mở lại.

> Kho này phải để **Public** thì nút cập nhật trong app mới tải được bản mới.

## Tệp trong mỗi bản phát hành

| Tệp | Dùng để |
| --- | --- |
| `XTool-Setup-<phiên bản>.exe` | Cài lần đầu trên máy mới |
| `xtool-app.zip` | Gói mã nhỏ mà nút Cập nhật trong app tải về |
| `xtool-app.json` | Phiên bản, SHA-256 và dung lượng của `xtool-app.zip` |
