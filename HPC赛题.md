## 科学计算题目

科学计算题目可参考[去年赛题](https://github.com/royenheart/LzuOssHPC-2023/)，作为学习与加深理解用，其中[SCI-3](https://github.com/royenheart/LzuOssHPC-2023/blob/main/problem-sets/sci-3.md)为今年必做，请附到你的报告当中

### 任务描述

单精度纯CPU条件下的MPAS-Atmosphere模型的优化，输入为**benchmark_120km**，可从[Index of /projects/mpas/benchmark](https://www2.mmm.ucar.edu/projects/mpas/benchmark/) 下载
namelist.atmosphere 中的 config_run_duration 值改为 16 分钟
**config_run_duration = '00:16:00'**

要求使用相同数量的 MPI 级联运行时，最后一个时间步的输出日志中 “全局最小、最大 w ”和 “全局最小、最大 u ”行的值必须相同

你可以申请兰州大学超算中心的节点，或是使用自己的机器

### 评判标准

1.是否成功编译并运行
2.是否进行了优化，以及相比于优化之前的运行效率的对比
3.是否进行了代码的改动、以及它对运行效率的影响（正负均可）

请你将尽可能多的内容写进你的报告中，以体现你做出的努力以及工作量

