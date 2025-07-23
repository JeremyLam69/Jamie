## 11(a)(i)
$\displaystyle P^2 = \begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 1 \\
1 & 1 & 1
\end{pmatrix} \begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 1 \\
1 & 1 & 1
\end{pmatrix} = \begin{pmatrix}
1 & 1 & 1 \\
1 & 2 & 2 \\
1 & 2 & 3
\end{pmatrix}$

$\displaystyle P^3 = P^2P = \begin{pmatrix}
1 & 1 & 1 \\
1 & 2 & 2 \\
1 & 2 & 3
\end{pmatrix} \begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 1 \\
1 & 1 & 1
\end{pmatrix} = \begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & 5 \\
3 & 5 & 6
\end{pmatrix}$

$\displaystyle \Rightarrow P^3 - 2P^2 - P + I$
$\displaystyle = \begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & 5 \\
3 & 5 & 6
\end{pmatrix} - 2  \begin{pmatrix}
1 & 1 & 1 \\
1 & 2 & 2 \\
1 & 2 & 3
\end{pmatrix} - \begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 1 \\
1 & 1 & 1
\end{pmatrix} + \begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow P^3 - 2P^2 - P + I$
$\displaystyle = \begin{pmatrix}
1-2-0+1 & 2-2-0+0 & 3-2-1+0 \\
2-2-0+0 & 4-4-1+1 & 5-4-1+0 \\
3-2-1+0 & 5-4-1+0 & 6-6-1+1
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
0 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 0
\end{pmatrix} = 0$

## 11(a)(ii)
$\displaystyle P^3 - 2P^2 - P + I = 0$
$\displaystyle \Rightarrow  I = -P^3 + 2P^2 + P$
$\displaystyle \Rightarrow  P^{-1} = -P^2 + 2P + I$
$\displaystyle \Rightarrow  P^{-1} = -P^2 + 2P + I$

$\displaystyle = -\begin{pmatrix}
1 & 1 & 1 \\
1 & 2 & 2 \\
1 & 2 & 3
\end{pmatrix} + 2 \begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 1 \\
1 & 1 & 1
\end{pmatrix}+ \begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
-1+0+1 & -1+0+0 & -1+2+0 \\
-1+0+0 & -2+2+1 & -2+2+0 \\
-1+2+0 & -2+2+0 & -3+2+1
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
0 & -1 & 1 \\
-1 & 1 & 0 \\
1 & 0 & 0
\end{pmatrix}$

## 11(b)(i)
$\displaystyle P^{-1}AP = \begin{pmatrix}
0 & -1 & 1 \\
-1 & 1 & 0 \\
1 & 0 & 0
\end{pmatrix}  \begin{pmatrix}
2 & 0 & 0 \\
1 & 1 & 0 \\
1 & 0 & 1
\end{pmatrix} \begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 1 \\
1 & 1 & 1
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
0 & -1 & 1 \\
-1 & 1 & 0 \\
2 & 0 & 0
\end{pmatrix} \begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 1 \\
1 & 1 & 1
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 2
\end{pmatrix} = D$

## 11(b)(ii)
$det\ D = 2 \neq 0 \Rightarrow$ D is non-singular. 
$det\ A = 2 \neq 0 \Rightarrow$ A is non-singular.

## 11(b)(iii)
$\displaystyle D^{-1} = {1 \over 2} \begin{pmatrix}
2 & 0 & 0 \\
0 & 2 & 0 \\
0 & 0 & 1
 \end{pmatrix}^T  = {1 \over 2} \begin{pmatrix}
2 & 0 & 0 \\
0 & 2 & 0 \\
0 & 0 & 1
 \end{pmatrix} = \begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & {1 \over 2}
 \end{pmatrix}$

Also
$\displaystyle D = P^{-1}AP$
$\displaystyle \Rightarrow D^{-1} = (P^{-1}AP)^{-1}$
$\displaystyle \Rightarrow D^{-1} = (AP)^{-1}(P^{-1})^{-1}$
$\displaystyle \Rightarrow D^{-1} = P^{-1}A^{-1}P$
$\displaystyle \Rightarrow A^{-1} = PD^{-1}P^{-1}$
$\displaystyle \Rightarrow (A^{-1})^{100} = (PD^{-1}P^{-1})^{100}$
$\displaystyle \Rightarrow (A^{-1})^{100} = P(D^{-1})^{100}P^{-1}$

$\displaystyle \Rightarrow (A^{-1})^{100} = \begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 1 \\
1 & 1 & 1
\end{pmatrix} \begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & {1 \over 2}
 \end{pmatrix}^{100} \begin{pmatrix}
0 & -1 & 1 \\
-1 & 1 & 0 \\
1 & 0 & 0
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
0 & 0 & 1 \\
0 & 1 & 1 \\
1 & 1 & 1
\end{pmatrix} \begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & {1 \over {2^{100}}}
 \end{pmatrix} \begin{pmatrix}
0 & -1 & 1 \\
-1 & 1 & 0 \\
1 & 0 & 0
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
0 & 0 & {1 \over {2^{100}}} \\
0 & 1 & {1 \over {2^{100}}} \\
1 & 1 & {1 \over {2^{100}}}
\end{pmatrix} \begin{pmatrix}
0 & -1 & 1 \\
-1 & 1 & 0 \\
1 & 0 & 0
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
{1 \over {2^{100}}} & 0 & 0 \\
{1 \over {2^{100}}}-1 & 1 & 0 \\
{1 \over {2^{100}}}-1 & 0 & 1
\end{pmatrix}$