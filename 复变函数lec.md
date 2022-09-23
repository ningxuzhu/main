<font size=2>

# 复变函数重点
## $class1$
### 辐角主值的计算：
$$arg=
\begin{cases}
0& \text{正实轴}\\
\pi& \text{负实轴}\\
\pi/2& \text{上半虚轴} \\
-\pi/2& \text{下半虚轴} \\
arctan \frac{y}{x} &\text{一、四象限} \\
arctan \frac{y}{x}+\pi &\text{第二象限} \\
arctan \frac{y}{x}-\pi &\text{第三象限} 
\end{cases}$$ 
1.**$arg\in(-\pi,\pi]$**

3.$arg0$ 无意义

2.$|z|^{2}=z\bar{z}$
## $class2$
### 复数的开方(de Moivre公式)以n为周期，有n个值(内接圆正n边形顶点)
#### $z_{0}是z_{n}的极限即\lim\limits_{n\rightarrow\infty}|z_{n}-z_{0}|=0$

### 一些概念:
#### 复平面(开复平面或有限平面) && 闭复平面或扩充平面
#### 区域：非空，开集(无膜)，连通(任意内点用全在区域中的折线连接) vs 闭区域(有膜)
#### 有界集：可包含在以原点为中心的某一圆内。无界集不可
#### Jordan曲线(简单曲线)：无重点且连续
#### 任一简单<font color=red>闭</font>曲线分平面为两区域，其中有界集称为内区域，无界集称为外区域
$$区域
\begin{cases}
单连通(无洞，无内割痕) \\
多连通
\end{cases}$$
## $class3$
### 复变函数
#### 单值函数：$z$与唯一复数$w=u+iv$对应
#### 多值函数：$z$对应两个及以上$w$
一个复变函数对应两个实变函数$u(x,y),v(x,y)$或$u(r,\phi),v(r,\phi)$
#### 一一映照：$z_{1}-z_{2}\neq0\longleftrightarrow w_{1}-w_{2}\neq0$
### 求曲线在映照下的像的一般方法：
#### 法一：1.求映照$w$确定的两个实变函数。2.将原像曲线方程与函数对应方程联立，消$x,y$得到关于$u，v$的方程。
#### 法二：将原像方程写成关于$z$的方程，再带入逆映照。
### 函数的极限
$\forall \varepsilon>0$，当$|z-z_{0}|<\delta$时有$|f(z)-w_{0}|<\varepsilon$则称当$z$趋向于$z_{0}$时，$f(z)$的极限值是$w_{0}$
### 函数的连续
若$\lim\limits_{z\rightarrow z_{0}}f(z)=f(z_{0})，$那么称$f(z)$在$z_{0}$连续，推广至区域$D$连续记为$f(z)\in C(D)$

连续充要条件：$u(x,y),v(x,y)$连续

结论：多项式在复平面处处连续，有理分式在除去使分母为0的点连续

$argz$在$z=0$与$x<0$时不连续
## $class4$
### 函数的导数
$w=f(z)$在$z$的某个邻域内有定义，若$\lim\limits_{\Delta z\rightarrow0}\frac{f(z+\Delta)-f(z)}{\Delta z}$存在，则称$f(z)$在$z$可微
### 解析
$f(z)$在$z_{0}$的某个邻域$(|z-z_{0}|<\delta)$内<font color=red>每一点</font>可微，则称$f(z)$在$z_{0}$解析
### 奇点
$f(z)$在$z_{0}$的任一领域内都有不可微的点，则称$z_{0}$为$f(z)$的奇点

结论：$f(z)=\bar{z}$处处不可微，处处不解析
### Cauchy-Riemann function(判断可微的充要条件)
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
## $class5$
### 根式函数$w=\sqrt[n]{z}$
#### 辐角变化
$z$平面上存在一条起点为$a$，终点为$b$的连续曲线。选定$arga\Rightarrow argb$被确定$\Delta_{l}argz=argb-arga$
$$l是连续闭曲线
\begin{cases}
\Delta_{l}argz=2\pi& \text{原点在内}\\
\Delta_{l}argz=0& \text{原点在外}\\
\end{cases}$$
#### 支点
在$z=a$点的充分小邻域内，作一条包围该点的闭曲线$C$ ，绕$C$连续转动一周后$f(z)$从一个值变到另一个值，就称$a$是$f(z)$的支点。

$ps$：考虑$\Delta_{l}argz$是否引起$f(z)$的任何变化

$z=0,z=\infty$是$w=\sqrt[n]{z}$的支点

$w=\sqrt{z^2-1},w=\sqrt[4]{\frac{z(1-z)^{3}}{(z+i)^{4}}}$的支点？
#### 支割线
连接$f(z)$任意两支点的**简单**曲线\
目的：防止曲线包围支点
#### 单值解析分支
第$k$支的表达式为$w_{k}=\sqrt[n]{r}exp(i\frac{argz+2k\pi}{n}),k=0,1,2,...,n-1$

$w_{k}$把割开了的$z$平面$(2k-1)\pi<argz<(2k+1)\pi$映为角域$D_{k},\frac{(2k-1)\pi}{n}<argw<\frac{(2k+1)\pi}{n}$
## $class5$
### 指数函数$w=e^{z}$
$|e^{z}|=e^{x},Arge^{z}=Imz+2k\pi$

$w$把$z$的条形域映为角域
## $class6$
### 对数函数$w=Lnz$
$\forall z\neq0,\exist Lnz,u=ln|z|,v=Argz,Lnz=ln|z|+i(argz+2k\pi)$

支点：$z=0,\infty$


$-\pi<argz<\pi\Rightarrow(2k-1)\pi<Imw_{k}<(2k-1)\pi$\
$w$把$z$的角域映为条形域
### 三角函数$sinz=\frac{(e^{iz}-e^{-iz})}{2i},cosz=\frac{(e^{iz}+e^{-iz})}{2}$
1.三角函数是欧拉公式在$\mathbb{C}$上的推广

2.$|sinz|=|sin(x+iy)|$，利用倍角公式得$|sinz|=\sqrt{cos^2hy-cos^2x}$
### 双曲函数$sinhz=\frac{(e^{z}-e^{-z})}{2},coshz=\frac{(e^{z}+e^{-z})}{2}$
注意：$sinz,cosz,sinhz,coshz$无界

$cosh(a+b)=coshacoshb+sinhasinhb$\
$sinh(a+b)=sinhacoshb+coshasinhb$
### 反三角函数$e.g.(w=Arcsinz)$
解法：两边取三角函数，令$e^{iz}=\beta$，求解关于$\beta$的一元二次方程，最后两边取$Ln$
### 一般幂函数$w=z^\alpha=e^{\alpha  Lnz}$
## $class7$
### 函数的积分
条件：$f(z)$在（逐段）**光滑**曲线上**连续**
$$\int_{C}f(z)dz=\int_{C}udx-vdy+i\int_{C}vdx+udy$$
#### 参数法求积分(不解析函数只能用此办法)
$t$为参数且$a\leqslant t\leqslant b$，  正方向为逆时针方向
$$\int_{C}f(z)dz=\int_{a}^{b}f(z(t))z'(t)dt$$
直线参数方程：$z=$(终点$-$起点)$t+$起点（$0\leqslant t\leqslant1$）

圆的参数方程：$z=$圆心$+$半径$e^{i\theta}$（$\theta$从圆心计算）

结论：$C:|z-a|=R$，正方向为逆时针方向

$$\oint_{C}\frac{1}{(z-a)^n}dz=
\begin{cases}
2\pi i & n=1\\
0      & n\neq1\\
\end{cases}$$
长大不等式：$|\int_{C}f(z)dz|\leqslant\int_{C}|f(z)||dz|\leqslant sup|f(z)|\cdot s_C$
## $class8$
### 柯西积分定理
闭域$\bar{D}$内一闭路$C$围成单连通区域，$f(z)$在$\bar{D}$内解析，则$\oint_{C}f(z)dz=0$\
考虑：是闭路？奇点在内？

### 多连通区域的柯西积分定理
$Def$复闭路：$C_0,C_1,...,C_n$为$n+1$条**简单**闭曲线，$C=C_0+C_1^-+...+C_n^-$且满足：\
$1.C_0,C_1,...,C_n$都在$C_0$内；\
$2.C_0,C_1,...,C_n$互不接触；

$\bar{D}(=\bar{D_1}+\bar{D_2}+...+\bar{D_n})$为$C_0$内的多连通区域，若$f(z)$在$\bar{D}$上解析，则$\int_{C}f(z)dz=0$

$\int_{C_0}f(z)dz=\int_{C_1}f(z)dz+\int_{C_2}f(z)dz+...+\int_{C_n}f(z)dz$
### $Newton-Leibniz$ $eqution$
若$f(z)$在单连通区域$D$内解析$H(z)$是$f(z)$的**任一**原函数，$\forall z_0,z\in D$\
$F(z)=\int_{z_0}^{z}f(\zeta)d\zeta=H(z)-H(z_0)$

$Q:how$ $to$ $proof?$

