进阶教程
========

本章节主要介绍游戏的主要内容 Deploy, Link, Field 以及摧毁敌对 Portal 等相关内容。这部分是玩家在 L3 之后进行的主要游戏内容。  

Deploy Resonator
--------------

无论是看到一个白色的无主 Portal，或者是摧毁了敌对阵营对 Portal 的占领，通常都会选择 Deploy Resonator 以 Capture Portal。而之后的 Link 也要求两侧的 Portal 必须 Deploy 所有的 Resonator。  

Deploy 操作要求 Portal 必须在玩家脚下的黄圈范围内，选择 Portal，点击 Deploy Status后，在新的界面里点击空的槽后选择下方对应的 Resonator 即可。每个玩家在每个 Portal 部署的不同等级的 Resonator 数量上有限制，具体参见 [Ingress 道具介绍][ingress_items_intro]。  

[图片位置]  


Deploy Mod
----------

玩家可以给同阵营的 Portal Deploy Mod，操作方法类似于 Resonator，区别主要在于选择完 Portal 后点击的是 Mod Status，关于各种 Mod 的功能和使用，参见 [Ingress 道具介绍][ingress_items_intro]。  

对每一个 Portal，每个玩家最多只能同时 Deploy 2个 Mod。  

Link
----

Link Portal 是建立 Field 的前提，建立 Link 有一定的限制条件，具体如下  

+ 建立 Link 的 Portal 必须均归属己方阵营  
+ 无论起始和结束，Portal 必须插满 Resonator（即每个 Portal 均拥有8个 Resonator）  
+ 起始 Portal 必须在 Link 建立者的黄圈范围内，目标 Portal 必须在起始 Portal 的 Link 范围内（在 Deploy Status 页面可以看到）  
+ 建立者需要持有目标 Portal 的 key，且每次 Link 都会消耗一把，关于 key 的积累，参见 [Ingress 道具介绍][ingress_items_intro]  
+ 试图建立的 Link 不能穿越任何已经存在的 Link 和 Field  
+ 不能从 Field 内部的 Portal 向其它Portal Link  
+ 任何 Portal 最多只能 Link 到 8个其它 Portal，但被 Link 不受限制  

确认满足以上条件后，点开起始 Portal 的详情页面，在左下方选择 Link 按钮，稍作等待后便会在地图上显示附近可以 Link 的Portal，也可以在右侧点击 key 标志展开后选择自己拥有 key 且满足条件的 Portal。如果 Link 失败，下方会显示失败原因，可据此排除问题。  

[图片位置]  

[ingress_items_intro]: https://github.com/GhostFlying/ingress-tutorials/blob/master/ItemsIntro.md
