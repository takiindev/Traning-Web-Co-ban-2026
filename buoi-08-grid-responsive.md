# KẾ HOẠCH CHI TIẾT: BUỔI 8 - CSS GRID & RESPONSIVE DESIGN

**Tổng thời gian: 90 phút**

---

# 1. MỞ ĐẦU (10 PHÚT)

- Ôn Flexbox.
- Dẫn vào layout nhiều chiều.

---

# 2. CSS GRID (50 PHÚT)

## 2.1. Khái niệm (15 phút)

- Grid container.
- Grid item.
- Layout theo hàng và cột.

## 2.2. Thuộc tính quan trọng (20 phút)

- `grid-template-columns`
- `grid-template-rows`
- `gap`
- `grid-column`
- `grid-row`

## 2.3. Thực hành (15 phút)

- Làm lưới sản phẩm.
- Dựng bố cục dashboard.

### Mẹo thực tế

- Grid rất hợp cho layout tổng thể và khu vực nhiều ô.

---

# 3. RESPONSIVE DESIGN (60 PHÚT)

## 3.1. Nguyên tắc & tư duy (10 phút)

- Mobile-first: viết CSS cho màn hình nhỏ trước, sau đó mở rộng bằng media queries.
- Fluid layout: dùng phần trăm, `vw`, `vh`, `max-width` để phần tử co dãn theo viewport.
- Progressive enhancement: bắt đầu từ nội dung cơ bản, thêm layout/hiệu ứng cho màn hình lớn.

## 3.2. Đơn vị & kỹ thuật (10 phút)

- `%`, `vw`/`vh` — cho kích thước linh hoạt.
- `rem`/`em` — cho kiểu chữ và khoảng cách theo tỉ lệ.
- `clamp()` — giới hạn kích thước chữ (ví dụ: `font-size: clamp(1rem, 2.5vw, 1.5rem);`).
- `min()`, `max()` hữu ích khi kết hợp với `clamp()`.

## 3.3. Grid + Flex trong responsive (10 phút)

- Kết hợp `grid` cho layout tổng thể và `flex` cho thành phần xếp hàng/ô nhỏ.
- Sử dụng `grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));` để tạo lưới linh hoạt.

## 3.4. Media queries & breakpoints (10 phút)

- Nguyên tắc: đặt breakpoint theo nội dung (content-driven), không phải chỉ theo thiết bị.
- Ví dụ phổ biến (mobile-first):

```css
/* Mobile first */
.container { grid-template-columns: 1fr; }

@media (min-width: 600px) {
	.container { grid-template-columns: repeat(2, 1fr); }
}

@media (min-width: 900px) {
	.container { grid-template-columns: repeat(3, 1fr); }
}
```

## 3.5. Hình ảnh và media responsive (5 phút)

- `srcset` + `sizes` và thẻ `<picture>` để phục vụ ảnh phù hợp với viewport và DPR.
- Kỹ thuật lazy-loading (`loading="lazy"`) để tối ưu hiệu năng.

Ví dụ ngắn:

```html
<img src="image-800.jpg" srcset="image-400.jpg 400w, image-800.jpg 800w, image-1200.jpg 1200w" sizes="(max-width: 600px) 100vw, 33vw" alt="...">
```

## 3.6. Responsive typography & scale (5 phút)

- Sử dụng `clamp()` để có tỷ lệ chữ mượt giữa các breakpoint.
- Line-height, max-width (chữ đọc tốt ở 60–75 ký tự/ dòng).

## 3.7. Kiểm thử & accessibility (5 phút)

- Test trên nhiều kích thước: DevTools responsive, thiết bị thật.
- Kiểm tra tương phản màu sắc, kích thước touch targets, và thứ tự DOM.

## 3.8. Bài tập thực hành (10 phút)

- Bài 1: Chỉnh sửa layout lưới sản phẩm dùng `auto-fit`/`minmax` để hiển thị 1/2/3 cột tùy viewport.
- Bài 2: Thêm `srcset` cho ảnh sản phẩm và tối ưu typography bằng `clamp()`.

---

_Ghi chú_: Nội dung trên được soạn theo các nguyên tắc Responsive Web Design. Nếu bạn muốn tôi trích dẫn hoặc chuyển đổi trực tiếp các mục từ `Responsive Web Design.pdf`, gửi cho tôi file (hoặc cho phép tôi truy xuất nội dung cụ thể) để mình căn chỉnh chính xác theo tài liệu đó.

---

# 4. THỰC HÀNH & BONUS (35 PHÚT)

## Bài tập

- Dựng trang sản phẩm responsive.

### Bonus cuối buổi

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 8

- Dùng được CSS Grid.
- Biết viết media queries.
- Làm được giao diện thích ứng cơ bản.
