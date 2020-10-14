# 使用方法

## 激活adb

### 开启服务

shift右键本文件夹，在此处打开命令窗口

````bash
adb start-server
````

### 手机开启开发者模式和adb

### 验证adb是否连接

````bash
adb start-server
````

## 完善csv文件

请在template.csv中第一行完善测试号码和名字，从第二行开始添加号码和名字。

格式：

| 测试号码 | 测试名字 |
| -------- | -------- |
| 号码     | 名字     |

## 编辑run.py文件

一组引号内的文字为短信内容，可以带空格，未测试回车。

如果需要添加其他信息请从第三列开始添加，并在代码中添加row[2]，相信会adb基本操作的你一定知道该怎么办。

## 运行run.py

