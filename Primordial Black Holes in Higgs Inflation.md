[Recent progress in Higgs inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/2103.00177_Progress-in-Higgs-inflation.pdf)
[Higgs inflation review](file:///Users/lyuzhenhong/Desktop/Academic/Research/Higgs_inflation_review.pdf)
[Higgs inflation at the critical point](file:///Users/lyuzhenhong/Desktop/Academic/Research/Higgs%20inflation%20at%20the%20critical%20point.pdf)
[Overshooting critical Higgs inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/Overshooting,%20critical%20Higgs%20inflation%20and%20second%20order%20gravitational%20wave%20signatures.pdf)
[PBH production in CHI](file:///Users/lyuzhenhong/Desktop/Academic/Research/Primordial-black-hole-production-in-Critical-Higgs-Inflation.pdf)

[Conformal Transformations with multiple scalar fields](file:///Users/lyuzhenhong/Desktop/Academic/Research/PhysRevD.81.084044_Conformal%20transformations%20with%20multiple%20scalar%20fields.pdf)

## Modified gravity
The action principle is also employed in general relativity (GR). In fact the Lagrangian density of GR is deceptively simple, given by
$$\mathcal{L}=\frac{R}{16 \pi G}=\frac{1}{2} m_{P}^{2} R$$
The spacetime integral of the above is called the Einstein-Hilbert action.
However, for a long time (almost immediately after its inception) there have been numerous efforts to go beyond and generalise GR. One of the most prominent attempts to do this is scalar-tensor theory in which the gravitational action is written as
$$S=\int d^{4} x \sqrt{-g}\left[\frac{1}{2} m_{P}^{2} f(R, \chi)+\frac{1}{2} j(\chi)(\partial \chi)^{2}-U(\chi)\right]$$
this proposal mixes gravity with a scalar field, which is in fact part of the matter content of the theory.
We may formulate the theory in Eq. (7.58) so that the Einstein-Hilbert action reemerges and the theory appears as normal GR. This is done through a conformal transformation of the metric $g_{\mu\nu}\to\Omega^2 g_{\mu\nu}$. where the conformal factor $\Omega$ can be a function of both the location in spacetime and also of the field $\chi$. To yield the desired GR action the conformal factor must be chosen to be $\Omega^2=\pdv{f}{R}$.
Now, the kinetic term of the scalar field χ is in general noncanonical, meaning it is not of the form $1/2(\partial\chi)^2$.  In the case when $\Omega^2$ is determined only by a single degree of freedom, we can generate the canonically normalised scalar field $\phi$ through the expression
$$\phi=\int d \chi \sqrt{\frac{3}{2} m_{P}^{2}\left(\frac{\partial \ln \Omega^{2}}{\partial \chi}\right)^{2}+\frac{j(\chi)}{\Omega^{2}}}$$
$$S=\int d^{4} x \sqrt{-g}\left[\frac{1}{2} m_{P}^{2} R+\frac{1}{2}(\partial \phi)^{2}-V(\phi)\right]$$
with $V=\Omega^{-4}U$.
The above can be better understood when put in action, as we do below. Before this we need to briefly discuss the meaning of the conformal transformation. This is not a coordinate transformation, because GR is invariant under those. It is a transformation which mixes the gravitational field with the matter content of spacetime, meaning it redefines the gravitational and matter degrees of freedom. A particular definition of the gravitational degrees of freedom is called a (conformal) frame.∗ If gravity is described by GR and the gravitational action is the Einstein-Hilbert action then we say we are in the Einstein frame. In contrast, if gravity is not GR, as with $f\neq R$, then we say that we are in the Jordan frame.
However, there are subtleties that make this difficult, having to do with the choice of a cutoff (MP in case of GR) or of a “smooth” gravitational background in quantum field theory in curved spacetime. When differences do appear between frames, it is still debatable, which is the “true” frame, the Einstein or the Jordan one.

## Higgs inflation
Higgs inflation, equivalently Starobinsky’s inflation with a $R^2$ term, attracts special attention as it provides the best fit to the astrophysical and cosmological observations. 

However, Higgs inflation is not free from theoretical issues: most notably, ==its original setup requires a large nonminimal coupling== $\xi ∼ 10^4$ that leads to a low cutoff $$\Lambda \lesssim M_{P} / \xi \ll M_{P}$$
>minimal coupling
 $S=-\int\dd[4]{x}\sqrt{-g}\left[\frac{1}{2}{R}-\frac{1}{2}\partial_\mu h\partial^\mu h+V(h)\right]$
 $V(h)=\frac{\lambda(h)}{4}h^4$

>Neglecting the kinetic term during inflation, both theories are equivalent since $L/\sqrt{-g} \supset (M^2 + \xi\phi^2)R/2 - \lambda\phi^4/4$  is mapped to $M^2R/2 + (\xi^2/4\lambda)R^2$ by solving the field equation for $\delta\phi$.

==Jordan frame==
$$\begin{aligned}
S_{J} & =-\int \dd[4] x \sqrt{-g} \\
& \times\left[\frac{1}{2}\left(1+\xi(h) h^{2}\right) R-\frac{1}{2} \partial_{\mu} h \partial^{\mu} h+\frac{\lambda(h)}{4} h^{4}\right] \\
& =-\int \dd[4] x \sqrt{-g}\left[f(h) R-\frac{1}{2} \partial_{\mu} h \partial^{\mu} h+\frac{\lambda(h)}{4} h^{4}\right]
\end{aligned}$$
The crucial observation is that for realistic values of the relevant SM parameters, the running Higgs self-coupling $\lambda$ attains a minimum at scale $\mu$. Near this minimum it can then be expanded as:
$$\lambda(h)=\lambda_{0}+b_{\lambda} \ln ^{2}\left(\frac{h}{\mu}\right)$$
($h>\mu$, $h<\mu$都有$\lambda(h)>\lambda(\mu)$。)
The running non-minimal coupling $\xi$ to the Ricci scalar is also expanded around scale $\mu$:
$$\xi(h)=\xi_0+b_\xi\ln\left(\frac{h}{\mu}\right)$$
since $\xi$ does not have an extremum at scale $\mu$, the leading energy dependence is described by a term linear, rather than quadratic, in $\ln(h/\mu)$.

In order to use standard results for the inflationary dynamics we transform to the ==Einstein frame==, where gravity is described by the well-known Einstein–Hilbert action and the inflaton is described by a canonically normalized field $\chi$.
To that end we first utilize a conformal transformation to the Einstein frame.
$$\tilde{g}_{\mu \nu}=\Omega^{2} g_{\mu \nu}=\left(1+\xi h^{2}\right) g_{\mu \nu}$$
Then we use a field redefinition to obtain a canonical kinetic term.
$$\begin{aligned}
\dv{ \chi}{h} & =\sqrt{\frac{f(h)+3 f(h)^{\prime 2}}{2 f(h)^{2}}} \\
& =\sqrt{\frac{1+\xi h^{2}+6\left(h \xi+\frac{1}{2} h^{2} \xi^{\prime}\right)^{2}}{\left(1+\xi h^{2}\right)^{2}}}
\end{aligned}$$
$$\Rightarrow S_{E}=-\int \dd[4] x \sqrt{-\tilde{g}}\left[\frac{1}{2} \tilde{R}-\frac{1}{2} \partial_{\mu} \chi \partial^{\mu} \chi+V(\chi)\right]$$
## Critical Higgs Inflation
For the currently known Higgs masses and top quark masses, the EW Higgs potential is known to be metastable as $\lambda$ becomes negative when the renormalization scale is $\mu \simeq \mathcal{O}(10^{10}GeV)$.
$$\left.\lambda(\mu)\right|_{\mu=h}=\lambda_{\min }+\frac{\beta_{2}^{\mathrm{SM}}}{\left(16 \pi^{2}\right)^{2}} \ln ^{2}\left(\frac{h}{h_{\min }}\right)$$
with $\beta_2^{\text{SM}}=0.5$, $\mu_{\text{min}}=h_{\text{min}}\sim 10^{17}-10^{18}GeV$.

The self-coupling $\lambda$ of the Higgs boson in the Standard Model may show critical behavior, i.e. the Higgs potential may have a point at an energy scale $\sim 10^{17−18} GeV$ where both the first and second derivatives (almost) vanish.

> Higgs势变得unbounded


Introduce the quantities
$$
\begin{array}{l}
x=\frac{h}{\mu}, a=\frac{b_{\lambda}}{\lambda_{0}}, b=\frac{b_{\xi}}{\xi_{0}}, \\
c=\xi_{0} \mu^{2} \text { and } V_{0}=\frac{\lambda_{0} \mu^{4}}{4} .
\end{array}
$$
The inflation potential can then be written as
$$
V(x)=\frac{V_{0}\left(1+a \ln ^{2} x\right) x^{4}}{\left[1+c(1+b \ln x) x^{2}\right]^{2}}
$$
Note that for nonminimal coupling $\xi \neq 0$ the potential approaches a constant as $x\to\infty$; it is this “flattening” which allows inflation.

> 非最小耦合项使得暴胀势变平

Consistency with the CMB observables and with current measurements of SM parameters can be obtained for parameter values in some ranges.  We mainly work with a representative set of parameters:
$$
\begin{array}{l}
\lambda_{0}=2.23 \times 10^{-7}, \xi_{0}=7.55, \mu^{2}=0.102 \\
b_{\lambda}=1.2 \times 10^{-6}, \text { and } b_{\xi}=11.5
\end{array}
$$
The inflaton potential for these values of the parameters is shown below. It features an inflection point at $x = x_c = 0.784$. 

>The potential can be expressed in analytical form only in terms of $h$ or $x$, not in terms of the canonical variable $\chi$. However, $\dv{V}{x} = \dv[2]{V}{x}=0$ at $x=x_c$ implies $\dv{V}{\chi}=\dv[2]{V}{\chi} =0$ at $\chi=\chi_c = \chi(x_c )$, i.e. the potential of the canonically normalized inflaton also has an inflection point. In fact, $V(\chi)$ is qualitatively similar to $V(x)$.

![[截屏2023-01-26 14.50.51.png]]
$$\ddot{\chi}+3 H \dot{\chi}+\frac{d V}{d \chi}=0$$
利用$\dd{N}=H\dd{t}$
$$
\frac{d^{2} \chi}{d N^{2}}+3 \frac{d \chi}{d N}-\frac{1}{2}\left(\frac{d \chi}{d N}\right)^{3}+\left[3-\frac{1}{2}\left(\frac{d \chi}{d N}\right)^{2}\right] \frac{V^{\prime}(\chi)}{V(\chi)}=0
$$
$x=h/\mu$, $\displaystyle\dv{\chi}{h}=g(x)$
$$\begin{aligned}
\mu & {\left[\frac{d^{2} x}{d N^{2}} g(x)+\frac{d x}{d N} \frac{d g(x)}{d N}\right] } +3 \mu g(x) \frac{d x}{d N}-\frac{1}{2}\left(\mu g(x) \frac{d x}{d N}\right)^{3} \\
& +\left[3-\frac{1}{2}\left(\mu g(x) \frac{d x}{d N}\right)^{2}\right] \frac{1}{\mu g(x)} \frac{V^{\prime}(x)}{V(x)}=0
\end{aligned}$$
$$\begin{array}{l}
g(x)&=\displaystyle\sqrt{\frac{1+\xi h^{2}+6\left(h \xi+\frac{1}{2} h^{2} \xi^{\prime}\right)^{2}}{2\left(1+\xi h^{2}\right)^{2}}}\\
&=\displaystyle\left\{\frac{1+c(1+b\ln{x})x^2+6[\frac{c}{\mu}((1+b\ln{x})x+\frac{1}{2}bx)]^2}{2(1+c(1+b\ln{x})x^2)^2}\right\}^{1/2}
\end{array}$$


## Higgs-$R^2$ Inflation
- The original setup of Higgs inflation requires a large nonminimal coupling $\xi \sim 10^4$ that leads to a low cutoff $\Lambda \lesssim M_P /\xi \ll M_P$

#### Unitray Problem

[Higgs Inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/1008.5157_Higgs%20inflation-%20consistency%20and%20generalisations.pdf)

对小场值情形$\phi<M_P/\xi$（对应当前宇宙），
$$h \simeq \phi+\sqrt{\frac{3}{2}} \frac{\xi \phi^{2}}{M_{P}}$$
$$\left(\partial_{\mu} h\right)^{2}=\left(\partial_{\mu} \phi\right)^{2}+\frac{3}{2} \frac{\xi^{2}}{M_{P}^{2}} \phi^{2}\left(\partial_{\mu} \phi\right)^{2}+\cdots$$
理论在$E\gtrsim \Lambda = M/\xi$变为强耦合。

对于暴胀时期（$\bar{\phi}\gg M_P/\xi$），有效的自由度是暴胀场关于经典背景的扰动
$$
g_{\mu\nu}=\eta_{\mu\nu}+h_{\mu\nu},\ \phi=\bar{\phi}+\delta\phi
$$

能标由量纲大于4的有效算符
$$\frac{\mathcal{O}_{(n)}(\delta \phi)}{\left[\Lambda_{(n)}(\bar{\phi})\right]^{n-4}}$$

确定。领头阶
$$\sqrt{\xi}\bar{\phi}\left(\delta\phi\right)^{2}\square h=\frac{\mathcal{O}_{(5)}}{\Lambda}$$

意味着
$$
\Lambda^J=\sqrt{\xi}\bar{\phi}
$$
这大于暴胀能标。因此幺正性被保证。


对于重加热时期，$M_{P} / \xi \ll \bar{\phi} \ll M_{P} / \sqrt{\xi}$

$$\frac{\xi^{2}}{M_{P}^{2}} \bar{\phi}^{2}\left(\delta\phi\right)^{2}\square h=\frac{\mathcal{O}_{(5)}}{\Lambda}$$

截断能标为
$$\Lambda^{J} \simeq \frac{\xi \bar{\phi}^{2}}{M_{P}}$$

重加热时期，规范玻色子的纵向极化自由度会猛烈地衰变，末态粒子的动量为$k\simeq \mathcal{O}(\sqrt{\lambda}M_P)$，这大于重加热时期的截断能标。在截断能标之上，衰变过程会破坏幺正性。


[Higgs-R2 Inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/1912.12032_Primordial-Black-Holes-in-Higgs-R2-Inflation-as-the-Whole-of-Dark-Matter.pdf)
[Progress in Higgs Inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/2103.00177_Progress-in-Higgs-inflation.pdf)

$$S_{J}=\int d^{4} x \sqrt{-g_{J}}\left[F\left(h, R_{J}\right)-\frac{1}{2} g^{\mu \nu} \nabla_{\mu} h \nabla_{\nu} h-\frac{\lambda}{4} h^{4}\right]$$

$$F\left(h, R_{J}\right)=\frac{M_{P}^{2}}{2}\left(R_{J}+\frac{\xi h^{2}}{M_{P}^{2}} R_{J}+\frac{R_{J}^{2}}{6 M^{2}}\right)$$

The scalaron mass $M\lesssim M_P/\xi$。

The scalaron $s$ is defined as

$$\sqrt{\frac{2}{3}} \frac{s}{M_{P}}=\ln \left(1+\frac{\xi h^{2}}{M_{P}^{2}}+\frac{R_{J}}{3 M^{2}}\right) \equiv \Omega(s)$$

$g_{\mu\nu}=e^{\Omega{(s)}}g^J_{\mu\nu}$，


$$S=\int d^{4} x \sqrt{-g}\left[\frac{M_{P}^{2}}{2} R-\frac{1}{2} G_{a b} g^{\mu \nu} \nabla_{\mu} \phi^{a} \nabla_{\nu} \phi^{b}-U\left(\phi^{a}\right)\right]$$

$$U\left(\phi^a\right)\equiv e^{-2 \Omega(s)}\left\{\frac{3}{4} M_{P}^{2} M^{2}\left(e^{\Omega(s)}-1-\frac{\xi h^{2}}{M_{P}^{2}}\right)^{2}+\frac{\lambda(\mu)}{4} h^{4}\right\}$$

$$
\left(\phi^a\right)=\left(s,h\right)
$$
非平凡场空间的度规为
$$G_{a b}=\left(\begin{array}{cc}
1 & 0 \\
0 & e^{-\Omega(s)}
\end{array}\right)$$

$$D_{t} \dot{\phi}^{a}+3 H \dot{\phi}^{a}+G^{a b} D_{b} U=0$$
其中
$$D_{a} \phi^{b}=\partial_{a} \phi^{b}+\Gamma_{c a}^{b} \phi^{c}, \Gamma_{c a}^{b}=\frac{1}{2} G^{b e}\left(\partial_{c} G_{a e}+\partial_{a} G_{e c}-\partial_{e} G_{c a}\right), D_t=\dot{\phi}^a\nabla_a$$

单圈beta函数
$$\begin{array}{l}
\beta_{\alpha}=-\frac{1}{16 \pi^{2}} \frac{(1+6 \xi)^{2}}{18} \\
\beta_{\xi}=-\frac{1}{16 \pi^{2}}\left(\xi+\frac{1}{6}\right)\left(12 \lambda+6 y_{t}^{2}-\frac{3}{2} g^{2}-\frac{9}{2} g^{2}\right) \\
\beta_{\lambda} =\beta_{\mathrm{SM}}+\frac{1}{16 \pi^{2}} \frac{2 \xi^{2}(1+6 \xi)^{2} M^{4}}{M_{P}^{4}}
\end{array}$$

其中
$\alpha=M_P^2/(12M^2)$。

重整化跑动
$$\begin{array}{l}
\left.\lambda(\mu)\right|_{\mu=h}=\lambda_{m}+\frac{\beta_{2}^{\mathrm{SM}}}{\left(16 \pi^{2}\right)^{2}} \ln ^{2}\left(\sqrt{\frac{h^{2}}{h_{m}^{2}}}\right)=\lambda_{m}+b \ln ^{2}\left(\sqrt{\frac{h^{2}}{h_{m}^{2}}}\right) \\
\left.\xi(\mu)\right|_{\mu=h}=\xi_{0}+2 \beta_{\xi}^{0} \ln \left(\sqrt{\frac{h^{2}}{h_{m}^{2}}}\right)=\xi_{0}+b_{\xi} \ln \left(\sqrt{\frac{h^{2}}{h_{m}^{2}}}\right)
\end{array}$$

[Tachyonic instability](file:///Users/lyuzhenhong/Desktop/Academic/Research/2205.14813_Tachyonic%20Instability%20induced%20in%20Higgs-R2%20Inflation.pdf)


