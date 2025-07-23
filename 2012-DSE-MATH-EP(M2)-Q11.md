## 11(a)
$\displaystyle \begin{vmatrix}
1-x & 4 \\
2 & 3-x
\end{vmatrix} = 0$

$\displaystyle \Rightarrow (1-x)(3-x)-8=0$
$\displaystyle \Rightarrow x^2 -4x -5 = 0$
$\displaystyle \Rightarrow (x-5)(x+1) = 0$
$\displaystyle \Rightarrow x=-1$ or $x=5$

## 11(b)(i)
$\displaystyle \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix} \begin{pmatrix}
a \\
b
\end{pmatrix} = x_1 \begin{pmatrix}
a \\
b
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix} \begin{pmatrix}
a \\
b
\end{pmatrix} = \begin{pmatrix}
-a \\
-b
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
a + 4b \\
2a + 3b
\end{pmatrix} = \begin{pmatrix}
-a \\
-b
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
2a + 4b \\
2a + 4b
\end{pmatrix} = \begin{pmatrix}
0 \\
0
\end{pmatrix}$

$\displaystyle \Rightarrow a= -2t$ , $b=t$ for some real number t.

$\displaystyle \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix} \begin{pmatrix}
c \\
1
\end{pmatrix} = x_2 \begin{pmatrix}
c \\
1
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix} \begin{pmatrix}
c \\
1
\end{pmatrix} = \begin{pmatrix}
5c \\
5
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
c + 4 \\
2c + 3
\end{pmatrix} = \begin{pmatrix}
5c \\
5
\end{pmatrix}$

$\displaystyle \Rightarrow c = 1$

Also, $\begin{vmatrix} P \end{vmatrix} = 1$

$\displaystyle \Rightarrow \begin{vmatrix}
a & c \\
b & 1
\end{vmatrix} = 1$

$\displaystyle \Rightarrow \begin{vmatrix}
-2t & 1 \\
t & 1
\end{vmatrix} = 1$ for some real number t

$\displaystyle \Rightarrow -3t=1$
$\displaystyle \Rightarrow t=-{1 \over 3}$

Therefore, $P = \begin{pmatrix}
{2 \over 3} & 1 \\
-{1 \over 3} & 1
\end{pmatrix}$

## 11(b)(ii)
$\displaystyle P^{-1} \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix} P$

$\displaystyle =  \begin{pmatrix}
1 & -1 \\
{1 \over 3} & {2 \over 3}
\end{pmatrix} \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix}  \begin{pmatrix}
{2 \over 3} & 1 \\
-{1 \over 3} & 1
\end{pmatrix}$

$\displaystyle =  \begin{pmatrix}
-1 & 1 \\
{5 \over 3} & {10 \over 3}
\end{pmatrix} \begin{pmatrix}
{2 \over 3} & 1 \\
-{1 \over 3} & 1
\end{pmatrix}$

$\displaystyle =  \begin{pmatrix}
-1 & 0 \\
0 & 5
\end{pmatrix}$

## 11(b)(iii)
$\displaystyle P^{-1} \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix} P =  \begin{pmatrix}
-1 & 0 \\
0 & 5
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix} = P \begin{pmatrix}
-1 & 0 \\
0 & 5
\end{pmatrix} P^{-1}$

$\displaystyle \Rightarrow \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix}^{12} = P \begin{pmatrix}
-1 & 0 \\
0 & 5
\end{pmatrix}^{12} P^{-1}$

$\displaystyle \Rightarrow \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix}^{12} = \begin{pmatrix}
{2 \over 3} & 1 \\
-{1 \over 3} & 1
\end{pmatrix} \begin{pmatrix}
1 & 0 \\
0 & 5^{12}
\end{pmatrix} \begin{pmatrix}
1 & -1 \\
{1 \over 3} & {2 \over 3}
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix}^{12} = \begin{pmatrix}
{2 \over 3} & 5^{12} \\
-{1 \over 3} & 5^{12}
\end{pmatrix} \begin{pmatrix}
1 & -1 \\
{1 \over 3} & {2 \over 3}
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
1 & 4 \\
2 & 3
\end{pmatrix}^{12} = {1 \over 3} \begin{pmatrix}
5^{12} + 2 & 2 \cdot 5^{12} -2 \\
5^{12} - 1 & 2 \cdot 5^{12} + 1
\end{pmatrix}$
