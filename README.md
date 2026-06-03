# Web Cơ Bản Hè 2026

## Mục lục nhanh các buổi

- [Buổi 1: Cài đặt & thẻ văn bản cơ bản](./buoi-01-cai-dat-the-van-ban-co-ban.md)
- [Buổi 2: Danh sách, bảng, đa phương tiện](./buoi-02-danh-sach-bang-da-phuong-tien.md)
- [Buổi 3: Semantic & Form](./buoi-03-semantic-form.md)
- [Buổi 4: CSS selector & background](./buoi-04-css-selector-background.md)
- [Buổi 5: Box model & typography](./buoi-05-box-model-typography.md)
- [Buổi 6: Position & variables](./buoi-06-position-variables.md)
- [Buổi 7: Flexbox](./buoi-07-flexbox.md)
- [Buổi 8: Grid & responsive](./buoi-08-grid-responsive.md)
- [Buổi 9: Pseudo, BEM, animation](./buoi-09-pseudo-bem-animation.md)
- [Buổi 10: JS cơ bản & control flow](./buoi-10-js-co-ban-control-flow.md)
- [Buổi 11: ES6, function, module](./buoi-11-es6-functions-module.md)
- [Buổi 12: Array methods & timers](./buoi-12-array-methods-timers.md)
- [Buổi 13: DOM manipulation](./buoi-13-dom-manipulation.md)
- [Buổi 14: Form validation & regex](./buoi-14-form-validation-regex.md)
- [Buổi 15: Async, fetch, CRUD](./buoi-15-async-fetch-crud.md)
- [Buổi 16: State, localStorage, auth](./buoi-16-state-localstorage-auth.md)
- [Nghiệm thu cuối khóa](./nghiem-thu-cuoi-khoa.md)

**PHẦN 1: HTML5 - NỀN TẢNG CẤU TRÚC (Buổi 1 - 3)**

- **Buổi 1: Cài đặt & Thẻ văn bản cơ bản**
    - Cài đặt VS Code, các Extensions: Live Server, Auto Rename Tag, Prettier.
    - Cấu trúc file HTML5 chuẩn (**`!DOCTYPE`**, **`html`**, **`head`**, **`body`**).
    - Các thẻ tiêu đề (**`h1-h6`**), đoạn văn (**`p`**), định dạng văn bản (**`b`**, **`strong`**, **`i`**, **`em`**...).
    - Thẻ liên kết (**`a`**) và Thẻ hình ảnh (**`img`**).
    - **Tư duy quan trọng:** Giải thích tại sao phải bọc layout (wrapping) và ảnh hưởng của nó đến Flexbox / Grid sau này.
- **Buổi 2: Danh sách, Bảng & Đa phương tiện**
    - Danh sách: **`ul`**, **`ol`**, **`li`** và các kiểu đánh số.
    - Bảng: **`table`**, **`thead`**, **`tbody`**, **`tr`**, **`th`**, **`td`** và thuộc tính **`colspan`**, **`rowspan`**.
    - Nhúng Multimedia: **`video`**, **`audio`** (controls, autoplay, muted) và **`iframe`** để nhúng bản đồ/Youtube.
- **Buổi 3: HTML5 Semantic & Form (Nâng cao)**
    - Phân biệt thẻ **Block** và **Inline**.
    - Thẻ ngữ nghĩa (Semantic HTML5): **`header`**, **`nav`**, **`main`**, **`footer`**, **`section`**, **`article`**, **`aside`**.
    - Cấu trúc Form: **`form`**, **`label`**, **`input`** (text, email, password, date, radio, checkbox, file...), **`select/option`**, **`textarea`**.

**PHẦN 2: CSS3 - GIAO DIỆN & BỐ CỤC (Buổi 4 - 9)**

- **Buổi 4: Selector Cơ bản & Relational Selectors**
    - 3 cách chèn CSS và Độ ưu tiên (Specificity).
    - **Universal Selector ()** để reset CSS.
    - **Bộ chọn tổ hợp (Combinators):** Descendant (khoảng trắng), **Child (>)**, **Adjacent Sibling (+)**, **General Sibling (~)**.
    - Màu sắc (HEX, RGB) và Background (image, size, position, repeat).
- **Buổi 5: Box Model & Typography**
    - Chi tiết **Box Model**: Content, Padding, Border, Margin.
    - Thuộc tính **box-sizing: border-box**.
    - Đơn vị đo lường: **`px`**, **`%`**, **`rem`**, **`em`**.
    - Fonts: **`font-family`**, **`font-weight`**, **`font-size`**, nhúng Google Fonts.
- **Buổi 6: Positioning & Variables**
    - Các giá trị **`position`**: **`static`**, **`relative`**, **`absolute`**, **`fixed`**, **`sticky`**.
    - Quản lý lớp hiển thị với **`z-index`**.
    - **CSS Variables**: Khai báo biến trong **`:root`** để tái sử dụng mã nguồn.
- **Buổi 7: Flexbox - Tư duy dàn trang hiện đại**
    - Flex-container: **`display: flex`**, **`flex-direction`**, **`justify-content`**, **`align-items`**, **`flex-wrap`**.
    - Flex-items: **`flex-grow`**, **`flex-shrink`**, **`order`**, **`align-self`**.
- **Buổi 8: CSS Grid & Responsive Design**
    - Giới thiệu CSS Grid cho các layout phức tạp.
    - **Media Queries**: Thiết kế giao diện thích ứng cho Mobile, Tablet và Desktop.
- **Buổi 9: Pseudo-classes, Pseudo-elements & BEM**
    - **Pseudo-classes**: **`:hover`**, **`:focus`**, **`:nth-child()`**, **`:first-child`**, **`:last-child`**, và đặc biệt là bộ chọn hiện đại **:has()** [72, 73, 550, Image 8].
    - **Pseudo-elements**: **`::before`**, **`::after`** kết hợp với thuộc tính **`content`**.
    - Quy chuẩn đặt tên **BEM** (Block-Element-Modifier) để tránh xung đột code [Image 1, 15].
    - CSS Animations & Transitions: **`@keyframes`**.

**PHẦN 3: JAVASCRIPT - LOGIC & DỮ LIỆU (Buổi 10 - 16)**

- **Buổi 10: JS Cơ bản & Cấu trúc điều khiển**
    - Giới thiệu ngôn ngữ, kiểu dữ liệu và các "tricks" Coercion (ví dụ: **`1 + "1" = "11"`**).
    - Cấu trúc **`if-else`**, **`switch-case`**, vòng lặp **`for`**, **`while`**.
- **Buổi 11: Modern JS (ES6+) & Functions**
    - Cú pháp ES6: **`const/let`**, Arrow functions, Destructuring, Spread operator (**`...`**).
    - Tư duy Module: **`import/export`** file JS.
- **Buổi 12: Xử lý Mảng & Hàm định thời**
    - Các phương thức xử lý mảng (Array Methods): **`map`**, **`filter`**, **`reduce`**, **`find`**, **`some`**, **`forEach`**.
    - Hàm định thời: **`setTimeout`**, **`setInterval`**.
- **Buổi 13: DOM Manipulation**
    - Truy xuất phần tử DOM (**`querySelector`**, **`getElementById`**).
    - Thay đổi nội dung (**`innerHTML`**, **`innerText`**), thuộc tính (**`setAttribute`**), class (**`classList`**).
    - Lắng nghe sự kiện: **`click`**, **`scroll`**, **`input`**, **`blur`**.
- **Buổi 14: Form Logic & Real-time Validation**
    - Xử lý dữ liệu từ Form.
    - **Real-time Validation**: Bắt sự kiện **`input/blur`** để báo lỗi ngay lập tức mà không cần đợi submit.
    - Sử dụng Regex (**`pattern`**) để kiểm tra email, SĐT.
- **Buổi 15: Asynchronous JS & CRUD với Fake API**
    - Bất đồng bộ với Fetch API.
    - Sử dụng **`json-server`** để tạo Fake REST API với 3 bảng: **`Products`**, **`Users`**, **`Orders`**.
    - Thực hiện các thao tác CRUD: Đọc dữ liệu (GET), Thêm mới (POST), Xóa (DELETE) có hộp thoại xác nhận.
- **Buổi 16: State Management, LocalStorage & Auth**
    - Tư duy quản lý State: Luồng **Action -> State -> Render** (tiền đề cho React).
    - Xử lý Đăng ký/Đăng nhập và lưu **`userId`** vào **`localStorage`**.
    - Bảo mật luồng đi: Kiểm tra **`localStorage`** để chặn truy cập trang Admin nếu chưa đăng nhập.

**TỔNG KẾT NHÂN SỰ ĐỨNG LỚP (16 BUỔI)**

**Giai Đoạn 1: Từ Buổi 1 Đến Buổi 8 (Đầy đủ nhân sự)**
• Buổi 1 Nhóm Quý - Vân.  
• Buổi 2 Nhóm Khang - Hoàng.  
• Buổi 3 Nhóm Vũ - Quý.  
• Buổi 4 Nhóm Vân - Khang.  
• Buổi 5 Nhóm Hoàng - Vũ.  
• Buổi 6 Nhóm Quý - Vân.  
• Buổi 7 Nhóm Khang - Hoàng.  
• Buổi 8 Nhóm Vũ - Quý.  
**Giai Đoạn 2: Từ Buổi 9 Đến Buổi 16 ( 1 Nhân sự không tham gia chính thức)**
• Buổi 9 Nhóm Khang - Hoàng.
• Buổi 10 Nhóm Hoàng - Vũ.  
• Buổi 11 Nhóm Quý - Khang.
• Buổi 12 Nhóm Khang - Hoàng.  
• Buổi 13 Nhóm Vũ - Quý.  
• Buổi 14 Nhóm Hoàng - Khang.
• Buổi 15 Nhóm Hoàng - Vũ.  
• Buổi 16 Nhóm Vũ - Quý.

| **Người đứng** | **Tổng số buổi đứng lớp** | **Danh sách các buổi phụ trách** |
| --- | --- | --- |
| **Vũ** | **6 buổi** | Buổi 3, 5, 8, 10, 13, 15, 16 |
| **Quý** | **6 buổi** | Buổi 1, 3, 6, 8, 11, 13, 16 |
| **Khang** | **6 buổi** | Buổi 2, 4, 7, 9, 11, 12, 14 |
| **Hoàng** | **6 buổi** | Buổi 2, 5, 7, 9, 10, 12, 14, 15 |
| **Vân** | **3 buổi** | Buổi 1, 4, 6 (Nghỉ từ giai đoạn 2) |

# Chi tiết các buổi:

# **KẾ HOẠCH CHI TIẾT: BUỔI 1 - CÀI ĐẶT & THẺ VĂN BẢN CƠ BẢN**

**Tổng thời gian: 150 phút**

---

# **1. GIỚI THIỆU KHÓA HỌC & CÀI ĐẶT CÔNG CỤ (20 PHÚT)**

## **1.1. Mở đầu khóa học (8 phút)**

### **Mục tiêu**

- Học viên hiểu Front-end là gì.
- Hình dung được lộ trình 16 buổi và sản phẩm cuối khóa.
- Tạo động lực học ngay từ đầu.

### **Nội dung**

Giảng viên giới thiệu ngắn:

> Front-end là phần giao diện và tương tác mà người dùng nhìn thấy, thao tác trực tiếp trên website.
> 

Trình chiếu nhanh:

- Landing page đơn giản.
- Website bán hàng mini.
- Dashboard quản lý cơ bản.

### **Mẹo chia sẻ thực tế**

- Vì sao phải học theo thứ tự HTML -> CSS -> JavaScript.
- Cách học hiệu quả: nghe, gõ lại, tự sửa lỗi, rồi mới tùy biến.

## **1.2. Cài đặt công cụ (12 phút)**

### **Cần chuẩn bị**

- Visual Studio Code.
- Trình duyệt Google Chrome.

### **Extension nên cài**

- Live Server.
- Prettier.
- Auto Rename Tag.
- Path Intellisense.

### **Lưu ý**

- Không dành quá nhiều thời gian fix từng máy.
- Lỗi cá nhân sẽ xử lý sau buổi học.
- Ưu tiên giữ nhịp cho cả lớp.

---

# **2. HTML5 CƠ BẢN & THẺ VĂN BẢN (35 PHÚT)**

## **2.1. Tạo cấu trúc HTML5 chuẩn (10 phút)**

### **Thực hành**

Tạo file:

```html
index.html
```

Gõ:

```html
!
```

Nhấn `Enter` để sinh khung HTML5.

### **Giải thích nhanh**

- `<!DOCTYPE html>`: khai báo chuẩn HTML5.
- `<html>`: thẻ gốc của tài liệu.
- `<head>`: phần cấu hình.
- `<body>`: phần hiển thị trên màn hình.

## **2.2. Thẻ văn bản cơ bản (25 phút)**

### **Nội dung cần luyện**

- Tiêu đề `h1` đến `h6`.
- Đoạn văn `p`.
- In đậm `strong`, `b`.
- In nghiêng `em`, `i`.
- Gạch ngang `del`.
- Chữ nhỏ `small`.
- Chỉ số dưới `sub`.
- Chỉ số trên `sup`.

### **Kiến thức lồng ghép**

- Element là một phần tử HTML.
- Attribute là thuộc tính đi kèm thẻ.
- Comment dùng để ghi chú code.

### **Ví dụ minh họa nhanh**

```html
<h1>Giới thiệu bản thân</h1>
<p>Tôi đang học Front-end cơ bản.</p>
<p><strong>Mục tiêu:</strong> làm được website đầu tiên.</p>
```

### **Lỗi thường gặp**

- Dùng quá nhiều `h1` trong cùng một trang.
- Trộn `b` và `strong` mà không hiểu mục đích.
- Quên đóng thẻ hoặc đặt thẻ sai vị trí.

### **Thực hành nhanh**

- Tạo một đoạn giới thiệu bản thân.
- Đặt tiêu đề trang.
- Chèn comment để đánh dấu phần code.

### **Mẹo chia sẻ thực tế**

- Đặt tiêu đề ngắn, rõ ý.
- Đừng lạm dụng quá nhiều thẻ định dạng trong một đoạn.

---

# **3. HÌNH ẢNH - LIÊN KẾT - ĐƯỜNG DẪN (35 PHÚT)**

## **3.1. Thẻ hình ảnh `img` (12 phút)**

### **Nội dung**

- `src` là đường dẫn ảnh.
- `alt` là nội dung thay thế khi ảnh lỗi.

### **Thực hành**

- Chèn ảnh cá nhân.
- Thử sửa đường dẫn sai để thấy ảnh vỡ.

## **3.2. Đường dẫn tuyệt đối và tương đối (10 phút)**

### **Phân biệt**

- Đường dẫn tuyệt đối: lấy trực tiếp từ internet.
- Đường dẫn tương đối: ảnh nằm trong dự án.

### **Mẹo**

- Khi làm bài thật, ưu tiên để tài nguyên cùng thư mục dự án để dễ quản lý.

## **3.3. Thẻ liên kết `a` (13 phút)**

### **Nội dung**

- `href`: địa chỉ chuyển hướng.
- `target="_blank"`: mở tab mới.

### **Thực hành**

- Tạo liên kết Facebook.
- Tạo liên kết GitHub.
- Lồng link vào ảnh hoặc nút chữ.

---

# **4. BỌC LAYOUT BẰNG DIV (30 PHÚT)**

## **4.1. Tư duy chia khối (10 phút)**

### **Mục tiêu**

- Hiểu HTML không chỉ để hiển thị chữ.
- Biết tổ chức nội dung thành từng khối.

### **Nội dung**

- Header.
- Main.
- Footer.
- Khối thông tin cá nhân.
- Khối sở thích.

## **4.2. Thực hành bọc khối (20 phút)**

### **Bài mẫu**

- 1 ảnh đại diện.
- 1 họ tên.
- 1 đoạn mô tả ngắn.
- 1 liên kết mạng xã hội.

### **Mẹo**

- Dùng `div` để gom nhóm nội dung trước.
- Sau này Flexbox và Grid sẽ dễ làm việc hơn.

---

# **5. CODE-ALONG & NGHIỆM THU NHANH (30 PHÚT)**

## **5.1. Làm bài cùng giảng viên (15 phút)**

- Dựng một trang giới thiệu cá nhân đơn giản.
- Có ảnh, tên, mô tả, link.
- Có ít nhất 2 thẻ định dạng chữ.

### **Khung gợi ý**

```html
<div>
	<img src="avatar.jpg" alt="Avatar">
	<h1>Nguyễn Văn A</h1>
	<p>Một đoạn giới thiệu ngắn về bản thân.</p>
</div>
```

## **5.2. Nghiệm thu mini (15 phút)**

### **Yêu cầu**

- Hoàn thành đúng cấu trúc.
- Không lỗi đường dẫn ảnh.
- Không quên đóng thẻ.

### **Bonus cuối buổi**

- 5 bạn nộp nhanh nhất và đúng yêu cầu được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 1**

Sau buổi học, học viên cần:

- Tạo được file HTML5 chuẩn.
- Sử dụng được các thẻ văn bản cơ bản.
- Chèn ảnh và tạo liên kết.
- Phân biệt được đường dẫn tuyệt đối và tương đối.
- Hiểu cách bọc layout bằng `div`.
- Hoàn thành một trang giới thiệu cá nhân đơn giản.

# **KẾ HOẠCH CHI TIẾT: BUỔI 2 - DANH SÁCH, BẢNG & ĐA PHƯƠNG TIỆN**

**Tổng thời gian: 150 phút**

---

# **1. ÔN NHANH BUỔI TRƯỚC & DẪN VÀO BUỔI MỚI (15 PHÚT)**

## **1.1. Check lại kiến thức cũ (5 phút)**

- Cấu trúc HTML5.
- Ảnh và link.
- Cách chia khối bằng `div`.
- Nhắc nhanh lại ý nghĩa của `img`, `a`, `div`.

### **Mục tiêu**

- Củng cố để học viên không bị đứt mạch giữa các buổi.
- Chuyển từ nội dung đơn lẻ sang nội dung có cấu trúc.

## **1.2. Mục tiêu buổi học (10 phút)**

- Biết tạo danh sách đúng ngữ cảnh.
- Biết dựng bảng dữ liệu rõ ràng, dễ đọc.
- Biết nhúng video, audio, iframe.
- Biết chọn đúng thẻ cho từng loại nội dung.

### **Mẹo thực tế**

- Các website bán hàng, blog, tin tức đều dùng danh sách và bảng rất nhiều.
- Danh sách dùng cho nhóm item lặp lại.
- Bảng dùng khi cần so sánh theo hàng/cột.

---

# **2. DANH SÁCH TRONG HTML (35 PHÚT)**

## **2.1. Danh sách không thứ tự `ul`, `li` (15 phút)**

### **Nội dung**

- Khi nào nên dùng `ul`.
- Cách lồng `li`.
- Tạo menu hoặc danh sách tính năng.
- Phân biệt danh sách đơn và danh sách lồng nhiều cấp.

### **Ví dụ**

```html
<ul>
	<li>HTML</li>
	<li>CSS</li>
	<li>JavaScript</li>
</ul>
```

### **Giải thích nhanh**

- Mỗi `li` là một mục độc lập.
- Khi danh sách có nhiều mục tương tự nhau, nên nghĩ đến `ul` đầu tiên.

## **2.2. Danh sách có thứ tự `ol`, `li` (10 phút)**

### **Nội dung**

- Dùng cho quy trình.
- Dùng cho bước làm.
- Dùng cho timeline.
- Có thể thay đổi kiểu đánh số nếu cần.

### **Ví dụ**

```html
<ol>
	<li>Mở trình duyệt</li>
	<li>Nhập địa chỉ</li>
	<li>Nhấn Enter</li>
</ol>
```

## **2.3. Danh sách mô tả `dl`, `dt`, `dd` (10 phút)**

### **Nội dung**

- `dl` dùng cho nhóm khái niệm.
- `dt` là tên mục.
- `dd` là phần giải thích.

### **Thực hành**

- Tạo danh sách kỹ năng.
- Tạo danh sách câu hỏi - trả lời.
- Tạo một nhóm thuật ngữ nhỏ cho buổi học.

### **Lỗi thường gặp**

- Dùng `ul` cho mọi thứ mà không phân biệt mục đích.
- Lồng danh sách quá sâu khiến học viên khó đọc code.

---

# **3. BẢNG DỮ LIỆU (35 PHÚT)**

## **3.1. Cấu trúc bảng cơ bản (15 phút)**

### **Thành phần**

- `table`
- `thead`
- `tbody`
- `tr`
- `th`
- `td`

### **Ví dụ**

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

### **Thực hành**

- Bảng điểm.
- Bảng sản phẩm.
- Bảng thời khóa biểu.

### **Mẹo thực tế**

- Dựng hàng tiêu đề trước rồi mới thêm dữ liệu.
- Nếu bảng nhiều cột, nên kiểm tra lại từng ô để tránh lệch cột.

## **3.2. Gộp cột, gộp dòng (20 phút)**

### **Thuộc tính**

- `colspan`
- `rowspan`

### **Mẹo**

- Không cố nhồi dữ liệu vào bảng nếu nội dung quá dài.
- Bảng nên ngắn, rõ, dễ quét.
- Gộp ô chỉ dùng khi thật sự giúp trình bày dễ hiểu hơn.

---

# **4. NHÚNG ĐA PHƯƠNG TIỆN (35 PHÚT)**

## **4.1. Video và audio (15 phút)**

### **Nội dung**

- `video`
- `audio`
- `controls`
- `autoplay`
- `muted`

### **Ví dụ**

```html
<video controls width="320">
	<source src="movie.mp4" type="video/mp4">
</video>
```

### **Gợi ý giảng dạy**

- Nếu video không phát, kiểm tra lại định dạng file và đường dẫn.
- Giải thích tại sao `muted` thường đi cùng `autoplay`.

## **4.2. iframe (20 phút)**

### **Ứng dụng**

- Nhúng YouTube.
- Nhúng Google Maps.
- Nhúng trang web khác.

### **Ví dụ**

```html
<iframe
	width="560"
	height="315"
	src="https://www.youtube.com/embed/..."
	title="YouTube video"
	allowfullscreen>
</iframe>
```

### **Mẹo thực tế**

- iframe rất hữu ích nhưng phải dùng có kiểm soát để không làm nặng trang.
- Nên giữ tỷ lệ khung rõ ràng để không vỡ layout.

---

# **5. THỰC HÀNH & TOP 5 NHANH NHẤT (30 PHÚT)**

## **5.1. Bài tập**

- Tạo danh sách món ăn.
- Tạo bảng thông tin lớp học.
- Nhúng một video và một iframe.
- Mỗi học viên hoàn thành một phần nhỏ rồi ghép lại thành sản phẩm hoàn chỉnh.

## **5.2. Nghiệm thu nhanh**

- Kiểm tra cú pháp.
- Kiểm tra hiển thị.
- Kiểm tra đường dẫn.
- Nhìn lại xem đã dùng đúng thẻ theo ngữ cảnh hay chưa.

### **Bonus cuối buổi**

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

### **Ghi nhận**

- Top 5 được ghi lại theo thứ tự nộp bài.
- Chỉ tính khi bài chạy được và đúng yêu cầu.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 2**

- Tạo được các loại danh sách.
- Dựng được bảng có gộp ô.
- Nhúng được video, audio, iframe.
- Phân biệt được ngữ cảnh dùng danh sách và bảng.

# **KẾ HOẠCH CHI TIẾT: BUỔI 3 - BLOCK/INLINE, SEMANTIC HTML5 & FORM**

**Tổng thời gian: 150 phút**

---

# **1. KHỞI ĐỘNG & ÔN NHANH (15 PHÚT)**

## **1.1. Nhắc lại buổi trước (5 phút)**

- Danh sách.
- Bảng.
- Multimedia.

## **1.2. Mục tiêu buổi học (10 phút)**

- Phân biệt block và inline.
- Biết dùng semantic HTML5.
- Tạo form cơ bản.

---

# **2. BLOCK VS INLINE (25 PHÚT)**

## **2.1. Khái niệm (10 phút)**

### **Block**

- Chiếm full hàng.
- Dễ tạo layout.

### **Inline**

- Nằm cùng hàng.
- Thường dùng cho text nhỏ.

## **2.2. Thực hành (15 phút)**

- Quan sát `div`, `p`, `h1`.
- Quan sát `span`, `a`, `strong`.
- Tạo ví dụ mix block và inline.

### **Ví dụ minh họa**

```html
<div>
	<p>Đây là block.</p>
	<a href="#">Đây là inline</a>
</div>
```

### **Lỗi thường gặp**

- Cho rằng inline không thể nằm trong block.
- Dùng `span` cho mọi thứ mà quên mất ngữ cảnh ngữ nghĩa.

### **Mẹo**

- Khi chưa chắc, hãy nhìn bằng DevTools để hiểu phần tử đang chiếm chỗ thế nào.

---

# **3. SEMANTIC HTML5 (35 PHÚT)**

## **3.1. Các thẻ chính (20 phút)**

- `header`
- `nav`
- `main`
- `section`
- `article`
- `aside`
- `footer`

## **3.2. Thực hành khung trang (15 phút)**

- Dựng trang tin tức.
- Dựng trang giới thiệu sản phẩm.
- Dựng bố cục blog mini.

### **Gợi ý cấu trúc**

```html
<header></header>
<nav></nav>
<main>
	<section></section>
	<aside></aside>
</main>
<footer></footer>
```

### **Mẹo thực tế**

- Semantic giúp code dễ đọc, dễ bảo trì, dễ chấm bài.

---

# **4. FORM CƠ BẢN (45 PHÚT)**

## **4.1. Cấu trúc form (15 phút)**

- `form`
- `label`
- `input`
- `textarea`
- `select`/`option`

## **4.2. Các loại input hay dùng (20 phút)**

- `text`
- `email`
- `password`
- `date`
- `radio`
- `checkbox`
- `file`

## **4.3. Thực hành (10 phút)**

- Form đăng ký.
- Form liên hệ.

### **Mẫu form ngắn**

```html
<form>
	<label for="email">Email</label>
	<input id="email" type="email" placeholder="Nhập email">
</form>
```

### **Lỗi thường gặp**

- Quên `label`.
- Để `input` không có `name`.
- Không kiểm tra trạng thái `required`.

---

# **5. CODE-ALONG & TOP 5 NHANH NHẤT (30 PHÚT)**

## **5.1. Bài tập**

- Dựng trang có header, main, footer.
- Trong main có một form liên hệ.

## **5.2. Nghiệm thu**

- Kiểm tra block/inline.
- Kiểm tra semantic đúng chỗ.

### **Bonus cuối buổi**

- 5 bạn nộp đúng và nhanh nhất được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 3**

- Phân biệt được block và inline.
- Dùng được semantic HTML5.
- Tạo được form cơ bản.

# **KẾ HOẠCH CHI TIẾT: BUỔI 4 - SELECTOR CƠ BẢN, RELATIONAL SELECTORS & BACKGROUND**

**Tổng thời gian: 150 phút**

---

# **1. MỞ ĐẦU & ÔN NỀN (15 PHÚT)**

## **1.1. Nhắc lại HTML (5 phút)**

- Semantic.
- Form.
- Block/inline.

## **1.2. Mục tiêu buổi học (10 phút)**

- Biết 3 cách chèn CSS.
- Biết bộ chọn cơ bản.
- Biết background và màu sắc.

---

# **2. CÁCH CHÈN CSS & SPECIFICITY (25 PHÚT)**

## **2.1. 3 cách chèn CSS (15 phút)**

- Inline CSS.
- Internal CSS.
- External CSS.

## **2.2. Độ ưu tiên (10 phút)**

- Khi nào CSS nào thắng.
- Vì sao nên ưu tiên file CSS riêng.

### **Mẹo**

- Làm dự án thật nên giữ CSS sạch, tách file rõ ràng.

---

# **3. SELECTOR CƠ BẢN & COMBINATOR (40 PHÚT)**

## **3.1. Selector cơ bản (15 phút)**

- Tag selector.
- Class selector.
- Id selector.
- Universal selector.

### **Ví dụ**

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

### **Lỗi thường gặp**

- Dùng `id` cho quá nhiều phần tử.
- Viết selector quá dài và khó bảo trì.

## **3.2. Selector tổ hợp (25 phút)**

- Descendant.
- Child.
- Adjacent sibling.
- General sibling.

### **Thực hành**

- Tô màu menu.
- Đổi style một khối con.
- Chọn phần tử liền kề.

---

# **4. MÀU SẮC & BACKGROUND (35 PHÚT)**

## **4.1. Màu sắc (15 phút)**

- HEX.
- RGB.
- RGBA.

## **4.2. Background (20 phút)**

- `background-color`.
- `background-image`.
- `background-size`.
- `background-position`.
- `background-repeat`.

### **Ví dụ**

```css
.hero {
	background-image: url('../images/banner.jpg');
	background-size: cover;
	background-position: center;
	background-repeat: no-repeat;
}
```

### **Mẹo thực tế**

- Nền đẹp nhưng phải dễ đọc chữ.
- Đừng làm ảnh nền quá nặng.

---

# **5. THỰC HÀNH & BONUS (35 PHÚT)**

## **5.1. Bài tập**

- Tạo card sản phẩm có ảnh nền.
- Tô màu menu bằng selector tổ hợp.

## **5.2. Nghiệm thu nhanh**

- CSS tách file.
- Selector đúng.
- Background hiển thị chuẩn.

### **Bonus cuối buổi**

- 5 bạn hoàn thành nhanh nhất được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 4**

- Viết được selector cơ bản.
- Hiểu relational selectors.
- Dùng được background và màu sắc.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 6**

- Dùng được position.
- Hiểu z-index.
- Tạo được CSS variables.

# **KẾ HOẠCH CHI TIẾT: BUỔI 7 - FLEXBOX**

**Tổng thời gian: 150 phút**

---

# **1. MỞ ĐẦU (10 PHÚT)**

- Ôn position.
- Nêu lý do cần Flexbox.

---

# **2. FLEX CONTAINER (45 PHÚT)**

## **2.1. Kích hoạt Flexbox (10 phút)**

- `display: flex`.

## **2.2. Thuộc tính quan trọng (25 phút)**

- `flex-direction`
- `justify-content`
- `align-items`
- `flex-wrap`

### **Ví dụ**

```css
.navbar {
	display: flex;
	justify-content: space-between;
	align-items: center;
}
```

### **Lỗi thường gặp**

- Dùng `justify-content` nhưng quên container phải là flex.
- Trộn nhiều giá trị mà không xác định rõ trục chính.

## **2.3. Thực hành (10 phút)**

- Căn menu.
- Căn card.
- Căn header.

### **Mẹo**

- Flexbox rất mạnh cho một chiều, đừng cố ép nó làm mọi thứ.

---

# **3. FLEX ITEMS (35 PHÚT)**

## **3.1. Thuộc tính trên item (20 phút)**

- `flex-grow`
- `flex-shrink`
- `order`
- `align-self`

## **3.2. Thực hành (15 phút)**

- Layout 2 cột.
- Card đều nhau.
- Menu responsive nhẹ.

### **Mẹo**

- Nếu muốn căn giữa cả ngang lẫn dọc, hãy thử `justify-content: center` và `align-items: center`.

---

# **4. THỰC HÀNH & TOP 5 (40 PHÚT)**

## **Bài tập**

- Dựng một trang có header, main, sidebar, footer bằng Flexbox.

### **Khung gợi ý**

```html
<div class="page">
	<header></header>
	<main class="layout">
		<aside></aside>
		<section></section>
	</main>
</div>
```

### **Bonus cuối buổi**

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 7**

- Dùng được Flex container.
- Hiểu các thuộc tính Flex items.
- Tạo được layout hiện đại cơ bản.

# **KẾ HOẠCH CHI TIẾT: BUỔI 8 - CSS GRID & RESPONSIVE DESIGN**

**Tổng thời gian: 150 phút**

---

# **1. MỞ ĐẦU (10 PHÚT)**

- Ôn Flexbox.
- Dẫn vào layout nhiều chiều.

---

# **2. CSS GRID (50 PHÚT)**

## **2.1. Khái niệm (15 phút)**

- Grid container.
- Grid item.
- Layout theo hàng và cột.

## **2.2. Thuộc tính quan trọng (20 phút)**

- `grid-template-columns`
- `grid-template-rows`
- `gap`
- `grid-column`
- `grid-row`

## **2.3. Thực hành (15 phút)**

- Làm lưới sản phẩm.
- Dựng bố cục dashboard.

### **Mẹo thực tế**

- Grid rất hợp cho layout tổng thể và khu vực nhiều ô.

---

# **3. RESPONSIVE DESIGN (45 PHÚT)**

## **3.1. Tư duy responsive (15 phút)**

- Desktop.
- Tablet.
- Mobile.

## **3.2. Media queries (20 phút)**

- Đổi số cột.
- Thu nhỏ chữ.
- Xếp lại card.

## **3.3. Thực hành (10 phút)**

- Tối ưu một trang card cho 3 màn hình.

---

# **4. THỰC HÀNH & BONUS (35 PHÚT)**

## **Bài tập**

- Dựng trang sản phẩm responsive.

### **Bonus cuối buổi**

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 8**

- Dùng được CSS Grid.
- Biết viết media queries.
- Làm được giao diện thích ứng cơ bản.

# **KẾ HOẠCH CHI TIẾT: BUỔI 9 - PSEUDO-CLASSES, PSEUDO-ELEMENTS, BEM & ANIMATION**

**Tổng thời gian: 150 phút**

---

# **1. MỞ ĐẦU (10 PHÚT)**

- Ôn Grid và responsive.
- Dẫn vào phần tinh chỉnh giao diện.

---

# **2. PSEUDO-CLASSES (35 PHÚT)**

## **Nội dung**

- `:hover`
- `:focus`
- `:nth-child()`
- `:first-child`
- `:last-child`
- `:has()`

### **Thực hành**

- Hover nút.
- Tô màu item thứ 2.
- Làm trạng thái focus cho input.

---

# **3. PSEUDO-ELEMENTS & BEM (35 PHÚT)**

## **3.1. Pseudo-elements**

- `::before`
- `::after`
- Thuộc tính `content`

## **3.2. BEM**

- Block.
- Element.
- Modifier.

### **Mẹo**

- BEM giúp đặt tên rõ ràng, tránh đụng class khi dự án lớn dần.

---

# **4. ANIMATION & TRANSITION (35 PHÚT)**

## **Nội dung**

- `transition`
- `@keyframes`
- `animation`

### **Thực hành**

- Hover card.
- Hiệu ứng nút.
- Loading đơn giản.

---

# **5. THỰC HÀNH & TOP 5 (35 PHÚT)**

## **Bài tập**

- Làm card sản phẩm có hover, badge và hiệu ứng nhẹ.

### **Bonus cuối buổi**

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 9**

- Dùng được pseudo-classes.
- Dùng được pseudo-elements.
- Biết quy tắc BEM.
- Tạo được hiệu ứng chuyển động cơ bản.

# **KẾ HOẠCH CHI TIẾT: BUỔI 10 - JS CƠ BẢN & CẤU TRÚC ĐIỀU KHIỂN**

**Tổng thời gian: 150 phút**

---

# **1. MỞ ĐẦU (10 PHÚT)**

- JS là gì.
- Vì sao cần JS sau HTML/CSS.
- JS dùng để tạo tương tác và xử lý logic.

### **Mục tiêu**

- Học viên hiểu JS không phải chỉ là cú pháp.
- Biết dùng JS để quyết định điều gì sẽ xảy ra trên giao diện.

---

# **2. KIỂU DỮ LIỆU & BIẾN (30 PHÚT)**

## **Nội dung**

- `var`, `let`, `const`.
- String, Number, Boolean, Array, Object.
- Toán tử cơ bản.

### **Ví dụ**

```jsx
const userName = 'An';
let age = 20;
const isStudent = true;
```

### **Giải thích nhanh**

- `const` dùng cho giá trị không đổi.
- `let` dùng cho giá trị có thể thay đổi.
- `var` nhắc nhanh để biết lịch sử, nhưng hạn chế dùng trong bài mới.

### **Mẹo**

- Ưu tiên dùng `const`, chỉ dùng `let` khi cần đổi giá trị.
- Đặt tên biến rõ nghĩa để đọc lại sau không bị quên mục đích.

### **Lỗi thường gặp**

- Khai báo rồi không dùng.
- Gán nhầm kiểu dữ liệu.
- Đặt tên biến quá ngắn, không hiểu ý nghĩa.

---

# **3. COERCION & TRICKS (20 PHÚT)**

## **Nội dung**

- Ép kiểu ngầm định.
- Các ví dụ như `1 + "1"`.
- So sánh `==` và `===`.

### **Ví dụ minh hoạ**

```jsx
console.log(1 + '1');
console.log('5' - 1);
console.log(0 == false);
console.log(0 === false);
```

### **Gợi ý giảng viên**

- Cho học viên tự đoán kết quả trước khi chạy code.
- Nhấn mạnh chỗ khác nhau giữa ép kiểu ngầm định và so sánh chặt.

### **Mẹo thực tế**

- Luôn ưu tiên `===` để tránh lỗi khó đoán.
- Khi dữ liệu lấy từ input, nên chủ động chuyển kiểu trước khi tính toán.

---

# **4. ĐIỀU KHIỂN LUỒNG (50 PHÚT)**

## **Nội dung**

- `if / else`
- `switch / case`
- `for`
- `while`
- `break`, `continue`

### **Ví dụ**

```jsx
const score = 8;

if (score >= 8) {
	console.log('Giỏi');
} else if (score >= 6.5) {
	console.log('Khá');
} else {
	console.log('Cần cố gắng hơn');
}
```

### **Thực hành**

- Kiểm tra điểm.
- Duyệt danh sách sản phẩm.
- Lặp menu.

### **Mẹo thực tế**

- Chia bài toán lớn thành nhiều điều kiện nhỏ.
- Đừng để khối `if` quá dài mới bắt đầu viết logic.

### **Lỗi thường gặp**

- Thiếu `else` nên rơi vào trạng thái không xử lý.
- Quên `break` trong `switch`.
- Dùng vòng lặp khi thực ra chỉ cần một điều kiện.

---

# **5. THỰC HÀNH & TOP 5 (40 PHÚT)**

## **Bài tập**

- Viết script kiểm tra độ tuổi.
- Lặp ra danh sách tên.
- Dùng điều kiện để đổi nội dung trên trang.

### **Cách tổ chức thực hành**

- Làm từng câu nhỏ trước.
- Chạy kết quả từng phần.
- Sau đó mới ghép thành bài hoàn chỉnh.

### **Bonus cuối buổi**

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

### **Ghi nhận**

- Chỉ tính bonus khi code chạy và học viên giải thích được logic.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 10**

- Biết khai báo biến.
- Hiểu kiểu dữ liệu cơ bản.
- Dùng được điều kiện và vòng lặp.
- Biết tránh các lỗi coercion thường gặp.

# **KẾ HOẠCH CHI TIẾT: BUỔI 11 - ES6, FUNCTIONS & MODULE**

**Tổng thời gian: 150 phút**

---

# **1. MỞ ĐẦU (10 PHÚT)**

- Ôn JS cơ bản.
- Dẫn vào cú pháp hiện đại.

---

# **2. FUNCTION & ARROW FUNCTION (35 PHÚT)**

## **Nội dung**

- Function declaration.

### **Ví dụ**

```jsx
function sum(a, b) {
	return a + b;
}

const multiply = (a, b) => a * b;
```

### **Lỗi thường gặp**

- Viết arrow function nhưng quên `return` khi dùng block body.
- Dùng function quá dài, không tách nhiệm vụ.
- Function expression.
- Arrow function.

### **Mẹo**

- Function càng rõ đầu vào - đầu ra thì code càng dễ kiểm soát.

---

# **3. ES6 CƠ BẢN (35 PHÚT)**

## **Nội dung**

### **Ví dụ**

```jsx
const user = { name: 'An', age: 20 };
const { name, age } = user;
const arr2 = [...[1, 2, 3], 4];
```

### **Mẹo**

- Destructuring rất tiện nhưng phải biết dữ liệu đang có cấu trúc gì.
- `const` / `let`
- Destructuring.
- Spread operator `...`.
- Template literal.

### **Thực hành**

- Tách object.
- Gộp mảng.
- Tạo chuỗi động.

---

# **4. MODULE: IMPORT / EXPORT (30 PHÚT)**

## **Nội dung**

### **Ví dụ**

```jsx
// math.js
export const sum = (a, b) => a + b;

// app.js
import { sum } from './math.js';
```

### **Lỗi thường gặp**

- Sai đường dẫn import.
- Quên `type="module"` khi chạy file JS module trên trình duyệt.
- Chia code thành file.
- Export hàm.
- Import hàm.

### **Mẹo thực tế**

- Dự án thật không nên dồn toàn bộ logic vào một file.

---

# **5. THỰC HÀNH & TOP 5 (40 PHÚT)**

## **Bài tập**

- Tách hàm hiển thị dữ liệu.
- Dùng destructuring để lấy dữ liệu.
- Gọi hàm từ file khác.

### **Bonus cuối buổi**

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 11**

- Viết được function hiện đại.
- Dùng được destructuring và spread.
- Biết tách code thành module.

# **KẾ HOẠCH CHI TIẾT: BUỔI 12 - ARRAY METHODS & HÀM ĐỊNH THỜI**

**Tổng thời gian: 150 phút**

---

# **1. MỞ ĐẦU (10 PHÚT)**

- Ôn function và module.

---

# **2. ARRAY METHODS (55 PHÚT)**

## **Nội dung**

### **Ví dụ**

```jsx
const prices = [100, 200, 300];
const total = prices.reduce((sum, price) => sum + price, 0);
```

### **Mẹo**

- `map` tạo mảng mới.
- `filter` lọc dữ liệu.
- `reduce` gom về một giá trị.
- `forEach`
- `map`
- `filter`
- `find`
- `some`
- `reduce`

### **Thực hành**

- Biến đổi danh sách.
- Lọc sản phẩm.
- Tính tổng tiền.
- Tìm phần tử đầu tiên phù hợp.

### **Mẹo**

- Chọn đúng method sẽ làm code ngắn và dễ đọc hơn nhiều so với dùng vòng lặp tay.

---

# **3. HÀM ĐỊNH THỜI (25 PHÚT)**

## **Nội dung**

### **Ví dụ**

```jsx
setTimeout(() => {
	console.log('Done');
}, 1000);
```

### **Lỗi thường gặp**

- Quên xóa interval sau khi không dùng nữa.
- Dùng timeout cho việc cần lặp lại.
- `setTimeout`
- `setInterval`

### **Thực hành**

- Chạy thông báo chậm.
- Tạo đồng hồ đếm ngược.

---

# **4. THỰC HÀNH & TOP 5 (50 PHÚT)**

## **Bài tập**

- Lọc danh sách sản phẩm theo giá.
- Tính tổng đơn hàng.
- Tạo countdown đơn giản.

### **Khung gợi ý**

```jsx
const cheapProducts = products.filter(product => product.price < 500000);
```

### **Bonus cuối buổi**

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 12**

- Dùng được array methods.
- Biết `setTimeout` và `setInterval`.
- Viết được logic xử lý dữ liệu gọn hơn.

# **KẾ HOẠCH CHI TIẾT: BUỔI 13 - DOM MANIPULATION**

**Tổng thời gian: 150 phút**

---

# **1. MỞ ĐẦU (10 PHÚT)**

- Ôn array methods.
- Dẫn vào tương tác với giao diện.

---

# **2. TRUY XUẤT DOM (30 PHÚT)**

## **Nội dung**

- `querySelector`
- `querySelectorAll`
- `getElementById`

### **Ví dụ**

```jsx
const button = document.querySelector('.btn');
const title = document.getElementById('title');
```

### **Lỗi thường gặp**

- Chọn nhầm selector dẫn đến `null`.
- Viết code trước khi DOM sẵn sàng.

### **Thực hành**

- Lấy nút.
- Lấy input.
- Lấy danh sách item.

---

# **3. THAY ĐỔI NỘI DUNG & THUỘC TÍNH (35 PHÚT)**

## **Nội dung**

- `innerHTML`
- `innerText`
- `setAttribute`
- `classList`

### **Ví dụ**

```jsx
title.innerText = 'Tiêu đề mới';
button.classList.add('active');
```

### **Mẹo**

- Chỉ dùng `innerHTML` khi cần chèn cấu trúc, còn lại ưu tiên cách an toàn hơn.

---

# **4. SỰ KIỆN (35 PHÚT)**

## **Nội dung**

- `click`
- `scroll`
- `input`
- `blur`

### **Ví dụ**

```jsx
button.addEventListener('click', () => {
	console.log('Clicked');
});
```

### **Thực hành**

- Đổi nội dung khi bấm nút.
- Hiện/ẩn phần tử.
- Đếm số lần click.

---

# **5. THỰC HÀNH & TOP 5 (40 PHÚT)**

## **Bài tập**

- Làm nút đổi theme.
- Thêm class active cho menu.
- Render danh sách từ mảng.

### **Bonus cuối buổi**

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 13**

- Truy xuất được phần tử DOM.
- Thay đổi được nội dung và class.
- Bắt được các sự kiện cơ bản.

# **KẾ HOẠCH CHI TIẾT: BUỔI 14 - FORM LOGIC & REAL-TIME VALIDATION**

**Tổng thời gian: 150 phút**

---

# **1. MỞ ĐẦU (10 PHÚT)**

- Ôn DOM và sự kiện.
- Dẫn vào xử lý form thật.

---

# **2. XỬ LÝ DỮ LIỆU FORM (35 PHÚT)**

## **Nội dung**

- Lấy giá trị input.
- Kiểm tra rỗng.
- Chặn submit khi sai.

### **Ví dụ**

```jsx
form.addEventListener('submit', (event) => {
	event.preventDefault();
});
```

### **Thực hành**

- Form đăng ký.
- Form liên hệ.

---

# **3. REAL-TIME VALIDATION (35 PHÚT)**

## **Nội dung**

- Bắt sự kiện `input`.
- Bắt sự kiện `blur`.
- Báo lỗi ngay khi người dùng nhập sai.

### **Mẹo thực tế**

- Báo lỗi càng sớm càng tốt, nhưng câu chữ phải ngắn và dễ hiểu.

---

# **4. REGEX CƠ BẢN (35 PHÚT)**

## **Nội dung**

- Kiểm tra email.
- Kiểm tra số điện thoại.
- Kiểm tra mật khẩu.

### **Ví dụ**

```jsx
const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
```

### **Thực hành**

- Viết regex đơn giản.
- Ghép regex với form validation.

---

# **5. THỰC HÀNH & TOP 5 (35 PHÚT)**

## **Bài tập**

- Tạo form đăng ký có validate realtime.
- Hiển thị thông báo lỗi rõ ràng.

### **Bonus cuối buổi**

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 14**

- Xử lý được dữ liệu form.
- Validate realtime cơ bản.
- Dùng được regex cho bài toán thực tế.

# **KẾ HOẠCH CHI TIẾT: BUỔI 15 - ASYNCHRONOUS JS & CRUD VỚI FAKE API**

**Tổng thời gian: 150 phút**

---

# **1. MỞ ĐẦU (10 PHÚT)**

- Ôn form validation.
- Dẫn vào dữ liệu từ server giả lập.

---

# **2. FETCH API & ASYNC JS (35 PHÚT)**

## **Nội dung**

- Bất đồng bộ là gì.
- `fetch`.
- `then/catch` hoặc `async/await`.

### **Ví dụ**

```jsx
const response = await fetch('/api/products');
const data = await response.json();
```

### **Mẹo**

- Khi làm việc với API, luôn chuẩn bị trạng thái loading và lỗi.

---

# **3. FAKE API VỚI JSON-SERVER (25 PHÚT)**

## **Nội dung**

- Tạo dữ liệu giả.
- Chạy server local.
- Đọc dữ liệu từ `Products`, `Users`, `Orders`.

### **Mẹo**

- Tách dữ liệu theo bảng để dễ test từng chức năng.

---

# **4. CRUD CƠ BẢN (45 PHÚT)**

## **Nội dung**

- `GET`.
- `POST`.
- `DELETE`.
- Xác nhận trước khi xóa.

### **Ví dụ luồng**

1. GET danh sách.
2. POST thêm mới.
3. DELETE bản ghi.

### **Lỗi thường gặp**

- Không cập nhật lại giao diện sau khi gọi API.
- Quên xử lý lỗi mạng.

### **Thực hành**

- Hiển thị danh sách.
- Thêm mới dữ liệu.
- Xóa dữ liệu.

---

# **5. THỰC HÀNH & TOP 5 (35 PHÚT)**

## **Bài tập**

- Lấy danh sách sản phẩm từ fake API.
- Hiển thị lên giao diện.
- Thêm mới một item.
- Xóa một item có confirm.

### **Bonus cuối buổi**

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 15**

- Biết dùng fetch.
- Hiểu async JS.
- Làm được CRUD cơ bản với fake API.

# **KẾ HOẠCH CHI TIẾT: BUỔI 16 - STATE MANAGEMENT, LOCALSTORAGE & AUTH**

**Tổng thời gian: 150 phút**

---

# **1. MỞ ĐẦU (10 PHÚT)**

- Ôn CRUD và fetch.
- Dẫn vào tư duy quản lý trạng thái.

---

# **2. STATE MANAGEMENT CƠ BẢN (35 PHÚT)**

## **Nội dung**

- Luồng `Action -> State -> Render`.
- Tách dữ liệu và giao diện.
- Cập nhật lại màn hình khi state thay đổi.

### **Ví dụ**

```jsx
let state = { count: 0 };

function render() {
	document.querySelector('#count').innerText = state.count;
}
```

### **Mẹo thực tế**

- Làm rõ nguồn dữ liệu nào là thật, dữ liệu nào là đang hiển thị.

---

# **3. LOCALSTORAGE (30 PHÚT)**

## **Nội dung**

- Lưu `userId`.
- Lưu trạng thái đăng nhập.
- Đọc lại khi reload trang.

### **Ví dụ**

```jsx
localStorage.setItem('userId', '123');
const userId = localStorage.getItem('userId');
```

## **Thực hành**

- Ghi nhớ user.
- Tự đăng nhập lại sau refresh.

---

# **4. AUTH FLOW & BẢO VỆ ROUTE (40 PHÚT)**

## **Nội dung**

- Đăng ký.
- Đăng nhập.
- Chặn truy cập trang admin nếu chưa login.

### **Lỗi thường gặp**

- Chỉ lưu trạng thái mà không kiểm tra lại khi reload.
- Để logic auth rải khắp file.

### **Mẹo**

- Luồng auth cơ bản phải rõ: vào -> kiểm tra -> cho phép hoặc chuyển hướng.

---

# **5. TỔNG KẾT & TOP 5 (35 PHÚT)**

## **Bài tập**

- Hoàn thiện luồng đăng nhập.
- Lưu trạng thái vào localStorage.
- Chặn vào trang admin khi chưa hợp lệ.

### **Bonus cuối buổi**

- 5 bạn làm đúng và nhanh nhất được cộng `+1` điểm.

---

# **KẾT QUẢ ĐẦU RA SAU BUỔI 16**

- Hiểu state flow cơ bản.
- Dùng được localStorage.
- Biết làm luồng đăng nhập và chặn truy cập cơ bản.

# **ĐỀ BÀI NGHIỆM THU CUỐI KHÓA - WEBSITE CƠ BẢN**

## **1. Mục tiêu**

Học viên xây dựng một website hoàn chỉnh ở mức cơ bản, có cấu trúc rõ ràng, giao diện responsive, tương tác bằng JavaScript và có luồng dữ liệu đủ để nghiệm thu đầu ra cuối khóa.

### **Yêu cầu tinh thần của bài**

- Bài phải thể hiện được tư duy làm web thực tế.
- Không chỉ làm cho có, mà phải làm để có thể chấm, có thể demo và có thể mở rộng.
- Ưu tiên rõ ràng, chạy được, dễ hiểu trước khi tối ưu nâng cao.

## **2. Phạm vi bài làm**

### **Bắt buộc**

- Có ít nhất 1 trang chính và 1 trang chức năng phụ hoặc 1 khu vực quản trị rõ ràng.
- Sử dụng HTML semantic hợp lý.
- Có CSS riêng, không viết style inline tràn lan.
- Có JavaScript cho tương tác chính.
- Có sử dụng `localStorage` hoặc fake API tùy theo mô hình bài làm.

### **Giải thích từng ý**

- Trang chính: nơi thể hiện dữ liệu và giao diện chủ đạo.
- Trang phụ hoặc admin: nơi thể hiện luồng chức năng.
- Semantic: giúp chấm nhanh và code sạch.
- CSS riêng: giúp tách trách nhiệm rõ ràng.
- JavaScript: để bài có tương tác thật.
- localStorage hoặc fake API: để có luồng dữ liệu phù hợp bài cuối khóa.

### **Khuyến khích**

- Có responsive cho mobile và tablet.
- Có animation hoặc transition vừa đủ.
- Có form validation và trạng thái loading/thông báo.

### **Gợi ý chấm cộng thêm**

- Có loading skeleton hoặc trạng thái empty sẽ dễ ăn điểm hơn.
- Có transition nhẹ nhàng sẽ giúp bài trông hoàn thiện hơn.

## **3. Gợi ý đề tài**

- Website bán hàng mini.
- Website quản lý sản phẩm.
- Website giới thiệu dịch vụ có trang admin đơn giản.

### **Lưu ý chọn đề tài**

- Chọn đề tài đủ nhỏ để làm xong.
- Không chọn đề tài quá rộng khiến bài bị dở dang.
- Nên ưu tiên đề tài có danh sách, form, và ít nhất một luồng dữ liệu.

## **4. Cấu trúc file khuyến nghị**

```
project/
├─ index.html
├─ pages/
└─ assets/
	├─ css/
	├─ js/
	└─ images/
```

### **Giải thích**

- `index.html`: trang gốc để mở và điều hướng vào website.
- `pages`: các trang con như `about`, `product`, `admin`, `login`.
- `assets`: nơi chứa tài nguyên dùng chung cho toàn bộ dự án.
- `assets/css`: toàn bộ style riêng của bài.
- `assets/js`: toàn bộ logic tương tác.
- `assets/images`: ảnh, icon, banner, hình minh họa.

## **5. Quy chuẩn nộp bài**

- Tên file và thư mục rõ ràng, không đặt tên mơ hồ.
- Không lỗi vỡ layout ở kích thước màn hình phổ biến.
- Không để console lỗi nghiêm trọng khi chạy bài.
- Không copy nguyên khối từ nguồn khác nếu chưa chỉnh sửa phù hợp.

### **Checklist trước khi nộp**

- Mở bằng Live Server.
- Refresh lại vài lần để kiểm tra state.
- Test form và nút bấm chính.
- Kiểm tra responsive ở mobile width.
- Xem lại console trước khi nộp.

## **6. Móc chấm điểm tối đa 100**

### **A. HTML và cấu trúc trang - 20 điểm**

- 5 điểm: có cấu trúc HTML5 chuẩn.
- 5 điểm: dùng semantic hợp lý.
- 5 điểm: bố cục rõ ràng, chia khối hợp lý.
- 5 điểm: nội dung đầy đủ, không thiếu phần chính.

### **Điều kiện đạt**

- Phần HTML phải có khung rõ ràng, không lộn xộn.
- Nội dung phải nhìn ra được đâu là khu vực chính, đâu là khu vực phụ.

### **B. CSS và giao diện - 25 điểm**

- 10 điểm: bố cục đẹp, cân đối, dễ nhìn.
- 5 điểm: dùng Flexbox/Grid hợp lý.
- 5 điểm: typography và màu sắc ổn.
- 5 điểm: responsive cơ bản tốt.

### **Điều kiện đạt**

- Giao diện phải đồng nhất từ đầu đến cuối.
- Khoảng cách, cỡ chữ, màu sắc không được lộn xộn.

### **C. JavaScript logic - 25 điểm**

- 10 điểm: DOM, render, tương tác chạy đúng.
- 5 điểm: validate form hợp lý.
- 5 điểm: dùng array methods hoặc logic xử lý dữ liệu tốt.
- 5 điểm: code sạch, tách hàm rõ.

### **Điều kiện đạt**

- Nút bấm có phản hồi.
- Form có kiểm tra.
- Dữ liệu render ra đúng nguồn.

### **D. Dữ liệu, fetch, localStorage - 15 điểm**

- 5 điểm: đọc dữ liệu từ nguồn giả lập hoặc API.
- 5 điểm: có localStorage lưu trạng thái.
- 5 điểm: luồng đăng nhập hoặc lưu dữ liệu hoạt động đúng.

### **Điều kiện đạt**

- Có thể lưu và đọc lại dữ liệu sau khi reload.
- Nếu dùng API giả lập, phải có luồng chạy ổn định.

### **E. Tính hoàn thiện - 15 điểm**

- 5 điểm: giao diện đồng nhất.
- 5 điểm: có trạng thái loading, empty hoặc error nếu cần.
- 5 điểm: trình bày mạch lạc, chạy ổn định.

### **Điều kiện đạt**

- Người chấm nhìn vào phải hiểu ngay bài đang làm gì.
- Không được để bài có cảm giác dang dở hoặc thiếu chốt logic.

## **7. Tiêu chí trừ điểm**

- Lỗi không chạy được dự án: trừ mạnh theo mức độ.
- Thiếu file quan trọng: trừ điểm rõ ràng.
- Vỡ giao diện ở màn hình cơ bản: trừ điểm phần CSS.
- Logic sai hoặc không dùng được: trừ điểm phần JS.
- Sao chép mẫu mà không hiểu: có thể bị yêu cầu làm lại.

## **8. Quy chuẩn đánh giá nhanh**

1. Mở được bằng Live Server.
2. Giao diện chính hiển thị đúng.
3. Có tương tác JS.
4. Có lưu trạng thái hoặc dữ liệu.
5. Có responsive cơ bản.
6. Trình bày và đặt tên rõ ràng.

### **Trình tự chấm gợi ý**

- Chấm tổng quan giao diện trước.
- Sau đó test tương tác.
- Cuối cùng mới soi chi tiết code và dữ liệu.

## **9. Bonus trong quá trình học**

- Mỗi buổi, 5 bạn nộp nhanh nhất và đúng yêu cầu được cộng `+1` điểm.
- Điểm bonus được ghi riêng theo từng buổi.

### **Cách ghi nhận**

- Ghi theo tên học viên và buổi học.
- Chỉ cộng khi bài chạy đúng và nộp trong thời gian quy định.

## **10. Lưu ý khi nộp**

- Nộp source đầy đủ.
- Kèm hướng dẫn chạy nếu có fake API hoặc data đặc biệt.
- Kiểm tra lại toàn bộ luồng trước khi nộp.

### **Lưu ý cuối**

- Nếu bài dùng dữ liệu cục bộ, nên để một file mô tả ngắn cách chạy.
- Nếu bài có trang admin, nên ghi rõ tài khoản demo nếu có.