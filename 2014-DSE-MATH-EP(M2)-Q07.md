## 7(a)
Let P(n) be the statement that $A^{n+1} = 2^n A$ for all positive integer $n$.

When n=1, $\displaystyle A^2$
$\displaystyle = \begin{pmatrix}
1 & 0 & 1 \\
0 & 2 & 0 \\
1 & 0 & 1
\end{pmatrix} \begin{pmatrix}
1 & 0 & 1 \\
0 & 2 & 0 \\
1 & 0 & 1
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
2 & 0 & 2 \\
0 & 4 & 0 \\
2 & 0 & 2
\end{pmatrix}$

$\displaystyle = 2 \begin{pmatrix}
1 & 0 & 1 \\
0 & 2 & 0 \\
1 & 0 & 1
\end{pmatrix} = 2 A$

Therefore P(1) is true.

Assume that P(k) is true for some positive integer $k \geq 1$. Then
$\displaystyle A^{k+1}$
$\displaystyle = A^k A$
$\displaystyle = 2^k A A$
$\displaystyle = 2^k A^2$
$\displaystyle = 2^k \cdot 2A$
$\displaystyle = 2^{k+1} A$
P(k+1) is true. Therefore by mathematical induction, P(n) is true.

## 7(b)
Consider
$\displaystyle \begin{vmatrix} A \end{vmatrix} = \begin{vmatrix} 
1 & 0 & 1 \\
0 & 2 & 0 \\
1 & 0 & 1
\end{vmatrix} = 2 - 2 = 0$

$\displaystyle \Rightarrow A^{-1}$ does NOT exist.
$\displaystyle \Rightarrow A^2 A^{-1} = 2A A^{-1}$ is invalid.
$\displaystyle \Rightarrow A = 2I$ is invalid.