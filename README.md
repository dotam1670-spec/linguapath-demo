# LinguaPath

Trang web một trang giúp học sinh, sinh viên và người trẻ ở Việt Nam xếp lớp ngoại ngữ và lập lộ trình học theo mục tiêu du học hoặc nghề nghiệp.

## Tính năng

- Sáu ngôn ngữ: Tiếng Anh, Tiếng Nhật, Tiếng Hàn, Tiếng Đức, Tiếng Trung, Tiếng Pháp
- Bài xếp lớp 24 câu cho mỗi ngôn ngữ (Đọc, Nghe, Ngữ pháp, Từ vựng)
- Lộ trình học theo mục tiêu và thời gian
- Bảng học lưu ngay trong trình duyệt

## Chạy thử

Không cần cài đặt gì. Mở file `index.html` bằng trình duyệt.

## Đưa lên GitHub Pages

1. Tạo repository mới trên GitHub, ví dụ `linguapath`.
2. Tải toàn bộ file trong thư mục này lên repository (xem lệnh bên dưới).
3. Vào **Settings → Pages**, ở mục **Build and deployment** chọn **Deploy from a branch**, branch `main`, thư mục `/ (root)`, rồi bấm **Save**.
4. Sau 1–2 phút trang sẽ có tại `https://<ten-tai-khoan>.github.io/<ten-repo>/`.

## Cấu trúc

```
index.html     Toàn bộ trang (HTML, CSS, JavaScript trong một file)
favicon.svg    Biểu tượng tab trình duyệt
.nojekyll      Báo GitHub Pages phục vụ file nguyên trạng
```

## Quyền riêng tư

Dữ liệu học chỉ lưu trong trình duyệt của người dùng (localStorage). Trang không gửi dữ liệu đi đâu.
