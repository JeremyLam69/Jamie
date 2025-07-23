## 11(a)
$M^2 = aM + bI$
$\displaystyle \Rightarrow \begin{pmatrix}
2 & 7 \\
-1 & -6
\end{pmatrix} \begin{pmatrix}
2 & 7 \\
-1 & -6
\end{pmatrix} = a \begin{pmatrix}
2 & 7 \\
-1 & -6
\end{pmatrix} + b \begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
-3 & -28 \\
4 & 29
\end{pmatrix} = \begin{pmatrix}
2a+b & 7a \\
-a & -6a+b
\end{pmatrix}$

$\displaystyle \Rightarrow a=-4$  and  $b=5$

## 11(b)
Let P(n) be the statement that $6M^n = (1-(-5)^n)M+(5+(-5)^n)I$ for all positive integers n.

When n = 1,
R.H.S. = $(1-(-5)^n)M+(5+(-5)^n)I$
= $(1-(-5))M+(5+(-5))I$
= $6M-4I$
= $6M$
= L.H.S.
Therefore P(1) is true.

Assume P(k) is true for some positive integer $k \geq 1$. Then,
$6M^{k+1}$
$= 6M^k M$
$= [(1-(-5)^k)M+(5+(-5)^k)I] M$
$= (1-(-5)^k)M^2+(5+(-5)^k)M$
$= (1-(-5)^k)(-4M+5I)+(5+(-5)^k)M$
$= [\ (5+(-5)^k)-4(1-(-5)^k)\ ]M + 5(1-(-5)^k)I$
$= [\ 5+(-5)^k-4+4(-5)^k)\ ]M + 5(1-(-5)^k)I$
$= [\ 1+5(-5)^k)\ ]M + 5(1-(-5)^k)I$
$= [\ 1-(-5)(-5)^k)\ ]M + (5-5(-5)^k)I$
$= [\ 1-(-5)^{k+1})\ ]M + [\ 5+(-5)(-5)^k\ ]I$
$= (1-(-5)^{k+1}))M + (5+(-5)^{k+1})I$
Therefore P(k+1) is true and by mathematical indication P(n) is true.

## 11(c)

Note that $\displaystyle M^{-1} = - {1 \over 5} \begin{pmatrix}
-6 & -7 \\
1 & 2
\end{pmatrix}$ and $\displaystyle M^{-2} = {1 \over 25} \begin{pmatrix}
-6 & -7 \\
1 & 2
\end{pmatrix} \begin{pmatrix}
-6 & -7 \\
1 & 2
\end{pmatrix} = {1 \over 25} \begin{pmatrix}
29 & 28 \\
-4 & -3
\end{pmatrix}$

Consider matrices A and B such that 
$\displaystyle M^{-1} = A - {1 \over 5} B$ and $\displaystyle M^{-2} = A + {1 \over 25} B$

$\displaystyle \Rightarrow - {1 \over 5} \begin{pmatrix}
-6 & -7 \\
1 & 2
\end{pmatrix} = A - {1 \over 5} B$ and $\displaystyle {1 \over 25} \begin{pmatrix}
29 & 28 \\
-4 & -3
\end{pmatrix} = A + {1 \over 25} B$

$\displaystyle \Rightarrow 5A - B = \begin{pmatrix}
6 & 7 \\
-1 & -2
\end{pmatrix}$ and $\displaystyle 25A + B = \begin{pmatrix}
29 & 28 \\
-4 & -3
\end{pmatrix}$

$\displaystyle \Rightarrow A = {1 \over 6} \begin{pmatrix}
7 & 7 \\
-1 & -1
\end{pmatrix}$ and $\displaystyle B = {1 \over 6} \begin{pmatrix}
-1 & -7 \\
1 & 7
\end{pmatrix}$

Also,
$\displaystyle AM = {1 \over 6} \begin{pmatrix}
7 & 7 \\
-1 & -1
\end{pmatrix} \begin{pmatrix}
2 & 7 \\
-1 & -6
\end{pmatrix} = {1 \over 6} \begin{pmatrix}
7 & 7 \\
-1 & -1
\end{pmatrix} = A$

$\displaystyle MA = \begin{pmatrix}
2 & 7 \\
-1 & -6
\end{pmatrix} \cdot {1 \over 6} \begin{pmatrix}
7 & 7 \\
-1 & -1
\end{pmatrix} = {1 \over 6} \begin{pmatrix}
2 & 7 \\
-1 & -6
\end{pmatrix} \begin{pmatrix}
7 & 7 \\
-1 & -1
\end{pmatrix} = {1 \over 6} \begin{pmatrix}
7 & 7 \\
-1 & -1
\end{pmatrix} = A$

$\displaystyle BM = {1 \over 6} \begin{pmatrix}
-1 & -7 \\
1 & 7
\end{pmatrix} \begin{pmatrix}
2 & 7 \\
-1 & -6
\end{pmatrix} = {1 \over 6} \begin{pmatrix}
5 & 35 \\
-5 & -35
\end{pmatrix} = -{5 \over 6} \begin{pmatrix}
-1 & -7 \\
1 & 7
\end{pmatrix} = -5B$

$\displaystyle MB = \begin{pmatrix}
2 & 7 \\
-1 & -6
\end{pmatrix} \cdot {1 \over 6} \begin{pmatrix}
-1 & -7 \\
1 & 7
\end{pmatrix} = {1 \over 6}  \begin{pmatrix}
2 & 7 \\
-1 & -6
\end{pmatrix} \begin{pmatrix}
-1 & -7 \\
1 & 7
\end{pmatrix} = {1 \over 6} \begin{pmatrix}
5 & 35 \\
-5 & -35
\end{pmatrix} = -5B$

$\displaystyle A + B = {1 \over 6} \begin{pmatrix}
7 & 7 \\
-1 & -1
\end{pmatrix} + {1 \over 6} \begin{pmatrix}
-1 & -7 \\
1 & 7
\end{pmatrix} = I$

Now let $\displaystyle X = A + {1 \over {(-5)^n}}B$ for all positive integers n. Then,
$\displaystyle M^nX$
$\displaystyle = {1 \over 6} [\ (1-(-5)^n)M+(5+(-5)^n)I\ ] (A + {1 \over {(-5)^n}}B)$

$\displaystyle = {1 \over 6} [\ (1-(-5)^n)MA + (5+(-5)^n)A + {1-(-5)^n \over {(-5)^n}}MB + {5+(-5)^n \over {(-5)^n}}B\ ]$

$\displaystyle = {1 \over 6} [\ (1-(-5)^n)A + (5+(-5)^n)A + {1-(-5)^n \over {(-5)^n}}(-5)B + {5+(-5)^n \over {(-5)^n}}B\ ]$

$\displaystyle = {1 \over 6} [\ 6A + {5(-5)^n-5 \over {(-5)^n}}B + {5+(-5)^n \over {(-5)^n}}B\ ]$

$\displaystyle = {1 \over 6} [\ 6A + {6(-5)^n \over {(-5)^n}}B\ ]$

$\displaystyle = A + B = I$

$\displaystyle XM^n$
$\displaystyle = (A + {1 \over {(-5)^n}}B) \cdot {1 \over 6} [\ (1-(-5)^n)M+(5+(-5)^n)I\ ]$

$\displaystyle = {1 \over 6} (A + {1 \over {(-5)^n}}B) [\ (1-(-5)^n)M+(5+(-5)^n)I\ ]$

$\displaystyle = {1 \over 6} [\ (1-(-5)^n)AM+(5+(-5)^n)A + {1-(-5)^n \over {(-5)^n}}BM + {5+(-5)^n \over {(-5)^n}}B ]$

$\displaystyle = {1 \over 6} [\ (1-(-5)^n)A + (5+(-5)^n)A + {1-(-5)^n \over {(-5)^n}}(-5)B + {5+(-5)^n \over {(-5)^n}}B ]$

$\displaystyle = {1 \over 6} [\ 6A + {5(-5)^n-5 \over {(-5)^n}}B + {5+(-5)^n \over {(-5)^n}}B ]$

$\displaystyle = {1 \over 6} [\ 6A + {6(-5)^n \over {(-5)^n}}B\ ]$

$\displaystyle = A + B = I$

Therefore $\displaystyle (M^n)^{-1} = X = A + {1 \over {(-5)^n}}B$