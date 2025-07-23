## 9(a)
Consider (S), 

$\Delta = \begin{vmatrix}
2 & 2 & -1 \\
h & -3 & -1 \\
-3 & h & 1
\end{vmatrix}$

$= 2(-3)(1)+2(-1)(-3)+(-1)h^2 - 2(-1)h - 2h +(-3)(-3)$
$= -6+6-h^2+2h-2h+9$
$= 9-h^2$

**(1)** when (S) has a unique solution
$\Rightarrow \Delta \neq 0$
$\Rightarrow 9-h^2 \neq 0$
$\Rightarrow h^2 \neq 9$

**(2)** when $h^2 \neq 9$
$\Rightarrow 9-h^2 \neq 0$
$\Rightarrow \Delta \neq 0$
$\Rightarrow$ (S) has a unique solution

From (1) and (2), (S) has a unique solution if and only if $h^2 \neq 9$

Consider, 
$\Delta_x = \begin{vmatrix}
k & 2 & -1 \\
0 & -3 & -1 \\
0 & h & 1
\end{vmatrix} = k(-3+h) = k(h-3)$

$\Delta_y = \begin{vmatrix}
2 & k & -1 \\
h & 0 & -1 \\
-3 & 0 & 1
\end{vmatrix} = -k(h-3)$

$\Delta_z = \begin{vmatrix}
2 & 2 & k \\
h & -3 & 0 \\
-3 & h & 0
\end{vmatrix} = k(h^2-9)$

Then,
$\displaystyle x = {\Delta_x \over \Delta} = {k(h-3) \over {9-h^2}} = -{k \over {h+3}}$

$\displaystyle y = {\Delta_y \over \Delta} = {-k(h-3) \over {9-h^2}} = {k \over {h+3}}$

$\displaystyle z = {\Delta_z \over \Delta} = { k(h^2-9) \over {9-h^2}} = -k$


## 9(b)(i)
When h = 3, (S) becomes:
2x + 2y - z = k
3x - 3y - z = 0

$\displaystyle \Rightarrow y={{x+k} \over 5}$ and $\displaystyle z={{3(4x-k)} \over 5}$ for any $k \in R$

$\Rightarrow$k can be any real number and solutions are ($\displaystyle t,\ {{t+k} \over 5},\ {{3(4t-k)} \over 5})$ for any $t \in R$

## 9(b)(ii)
When h = -3, (S) becomes:
2x + 2y - z = k
-3x - 3y - z = 0
-3x - 3y + z = 0

$\displaystyle \Rightarrow y = -x,\ z = 0,\ k=0$
$\displaystyle \Rightarrow k=0$ and solutions are ($\displaystyle t,\ -t,\ 0)$ for any $t \in R$


## 9(c)
The top 3 equations in (T) are actually (S) where $\displaystyle k={2 \over 3}$.
To ensure (T) has solutions , (S) must have solutions first of all. 

-----
Consider result 9(b)(ii), when h = -3, k must be 0.
Therefore, $h \neq -3$

-----
Consider result 9(a), when $h \neq 3$
$\displaystyle x = -{k \over {h+3}} = -{2 \over {3(h+3)}}$

$\displaystyle y = {k \over {h+3}} = {2 \over {3(h+3)}}$

$\displaystyle z = -k = -{2 \over 3}$

Put them to the last equation in (T),
L.H.S. 
$\displaystyle = -5x - 2y + 6z$

$\displaystyle = 5 \cdot {2 \over {3(h+3)}} - 2 \cdot {2 \over {3(h+3)}} - 6 \cdot {2 \over 3}$

$\displaystyle = {{10 - 4 - 12h -36} \over {3(h+3)}}$

$\displaystyle = {{- 12h - 30} \over {3(h+3)}}$

$\displaystyle = {{- 4h - 10} \over {h+3}}$

To make L.H.S. = h, we must have:
$-4h-10 = h(h+3)$
$\Rightarrow h^2+7h+10=0$
$\Rightarrow (h+2)(h+5)=0$
$\Rightarrow h=-2$ or $h=-5$

Therefore, (T) has solution 
when $\displaystyle h=-2,\ x=-{2 \over 3},\ y={2 \over 3}, z=-{2 \over 3}$
or
when $\displaystyle h=-5,\ x={1 \over 3},\ y=-{1 \over 3}, z=-{2 \over 3}$

-----
From result 9(b)(i), when h = 3, 
$\displaystyle x = t,\ y = {{t+k} \over 5},\ z = {{3(4t-k)} \over 5}$ for any $t \in R$

$\displaystyle \Rightarrow x = t,\ y = {{3t+2} \over 15},\ z = {{12t-2} \over 5}$ for any $t \in R$

Put them to the last equation in (T),
L.H.S. 
$\displaystyle = -5x - 2y + 6z$

$\displaystyle = -5t - 2\cdot {{3t+2} \over 15} + 6\cdot {{12t-2} \over 5}$

$\displaystyle = {{-75t - 6t-4 + 216t - 36} \over 15}$

$\displaystyle = {{135t -40} \over 15} = 9t - {8 \over 3}$

if $\displaystyle t = {17 \over 27}$ then L.H.S. = 3 = h. resulting in (T) having a solution.

Hence, (T) has a solution when h = 3, $\displaystyle x= {17 \over 27},\ y={7 \over 27},\ z={10 \over 9}$

