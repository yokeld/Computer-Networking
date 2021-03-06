## 单项选择题 14

- 1.网络协议中定义实体之间交换信息格式与结构的协议的要素是
  - A 语法

- 2.当某个分组在输出链路发送时，从发送第一位开始到发送完最后一位为止所用的时间称为
  - C 传输时延

- 3.设信号传输速度 V=2500km/s，链路长度 D=500m, 链路带宽 R=10Mbit/s，则该段链路的时延带宽积为
  - B 2000 bit

- 4.在 OSI 参考模型中，数据链路层的协议数据单元（PDU）称为
  - C 帧

- 5.TCP/IP 参考模型的核心层是
  - B 网络互联层

- 6.分别用 a-m 共 13 个英文字母命名的域名服务器是
  - A 根域名服务器

- 7.HTTP 报文中最常见的请求方法是
  - C GET

- 8.下列关于 Cookie 的说法错误的是
  - B Cookie 由客户端生成

- 9.电子邮件应用中将非 ASCII 码文本转换为 ASCII 码文本内容的协议是 
  - A MIME 协议

- 10.在 Socket 编程过程中绑定套接字的本地端点地址是的 SocketAPI 函数是
  - B bind

- 11.从滑动窗口协议的角度，选择重传(SR)协议的发送窗口 W，与接收窗口 W，满足
  - B Ws > 1，Wr > 1

- 12.虚电路网络是一种
  - B 分组交换网络

- 13.在网络层实现网络互连的设备是
  - A 路由器

- 14.总长度为 38008 的 IP 数据报通过 MTU 为 15008 的链路传输，则该数据报需分成的片数和 MF 标志为：
  - A 3 和 1，1，0

- 15.设子网中主机的 IP 地址为 192.168.0.135，子网掩码为 255.255.255.192，该子网地址和子网所包含的 IP 地址总数分别为
  - C 192.168.0.128/26 和 64

- 16.可以作为 IPv6 数据报源地址和目的地址的地址类型是
  - B 单播地址

- 17.对于二进制数据 0111011 采用奇校验和偶检验编码后的码字分别为
  - C 01110110 和 01110111

- 18.下列以太网的 MAC 地址表示中错误的是
  - D．43：25：AB：E5：2L：44

- 19.划分虚拟局域网的方法中不包括
  - C 基于安全需求划分

- 20.利用带宽为 4000Hz 的无噪声信道传输二进制基带信号，其最大的传输速率可达到
  - D 8000bps

- 21.若利用电平的变化与否表示信息，且相邻脉冲用电平有跳变表示 1，无跳变表示 0，则该编码类型属于
  - B 差分码

- 22.指明利用接口传输比特流的全过程以及各项用于传输事件发送的合法顺序的物理层接口特性是
  - D 规程特性

- 23.最高具有 11Mbit/s 速率且工作在无需许可的 2.4GHz 的无线频谱上的无线局域网标准是
  - B IEEE802.11b

- 24.IEEE802.11 帧的类型中不包括
  - D 无编号帧

- 25.下列加密算法中属于公开密钥算法的是
  - C RSA

## 填空题 3
- 26.在目前的互联网环境下，软件共享的典型形式是（SaaS（软件即服务））；
- 27.对于报文和分组交换方式来说，更为公平的交换方式是（分组交换）；
- 28.每个 URL 地址主要包括存放对象的服务器主机域名（或IP 地址）和（对象的路径名）；
- 29.从传输层的角度来看，端到端的通信是（应用进程）之间的通信；
- 30.路由选择算法可分为全局式路由选择算法和（分布式）路由选择算法；
- 31.冲击噪声引起的第一位错误与最后一位错误之间的长度称为（突发长度）；
- 32.广泛应用于光纤通信中的多路复用技术是（波分多路复用）技术；
- 33.令牌环网上最严重的两种错误是令牌丢失和（数据帧无法撤销）；
- 34.HDLC 的三种帧类型是信息帧、管理帧和（无序号帧（U帧)）；
- 35.无状态分组过滤器是典型的部署在内部网和（网络边缘路由器）上的防火墙；

## 简答题 6
- 36.简述米勒码的编码规则；
  - 答：
    - 信息码中的 1 编码为双极非归零码的 01 或者 10；
    - 信息码连 1 时，后面的 1 要交替编码；
    - 信息码中的 0 编码为双极非归零码 00 或者 11，即码元中间不跳变；
    - 信息码单个 0 时，其前沿、中间时刻、后沿均不跳变；
    - 信息码连 0 时，两个 0 码元的间隔跳变；

- 37.简述路由器输入端口接收和处理数据的过程；
  - 答：输入端口负责从物理接口接收信号，还原数据链层帧，提取 IP 数据报，根据 IP 数据报的目的 IP 地址检索路由表，决策需要将该数据报交换到哪个输出端口。

- 38.简述非坚持 CSMA 的基本原理；
  - 答：若通信站有数据发送，先侦听信道，若发现信道空闲，则立即发送数据，若发现信道忙，则等待一个随机时间，然后重新开始侦听信道，尝试发送数据；如果发送数据时产生冲突，则等待一个随机时间，然后重新开始侦听信道，尝试发送数据。

- 39.简述地址解析协议 ARP 的作用及其基本思想
  - 答：ARP 用于根据本网内目的主机和默认网关的 IP 地址获取其 MAC 地址；基本思想：在每一台主机中设置专用内存区域作为 ARP 高速缓存区域，存储该主机所在局域网中其他主机和路由器（即默认网关）的 IP 地址和 MAC 地址的对应关系，并且要经常更新这个地址表。ARP 通过广播 ARP 查询报文的方式来询问某目的站的 IP 地址对应的 MAC 地址。即知道本网内某主机的 IP 地址，可以查询得到其 MAC 地址。

- 40.简述差错控制的概念及差错控制的基本方式；
  - 答：差错控制就是通过差错编码技术，实现对信息传输差错的检测，并基于某种机制进行差错纠正和处理。差错控制的基本方式主要包括：检错重发、前后纠错、反馈校验、检错丢弃。

- 41.简述 IEEE802.11 中四个主要协议具有的共同特征；
  - 答：
    - 都使用相同的介质访问控制协议 CSMA/CA；
    - 链路层的帧使用相同的格式；
    - 都具有降低传输速率以增加传输距离的能力；
    - 都支持“基础设施模式”和“自组织模式”两种模式；

## 综合题 22
- 42．(10分)设Bob给Alice发送了frgh和cuerippnori$ottknlmrwpce两段密文。其中第一段密文为密钥k=3(字符集为26个小写英文字母)的恺撒密码，第二段密文是采用了第一段密文的明文作为加密密钥的列置换密码(填充字符为$)。试求：
  - (1)第一段密文的明文：
    - 答：code；
  - (2)第二段密文的明文(写出解密过程)。
    - 答：computer network principle；

- 43．(13分)题43图是某个TCP连接(协议为TCP—Reno)的拥塞窗口随RTT的变化过程。请回答如下问题：
  - (1)第1个RTT时的拥塞窗口阈值是多少?
    - 答：16 MSS；
  - (2)说明该过程中哪些时间段为慢启动阶段?
    - 答：0~4，17~20；
  - (3)说明该过程中哪些时间段为拥塞避免阶段?
    - 答：4~10、11~16、20~25；
  - (4)第10个RTT时，发生了什么事件?拥塞窗口及其阈值大小如何变化?
    - 答：发送端收到了 3 个重复的 ACK；拥塞窗口阈值设置为当前拥塞窗口的一半，即 11MSS，拥塞窗口大小由 22 MSS 变成 11MSS；
  - (5)第16个RTT时，发生了什么事件?拥塞窗口及其阈值大小如何变化? 
    - 答：发送端计时器超时；拥塞窗口阈值设置为当前拥塞窗口的一半，即 8MSS；拥塞窗口大小设置为 1MSS；

- 44．(12分)设网络拓扑如题44图所示。请利用Dijkstra最短路径算法计算节点X到网络中所有节点的最短路径，正确填写题44表中序号(1)一(12)的内容在答题卡上。
    注：如果某个节点在选择下一跳节点时，有多个节点的最短路径相同，则选择节点编号小的节点作为下一跳节点。例如，如果节点X到节点Y和节点Z的路径代价相同，而且都是X到所有下一跳节点中的最短路径，则选择Y为X的下一跳节点。
    - w
    - 6
    - w
    - 5
    - w
    - 3
    - w
    - 2
    - w
    - 3
    - w
    - 7