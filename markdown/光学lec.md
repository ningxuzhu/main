<font size=2>

# 光学重点

[TOC]



## 几何光学
#### 几何光学三定律
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
#### 傍轴光线反射球面物象距公式
$$\frac{1}{s}+\frac{1}{s'}=-\frac{2}{r}(n'\rightarrow-n,s'\rightarrow-s')$$
#### 折射球面横向放大率公式
$V=-\frac{ns'}{n's}$，反射球面横向放大率公式$V=-\frac{s'}{s}(n'\rightarrow-n,s'\rightarrow-s')$
#### $Gauss$公式
$$\frac{f'}{s'}+\frac{f}{s}=1$$
#### $Lagrange-Helmhotz$恒等式
$$ynu=y'n'u'$$
（其中$u$为光线倾角）
### 薄透镜动力学
$$\frac{n}{s}+\frac{n'}{s'}=\frac{n_{l}-n}{r1}+\frac{n'-n_{l}}{r2}$$
其中$n_{l}$为薄透镜折射率
令$\Phi_{1}=\frac{n_{l}-n}{r_{1}},\Phi_{2}=\frac{n'-n_{l}}{r_{2}},\Phi_{1}+\Phi_{2}=\Phi$
得到
$$\frac{n}{s}+\frac{n'}{s'}=\Phi$$
#### 空气中磨镜者公式
$$f=f'=\frac{1}{(n_{l}-1)(\frac{1}{r_{1}}-\frac{1}{r_{2}})}$$
空气中的薄透镜物距和像距**永远**位于两侧
#### 牛顿物像公式
$$xx'=ff'$$
#### 横向放大率
$$V=-\frac{ns'}{n's}=-\frac{fs'}{f's}=-\frac{x'}{f'}=-\frac{f}{x}$$
注意：负号是由第一次呈像的物距变为第二次呈像的像距产生的
#### 密接薄透镜组
$$\frac{1}{s}+\frac{1}{s'}=\frac{1}{f_{1}}+\frac{1}{f_{2}}$$
### 作图法（三条重要光线）
需要熟练掌握凹透镜作图
#### 主点&主面
主面：过主点做垂直于光轴的平面，是横向放大率为1的一对共轭面
## $class7$
光学间隔：$\Delta=|F_i'F_{i+1}|(\Delta>0$发散；$\Delta<0$会聚；$\Delta=0$无焦$)$

系统间隔：$d=|H_i'H_{i+1}|$

$X_{H}=|H_1H|\quad X_{H'}=|H_nH|$

$\Rightarrow f'=-\frac{f_1'f_2'}{\Delta},X_H'=\frac{df_2'}{\Delta}$

$\Rightarrow f=-\frac{f_1f_2}{\Delta},X_H=\frac{df_1}{\Delta}$

$\Phi=\frac{1}{f_1}+\frac{1}{f_2}-\frac{d}{f_1f_2}$

#### 横向放大率
$V=-\frac{ns'}{n's}$
#### 角放大率
$W=\frac{tanu'}{tanu}=-\frac{s}{s'}$
#### $VW=\frac{n}{n'}$
#### $Lagrange-Helmhotz$恒等式
$$yntanu=y'n'tanu'$$
(其中$u$为光线倾角)

### 照相相关

景深：由$Newton$物像公式得
$$\frac{\delta x'}{\delta x}=-\frac{f^2}{x^2}$$
大光圈+长焦镜头+近距离$\rightarrow$小景深

小光圈+短焦镜头+远距离$\rightarrow$大景深

像差：见PPT

## $class9$

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

## 波动光学
### 波前
记初相位为$-\varphi_0$
#### 平面波
$Def:$(i)振幅为常数(ii)具有线性相位因子

复振幅$\widetilde{U_P}=Ae^{i(\bf k\cdot \bf r+\varphi_0)}$

#### 球面波
复振幅$\widetilde{U_P}=\frac{a}{r}e^{i(kr+\varphi_0)}$

$\varphi(P)=kx-$源初相位
### 偏振光
总设
$$\begin{cases}
E_x=A_xcos(wt)\\
E_y=A_ycos(wt+\Delta\varphi)\\
\end{cases}$$
则“广义椭圆”的取向只取决于相位差

左旋偏振光：迎着传播方向观察，电矢量逆时针转动

右旋偏振光：迎着传播方向观察，电矢量顺时针转动
#### 马吕斯定律
$I_\theta=I_0cos^2\theta$
### $Fresnel$反射折射公式
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

光强（波印廷矢量）$I\propto n|E|^2$

能流（光强投影）反射率$\mathscr{R}=r^2$

能流（光强投影）透射率$\mathscr{T}=\frac{n_2cosi_2}{n_1cosi_1}t^2$

#### 布儒斯特角
$r_p=0,i_b+i_2=\frac{\pi}{2}$

$i_b=arctan(\frac{n_2}{n_1})$
#### 斯托克斯倒逆关系
无论是$s$分量还是$p$分量，其内反射与外反射振幅反射比$r=-r'$，相应的振幅透射比（$t_s$与$t_s'$，$t_p$与$t_p'$）总是符号相同， $tt'+r^2=1$
## $class13$
自然光经过偏振片强度变为原来的一半

入射光的半波损失:当且仅当$S$波和$P$波同时发生振动方向的反转，即只有**正入射**和**掠入射**的时候可能发生

反射光的半波损失:介质层（折射率$n_2$）上下表面的折射率为$n_1,n_3$，当满足$n_2$为极值时两反射光有半波损失
## 波动光学
### 干涉
$$I(P)=I_1(P)+I_2(p)+2\sqrt{I_1(P)I_2(P)}cos\delta(p)$$
#### 干涉的必要条件
**1.频率相同**（保证积分不为0）

**2.存在相互平行的振动分量**

**3.相位差$\delta(P)$稳定** $\delta$不固定则会出现$cos\delta$迅速变化使得$\overline{cos\delta}$为0

### 分波前干涉

条纹间距为

$$\Delta x=\frac{D}{d}\lambda$$

#### 光强衬比度

$$\gamma=\frac{2A_1A_2}{A_1^2+A_2^2}$$
则干涉公式变为：
$$I=I_0(1+\gamma cos\delta)$$
其中$I_0=I_1+I_2=A_1^2+A_2^2$

#### 两束平行光的干涉

沿$x,y$方向的条纹间距为
$$\begin{cases}
\Delta x=\frac{\lambda}{sin\alpha_1-sin\alpha_2}\\
\Delta y=\frac{\lambda}{cos\alpha_1-cos\alpha_2}\\
\end{cases}$$
空间频率为
$$\begin{cases}
f_x=\frac{1}{\Delta x}\\
f_y=\frac{1}{\Delta y}\\
\end{cases}$$

#### 光源宽度与干涉条纹的关系

$$\begin{cases}
\delta x=\frac{D}{R}\delta s\\
\Delta x=\frac{D}{d}\lambda\\
\end{cases}$$
$\delta x=\Delta x$（点源连续分布），令$\delta s=b_1$得到光源极限宽度：$b_1=\frac{R}{d}\lambda$

![光源宽度与干涉](D:\VScode文件\markdown\光源宽度与干涉.png)

#### 光源宽度与衬比度
$$\gamma=|\frac{sinu}{u}|$$
其中$u=\frac{b}{b_1}\pi$

### 分振幅干涉$\Delta L=2nhcosi_2(\pm\frac{\lambda}{2})$
等厚干涉
$$e.g\begin{cases}
楔形薄膜\Delta x=\frac{\lambda}{2\alpha}\\
牛顿环R=\frac{r^2_{k+m}-r^2_k}{m\lambda}中央级数最小，牛顿环向上移动，各级数变大\\
\end{cases}$$

等倾干涉：$\Delta L=2nhcosi_2(\pm\frac{\lambda}{2})$中央级数最大，增大$h$级数变大，有$l=N\frac{\lambda}{2}$
### 迈克尔逊干涉仪

#### 光源非单色性对条纹的影响
最大光程差（空间周期）
$$\Delta L_M=\frac{2\pi}{\Delta k}=\frac{\lambda^2}{|\Delta \lambda|}$$

#### 光源的时间相干性
$\tau_0\Delta\nu\approx1$
#### 光源的空间相干性
$b\Delta \theta=\lambda$

## 波动光学的一些应用
### 法布里-珀罗干涉
$$I_T=\frac{I_0}{1+\frac{4Rsin^2(\delta/2)}{(1-R)^2}}$$
推导需要使用**斯托克斯倒逆定理**，可以看出，$R$增大，反射条纹亮线越来越宽，透射条纹亮线越来越窄

由$\delta=\frac{4\pi nhcosi}{\lambda},n$和$h$一般是不变的，影响$\delta$变化的因素有$i$和$\lambda$

$(1)\lambda$固定，则半角宽度为
$$\Delta i=\frac{\lambda}{2\pi nhsini}\frac{1-R}{\sqrt{R}}$$
$(2)i$固定(经常是0)，则某一纵模的半值宽度为
$$\Delta \lambda=\frac{\lambda^2}{2\pi nhcosi}\frac{1-R}{\sqrt{R}}$$
由于多光束干涉，使得在很宽的光谱范围内只有特定的波长附近出现极大$2nh=k\lambda_k,k\in\mathbb{Z}$，相邻极强频率间是等间隔的：$\Delta\nu=\frac{c}{2nh}$

色分辨本领为：$\frac{\lambda}{\delta \lambda}=k\frac{\pi\sqrt{R}}{1-R}$

### 菲涅尔圆孔衍射和圆屏衍射

矢量图解$P151.5$

#### 半波带半径
$$\rho_k=\sqrt{\frac{Rb}{R+b}k\lambda}\qquad (k=1,2,...)$$

转化成透镜公式：
$$\frac{1}{R}+\frac{1}{b}=\frac{k\lambda}{\rho_k^2}\qquad \text{即}f=\frac{\rho_1^2}{\lambda}$$

### 夫琅禾费单缝衍射和矩孔衍射

矢量图解图像：$P154图7-4$

光强分布：
$$I_\theta=I_0(\frac{sin\alpha}{\alpha})^2$$
其中$\alpha=\frac{\pi a}{\lambda}(sin\theta\pm sin\theta_0),\frac{sin\alpha}{\alpha}$为单缝衍射因子，$\theta_0$为入射光与单缝所在平面法线的夹角

半角宽度：
$$\Delta\theta=\frac{\lambda}{acos\theta_0}$$
应用：由巴比涅定律，细丝所呈衍射图像与单缝所呈图像完全一致，可以用来测细丝直径

### 光学仪器像分辨本领

由于光学仪器光具组几乎都是圆形的，根据夫琅禾费圆孔衍射：$I_\theta=I_0[\frac{2J_1(x)}{x}]^2$，半角宽度为
$$\Delta\theta=1.22\frac{\lambda}{D}$$
由瑞利判据得光学仪器最小分辨角$\delta\theta_m=\Delta\theta$

角放大率
$$M=\frac{\delta\theta_e}{\delta\theta_m}$$
$\delta\theta_e\approx1'=2.9\times10^{-4}rad$

<font color=Blue>

显微镜分辨本领$\delta y_m=\frac{0.61\lambda}{N.A.}$

</font>

### 多缝夫琅禾费衍射

相关参数：光栅常数$d=a+b$，光栅有效长度$L=Nd$
$$I_\theta=a_0^2(\frac{sin\alpha}{\alpha})^2(\frac{sinN\beta}{sin\beta})^2\qquad \alpha=\frac{\pi a}{\lambda}sin\theta\quad\beta=\frac{\pi d}{\lambda}sin\theta$$
分析思路：矢量图解法（区别：衍射时$R\propto A_0$，干涉时$R\propto a_\theta$），单缝衍射因子和缝间干涉因子相乘实现相位调制，出现缺级

### 光栅分光

对于一定波长差$\delta\lambda$的两条谱线的角间隔？由光栅方程$dsin\theta_k=k\lambda$，取微分得到$\delta\theta=\frac{k\delta\lambda}{dcos\theta_k}$

$k$级条纹的角宽度：$\frac{\pi d}{\lambda}sin\theta_k=k\pi\qquad\frac{\pi d}{\lambda}sin(\theta_k+\Delta\theta)=(k+\frac{1}{N})\pi\quad\rightarrow\Delta\theta=\frac{\lambda}{Ndcos\theta_k}$

由瑞利判据$\delta\theta=\Delta\theta$得最小分辨波长$\delta\lambda=\frac{\lambda}{kN}$

### 闪耀光栅

由于$\alpha$中$\theta$是光线与狭缝法线的夹角，$\beta$中$\theta$则是与整个光栅平面法线夹角，传统的光栅$\theta$相同，衍射的零级主极大与干涉的零级主极大重合，导致大部分能量和信息都集中于光栅中央

## 傅里叶光学

### 屏函数

凡使波前上的复振幅发生改变的物都称为衍射屏，都具有屏函数：
$$\widetilde{t}(x,y)=\frac{\widetilde{U_2}(x,y)}{\widetilde{U_1}(x,y)}$$

![相因子1](D:\VScode文件\markdown\相因子1.png)

![相因子2](D:\VScode文件\markdown\相因子2.png)

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

### 双折射

$o$光：满足折射定律；$e$光：一般不满足折射定律

$$\begin{cases}主截面：晶体表面的法线方向与晶体内光轴方向所组成的平面\\主平面：晶体中某条光线与晶体光轴所构成的平面\\入射面：光线所在平面\\\end{cases}$$

光轴平行于界面，光线正入射（波片）

光线斜入射，光轴垂直于入射面（$o$光$e$光均满足折射定律）

### 偏振光的获得与检验

![检验偏振光](D:\VScode文件\markdown\检验偏振光.png)

![椭圆相位](D:\VScode文件\markdown\椭圆相位.png)

### 偏振光干涉

![偏振光干涉](D:\VScode文件\markdown\偏振光干涉.png)

各种光线通过巴比涅补偿器与偏振片的干涉
