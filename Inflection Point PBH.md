## 单场慢滚暴胀模型中的功率谱增强
文献中常用多场暴胀模型给出功率谱增强的机制。我们自然会问，单场暴胀是否可以有这样的机制。先驱工作 [Physics of the Dark Universe 18 (2017) 6–10](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/Primordial%20black%20holes%20from%20single%20field%20models%20of%20inflation.pdf) 提出了一个方法。
在暴胀势中引入了一个near-inflection point，使得暴胀子在一段<u>较短的e-folds</u>内进入超慢滚阶段，在此阶段功率谱得到增强。
根据慢滚理论，我们可以计算曲率扰动的功率谱
$$\mathcal{P}_{\zeta}(k)=\frac{1}{8 \pi^{2}} \frac{1}{\varepsilon_{*}} \frac{H_{*}^{2}}{M_{\mathrm{pl}}^{2}}\left(k / k_{*}\right)^{n_s-1}$$
其中，$n_s=1-2 \varepsilon_{*}-\eta_{*}$，∗代表在horizon entry时取值。目前CMB的观测限制给出$n_s\sim 1$。可看出功率谱和$\varepsilon_*^{-1}$成正比。
注意到$\varepsilon=\frac{1/2\dot{\phi}^2}{M_{pl}^2H^2}$，和暴胀场的动能相关，同时慢滚近似给出，$\varepsilon\simeq \frac{M_{pl}^2}{2}(V'/V)^2$。此类机制在near-inflection point处势形状变平，使得暴胀子运动变慢，亦即$\varepsilon$压低，从而给出功率谱尖峰。
- 我们必须把功率谱增强效应和CMB的观测限制区分开。在多场慢滚中，这种划分可以很自然地通过慢滚暴胀相和对称性自发破缺阶段中间的waterfall stage来实现；
- 而在这种机制中，则由慢滚和超慢滚两个阶段的划分来实现。
- 这会带来更强的模型参数限制。
文章提出了一个多项式暴胀势的toy model。
$$V(\phi)=\left(\frac{1}{2} m^{2} \phi^{2}-\frac{1}{3} \alpha v \phi^{3}+\frac{1}{4} \lambda \phi^{4}\right)\left(1+\xi \phi^{2}\right)^{-2}$$
可重写为
$$V(x)=\frac{\lambda v^{4}}{12} \frac{x^{2}\left(6-4 a x+3 x^{2}\right)}{\left(1+b x^{2}\right)^{2}}$$
其中$x=\phi/v$，$m^2=\lambda v^2$，$a=\alpha/\lambda$，$b=\xi v^2$。
极值点位于
$$1-a x+(1-b) x^{2}+\frac{a b}{3} x^{3}=0$$
可以求得三个解$x_{1,2,3}$，其中$x_1<0$不讨论，$x_{2,3}=x_0\pm iy_0$。同时要求$V''(x_0)=0$，$(y_0=0)$ 可以得到inflection point，记为$x_0$。这对$a,b$有一个约束方程。
$$b=b_c(a)=1-\frac{1}{3} a^{2}+\frac{a^{2}}{3}\left(\frac{9}{2 a^{2}}-1\right)^{2 / 3}$$
c代表临界点。

接下来计算慢滚参数和e-fold数
$$\begin{aligned}
\epsilon_{\mathrm{SR}} & =\frac{1}{2 \kappa^{2}}\left(\frac{V^{\prime}(\phi)}{V(\phi)}\right)^{2} \\
& =\frac{8}{\kappa^{2} v^{2}} \frac{\left(3-3 a x+3(1-b) x^{2}+a b x^{3}\right)^{2}}{x^{2}\left(6-4 a x+3 x^{2}\right)^{2}\left(1+b x^{2}\right)^{2}}
\end{aligned}$$
$$\begin{aligned}
N_{\mathrm{SR}}=\int \frac{\kappa d \phi}{\sqrt{2 \epsilon_{\mathrm{SR}}}} & =\frac{\kappa^{2} v^{2}}{4} \int \frac{x\left(6-4 a x+3 x^{2}\right)\left(1+b x^{2}\right)}{\left(3-3 a x+3(1-b) x^{2}+a b x^{3}\right)} d x \\
& =\frac{\kappa^{2} v^{2}}{4 a b} \int \frac{x\left(6-4 a x+3 x^{2}\right)\left(1+b x^{2}\right)}{\left(x-x_{1}\right)\left(\left(x-x_{0}\right)^{2}+y_{0}^{2}\right)} d x
\end{aligned}$$
显然inflection point处e-fold数发散。因此考虑near-inflection point，$(a,b=b_c(a)-\beta)$，共振参数$0<\beta\ll 1$。因此给定$(a,b_c(a))$，我们可以调整$\kappa v$和$\beta$，在$x_0$处产生我们想要的e-fold数。
上面只是慢滚近似，通过解场方程，可以得到精确结果。
![[截屏2023-01-08 23.40.53.png]]
(为什么慢滚近似在临界点处没有失效？)
有了场方程的精确解后，就可以精确计算慢滚参数$\varepsilon$和e-fold数。文章指出慢滚近似总是比较有效的，随着$a$增加，逐渐失效。
![[截屏2023-01-09 00.21.19.png]]
后面就可以计算功率谱了。慢滚估计
$$\begin{aligned}
P_{\mathcal{R}}^{\mathrm{SR}}(k) & =\frac{\kappa^{4} V(x)}{24 \pi^{2} \epsilon_{\mathrm{SR}}(x)} \\
& =\frac{\lambda \kappa^{6} v^{6}}{96 \times 24 \pi^{2}} \frac{\left(6-4 a x+3 x^{2}\right)^{3} x^{4}}{\left(3-3 a x+3(1-b) x^{2}+a b x^{3}\right)^{2}} .
\end{aligned}$$
![[截屏2023-01-09 00.25.07.png]]
## 模型修正
### 一般性地证明slow-roll violation
[Primordial black holes and slow-roll violation](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/PhysRevD.96.063503_PBH_slowroll_violation.pdf) 指出上述文献的分析事实上破坏了慢滚条件。
不仅仅要求$\varepsilon \ll 1$，还要求
$$\left|\frac{\Delta \ln \epsilon_{H}}{\Delta N}\right| \ll 1$$

文献给出了一般性的证明，==在单场暴胀模型中要求PBH产生增强到解释DM的量级，会在order-1程度上破坏慢滚条件==。

考虑质量大于$M$的PBH可以解释所有DM，对应共动尺度$a_HH=a_{exit}H_I$，在暴胀期间，在CMB尺度$k_0=0.05 Mpc^{-1}=a_0H_I$之后出视界。
假设$H_I$为常数。可以估计CMB尺度出视界到该尺度出视界的e-fold
$$\begin{aligned}
N & =\ln \left(\frac{a_{\text {exit }}}{a_{0}}\right)=\ln \left(\frac{a_{H} H}{0.05 \mathrm{Mpc}^{-1}}\right) \\
& =18.4-\frac{1}{12} \ln \frac{g_{*}}{g_{* 0}}+\frac{1}{2} \ln \gamma-\frac{1}{2} \ln \frac{M}{M_{\odot}}
\end{aligned}$$
那么$\Delta N\leq N$。我们考虑最大的$\Delta N$，也就是最小的PBH质量。PBH质量不能太小以抵抗Hawking辐射，能够存活到matter-radiation equality的PBH质量下界为
$$M_{\min }=1.5 \times 10^{-21}\left(\frac{\Omega_{m} h^{2}}{0.14}\right)^{-2 / 3} M_{\odot}$$
代入数据得到$\Delta N_\text{max}\approx 42+\frac{1}{2}\ln \gamma$。
设$\gamma=1$，由PBH丰度计算可以得到
$\Delta_\zeta^2=0.021$，而CMB尺度的$\Delta_\zeta^2(k_0)=2.2\times 10^{-9}$，因此可计算$\Delta \ln \varepsilon$，最后得到
$$\left|\frac{\Delta \ln \epsilon_{H}}{\Delta N}\right| > 0.38$$
可见$\mathcal{O}(1)$地破坏了慢滚条件。

### Overshooting, ultra-slow-roll, and fine-tunning
[On primordial black holes from an inflection point](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/On%20primordial%20black%20holes%20from%20an%20inflection%20point.pdf) 指出，在(near) inflection point暴胀子要么退出暴胀，要么进入超慢滚。在该点使用慢滚条件计算得到大的e-fold数的想法没有意义。
- 虽然有人可能想用在超慢滚阶段功率谱仍然可以指数增长来弥补，然而上述文献的模型参数必须要非常精确地调节，否则超慢滚的指数增长不会持续足够长。
- 这是因为，在进入超慢滚前，由于势形状曲率的改变，暴胀子shoots-over到了一个很大的速度，使得其在相图上已经跑到了慢滚的吸引子外。这一转变使得功率谱下降了几个量级，这要求一段较长的超慢滚才足以增强功率谱。
下面给出一个可以减弱over-shooting并且有较长超慢滚的方法。
我们知道慢滚条件下
$$\varepsilon=-\frac{\dot{H}}{H^2},\, \varepsilon_2=\frac{\dot{\varepsilon}}{\varepsilon H}=\dv{\ln \varepsilon}{N}$$
都远小于1。在慢滚吸引子轨道上，
$$\varepsilon \simeq \varepsilon_{\mathrm{sr}} \equiv \frac{M_{p}^{2}}{2} \frac{V^{\prime 2}}{V^{2}}, \quad \varepsilon_{2} \simeq 4 \varepsilon_{\mathrm{sr}}-2 \eta_{\mathrm{sr}}, \quad \eta_{\mathrm{sr}} \equiv M_{p}^{2} \frac{V^{\prime \prime}}{V}$$
然而，超慢滚相则由小$\varepsilon$而大$\abs{\varepsilon_2}$定义。此时$\varepsilon\neq \varepsilon_{sr},\,\varepsilon_2\neq 4\varepsilon_\text{sr}-2\eta_\text{sr}$。超慢滚势形状非常平，导致加速(惯性)效应比势梯度要强。换句话说，Hubble膨胀导致的等效阻尼项被加速项弥补
$$\ddot{\phi}+3 H \dot{\phi}=-V^{\prime} \simeq 0$$
这直接告诉我们$\dot{\phi}\propto a^{-3}$，超慢滚时暴胀子被减速。因此$\delta=-\ddot{\phi}/(H\dot{\phi})=3$，因此$\varepsilon_2=2(\varepsilon-\delta)\simeq -6$。
注意慢滚和超慢滚的曲率扰动功率谱均为
$$\mathcal{P}=\frac{H^{2}}{8 \pi^{2} \varepsilon M_{Pl}^{2}}$$
注意，由于慢滚和超慢滚下$\varepsilon=\frac{1/2\dot{\phi}^2}{M_{pl}^2H^2}\ll 1$，因此能量仍由势能主导，$H^2\propto V$。
由慢滚势能梯度项主导，到超慢滚加速项主导，场的加速度$\ddot{\phi}$必须增长到足以克服势能梯度，这会导致$\varepsilon$增长。但又不能增长太多以避免退出暴胀。
- overshooting epoch
	- 可见功率谱会被转变阶段$\varepsilon$的增长和势能$V$的下降同时压低
- ultra-slow-roll phase
	- 但又会在进入超慢滚后以$e^{6N_\text{usr}}$的幅度增强。其中$N_\text{usr}$为超慢滚的e-fold数。
给定总的e-fold数约为65。那么一种挽救infelction point model的方法是，要求standard inflation和overshooting epoch的e-fold数尽可能小，ultra-slow-roll phase的e-fold数尽可能大。
接下来文献对原始文献的模型做了修正
#### 模型修正
在 [Physics of the Dark Universe 18 (2017) 6–10](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/Primordial%20black%20holes%20from%20single%20field%20models%20of%20inflation.pdf) 引入的势中，给定参数$(a,b)$可以给出inflection point，而实际则让$b$微小偏离临界点。这是因为原始论文认为在inflection point处slow-roll条件仍成立，$\varepsilon$正比于势能导数平方，因此功率谱在此处会发散。
然而，在inflection point处要采用的应当是ultra-slow-roll的计算。
采用适当的参数，给出geometry slow-roll parameter $\varepsilon=-\frac{\dot{H}}{H^2}$和慢滚近似下的$\varepsilon_\text{sr}$，以及$\varepsilon_2$。
![[截屏2023-01-09 14.38.58.png]]![[截屏2023-01-09 14.39.15.png]]
可以看到，在inflection point处，$\varepsilon_\text{sr}$下降到非常小，功率谱发散。但此处根本不需要用慢滚近似，因为从$\varepsilon_2$的图来看，$\varepsilon_2$在inflection point处已经到了-6，而后进入超慢滚，变得很大。
功率谱的图则如下所示
![[截屏2023-01-09 14.43.29.png]]
可见在迎来超慢滚的指数增长前，功率谱由于overshooting一直被压低。
不过，模型参数还有可调整的空间。文章另外调整参数得到下面的功率谱
![[截屏2023-01-09 14.49.18.png]]
这会带来fine-tunning问题。而且这个事实上不足以产生足够多的PBH以解释DM。
另外一个问题是，究竟需要多精细的参数调节。当然这依赖于势能的具体形状。