## 11(a)
Note that $\displaystyle P = \begin{pmatrix}
sin \theta & cos \theta \\
-cos \theta & sin \theta
\end{pmatrix}$ and $\displaystyle P^{-1} = \begin{pmatrix}
sin \theta & -cos \theta \\
cos \theta & sin \theta
\end{pmatrix}$

$\displaystyle PAP^{-1}$
$\displaystyle = \begin{pmatrix}
sin \theta & cos \theta \\
-cos \theta & sin \theta
\end{pmatrix} \begin{pmatrix}
\alpha & \beta \\
\beta & -\alpha
\end{pmatrix} \begin{pmatrix}
sin \theta & -cos \theta \\
cos \theta & sin \theta
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
\alpha sin \theta + \beta cos \theta & \beta sin \theta - \alpha cos \theta \\
{-} \alpha cos \theta + \beta sin \theta & -\beta cos \theta - \alpha sin \theta
\end{pmatrix} \begin{pmatrix}
sin \theta & -cos \theta \\
cos \theta & sin \theta
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
\alpha sin^2 \theta + \beta sin \theta cos \theta + \beta sin \theta cos \theta - \alpha cos^2 \theta & -\alpha sin \theta cos \theta - \beta cos^2 \theta + \beta sin^2 \theta - \alpha sin \theta cos \theta\\
{-} \alpha sin \theta cos \theta + \beta sin^2 \theta -\beta cos^2 \theta - \alpha sin \theta cos \theta & \alpha cos^2 \theta - \beta sin \theta cos \theta -\beta sin \theta cos \theta - \alpha sin^2 \theta
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
\alpha (sin^2 \theta - cos^2 \theta) + \beta (sin \theta cos \theta + sin \theta cos \theta)  & -\alpha (sin \theta cos \theta + sin \theta cos \theta)- \beta (cos^2 \theta - sin^2 \theta) \\
{-} \alpha (sin \theta cos \theta + sin \theta cos \theta ) + \beta (sin^2 \theta - cos^2 \theta)  & \alpha (cos^2 \theta - sin^2 \theta)- \beta (sin \theta cos \theta + sin \theta cos \theta)
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
{-} \alpha (cos^2 \theta - sin^2 \theta) + \beta (2sin \theta cos \theta)  & -\alpha (2sin \theta cos \theta)- \beta (cos^2 \theta - sin^2 \theta) \\
{-} \alpha (2sin \theta cos \theta) - \beta (cos^2 \theta - sin^2 \theta)  & \alpha (cos^2 \theta - sin^2 \theta)- \beta (2sin \theta cos \theta)
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}{-} \alpha\ cos 2\theta + \beta\ sin 2\theta  & -\alpha\ sin 2\theta - \beta\ cos 2\theta \\
{-} \alpha\ sin 2\theta - \beta\ cos 2\theta  & \alpha\ cos 2\theta - \beta\ sin 2\theta
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}{-} \alpha\ cos 2\theta + \beta\ sin 2\theta  & - \beta\ cos 2\theta -\alpha\ sin 2\theta \\
{-} \beta\ cos 2\theta - \alpha\ sin 2\theta & \alpha\ cos 2\theta - \beta\ sin 2\theta
\end{pmatrix}$

## 11(b)(i)
Let $\alpha = 1$ , $\beta = \sqrt{3}$, then $A = B$.

$\displaystyle P B P^{-1} = \begin{pmatrix}
\lambda & 0 \\
0 & \mu
\end{pmatrix}$

$\displaystyle \Rightarrow P A P^{-1} = \begin{pmatrix}
\lambda & 0 \\
0 & \mu
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}{-} \alpha\ cos 2\theta + \beta\ sin 2\theta  & - \beta\ cos 2\theta -\alpha\ sin 2\theta \\
{-} \beta\ cos 2\theta - \alpha\ sin 2\theta & \alpha\ cos 2\theta - \beta\ sin 2\theta
\end{pmatrix} = \begin{pmatrix}
\lambda & 0 \\
0 & \mu
\end{pmatrix}$

$\displaystyle \Rightarrow - \beta\ cos 2\theta -\alpha\ sin 2\theta = 0$
$\displaystyle \Rightarrow \alpha\ sin 2\theta = - \beta\ cos 2\theta$

$\displaystyle \Rightarrow tan 2\theta = - {\beta \over \alpha} = -\sqrt{3}$

$\displaystyle \Rightarrow 2\theta = 2\pi - {\pi \over 3}\ (\because \pi<2\theta<2\pi)$

$\displaystyle \Rightarrow \theta = {5\pi \over 6}$

## 11(b)(ii)
$\lambda = - \alpha\ cos 2\theta + \beta\ sin 2\theta$ and $\mu =  \alpha\ cos 2\theta - \beta\ sin 2\theta$
$\displaystyle \Rightarrow \lambda = - cos ({5\pi \over 3}) + \sqrt{3}\ sin ({5\pi \over 3})$ and $\displaystyle \mu = cos ({5\pi \over 3}) - \sqrt{3}\ sin ({5\pi \over 3})$

$\displaystyle \Rightarrow \lambda = - {1 \over 2} + \sqrt{3}\ (-{\sqrt{3} \over 2})$ and $\displaystyle \mu = {1 \over 2} - \sqrt{3}\ (-{\sqrt{3} \over 2})$
$\displaystyle \Rightarrow \lambda = -2$ and $\displaystyle \mu = 2$

Also $\displaystyle P = \begin{pmatrix}
sin \theta & cos \theta \\
-cos \theta & sin \theta
\end{pmatrix}$ and $\displaystyle P^{-1} = \begin{pmatrix}
sin \theta & -cos \theta \\
cos \theta & sin \theta
\end{pmatrix}$

$\displaystyle \Rightarrow P = {1 \over 2} \begin{pmatrix}
1 & -\sqrt{3} \\
\sqrt{3} & 1
\end{pmatrix}$ and $\displaystyle P^{-1} = {1 \over 2} \begin{pmatrix}
1 & \sqrt{3} \\
-\sqrt{3} & 1
\end{pmatrix}$

Therefore,
$\displaystyle B = P^{-1} \begin{pmatrix}
-2 & 0 \\
0 & 2
\end{pmatrix} P$

$\displaystyle \Rightarrow B^n = P^{-1} \begin{pmatrix}
(-2)^n & 0 \\
0 & 2^n
\end{pmatrix} P$

$\displaystyle = {1 \over 2} \begin{pmatrix}
1 & \sqrt{3} \\
-\sqrt{3} & 1
\end{pmatrix} \begin{pmatrix}
(-2)^n & 0 \\
0 & 2^n
\end{pmatrix} {1 \over 2} \begin{pmatrix}
1 & -\sqrt{3} \\
\sqrt{3} & 1
\end{pmatrix}$

$\displaystyle = {1 \over 4} \begin{pmatrix}
1 & \sqrt{3} \\
-\sqrt{3} & 1
\end{pmatrix} \begin{pmatrix}
(-2)^n & 0 \\
0 & 2^n
\end{pmatrix} \begin{pmatrix}
1 & -\sqrt{3} \\
\sqrt{3} & 1
\end{pmatrix}$

$\displaystyle = {2^n \over 4} \begin{pmatrix}
1 & \sqrt{3} \\
-\sqrt{3} & 1
\end{pmatrix} \begin{pmatrix}
(-1)^n & 0 \\
0 & 1
\end{pmatrix} \begin{pmatrix}
1 & -\sqrt{3} \\
\sqrt{3} & 1
\end{pmatrix}$

$\displaystyle = 2^{n-2} \begin{pmatrix}
(-1)^n &  \sqrt{3} \\
-\sqrt{3}(-1)^n & 1
\end{pmatrix} \begin{pmatrix}
1 & -\sqrt{3} \\
\sqrt{3} & 1
\end{pmatrix}$

$\displaystyle = 2^{n-2} \begin{pmatrix}
(-1)^n+3 & -\sqrt{3}(-1)^n+\sqrt{3} \\
-\sqrt{3}(-1)^n+\sqrt{3} & 3(-1)^n+1
\end{pmatrix}$

$\displaystyle = 2^{n-2} \begin{pmatrix}
(-1)^n+3 & \sqrt{3}(-1)^{n+1}+\sqrt{3} \\
\sqrt{3}(-1)^{n+1}+\sqrt{3} & 3(-1)^n+1
\end{pmatrix}$

## 11(b)(iii)

$\displaystyle B^{555} = 2^{555-2} \begin{pmatrix}
(-1)^{555}+3 & \sqrt{3}(-1)^{555+1}+\sqrt{3} \\
\sqrt{3}(-1)^{555+1}+\sqrt{3} & 3(-1)^{555}+1
\end{pmatrix}$

$\displaystyle B^{555} = 2^{553} \begin{pmatrix}
2 & 2\sqrt{3} \\
2\sqrt{3} & -2
\end{pmatrix}$

$\displaystyle B^{555} = 2^{554} \begin{pmatrix}
1 & \sqrt{3} \\
\sqrt{3} & -1
\end{pmatrix}$

$\displaystyle \Rightarrow (B^{555})^{-1} = -2^{-556} \begin{pmatrix}
-1 & -\sqrt{3} \\
-\sqrt{3} & 1
\end{pmatrix}$

$\displaystyle \Rightarrow (B^{-1})^{555} = -2^{-556} \begin{pmatrix}
-1 & -\sqrt{3} \\
-\sqrt{3} & 1
\end{pmatrix}$

$\displaystyle \Rightarrow (B^{-1})^{555} = 2^{-556} \begin{pmatrix}
1 & \sqrt{3} \\
\sqrt{3} & -1
\end{pmatrix}$