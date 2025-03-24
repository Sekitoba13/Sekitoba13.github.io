<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="/api" method="post">
        昵称:<input type="text" name="" id=""><br>
        密码:<input type="password" name="" id=""><br>
        邮箱:<input type="text" name="" id=""> <select>
            <option>qq.com</option>
            <option>hotmail.com</option>
        </select><br>
        性别:<input type="radio" name="m" value="1"><label for="m">男</label><input type="radio" name="m" value="2"><label for="f">女</label><br>
        爱好:<input type="checkbox" name="" id="">学习<input type="checkbox" name="" id="">运动<input type="checkbox" name="" id="">游戏<br>
        个人简介：<br>
        <textarea name="" id="" cols="30" rows="10"></textarea><br>
        上传个人照片:<br>
        <input type="file" /><hr>
        <input type="submit" value="立即注册" />
