## 9(a)
(S) has an unique solution.
$\Rightarrow \Delta \neq 0$

$\displaystyle \Rightarrow \begin{vmatrix}
1 & \lambda & 1 \\
\lambda & -1 & 1 \\
3 & 1 & 2 
\end{vmatrix} \neq 0$

$\displaystyle \Rightarrow -3 - \lambda (2\lambda - 3) + \lambda + 3 \neq 0$
$\displaystyle \Rightarrow 2\lambda (2 - \lambda) \neq 0$
$\displaystyle \Rightarrow \lambda \neq 0$ and $\lambda \neq 2$

On the other hand, 
$\displaystyle \lambda \neq 0$ and $\lambda \neq 2$
$\Rightarrow \Delta \neq 0$
$\Rightarrow$ (S) has a unique solution.

Hence, (S) has a unique solution if and only if $\displaystyle \lambda \neq 0$ and $\lambda \neq 2$

## 9(b)(i)
$\Delta_x = \begin{vmatrix}
k & \lambda & 1 \\
1 & -1 & 1 \\
-1 & 1 & 2 
\end{vmatrix}$ and $\Delta_y = \begin{vmatrix}
1 & k & 1 \\
\lambda & 1 & 1 \\
3 & -1 & 2 
\end{vmatrix}$ and $\Delta_z = \begin{vmatrix}
1 & \lambda & k \\
\lambda & -1 & 1 \\
3 & 1 & -1 
\end{vmatrix}$

$\displaystyle \Rightarrow \Delta_x = -3(k+\lambda)$ and $\Delta_y = 3k -2k\lambda-\lambda$ and $\Delta_z =(k+\lambda)(\lambda+3)$

When $\displaystyle \lambda \neq 0$ and $\lambda \neq 2$ (i.e. $\Delta \neq 0$)
$\displaystyle \Rightarrow x = {\Delta_x \over \Delta}$ and $\displaystyle y = {\Delta_y \over \Delta}$ and $\displaystyle z = {\Delta_z \over \Delta}$

$\displaystyle \Rightarrow x = {-{3(k+\lambda)} \over {2\lambda (2 - \lambda)}}$ and $\displaystyle y = {{3k -2k\lambda-\lambda} \over {2\lambda (2 - \lambda)}}$ and $\displaystyle z = {{(k+\lambda)(\lambda+3)} \over {2\lambda (2 - \lambda)}}$

## 9(b)(ii)
When $\lambda = 0$ (i.e. $\Delta=0$), $\Delta_x = -3k$ and $\Delta_y = 3k$ and $\Delta_z =3k$

When $k \neq 0$, $\Delta_x \neq 0$ and $\Delta_y \neq 0$ and $\Delta_z \neq 0 \Rightarrow$ (S) is NOT consistent.

When k = 0,
(S) $\begin{cases}
x + z = 0 \\
-y + z = 1 \\
3x + y + 2z = -1
\end{cases}$

Consider the augmented matrix,
$\left[ \begin{array}{ccc|c} 
1 & 0 & 1 & 0 \\
0 & -1 & 1 & 1 \\
3 & 1 & 2 & -1
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & 1 & 0 \\
0 & -1 & 1 & 1 \\
0 & 1 & -1 & -1
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & 1 & 0 \\
0 & 1 & -1 & -1
\end{array} \right]$

$\Rightarrow$ The solutions are $x = -t$, $y = t-1$, $z = t \in R$.

## 9(b)(iii)
When $\lambda = 2$ (i.e. $\Delta=0$), $\Delta_x = -3(k+2)$ and $\Delta_y = -k-2$ and $\Delta_z =5(k+2)$

When $k \neq -2$, $\Delta_x \neq 0$ and $\Delta_y \neq 0$ and $\Delta_z \neq 0 \Rightarrow$ (S) is NOT consistent.

When k = -2,
(S) $\begin{cases}
x +2y + z = -2 \\
2x -y + z = 1 \\
3x + y + 2z = -1
\end{cases}$

Consider the augmented matrix,
$\left[ \begin{array}{ccc|c} 
1 & 2 & 1 & -2 \\
2 & -1 & 1 & 1 \\
3 & 1 & 2 & -1
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 2 & 1 & -2 \\
0 & -5 & -1 & 5 \\
0 & -5 & -1 & 5
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 2 & 1 & -2 \\
0 & -5 & -1 & 5
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 2 & 1 & -2 \\
0 & 1 & \displaystyle {1 \over 5} & -1
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & \displaystyle {3 \over 5} & 0 \\
0 & 1 & \displaystyle {1 \over 5} & -1
\end{array} \right]$

$\Rightarrow$ The solutions are $\displaystyle x = -{3t \over 5}$, $\displaystyle y = -1- {t \over 5}$, $z = t \in R$.

## 9(c)
According to 9(b)(ii), the solution $x = -t$, $y = t-1$, $z = t \in R$. satisfies $(x-p)^2+y^2+z^2=1$
$\displaystyle \Rightarrow (-t-p)^2+(t-1)^2+t^2=1$
$\displaystyle \Rightarrow t^2+2pt+p^2+t^2-2t+1+t^2=1$
$\displaystyle \Rightarrow 3t^2+2pt+p^2-2t=0$
$\displaystyle \Rightarrow 3t^2+2(p-1)t+p^2=0$
$\displaystyle \Rightarrow 4(p-1)^2-12p^2 \geq 0$ ($\because$ some solutions of t exist)
$\displaystyle \Rightarrow (p-1)^2-3p^2 \geq 0$ 
$\displaystyle \Rightarrow (p-1+\sqrt{3}p)(p-1-\sqrt{3}p) \geq 0$ 
$\displaystyle \Rightarrow [(\sqrt{3}+1)p-1]\ [(1-\sqrt{3})p-1] \geq 0$ 
$\displaystyle \Rightarrow [(\sqrt{3}+1)p-1]\ [-(\sqrt{3}-1)p-1] \geq 0$ 
$\displaystyle \Rightarrow [(\sqrt{3}+1)p-1]\ [(\sqrt{3}-1)p+1] \leq 0$ 

$\displaystyle \Rightarrow (\sqrt{3}+1)p-1 \geq 0$ and  $(\sqrt{3}-1)p+1 \leq 0$, or
$\displaystyle \quad (\sqrt{3}+1)p-1 \leq 0$ and  $(\sqrt{3}-1)p+1 \geq 0$

$\displaystyle \Rightarrow p \geq {1 \over {\sqrt{3}+1}}$ and  $\displaystyle p \leq {-1 \over {\sqrt{3}-1}}$, or
$\displaystyle \quad p \leq {1 \over {\sqrt{3}+1}}$ and $\displaystyle p \geq {-1 \over {\sqrt{3}-1}}$

$\displaystyle \Rightarrow p \leq {1 \over {\sqrt{3}+1}}$ and $\displaystyle p \geq {-1 \over {\sqrt{3}-1}}$

$\displaystyle \Rightarrow p \leq {{\sqrt{3}-1} \over 2}$ and $\displaystyle p \geq {{-\sqrt{3}-1} \over 2}$