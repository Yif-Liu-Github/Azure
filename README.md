# Azure
Azure学习


## 云计算
云计算会租用其他公司计算机上的存储空间或 CPU 周期等资源。 只需为所用的部分付费。 提供这些服务的公司称为云提供商。 某些提供商包括 Microsoft、Amazon 和 Google。  
云提供商负责提供执行工作所需的物理硬件，并使其保持最新。 提供的计算服务往往因云提供商而异。 但是，它们通常包括：  
+ 计算能力 - 例如，Linux 服务器或 Web 应用程序  
+ 存储 - 例如，文件和数据库  
+ 网络 - 例如，云提供商和公司之间的安全连接  
+ 分析例如，可视化遥测和性能数据  

### 云计算服务
云计算的目标是使企业开展业务更轻松、更高效，无论是小型初创企业还是大型企业。 每项业务都是独特的，有不同的需求。 为满足这些需求，云计算提供商提供广泛的服务。  
需要对其提供的一些服务有基本了解。 我们简要讨论所有云提供商都提供的两种最常见服务：– 计算能力_和_存储。  
#### 计算能力
发送一封电子邮件、在 Internet 上进行预订、在线付款、或甚至使用此 Microsoft Learn 模块时，你都在与处理每个请求并返回响应的基于云的服务器进行交互。 作为消费者，我们都依赖于组成 Internet 的各种云提供商提供的计算服务。  
使用云计算生成解决方案时，可以根据自己的资源和需求选择工作的完成方式。 例如，如果希望对维护拥有更多控制权并承担更多责任，则可以创建虚拟机 (VM)。 VM 是仿真计算机，与你正在使用的台式机或笔记本电脑相似。 每个 VM 都包括操作系统和硬件，在用户看来就像运行 Windows 或 Linux 的物理计算机一样。 然后，你可以安装任何所需的软件来执行要在云中运行的任务。  
不同之处在于，你无需购买任何硬件或安装 OS。 云提供商在其中一个数据中心的物理服务器上运行虚拟机，通常与其他 VM 共享该服务器（独立且安全）。 借助云，你能够以比物理计算机更低的成本在数分钟内准备好 VM。  
VM 不是唯一的计算选择，还有两个其他常用选项：容器和无服务器计算。  
#### 什么是容器？
容器为应用程序提供一致、独立的执行环境。 它们类似于 VM，但它们不需要来宾操作系统。 相反，应用程序及其所有依赖项都打包到“容器”中，然后使用标准运行时环境来执行应用。 这样，容器可以在数秒钟内启动，因为没有要启动和初始化的 OS。 只需启动应用。  
开放源代码项目 Docker 是用于管理容器的领先平台之一。 Docker 容器为应用程序部署提供了一种高效、轻量级的方法，因为通过它们可将应用程序的不同组件独立部署到不同的容器中。 多个容器可以在一台计算机上运行，并且容器可以在计算机之间移动。 由于容器的可移植性，可以非常轻松地将应用程序部署到多个环境（无论是在本地还是在云中），通常无需对应用程序进行任何更改。  
#### 什么是无服务器计算？
借助无服务器计算，无需创建、配置或维护服务器即可运行应用程序代码。 核心理念是将应用程序分为单独的函数，这些函数会在由某些操作触发时运行。 这是自动化任务的理想之选。例如，你可以构建无服务器进程，在客户进行在线购买后自动发送电子邮件确认。  
无服务器模型与 VM 和容器的不同之处在于，你只需为每个函数在执行时使用的处理时间付费。 VM 和容器运行时，即使其上的应用程序处于空闲状态，也会收取相应的费用。 此体系结构并不适用于每个应用 - 但是当应用逻辑可以分离到独立的单元时，可以单独对其进行测试和更新，并在数微秒内启动它们，从而使这种方法成为部署的最快选择。  
以下是比较我们介绍的三种计算方法的关系图。  
![三种云计算方法](https://docs.microsoft.com/zh-cn/learn/modules/principles-cloud-computing/media/2-vm-vs-container-vs-serverless.png)  
#### 存储
大多数设备和应用程序都会读取和/或写入数据。 下面是一些示例：
+ 在线购买电影票
+ 查询在线商品的价格
+ 拍摄照片
+ 发送电子邮件
+ 留语音邮件  

在以上所有案例中，不是读取数据（查询价格）就是写入数据（拍摄照片）。 在每种情况下，数据类型及其存储方式可能不同。  
云提供商通常会提供可处理所有这些类型的数据的服务。 例如，如果要存储文本或影片剪辑，则可以使用磁盘上的文件。 如果有一组关系（例如地址簿），可以采取一种更结构化的方法，比如使用数据库。  
使用基于云的数据存储的优点是可以缩放以满足需求。 如果发现需要更多空间来存储影片剪辑，则可以支付更多费用并增加可用空间。 在某些情况下，存储甚至可以自动进行扩展和缩放，因此你可以在任何给定的时间点为所需的内容付费。  
#### 总结
每项业务有不同的需求和要求。 云计算灵活且经济高效，不论是小型还是大型企业，均可由此受益。  

### 云计算的优势

云计算是一种灵活的服务方法。 公司可以选择使用云来存储数据和执行逻辑（大规模使用云计算），也可以使用尽可能少的云计算来满足业务需求。 现有企业可能选择逐渐过渡的方式以节省基础结构费用和管理费用（称为“提升和转移”），而新企业可以从一开始就采用云。  
我们来了解云计算的一些主要优势。  
#### 经济高效
云计算提供即用即付或基于使用定价模型。  
此基于使用的模型有许多好处，其中包括：
+ 无前期成本
+ 无需购买和管理你可能不会充分利用的成本高昂的基础结构
+ 能够仅在需要时为额外资源付费
+ 能够停止为不再需要的资源付费

这也有助于更好地预测成本。 提供了各资源和服务的价格，因此你可以根据预期使用情况预测在给定结算周期内的支出。 还可以使用云提供商跟踪的历史使用情况数据，根据未来增长情况进行分析。  
#### 可缩放
可以在任何给定时间根据需求或工作负载增加或减少使用的资源和服务。 云计算同时支持垂直扩展和水平扩展，具体视需求而定。  
垂直扩展（亦称为“纵向扩展”）是添加资源以增强现有服务器功能的过程。 垂直缩放的一些示例包括，添加更多的 CPU 或添加更多内存。  
水平扩展（亦称为“横向扩展”）是添加更多服务器作为一个单元一起工作的过程。 例如，多个服务器处理传入的请求。  
可以根据特定的触发器（例如 CPU 利用率或请求的数量）手动或自动完成缩放，资源可在几分钟内进行分配或解除分配。  
#### 灵活弹性
当工作负载因需求激增或下降而发生变化时，云计算系统可通过自动添加或删除资源来进行补偿。  
例如，假设一篇新闻文章中特别提到你的网站，这导致了一夜之间流量激增。 由于云具有弹性，因此会自动分配更多计算资源来处理增加的流量。 当流量开始正常化时，云自动取消分配额外资源以最大程度降低成本。  
再举一个例子，如果运行员工使用的应用程序，可以让云在大多数员工访问应用程序的高峰运营时间段自动添加资源，然后在一天结束时删除资源。  
#### 它是最新的  
使用云时，可以专注于真正重要的方面，即生成和部署应用程序。 云消除了维护软件修补程序、硬件设置、升级和其他 IT 管理任务的负担。 所有这些都是自动完成的，确保你使用最新、最好的工具来经营企业。  
此外，计算机硬件由云提供商进行维护和升级。 例如，如果磁盘发生故障，云提供商将更换磁盘。 如果新硬件更新不可用，无需更换硬件。 云提供商将确保为你自动提供硬件更新。  
#### 可靠
在经营一家企业时，你希望确保数据始终可用。 云计算提供商提供了数据备份、灾难恢复和数据复制服务，可确保数据始终安全。 此外，冗余通常内置于云服务体系结构中，因此，如果一个组件发生故障，备份组件会取而代之。 这称为容错，可确保发生灾难时，客户不会受到影响。  
#### 它是全球性的
云提供商拥有遍布全球各个区域的完全冗余的数据中心。 这使你可以靠近客户，无论他们身在何处，都能为他们提供最佳的响应时间。  
可以将服务复制到多个区域以实现冗余和定位，或选择特定区域以确保帮助客户满足数据驻留和合规性法规。  
#### 安全
想想你如何保护自己的数据中心。 你设置了物理安全性 – 谁可以进入大楼、谁可以操作服务器机架，等等。 你还设置了数字安全性 – 谁可以通过网络连接到系统和数据。  
云服务提供商提供广泛的策略、技术、控件和专家技术技能，可以提供比大多数组织可以实现的更好的安全性。 其结果是增强了安全性，这有助于保护数据、应用和基础结构免受潜在威胁。  
至于物理安全性 – 对云基础结构的威胁，云提供商大力投资于围墙、摄像机、大门、安全人员等，以便保护物理资产。 他们还制定了严格的规程，确保员工只能访问那些有权管理的资源。  
现在来讨论数字安全性。 你只允许经授权的用户登录在云中运行的虚拟机或存储系统。 云提供商提供用于缓解安全威胁的工具，你必须使用这些工具来保护所用资源。  
#### 总结
云计算让经营企业变得更加轻松。 云计算经济高效、可缩放、具有弹性、始终保持最新状态、可靠且安全。 这意味着你可以将更多时间花在重要事项上，而只需较少时间来管理基础细节。

### 云部署模型
有三种不同的云部署模型。 云部署模型定义了数据的存储位置以及客户与之交互的方式 - 用户如何访问数据以及应用程序在何处运行？ 这还取决于你想要或需要管理的基础结构的数量。  
#### 公有云
这是最常见的部署模型。 在此情况下，没有本地硬件可管理或保持最新 - 所有内容都在云提供商的硬件上运行。 在某些情况下，可通过与其他云用户共享计算资源来节省额外成本。  
企业可以使用不同规模的多个公有云提供商。 Microsoft Azure 就是一个公有云提供商。  
优点  
+ 高可伸缩性/敏捷性 - 无需购买新的服务器即可缩放
+ 即用即付定价 - 只需为使用的资源付费，无需支付 CapEx 费用
+ 你不负责维护或更新硬件
+ 设置和使用所需的技术知识非常少 - 可以利用云提供商的技能和专业知识来确保工作负荷的安全性和高可用性
常见用例场景是在云提供商拥有的硬件和资源上部署 Web 应用或博客站点。 通过在此方案中使用公有云，云用户可以快速创建网站或博客，然后专注于维护网站，而无需担心购买、管理或维护其运行的硬件的问题。 
 
缺点  
公有云并不适合所有方案。 下面是一些需要注意的缺点：  
+ 使用公有云可能无法满足特定的安全要求
+ 公有云可能无法满足政府政策、行业标准或法律要求
+ 你不拥有硬件或服务，也无法按照你的意愿管理它们
+ 可能很难满足独特的业务需求，例如必须维护旧版应用程序

#### 私有云
在私有云中，你可以在自己的数据中心创建云环境，并为组织中的用户提供对计算资源的自助访问。 这为你的用户提供了公有云的模拟，但你仍然全权负责购买和维护所提供的硬件和软件服务。  
优点  
此方法具有几个优点：  
+ 可以确保配置可以支持任何场景或旧版应用程序
+ 你对安全性有控制能力（并承担相应责任）
+ 私有云可以满足严格的安全性、合规性或法律要求
+ 实现大规模经济性，并与 Azure 安全中心集成

缺点  
团队迁离私有云的一些原因包括：  
+ 存在初始 CapEx 成本，必须购买硬件才能启动和维护
+ 对设备的拥有会限制敏捷性 - 必须购买、安装和设置新硬件才能进行缩放
+ 私有云需要 IT 技能和专业知识，而这些技能和知识很难获得

私有云的用例场景是，组织拥有不能放在公有云中的数据（可能出于法律原因）。 一个示例场景可能是，政府政策要求将特定数据保存在国内或以私有方式保存。  
私有云也可以为外部客户或特定内部部门（例如会计或人力资源）提供云功能。  
#### 混合云
混合云结合了公有云和私有云，让你能够在最合适的位置运行应用程序。 例如，可以在公有云中托管网站，并将其链接到托管在私有云（或本地数据中心）中的高度安全的数据库。  
如果出于法律原因，某些内容无法放入云中，使用混合云就很有用。 例如，你可能拥有一些不能公开的特定数据（例如医疗数据），这些数据需要保存在私有数据中心。 另一个示例是在无法更新的旧硬件上运行的一个或多个应用程序。 在此情况下，可保持旧系统在本地运行，并将其连接到公共云以进行授权或存储。  
优点  
下面是混合云的一些优点：  
+ 可使所有系统继续运行并保持可访问性，即使所用的操作系统或硬件已过时
+ 可以灵活地在本地运行，而不是在云中运行
+ 可以利用公有云提供商提供的规模效益，获得服务和资源（如果较便宜），或对自己的现有设备进行补充（如果服务和资源不是较便宜）
+ 如果你需要完全控制环境，可以使用自己的设备来满足安全性、合规性或旧版方案要求

缺点  
需要注意的一些问题包括：  
+ 这可能比选择一个部署模型更昂贵，因为它涉及一些前期的 CapEx 成本
+ 设置和管理可能会更复杂

#### 总结
云计算非常灵活，可以选择部署它的方式。 所选的云部署模型取决于你的预算，以及安全性、可伸缩性和维护需求。

### 云服务的类型IaaS、SaaS 与 PaaS
#### 基础结构即服务 (IaaS)
基础结构即服务是最灵活的云服务类别。 它旨在完全控制运行应用程序的硬件（IT 基础结构服务器和虚拟机 (VM)、存储、网络和操作系统）。 使用 IaaS 时，你是租用硬件，而不是购买硬件。 它是即时计算基础结构，可通过 Internet 进行预配和管理。  
IaaS 通常用于以下场景：  
+ 迁移工作负载。 通常情况下，IaaS 设施的管理方式与本地基础结构类似，IaaS 设施提供了将现有应用程序迁移到云的简单迁移路径。  
+ 测试和开发。 团队可以快速设置和拆除测试和开发环境，更快地将新应用程序推向市场。 IaaS 可以通过实惠的方式快速缩放开发测试环境。  
+ 存储、备份和恢复。 组织可以避免存储管理的资本支出和复杂性，存储管理通常需要熟练的员工来管理数据，并满足法律和符合性要求。 IaaS 对于管理无法预测的需求和稳定增长的存储需求非常有用。 IaaS 还可以简化备份和恢复系统的规划和管理过程。  

#### 平台即服务 (PaaS)
PaaS 为生成、测试和部署软件应用程序提供一个环境。 PaaS 旨在帮助快速创建应用程序，而无需管理底层基础结构。 例如，使用 PaaS 部署 Web 应用程序时，无需安装操作系统、Web 服务器甚或系统更新。  
PaaS 是云中的完整开发和部署环境，其资源使组织能够提供从简单的基于云的应用到复杂的支持云的企业应用程序的所有内容。 资源是按照“即用即付”的方式从云服务提供商处购买的，并通过安全的 Internet 连接进行访问。  
PaaS 通常用于以下场景：  
+ 开发框架。 PaaS 提供了一种框架，开发人员可以基于该框架进行构建，从而开发或自定义基于云的应用程序。 就像 Microsoft Excel 宏一样，PaaS 使开发人员能够使用内置软件组件创建应用程序。 包含可扩展性、高可用性和多租户功能等在内的云功能减少了开发人员的代码编写工作量。
+ Analytics 或商业智能。 借助作为 PaaS 服务提供的工具，组织可以分析和挖掘其数据。 他们可以查找见解和模式并预测结果，以改进预测、产品设计和投资回报等业务决策。

#### 服务型软件 (SaaS)
SaaS 是面向最终客户的集中托管和管理软件。 它通常基于这样的架构，其中同一版本的应用程序用于所有客户，并通过月度或年度订阅获得许可。 Office 365、Skype 和 Dynamics CRM Online 是 SaaS 软件的绝佳示例。
##### 成本和所有权
 -| IaaS | PaaS | SaaS
--|:--|:--|:--
前期成本 | 无前期成本。 用户只需为其使用的内容付费。 | 无前期成本。 用户只需为其使用的内容付费。 | 用户无前期成本；他们通常按月度或年度支付订阅费用。
用户所有权 | 用户负责购买、安装、配置和管理自己的软件、操作系统、中间件以及应用程序。 | 用户负责开发自己的应用程序。 但是，他们不负责管理服务器或基础结构。 这样，用户可以专注于要运行的应用程序或工作负荷。 | 用户只使用应用程序软件；他们不对该软件的任何维护或管理工作负责。
云服务提供商所有权 | 云服务提供商负责确保用户可以使用基础云基础结构（如虚拟机、存储和网络）。 | 云服务提供商对操作系统管理、网络和服务配置负责。 云服务提供商通常负责除用户想要运行的应用程序之外的所有内容。 他们提供了可运行应用程序的完整托管平台。 | 云服务提供商对应用程序软件的预配、管理和维护负责。
##### 管理职责
要了解的是，这些类别是彼此重叠的层。 例如，PaaS 通过提供一定级别的抽象在 IaaS 之上添加一层。 抽象的好处在于隐藏了你可能不关心的细节，便于你更快地编写代码。 但抽象的某一方面弱化了你对基础硬件的控制。 下图显示一个列表，其中列出了你和你的服务提供商在每个云服务类别中管理的资源。
![管理职责]（https://docs.microsoft.com/zh-cn/learn/modules/principles-cloud-computing/media/5-layer-diagram.png）
