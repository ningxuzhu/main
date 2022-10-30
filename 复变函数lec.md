<font size=2>

# 复变函数重点
## $class1$
### 辐角主值的计算：
$$arg(x+iy)=
\begin{cases}
arctan \frac{y}{x} &\text{一、四象限} \\
arctan \frac{y}{x}+\pi &\text{第二象限} \\
arctan \frac{y}{x}-\pi &\text{第三象限} 
\end{cases}$$ 
### $Tips$：
1.**$arg\in(-\pi,\pi]$**

2.$arg0,arg\infty$ 无意义

3.$|z|^{2}=z\bar{z},|z|=\textcolor{red}{\sqrt{x^2+y^2}}$

4.指数式的标准形式：$r(实数)e^{i\theta}$
## $class2$
### 复数的开方(de Moivre公式)以n为周期，有n个值(内接圆正n边形顶点)
#### $z_{0}是z_{n}的极限即\lim\limits_{n\rightarrow\infty}|z_{n}-z_{0}|=0$

### $Some$ $Definition$:
#### 复平面(开复平面或有限平面) && 闭复平面或扩充平面
#### 区域：非空，开集(无膜)，连通(任意内点用全在区域中的折线连接) vs 闭区域(有膜)
#### 有界集：可包含在以原点为中心的某一圆内
#### $Jordan$曲线(简单曲线)：无重点且连续
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
$\forall \varepsilon>0$，$\exists\delta>0$，当$|z-z_{0}|<\delta$时，有$|f(z)-w_{0}|<\varepsilon$，则称当$z$趋向于$z_{0}$时，$f(z)$的极限值是$w_{0}$
### 函数的连续
若$\lim\limits_{z\rightarrow z_{0}}f(z)=f(z_{0})$，那么称$f(z)$在$z_{0}$连续，推广至区域$D$连续记为$f(z)\in C(D)$

函数连续的充要条件：$u(x,y),v(x,y)$连续

#### 结论：

1.多项式在复平面处处连续，有理分式在除去使分母为0的点连续

2.$argz$在$z=0$与$x<0$时不连续
## $class4$
### 函数的导数
$w=f(z)$在$z$的某个邻域内有定义，若$\lim\limits_{\Delta z\rightarrow0}\frac{f(z+\Delta)-f(z)}{\Delta z}$存在，则称$f(z)$在$z$可微
### 解析
$f(z)$在$z_{0}$的某个邻域$(|z-z_{0}|<\delta)$内<font color=red>每一点</font>可微，则称$f(z)$在$z_{0}$解析
### 奇点
$f(z)$在$z_{0}$的任一领域内都有不可微的点，则称$z_{0}$为$f(z)$的奇点

#### 结论：
$f(z)=\bar{z}$ 处处不可微，处处不解析

$f(z)$解析，若$|f(z)|=const.$，则$f(z)=const.$
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
连接$f(z)$任意两支点的**简单**曲线
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

$-\pi<argz<\pi\Rightarrow(2k-1)\pi<Imw_{k}<(2k-1)\pi$
$w$把$z$的角域映为条形域

### 三角函数$sinz=\frac{(e^{iz}-e^{-iz})}{2\textbf{i}},cosz=\frac{(e^{iz}+e^{-iz})}{2}$
1.三角函数是欧拉公式在$\mathbb{C}$上的推广

2.$|sinz|=|sin(x+iy)|$，利用倍角公式得$|sinz|=\sqrt{cos^2hy-cos^2x}$

$Exercise：$
### 双曲函数$sinhz=\frac{(e^{z}-e^{-z})}{2},coshz=\frac{(e^{z}+e^{-z})}{2}$
注意：$sinz,cosz,sinhz,coshz$无界

$cosh(a+b)=coshacoshb+sinhasinhb$

$sinh(a+b)=sinhacoshb+coshasinhb$

### 反三角函数$e.g.(w=Arcsinz)$
解法：两边取三角函数，令$e^{iz}=\beta$，求解关于$\beta$的一元二次方程，最后两边取$Ln$
### 一般幂函数$w=z^\alpha=e^{\alpha  Lnz}$
## $class7$
### 函数的积分
条件：$f(z)$在（逐段）**光滑**曲线上**连续**
$$\int_{C}f(z)dz=\int_{C}udx-vdy+i\int_{C}vdx+udy$$
#### 参数法求积分(不解析函数只能用此办法，含$|dz|,\bar{z}$一般也用)
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



### 长大不等式
$|\int_{C}f(z)dz|\leqslant\int_{C}|f(z)||dz|\leqslant sup|f(z)|\cdot s_C$

## $class8$
### 柯西积分定理
闭域$\bar{D}$内闭路$\widetilde{C}$围成单（多）连通区域，$f(z)$在$\bar{D}$内解析，则$\int_{C}f(z)dz=0$

考虑：是闭路？奇点在内？
### $Newton-Leibniz$ 等式
若$f(z)$在单连通区域$D$内解析$H(z)$是$f(z)$的**任一**原函数，$\forall z_0,z\in D$

$F(z)=\int_{z_0}^{z}f(\zeta)d\zeta=H(z)-H(z_0)$

$Q:how$ $to$ $prove?$

## $class9$
### 柯西积分公式
若$f(z)$在闭路$C$及其所谓区域$D$内解析，则$\forall a_0\in D$
$$\int_{C}\frac{f(z)}{z-a_0}dz=2\pi if(a_0)$$
注意：$z$前的系数必为1

$prove?$ 连续+长大不等式，难点：构造出$f(z)$
### 高阶导数积分公式
$\forall a_0\in D，$$f(z)$有任意阶导数！！
$$\int_{C}\frac{f(z)}{(z-a_0)^n}dz=\frac{2\pi i}{(n-1)!}f^{(n-1)}(a_0)$$
$prove?$ $definition$+归纳+长大不等式，难点：$k-1\rightarrow k$
## $class10$
### 平均值公式（边界决定内部）
$f(z)$在闭圆$|z-a|\leqslant R$内解析
$$f(z)=\frac{1}{2\pi R}\int_{|z-a|=R}f(\zeta)ds$$
### 最大模原理
$f(z)$在有界区域$D+C$上解析且不恒等于常数，则$\exist a\in C,s.t.|f(z)|_{max}=|f(a)|$


### 柯西不等式（解析函数导数模的估计）
设$f(z)$在$|z|\leqslant R$上解析，且边界上的最大值为$M(R)$，则有
$$|f^{(n)}(z)|\leqslant \frac{n!M(R)}{R^n}$$

### $Liouville$定理
不恒为常数的整函数模无界

### $ex:$
证明：$f'(a)=\frac{1}{\pi r}\int_0^{2\pi}Re[f(a+re^{i\theta})]e^{-i\theta}d\theta$

难点：运用柯西积分定理+取共轭

$Tip:$对零点问题用反证+取倒数+最大模原理

$Tip:$对外部解析的问题，构造更大的复闭路
## $class 11$
### 调和函数
$\Delta f=0$

定理：$f$解析，其实部和虚部为共轭调和函数
### 必出考题
已知$u$调和，在$(x_0,y_0)$解析，求$f(z)$
$$v(x,y)=\int_{(x_0,y_0)}^{(x,y)}\frac{\partial v}{\partial x}dx+\frac{\partial v}{\partial y}dy+\textcolor{red}{C}$$

$$\stackrel{C-R}{\rightarrow}v(x,y)=\int_{(x_0,y_0)}^{(x,y)}-\frac{\partial u}{\partial y}dx+\frac{\partial u}{\partial x}dy+\textcolor{red}{C}$$

$$v(x,y)=\int_{x_0}^{x}-\frac{\partial u}{\partial y}\textcolor{red}{\bigg|_{y=y_0}}dx+\int_{y_0}^{y}\frac{\partial u}{\partial x}\bigg|_{x=x}dy+\textcolor{red}{C}$$
$$f(x,y)=u(x,y)+iv(x,y)\stackrel{x=z,y=0}{\longrightarrow}f(z)$$
### 调和函数性质
$u(z)$只能在$D$的边界$c$上取得$\bar{D}$上的最大值和最小值  
构造$g(z)=e^{\pm u(z)\pm iv(z)}$，利用最大模原理即可
## $class12$
### 调和函数的泊松积分公式
$f(z)$为调和函数，其在圆内任意点的值可以用圆周上的积分表示出来（柯西积分公式+柯西积分定理$z=\frac{R^2}{r}$）
$$f(z_0+re^{i\varphi})=\frac{1}{2\pi}\int_{0}^{2\pi}\frac{R^2-r^2}{R^2-2rRcos(\theta-\varphi)+r^2}f(z_0+re^{i\varphi})d\theta$$
### 级数
部分和定义！ 一致收敛的定义！ $Cauchy$收敛准则
#### $\sum_{n=0}^{\infty}z^n$的敛散性：
$|z|<1$时收敛，$\sum_{n=0}^{\infty}z^n=\frac{1}{1-z}$ 但不绝对收敛(?)

$|z|\geqslant1$时发散（逐项不收敛）

$|z|\leqslant r,$ $0<r<1$强级数绝对收敛

## $class13$
### $Weierstrass$定理
设$f_n(z)$在$D$内解析且$\sum_{n=1}^{+\infty}f_n(z)$在$D$内一致收敛，则$f(z)$在$D$内解析，且$f^{(k)}(z)=\sum_{n=1}^{+\infty}f_n^{(k)}(z),k=1,2,3,...$**这是实函数没有的**
### $Abel$定理
### 收敛半径
实系数幂级数$\sum_{n=0}^{+\infty}|a_n|x^n$的收敛半径R是$\sum_{n=1}^{+\infty}a_n(z-a)^n$的收敛半径

$R=\frac{1}{r}$其中$r=\lim\limits_{n\rightarrow+\infty}|\frac{a_{n+1}}{a_n}|$或$r=\lim\limits_{n\rightarrow+\infty}\sqrt[n]{a_n}$
### $Taylor$展开
设$f(z)$在点$a$解析，以点$a$为半径作圆，直至碰到$f(z)$的奇点
$$f(z)=\sum_{n=1}^{+\infty}\frac{f^{(n)}(a)}{n!}(z-a)^n$$

展开步骤：

1.求奇点

2.求收敛半径$R=|展开点-距离最近的奇点|$

3.从$n=0$处展开成幂级数，注意从基本的函数展开开始再运用变量代换

4.在幂级数展开后写出收敛半径

一些注意的问题：

1.求和号内的首个常数项要与求和号外的常数项合并

2.不好展开的函数/**级数乘级数**考虑求导/积分函数是否比较好展开

3.展开到第$n$项指展开到$z^{n-1}$















