
# 认知语言学全局认识

## [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#%E7%9B%AE%E5%BD%95)目录

## [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#0-%E6%91%98%E8%A6%81)0. 摘要

这是开智学堂「信息分析」课程第 2 周任务报告，包含分析背景、思路与分析步骤、主要结论、进一步讨论、参考文献等内容，完整重现我获取此题目答案的过程。

总体来说有 3 个分析思路——分别是从学术，技术和商业入手。最终采取思路一：确定领域重要学科并下载该学科1000篇论文 ，详细步骤参见正文。

## [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#1-%E8%83%8C%E6%99%AF)1. 背景

这个想法来自于我的职业发展，因为对人工智能和语言学感兴趣，因此想了解自然语言处理。

## [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#2-%E5%88%86%E6%9E%90%E8%BF%87%E7%A8%8B)2. 分析过程

### [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#21-%E4%B8%89%E7%A7%8D%E6%80%9D%E8%B7%AF)2.1 三种思路

#### [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#%E6%80%9D%E8%B7%AF%E4%B8%80%E4%BB%8E%E5%AD%A6%E7%A7%91%E5%85%A5%E6%89%8B)思路一：从学科入手

自然语言处理维基定义为：人工智能和语言学领域的分支学科。首先，我会希望利用找到问题背后学科的实践策略，确定该领域重要的学科。第二，在Google学术批量下载某一关键学科的1000篇论文——利用最小知识法则提炼知识框架。

#### [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#%E6%80%9D%E8%B7%AF%E4%BA%8C%E4%BB%8E%E6%8A%80%E6%9C%AF%E5%85%A5%E6%89%8B)思路二：从技术入手

首先以GitHub和Kaggle为源头，分析各类工具，技术，模型的使用频率及趋势。然后找到某学术+技术的大牛，查找并研究大牛相关论文和作品。最后得出该领域初步发展策略。

#### [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#%E6%80%9D%E8%B7%AF%E4%B8%89%E4%BB%8E%E5%95%86%E4%B8%9A%E5%85%A5%E6%89%8B)思路三：从商业入手

首先检索自然语言领域的相关应用如机器翻译，语义分析，语音输入等等。利用专利数据库查找相关专利，分析专利获得年份，机构等信息。了解各个机构想要解决的问题和已取得的关键成果，从而获知今后领域发展趋势。

### [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#22-%E5%85%B7%E4%BD%93%E6%AD%A5%E9%AA%A4)2.2 具体步骤

1.  确定涉及学科 从人工智能及语言学的维基页面提取涉及学科列表。

人工智能涉及：

物理学 哲学和认知科学 逻辑学 数学，统计学 心理学 计算机科学 控制论 决定论 不确定性原理 社会学 犯罪学 智能犯罪

语言学分支学科：

-   理论语言学
    -   语音学
    -   音韵学
    -   构词学
    -   语法学
    -   语义学
        -   词汇语义学
        -   结构语义学
        -   原型语义学
    -   语用学
-   应用语言学
    -   心理语言学
    -   社会语言学
    -   生成语言学
    -   认知语言学
    -   神经语言学
    -   计算语言学
    -   共时语言学
        -   对照语言学
    -   历史语言学
        -   比较语言学
    -   文体学
        -   规范语言学
        -   语源学
    -   语料库语言学
-   其他
    -   语言学史
    -   语言学家列表
    -   未解的问题

再查看自然语言分析的详细描述：

> 自然语言处理（英语：natural language processing，缩写作 NLP）是人工智能和语言学领域的分支学科。此领域探讨如何处理及运用自然语言；自然语言处理包括多方面和步骤，基本有认知、理解、生成等部分。 自然语言认知和理解，让计算机把输入的语言变成有意思的符号和关系，然后根据目的再处理。 自然语言生成系统把计算器数据转化为自然语言。

由此缩窄范围：认知语言学，结构语义学，生成语言学，计算机科学。再由此前读过的《语言本能》一书基本确定要分析的学科为：认知语言学。

查看认知语言学的定义及描述：

> 认知语言学是语言学的一门颇新分支，它脱胎自认知心理学或认知科学，大约在1980年代后期至1990年代开始成型。认知语言学涉及电脑自然语言理解、人工智能、语言学、心理学、神经科学、系统论等多种学科，它针对当时仍很火热的生成语言学，提出：语言的创建、学习及运用，从基本上都必须能够透过人类的认知而加以解释，因为认知能力是人类知识的根本。 认知语言学有以下三大分支： 认知语义学：包括了构词法及语意分析 认知文法：透过对现存语言的分析及了解其背后产生的环境及习惯、隐喻等，归纳出来的文法规则，而不是透过数学的生成方程来产生的文法规则 认知语音学 认知语言学的创立者普遍被认为是乔治·莱考夫(George Lakoff)、马克·詹森(Mark Johnson)及朗奴·兰盖克。当中雷可夫及詹森专门研究语言中的比喻及其与人类认知的关系；而兰盖克的专长在于认知文法的生成。

提取关键学科：生成语言学 知名人物：

-   乔治·雷可夫 (George P. Lakoff；/ˈleɪˌkɔf/，1941年-)：认知语言学的其中一位创立者，提倡比喻(隐喻)是日常语言活动中的必须认知能力。
-   马克·詹森 (Mark Johnson）
-   朗奴·兰盖克 (Ronald Langacker，1942年12月27日-)：认知文法的提倡者
-   诺姆·乔姆斯基：他的生成语法被认为是对20世纪理论语言学研究的重要贡献。
-   Gilles Fauconnier
-   Charles J. Fillmore
-   William Croft
-   Michael Tomasello
-   戴浩一：台湾国立中正大学语言学研究所教授，是少数专长于认知语言学的华人。
-   王士元：香港中文大学现代语言学系暨中研院院士，另一少数专长于认知语言学的华人。

下一步：检索学科论文，找一个牛人检索并分析其论文

2.  根据Google H指数找寻学科牛人

在Google学术搜索cognitive linguistics，然后用插件WebScrapper简单爬取每个有主页的作者的H指数数据（其中N Chomsky 和 RW Langacker 并没有学者主页），整理如下：

[![](https://github.com/JanusChoi/IA002/raw/master/ch2/_image/2018-10-18-18-08-44.jpg)](https://github.com/JanusChoi/IA002/blob/master/ch2/_image/2018-10-18-18-08-44.jpg)

3.  尝试下载牛人的论文

遇到问题：

-   M Tomasello的论文数非常多，参与论文数为3060，过滤认知语言学之后还有224。如何进一步缩小结果范围？
-   Google学术多下载几页就会报错，判别可能是机器人操作
-   Google学术没有提取文献的摘要
-   Update citations的操作也会导致Google识别为机器人
-   尝试了利用收藏后导出的功能，但可得信息太少（没有附件，没有快照）

后面尝试使用百度学术。百度学术的好处是能提取到摘要（但提取出来的内容不完整），但拿不到引用数（考虑修改translators）。尝试了提取R Jackendoff和NC Ellis的论文：

[![](https://github.com/JanusChoi/IA002/raw/master/ch2/_image/2018-10-19-11-42-47.jpg)](https://github.com/JanusChoi/IA002/blob/master/ch2/_image/2018-10-19-11-42-47.jpg)

[![](https://github.com/JanusChoi/IA002/raw/master/ch2/_image/2018-10-19-11-42-58.jpg)](https://github.com/JanusChoi/IA002/blob/master/ch2/_image/2018-10-19-11-42-58.jpg)

4.  下载领域1000篇论文

在中国知网搜索“认知语言学”的博硕论文，结果数为1688，按引用数排序，下载前1000篇。

[![](https://github.com/JanusChoi/IA002/raw/master/ch2/_image/2018-10-19-12-43-07.jpg)](https://github.com/JanusChoi/IA002/blob/master/ch2/_image/2018-10-19-12-43-07.jpg)

5.  后续阅读策略

选一个牛人研究：G Lakoff

最原始（上世纪80年代）： O1: Linguistics as a Cognitive Science and Its Role in an Undergraduate Curriculum. O2: Women, fire, and dangerous things: What categories tell us about the nature of thought O3: A Suggestion for a Linguistics with Connectionist Foundations

最新： N1: Lecture 4 - Ten Lectures on Cognitive Linguistics N2: Invariance principle (linguistics) N3: Mapping The Brain's Metaphor Circutry: Metaphorical Thought In Everyday Life

高引用： H1: Women, fire, and dangerous things: What categories tell us about the nature of thought H2: The neural theory of metaphor（NTL）. H3: Why cognitive linguistics requires embodied realism.

感兴趣： I1：Women, fire, and dangerous things: What categories tell us about the nature of thought I2：How unconscious metaphorical thought shapes dreams. I3：What Makes a Great Speech Great

I4：另外感兴趣的：M Tomasello对平克《语言本能》的书评 - Language is not an instinct

快速阅读提取信息：

H1：概念隐喻理论(conceptual metaphor)，心智的亲身性，核型理论，格式塔 H2：NTL解决的问题有 cross-domain mapping，隐喻系统与经验的关系，从大脑视角看待隐喻理论 H3：肉体中的哲学 Philosophy in the Flesh O1： O2： O3： N1： N2： N3： I1： I2： I3： I4：

## [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#3-%E7%BB%93%E8%AE%BA)3. 结论

做这个事情的感受是，大量信息一下子涌进，脑子一下懵掉了。好像面前有一个庞然大物，让我心生恐惧——于是在粗略读完三篇最高引用的文章后，决定先放一放去解决前面遇到的一些可解决的技术问题（笑哭）。

基本得到的一个讯息是，乔治·莱考夫的几本作品很值得一看，分别是：《我们赖以生存的隐喻》，《女人、火与危险事物：范畴显示的心智》，《肉身哲学：亲身心智及其向西方世界的挑战》还《乔治·莱考夫认知语言学十讲》

## [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#4-%E8%AE%A8%E8%AE%BA)4. 讨论

### [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#41-%E5%AF%B9%E7%BB%93%E8%AE%BA%E7%9A%84%E8%AE%A8%E8%AE%BA)4.1 对结论的讨论

-   未完成暂不讨论

### [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#42-%E5%8F%AF%E4%BC%98%E5%8C%96%E7%9A%84%E7%8E%AF%E8%8A%82)4.2 可优化的环节

-   学科确定环节应用时更短些
-   找两个平台替代Google学术——（有引用数，有摘要）

### [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#43-%E6%94%B6%E8%8E%B7)4.3 收获

找到一般大众看不到的信息点：例如H指数174的 M Tomasello，在发展心理学，认知科学，进化人类学，进化心理学等领域都有很多论文，在认知语言学方面更多地研究语言建构。

## [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#5-%E5%8F%82%E8%80%83%E6%96%87%E7%8C%AE)5. 参考文献

[维基百科-认知语言学](https://zh.wikipedia.org/wiki/%E8%AA%8D%E7%9F%A5%E8%AA%9E%E8%A8%80%E5%AD%B8)

Lakoff, “Linguistics as a Cognitive Science and Its Role in an Undergraduate Curriculum. Linguistics in the Undergraduate Curriculum, Appendix 4-F.”; Lakoff, Women, Fire, and Dangerous Things; Lakoff, “A Suggestion for a Linguistics with Connectionist Foundations”; Lakoff, “How Unconscious Metaphorical Thought Shapes Dreams.”; Johnson and Lakoff, “Why Cognitive Linguistics Requires Embodied Realism.”; Lakoff, “The Neural Theory of Metaphor.”; Lakoff, “Mapping The Brain’s Metaphor Circutry”; Lakoff, “Invariance Principle (Linguistics)”; Lakoff, “Lecture 4 - Ten Lectures on Cognitive Linguistics”; Lakoff and Com, “What Makes a Great Speech Great.”

## [](https://github.com/JanusChoi/IA002/blob/master/ch2/RepTaskBasic.md#changelog)changelog

181017-确定思路，研究学科 181018-找牛人，批量下载论文 181017-阅读收集回来的资料
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTkwMDgyNTIzNSw1OTUxMDM2MjIsLTIwOD
g3NDY2MTIsMTI2OTY5MTEwNl19
-->