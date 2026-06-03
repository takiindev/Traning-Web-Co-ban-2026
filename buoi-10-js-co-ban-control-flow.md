# KẾ HOẠCH CHI TIẾT: BUỔI 10 - JS CƠ BẢN & CẤU TRÚC ĐIỀU KHIỂN

**Tổng thời gian: 90 phút**

---

# 1. MỞ ĐẦU (10 PHÚT)

- JS là gì.
- Vì sao cần JS sau HTML/CSS.
- JS dùng để tạo tương tác và xử lý logic.

### Mục tiêu

- Học viên hiểu JS không phải chỉ là cú pháp.
- Biết dùng JS để quyết định điều gì sẽ xảy ra trên giao diện.

---

# 2. KIỂU DỮ LIỆU & BIẾN (30 PHÚT)

## Nội dung

- `var`, `let`, `const`.
- String, Number, Boolean, Array, Object.
- Toán tử cơ bản.

### Ví dụ

```js
const userName = 'An';
let age = 20;
const isStudent = true;
```

### Giải thích nhanh

- `const` dùng cho giá trị không đổi.
- `let` dùng cho giá trị có thể thay đổi.
- `var` nhắc nhanh để biết lịch sử, nhưng hạn chế dùng trong bài mới.

### Mẹo

- Ưu tiên dùng `const`, chỉ dùng `let` khi cần đổi giá trị.
- Đặt tên biến rõ nghĩa để đọc lại sau không bị quên mục đích.

### Lỗi thường gặp

- Khai báo rồi không dùng.
- Gán nhầm kiểu dữ liệu.
- Đặt tên biến quá ngắn, không hiểu ý nghĩa.

---

# 3. COERCION & TRICKS (20 PHÚT)

## Nội dung

- Ép kiểu ngầm định.
- Các ví dụ như `1 + "1"`.
- So sánh `==` và `===`.

### Ví dụ minh hoạ

```js
console.log(1 + '1');
console.log('5' - 1);
console.log(0 == false);
console.log(0 === false);
```

### Gợi ý giảng viên

- Cho học viên tự đoán kết quả trước khi chạy code.
- Nhấn mạnh chỗ khác nhau giữa ép kiểu ngầm định và so sánh chặt.

### Mẹo thực tế

- Luôn ưu tiên `===` để tránh lỗi khó đoán.
- Khi dữ liệu lấy từ input, nên chủ động chuyển kiểu trước khi tính toán.

---

# 4. ĐIỀU KHIỂN LUỒNG (50 PHÚT)

## Nội dung

- `if / else`
- `switch / case`
- `for`
- `while`
- `break`, `continue`

### Ví dụ

```js
const score = 8;

if (score >= 8) {
	console.log('Giỏi');
} else if (score >= 6.5) {
	console.log('Khá');
} else {
	console.log('Cần cố gắng hơn');
}
```

### Thực hành

- Kiểm tra điểm.
- Duyệt danh sách sản phẩm.
- Lặp menu.

### Mẹo thực tế

- Chia bài toán lớn thành nhiều điều kiện nhỏ.
- Đừng để khối `if` quá dài mới bắt đầu viết logic.

### Lỗi thường gặp

- Thiếu `else` nên rơi vào trạng thái không xử lý.
- Quên `break` trong `switch`.
- Dùng vòng lặp khi thực ra chỉ cần một điều kiện.

---

# 5. THỰC HÀNH & TOP 5 (40 PHÚT)

## Bài tập

- Viết script kiểm tra độ tuổi.
- Lặp ra danh sách tên.
- Dùng điều kiện để đổi nội dung trên trang.

### Cách tổ chức thực hành

- Làm từng câu nhỏ trước.
- Chạy kết quả từng phần.
- Sau đó mới ghép thành bài hoàn chỉnh.

### Bonus cuối buổi

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

### Ghi nhận

- Chỉ tính bonus khi code chạy và học viên giải thích được logic.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 10

- Biết khai báo biến.
- Hiểu kiểu dữ liệu cơ bản.
- Dùng được điều kiện và vòng lặp.
- Biết tránh các lỗi coercion thường gặp.

