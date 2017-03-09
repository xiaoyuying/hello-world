
web.html
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
   //下面是css
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
}
   
