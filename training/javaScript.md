---
sort: 1
---

## JavaScript

### Định nghĩa

- JavaScript (viết tắt là "js") là một ngôn ngữ lập trình mang đầy đủ tính năng của một ngôn ngữ động, được tích hợp và nhúng trong HTML giúp website sống động hơn. Cụ thể hơn, JavaScript có thể tính toán, thao tác, và phê duyệt dữ liệu cũng như cập nhật thay đổi cả HTML và CSS của trang web.

- Ngoài việc ứng dụng trong lập trình các website thì JavaScript còn có thể sử dụng để xây dựng ứng dụng cho website máy chủ và ứng dụng di động, app và thậm chí cả game

### Kiến thức cơ bản

1. Biến
- Có 7 kiểu cơ bản: 
  + String
  + Number
  + Boolean
  + Undefined: Undefined có nghĩa là không xác định. Khi bạn khai báo một biến mà không gán giá trị cho nó, giá trị của biến đó sẽ là undefined
  + Null: Null có nghĩa là giá trị rỗng hoặc giá trị không tồn tại, nó có thể sử dụng để gán cho một biến như là một đại diện không có giá trị.
  + Function
  + Object: Về mặt định nghĩa, một đối tượng (một object) là một danh sách các item, mỗi item là một cặp name-value, trong đó value có thể là: các kiểu dữ liệu cơ bản, function, hay cũng có thể là một object khác (kiểu dữ liệu phức hợp).

2. Function
- Function (hàm, chức năng), gọi chung là subprogram (chương trình con) có thể được gọi ở bên ngoài hoặc bên trong chính nó

```js
function nameFunction(parameter1, parameter2) {
  //Code here
}
```

- Function không có tham số và không trả về bất cứ giá trị gì.

```js
function hello() {
    console.log('hello')
}

hello();
```

- Function vô danh (Anonymous functions)

Anonymous functions hay còn gọi là hàm ẩn danh, là một hàm được sinh ra đúng vào thời điểm chạy của chương trình. Thông thường khi bạn khai báo một hàm thì trình biên dịch sẽ lưu lại trong bộ nhớ nên bạn có thể gọi ở trên hay dưới vị trí khai báo hàm đều được, nhưng với anonymous functions thì nó sẽ được sinh ra khi trình biên dịch xử lý tới vị trí của nó.

```js
var func = function () {
    console.log('Hello function');
}

func();
```

- Function có một tham số và trả về một giá trị cụ thể

```js
function square(number) {
    return number * number
}

console.log(square(2))
```

- Function self-invoking: Đây là function có thể gọi chính nó
```js
(function selfInvoking() {
  console.log('Hello')  
}()) 
```
