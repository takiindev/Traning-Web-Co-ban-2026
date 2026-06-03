# KẾ HOẠCH CHI TIẾT: BUỔI 4 - SELECTOR CƠ BẢN, RELATIONAL SELECTORS & BACKGROUND

**Tổng thời gian: 150 phút**

---

# 1. MỞ ĐẦU & ÔN NỀN (15 PHÚT)

## 1.1. Nhắc lại HTML (5 phút)

- Semantic.
- Form.
- Block/inline.

## 1.2. Mục tiêu buổi học (10 phút)

- Biết 3 cách chèn CSS.
- Biết bộ chọn cơ bản.
- Biết background và màu sắc.

---

# 2. CÁCH CHÈN CSS & SPECIFICITY (25 PHÚT)

## 2.1. 3 cách chèn CSS (15 phút)

- Inline CSS.
- Internal CSS.
- External CSS.

## 2.2. Độ ưu tiên (10 phút)

- Khi nào CSS nào thắng.
- Vì sao nên ưu tiên file CSS riêng.

### Mẹo

- Làm dự án thật nên giữ CSS sạch, tách file rõ ràng.

---

# 3. SELECTOR CƠ BẢN & COMBINATOR (40 PHÚT)

## 3.1. Selector cơ bản (15 phút)

- Tag selector.
- Class selector.
- Id selector.
- Universal selector.

### Ví dụ

```css
* {
	box-sizing: border-box;
}

.card {
	padding: 16px;
}

#header {
	background: #111;
}
```

### Lỗi thường gặp

- Dùng `id` cho quá nhiều phần tử.
- Viết selector quá dài và khó bảo trì.

## 3.2. Selector tổ hợp (25 phút)

- Descendant.
- Child.
- Adjacent sibling.
- General sibling.

### Thực hành

- Tô màu menu.
- Đổi style một khối con.
- Chọn phần tử liền kề.

---

# 4. MÀU SẮC & BACKGROUND (35 PHÚT)

## 4.1. Màu sắc (15 phút)

- HEX.
- RGB.
- RGBA.

## 4.2. Background (20 phút)

- `background-color`.
- `background-image`.
- `background-size`.
- `background-position`.
- `background-repeat`.

### Ví dụ

```css
.hero {
	background-image: url('../images/banner.jpg');
	background-size: cover;
	background-position: center;
	background-repeat: no-repeat;
}
```

### Mẹo thực tế

- Nền đẹp nhưng phải dễ đọc chữ.
- Đừng làm ảnh nền quá nặng.

---

# 5. THỰC HÀNH & BONUS (35 PHÚT)

## 5.1. Bài tập

- Tạo card sản phẩm có ảnh nền.
- Tô màu menu bằng selector tổ hợp.

## 5.2. Nghiệm thu nhanh

- CSS tách file.
- Selector đúng.
- Background hiển thị chuẩn.

### Bonus cuối buổi

- 5 bạn hoàn thành nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 4

- Viết được selector cơ bản.
- Hiểu relational selectors.
- Dùng được background và màu sắc.
