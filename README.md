以下是用html和css做的用户登录系统界面，在html中引用login.css实现的，在web.h中用表格的形式做了用户名、密码、登陆、注册，用
  id和name标记，然后在css中设定具体的样式，从而完成了一个简单的界面作为一个html和css的完全的一个小白我在题目发出来的这几天里了解并学会了
html的一些常用 元素及其属性，学会了如何设置文字、图片、邮箱、下载地址的超链接，初步掌握了表格的制作和div布局，分分钟做一个包括合并行、列，
 文字的颜色等设定的表格还有div一个网页布局是没问题的，能够 比较熟练的使用sublime text3.0的一些
  快捷键和基本操作 如下代码只是做了一个简单的登陆界面，下面来看代码：
/ /web.html文件
<html>

<head>
    <title>Welcome</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
    <link href="login.css" type="text/css" rel="stylesheet">
</head>

<body>
    <form>
        <table width="202" border="0" align="center" cellpadding="05" cellspacing="0" id="logintable">//定义并构造表格的基本框架
            <tr>
                <td width="192">
                    <div class="message">欢迎使用该系统</div>
                </td>
            </tr>
            <tr>
                <td>
                    <input name="name" type="text" id="username" value="" placeholder="用户名">
                </td>
            </tr>
            <tr>
                <td>
                    <input name="psd" type="password" id="password" value="" placeholder="密码">
                </td>
            </tr>
            <tr>
                <td id="tip"> </td>
            </tr>
            <tr>
                <td>
                    <input type="button" class="submit" value="登录" onclick="login()">
                </td>
                <td>
                <input  type="button"  class="submit" value="注册" onclick="login()">
                </td>
            </tr>
        </table>
    </form>
</body>

</html>
   //***********************下面是css
 //login.css
     body {  
    background-color: #F5F5F5;  
    font-family: Arial, Helvetica, sans-serif;  
    color:#666;  
}  
  
input {  
    padding: 9px;  
    border: solid 1px #E5E5E5;  
    outline: 0;  
    width: 200px;  
    background: -webkit-gradient(linear, left top, left 25, from(#FFFFFF), color-stop(4%,#EEEEEE),to(#FFFFFF));  
    background: -moz-linear-gradient(top, #FFFFFF, #EEEEEE 1px, #FFFFFF 25px);  
    box-shadow: rgba(0,0,0, 0.1) 0px 0px 8px;  
    -moz-box-shadow: rgba(0,0,0, 0.1) 0px 0px 8px;  
    -webkit-box-shadow: rgba(0,0,0, 0.1) 0px 0px 8px;  
    font-family: Verdana, Tahoma, sans-serif;  
    font-size: 13px;  
    font-style: normal;  
    line-height: 100%;  
    font-weight: normal;  
    font-variant: normal;  
    color: #617798;  
}  
  
.submit {  
    width: auto;  
    padding: 9px 15px;  
    background: #617798;  
    border: 0;  
    font-size: 14px;  
    color: #FFFFFF;  
    -moz-border-radius: 5px;  
    -webkit-border-radius: 5px;  
    cursor: pointer;  
}  
  
input:hover,  
input:focus {  
    border-color: #C9C9C9;  
    -webkit-box-shadow: rgba(0, 0, 0, 0.15) 0px 0px 8px;  
    color: #617798;  
}  
  
#logintable {  
    font-family: Arial, Helvetica, sans-serif;  
    background-color: #fefefe;  
    border: 1px solid #CCC;  
    color: #333;  
    box-shadow:0px 0px 8px #cccccc;  
    -moz-box-shadow:0px 0px 8px #cccccc;  
    -webkit-box-shadow:0px 0px 8px #cccccc;  
    -webkit-border-radius: 10px;  
    -moz-border-radius: 10px;  
    border-radius: 10px;  
    padding:10px;  
    margin-top: 50px;  
}  
              
.message {  
    text-align: center;  
    padding: 20px;  
    font-size: 24px;  
    text-shadow: -1px -1px 1px #cccccc;  
    filter: dropshadow(color=#ffffff, offx=1, offy=1);  
    color: #617798;  
}上面 的代码只是一个简单界面的制作，无法实现登陆与注册功能的跳转，网上可以实现这一功能的html代码非常少
 我找到的是通过JavaScript和Ajax连接PHP+MySQL实现用户登录注册API接口，对于这种方法我尝试过但是由于自己对js还有数据库
 php了解的少它里面的数据库的登陆（我下载了专门登陆数据库的软件尝试过很多次登陆代码中的数据库都失败了）对于js我知道是做web前端
 必须的，现在只能看懂一点基本的语言，但是我会努力去学习的，上面的登陆界面的实现我现在可以独立完成，这是我这几天学到的，
 当然还有一些东西上面的代码与功能没有体现
  虽然这次的题目我没有完全做完，但是这个过程我觉的很有趣，我觉得学习这些东西的过程跟玩游戏一样，我可能上瘾了，不管这次有没有
   进去下一轮，我都会坚持学下去的，我的目标就是可以达到熟练运用html，css与js
   
