# 2020.05.01 Javascript연습
## Local Storage 이용한 Todolist 작성 웹어플리케이션
## https://youtu.be/Ttf3CEsEwMQ 참고함

```html
<!-- FontAwesome CDN -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css"
        integrity="sha256-h20CPZ0QyXlBuAw7A+KluUYx/3pK+c7lYEpqLTlxjYQ=" crossorigin="anonymous" />
```

```css
/* click disable */
selector {
	pointer-events : none;
}
```

```js
/* domcontentloaded */
document.addEventListener('DOMContentLoaded', getTodos);

/* form submit disable */
todoButton.addEventListener('click', addTodo);
function addTodo(event) {
    //prevent form from submitting
    event.preventDefault();
}
```