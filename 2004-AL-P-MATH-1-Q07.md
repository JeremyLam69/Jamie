## 7(a)(i)
(E) has a unique solution.
$\Rightarrow \Delta \neq 0$

$\displaystyle \Rightarrow \begin{vmatrix}
1 & a-2 & a \\
1 & 2 & 4 \\
a & -1 & 3 
\end{vmatrix} \neq 0$

$\displaystyle \Rightarrow 2a^2-12a+16 \neq 0$
$\displaystyle \Rightarrow 2(a - 2)(a-4) \neq 0$
$\displaystyle \Rightarrow a \neq 2$ and $a \neq 4$

On the other hand, when $\displaystyle a \neq 2$ and $a \neq 4$
$\Rightarrow \Delta \neq 0$
$\Rightarrow$ (S) has an unique solution.

Hence, (E) has a unique solution if and only if $\displaystyle a \neq 2$ and $a \neq 4$.

Moreover, 
$\Delta_x = \begin{vmatrix}
1 & a-2 & a \\
1 & 2 & 4 \\
b & -1 & 3 
\end{vmatrix}$ and $\Delta_y = \begin{vmatrix}
1 & 1 & a \\
1 & 1 & 4 \\
a & b & 3 
\end{vmatrix}$ and $\Delta_z = \begin{vmatrix}
1 & a-2 & 1 \\
1 & 2 & 1 \\
a & -1 & b 
\end{vmatrix}$

$\Rightarrow \Delta_x = 2(b-2)(a-4)$ and $\Delta_y = (b-a)(a-4)$ and $\Delta_z = (a-b)(a-4)$

----
When $a \neq 2$ and $a \neq 4$ (i.e. $\Delta \neq 0$)
$\displaystyle \Rightarrow x = {\Delta_x \over \Delta}$ and $\displaystyle y = {\Delta_y \over \Delta}$ and $\displaystyle z = {\Delta_z \over \Delta}$

$\displaystyle \Rightarrow x = {{2(b-2)(a-4)} \over {2(a - 2)(a-4)}}$ and $\displaystyle y = {{(b-a)(a-4)} \over {2(a - 2)(a-4)}}$ and $\displaystyle z = {{(a-b)(a-4)} \over {2(a - 2)(a-4)}}$

$\displaystyle \Rightarrow x = {{b-2} \over {a - 2}}$ and $\displaystyle y = {{b-a} \over {2(a - 2)}}$ and $\displaystyle z = {{a-b} \over {2(a - 2)}}$

## 7(a)(ii)(1)
When a = 2 (i.e. $\Delta = 0$),

$\Delta_x = 2(b-2)(a-4)$ and $\Delta_y = (b-a)(a-4)$ and $\Delta_z = (a-b)(a-4)$
$\Rightarrow \Delta_x = -4(b-2)$ and $\Delta_y = -2(b-2)$ and $\Delta_z = 2(b-2)$

When (E) is consistent, $\Delta_x = \Delta_y = \Delta_z = 0$
$\Rightarrow -4(b-2) = -2(b-2) = 2(b-2) = 0$
$\Rightarrow b = 2$

In this case, (E) $\begin{cases}
x + 2z = 1 \\
x + 2y + 4z = 1 \\
2x - y + 3z = 2
\end{cases}$

Consider the augmented matrix :
$\left[ \begin{array}{ccc|c} 
1 & 0 & 2 & 1 \\
1 & 2 & 4 & 1 \\
2 & -1 & 3 & 2
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & 2 & 1 \\
0 & 2 & 2 & 0 \\
0 & -1 & -1 & 0
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & 2 & 1 \\
0 & 1 & 1 & 0
\end{array} \right]$

$\Rightarrow$ The solutions are $x = 1 - 2t$, $y = -t$, $z = t$ where $t \in R$

## 7(a)(ii)(2)
When a = 4,

(E) $\begin{cases}
x + 2y + 4z = 1 \\
x + 2y + 4z = 1 \\
4x - y + 3z = b
\end{cases}$

$\Rightarrow$ (E) $\begin{cases}
x + 2y + 4z = 1 \\
4x - y + 3z = b
\end{cases}$

Consider the augmented matrix :
$\left[ \begin{array}{ccc|c} 
1 & 2 & 4 & 1 \\
4 & -1 & 3 & b
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 2 & 4 & 1 \\
0 & -9 & -13 & b-4
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 2 & 4 & 1 \\
0 & 1 & \displaystyle {13 \over 9} & \displaystyle {{4-b} \over 9}
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & \displaystyle {10 \over 9} & \displaystyle {{1+2b} \over 9} \\
0 & 1 & \displaystyle {13 \over 9} & \displaystyle {{4-b} \over 9}
\end{array} \right]$

$\Rightarrow$ The solutions are $\displaystyle x = {{2b-10t+1} \over 9}$, $\displaystyle y = {{4-b-13t} \over 9}$, $z = t$ where $b,\ t \in R$

## 7(b)
Using result in (a)(ii)(1), $x = 1 - 2t$, $y = -t$, $z = t$ where $t \in R$
Since x, y, z satisfy $k(x^2-3) > yz$

$\Rightarrow k[\ (1 - 2t)^2-3\ ] > -t^2$
$\displaystyle \Rightarrow (4k+1)t^2-4kt-2k > 0$
$\displaystyle \Rightarrow 4k+1>0$ and $\displaystyle (-4k)^2-4(4k+1)(-2k)<0$
$\displaystyle \Rightarrow k>-{1 \over 4}$ and $\displaystyle 48k^2+8k<0$
$\displaystyle \Rightarrow k>-{1 \over 4}$ and $\displaystyle k(6k+1)<0$
$\displaystyle \Rightarrow k>-{1 \over 4}$ and { ($k<0$ and $6k+1>0$) or ($k>0$ and $6k+1<0$) }
$\displaystyle \Rightarrow k>-{1 \over 4}$ and { ($k<0$ and $\displaystyle k>-{1 \over 6}$) or ($k>0$ and $\displaystyle k<-{1 \over 6}$) <span style="color:red">rejected</span> }
$\displaystyle \Rightarrow k>-{1 \over 4}$ and $k<0$ and $\displaystyle k>-{1 \over 6}$
$\displaystyle \Rightarrow k>-{1 \over 6}$ and $k<0$