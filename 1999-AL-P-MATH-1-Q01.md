## 1(a)
(\*) has non-trivial solutions.
$\Rightarrow \Delta = 0$

$\Rightarrow \begin{vmatrix}
1 & 1 & -\lambda \\
1 & \lambda & -1 \\
\lambda & 1 & -1
\end{vmatrix}= 0$

$\Rightarrow -\lambda+1 +1 -\lambda + \lambda (\lambda^2-1) = 0$

$\Rightarrow -2\lambda + 2 + \lambda^3 - \lambda = 0$

$\Rightarrow \lambda^3 -3\lambda + 2 = 0$

$\Rightarrow (\lambda - 1)(\lambda^2 + \lambda - 2) = 0$

$\Rightarrow (\lambda - 1)^2(\lambda + 2) = 0$

$\Rightarrow \lambda = -2$ or $\lambda = 1$

## 1(b)
When $\lambda = -2$,
(\*) $\begin{cases}
x + y +2z = 0 \\
x -2y - z = 0
\end{cases}$

Consider the augmented matrix.

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 2 & 0 \\
1 & -2 & -1 & 0
\end{array} \right]$

$\displaystyle \Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 2 & 0 \\
0 & -3 & -3 & 0
\end{array} \right]$

$\displaystyle \Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 2 & 0 \\
0 & 1 & 1 & 0
\end{array} \right]$

$\displaystyle \Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & 1 & 0 \\
0 & 1 & 1 & 0
\end{array} \right]$

$\displaystyle \Rightarrow$ Solutions are $x = -t$, $y = -t$, $z = t \in R$

-----
When $\lambda = 1$,
(\*) x + y - z = 0

Solutions are $x = t-s$, $y = s \in R$, $z = t \in R$