# KẾ HOẠCH CHI TIẾT: BUỔI 12 - ARRAY METHODS & HÀM ĐỊNH THỜI

**Tổng thời gian: 90 phút**

---

# 1. MỞ ĐẦU (10 PHÚT)

- Ôn function và module.

---

# 2. ARRAY METHODS (55 PHÚT)

## Nội dung

### Ví dụ

```js
const prices = [100, 200, 300];
const total = prices.reduce((sum, price) => sum + price, 0);
```

### Mẹo

- `map` tạo mảng mới.
- `filter` lọc dữ liệu.
- `reduce` gom về một giá trị.

- `forEach`
- `map`
- `filter`
- `find`
- `some`
- `reduce`

### Thực hành

- Biến đổi danh sách.
- Lọc sản phẩm.
- Tính tổng tiền.
- Tìm phần tử đầu tiên phù hợp.

### Mẹo

- Chọn đúng method sẽ làm code ngắn và dễ đọc hơn nhiều so với dùng vòng lặp tay.

---

# 3. HÀM ĐỊNH THỜI (25 PHÚT)

## Nội dung

### Ví dụ

```js
setTimeout(() => {
	console.log('Done');
}, 1000);
```

### Lỗi thường gặp

- Quên xóa interval sau khi không dùng nữa.
- Dùng timeout cho việc cần lặp lại.

- `setTimeout`
- `setInterval`

### Thực hành

- Chạy thông báo chậm.
- Tạo đồng hồ đếm ngược.

---

# 4. THỰC HÀNH & TOP 5 (50 PHÚT)

## Bài tập

- Lọc danh sách sản phẩm theo giá.
- Tính tổng đơn hàng.
- Tạo countdown đơn giản.

### Khung gợi ý

```js
const cheapProducts = products.filter(product => product.price < 500000);
```

### Bonus cuối buổi

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 12

- Dùng được array methods.
- Biết `setTimeout` và `setInterval`.
- Viết được logic xử lý dữ liệu gọn hơn.
