# Select & Append

```html
<!DOCTYPE html>
<html>
<head>
    <title>D3 tutorial</title>
    <script src="http://d3js.org/d3.v3.min.js"></script>
</head>

<body>

    <script>
        d3.select('body')
            .append("p")
            .text("Hi, What's up?");
    </script>

</body>

</html>
```



### select

- DOM의 querySelector 처럼 Element를 찾아주는 메소드



### append

- 선택한 Element의 자식 Element를 추가하는 메소드