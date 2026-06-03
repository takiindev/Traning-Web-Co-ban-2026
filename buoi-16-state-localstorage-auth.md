# KẾ HOẠCH CHI TIẾT: BUỔI 16 - STATE MANAGEMENT, LOCALSTORAGE & AUTH

**Tổng thời gian: 150 phút**

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

# 5. TỔNG KẾT & TOP 5 (35 PHÚT)

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
