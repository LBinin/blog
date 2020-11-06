## Wi-Fi 简介

Wi-Fi是一种可以将个人电脑、手持设备（如 PDA、手机）等终端，以无线（Wireless）的方式连接到一个无线局域网（WLAN）的技术。

Wi-Fi 全称是 Wireless Fidelity，即无线保真，是当今使用最广的一种无线网络传输技术。原本是一种无线局域网技术**商业化的品牌认证**。

第一代的 Wi-Fi 技术的标准化标号其实的 802.11，最早由 IEEE（美国电气电子工程师协会）在 1997 年所制定，主要是为了能够**让不同品牌的无线网络产品之间实现通用和兼容**，也常有人把 Wi-Fi 当做 IEEE 802.11 标准的同义术语。

## 版本迭代

### 802.11

第一代 802.11，1997 年制定，只运行于 2.4GHz 频段，最快速率为 **2Mbit/s（0.25MBps）**。

### 802.11a

### 802.11b

### 802.11g

### 802.11n

### 802.11ac

### 整理

IEEE 802 委员会成立于 1980 年 2 月，它的任务是**制定局域网和城域网标准**。

IEEE 802 中定义的服务和协议限定在 OSI 模型「OSI 网络参考模型」的最低两层（即**物理层**和**数据链路层**）。

这些版本之间的最大区别在于传输速度不断提升、信号覆盖不断扩容。

为了方便推广，一些相关的厂商又组织了一个产业联盟，在 2000 年更名为「Wi-Fi」联盟，并使用 Wi-Fi 为商标推广无线局域网技术。

第一代 802.11，1997 年制定，只运行于 2.4GHz，最快 2Mbit/s；

第二代 802.11b，只运行于 2.4GHz，最快 11Mbit/s，正逐渐淘汰；

第三代 802.11g/a，分别运行于 2.4GHz 和 5GHz，最快 54Mbit/s；

第四代 802.11n，可运行于 2.4GHz 或 5GHz，20 和 40MHz 带宽下最快 72Mbit/s 和 150Mbit/s；

第五代 802.11ac（俗称5G WiFi），只运行于 5GHz。

<details>

<summary><strong>按发布时间排序（点击展开）</strong></summary>

|   协议   | 发布时间 | 频率(Ghz) |    信号     | 最大传输速率(Mbps) | 性能演变                                                                                                                                                                                                                                                                                    |
| :------: | :------: | :-------: | :---------: | :----------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  802.11  |   1997   |    2.4    | FHSS / DSSS |         2          | 第一代无线局域网标准之一                                                                                                                                                                                                                                                                    |
| 802.11a  |   1999   |     5     |    OFDM     |         54         | IEEE802.11a 在整个覆盖范围内提供了**更高的速度，规定的频点为 5GHz**。目前该频段用得不多，干扰和信号争用情况较少。802.11a 同样采用 CSMA/CA 协议。但在物理层，802.11a 采用了正交频分复用（Orthogonal Frequency Division Multiplexing，OFDM）技术。                                            |
| 802.11b  |   1999   |    2.4    |   HR-DSSS   |         11         | 既可作为**对有线网络的补充，也可独立组网**，从而使网络用户摆脱网线的束缚，实现真正意义上的移动应用。IEEE 802.11b 的关键技术之一是采用**补偿码键控 CCK 调制技术**，可以实现动态速率转换。                                                                                                    |
| 802.11g  |   2003   |    2.4    |    OFDM     |         54         | 「使命」就是**兼顾 802.11a 和 802.11b**，为 802.11b 过渡到 802.11a 铺路修桥。802.11g 中规定的调制方式包括 802.11a 中采用的 OFDM 与 802.11b 中采用的 CCK。通过规定两种调制方式，既达到了用 2.4GHz 频段实现 IEEE 802.11a 的 **54Mbit/s** 的数据传送速度，也确保了与 IEEE 802.11b 产品的兼容。 |
| 802.11n  |   2008   | 2.4 或 5  |    OFDM     |        540         | 速率提升，理论速率最高可达 600Mbps，802.11n 可工作在 2.4GHz 和 5GHz 两个频段。                                                                                                                                                                                                              |
| 802.11ac |   2012   |     5     |    OFDM     |        600         | 802.11ac 是 802.11n 的继承者。它采用并扩展了源自 802.11n 的空中接口（air interface）概念，包括：**更宽的 RF 带宽**（提升至 160MHz），**更多的 MIMO 空间流**（spatial streams）（增加到 8），多用户的 MIMO，以及更高阶的调制（modulation）（达到 256QAM）。                                  |

</details>

## WLAN 和 Wi-Fi 的区别

## 2.4G 和 5G 的区别

在配置好新的路由器之后，可以发现有两个无线 Wi-Fi，其中一个显示有 **5G**。

我们知道普通的无线 Wi-Fi 频段是 **2.4G**，那么这个 5G Wi-Fi 和 2.4G 的分别在哪？

2.4G 主要指的是频段频率在 2.4GHz~2.485GHz 之间的无线信号；

接下来我们看看 5GHz Wi-Fi：

### 何为 5G Wi-Fi

:::tip 百度百科
严格意义上并没有叫做 5G Wi-Fi 的东西存在。笼统上称，5G Wi-Fi（802.11ac）是指**运行在 5GHz 无线电波频段**，也是第五代 Wi-Fi 技术的简称。

❗️这里有个误区，并不是运行在 5GHz 频段的 Wi-Fi 就是 5G Wi-Fi 了，运行在 5GHz 频段的 Wi-Fi 协议标准包括 802.11a（第一代）、802.11n（第四代，同时运行在 2.4GHz 和 5GHz 双频段）和 802.11ac（第五代），而只有采用 802.11ac 协议的 Wi-Fi 才是真正 5G Wi-Fi。

「更高的无线传输速度」是 5G Wi-Fi 的**最大特征**。

[5G Wi-Fi_百度百科](https://baike.baidu.com/item/5G%20Wi-Fi/7089886?fr=aladdin)
:::

### 各自的优缺点

#### 2.4GHz

**优点**：绕墙能力强

**缺点**：

- 速率相比 5GHz 要低
- 只有 3 条信道，干扰多

#### 5GHz

**优点**：

- 速率更快
- 信道多、干扰少

### 关于 5G 穿墙能力的误解

网络上很多文章都有说到「5Ghz 穿墙能力更差」，其实不然。

5GHz 信号的**波长**要比 2.4GHz 信号的要「短」，而**波长越短**的电磁波**穿透力就越强**。

但因为频率越高**消耗在穿透上的能量越大**，加上 Wi-Fi 自身的功率本来就不大，导致**信号浪费**，设备接受到的反而是**反射或衍射**过来的信号。

所以同比 2.4Ghz 下，衍射和反射比 5Ghz 要多，因此设备接受到的信号反而强。

:::tip 关于反射与衍射
对于 2.4GHz 和 5GHz 频段的电磁波来说，其主要传播方式是**直线传播**。

在直线传播中碰到障碍物时会产生**穿透、反射、衍射**等多种现象，其中穿透是主要现象，只有小部分的信号会发生反射和衍射。

然而电磁波信号在穿透障碍物时会**损失大量的能量**，有时候尚未穿透障碍物，能量就已经消耗殆尽，结果接收端收到的是通过反射和衍射而来信号，简单来说就是**绕过了障碍物的信号**。
:::

由于 5GHz 的型号波长短，穿透能力强，用在穿透上的能量更多，导致了能量的消耗和最终信号的变弱。

所以与其说「2.4GHz 信号穿墙能力比 5GHz 信号更强」，应该说「2.4GHz 信号**绕墙能力**比 5GHz 信号更强」。

## 注意点

### 速率说明

在之前只有单频的时候，比较无线路由器的速率很简单，只要看产品介绍就行了。

但进入双频时代之后情况就变了。别看产品速率动辄就是 **750Mbps**、**1200Mbps**，实际上这是 2.4GHz 网络速率和 5GHz 网络速率之和。

以 750Mbps 速率为例，一般是 300Mbps（2.4GHz）+433Mbps（5GHz）之和，用户实际使用的只是其中的一个网络，5GHz 网络最高速率也只有 433Mbps 而已，自然提升很有限。

---

另一方面类似「AC 双频，3 倍网速提升」这样的介绍，也是比较常见的宣传语，这可是很有欺骗性的。

所谓的 3 倍网速提升其实并没有错，但其指的是 802.11ac 标准中，单 MIMO（多入多出）的传输速率由 802.11n 的 **150Mbps** 提升到了 **433Mbps**。

而主流 802.11n 产品往往会采用 2 × MIMO 设计，传输速率为 **300Mbps**。如果 5GHz 网络只有 433Mbps 的话，显然提升远达不到 3 倍。

### LAN 口速率

受制于成本，一些低端的 802.11ac 无线路由器在带来「高无线速率」的同时，在**其他方面必然会有所缩水**，导致无线路由器配置不合理，最为明显的是有线 LAN 口的速率只有 **100Mbps**。

一般来说存储大文件的 PC、NAS 如果都是用网线接入局域网的话，100Mbps 的 LAN 口速率必然会成为 867Mbps 无线局域网的瓶颈，这是无线局域网速度再高也成了摆设。

而市面上 100 元 ~ 300 元价位上有不少带**百兆 LAN 口**的 **1200Mbps** 速率「双频无线路由器」，像这种就千万不能买。一方面受制于百兆 LAN 口，无线局域网高速率的优势发挥不出来，另一方面价格还不便宜，全就是鸡肋，不建议大家购买。

### 穿墙优化

部分双频无线路由器也号称是穿墙王、有穿墙模式，这主要还是**对 2.4GHz 信号有作用**。

> 其原理是采用了动态调节发射功率的技术，当无线路由器发现信号因为障碍物的阻挡而出现衰减，连接速率下降时，无线路由器就会调高发射功率以保证信号强度。

这样一来，信号虽然增强了，但是信号的容错率却下降了，会出现网页打开速度慢、在线视频卡顿等情况。简单来说就是信号看上去增强了，但依然很卡。

所以产品所谓的穿墙优化，一般是**针对 2.4GHz 信号**。

## 名词解释

### AP

### AC 双频

### 信道

### 频段、频率和带宽

在可供自由频段中，频段频率过低则带宽不足，频率太高又难以使用，因此 5GHz 就是比较好的选择。

## 参考资料

> [关于Wi-Fi必须了解的基础知识 - crazy boy - CSDN博客](https://blog.csdn.net/zouleideboke/article/details/74924588)
> 
> [WI-FI无线协议802.11a/b/g/n/ac的演变以及区别 - 自如如是 - CSDN博客](https://blog.csdn.net/Brouce__Lee/article/details/80956945)
> 
> [5G Wi-Fi_百度百科](https://baike.baidu.com/item/5G%20Wi-Fi/7089886?fr=aladdin)
> 
> [什么是5G无线Wi-Fi 5G无线Wi-Fi和2.4G Wif有什么区别【详解】-太平洋IT百科](https://product.pconline.com.cn/itbk/wlbg/network/1802/10851660.html)
> 
> [Wi-Fi 网络中，2.4GHz 和 5GHz 各自有哪些优缺点？ - 知乎](https://www.zhihu.com/question/20001576)