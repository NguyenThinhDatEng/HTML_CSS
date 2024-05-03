# HTML

## Operators

### \*

## Elements

### a Tag

#### rel="noopener" with target="\_blank"

- Với cách làm trên có 2 vấn đề về bảo mật và hiệu suất:

1. Tại trang đích có thể sử dụng window.opener để kiểm soát được cửa sổ trang gốc của chúng ta, ví dụ chạy window.opener.location.href = 'https://fullstack.edu.vn/' là có thể chuyển hướng cửa sổ gốc tới https://fullstack.edu.vn/. Hãy tưởng tượng bạn bị chuyển tới một URL có nội dung “độc hại” như 18+ (khi ngồi cạnh người yêu), hay các trang giả mạo để đánh cắp tài khoản ngân hàng, thông tin cá nhân, v.v…
2. Trang đích chạy cùng tiến trình xử lý Javascript với trang gốc, nếu trang đích sử dụng nhiều logic “nặng” hoặc tối ưu chưa tốt về mặt hiệu năng có thể làm ảnh hưởng tới trang web của bạn đang được mở tại cửa sổ gốc.

## Popular components

1. Header
2. Navigation
3. Breadcrumbs
4. Banner
5. Sidebar
6. Slider
7. Footer

## Keywords

- Overlay

# CSS

## Priority

1. Inline 1000
2. #id 100
3. .class 10
4. tag 1
5. #id.class 110

## Functions

1. var(variable)
2. linear-gradient()
3. rgba(red, green, blue, alpha)
4. rgb(a, b, c)
5. calc(size)
6. attr(attribute)

## Pseudo classes

### :

1. root
2. hover
3. active
   Click + Hold left mouse button
4. first-child
5. last-child

### ::

1. before

- Properties
  content: ""
  display: block

2. after

- Properties
  content: ""
  display: block

3. first-letter
4. first-line
5. selection (highlight by mouse)

## Properties

### box-sizing

1. border-box
   content-width = Element width - padding width - border width
2. content-box (Normal)

### background-image

1. background-image (can combined (many url, url with linear-gradient))

- url();
- linear-gradient(deg, from color, to color)

2. background-size

- contain
  Take the longest edge of the photo (ensure 100% of the image)
- cover
  Take the longest edge of browser (Take a part of the image but cover the screen)

3. background-origin

- padding-box (default) - Fill the image over padding part
- border-box - Fill the image over border part
- content-box - Only fill the image over the content part

4. background-position

- Case 1: position position
  Examples: bottom center, top left, ...
- Case 2: specific positioning
  Example: Left: 50px, top: 50px (50px 50px)

### display

1. block
   => set width of the element equal width of the parent element

2. inline-block

- inline: set elements in a line
- block: allow to control the size of element
  => set width of the element equal sum width of it's children

### float

- With display: block
  => Ignore to set element width equal parent width

### padding

- Using % => Auto set by it's own width (Ex: padding-top: 50%)

## Postion

1. Relative (Take itself as the origin coordinate)

- relations: top, left, bottom, right

2. Absolute (Take the nearest parent with the attribute 'position' as the origin coordinate)
3. Fixed (Take the body element as the origin coordinate)
4. Sticky

- top: 0;
- bottom: 0;

# Javascript

## keyword

- MODAL
