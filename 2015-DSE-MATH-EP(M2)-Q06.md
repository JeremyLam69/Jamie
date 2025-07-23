## 6(a)
$M^T = -M$
$\Rightarrow \begin{vmatrix} M^T \end{vmatrix} = \begin{vmatrix} -M \end{vmatrix}$
$\Rightarrow \begin{vmatrix} M \end{vmatrix} = - \begin{vmatrix} M \end{vmatrix}$
$\Rightarrow 2 \begin{vmatrix} M \end{vmatrix} = 0$
$\Rightarrow \begin{vmatrix} M \end{vmatrix} = 0$

## 6(b)(i)
$\displaystyle A + I$
$\displaystyle = \begin{pmatrix}
-1 & a & b \\
-a & -1 & -8 \\
-b & 8 & -1
\end{pmatrix} + \begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
0 & a & b \\
-a & 0 & -8 \\
-b & 8 & 0
\end{pmatrix}$

$\displaystyle \Rightarrow (A+I)^T =  \begin{pmatrix}
0 & a & b \\
-a & 0 & -8 \\
-b & 8 & 0
\end{pmatrix}^T$

$\displaystyle \Rightarrow (A+I)^T =  \begin{pmatrix}
0 & -a & -b \\
a & 0 & 8 \\
b & -8 & 0
\end{pmatrix}$

$\displaystyle \Rightarrow (A+I)^T =  -(A+I)$
$\displaystyle \Rightarrow \begin{vmatrix} A+I \end{vmatrix} =  0$

## 6(b)(ii)
$\displaystyle \begin{vmatrix} A^3+I \end{vmatrix}$
$\displaystyle = \begin{vmatrix} (A+I)(A^2-A+I) \end{vmatrix}$
$\displaystyle = \begin{vmatrix} A+I \end{vmatrix} \begin{vmatrix} A^2-A+I \end{vmatrix}$
$\displaystyle = (0) \begin{vmatrix} A^2-A+I \end{vmatrix}$
$\displaystyle = 0$

Therefore $A^3+I$ is singular.