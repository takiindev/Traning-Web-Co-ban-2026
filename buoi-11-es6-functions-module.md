# KẾ HOẠCH CHI TIẾT: BUỔI 11 - ES6, FUNCTIONS & MODULE

**Tổng thời gian: 150 phút**

---

# 1. MỞ ĐẦU (10 PHÚT)

- Ôn JS cơ bản.
- Dẫn vào cú pháp hiện đại.

---

# 2. FUNCTION & ARROW FUNCTION (35 PHÚT)

## Nội dung

- Function declaration.

### Ví dụ

```js
function sum(a, b) {
	return a + b;
}

const multiply = (a, b) => a * b;
```

### Lỗi thường gặp

- Viết arrow function nhưng quên `return` khi dùng block body.
- Dùng function quá dài, không tách nhiệm vụ.
- Function expression.
- Arrow function.

### Mẹo

- Function càng rõ đầu vào - đầu ra thì code càng dễ kiểm soát.

---

# 3. ES6 CƠ BẢN (35 PHÚT)

## Nội dung


### Ví dụ

```js
const user = { name: 'An', age: 20 };
const { name, age } = user;
const arr2 = [...[1, 2, 3], 4];
```

### Mẹo

- Destructuring rất tiện nhưng phải biết dữ liệu đang có cấu trúc gì.
- `const` / `let`
- Destructuring.
- Spread operator `...`.
- Template literal.

### Thực hành

- Tách object.
- Gộp mảng.
- Tạo chuỗi động.

---

# 4. MODULE: IMPORT / EXPORT (30 PHÚT)

## Nội dung


### Ví dụ

```js
// math.js
export const sum = (a, b) => a + b;

// app.js
import { sum } from './math.js';
```

### Lỗi thường gặp

- Sai đường dẫn import.
- Quên `type="module"` khi chạy file JS module trên trình duyệt.
- Chia code thành file.
- Export hàm.
- Import hàm.

### Mẹo thực tế

- Dự án thật không nên dồn toàn bộ logic vào một file.

---

# 5. THỰC HÀNH & TOP 5 (40 PHÚT)

## Bài tập

- Tách hàm hiển thị dữ liệu.
- Dùng destructuring để lấy dữ liệu.
- Gọi hàm từ file khác.

### Bonus cuối buổi

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 11

- Viết được function hiện đại.
- Dùng được destructuring và spread.
- Biết tách code thành module.
