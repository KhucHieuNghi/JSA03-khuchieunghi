# Lập trình Web
- website tham khảo: http://www.omnifood.net

## HTML ( Các thẻ thường sử dụng )
> Lưu ý: Mở thẻ là phải đóng thẻ 
***Thẻ tạo các khối***
- div
- p
- a
- span
- h1-6

***Thẻ tao Medias***
- video
- img

Ví dụ:
``` 
    <div id='' class='' > Thẻ div </div>
    <video src=" ./video.mp4 " /> 
    <img src=" ./hinh-anh.png " /> 
```

***

## CSS (các thuộc tính thường dùng)
***Chữ***
- font-size: Thay đổi kích thước chữ
- font-weight: Thay đổi độ đậm nhạt của chữ
- color: Thay đổi màu săc của chữ
- text-transform: In hoa chữ viết hoặc, viết thường chữ viết


Ví dụ:
```
    .class {
        font-size: 16px;
        font-weight: bold;
        color: red;
        text-transform: uppercase;
    }
```

***Dàn bố cục***
- display: flex
    - align-items: Căn lề các phần từ con theo chiều dọc
    - justify-content: Căn lề các phần tử con theo chiều ngang

Ví dụ:
```
    .class, div, span, p, img{
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
```

***Khoảng cách***
- margin
    - margin-left
    - margin-right
    - margin-top
    - margin-bottom
- padding
    - padding-left
    - padding-right
    - padding-top
    - padding-bottom

***Khung***
- border: Viền bên ngoài
- border-radius: Bo tròn khung
- background: Màu sắc của khung hoặc 1 hình ảnh
    - background-image: url("./hinh-anh.png")

Ví dụ:
```
    .class, div, span, p, img{
        border: 1px solid red;
        border-radius: 99px;
        background-image: url("./hinh-anh.png")
    }
```

***

## HTML Nâng cao
> HTML5 semantic giúp cho người đọc hình dung được nơi đặt vị trí của trong bố cục thiết kế website thay vì chỉ dùng thẻ div
***Thẻ tạo các khối***
- section
- article
- nav
- aside
- header
- footer

***

## CSS Nâng cao
> Sử dụng các thuộc tính hiệu ứng khi trỏ chuột vào 1 khối ( tag: div, span, a,... )

> Sử dụng các thuộc tính tính hỗ trợ "responsive"
![Thuộc tính CSS hỗ trợ responsive](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp) (&lt;a&gt;)

Ví dụ:
```
    .class{
        background: red;
    }
    .class:hover{
        background: blue;
    }
```


