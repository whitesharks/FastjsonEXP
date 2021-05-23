# FastjsonEXP
FastJson利用工具

恶意类挂载借用wyzxxz老哥的工具，我只是套个壳子

https://github.com/wyzxxz/fastjson_rce_tool

此工具未做加密，不放心的老哥可以自己看，不放源码只因代码太过丑陋

此工具尚不完善，目前仅在靶机环境中测试，欢迎各位老哥提bug

功能如下：

1.检测功能

单目标检测：

![image](https://user-images.githubusercontent.com/29255605/119251358-b8a3ba80-bbd8-11eb-811b-5bdc4fa2ca4d.png)

多目标检测：

![image](https://user-images.githubusercontent.com/29255605/119251398-ed177680-bbd8-11eb-878a-02394412c016.png)

2.利用功能

本地利用：

把fastjson_tool.jar放在fastjson.jar同目录下

输入本机ip及端口后，输入命令，点击监听

![image](https://user-images.githubusercontent.com/29255605/119251476-5303fe00-bbd9-11eb-9f9a-244ba8c5c35b.png)

输入目标地址，选择版本后，点击发送（此处不会提示发送成功失败，结果需要自己查看）

![image](https://user-images.githubusercontent.com/29255605/119251534-9a8a8a00-bbd9-11eb-96e2-0d4077fc08dc.png)

远程利用：

把fastjson_tool.jar放在远程服务器（linux）的root目录下

输入账号密码后，点击测试看是否连接成功

![image](https://user-images.githubusercontent.com/29255605/119251586-daea0800-bbd9-11eb-92f0-97efc32fc014.png)

输入命令，点击监听，等待片刻

![image](https://user-images.githubusercontent.com/29255605/119251620-11278780-bbda-11eb-9d7b-9447adbc4e3b.png)

输入目标地址，选择版本后，点击发送（此处不会提示发送成功失败，结果需要自己查看）

![image](https://user-images.githubusercontent.com/29255605/119251663-47fd9d80-bbda-11eb-83c8-579d80dbbd1b.png)
