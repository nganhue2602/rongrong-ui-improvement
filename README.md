
# E-commerce UI Improvement

**Tên dự án:** Rong Rong Project – Pre-order UI Improvement  
**Bài tập:** Bài tập cá nhân Chương 1 – Phát triển ứng dụng WEB/TMĐT  
**Website tham khảo:** https://rongrongproject.vn/

## 1. Giới thiệu

Dự án thực hiện khảo sát website thương mại điện tử Rong Rong Project và xây dựng phiên bản giao diện cải tiến bằng HTML5 và CSS3.

Khu vực được lựa chọn cải tiến là **trang chi tiết sản phẩm Curved Tote – Denim Đen**, tập trung vào cách hiển thị thông tin đặt trước (Pre-order).

Mục tiêu của cải tiến là giúp khách hàng nhận biết tình trạng đặt trước trước khi thực hiện thao tác mua hàng.

Đây là bản demo phục vụ học tập, không phải website chính thức của Rong Rong Project.

## 2. Website tham khảo

- **Tên website:** Rong Rong Project
- **URL:** https://rongrongproject.vn/
- **Lĩnh vực:** Thời trang, túi xách và phụ kiện.
- **Sản phẩm tham khảo:** [Pre-order] Curved Tote – Denim Đen.
- **Trang sản phẩm:** https://rongrongproject.vn/products/curved-tote-denim-mau-den

### Các khu vực đã khảo sát

| Khu vực | Nội dung khảo sát |
|---|---|
| Trang chủ | Hình ảnh giới thiệu, logo và điều hướng |
| Danh mục sản phẩm | Phân loại sản phẩm, hình ảnh và giá bán |
| Chi tiết sản phẩm | Hình ảnh, giá, màu sắc, số lượng, nút mua và thông tin Pre-order |
| Tìm kiếm | Ô tìm kiếm và danh sách sản phẩm bán chạy |
| Giỏ hàng | Sản phẩm, số lượng, giá, tạm tính và nút thanh toán |

## 3. Chức năng

Website demo cung cấp các chức năng giao diện:

- Hiển thị thông tin chi tiết sản phẩm Curved Tote – Denim Đen.
- Hiển thị hình ảnh minh họa, tên, màu sắc và giá tham khảo.
- Hiển thị khung thông báo tình trạng Pre-order.
- Cung cấp liên kết đến trang sản phẩm chính thức.
- Hiển thị danh sách 4 sản phẩm minh họa.
- Mỗi thẻ sản phẩm có hình ảnh, tên, thông tin giá và liên kết thao tác.
- Có thanh điều hướng giữa các khu vực.
- Hỗ trợ giao diện responsive cho máy tính và điện thoại.

**Giới hạn chức năng:** Website chỉ là bản demo HTML/CSS, không có backend, cơ sở dữ liệu, giỏ hàng hoặc thanh toán thực tế.

## 4. Công nghệ

### HTML5
Sử dụng các thẻ `header`, `nav`, `main`, `section`, `article`, `img`, `a`, `select`, `details` và `footer` để tổ chức cấu trúc nội dung.

### CSS3
Sử dụng để thiết kế màu sắc, kiểu chữ, khoảng cách, nút bấm và bố cục giao diện.

### CSS Grid
Sử dụng để bố trí khu vực chi tiết sản phẩm và danh sách sản phẩm theo dạng lưới.

### Media Queries
Điều chỉnh bố cục để phù hợp với các kích thước màn hình khác nhau.

## 5. Cách chạy

### Chạy trên máy tính

1. Tải mã nguồn từ GitHub.
2. Giải nén thư mục dự án.
3. Mở file `index.html` bằng trình duyệt Chrome.
4. Kiểm tra hình ảnh, nội dung và bố cục giao diện.

### Chạy trực tuyến

**GitHub Repository:**  
https://github.com/nganhue2602/rongrong-ui-improvement

**GitHub Pages:**  
https://nganhue2602.github.io/rongrong-ui-improvement/

### Cấu trúc thư mục

```text
rongrong-ui-improvement/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── bag-black.svg
│   ├── bag-olive.svg
│   ├── bag-navy.svg
│   └── bag-sand.svg
├── README.md
└── AI_USAGE.md
```

## 6. Cải tiến đã thực hiện

### 6.1. Vấn đề ban đầu

Trên trang chi tiết sản phẩm Curved Tote của Rong Rong Project, mục "Thời gian nhận hàng (Pre-order)" được đặt trong phần nội dung thu gọn, bên dưới các nút mua hàng.

Cách trình bày này có thể khiến khách hàng chưa chú ý đến thông tin đặt trước khi quyết định mua.

### 6.2. Phương án cải tiến

- Đưa thông báo Pre-order lên ngay dưới giá bán.
- Sử dụng khung thông tin riêng để làm nổi bật trạng thái đặt trước.
- Bổ sung liên kết kiểm tra thời gian nhận hàng trên website chính thức.
- Giữ tên, giá và lựa chọn màu sắc trong khu vực thông tin sản phẩm.
- Thiết kế bố cục hai cột trên màn hình lớn.
- Điều chỉnh bố cục phù hợp với điện thoại.
- Bổ sung 4 thẻ sản phẩm minh họa.

### 6.3. Giá trị kỳ vọng

- Giúp khách hàng dễ nhận biết tình trạng Pre-order.
- Hạn chế nguy cơ hiểu nhầm sản phẩm đặt trước là hàng giao ngay.
- Hỗ trợ khách hàng tiếp cận thông tin trước khi mua.
- Cải thiện khả năng quan sát và đọc nội dung trên nhiều kích thước màn hình.

Đây là các lợi ích kỳ vọng từ phương án thiết kế, chưa được kiểm chứng bằng nghiên cứu người dùng.

## 7. Hỗ trợ từ AI

### 7.1. Công cụ sử dụng

**ChatGPT – OpenAI**

### 7.2. Nội dung AI hỗ trợ

- Phân tích 5 khu vực của website Rong Rong Project.
- Đề xuất phương án cải tiến giao diện.
- Hỗ trợ xây dựng mã HTML5 và CSS3.
- Giải thích các thành phần mã nguồn.
- Hướng dẫn tổ chức repository và triển khai GitHub Pages.
- Hỗ trợ kiểm tra lỗi hiển thị CSS.

### 7.3. Kiểm tra và điều chỉnh

Các nhận xét AI được đối chiếu với ảnh chụp màn hình website thực tế.

Trong quá trình triển khai, giao diện ban đầu không hiển thị đúng CSS. Sau khi kiểm tra cấu trúc thư mục, đường dẫn `css/style.css` và tải lại website, giao diện đã hiển thị đúng định dạng.

Thông tin thời gian giao hàng cụ thể chưa được xác minh nên không được tự bổ sung vào bản demo.

Chi tiết quá trình sử dụng AI được ghi trong file `AI_USAGE.md`.

---

**Lưu ý:** Đây là bài tập học tập độc lập. Các hình SVG được sử dụng là hình minh họa, không phải ảnh sản phẩm chính thức của Rong Rong Project.
