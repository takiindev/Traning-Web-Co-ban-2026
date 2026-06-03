# KẾ HOẠCH CHI TIẾT: BUỔI 5 - BOX MODEL & TYPOGRAPHY

**Tổng thời gian: 90 phút**

---

# 1. KHỞI ĐỘNG (10 PHÚT)

- Ôn selector.
- Ôn background.
- Nêu mục tiêu: làm đẹp bố cục và chữ.

---

# 2. BOX MODEL (60 PHÚT)

## 2.1. Khái niệm (30 phút)

- Content.
- Padding.
- Border.
- Margin.

### Ví dụ hình dung

```css
.card {
	width: 300px;
	padding: 16px;
	border: 1px solid #ddd;
	margin-bottom: 20px;
}
```

### Lỗi thường gặp

- Nhầm margin với padding.
- Quên `box-sizing` nên kích thước bị đội lên.

### Cách dạy cho newbie (thêm thời gian luyện)

- Vẽ 1 khung theo thứ tự: `content -> padding -> border -> margin`.
- So sánh trực tiếp 2 card: 1 card tăng `padding`, 1 card tăng `margin`.
- Cho học viên tự đo kích thước trước/sau khi thêm `border` để thấy khác biệt.

## 2.2. `box-sizing: border-box` (10 phút)

### Mục tiêu

- Dễ kiểm soát kích thước phần tử.

## 2.3. Thực hành (20 phút)

- Dựng card sản phẩm.
- Dùng padding và margin để tạo khoảng thở.

### Mẹo

- Sai box model là lỗi phổ biến nhất khi mới học CSS.

---

# 3. ĐƠN VỊ ĐO LƯỜNG & TYPOGRAPHY (30 PHÚT)

## 3.1. Đơn vị cơ bản (10 phút)

- `px`
- `%`
- `rem`
- `em`

## 3.2. Typography (15 phút)

- `font-family`
- `font-size`
- `font-weight`
- `line-height`

### Ví dụ

```css
body {
	font-family: Arial, sans-serif;
	font-size: 16px;
	line-height: 1.6;
}
```

### Mẹo thực tế

- Chữ đẹp không phải là font lạ, mà là chữ dễ đọc và có nhịp điệu.

## 3.3. Google Fonts (5 phút)

- Cách nhúng font.
- Khi nào nên dùng font web.

---

# 4. THỰC HÀNH & TOP 5 NHANH NHẤT (30 PHÚT)

## Bài tập

- Làm card có ảnh, tiêu đề, mô tả, giá tiền.
- Dùng đúng box model.
- Tùy biến typography cho dễ đọc.

### Khung gợi ý

```html
<div class="card">
	<img src="product.jpg" alt="Sản phẩm">
	<h3>Tên sản phẩm</h3>
	<p>Mô tả ngắn.</p>
	<strong>500.000đ</strong>
</div>
```

### Bonus cuối buổi

- 5 bạn đúng và nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 5

- Hiểu box model.
- Dùng được `box-sizing`.
- Biết chọn đơn vị và chỉnh chữ hợp lý.
