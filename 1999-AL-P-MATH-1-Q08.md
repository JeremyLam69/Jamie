## 8(a)
(E) has a unique solution
$\Rightarrow \Delta \neq 0$

$\displaystyle \Rightarrow \begin{vmatrix}
1 & \lambda & 1 \\
3 & -1 & \lambda+2 \\
1 & -1 & 1
\end{vmatrix} \neq 0$
$\displaystyle \Rightarrow \lambda (\lambda+2)+1+(\lambda+2)-3-1-3\lambda \neq 0$
$\displaystyle \Rightarrow \lambda ^2 - 1 \neq 0$
$\displaystyle \Rightarrow (\lambda + 1)(\lambda - 1) \neq 0$
$\displaystyle \Rightarrow \lambda \neq -1$ and $\lambda \neq 1$

On the other hand,
$\displaystyle \lambda \neq -1$ and $\lambda \neq 1$
$\Rightarrow \Delta \neq 0$
$\Rightarrow$ (E) has a unique solution.

Hence, (E) has a unique solution if and only if $\lambda \neq \pm1$

## 8(b)(i)
$\Delta_x = \begin{vmatrix}
\lambda & \lambda & 1 \\
7 & -1 & \lambda+2 \\
3 & -1 & 1
\end{vmatrix}$ and $\Delta_y = \begin{vmatrix}
1 & \lambda & 1 \\
3 & 7 & \lambda+2 \\
1 & 3 & 1
\end{vmatrix}$ and $\Delta_z = \begin{vmatrix}
1 & \lambda & \lambda \\
3 & -1 & 7 \\
1 & -1 & 3
\end{vmatrix}$

$\displaystyle \Rightarrow \Delta_x = 4(\lambda+1)(\lambda-1)$ and $\Delta_y =  (\lambda-1)(\lambda-3)$ and $\Delta_z = 4(1-\lambda)$

$\displaystyle \Rightarrow x = {\Delta_x \over \Delta}$ and $\displaystyle y = {\Delta_y \over \Delta}$ and $\displaystyle z = {\Delta_z \over \Delta}$

$\displaystyle \Rightarrow x = {{4(\lambda+1)(\lambda-1)} \over {(\lambda + 1)(\lambda - 1)}}$ and $\displaystyle y = {{(\lambda-1)(\lambda-3)} \over {(\lambda + 1)(\lambda - 1)}}$ and $\displaystyle z = {{4(1-\lambda)} \over {(\lambda + 1)(\lambda - 1)}}$

$\displaystyle \Rightarrow x = 4$ and $\displaystyle y = {{\lambda-3} \over {\lambda + 1}}$ and $\displaystyle z = {{-4} \over {\lambda + 1}}$

## 8(b)(ii)
When $\lambda = -1$
$\displaystyle \Delta = (\lambda + 1)(\lambda - 1)$ and  $\Delta_x = 4(\lambda+1)(\lambda-1)$ and $\Delta_y =  (\lambda-1)(\lambda-3)$ and $\Delta_z = 4(1-\lambda)$
$\displaystyle \Rightarrow \Delta = \Delta_x = 0$ and $\Delta_y = \Delta_z = 8 \neq 0$
$\displaystyle \Rightarrow$ (E) has NO solution.

## 8(b)(iii)
When $\lambda = 1$, consider the augmented matrix
$\left[ \begin{array}{ccc|c} 
1 & 1 & 1 & 1 \\
3 & -1 & 3 & 7 \\
1 & -1 & 1 & 3
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 1 & 1 \\
0 & -4 & 0 & 4 \\
0 & -2 & 0 & 2
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 1 & 1 \\
0 & -2 & 0 & 2
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 1 & 1 \\
0 & 1 & 0 & -1
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & 1 & 2 \\
0 & 1 & 0 & -1
\end{array} \right]$

$\Rightarrow$ The solutions are $x = 2-t$, $y = -1$ , $z = t \in R$

## 8(c)(iii)
The solution must fulfill (E) for $\lambda=1$ and $ax + by +cz =d$

$\Rightarrow a(2-t)+b(-1)+ct=d$ for some $t \in R$
$\Rightarrow a(2-t)-b+ct=d$ for some $t \in R$
$\Rightarrow (c-a)t+2a-b-d=0$ for some $t \in R$

Therefore, there are 2 possible ways for the system to be consistent
1. a=c and 2a-b-d=0
or
2. $a \neq c$ and a, b, c, d can be any number so that $\displaystyle t = {{2a-b-d} \over {a-c}}$