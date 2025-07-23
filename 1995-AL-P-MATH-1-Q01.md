## 1995-AL-P MATH 1 #01(a)
Let $P(n)$ be the statement that $\displaystyle A^n = \begin{pmatrix}
a^n & {a^n - b^n} \over {a-b} \\
0 & b^n
\end{pmatrix}$ for all positive integers n

For n = 1, 
L.H.S = $A = \begin{pmatrix}
a & 1 \\
0 & b
\end{pmatrix}$
R.H.S = $\displaystyle \begin{pmatrix}
a^1 & {a^1 - b^1} \over {a-b} \\
0 & b^1
\end{pmatrix} = \begin{pmatrix}
a & 1 \\
0 & b
\end{pmatrix}$
$\Rightarrow$ L.H.S = R.H.S.
$\Rightarrow P(1)$ is true

Assume that $P(k)$ is true for some integer $k \geq 1$, then
$A^{k+1} = A^k A$
$\displaystyle \Rightarrow A^{k+1} = \begin{pmatrix}
a^k & {a^k - b^k} \over {a-b} \\
0 & b^k
\end{pmatrix}  \begin{pmatrix}
a & 1 \\
0 & b
\end{pmatrix}$

$\displaystyle \Rightarrow A^{k+1} = \begin{pmatrix}
a^{k+1} & a^k + { {a^k - b^k} \over {a-b}} \cdot b \\
0 & b^{k+1}
\end{pmatrix}$

$\displaystyle \Rightarrow A^{k+1} = \begin{pmatrix}
a^{k+1} & {a^k (a - b) + a^k \cdot b - b^{k+1} \over {a-b}} \\
0 & b^{k+1}
\end{pmatrix}$

$\displaystyle \Rightarrow A^{k+1} = \begin{pmatrix}
a^{k+1} & {a^{k+1} - a^k \cdot b + a^k \cdot b - b^{k+1} \over {a-b}} \\
0 & b^{k+1}
\end{pmatrix}$

$\displaystyle \Rightarrow A^{k+1} = \begin{pmatrix}
a^{k+1} & {a^{k+1} - b^{k+1} \over {a-b}} \\
0 & b^{k+1}
\end{pmatrix}$

$\displaystyle \Rightarrow P(k+1)$  is true
Therefore, $P(n)$ is true by mathematical induction.

## 1995-AL-P MATH 1 #01(b)
Let $a = {1 \over 2}$, and $b = {3 \over 2}$ 

Then $\displaystyle A = \begin{pmatrix}
{1 \over 2} & 1 \\
0 & {3 \over 2}
\end{pmatrix}$ and $\begin{pmatrix}
1 & 2 \\
0 & 3 
\end{pmatrix} = 2 A$

 $\displaystyle \Rightarrow \begin{pmatrix}
1 & 2 \\
0 & 3 
\end{pmatrix}^{95} = (2 A)^{95}$

 $\displaystyle \Rightarrow \begin{pmatrix}
1 & 2 \\
0 & 3 
\end{pmatrix}^{95} = 2^{95} \cdot A^{95}$

 $\displaystyle \Rightarrow \begin{pmatrix}
1 & 2 \\
0 & 3 
\end{pmatrix}^{95} = 2^{95} \cdot \begin{pmatrix}
({1 \over 2})^{95} & {({1 \over 2})^{95} - ({3 \over 2})^{95}} \over {{1 \over 2}-{3 \over 2}} \\
0 & ({3 \over 2})^{95}
\end{pmatrix}$

 $\displaystyle \Rightarrow \begin{pmatrix}
1 & 2 \\
0 & 3 
\end{pmatrix}^{95} = 2^{95} \cdot \begin{pmatrix}
{1 \over 2^{95}} & {3^{95} - 1 \over {2^{95}}} \\
0 & ({3 \over 2})^{95}
\end{pmatrix}$

 $\displaystyle \Rightarrow \begin{pmatrix}
1 & 2 \\
0 & 3 
\end{pmatrix}^{95} = \begin{pmatrix}
1 & 3^{95} - 1 \\
0 & 3^{95}
\end{pmatrix}$
