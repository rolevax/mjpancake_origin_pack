# MJPANCAKE Origin Pack

## 这是什么

这是一个[松饼麻雀](https://mjpancake.github.io/)的非官方脚本仓库，存放我已经制作而未见于官方发行版本的人物脚本。松饼麻雀是一个致力于比官方游戏更好地呈现 Saki 世界观的麻将游戏（自称麻将模拟器但曾经支持线上游戏）。

新上传的脚本通常只经过我（打得爽就完事了）的简单测试。如果您对角色能力表现、代码逻辑等有何高见，请通过邮件或企鹅告诉我。

## 如何使用

在「松饼麻雀」-「人物下载」中，选择 MJPANCAKE Origin Pack 并「更新人物包」。在那之后，您可以在选人模式下的「下载」中看到可选人物。

## 它报错了

这是由于角色子模块一处已经被修复的 Bug 没有被更新到游戏本体中。并非所有的角色都会涉及到这个 Bug，您可以选择暂时不使用会报错的角色，等待更新。或者，您可以参考官方指导装配 libsaki 库，自行编译到可用的版本。

## 更新说明

### Feb 28, 2019

+ [Aislinn Wishart](#aislinn-wishart)
	+ 完全重写。
	+ 现在 Aislinn 被允许独占预测进张，只有极小概率或受他家能力影响时预测出错。
	+ 增加了预测进张方位、当前巡目预测进张和下一巡目预测进张的提示。
	+ **Aislinn 在测试中偶尔出现难以理解、难以复现的崩溃，如果您在使用中遇到相同问题，请保存截图和错误报告并联系我。**
+ [宮永咲](#宮永咲)
	+ 新增角色。
	+ **宮永咲是一个未完成的角色，亟待提出有效算法和改进 API 来完善她。在此之前，只提供现有的解决方案。**

## 人物列表

+ [高鴨穏乃](#高鴨穏乃)
+ [天江衣](#天江衣)
+ [妹尾佳織](#妹尾佳織)
+ [Aislinn Wishart](#aislinn-wishart)
+ [宮永咲](#宮永咲)

## 高鴨穏乃

> 踏过现实中修行的山路  
> 越过尘世间山谷的深处  
> 在那前方的  
> 是深山幽谷的化身

+ 深山之主
	+ 削弱其他三家能力对本局配牌的影响。随着局数增加，能够影响更强的能力和进行更大幅度的削弱。
	+ 使其他三家进张趋于混沌。随着局数增加和牌山深入，其他三家的摸牌结果将愈发难以预测。
	+ 使自己的进张变好。随着局数增加和牌山深入，这个能力将益发明显。

## 天江衣

> 真舒服的风呢  
> 衣喜欢这个季节  
> 不太冷也不太热  
> 新绿的光辉  对夏天的期待高涨  
> 每年的这个时期好像都在变短  真是遗憾  
> 母亲常常这么说  
> 长期的自我实现得不到幸福和快乐  
> 幸福只存在于刹那之间  
> 想分享这些的心向往着爱和娱乐  
> 但是  麻将做不到这些  
> 麻将未必能让四个人分享快乐  
> 和衣打牌的大家  都露出了是像看到了世界末日一样的表情  
> 衣因此  又独自一人被留下来了 

+ 魑魅魍魉
	+ 使其他三家在手牌达到一向听以后进展停滞。
		+ 岭上和鸣牌不受作用。
	+ 容易在早巡直击和牌。
+ 海底捞月
	+ 听牌的下一巡摸牌前将一枚和牌沉入牌山底部，当有人到达海底时取出。
		+ 可以感知和牌残枚不足的情形。
		+ 完成换听的下一巡摸牌前，重复发动此技能。
			+ 此前被沉入海底的和牌，除非受到他家能力作用，将永远沉底。
	+ 容易以鸣牌控制海底方位，相应的，到达海底方位后，他家不容易以鸣牌错开。

## 妹尾佳織

> 三个一堆，三个一堆……  
> 啊，门清自摸对对和。

+ Beginner's Luck
	+ 乱打时牌运变好。
		+ 退向听切张、不进向听切张、他家立直打生张、晚巡打生张等皆可能触发此技能。

## Aislinn Wishart

> “……”  
> （举起画板）

+ 绘制理想
	+ 每局摸第一张牌前，确定接下来 13 巡没有发生鸣牌的情形下自己的进张。
		+ 鸣牌并不会改变真实的进张顺序，他家会取代 Aislinn 获得预测的进张。
+ 快速听牌
	+ 没有被鸣牌错开的情况下，Aislinn 有较大概率会在 13 巡内听牌。

## 宮永咲

> 麻雀って、楽しいね！

+ 岭上开花
	+ 容易做出碰和杠。
	+ 存在碰副露并有杠材剩余的情况下，容易摸到杠材。
	+ 从岭上容易摸到有效牌。
+ 牌风
	+ 容易摸到西风