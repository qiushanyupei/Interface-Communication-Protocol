<img width="453" height="185" alt="image" src="https://github.com/user-attachments/assets/81552c42-207e-499c-a0df-8d12aace8f13" />
1️⃣ IP 协议（网络层）
Internet Protocol
作用：
负责寻址
负责数据包路由
不保证可靠性
IP地址示例：
192.168.1.1
分为：
IPv4
IPv6
IP 的特点：
无连接
不可靠
尽最大努力传输
2️⃣ TCP 协议（传输层）
Transmission Control Protocol
作用：
可靠传输
有序传输
流量控制
拥塞控制
三次握手：
SYN
SYN-ACK
ACK
建立连接。
TCP 特点：
面向连接
可靠
有序
慢但安全
3️⃣ UDP 协议（传输层）
User Datagram Protocol
特点：
无连接
不可靠
快
无拥塞控制
适用场景：
视频直播
语音通话
实时游戏
4️⃣ HTTP 协议（应用层）
HTTP
基于 TCP。
用于：
浏览网页
RESTful API
前后端通信
三、TCP/IP 数据封装过程（重点）
假设你访问一个网站：
HTTP 生成请求
TCP 封装成段
IP 封装成数据包
以太网封装成帧
发送出去
封装顺序：
