## 8(a)
Let $s = \alpha - \beta$

$\displaystyle X = {1 \over {\alpha - \beta}}(A-\beta I)$

$\displaystyle= {1 \over s}( \begin{pmatrix}
\alpha - k & \alpha - \beta - k \\
k & \beta + k
\end{pmatrix} - \begin{pmatrix}
 \beta & 0 \\
0 & \beta
\end{pmatrix}
)$

$\displaystyle = {1 \over s} \begin{pmatrix}
\alpha - \beta - k & \alpha - \beta - k \\
k & k
\end{pmatrix}$

$\displaystyle= {1 \over s} \begin{pmatrix}
s - k & s - k \\
k & k
\end{pmatrix}$

-----
$\displaystyle Y = {1 \over {\beta - \alpha}}(A-\alpha I)$

$\displaystyle=  -{1 \over s}( \begin{pmatrix}
\alpha - k & \alpha - \beta - k \\
k & \beta + k
\end{pmatrix} - \begin{pmatrix}
 \alpha & 0 \\
0 & \alpha
\end{pmatrix})$

$\displaystyle =  -{1 \over s} \begin{pmatrix}
{- k} & \alpha - \beta - k \\
k & - \alpha + \beta + k
\end{pmatrix}$

$\displaystyle=  -{1 \over s} \begin{pmatrix}
{- k} & s - k \\
k & - s + k
\end{pmatrix}$

-----
Therefore,

$\displaystyle XY = {1 \over s} \begin{pmatrix}
s - k & s - k \\
k & k
\end{pmatrix} (-1) {1 \over s} \begin{pmatrix}
{- k} & s - k \\
k & - s + k
\end{pmatrix}$

$\displaystyle = -{1 \over s^2}  \begin{pmatrix}
s - k & s - k \\
k & k
\end{pmatrix} \begin{pmatrix}
{- k} & s - k \\
k & - s + k
\end{pmatrix}$

$\displaystyle = -{1 \over s^2}  \begin{pmatrix}
(-k)(s - k)+k(s - k) & (s - k)^2-(s - k)^2 \\
-k^2+k^2 & k(s-k)-k(s-k)
\end{pmatrix}$

$=0$

-----
$\displaystyle YX = -{1 \over s} \begin{pmatrix}
{- k} & s - k \\
k & - s + k
\end{pmatrix} {1 \over s} \begin{pmatrix}
s - k & s - k \\
k & k
\end{pmatrix}$

$\displaystyle= -{1 \over s^2} \begin{pmatrix}
{- k} & s - k \\
k & - s + k
\end{pmatrix} \begin{pmatrix}
s - k & s - k \\
k & k
\end{pmatrix}$

$\displaystyle = -{1 \over s^2} \begin{pmatrix}
(- k)(s-k)+k(s-k) & (- k)(s-k)+k(s-k) \\
k(s-k)-k(s-k) & k(s-k)-k(s-k)
\end{pmatrix}$

$=0$

-----
$\displaystyle X + Y =  {1 \over s} \begin{pmatrix}
s - k & s - k \\
k & k
\end{pmatrix} - {1 \over s} \begin{pmatrix}
{- k} & s - k \\
k & - s + k
\end{pmatrix}$

$\displaystyle =  {1 \over s} \begin{pmatrix}
s & 0 \\
0 & s
\end{pmatrix}$

$\displaystyle = I$

-----

$\displaystyle X^2 = {1 \over s^2}  \begin{pmatrix}
s - k & s - k \\
k & k
\end{pmatrix} \begin{pmatrix}
s - k & s - k \\
k & k
\end{pmatrix}$

$\displaystyle = {1 \over s^2}  \begin{pmatrix}
s(s - k) & s(s - k) \\
sk & sk
\end{pmatrix}$

$\displaystyle = {1 \over s}  \begin{pmatrix}
s - k & s - k \\
k & k
\end{pmatrix}$

$\displaystyle = X$

-----
$\displaystyle Y^2 = {1 \over s^2} \begin{pmatrix}
{- k} & s - k \\
k & - s + k
\end{pmatrix} \begin{pmatrix}
{- k} & s - k \\
k & - s + k
\end{pmatrix}$

$\displaystyle = {1 \over s^2} \begin{pmatrix}
sk & -s(s - k) \\
-sk & s(s - k)
\end{pmatrix}$

$\displaystyle = {1 \over s} \begin{pmatrix}
k & -(s - k) \\
-k & (s - k)
\end{pmatrix}$

$\displaystyle = -{1 \over s} \begin{pmatrix}
-k & s - k \\
k & -s + k)
\end{pmatrix}$

$\displaystyle = Y$

## 8(b)
Let P(n) be the statement that $A^n = \alpha^nX + \beta^nY$ for all positive integers n.

When n = 1,
$\alpha^nX + \beta^nY$
$\displaystyle = {\alpha \over {\alpha - \beta}}(A - \beta I) + {\beta \over {\beta - \alpha}}(A - \alpha I)$
$\displaystyle = {\alpha \over {\alpha - \beta}}(A - \beta I) - {\beta \over {\alpha - \beta}}(A - \alpha I)$
$\displaystyle = {1 \over {\alpha - \beta}}(\alpha A - \alpha \beta I - \beta A + \alpha \beta I)$
$\displaystyle = {1 \over {\alpha - \beta}}((\alpha - \beta) A)$
$\displaystyle = A$
Therefore, P(1) is true.

Assume that P(k) is true for some positive integer k $\geq 1$. Then,
$\displaystyle A^{k+1} = A^kA = (\alpha^kX + \beta^kY)(\alpha X + \beta Y)$
$\displaystyle = \alpha^{k+1}X^2 + \alpha^k \beta XY + \alpha \beta^kYX + \beta^{k+1}Y^2$
$\displaystyle = \alpha^{k+1}X + \alpha^k \beta 0 + \alpha \beta^k0 + \beta^{k+1}Y$
$\displaystyle = \alpha^{k+1}X + \beta^{k+1}Y$
Therefore, P(k+1) is true. By mathematical induction P(n) is true.

## 8(c)
Let $\alpha = 7$ , $\beta = 1$ , $k = 2$

$\displaystyle \begin{pmatrix}
5 & 4 \\
2 & 3
\end{pmatrix}^{2004} = A^{2004} =  \alpha^{2004}X + \beta^{2004}Y$

$\displaystyle = 7^{2004} ({1 \over 3}) \begin{pmatrix}
2 & 2 \\
1 & 1
\end{pmatrix} + ({1 \over 3}) \begin{pmatrix}  
1 & -2 \\ 
-1 & 2  
\end{pmatrix}$

$\displaystyle = {1 \over 3} \begin{pmatrix}
2 \cdot 7^{2004} +1 & 2  \cdot 7^{2004} - 2 \\
7^{2004} - 1 & 7^{2004} + 2
\end{pmatrix}$

## 8(d)
Let $B = \alpha^{-1}X + \beta^{-1}Y$. Then

-----
$\displaystyle AB = (\alpha X + \beta Y) (\alpha^{-1}X + \beta^{-1}Y)$
$\displaystyle = X^2 + {\alpha \over \beta}XY + {\beta \over \alpha}YX + Y^2$
$\displaystyle = X + {\alpha \over \beta}0 + {\beta \over \alpha}0 + Y$
$\displaystyle = X + Y$
$\displaystyle = I$
-----
Also $\displaystyle BA = (\alpha^{-1}X + \beta^{-1}Y) (\alpha X + \beta Y)$
$\displaystyle = X^2 + {\beta \over \alpha}XY + {\alpha \over \beta}YX + Y^2$
$\displaystyle = X + {\beta \over \alpha}0 + {\alpha \over \beta}0 + Y$
$\displaystyle = X + Y$
$\displaystyle = I$
-----
Hence $A^{-1} = B  = \alpha^{-1}X + \beta^{-1}Y$
