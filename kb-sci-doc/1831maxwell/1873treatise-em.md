---
title: 1873电磁通论摘录
type: freebase
tags:  ONE/电磁/麦克斯韦
---

《电磁通论》，麦克斯韦收集当时电磁发现和电磁理论，重点是法拉第的电磁理论，用数学的方法总结了：
- 静电学
- 动电学
- 磁学
- 电磁学

四个方面的电磁理论，重点是用数学方法构建了电磁模型。

《电磁通论》重点以电磁媒介论（以太论）推导电磁模型，证明以太假说和直接超距作用假说所引起的能量在数学上是等价，并在以太假说的基础上发表了“动态电磁场理论”，预测电磁波的存在。

由于通论中数学论证较多，没有很好的微积分基础是看不太懂的，但除开公式部分，其对电磁光的概念的论述还是非常值得学习理解的。

这里摘录通论中核心观点相关论述。通论除了正常的章节目录，从头到尾用统一数字编号做了分段，共计866段，摘录中可以按段找书中对应内容。

这里中文内容摘录自《科学素养文库·科学元典丛书(第2辑)-电磁通论-[英]麦克斯韦.pdf》，但翻译的直不咋地，章节和编号中英版都是一样的。

中文翻译中用了较多胁强这个词，这里查了一下想着概念：

胁强：应力

机械胁强：机械应力

胁强：条长度为L，横截面积为 A 的金属丝，在力 F的作用下伸长 ∆L，其中F/A 叫做胁强，其物理意义是金属数单位截面积所受到的力;   ∆L/L叫做胁变，其物理意义是金属丝单位长度所对应的伸长量，其中 ∆L 是一个小量。

# 绪论 量的测量

注：这部分主要讲了物理量的定义，这部分比较重要，也比较枯燥。如果想深入理解数学模型是要好好读的。

# 第一编 静电学

## 第一章 现象描述

注：这里主要讲了各种静电现象和常见静电理论，没有什么数学内容，可以好好读读，方便理解电现象。

### 本论著的计划

注：这里可以重点读读，表达了麦克斯韦对以太假说和直接超距作用假说的认识

59.] 在本书中,我打算首先解释普通的电作用理论。这种理论把电作用看成只依赖各带电体和它们的相对位置,而并不考虑可以出现在中间媒质中的任何现象。用这种办法,我们将建立平方反比定律、势论,以及拉普拉斯的和泊松的方程。其次我们将考虑一个带电导体组的用一组方程联系起来的电荷和电势,各方程的系数在我们现有数学方法不能适用的那些事例中可以被假设为由实验来确定,而由这些方程,我们将确定在不同的带电体之间作用着的机械力。

然后我们将考察某些普遍定理;利用这些定理,格林、高斯和汤姆孙曾经指示了求解电分布问题的条件。这些定理的一个结果就是,如果泊松方程被任何一个函数所满足而且这个函数在每--导体的表面上具有该导体的电势的值,则这个函数就代表每一个点上的体系的实际电势。我们也将导出一种方法来找出可以有精确解的那些问题。

在汤姆孙定理中,体系的总能量用在各带电体之间的整个空间中求的某量的积分表示了出来,也用只在带电表面上求的积分表示了出来。于是这两个表示式的相等就可以物理地加以解说。我们可以把带电体之间物理关系或是设想为中间媒质的状态的结果或是把它设想为带电体之间一种直接的超距作用的结果。如果我们采用后一种观念,我们就可以确定作用定律,但是我们却绝不能进一步思索作用的原因。另一方面,如果我们采用通过媒质的作用的观念,我们就会被引导着来探索媒质之每一部分中的作用的本性了。

由定理可见,如果我们应该到电介媒质的不同部分中去寻求电能的存身之处,任一小部分媒质中的能量就必将依赖于该处合电动强度的平方乘以一个叫做媒质之比感本领的系数。

然而,当从最普遍的观点来考虑电介质的理论时，一个更好的作法却是把任意点上的电动强度和该点上的媒质的电极化区分开来,因为这些有向量虽然是互相联系着的，但在某些固体物质中却不是沿着相同的方向的。单位体积的媒质电能量的最普遍表示式,就是电动强度和电极化之积乘以二者夹角的余弦的二分之一。在所有的流体媒质中，电动强度和电极化都是同方向的和具有恒定比值的。

如果我们按照这一假说来计算存在于媒质中的总能量,我们就将发现它等于按照直接超距作用假说而求得的由各导体的电荷所引起的能量。因此这两种假说在数学上是等价的。

现在,如果我们根据把所观察到的带电体之间的机械作用看成通过并借助于媒质而进行的那一假说来着手考察媒质的机械状态,我们就会像在一个物体通过绳子的张力或棍子的压力而对另一物体作用以力的那种习见的例子中一样,发现媒质必然处于一种机械胁强的状态之中。

正如法拉第所指出的那样,这种胁强的本性就在于,一个沿力线方向的张力和一个沿一切垂直于力线的方向的相等压力相结合。这些胁强的量值正比于单位体积的电能量，或者换句话说,正比于合电动强度的平方乘以媒质的比感本领。

这种胁强分布，是唯一可以和观察到的对各带电体的机械作用相一致而且也和观察到的各带电体周围流体电个质的平衡相一致的一种分布。因此,我曾经想到，假设这种胁强状态的实际存在并追索这一假设的推论，是科学程序中的有保障的一步。由于发现电张力一词是在几种含糊不清的意义下被使用的,我曾经力图把它的应用限制在我认为其中某些应用过它的人们所曾设想的那种意义中，也就是用它来指媒质中导致带电体的运动并当不断增大时导致破坏性放电的那种胁强状态。在这种意义下,电张力就和一根绳子中的张力属于同一种类并用相同的方式来量度,而可以禁受某一张力而不能禁受更大张力的电介媒质就可以被说成有一定的强度,其意义正和一根绳子被说成有一定的强度时的意义相同。例如,汤姆孙曾经发现,在出现一个火花之前,常压常温下的空气可以经受住一个每平方英尺 9600 格令重的电张力。

60.] 根据电作用不是物体之间的直接超距作用而是借助于物体间的媒质来发生的作用的这种假说,我们已经推知这种媒质必然处于一种胁强状态中。我们也确定了胁强的特性,并把它比拟成了可以出现在固体中的那些胁强。沿着力线存在的是张力,而垂直于力线存在的是压力,各力的数值相等,而且每个力都正比于该点的合电动强度的平方。确立了这些结果,我们就作好了准备,可以迈出另外一步并对电介媒质的电极化的本性形成一个概念了。

当一个物体的元体积在相对的两面上获得相等而相反的性质时,它就可以说是被极化了。内部极性的概念可以用永磁体的例子来最好地加以研究,而且将在我们进而处理磁性时再来更详细地加以解释。

电介质的一个元体积的电极化是一种受迫状态;媒质被电动势的作用推入这种状态中,而当电动热取消时这种状态也不复存在。我们可以把它设想为是由我们称之为电位移的东西构成的,而电位移则由电动强度所引起。当电动势作用在一种导电媒质上时，它就在媒质中引起一种电流,但是,如果媒质是不导电的,或者说是一种电介质,电流就不能(长久地)流过媒质,而电就只能在媒质内部沿着电动强度的方向发生位移;这种位移的大小依赖于电动强度的量值,从而如果电动强度增大或减小,则电位移将按相同的比例增大或减小。

位移的数量用当位移从零增大到它的实际大小时穿过单位面积的电量来量度。因此，这就是电极化的量度。

电动强度产生电位移的作用和普通机械力产生弹性体之位移的作用之间的类似性是如此的明显,以致我曾经冒昧地把电动强度和对应电位移之比称为媒质的电弹性系数。这个系数在不同的媒质中是不同的,而且反比于每一媒质的比感本领而变化。电位移的变化显然就构成电流·。然而这种电流只有在电位移变化的过程中才能存在,而既然电位移不能超过一个一定的值而不引起破坏性的放电，这种电流也就不能像导体中的电流那样不受限制地沿着相同的方向继续流动。

在电气石和另一些热电晶体中,或许有--种电极化状态存在着;它依赖于温度,但不需要一个外电动强度来引起它。假如一个物体的内部是处于一种电极化的状态中的,它的外表面就将以一种方式逐渐变成带电的,以便在物体外面的所有各点上把内极化的作用中和掉。这种外表面上的电荷不能用任何普通的方法来探测,也不能用普通的使表面电荷放电的方法来消除。因此,物质的内极化将根本无法被发现,除非可以通过温度变化之类的方法来使内极化的数量增大或减小。这时外电荷将不再能够中和内极化的外部效应，从而-种表观电荷就会被观察到，正如在电气石的事例中那样如果一个电荷 e 被均匀地分布在-个球的表面上，则球周围媒质中任一点上的合强度和电荷e 除以该点到球心距离的平方成正比。按照我们的理论,这一合强度是和-.个沿从球心向外的方向的电位移相坐随的。

如果现在我们画一个半径为，的同心球面，则通过这一球面的全部位移 E将正比于合强度和球面积的乘积。但是合强度正比于电荷。而反比于半径的平方,而球面积正比于半径的平方。因此总的位移量 E 就正比于电荷 而和半径无关。

61.] 于是我们就得到我们所考查的这种理论的一个很惊人的推论,那就是,电的运动像一种不可压缩的流体的运动一样,使得一个假想的固定闭合曲面中的总量永远保持相同。初看起来,这一结果显得和一个事实直接抵触,那就是我们可以给一个导体充电然后把它引入闭合曲面之内。但是我们必须记得,普通的理论并不顾及我们已经考虑了的电介质中的电位移,而是只把它的注意力限制在导体和电介质的分界面的带电现拿上的。在带电导体的事例中。让我们假设电荷是正的,于是,如果周围的电介质向各力面延伸到闭合曲面以外,那就会出现电极化,伴随以整个闭合曲面上从内向外的电位移而在该曲面上计算的位移的面积分就将等于曲面内的导体上的电荷。

于是，当带电导体被移人闭合曲面之内时,立刻就会有一个等于导体电荷的电量从内向外通过该曲面，从而曲面内的总电量就保持不变。

电极化的理论将在第五章中加以更详细的讨论，而且它的一个机被例证将在第 334节中被给出,但是这种理论的重要性却只有当我们进人电磁现象的研究时才能得到充分的理解。

62.] 这种理论的特点是:

带电时的能量存在于电介媒质中,不论媒质是固体、液体还是气体,是浓密的还是稀薄的，甚至也可以是所谓的真空，如果它还能传送电作用的话。

任何媒质部分中的能量,是以一种叫做电极化的胁变状态的形式被储存的,电极化的数量依赖于空间中的合电动强度。

作用在一种电介质上的电动势,会引起我们所说的电位移,强度和位移之间的关系在最普遍的情况下属于我们在以后当处理导电问题时即将考虑的那一种,但是在那些最普遍的事例中,位移却和强度同方向。

由电极化引起的每单位电介质体积的能量,等于电场强度和电位移的乘积的一半如果必要则乘以二者方向之间的夹角的余弦。

在液体电介质中,电极化伴随以沿电感线方向的一种张力,以及沿和电感线相垂直的一切方向的一种相等的压力,单位面积上的张力或压力在数值上等于同一位置上的单位体积中的能量。

我们所设想的可以由电介质体积划分成的任一体积元的表面,必须被设想为带申的,而表面任一点上的面密度则在量值上等于向内计算的通过表面上该点的位移。如果位移是沿正方向的,则面积元的正面将带负电荷而其反面将带正电荷。当相邻的体积元被考患在内时,这种表面电荷通常将互相抵消,只有在电介质带有内部电荷的地方或在电介质的表面上是例外。

不论电是什么,不论我们怎样理解电的运动,我们称之为电位移的这种现象都是-种电的运动,其意义和电量通过导线的传送是一种运动的那种意义相同;其唯一的不同就是,在电介质中,有一种我们称之为电弹性的力,它反对着电位移而起作用,并当电动势被取消时迫使电荷返回原处;而在导线中,电弹性则一直是退让的,从而阻力就不是依赖于从它的平衡位置上被移动了的总电量,而是依赖于在给定的时间内通过导体的一个截面的电量。

在每一事例中,电的运动都服从和不可压缩流体的运动所服从的条件相同的条件那就是,在任何时刻,有多少电从一个任意的给定闭合曲面中流出,就有多少电流进该曲面中来。

由此可以推知,每一电流都必然形成一个闭合的回路。这一结果的重要性,当我们研究电磁现象的定律时就会被看到。

既然正如我们已经看到的那样,直接超距作用的理论和借助于媒质的作用的理论在数学上是等同的,实际的现象就既可以用这种又可以用那种理论来加以解释,如果当出现任何困难时就引用适当的假说的话。例如,莫索提曾经根据普通的吸引力学说导出了电介质的数学理论,他所用的方法只是在研究中对一些符号作出了电学的而不是磁学的诠释,而利用那些符号,泊松曾经根据磁流体的学说导出了磁感应的理论。莫索提假议在电介质内部存在一些小的导电单元,它们的相对的表面可以通过感应而带异号的电但就整体来看却不能失去和获得电,因为它们彼此之间是由一种不导电的媒质绝了缘的。这种电介质理论是和电的定律相协调的,从而可能实际上是对的。如果它是对的-种电介质的比感本领就可以大于但不能小于真空的比感本领。迄今还没有发现比感本领小于真空比感本领的一种电介质的实例,但是假如发现了这种实例,莫索提的物理学说就必须被放弃,尽管他的公式将仍然准确而只将要求我们改变其系数的正负号。

在物理科学的许多部门中,人们发现一·些形式相同的方程可以应用于肯定有着不同本性的一些现象,例如电介质中的电感应,导体中的电传导,以及磁感应。在所有这些事例中,强度和它所引起的效应之间的关系都是用一组种类相同的方程来表示的,因此,当其中某一课题中的一个问题已经解决时,该问题及其解就可以翻译成其他课题的语言，而新形式下的结果将仍然是对的。

## 第五章 两个带电体之间的机械作用

110.] 在空气或松节油之类的流体电介质中也存在这样一种胁强状态;初看起来，这一假说似乎和已经确立的原理相抵触,那原理就是,在流体中,压强在一切方向上都是相等的。但是,在从关于流体各部分的活动和平衡的考虑推出这条原理时,曾经不言而喻地认为流体中不存在我们在这儿假设为沿着力线进行的那样作用。我们所研究的这种胁强状态,是和流体的活动及平衡完全不矛盾的,因为我们已经看到,如果流体的任何部分都不带电荷,它就不会从它表面上的胁强受到任何合力的作用,不论那些胁强多么强。只有当一部分流体带了电时,它的平衡才会被它表面上的胁强所打乱,而我们知道在这种情况下流体确实倾向于发生运动。由此可见,所设的胁强状态并不是和流体电介质的平衡相矛盾的。

在第四章第 99a 节中研究了的 W 这个量,可以诠释为由于胁强的分布而出现在媒质中的能量。由该章的那些定理可以看到,满足在该章中给出的那些条件的胁强分布,也使 W 有一个绝对最小值。喏,当在任何一个位形下能量有极小值时,那个位形就是一个平衡位形,而且平衡是稳定的。因此,当受到带电体的感应作用时,电介质就将自动采取一种按我们所描述过的方式而分布的胁强状态@.

必须认真地记住,我们只在媒质作用的理论中迈出了一步。我们曾经假设媒质处于种胁强状态中,但是我们却没有用任何方式来说明这种胁强，也没有解释它是怎样被保持的。然而,在我看来,迈出的这一步却似乎是很重要的一步,因为它利用媒质各相邻部分的作用来解释了以前被认为只能用超距作用来加以解释的那些现象。


# 第三编 磁学

## 第二十六章 磁学的初等理论

如果一个物体的粒子具有一些和物体中某一直线或方向有关的性质,而且当物体保持着这些性质而被转动,以使这一方向反向时,如果粒子的这些性质相对于其他物体也反向,则按照这些性质来说,粒子就叫做极化的,而这些性质就叫做构成一种特定的极化。

例如,我们可以说物体绕一条轴线的转动就构成一种极化。因为,如果在转动继续进行中轴线方向被颠倒过来,则物体对空间来说将是向反方向转动的。

通有电流的一个导电粒子可以说是极化的，因为,如果把粒子倒过来,而粒子中的电流则相对于粒子来说仍沿相同的方向在流动,则电流在空间中的方向将是反了向的。

简短地说,如果任何一个数学量或物理量具有在第 11 节中定义了的那种矢量的性质,则这种有向量所属于的任何一个物体或粒子就可以被说成是“极化的”,因为在有向量的两个方向或两个极上，它是具有相反的性质的。

例如,地球的两极是和它的转动有关的，从而各极就具有不同的名称。

### "磁极化"一词的意义

382.] 当把一个物体的各粒子的状态说成磁极化时,我们的意思就是，一个磁体所能分成的那些最小部分中的每一个部分,都具有某些和通过粒子的一个确定方向有关的性质,该方向叫做粒子的“磁化轴”,而且,和这个轴的一端有关的那些性质,是与和另一端有关的那些性质相反的。

指定给粒子的那些性质,是和我们在整个磁体中观察到的那些性质同一种类的,而在假设各粒子具有这些性质时,我们所肯定的只是我们可以通过把磁体打成小块来证明的情况，因为我们发现其中每一小块都是一个磁体。

# 第四编 电磁学

## 第三十四章 电磁力

486.] 如果一个细长而柔硬的管性磁体被放在一个电路的附近,则磁管的北极和南极将倾向于沿相反的方向而绕着导线运动,而且,假如它们可以自由地服从磁力,则磁体最后将绕着导线缠成一个闭合的线圈。假若能够得到只有一个极的磁体,或得到磁极的强度不相等的磁体,则这样一个磁体将绕着导线而向一个方向不停地转动,但是,既然每个磁体的极事实上是相等而反号的,这样的结果就绝不会发生。然而,通过使磁体的一个极可以绕着导线继续转动而另一个极却不能,法拉第曾经指明了如何引起磁体的个极绕一个电流的连续转动。为了使这种过程可以无限地重复进行,整个的磁体在每周转动中必须从电流的一侧被搬到另一侧。

501.] 必须认真记住，促使一个载流导体扫过磁力线而运动的机械力,不是作用在501.1电流上而是作用在电流所通过的导体上的。如果导体是一个转动圆盘或一种流体,它就将服从这个力而运动,而这种运动可能和它所载有的电流的一种位置变化相伴随,也可能不和这种位置变化相伴随。[但是,如果电流可以在一个固定的导体或导线网路中自由地选取任意路径,则当使一个恒定的力作用在体系上时,电流通过导体的路径并不会发生永久性的变化,而在某种被称为感生电流的瞬变现象已经衰退以后，人们就将发现电流的分布是和没有任何磁力在起作用时的电流分布相同的。

唯一对电流起作用的力就是电动力,这种力必须和本章所考虑的机械力区别开来。

## 第四十四章 论电磁场中的能量和胁强

645.] 在借助于媒质中的一种胁强状态来解释电磁力时,我们只是在追随法拉第的观念,即认为磁力线倾向于自已缩短而且当并排存在时就互相推斥。我们所做的一切就是用数学语言来表示沿磁力线的张力的值以及垂直于磁力线的压强的值,并证明这样假设为存在于媒质中的胁强状态实际上就能产生观察到的作用在载有电流的导体上的力。

关于这种胁强状态在媒质中被引起和被保持的方式,我们还没有肯定过任何东西我们只曾证明,有可能设想电流的相互作用依赖于周围媒质中的一-种特定的胁强，而不是一种直接的和即时的远距作用。

任何一种借助于媒质的运动或用其他方式来对胁强状态作出的进一步解释,应被看成理论的一个另外的和独立的部分,它的成立或垮台并不影响我们目前的观点。请参阅第 832 节。

在本书第一编第 108 节中我们证明了观察到的静电力可被设想为是通过周围媒质中的一-种胁强状态的介人而起作用的。现在我们针对电磁力作了同样的事情,而剩下来要考察的就是,关于能够支持这些胁强状态的一种媒质的观念是否能够和其他的已知现象相容,或者说,我们是否必须认为这种观念没有成果而把它放弃掉。在一个既存在电磁作用又存在静电作用的场中,我们必须假设在第一-编中描述了的那种静电胁强是叠加在我们刚才还在考虑的电磁胁强上的。

在一个既存在电磁作用又存在静电作用的场中,我们必须假设在第一·编中描述了的那种静电胁强是春加在我们刚才还在考虑的电磁胁强上的。


## 第五十三章 光的电磁学说

781.] 在本论著的若干部分中,曾经作过借助于机械作用来解释电磁现象的尝试，那种机械作用是通过占据着物体之间的空间的一种媒质而从一个物体传到另一个物体的。光的波动学说也假设一种媒质的存在。现在我们必须证明,电磁媒质的性质是和光媒质的性质相等同的。

每当有一种新现象需要解释时就用一种新的媒质来充满全部的空间,这在哲学上绝不是多么有道理的。但是,如果两个不同科学分支的研究已经独立地提供了关于一·种媒质的想法,而且,如果为了说明电磁现象而必须赋予媒质的那些性质是和我们为了说明光的现象而赋予光媒质的那些性质种类相同的,那种媒质之物理存在的证据就将得到很大的加强。

但是,各物体的性质是可以定量地测量的。因此我们就得到媒质的数据,例如一种扰动通过媒质而传播的那一速度的数值,而这一速度是可以根据电磁实验来算出的,也是在光的事例中可以直接观测的。如果居然发现电磁扰动的传播速度和光的速度相同.而且这不但在空气中是如此,在别的透明媒质中也是如此,则我们将有很强的理由相信光是一种电磁现象,而且光学资料和电学资料的组合也将产生一种关于媒质之实在性的信念，和我们在其他种类的物质的事例中通过感官资料的组合而得到那种信念相似。

782.] 当光被发出时,发光物体就会消耗一定的能量;而如果光被另一物体所吸收,则这个物体会变热,表明它从外面接收到了能量。在从光离开第一个物体以后到它达到第二个物体以前的那一时间阶段中,光必须曾经作为能量而存在于中间的空间之中。

按照粒子发射学说,能量的传递是通过光颗粒从发光物体到被照物体的实际转移来达到的,这些颗粒携带着它们的动能,以及它们可以接受的任何其他种类的能量。按照波动学说,有一种物质性的媒质充满在两个物体之间的空间中,而正是通过这种媒质的各相邻部分的作用,能量才从一部分传到其次的部分,直到它到达了被照明的物体为止。

因此,在光通过它的期间,光媒质就是能量的一种承受物。在由惠更斯、菲涅耳、杨格林等人发展起来的波动学说中,这种能量被假设为部分地是势能而部分地是动能。势能被假设为起源于媒质各元部分的形变。因此我们必须认为媒质是弹性的,动能被假设为起源于媒质的振动。因此我们必须认为媒质有一种有限的密度。

在本书所采用的关于电和磁的理论中,两种形式的能量曾经得到承认,那就是静电能量和动电能量(见第 630 节和第 636 节)而这些能量被假设为不仅在带电的物体和磁化的物体上有其存身之处,而且在观察到有电力或磁力起作用的每一部分周围的空间中有其存身之处。由此可见,我们的理论在假设存在可以成为两种形式的能量的承受者的一种媒质方面是和波动学说一致的。

## 第五十四章 对光的磁作用


806.] 在电现象及磁现象和光的现象之间建立一种关系的最重要步骤,必然是某种实例的发现,在那种实例中，一组现象受到了另一组现象的影响。在寻找这样的现象时,我们必须以我们可能在想要对比的各量的数学形式或几何形式方面已经获得的任何知识为我们的指针。例如,如果我们像索未维耳夫人所做的那样企图借助于光来磁化一根针,我们就必须记得,磁南方和磁北方的区别只是一个方向的问题,从而它会立即反向,如果我们反转了有关数学正负号之应用的某些约定的话。电解现象使我们能够通过观察氧出现在电解槽的一个极上而氢出现在另一个极上来把正电和负电区分开来;而磁学中却没有任何和电解现象相类似的现象。

因此我们就不能指望,如果我们使光射中一根针的一端,那一端就会变成具有确定名称的一个磁极，因为两个磁极并不是像明和暗那样地不同的。

如果我们让圆偏振光射在针上,让右手偏振光射在针的一端而让左手偏振光射在针的另一端上,我们也许就能指望有较好的结果,因为在某些方面这两种光之间的相互关系可以说是和两种磁极之间的关系具有相同的形式的。然而,类似性甚至在这儿也是有毛病的,因为当两种光线互相合并时,它们并不是互相抵消而是形成一种平面偏振的光线。

法拉第是很熟悉借助于偏振光来研究产生在透明固体中的胁变的方法的。他作了许多实验,希望发现偏振光在通过内部存在着电解导电或介电感应的媒质时所受到的某种作用。然而他并没能找到任何这种作用,尽管实验是用按照最适宜发现拉力的效应的方式装置起来的一一电力或电流和光线相垂直,并和偏振平面成 45°的角。法拉第用各种方式改变了实验,但是没有发现由电解电流或静电感应引起的对光的任何作用。然而他在确立光和磁之间的关系方面却取得了成功,而他做到这一点的那些实验则描述在他的《实验研究》的第十九组中。我们将把法拉第的发现取作我们有关磁的本性的进一步探索的出发点，从而我们将描述一下他所观察到的现象。

807.] 一条平面偏振的光线从一种透明的抗磁性媒质中通过;当从媒质中出来时用一个检偏器截断它的路程,以测定它的偏振面。然后加上一个磁力,使透明媒质中的磁力方向和光线的方向相重合。于是光立即重新出现,但是如果把检偏器转过某一角度,光就又被截断。这就表明,磁力的效应就是使偏振面以光线方向为轴而转过一个确定的角度,这个角度为了截断光线而必须使检偏器转过的那个角度来描述。

808.] 偏振面转过的角度和下列各量成正比:
(1) 光线在媒质中走过的距离。因此偏振面是从它的原始位置开始而连续变化的。
(2) 磁力在光线方向上的分量。
(3) 转动角的大小依赖于媒质的种类。当媒质是空气或任何其他气体时,还没有观察到任何的转动。

这三点说法被包括在一个更普遍的叙述中,那就是,旋转角在数值上等于光线从进人媒质的一点到离开媒质的一点的矢势增量乘以一个系数,而对抗磁性媒质来说,这个系数通常是正的。

809.] 在抗磁性物质中,偏振面被转向的方向《一般说来》和一个电流的正方向相同,那个电流就是为了产生和实际存在的磁力同方向的磁力而必须绕着光线运行的。然而外尔代特却发现,在某些铁磁性媒质中,例如一种高氯化铁在木精或乙醚的浓溶液中，旋转方向却和将会产生磁力的电流运行方向相反。

这就表明,铁磁性物质和抗磁性物质的区别不仅仅起源于“磁导率”在前一事例中大于而在后一事例中小于空气的磁导率,而是这两类物体确实性质相反。

种物质在磁力作用下获得的使光的偏振面发生旋转的能力,并不是恰好正比于它的抗磁的或铁磁的磁化率。事实上,抗磁性物质中的旋转为正而铁磁性物质中的旋转为负这一法则,是有例外情况的,因为中性的铬酸钾是抗磁性的,但它却引起负旋转。

810.] 也存在另外一些物质,它们不依赖于磁力的施加就能在光线通过物质时使偏振面向右或向左旋转。在某些这种物质中,性质依赖于一个轴,例如在石英的事例中就是如此。在另一些物质中,性质并不依赖于光线在媒质中的方向,例如在松节油、糖溶液等等中就是如此。然而,在所有这些物质中,如果任何一条光线的偏振面在媒质中是像一个右手螺旋那样地扭转的,则当光线沿相反方向通过媒质时偏振面仍将像右手螺旋似的扭转。当把媒质放在光线的路程上时,观察者为了截断光线就必须旋转他的检偏器,而不论光线是从南或从北向他射来,旋转的方向相对于观察者来说都是相同的。当光线的方向反向时,旋转在空间中的方向当然也会反向。但是当旋转是由磁作用引起的时,它在空间中的方向却不论光是向南还是向北传播都是相同的。如果媒质属于正类，则旋转方向总是和产生或将会产生实际的磁场状态的电流的方向相同,而如果媒质属于负类则旋转方向总是和该电流的方向相反。

由此可以推知,如果光线在从北向南通过了媒质以后受到一个镜面的反射而从南向北返回媒质中,则当旋转是由磁作用引起的时,旋转就会加倍。当旋转只依赖于媒质的种类(而不依赖于光线的方向),就像在松节油等等中那样时,光线在被反射而回到媒质中再从媒质中出来时,它的偏振将是和入射时在相同的平面上的,第一次通过时的旋转将在第二次通过时被恰好倒了回来。

811.] 现象的物理解释带来了相当大的困难。不论是在磁致旋转方面,还是在某些媒质的表现方面,这些困难还几乎不能说已经解决。然而我们可以通过分析已经观察到的事实来给一种解释做些准备运动学中的一个众所周知的定理就是,两个振幅相同、振动周期相同、在同一平面上但沿相反方向转动的匀速圆周振动,当合成在一起时是和一个直线振动相等价的。这一振动的周期等于圆周振动的周期,它的振幅等于圆周振动的振幅的两倍,它的方向是两个点的连线,那就是在同一圆周上沿不同方向描述圆周运动的两个质点即将相遇的两个点。因此,如果一个圆周运动的周相被加速,则直线振动的方向将沿着圆周运动的方向转过一个等于周相加速度的二分之一的角。

也可以通过直接的光学实验来证明,两条沿相反方向而圆偏振的强度相同的光线当合并在一起时就变成一条平面偏振的光线，而且,如果其中一条圆偏振光线的周相由于任何原因被加速了，则合光线的偏振平面会转过--个等于周相加速度之一半的角度

812.] 因此我们可以表示偏振面的旋转现象如下:有一条平面偏振光线射在媒质上。这条光线和两条圆偏振光线相等价,其中一条是右手圆偏振的,而另一条是左手圆偏振的(对观察者而言)。通过了媒质以后,光线仍然是平面偏振的,但其偏振面却向警如说右方旋转了(相对于观察者而言)。由此可见,在两条圆偏振光线中,右手圆偏振的那一条的周相一定是在通过媒质时相对于另一条而被加速了。

换句话说,右手圆偏振的光线曾经完成了更多次数的振动,从而在媒质内部比周期相同的左手圆偏振的光线具有较小的波长。

现象的这种叙述方式是和任何光的学说都无关的,因为虽然我们使用了波长、圆偏振等等在我们头脑中可能和某种形式的波动学说相联系的术语,但是推理过程却和这种联系无关而只依赖于被实验证明了的事实。

813.] 其次让我们考虑其中一-条光线在某一给定时刻的位形。每时刻的运动都是圆周运动的任何波动,都可以用一个螺纹线或螺旋来代表。如果让螺旋绕着它的轴线放转而并不发生任何纵向运动,则每一个粒子都会描述一个圆,而与此同时,波动的传播则将由螺旋纹路上位置相似的各部分的表现纵向运动来代表。很容易看到,如果螺旋是右手的,而观察者是位于波动所传向的一端的,则在他看来螺旋的运动将显得是左手的,也就是说,运动将显得是逆时针的。因此,这样的一条光线曾经被称为一条左手圆偏振的光线;这名称最初起源于一些法国作者，现在已经在整个科学界都通行了。

一条右手圆偏振的光线可以按相似的方式用个左手螺旋来表示。在图 107 中，右侧的右手螺旋线A 表示一一条左手圆偏振的光线，而左侧的左手螺旋线B 则表示一条右手圆偏振的光线。

814.]现在让我们考虑在媒质内部具有相同波长的两条这样的光线。它们在一切方面都是几何地相似的，只除了其中一条是另-条的“反演”，即有如另一条在镜子里的像一样。然而，其中一条，譬如说是 A,却比另一条具有较短的旋转周期。如果运动完全起源于由位移所引起的力，那么这就表明，当位形像 A那样时，由相同的位移引起的力要比位形像 B那样时大一些。因此，在这一事例中，左手光线将相对于右手光线而被加速,而且不论各光线是从北向南还是从南向北行进,情况都将是这样的。因此这就是松节油等等引起的那种现象的解释。在这些媒质中,当位形像 A 那样时,由一条圆偏振光线所造成的位移将比位形像 B 那样时引起较大的恢复力。于是这些力就只依赖于位形，而不依赖于运动的方向。

但是在沿 SN 方向受到磁作用的一种抗磁性媒质中,两个螺旋 A 和B 中的一个却永远是以最大的速度旋转的,那就是当眼睛从 S向N 看去时看到它在顺时针转动的那个螺旋。因此,对于从 S向N 射去的光线来说,手光线 B 将传播得最快;而对于从 N 向S射去的光线来说，则左手光线 A 将传播得最快。

815.] 当把我们的注意力只集中在一条光线上时,螺纹线 B 就具有完全相同的位形,不论它表示的是一条由 S 向 N 的光线还是一条 N 向 S 的光线。但是在第一种情况下光线传播得更快一些,从而螺纹线也旋转得更快一些。因此,当螺纹线向一个方向运动时,将比它向另一个方向运动时引起较大的力。因此力并不仅仅依赖于光线的位形，而且也依赖于光线各部分的运动方向。

816.] 构成光的那种扰动,不论它的物理本性如何，是具有垂直于光线方向的矢量性质的。这可以由两条光线在干涉时在某些条件下会造成黑暗这--事实以及偏振在互相垂直的平面上的两条光线并不互相干涉这一事实来得到证明。因为,既然干涉依赖于偏振面的角位置,扰动就必然是一个有向量或矢量:而既然当偏振面互相正交时干涉就停止,代表扰动的那个矢量就必然垂直于这些偏振面的交线,也就是垂直于光线的方向。

821.] 我们迄今为止不得不使用一种语言,它或许过分暗示了关于波动学说中的运动的普遍假说。然而也很容易用一种不带这种假说的色彩的形式来叙述我们的结果。

不论光是什么,在空间每一点上总是有种什么事情在进行,这或许是移动，或许是转动,或许是还没有想象到的什么东西,但它肯定具有一个矢量或有向量的本性,其方向垂直于光线的方向。这是由干涉现象全面证明了的。在圆偏振光的事例中,这一矢量的量值保持不变,但其方向则绕着光线的方向而旋转,在波的一个周期内正好转一周。至于这个矢量是位于偏振面上还是和该平面相垂直,这种不确定性并不影响我们关于该矢量在右手圆偏振光和左手圆偏振光中的旋转方向的知识。这一矢量的方向和角速度是完全已知的,尽管这一矢量的物理本性和它在一个给定时刻的绝对方向是不确定的。

当一条圆偏振光线射在一种处于磁力作用下的媒质上时,它在媒质中的传播就受到光的旋转方向和磁力的方向之间的关系的影响。利用第 817 节中的推理,我们由此就得出结论说,在媒质中,当处于磁力的作用之下时,有某种旋转运动是正在进行着的,其旋转轴线就是磁力的方向;而且,当光的振动性旋转的方向和媒质的磁旋转方向相同时，圆偏振光的传播速率是和该二方向相反时不同的。

一方面是有圆偏振光从中通过的媒质,另一方面是有磁力线从中通过的媒质,我们在二者之间所能追索的唯一相似性就是,在二者中都存在一种绕轴旋转的运动。但是相似性也就到此为止,因为光现象中的转动就是表示着扰动的那个矢量的转动。这个矢量永远垂直于光线的方向,而且每秒绕该方向转过一定的转数。在磁现象中,转动的东西没有可以据以确定其侧面的任何性质,从而我们就不能确定它每秒转动多少次。

因此,在磁现象中,就没有任何东西和光现象中的波长及波动传播相对应。在有一个恒定磁力作用于其内的媒质中,并不会由于该力的作用而像当有光在其内传播时那样充满一种沿一个方向前进的波动。光现象和磁现象之间的唯一相似性就是,在媒质的每一点上，存在某种东西，它具有以磁力方向为轴的角速度的本性。