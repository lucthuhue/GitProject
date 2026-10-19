# GitProject - Bài Tập HTML Form & Table

Kho lưu trữ bài tập thực hành môn Lập trình Web với các bài tập về Biểu mẫu (Form) và Bảng dữ liệu (Table) trong HTML5.

## 📁 Danh sách tệp tin trong dự án:

1. **`form_simple.html`**: Form nhập liệu người dùng cơ bản gồm:
   - Họ và tên (`yourname`), Email (`email`), Sở thích (`checkbox` hobby).
   - Nút Gửi thông tin (Submit) và Nhập lại (Reset).
2. **`form_register.html`**: Form đăng ký học viên chi tiết đầy đủ 10 trường:
   - `fullname`, `email`, `phone`, `birthday`, `gender`, `address`, `course`, `study_type`, `hobby`, `note`.
   - Nút Đăng ký (Submit) và Nhập lại (Reset).
3. **`index.html`**: Bảng thời khóa biểu luyện tập gộp ô:
   - Gộp hàng dọc: `rowspan="2"` cho ô Thứ Hai.
   - Gộp cột ngang: `colspan="2"` cho ô Nghỉ học Thứ Ba.
4. **`simpleform.html`**: Form đặt hàng (Order Form) sử dụng phông chữ Wufoo.
5. **`search.html`**: Form tìm kiếm gửi dữ liệu qua phương thức `GET` đến Google và Bing.

---
## 🚀 Cách đẩy mã nguồn lên GitHub:

```bash
git init
git add .
git commit -m "feat: complete html form and table exercises"
git branch -M main
git remote add origin https://github.com/lucthuhue/GitProject.git
git push -u origin main
```