


<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>首页</title>
    <style>
    
   #man{
	width: 393px;
       height:100px;
	margin: 0auto;
	border:1px solid dodgerblue;
	position: absolute;
        top:0px;
        left:0px;
 background-color:#000;
}
        h1{
            font-family:'Microsoft YaHei' 'Lucida Sans','Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            
            color:yellow;
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
left:20px;
 }
 #triangle-up {
width: 50px;height: 50px;border-left: 13px solid transparent;border-right: 13px solid red;border-top: 13px solid red;border-bottom: 13px solid red;border-top-left-radius: 50px;border-top-right-radius: 50px;border-bottom-left-radius: 50px;border-bottom-right-radius: 50px;
transform:rotate(-10deg);
position: absolute;top:0px;
}
#trapezoid-down {
width: 13px;/*要等于border-right的值*/
height: 66px;/*尾巴长度*/
border-right: 13px solid red;/*等于宽*/
border-top:3px solid transparent;/*一边斜度*/
border-bottom:5px solid transparent;/*另一边斜度*/
transform:rotate(-20deg);
position:  absolute;/*relative;*/
top:35px;
left:17px;
}
    </style>
</head>
<body>
<div id="man">
<div id="triangle-up"></div>
<div id="trapezoid-down"></div>
</div>
<div class="demo">
   <h1> 三明学邸</h1>
    </div>

<h2>我的第一个标题</h2>
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
</body>
</html>
