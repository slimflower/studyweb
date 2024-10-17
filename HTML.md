# Giới thiệu HTML(HTML Introduction)
## HTML là gì?
- HTML là viết tắt của Hyper Text Markup Language.
- HTML mô tả cấu trúc của một trang web.
- HTML bao gồm một loạt các phần tử.
- Các thành phần HTML cho trình duyệt biết cách hiển thị nội dung
- Các phần tử HTML gắn nhãn cho các phần nội dung như "đây là tiêu đề","đây là đoạn văn","đây là liên kết".
### Ví dụ :
 ```<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
- Tuyên bố này `<!DOCTYPE html>`xác định rằng tài liệu này là tài liệu HTML.
- Phần `<html>`tử là phần tử gốc của một trang HTML.
- Phần `<head>`tử chứa thông tin meta về trang HTML.
- Phần tử này `<title>`chỉ định tiêu đề cho trang HTML (được hiển thị trên thanh tiêu đề của trình duyệt hoặc trên tab của trang).
- Phần tử này `<body`>xác định phần nội dung của tài liệu và là nơi chứa tất cả nội dung hiển thị, chẳng hạn như tiêu đề, đoạn văn, hình ảnh, siêu liên kết, bảng, danh sách, v.v.
- Phần tử này `<h1>`xác định một tiêu đề lớn.
- Phần tử này `<p>`xác định một đoạn văn.
## Phần tử HTML là gì?
Một phần tử HTML được xác định bởi một thẻ bắt đầu -> nội dung -> Thẻ kết thúc .<p>
`<tagname>Nội dung ở đây...</tagname>`<p>
- Phần tử HTML bao gồm mọi thứ từ thẻ bắt đầu đến thẻ kết thúc:<p>

  |Start tag|Element content|End tag|
  |:---|:---|:---|
  |`<h1>`|My first heading|`</h1>`|
  |`<p>`|My first paragraph|`</p>`|
  |`<br>`|none|none|

## Trình duyệt web
- Mục đích của trình duyệt web (Chrome,Edge,Firefox,Safari) là đọc tài liêuj HTML và hiển thị chúng một cách chính xác .
## Cấu trúc trang HTML 
Dưới đây là hình ảnh trực quan về cấu trúc trang HTML:<p>
<img width="663" alt="Ảnh màn hình 2024-10-17 lúc 08 41 35" src="https://github.com/user-attachments/assets/dd85ead7-328d-4645-9290-a33b1d3bc680"><p>
**Lưu ý**: Nội dung bên trong phần <body> sẽ được hiển thị trong trình duyệt. Nội dung bên trong phần tử <title> sẽ được hiển thị trên thanh tiêu đề của trình duyệt hoặc trên tab của trang.<p>
# Ví dụ cơ bản về HTML (HTML Basic Examples)
## Tài liệu HTML
- Tất cả tài liệu HTML phải bắt đầu bằng khai báo loại tài liệu: `<!DOCTYPE html>`.
- Bản thân tài liệu HTML bắt đầu bằng `<html>`và kết thúc bằng `</html>`.
- Phần hiển thị của tài liệu HTML nằm giữa `<body`>và `</body>`.
### Ví dụ :
```<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
## Tuyên bố `<!DOCTYPE>`
- Khai báo này `<!DOCTYPE>`thể hiện loại tài liệu và giúp trình duyệt hiển thị các trang web một cách chính xác.
- Nó chỉ được xuất hiện một lần, ở đầu trang (trước bất kỳ thẻ HTML nào).
- Tuyên bố này `<!DOCTYPE>`không phân biệt chữ hoa chữ thường.
- Tuyên `<!DOCTYPE>`bố cho HTML5 là: `<!DOCTYPE html>`
## Tiêu Tiêu đề HTML
- Tiêu đề HTML được định nghĩa bằng thẻ `<h1>`to `<h6>`.
## Đoạn văn HTML 
Các đoạn văn HTML được định nghĩa bằng `<p>`thẻ:<p>
Ví dụ :<p>
```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```
## Liên kết HTML
Liên kết HTML được định nghĩa bằng `<a>`thẻ:<p>
```
<a href="https://www.w3schools.com">This is a link</a>
```
- Điểm đến của liên kết được chỉ định trong hrefthuộc tính.
- Thuộc tính được sử dụng để cung cấp thông tin bổ sung về các phần tử HTML.
## Hình ảnh HTML 
- Hình ảnh HTML được định nghĩa bằng <img>thẻ .<p>
- Tệp nguồn ( src), văn bản thay thế ( alt), widthvà heightđược cung cấp dưới dạng thuộc tính:
```
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```
# Các phần tử HTML (HTML Elements)
## Các phần tử HTML 
Phần tử HTML bao gồm mọi thứ từ thẻ bắt đầu đến thẻ kết thúc:<p>
