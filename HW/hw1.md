# HW1

## Calculus

$1.$

(a) 显然 $\sigma(-x)=\dfrac{1}{1+e^x}=1-\sigma(x)$.

(b) $e^x=\dfrac{\sigma(x)}{1-\sigma(x)}$，因此 $\dfrac{\mathrm d}{\mathrm dx}\sigma(x)=\dfrac{e^x}{(1+e^x)^2}=\sigma(x)(1-\sigma(x))$.

## Minimization

$2.$

$f(c)=\dfrac{1}{n}\displaystyle\sum_{i=1}^n(x_i-c)^2$，$f'(c)=\dfrac{2}{n}\displaystyle\sum_{i=1}^n(x_i-c)=2(c-\dfrac{\sum_{i=1}^n x_i}{n})$. 因此当 $c=\displaystyle\dfrac{\sum_{i=1}^n x_i}{n}:=c_0$ 时，$f'(c)=0$，取到 local minima / maxima. 由于 $c<c_0$ 时 $f'(c)<0$，$c>c_0$ 时 $f'(c)>0$，所以 $c=c_0$ 是 minimum.

## Probability and Statistics

$3.$

Choose 2. Cannot be found with the information in the article. 原因显然.

$4.$

根据 Bayes Rule，$P(\text{cancer}|\text{positive})=\dfrac{P(\text{positive}|\text{cancer})P(\text{cancer})}{P(\text{positive}|\text{cancer})P(\text{cancer})+P(\text{positive}|\text{not cancer})P(\text{not cancer})}$

根据题意，$P(\text{positive}|\text{cancer})=80\%$，$P(\text{positive}|\text{not cancer})=9.6\%$，$P(\text{cancer})=1\%$，$P(\text{not cancer})=99\%$. 代入数据可得，$P(\text{cancer}|\text{positive})=7.76\%$.

$5.$

可以认为它服从 Gaussian Distribution. $f(x)=\dfrac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(x-\mu)^2}{2\sigma^2}}$. 于是 $f(\mu)=\dfrac{1}{\sigma\sqrt{2\pi}}$. 在图中，$f(\mu)\approx 0.065$，因此计算出 $\sigma\approx 6.1$. 选 B.

$6.$

略.