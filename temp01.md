```
@AIHackers/IA002stu [你的名号]完成 ch* 任务啦

1. 学习成果
	* 检索实操题：[作品标题](成果链接)
	* 基础任务：[作品标题](成果链接)
	* 进阶任务：[作品标题](成果链接)
2. 个人笔记、教程地址：教过去的自己学信息分析，可包括本次作业刻意练习之处、探索过程、可积累的清单/经验等
3. 自评：140 字左右，比如学习体验，或者希望同大家讨论的要点等
4. 给楼上战友的反馈：挖掘肯定其 1-3 个亮点，给出 1-3 点改进建议
```
@AIHackers/IA002stu [bowenchris]完成 ch1 任务

5.  学习成果
    -   检索实操题：[ch1检索实操题](https://github.com/bowenchris/IA002/blob/master/ch1/RepSearchPractice.md)
    -   基础任务：[zotero的使用](https://github.com/hyacinth0906/IA002/blob/master/ch1/RepTaskBasic.md)
    -   进阶任务：[作品标题](https://github.com/AIHackers/IA002/issues/%E6%88%90%E6%9E%9C%E9%93%BE%E6%8E%A5)
6.  个人笔记、教程地址：教过去的自己学信息分析，可包括本次作业刻意练习之处、探索过程、可积累的清单/经验等
7.  自评：140 字左右，比如学习体验，或者希望同大家讨论的要点等
8.  给楼上战友的反馈：挖掘肯定其 1-3 个亮点，给出 1-3 点改进建议


ch1检索实操题：

请根据下图检索信息，补全下面两段话中 A-F 的空缺。

![](https://static.openmindclub.com/openmindclub/2018-10-01-PicIA002Ch1TaskSearch.jpg)

> 这是 A 国 2006 年发行的纸币，用来纪念 20 世纪物理学家、发明家 B 。他精通多个领域，一生拥有上千项专利，最著名的发明是 C 。
> 
> 为了纪念他，在美国纽约 D 瀑布 E 方向伫立着 B 的铜像，这座铜像具体地址是 F 。他拄着拐杖平静地凝望远方，夜幕降临，七彩霓虹随瀑布倾泻而下。

提交方式：fork 课程仓库，生成个人学习仓库，上传截图、过程和思考至  `ch0`  >  `RepSearchPractice.md`。上传成功后获取网页链接，按要求回复在所属战队作业提交 Issue 下。
#解题过程：
##  题目信息分析：

**已知确定信息：** 一张2006年发行的某国的面值100的纸币，纸币上有“sto dinara”的标识，纸币的编号是AA0009113、20世纪的男性物理学家、发明家；拥有上千项专利；在美国纽约D瀑布伫立着他的拄着拐杖的铜像。

**解题思路：** 将确定信息进行分组，检索信息，然后以不同的信息分组进行交叉验证。
- 确定纸币信息：
> 在Google、百度等上搜索“2006年货币 sto dinara”的信息；用Google、百度、货币类的网站“搜图”的功能确认图片的具体信息；
> 在该国官方网站验证货币信息的准确性。
- 确定人物的基本信息
>以wikipedia作为信息入口，搜索纸币人物的信息，进一步获取题目要求的信息；
- 通过“Tabs Outline”记录搜索的路径，用于搜索复盘；
- 获取信息的过程中不断地从多角度交叉验证确认信息的准确性。

**解题过程记录**

- 用百度搜索“纸币 sto dinara”发现有很多国家使用第纳尔作为货币单位，需要改变搜索的方式
- 用百度“图搜”，显示：塞尔维亚2006年版100 Dinara纸钞![enter image description here](https://img12.360buyimg.com/n1/jfs/t5389/306/1882559947/141581/5fdc07e/59155b58N45b5d77c.jpg)
- 在百度上搜索“塞尔维亚2006年版100 Dinara纸钞”的相关性息：
> 正面： 塞尔维亚裔美国科学家，电气工程师和发明家特斯拉Nikola Tesla 1856—1943。他的研究为现代电气和通信系统奠定了基础
背面：特斯拉与他发明的电磁感应机。
> 在官方网站交叉验证信息。搜索“塞尔维亚国家银行”验证2006年版100 Dinara纸币信息（没有查到）

A——塞尔维亚

- wikipedia搜素“Nikola Tesla”相关信息
> "特斯拉的一座纪念碑在[纽约尼亚加拉瀑布](https://en.wikipedia.org/wiki/Niagara_Falls,_New_York "尼亚加拉瀑布，纽约")建立。
B——	Nikola Tesla
C——[交流电](https://en.wikipedia.org/wiki/Alternating_current "交流电")（AC）[感应电动机](https://en.wikipedia.org/wiki/Induction_motor "感应电动机")
>    来自纽约特斯拉纪念协会的网站：[http](http://www.teslasociety.com/victoria.htm)：[//www.teslasociety.com/victoria.htm](http://www.teslasociety.com/victoria.htm)
D——尼亚加拉瀑布
在Google地图查“Nikola Tesla Monument within Queen Victoria Park”得出E——西。

## 结论



这是 塞尔维亚 国 2006 年发行的纸币，用来纪念 20 世纪物理学家、发明家 特斯拉(Nikola Tesla) 。他精通多个领域，一生拥有上千项专利，最著名的发明是 交流电系统AC(Alternative current) 。

为了纪念他，在美国纽约 尼亚加拉瀑布的美国(American Fall - A drop of Niagara Fall) 瀑布 西南 方向伫立着 特斯拉 的铜像，这座铜像具体地址是 6342 Niagara Pkwy, Niagara Falls。他拄着拐杖平静地凝望远方，夜幕降临，七彩霓虹随瀑布倾泻而下。

## 核心知识点练习

-   上位词。
-   交叉验证。
-   awesome清单——基本围绕wiki搜索，因为对于这类信息，wiki靠谱足够。
-   英语，最好是google默认工作语言（我暂时是法语，学习需要）
<!--stackedit_data:
eyJoaXN0b3J5IjpbNzQ3NzI5NywtMjA4ODc0NjYxMiwxMjY5Nj
kxMTA2XX0=
-->