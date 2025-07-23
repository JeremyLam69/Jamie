## 7(a)
$MX=XM$

$\displaystyle \Rightarrow \begin{pmatrix}
7 & 3 \\
-1 & 5
\end{pmatrix} \begin{pmatrix}
a & 6a \\
b & c
\end{pmatrix} = \begin{pmatrix}
a & 6a \\
b & c
\end{pmatrix} \begin{pmatrix}
7 & 3 \\
-1 & 5
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
7a+3b & 42a+3c \\
-a+5b & -6a+5c
\end{pmatrix} = \begin{pmatrix}
a & 33a \\
7b-c & 3b+5c
\end{pmatrix}$

$\displaystyle \Rightarrow 7a+3b=a$  and  $42a+3c=33a$
$\displaystyle \Rightarrow b = -2a$  and  $c = -3a$

## 7(b)
$\displaystyle X = \begin{pmatrix}
a & 6a \\
b & c
\end{pmatrix} = \begin{pmatrix}
a & 6a \\
-2a & -3a
\end{pmatrix}  = a \begin{pmatrix}
1 & 6 \\
-2 & -3
\end{pmatrix}$

$\displaystyle \begin{vmatrix} X \end{vmatrix} = \begin{vmatrix}
a \begin{pmatrix}
1 & 6 \\
-2 & -3
\end{pmatrix}
\end{vmatrix} = a^2 \begin{vmatrix}
1 & 6 \\
-2 & -3
\end{vmatrix} = 9a^2 \neq 0$

Therefore X is non-singular.

## 7(c)
$\displaystyle (X^T)^{-1}$
$\displaystyle = (X^{-1})^T$

$\displaystyle = ( {1 \over {9a^2}} \cdot a \begin{pmatrix}
-3 & -6 \\
2 & 1
\end{pmatrix})^T$

$\displaystyle = ( {1 \over {9a}} \begin{pmatrix}
-3 & -6 \\
2 & 1
\end{pmatrix})^T$

$\displaystyle = {1 \over {9a}} \begin{pmatrix}
-3 & 2 \\
-6 & 1
\end{pmatrix}$
