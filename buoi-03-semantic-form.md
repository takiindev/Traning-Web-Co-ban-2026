# KẾ HOẠCH CHI TIẾT: BUỔI 3 - BLOCK/INLINE, SEMANTIC HTML5 & FORM

**Tổng thời gian: 90 phút**

---

# 1. KHỞI ĐỘNG & ÔN NHANH (15 PHÚT)

## 1.1. Nhắc lại buổi trước (5 phút)

- Danh sách.
- Bảng.
- Multimedia.

## 1.2. Mục tiêu buổi học (10 phút)

- Phân biệt block và inline.
- Biết dùng semantic HTML5.
- Tạo form cơ bản.

---

# 2. BLOCK VS INLINE (25 PHÚT)

## 2.1. Khái niệm (10 phút)

### Block

- Chiếm full hàng.
- Dễ tạo layout.

### Inline

- Nằm cùng hàng.
- Thường dùng cho text nhỏ.

## 2.2. Thực hành (15 phút)

- Quan sát `div`, `p`, `h1`.
- Quan sát `span`, `a`, `strong`.
- Tạo ví dụ mix block và inline.

### Ví dụ minh họa

```html
<div>
	<p>Đây là block.</p>
	<a href="#">Đây là inline</a>
</div>
```

### Lỗi thường gặp

- Cho rằng inline không thể nằm trong block.
- Dùng `span` cho mọi thứ mà quên mất ngữ cảnh ngữ nghĩa.

### Mẹo

- Khi chưa chắc, hãy nhìn bằng DevTools để hiểu phần tử đang chiếm chỗ thế nào.

---

# 3. SEMANTIC HTML5 (35 PHÚT)

## 3.1. Các thẻ chính (20 phút)

- `header`
- `nav`
- `main`
- `section`
- `article`
- `aside`
- `footer`

## 3.2. Thực hành khung trang (15 phút)

- Dựng trang tin tức.
- Dựng trang giới thiệu sản phẩm.
- Dựng bố cục blog mini.

### Gợi ý cấu trúc

```html
<header></header>
<nav></nav>
<main>
	<section></section>
	<aside></aside>
</main>
<footer></footer>
```

### Mẹo thực tế

- Semantic giúp code dễ đọc, dễ bảo trì, dễ chấm bài.

---

# 4. FORM CƠ BẢN (45 PHÚT)

## 4.1. Cấu trúc form (15 phút)

- `form`
- `label`
- `input`
- `textarea`
- `select`/`option`

## 4.2. Các loại input hay dùng (20 phút)

- `text`
- `email`
- `password`
- `date`
- `radio`
- `checkbox`
- `file`

## 4.3. Thực hành (10 phút)

- Form đăng ký.
- Form liên hệ.

### Mẫu form ngắn

```html
<form>
	<label for="email">Email</label>
	<input id="email" type="email" placeholder="Nhập email">
</form>
```

### Lỗi thường gặp

- Quên `label`.
- Để `input` không có `name`.
- Không kiểm tra trạng thái `required`.

---

# 5. CODE-ALONG & TOP 5 NHANH NHẤT (30 PHÚT)

## 5.1. Bài tập

- Dựng trang có header, main, footer.
- Trong main có một form liên hệ.

## 5.2. Nghiệm thu

- Kiểm tra block/inline.
- Kiểm tra semantic đúng chỗ.

### Bonus cuối buổi

- 5 bạn nộp đúng và nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 3

- Phân biệt được block và inline.
- Dùng được semantic HTML5.
- Tạo được form cơ bản.
