# 微信命令行版
- 命令行版的微信，上班专用，不用打开微信也能够进行收发消息啦。
- 老板以为我在敲命令，其实我在回微信，办公室利器。
- 两个命令行窗口，一个用于发消息，一个用于打印消息，两个窗口之间用socket套接字进行通信。

## 一.功能
- 1.实现了从所有人中选择一个发消息
- 2.实现了从最近10个联系人中选择一个发消息
- 3.实现了选择上一个联系人发消息
- 4.实现打印与该联系人的聊天记录
- 5.实现了滚动打印实时收到的消息
键入r：从10个最近联系人选择一个发消息   
键入l：选择上一个联系人发消息   
键入用户名：直接给改用户发消息     
键入b：返回到选择联系人 

## 二.依赖
```
python3 + itchat
```

## 三.环境
```
mac /windows /linux
```

## 四.运行
- 1.pip install itchat
- 2.git clone https://github.com/lim1942/cmd_wechat
- 3.python3 wechat.py    (运行后，进行扫码登录，即可收发消息啦)
- 4.python3 scroll_mess_server.py  （可选运行）运行后可打印实时收到的新消息,在 wechat.py 运行后才可运行。  


## 五.展示
2018-11-07 10:34:37 * Me *:  对的  
2018-11-07 10:34:40 * Me *:  测试  
2018-11-07 10:34:47 * Me *:  实时消息  
2018-11-07 10:34:55 韩瑞 :  滚动打印  
2018-11-07 10:35:12 * Me *:  你在吗  
2018-11-07 10:35:29 * Me *:  江少华  
2018-11-07 10:35:44 江少华 :  嗯嗯好的  



-
-作者：何林 
-e-mail:940711277@qq.com



