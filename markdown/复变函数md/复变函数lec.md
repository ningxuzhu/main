# 复变函数重点

[TOC]

![思维导图](D:\VScode文件\markdown\复变函数md\思维导图.jpg)

## $chapter$ 1

### 辐角主值的计算：

$$arg(x+iy)=
\begin{cases}
arctan \frac{y}{x} &\text{一、四象限} \\
arctan \frac{y}{x}+\pi &\text{第二象限} \\
arctan \frac{y}{x}-\pi &\text{第三象限} \\
\end{cases}$$ 

### $tips$：

1.**$arg\in(-\pi,\pi]$**

2.$arg0,arg\infty$ 无意义

3.$|z|^{2}=z\bar{z},|z|=\textcolor{red}{\sqrt{x^2+y^2}}$

4.指数式的标准形式：$r(实数)e^{i\theta}$

5.复数的开方($de Moivre$公式)以n为周期，有n个值(内接圆正n边形顶点)

6.$z_{0}是z_{n}的极限即\lim\limits_{n\rightarrow\infty}|z_{n}-z_{0}|=0$

### $Some$ $Definition$:

-  复平面(开复平面或有限平面) && 闭复平面或扩充平面
-  区域：非空，开集(无膜)，连通(任意内点用全在区域中的折线连接) vs 闭区域(有膜)
-  有界集：可包含在以原点为中心的某一圆内
-  $Jordan$曲线(简单曲线)：无重点且连续
-  任一简单<font color=red>闭</font>曲线分平面为两区域，其中有界集称为内区域，无界集称为外区域
- $$区域\begin{cases}单连通(无洞，无内割痕) \\多连通\end{cases}$$

## $chapter$ 2

### 复变数函数

#### 单值函数

$z$与唯一复数$w=u+iv$对应

#### 多值函数

$z$对应两个及以上$w$

一个复变函数对应两个实变函数$u(x,y),v(x,y)$或$u(r,\phi),v(r,\phi)$

#### 一一映照

$z_{1}-z_{2}\neq0\longleftrightarrow w_{1}-w_{2}\neq0$

### 求曲线在映照下的像的一般方法

**法一**：1.求映照$w$确定的两个实变函数。2.将原像曲线方程与函数对应方程联立，消$x,y$得到关于$u，v$的方程

**法二**：将原像方程写成关于$z$的方程，再带入逆映照

### 函数的极限

$\forall \varepsilon>0$，$\exists\delta>0$，当$|z-z_{0}|<\delta$时，有$|f(z)-w_{0}|<\varepsilon$，则称当$z$趋向于$z_{0}$时，$f(z)$的极限值是$w_{0}$

### 函数的连续

若$\lim\limits_{z\rightarrow z_{0}}f(z)=f(z_{0})$，那么称$f(z)$在$z_{0}$连续，推广至区域$D$连续记为$f(z)\in C(D)$

函数连续的充要条件：$u(x,y),v(x,y)$连续

#### 结论

1.多项式在复平面处处连续，有理分式在除去使分母为0的点连续

2.$argz$在$z=0$与$x<0$时不连续

### 函数的导数

$w=f(z)$在$z$的某个邻域内有定义，若$\lim\limits_{\Delta z\rightarrow0}\frac{f(z+\Delta)-f(z)}{\Delta z}$存在，则称$f(z)$在$z$可微

### 解析

$f(z)$在$z_{0}$的某个邻域$(|z-z_{0}|<\delta)$内<font color=red>每一点</font>可微，则称$f(z)$在$z_{0}$解析

### 奇点

$f(z)$在$z_{0}$的任一领域内都有不可微的点，则称$z_{0}$为$f(z)$的奇点

#### 结论

1. $f(z)=\bar{z}$ 处处不可微，处处不解析
2. $f(z)$解析，若$|f(z)|=const.$，则$f(z)=const.$

### $Cauchy-Riemann$ 等式(判断可微的充要条件)

设$f(z)=u(x,y)+iv(x,y)$定义在区域$D$内，则$f(z)$在点$z=x+iy\in D$可微的充要条件是：
$$
\begin{cases}
(1)u(x,y),v(x,y)在点(x,y)都可微； \\
(2)u(x,y),v(x,y)在点(x,y)满足\frac{\partial u}{\partial x}=\frac{\partial v}{\partial y},\frac{\partial u}{\partial y}=-\frac{\partial v}{\partial x}
\end{cases}$$
若$f(z)$可微，则$f'(z)=\frac{\partial u}{\partial x}+i\frac{\partial v}{\partial x}$

### 单叶函数

$w=f(z)$是区域$D$内一一<font color=red>解析</font>映照，则称$f(z)$是$D$内的单叶函数，称$D$为$f(z)$的单叶性区域

### 幂函数$w=z^{n}$

$z$的单叶性区域(平面角域)为：$0<|z|<+\infty, \frac{(2k-1)\pi}{n}<argz<\frac{(2k+1)\pi}{n}(k\in\mathbb{Z})$，映照为角域$0<|w|<+\infty,(2k-1)\pi<argw<(2k+1)\pi$

### 根式函数$w=\sqrt[n]{z}$

#### 辐角变化

$z$平面上存在一条起点为$a$，终点为$b$的连续曲线.选定$arga\Rightarrow argb$被确定$\Delta_{l}argz=argb-arga$

$$l是连续闭曲线
\begin{cases}
\Delta_{l}argz=2\pi& \text{原点在内}\\
\Delta_{l}argz=0& \text{原点在外}\\
\end{cases}$$

#### 支点

在$z=a$点的充分小邻域内，作一条包围该点的闭曲线$C$ ，绕$C$连续转动一周后$f(z)$从一个值变到另一个值，就称$a$是$f(z)$的支点。

$ps$：考虑$\Delta_{l}argz$是否引起$f(z)$的任何变化

$z=0,z=\infty$是$w=\sqrt[n]{z}$的唯一两个支点

$w=\sqrt{z^2-1},w=\sqrt[4]{\frac{z(1-z)^{3}}{(z+i)^{4}}}$的支点？$Arg(z-1)$围绕$z=1$转动

#### 支割线

连接$f(z)$任意两支点的**简单**曲线
目的：防止曲线包围支点

#### 单值解析分支

第$k$支的表达式为$w_{k}=\sqrt[n]{r}exp(i\frac{argz+2k\pi}{n}),k=0,1,2,...,n-1$

$w_{k}$把割开了的$z$平面$(2k-1)\pi<argz<(2k+1)\pi$映为角域$D_{k},\frac{(2k-1)\pi}{n}<argw<\frac{(2k+1)\pi}{n}$

### 其他初等函数

| 初等函数   | 具体表达式                                                   | 保形变换                                                | 杂项                                                         |
| ---------- | ------------------------------------------------------------ | ------------------------------------------------------- | ------------------------------------------------------------ |
| 指数函数   | $w=e^z$                                                      | $a<Imz<b\quad b-a\le2\pi\\\Rightarrow a<Argw<b$         | $Arge^{z}=Imz+2k\pi$                                         |
| 对数函数   | $w=Lnz$                                                      | $-\pi<argz<\pi\\\Rightarrow(2k-1)\pi<Imw_{k}<(2k-1)\pi$ | $Lnz=ln|z|+iArgz\\Ln\overline z=\overline{Lnz}$              |
| 三角函数   | $w=\begin{cases}sinz=\frac{e^{iz}-e^{-iz}}{2\textbf{i}}\\cosz=\frac{e^{iz}+e^{-iz}}{2} \end{cases}$ |                                                         | $sinz,cosz无界\\|sinz|=\sqrt{cos^2hy-cos^2x}\\sin(iz)=isinhz\\cos(iz)=coshz$ |
| 双曲函数   | $w=\begin{cases}sinz=\frac{e^{z}-e^{-z}}{2}\\cosz=\frac{e^{z}+e^{-z}}{2} \end{cases}$ |                                                         | $cosh(a+b)=coshacoshb+sinhasinhb$$sinh(a+b)=sinhacoshb+coshasinhb$ |
| 反三角函数 | $w=\begin{cases}Arcsinz\\Arccosz\end{cases}$                 |                                                         | 解法：两边取三角函数，令$e^{iz}=\beta$，求解关于$\beta$的一元二次方程，最后两边取$Ln$ |
| 一般幂函数 | $w=z^\alpha=e^{\alpha  Lnz}$                                 |                                                         |                                                              |

## $chapter$ 3

### 函数的积分

条件：$f(z)$在（逐段）**光滑**曲线上**连续**
$$\int_{C}f(z)dz=\int_{C}udx-vdy+i\int_{C}vdx+udy$$

#### 参数法求积分(不解析函数只能用此办法，含$|dz|,\bar{z}$...)

$t$为参数且$a\leqslant t\leqslant b$， 正方向为逆时针方向

$$\int_{C}f(z)dz=\int_{a}^{b}f(z(t))z'(t)dt$$

- 直线参数方程：$z=$(终点$-$起点)$t+$起点（$0\leqslant t\leqslant1$）

- 圆的参数方程：$z=$圆心$+$半径$e^{i\theta}$（$\theta$从圆心计算）


结论：$C:|z-a|=R$，正方向为逆时针方向

$$\oint_{C}\frac{1}{(z-a)^n}dz=
\begin{cases}
2\pi i & n=1\\
0      & n\neq1\\
\end{cases}$$

### 长大不等式

$|\int_{C}f(z)dz|\leqslant\int_{C}|f(z)||dz|\leqslant sup|f(z)|\cdot s_C$

### 柯西积分定理

> 闭域$\bar{D}$内闭路$\widetilde{C}$围成单（多）连通区域，$f(z)$在$\bar{D}$内解析

$\int_{C}f(z)dz=0$

考虑：是闭路？奇点在内？

### $Newton-Leibniz$ 等式

若$f(z)$在单连通区域$D$内解析$H(z)$是$f(z)$的**任一**原函数，$\forall z_0,z\in D$

$F(z)=\int_{z_0}^{z}f(\zeta)d\zeta=H(z)-H(z_0)$

$Q:how$ $to$ $prove?$

### 柯西积分公式

> 若$f(z)$在==闭路==$C$及其所围区域$D$内解析，则$\forall a_0\in D$

$$\int_{C}\frac{f(z)}{z-a_0}dz=2\pi if(a_0)$$

注意：$z$前的系数必为1

若两个解析函数在边界上的值处处相等，则它们在整个区域上也恒等

$prove?$ 连续+长大不等式，难点：构造出$f(z)$

### 高阶导数积分公式

> $\forall a_0\in D$解析域，$f(z)$有任意阶导数！

$$\int_{C}\frac{f(z)}{(z-a_0)^n}dz=\frac{2\pi i}{(n-1)!}f^{(n-1)}(a_0)$$

$prove?$ $definition$+归纳+长大不等式，难点：$k-1\rightarrow k$

### 平均值公式（边界决定内部）

> $f(z)$在闭圆$|z-a|\leqslant R$内解析

$$f(z)=\frac{1}{2\pi R}\int_{|z-a|=R}f(\zeta)ds$$

### 最大模原理

> $f(z)$在有界区域$D+C$上解析且**不恒等于常数**

$\exist a\in C,s.t.|f(z)|_{max}=|f(a)|$


### 柯西不等式（解析函数导数模的估计）

> 设$f(z)$在$|z|\leqslant R$上解析，且**边界上**的最大值为$M(R)$

$$|f^{(n)}(z)|\leqslant \frac{n!M(R)}{R^n}$$

### $Liouville$定理

不恒为常数的整函数模无界

### $ex:$

证明：$f'(a)=\frac{1}{\pi r}\int_0^{2\pi}Re[f(a+re^{i\theta})]e^{-i\theta}d\theta$

难点：运用柯西积分定理+取共轭

$Tip:$对零点问题用反证+取倒数+最大模原理

$Tip:$对外部解析的问题，构造更大的复闭路

## $chpter$ 4

### 调和函数

$\Delta f=0$

定理：$f$解析，其实部和虚部为共轭调和函数

### 必考题

已知$u$在单连通区域$D$内调和，求$D$内的解析函数$f(z)$
$$v(x,y)=\int_{(x_0,y_0)}^{(x,y)}\frac{\partial v}{\partial x}dx+\frac{\partial v}{\partial y}dy+\textcolor{red}{C}$$

$$\stackrel{C-R}{\rightarrow}v(x,y)=\int_{(x_0,y_0)}^{(x,y)}-\frac{\partial u}{\partial y}dx+\frac{\partial u}{\partial x}dy+\textcolor{red}{C}$$

$$v(x,y)=\int_{x_0}^{x}-\frac{\partial u}{\partial y}\textcolor{red}{\bigg|_{y=y_0}}dx+\int_{y_0}^{y}\frac{\partial u}{\partial x}\bigg|_{x=x}dy+\textcolor{red}{C}$$
$$f(x,y)=u(x,y)+iv(x,y)\stackrel{x=z,y=0}{\longrightarrow}f(z)$$

其中$C$是任意$\textcolor{red}{实}$常数

### 调和函数性质

$u(z)$只能在$D$的边界$C$上取得$\bar{D}$上的最大值和最小值，构造$g(z)=e^{\pm u(z)\pm iv(z)}$，利用最大模原理即可

### 调和函数的泊松积分公式

$f(z)$为调和函数，其在圆内任意点的值可以用圆周上的积分表示出来（柯西积分公式+柯西积分定理$z=\frac{R^2}{r}$）
$$f(z_0+re^{i\varphi})=\frac{1}{2\pi}\int_{0}^{2\pi}\frac{R^2-r^2}{R^2-2rRcos(\theta-\varphi)+r^2}f(z_0+re^{i\varphi})d\theta$$

## $chapter$ 5

### 解析函数的级数展开

部分和定义！ 一致收敛的定义！ $Cauchy$收敛准则

#### $\sum_{n=0}^{\infty}z^n$的敛散性：

$|z|<1$时收敛，$\sum_{n=0}^{\infty}z^n=\frac{1}{1-z}$ 但不绝对收敛(?)

$|z|\geqslant1$时发散（逐项不收敛）

$|z|\leqslant r,$ $0<r<1$强级数绝对收敛

- $Weierstrass$定理


设$f_n(z)$在$D$内解析且$\sum_{n=1}^{+\infty}f_n(z)$在$D$内一致收敛，则$f(z)$在$D$内解析，且$f^{(k)}(z)=\sum_{n=1}^{+\infty}f_n^{(k)}(z),k=1,2,3,...$**这是实函数没有的**

- $Abel$定理


### 收敛半径

实系数幂级数$\sum_{n=0}^{+\infty}|a_n|x^n$的收敛半径R是$\sum_{n=1}^{+\infty}a_n(z-a)^n$的收敛半径

$R=\frac{1}{r}$其中$r=\lim\limits_{n\rightarrow+\infty}|\frac{a_{n+1}}{a_n}|$或$r=\lim\limits_{n\rightarrow+\infty}\sqrt[n]{a_n}$

### $Taylor$展开（必考）

设$f(z)$在点$a$解析，以点$a$为半径作圆，直至碰到$f(z)$的奇点
$$f(z)=\sum_{n=1}^{+\infty}\frac{f^{(n)}(a)}{n!}(z-a)^n\qquad \textcolor{red}{|z-a|<R}$$

#### $steps:$

1.求奇点

2.求收敛半径$R=$|展开点-距离最近的奇点|

3.从$n=0$处展开成幂级数，注意从基本的函数展开开始再运用变量代换

4.在幂级数展开后写出**收敛半径**

#### $tips:$

1.求和号内的首个常数项要与求和号外的常数项合并

2.不好展开的函数/**级数乘级数**考虑求导/积分函数是否比较好展开

3.展开到第$n$项指展开到$z^{n-1}$

4.$n+1或n-1$要换成$n$

### 零点

$z_0$为$f(z)$的$m$级零点

$\iff f(z_0)=...=f^{(m-1)}(z_0)=0,f^{(m)}(z_0)\neq0$

$\iff f(z)=(z-z_0)^mg(z),g(z)$在$z_0$解析

单零点：1级零点

### $Laurent$级数

$f(z)$在圆环域$D:r<|z-a|<R$中解析，则$f(z)$一定能在这个圆环中展开成罗朗级数，即$f(z)=\sum_{n=-\infty}^{+\infty}a_n(z-a)^n\qquad 其中a_n=\frac{1}{2\pi i}\int_C\frac{f(\zeta)}{(\zeta-a)^{n+1}}d\zeta=\frac{1}{n!}f^{(n)}(a_0)$

#### $tips:$

有理分式先分解，当遇到有理真分式为二阶时考虑求导$P94例12$

### 奇点

$$\cdot\begin{cases}
可去奇点:1.无主要部分，\exist\rho>0,f(z)在0<|z-a|<\rho内有界；2.\lim\limits_{z\rightarrow a}f(z)=a_0\quad P101例17 \\
极点:1.f(z)=\frac{\varphi(z)}{(z-a)^m}且\varphi(a)\neq0\rightarrow a是m级极点；2.a是函数g(z)=\frac{1}{f(z)}的m级零点；3.\lim\limits_{z\rightarrow a}f(z)=\infty\\
本性奇点:1.m=+\infty；2.\lim\limits_{z\rightarrow a}f(z)不存在\\
\end{cases}$$

#### 无穷奇点

做代换$\varphi(\zeta)=f(\frac{1}{\zeta})$再讨论，此时积分区间变化

#### $tips:$

$1=e^{i\theta}e^{-i\theta}$的运用$P104.6$

## $chapter$ 6

### 留数定理

>设$a$是$f(z)$的孤立奇点，$C$是$a\textcolor{red}{充分小邻域内}$一条把$a$点包含在其内部的闭路，定义留数（残数）为：
$$Res[f(z),a]=\frac{1}{2\pi i}\int_Cf(z)dz$$

$$\cdot
\begin{cases}
Res[f(z),a]=a_{-1}  & \text{a为本性奇点\&else}\\
Res[f(z),a]=\frac{1}{(m-1)!}\lim\limits_{z\rightarrow a}\frac{d^{m-1}}{dz^{m-1}}[(z-a)^mf(z)]\textcolor{red}{或:待定系数法(基的观点)}  & \text{a为m级极点}\\
Res[\frac{P(z)}{Q(z)},a]=\frac{P(a)}{Q'(a)}\textcolor{red}{(只适用于1级)} & \text{a为1级极点}
\end{cases}$$

### 积分计算

$$\int_Cf(z)dz=2\pi iRes[f(z),a]$$

$C$内含有两个奇点（且其中一个为本性奇点），*分开计算*留数较为麻烦：$e.g.\ \int_{|z|=7}\frac{cos\frac{1}{z-2}}{6-z}dz\quad$，可以把$P92$定理$17$反用，只求一次罗朗级数：寻找$|z|=7$所处的解析范围，在$z-2>4$内展开为罗朗级数，则$\int_{|z|=7}\frac{cos\frac{1}{z-2}}{6-z}dz=2\pi a_{-1}$

### 计算实积分

> #### 小圆弧定理
>
> 当$\rho$充分小，$f(z)$在$C_{\rho}:z=a+\rho e^{i\theta},\alpha\leqslant\theta\leqslant\beta$上**连续**，且$\lim\limits_{z\rightarrow a}(z-a)f(z)=k$，则$\lim\limits_{\rho\rightarrow0}\int_{C_{\rho}}f(z)dz=i(\beta-\alpha)k$
>
> #### 大圆弧定理
>
> $C_{\rho}:|z|=R>R_0,f(z)$在$D:|z|>R_0,0\le argz\le\alpha,0<\alpha\le2\pi$内**连续**，且$\lim\limits_{z\rightarrow \infty}zf(z)=k$，则$\lim\limits_{\rho\rightarrow\infty}\int_{C_{\rho}}f(z)dz=i\alpha k$
>
> #### 约当定理
>
> 当$\rho$充分大，$f(z)$在$C_\rho:|z|=\rho,Imz>-a(a>0)$**上连续**，且$\lim\limits_{z\rightarrow\infty}f(z)=0$，则对$\forall\lambda>0$都有$\lim\limits_{\rho\rightarrow\infty}\int_{C_{\rho}}f(z)e^{i\lambda z}dz=0$

$$1.\int_{0(-\pi)}^{2\pi(\pi)}R(cos\theta,sin\theta)d\theta=2\pi i\sum_{k=1}^{n}Res[R(z),a_k]\qquad a_k为所有奇点$$

令$z=e^{i\theta}\quad d\theta=\frac{1}{iz}dz\quad cos\theta=\frac{1}{2}(z+\frac{1}{z})=Re\ e^{i\theta}\quad sin\theta=\frac{1}{2}(z-\frac{1}{z})=Im\ e^{i\theta}\quad 路径\rightarrow|z|=1(逆)$

必备技巧：奇偶性、变量代换

$$2.\int_{-\infty}^{+\infty}\frac{P(x)}{Q(x)}dx=2\pi i\sum_{k=1}^{n}Res[\frac{P(z)}{Q(z)},a_k]$$

证明用到：大圆弧定理

条件：$Q(x)$的次数高$P(x)2$次及以上，$Q(x)$在$x$轴上无零点，$a_k$为上半平面所有奇点

$$3.\int_{\textcolor{red}{-\infty}}^{+\infty}\frac{P(x)}{Q(x)}cosmxdx=\textcolor{red}{Re}\{2\pi i\sum_{k=1}^{n}Res[\frac{P(z)}{Q(z)}\textcolor{red}{e^{imz}},a_k]+\textcolor{red}{\pi i}\sum_{k=1}^{l}Res[\frac{P(z)}{Q(z)}\textcolor{red}{e^{imz}},x_k]\}$$

$$\int_{\textcolor{red}{-\infty}}^{+\infty}\frac{P(x)}{Q(x)}sinmxdx=\textcolor{red}{Im}\{2\pi i\sum_{k=1}^{n}Res[\frac{P(z)}{Q(z)}\textcolor{red}{e^{imz}},a_k]+\textcolor{red}{\pi i}\sum_{k=1}^{l}Res[\frac{P(z)}{Q(z)}\textcolor{red}{e^{imz}},x_k]\}$$

证明用到：小圆弧定理+约当定理

条件：$Q(x)$的次数高$P(x)1$次及以上，$Q(x)$在$x$轴上有$l$个一级零点$x_k$，$a_k$为$\textcolor{red}{上半平面}$所有奇点，$\textcolor{red}{m>0}$

### 幅角原理

> $lemma1$：设$a,b$分别是$f(z)$的$m$级零点和$n$级极点，则$a,b$都是$\frac{f'(z)}{f(z)}$的一级极点，且
> $$Res[\frac{f'(z)}{f(z)},a]=m,\quad Res[\frac{f'(z)}{f(z)},b]=-n$$
> $prove:f(z)=(z-a)^m\varphi(z)...$

$$\int_C\frac{f'(z)}{f(z)}dz=2\pi i(N-P)$$，可以用来求解分子是分母一阶导的积分

$$\Delta_Cargf(z)=2\pi(N-P)$$，$N=\sum C$内部的零点**级数**，$P=\sum C$内部的极点**级数**

### 儒歇定理（必考）

设函数$f(z)$及$\varphi(z)$在闭路$C$及其内部解析，且在$C$上有不等式$|f(z)|>|\varphi(z)|$，则在$C$内部$f(z)+\varphi(z)$和$f(z)$的零点个数相等(和函数零点的个数取决于模较大函数在$C$中的零点个数)$\quad how \ to\ prove?$

圆环情形：$e.g. \quad r_1<|z|<r_2$考虑$|Z|<r_1$内$N_{内圆}$；说明$|z|=r_1$上无零点；考虑$|Z|<r_2$内$N_{外圆}$；则$N=N_{外圆}-N_{内圆}$

## $chapter$ 7

### 唯一性定理

$f(z),g(z)$在区域$D$**内**解析，若$f(z),g(z)$在互不相同的点列$\alpha_1,\alpha_2,...,\alpha_k,...$上的值相等且$\lim\limits_{k\rightarrow\infty}=a$（$a$必须在$D$内），则$f(z)\equiv g(z)\quad z\in D.$

### 零点问题

证明无零点用最大模原理（边界不要求解析）；证明有零点用儒歇定理$f(z_0)=z_0...$（边界必须解析）；证明恒为零用唯一性定理

## $chapter$ 8

### 导数的几何意义

> 设$w=f(z)$在$D$内解析，$z_0\in D,w_0=f(z_0),\textcolor{red}{f'(z_0)\neq0}$，设$C:z(t)=x(t)+iy(t)$是$D$内过$z_0$的简单光滑曲线，$f(z)$将$C$映成$w$平面过$w_0$的曲线$C_1$
>

有：
$$w'(t)=f'(z(t))z'(t)$$
$$arg[w'(t_0)]=arg[f'(z_0)]+arg[z'(t_0)]$$
$$arg[f'(z_0)]=arg[w'(t_0)]-arg[z'(t_0)]$$
又有：
$$|f'(z_0)|=\lim\limits_{\Delta z\rightarrow 0}\frac{|\Delta w|}{|\Delta z|}$$
综上：$arg[f'(z_0)]$为旋转角，$|f'(z_0)|$为伸张系数，只与$z_0$有关

### 保形变换

区域$D$内**单叶函数**所确定的变换为保形变换（$f'(z)\neq0$）

### 黎曼定理

如果$D$是闭复平面上一个边界至少包含**两个点**（$\infty$可以看作一点）的**单连通**区域，则必存在单叶函数$w=f(z)$把$D$变为单位圆内部$D_1$.

### 分式线性变换

$$w=\frac{az+b}{cz+d},\quad ad-bc\neq0$$

规定：$w(-\frac{d}{c})=+\infty,w(\infty)=\frac{a}{c}$，满足**黎曼定理**
$$w=\frac{az+b}{cz+d}=\overbrace{\frac{a}{c}}^{T}+\overbrace{|\frac{b}{c}-\frac{ad}{c^2}|}^{S}\overbrace{exp\{iarg(\frac{b}{c}-\frac{ad}{c^2})\}}^{R}\overbrace{\frac{1}{z+\frac{d}{c}}}^{I}$$

### 寻找分式变换

- 任给$z$平面上三个不同点$z_1,z_2,z_3$和$w$平面上三个不同点$w_1,w_2,w_3$，存在一个唯一的分式线性变换把$z_1,z_2,z_3$分别变成$w_1,w_2,w_3$


  $$\frac{w-w_1}{w-w_2}\cdot\frac{w_3-w_2}{w_3-w_1}=\frac{z-z_1}{z-z_2}\cdot\frac{z_3-z_2}{z_3-z_1}$$

- 若给定两个条件$w(z_1)=w_1,w(z_2)=w_2$（一般为两个对称点）则变换可以表示为


  $$\frac{w-w_1}{w-w_2}=k\frac{z-z_1}{z-z_2}$$，$k$为任意复常数，一般由边界对应边界的关系确定

定义：$z_1,z_2$关于有限圆周$|z-z_0|=R$的对称点：$|z_1-z_0||z_2-z_0|=R^2$，圆心对应无穷

### 几种常见的保形变换

- 上半平面$\rightarrow$单位圆，把$z_0$变为圆的圆心

  $w=e^{i\theta}\frac{z-z_0}{z-\bar{z_0}}$

- 单位圆$\rightarrow$单位圆，把$z_0$变为第二个圆的圆心

  $w=e^{i\theta}\frac{z-z_0}{1-z\bar{z_0}}$

- 二角形$\rightarrow$上半平面

  $\varphi_1=\frac{z-顶点1}{z-顶点2}$
  
- 将（原像）条形域变成角域用指数函数$e^z$，将（原像）角域变成条形域用对数函数主值$lnz$

## $chapter$ 9

### 拉氏变换

$Def:f(t)$是实变量$t$的实值函数或复值函数，当$t<0$时$f(t)=0$
$$F(p)=\int_0^{+\infty}f(t)e^{-pt}dt$$
若其在$p$的某个区域内收敛，则其称为$f(t)$的拉普拉斯变换（像函数）记为$F(p)=L[f(t)]$，$f(t)$为本函数，记为$f(t)=L^{-1}[F(p)]$

注：$f(t)$的拉氏变换就是$f(t)h(t)e^{-\sigma t}$的傅氏变换

### 一些重要的拉式变换

$$L[1]=\frac{1}{p}\\L[e^{at}]=\frac{1}{p-a}\\L[cos\omega t]=\frac{p}{p^2+\omega^2},L[cos\omega ht]=\frac{p}{p^2-\omega^2}\\L[sin\omega t]=\frac{w}{p^2+\omega^2},L[sin\omega ht]=\frac{w}{p^2-\omega^2}\\L[t^n]=\frac{n!}{p^{n+1}}$$

#### 本函数的微分

$$L[f^{(n)}(t)]=p^nL[f(t)]-p^{n-1}f(+0)+p^{n-2}f^{(1)}(+0)+...+f^{(n-1)}(+0)$$

#### 本函数的积分

$$L[\int_0^tf(t)dt]=\frac{1}{p}L[f(t)]$$

#### 像函数的微分

$$\frac{d^n}{dp^n}L[f(t)]=L[(-t)^nf(t)]$$

像函数求导，本函数乘$-t$

#### 像函数的积分

$$\int_p^{\infty}L[f(t)]dp=L[\frac{f(t)}{t}]$$

像函数积分，本函数除以$t$

#### 位移定理

$$F(p+a)=e^{-at}F(p)$$

$$L^{-1}[F(p+\mu)]=e^{-\mu t}L^{-1}[F(p)]$$

#### 延迟定理

$$L[f(t-\tau)h(t-\tau)]=e^{-\tau p}L[f(t)]$$

$$L^{-1}e^{-p\tau}L[f(t)]=f(t-\tau)h(t-\tau)$$

#### 卷积定理

$$L[f_1*f_2]=L[f_1]L[f_2]$$

$$L^{-1}[F_1(p)F_2(p)]=L^{-1}[F_1(p)]*L^{-1}[F_2(p)]$$

#### $Fourier-Mellin$公式

$$f(t)=h(t)\{\sum_{k=1}^nRes[F(p)e^{pt},p_k]\}\quad t>0$$

或者$f(t)=h(t)\{F(p)e^{pt}在实轴所有奇点留数和+2Re(F(p)e^{pt}在上半平面所有奇点留数和)\}$

#### $tips:$

- 分母不能因式分解$\rightarrow$配方$\rightarrow$位移定理

- $\frac{1}{(p-a)^2(p^2+b)}=\frac{A}{p-a}+\frac{B}{(p-a)^2}(几次几项)+\frac{Cp+D}{p^2+b}$保留$A=-\frac{2a}{2a^2b+b^2+a^4},B=\frac{a^2+b}{2a^2b+b^2+a^4},C=\frac{2a}{2a^2b+b^2+a^4},D=\frac{a^2-b}{2a^2b+b^2+a^4}$直到最后再代入数值

- 积化和差

- 求导

------



[复变函数（第二版）严镇军]: 

