# KẾ HOẠCH CHI TIẾT: BUỔI 1 - CÀI ĐẶT & THẺ VĂN BẢN CƠ BẢN

**Tổng thời gian: 90 phút**

---

# 1. GIỚI THIỆU KHÓA HỌC & CÀI ĐẶT CÔNG CỤ (20 PHÚT)

## 1.1. Mở đầu khóa học (8 phút)

### Mục tiêu

- Học viên hiểu Front-end là gì.
- Hình dung được lộ trình 16 buổi và sản phẩm cuối khóa.
- Tạo động lực học ngay từ đầu.

### Nội dung

Giảng viên giới thiệu ngắn:

> Front-end là phần giao diện và tương tác mà người dùng nhìn thấy, thao tác trực tiếp trên website.

Trình chiếu nhanh:

- Landing page đơn giản.
- Website bán hàng mini.
- Dashboard quản lý cơ bản.

### Mẹo chia sẻ thực tế

- Vì sao phải học theo thứ tự HTML -> CSS -> JavaScript.
- Cách học hiệu quả: nghe, gõ lại, tự sửa lỗi, rồi mới tùy biến.

## 1.2. Cài đặt công cụ (12 phút)

### Cần chuẩn bị

- Visual Studio Code.
- Trình duyệt Google Chrome.

### Extension nên cài

- Live Server.
- Prettier.
- Auto Rename Tag.
- Path Intellisense.

### Lưu ý

- Không dành quá nhiều thời gian fix từng máy.
- Lỗi cá nhân sẽ xử lý sau buổi học.
- Ưu tiên giữ nhịp cho cả lớp.

---

# 2. HTML5 CƠ BẢN & THẺ VĂN BẢN (35 PHÚT)

## 2.1. Tạo cấu trúc HTML5 chuẩn (10 phút)

### Thực hành

Tạo file:

```html
index.html
```

Gõ:

```html
!
```

Nhấn `Enter` để sinh khung HTML5.

### Giải thích nhanh

- `<!DOCTYPE html>`: khai báo chuẩn HTML5.
- `<html>`: thẻ gốc của tài liệu.
- `<head>`: phần cấu hình.
- `<body>`: phần hiển thị trên màn hình.

## 2.2. Thẻ văn bản cơ bản (25 phút)

### Nội dung cần luyện

- Tiêu đề `h1` đến `h6`.
- Đoạn văn `p`.
- In đậm `strong`, `b`.
- In nghiêng `em`, `i`.
- Gạch ngang `del`.
- Chữ nhỏ `small`.
- Chỉ số dưới `sub`.
- Chỉ số trên `sup`.

### Kiến thức lồng ghép

- Element là một phần tử HTML.
- Attribute là thuộc tính đi kèm thẻ.
- Comment dùng để ghi chú code.

### Ví dụ minh họa nhanh

```html
<h1>Giới thiệu bản thân</h1>
<p>Tôi đang học Front-end cơ bản.</p>
<p><strong>Mục tiêu:</strong> làm được website đầu tiên.</p>
```

### Lỗi thường gặp

- Dùng quá nhiều `h1` trong cùng một trang.
- Trộn `b` và `strong` mà không hiểu mục đích.
- Quên đóng thẻ hoặc đặt thẻ sai vị trí.

### Thực hành nhanh

- Tạo một đoạn giới thiệu bản thân.
- Đặt tiêu đề trang.
- Chèn comment để đánh dấu phần code.

### Mẹo chia sẻ thực tế

- Đặt tiêu đề ngắn, rõ ý.
- Đừng lạm dụng quá nhiều thẻ định dạng trong một đoạn.

---

# 3. HÌNH ẢNH - LIÊN KẾT - ĐƯỜNG DẪN (35 PHÚT)

## 3.1. Thẻ hình ảnh `img` (12 phút)

### Nội dung

- `src` là đường dẫn ảnh.
- `alt` là nội dung thay thế khi ảnh lỗi.

### Thực hành

- Chèn ảnh cá nhân.
- Thử sửa đường dẫn sai để thấy ảnh vỡ.

## 3.2. Đường dẫn tuyệt đối và tương đối (10 phút)

### Phân biệt

- Đường dẫn tuyệt đối: lấy trực tiếp từ internet.
- Đường dẫn tương đối: ảnh nằm trong dự án.

### Mẹo

- Khi làm bài thật, ưu tiên để tài nguyên cùng thư mục dự án để dễ quản lý.

## 3.3. Thẻ liên kết `a` (13 phút)

### Nội dung

- `href`: địa chỉ chuyển hướng.
- `target="_blank"`: mở tab mới.

### Thực hành

- Tạo liên kết Facebook.
- Tạo liên kết GitHub.
- Lồng link vào ảnh hoặc nút chữ.

---

# 4. BỌC LAYOUT BẰNG DIV (30 PHÚT)

## 4.1. Tư duy chia khối (10 phút)

### Mục tiêu

- Hiểu HTML không chỉ để hiển thị chữ.
- Biết tổ chức nội dung thành từng khối.

### Nội dung

- Header.
- Main.
- Footer.
- Khối thông tin cá nhân.
- Khối sở thích.

## 4.2. Thực hành bọc khối (20 phút)

### Bài mẫu

- 1 ảnh đại diện.
- 1 họ tên.
- 1 đoạn mô tả ngắn.
- 1 liên kết mạng xã hội.

### Mẹo

- Dùng `div` để gom nhóm nội dung trước.
- Sau này Flexbox và Grid sẽ dễ làm việc hơn.

---

# 5. CODE-ALONG & NGHIỆM THU NHANH (30 PHÚT)

## 5.1. Làm bài cùng giảng viên (15 phút)

- Dựng một trang giới thiệu cá nhân đơn giản.
- Có ảnh, tên, mô tả, link.
- Có ít nhất 2 thẻ định dạng chữ.

### Khung gợi ý

```html
<div>
	<img src="avatar.jpg" alt="Avatar">
	<h1>Nguyễn Văn A</h1>
	<p>Một đoạn giới thiệu ngắn về bản thân.</p>
</div>
```

## 5.2. Nghiệm thu mini (15 phút)

### Yêu cầu

- Hoàn thành đúng cấu trúc.
- Không lỗi đường dẫn ảnh.
- Không quên đóng thẻ.

### Bonus cuối buổi

- 5 bạn nộp nhanh nhất và đúng yêu cầu được cộng `+1` điểm.

---

# KẾT QUẢ ĐẦU RA SAU BUỔI 1

Sau buổi học, học viên cần:

- Tạo được file HTML5 chuẩn.
- Sử dụng được các thẻ văn bản cơ bản.
- Chèn ảnh và tạo liên kết.
- Phân biệt được đường dẫn tuyệt đối và tương đối.
- Hiểu cách bọc layout bằng `div`.
- Hoàn thành một trang giới thiệu cá nhân đơn giản.
