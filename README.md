![Alt text](https://images.unsplash.com/photo-1587620962725-abab7fe55159?q=80&w=3262&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D "a title")

## Học CSS cùng với Evondev cực hay

#### **I. Sử dụng Selector**

Tags: p, div, h1, h2, main, a, span,...

1. Class:

.demo, .header, .daniel,...

Ví dụ:

```css
.demo {
  property: value, ....;
}
```

2. ID:
   #container, #footer, #head,...

Ví dụ

```css
#footer {
  margin: 5px;
}
```

3. Sử dụng nhiều Selector

```
h1, h2 {
    font-size: 7rem;
}
```

### **II. Thuộc tính color và các giá trị màu sắc**

1. Sử dụng Property và giá trị

Sử dụng thuộc tính `color` và các giá trị như
red, green, orange, blue,...

Ví dụ:

```css
p {
  color: red;
  background-color: yellow;
}
.demo {
  color: orange;
}
```

2. Sử dụng Hexa color
   Sử dụng thuộc tính `color` và các giá trị **hexa** như `#f0f0f0, #fff, #ffa400,...`

Ví dụ:

```css
#container {
  background-color: #ffa400;
}

.header {
  color: #ff7870;
}
```

3. Sử dụng Hexa color với một giá trị

**hexa** một giá trị là cách viết rút gọn của thuộc tính **hexa**

Ví dụ:

```
#footer {
    background-color: #7cd;
}
```

4. Sử dụng **RGB color** với thuộc tính `rbg(value, value, value)`

Ví dụ:

```
.main {
    background-color: rgb(115, 183, 115);
}
```

5. Sử dụng rgba
   `rgba` là cái gì?

Thì `rgba` cũng là `rgb` nhưng nó có thêm một giá trị gọi là **opacity (độ mờ)**. Ví dụ mình sử dùng `css color: rgb(0, 0, 0, 0.8) ` thì **0.8** chính là **opacity** của thuộc tính `rgba`

Ví dụ:

```css
.daniel {
  background-color: rgba(0, 0, 0, 0.5);
}
```

### **III. Tất tần tật về kích thước trong css**

1. Các thuộc tính về kích thước

**width** , **height**, **min-width**, **min-height**, **max-width**, **max-height**,...

2. Các giá trị về kích thước

**px, rem, em, %, vh, vw,...**

**100% = 16px**

Sự khác nhau giữa em và rem:

**em** là đơn vị phụ thuộc vào thuộc tính font-size của chính nó hoặc phần tử chứa nó

còn

**rem**
là đơn vị phụ thuộc vào thuộc tính font-size của thẻ html

`vw` là đơn vị dành cho Background nếu muốn nó phủ toàn màn hình theo lớp cha của nó

và ngược lại thì

`vh` cũng vậy, `vh` cũng là đơn vị giống như `vw`

```css
.em {
  width: 10em;
  height: 10em;
  font-size: 32px;
  background-color: #ffa400;
  text-align: center;
}
.rem {
  width: 10rem;
  max-height: 219px;
  font-size: 32px;
  border: 2px solid black;
}
```

thêm nữa tạo Scroll cho item khi nó vượt quá kích thước bằng cách sử dụng các thuộc tính:

```css
overflow: hidden; /* ẩn khi nó vượt quá kích thước */
overflow-x: hidden;
overflow-x: auto;
overflow-y: hidden;
overflow-y: auto;
```

### **IV. Các thuộc tính về Backgound trong css**

Sử dụng **background** là hình ảnh với thuộc tính

```css
background-image: url(url_image);
width: 100vw;
height: 100vh;
background-repeat: no-repeat;
background-attachment: fixed;
background-size: cover;
background-position: center center; /* set vị trí hình ảnh*/
/* background: url("https://images.unsplash.com/photo-1514539079130-25950c84af65?q=80&w=1469&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D") no-repeat center center / cover fixed; */
/*Ví dụ muốn lấy ảnh ở vị trị giữa thì
    background-position: center center;
    */
```
