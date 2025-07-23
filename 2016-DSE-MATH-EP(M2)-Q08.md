## 8(a)(i)
$\displaystyle A^2 = \begin{pmatrix}
1 & 0 \\
1 & 1
\end{pmatrix}  \begin{pmatrix}
1 & 0 \\
1 & 1
\end{pmatrix} = \begin{pmatrix}
1 & 0 \\
2 & 1
\end{pmatrix}$

## 8(a)(ii)
Let $X =  \begin{pmatrix}
0 & 0 \\
1 & 0
\end{pmatrix}$. Then,

$\displaystyle X^2 =  \begin{pmatrix}
0 & 0 \\
1 & 0
\end{pmatrix} \begin{pmatrix}
0 & 0 \\
1 & 0
\end{pmatrix} = 0$ 

Therefore, for all positive integer $n \geq 3$
$\displaystyle X^n = X^2 X^{n-2} = (0) X^{n-2} = 0$

Now, for all positive integer $n \geq 3$, $A^n$
$\displaystyle = (I + X)^n$
$\displaystyle = I + nX + \binom{n}{2}X^2 + \sum_{r=3}^{n} \binom{n}{r}X^r$
$\displaystyle = I + nX + \binom{n}{2}(0) + \sum_{r=3}^{n} \binom{n}{r}(0)$
$\displaystyle = I + nX$

$\displaystyle = \begin{pmatrix}
1 & 0 \\
n & 1
\end{pmatrix}$

Consider also the definition of A (case n=1) and result in (i) (case n=2), 
$\displaystyle A^n= \begin{pmatrix}
1 & 0 \\
n & 1
\end{pmatrix}$  for all positive integer n.

## 8(a)(iii)
$\displaystyle (A^{-1})^n$
$\displaystyle = (A^n)^{-1}$

$\displaystyle = \begin{pmatrix}
1 & 0 \\
n & 1
\end{pmatrix}^{-1}$

$\displaystyle = \begin{pmatrix}
1 & 0 \\
-n & 1
\end{pmatrix}$

## 8(b)(i)
Let P(n) be the statement that $\sum_{k=0}^{n-1} 2^k = 2^n - 1$ for all positive integers n.
When n=1,
$L.H.S = \sum_{k=0}^{1-1} 2^k = \sum_{k=0}^{0} 2^k = 2^0 = 1 = 2 - 1 = 2^1 - 1 = R.H.S.$
Therefore, P(1) is true.

Assume P(r) is true for positive integer $r \geq 1$. Then
$\sum_{k=0}^{(r + 1) -1} 2^k$

$= \sum_{k=0}^r 2^k$

$= 2^r + \sum_{k=0}^{r-1} 2^k$

$= 2^r + 2^r - 1$

$= 2 \cdot 2^r - 1$

$= 2^{r+1} - 1$
Therefore, P(r+1) is also true and by mathematical induction, P(n) is true.

Hence, $\sum_{k=0}^{n-1} 2^k = 2^n - 1$ for all positive integers n


## 8(b)(ii)
Let $Y = \begin{pmatrix}
1 & 0 \\
1 & 2
\end{pmatrix}$

Let P(n) be the statement that $Y^n = \begin{pmatrix}
1 & 0 \\
\sum_{k=0}^{n-1} 2^k & 2^n
\end{pmatrix}$ for all positive integers n.

When n=1,
R.H.S. = $\begin{pmatrix}
1 & 0 \\
\sum_{k=0}^{1-1} 2^k & 2^1
\end{pmatrix} = \begin{pmatrix}
1 & 0 \\
2^0 & 2
\end{pmatrix} = \begin{pmatrix}
1 & 0 \\
1 & 2
\end{pmatrix} = Y = Y^1$ = L.H.S.
Therefore, P(1) is true.

Assume that P(r) is true for some positive integer $r \geq 1$. Then,
$Y^{r+1}$
$= Y^r Y$
$\displaystyle = \begin{pmatrix}
1 & 0 \\
\sum_{k=0}^{r-1} 2^k & 2^r
\end{pmatrix} \begin{pmatrix}
1 & 0 \\
1 & 2
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
1 & 0 \\
\sum_{k=0}^{r-1} 2^k + 2^r & 2^{r+1}
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
1 & 0 \\
\sum_{k=0}^r 2^k & 2^{r+1}
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
1 & 0 \\
\sum_{k=0}^{(r+1)-1} 2^k & 2^{r+1}
\end{pmatrix}$

Therefore, P(r+1) is true and by mathematical induction P(n) is true.

Hence,
$\begin{pmatrix}
1 & 0 \\
1 & 2
\end{pmatrix}^n = \begin{pmatrix}
1 & 0 \\
\sum_{k=0}^{n-1} 2^k & 2^n
\end{pmatrix}  = \begin{pmatrix}
1 & 0 \\
2^n-1 & 2^n
\end{pmatrix}$