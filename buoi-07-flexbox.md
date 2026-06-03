# KẾ HOẠCH CHI TIẾT: BUỔI 7 - FLEXBOX

**Tổng thời gian: 90 phút**

---

# 1. MỞ ĐẦU (10 PHÚT)

- Ôn position.
- Nêu lý do cần Flexbox.

---

# 2. FLEX CONTAINER (45 PHÚT)

## 2.1. Kích hoạt Flexbox (10 phút)

- `display: flex`.

## 2.2. Thuộc tính quan trọng (25 phút)

- `flex-direction`
- `justify-content`
- `align-items`
- `flex-wrap`

### Ví dụ

```css
.navbar {
	display: flex;
	justify-content: space-between;
	align-items: center;
}
```

### Lỗi thường gặp

- Dùng `justify-content` nhưng quên container phải là flex.
- Trộn nhiều giá trị mà không xác định rõ trục chính.

## 2.3. Thực hành (10 phút)

- Căn menu.
- Căn card.
- Căn header.

### Mẹo

- Flexbox rất mạnh cho một chiều, đừng cố ép nó làm mọi thứ.

---

# 3. FLEX ITEMS (35 PHÚT)

## 3.1. Thuộc tính trên item (20 phút)

- `flex-grow`
- `flex-shrink`
- `order`
- `align-self`

## 3.2. Thực hành (15 phút)

- Layout 2 cột.
- Card đều nhau.
- Menu responsive nhẹ.

### Mẹo

- Nếu muốn căn giữa cả ngang lẫn dọc, hãy thử `justify-content: center` và `align-items: center`.

---

# 4. THỰC HÀNH & TOP 5 (40 PHÚT)

## Bài tập

- Dựng một trang có header, main, sidebar, footer bằng Flexbox.

### Khung gợi ý

```html
<div class="page">
	<header></header>
	<main class="layout">
		<aside></aside>
		<section></section>
	</main>
</div>
```

### Bonus cuối buổi

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 7

- Dùng được Flex container.
- Hiểu các thuộc tính Flex items.
- Tạo được layout hiện đại cơ bản.
