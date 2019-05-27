---
id: hello-world
title: Hello World
permalink: docs/hello-world.html
prev: cdn-links.html
next: introducing-jsx.html
---

Ví dụ React đơn giản nhất sẽ trông như thế này:

```js
ReactDOM.render(
  <h1>Hello, world!</h1>,
  document.getElementById('root')
);
```

Nó hiển thị một tiêu đề "Hello, world!" trên trang.

[](codepen://hello-world)

Click vào link trên để mở trình chỉnh sửa trực tuyến. Hãy thoải mái thực hiện một số thay đổi và xem chúng ảnh hưởng như thế nào đến đầu ra. Hầu hết các trang trong hướng dẫn này sẽ có các ví dụ có thể chỉnh sửa như trên.


## Cách đọc hướng dẫn này {#how-to-read-this-guide}

Trong hướng dẫn này, chúng ta sẽ kiểm tra các building blocks của ứng dụng React: elements và components. Một khi thành thạo chúng, bạn có thể tạo các ứng dụng phức tạp từ những mảnh nhỏ có thể tái sử dụng.

>Mẹo
>
>Hướng dẫn này được thiết kế cho những người thích **học các khái niệm theo từng bước**. Nếu bạn thích học bằng cách thực hành, hãy xem [hướng dẫn thực hành](/tutorial/tutorial.html). Bạn sẽ thấy hai hướng dẫn này có sự bổ sung cho nhau.

Đây là chương đầu tiên trong hướng dẫn từng bước về các khái niệm chính của React. Bạn có thể thấy một danh sách tất cả các chương ở thanh bên. Nếu bạn đọc từ thiết bị di động, có thể truy cập điều hướng bằng cách nhấn nút ở góc dưới bên phải màn hình.

Mỗi chương trong hướng dẫn này được xây dựng dựa trên kiến ​​thức được giới thiệu trong các chương trước. **Bạn có thể học hầu hết React bằng cách đọc các chương hướng dẫn “Khái niệm chính” theo thứ tự chúng xuất hiện ở thanh bên.** Ví dụ, [“Giới thiệu JSX”](/docs/introducing-jsx.html) là chương tiếp theo ngay sau đây.

## Giả định trình độ kiến ​​thức {#knowledge-level-assumptions}

React là một thư viện JavaScript, và vì vậy chúng tôi sẽ cho rằng bạn có hiểu biết cơ bản về ngôn ngữ JavaScript. **Nếu bạn không cảm thấy tự tin, chúng tôi khuyên bạn nên [xem qua hướng dẫn về JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript) để kiểm tra trình độ kiến ​​thức của bạn** và cho phép bạn làm theo hướng dẫn này mà không bị mất phương hướng. Nó có thể khiến bạn mất từ ​​30 phút đến một giờ, nhưng kết quả là bạn đã thắng được cảm giác như bạn đang học cả React và JavaScript cùng một lúc.

>Chú thích
>
>Hướng dẫn này thỉnh thoảng sử dụng một số cú pháp JavaScript mới trong các ví dụ. Nếu bạn đã không làm việc với JavaScript trong vài năm qua, [ba điểm này](https://gist.github.com/gaearon/683e676101005de0add59e8bb345340c) sẽ giúp bạn hiểu rõ hơn.


## Bắt đầu thôi! {#lets-get-started}

Tiếp tục kéo xuống, và bạn sẽ thấy link đến [chương tiếp theo của hướng dẫn này](/docs/introducing-jsx.html) ngay trước phần chân trang.


