PRD V1.0

Signal Oracle（信号神谕）

Product Vision

利用 Flipper Zero 对现实世界无线环境的感知能力，将不可见的电磁信号转化为可感知的信息与启示。

用户提出问题。

系统不依赖传统随机数生成器。

而是基于周围真实存在的无线电活动生成答案。

每一次回答都来自：

* 当前环境
* 当前时间
* 当前信号状态

因此不存在完全相同的答案。

⸻

一、产品定义

产品名称

Signal Oracle

中文：

《信号神谕》

⸻

产品定位

一个基于环境电磁熵的现实世界神谕系统。

不是占卜工具。

不是 AI 助手。

而是一种：

现实世界状态映射器。

⸻

产品核心公式

Answer = F(Environment State)

其中：

Environment State =

* BLE
* SubGHz
* NFC
* Device State
* Time

⸻

二、用户价值

用户获得

1. 决策触发器

帮助用户跳出思维循环。

⸻

2. 环境感知

感知平时看不见的无线世界。

⸻

3. 仪式感

形成独特的交互体验。

⸻

4. 收藏价值

每个答案都与特定环境绑定。

具有唯一性。

⸻

三、目标用户

核心用户

Flipper Zero 玩家

占比：

70%

⸻

次级用户

开发者

创业者

极客群体

⸻

潜在用户

数字神秘学爱好者

电子艺术玩家

赛博朋克文化群体

⸻

四、核心体验流程

用户：

提出问题

↓

开始扫描

↓

采集环境信号

↓

生成世界状态

↓

映射答案

↓

保存神谕记录

⸻

五、世界状态引擎

Oracle Engine

核心模块：

World State Generator

⸻

输入源

BLE

采集：

* 设备数量
* RSSI
* 信号变化率

输出：

Activity Score

⸻

SubGHz

采集：

* 频率数量
* 信号密度
* RSSI波动

输出：

Entropy Score

⸻

NFC

采集：

* 是否存在Tag
* Tag类型

输出：

Presence Score

⸻

Device

采集：

* 电量
* 温度
* 启动时间

输出：

Device State

⸻

Time

采集：

* 小时
* 星期
* 日期

输出：

Temporal State

⸻

六、环境状态模型

Environment Vector

{
  "entropy":0.73,
  "activity":0.85,
  "stability":0.21,
  "novelty":0.67,
  "silence":0.12
}

⸻

七、五维世界状态

Entropy

混乱程度

高：

变化剧烈

低：

秩序稳定

⸻

Activity

活跃程度

高：

大量设备

低：

环境安静

⸻

Stability

稳定程度

高：

变化很小

低：

变化频繁

⸻

Novelty

新颖程度

高：

发现未知设备

低：

环境熟悉

⸻

Silence

静默程度

高：

几乎无信号

低：

无线环境活跃

⸻

八、答案系统

答案类别

Forward

行动

例如：

向前。

立即验证。

开始执行。

⸻

Observe

观察

例如：

继续观察。

不要急于判断。

信息仍在形成。

⸻

Warning

警示

例如：

噪声正在干扰判断。

你忽略了异常。

⸻

Explore

探索

例如：

答案在新的方向。

改变观察点。

⸻

Reflection

反思

例如：

问题本身值得重新审视。

你真正想问的不是这个。

⸻

九、神谕生成流程

Step1

生成环境向量

⸻

Step2

计算环境熵

⸻

Step3

生成随机种子

Seed =

Hash(
BLE
+
SubGHz
+
Time
+
Battery
)

⸻

Step4

答案权重计算

例如：

Entropy > 0.8

增加：

Warning

Explore

权重

⸻

Silence > 0.8

增加：

Observe

Reflection

权重

⸻

Step5

输出最终神谕

⸻

十、神谕记录系统

保存：

{
 "time":"2027-06-18T20:30",
 "entropy":0.84,
 "activity":0.73,
 "answer":"向前。",
 "rarity":"Epic"
}

⸻

十一、稀有事件系统

Rare Event

触发概率：

约5%

⸻

条件：

环境向量满足特殊组合

例如：

高熵

高活跃

低稳定

⸻

输出：

特殊神谕

⸻

Legendary Event

概率：

0.5%

⸻

输出：

唯一神谕

例如：

世界正在回应你的问题。

⸻

十二、图鉴系统

Oracle Codex

统计：

* 神谕总数
* 稀有神谕
* 环境组合
* 收藏记录

⸻

示例：

Oracle Entries
237 / 999

⸻

十三、版本规划

V1

核心神谕系统

BLE

SubGHz

答案引擎

历史记录

图鉴

⸻

V2

环境模式扩展

NFC

IR

稀有事件

环境画像

⸻

V3

成长型神谕书

Oracle Memory

⸻

新增：

环境历史分析

用户探索风格识别

神谕人格

长期趋势生成

⸻

示例：

你最近总是在高噪声环境下寻找答案。

过去30天里，
世界变得比以前更加活跃。

你已经发现了78种独特环境模式。

---
# 产品Slogan
**The World Is Already Answering.**
**世界一直在回答你。**
:::
这个版本最大的不同在于：**答案不再是“随机抽签”**，而是把 Flipper Zero 变成一个“现实世界状态采样器”。产品叙事也从神秘学转向了“信号哲学”——答案来自环境，而不是来自程序。这样在极客社区会更容易获得认同。