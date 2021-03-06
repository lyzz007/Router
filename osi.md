# 开放式系统互联- [开放式系统互联](#开放式系统互联)
  - [介绍](#介绍)
    - [物理层（第一层）](#物理层第一层)
    - [数据链路层](#数据链路层)
    - [网络层](#网络层)
    - [传输层- 开放式系统互联](#传输层--开放式系统互联)
    - [会话层](#会话层)
    - [表示层](#表示层)
    - [应用层](#应用层)
  - [层次划分](#层次划分)
    - [第7层 应用层](#第7层-应用层)
    - [第6层 表达层](#第6层-表达层)
    - [第5层 会话层](#第5层-会话层)
    - [第4层 传输层](#第4层-传输层)
    - [第3层 网络层](#第3层-网络层)
    - [第2层 数据链路层](#第2层-数据链路层)
    - [第1层 物理层](#第1层-物理层)

## 介绍- [开放式系统互联- 开放式系统互联](#开放式系统互联--开放式系统互联)

### 物理层（第一层）

- 将数据转换为可通过物理介质传送的电子信号 相当于邮局中的搬运工人。
  
### 数据链路层

- 决定访问网络介质的方式。
  
- 在此层将数据分帧，并处理流控制。本层指定拓扑结构并提供硬件寻址，相当于邮局中的装拆箱工人。
  
### 网络层

- 使用权数据路由经过大型网络 相当于邮局中的排序工人

### 传输层- [开放式系统互联](#开放式系统互联)

- 提供终端到终端的可靠连接 相当于公司中跑邮局的送信职员。

### 会话层

- 允许用户使用简单易记的名称建立连接 相当于公司中收寄信、写信封与拆信封的秘书。

### 表示层

- 协商数据交换格式 相当公司中简报老板、替老板写信的助理。
  
### 应用层

- 用户的应用程序和网络之间的接口。
  
## 层次划分

### 第7层 应用层

  主条目：应用层

- 应用层（Application Layer）提供为应用软件而设的接口，以设置与另一应用软件之间的通信。例如: HTTP，HTTPS，FTP，TELNET，SSH，SMTP，POP3等

### 第6层 表达层

  主条目：表达层

- 表达层（Presentation Layer）把数据转换为能与接收者的系统格式兼容并适合传输的格式。
  
### 第5层 会话层

  主条目：会话层

- 会话层（Session Layer）负责在数据传输中设置和维护计算机网络中两台计算机之间的通信连接。

### 第4层 传输层

  主条目：传输层

- 传输层（Transport Layer）把传输表头（TH）加至数据以形成数据包。传输表头包含了所使用的协议等发送信息。例如:传输控制协议（TCP）等。
  
### 第3层 网络层

  主条目：网络层

- 网络层（Network Layer）决定数据的路径选择和转寄，将网络表头（NH）加至数据包，以形成分组。网络表头包含了网络数据。例如:互联网协议（IP）等。

### 第2层 数据链路层

  主条目：数据链路层

- 数据链路层（Data Link Layer）负责网络寻址、错误侦测和改错。当表头和表尾被加至数据包时，会形成帧。数据链表头（DLH）是包含了物理地址和错误
侦测及改错的方法。数据链表尾（DLT）是一串指示数据包末端的字符串。例如以太网、无线局域网（Wi-Fi）和通用分组无线服务（GPRS）等。  

- 分为两个子层：逻辑链路控制（logic link control，LLC）子层和介质访问控制（media access control，MAC）子层。
  
### 第1层 物理层

  主条目：主条目：物理层

- 物理层（Physical Layer）在局部局域网上传送数据帧（data frame），它负责管理计算机通信设备和网络媒体之间的互通。
包括了针脚、电压、线缆规范、集线器、中继器、网卡、主机适配器等。

