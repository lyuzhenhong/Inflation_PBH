## new inflation
[new inflation by Linde](file:///Users/lyuzhenhong/Desktop/Academic/Research/NewInflation_Linde.pdf)
原始的暴胀模型（Guth）有以下问题
- The phase transition from the symmetric vacuum state $\varphi=0$ to the asymmetric state $\varphi_0$ proceeds by creation and subsequent expansion of bubbles containing some nonvanishing fields $\varphi$.  It was implicitly assumed that inside these bubbles the scalar field rapidly grows to $\varphi=\varphi_0$, all energy of the bubbles becomes concentrated in their walls and thermalization occurs only after the collision of the walls. If this qualitative picture were correct, the exponential expansion would be finished at the temperature $T_c$, at which the phase transition occurs. For the flatness problem to be solved the universe (the scale factor a) should grow at least $10^{28}$.
	- Since at this period the value of $aT$ is constant, the critical temperature $T_c$ should be $10^{28}$ times smaller than the temperature $T_0$, at which the exponential expansion starts. In the simplest SU(5) model $T_0\sim 10^{14}GeV$, so that $T_c\simeq 10^{-14}GeV$. No GUTs with such a fantastically small value of the critical temperature have been suggested.
- If the bubble wall collisions are necessary for the reheating of the universe, then after such a phase transition the universe becomes greatly inhomogeneous and anisotropic, which would contradict cosmological data.



With this purpose we shall consider the phase transitions in GUTs with the Coleman-Weinberg mechanism of symmetry breaking.
The one-loop effective potential for the symmetry breaking $SU(5) \to SU(3) \times SU(2) \times U(1)$ in the Coleman-Weinberg version of this model at finite temperature $T$
$$\begin{array}{l}
V(\varphi, T)=\left(18 T^{4} / \pi^{2}\right) \\
\quad \times \int_{0}^{\infty} \mathrm{d} x x^{2} \ln \left\{1-\exp \left[-\left(x^{2}+25 g^{2} \varphi^{2} / 8 T^{2}\right)^{1 / 2}\right]\right\} \\
\quad+\left(5625 / 512 \pi^{2}\right) g^{4}\left[\varphi^{4} \ln \left(\varphi / \varphi_{0}\right)-\varphi^{4} / 4+\varphi_{0}^{4} / 4\right]
\end{array}$$
其中$\varphi_0\sim 10^{14}GeV$, $g^2\sim 1/3$ is the gauge coupling constant. 

Let us suppose that the phase transition in the Coleman-Weinberg SU(5) theory occurs at $T_c \approx 2 \times 10^6 GeV$, and $H$ is equal to $1.5\times 10^{10}GeV$，thus the efold number will be $H\tau\sim H/T_c\sim 3000$, much larger than the observable universe $l\sim 10^{28}cm$. Therefore the whole observable part of the universe is contained inside one bubble, so we see no inhomogeneities caused by the wall collisions.

Inflation持续足够长时间要求
$$
\frac{\Gamma}{H^4}\ll 1
$$
Gracefully exit要求
$$
\frac{\Gamma}{H^4}>1
$$
不能两全

Linde $\Gamma$
steinhanrdt $H$

## chaotic inflation
[chaotic inflation by Linde](file:///Users/lyuzhenhong/Desktop/Academic/Research/ChaoticInflation_Linde.pdf)
我们对暴胀的动力学描述是经典的。

经典场$\varphi$的取值在空间上是任意的，因此可以预期不同的取值会在不同的区域出现。例如$\varphi\gg M_P$的取值应当是完全合理的，但需注意$(\partial_\mu\varphi)^2\lesssim M_P^4$，因为当前理论没有办法描述Planck尺度下的时空。

另一方面，我们必须一直要求暴胀势$V(\varphi)<M_P^4$(暴胀场的动能和热平衡能均随宇宙膨胀被稀释)，这对于暴胀场的初值给出了要求。

对宇宙的经典描述在Planck时间$t_P$后才有效，在那之前，宇宙被认为处于混沌量子态。例如对于$V(\varphi)=\frac{\lambda}{4}\varphi^4$，我们可以预期$t_P$后$\abs{\varphi}<(\frac{4}{\lambda})^{1/4}M_P$内的不同取值都能出现。因此完全可能存在一块区域，均匀布满$M_P\lesssim \abs{\varphi}\lesssim \frac{M_P}{\lambda^{1/4}}$的场值。

当然，暴胀场取任何初值最后都会回落到吸引子上。但是不同的初值影响膨胀。
$$H=\left(\frac{8}{3} \pi V(\varphi) / M_{\mathrm{p}}^{2}\right)^{1 / 2}=\left(\frac{2}{3} \pi \lambda\right)^{1 / 2} \varphi^{2} / M_{\mathrm{P}}$$
$$\ddot{\varphi}+3 H \dot{\varphi}=-\lambda \varphi^{3}$$
对于$\varphi^2\gg M_P^2/(6\pi)$，忽略第三项，得到$\varphi=\varphi_{0} \exp \left\{-\left[\sqrt{\lambda} M_{\mathrm{P}} /(6 \pi)^{1 / 2}\right] t\right\}$。
尺度因子和efold数受初值影响
$$a(\Delta t) \sim a_{0} \exp (H \Delta t) \sim a_{0} \exp \left(2 \pi \varphi_{0}^{2} / M_{\mathrm{P}}^{2}\right)$$
我们的宇宙要求efold数约为65，只要$\varphi_0\sim3M_P$。这落在上述区间内。但是显然大于这个值的初值区域也是存在的，它们的尺度比我们的宇宙相比指数增长，对应着更混沌的初态。

"初值为0，被量子激发到不同的值作为暴胀经典运动方程的初值，有大有小，大的对应更大的宇宙。"

[Introduction to cosmic inflation and Dark Enenrgy](file:///Users/lyuzhenhong/Desktop/Academic/Research/monograph/(Series%20in%20Astronomy%20and%20Astrophysics)%20Konstantinos%20Dimopoulos%20-%20Introduction%20to%20Cosmic%20Inflation%20and%20Dark%20Energy-CRC%20Press%20(2020).pdf)
暴胀势的形式为
$$V(\phi)=V_0\left(\frac{\phi}{M_P}\right)^q$$
$\phi$场先从0由量子激发到初值，滚到平衡位置附近，伴随着Hubble阻尼做振荡。

在chaotic inflation中，慢滚并不是通过势很平来实现，而是通过大的Hubble阻尼项。根据$H^2=\frac{1}{3M_P^2}[\frac{1}{2}\dot{\phi}^2+V(\phi)]$，大的初值对应大的阻尼项。

慢滚参数为
$$\varepsilon=\frac{q^{2}}{2}\left(\frac{m_{P}}{\phi}\right)^{2} \quad \text { and } \quad \eta=q(q-1)\left(\frac{m_{P}}{\phi}\right)^{2}$$
据此也可看出大的场值更容易慢滚。

根据当前的谱指数和张标比测量值，可以限制$q<1/2$。这排除了原始的$\frac{1}{2}m^2\phi^2$和$\frac{1}{4}\lambda\phi^4$理论。$q=2/5$的情形对应axion monodromy inflation。


chaotic inflation的意义在于：inflation在某个初值进入慢滚前的相变机制是不重要的。可能有不同的机制和途径set到不同初值，但是重要的是之后能否进入慢滚

## chaotic new inflation
[Chaotic new inflation and formation of primordial black holes](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/physrevd.58.083510_Chaotic-new-inflation-and-formation-of-PBH.pdf)
该机制可以让单个场实现double inflation。
其暴胀势在0有不稳定极小值，在两旁有稳定极小值，例如四次双阱势。
下面考虑两类暴胀势，它们在$\phi=v$处有全局最小值。
$$V_{\mathrm{Coleman-Weinberg}}[\phi]=\frac{\tilde{\lambda}}{4} \phi^{4}\left(\ln \left|\frac{\phi}{v}\right|-\frac{1}{4}\right)+\frac{\tilde{\lambda}}{16} v^{4}$$
$$V_\mathrm{DW}[\phi]=\frac{\lambda}{4}(\phi^2-v^2)^2$$
它们在较大场值，即$\phi\gg M_P>v$处均退化为$V=\frac{\lambda}{4}\phi^4$ (Coleman-Weinberg势中的$\tilde{\lambda}\ln\abs{\phi/v}$重定义为$\lambda$)，因此等价为chaotic inflation。
$$\begin{array}{c}
3 H \dot{\phi}=-V^{\prime}[\phi] \\
H^{2}=\left(\frac{\dot{a}}{a}\right)^{2}=\frac{8 \pi}{3 M_{P}^{2}} V[\phi],
\end{array}$$
$$\phi(t)=\phi_{i} \exp \left(-\sqrt{\frac{\lambda}{6 \pi}} M_{P}\left(t-t_{i}\right)\right)$$
$$a(t)=a_{i} \exp \left[\frac{\pi}{M_{P }^{2}}\left(\phi_{i}^{2}-\phi^{2}(t)\right)\right]$$
暴胀条件在$\phi_e\simeq \max(M_P/(8\pi),4v)$处失效。$\phi$到$\phi_e$期间的efold数为
$$N\left(\phi \rightarrow \phi_{e}\right)=\frac{\pi}{M_{P l}^{2}}\left(\phi^{2}-\phi_{e}^{2}\right) \simeq \frac{\pi}{M_{P l}^{2}} \phi^{2}$$
共动尺度$l=2\pi/k$下的曲率扰动和密度扰动为
$$\Phi\left(l=\frac{2 \pi}{k}\right)=\left.f \frac{H}{|\dot{\phi}|} \delta \phi\right|_{t_{k}}=\left.f \frac{H^{2}}{2 \pi|\dot{\phi}|}\right|_{t_{k}} \equiv f \Delta\left(t_{k}\right)=f \sqrt{\frac{2 \pi \lambda}{3}}\left(\frac{\phi\left(t_{k}\right)}{M_{P l}}\right)^{3} \simeq \frac{f}{\pi} \sqrt{\frac{2 \lambda}{3}} N_{k e}^{3 / 2}$$
其中$f=3/5(2/3)$对应物质主导(辐射主导)时期。
一般的单场暴胀机制中，由CMB各向异性的数据($\delta T/T\simeq 10^{-5}$)来限制模型参数$\lambda\simeq 10^{-13}$。然而在chaotic new inflation机制中，$N_{ke}$可以取小一点，得到的$\lambda$量级也会下降。
下面讨论new inflation。此时两类势的情况会有所区别。
首先是CW势，在原点附近可约化为
$$V_{\mathrm{CW}}[\phi] \simeq V_{0}-\frac{\hat{\lambda}}{4} \phi^{4}$$
其中$\hat{\lambda}=\tilde{\lambda}\ln\abs{\phi_s/v}$，$V_0=\tilde{\lambda}v^4/{16}$。
$$\begin{aligned}
H^{2} & =H_{0}^{2}=\frac{8 \pi V_{0}}{3 M_{P l}^{2}}, \\
\hat{\lambda} \phi^{2} & =\frac{3 H_{0}^{2}}{2 N\left(\phi \rightarrow \phi_{f}\right)+1} \simeq \frac{3 H_{0}^{2}}{2 N\left(\phi \rightarrow \phi_{f}\right)},
\end{aligned}$$
$f$记为new inflation的终点。
密度扰动为$$\Phi(l)=\frac{f}{\pi} \sqrt{\frac{2 \hat{\lambda}}{3}} N_{k f}^{3 / 2}$$
注意到$\hat{\lambda}\sim 10^{-10}$，$N_{kf}$不能大于$60$，因此CW势并不能产生足够大的密度扰动 ($10^{-4}$)。
下面是DW势。在原点附近写为
$$V_{\mathrm{DW}}[\phi] \simeq V_{0}-\frac{1}{2} m^{2} \phi^{2}$$
其中$V_0=\tilde{\lambda}v^4/{4}$，$m^2=\lambda v^2$。
慢滚解为
$$\begin{array}{c}
\phi(t)=\phi_{s} \exp \left[\frac{m^{2}}{3 H_{0}^{2}} H_{0}\left(t-t_{s}\right)\right], \\
H_{0}^{2}=\frac{8 \pi V_{0}}{3 M_{P l}^{2}}, \quad a(t) \sim e^{H_{0} t} .
\end{array}$$
暴胀在$\phi_f=cv$处结束，其中$c\sim\mathcal{O}(0.1)$。计算得到
$$
N\left(\phi \rightarrow \phi_{f}\right)=\frac{3 H_{0}^{2}}{m^{2}} \ln \frac{\phi_{f}}{\phi}=\frac{3 H_{0}^{2}}{m^{2}} \ln \frac{c v}{\phi}
$$
$$
\begin{aligned}
\Phi(l) & =f \Delta_{\mathrm{SR}}\left(t_{k}\right) \equiv 3 f \frac{H_{0}^{2}}{m^{2}} \frac{H_{0}}{2 \pi \phi\left(t_{k}\right)} \\
& =\frac{3 f}{2 \pi} \frac{H_{0}^{3}}{m^{2} \phi_{f}} \exp \left(\frac{m^{2}}{3 H_{0}^{2}} N_{k f}\right)
\end{aligned}
$$
注意上述经典的慢滚解只在经典势梯度效应比量子随机涨落导致的扩散效应大时才成立。换句话说，在一个Hubble时间内，场的经典运动$\Delta\phi=\abs{\dot{\phi}}H^{-1}$，应该比量子涨落在一个Hubble时间内累积的变化$\delta\phi=H/(2\pi)$要大。代入$\phi\sim\exp[m^2/(3H_0^2)H_0(t-t_s)]$，条件化为
$$\abs{\phi}>\frac{3H_0^3}{2\pi m^2}\equiv\phi_q$$
如果$\phi$在$\abs{\phi}<\phi_q$停留超过一个Hubble时间，那么量子涨落将会主导动力学，宇宙进入一个永无止境的自我复制环节。那么chaotic inflation的影响将会被冲刷干净。
注意到$$\Delta_{SR}==\frac{3H_{0}^{3}}{2\pi m^{2}}\frac{1}{\phi_{f}}\frac{\phi_f}{\phi}=\frac{3H_{0}^{3}}{2\pi m^{2}}\frac{1}{\phi}=\frac{\phi_q}{\phi}$$若要求密度扰动的幅度得到增强，必须让$\phi$在$\abs{\phi}<\phi_q$的区域内停留一段时间，这意味着我们比如调节参数让$\phi$快速经过，以便符合我们的扰动增强幅度($\mathcal{O}(10^{-2})$)。
$\Phi$的表达式意味着谱指数为$n=1-\frac{2m^2}{3H_0^2}<1$。
$$\max \Phi=3 f \frac{H_{0}^{2}}{m^{2}} \frac{H_{0}}{2 \pi \phi_{s}}$$


