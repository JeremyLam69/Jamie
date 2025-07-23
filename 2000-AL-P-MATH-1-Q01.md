## 2000-AL-P MATH 1 #01
Let P(n) be the statement that $\displaystyle M^{2n} = \begin{pmatrix}
1 & 0 & 0 \\
n [ \lambda (1+b)+\mu a ] & 1 & 0 \\
n [ \lambda c+\mu (1-b) ] & 0 & 1
\end{pmatrix}$ for all positive integers n.

When n = 1,

$\displaystyle M^{2} = \begin{pmatrix}
1 & 0 & 0 \\
\lambda & b & a \\
\mu & c & -b
\end{pmatrix} \begin{pmatrix}
1 & 0 & 0 \\
\lambda & b & a \\
\mu & c & -b
\end{pmatrix} =  \begin{pmatrix}
1 & 0 & 0 \\
\lambda + b \lambda + a \mu & b^2 + ac & ab-ab \\
\mu + c \lambda - b \mu & bc-bc & ac+b^2
\end{pmatrix}$

$\displaystyle \Rightarrow M^{2} = \begin{pmatrix}
1 & 0 & 0 \\
\lambda (1+b) + \mu a  & 1 & 0 \\
\lambda c + \mu (1 - b) & 0 & 1
\end{pmatrix} \ (\because b^2+ac=1)$

Therefore P(1) is true.

Assume that $P(k)$ is true for some positive integer $k \geq 1$. Then

$\displaystyle M^{2(k+1)} = M^{2k+2} = M^{2k} M^2 = \begin{pmatrix}
1 & 0 & 0 \\
k [ \lambda (1+b)+\mu a ] & 1 & 0 \\
k [ \lambda c+\mu (1-b) ] & 0 & 1
\end{pmatrix} \begin{pmatrix}
1 & 0 & 0 \\
\lambda (1+b) + \mu a  & 1 & 0 \\
\lambda c + \mu (1 - b) & 0 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow M^{2(k+1)} =  \begin{pmatrix}
1 & 0 & 0 \\
k [ \lambda (1+b)+\mu a ] + \lambda (1+b)+\mu a & 1 & 0 \\
k [ \lambda c+\mu (1-b) ] + \lambda c+\mu (1-b) & 1 & 0
\end{pmatrix}$

$\displaystyle \Rightarrow M^{2(k+1)} =  \begin{pmatrix}
1 & 0 & 0 \\
(k+1) [ \lambda (1+b)+\mu a ] & 1 & 0 \\
(k+1) [ \lambda c+\mu (1-b) ] & 1 & 0
\end{pmatrix}$

Therefore P(k+1) is true. By mathematical induction, P(n) is true for positive integers n.

-----
Let $\lambda = -2,\ \mu = 1,\ a = 2,\ b = 3,\ c = -4,\ n = 1000$ . Then

$\displaystyle \begin{pmatrix}
1 & 0 & 0 \\
-2 & 3 & 2 \\
1 & -4 & -3
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
1 & 0 & 0 \\
1000[-2(1+3)+2] & 1 & 0 \\
1000[(-2)(-4) + 1 - 3] & 0 & 1
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
1 & 0 & 0 \\
1000(-6) & 1 & 0 \\
1000(6) & 0 & 1
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
1 & 0 & 0 \\
-6000 & 1 & 0 \\
6000 & 0 & 1
\end{pmatrix}$