## 8(a)
$\displaystyle M^{-1} = {1 \over k^2} \begin{pmatrix}
0 & k & -k \\
0 & 0 & k^2 \\
k & -1 & 1
\end{pmatrix}^T  = {1 \over k^2} \begin{pmatrix}
0 & 0 & k \\
k & 0 & -1 \\
-k & k^2 & 1
\end{pmatrix}$

## 8(b)
$\displaystyle M \begin{pmatrix}
x \\
1 \\
z 
\end{pmatrix} = \begin{pmatrix}
2 \\
2 \\
1 
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
x \\
1 \\
z 
\end{pmatrix} = M^{-1} \begin{pmatrix}
2 \\
2 \\
1 
\end{pmatrix}$

$\displaystyle \Rightarrow M^{-1} \begin{pmatrix}
2 \\
2 \\
1 
\end{pmatrix} = \begin{pmatrix}
x \\
1 \\
z 
\end{pmatrix}$

$\displaystyle \Rightarrow {1 \over k^2} \begin{pmatrix}
0 & 0 & k \\
k & 0 & -1 \\
-k & k^2 & 1
\end{pmatrix} \begin{pmatrix}
2 \\
2 \\
1 
\end{pmatrix} = \begin{pmatrix}
x \\
1 \\
z 
\end{pmatrix}$

$\displaystyle \Rightarrow {1 \over k^2} \begin{pmatrix}
k \\
2k - 1 \\
-2k + 2k^2 +1 
\end{pmatrix} = \begin{pmatrix}
x \\
1 \\
z 
\end{pmatrix}$

$\displaystyle \Rightarrow k^2 - 2k + 1 = 0$
$\displaystyle \Rightarrow (k - 1)^2 = 0$
$\displaystyle \Rightarrow k = 1$