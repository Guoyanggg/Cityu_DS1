# Question

## CH01

### 云计算的定义是什么？

​	云计算是各种虚拟化、效用计算、服务计算、网格计算、自动计算等概念的混合演进的
结果。它从主机计算开始、历经小型机计算、客户机/服务器计算、分布式计算、网格计算、
效用计算进化而来，它既是技术上的突破，也是商业模式上的飞跃

### 云计算的公共特征有哪几个？

 - 弹性伸缩
 - 快速部署
 - 资源抽象
 - 按用量收费
 - 宽带访问

### 云计算按照部署方式和服务类型分别分成哪几类？

 	1. 按部署分类
     - 公共云
     - 私有云
     - 社区云
     - 混合云
     - 行业云
     - 其他云
 	2. 按服务类型分类
     - IasS 基础设施即服务
     - PasS 平台即服务
     - SasS 软件即服务

### 如何从三元认识论的角度理解云计算？

- 商业模式
- 计算范式
- 实现方式

### 云计算作为一种计算范式可以分成哪两种结构？

- 横向云体逻辑结构
- 纵向云栈逻辑结构

### 开源软件、自由软件和免费软件的区别与联系是什么？

- 免费软件就是免费提供给用户使用的软件

- 自由软件是一项思想运动，强调用户拥有如何使用软件的自由。可以自由地运行；可以自由地拷贝；

  可以自由地修改；可以自由地再发行

- 开源软件是指在软件发行的时候，附上软件的源代码，并授权允许用户更改/自由再散布/衍生著作，开源并不抵制商业收费

​	开源软件既继承了自由软件所提倡的知识共享的理念，同时又允许人们以专利的形式从知识产品中谋取利益，从而保护了人们生产、创造知识产品的积极性

### 计算系统是如何演变成今天的云计算的？

​	云计算与并行计算、分布式计算和网格计算有关系，是虚拟化、效用计算、SaaS、SOA 等技术混合演进的结果

### 如何理解“开源是种方法论”？

​	开源软件依托同行评审和社区生产，皆以分散、协作的方式开发。开源软件由社区开发，而非单个作者或公司，因此通常成本更低、更灵活，寿命比专有软件更长。

​	开源已成为一种超越软件生产界限的运动和工作方式。开源运动旨在利用开源软件的价值和分散的生产模型，为其社区和行业的问题寻找新的解决方法。

- **同行评审：**由于源代码可自由访问，而且开源社区非常活跃，因此同行程序员会积极检查和改进开源代码。它就如同充满活力和生机的代码，而不是固步自封、停滞不前。
- **透明性：**想要准确了解哪些类型的数据移动到哪里，或代码中发生了哪些类型的变化？开源允许您自行检查和跟踪，不必依赖供应商承诺。
- **可靠性：**专有代码只靠单个作者或控制该代码的公司来更新、修复和保持正常工作。开源代码的存在时间可以超越其原作者，因为活跃的开源社区会不断进行更新。开放标准和同行评审可以确保开源代码经常得到适当的测试。
- **灵活性：**由于开源代码注重修改，因此您可以使用它来解决您的业务或社区面临的独特问题。您不再只能用一种特定方式使用代码，您可以依托社区帮助和同行评审帮助您实施新解决方案。
- **更低成本：**因为开源，所以代码本身是免费的，当您使用红帽等公司时，您只用为支持、安全强化和管理互操作性帮助等服务买单。
- **无供应商锁定：**赋予用户自由，意味着您可以随时随地使用开源代码，用于任何目的。
- **开放式协作：**活跃的开源社区，让您不再囿于方寸天地，而是能获得超越兴趣小组或者一个公司的帮助、资源和观点。

### 开源技术是如何促进云计算发展的？

​	开源云计算带来的好处很多，其中最吸引人的就是可以帮助企业降低成本。另外，开源模式消除了供应商的限制和壁垒，并且可让技术变得更加协作，合作者会不断更新开源软件，使该技术得到持续的完善和发展

​	面对庞大的业务、海量的数据都在不断的增长，几乎没有任何一家传统的商业方案能够独立解决这些业务。企业内部的“合作”已经成为局限，要想应对这些，需要更多的力量，这无疑给开源模式带来了新的机遇和挑战。开源浪潮之所以风生水起，是因为成本低、灵活性强，又有受过培训的人员，帮助使业更好地挖掘隐藏在大数据当中的价值

​	另外，开源的开放所带来的一大弊端就是安全问题。也正是出于对这种风险的考虑，目前有很多大数据项目都没有放在云环境中运行

## CH02

### 分布式计算的定义和特征是什么？

#### 	定义

​		分布式计算就是在两个或多个软件互相共享信息，这些 软件既可以在同一台计算机上运行，也可以在通过网	络连接起来的多台计算机上运行

​		集中式计算完全依赖于一台大型的中心计算机的处理能力， 这台中心计算机称为主机，与中心计算机相连的	终端设备具有各不相同非常低的计算能力。实际上大多数终端完全不具有处理能力，仅作为输入输出设备使用

#### 	特征

		- 容错性
		- 高可扩展性
		- 开放性
		- 并发处理能力
		- 透明性

### 什么是ACID原则？

- 原子性（Atomicity）：指事务里的所有操作要么全部做完，要么都不做，只要有一个操作失败，整个事务就失败，需要回滚
- 一致性（Consistency）：数据库要一直处于一致的状态，事务的运行不会改变数据库原本的一致性约束
- 独立性（Isolation）：指并发的事务之间不会互相影响，如果一个事务要访问的数据正在被另外一个事务修改，只要另外 一个事务未提交，它所访问的数据就不受未提交事务的影响
- 持久性（Durability）：指一旦事务提交后，它所做的修改将会永久保存在数据库上，即使出现宕机也不会丢失

### 什么是CAP理论？

- 一致性（Consistency）：分为从客户端和服务端两个不同的视角，更新操作成功并返回客户端完成后，所有节点在同一时间的数据完全一致
- 可用性（Availability）：在正常的响应时间内，服务一直可用
- 分区容错性（Partition tolerance）：指分布式系统在遇到某节点或网络分区故障的时候，仍然能够对外提供满足一致性和可用性的服务

### 什么是BASE理论？

对CAP理论的延申

- 基本可用（Basically Available）：指分布式系统在出现故障的时候，允许损失部分可用性，即保证核心可用
- 软状态（Soft State）：指允许系统存在中间状态，而该中间状态不会影响系统整体可用性。分布式存储中一般一份数据至少会有三个副本，允许不同节点间 副本同步的延时就是软状态的体现
- 最终一致性（Eventual Consistency）：指系统中的所有数据副本经过一定时间后，最终能够达到一致的状态

### 如何理解最终一致性？

- 强一致性（即时一致性）：对于关系型数据库，要求更新过的数据能被后续的访问都能看到
- 弱一致性：能容忍后续的部分或者全部访问不到，
- 最终一致性：经过一段时间后要求能访问到更新后的数据
- 一致性散列：将整个散列值空间组织成一个虚拟的圆环，散列值是一个32位无符号整形
  - 容错性：如果一台服务器不可用， 则受影响的数据仅仅是此服务器到其环空间中前一台服务器（即沿着逆时针方向行走遇到的第一台服务器）之间的数据，其他不会受到影响
  - 扩展性：如果增加一台服务器，则受影响的数据仅仅是新服务器到其环 空间中前一台服务器（即沿着逆时针方向行走遇到的第一台服务器）之间数据，其他数据也不会受到影响
  - 虚拟节点：在服务节点太少时，容易因为节点 分布不均匀而造成数据倾斜问题

### 分布式存储与分布式计算的区别与联系是什么？

**分布式存储系统**，是将数据分散存储在多台独立的设备上。传统的网络存储系统采用集中的存储服务器存放所有数据，存储服务器成为系统性能的瓶颈，也是可靠性和安全性的焦点，不能满足大规模存储应用的需要。

**分布式计算**，是一种计算方法和集中式计算是相对的。随着计算技术的发展，有些应用需要非常巨大的计算能力才能完成，如果采用集中式计算，需要耗费相当长的时间来完成。分布式计算将该应用分解成许多小的部分，分配给多台计算机进行处理。这样可以节约整体计算时间，大大提高计算效率。

### 典型的分布式系统

- 网格系统：网格是一种能够将多组织拥有和管理的计算机、网络、数据库和科学仪器综合协同使用的基础设施
- P2P系统：网络的所有参与者共享他们所拥有的一部分硬件资源，包括处理器资源、存储资源和网络资源等，这些共享资源可以通过网络被其他对等者直接访问并为之提供服务和内容。
- 透明计算：用户无须感知计算机操作系统、中间件、应用程序和 通信网络的具体所在，只需根据自己的需求，通过网络从所使用的各种终端设备中选择并使用相应服务的计算模式
- 区块链系统：去中心化、不可篡改、可追溯、多方共同维护的分布式数据库系统，能够将传统单方维护的仅涉及自己业务的多个孤立数据库整合在一起，分布式地存储在多方共同维护的多个节点，任何一方都无法完全控制这些数据，只能按照严格的规则和共识进行更新

### 在我们的日常生活当中，为什么我们所接触到的分布式系统越来越多了？

### CAP定理中的几个关键因素为什么不能同时保证？不同的组合有什么样的应用场景？

​	假设某个时刻N1和N2之间的网络通信突然中断了。如果系统满足分区容错性，那么显然可以支持这种异常。问题是在此前提下，一致性和可用性是否可以做到不受影响呢？

​	有用户向N1发送了请求更改了数据，将数据库从V0更新成了V1。由于网络断开，所以N2数据库依然是V0，如果这个时候有一个请求发给了N2，但是N2并没有办法可以直接给出最新的结果V1，这个时候该怎么办呢？这个时候无法两种方法，一种是将错就错，将错误的V0数据返回给用户。第二种是阻塞等待，等待网络通信恢复，N2中的数据更新之后再返回给用户。显然前者牺牲了一致性，后者牺牲了可用性。

- 舍弃A，保留CP：数据一致性是最基本的要求。不满足一致性的存储显然不会有用户愿意使用（Zookeeper）
- 舍弃C，保留AP：这种是大部分的分布式系统的设计，保证高可用和分区容错，但是会牺牲一致性（淘宝）
- 舍弃P，保留CA：这种情况几乎不存在。因为分布式系统，网络分区是必然的。如果要舍弃P，那么就是要舍弃分布式系统，CAP也就无从谈起了。可以说P是分布式系统的前提，所以这种情况是不存在的

### 通过了解区块链的背景，说说你所理解的区块链做为一种分布式系统背后的全新理念

## CH03

### 云计算中的工作负载有哪几种模式？它们的特征是什么？

### 如何避免云计算资源“超配”带来的问题？

### 如何理解“云栈”和“云体”的概念？

### 什么是软件定义的数据中心？它的特点是什么？
云计算的架构是如何演化的？

### 如何理解“软件定义一切”的说法？

## CH04

### 什么是虚拟化技术？以及该技术有哪三种类型？

### 全虚拟化技术和半虚拟化技术的区别是什么？

### 硬件虚拟化技术有哪些代表？

### 什么是轻量级虚拟化技术？其代表是什么？

### 虚拟化技术对计算资源的利用率究竟带来了怎样的好处？

### 轻量级虚拟化技术相对于传统虚拟化技术的优势和不足是什么？

### 容器的轻量级虚拟技术还能进一步的轻量化吗？有些什么样的方式？