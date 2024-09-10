[Recent progress in Higgs inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/Higgs_inflation/2103.00177_Progress-in-Higgs-inflation.pdf)
[Higgs inflation review](file:///Users/lyuzhenhong/Desktop/Academic/Research/Higgs_inflation/Higgs_inflation_review.pdf)
[Higgs inflation at the critical point](file:///Users/lyuzhenhong/Desktop/Academic/Research/Higgs_inflation/Higgs%20inflation%20at%20the%20critical%20point.pdf)
[Overshooting critical Higgs inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/Higgs_inflation/Overshooting,%20critical%20Higgs%20inflation%20and%20second%20order%20gravitational%20wave%20signatures.pdf)
[PBH production in CHI](file:///Users/lyuzhenhong/Desktop/Academic/Research/Higgs_inflation/Primordial-black-hole-production-in-Critical-Higgs-Inflation.pdf)

[Conformal Transformations with multiple scalar fields](file:///Users/lyuzhenhong/Desktop/Academic/Research/PhysRevD.81.084044_Conformal%20transformations%20with%20multiple%20scalar%20fields.pdf)

## Modified gravity
The action principle is also employed in general relativity (GR). In fact, the Lagrangian density of GR is deceptively simple, given by
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
To that end, we first utilize a conformal transformation to the Einstein frame.
$$\tilde{g}_{\mu \nu}=\Omega^{2} g_{\mu \nu}=\left(1+\xi h^{2}\right) g_{\mu \nu}$$
Then we use a field redefinition to obtain a canonical kinetic term.
$$\begin{aligned}
\dv{ \chi}{h} & =\sqrt{\frac{f(h)+3 f(h)^{\prime 2}}{2 f(h)^{2}}} \\
& =\sqrt{\frac{1+\xi h^{2}+6\left(h \xi+\frac{1}{2} h^{2} \xi^{\prime}\right)^{2}}{\left(1+\xi h^{2}\right)^{2}}}
\end{aligned}$$
$$\Rightarrow S_{E}=-\int \dd[4] x \sqrt{-\tilde{g}}\left[\frac{1}{2} \tilde{R}-\frac{1}{2} \partial_{\mu} \chi \partial^{\mu} \chi+V(\chi)\right]$$
## Critical Higgs Inflation

[[Metastability of EW vacuum]]

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
$$
\mu g(x)\dv{x}{N}=\dv{\chi}{N}=\dv{\chi}{t}\dv{t}{N}=\frac{V'}{3H^2}=\frac{V'}{V}=[\mu g(x)]^{-1}\frac{{\dd V}/{\dd x}}{V}
$$
$$
\dv{x}{N}=\frac{1}{[\mu g(x)]^{2}V}\dv{V}{x}
$$
$$\begin{aligned}
\mu & {\left[\frac{d^{2} x}{d N^{2}} g(x)+\frac{d x}{d N} \frac{d g(x)}{d N}\right] } +3 \mu g(x) \frac{d x}{d N}-\frac{1}{2}\left(\mu g(x) \frac{d x}{d N}\right)^{3} \\
& +\left[3-\frac{1}{2}\left(\mu g(x) \frac{d x}{d N}\right)^{2}\right] \frac{1}{\mu g(x)} \frac{V^{\prime}(x)}{V(x)}=0
\end{aligned}$$
$$\begin{array}{l}
g(x)&=\displaystyle\sqrt{\frac{1+\xi h^{2}+6\left(h \xi+\frac{1}{2} h^{2} \xi^{\prime}\right)^{2}}{2\left(1+\xi h^{2}\right)^{2}}}\\
&=\displaystyle\left\{\frac{1+c(1+b\ln{x})x^2+6[\frac{c}{\mu}((1+b\ln{x})x+\frac{1}{2}bx)]^2}{2(1+c(1+b\ln{x})x^2)^2}\right\}^{1/2}
\end{array}$$



