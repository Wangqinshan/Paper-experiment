 The experiment of paper
 ====
 Backgroud
 ----
`*`为了模拟基于雾服务器的车联网模式下，车与雾服务器的交互过程。实验的重点是测量车与雾服务器交互的效率，所以直接使用socket实现雾服务器与车辆的通信过程。
<br>`*`且为了实现一个雾服务器对多个车辆的通讯，使用多线程去模拟。
<br>`*`在交互过程中，信息都是以密文的方式实现的，所以涉及到了密码学方面的知识，具体的加密方式有AES，RSA和秘密共享。 
<br>`*`雾服务器通过执行联通块形成算法和雾服务器挑选算法去选取所需的雾服务器，从而实现追踪的目的。
