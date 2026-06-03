# KẾ HOẠCH CHI TIẾT: BUỔI 15 - ASYNCHRONOUS JS & CRUD VỚI FAKE API

**Tổng thời gian: 150 phút**

---

# 1. MỞ ĐẦU (10 PHÚT)

- Ôn form validation.
- Dẫn vào dữ liệu từ server giả lập.

---

# 2. FETCH API & ASYNC JS (35 PHÚT)

## Nội dung

- Bất đồng bộ là gì.
- `fetch`.
- `then/catch` hoặc `async/await`.

### Ví dụ

```js
const response = await fetch('/api/products');
const data = await response.json();
```

### Mẹo

- Khi làm việc với API, luôn chuẩn bị trạng thái loading và lỗi.

---

# 3. FAKE API VỚI JSON-SERVER (25 PHÚT)

## Nội dung

- Tạo dữ liệu giả.
- Chạy server local.
- Đọc dữ liệu từ `Products`, `Users`, `Orders`.

### Mẹo

- Tách dữ liệu theo bảng để dễ test từng chức năng.

---

# 4. CRUD CƠ BẢN (45 PHÚT)

## Nội dung

- `GET`.
- `POST`.
- `DELETE`.
- Xác nhận trước khi xóa.

### Ví dụ luồng

1. GET danh sách.
2. POST thêm mới.
3. DELETE bản ghi.

### Lỗi thường gặp

- Không cập nhật lại giao diện sau khi gọi API.
- Quên xử lý lỗi mạng.

### Thực hành

- Hiển thị danh sách.
- Thêm mới dữ liệu.
- Xóa dữ liệu.

---

# 5. THỰC HÀNH & TOP 5 (35 PHÚT)

## Bài tập

- Lấy danh sách sản phẩm từ fake API.
- Hiển thị lên giao diện.
- Thêm mới một item.
- Xóa một item có confirm.

### Bonus cuối buổi

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 15

- Biết dùng fetch.
- Hiểu async JS.
- Làm được CRUD cơ bản với fake API.
