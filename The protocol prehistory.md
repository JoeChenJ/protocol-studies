# 以太坊的历史背景

> “英雄之所以成为英雄，是因为他们的行为具有英雄气概，而非因为他们取得了胜利或失败。” \
> — Nicholas Taleb

本文探讨了以太坊的发展脉络，赞颂了那些凭借勇气、创造力以及纯粹的叛逆精神对其产生深远影响的英雄们。

以太坊起源于早期互联网的开放精神，其设计理念深受 Unix 系统“专注于一件事并将其做好”这一理念的影响。由 GNU/Linux 所体现的自由开源运动的兴起，再次确认了软件领域的开放标准。与此同时，公钥加密技术的重大突破以及“密码朋克”（cypherpunks）对其的倡导，为像比特币这样安全、透明且去中心化的系统奠定了基础，而比特币最终启发了以太坊构建一个无国界、自主主权的数字经济平台的愿景。

> “倘若你审视一下那些在比特币领域早期阶段有所涉足的人士，他们过往的经历（如果有的话）大多源自开源软件领域——比如 Linux、Mozilla 以及 cypherpunk 邮件列表。”\
> — _Vitalik Buterin, 以太坊的联合创始人。_

## 信息高速公路

从1969年作为一个冷战项目（[ARPANET](https://en.wikipedia.org/wiki/ARPANET)）的微小开始，互联网已经发展成为一种前所未有的全球现象。

> “互联网的普及速度超过了之前的所有其他技术。在5000万人收听收音机之前，收音机已经存在了38年；电视花了13年才达到这个标准。第一个个人电脑套件问世16年后，有5000万人在使用它。一旦它向公众开放，互联网在四年后就跨越了这条线。”\
> — [新兴的数字经济，（1998年7月）。](https://www.commerce.gov/sites/default/files/migrated/reports/emergingdig_0.pdf)

![1989年至2021年的互联网连线地图。](img/overview/information-superhighway.gif)
**1989年至2021年的互联网连线地图。 [来源：《纽约时报》](https://www.nytimes.com/interactive/2019/03/10/technology/internet-cables-oceans.html)**

它最初只是少数几个机构的研究工具，现在连接了全球数十亿人，打破了地理边界，促进了曾经不可思议的人类互动。


> “国界只是信息高速公路上的减速带。”\
> — Timothy May, Cypherpunk.

## Unix和贝尔实验室


Unix起源于简化[MULTICS]（https://en.wikipedia.org/wiki/Multics）复杂性的努力，MULTICS是20世纪60年代一个雄心勃勃的大型操作系统项目。由于MULTICS变得难以控制，一个包括AT&T贝尔实验室的[Ken Thompson]（https://en.wikipedia.org/wiki/Ken_Thompson）和[Dennis Ritchie]（https://en.wikipedia.org/wiki/Dennis_Ritchie）在内的小团队试图创建Unix——一个更模块化、更简单和可组合的替代方案：

> “在某种程度上，我意识到我距离操作系统只有三周的时间。我需要一个编辑器、汇编器和内核覆盖层——就叫它操作系统吧。一周，一周，一周，我们就有了Unix。”\
> — [_Ken Thompson 在一场采访中提到_](https://www.youtube.com/watch?v=EY6q5dv_B-o)

1972年，丹尼斯还写了《影响力》 [C 语言 ](<https://en.wikipedia.org/wiki/C_(programming_language)>).

![Ken Thompson 和 Dennis Ritchie](img/overview/ken-thompson-dennis-ritchie.jpg)
**Ken Thompson 和 Dennis Ritchie.**

贝尔实验室是本世纪最具决定性的技术构件无与伦比的孵化器：

> “你不可能去商店买到贝尔实验室的创新产品，但它深藏在其他东西里面；这是通信基础设施不可或缺的平台创新。” \
> — Jon G., 创意工厂

> 🎦 观看: [Jon talk about innovations at Bell Labs.](https://www.youtube.com/watch?v=OJsKgiGGzzs)

在很多方面， [Ethereum functions](https://ethereum.foundation/infinitegarden) 就像一个开放的贝尔实验室。
Unix引入了一些概念，比如分层文件系统、shell作为命令行界面、可以组合起来执行复杂任务的单一用途实用程序。
这些基本原则奠定了后来被称为UNIX哲学的基础——在软件设计中支持简单、灵活和可重用性。

今天，UNIX及其衍生物继续支撑着现代计算的大部分，影响着从Linux和macOS这样的操作系统到永恒的软件开发原则的一切。

> 🎦 观看: [ Unix纪录片。](https://www.youtube.com/watch?v=tc4ROCJYbm0)

Unix遗产展示了一小群人可以通过软件对世界产生的深远影响。

## 我们能保守秘密吗？

自人类文明诞生以来，秘密传递信息的需要一直是人类的追求。从商人隐藏商业秘密到间谍和传递关键信息的军方，密码学发挥了至关重要的作用。早期的方法通常使用相同的密钥进行加密和解密，这使得安全的密钥分发成为一个噩梦：

> “对于一个没有军事通信经验的人来说，制造、登记、分发和取消密钥的问题可能显得微不足道，但在战时，交通流量甚至会让信号工作人员感到吃惊。” \
> — [David Kahn在 **the codebreakers** 中写道](https://en.wikipedia.org/wiki/The_Codebreakers)

如果密钥落入敌人手中，消息就会变得脆弱。在第二次世界大战中，数学家艾伦·图灵（https://en.wikipedia.org/wiki/Alan_Turing）和他的团队破解了一个复杂的德国密码——[Enigma machine](https://en.wikipedia.org/wiki/Enigma_machine)，这一点显而易见。他们的成功极大地改变了战争的结果。

！[ 艾伦·图灵的雕像和谜机。]（img/overview/ Alan - Turing .jpg）
**艾伦·图灵和英格玛机的雕像。**

你如何在素未谋面的人之间安全地远距离交换密钥？批评者认为密码学注定要依赖信任：

> “几乎没有人会相信，发明一种能妨碍调查的秘密写作方法不是一件容易的事。然而，我们可以断言，人类的聪明才智无法编造出一种人类聪明才智无法解决的密码。”\
> — Edgar Allan Poe

从1974年到1978年，Poe 的一系列发明证明他错了。

1974年，[Ralph Merkle]（https://en.wikipedia.org/wiki/Ralph_Merkle）设计了[Merkle’s Puzzles]（https://en.wikipedia.org/wiki/Merkle%27s_Puzzles）——一种初始方法，允许双方通过交换消息就共享秘密达成一致，即使他们事先没有共同的秘密。

两年后，1976年，默克尔的工作启发了[Whitfield Diffie]（https://en.wikipedia.org/wiki/Whitfield_Diffie）和[Martin Hellman]（https://en.wikipedia.org/wiki/Martin_Hellman）发表了他们具有历史意义的论文[ “密码学的新方向” ](https://ee.stanford.edu/~hellman/publications/24.pdf)，介绍了[Diffie - Hellman 密钥交换算法]（https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange）。这种方法在数学上明显比默克尔的谜题更鲁棒——催生了不可靠的加密。

![Whitfield和Martin发表了《密码学新方向》](img/overview/new-direction-in-cryptography.jpg)
**Whitfield和Martin发表了《密码学的新方向》。**

在接下来的1977年，计算机科学家们 [Ronald Rivest](http://amturing.acm.org/award_winners/rivest_1403005.cfm), [Adi Shamir](http://amturing.acm.org/award_winners/shamir_2327856.cfm)， 和 [Leonard Adleman](http://amturing.acm.org/award_winners/adleman_7308544.cfm) 开发了[RSA密码系统](<https://en.wikipedia.org/wiki/RSA_(cryptosystem)>) - 在一篇题为[" a Method for getting Digital Signatures and public key Cryptosystems"](https://people.csail.mit.edu/rivest/Rsapaper.pdf)的论文中，首次实现了公钥密码体制。里维斯特把这篇论文的副本寄给了数学家马丁·加德纳。马丁被深深打动了，他打破了通常几个月前就计划好专栏的规矩，很快就写好了，准备在[1977年8月发表](https://web.archive.org/web/20230728001717/http://simson.net/ref/1977/Gardner_RSA.pdf)。《科学美国人》杂志：
![Len, Adi,Ron 在 CRYPTO '82，以及 Martin Gardner 现在著名的文章](img/overview/rsa-in-scientific-american.jpg)
**Len, Adi, Ron 在 CRYPTO '82，和 [现在很出名的文章](https://web.archive.org/web/20230728001717/http://simson.net/ref/1977/Gardner_RSA.pdf) 由 Martin Gardner 发表在《科学美国人》**

在文章中，Gardner提供了一个RSA-129密码，并向第一个解决它的人提供100美元：
![MIT 的 RSA 挑战](img/overview/rsa-challenge.jpg)
**MIT 的 RSA 挑战**

1994年，一群计算机科学家和志愿者 [破解密码](https://en.wikipedia.org/wiki/The_Magic_Words_are_Squeamish_Ossifrage) 把钱捐给了 [自由软件基金会。](https://www.fsf.org/) 这项工作强调了一个关键点：密码学的完美安全性是一种错觉。像RSA这样的加密方法正在不断发展，特别是在预测[量子计算机](/wiki/Cryptography/post-quantum-cryptography.md)的时候。
