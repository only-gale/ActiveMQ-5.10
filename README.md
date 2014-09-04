ActiveMQ-5.10
=============

ActiveMQ5.10.0初学习

PS20140904:
因为是在单机上测试，所以需要开启两个eclipse，每一个eclipse都有自身的workspace。我们在eclipse1中运行Receiver，在eclipse2中运行Sender。

刚开始eclipse1中运行Receiver以后console介面没有任何信息，在eclipse2中运行Sender以后，eclipse2中的console显示如下信息：

发送消息：ActiveMq 发送的消息1
发送消息：ActiveMq 发送的消息2
发送消息：ActiveMq 发送的消息3
发送消息：ActiveMq 发送的消息4
发送消息：ActiveMq 发送的消息5

而回到eclipse1中发现console界面出现如下信息：

收到消息ActiveMq 发送的消息1
收到消息ActiveMq 发送的消息2
收到消息ActiveMq 发送的消息3
收到消息ActiveMq 发送的消息4
收到消息ActiveMq 发送的消息5
