# 重积分

## 定义

定义 设$f(x,y)$是有界闭区域 D 上的有界函数,将闭区域 D 任意分成n个小闭区域

$$\Delta \sigma_1,\Delta \sigma_2,\cdots,\Delta \sigma_n$$

其中$\Delta \sigma_i$表示第$i$个小闭区域,也表示他的面积。在$\Delta \sigma_i$上任取一点$(\xi_i,\eta_i)$,作乘积$f(\xi_i,\eta_i)\Delta \sigma_i(i=1,2,\cdots,n)$,并作和$\sum_{i=1}^n f(\xi_i,\eta_i)\Delta \sigma_i$。如果当各小闭区域的直径中的最大值$\lambda$趋于零时,这和的极限总存在,则称此极限为函数$f(x,y)$在闭区域 D 上的二重积分,记作$\iint_D f(x,y)d\sigma$,即

$$\iint_D f(x,y)d\sigma=\lim_{\lambda\to 0}\sum_{i=1}^n f(\xi_i,\eta_i)\Delta \sigma_i$$

其中$f(x,y)$叫被积函数,$f(x,y)d\sigma$叫被积表达式,$d\sigma$叫面积元素，
x与y叫积分变量，D叫做积分区域，$\sum_{i=1}^n f(\xi_i,\eta_i)\Delta \sigma_i$叫做积分和。

在二重积分的定义中对闭区域 D的划分是任意的,如果在直角坐标系中用平行于坐标轴的直线网来划分 D,那么除了包含边界点的一些小闭区域外D,其余的小闭区域都是矩形闭区域.设矩形闭区域$\Delta \sigma_i$，的边长为$\Delta x_j$和$\Delta x_k$则$\Delta \sigma_i=\Delta x_j \cdot \Delta x_k$因此在直角坐标系中,有时也把面积元素$\Delta \sigma_i$记作 $dxdy$,而把重积分记作

$$\iint_D f(x,y)dxdy$$

## 二重积分的性质

## 二重积分的计算

$$\iint_D f(x,y)d\sigma=\int_a^b dx\int_{\varphi_1(x)}^{\varphi_2(x)} f(x,y)dy\\=\int_a^b dy\int_{\varphi_1(y)}^{\varphi_2(y)} f(x,y)dx$$

### 利用极坐标计算二重积分

## 三重积分

定义 设$f(x,y,x)$是空间有界闭区域 $\Omega$ 上的有界函数,将$\Omega$任意分成n个小闭区域

$$\Delta v_1,\Delta v_2,\cdots,\Delta v_n$$

其中$\Delta v_i$表示第$i$个小闭区域,也表示他的体积。在$\Delta v_i$上任取一点$(\xi_i,\eta_i,\zeta_i)$,作乘积$f(\xi_i,\eta_i,\zeta_i)\Delta v_i(i=1,2,\cdots,n)$,并作和$\sum_{i=1}^n f(\xi_i,\eta_i,\zeta_i)\Delta v_i$。如果当各小闭区域的直径中的最大值$\lambda$趋于零时,这和的极限总存在,则称此极限为函数$f(x,y,z)$在闭区域$\Omega$上的三重积分,记作$\iiint_\Omega f(x,y,z)dv$,即

$$\iiint_\Omega f(x,y,z)dv=\lim_{\lambda\to 0}\sum_{i=1}^n f(\xi_i,\eta_i,\zeta_i)\Delta v_i$$

$dv$叫体积元素。

在直角坐标系中,如果用平行于坐标面的平面来划分$\Omega$,那么除了包含$\Omega$的边界点的一些不规则小闭区域外,得到的小闭区域$\Delta v_i$为长方体。设长方体小闭区域$\Delta v_i$的边长为$\Delta x_j,\Delta y_k,\Delta z_l$则$\Delta v_i=\Delta x_j\cdot \Delta y_k\cdot \Delta z_l$.因此在直角坐标系中，有时也把体积元素 $dv$ 记作 $dxdydz$,而把三重积分记作

$$\iiint_\Omega f(x,y,z)dxdydz$$

### 三重积分的计算

$$\iiint_\Omega f(x,y,z)dxdydz=\int_a^b dx\int_{y_1(x)}^{y_2(x)}\int_{z_1(x,y)}^{z_2(x,y)} f(x,y)dy$$

### 利用柱面坐标计算三重积分

### 利用球面坐标计算三重积分

## 弧长曲线积分计算

定义 设L为xOy面内的一条光滑曲线驱,函数 $f(x,y)$在L上有界.在L上任意插入一点列$M_1,M_2,\cdots,M_{n-1}$把L分成n个小段设第个$i$小段的长度为$\Delta s_i$. 又$(\xi_i,\eta_i)$为第个小段上任意取定的一点, 作乘积 $f(\xi_i,\eta_i)\Delta s_i(i=1,2,\cdots,n)$, 并作和$\sum_{i=1}^n f(\xi_i,\eta_i)\Delta s_i$,如果当各小弧段的长度的最大值$\lambda \to0$, 这和的极限总存在,则称此极限为函数 $f(x,y)$在曲线弧L上对弧长的曲线积分或第一类曲线积分,记作$\int_Lf(x,y)ds$,即

$$\int_Lf(x,y)ds=\lim_{\lambda\to 0}\sum_{i=1}^n f(\xi_i,\eta_i)\Delta s_i$$

其中$f(x,y)$叫做被积函数, L叫做积分弧段。

**空间曲线**

$$\int_\Gamma f(x,y,z)ds=\lim_{\lambda\to 0}\sum_{i=1}^n f(\xi_i,\eta_i,\zeta_i)\Delta s_i$$

如果$L=L_1+L_2$

如果L是闭曲线，曲线积分记作为$\oint_Lf(x,y)ds$。

**性质**

性质1 设$\alpha,\beta$为常数，则

$$\int_L [\alpha f(x,y)+\beta g(x,y)]ds=\alpha\int_Lf(x,y)ds+\beta\int_Lg(x,y)ds$$

性质2 若积分弧段L可分成两段光滑的曲线弧$L_1,L_2$，则

$$\int_{L_1+L_2}f(x,y)ds=\int_{L_1}f(x,y)ds+\int_{L_2}f(x,y)ds$$

性质3 设在L上$f(x,y)\le g(x,y)$，则

$$\int_Lf(x,y)ds\le\int_Lg(x,y)ds$$

特别的有

$$|\int_Lf(x,y)ds|\le\int_L|g(x,y)|ds\$$

**计算**

定理 设$f(x,y)$在曲线弧L上有定义且连续, L 的参数方程为
$$
 \begin{cases}
 x=\varphi(t)  (\alpha<t<\beta)\\
 y=\psi(t)
 \end{cases}
$$

其中 $\varphi(t),\psi(t)$ 在$[\alpha,\beta]$上具有一阶连续导数，且$\varphi^{'2}(t)+\psi^{'2}(t)\ne 0$，则曲线积分$\int_Lf(x,y)ds$存在且

$$\int_Lf(x,y)ds=\int_{\alpha}^{\beta}f[\varphi(t),\psi(t)]\sqrt{\varphi^{'2}(t)+\psi^{'2}(t)}dt$$

## 对坐标的曲线积分

定义 设L为xOy面内从点 A 到点B 的一条有向光滑曲线弧，函数$P(x,y)Q(z,y)$在 L 上有界. 在 L 上沿L 的方向任意插入一点列 $M(x_1,y_1),M,(x_2,y_2),\cdots,M_{n-1}(x_{n-1},y_{n-1})$,把L分成n 个有向小弧段

$$\widehat{M_{i-1}M_i}(i=1,2,\cdots,n-1;M_0=A,M_n=B)$$

设$\Delta x_i=x_i-x_{i-1}$，$\Delta y_i=y_i-y_{i-1}$，点$(\xi_i,\eta_i)$为$\widehat{M_{i-1}M_i}$上任取一点，如果当各小弧段长度的最大$\lambda \to 0$时，$sum_{i=1}^n P(\xi_i,\eta_i)\Delta x_i$的极限总存在, 则称此极限为函数 $P(x,y)$在有向曲线弧 L 上对坐标$x$的曲线积分, 记作 $\int_L P(x,y)dx$. 类似地,如果$sum_{i=1}^n P(\xi_i,\eta_i)\Delta y_i$总存在,则称此极限为函数 $Q(x,y)$在有向曲线弧 L 上对坐标$y$的曲线积分,记作$\int_L Q(x,y)dy$. 即 

$$\int_L P(x,y)dx=\lim_{\lambda\to 0}\sum_{i=1}^n P(\xi_i,\eta_i)\Delta x_i$$

$$\int_L Q(x,y)dy=\lim_{\lambda\to 0}\sum_{i=1}^n Q(\xi_i,\eta_i)\Delta y_i$$

其中$P(x,y)$和$Q(x,y)$分别称为被积函数，L称为积分弧段。

以上两个积分也称为第二类曲线积分

**空间曲线**

$$\int_\Gamma P(x,y,z)dx=\lim_{\lambda\to 0}\sum_{i=1}^n P(\xi_i,\eta_i,\zeta_i\Delta x_i$$

$$\int_\Gamma Q(x,y,z)dy=\lim_{\lambda\to 0}\sum_{i=1}^n Q(\xi_i,\eta_i,\zeta_i)\Delta y_i$$

$$\int_\Gamma R(x,y,z)dx=\lim_{\lambda\to 0}\sum_{i=1}^n R(\xi_i,\eta_i,\zeta_i)\Delta x_i$$

**简化写法**

$$\int_L P(x,y)dx+\int_L Q(x,y)dy$$

$$\int_L P(x,y)dx+ Q(x,y)dy$$

$$\int_L \vec F(x,y)d\vec r$$

其中$\vec F=P(x,y)\vec i+Q(x,y)\vec j$为向量值函数，$d\vec r=dx\vec i+dy\vec j$.

类似的

$$\int_\Gamma P(x,y,z)dx+\int_\Gamma Q(x,y,z)dy+\int_\Gamma R(x,y,z)dz$$

$$\int_\Gamma P(x,y,z)dx+ Q(x,y,z)dy+ R(x,y,z)dz$$

$$\int_\Gamma \vec A(x,y,z)d\vec r$$

其中$\vec A=P(x,y,z)\vec i+Q(x,y,z)\vec j+R(x,y,z)\vec k$为向量值函数，$d\vec r=dx\vec i+dy\vec j+dz\vec k$.

**性质**

性质1 设$\alpha,\beta$为常数，则

$$\int_L [\alpha \vec F_1(x,y)+\beta \vec F_2(x,y)]d\vec r=\alpha\int_L\vec F_1(x,y)d\vec r+\beta\int_L\vec F_2(x,y)d\vec r$$

性质2 若积分弧段L可分成两段光滑的曲线弧$L_1,L_2$，则

$$\int_L \vec F(x,y)d\vec r=\int_{L_1}\vec F(x,y)d\vec r+\int_{L_2}\vec F(x,y)d\vec r$$

性质3 设L是有几光滑曲线弧，$L^-$是$L$的反向曲线弧，则

$$\int_{L^-} \vec F(x,y)d\vec r=-\int_L\vec F(x,y)d\vec r$$

**计算**

定理 设$P(x,y)、Q(x,y)$在有向曲线弧L上有定义且连续, L 的参数方程为
$$
 \begin{cases}
 x=\varphi(t) \\
 y=\psi(t)
 \end{cases}
$$

当参数t单调的由$\alpha$变到$\beta$时，点$M(x,y)$从L的起点A沿L运动到终点B,  $\varphi(t),\psi(t)$ 在$[\alpha,\beta]$上具有一阶连续导数，且$\varphi^{'2}(t)+\psi^{'2}(t)\ne 0$，则曲线积分$\int_LP(x,y)ds+Q(x,y)dy$存在,且

$$\int_L P(x,y)dx+ Q(x,y)dy=\int_{\alpha}^{\beta} |P[\varphi(t),\psi(t)]\varphi'(t)+Q[\varphi(t),\psi(t)]\psi'(t)|dt$$

## 格林公式

定理1 设闭区域 D 由分段光滑的曲线L围成函数 $P(x,y)$及$Q(x,y)$在 D 上具有一阶连续偏导数,则有

$$\iint_D (\frac{\alpha Q}{\alpha x}-\frac {\alpha P}{\alpha y})dydy=\oint_L Pdx+Qdy$$

其中L是D 的取正向的边界曲线.

定理2 设区域 G 是一个单连通域,函数 $P(x,y),Q(x,y)$在 G 内具有阶连续偏导数,则曲线积分$\int_L Pdx+Qdy$在G 内与路径无关(或沿 G 内任意闭曲线的曲线积分为零)的充分必要条件是

$$\frac{\alpha Q}{\alpha x}=\frac {\alpha P}{\alpha y}$$

在G内恒成立

定理3 设区域 G 是一个单连通域,函数 $P(x,y)、Q(x,y)$在 G 内具有阶连续偏导数,则 $P(x,y)dx + Q(z,y)dy$在G 内为某一函数 $u(x,y)$的全微分的充分必要条件是

$$\frac{\alpha Q}{\alpha x}=\frac {\alpha P}{\alpha y}$$

在G内恒成立

定理4(曲线积分的基本定理) 设 $\vec F(x,y)= P(x,y)\vec i+ Q(x,y)\vec j$ 是平面区域G 内的一个向量场,$P(x,y)Q(x,y)$都在 G 内连续,且存在一个数量函数$f(x,y)$使得 $F=\nabla f$,则曲线积分$\int_L \vec F\cdot d\vec r$在G 内与路径无关,且

$$\int_L \vec F\cdot d\vec r=f(B)-f(A)$$

其中 L 是位于 G 内起点为 A、终点为 B 的任一分段光滑曲线

## 对面积的曲面积分

定义 设曲面$\varSigma$是光滑的,函数 $f(x,y,z)$在$\varSigma$上有界.把$\varSigma$分成n小块$\Delta S_i$($\Delta S_i$同时也代表第i小块曲面的面积), 设$(\xi_i,\eta_i,\zeta_i)$为$\Delta S_i$上任意取定的一点, 作乘积 $f(\xi_i,\eta_i,\zeta_i)\Delta S_i(i=1,2,\cdots,n)$, 并作和$\sum_{i=1}^n f(\xi_i,\eta_i,\zeta_i)\Delta S_i$,如果当各小块曲面直径的最大值$\lambda \to0$, 这和的极限总存在,则称此极限为函数 $f(x,y,z)$在曲面$\varSigma$上对面积的曲面积分或第一类曲面积分,记作$\iint_\varSigma f(x,y)dS$,即

$$\int_\varSigma f(x,y,x)dS=\lim_{\lambda\to 0}\sum_{i=1}^n f(\xi_i,\eta_i,\zeta_i)\Delta S_i$$

其中$f(x,y,z)$叫做被积函数, $\varSigma$叫做积分曲面。
















