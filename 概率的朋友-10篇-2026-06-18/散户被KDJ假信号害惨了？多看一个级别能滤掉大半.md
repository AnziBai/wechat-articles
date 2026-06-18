---
title: 散户被KDJ假信号害惨了？多看一个级别能滤掉大半
author: 桥博士
cover: C:/Users/Administrator/gzhpublisher/assets/概率的朋友配图/图 3.33 KDJ 指标示意图.jpg
---

你觉得KDJ不好用。金叉买了就跌，死叉卖了就涨。折腾了半年，亏了不少，最后得出一个结论——"KDJ是垃圾指标。"

KDJ不是垃圾。是你只看了一层。

你拿着日线的KDJ金叉死叉在做交易决策，就像站在一楼窗户往外看天气决定穿什么——你只能看到楼前面那片天。你换到三楼看一眼，就会发现整个天空的云在往另一个方向走。

日线KDJ在震荡市里反复发信号，是正常的。问题不在指标，在你只看了一个级别。加一层大级别过滤，就能把大部分假信号挡掉。

<img src="C:/Users/Administrator/gzhpublisher/assets/概率的朋友配图/图 3.33 KDJ 指标示意图.jpg" alt="图 3.33 KDJ 指标示意图" style="border-radius: 8px; max-width: 100%;" />

## 单级别KDJ：你现在用的方式

大部分散户用KDJ就是这个模式：打开日线图，看K线和D线。K往上穿过D，金叉，买。K往下穿过D，死叉，卖。

参数一般是默认的9,3,3。有人改成14或者21，觉得"慢一点更稳"。

<img src="C:/Users/Administrator/gzhpublisher/assets/概率的朋友配图/图 3.22 参数优化结果.jpg" alt="图 3.22 参数优化结果" style="border-radius: 8px; max-width: 100%;" />

这个用法在趋势行情里是能赚钱的。一波上涨行情启动时，KDJ金叉出现得比较早，你能吃到大部分利润。

问题出在震荡市。

A股一年里有六七个月是震荡的——指数在一个区间来回晃，不上不下。这段时间你打开KDJ，会看到什么？金叉。死叉。金叉。死叉。两三天一次。你追着它操作，今天买明天卖，来回摩擦，佣金加上滑点，每来回一次大概损耗0.5%-1%。

一个月被假信号骗进骗出五六次，3%-5%就没了。你不是"不会用KDJ"。你是在一个不该用单级别KDJ的环境里用了单级别KDJ。

<img src="C:/Users/Administrator/gzhpublisher/assets/概率的朋友配图/图 3.35 KDJ 指标针对上证 50 指数所有个股品种回测损益图.jpg" alt="图 3.35 KDJ 指标回测损益图" style="border-radius: 8px; max-width: 100%;" />

还有一种情况更坑——钝化。在一波强趋势里，K和D值冲到80以上，然后在高位反复纠缠。你看着"超买了"，卖了。结果它继续涨。你在趋势起步的时候被甩下车了。KDJ的超买超卖区在强趋势里是不可靠的——它并不意味着要反转，只是说明涨得快。

所以单级别KDJ的问题总结起来就两个：震荡市假信号太多，趋势市容易过早出场。

## 多级别过滤：加一层就完全不一样

多级别过滤的意思很简单：在你操作的那个级别之上，再看一个更大的级别。

你在日线上做交易，那就同时看周线的KDJ。

规则是这样的：

周线KDJ方向向上（K在D上方，KDJ值在上升或者在高位运行），日线KDJ出现金叉——买入信号有效。

周线KDJ方向向下（K在D下方），日线KDJ出现金叉——不买。大方向往下走，小级别的反弹信号不可靠。

周线KDJ方向向上，日线出现死叉——不急着卖。大方向还在，小级别回调可能是上车机会。

周线KDJ方向向下，日线死叉——确认卖出。大小同向，信号可信。

你做的事情就是：用大级别来判断"现在是什么环境"，只有环境对了才执行小级别的信号。环境不对的信号直接忽略。

这一层过滤能挡掉多少假信号？保守估计一半以上。那些在震荡市里让你反复被打脸的金叉，大部分都发生在周线KDJ方向不明或者向下的时候。周线这一关没过，你就不会去追日线的金叉。

## 单级别和多级别到底差在哪

<table style="width:100%; border-collapse:collapse; font-size:15px; margin:20px 0;">
<thead>
<tr style="background:#f5f5f5;">
<th style="padding:10px; border:1px solid #ddd; text-align:left;">维度</th>
<th style="padding:10px; border:1px solid #ddd; text-align:left;">单级别KDJ</th>
<th style="padding:10px; border:1px solid #ddd; text-align:left;">多级别KDJ过滤</th>
</tr>
</thead>
<tbody>
<tr>
<td style="padding:10px; border:1px solid #ddd;">信号频率</td>
<td style="padding:10px; border:1px solid #ddd;">高。震荡市每周1-2次</td>
<td style="padding:10px; border:1px solid #ddd;">低。只在大小同向时触发</td>
</tr>
<tr>
<td style="padding:10px; border:1px solid #ddd;">假信号率</td>
<td style="padding:10px; border:1px solid #ddd;">震荡市60%-70%是假信号</td>
<td style="padding:10px; border:1px solid #ddd;">过滤后降到30%以下</td>
</tr>
<tr>
<td style="padding:10px; border:1px solid #ddd;">趋势市表现</td>
<td style="padding:10px; border:1px solid #ddd;">能抓住，但钝化容易被甩</td>
<td style="padding:10px; border:1px solid #ddd;">周线确认趋势，日线钝化可以扛</td>
</tr>
<tr>
<td style="padding:10px; border:1px solid #ddd;">震荡市表现</td>
<td style="padding:10px; border:1px solid #ddd;">反复打脸，来回损耗</td>
<td style="padding:10px; border:1px solid #ddd;">大部分信号被过滤，减少操作</td>
</tr>
<tr>
<td style="padding:10px; border:1px solid #ddd;">操作复杂度</td>
<td style="padding:10px; border:1px solid #ddd;">低。看一张图就行</td>
<td style="padding:10px; border:1px solid #ddd;">中。要同时看两个周期</td>
</tr>
<tr>
<td style="padding:10px; border:1px solid #ddd;">适合的人</td>
<td style="padding:10px; border:1px solid #ddd;">纯新手入门练手</td>
<td style="padding:10px; border:1px solid #ddd;">有基础、想提高胜率的散户</td>
</tr>
</tbody>
</table>

表里有一个关键信息：多级别过滤并不完美。它过滤掉假信号的同时，也会过滤掉一些真信号——特别是趋势转折初期，大级别还没确认，小级别已经启动了。这时候你按规则不买，可能会错过一段行情的起步阶段。

这是所有过滤方法的共同代价：更少的操作，更少的错误，但也更少的机会。

如果你接受这个代价——事实上大部分散户应该接受，因为"做得少但做得对"远比"做得多但做得乱"赚钱——那多级别过滤是一个值得用的改进。

## 什么时候用单级别，什么时候用多级别

不需要二选一。看你做什么类型的交易。

如果你做日内交易或者极短线（持仓不超过3天），单级别KDJ可以用。因为你的进出速度快，假信号造成的损耗你能通过快速止损控制住。这种情况下多级别过滤反而让你反应太慢。

如果你做波段（持仓1-4周），多级别过滤几乎是必须的。波段交易的核心是"方向对了再进"，大级别的方向判断是波段操作的前提。

如果你做趋势交易（持仓一个月以上），单独的KDJ——不管单级别还是多级别——都不够用了。趋势交易需要的是对市场环境的整体判断，不是某个指标的金叉死叉。

<img src="C:/Users/Administrator/gzhpublisher/assets/概率的朋友配图/图 3.37 KDJ+MACD 指标参数优化后针对上证 50 指数所有个股品种组合的损益图.jpg" alt="图 3.37 KDJ+MACD 组合回测损益图" style="border-radius: 8px; max-width: 100%;" />

## 弹论做的其实是同一件事，但更干净

多级别KDJ过滤的思路是对的——用大级别判断环境，只在环境对的时候操作。

我在宽论体系里用弹论，做的本质上是同一件事。区别在于：弹论不需要你切换周期。

弹论看的是日线上5日、10日、20日、40日、60日这5根均线的排列结构。这5根均线本身就包含了不同级别的信息——5日线代表一周、20日线代表一个月、60日线代表一个季度。你不用切换到周线或月线，在一张图上就能看到多个级别的趋势方向。

弹上——5根均线从上到下排好，多头排列——环境OK，可以操作。弹下——空头排列——不操作。弹中——均线缠绕——不操作。

这就是多级别KDJ过滤的升级版。你不用在两张图之间来回切换，不用同时跟踪两个周期的KDJ状态。5根均线排列一眼看完，环境判断完毕。

然后信号怎么出？不用KDJ了。用CDVA分型。V分型——收盘价站上前一根K线实体上沿——在弹上环境里出现，就是买入信号。A分型——跌破下沿——是减仓信号。信号定义严格，不含糊。

<img src="C:/Users/Administrator/gzhpublisher/assets/概率的朋友配图/图 3.40 各量化指标的准确性对比（以 2007 年上证指数创新高行情内各指标开平仓位置为例）.jpg" alt="图 3.40 各量化指标准确性对比" style="border-radius: 8px; max-width: 100%;" />

<p style="font-size:13px; color:#888; margin-top:-10px;">弹论和CDVA分型的完整推导和历史回测数据在《概率的朋友》第10章。KDJ、MACD等单指标的回测对比在第3章。两章对照着看，你会理解为什么多级别过滤是必须的，以及弹论怎么用一张图做到同样的事。</p>

## 你现在能做的改进

如果你还想继续用KDJ，最小的改进就是加一层周线过滤：

第一步，打开周线图，看周线KDJ的方向。K在D上方且向上——大方向向上。K在D下方且向下——大方向向下。不上不下的——观望。

第二步，只有大方向向上的时候，才看日线KDJ的金叉。大方向向下或不明的时候，日线金叉一律不理。

第三步，记录一个月。把每次操作写下来：哪些是过了周线过滤的，哪些是没过你照样做了的。一个月后对比两组的盈亏。你自己的数据会告诉你这一层过滤值不值。

做完这三步，你再看看要不要了解弹论。弹论做的事情更彻底——它不是"给KDJ加一层过滤"，是用5根均线的排列结构直接替代了KDJ的环境判断功能。两个工具解决同一个问题，只是路径不同。你先体会到"多级别过滤"的价值，弹论你一看就懂。

---

<div style="text-align:center; margin:36px 0 16px 0;">
  <span style="display:inline-block; background:linear-gradient(90deg,#ff6b35,#eb1313); color:#fff; font-size:17px; font-weight:bold; padding:9px 24px; border-radius:22px;">📚 读者专属 · 概率的朋友知识手册</span>
</div>
<img src="C:/Users/Administrator/gzhpublisher/assets/手册/1.png" alt="知识手册-K线是什么" style="border-radius:10px; max-width:100%; display:block; margin:14px auto;" />
<img src="C:/Users/Administrator/gzhpublisher/assets/手册/10.png" alt="知识手册-黄昏之星" style="border-radius:10px; max-width:100%; display:block; margin:14px auto;" />
<img src="C:/Users/Administrator/gzhpublisher/assets/手册/20.png" alt="知识手册-楔形" style="border-radius:10px; max-width:100%; display:block; margin:14px auto;" />
<img src="C:/Users/Administrator/gzhpublisher/assets/手册/35.png" alt="知识手册-RSI" style="border-radius:10px; max-width:100%; display:block; margin:14px auto;" />
<img src="C:/Users/Administrator/gzhpublisher/assets/手册/45.png" alt="知识手册-唐奇安通道" style="border-radius:10px; max-width:100%; display:block; margin:14px auto;" />
<div style="margin:22px 0; padding:20px; background:#fff9e6; border-left:4px solid #ff6b35; border-radius:8px;">
  <p style="font-size:16px; color:#333; line-height:1.9; margin:0;">我已经把《概率的朋友》中涉及到的指标模型以及K线形态知识整理成了知识手册，是电子版的，你用手机就可以看，下面留"<strong style="color:#eb1313;">学习</strong>"，就能取。</p>
</div>

还请麻烦给文章点个在看或者免费的赞，感谢您的阅读。

*免责声明：本文介绍的是量化分析技术培训，不构成投资建议。投资有风险，入市需谨慎。*
