# AI Usage Log

## 1. Công cụ
ChatGPT (OpenAI).

## 2. Mục đích
Hỗ trợ phân tích ảnh chụp 5 khu vực website Rong Rong Project, đề xuất cải tiến trạng thái Pre-order, tạo mã HTML/CSS mẫu và giải thích responsive.

## 3. Prompt chính
- Phân tích 5 khu vực trang chủ, danh mục, chi tiết, tìm kiếm, giỏ hàng từ ảnh chụp; phân biệt quan sát và đề xuất.
- Đề xuất bố cục trang chi tiết sản phẩm, làm rõ thông tin Pre-order trước nút mua; chưa tạo code ngay.
- Tạo trang HTML5/CSS3, ít nhất 4 thẻ sản phẩm, CSS riêng, responsive, không backend.

## 4. Kết quả AI đề xuất
Tạo khung thông báo Pre-order phía dưới giá; bố cục chi tiết hai cột trên desktop và một cột trên mobile; 4 thẻ sản phẩm minh họa.

## 5. Kiểm tra và điều chỉnh
Ảnh chụp thực tế xác nhận website đã có mục thời gian nhận hàng Pre-order nhưng mục này đang thu gọn. Không khẳng định thiếu chức năng. Chưa xác minh thời gian giao hàng cụ thể nên demo dẫn đến trang chính thức. **Sinh viên bổ sung kết quả kiểm tra thực tế và một chỉnh sửa tự thực hiện sau khi chạy trang.**

## 6. Phần mã nguồn có thể giải thích
`<section>` phân chia nội dung; `<img alt>` hiển thị hình có mô tả; `<a>` tạo liên kết; `display:grid` bố trí cột; `@media(max-width:760px)` thay bố cục theo màn hình; `.notice` nhấn mạnh thông tin Pre-order.
