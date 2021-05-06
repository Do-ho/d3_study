# Basic SVG Shapes

```html
<!DOCTYPE html>
<html>
<head>
    <title>D3 tutorial</title>
    <script src="http://d3js.org/d3.v3.min.js"></script>
</head>

<body style="margin: 0">

    <script>
        let canvas = d3.select('body')
            .append("svg")
            .attr("width", 500)
            .attr("height", 500);
        
        let circle = canvas.append("circle")
            .attr("cx", 250)
            .attr("cy", 250)
            .attr("r", 50)
            .attr("fill", "red");

        let rect = canvas.append("rect")
            .attr("width", 100)
            .attr("height", 50);
        
        let line = canvas.append("line")
            .attr("x1", 0)
            .attr("y1", 100)
            .attr("x2", 400)
            .attr("y2", 400)
            .attr("stroke", "green")
            .attr("stroke-width", 10);
    </script>

</body>

</html>
```



### circle

- cx : 중심 x좌표
- cy : 중심 y좌표
- r : 반지름
- fill : 채우기



### rect

- width : 가로
- height : 세로



### line

- x1, y1, x2, y2를 지정
- stroke의 색깔과 굵기를 지정