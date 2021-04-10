<!DOCTYPE html>
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>首页</title>
    <style>
      #main{
	width: 1500px;
	margin: 0 auto;
	border:1px solid dodgerblue;
}
        h1{
            font-family:'Microsoft YaHei' 'Lucida Sans','Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            
            color:blue;
            font-size: 30px;
            font-weight: bold;
            font-style: normal;
            letter-spacing:0px;
        }
     .demo * {
 width: 130px;
 height: 50px;
 border:1px solid transparent;
 margin: 15px;
position: absolute;
top:40px;
left:438px;
 }
    </style>
</head>
<body>
<style>
#triangle-up {
width: 50px;
height: 50px;
border-left: 13px solid transparent;

border-right: 13px solid red;
border-top: 13px solid red;
border-bottom: 13px solid red;
border-top-left-radius: 50px;
border-top-right-radius: 50px;
border-bottom-left-radius: 50px;
border-bottom-right-radius: 50px;
position: absolute;
top:0px;
}
#triangle-down{
width: 15px;
height: 50px;
margin-left:5px;
-webkit-transform: skew(26deg);
-moz-transform: skew(10deg);

background: red;
position:  absolute;/*relative;*/
top:34px;
left:427px;
}
</style>
<div id="main">
<div id="triangle-up"></div>
<div id="triangle-down"></div>
<div class="demo">
   <h1> 三明学邸</h1>
    </div>
<h1>我的第一个标题</h1>
<p>我的第一个段落。

 <a href="https://sanmingxuedi.github.io/index.html">这是一个链接使用了 href 属性</a>
 再写点什么
 </p>
 <p>我的第二个段落。
 <table border="1">
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
        <th>Header 4</th>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td><a href="https://sanmingxuedi.github.io/index.html">第一部</a></td>
        <td>row 1, cell 2</td>
        <td>row 1, cell 3</td>
        <td>row 1, cell 4再添一些文字链接</td>
        <td>row 1, cell 5</td>
        <td>row 1, cell 6</td>
    </tr>
    <tr>
        <td>row 2, cell 1</td>
        <td>row 2, cell 2</td>
        <td>row 2, cell 3</td>
        <td>row 2, cell 4</td>
        <td>row 2, cell 3</td>
        <td>row 2, cell 4</td>
    </tr>
    <tr>
        <td>row 2, cell 1</td>
        <td>row 2, cell 2</td>
        <td>row 2, cell 3</td>
        <td>row 2, cell 4</td>
        <td>row 2, cell 3</td>
        <td>row 2, cell 4</td>
    </tr>
</table>
</p>
</div>
</body>
</html>
