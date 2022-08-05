# AI_Medical_System
AI_Medical_System(idea分享，大创项目：AI全自动疾病诊断流程的一些构思）

#-----------------------------------------------#
update on 05/08/2022 by GW.kayak


主干网络流程图如下：

![Imgur](https://github.com/kay-cottage/AI_Medical_System/blob/main/1%20(2).png)

#-----------------------------------------------#


update on 05/04/2022 by GW.kayak

类DNS域名解析服务的疾病流程分级解析流程（初筛疾病种类进行分科->对应专科的疾病初筛网络（开出检查项目）->临床决策网络->临床后端评价网络）

初筛网络，决策网络，时序网络，强化学习网络

多个多模态Clip网络作分类器进程集成，深度强化学习state reward的现实交互模式从临床中学习（clip Finetune可以见我另一主页）

LSTM时序网络联系前后网络结果最后做出
