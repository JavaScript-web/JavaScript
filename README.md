# Chúc Mừng Năm Mới — Bính Ngọ 2026

Trang tĩnh chào mừng Năm Mới Bính Ngọ 2026, gồm phần đếm ngược đến giao thừa, giới thiệu phong tục, ẩm thực, lời chúc, và hiệu ứng pháo hoa.

Demo: Mở file `20.html` trong trình duyệt (hoặc triển khai lên GitHub Pages) để xem giao diện.

---

## Nội dung chính
- `20.html` — Trang HTML chính (hero, countdown, traditions, cuisine, wishes, fireworks).
- CSS và JS được nhúng trong file HTML (tải AOS từ CDN).
- Canvas pháo hoa tương tác, slider lời chúc, đồng hồ đếm ngược đến 17/02/2026 00:00.

---

## Tính năng nổi bật
- Giao diện đẹp, responsive, sử dụng Google Fonts và AOS (Animate On Scroll).
- Đồng hồ đếm ngược đến mùng 1 Tết Bính Ngọ 2026.
- Slider lời chúc tự động và điều khiển thủ công.
- Hiệu ứng pháo hoa bằng canvas, có thể click để tạo pháo hoa.
- Hỗ trợ cuộn mượt (smooth scroll) cho anchor nội bộ.

---

## Hướng dẫn sử dụng (Local)
1. Clone repository hoặc tải file `20.html`.
2. Mở `20.html` bằng trình duyệt hiện đại (Chrome, Firefox, Edge, Safari).
3. Nếu bạn muốn chạy trên máy chủ cục bộ:
   - Với Python 3: `python -m http.server 8000` trong thư mục chứa file, sau đó mở `http://localhost:8000/20.html`.

---

## Triển khai lên GitHub Pages
1. Đẩy source (chứa `20.html`) lên repository trên GitHub.
2. Vào Settings > Pages, chọn branch (ví dụ `main`) và thư mục (root).
3. Lưu — trang sẽ được phục vụ tại `https://<owner>.github.io/<repo>/20.html` (có thể cần vài phút).

Gợi ý: Đổi tên `20.html` thành `index.html` nếu muốn trang được mở mặc định tại gốc GitHub Pages.

---

## Tùy chỉnh nhanh
- Thay đổi ngày đích trong script (nếu muốn đếm đến ngày khác):
  ```js
  const target = new Date(2026,1,17,0,0,0).getTime();
  ```
  Lưu ý: Tháng trong `Date(year, monthIndex, ...)` bắt đầu từ 0 (0 = tháng 1).

- Thay hình nền hero: chỉnh `background-image` trong `.hero-overlay` style.

---

## Accessibility & Progressive Enhancement
- Các phần tương tác có `aria-label` (ví dụ nút slider).
- Canvas pháo hoa cho phép tương tác bằng chuột và cảm ứng.
- Tương thích trên thiết bị di động (touch-friendly).

---

## Đóng góp
Mọi đóng góp (báo lỗi, cải tiến giao diện, tối ưu performance) đều được hoan nghênh. Vui lòng mở issue hoặc gửi pull request.

---

## Bản quyền & License
© 2026 — T��t Bính Ngọ. Thiết kế với tình yêu Việt Nam.  
Bạn có thể sử dụng, sửa đổi và phân phối lại nội dung này. Nếu muốn, tôi có thể thêm tệp LICENSE (MIT/Apache/BSD) theo yêu cầu.

---

## Tác giả
Thiết kế & phát triển: (Bạn)  
Liên hệ: cung cấp GitHub username hoặc email nếu muốn ghi rõ.
