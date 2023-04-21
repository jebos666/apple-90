# apple-91大神
simple code
// ----------------------------------------------

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        .box {
            width: 300px;
            height: 300px;
            background-color: pink;
        }
        /* 观察当元素本身有宽高，伪类选择器作用范围。和在伪元素本身添加时候的比较,以元素本身优先级更高 */
        
        .box a:hover {
            display: block;
            background-color: blue;
            width: 100px;
            height: 50px;
        }
        
        a {
            display: block;
            width: 50px;
            height: 50px;
            padding-bottom: 150px;
            margin-bottom: 50px;
        }
    </style>
</head>

<body>
    <div class="box">
        <a href="#">frgggfrge</a>
    </div>
</body>

</html>
