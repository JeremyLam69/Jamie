## 7(a)(i)
(E) has a unique solution.
$\Rightarrow \Delta \neq 0$

$\displaystyle \Rightarrow \begin{vmatrix}
1 & a & -1 \\
2 & -1 & a \\
-1 & 2a^2 & a-3 
\end{vmatrix} \neq 0$

$\displaystyle \Rightarrow -2a^3-7a^2+5a+4 \neq 0$
$\displaystyle \Rightarrow -(a+4)(2a+1)(a-1) \neq 0$
$\displaystyle \Rightarrow a \neq -4$ and $\displaystyle a \neq -{1 \over 2}$ and $a \neq 1$

Also, 
$\Delta_x = \begin{vmatrix}
0 & a & -1 \\
-2a & -1 & a \\
2a & 2a^2 & a-3 
\end{vmatrix}=2a(4a+1)(a-1)$ and 

$\Delta_y = \begin{vmatrix}
1 & 0 & -1 \\
2 & -2a & a \\
-1 & 2a & a-3 
\end{vmatrix}=-4a(a-1)$ and 

$\Delta_z = \begin{vmatrix}
1 & a & 0 \\
2 & -1 & -2a \\
-1 & 2a^2 & 2a 
\end{vmatrix}=2a(2a+1)(a-1)$

----
When $\Delta \neq 0$
$\displaystyle \Rightarrow x = {\Delta_x \over \Delta}$ and $\displaystyle y = {\Delta_y \over \Delta}$ and $\displaystyle z = {\Delta_z \over \Delta}$

$\displaystyle \Rightarrow x = {{2a(4a+1)(a-1)} \over {-(a+4)(2a+1)(a-1)}}$ , $\displaystyle y = {{-4a(a-1)} \over {-(a+4)(2a+1)(a-1)}}$ , $\displaystyle z = {{2a(2a+1)(a-1)} \over {-(a+4)(2a+1)(a-1)}}$

$\displaystyle \Rightarrow x = {{-2a(4a+1)} \over {(a+4)(2a+1)}}$ , $\displaystyle y = {{4a} \over {(a+4)(2a+1)}}$ , $\displaystyle z = {{-2a} \over {(a+4)}}$

## 8(a)(ii)(1)
When a = 1,

(E) $\begin{cases}
x + y - z = 0 \\
2x - y + z = -2 \\
-x + 2y - 2z = 2
\end{cases}$

$\Rightarrow \begin{cases}
x + y - z = 0 \\
2x - y + z = -2
\end{cases}$

Consider the augmented matrix :
$\left[ \begin{array}{ccc|c} 
1 & 1 & -1 & 0 \\
2 & -1 & 1 & -2
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & -1 & 0 \\
0 & -3 & 3 & -2
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & -1 & 0 \\
0 & 1 & -1 & {2 \over 3}
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & 0 & -{2 \over 3} \\
0 & 1 & -1 & {2 \over 3}
\end{array} \right]$

$\Rightarrow$ The solutions are $\displaystyle x = -{2 \over 3}$, $\displaystyle y = t+{2 \over 3}$, $\displaystyle z = t$ where $t \in R$

## 8(a)(ii)(2)
When a = -4 (i.e. $\Delta = 0$),

$\Delta_x = 2a(4a+1)(a-1) = -600 \neq 0$ and 

$\Delta_y = -4a(a-1) = -80 \neq 0$ and 

$\Delta_z = 2a(2a+1)(a-1)= -280 \neq 0$

$\Rightarrow$ (E) has NO solution.

## 8(b)
Using result in (a)(ii)(1), 
$\displaystyle x = -{2 \over 3}$, $\displaystyle y = t+{2 \over 3}$, $\displaystyle z = t$ where $t \in R$

$24x^2+3y^2+2z$ 
=$\displaystyle 24(-{2 \over 3})^2+3(t+{2 \over 3})^2+2t$ for some $t \in R$
=$\displaystyle 3t^2+6t+12$ for some $t \in R$
=$\displaystyle 3(t+1)^2+9$ for some $t \in R$
$\leq 9$

Therefore, the least value of $24x^2+3y^2+2z$  is 9 when $t=-1$, i.e. $\displaystyle x = -{2 \over 3}$, $\displaystyle y = -{1 \over 3}$, $\displaystyle z = -1$