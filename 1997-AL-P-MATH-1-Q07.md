## 7(a)
$A$ is non-singular  $\Rightarrow det A \neq 0$ 
Also,

$A (A^{-1} - xI) = I - xA$
$\displaystyle \Rightarrow A (A^{-1} - xI) = x\ (x^{-1}I - A)$
$\displaystyle \Rightarrow A (A^{-1} - xI) = -x\ (A - x^{-1}I)$
$\displaystyle \Rightarrow det\ (\ A (A^{-1} - xI)\ ) = det\ (-x\ (A - x^{-1}I)\ )$
$\displaystyle \Rightarrow (det\ A)\ (det\ (A^{-1} - xI)) =  (-x)^{3}\ det\ (A - x^{-1}I)$ $\because$  A is 3x3
$\displaystyle \Rightarrow (det\ A)\ (det\ (A^{-1} - xI)) =  -\ x^{3}\ det\ (A - x^{-1}I)$
$\displaystyle \Rightarrow det\ (A^{-1} - xI) =  -\ {x^{3} \over {det\ A} }\ det\ (A - x^{-1}I)$

## 7(b)
$\displaystyle A - xI = \begin{pmatrix}
0 & 1 & 0 \\
0 & 0 & 1 \\
4 & -17 & 8
\end{pmatrix} -  \begin{pmatrix}
x & 0 & 0 \\
0 & x & 0 \\
0 & 0 & x
\end{pmatrix} = \begin{pmatrix}
-x & 1 & 0 \\
0 & -x & 1 \\
4 & -17 & 8-x
\end{pmatrix}$

$\displaystyle \Rightarrow det(A - xI) = \begin{vmatrix}
-x & 1 & 0 \\
0 & -x & 1 \\
4 & -17 & 8-x
\end{vmatrix}$

$\displaystyle \Rightarrow det(A - 4I) = \begin{vmatrix}
-4 & 1 & 0 \\
0 & -4 & 1 \\
4 & -17 & 8-4
\end{vmatrix} = \begin{vmatrix}
-4 & 1 & 0 \\
0 & -4 & 1 \\
4 & -17 & 4
\end{vmatrix}$

$\displaystyle \Rightarrow det(A - 4I) = (-4) \begin{vmatrix}
-4 & 1 \\
-17 & 4
\end{vmatrix} - \begin{vmatrix}
0 & 1 \\
4 & 4
\end{vmatrix} = (-4)(1) - (-4) = 0$

Therefore, $x = 4$ is a root of $det(A - xI) = 0$

Also, $\displaystyle det(A - xI) = (-x) \begin{vmatrix}
-x & 1 \\
-17 & 8-x
\end{vmatrix} - \begin{vmatrix}
0 & 1 \\
4 & 8-x
\end{vmatrix}$

$\displaystyle \Rightarrow det(A - xI) = -x^3 + 8x^2 - 17x + 4 = -(x - 4) (x^2 -4x +1) = -(x - 4)\ [x - (2+\sqrt3)]\ [x - (2-\sqrt3)]$

Therefore, roots of $det(A - xI)$ are $4\ , 2+\sqrt3$ and $2-\sqrt3$

Now, $\displaystyle det A =  \begin{vmatrix}
0 & 1 & 0 \\
0 & 0 & 1 \\
4 & -11 & 8
\end{vmatrix} = -4  \begin{vmatrix}
1 & 0 \\
0 & 1
\end{vmatrix} = -4 \neq 0$

Therefore, A is non-singular and $\displaystyle det\ (A^{-1} - xI) =  -\ {x^{3} \over {det\ A} }\ det\ (A - x^{-1}I)$

Hence, $det\ (A^{-1} - xI) = 0$
$\displaystyle \Rightarrow -\ {x^{3} \over {det\ A} }\ det\ (A - x^{-1}I) = 0$

$\displaystyle \Rightarrow x^{3} \ det\ (A - x^{-1}I) = 0$

$x = 0$ is NOT a solution because $\displaystyle det\ (A^{-1} - 0\ I) = det\ A^{-1} = {1 \over {det A}} \neq 0$

$\displaystyle \Rightarrow det\ (A - x^{-1}I) = 0$

$\displaystyle \Rightarrow x^{-1} = 4$ or $\ x^{-1} = 2+\sqrt3$ or $\ x^{-1} = 2-\sqrt3$

$\displaystyle \Rightarrow x={1 \over 4}$ or $\displaystyle x={1 \over {2+\sqrt3}}=2-\sqrt3$ or $\displaystyle x={1 \over {2-\sqrt3}}=2+\sqrt3$
