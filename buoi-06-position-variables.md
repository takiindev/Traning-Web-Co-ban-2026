# KẾ HOẠCH CHI TIẾT: BUỔI 6 - POSITIONING & VARIABLES

**Tổng thời gian: 90 phút**

---

# 1. KHỞI ĐỘNG (10 PHÚT)

- Ôn box model.
- Ôn typography.
- Dẫn vào vị trí phần tử trong layout.

---

# 2. POSITION (50 PHÚT)

## 2.1. Các giá trị position (25 phút)

- `static`
- `relative`
- `absolute`
- `fixed`
- `sticky`

### Ví dụ minh họa

```css
.badge {
	position: absolute;
	top: 8px;
	right: 8px;
}
```

### Lỗi thường gặp

- Dùng `absolute` nhưng quên đặt phần tử cha `relative`.
- Cố dùng position để dàn cả layout chính.

## 2.2. `z-index` (10 phút)

- Khi nào phần tử nằm trên.
- Khi nào bị che.

## 2.3. Thực hành (15 phút)

- Tạo badge.
- Tạo nút nổi.
- Tạo header sticky.

### Mẹo thực tế

- Position chỉ nên dùng đúng việc, không lạm dụng để dàn layout chính.

---

# 3. CSS VARIABLES (35 PHÚT)

## 3.1. Khai báo biến trong `:root` (15 phút)

- Màu chủ đạo.
- Kích thước lề.
- Bo góc.

## 3.2. Tái sử dụng (20 phút)

- Dùng biến cho nhiều component.
- Sửa một chỗ, cập nhật toàn bộ.

### Ví dụ

```css
:root {
	--primary: #2563eb;
	--radius: 12px;
	--space: 16px;
}
```

### Mẹo

- Biến CSS nên đặt tên theo vai trò, không nên đặt theo màu ngẫu hứng.

### Mẹo

- Biến CSS giúp giao diện đồng nhất và dễ bảo trì.

---

# 4. THỰC HÀNH & BONUS (35 PHÚT)

## Bài tập

- Dựng card có ảnh chồng lớp.
- Tạo menu sticky.
- Dùng biến màu cho toàn trang.

### Khung gợi ý

```html
<header class="header">...</header>
<section class="hero">
	<span class="badge">New</span>
</section>
```

### Bonus cuối buổi

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 6

- Dùng được position.
- Hiểu z-index.
- Tạo được CSS variables.
