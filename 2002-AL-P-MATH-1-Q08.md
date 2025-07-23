## 8(a)(i)
(S) has a unique solution.
$\Rightarrow \Delta \neq 0$

$\displaystyle \Rightarrow \begin{vmatrix}
a & -2 & 1 \\
1 & -1 & 2 \\
0 & 1 & a 
\end{vmatrix} \neq 0$

$\displaystyle \Rightarrow 1 - a^2 \neq 0$
$\displaystyle \Rightarrow a^2 \neq 1$

On the other hand, $\displaystyle a^2 \neq 1$
$\Rightarrow \Delta \neq 0$
$\Rightarrow$ (S) has an unique solution.

Hence, (S) has a unique solution if and only if $\displaystyle a^2 \neq 1$.

Moreover, 
$\Delta_x = \begin{vmatrix}
0 & -2 & 1 \\
b & -1 & 2 \\
b & 1 & a 
\end{vmatrix}$ and $\Delta_y = \begin{vmatrix}
a & 0 & 1 \\
1 & b & 2 \\
0 & b & a 
\end{vmatrix}$ and $\Delta_z = \begin{vmatrix}
a & -2 & 0 \\
1 & -1 & b \\
0 & 1 & b 
\end{vmatrix}$

$\Rightarrow \Delta_x = 2b(a-1)$ and $\Delta_y = b(a-1)^2$ and $\Delta_z = -2b(a-1)$

----
When $a^2 \neq 1$ (i.e. $\Delta \neq 0$)
$\displaystyle \Rightarrow x = {\Delta_x \over \Delta}$ and $\displaystyle y = {\Delta_y \over \Delta}$ and $\displaystyle z = {\Delta_z \over \Delta}$

$\displaystyle \Rightarrow x = {{2b(a-1)} \over {1 - a^2}}$ and $\displaystyle y = {{b(a-1)^2} \over {1 - a^2}}$ and $\displaystyle z = {{-2b(a-1)} \over {1 - a^2}}$

$\displaystyle \Rightarrow x = {{-2b} \over {1 + a}}$ and $\displaystyle y = {{b(1-a)} \over {1 + a}}$ and $\displaystyle z = {{2b} \over {1 + a}}$

## 8(a)(ii)(1)
When a = 1,

(S) $\begin{cases}
x - 2y + z = 0 \\
x - y + 2z = b \\
y + z = b
\end{cases}$

$\Rightarrow \begin{cases}
x - 2y + z = 0 \\
y + z = b
\end{cases}$

Consider the augmented matrix :
$\left[ \begin{array}{ccc|c} 
1 & -2 & 1 & 0 \\
0 & 1 & 1 & b
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & 3 & 2b \\
0 & 1 & 1 & b
\end{array} \right]$

$\Rightarrow$ The solutions are $x = 2b - 3t$, $y = b - t$, $z = t$ where $b, t \in R$

## 8(a)(ii)(2)
When a = -1,
$\displaystyle \Delta = 0$, $\Delta_x = -4b$ and $\Delta_y = 4b$ and $\Delta_z = 4b$

For (S) to be consistent,
$\displaystyle \Delta_x = \Delta_y = \Delta_x = 0$
$\Rightarrow b = 0$

(S) $\begin{cases}
-x - 2y + z = 0 \\
x - y + 2z = 0 \\
y - z = 0
\end{cases}$

$\Rightarrow$ (S) $\begin{cases}
x - y + 2z = 0 \\
y - z = 0
\end{cases}$

Consider the augmented matrix :
$\left[ \begin{array}{ccc|c} 
1 & -1 & 2 & 0 \\
0 & 1 & -1 & 0
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & 1 & 0 \\
0 & 1 & -1 & 0
\end{array} \right]$

$\Rightarrow$ The solutions are $x = -t$, $y = t$, $z = t \in R$

## 8(b)
(T) is a combination of (S) where b = -1 and equation $5x - 2y + z = a$

When $a^2 \neq 1$,
According to 8(a)(i), the solution of in 8(a)(i) must fulfill the equation for (T) being consistent.
Put the solution in 8(a)(i) $\displaystyle x = {{2} \over {1 + a}}$ and $\displaystyle y = {{a-1} \over {1 + a}}$ and $\displaystyle z = {{-2} \over {1 + a}}$ into the equation.

$5x - 2y + z = a$
$\displaystyle \Rightarrow {{10} \over {1 + a}} - {{2a-2} \over {1 + a}} + {{-2} \over {1 + a}} = a$

$\displaystyle \Rightarrow {{10-2a} \over {1 + a}} = a$
$\displaystyle \Rightarrow 10-2a = a + a^2$
$\displaystyle \Rightarrow a^2 +3a - 10 = 0$
$\displaystyle \Rightarrow (a+5)(a-2) = 0$
$\displaystyle \Rightarrow a = -5$ or $a = 2$

When $a = -5$, (T) is consistent where
$\displaystyle x = -{1 \over 2}$ and $\displaystyle y = {3 \over 2}$ and $\displaystyle z = {1 \over 2}$

When $a = 2$, (T) is consistent where
$\displaystyle x = {2 \over 3}$ and $\displaystyle y = {1 \over 3}$ and $\displaystyle z = -{2 \over 3}$

-----
When a = -1,
According to 8(a)(ii)(2), (S) is NOT consistent when $b \neq 0$ and now $b = -1 \neq 0$.
Therefore, when a = -1, (T) is NOT consistent.

-----
When a = 1,
According to 8(a)(i), the solution of in 8(a)(i) must fulfill the equation for (T) being consistent.
Put the solution in 8(a)(i) $x = -2 - 3t$, $y = -1 - t$, $z = t$ into the equation.

$5x - 2y + z = a$
$\Rightarrow -10-15t+2+2t+t = 1$
$\Rightarrow -12t = 9$
$\displaystyle \Rightarrow t = -{3 \over 4}$

Therefore, when a = 1, (T) is consistent where
$\displaystyle x = {1 \over 4}$, $\displaystyle y = -{1 \over 4}$, $\displaystyle z = -{3 \over 4}$

