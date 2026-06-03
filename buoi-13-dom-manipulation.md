# KẾ HOẠCH CHI TIẾT: BUỔI 13 - DOM MANIPULATION

**Tổng thời gian: 150 phút**

---

# 1. MỞ ĐẦU (10 PHÚT)

- Ôn array methods.
- Dẫn vào tương tác với giao diện.

---

# 2. TRUY XUẤT DOM (30 PHÚT)

## Nội dung

- `querySelector`
- `querySelectorAll`
- `getElementById`

### Ví dụ

```js
const button = document.querySelector('.btn');
const title = document.getElementById('title');
```

### Lỗi thường gặp

- Chọn nhầm selector dẫn đến `null`.
- Viết code trước khi DOM sẵn sàng.

### Thực hành

- Lấy nút.
- Lấy input.
- Lấy danh sách item.

---

# 3. THAY ĐỔI NỘI DUNG & THUỘC TÍNH (35 PHÚT)

## Nội dung

- `innerHTML`
- `innerText`
- `setAttribute`
- `classList`

### Ví dụ

```js
title.innerText = 'Tiêu đề mới';
button.classList.add('active');
```

### Mẹo

- Chỉ dùng `innerHTML` khi cần chèn cấu trúc, còn lại ưu tiên cách an toàn hơn.

---

# 4. SỰ KIỆN (35 PHÚT)

## Nội dung

- `click`
- `scroll`
- `input`
- `blur`

### Ví dụ

```js
button.addEventListener('click', () => {
	console.log('Clicked');
});
```

### Thực hành

- Đổi nội dung khi bấm nút.
- Hiện/ẩn phần tử.
- Đếm số lần click.

---

# 5. THỰC HÀNH & TOP 5 (40 PHÚT)

## Bài tập

- Làm nút đổi theme.
- Thêm class active cho menu.
- Render danh sách từ mảng.

### Bonus cuối buổi

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 13

- Truy xuất được phần tử DOM.
- Thay đổi được nội dung và class.
- Bắt được các sự kiện cơ bản.
