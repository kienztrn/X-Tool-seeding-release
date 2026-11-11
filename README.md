# XTool — bản cài đặt

Kho này chứa **bản cài đặt và các bản cập nhật** của XTool. Mã nguồn nằm ở https://github.com/kienztrn/X-Tool-seeding.

## Cài lần đầu (Windows 10/11 64-bit)

1. Vào tab **Releases**, tải tệp `XTool-v<phiên bản>-win64.zip` của bản mới nhất.
2. Giải nén **đầy đủ** ra một thư mục.
3. Chạy `Cai-dat-XTool.cmd` trong thư mục vừa giải nén. Nó cài XTool vào `%LOCALAPPDATA%\Programs\XTool`, tạo biểu tượng ở Desktop và Start Menu rồi mở app.

Dữ liệu và key của bạn nằm ở `%APPDATA%\XTool`, không bị ảnh hưởng khi cài lại hay cập nhật.

## Cập nhật

Trong app: **Cài đặt → Cập nhật ứng dụng → Kiểm tra cập nhật → Cập nhật và mở lại**. App tải gói `xtool-app.zip` của bản mới nhất ở đây, kiểm tra mã SHA-256 trong `xtool-app.json`, cài đè rồi tự mở lại.

> Kho này phải để **Public** thì nút cập nhật trong app mới tải được bản mới.

## Tệp trong mỗi bản phát hành

| Tệp | Dùng để |
| --- | --- |
| `XTool-v<phiên bản>-win64.zip` | Cài lần đầu trên máy mới (bản đầy đủ + `Cai-dat-XTool.cmd`) |
| `xtool-app.zip` | Gói mã nhỏ mà nút Cập nhật trong app tải về |
| `xtool-app.json` | Phiên bản, SHA-256 và dung lượng của `xtool-app.zip` |
