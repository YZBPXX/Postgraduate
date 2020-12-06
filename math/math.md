#### 二次函数相关公式
一般式：$ax^{2}+bx+c=0$
- 韦达定理（通过两根式容易证明）
	- $x_1+x_2=-\frac{b}{a}$
	- $x_1x_2=\frac{c}{a}$
- 两根：$x_{1,2}=\frac{-b \pm \sqrt{b^2-4ac}}{2a}$
- 最值：$a(x+\frac{b}{2a})^2+\frac{4ac-b^2}{4a}$
#### 泰勒展开

$
\sin x=x-\frac{1}{6}x^3+o(x^3)=\sum\limits_{n=0}^\infty (-1)^{n} \frac{x^{2n+1}}{(2n+1)!} \\
\cos x=1-\frac{1}{2}x^2+o(x^2)=\sum\limits_{n=0}^\infty (-1)^{n} \frac{x^{2n}}{(2n)!}\\
\ln(1+x)=\sum\limits_{n=1}^\infty (-1)^{n-1}\frac{x^n}{n}\\
e^x=\sum\limits_{n=0}^\infty \frac{x^n}{n!} \\
\frac{1}{1-x}=\sum\limits_{n=0}^\infty x^n\\
(1+x)^{\alpha}=1+\alpha x+\frac{\alpha(\alpha-1)}{2}x^2+o(x^2)\\
\tan x= x+\frac{1}{3}x^3+o(x^3)\\
\arctan x = x-\frac{1}{3}x^3+o(x^3)\\
\arcsin x = x+\frac{1}{6}x^3+o(x^3)\\
$

---

### 常见的等价无穷小

$
\sin x \sim \tan x \sim \ln{(1+x)} \sim  e^x-1 \sim\arcsin x\sim\arctan x\sim\ln(x+\sqrt{1+x^2})\sim x\\
\log_a(1+x) \sim \frac{x}{\ln a}\\
a^x-1\sim x\ln a\\
(1-\beta x)^\alpha \sim \beta \alpha x\\
1-\cos x \sim \frac{1}{2}x^2\\
\tan x-\sin x \sim \frac{1}{2}x^3\\
\tan x-x\sim \frac{1}{3}x^3\\
x-\arctan x\sim\frac{1}{3}x^3\\
x-\sin x\sim \frac{1}{6}x^3\\
\arcsin x -x \sim \frac{1}{6}x^3\\
\text{sin/arcsin 和x在一起就是}\frac{1}{6}\\
\text{tan/arcsin 和x在一起就是}\frac{1}{3}\\
$

---- 
### 和差化积口诀
- 帅+帅=帅哥
- 帅-帅=哥帅
- 哥+哥=哥哥
- 哥-哥=负嫂嫂

$
\text{和差化积:}\\
\sin a +\sin b =2\sin(\frac{a+b}{2})\cos(\frac{a-b}{2})\\
\sin a -\sin b =2\cos(\frac{a+b}{2})\sin(\frac{a-b}{2})\\
\cos a +\cos b =2\cos(\frac{a+b}{2})\cos(\frac{a-b}{2})\\
\cos a -\cos b =-2\sin(\frac{a+b}{2})\sin(\frac{a-b}{2})\\
\tan a \pm\tan b =\frac{\sin(a\pmb)}{\cos a \times \cos b}\\
\cot a \pm\cot b =\pm\frac{\sin(a\pmb)}{\sin a \times \sin b}\\
\sin a\cos b=\frac{sin(a+b)+sin(a-b)}{2}\\
\cos a\sin b=\frac{sin(a+b)-sin(a-b)}{2}\\
\cos a\cos b=\frac{\cos(a+b)+\cos(a-b)}{2}\\
\sin a\sin b=-\frac{\cos(a+b)-\cos(a-b)}{2}\\
$

----

### 曲率
$\rho=\frac{|y''|}{(1+y'^{2})^{\frac{3}{2}}}$

### 积分
$
\int \frac{dx}{\sqrt{x^2-a^2}}=\frac{x}{|x|}arch \frac{{x}}{a}+C_1=\ln |x+\sqrt{x^2-a^2}|+C
$
### 积分中的替换
> 计算时先将参数范围确定，一般积分次序为:$z,\rho,\theta$
- 柱面坐标计算三重积分：$\iiint\limits_\Omega f(x,y,z)dx dydz = \iiint\limits_{\Omega} (F(\rho,\theta,z)) \rho d\rho d\theta dz$
	- 长$\rho d\theta$
	- 宽$\rho$
- 球面坐标计算三重积分:$\iiint\limits_{\Omega}f(x,y,z)dx dydz =F(r,\phi,\theta)r^2\sin \phi drd\phi dt\theta$
	- 长 $rd\phi$
	- 宽$r\sin\phi d\theta$
	- 高$dr$
