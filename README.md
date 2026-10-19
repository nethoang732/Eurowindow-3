# Eurowindow website preview

Website giới thiệu Eurowindow được phục vụ bởi NestJS. Giao diện hiện tại là HTML, CSS và JavaScript thuần; NestJS cung cấp máy chủ để chạy trang và làm nền cho các API sau này.

## Chạy tại máy

```bash
npm install
npm run start:dev
```

Mở `http://localhost:3000`.

## Build và chạy production

```bash
npm run build
npm run start:prod
```

## Triển khai trên Vercel

Vercel tự nhận diện ứng dụng NestJS từ `src/main.ts`. Import repository này trên Vercel để bật triển khai tự động khi có commit mới.

## Lưu ý

Form tư vấn hiện chỉ kiểm tra dữ liệu trong trình duyệt, chưa gửi hay lưu thông tin. Cần nối API và nơi lưu trữ trước khi dùng để tiếp nhận yêu cầu thật. Hình ảnh đang lấy từ Unsplash để minh họa.

