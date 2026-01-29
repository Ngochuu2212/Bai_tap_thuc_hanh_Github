# Mô tả Dự án: Landing Page Đa Thành Phần

Dự án này sử dụng phương pháp phát triển theo module, chia nhỏ trang web thành các phần riêng biệt để dễ dàng quản lý và bảo trì. Thay vì viết hàng nghìn dòng code trong một file duy nhất, các nội dung được tách ra các tệp HTML con nằm trong thư mục `sections/`.

## Cấu trúc Thành phần:

- **index.html**: Đóng vai trò là "khung xương" chính. Nó chứa các thẻ giữ chỗ `div` và mã điều hướng để lắp ghép nội dung.
- **style.css**: Tệp phong cách tập trung, dùng để định dạng giao diện cho toàn bộ trang web.
- **Thư mục `sections/`**: Chứa các mảnh ghép nội dung cụ thể:
  - **hero.html**: Phần đầu trang (Banner, lời chào gọi).
  - **features.html**: Giới thiệu tính năng hoặc dịch vụ.
  - **pricing.html**: Bảng giá sản phẩm.
  - **contact.html**: Thông tin liên hệ và form đăng ký.
