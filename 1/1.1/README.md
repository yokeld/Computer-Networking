# Internet 概览
## 网络
+ 局域网：局域网（local area network，LAN）通常是私有的，连接一个办公室、大楼或校园内的一些主机。
+ 广域网：广域网（wide area network，WAN）也是由具有通信能力的设备相互连接而形成的，具有更广的地理覆盖范围，可以覆盖一个城市、一个省、一个国家甚至整个世界。
  + 点到点广域网：点到点广域网通过传输介质（电缆或大气）连接两个同心设备。
  + 交换式广域网：交换式广域网具有多个断点，交换式广域网是交换机连接几个点到点的广域网而形成的。
+ 互联网络：当两个或多个网络连接起来，它们就形成了一个互联网络（inter network)，或者互联网（internet）。

## 交换
+ 电路交换网络：在电路交换网络（circuit switched network）中，两个端系统之间总是存在一条专用的连接（成为电路），交换机只能使其变成活跃或非活跃状态。仅当占用全部容量时，电路交换网络才具有高效率；在多数实践中，由于工作仅仅占用部分容量，因此它的效率低下（交换机具有转发功能但是没有存储能力）。
+ 分组交换网络：在一个计算机网络中，两个端点之间使用被称为分组（packet）的数据块进行通信。两台计算机之间交换的是独立的数据分组，由于分组是一个能够被存储和以后发送的独立实体，因此这种机制允许我们实施存储转发的交换功能。分组交换网络与电路交换网络效率高，但是分组可能会遇到一些延迟。

## Internet
+ 主干：主干（backbone）处于最高层次，是一些通信公司拥有的大型网络，如 Sprint、Verizon(MCI)、AT&T、NTT。主干网络通过称为对等点（peering point）的复杂交换系统进行连接。主干常常称为国际ISP。
+ 提供者网络：一些小些的提供者网络（provider network）处于第二个层次，这些网络通过付费使用主干网络服务。提供者网络连接主干网络，有时提供者网络之间也相互连接。提供者网络常常称为国家或区域ISP。
+ 客户网络（customer network）是 Internet 边缘的网络，它们使用 Internet 提供的服务。为了接收服务，客户网络需要要提供者网络付费。

## 访问 Internet
+ 使用电话网络
  + 拨号服务：在电话线路中增加将数据转换为语音的调试解码器，安装在计算机中的软件拨打 ISP 的号码，形成一条电话连接。拨号服务非常慢，同时当线路用于 Internet 连接时，线路就不能进行电话（语音）连接。
  + DSL 服务：DSL 服务允许语音和数据通信同时进行。
+ 利用有线电视网络
+ 采用无线网络
+ 直接连接到 Internet：大机构或大公司自身可以变成一个本地 ISP 并连入 Internet。

## 硬件和软件
+ Internet 是由连接设备将大型和小型网络连接起来形成的，但是仅仅连接这些东西是不够的，为了使通信正常进行，我们既需要硬件也需要软件。