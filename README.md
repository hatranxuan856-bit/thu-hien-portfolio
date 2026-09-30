# Thu Hiền Portfolio

## Cấu trúc

```text
thu-hien-portfolio/
├── index.html
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── main.js
    └── images/
        └── (đặt ảnh portfolio vào đây)
```

## Cách chạy
Mở `index.html` bằng trình duyệt.

## Cách chỉnh sửa
- Nội dung portfolio: `index.html`
- Màu sắc, bố cục, responsive: `assets/css/style.css`
- Menu mobile, lọc dự án, popup chi tiết, copy email, animation: `assets/js/main.js`
- Ảnh: đặt trong `assets/images/`

## Thêm ảnh chân dung
Trong `index.html`, tìm phần `.portrait-placeholder` và thay bằng:

```html
<img src="assets/images/portrait.jpg"
     alt="Trần Thị Thu Hiền"
     style="width:100%;height:100%;object-fit:cover">
```
## Giao diện
Bản hiện tại dùng bảng màu tím–hồng–lime nổi bật, tăng độ tương phản và kích thước chữ để portfolio dễ đọc hơn.
