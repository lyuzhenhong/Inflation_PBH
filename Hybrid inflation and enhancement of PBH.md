## 原始模型
### 基本介绍
在chaotic inflation中我们需要让$\phi$的初值在super-Planckian能标以让$V(\phi)$能贡献足够大的Hubble阻尼项，从而导致慢滚。我们自然会想，如果在$V(\phi)$中引入一个足够大的常数项，使得不依赖于$\phi$值就可以贡献足够大的阻尼呢？当然这会带来一个无法结束暴胀的问题。因此我们可以再引入一个额外的场$\psi$来控制$\phi$场暴胀的结束，这便是hybrid inflation的想法，其原型可以看成一个自发对称破缺势和chaotic势的混合(hybrid)。

在单场暴胀中，暴胀的进行和结束由慢滚参数决定。慢滚参数远小于1时暴胀进行，趋于1时暴胀结束。根据慢滚近似，这也与暴胀势的形状直接相关。
作为对比，在混合暴胀中，暴胀的结束与否和暴胀势的形状无关。这通过耦合暴胀场$\phi$和一个额外场$\psi$来实现
$$\mathcal{L}=-\frac{1}{2}\left(\partial_{\mu} \phi\right)^{2}-\frac{1}{2}\left(\partial_{\mu} \psi\right)^{2}-V(\phi)-\frac{1}{4 \lambda}\left(M^{2}-\lambda \psi^{2}\right)^{2}-\frac{g^{2}}{2} \phi^{2} \psi^{2}$$
$$V(\psi,\phi)=\frac{M^4}{4\lambda}+\frac{1}{2}(-M^2+g^2\phi^2)\psi^2+\frac{\lambda}{4}\psi^4+V(\phi)$$
$\phi$和$\psi$的耦合给$\psi$带来了有效质量 $m_\psi=-M^2+g^2\phi^2$。$\psi$场的势形状由$\phi$控制，当$\phi>\phi_c=M/g$时，有效质量为正，$V(\psi)$只有一个极小值，位于$\psi=0$处，记为伪真空能$V_0=\frac{M^4}{4\lambda}$；当$\phi<\phi_c=M/g$时，$V(\psi)$有两个分别位于0两侧的极小值点，且比$\frac{M^4}{4\lambda}$低，因此自发破缺。
![[截屏2023-01-15 12.35.05.png]]
$\phi>\phi_c$时，$\psi=0$场，位于伪真空，此时$V(\phi,\psi)=V_0+V(\phi)$，这等价于$\phi$场作chaotic inflation的情形 (由于$\psi$场较重，可以积掉)，$\phi$场慢滚；当$\phi$场滚动到$\phi_c$时，$\psi$场无质量，通过量子效应触发二阶相变，迅速滚动到新的真空$\psi\to M/\sqrt{\lambda}$ (tachyonic)，使得$V_0$消失，从而结束暴胀。这一阶段也称waterfall stage。

假设$V(\phi)=\frac{1}{2}m^2\phi^2$  [Linde hybrid inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/physrevd.49.748_hybrid_inflation.pdf)。
$$V=V_0+\frac{1}{2}m^2\phi^2+\frac{\lambda}{4}\psi^4+\frac{1}{2}M^2(\phi)\psi^2$$
其中$M^2(\phi)=g^2(\phi^2-\phi_c^2)$。
要求$V(\phi)\ll\frac{M^4}{4\lambda}$，暴胀由伪真空能驱动。$\phi_c$处发生相变时，Hubble常数为
$$H^2\approx\frac{1}{3M_P^2}V(\phi)=\frac{2\pi M^4}{3\lambda M_P^2}$$
同时也假设$m^2\ll H^2$，这给出$M^2\gg mM_P\sqrt{\frac{3\lambda}{2\pi}}$。可以在此条件下验证$\phi>\phi_c$时，暴胀发生。
$$\varepsilon_{1\phi}=\frac{M_P^2}{2}(\frac{V'}{V})^2=2(\frac{M_P}{\phi})^2<2(\frac{M_P}{M/g})^2\ll 2(\frac{M_P^2}{mM_P\sqrt{\frac{3\lambda}{2\pi}}})\sim \frac{M_P}{m}\ll 1$$
$\varepsilon_{2\phi}=2M_P^2\left[(\frac{V'}{V})^2-\frac{V''}{V}\right]=-2(\frac{M_P}{\phi})^2$同理。

我们考虑跨越临界点$(\phi_c,\psi_c)$，$\Delta t=H^{-1}$时间之后，$\phi$和$\psi$场的行为。

在这段时间内，$\phi$场值减小
$$\Delta\phi=\dot{\phi}\Delta t=\frac{m^2}{3H}\phi H^{-1}=\frac{\lambda m^2M_P^2}{2\pi gM^3}$$

$\psi$场的有效质量平方为$M^2(\phi)\sim g^2\phi_c\Delta\phi=\lambda m^2M_P^2/(\pi M^2)$。我们发现只要$M^3\ll \lambda mM_P^2$，则有$M^2(\phi)\gg H^2$。因此在跨越临界点后$\Delta t=H^{-1}$时间内，$\psi$场迅速滚落到最小值$\psi_0=M(\phi)/\sqrt{\lambda}$，并在附近振荡。由于其有效质量为负，振荡过程中会向外辐射能量。

另外也可验证在远小于$\Delta t=H^{-1}$时间内，$\phi$方向运动变快，快速滚落到最小值。综合以上，因此暴胀在$\phi_c$附近瞬间结束。

#### Shortcomings
The original hybrid model in the false vacuum regime generically predicts a ==blue spectrum== of scalar perturbations.
- [Lindle hybrid inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/physrevd.49.748_hybrid_inflation.pdf)
- [False vacuum inflation with Einstein gravity](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/PhysRevD.49.6410_False-vacuum-inflation-with-Einstein-gravity.pdf)
-  Since $V\simeq V_0$, the scalar potential is very flat, and so the $\varepsilon$ slow-roll parameter is extremely small. This means that the spectral index is given by $n_s \simeq 1 + 2\eta$. The potential for quadratic or quartic inflation is curved upwards, meaning $V'' > 0$. Consequently, $\eta > 0$  which would result in a blue spectrum of scalar curvature perturbations $n_s > 1$.


### 相变时的量子涨落导致PBH产生
$\psi$的负质量导致其运动方程为负频率的谐振子方程，会引发量子涨落的指数增长，进视界带来很大的密度扰动（包括 inflating topological defect）。[1996 Juan Garc´ıa-Bellido, Andrei Linde and David Wands](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/9605094_Density-Perturbations-and-Black-Hole-Formation-in-Hybrid-Inflation.pdf)

Large curvature perturbations on smaller scales than the ones probed by CMB anisotropy experiments can also be generated during inflation, e.g. for hybrid models ending with a fast (in terms of e-folds of expansion) waterfall phase. In this case, ==exponentially growing modes of a tachyonic auxiliary field== induce order one curvature perturbations.

#### Exponential growth
[Lyth 1107.1681](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/1107.1681_PBH-formation-and-hybrid-inflation.pdf)
$$V(\phi,\chi)=V_0+V(\phi)+\frac{1}{2}m^2(\phi)\chi^2+\frac{\lambda}{4}\chi^4$$
其中$m^2(\phi)=g^2\phi^2(t)-m^2=g^2(\phi^2-\phi_c^2)$，$V_0=\frac{M^4}{4\lambda}$。$g,\lambda\ll 1$，$m\gg H$
- 由$V_0\gg V(\phi)$有$V_0=m^4/(4\lambda)\simeq 3M_P^2H^2$；
- 要求$\pdv{V}{\chi}|_{\chi_0}=0$，得到vev $\chi_0^2=-m^2(\phi)/\lambda$。在$\phi=0$处$\chi_0^2=m^2/\lambda=12M_P^2H^2/m^2$。
选取uniform-$\phi$规范，有
$$\ddot{\chi}_{\mathbf{k}}+3 H \dot{\chi}_{\mathbf{k}}+\left[(k / a)^{2}+m^{2}(\phi(t))\right] \chi_{\mathbf{k}}=0$$
采用共形时$\eta=-1/(aH)$，
$$\frac{d^{2}\left(a \chi_{\mathbf{k}}\right)}{d \eta^{2}}+\omega_{k}^{2} a \chi_{\mathbf{k}}=0$$
其中$\omega_k^2(\eta)=k^2+a^2\tilde{m}^2(t)$，$\tilde{m}^2=m^2(\phi(t))-2H^2$。
考虑$\chi$场的裸质量$M^2\gg H^2$的情况。对于较小的$k$，我们可以认为$\omega^2_k\simeq a^2\tilde{m}^2$。那么$\omega^2_k$在相变$\phi=\phi_c$前一小段时间从正号变为负号(之所以偏离一小段，是因为$-2H^2$的影响)。
对我们所考虑的模式，在正频变负频前后都有满足绝热条件$\dv{\omega_k^2}{\eta}\ll\abs{\omega_k^2}$的时期。
变号前后的绝热时期内，扰动分别为振荡解和指数增长解
$$a \chi_{k} \simeq\left(2 \omega_{k}(\eta)\right)^{-1 / 2} \exp \left(-i \int^{\eta} \omega_{k}(\eta) d \eta\right)$$
$$a \chi_{k} \sim\left(2\left|\omega_{k}(\eta)\right|\right)^{-1 / 2} \exp \left(\int_{\eta_{1}(k)}^{\eta}\left|\omega_{k}(\eta)\right| d \eta\right)$$
1代表绝热时期的开始。
绝热条件等价于$$\begin{aligned}
\tilde{m}(t) & \simeq m(t), \\
\frac{2 H}{|m(t)|} & \ll\left[1-\left(\frac{k}{a(t)|m(t)|}\right)^{2}\right]^{3 / 2} \\
\frac{1}{|m(t)|^{2}} \frac{d|m(t)|}{d t} & \ll\left[1-\left(\frac{k}{a(t)|m(t)|}\right)^{2}\right]^{3 / 2}
\end{aligned}$$
由绝热解指数形式的特点（$\eta^{-1}\sim\omega_k\sim a\tilde{m},\,t^{-1}\sim\tilde{m}\gg H$），结合上述条件的第一式，有$\dot{\chi}_k\simeq\abs{m(t)}\chi_k$。对$k/(a\abs{m(t)})$做小量展开，得到
$$\left|\omega_{k}\right| \simeq a|m(t)|\left(1-\frac{1}{2} \frac{k^{2}}{a^{2}|m(t)|^{2}}\right)$$
代入得
$$\chi_{k}(t) \simeq \chi_{k=0}(t) e^{-k^{2} / 2 k_{*}^{2}(t)}, \quad \chi_{k=0}(t) \simeq\left(2 a^{3}|m(t)|\right)^{-1 / 2} \exp \left(\int_{t_{1}}^{t} d t|m(t)|\right)$$
$$k_{*}^{2}(t) \equiv\left(\int_{t_{1}}^{t} \frac{d t}{a^{2}|m(t)|}\right)^{-1}$$
$$\left\langle\chi^{2}(t)\right\rangle=\frac{4 \pi}{(2 \pi)^{3}} P_{\chi}(0, \tau) \int_{0}^{\infty} d k k^{2} e^{-\left(k^{2} / k_{*}^{2}(t)\right)}=(2 \pi)^{-3 / 2} P_{\chi}(0, \tau) k_{*}^{3}(t)$$
无量纲化的功率谱为
$$\mathcal{P}_{\delta \chi^{2}}(t, k)=\frac{1}{\sqrt{\pi}}\left\langle\chi^{2}(t)\right\rangle^{2}\left[k / k_{*}(\tau)\right]^{3}$$
计算$\chi$场扰动对曲率扰动功率谱的贡献

$$
\zeta_{\chi}(\mathbf{x}, t)=-H \frac{\delta \rho_{\chi}\left(\mathbf{x}, t_{\mathrm{nl}}\right)}{\dot{\rho}(t)}=\frac{1}{3} \frac{\delta \rho_{\chi}\left(\mathbf{x}, t_{\mathrm{nl}}\right)}{\left\langle\dot{\chi}^{2}\left(t_{\mathrm{nl}}\right)\right\rangle+\dot{\phi}^{2}(t)}
$$
对$k \ll k_{*}$有
$$
\zeta_{\chi}(\mathbf{x})=-\frac{H}{2\left|m\left(t_{\mathrm{nl}}\right)\right|} \frac{\left\langle\dot{\chi}^{2}\left(t_{\mathrm{nl}}\right)\right\rangle}{\left\langle\dot{\chi}^{2}\left(t_{\mathrm{nl}}\right)\right\rangle+\dot{\phi}^{2}\left(t_{\mathrm{nl}}\right)} \frac{\delta \chi^{2}\left(\mathbf{x}, t_{\mathrm{nl}}\right)}{\left\langle\chi^{2}\left(t_{\mathrm{nl}}\right)\right\rangle}
$$
$$
\mathcal{P}_{\zeta_{\chi}}(k) \simeq\left[\frac{H}{2\left|m\left(t_{\mathrm{nl}}\right)\right|} \frac{\left\langle\dot{\chi}^{2}\left(t_{\mathrm{nl}}\right)\right\rangle}{\left\langle\dot{\chi}^{2}\left(t_{\mathrm{nl}}\right)\right\rangle+\dot{\phi}^{2}\left(t_{\mathrm{nl}}\right)}\right]^{2}\left(\frac{k}{k_{*}}\right)^{3} .
$$
在$k_*$处有峰值。

- In the standard picture of hybrid inflation, the corresponding scales reenter the horizon shortly after the end of inflation, leading to the formation of PBHs with relatively low masses: $M_{PBH} \sim \mathcal{O}(10) kg$. These PBHs evaporate in a very short time, compared to the age of the Universe, and cannot contribute to dark matter today. This process can nevertheless eventually contribute to the reheating of the Universe.
	- [9605094](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/9605094_Density-Perturbations-and-Black-Hole-Formation-in-Hybrid-Inflation.pdf)
	- [Lyth 1107.1681](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/1107.1681_PBH-formation-and-hybrid-inflation.pdf)
	- [PRD103504](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/physrevd.85.103504_Formation-of-primordial%20black%20holes%20from%20non-Gaussian-perturbations-produced-in-a-waterfall-transition.pdf)



## 改进模型
 [Massive primordial black holes from hybrid inflation as dark matter and the seeds of galaxies](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/PhysRevD.92.023524_PBH_hybrid%20inflation_DM_Seeds_of_galaxies.pdf)
### Along the valley
$$V(\phi, \psi)=\Lambda\left[\left(1-\frac{\psi^{2}}{M^{2}}\right)^{2}+\frac{\left(\phi-\phi_{\mathrm{c}}\right)}{\mu_{1}}-\frac{\left(\phi-\phi_{\mathrm{c}}\right)^2}{\mu_{2}}+\frac{2\phi^2\psi^2}
{M^2\phi_c^2}\right]$$
跟通常的hybrid势相比，多了$\phi$的一次项，且$\phi$二次项符号变号。
在偏离$\phi_c$处比较远的位置，即在山谷区，$\mu_1$比$\mu_2$足够大，以保证正的一次斜率和负的二次斜率相消得到的势足够平。
在$\phi=\phi_c$处的慢滚参数
$$\begin{array}{c}
\epsilon_{1 \phi_{\mathrm{c}}}=\frac{M_{\mathrm{P}}^{2}}{2}\left(\frac{V^{\prime}}{V}\right)^{2}=\frac{M_{\mathrm{P}}^{2}}{2 \mu_{1}^{2}} \\
\epsilon_{2 \phi_{\mathrm{c}}}=2 M_{\mathrm{P}}^{2}\left[\left(\frac{V^{\prime}}{V}\right)^{2}-\frac{V^{\prime \prime}}{V}\right]=2 M_{\mathrm{P}}^{2}\left(\frac{1}{\mu_{1}^{2}}+\frac{2}{\mu_{2}^{2}}\right)
\end{array}$$
由于$\mu_1>\mu_2$，谱指数
$$n_s=1-2\varepsilon_{1*}-\varepsilon_{2*}$$
被$\varepsilon_2$主导。其中$*$标记在CMB尺度$k_*=0.05Mpc^{-1}$出视界时取值。我们认为场滚过$\phi=\phi_c$处，CMB尺度刚好出视界，因此可估计
$$n_s=1-\frac{4M_P^2}{\mu_2^2}$$
代入当前的测量值$n_s\simeq 0.9603$，得到$\mu_2\simeq 10M_P$。
曲率扰动功率谱为
$$\begin{aligned}
\mathcal{P}_{\zeta}\left(k_{*}\right) & =\frac{H_{*}^{2}}{8 \pi^{2} M_{\mathrm{P}}^{2} \epsilon_{1 *}} \\
& \simeq \frac{\Lambda \mu_{1}^{2}}{12 \pi^{2} M_{\mathrm{P}}^{6}}\left(\frac{k_{*}}{k_{\phi_{\mathrm{c}}}}\right)^{n_{\mathrm{s}}-1} 
\end{aligned}$$
第二个等号用到了$H^2\simeq V/(3M_P^2)$。结合当前的测量值$2.21 \times 10^{-9}$，有
$$\Lambda=2.21 \times 10^{-9} \times \frac{12 \pi^{2} M_{\mathrm{P}}^{6}}{\mu_{1}^{2}}\left(\frac{k_{\phi_{\mathrm{c}}}}{k_{*}}\right)^{n_{\mathrm{s}}-1}$$
### Waterfall phase

#### Quantum diffusion at the critical point
在相变点$\phi_c$附近$\psi$有效质量接近并小于$H$的区域内，量子扩散效应明显，使得$\psi$场此处的场值$\psi_c$相对于0有所偏移，作为后续waterfall经典动力学的初值。不同空间该偏离的分布不同，总体来讲是一个高斯分布。通过$\psi$场的量子随机噪声动力学，可以计算宽度
$$\psi_{0} \equiv \sqrt{\left\langle\psi^{2}\right\rangle}=\left(\frac{\Lambda \sqrt{2 \phi_{\mathrm{c}} \mu_{1}} M}{96 \pi^{3 / 2}}\right)^{1 / 2}$$

#### Background classical dynamics
$$H^{2}=\frac{1}{3 M_{\mathrm{P}}^{2}}\left[\frac{\dot{\phi}^{2}}{2}+\frac{\dot{\psi}^{2}}{2}+V(\phi, \psi)\right]$$
$$\begin{array}{l}
\ddot{\phi}+3 H \dot{\phi}+\frac{\partial V}{\partial \phi}=0, \\
\ddot{\psi}+3 H \dot{\psi}+\frac{\partial V}{\partial \psi}=0 .
\end{array}$$
以上即为双场暴胀的全部动力学。可通过数值计算求解，也可先利用慢滚近似忽略动能项和二阶导项。
在慢滚近似下，引入参数化
$$\phi \equiv \phi_{\mathrm{c}} \mathrm{e}^{\xi}, \quad \psi \equiv \psi_{0} \mathrm{e}^{\chi}$$
$$\begin{array}{r}
3 H \dot{\xi} \simeq-\frac{2 \Lambda}{\mu_{1}^{2}}\left(1+\frac{2 \mu_{1}^{2} \psi^{2}}{M^{2} \phi_{\mathrm{c}}^{2}}\right) \\
3 H \dot{\chi} \simeq-\frac{4 \Lambda}{M^{2}}\left(2 \xi+\frac{\psi^{2}}{M^{2}}\right)
\end{array}$$
且$$H^2=\frac{\Lambda}{3M_P^2}$$
在phase 1期间，两式右侧的第二项均可忽略不计；等到第一式右侧第二项大于1时，进入phase 2。
- phase 1：对方程积分得到$$\xi^2=\frac{M^2}{4\phi_c\mu_1}\chi$$
定义e-fold time，在$\phi=\phi_c$时，$\mathcal{N}=0$，得到$\mathcal{N}=-\frac{\xi\mu_1\phi_c}{M_P^2}$。
总的e-fold数$$N_{1}=\frac{\sqrt{\chi_{2}} \phi_{\mathrm{c}}^{1 / 2} \mu_{1}^{1 / 2} M}{2 M_{\mathrm{P}}^{2}}$$
其中$\chi_2=\ln\left(\frac{\phi_c^{1/2}M}{2\mu_1^{1/2}\psi_0}\right)$，为phase 1到phase 2转变时的$\chi$值。
- phase 2：对方程积分得到$$\xi^{2}=\xi_{2}^{2}+\frac{M^{2}}{8 \phi_{c} \mu_{1}}\left[\mathrm{e}^{2\left(\chi-\chi_{2}\right)}-1\right]$$
其中$\xi_2=-\frac{M\sqrt{\chi_2}}{2\sqrt{\mu_1\phi_c}}$。
当$\psi$场的慢滚近似被破坏时，$\xi_{\text{end}}=-\frac{M^2}{8M_P^2}$，暴胀结束。
考虑mild-waterfall情形，$N\gg 50$时，$\abs{\xi_2}\gg\abs{\xi_{\text{end}}}$，总e-fold数可近似估计为
$$N_{2} \simeq \frac{M \mu_{1}^{1 / 2} \phi^{1 / 2}}{4 M_{\mathrm{P}}^{2} \chi_{2}^{1 / 2}}$$
### Power spectrum of curvature perturbations
利用$\delta N$ formalism，共动动量为$k$的模式计算的功率谱为
$$\mathcal{P}_{\zeta}(k)=\frac{H_{k}^{2}}{4 \pi^{2}}\left(N_{, \psi}^{2}+N_{, \phi}^{2}\right)$$
$$N_{, \phi} \equiv \frac{\partial N_{i}^{f}}{\partial \phi_{k}^{i}}, \quad N_{, \psi} \equiv \frac{\partial N_{i}^{f}}{\partial \psi_{k}^{i}},$$
$N_i^f$对应两个类空超曲面之间的e-fold数，初始曲面选为$t_k$空间平坦的曲面，满足$k/a(t_k)=H(t_k)$。最终曲面选为等能量密度的曲面，$\xi=\xi_{\text{end}}$。
$N_{,\phi(\psi)}$表征初始$t_k$时刻场值$\phi$或者$\psi$变动导致的e-fold数变化。可以拆分为phase 1和phase 2的贡献。
$$N_{1}=-\frac{\mu_{1} \phi_{\mathrm{c}}\left(\xi_{2 \mathrm{i}}-\xi_{\mathrm{i}}\right)}{M_{\mathrm{P}}^{2}}$$
其中
$$\xi_{2 \mathrm{i}} \equiv-\sqrt{\xi_{\mathrm{i}}^{2}+M^{2}\left(\chi_{2}-\chi_{\mathrm{i}}\right) /\left(4 \mu_{1} \phi_{\mathrm{c}}\right)}$$
[Non-Gaussianities and curvature perturbations from hybrid inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/PhysRevD.89.063519_Non-Gaussianities-and-curvature-perturbations-from-hybrid-inflation.pdf)
指出，$(\xi_{2i},\chi_2)$变动导致phase 2期间的e-fold数变化$N_{2,\phi(\psi)}$较小，作为初步估计可忽略。
$$N_{, \phi} \simeq \frac{\mu_{1}}{M_{\mathrm{P}}^{2}}, \quad N_{, \psi} \simeq \frac{M^{2}}{8 M_{\mathrm{P}}^{2} \xi_{2} \psi_{k}}$$
对于$10\simeq N_k\simeq 50$，有$N_{,\phi}\ll N_{,\psi}$。功率谱近似为
$$\mathcal{P}_{\zeta}(k) \simeq \frac{\Lambda M^{2} \mu_{1} \phi_{\mathrm{c}}}{192 \pi^{2} M_{\mathrm{P}}^{6} \chi_{2} \psi_{k}^{2}}$$
其中$\psi_{k}{=\psi_{0} \mathrm{e}^{\chi_{k}}, \chi_{k}=4 \phi_{c} \mu_{1} \xi_{k}^{2} / M^{2}},\text { and } \xi_{k}=-M_{p}^{2}\left(N_{1}+N_{2}-N_{k}\right) /\left(\phi_{c} \mu_{1}\right)$。$N_k$定义为满足$k=\mathrm{e}^{-N_{k}} k_{f}$。
对于在phase 1和phase 2转变期间出视界的模式，功率谱为$$\mathcal{P}_{\zeta}\left(k, t_{k} \simeq t_{1,2}\right) \simeq \frac{\Lambda \mu_{1}^{2}}{48 \pi^{2} p^{2} M_{\mathrm{P}}^{6} \chi_{2}}$$
而深入phase 1出视界的模式，功率谱会得到指数增长
$$\begin{aligned}
\mathcal{P}_{\zeta}(k)= & \mathcal{P}_{\zeta}\left(k, t_{k} \simeq t_{1,2}\right) \\
& \times \exp \left[2 \chi_{2}\left(1-\frac{\left(N_{\text {end }}-N_{k}\right)^{2}}{N_{1}^{2}}\right)\right]
\end{aligned}$$
在phase 1的起点，即临界点$\phi_c$处取极值。
总的来说，phase1起点出视界扰动增强最大，在其往phase2或往山谷方向的量子涨落明显区域，功率谱均得到增强，但相比phase1起点有一个指数因子的下降，功率谱有一个很宽的峰。
![[截屏2023-01-25 14.59.36.png]]


##### Waterfall行为的精细研究
[Non-Gaussianities and curvature perturbations from hybrid inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/PhysRevD.89.063519_Non-Gaussianities-and-curvature-perturbations-from-hybrid-inflation.pdf)
[On the Waterfall Behavior in Hybrid Inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/On-the-Waterfall-Behavior-in-Hybrid-Inflation.pdf)
[Hybrid inflation along waterfall trajectories](file:///Users/lyuzhenhong/Desktop/Academic/Research/PhysRevD.83.063518_Hybrid-inflation-along-waterfall-trajectories.pdf)

It is often assumed that this waterfall phase transition is sudden and inflation soon ends at $\phi=\phi_c$. The true ends of inflation are at the point where the slow-roll conditions are violated, and what we are concerned with is the dynamics between the critical point $\phi=\phi_c$ and this inflation endpoint.




$$

$$



