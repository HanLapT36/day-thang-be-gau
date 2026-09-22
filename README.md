# Bé Gấu V6.2 – Clean Invite Links + Zalo Preview

Bản này giữ giao diện V6.1 Việt Premium nhưng đổi cách chia sẻ thiệp:

- Link sạch, không còn `?guest=...`.
- Mỗi khách có một URL riêng, ví dụ: `https://day-thang-be-gau.vercel.app/bac-cu-tuan`.
- Tên khách vẫn tự xuất hiện xuyên suốt thiệp.
- Mỗi trang khách có thẻ Open Graph riêng để Zalo/Facebook đọc tiêu đề phù hợp.
- Có ảnh preview 1200×630 tại `assets/zalo-preview.jpg`.

## 5 link đã tạo
- **Bác Cù Tuấn**: `https://day-thang-be-gau.vercel.app/bac-cu-tuan`
- **Bá Hoài Anh**: `https://day-thang-be-gau.vercel.app/ba-hoai-anh`
- **Bá Hồng Quyên**: `https://day-thang-be-gau.vercel.app/ba-hong-quyen`
- **Bá Ngọc Dung**: `https://day-thang-be-gau.vercel.app/ba-ngoc-dung`
- **Bác Phan Tuấn**: `https://day-thang-be-gau.vercel.app/bac-phan-tuan`

## Cách cập nhật
Upload toàn bộ nội dung thư mục này lên repo GitHub (không chỉ index.html), commit và chờ Vercel deploy.

`vercel.json` bật Clean URLs nên file `bac-cu-tuan.html` được truy cập bằng `/bac-cu-tuan`.
