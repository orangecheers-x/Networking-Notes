绪论部分

计网是我见过的绪论部分最难的科目

# Chapter 1 绪论

### 数据通信的五个组成部分

1. 报文
2. 发送方
3. 接收方
4. 传输介质
5. 协议

### 数据流

1. 单工
2. 半双工
3. 双工

### 连接类型

1. 点到点, 就是一对设备单独用一个线路, 没有其他设备.
2. 多点, 就是一堆设备连一起.

### 网络拓扑结构

1. 网状, 就是随意的连一起, 任何两个设备之间都可能有边.
2. 星型, 就是全部连到一个Hub上
3. 总线, 一个总线连一堆其他设备
4. 环状, 字面意思.

### 网络分类

局域网 城域网 广域网



### 协议的三要素

1. 语法
2. 语义
3. 时序



机械特性, 尺寸大小

电气特性, 电压

功能特性, 线的用途

过程特性, 时序



**先高后低是0**



基带传输是数字信号(高低电平), 宽带是模拟信号, 模拟信道传数字信号叫频带传输

同步传输以帧位单位, 异步传输以字节为单位, 每一个字节前后都要加标志位.



带宽乘2等于波特率

双绞线传 数字信号

同轴电缆误码率最低



直接交付?

**私有地址?**

IPv4不允许分片

IPv6没头部校验和

OSPF 4次Hello没响应 就认为他死了

路由器按照子网安排路由表, 所以不在一个子网的东西发都发不出去

链路层, 差错控制, 流量控制

网络层, 只有首部校验, 没有整体校验. IPv4有总长度和头长度.

传输层, 拥塞控制, 流量控制, 差错控制. 都有全部校验, TCP没有长度, UDP有总长度.

先高后低0 

差分是看后一段, 0后一段不变, 1反向





# Chapter 2 网络模型



