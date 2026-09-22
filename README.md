# Bé Gấu V6.7 – Zalo Card Fix

Bản này tối ưu riêng cho preview/card Zalo của khách tạo mới.

Thay đổi chính:
- Mỗi thiệp có một `og:image` riêng theo slug:
  `zalo-preview.jpg?v=<slug>`
- Bổ sung `og:site_name`, `og:locale`, `og:image:alt`
- Bổ sung canonical URL
- Vẫn giữ `zalo-preview.jpg` ở thư mục gốc
- Ảnh Gấu và QR trong thiệp vẫn tự chứa

Lý do:
Zalo có cache preview khá mạnh. Nếu mọi thiệp cùng trỏ tới đúng một URL ảnh,
khách mới đôi khi không được làm mới card ngay. Thêm `?v=<slug>` khiến mỗi thiệp
có URL preview ảnh riêng, giảm khả năng dính cache cũ.

Sau khi upload:
1. Commit toàn bộ file lên GitHub.
2. Chờ Vercel deploy.
3. Kiểm tra URL khách mới.
4. Gửi lại link sạch lên Zalo.