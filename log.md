# 宕机日志
![宕机](https://github.com/lyMeiSEU/Down-log/blob/master/Dangji.jpg)
## 第一次宕机：
### 原因：随手删除了动态链接库文件.dll
### 解决方法：当时比较菜，直接重装了系统
## 第二次宕机：
### 原因：无效的驱动签名
### 解决方法：启动设置，禁用
## 第三次宕机
### 原因一样
### 忍不了了，命令提示符输入bcdedit.exe /set nointegritychecks on
#### 永久禁用数字签名(Windows设计数字签名的目的是保障系统的安全性，禁用可以会对电脑安全性有一些影响，最好的解决方法是用官网驱动）
### 想要回复驱动签名检测：开启数字签名的话bcdedit.exe /set nointegritychecks off