# KẾ HOẠCH CHI TIẾT: BUỔI 14 - FORM LOGIC & REAL-TIME VALIDATION

**Tổng thời gian: 150 phút**

---

# 1. MỞ ĐẦU (10 PHÚT)

- Ôn DOM và sự kiện.
- Dẫn vào xử lý form thật.

---

# 2. XỬ LÝ DỮ LIỆU FORM (35 PHÚT)

## Nội dung

- Lấy giá trị input.
- Kiểm tra rỗng.
- Chặn submit khi sai.

### Ví dụ

```js
form.addEventListener('submit', (event) => {
	event.preventDefault();
});
```

### Thực hành

- Form đăng ký.
- Form liên hệ.

---

# 3. REAL-TIME VALIDATION (35 PHÚT)

## Nội dung

- Bắt sự kiện `input`.
- Bắt sự kiện `blur`.
- Báo lỗi ngay khi người dùng nhập sai.

### Mẹo thực tế

- Báo lỗi càng sớm càng tốt, nhưng câu chữ phải ngắn và dễ hiểu.

---

# 4. REGEX CƠ BẢN (35 PHÚT)

## Nội dung

- Kiểm tra email.
- Kiểm tra số điện thoại.
- Kiểm tra mật khẩu.

### Ví dụ

```js
const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
```

### Thực hành

- Viết regex đơn giản.
- Ghép regex với form validation.

---

# 5. THỰC HÀNH & TOP 5 (35 PHÚT)

## Bài tập

- Tạo form đăng ký có validate realtime.
- Hiển thị thông báo lỗi rõ ràng.

### Bonus cuối buổi

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 14

- Xử lý được dữ liệu form.
- Validate realtime cơ bản.
- Dùng được regex cho bài toán thực tế.
