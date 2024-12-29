## 一些信息
* **Dijkstra算法、动态规划算法那前后一整块**都是期末重点
* 期末题型：
    * 20道选择题，共40分
    * 5道判断题，共10分
    * 5道综合大题
        * 其中2道简答题（概念题，实在不会用英文表述可以用一点点中文），e.g.解释一下ARP是干什么的
        * 3道计算题
        * **链路层、网络层和运输层，一层一道大题**
    * 没有附加题，难度应该没有作业高
    * 可以带计算器
* 重点中的重点：**HTTP、DNS、UDP、TCP、**
* 有时间就考前看一下（可能不是重点）：
    * TCP的公平性
    * BGP的路径广播、传播策略（政策）、热土豆路由
    * SDN网络框架（第五章ppt最后）
    * Slotted ALOHA和pure ALOHA
    * “Taking turns” MAC protocols和Cable access network
    * **将所有层和所有协议串起来、总结思维导图**（第六章ppt最后）（**重点，用来加深理解和记忆**）
* 第一章：分层、delay、各种交换、协议等
* 第二章：TCP、UDP、HTTP、DNS，**P2P公式不用专门看**
    * **第二章没有什么计算题，应该会有一些问答题**，就是基础的原理、概念、简答
* 第三章：socket、多路复用、SNMP不用管、checksum计算也不考、rdt主要理解原理和几个问题，具体非常细节的不会抠比如状态转移之类的、GBN和具体的算法、**TCP，注意报文结构中的RSF，ACK和sequence number对应的关系，connection management，三次握手的过程的SYN和ACK（两次的问题不用管）**、拥塞控制慢启动的算法、QUIC不用管、UDP
* 第四章：**longest prefix matching一定要掌握**、IP addressing、子网（比如两个地址之间通信需不需要路由器）、特殊IP地址、专用地址不用专门记范围、**路由转发算法一定要会，比如怎么根据转发表看下一跳，下一跳之后怎么处理，怎么计算等**、DHCP、**NAT是关键，一定要好好理解、如果服务器在里面，内网怎么往外网通信（需要有一个服务器来进行帮助，从内网发起，不能从外网发起，把外网IP地址告诉内网，叫做NAT的穿透）**、tunneling和encapsulation理解一下就行、转发知道基本原理、OpenFlow的flow table有哪些项（field）和基本原理，不需要掌握它的计算
* 第五章（是重点）：SDN、数据平面和控制平面、**Dijkstra最短路径算法一定要掌握**、distance vector algorithm（动态规划算法，Bellman-Ford，BF）算法的基本原理和计算方法、**count-to-infinity problem（上课讲的，翻聊天记录）一定要好好看**、域内和域间路由协议可能会考简答题、路径向量协议、BGP、ICMP、每一章每一层的service都要搞清楚
* 第六章（是重点）：**CRC一定要会算（也是之前上课讲的，翻聊天记录）、CSMA这些的基本原理和算法一定要搞清楚、binary backoff也一定要好好看**、mac address（和IP address的区别之类的）、**ARP和跨网络的ARP怎么进行计算一定要搞清楚，ARP和IP相结合怎么进行通信**、topology、以太网、**switch交换机的自学习算法一定要搞清楚**、VLAN知道概念就行、RTS和CTS、MPLS掌握基础原理，转发计算不用掌握

## 知识框架
### 关键词缩写解释
![alt text](image-12.png)

![alt text](image-6.png)

![alt text](image-7.png)

![alt text](image-22.png)
![alt text](image-23.png)

![alt text](image-58.png)

![alt text](image-31.png)

![alt text](image-41.png)

![alt text](image-52.png)

![alt text](image-56.png)

![alt text](image-59.png)

p2p

![alt text](image-73.png)

![alt text](image-72.png)

![alt text](image-26.png)

![alt text](image-30.png)

![alt text](image-78.png)

![alt text](image-79.png)

ACK：acknowledgement

NACK：not acknowledgement

![alt text](image-99.png)

![alt text](image-111.png)

![alt text](image-115.png)

![alt text](image-119.png)

![alt text](image-38.png)

![alt text](image-105.png)

![alt text](image-120.png)

![alt text](image-48.png)

![alt text](image-134.png)

![alt text](image-135.png)

![alt text](image-136.png)

![alt text](image-139.png)

![alt text](image-145.png)

![alt text](image-126.png)

OpenFlow

![alt text](image-166.png)

![alt text](image-165.png)

![alt text](image-169.png)

eBGP：external BGP

iBGP：internal BGP

![alt text](image-161.png)

TTL：Time To Live

![alt text](image-205.png)

![alt text](image-182.png)

MAC 地址（Media Access Control Address）
![alt text](image-184.png)

![alt text](image-186.png)

![alt text](image-187.png)

ALOHA

![alt text](image-189.png)

![alt text](image-190.png)

![alt text](image-191.png)

![alt text](image-210.png)

![alt text](image-219.png)

![alt text](image-206.png)

![alt text](image-218.png)

![alt text](image-222.png)

### FAQ
![alt text](image-1.png)

![alt text](image-13.png)

![alt text](image-14.png)
![alt text](image-15.png)

![alt text](image-43.png)
![alt text](image-44.png)

![alt text](image-47.png)

![alt text](image-62.png)

![alt text](image-75.png)

![alt text](image-85.png)

![alt text](image-92.png)

![alt text](image-113.png)

![alt text](image-125.png)

![alt text](image-131.png)

![alt text](image-142.png)

![alt text](image-143.png)

![alt text](image-144.png)

![alt text](image-149.png)

![alt text](image-151.png)

![alt text](image-162.png)
![alt text](image-163.png)

![alt text](image-164.png)

![alt text](image-175.png)

![alt text](image-177.png)

![alt text](image-201.png)

![alt text](image-200.png)

![alt text](image-207.png)

![alt text](image-214.png)

![alt text](image-215.png)

![alt text](image-221.png)

### 重要知识点

![alt text](image-2.png)

![alt text](image-3.png)

![alt text](image-4.png)

![alt text](image-5.png)

![alt text](image-8.png)

![alt text](image-9.png)

![alt text](image-10.png)

![alt text](image-16.png)

![alt text](image-17.png)

![alt text](image-18.png)
![alt text](image-19.png)
![alt text](image-20.png)
![alt text](image-21.png)

![alt text](image-28.png)

![alt text](image-29.png)

![alt text](image-216.png)

### 应用层
![alt text](image-24.png)

![alt text](image-25.png)

![alt text](image-27.png)

![alt text](image-32.png)
![alt text](image-33.png)
![alt text](image-34.png)
![alt text](image-37.png)
![alt text](image-36.png)

![alt text](image-39.png)
![alt text](image-40.png)

![alt text](image-42.png)

![alt text](image-45.png)
![alt text](image-46.png)

![alt text](image-49.png)
![alt text](image-50.png)

![alt text](image-51.png)

![alt text](image-53.png)

![alt text](image-54.png)

![alt text](image-55.png)

![alt text](image-57.png)

![alt text](image-60.png)

![alt text](image-61.png)

![alt text](image-63.png)

![alt text](image-64.png)

![alt text](image-65.png)

![alt text](image-66.png)

![alt text](image-67.png)

![alt text](image-68.png)

![alt text](image-69.png)

![alt text](image-70.png)

![alt text](image-71.png)
![alt text](image-74.png)

#### 应用层框架
![alt text](image-76.png)
![alt text](image-77.png)

### 运输层
![alt text](image-80.png)

![alt text](image-81.png)

![alt text](image-82.png)

![alt text](image-83.png)

![alt text](image-84.png)

![alt text](image-86.png)

![alt text](image-87.png)

![alt text](image-88.png)

![alt text](image-89.png)

![alt text](image-90.png)

![alt text](image-91.png)

![alt text](image-93.png)

![alt text](image-94.png)

![alt text](image-95.png)

![alt text](image-96.png)

![alt text](image-97.png)

![alt text](image-98.png)

![alt text](image-100.png)

![alt text](image-101.png)

![alt text](image-102.png)

![alt text](image-103.png)
![alt text](image-104.png)

![alt text](image-106.png)
![alt text](image-107.png)

![alt text](image-108.png)

![alt text](image-109.png)

![alt text](image-110.png)

![alt text](image-112.png)

![alt text](image-114.png)

![alt text](image-116.png)

![alt text](image-117.png)

![alt text](image-118.png)

![alt text](image-121.png)

![alt text](image-122.png)

![alt text](image-123.png)

![alt text](image-124.png)

### 网络层：数据平面
![alt text](image-127.png)

![alt text](image-128.png)

![alt text](image-129.png)

![alt text](image-130.png)

![alt text](image-132.png)

![alt text](image-133.png)

![alt text](image-137.png)
![alt text](image-138.png)

![alt text](image-140.png)

![alt text](image-141.png)

![alt text](image-146.png)

![alt text](image-147.png)

![alt text](image-148.png)

![alt text](image-150.png)

### 网络层：控制平面
![alt text](image-152.png)
![alt text](image-153.png)
![alt text](image-154.png)
![alt text](image-155.png)
![alt text](image-156.png)

![alt text](image-157.png)
![alt text](image-158.png)
![alt text](image-159.png)

![alt text](image-160.png)

![alt text](image-167.png)

![alt text](image-168.png)

![alt text](image-170.png)

![alt text](image-171.png)

![alt text](image-172.png)

![alt text](image-173.png)

![alt text](image-174.png)

### 链路层
![alt text](image-176.png)
![alt text](image-178.png)

![alt text](image-179.png)

![alt text](image-180.png)
![alt text](image-181.png)

![alt text](image-183.png)

![alt text](image-185.png)

![alt text](image-188.png)

![alt text](image-192.png)

![alt text](image-193.png)

![alt text](image-194.png)

![alt text](image-195.png)

![alt text](image-196.png)

![alt text](image-197.png)
![alt text](image-198.png)
![alt text](image-199.png)

![alt text](image-202.png)
![alt text](image-203.png)

![alt text](image-204.png)

![alt text](image-209.png)

![alt text](image-211.png)

![alt text](image-212.png)

![alt text](image-213.png)

![alt text](image-217.png)

![alt text](image-220.png)

![alt text](image-223.png)

![alt text](image-224.png)

![alt text](image-225.png)

![alt text](image-226.png)
![alt text](image-227.png)
![alt text](image-228.png)