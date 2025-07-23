## 11(a)
$\displaystyle A^2 = \begin{pmatrix}
\alpha + \beta & -\alpha \beta \\
1 & 0
\end{pmatrix} \begin{pmatrix}
\alpha + \beta & -\alpha \beta \\
1 & 0
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
(\alpha + \beta)^2-\alpha \beta & -\alpha \beta (\alpha + \beta)\\
\alpha + \beta & -\alpha \beta
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
(\alpha + \beta)^2 & -\alpha \beta (\alpha + \beta)\\
\alpha + \beta & 0
\end{pmatrix} - \begin{pmatrix}
\alpha \beta & 0\\
0 & \alpha \beta
\end{pmatrix}$

$\displaystyle = (\alpha + \beta) \begin{pmatrix}
\alpha + \beta & -\alpha \beta \\
1 & 0
\end{pmatrix} - \alpha \beta \begin{pmatrix}
1 & 0\\
0 & 1
\end{pmatrix}$

$\displaystyle = (\alpha + \beta) A - \alpha \beta I$

## 11(b)
$(A - \alpha I)^2$
$\displaystyle = A^2 - 2 \alpha A + \alpha^2 I$
$\displaystyle = (\alpha + \beta) A - \alpha \beta I- 2 \alpha A + \alpha^2 I$
$\displaystyle = (\alpha + \beta - 2 \alpha) A + (\alpha^2 - \alpha \beta) I$
$\displaystyle = (\beta - \alpha) A + \alpha (\alpha - \beta) I$
$\displaystyle = (\beta - \alpha) (A - \alpha I)$

Also $(A - \beta I)^2$
$\displaystyle = A^2 - 2 \beta A + \beta^2 I$
$\displaystyle = (\alpha + \beta) A - \alpha \beta I- 2 \beta A + \beta^2 I$
$\displaystyle = (\alpha + \beta - 2 \beta) A + (\beta^2 - \alpha \beta) I$
$\displaystyle = (\alpha - \beta) A + \beta (\beta - \alpha) I$
$\displaystyle = (\alpha - \beta) (A - \beta I)$

## 11(c)(i)
$A = X + Y$
$\displaystyle \Rightarrow \begin{pmatrix}
\alpha + \beta & - \alpha \beta \\
1 & 0
\end{pmatrix} = s \begin{pmatrix}
\alpha + \beta & - \alpha \beta \\
1 & 0
\end{pmatrix} - s \alpha \begin{pmatrix}
1 & - 0 \\
0 & 1
\end{pmatrix} + t \begin{pmatrix}
\alpha + \beta & - \alpha \beta \\
1 & 0
\end{pmatrix} - t \beta \begin{pmatrix}
1 & - 0 \\
0 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
\alpha + \beta & - \alpha \beta \\
1 & 0
\end{pmatrix} = \begin{pmatrix}
(\alpha + \beta) (s + t) - s \alpha - t \beta & - \alpha \beta (s + t) \\
s + t & - s \alpha  - t \beta
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
\alpha + \beta & - \alpha \beta \\
1 & 0
\end{pmatrix} = \begin{pmatrix}
 s \beta + t \alpha & - \alpha \beta (s + t) \\
s + t & - s \alpha  - t \beta
\end{pmatrix}$

$\displaystyle \Rightarrow \alpha + \beta = t \alpha + s \beta$ and $s \alpha + t \beta = 0$

$\displaystyle \Rightarrow s = {\beta \over {\beta - \alpha}}$ and $\displaystyle t = -{\alpha \over {\beta - \alpha}} = {\alpha \over {\alpha - \beta}}$

## 11(c)(ii)
Let P(n) be the statement that $\displaystyle X^n = {{\beta^n} \over {\beta - \alpha}} (A - \alpha I)$ and $\displaystyle Y^n = {{\alpha^n} \over {\alpha - \beta}} (A - \beta I)$ for any positive $n$.

When n = 1,
$\displaystyle X^1 = X = s(A - \alpha I) = {\beta \over {\beta - \alpha}} (A - \alpha I)$ and
$\displaystyle Y^1 = Y = t(A - \beta I) = {\alpha \over {\alpha - \beta}} (A - \beta I)$
Therefore, P(1) is true.

Assume that P(k) is true for some positive integer k $\geq 1$. Then
$\displaystyle X^{k+1} = X^k X = {{\beta^k} \over {\beta - \alpha}} (A - \alpha I) \cdot {\beta \over {\beta - \alpha}} (A - \alpha I)$ 
$\displaystyle = {{\beta^{k+1}} \over {(\beta - \alpha)^2}} (A - \alpha I)^2$ 
$\displaystyle = {{\beta^{k+1}} \over {(\beta - \alpha)^2}} (A^2 - 2\alpha A + \alpha^2 I)$ 
$\displaystyle = {{\beta^{k+1}} \over {(\beta - \alpha)^2}} ((\alpha + \beta) A - \alpha \beta I - 2\alpha A + \alpha^2 I)$ 
$\displaystyle = {{\beta^{k+1}} \over {(\beta - \alpha)^2}} ((\beta - \alpha ) A - \alpha (\beta - \alpha) I)$
$\displaystyle = {{\beta^{k+1}} \over {\beta - \alpha}} (A - \alpha I)$ 

Also, $\displaystyle Y^{k+1} = Y^k Y = {{\alpha^k} \over {\alpha - \beta}} (A - \beta I) \cdot {\alpha \over {\alpha - \beta}} (A - \beta I)$
$\displaystyle = {{\alpha^{k+1}} \over {(\alpha - \beta)^2}} (A - \beta I)^2$
$\displaystyle = {{\alpha^{k+1}} \over {(\alpha - \beta)^2}} (A^2 - 2\beta A + \beta^2 I)$
$\displaystyle = {{\alpha^{k+1}} \over {(\alpha - \beta)^2}} ((\alpha + \beta) A - \alpha \beta I - 2\beta A + \beta^2 I)$
$\displaystyle = {{\alpha^{k+1}} \over {(\alpha - \beta)^2}} ((\alpha - \beta) A - \beta (\alpha - \beta) I)$
$\displaystyle = {{\alpha^{k+1}} \over {\alpha - \beta}} (A - \beta I)$
Therefore, P(k+1) is true. By mathematical induction, P(n) is true.

## 11(c)(iii)
Consider,
$X Y = s(A - \alpha I) \cdot t(A - \beta I)$
$\displaystyle = st(A^2 - (\alpha + \beta) A + \alpha \beta I)$
$\displaystyle = st((\alpha + \beta) A - \alpha \beta I - (\alpha + \beta) A + \alpha \beta I)$
$\displaystyle = st (0) = 0$

$Y X = t(A - \beta I) \cdot s(A - \alpha I)$
$\displaystyle = st(A^2 - (\alpha + \beta) A + \alpha \beta I)$
$\displaystyle = st((\alpha + \beta) A - \alpha \beta I - (\alpha + \beta) A + \alpha \beta I)$
$\displaystyle = st (0) = 0$

Therefore $XY = YX = 0$
$\displaystyle \Rightarrow (X + Y)^n = X^n + K^n$ for any positive integer n.

Now, $A = X + Y$
$\displaystyle \Rightarrow A^n = (X + Y)^n$
$\displaystyle \Rightarrow A^n = X^n + Y^n$
$\displaystyle \Rightarrow A^n = {{\beta^n} \over {\beta - \alpha}} (A - \alpha I) + {{\alpha^n} \over {\alpha - \beta}} (A - \beta I)$
$\displaystyle \Rightarrow A^n = {{\beta^n - \alpha^n} \over {\beta - \alpha}} A + {{\alpha^n \beta - \alpha \beta^n} \over {\beta - \alpha}} I$
