# Thần Số Học 4G – bản phát hành

Kho này do máy build tự cập nhật (từ kho riêng `thansohoc-abin`), không sửa tay.

- **Tải app**: vào mục [Releases](../../releases/latest), tải `ThanSoHoc-4G.apk` và cài đè lên bản cũ (không mất danh sách đã lưu).
- `ThanSoHoc.apk`: bản app mở trang web trên máy chủ.
- `thansohoc-web.zip`: bản web để tải lên máy chủ (PHP chỉ trả trang, trình duyệt tự tính).
- `manifest.json`: app đọc file này để biết có bản app mới, có bộ công thức mới.
- `engine/engine-<số bản>.js`: bộ công thức có chữ ký số; app chỉ dùng khi chữ ký đúng.
