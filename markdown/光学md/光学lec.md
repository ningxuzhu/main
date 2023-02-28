# 光学重点

[TOC]



## 几何光学
### 几何光学三定律
1. 直线传播定律：在均匀介质中光沿**直线**传播

2. **独立**传播定律：不同方向的光线相交，不影响每一光线的传播

3. 反射、折射定律：在两种媒质的**界面**发生反射、折射

#### $snell's$ $law$
$$nsin\theta_{i}=n'sin\theta_{i}'$$
#### 棱镜最小偏向角
$$n=\frac{sin\frac{\delta_{m}+\alpha}{2}}{sin\frac{\alpha}{2}}n_{0}$$
（其中$\alpha$为棱镜顶角）

#### 费马原理
$$\delta\int_Q^Pndl=0$$
#### 共轭点
将物点移到原来的像点位置，并使光线沿反方向射入光具组，像点将出现在原来的物点位置上。这样的一对物像点被称为共轭点。
#### 光学系统严格成像的条件
1.同心性不变：由物点发出的同心光束通过光具组后保持同心性不变。

2.等光程成像：由物点发出的所有光线通过光具组后均应以相等的光程到达像点。
透镜往往难以形成共轭点。$specially$：齐明点

### 傍轴光线透镜物象距公式($important$)
$$\frac{n}{s}+\frac{n'}{s'}=\frac{n'-n}{r}=\Phi$$
$Def:\Phi=\frac{n'-n}{r}$为光焦度，单位为屈光度($D/m^{-1})$

<img src="D:\VScode文件\markdown\光学md\单个球面折射.png" alt="单个球面折射" style="zoom:67%;" />

#### 傍轴光线反射球面物象距公式
$$\frac{1}{s}+\frac{1}{s'}=-\frac{2}{r}(n'\rightarrow-n,s'\rightarrow-s')$$
#### 横向放大率公式
- 折射球面$V=\frac{y'}{y}=-\frac{ns'}{n's}$

<img src="D:\VScode文件\markdown\光学md\横向放大率推导.png" alt="横向放大率推导" style="zoom: 67%;" />

- 反射球面$V=-\frac{s'}{s}(n'\rightarrow-n,s'\rightarrow-s')$

#### $Gauss$公式
$$\frac{f'}{s'}+\frac{f}{s}=1$$
#### <font color=Blue>$Lagrange-Helmhotz$恒等式
$$ynu=y'n'u'\quad其中u=\frac{h}{s},-u'=\frac{h}{s'}$$

</font>

### 薄透镜动力学
$$\frac{n}{s}+\frac{n'}{s'}=\frac{n_{l}-n}{r_1}+\frac{n'-n_{l}}{r_2}\quad其中n_{l}为薄透镜折射率$$

令$\Phi_{1}=\frac{n_{l}-n}{r_{1}},\Phi_{2}=\frac{n'-n_{l}}{r_{2}},\Phi_{1}+\Phi_{2}=\Phi\to\frac{n}{s}+\frac{n'}{s'}=\Phi$

#### 空气中磨镜者公式
$$f=f'=\frac{1}{(n_{l}-1)(\frac{1}{r_{1}}-\frac{1}{r_{2}})}$$

空气中的薄透镜物距和像距**永远**位于两侧

#### 牛顿物像公式
$$xx'=ff'$$

<img src="D:\VScode文件\markdown\光学md\牛顿物像公式.png" alt="牛顿物像公式" style="zoom: 50%;" />

#### 横向放大率
$$V\stackrel{tip}{=}-\frac{ns'}{n's}=-\frac{fs'}{f's}=-\frac{x'}{f'}=-\frac{f}{x}$$

$tip$：负号是由第一次呈像的物距变为第二次呈像的像距产生的

#### 密接薄透镜组
$$\frac{1}{s}+\frac{1}{s'}=\frac{1}{f_{1}}+\frac{1}{f_{2}}$$
### 作图法（三条重要光线）
需要熟练掌握凹透镜作图
#### 主点和主面
主面：过主点做垂直于光轴的平面，是横向放大率为1的一对共轭面

#### <font color=Blue>基点和基平面

考虑两个理想光具组的联合基点为图中$H'$，由相似关系和$Gauss$公式即可推得下列公式

![理想光具组联合](D:\VScode文件\markdown\光学md\理想光具组联合.png)

$\cdot\begin{cases} f'=-\frac{f_1'f_2'}{\Delta},X_H'=\frac{df_2'}{\Delta}\\f=-\frac{f_1f_2}{\Delta},X_H=\frac{df_1}{\Delta}\end{cases}$

$\Phi=\frac{1}{f_1}+\frac{1}{f_2}-\frac{d}{f_1f_2}$

#### 角放大率
$W=\frac{tanu'}{tanu}=-\frac{s}{s'}$

可得横向放大率与角放大率成反比：$VW=\frac{n}{n'}$

#### $Helmhotz$公式

$$yntanu=y'n'tanu'$$
在傍轴情况下变为$Lagrange-Helmhotz$等式

</font>

### 照相相关

景深：由$Newton$物像公式得
$$\frac{\delta x'}{\delta x}=-\frac{f^2}{x^2}$$
大光圈+长焦镜头+近距离$\rightarrow$小景深

小光圈+短焦镜头+远距离$\rightarrow$大景深

像差：见PPT

### 光学仪器

投影仪：$s\approx f$

照相机：$s'\approx f$

#### 眼睛

远点：无穷远；近点：明视距离

#### 和眼睛直接相关的两种仪器（需要考虑到眼睛特性）

对于眼睛前的放大镜和目镜：

由于眼睛的特点，物体只能处于凸透镜焦点以内的一个小范围内，这个范围叫焦深

物体的视角最大不超过$w=\frac{y}{s_0}$由牛顿公式，其对光心夹角为$w'=\frac{y}{f}$则放大镜视角放大率$M=\frac{s_0}{f}$，对不同放大倍率的目镜来说焦深$x=\frac{s_0}{M(M+1)}$

显微镜：物在$f_0$附近，**第一次呈像在$f_e$附近**，最后呈像在明视距离$s_0$(25cm)外，角放大率$M\stackrel{?}{=}-\frac{\Delta s_0}{f_ef_o}$，其中$\Delta$为光学筒长

望远镜：**第一次呈像在$f_e$附近**且$f_0'\approx f_e$，角放大率$M\stackrel{?}{=}-\frac{f_o'}{f_e}$
#### 光瞳
入射光瞳：孔径光阑在物方的共轭，大小用物镜横向放大率计算

出射光瞳：孔径光阑在像方的共轭，大小用目镜横向放大率计算

#### $E.Abbe$正弦条件

傍轴物点以大孔径光束呈像的充要条件：$nysinu=n'y'sinu'$

#### 照度，亮度见$P98.5$

$tip:$与太阳能量有关的问题要从太阳的辐射出能量的通量不变下手

## 波动光学
### 复振幅描述

光波是电磁波，是矢量横波，用两个矢量场描述：

$\begin{cases}\pmb{E}(P,t)=\pmb{E}_0(P)cos[\omega t-\varphi(P)]\\\pmb{H}(P,t)=\pmb{H}_0(P)cos[\omega t-\varphi(P)]\end{cases}$

通常讨论单色波场空间分布时，时间因子$e^{-i\omega t}$相同，剩下的空间分布因子$\widetilde{U_P}=A(P)e^{i\varphi(P)}$称为复振幅

- 平面波

  $Def:$(i)振幅为常数(ii)具有线性相位因子

  复振幅$\widetilde{U_P}=Ae^{i(\bf k\cdot \bf r+\varphi_0)}$

- 球面波

  复振幅$\widetilde{U_P}=\frac{a}{r}e^{i(kr+\varphi_0)}$

$\textcolor{red}{实际初相位与初相位相差一个负号。}$相对于初相位来说：相位落后为正，相位超前为负

#### $Fresnel$反射折射公式

边界处两个$Maxwell$方程$+$折射率$n\approx\sqrt{\epsilon_r}$
$$\begin{cases}
\vec{n}\times(E_1-E_2)=0\\
\vec{n}\times(H_1-H_2)=0\\
\end{cases}$$

$$r_s=-\frac{sin(i_1-i_2)}{sin(i_1+i_2)}=\frac{cosi_1-\sqrt{n_{21}^2-sin^2i_1}}{cosi_1+\sqrt{n_{21}^2-sin^2i_1}}$$

$$r_p=\frac{tan(i_1-i_2)}{tan(i_1+i_2)}=\frac{n_{21}^2cosi_1-\sqrt{n_{21}^2-sin^2i_1}}{n_{21}^2cosi_1+\sqrt{n_{21}^2-sin^2i_1}}$$

$$t_s=\frac{2cosi_1sini_2}{sin(i_1+i_2)}=\frac{2cosi_1}{cosi_1+\sqrt{n_{21}^2-sin^2i_1}}$$

$$t_p=\frac{2cosi_1sini_2}{sin(i_1+i_2)cos(i_1-i_2)}=\frac{2n_{21}cosi_1}{n_{21}^2cosi_1+\sqrt{n_{21}^2-sin^2i_1}}$$

【注意】1.$i_2=arcsin(\frac{n_1}{n_2}sini_1)$

2.后一个等于号是把$n_{21}cosi_2$换成了$\sqrt{n_{21}^2-sin^2i_1}$

$\textcolor{red}{正入射}有\begin{cases}r_s=-r_p=\frac{n_2-n_1}{n_1+n_2}\\t_s=t_p=\frac{2n_1}{n_1+n_2}\end{cases}$

- 光强（波印廷矢量）$I\propto n|E|^2$

- 能流（光强投影）反射率$\mathscr{R}=r^2$

- 能流（光强投影）透射率$\mathscr{T}=\frac{n_2cosi_2}{n_1cosi_1}t^2$


#### 布儒斯特角
$r_p=0,i_b+i_2=\frac{\pi}{2}$

$i_b=arctan(\frac{n_2}{n_1})$
#### 斯托克斯倒逆关系
无论是$s$分量还是$p$分量，其内反射与外反射振幅反射比$r=-r'$，相应的振幅透射比（$t_s$与$t_s'$，$t_p$与$t_p'$）总是符号相同， $tt'+r^2=1$

#### 相位关系与半波损

- 透射时不会出现相位的突变
- 反射时由$\widetilde r_p=\frac{tan(i_1-i_2)}{tan(i_1+i_2)}=r_pe^{i\delta},\widetilde r_s=-\frac{sin(i_1-i_2)}{sin(i_1+i_2)}=r_se^{i\delta}$
  - $单界面反射光与入射光的半波损\begin{cases}正入射(S波反向):n_1<n_2\to\widetilde r_s<0\\琼入射(S波和P波同时反向):i_1>i_b\to i_1+i_2>\frac{\pi}{2},n_1<n_2\to i_1>i_2\end{cases}$
  - $双界面两束反射光间的半波损\begin{cases}斜入射:介质层(折射率n_2)上下表面的折射率为n_1,n_3,当满足n_2为极值时两反射光有半波损失\end{cases}$

## 干涉

$$I(P)=I_1(P)+I_2(p)+2\sqrt{I_1(P)I_2(P)}cos\delta(p)$$

### 干涉的必要条件

**1.频率相同**（保证积分不为0）

**2.存在相互平行的振动分量**

**3.相位差$\delta(P)$稳定** $\delta$不固定则会出现$cos\delta$迅速变化使得$\overline{cos\delta}$为0

#### 光强衬比度

$$\gamma=\frac{2A_1A_2}{A_1^2+A_2^2}$$

则干涉公式变为：

$$I=I_0(1+\gamma cos\delta)$$

其中$I_0=I_1+I_2=A_1^2+A_2^2$

### 分波前干涉

<img src="D:\VScode文件\markdown\光学md\分波前装置.png" alt="分波前装置" style="zoom:50%;" />

#### 杨氏双缝干涉

条纹间距为

$$\Delta x=\frac{D}{d}\lambda$$

#### 两束平行光的干涉

由两束平面波函数在波前同一点的相位差$\delta=k[(sin\alpha_1-sin\alpha_2)x+(sin\beta_1-sin\beta_2)y]$

$$沿x,y方向的条纹间距为\begin{cases}
\Delta x=\frac{\lambda}{sin\alpha_1-sin\alpha_2}\\
\Delta y=\frac{\lambda}{sin\beta_1-sin\beta_2}\\
\end{cases}\qquad空间频率为\begin{cases}
f_x=\frac{1}{\Delta x}\\
f_y=\frac{1}{\Delta y}\\
\end{cases}$$

#### 光源宽度与干涉条纹的关系

$$\begin{cases}
\delta x=\frac{D}{R}\delta s\\
\Delta x=\frac{D}{d}\lambda\\
\end{cases}$$
$\delta x=\Delta x$（点源连续分布），令$\delta s=b_1$得到光源极限宽度：$b_1=\frac{R}{d}\lambda$

![光源宽度与干涉](D:\VScode文件\markdown\光学md\光源宽度与干涉.png)

#### 光源宽度与衬比度

$$\gamma=|\frac{sinu}{u}|$$
其中$u=\frac{b}{b_1}\pi$

### 分振幅干涉$\Delta L=2nhcosi_2(\pm\frac{\lambda}{2})$

$$等厚干涉\begin{cases}
楔形薄膜\Delta x=\frac{\lambda}{2\alpha}\\
牛顿环R=\frac{r^2_{k+m}-r^2_k}{m\lambda}中央级数最小，牛顿环向上移动，各级数变大\\
\end{cases}$$

等倾干涉：$\Delta L=2nhcosi_2(\pm\frac{\lambda}{2})$中央级数最大，增大$h$级数变大，有$l=N\frac{\lambda}{2}$
#### 光源非单色性对条纹的影响
最大光程差（空间周期）
$$\Delta L_M=\frac{2\pi}{\Delta k}=\frac{\lambda^2}{|\Delta \lambda|}$$

#### 光源的时间相干性
$\tau_0\Delta\nu\approx1$由$\nu=\frac{c}{\lambda}\to\Delta\nu=\frac{c}{\lambda^2}\Delta\lambda\to\tau=\frac{\lambda^2}{c\Delta\lambda}$波列长度为$L=c\tau=\frac{\lambda^2}{\Delta\lambda}$

#### 光源的空间相干性
$b\Delta \theta=\lambda$

### 法布里-珀罗干涉

$$I_T=\frac{I_0}{1+\frac{4Rsin^2(\delta/2)}{(1-R)^2}}$$
推导需要使用**斯托克斯倒逆定理**，可以看出，$R$增大，反射条纹亮线越来越宽，透射条纹亮线越来越窄

由$\delta=\frac{4\pi nhcosi}{\lambda},n$和$h$一般是不变的，影响$\delta$变化的因素有$i$和$\lambda$，记住干涉条纹的半值宽度$\varepsilon=\frac{2(1-R)}{\sqrt R}$

- $\lambda$固定，对$\delta=\frac{4\pi nhcosi}{\lambda}$求$i$的微分，令$d\delta=\varepsilon$则第$k$级亮纹角宽度为

  $$\Delta i_k=\frac{\lambda}{2\pi nhsini_k}\frac{1-R}{\sqrt{R}}$$

- $i$固定(经常是0)，对$\delta=\frac{4\pi nhcosi}{\lambda}$求$\lambda$的微分，则某一纵模($\lambda_k$)的半值宽度为

  $$\Delta \lambda_k=\frac{\lambda_k^2}{2\pi nhcosi}\frac{1-R}{\sqrt{R}}=\frac{\lambda_k}{\pi k}\frac{1-R}{\sqrt{R}}$$

  由于多光束干涉，使得在很宽的光谱范围内只有特定的波长附近出现极大$2nh=k\lambda_k,k\in\mathbb{Z}$，相邻极强频率间是等间隔的：$\Delta\nu=\frac{c}{2nh}$

- $i$不同$\lambda$也不同$\begin{cases}
  2nhcosi_k=k\lambda\\
  2nhcos(i_k+\delta i_k)=k(\lambda+\delta\lambda)\\
  \end{cases}$得到$\delta i_k=\frac{k}{2nhsini_k}\delta\lambda$令$\delta i_k=\Delta i_k$则得到色分辨本领为：$\frac{\lambda}{\delta \lambda}=k\pi\frac{\sqrt{R}}{1-R}$

## 衍射

基于：惠更斯－菲涅耳衍射积分公式

$$\widetilde U(P)=\iint_\Sigma KF(\theta_0,\theta)\widetilde U(Q)\frac{e^{ikr}}{r}d\Sigma$$

### 菲涅尔圆孔衍射

光源-衍射屏-接收屏距离有限，或至少一个有限

各个半波带次波叠加后的和振动的振幅为$A=\frac{1}{2}[A_1+(-1)^{n-1}A_n],n$为奇数$P$为亮点$,n$为偶数$P$为暗点$,n\to\infty$始终为亮点(圆屏衍射)

矢量图解$P151.5$

#### 半波带半径
$$\rho_k=\sqrt{\frac{Rb}{R+b}k\lambda}\qquad (k=1,2,...)$$

转化成透镜公式：
$$\frac{1}{R}+\frac{1}{b}=\frac{k\lambda}{\rho_k^2}\qquad \text{即}f=\frac{\rho_1^2}{\lambda}$$

### 单缝夫琅禾费衍射

光源-衍射屏-接收屏距离无限

<img src="D:\VScode文件\markdown\光学md\单缝衍射的矢量图解.png" alt="单缝衍射的矢量图解" style="zoom:50%;" />

$A_0=\mathop{AB}\limits^{\frown},\vec{A_\theta}=\vec{AB}$，注意$AB=const.,R=R(\theta)$：

光强分布：$$I_\theta=I_0(\frac{sin\alpha}{\alpha})^2$$
其中$\alpha=\frac{\pi a}{\lambda}(sin\theta\pm sin\theta_0),\frac{sin\alpha}{\alpha}$为单缝衍射因子，$\theta_0$为入射光与单缝所在平面法线的夹角

半角宽度：$$\Delta\theta=\frac{\lambda}{acos\theta_0}$$
应用：由巴比涅定律，细丝所呈衍射图像与单缝所呈图像完全一致，可以用来测细丝直径

夫琅禾费矩孔衍射：$I_\theta=I_0(\frac{sin\alpha}{\alpha})^2(\frac{sin\beta}{\beta})^2$

其中$\alpha=\frac{\pi a}{\lambda}(sin\theta\pm sin\theta_0),\beta=\frac{\pi b}{\lambda}(sin\beta\pm sin\beta_0)$

### 光学仪器像分辨本领

由于光学成像系统中，光瞳多呈圆形。

根据夫琅禾费圆孔衍射：$I_\theta=I_0[\frac{2J_1(x)}{x}]^2$，半角宽度为$$\Delta\theta=1.22\frac{\lambda}{D}$$

由瑞利判据(一个点光源的衍射图像的中央最亮处恰好与另一个点光源衍射图像的第一个最暗处相重合)得光学仪器最小分辨角$\delta\theta_m=\Delta\theta$

角放大率
$$M=\frac{\delta\theta_e}{\delta\theta_m}$$
$\delta\theta_e\approx1'=2.9\times10^{-4}rad$

<font color=Blue>

显微镜分辨本领$\delta y_m=\frac{0.61\lambda}{N.A.}$

</font>

### 多缝夫琅禾费衍射

<img src="D:\VScode文件\markdown\光学md\多缝衍射的矢量图解.png" alt="多缝衍射的矢量图解" style="zoom: 50%;" />

多缝=衍射+干涉

相关参数：光栅常数$d=a+b$，光栅有效长度$L=Nd$

$$I_\theta=a_0^2(\frac{sin\alpha}{\alpha})^2(\frac{sinN\beta}{sin\beta})^2\qquad \alpha=\frac{\pi a}{\lambda}sin\theta\quad\beta=\frac{\pi d}{\lambda}sin\theta$$

单缝衍射因子和缝间干涉因子相乘实现相位调制，出现缺级(干涉主极大不能出现)

光栅方程：衍射的极大值条件$d(sin\theta_0-sin\theta_j)=j\lambda,j\in\mathbb{Z}$

### 光栅分光

正弦光栅三个主极大：$\beta=0,\pi,-\pi$

- 角色散本领：由光栅方程(干涉因子取极大)$dsin\theta_k=k\lambda$，取微分得到$\delta\theta_k=\frac{k\delta\lambda}{dcos\theta_k}$整理得到$D_\theta=\frac{\delta\theta_k}{\delta\lambda}=\frac{k}{dcos\theta_k}$
- 线色散本领：$D_l=\frac{\delta\theta_k f}{\delta\lambda}=\frac{kf}{dcos\theta_k}$

- 对于一定波长差$\delta\lambda$的两条谱线的角间隔？由光栅方程(干涉因子取极大)$dsin\theta_k=k\lambda$，取微分得到$\delta\theta_k=\frac{k\delta\lambda}{dcos\theta_k}$

  $k$级条纹的角宽度：$\frac{\pi d}{\lambda}sin\theta_k=k\pi\qquad\frac{\pi d}{\lambda}sin(\theta_k+\Delta\theta)=(k+\frac{1}{N})\pi\quad\rightarrow\Delta\theta_k=\frac{\lambda}{Ndcos\theta_k}$

  由瑞利判据$\delta\theta_k=\Delta\theta_k$得最小分辨波长$\delta\lambda=\frac{\lambda}{kN}$

### 闪耀光栅

- 光栅的衍射包括单元衍射和缝间干涉两部分

- $\alpha$中$\theta$是光线与狭缝法线的夹角(衍射几何像点)，$\beta$中$\theta'$则是与整个光栅平面法线夹角，传统的光栅$\theta$相同，衍射的零级主极大与干涉的零级主极大重合，导致大部分能量和信息都集中于光栅中央

- 设闪耀角为$\theta_b$，第一种照明方式：$\theta=0$，一级闪耀波长$\lambda=2dsin\theta_b$；第二种照明方式：$\theta'=0$，一级闪耀波长$\lambda=dsin2\theta_b$

## 傅里叶光学

### 屏函数

凡使波前上的复振幅发生改变的物都称为衍射屏，都具有屏函数：
$$\widetilde{t}(x,y)=\frac{\widetilde{U_2}(x,y)}{\widetilde{U_1}(x,y)}$$

<img src="D:\VScode文件\markdown\光学md\相因子1.png" alt="相因子1" style="zoom: 50%;" />

<img src="D:\VScode文件\markdown\光学md\相因子2.png" alt="相因子2" style="zoom:50%;" />

透镜的相位变换函数：
$$\widetilde{t_L}(x,y)=exp[-ik\frac{x^2+y^2}{2f}]$$

棱镜的相位变换函数：
$$\widetilde{t_P}(x,y)=exp[-ik(n-1)\alpha x]$$

正弦光栅的相位变换函数：
$$\widetilde{t}(x,y)=t_0+t_1cos(q_xx+q_yy+\varphi_0)$$
$q=2\pi f$为空间圆频率

### 正弦光栅的制备

两束平行光干涉的光强为：$I=I_0[1+\gamma cos(q_xx+q_yy+\varphi_0)]$

经过线性冲洗：$\widetilde{t}(x,y)=t_0+\beta I(x,y)$得到正弦光栅

由欧拉公式可知平行光通过正弦光栅后分为三列平面波,对照平面波的复振幅和复振幅$\widetilde{U_2}$得到 $2\pi fx=kx\rightarrow sin\theta_{\pm1}=\pm f\lambda$

### 屏函数傅里叶展开

任何复杂衍射屏的屏函数都可以展开成一系列简单屏函数的和

### 空间滤波

凸透镜本身就是一个低通滤波器，物平面在前焦面附近时截止频率为
$$sin\theta=f\lambda\qquad f_M=\frac{D}{2F\lambda}$$

### 全息$Halo$

无源空间中的光场分布由边界条件（波前）唯一确定$I=(\widetilde U_o+\widetilde U_R)(\widetilde U_o^*+\widetilde U_R^*)$

利用线性冲洗得到屏函数$\widetilde{t}(x,y)=t_0+\beta I(x,y)$

最后用与参考光$R$频率、角度相同的光源$R'$照明得到全息图像$\widetilde{U}=\widetilde{U}_{R'}\widetilde{t}(x,y)$

## 偏振光学

总设$\begin{cases}
E_x=A_xcos(wt)\\
E_y=A_ycos(wt+\delta)\\
\end{cases}$

则“广义椭圆”的取向只取决于相位差

判断椭圆主轴的方向和左右旋的方法：令$t=0,E_x=A_x,E_y=A_ycos\delta\to\begin{cases}
cos\delta>0&右上\\
cos\delta<0&左上\\
\end{cases}$

再考虑经过时间$\Delta t$后的情况$E_y=A_ycos(\Delta t+\delta)$增大还是减小

左旋偏振光：迎着传播方向观察，电矢量逆时针转动

右旋偏振光：迎着传播方向观察，电矢量顺时针转动

### 光强

由马吕斯定律：$I_\theta=I_0cos^2\theta$

- 不经过起偏器的初始光强，设$A_x=A_y=A$

  $I_0=\begin{cases}自然光\int_0^{2\pi}A^2d\theta=2\pi A^2\\线偏光A_x^2+A_y^2=2A^2\\圆偏光A_x^2+A_y^2=2A^2\end{cases}$

- 经过检偏器的光强，设线偏光与检偏器夹角$\alpha$

  $I=\begin{cases}自然光\int_0^{2\pi}(Acos\theta)^2d\theta=\pi A^2=\frac{I_0}{2}\\线偏光(\sqrt2Acos\alpha)^2=2A^2cos^2\alpha=\frac{I_0}{2}cos^2\alpha\\圆偏光A^2=\frac{I_0}{2}\end{cases}$

### 双折射

$o$光：满足折射定律；$e$光：一般不满足折射定律

$$\begin{cases}主截面：晶体表面的法线方向与晶体内光轴方向所组成的平面\\主平面：晶体中某条光线与晶体光轴所构成的平面\\入射面：光线所在平面\\\end{cases}$$

光轴平行于界面，光线正入射（波片）

光线斜入射，光轴垂直于入射面（$o$光$e$光均满足折射定律）

### 偏振光的获得与检验

<img src="D:\VScode文件\markdown\光学md\检验偏振光.png" alt="检验偏振光" style="zoom: 80%;" />

![李萨如图像](D:\VScode文件\markdown\光学md\李萨如图像.png)

### 偏振光干涉

![偏振光干涉](D:\VScode文件\markdown\光学md\偏振光干涉.png)

考点：各种偏振光通过巴比涅补偿器与偏振片的干涉

### 电光效应

折射率和电场的关系可以表示为$n=n_0+aE+bE^2+...$

- 二阶电光效应$kerr\ effect$

  $\delta=\frac{2\pi}{\lambda}bE^2l=2\pi K_r\frac{U^2}{h^2}l$

- 一阶电光效应$Pockels\ effect$

  $\delta=\frac{2\pi}{\lambda}n_0^3\gamma El=\frac{2\pi}{\lambda}n_0^3\gamma U$  

### 旋光效应

原理：平面偏振光可以分解为两束圆偏振光的叠加，==圆偏振光的相位即旋转电矢量的角位移，相位滞后即角度倒转==

$$\theta=\textcolor{red}{\frac{\pi}{\lambda}}|n_e-n_o|l=\alpha l$$，$\alpha$为晶体的旋光本领，$l$为光波在晶体中的传播距离（轴向厚度）

自然旋光具有互易性

## 光的吸收、色散和散射

### 吸收

- 朗伯定律

  $-dI=\alpha Idx\rightarrow I=I_0e^{-\alpha x}$溶液中$\alpha=AC$

- 复折射率

  $\widetilde n=n(1+i\kappa)\to\widetilde E=\widetilde E_0e^{-i(wt-\frac{w}{v_p}x)}=\widetilde E_0e^{-iw(t-\frac{\widetilde n}{c}x)}=\widetilde E_0e^{-\frac{nw\kappa x}{c}}e^{-iw(t-\frac{n}{c}x)}\to I=I_0e^{-\frac{2nw\kappa x}{c}},\kappa$为衰减指数
  
- 经典微观解释理论从电偶极子受迫振动出发$m\ddot r+\gamma\dot r+kr=-\frac{eE_0}{m}e^{-iwt}$再由电磁学理论$\widetilde n^2=\epsilon_r$

### 色散

> 光在介质中传播速度随波长而异的现象称为色散，定义色散率为：$\frac{dn}{d\lambda}$，根据实验定义$\frac{dn}{d\lambda}>0$为反常色散，$\frac{dn}{d\lambda}<0$为正常色散

- $Cauchy$经验公式：$n=A+\frac{B}{\lambda^2}(+\frac{C}{\lambda^4})$

- 棱镜光谱仪

### 群速

> 由于波的传播，前一个时刻的相位信息经过$dt$传递到下一时刻，则有$cos[k(x_0+dx)-w(t_0+dt)]=cos[kx_0-wt_0]$$\to \frac{dx}{dt}=\frac{w}{k}\stackrel{\triangle}{=}v_p$，$v_p$为相速度

群速度则对应不同频率的波叠加后包络的移动速度，考虑简单情况$\omega_1,\omega_2$两列波叠加传播，只用关注低频包络因子$cos[\Delta k(x_0+dx)-\Delta w(t_0+dt)]=cos[\Delta kx_0-\Delta wt_0]=\frac{dx}{dt}=\frac{\Delta w}{\Delta k}\stackrel{\triangle}{=}v_g,v_g$为群速度

- 对于连续频率的光波叠加需要用到积分和泰勒一阶展开

- $v_p$与$v_g$的关系：对$w=kv_p$两边各取$k$的微分

### 散射

介质的不均匀性使光线朝四面八方散射，物体尺度与波长可比拟的不均匀性引起的散射就是衍射，尺度远大于波长引起反射和折射

瑞利定律适用的范围和米德拜理论适用的范围如下图

![米氏散射与瑞利散射](D:\VScode文件\markdown\光学md\米氏散射与瑞利散射.png)

白昼天空是亮的是因为大气散射阳光，天是蓝的是因为短波遭到的散射比长波成分强烈得多，白云是大气中的水滴组成的，其尺度已经大于瑞利尺度，与波长关系不大

## 量子光学

### 热辐射

绝对黑体

- 辐射本领(单位面积上的通量)与绝对温度的关系：$R=\sigma T^4\quad\sigma=5.67\times10^{-8}(W/m^2\cdot K^4)$
- $Wien$位移定律（辐射波长与温度的关系）：$\lambda_MT=b\quad b=2.88\times10^{-3}(m\cdot K)$

### 光电效应

$h\nu=\frac{1}{2}mv^2+A\quad A$为逸出功

$\nu=\frac{c}{\lambda}$

### 康普顿效应

> 用来解释光子在电子上散射时的能量和动量的守恒定律

$由\begin{cases}h\nu_0=h\nu+\frac{1}{2}mv^2\\\frac{h\nu_0}{c}\vec e_0=\frac{h\nu}{c}\vec e_\theta+m\vec v\end{cases}$

解得$\Delta\nu=\frac{h\nu\nu_0}{mc^2}(1-cos\theta)\quad\Delta\lambda=2\lambda_Csin^2\frac{\theta}{2}\quad\lambda_C=\frac{h}{mc}$称为康普顿波长

### 玻尔原子模型

波尔假定电子轨道角动量量子化$L=n\frac{h}{2\pi}\quad n=1,2,...$

见$P480$习题1

### 激光

$激光的产生\begin{cases}泵浦源\\激活介质\\谐振腔\end{cases}$

激活介质要实现粒子数反转？（低能级电子少于高能级电子）

------

[光学(重排本) 赵凯华]:

[光学重难点释疑 崔宏滨 吴强]:  
