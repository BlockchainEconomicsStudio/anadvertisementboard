## 一块广告牌 An Advertisement Board

***关于本实验背景的一点简单介绍***
https://docs.google.com/document/d/1UeqzCrml9HQFg7eK8k1xcTtB_SKRSecnR9SkZcp0JTo/edit?usp=sharing

***一块广告牌————二十一世纪的共享广播站***

by Mable Jiang

June 5, 2019

之前海外有一个关于哈勃格税（Harberger Tax）的实验项目，叫[《此艺术品永远出售》（This Art is Always on Sale）](https://thisartworkisalwaysonsale.com/)，是由一个数字艺术家为一个代表“this art is always on sale”这段文字的条形码所制成的数码艺术提供的竞拍和艺术家征税平台。参与竞拍的人需要支付上一任拥有者所给出的标价，标出卖给下一任买家的价格，并往项目里另外预存入一定数额的押金用于之后的税款支付（标出价格的5%）。当押金余额不足以支付项目的税款时，智能合约会强制赎回艺术品，此时由于没有下一任买家，价格归零，重新开始。项目的主旨是对哈勃格税对物权与社会关系（艺术、艺术家与购买者之间）的影响进行探索。

艺术家征税？这个概念听起来感觉不太好理解，那么让我们先从哈勃格税开始。

首先，这个税的核心规则有两点：
1. 为私人拥有的财产公开一个标价，并每年提交根据该估价某个百分比的税；
2. 市场上的任何人都可以按该公开标价从你手中购买该财产。

其核心的制衡因素在于：标价开高了，交税要交更多；开低了，别人可以轻易买走你的财产。这两点迫使每个理性人（假设你不想多交税，假设你不想被人轻易买走）趋向合理范围估价。

听起来很简单，实践上会遇到各种各样的挑战，因此尽管一直被讨论，却从没有哪怕是小范围真正走进人们的生活。首先一点就是它在实体经济中难以操作：当一个人拥有对某个实体物品的控制权，很难真正意义上地让其他人“强行买走”。其次则是它的价值并不那么直观体现，尤其是对于一直需要增加投入一段时间后才能显著提升价值的资产，如果不断的投入使得资产价值增加，每年标价的上升使税收变高，而别人又能轻易地在这过程中从投入开发者手中买入，那必然导致的结果就是投资收益减少，潜在开发者的初始投资意愿降低。

当然，它吸引人的地方则是体现在它对于资源分配效率的改善。试想一下，在人口爆炸、共享经济的今天，到底有多少物品是你真正需要永久拥有物权 v.s. 你愿意仅在一段时间内拥有使用权的？哈勃格税所代表的“部分共同所有权”，可以说是“小孩子才谈选择，成年人全部都要”思维的一种实践。

关于哈勃格税的更多探讨和阅读，橙皮书的存档里有很多不错的文章：<https://orange.xyz/tag/5>。

上述的背景介绍希望能够帮大家更好的理解我们 This Art is Always on Sale 的分叉实验——[一块广告牌](http://anadvertisementboard.com/)。

为什么要把艺术品替换为广告牌？
- 首先，哈勃格税，在我们看来，与其说是一段时间的所有权，不如更恰当说是一段时间的使用权。拥有艺术品一段时间所给艺术家支付的税，可以理解为拍卖者对于艺术家的资助（patronage），但在拥有广告牌的期间能够随意更改上面的内容，则更加体现了“一段时间使用权”的本质。
- 其次，广告牌带有的传播属性，会给系统引入更多元的关注，探索更广泛的社会影响。广告牌所承载的价值将会部分基于本身的流量，相比于艺术品其标价更容易被评估。
- 再者，税负本质应当是给更大的群体创造价值，广告牌在于它能够利用自身的流量传播信息的价值，因此为广告牌本身的运营征税是合情合理的。

关于本广告牌：
《一块广告牌》用崭新的方式探索使用权的问题。以太坊网络将确认数字艺术品所有权的稀缺性变为可能，同时用全新的方式定义了经济与虚拟内容所有权。受《激进市场》（Radical Markets）一书影响，这个作品遵循了稍作改动的哈勃格税物权体系，即仅由作品运营者征税。

参与到这个实验里，你只需要：
1. 根据上一任买主定义的价格（初始为0）拍下广告牌
2. 预存一定数量的以太坊作为抵扣税金
3. 定义给下一任买主的标价
4. 在拥有广告牌期间随意更改上面文字的内容，可以是市场预测，也可以是表白，甚至是你想跟大家分享的俳句、小诗

通过这一实验，我们试图提出以下问题：
- 广告牌的价值怎样被购买者定义，或者说广告牌拥有者如何定价？是通过上面的文字本身创造的价值（经济价值与审美艺术价值），还是潜在进入的大流量？
- 广告牌提供的更弹性的转手率可能性，和由此带来的广告牌上的创作被更多人拥有的可能性，是增加还是减少了它的价值？
- 这样一个平台，能否成为没有IP的个人在特定时间段宣传的好选择 ，成为真正的“一块广告牌”？
- 这种广告牌永久可拍卖的市场体制和由此产生的投机和价格变化是否改变创作者本身的态度，它是降低了创作门槛（e.g.资金来源），还是让大家对投入变得更谨慎？在参与的过程中，投机者和创作者的身份，是否能够区分？
- 这个永久可拍卖的广告牌是否能让人意识到人类生活的方方面面已经潜移默化地进入不断的可卖的过程？

技术层面上来讲，本作品运用了以太坊智能合约技术,是开源的，它选择了适当的通证标准ERC721来展示和确权。广告牌的名称叫 advertisement，简称ADS。

你可以在如下网址随意产生本项目的分叉和创造你自己版本的广告牌：
<https://github.com/anadvertisementboard/anadvertisementboard>

给这个作品提供灵感的原《此艺术品永远出售》GitHub 地址：
<https://github.com/simondlr/thisartworkisalwaysonsale>。

我们很期待看到在这场实验中展示出来的预期与非预期的市场反应。

请开始你的表演。

**项目特别鸣谢：程序员 Mino**


--------------------------------------------------------------------


***用哈勃格税卖广告，我们迈出了网站token化的第一步***

by Nick Wu

June 27, 2019

原文链接（含图）：https://mp.weixin.qq.com/s/L162MmrXQModSW3uJA7RiA


去年4月，以太坊创始人V神(Vitalik Buterin) 在个人博客中深度探讨了一个叫做“哈伯格税（Harberger taxes）”的经济理论。

他认为该理论“是对政治经济学的另一种新奇又有趣的解读”，并且可以和区块链的通证设计有着很好的结合。

那么哈勃格税究竟是什么？这个税的核心规则有两点：

1. 为私人拥有的财产公开一个标价，并每年提交根据该估价某个百分比的税；

2. 市场上的任何人都可以按该公开标价从你手中购买该财产。

其核心的制衡因素在于：

*标价开高了，交税要交更多；
开低了，别人可以轻易买走你的财产。*

这两点迫使每个理性人（假设你不想多交税，假设你不想被人轻易买走）趋向合理范围估价。

听起来似乎简单，在实践中会有价值无法直观体现等重重困难。但这一概念激起了很大范围的讨论，也有人开始进行各种各样的实践。

01

去年9月，V神和哈佛大学Zoë Hitzig及《Radical Markets》一书作者Glen Weyl共同撰写了论文《自由激进主义:社会基于社群中立的正式规则》，进一步探讨哈伯格税的应用。

今年3月，南非数字艺术家Simon de la Rouviere 基于哈勃格税的理念和以太坊，以ERC 721的形式做了一个数字艺术品，意在探索哈勃格税在艺术领域的应用。
网址：https://thisartworkisalwaysonsale.com/

该艺术品目前的价格已经升至240以太坊（约50万元人民币）。

这个月初，BES (beslab.xyz）区块链实验室分叉了该项目，将Harberger税应用到“线上广告”这一资产类别上，并在经济机制，应用场景，社区治理形式上做了进一步的创新，项目名为“一块广告牌”。

“一块广告牌”上线后，短短几天时间里，就被换手多次，内容大多是对某个人的祝福。被祝福的人包括BES 创始人Jade、DappReview 创始人 Vincent、链圈斯嘉丽等等，很是温馨和逗趣。
  
02
  
“一块广告牌”这个有趣的DApp（去中心化应用）对我来说犹如一股清流，在浮躁的币圈不断的带来小温馨小快乐。

《Radical Markets》作者Glen、数字艺术家Simon等海外学者，也在持续的关注这个有趣的小实验。

广告牌用于个人情感的表达固然颇有行为艺术的感觉，这也同时这也启发我去思考物权、使用权与社会关系的影响。

基于哈勃格税的广告牌设计有没有可能被用于商业项目？

网站的广告位该如何定价？

目前一对一商务接洽售卖的方式是否最有效率？

有没有可能借助哈伯格税以一种全新的方式售卖或出租网站广告位？

网站价值该如何评估？是否可以被token化？

想了很久，我发现这些问题光靠想是想不明白的。

山不过来，我就过去。
既然没有人去实践，那我们就自己来。

03

我们买下了这块广告牌的所有权，并通过我们DOGIgames.com的网站给这个广告牌赋予价值：

具体玩法如下：

1、我们把网站左侧的展示空间留给“一块广告牌”网站。
 
2、在“一块广告牌”网站上购买该广告牌的玩家，可以获得在DOGIgames.com网站首页广告展示的服务，广告展示至2019年7月31日。

点击阅读原文或访问以下网站，均可到达访问网站：
http://anadvertisementboard.com/#/main

3、购买该广告牌后，你可以随意将该广告牌以任何价格进行出售或转让，但转让后广告展示时间不变。

4、请购得广告牌的广告主联系我们，以更新在DOGIgames.com网站上展示框的内容，刊登内容需符合相关国家的法律法规。

5、广告牌的初始价格为2.5ETH，购买后可以随意修改价格。

6、如需帮助请随时联系我们。

在文章发出前我们得到了一个意外惊喜，在我们推出这个玩法之后，《Radical Markets》作者Glen在Twitter上做了回复：
https://twitter.com/glenweyl/status/1143873343923400704

很高兴能参与到这样一场关于哈勃格税的社会实验，并与我们DOGIgame.com的自身媒体属性找到了一个很好的契合点，未来这场实验将会如何推进，我们会进行持续的跟踪和报导，请继续关注。


文章里涉及的一些参考资料及其他与哈勃格税相关的资料：

1、论文链接：
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3243656
2、V神medium发文： 
https://medium.com/@VitalikButerin/liberation-through-radical-decentralization-22fc4bedc2ac
3、橙皮书上亦有中文翻译和很多很好的讨论
https://orange.xyz/tag/5
4、一块广告牌网站地址：
http://anadvertisementboard.com/#/main
5、GitHub：
https://github.com/anadvertisementboard/anadvertisementboard
6、微信文章：
Mable 2019 <一块广告牌——二十一世纪的共享广播站？>, 
https://mp.weixin.qq.com/s/NCjncWZAMEn-lljXKRMM6w
7、Harberger Tax卖艺术品：
https://thisartworkisalwaysonsale.com/
8、卖艺术品的medium：
https://medium.com/@simondlr/this-artwork-is-always-on-sale-92a7d0c67f43
9、卖艺术品的GitHub：
https://github.com/simondlr/thisartworkisalwaysonsale
10、橙皮书相关文章：
https://orange.xyz/tag/5
11、Vitalik Buterin 关于Radical Markets 和Harberger taxes 的介绍：
 Vitalik  2018, ‘On Radical Markets’  Vitalik Buterin's website, 
https://vitalik.ca/general/2018/04/20/rad ical_markets .html
12、Harberger Tax和Radical Markets的书：
Eric A. Posner & E. Glen Weyl 2018, <Radical Markets: Uprooting Capitalism and Democracy for a Just Society>, Princeton University Press, 
https://www.amazon.com/Radical-Markets-Uprooting-Capitalism-Democracy/dp/0691177503



---------------------------------------------------------
***广告牌进度讨论会议笔记***

我们把围绕广告牌的每一次讨论记录在了google文档上，方便开源社区随时翻阅+评论：

https://docs.google.com/document/d/1rl9alCS56aZRf0ouc4fWKJXmUsgSA9s3Sz6iM6peyrk/edit?usp=sharing


---------------------------------------------------------
***About Us***

**本实验由BES (beslab.xyz）区块链实验室和DOGI区块链游戏媒体（DOGIgames.com）共同发起。**

**Blockchain Economics Studio （BES）** 是一个专注于发现和构建区块链科技未来经济的工作室。我们同创业者、开发者、投资人一起合作从零开始孵化产品或服务。 目前项目包括虚拟货币资产管理平台、虚拟机构交易终端、非可替代性资产、PoC 共识协议以及区块链应用程序等。 我们的研究重点主要在区块链世界的新经济模型。 我们相信区块链会成为数字时代，人与机器新型合作的支柱产业，我们也希望能够连结人们及他们的创意来实现这一目标。

网站：https://beslab.xyz/
twitter：https://twitter.com/BES_zen

**DOGIgames是一家专注区块链游戏的媒体。**我们认为区块链将对游戏带来深远的变革。虽然我们无法预测这种变革发生的具体时间，但我们相信他必将发生。DOGIgames愿意发掘并传播全球区块链游戏从业者在推动变革的洞见、创新、探索、成功和以及失败。DOGIgames也致力将中国区块链游戏行业的进展传播到全球各个角落。
网站：https://www.dogigames.com/

**本项目早期贡献者包括：**
Jade - 连续创业者，建立 BES 的目的是连接区块链技术与现实价值。坚信问题比答案更重要，希望以独立开源组织的形式推动自己关心问题的解决。热爱哲学，统计学，神经科学，人工智能，长年瑜伽及冥想。

Mable - 毕业于哥伦比亚大学，获艺术史与统计学士学位，相信美是统一技术与艺术的矢量。传统金融与互联网战略出身，现任一家早期风投任合伙人。热爱通过独立采访者的方式让社会接触到多样的思考，致力于探索生活、艺术与哲学的有机结合形式。

小胖 - 前 Apple Store 员工，因偶遇比特币而经历了更加丰厚的生命，认同疯狂区块链世界里理性认知的力量，坚信区块链将带来更好的世界，也坚信 BES 会成为更好世界的一部分。

Nick – 区块链游戏生态建设者。投机于股市和币圈，专注中短线趋势操作。多国注册会计师，擅长泡沫中洞察真相。对电子游戏和有趣的灵魂没不了抵抗力。

Liu Ya – AjoyLab 区块链游戏制作人。作为创业者开发的游戏曾进入苹果畅销榜Top 20， 产品累计超过1,000 万的下载量。曾在诺基亚担任高级软件工程师， 拥有丰富的从系统底层到应用层的开发经验。

Mino - DApp 产品经理。探索区块链技术与现实之间的结合的场景，相信去中心化的应用将进一步改变人们的生活方式和生产关系。世界乱糟糟，待我去改造。

垚垚 – 需要灵感创作的前端工程师


