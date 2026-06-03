# KẾ HOẠCH CHI TIẾT: BUỔI 2 - DANH SÁCH, BẢNG & ĐA PHƯƠNG TIỆN

**Tổng thời gian: 150 phút**

---

# 1. ÔN NHANH BUỔI TRƯỚC & DẪN VÀO BUỔI MỚI (15 PHÚT)

## 1.1. Check lại kiến thức cũ (5 phút)

- Cấu trúc HTML5.
- Ảnh và link.
- Cách chia khối bằng `div`.
- Nhắc nhanh lại ý nghĩa của `img`, `a`, `div`.

### Mục tiêu

- Củng cố để học viên không bị đứt mạch giữa các buổi.
- Chuyển từ nội dung đơn lẻ sang nội dung có cấu trúc.

## 1.2. Mục tiêu buổi học (10 phút)

- Biết tạo danh sách đúng ngữ cảnh.
- Biết dựng bảng dữ liệu rõ ràng, dễ đọc.
- Biết nhúng video, audio, iframe.
- Biết chọn đúng thẻ cho từng loại nội dung.

### Mẹo thực tế

- Các website bán hàng, blog, tin tức đều dùng danh sách và bảng rất nhiều.
- Danh sách dùng cho nhóm item lặp lại.
- Bảng dùng khi cần so sánh theo hàng/cột.

---

# 2. DANH SÁCH TRONG HTML (35 PHÚT)

## 2.1. Danh sách không thứ tự `ul`, `li` (15 phút)

### Nội dung

- Khi nào nên dùng `ul`.
- Cách lồng `li`.
- Tạo menu hoặc danh sách tính năng.
- Phân biệt danh sách đơn và danh sách lồng nhiều cấp.

### Ví dụ

```html
<ul>
	<li>HTML</li>
	<li>CSS</li>
	<li>JavaScript</li>
</ul>
```

### Giải thích nhanh

- Mỗi `li` là một mục độc lập.
- Khi danh sách có nhiều mục tương tự nhau, nên nghĩ đến `ul` đầu tiên.

## 2.2. Danh sách có thứ tự `ol`, `li` (10 phút)

### Nội dung

- Dùng cho quy trình.
- Dùng cho bước làm.
- Dùng cho timeline.
- Có thể thay đổi kiểu đánh số nếu cần.

### Ví dụ

```html
<ol>
	<li>Mở trình duyệt</li>
	<li>Nhập địa chỉ</li>
	<li>Nhấn Enter</li>
</ol>
```

## 2.3. Danh sách mô tả `dl`, `dt`, `dd` (10 phút)

### Nội dung

- `dl` dùng cho nhóm khái niệm.
- `dt` là tên mục.
- `dd` là phần giải thích.

### Thực hành

- Tạo danh sách kỹ năng.
- Tạo danh sách câu hỏi - trả lời.
- Tạo một nhóm thuật ngữ nhỏ cho buổi học.

### Lỗi thường gặp

- Dùng `ul` cho mọi thứ mà không phân biệt mục đích.
- Lồng danh sách quá sâu khiến học viên khó đọc code.

---

# 3. BẢNG DỮ LIỆU (35 PHÚT)

## 3.1. Cấu trúc bảng cơ bản (15 phút)

### Thành phần

- `table`
- `thead`
- `tbody`
- `tr`
- `th`
- `td`

### Ví dụ

```html
<table>
	<thead>
		<tr>
			<th>Tên</th>
			<th>Lớp</th>
			<th>Điểm</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>An</td>
			<td>FE01</td>
			<td>9</td>
		</tr>
	</tbody>
</table>
```

### Thực hành

- Bảng điểm.
- Bảng sản phẩm.
- Bảng thời khóa biểu.

### Mẹo thực tế

- Dựng hàng tiêu đề trước rồi mới thêm dữ liệu.
- Nếu bảng nhiều cột, nên kiểm tra lại từng ô để tránh lệch cột.

## 3.2. Gộp cột, gộp dòng (20 phút)

### Thuộc tính

- `colspan`
- `rowspan`

### Mẹo

- Không cố nhồi dữ liệu vào bảng nếu nội dung quá dài.
- Bảng nên ngắn, rõ, dễ quét.
- Gộp ô chỉ dùng khi thật sự giúp trình bày dễ hiểu hơn.

---

# 4. NHÚNG ĐA PHƯƠNG TIỆN (35 PHÚT)

## 4.1. Video và audio (15 phút)

### Nội dung

- `video`
- `audio`
- `controls`
- `autoplay`
- `muted`

### Ví dụ

```html
<video controls width="320">
	<source src="movie.mp4" type="video/mp4">
</video>
```

### Gợi ý giảng dạy

- Nếu video không phát, kiểm tra lại định dạng file và đường dẫn.
- Giải thích tại sao `muted` thường đi cùng `autoplay`.

## 4.2. iframe (20 phút)

### Ứng dụng

- Nhúng YouTube.
- Nhúng Google Maps.
- Nhúng trang web khác.

### Ví dụ

```html
<iframe
	width="560"
	height="315"
	src="https://www.youtube.com/embed/..."
	title="YouTube video"
	allowfullscreen>
</iframe>
```

### Mẹo thực tế

- iframe rất hữu ích nhưng phải dùng có kiểm soát để không làm nặng trang.
- Nên giữ tỷ lệ khung rõ ràng để không vỡ layout.

---

# 5. THỰC HÀNH & TOP 5 NHANH NHẤT (30 PHÚT)

## 5.1. Bài tập

- Tạo danh sách món ăn.
- Tạo bảng thông tin lớp học.
- Nhúng một video và một iframe.
- Mỗi học viên hoàn thành một phần nhỏ rồi ghép lại thành sản phẩm hoàn chỉnh.

## 5.2. Nghiệm thu nhanh

- Kiểm tra cú pháp.
- Kiểm tra hiển thị.
- Kiểm tra đường dẫn.
- Nhìn lại xem đã dùng đúng thẻ theo ngữ cảnh hay chưa.

### Bonus cuối buổi

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

### Ghi nhận

- Top 5 được ghi lại theo thứ tự nộp bài.
- Chỉ tính khi bài chạy được và đúng yêu cầu.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 2

- Tạo được các loại danh sách.
- Dựng được bảng có gộp ô.
- Nhúng được video, audio, iframe.
- Phân biệt được ngữ cảnh dùng danh sách và bảng.

