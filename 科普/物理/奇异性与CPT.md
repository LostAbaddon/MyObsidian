---
作者: LostAbaddon
created: 2024/06/10 15:35:08
tags:
  - 科学/物理
  - 科学/科普
---

彭罗斯的引力奇异性定理的证明过程中有一个很关键的论点：

**一张非时序超曲面 A 的过去依赖域与一张柯西超曲面相交的区域 B，A 必然可以同胚嵌入到 B 中。**

在彭罗斯的定理中，为了运用这一拓扑原则，我们会构造一种特殊的非时序超曲面。

具体来说，如果整体双曲时空中有一个闭合超曲面 S，则 S 的光锥面可以分为四部分：指向未来的内行超曲面 $I^+$，指向未来的外行超曲面 $O^+$，指向过去的内行超曲面 $I^-$，指向过去的外行超曲面 $O^-$。这样 $O^ + \cup S \cup I^+$ 就构成了一张非时序超曲面，而这张非时序超曲面必然可以嵌入到过去的一张柯西超曲面中。那么，但 S 是一张陷俘面时，通过雷乔杜里方程可以证明，$O^+$ 会和 $I^+$ 一样都会收缩，最终到达超曲面上体元为0 的点。可以证明，如果这个点只是坐标系上的一个共轭点，那么此时 $O^+$ 与 $I^+$ 都会闭合，那么同胚嵌入就无法达成。从而彭罗斯利用拓扑方法证明了，$O^+$ 和 $I^+$ 上至少有一根指向未来的类光测地线会遇到引力奇异性点。

现在，让我们考虑这么一个问题：如果这样一个整体双曲的时空中出现了一个引力奇异性的点集，这个点集随时间的演化是否会消失？

显然，并不会。

我们去包含这些点集的某个非时序超曲面 S，然后考虑其未来依赖域，如果在某个时间点这个点集消失，那就表示在这个时间点之后的未来依赖域内可以找到一张非时序超曲面 C，其中最多只有共轭点，这样的超曲面在拓扑上显然亏格为 0，但原来的超曲面 S 的亏格却不是0，C 显然不可能拓扑同胚于 S，从而 C 是不可能从 S 演化而来的。

这就是说，**在不考虑量子效应的纯经典广义相对论中，引力奇异性点集一经出现，就不可能消失**。

但这样就存在一个问题，让我们考虑时间反演，此时场方程形式不变，但时空的演化却出现了反演不对称的情况：引力奇异性点集原本是只能出现不能消失，但在时间反演后却成了只能消失不能出现。

也就是说，在经典层面上，**虽然广义相对论的时空的规律本身是时间反演不变的，但时空的演化过程本身却不是时间反演不变的**。

也即，广义相对论的时空不是 T 反演不变的。

那么 CPT 联合反演呢？

显然，场方程本身是 CPT 联合反演对称的，三个操作独立作用下也是不变的。而时空在 C 和 P 独立作用下看起来也是不变的，尤其在上述拓扑方法下，C 和 P 根本不起作用。但唯独 T 会起作用，其不是不变的，这就很有趣了。











那么，让我们考虑一个问题：这个引力奇异性的点，它是只要在空间上抵达了就会遇到奇异性，还是和怎么抵达这个位置有关？或者说，这个奇异性是只与空间位置相关，还是和速度矢量也相关？

在深入考虑这个问题之前，让我们先来想一个问题：




如果说是前者，那么必然存在一个时刻，从该时刻起，任意陷俘面




让我们先从这套拓扑方法引申出来一些有趣的命题。

首先，如果一个整体双曲时空中，已经存在了一个陷俘面，那么未来这个陷俘面是否会消失？

答案显然是不会的，因为如果陷俘面消失，那么现在的陷俘面的未来依赖域内会出现一张非时序超曲面，这张超曲面应该能同胚映射到陷俘面的 $O^+$ 上，但前者是无洞的，后者是有洞的，洞对应的就是引力奇异性点集，从而这样的同胚映射是不存在的。

从这里我们发现了这种映射关系背后的一个有趣的“时间反演不对称性”：将有洞的 $O^+$ 映射到无洞的非时序超曲面上是可以的，但将无洞的非时序超曲面映射到 $O^+$ 上却是不可以的，而前者可以存在于陷俘面出现之前的时空中，后者却是

由于未来的非时序超曲面必须要嵌入到过去的非时序超曲面中（这里当然要求后者位于前者的过去依赖域内），那么如果过去的非时序超曲面上有引力奇异性点集




假如说，这个引力奇异性所在位置只和位置相关而和速度矢量无关，那就表示陷俘面 S 的未来外行光锥面 $O^+$ 会抵达该奇异性位置的同时，总存在一个位于未来时刻的陷俘面 S 的未来投影 S'，它的未来内行陷俘面 $I^+$ 也会遇到这个奇异性位置。



那么，让我们考虑一个问题：$I^+$ 是否会遇到引力奇异性？

显然，只要 $O^+$ 会遇到引力奇异性，那么从上述拓扑原则我们