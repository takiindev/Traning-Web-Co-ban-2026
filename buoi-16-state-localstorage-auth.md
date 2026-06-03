# KẾ HOẠCH CHI TIẾT: BUỔI 16 - STATE MANAGEMENT, LOCALSTORAGE & AUTH

**Tổng thời gian: 90 phút**

---

# 1. MỞ ĐẦU (10 PHÚT)

- Ôn CRUD và fetch.
- Dẫn vào tư duy quản lý trạng thái.

---

# 2. STATE MANAGEMENT CƠ BẢN (35 PHÚT)

## Nội dung

- Luồng `Action -> State -> Render`.
- Tách dữ liệu và giao diện.
- Cập nhật lại màn hình khi state thay đổi.

### Ví dụ

```js
let state = { count: 0 };

function render() {
	document.querySelector('#count').innerText = state.count;
}
```

### Mẹo thực tế

- Làm rõ nguồn dữ liệu nào là thật, dữ liệu nào là đang hiển thị.

---

# 3. LOCALSTORAGE (30 PHÚT)

## Nội dung

- Lưu `userId`.
- Lưu trạng thái đăng nhập.
- Đọc lại khi reload trang.

### Ví dụ

```js
localStorage.setItem('userId', '123');
const userId = localStorage.getItem('userId');
```

## Thực hành

- Ghi nhớ user.
- Tự đăng nhập lại sau refresh.

---

# 4. AUTH FLOW & BẢO VỆ ROUTE (40 PHÚT)

## Nội dung

- Đăng ký.
- Đăng nhập.
- Chặn truy cập trang admin nếu chưa login.

### Lỗi thường gặp

- Chỉ lưu trạng thái mà không kiểm tra lại khi reload.
- Để logic auth rải khắp file.

### Mẹo

- Luồng auth cơ bản phải rõ: vào -> kiểm tra -> cho phép hoặc chuyển hướng.

---

# 5. HƯỚNG DẪN NHANH QUẢN LÝ CODE & DEPLOY VỚI GIT/GITHUB (15 PHÚT)

## Mục tiêu

- Học viên nắm luồng nộp bài và quản lý version trước khi vào nghiệm thu.
- Biết đẩy project lên GitHub và chia sẻ link chạy online cơ bản.

## Nội dung

- Khởi tạo Git trong project:

```bash
git init
git add .
git commit -m "init project"
```

- Tạo repository trên GitHub và đẩy code:

```bash
git branch -M main
git remote add origin <repo-url>
git push -u origin main
```

### Quy tắc tối thiểu trước nghiệm thu

- Commit rõ nghĩa theo từng phần việc.
- Có file `README.md` mô tả cách chạy dự án.
- Chạy thử và xác nhận link repository truy cập được.

## Gợi ý deploy nhanh

- Frontend tĩnh: deploy bằng GitHub Pages hoặc Netlify.
- Chia sẻ 2 link khi nghiệm thu: link GitHub + link deploy.

---

# 6. TỔNG KẾT & TOP 5 (20 PHÚT)

## Bài tập

- Hoàn thiện luồng đăng nhập.
- Lưu trạng thái vào localStorage.
- Chặn vào trang admin khi chưa hợp lệ.

### Bonus cuối buổi

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 16

- Hiểu state flow cơ bản.
- Dùng được localStorage.
- Biết làm luồng đăng nhập và chặn truy cập cơ bản.
- Biết quy trình quản lý code bằng Git/GitHub và chuẩn bị deploy trước nghiệm thu.
