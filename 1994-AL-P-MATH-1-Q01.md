## 1994-AL-P MATH 1 #01
$\displaystyle P^{-1}AP = {1 \over 6} \begin{pmatrix}
1 & 4\\
-1 & 2
\end{pmatrix} \begin{pmatrix}
3 & 8\\
1 & 5
\end{pmatrix} \begin{pmatrix}
2 & -4\\
1 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow P^{-1}AP = {1 \over 6} \begin{pmatrix}
7 & 28\\
-1 & 2
\end{pmatrix} \begin{pmatrix}
2 & -4\\
1 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow P^{-1}AP = {1 \over 6} \begin{pmatrix}
42 & 0\\
0 & 6
\end{pmatrix}$

$\displaystyle \Rightarrow P^{-1}AP = \begin{pmatrix}
7 & 0\\
0 & 1
\end{pmatrix}$

Then, $\displaystyle (P^{-1}AP)^n = \begin{pmatrix}
7 & 0\\
0 & 1
\end{pmatrix}^n$

$\displaystyle \Rightarrow P^{-1}A^nP = \begin{pmatrix}
7^n & 0\\
0 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow A^n = P \begin{pmatrix}
7^n & 0\\
0 & 1
\end{pmatrix} P^{-1}$

$\displaystyle \Rightarrow A^n = \begin{pmatrix}
2 & -4\\
1 & 1
\end{pmatrix} \begin{pmatrix}
7^n & 0\\
0 & 1
\end{pmatrix} {1 \over 6} \begin{pmatrix}
1 & 4\\
-1 & 2
\end{pmatrix}$

$\displaystyle \Rightarrow A^n = {1 \over 6} \begin{pmatrix}
2 & -4\\
1 & 1
\end{pmatrix} \begin{pmatrix}
7^n & 0\\
0 & 1
\end{pmatrix} \begin{pmatrix}
1 & 4\\
-1 & 2
\end{pmatrix}$

$\displaystyle \Rightarrow A^n = {1 \over 6} \begin{pmatrix}
2 \cdot 7^n & -4\\
7^n & 1
\end{pmatrix} \begin{pmatrix}
1 & 4\\
-1 & 2
\end{pmatrix}$

$\displaystyle \Rightarrow A^n = {1 \over 6} \begin{pmatrix}
2 \cdot 7^n+4 & 8 \cdot 7^n-8\\
7^n-1 & 4 \cdot 7^n+2
\end{pmatrix}$
