## 8(a)
(E) has a unique solution
$\displaystyle \Rightarrow \Delta \neq 0$

$\displaystyle \Rightarrow \begin{vmatrix}
a & 1 & b \\
1 & a & b \\
1 & 1 & ab
\end{vmatrix} \neq 0$

$\displaystyle \Rightarrow a(a^2b-b)-ab+b+b-ab \neq 0$

$\displaystyle \Rightarrow a^3b-3ab+2b \neq 0$

$\displaystyle \Rightarrow b(a^3-3a+2) \neq 0$

$\displaystyle \Rightarrow b(a+2)(a^2-2a+1) \neq 0$

$\displaystyle \Rightarrow b(a+2)(a-1)^2 \neq 0$

$\displaystyle \Rightarrow b \neq 0$ and $a \neq -2$ and $a \neq 1$

On the other hand, when $\displaystyle b \neq 0$ and $a \neq -2$ and $a \neq 1$

$\displaystyle \Rightarrow \Delta \neq 0$

$\displaystyle \Rightarrow$ (E) has unique solution.

Hence (E) has a unique solution if and only if  $\displaystyle b \neq 0$ and $a \neq -2$ and $a \neq 1$

-----
When $\displaystyle b \neq 0$ and $a \neq -2$ and $a \neq 1$
$\Delta_x = \begin{vmatrix}
1 & 1 & b \\
1 & a & b \\
b & 1 & ab
\end{vmatrix}$

$= a^2b-b-ab+b+b^2-ab^2$
$= a^2b-ab+b^2-ab^2$
$= b(a^2-a+b-ab)$
$= b(a-1)(a-b)$

$\Delta_y = \begin{vmatrix}
a & 1 & b \\
1 & 1 & b \\
1 & b & ab
\end{vmatrix}$

$= a(ab-b^2)-ab+b^2$
$= a^2b-ab^2-ab+b^2$
$= a^2b-ab+b^2-ab^2$
$= ab(a-1)-b^2(a-1)$
$= b(a-1)(a-b)$

$\Delta_z = \begin{vmatrix}
a & 1 & 1 \\
1 & a & 1 \\
1 & 1 & b
\end{vmatrix}$

$= a(ab-1)-b+1+1-a$
$= a^2b-a-b+2-a$
$= a^2b-2a-b+2$
$= a^2b-b-2a+2$
$= b(a^2-1)-2(a-1)$
$= (a-1)(b(a+1)-2)$
$= (a-1)(ab+b-2)$

Then, $\displaystyle x = {\Delta_x \over \Delta}$ and  $\displaystyle y = {\Delta_y \over \Delta}$ and $\displaystyle z = {\Delta_z \over \Delta}$

$\displaystyle \Rightarrow x = {{b(a-1)(a-b)} \over {b(a+2)(a-1)^2}}$ and  $\displaystyle y = {{b(a-1)(a-b)} \over {b(a+2)(a-1)^2}}$ and $\displaystyle z = {{(a-1)(ab+b-2)} \over {b(a+2)(a-1)^2}}$

$\displaystyle \Rightarrow x = {{a-b} \over {(a+2)(a-1)}}$ and  $\displaystyle y = {{a-b} \over {(a+2)(a-1)}}$ and $\displaystyle z = {{ab+b-2} \over {b(a+2)(a-1)}}$

## 8(b)(i)
When a = -2,
$\Delta_x = \Delta_y = b(a-1)(a-b)$ and $\Delta_z = (a-1)(ab+b-2)$
$\Rightarrow \Delta_x = \Delta_y = 3b(b+2)$ and $\Delta_z = 3(b+2)$

(E) is consistent and $\Delta=0$
$\Rightarrow \Delta_x = \Delta_y = \Delta_z = 0$
$\Rightarrow 3b(b+2) = 0$ and $3(b+2) = 0$
$\Rightarrow (b=0$ or $b=-2)$ and $b=-2$
$\Rightarrow b=-2$

Then (E) $\begin{cases}
-2x + y - 2z = 1 \\
x - 2y - 2z = 1 \\
x + y + 4z = -2
\end{cases}$

 $\Rightarrow$ (E) $\begin{cases}
x - 2y - 2z = 1 \\
x + y + 4z = -2
\end{cases}$

Consider the augmented matrix :

$\left[ \begin{array}{ccc|c} 
1 & -2 & -2 & 1 \\
1 & 1 & 4 & -2
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & -2 & -2 & 1 \\
0 & 3 & 6 & -3
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & -2 & -2 & 1 \\
0 & 1 & 2 & -1
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & 2 & -1 \\
0 & 1 & 2 & -1
\end{array} \right]$

$\Rightarrow$ Solutions are $\displaystyle x = y = -2t-1$,  $z = t \in R$

## 8(b)(ii)
When a = 1,
$\Delta_x = \Delta_y = b(a-1)(a-b)$ and $\Delta_z = (a-1)(ab+b-2)$
$\Rightarrow \Delta_x = \Delta_y = \Delta_z = 0$ for any $b \in R$

Then (E) $\begin{cases}
x + y + bz = 1 \\
x + y + bz = b
\end{cases}$

(E) is consistent $\Rightarrow b = 1$

Solutions are $\displaystyle x = 1-m-n, y = m \in R$,  $z = n \in R$

## 8(c)
When b = 0,
$\Delta_x = \Delta_y = b(a-1)(a-b)$ and $\Delta_z = (a-1)(ab+b-2)$
$\Rightarrow \Delta_x = \Delta_y = 0$ and $\Delta_z = 2(1-a)$

When $a \neq 1$, (E) has NO solution because $\Delta=0$ but $\Delta_z \neq 0$.
When a=1, according to result in 8(b)(ii), (E) has NO solution because $b=0 \neq 1$.

Hence, (E) is NOT consistent for b=0.
