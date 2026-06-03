# ĐỀ BÀI NGHIỆM THU CUỐI KHÓA - WEBSITE CƠ BẢN

## 1. Mục tiêu

Học viên xây dựng một website hoàn chỉnh ở mức cơ bản, có cấu trúc rõ ràng, giao diện responsive, tương tác bằng JavaScript và có luồng dữ liệu đủ để nghiệm thu đầu ra cuối khóa.

### Yêu cầu tinh thần của bài

- Bài phải thể hiện được tư duy làm web thực tế.
- Không chỉ làm cho có, mà phải làm để có thể chấm, có thể demo và có thể mở rộng.
- Ưu tiên rõ ràng, chạy được, dễ hiểu trước khi tối ưu nâng cao.

## 2. Phạm vi bài làm

### Bắt buộc

- Có ít nhất 1 trang chính và 1 trang chức năng phụ hoặc 1 khu vực quản trị rõ ràng.
- Sử dụng HTML semantic hợp lý.
- Có CSS riêng, không viết style inline tràn lan.
- Có JavaScript cho tương tác chính.
- Có sử dụng `localStorage` hoặc fake API tùy theo mô hình bài làm.

### Giải thích từng ý

- Trang chính: nơi thể hiện dữ liệu và giao diện chủ đạo.
- Trang phụ hoặc admin: nơi thể hiện luồng chức năng.
- Semantic: giúp chấm nhanh và code sạch.
- CSS riêng: giúp tách trách nhiệm rõ ràng.
- JavaScript: để bài có tương tác thật.
- localStorage hoặc fake API: để có luồng dữ liệu phù hợp bài cuối khóa.

### Khuyến khích

- Có responsive cho mobile và tablet.
- Có animation hoặc transition vừa đủ.
- Có form validation và trạng thái loading/thông báo.

### Gợi ý chấm cộng thêm

- Có loading skeleton hoặc trạng thái empty sẽ dễ ăn điểm hơn.
- Có transition nhẹ nhàng sẽ giúp bài trông hoàn thiện hơn.

## 3. Gợi ý đề tài

- Website bán hàng mini.
- Website quản lý sản phẩm.
- Website giới thiệu dịch vụ có trang admin đơn giản.

### Lưu ý chọn đề tài

- Chọn đề tài đủ nhỏ để làm xong.
- Không chọn đề tài quá rộng khiến bài bị dở dang.
- Nên ưu tiên đề tài có danh sách, form, và ít nhất một luồng dữ liệu.

## 4. Cấu trúc file khuyến nghị

```text
project/
├─ index.html
├─ pages/
└─ assets/
	├─ css/
	├─ js/
	└─ images/
```

### Giải thích

- `index.html`: trang gốc để mở và điều hướng vào website.
- `pages`: các trang con như `about`, `product`, `admin`, `login`.
- `assets`: nơi chứa tài nguyên dùng chung cho toàn bộ dự án.
- `assets/css`: toàn bộ style riêng của bài.
- `assets/js`: toàn bộ logic tương tác.
- `assets/images`: ảnh, icon, banner, hình minh họa.

## 5. Quy chuẩn nộp bài

- Tên file và thư mục rõ ràng, không đặt tên mơ hồ.
- Không lỗi vỡ layout ở kích thước màn hình phổ biến.
- Không để console lỗi nghiêm trọng khi chạy bài.
- Không copy nguyên khối từ nguồn khác nếu chưa chỉnh sửa phù hợp.

### Checklist trước khi nộp

- Mở bằng Live Server.
- Refresh lại vài lần để kiểm tra state.
- Test form và nút bấm chính.
- Kiểm tra responsive ở mobile width.
- Xem lại console trước khi nộp.

## 6. Móc chấm điểm tối đa 100

### A. HTML và cấu trúc trang - 20 điểm

- 5 điểm: có cấu trúc HTML5 chuẩn.
- 5 điểm: dùng semantic hợp lý.
- 5 điểm: bố cục rõ ràng, chia khối hợp lý.
- 5 điểm: nội dung đầy đủ, không thiếu phần chính.

### Điều kiện đạt

- Phần HTML phải có khung rõ ràng, không lộn xộn.
- Nội dung phải nhìn ra được đâu là khu vực chính, đâu là khu vực phụ.

### B. CSS và giao diện - 25 điểm

- 10 điểm: bố cục đẹp, cân đối, dễ nhìn.
- 5 điểm: dùng Flexbox/Grid hợp lý.
- 5 điểm: typography và màu sắc ổn.
- 5 điểm: responsive cơ bản tốt.

### Điều kiện đạt

- Giao diện phải đồng nhất từ đầu đến cuối.
- Khoảng cách, cỡ chữ, màu sắc không được lộn xộn.

### C. JavaScript logic - 25 điểm

- 10 điểm: DOM, render, tương tác chạy đúng.
- 5 điểm: validate form hợp lý.
- 5 điểm: dùng array methods hoặc logic xử lý dữ liệu tốt.
- 5 điểm: code sạch, tách hàm rõ.

### Điều kiện đạt

- Nút bấm có phản hồi.
- Form có kiểm tra.
- Dữ liệu render ra đúng nguồn.

### D. Dữ liệu, fetch, localStorage - 15 điểm

- 5 điểm: đọc dữ liệu từ nguồn giả lập hoặc API.
- 5 điểm: có localStorage lưu trạng thái.
- 5 điểm: luồng đăng nhập hoặc lưu dữ liệu hoạt động đúng.

### Điều kiện đạt

- Có thể lưu và đọc lại dữ liệu sau khi reload.
- Nếu dùng API giả lập, phải có luồng chạy ổn định.

### E. Tính hoàn thiện - 15 điểm

- 5 điểm: giao diện đồng nhất.
- 5 điểm: có trạng thái loading, empty hoặc error nếu cần.
- 5 điểm: trình bày mạch lạc, chạy ổn định.

### Điều kiện đạt

- Người chấm nhìn vào phải hiểu ngay bài đang làm gì.
- Không được để bài có cảm giác dang dở hoặc thiếu chốt logic.

## 7. Tiêu chí trừ điểm

- Lỗi không chạy được dự án: trừ mạnh theo mức độ.
- Thiếu file quan trọng: trừ điểm rõ ràng.
- Vỡ giao diện ở màn hình cơ bản: trừ điểm phần CSS.
- Logic sai hoặc không dùng được: trừ điểm phần JS.
- Sao chép mẫu mà không hiểu: có thể bị yêu cầu làm lại.

## 8. Quy chuẩn đánh giá nhanh

1. Mở được bằng Live Server.
2. Giao diện chính hiển thị đúng.
3. Có tương tác JS.
4. Có lưu trạng thái hoặc dữ liệu.
5. Có responsive cơ bản.
6. Trình bày và đặt tên rõ ràng.

### Trình tự chấm gợi ý

- Chấm tổng quan giao diện trước.
- Sau đó test tương tác.
- Cuối cùng mới soi chi tiết code và dữ liệu.

## 9. Bonus trong quá trình học

- Mỗi buổi, 5 bạn nộp nhanh nhất và đúng yêu cầu được cộng `+1` điểm.
- Điểm bonus được ghi riêng theo từng buổi.

### Cách ghi nhận

- Ghi theo tên học viên và buổi học.
- Chỉ cộng khi bài chạy đúng và nộp trong thời gian quy định.

## 10. Lưu ý khi nộp

- Nộp source đầy đủ.
- Kèm hướng dẫn chạy nếu có fake API hoặc data đặc biệt.
- Kiểm tra lại toàn bộ luồng trước khi nộp.

### Lưu ý cuối

- Nếu bài dùng dữ liệu cục bộ, nên để một file mô tả ngắn cách chạy.
- Nếu bài có trang admin, nên ghi rõ tài khoản demo nếu có.
