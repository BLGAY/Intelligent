# Intelligent
基于zigbee协议栈的网关代码<br>
实现了同种传感器的分别控制<br>
摄像头的集成<br>
socket的本地上传<br>
基本的控制功能<br>
以及足够用的串口源代码<br>
<br>
本系统集成了两个温度湿度光照传感器、两个电机、红外、PWM、烟雾、摄像头、协调器<br>
<br>
调试过程中使用移植到 TQ210-linux开发板 的ssh服务进行调试<br>
<br>
代码可以作为摄像头模块调用的demo来学习<br>
<br>
最近添加了多线程功能（mythread.h & mythread.cpp）来实现socket的收发信息，其中包括socket的使用demo
