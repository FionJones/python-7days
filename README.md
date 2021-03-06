## Python 程序设计 课程设计

###  单元1-分组与选题 

---

##### 0.基本信息

~~~
组名：九宗七组
组长：冯**
组员：孟** 陈**
选题：Python五子棋小游戏
Github地址：https://github.com/AntonVanke/python-7days/
~~~

##### 1.选题

~~~
Python五子棋小游戏

~~~

##### 2.为何要选择这个题

```
我们从一开始Python程序设计课（2月底）就想好了这个题目，并于四月设计好了原型，以下是我们对 这个选题的受益之处的理解

首先 我们需要有一个简单的五子棋判断程序，来判断五子棋的输赢并存储棋盘。借此来锻炼我们对Python基础的掌握

其次 我们需要有 UI 界面，可以锻炼我们对 Tkinter/PyQT5 的运用

其三 我们需要有内网联机机制，借此来了解 socket

其四 我们可能会用到服务器端，或许会接触到 Django

其五 我们会通过 α/β 剪枝算法来建造五子棋 AI 或许它很“弱智”，但能让我们有所了解 Python 如何使运行效率最大化

```

##### 3. 小组每个人对题目的看法与考虑 

~~~bash
孟** # “从小到大特别喜欢五子棋，五子棋容易上手，老少皆宜，而且趣味横生，引人入胜；不仅能增强思维能力，提高智力，而且富含哲理，有助于修身养性。已在各个游戏平台有应用。 所以希望用代码来实现五子棋”

冯** # ”我们的构思很好，究竟能不能做出和我们预想的一样就是另外一回事了“

陈** # “五子棋是一种两人对弈的纯策略型棋类游戏，是起源于中国古代的传统黑白棋种之一。发展于日本，流行于欧美。容易上手，老少皆宜.”
~~~

#####  4. 代码平台信息 

~~~
我们的代码会发布到 [Github平台](https://github.com/AntonVanke/python-7days) 
~~~

[Github平台](https://github.com/AntonVanke/python-7days)











---

#### 附 0：Python 程序设计课程设计指导

##### 一、 课程设计目的和任务 

本课程设计是本专业的一门重要实践性教学环节。在学习了专业基础课和
《Python 程序设计》课程的基础上，本课程设计旨在加深对 Python 程序设计的
认识， 对 Python 语言及其语言生态有一个进一步的掌握和应用，学会运用 Python
标准库及外接相关库来解决实际问题的基本能力，培养和提高学生分析问题、解
决问题的能力，尤其是提高学生使用 Python 为开发语言来进行问题描述、交流
与思考的能力，为毕业设计和以后的工程实践打下良好的基础。 

##### 二、 课程设计任务和要求 

本课程设计主要任务是以三人一组为单位，用 Python 语言完成一个小规模
的程序项目开发。每个小组一名组长，两个成员。设计参考题目见附件 1，各小
组题目允许相同。 
课程设计的基本要求是：在课程设计的各个阶段严格、规范地完成相关的文
档，例如总体方案报告，详细设计报告、功能说明、数据结构说明、算法说明、
程序设计框图、图例和源程序等。要求所写文档结构合理、内容完整、叙述清晰。
程序源码要有详细注释，可读性好。更高要求是：有创意、系统界面美观。 

##### 三、 课程设计评分标准： 

课程设计成绩=`小组成绩 70%`+`个人成绩 30%` 小组成绩主要依据最后汇报答辩，个人成绩主要参考个人完成的任务、设计报告。

##### 四、 课程进度安排 

| 次数 | 时间                   | 地点 | 任务安排                       |
| :--: | ---------------------- | ---- | ------------------------------ |
|  1   | 周一上午 8：00-11：30  |      | 分组与选题，三人一组，共 29 组 |
|  2   | 周一下午 14：30-18：00 |      | 任务计划与分配，相关文档上传   |
|  3   | 周五上午 8：00-11：30  |      | 1-15 组答辩                    |
|  4   | 周五下午 14：30-18：00 |      | 16-29 组答辩                   |

##### 五、 课程设计报告要求 

每位同学都必须提交课程设计报告。报告主要由五部分组成： 
1.选题：为何要选择这个题？小组每个人对题目的看法与考虑。 
2.任务分配：每个小组成员的任务分工与内容分配。要求分工必须清晰，内
容要明确。 
3.进度安排：根据任务分配结果来计划确定每个小组成员的任务进度安排，
具体到每个半天，可参考下表。 

| 次数 | 时间     | 小组单元任务   | 张三 | 李四 | 王五 |      |
| ---- | -------- | -------------- | ---- | ---- | ---- | ---- |
| 1    | 周一上午 | 分组与选题     |      |      |      |      |
| 2    | 周一下午 | 任务计划与分配 |      |      |      |      |
| 3    | 周二     |                |      |      |      |      |
| 4    | 周三     |                |      |      |      |      |
| 5    | 周四     |                |      |      |      |      |
| 6    | 周五     | 课程设计汇报   |      |      |      |      |

 4.工作内容 
根据每个人的任务分配和进度安排表，按每个半天为单位将自己的工作内容
详细记录并整理，可参考下表： 

| 次数 | 时间 | 单元工作任务与内容 | 遇到问题       | 解决方法 | 单元总结 |
| ---- | ---- | ------------------ | -------------- | -------- | -------- |
| 1    | 周一 | 上午               | 分组与选题     |          |          |
| 2    | 周一 | 下午               | 任务计划与分配 |          |          |
| 3    | 周二 |                    |                |          |          |
| 4    | 周三 |                    |                |          |          |
| 5    | 周四 |                    |                |          |          |
| 6    | 周五 | 课程设计汇报       |                |          |          |

 

5.总结：对课程设计进行总结，写出自己本次课程设计的收获与心得。可以
在单元总结的基础上进行课程设计总结。 
上述 5 部分内容中，1-3 部分每个小组成员可以相同，4-5 部分是每个成员
自己的工作内容，不得与其他成员相同。 
报告格式与字体： 
1) 各段标题可采用四号黑体 
2) 正文采用小四宋体，每段正文首行缩进 2 字符 
3) 行距（1.5 倍行距） 
4) 段落间距（自动） 
5) 页眉页脚（有页码） 
6) 图表需编号并命名。 
报告封面统一，格式见附件 2。 

##### 六、 课程设计报告提交要求： 

课程设计报告打印稿在答辩前，按小组提交。 电子稿提交到课堂派课程作业。要求如下：电子稿含一个设计报告的 word 文件和若干个程序代码文件。设计报告按“序号_姓名_设计题目”格式命名，例 “03_刘备_俄罗斯方块游戏设计”；程序代码文件数量不超过 3 个的话，直接按 文件上传，否则的话可以压缩为一个文件再上传
