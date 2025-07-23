## 1992-AL-P MATH 1 #03
1. $B^{-1}\ exists \Rightarrow det\ B \neq 0 \Rightarrow \lambda \neq 0$

2. $\displaystyle B^{-1}AB = \begin{pmatrix}
a & 0 \\
0 & b \\
\end{pmatrix}$

$\displaystyle \Rightarrow AB = B \begin{pmatrix}
a & 0 \\
0 & b \\
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
1 & 0\\
1 & 3
\end{pmatrix} \begin{pmatrix}
-2 & 0\\
1 & \lambda \\
\end{pmatrix} = \begin{pmatrix}
-2 & 0\\
1 & \lambda \\
\end{pmatrix} \begin{pmatrix}
a & 0 \\
0 & b \\
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
-2 & 0 \\
1 & 3\lambda
\end{pmatrix} = \begin{pmatrix}
-2a & 0 \\
a & b\lambda
\end{pmatrix}$
$\Rightarrow a = 1$ and $b = 3$

3. $\displaystyle (B^{-1}AB)^{100} = \begin{pmatrix}
 1 & 0\\
 0 & 3
 \end{pmatrix}^{100}$

$\displaystyle \Rightarrow B^{-1}A^{100}B = \begin{pmatrix}
 1^{100} & 0\\
 0 & 3^{100}
\end{pmatrix}$

$\displaystyle \Rightarrow A^{100} = B \begin{pmatrix}
 1 & 0\\
 0 & 3^{100}
\end{pmatrix} B^{-1}$

$\displaystyle \Rightarrow A^{100} = \begin{pmatrix}
-2 & 0 \\
1 & \lambda
\end{pmatrix} \begin{pmatrix}
 1 & 0\\
 0 & 3^{100}
\end{pmatrix} B^{-1}$

$\displaystyle \Rightarrow A^{100} = \begin{pmatrix}
-2 & 0 \\
1 &  3^{100}\ \lambda
\end{pmatrix} B^{-1}$

$\displaystyle \Rightarrow A^{100} = \begin{pmatrix}
-2 & 0 \\
1 &  3^{100}\ \lambda
\end{pmatrix} \ {1 \over {-2\lambda}} \begin{pmatrix}
\lambda & 0 \\
-1 & -2
\end{pmatrix}$

$\displaystyle \Rightarrow A^{100} = {1 \over {-2\lambda}} \begin{pmatrix}
-2 & 0 \\
1 &  3^{100}\ \lambda
\end{pmatrix} \begin{pmatrix}
\lambda & 0 \\
-1 & -2
\end{pmatrix}$

$\displaystyle \Rightarrow A^{100} = {1 \over {-2\lambda}} \begin{pmatrix}
-2 \lambda & 0 \\
{\lambda -  \lambda \ 3^{100}}  &  -2\ \lambda \ 3^{100} 
\end{pmatrix}$

$\displaystyle \Rightarrow A^{100} = \begin{pmatrix}
1 & 0 \\
{3^{100} - 1} \over 2  &  3^{100} 
\end{pmatrix}$
