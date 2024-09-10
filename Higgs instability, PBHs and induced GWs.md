## Ref List 
[A cosmological signature of the SM Higgs instability: gravitational waves](file:///Users/lyuzhenhong/Desktop/Academic/Research/Espinosa_2018_J._Cosmol._Astropart._Phys._2018_012_HiggsVacuumInstability_GW.pdf)
[Cosmological Signature of the Standard Model Higgs Vacuum Instability: Primordial Black Holes as Dark Matter](file:///Users/lyuzhenhong/Desktop/Academic/Research/PBH/10.1103_PhysRevLett.120.121301_HiggsVacuumInstability_PBH.pdf)
[Cosmological implications of the Higgs mass measurement](file:///Users/lyuzhenhong/Desktop/Academic/Research/Espinosa_2008_J._Cosmol._Astropart._Phys._2008_002_Cosmological%20implications%20of%20the%20Higgs%20mass%20measurement.pdf)
[The cosmological Higgstory of the vacuum instability](file:///Users/lyuzhenhong/Desktop/Academic/Research/JHEP09(2015)174_The%20cosmological%20Higgstory.pdf)
[Electroweak Vacuum Stability in Light of BICEP2](file:///Users/lyuzhenhong/Desktop/Academic/Research/PhysRevLett.112.201801_EW_VacuumStability_BICEP2.pdf)
[Spacetime Curvature and the Higgs Stability During Inflation](file:///Users/lyuzhenhong/Desktop/Academic/Research/PhysRevLett.113.211102_Curvature_HiggsStability.pdf)
[Generation of fluctuations during inflation: Comparison of stochastic and field-theoretic approaches](file:///Users/lyuzhenhong/Desktop/Academic/Research/PhysRevD.79.044007_stochastic_field-theoretic.pdf)

## Introduction

In the context of the SM with no additional physics, our universe lies at the edge between stability and instability (near-criticality) of the electroweak vacuum. The Higgs potential develops an instability well below the Planck scale.
- If the effective mass of the Higgs field is smaller than the Hubble rate $H$ during inflation, ==quantum excitations push the Higgs field away from its minimum==. The classical value of the Higgs field ==randomly walks== receiving kicks $\sim \pm H/(2\pi)$ (the effective Gibbons-Hawking temperature [1](file:///Users/lyuzhenhong/Desktop/Academic/Research/Higgs_Inflation/JHEP09(2015)174_The%20cosmological%20Higgstory.pdf)) each Hubble time and can surmount the potential barrier and ==fall deep into the unstable side of the potential==.

One can derive upper bounds on $H$, which depends on the reheating temperature $T_{RH}$ and on the Higgs coupling to the scalar curvature or to the inflaton.
- Patches in which the Higgs field probes the unstable part of the potential can be recovered thanks to the thermal effects after inflation. Indeed, the mass squared of the Higgs field receives a positive correction proportional to $T^2$ in such a way that in those would-be dangerous regions the Higgs field can roll back down to the origin and be safe.

### General Picture
1. During inflation, there are patches where the Higgs field has been pushed by quantum fluctuations beyond the potential barrier and is classically rolling down the slope. 
2. ==Higgs perturbations instead grow to large values in the last e-folds of inflation==, which are <u>irrelevant for observations in the CMB</u>.
3. When inflation ends and reheating takes place, these regions are rescued by thermal effects and the Higgs field rolls down to the origin of its potential. 
4. At later times, the Higgs perturbations reenter inside the Hubble radius, and they provide high peaks in the matter power spectrum that give rise to primordial black holes (PBH)

#### First phase
The Higgs has an initial value smaller than the Hubble rate $H$.
Fokker planck equation
$$
\ddot{h}_c+3H\dot{h}_c+V'(h_c)=3H\eta
$$
其中$V(h_c)=-\frac{1}{4}\lambda h_c^4$。$\eta$为满足高斯分布的背景随机噪声，$\langle\eta(t)\eta(t')\rangle=\frac{H^3}{4\pi^2}\delta(t-t')$，用于模拟量子涨落。

#### Second phase
The Higgs has been pushed beyond the barrier of its effective potential and finds itself in the unbounded from below region. The motion starts being ==classically dominated== over the quantum jumps at some time $t_*$ if the classical displacement, $(\Delta h)_{cl} \simeq V'/(3H^2)$ in a Hubble time, is larger than the quantum jumps $(\Delta h)q \simeq H/(2\pi)$.
$$
h_c^3\gtrsim\frac{3H^3}{2\pi\lambda}  
$$
$$
\ddot{h}_c+3H\dot{h}_c+V'(h_c)=0
$$
At the beginning of this phase, the motion of the Higgs is friction dominated, $\ddot{h}_c \lesssim 3H\dot{h}_c$. This happens as long as $h^2_c \lesssim 3H^2/\lambda$.
$$
\Rightarrow h_{\mathrm{c}}(t) \simeq \frac{h_{*}}{\left[1-2 \lambda h_{*}^{2}\left(t-t_{*}\right) / 3 H\right]^{1 / 2}}
$$
Meanwhile, Higgs fluctuations are generated. Perturbing around the slowly-rolling classical value of the Higgs field and accounting for metric perturbations as well, the Fourier transform of the perturbations of the Higgs field satisfy the equation of motion (in the flat gauge)
$$
\delta \ddot{h}_{k}+3 H \delta \dot{h}_{k}+\frac{k^{2}}{a^{2}} \delta h_{k}+V^{\prime \prime}\left(h_{c}\right) \delta h_{k}=\frac{\delta h_{k}}{a^{3} m_{P}^{2}} \frac{d}{d t}\left(\frac{a^{3}}{H} \dot{h}_{c}^{2}\right)
$$
the last term accounts for the backreaction of the metric perturbations.

==Driven by the Higgs background evolution in the last e folds of inflation, the Higgs perturbations grow significantly after leaving the Hubble radius. These Higgs perturbations will be responsible for the formation of PBHs.==

The comoving curvature perturbation reads
$$
\zeta=H \frac{\delta \rho}{\dot{\rho}}=H \frac{\delta \rho_{st}+\delta\rho_{h}}{\dot{\rho}}=\frac{\dot{\rho}_{\mathrm{st}}}{\dot{\rho}} \zeta_{\mathrm{st}}+\frac{\dot{\rho}_{h}}{\dot{\rho}} \zeta_{h}=\frac{\dot{\rho}_{\mathrm{st}}}{\dot{\rho}} \zeta_{\mathrm{st}}+H \frac{\delta \rho_{h}}{\dot{\rho}}
$$
其中$\zeta_{st,h}=H\delta\rho_{st,h}/\dot{\rho}_{st,h}$
$\zeta_{st}$ stands for the origin of the curvature perturbation, which is responsible for the CMB anisotropies. $\zeta_h$ is the Higgs perturbation.
We assume $\zeta_{st}$ is conserved during inflation on super-Hubble scales. However, during inflation and on super-Hubble scales, $\zeta_h$ reaches the plateau
$$
\zeta_{h}(k \ll a H)=H \frac{\delta \rho_{h}}{\dot{\rho}_{h}}=H C(k)=\frac{H^{2}}{\sqrt{2 k^{3}} \dot{h}_{c}\left(t_{k}\right)}
$$
#### Reheating
The reheating temperature $T_{RH}$ after inflation is large enough to push the Higgs back to our current vacuum. This happens because, thanks to the thermal interactions with the surrounding plasma, the Higgs potential is corrected to the form
$$
V_{T} \simeq \frac{1}{2} m_{T}^{2} h_{\mathrm{c}}^{2},\, m_{T}^{2} \simeq 0.12 T^{2} e^{-h_{\mathrm{c}} /(2 \pi T)}
$$
If the maximum temperature is larger than the value of the Higgs field $h_e$ at the end of inflation, then the patch is rescued and the Higgs starts oscillating (with a relativistic equation of state) around the current electroweak vacuum where it will settle after a while.
At the same time, the curvature perturbation, with power spectrum $P_\zeta$, gets the largest contribution from the Higgs fluctuations. After inflation, the long wavelength Higgs perturbations decay after several oscillations into radiation curvature perturbation which, being radiation now the only component, will stay constant on super- Hubble scales.
![[截屏2022-12-12 23.18.42.png]]
![[截屏2022-12-12 23.19.49.png]]
![[截屏2022-12-12 23.21.37.png]]
