# LzuOssHPC 超算团队选拔题目

兰州大学 LzuOssHPC 超算团队及 ASC 25 选拔题目。


## 题目

我们分为科学计算和人工智能两个赛题，只需选取一个赛道的题做就可以，本仓库为科学计算赛道的赛题。

科学计算赛道不要求完成全部要求，做多少是多少，可以使用各种方式去学习（包括类似 ChatGPT 的人工智能）。我们的门槛不高，欢迎任何对这个领域感兴趣并有精力去学习的同学来到我们的团队，我们会根据报告判定你是否具备一定的兴趣以及必要的基础能力。

可参考[去年赛题](https://github.com/royenheart/LzuOssHPC-2023/)，作为学习与加深理解用，其中[SCI-3](https://github.com/royenheart/LzuOssHPC-2023/blob/main/problem-sets/sci-3.md)为今年必做，请附到你的报告当中

### 任务描述
单精度纯CPU条件下的MPAS-Atmosphere模型的优化，输入为**benchmark_120km**，可从[Index of /projects/mpas/benchmark](https://www2.mmm.ucar.edu/projects/mpas/benchmark/) 下载
namelist.atmosphere 中的 config_run_duration 值改为 16 分钟
**config_run_duration = '00:16:00'**

要求使用相同数量的 MPI 级联运行时，最后一个时间步的输出日志中 “全局最小、最大 w ”和 “全局最小、最大 u ”行的值必须相同

你可以申请兰州大学超算中心的节点，或是使用自己的机器

评判标准：
1.是否成功编译并运行
2.是否进行了优化，以及相比于优化之前的运行效率的对比
3.是否进行了代码的改动、以及它对运行效率的影响（正负均可）

请你将尽可能多的内容写进你的报告中，以体现你做出的努力以及工作量

## 报告格式

推荐使用 Markdown 或者 LaTeX 编写，生成 PDF 文件。LaTeX 推荐使用 overleaf 或者配置 vscode 写作环境。如果你的 word 写得相当规范也可以接受（最好还是生成 PDF 文件）。

## 提交方式以及提交时间
待定

## Thanks

感谢兰州大学超算中心、兰州大学开源社区的大力支持。
