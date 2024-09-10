- direct constraints
	- derived by investigating the observational effects that PBHs directly trigger by their gravitational potential, and are thus ==independent of the mechanisms of PBH formation==.
	- gravitational lensing, dynamical effect, accretion, and growth of large-scale structures. 
-  Indirect constraints 
	- can be obtained by observational effects that are not caused by the PBHs but by something else which is deeply connected to PBHs. 
	- although such constraints cannot be applied to all the possible PBH scenarios, they are ==powerful in excluding some of them==.
It is important to keep in mind that all the constraints in this section are derived under the assumption that ==the PBH mass function is monochromatic==, which is valid when the width of the mass function is sufficiently narrow.
## The constraints on PBHs lighter than  ∼$10^{15}\operatorname{g}$ that have already evaporated
high-energy particles emitted from PBHs leave certain signals from which we can place the upper limit on the PBH abundance.
- production of the lightest supersymmetric particles (if they exist) ($10^4g < M_{PBH}< 10^9g$)
- entropy production in the early universe ($10^6g < M_{PBH}< 10^9g$)
- change of the abundance of the light elements produced by the big bang nucleosynthesis ($10^9g < M_{PBH}< 10^{13}g$)
- extragalactic photon background ($10^{14}g < M_{PBH}< 10^{15}g$)
- damping of the CMB temperature anisotropies on small scales by modifying the cosmic ionization history ($10^13g < M_{PBH}< 10^{14}g$)
## Direct
### Gravitational lensing
The outstanding virtue of gravitational lensing is that the individual lensing signal is ==solely based on gravitational physics, and does not suffer from the uncertainties that exist in studying electromagnetic signals== resulting from the interaction between PBHs and surrounding matter.
![[截屏2023-01-13 13.48.41.png]]
光线通过大质量天体时会弯曲。利用薄透镜近似，透镜方程写为
$$\theta D_{S}=D_{S} \beta+D_{L S} \alpha, \quad \alpha=\frac{4 G M_{\mathrm{BH}}}{D_{L} \theta}$$
考虑在透镜平面上，像的位置 $r=D_L\theta$，以及没有弯曲时的位置 $r_0=D_L\beta$。透镜方程化为
$$r^2-r_0r-R_E^2=0$$
其中 $R_E=\sqrt{4GM_{PBH}D_LD_{LS}/D_S}$ 为Einstein半径。解方程得到两个像的位置
$$r_{1,2}=\frac{1}{2}\left(r_{0} \pm \sqrt{r_{0}^{2}+4 R_{E}^{2}}\right)$$
当源、透镜和观测者在一条直线上时，$\beta=0$，像的位置落在一个圆上，即Einstein环 $r=R_E$。
注意，在$r_0\simeq R_E$时，引力透镜效应才是明显的。典型的角分辨为
$$\Delta \sim \frac{R_{E}}{D_{L}}=\sqrt{\frac{4 G M_{\mathrm{BH}}}{D_{S}} \frac{1-x}{x}} \approx 0.3 \operatorname{mas}\left(\frac{M_{\mathrm{BH}}}{10 M_{\odot}}\right)^{1 / 2}\left(\frac{D_{S}}{100 \mathrm{kpc}}\right)^{-1 / 2} \sqrt{\frac{1-x}{x}},$$
其中$x=D_L/D_S$。
因此可通过对角分辨的观测来限制PBH质量。

依据成像的角分辨和当前观测分辨率的不同大小关系，可以将引力透镜效应分为Microlensing，Millilensing，Femtolensing。

#### Microlensing
像的角分辨太小以至于无法被观测分辨（如MACHO Project 和EROS，大约为0.6角秒）。
在Microlensing中，我们只能看到两个像叠加后更亮的像。亮度被放大的倍数记为
$$A=\frac{u^{2}+2}{u \sqrt{u^{2}+4}}, \quad u=\frac{r_{0}}{R_{E}}$$
当$r_0=R_E$时，$A=1.34$。
一个有用的量是optical depth $\tau$。它表征背景天体的亮度被引力透镜放大1.34倍以上的概率，换句话说，表征光线穿过Einstein环内的概率（$u$越小，$A$越大）。
$$\tau=\int_{0}^{D_{S}} \mathrm{~d} r n_{\mathrm{BH}}(r) \pi R_{E}^{2}(r)=4 \pi G \int_{0}^{D_{S}} \mathrm{~d} D_{L} \rho_{\mathrm{BH}}\left(D_{L}\right) \frac{D_{L}\left(D_{S}-D_{L}\right)}{D_{S}}$$
注意其并不依赖于PBH质量，而是依赖于PBH的丰度。
有文献提出，麦哲伦星云的光会通过布满银河系的暗物质晕到达地球。因此PBH组成了暗物质的多大组分会直接影响其optical depth。
#### Millilensing
大于$10^6M_\odot$的大质量PBH产生的引力效应，所成的两个像之间的角分辨在毫角秒之间。有文献提出可以用VLBI来分辨。
#### Femtolensing
很小质量但还没蒸发的PBH，即$10^{-16}-10^{-13}M_\odot$之内，也可以被引力透镜所观测。但是对于如此小质量天体的引力透镜效应，光的波动性会变得显著，不能再用几何光学近似，需要考虑衍射效应。这是由于光的波长已经可以和PBH的Shwarzshild半径所比拟。
采用准几何光学近似，放大因子修改为
$$A=\frac{u^{2}+2+2 \sin \left(E_{\gamma} T_{12}\right)}{u \sqrt{u^{2}+4}}$$
$T_{12}$是两个像的到达时间差。
$$T_{12}=4 G M_{\mathrm{PBH}}\left[\frac{1}{2} u \sqrt{u^{2}+4}+\ln \left(\frac{\sqrt{u^{2}+4}+u}{\sqrt{u^{2}+4}-u}\right)\right] $$
### Dynamical constraints
原初黑洞通过引力相互作用影响天体系统。通过理论估计和实验的比照，可以对不同质量的丰度做上限估计。
这部分争议较大。
通常考虑的是以下几类天体系统
#### Disruption of white dwarfs
[白矮星](https://doi.org/10.1103/PhysRevD.92.063007)
典型的白矮星具有太阳质量大小，尺度则可与地球比拟。可见其密度之大，这也导致其具有较强的表面引力。
白矮星通常被认为是Type Ia超新星的祖先。白矮星通过吸积伴星物质，在吸积-爆发循环中不断冗余质量，最后超过钱德拉塞卡极限，通过热失控（Thermonuclear runaway）的方式导致超新星爆发。
原初黑洞可以对白矮星造成影响导致其在钱德拉塞卡极限之下也可形成超新星。其想法如下：小尺度的原初黑洞穿过白矮星时，在其内部留下一个过道（tube），这里面的物质由于吸收了原初黑洞的动能，温度升高；如果能量向外扩散的速率比核聚变的速率快，则会点燃整个白矮星。
这个方法可以用来限制行星质量大小的原初黑洞丰度。（太小了不能对白矮星造成影响；太大了碰撞几率过小）
#### Disruption of neutron stars
中子星是比白矮星更致密的天体。利用它来限制原初黑洞丰度的原理同白矮星相近，只不过考虑的是原初黑洞被其引力束缚在内的可能性。
如果原初黑洞在中子星内部完全损失动能，那么它将会在几次往复振荡后摧毁中子星。
#### Disruption of wide halo binaries
wide halo binaries是星系晕内距离较远的双星，对原初黑洞的引力扰动不稳定。
#### Disruption of globular clusters
和wide halo binaries类似，只不过其中包含了更多恒星。
#### Disruption of ultra-faint dwarf galaxies
如果原初黑洞存在于极暗矮星系之中，星系会由于和原初黑洞的相互作用导致扩散得更宽，从而和观测矛盾。
#### Dynamical friction on PBHs
原初黑洞和星系内其他物质摩擦，在星系中心沉积聚团，可以通过对星系中心的质量限制来观测
#### Disk heating
原初黑洞穿过星系盘时，由于引力相互作用导致星系盘内的恒星在长时间内叠加一个随机行走的效应，导致星系盘速度变大。
### Accretion constraints
在形成原初黑洞时，星际气体会在黑洞附近形成吸积盘。这是一个高度非线性的过程，估计比较复杂且对过程中的估计比较依赖。
#### Accretion effects on CMB
早期宇宙中，重子气体被原初黑洞吸积过程中，会由于自身内部的碰撞或者辐射从而离子化，这会影响CMB光子谱，导致其偏离普朗克分布、光子退耦时间、宇宙热历史中离子化的进程。后两者会对CMB的功率谱和极化各向异性有影响。
对以上CMB偏离的零探测结果可以给出原初黑洞的限制。
#### X-rays and radio from present-day PBHs
当前宇宙中，原初黑洞也会吸积气体导致电磁辐射从而被无线电望远镜和X射线望远镜观测到。
### Large-scale structure constraints
在大尺度上，原初黑洞在宇宙中随机分布，导致泊松分布的功率谱。等曲率扰动的方差为
$$\left\langle\delta_{\mathrm{DM}}^{2}\right\rangle=\left\langle\left(\frac{\delta \rho_{\mathrm{PBH}}}{\rho_{\mathrm{DM}}}\right)^{2}\right\rangle=f_{\mathrm{PBH}}^{2} N_{\lambda}^{-1}=\frac{f_{\mathrm{PBH}} M_{\mathrm{PBH}}}{\rho_{\mathrm{DM}} \lambda^{3}}$$
其中$N_\lambda=n_{\mathrm{PBH}}\lambda^3$是共动体积内的平均原初黑洞数量。$\lambda^{-3}$的标度关系意味着在小尺度上原初黑洞的扰动增强。这会对LSS的功率谱带来影响。
## Indirect
上述效应都是原初黑洞直接造成的。以下讨论的则是间接探测，其对由于暴胀导致的原初不均匀性所形成的原初黑洞有效，相当于对原初不均匀性作探测，来间接探测原初黑洞。
### Stochastic gravitational waves from the primordial density perturbations
导致原初黑洞产生的原初密度扰动，足以通过二阶效应产生诱导引力波。引力波形成时的频率和当时的视界尺度，从而与原初黑洞质量联系。
$$f_{\mathrm{GW}} \simeq 1 \times 10^{-9} \mathrm{~Hz}\left(\frac{M_{\mathrm{PBH}}}{30 M_{\odot}}\right)^{-1 / 2}$$
可见恒星质量量级的原初黑洞产生的引力波背景频率在nHz区间。这可以被PTA限制。
### CMB spectral distortions from the primordial density perturbations
在CMB解耦（$z\simeq 1100$）之前重新进入视界的光子和重子气体的扰动，会由于光子和重子之间的紧密耦合而经历声振荡（acoustic oscillations）。这些振荡最终被光子扩散，即光子和自由电子之间的不完美耦合，所消除，称为Silk 阻尼。
对于越小尺度的扰动，Silk 阻尼越早发生。因此导致原初黑洞产生的小尺度扰动增强会通过这一点使得CMB原初密度扰动功率谱的谱指数偏离。
- $50\lesssim k\lesssim 10^4$：$\mu$-type。Silk 阻尼在$z\sim 5\times 10^4$之前发生。光子只达到了运动学平衡，有化学势，BE分布。
- $k\lesssim 50$：y-type。Silk 阻尼在$z\sim 5\times 10^4$之后发生。运动学平衡也未达到，由Compton-y因子描述分布。
目前未测到CMB谱指数偏离，这带来一个上限，几乎排除了$10^{4-13}M_\odot$的原初黑洞。
### Big-bang nucleosynthesis
对$k\gtrsim 10^4$的模式，Silk 阻尼发生在远早于CMB退耦之前，在BBN之后。这会对BBN产生影响。
## Future
### Fast radio bursts
### 21 cm

