# AlgoLab算法教学实验室
## AlgoLab——Algorithm Teaching Auxiliary Laboratory
Author：Thomas Wang, Donghua University, Shanghai, China<br />
Author's Research: Analysis and Construction of Information System; Big Data Analysis; Commercial Artificial Intelligence<br />
<p style="line-height:10px">

## 1. 简介<br />
### 1.1	作品创意/项目背景<br />
#### 1.1.1 项目背景阐述<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;算法作为工科类专业的重要基础课程，对计算机等工科相关专业课的掌握和研究有着重要的意义。然而，由于算法的概念、思想、实现步骤等过于抽象，仅仅通过使用静态的理论知识讲解，对于要求不同掌握程度的学习用户来说很难想象出算法的动态执行过程与数据的动态变化。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;同时，老师在讲解的过程中经常因为时间关系省略算法的基础知识（如概率论、统计学等）具体的算法实现过，学生必须靠自己的理解去摸索算法的执行过程。目前，教师大多采用“幻灯片+教材”的模式来讲解算法的原理和实现过程，再结合课后布置的算法编程实验来完成算法的教学，有的老师通过动画视频配合一定的文字说明来讲解算法的动态执行过程。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;但考虑到算法教学的可视化与交互性，幻灯片或视频动画并没有有效地表现算法多样化的动态过程，导致教师无法与学生进行深入探讨，学生在抽象概念和算法思想方面的理解仍然存在困难，没有达到良好的教学效果。<br /><br />
  

#### 1.1.2 行业现状分析<br />
1.1.2.1算法相关的岗位需求现状<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;根据2019年上半年的互联网人才招聘报告，在7月中，人工智能类职位招聘数为210个，而北京、广州、上海需求量较大。在互联网公司中，今日头条、腾讯、网易对该类工程师需求量较大。其中算法工程师职位稀缺（图1），成为人工智能领域招聘需求最多的岗位！<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一方面，算法岗位供需增长显著，但求职者所获人均面邀大幅下降，算法岗位求职者增加87%。2017年，期望求职方向为算法的求职者增加了87%，一跃成为去年求职数量最多的技术岗位第三名。我们通过细分数据后发现，这部分增长人群主要来自：<br />
（1）高学历群体。算法是高学历人群的聚集地。近年来，算法岗位的硕博占比逐渐升高；<br />
（2）资深求职者。除了学历越来越高外，市场上看机会的资深候选人变多。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;另一方面，招聘算法岗公司数量增加1.2倍，但发出面邀也在增长，2018年进行算法岗位招聘的公司较2017年增长约1.2倍，一跃成为需求量最大岗位第三名，和需求公司一起增长的还有公司发出的面邀数。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;同时，但是我们也看到匹配率低带来的算法岗求职之苦。求职者所获平均面邀数显著下降。求职匹配率低是导致在供需都增长的情况下，平均面邀数显著下降的主要原因。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;我们首先需要明确一个前提：与其他技术岗位相比，算法岗有明确的门槛。算法岗位相对于其他的技术岗位而言，对于求职者提出了更高的学术背景要求。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;除了学术背景的要求之外，算法工程师的第二道门槛就是理论联系实际：应用的门槛。如果你很会推导公式，在训练模型上很有经验，但是求职者如果缺少将理论与实际业务相结合的能力，那么市场能够给的机会也不多。<br />
<br />
1.1.2.2我国高校线下算法课程培训教学现状<br />
（1）算法课程理论性强<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;首先，经过几年的教学实践和调查，大多数学生的感慨是算法非常重要，但该课程内容抽象，算法枯燥乏味，理解起来比较困难，学起来也比较累。这对学生造成不小的心理负担，影响了学生学习的求知欲，降低了学生对算法分析设计、程序设计、开发的热情。<br />
（2）课程较为抽象，“实际应用”案例少，会产生算法“用不到”和“不会用”的错觉<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;该课程理论性较强，因此对于学生来说课程较为抽象、难以理解原理的精髓。目前上机主要是对课本上的一些算法进行的验证性实现，但在却缺少实际生活或工作中的灵活应用。因此，让学生产生了该门课在今后的软件开发中是极少用甚至是用不到的错觉。进而导致学生降低对该课程的重视，以至于失去学习积极性。<br />
（3）先行课程掌握不扎实，部分学生产生“畏难情绪，止步不前”<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;本课程涉及的知识面较广。要掌握该课程，学生必须掌握一定的编程能力和具备一定的数学理论基础。而课程中的算法编程实现大都是用Python、C等语言。因此要求学生具备较高的编程基础。因而，对数学和编程课程认识和理解不但不深，而且还不会用。然而，正是此部分内容才是数据结构课程的重要基础和灵活运用的知识点，并且贯穿整个数据结构课程学习的始终。因此，这种现状必然导致许多学生在实现数据结构中的算法时不能得心应手，从而止步不前，产生畏难情绪，严重影响了学习效果和学习进度。<br />
（4）传统灌输式教学虽然可以短时灌输大量的知识，但无法进行软件行业亟需的主动性和创造性的培养<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;目前，无论是计算机专业和非计算专业的其他工科类专业，算法这门课绝大多数教师采用传统的是灌输式教学，即教师讲授、学生接受的教学方式，目的让学生在短时间内掌握大量的知识；但是对于日新月异的算法岗位，重点是对各类算法的灵活应用和创新，而不是对知识的简单记忆<br />
<br />
1.1.2.3 我国互联网线上课程算法培训教学现状<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在人工智能大数据日新月异的时代，更加尖端、细分的学习需求，让算法学习培训仍然是一片蓝海。除了以网易云课堂、腾讯课堂、MOOC（慕课）等综合性平台、淘宝大学、牛气学堂为代表的线上垂直型平台之外，虎嗅商学院、非凡学院等线下机构同样发展迅速，而人工智能算法的网络教学模式，几乎还处于课堂教学状态，缺少系统化的教学设计以及交互式的新型教学模式，并且与人工智能算法教材教辅资料充斥市场，鱼龙混杂，并不能让学员将算法的理论学习与实际应用很好的结合。人工智能算法的学习要求统计学，概率论，数量经济学等知识基础，然学习这些基础数理类课程，将这类课程的理论知识内容和实际相结合存在一定困难度，缺少应用自然无法理解算法的意义和无法将算法与业务知识结合在一起。<br /><br />
  
#### 1.1.3 项目需求分析<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;现实生活中，我们可以发现学员们关注的也不再只是基本的技能。淘宝大学的数据显示，高层次的红冠卖家、皇冠卖家，兴趣更集中在数据化运营、人群标签和人工智能领域，人才技能的需求正在进阶，所以我们项目的需求和宗旨是让用户通过我们的平台初步具备以下的能力：<br />
① 编程和理论能力<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;算法工程师的工程素养其实就是一个程序员的基本素养。这也是大部分公司招聘算法工程师的基本要求之一。<br />
② 业务理解能力<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;对于算法工程师而言，业务的理解是能够结果的充分且必要条件，能够把具体问题抽象成数学模型进行解决，然后将模型应用在产生业务上，并产生已有数据的敏感性，了解数据的业务涵义、能够把数据进行准确的应用。<br />
③ 创新能力<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;对于算法工程师的创新能力的考察背后隐含的是对其未来发展潜力的一种考察。模型应用从最初的调参，到模型优化，再到端到端解决问题，中间都需要有能够在业务基础上进行模型的创新。<br />
学员群体定位：<br />
A．对于计算机专业的学生，他们更注重底层算法的原理、步骤和实现，即偏重理论学习和算法实现；<br />
B．对于非计算机专业的其他学生，他们更注重算法的实现和实际应用，并将之运用到实际的场景和业务中；<br />
C．对于高校老师来说，他们更希望能够与学生用户进行互动、交流和学习，帮助到平台的用户。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;对于新型的人工智能算法，例如聚类算法、神经网络算法、决策树算法、支持向量机等大部分课程培训讲解得晦涩难懂，如何通过动态可视化和简单明了的教学讲解模式让用户更容易理解算法的原理和步骤是我们第一步努力的方向。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;更何况从事算法或者是数据驱动的行业，理论学习又与实际应用存在极大差距，因此第二步我们也会从实际项目入手，让学生人群不仅简单明了的学懂纯理论算法基础，而且在理论学习之外又能够快速融入到实战式业务项目学习中，从而可以更全面地掌握整个算法。<br /><br />
<br /><br />
## 2. 总体设计<br />
### 2.1 系统功能<br />
#### 2.1.1 功能概述<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;该系统实现了算法辅助教学的功能，学生端主要涉及算法理论教学设计、算法实践教学设计、算法动态可视化教学、算法自适应测验、用户学习结果分析、算法知识图谱展示六个方面的功能。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;教师端主要完成相关学习资源的添加和删除，教师可以可以添加算法教学课程以及算法所涉及的学习资源，比如测试习题、教学视频等，也可以查看该门课程中学生的成绩。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;系统管理员端主要实现用户（教师与学生）管理，包括添加、删除和修改操作，同时对算法课程进行管理，包括添加、删除和修改操作。<br /><br /><br />

### 2.2	系统软硬件平台<br />
#### 2.2.1	系统开发平台<br />
操作系统<br />
操作系统名称：Windows 10家庭中文版（x64）<br />
生产厂家Microsoft Corporation，版本号10.0<br />
<br />
数据库<br />
关系型数据库名称：MySQL，版本号8.0，生产厂家Oracle Corporation.<br />
图数据库名称：Neo4j，版本号2.1.3，生产厂家Neo4J<br />
<br />
系统代码构建实现平台<br />
Java SE，版本号8.0，生产厂家：Oracle Corporation.<br />
JDK，版本号1.8，生产厂家：Oracle Corporation.<br />
IDEA2018，版本号2018.1.3，生产厂家：Jet Brains.<br />
Springboot开发框架，版本号2.2.6，生产厂家Pivotal.<br />
<br />
系统构建工具<br />
git	2.23.0	https://git-scm.com/downloads<br />
有效高速处理项目<br />
版本管理<br />
node.js	10.15.1	https://nodejs.org/en/<br />
安装npm<br />
npm	6.4.x	https://nodejs.org/en/download/<br />
允许用户下载和安装第三方编写的命令行程序<br /><br />

#### 2.2.2	系统运行平台<br />
算法辅助教学系统采用B/S架构<br />
若要在自己的电脑上运行系统，则需安装以下软件并进行配置：<br />
	Java<br />
首先我们要下载java开发工具包JDK，下载地址：<br />
http://www.oracle.com/technetwork/java/javase/downloads/index.html，<br />
Windows安装地址：https://learner.blog.csdn.net/article/details/88926242<br />
之后再需要配置环境变量，安装教程：<br />
https://www.runoob.com/java/java-environment-setup.html<br />
<br />
	IDE2018（IntelliJ IDEA）<br />
下载地址为：https://www.jetbrains.com/idea/download/<br />
Professionnal版本，选择合适的操作系统版本下载。<br />
<br />
	Mysql关系型数据库<br />
下载地址为：https://www.mysql.com/downloads/<br />
选择对应的版本下载并安装，并配置环境变量。<br />
安装教程见：https://www.cnblogs.com/laumians-notes/p/9069498.html<br />
<br />
	Navicat for Mysql<br />
为了方便管理数据库，我们下载数据库管理工具Navicat for Mysql 12.1。安装教程见：<br />
https://www.navicat.com.cn/manual/online_manual/cn/navicat/win_manual/#/installation<br />
<br />
	Neo4j图数据库<br />
为了方便对大数据算法的知识点进行管理，我们使用Neo4j图数据库进行存储，安装官网为https://neo4j.com/download-center/<br />
安装教程https://blog.csdn.net/vivian_ll/article/details/89312526<br />
<br />
	vis.js可视化<br />
为了方便将算法知识图谱进行可视化，我们使用vis.js技术进行展示，安装官网为：<br />
http://visjs.org/dist/vis.js<br />
http://visjs.org/dist/vis.css<br />
<br />
	Python实践模块中案例代码的运行环境设置<br />
Python 3.6 (Anaconda 5.1亦可, 安装Anaconda之后不需另行安装Python3. 6)<br />
Anaconda的下载地址为：https://www.anaconda.com/download/<br />
Python 3.6 的下载地址为：https://www.python.org/downloads/<br />
安装教程参见：https://blog.csdn.net/huzenhuzen/article/details/8866150<br />
① 配置环境变量<br />
需要将Python安装目录/python. exe配置进环境变量，具体操作如下：<br />
我的电脑 > 属性 > 高级系统设置 > 环境变量 > 系统变量下的path > 编辑 > 添加python路径。<br />
② 外接库的安装，在命令提示符(cmd)中，使用pip install安装以上库或者框架。<br />
	pymysql；<br />
	urllib.request；<br />
	urllib.parse；<br />
	time；<br />
	json；<br />
	pandas；<br />
	numpy等<br />
<br /><br />
## 我们会不断更新，敬请关注！<br />
</p>
