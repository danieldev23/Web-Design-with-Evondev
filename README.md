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

### **IV. Các thuộc tính về Backgound trong css**
