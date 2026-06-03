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

# 5. SETUP SERVER MẪU VỚI JSON SERVER (25 PHÚT)

## Mục tiêu

- Biết cách dựng nhanh API giả để test form và auth flow.
- Chuẩn bị môi trường từ đầu: Node.js -> npm -> json-server.

## Quy trình setup

### Bước 1: Cài Node.js

- Tải và cài Node.js bản LTS tại trang chủ Node.js.
- Kiểm tra sau cài đặt:

```bash
node -v
npm -v
```

### Bước 2: Khởi tạo project

```bash
mkdir demo-json-server
cd demo-json-server
npm init -y
```

### Bước 3: Cài json-server

```bash
npm install json-server
```

### Bước 4: Tạo file dữ liệu mẫu

- Tạo file `db.json`:

```json
{
	"users": [
		{ "id": 1, "email": "admin@gmail.com", "password": "123456" }
	]
}
```

### Bước 5: Thêm script chạy server

- Trong `package.json` thêm:

```json
"scripts": {
	"server": "json-server --watch db.json --port 3000"
}
```

### Bước 6: Chạy thử API

```bash
npm run server
```

- Test nhanh endpoint: `http://localhost:3000/users`

## Gợi ý dùng trong buổi học

- Dùng endpoint `/users` để test validate form đăng ký/đăng nhập.
- Cho học viên thực hành `GET/POST` trước khi sang buổi async/fetch nâng cao.

---

# 6. THỰC HÀNH & TOP 5 (10 PHÚT)

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
- Tự setup được server mẫu bằng json-server để test form/API.
