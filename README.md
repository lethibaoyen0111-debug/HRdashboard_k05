# TechBank Vietnam HR Dashboard

Đây là hệ thống HR Dashboard tương tác được xây dựng cho mục tiêu phân tích dữ liệu nhân sự của TechBank Vietnam.

## Hướng dẫn triển khai trên GitHub Pages

Để triển khai dashboard này lên GitHub Pages, bạn hãy thực hiện các bước sau:

1. **Tạo repository mới:** Tạo một repository mới trên GitHub (ví dụ: `hr-dashboard`).
2. **Upload file:** Upload file `index.html` vào thư mục gốc của repository.
3. **Cấu hình GitHub Pages:**
    - Vào **Settings** của repository.
    - Chọn **Pages** ở menu bên trái.
    - Tại mục **Source**, chọn nhánh `main` (hoặc `master`) và thư mục `/(root)`.
    - Nhấn **Save**.
4. **Truy cập:** Sau vài phút, dashboard của bạn sẽ có thể truy cập tại đường dẫn: `https://<your-username>.github.io/<your-repository-name>/`

## Sử dụng Dashboard
- Mở trang web trên trình duyệt (Khuyên dùng Chrome).
- Nhấn nút "Upload Dataset.xlsx" để tải dữ liệu nhân sự của bạn lên.
- Dashboard sẽ tự động tính toán KPI, vẽ biểu đồ và phân tích Insight.

## Công nghệ sử dụng
- **SheetJS:** Xử lý dữ liệu Excel tại client-side.
- **Chart.js:** Thư viện biểu đồ tương tác.
- **Tailwind CSS:** Thiết kế giao diện hiện đại, responsive.
