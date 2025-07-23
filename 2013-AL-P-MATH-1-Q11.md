## 11(a)(i)
$\displaystyle A \begin{pmatrix}
1 \\
-2
\end{pmatrix} = \lambda \begin{pmatrix}
1 \\
-2
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
a & -2 \\
-2 & a+3
\end{pmatrix} \begin{pmatrix}
1 \\
-2
\end{pmatrix} = \begin{pmatrix}
\lambda \\
-2 \lambda
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
a + 4 \\
-2a-8
\end{pmatrix} = \begin{pmatrix}
\lambda \\
-2 \lambda
\end{pmatrix}$

$\displaystyle \Rightarrow \lambda = a+4$

## 11(a)(ii)
$\displaystyle A \begin{pmatrix}
b \\
1
\end{pmatrix} = \mu \begin{pmatrix}
b \\
1
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
a & -2 \\
-2 & a+3
\end{pmatrix} \begin{pmatrix}
b \\
1
\end{pmatrix} = \begin{pmatrix}
\mu b \\
\mu
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
ab-2 \\
-2b+a+3
\end{pmatrix} = \begin{pmatrix}
\mu b \\
\mu
\end{pmatrix}$

$\displaystyle \Rightarrow ab-2=\mu b$ and $\displaystyle -2b+a+3=\mu$
$\displaystyle \Rightarrow ab-2=(-2b+a+3) b$
$\displaystyle \Rightarrow ab-2 = -2b^2+ab+3b$
$\displaystyle \Rightarrow 2b^2 - 3b - 2 = 0$
$\displaystyle \Rightarrow (2b+1) (b-2) = 0$
$\displaystyle \Rightarrow b = - {1 \over 2}$(rejected since b>0) or $2$
$\displaystyle \Rightarrow b = 2$

Therefore $\mu = -2b+a+3 = a-1$

## 11(a)(iii)(1)
$\displaystyle M^T M =\begin{pmatrix}
1 & -2 \\
2 & 1
\end{pmatrix} \begin{pmatrix}
1 & 2 \\
-2 & 1
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
5 & 0 \\
0 & 5
\end{pmatrix} = 5I$

## 11(a)(iii)(2)
Let P(n) be the statement that $A^n = {1 \over 5} M D^n M^T$ for any $n \in N$ where $D = \begin{pmatrix}
\lambda & 0 \\
0 & \mu
\end{pmatrix}$

When n = 1,
$\displaystyle {1 \over 5} M D^1 M^T$

$\displaystyle = {1 \over 5} \begin{pmatrix}
1 & 2 \\
-2 & 1
\end{pmatrix}  \begin{pmatrix}
\lambda & 0 \\
0 & \mu
\end{pmatrix} \begin{pmatrix}
1 & -2 \\
2 & 1
\end{pmatrix}$

$\displaystyle = {1 \over 5} \begin{pmatrix}
\lambda & 2 \mu \\
-2 \lambda & \mu
\end{pmatrix} \begin{pmatrix}
1 & -2 \\
2 & 1
\end{pmatrix}$

$\displaystyle = {1 \over 5} \begin{pmatrix}
\lambda + 4 \mu & -2 \lambda + 2 \mu \\
-2 \lambda + 2 \mu & 4 \lambda + \mu
\end{pmatrix}$

$\displaystyle = {1 \over 5} \begin{pmatrix}
a+4 + 4(a-1) & -2(a+4) + 2(a-1) \\
-2 (a+4) + 2 (a-1) & 4 (a+4) + a-1
\end{pmatrix}$

$\displaystyle = {1 \over 5} \begin{pmatrix}
5a & -10 \\
-10 & 5a+15
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
a & -2 \\
-2 & a+3
\end{pmatrix}$

$\displaystyle = A$
Therefore P(1) is true.

Assume that P(k) is true for some natural number $k \geq 1$. Then,
$\displaystyle A^{k+1}$
$\displaystyle = A^k A$
$\displaystyle = {1 \over 5} M D^k M^T \cdot {1 \over 5} M D M^T$
$\displaystyle = {1 \over {25}} M D^k (M^T M) D M^T$
$\displaystyle = {1 \over {25}} M D^k (5I) D M^T$
$\displaystyle = {1 \over 5} M D^k D M^T$
$\displaystyle = {1 \over 5} M D^{k+1} M^T$.
Therefore P(k+1) is true and by mathematical induction P(n) is true.

## 11(b)(i)
Let a=3, then $\lambda = 7$ , $\mu = 2$ and $A = \begin{pmatrix}
3 & -2 \\
-2 & 6
\end{pmatrix}$. Then 

$\displaystyle \begin{pmatrix}
x & y
\end{pmatrix} \begin{pmatrix}
3 & -2 \\
-2 & 6
\end{pmatrix}^{2013} \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow \begin{pmatrix}
x & y
\end{pmatrix} A^{2013} \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow \begin{pmatrix}
x & y
\end{pmatrix} {1 \over 5} M D^{2013} M^T \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow {1 \over 5} \begin{pmatrix}
x & y
\end{pmatrix} \begin{pmatrix}
1 & -2 \\
2 & 1
\end{pmatrix} \begin{pmatrix}
7^{2013} & 0 \\
0 & 2^{2013}
\end{pmatrix} \begin{pmatrix}
1 & 2 \\
-2 & 1
\end{pmatrix} \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow {1 \over 5} \begin{pmatrix}
x & y
\end{pmatrix} \begin{pmatrix}
7^{2013} & -2^{2014} \\
2 \cdot 7^{2013} & 2^{2013}
\end{pmatrix} \begin{pmatrix}
1 & 2 \\
-2 & 1
\end{pmatrix} \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow {1 \over 5} \begin{pmatrix}
x & y
\end{pmatrix} \begin{pmatrix}
7^{2013}+2^{2015} & 2 \cdot 7^{2013}-2^{2014} \\
2 \cdot 7^{2013} - 2^{2014} & 4 \cdot 7^{2013} + 2^{2013}
\end{pmatrix} \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow \begin{pmatrix}
(7^{2013}+2^{2015})x + (2 \cdot 7^{2013} - 2^{2014})y & (2 \cdot 7^{2013}-2^{2014})x + (4 \cdot 7^{2013} + 2^{2013})y
\end{pmatrix} \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow (7^{2013}+2^{2015})x^2 + (2 \cdot 7^{2013} - 2^{2014})xy + (2 \cdot 7^{2013}-2^{2014})xy + (4 \cdot 7^{2013} + 2^{2013})y^2 = 0$

$\displaystyle \Rightarrow (7^{2013} + 2^{2015})x^2 + 2(7^{2013} - 2^{2013})xy + (4 \cdot 7^{2013} + 2^{2013})y^2 = 0$

$\displaystyle \Rightarrow (7^{2013} + 4 \cdot 2^{2013})x^2 + 2(7^{2013} - 2^{2013})xy + (4 \cdot 7^{2013} + 2^{2013})y^2= 0$

$\displaystyle \Rightarrow (7^{2013} - 2^{2013} + 6 \cdot 2^{2013})x^2 + 2(7^{2013} - 2^{2013})xy + (7^{2013} - 2^{2013} + 3 \cdot 7^{2013} + 2 \cdot 2^{2013})y^2= 0$

$\displaystyle \Rightarrow (7^{2013} - 2^{2013}) (x^2 + 2xy + y^2) + 6 \cdot 2^{2013}x^2 + (3 \cdot 7^{2013} + 2 \cdot 2^{2013})y^2= 0$

$\displaystyle \Rightarrow (7^{2013} - 2^{2013}) (x + y)^2 + 6 \cdot 2^{2013}x^2 + (3 \cdot 7^{2013} + 2 \cdot 2^{2013})y^2= 0$

$\displaystyle \Rightarrow (x + y)^2=0$ or $x^2=0$ or $y^2=0$

$\displaystyle \Rightarrow x=0$ or $y=0$



## 11(b)(ii)
Let a=1, then $\lambda = 5$ , $\mu = 0$ and $A = \begin{pmatrix}
1 & -2 \\
-2 & 4
\end{pmatrix}$. Then

$\displaystyle \begin{pmatrix}
x & y
\end{pmatrix} \begin{pmatrix}
1 & -2 \\
-2 & 4
\end{pmatrix}^{2013} \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow {1 \over 5} \begin{pmatrix}
x & y
\end{pmatrix} \begin{pmatrix}
1 & -2 \\
2 & 1
\end{pmatrix} \begin{pmatrix}
5^{2013} & 0 \\
0 & 0
\end{pmatrix} \begin{pmatrix}
1 & 2 \\
-2 & 1
\end{pmatrix} \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow {1 \over 5} \begin{pmatrix}
x & y
\end{pmatrix} \begin{pmatrix}
5^{2013} & 0 \\
2 \cdot 5^{2013} & 0
\end{pmatrix} \begin{pmatrix}
1 & 2 \\
-2 & 1
\end{pmatrix} \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow {1 \over 5} \begin{pmatrix}
x & y
\end{pmatrix} \begin{pmatrix}
5^{2013} & 2 \cdot 5^{2013} \\
2 \cdot 5^{2013} & 4 \cdot 5^{2013}
\end{pmatrix} \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow \begin{pmatrix}
5^{2013}x + 2 \cdot 5^{2013}y & 2 \cdot 5^{2013}x + 4 \cdot 5^{2013}y
\end{pmatrix} \begin{pmatrix}
x \\
y
\end{pmatrix} = 0$

$\displaystyle \Rightarrow 5^{2013}x^2 + 2 \cdot 5^{2013}xy + 2 \cdot 5^{2013}xy + 4 \cdot 5^{2013}y^2 = 0$

$\displaystyle \Rightarrow x^2 + 4 xy + 4 y^2 = 0$

$\displaystyle \Rightarrow (x + 2 y)^2 = 0$

$\displaystyle \Rightarrow x + 2 y = 0$

Therefore, it is NOT necessary that both x and y equal 0.