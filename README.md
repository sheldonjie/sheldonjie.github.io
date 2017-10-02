## Welcome to My Blog Pages

### **1、Computer Network**
**1.1 Division Of Computer Networks:**

![division](https://github.com/sheldonjie/picture.github.io/blob/master/division.png?raw=true)

**1.2 Define Of Network**

|Elements|Define|
|:----|:----|
|节点(node)|计算机、交换机、路由器等构成网络的硬件|
|链路(link)|泛指将各个节点进行连接的逻辑链路，物理上可使用有线线缆或无线电波|
|主机(host)|通过网络为其他机器提供服务的计算机，或称服务器|
|客户端(client)|指从主机处获得服务的计算机，或称终端|

### **2、OSI Reference Model(开放系统互连参考模型)**

> 参考模型：是指该模型不是必须执行的标准，而是按照该模型的要求，不同企业生产的网络设备可以互相连接。

**2.1 通常将网络功能分配到不同层实现：**

- 高层使用底层的服务
- 层与层之间相对独立
- 通过SAP进行数据交换

![OSI](https://github.com/sheldonjie/picture.github.io/blob/master/OSI.png?raw=true)



> **流量控制：**即通信双方速度存在差异，需要协调匹配通信正常。<br />

> **差错控制：**即在数据传输过程中，如何发现错误，如何更正错误。

### **3、OSI参考模型对应的数据形式与网络协议范例** ###

|Layer|Data Form|Network Protocol|
|:----:|:----:|:----:|
|物理层|比特|IEEE802.3、FDDI、NRZ等|
|数据链路层|帧|IEEE802.2、帧中继、ATM、PPP、HDLC等|
|网络层|分组、数据报|IP、IPX、X.25等|
|传输层|段、消息|TCP、UDP等|
|会话层|应用数据|SSL等|
|表示层|应用数据|ASCII编码等|
|应用层|应用数据|HTTP、FTP、SMTP、SNMP等|

### **4、TCP/IP Model** ###

|Layer|Address|Network Hardware|
|:----:|:----:|:----:|
|数据链路层|MAC地址|L2交换机、无线LAN接入点|
|网络层|IP地址|路由器、L3交换机|
|传输层|端口号(TCP端口、UDP端口)|L4交换机、防火墙|
|应用层|根据应用程序的不同而不同|L7交换机、防火墙、代理|

### **5、LAN/MAN/WAN** ###

|Name|Full Name|Define|
|:----:|:----:|:----:|
|LAN|Local Area Network|用于机构内部通信与信息传递，常使用以太网技术在公司或校园等局部的地理范围内构建|
|MAN|Metropolitan Area Network|使用光缆在相距较远的校园或城市内建立通信网络，比LAN的范围更广|
|WAN|Wide Area Network|用于跨地区或国家远程通信，范围最广，一般由电信运营商建设|

### **6、Network Interconnection Equipment(网络互联设备)** ###

|Layer|Equipment|
|:----:|:----:|
|物理层|转发器(repeater)|
|数据链路层|网桥(bridge)或交换机(switch)|
|网络层|路由器(router)|
|传输层及以上|网关(gateway)|
