## 8(a)
$det  \begin{pmatrix}
-2-\alpha & \sqrt{3} \\
\sqrt{3} & -\alpha
 \end{pmatrix} = 0$

$\displaystyle \Rightarrow \alpha (\alpha+2) - 3 = 0$
$\displaystyle \Rightarrow \alpha^2 + 2\alpha - 3 = 0$
$\displaystyle \Rightarrow (\alpha + 3) (\alpha - 1) = 0$
$\displaystyle \Rightarrow \alpha = -3$ or $\alpha = 1$

## 8(b)
Now $\alpha_1= -3$ and $\alpha_2= 1$

$\begin{pmatrix}
-2-\alpha_1 & \sqrt{3} \\
\sqrt{3} & -\alpha_1
\end{pmatrix} \begin{pmatrix}
cos \theta_1\\
sin \theta_1
\end{pmatrix} =  \begin{pmatrix}
0\\
0
\end{pmatrix}$ 

$\Rightarrow \begin{pmatrix}
1 & \sqrt{3} \\
\sqrt{3} & 3
\end{pmatrix} \begin{pmatrix}
cos \theta_1\\
sin \theta_1
\end{pmatrix} =  \begin{pmatrix}
0\\
0
\end{pmatrix}$ 

$\Rightarrow cos \theta_1 + \sqrt{3} sin \theta_1 = 0$

$\displaystyle \Rightarrow tan \theta_1 = - {1 \over \sqrt{3}}$
$\displaystyle \Rightarrow \theta_1 = {5 \pi \over 6}$

Also,
$\begin{pmatrix}
-2-\alpha_2 & \sqrt{3} \\
\sqrt{3} & -\alpha_2
\end{pmatrix} \begin{pmatrix}
cos \theta_2\\
sin \theta_2
\end{pmatrix} =  \begin{pmatrix}
0\\
0
\end{pmatrix}$ 

$\Rightarrow \begin{pmatrix}
-3 & \sqrt{3} \\
\sqrt{3} & -1
\end{pmatrix} \begin{pmatrix}
cos \theta_2\\
sin \theta_2
\end{pmatrix} =  \begin{pmatrix}
0\\
0
\end{pmatrix}$ 

$\Rightarrow \sqrt{3}cos \theta_2 - sin \theta_2 = 0$
$\displaystyle \Rightarrow tan \theta_2 = \sqrt{3}$
$\displaystyle \Rightarrow \theta_2 = {\pi \over 3}$
-----
$\displaystyle P= \begin{pmatrix}
cos \theta_1 & cos \theta_2 \\
sin \theta_1 & sin \theta_2
\end{pmatrix} = \begin{pmatrix}
cos {5 \pi \over 6} & cos {\pi \over 3} \\
sin {5 \pi \over 6} & sin {\pi \over 3}
\end{pmatrix} = \begin{pmatrix}
{-\sqrt{3} \over 2} & {1 \over 2} \\
{1 \over 2} & {\sqrt{3} \over 2}
\end{pmatrix} = {1 \over 2} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix}$

$\displaystyle \Rightarrow P^2 = {1 \over 2} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix} {1 \over 2} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix}$

$\displaystyle = {1 \over 4} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix}$

$\displaystyle = {1 \over 4} \begin{pmatrix}
4 & 0 \\
0 & 4
\end{pmatrix} = I$

Since $P^2=I$
$\Rightarrow PP = I$
$\Rightarrow P^{-1} = P$

Therefore,
- For n = 2k where k is a positive integer,
	$P^n=P^{2k}=(P^2)^k=I^k=I$
- For n = 2k-1 where k is a positive integer,
	$P^n=P^{2k-1}=P^{2k}P^{-1}=IP=P$
-----
$P^{-1} \begin{pmatrix}
-2 & \sqrt{3} \\
\sqrt{3} & 0
\end{pmatrix} P$

$= P \begin{pmatrix}
-2 & \sqrt{3} \\
\sqrt{3} & 0
\end{pmatrix} P$

$= {1 \over 2} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix} \begin{pmatrix}
-2 & \sqrt{3} \\
\sqrt{3} & 0
\end{pmatrix} {1 \over 2} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix}$

$= {1 \over 4} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix} \begin{pmatrix}
-2 & \sqrt{3} \\
\sqrt{3} & 0
\end{pmatrix} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix}$

$= {1 \over 4} \begin{pmatrix}
3\sqrt{3} & -3 \\
1 & \sqrt{3}
\end{pmatrix} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix}$

$= {1 \over 4} \begin{pmatrix}
-12 & 0 \\
0 & 4
\end{pmatrix}$

$= \begin{pmatrix}
-3 & 0 \\
0 & 1
\end{pmatrix}$

## 8(c)
$\displaystyle \begin{pmatrix}
-2 & \sqrt{3} \\
\sqrt{3} & 0
\end{pmatrix}^n$

$\displaystyle = (P \begin{pmatrix}
-3 & 0 \\
0 & 1
\end{pmatrix} P^{-1})^n$

$\displaystyle = P \begin{pmatrix}
-3 & 0 \\
0 & 1
\end{pmatrix}^n P^{-1}$

$\displaystyle = P \begin{pmatrix}
(-3)^n & 0 \\
0 & 1
\end{pmatrix} P$

$\displaystyle = {1 \over 4} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix} \begin{pmatrix}
(-3)^n & 0 \\
0 & 1
\end{pmatrix} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix}$

$\displaystyle = {1 \over 4} \begin{pmatrix}
(-\sqrt{3})(-3)^n & 1 \\
(-3)^n & \sqrt{3}
\end{pmatrix} \begin{pmatrix}
-\sqrt{3} & 1 \\
1 & \sqrt{3}
\end{pmatrix}$

$\displaystyle = {1 \over 4} \begin{pmatrix}
3(-3)^n+1 & (-\sqrt{3})(-3)^n +  \sqrt{3} \\
(-\sqrt{3})(-3)^n +  \sqrt{3} & (-3)^n+3
\end{pmatrix}$
