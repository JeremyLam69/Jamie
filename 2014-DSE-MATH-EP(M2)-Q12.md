## 12(a)(i)
$\displaystyle A^{-1} = {1 \over {1+p}} \begin{pmatrix}
1 & 1 \\
-p & 1
\end{pmatrix}^T = {1 \over {1+p}} \begin{pmatrix}
1 & -p \\
1 & 1
\end{pmatrix}$

## 12(a)(ii)
$\displaystyle A^{-1} M A$

$\displaystyle =  {1 \over {1+p}} \begin{pmatrix}
1 & -p \\
1 & 1
\end{pmatrix} \begin{pmatrix}
k-1 & k \\
1 & 0
\end{pmatrix} \begin{pmatrix}
1 & p \\
-1 & 1
\end{pmatrix}$

$\displaystyle =  {1 \over {1+p}} \begin{pmatrix}
k-1-p & k \\
k & k
\end{pmatrix} \begin{pmatrix}
1 & p \\
-1 & 1
\end{pmatrix}$

$\displaystyle =  {1 \over {1+p}} \begin{pmatrix}
-1-p & pk-p^2-p+k \\
0 & kp+k
\end{pmatrix}$

$\displaystyle =  {1 \over {1+p}} \begin{pmatrix}
-(1+p) & (1+p) (k-p) \\
0 & k(p+1)
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
-1 & k-p \\
0 & k
\end{pmatrix}$

## 12(a)(iii)
p = k
$\displaystyle \Rightarrow A = \begin{pmatrix}
1 & k \\
-1 & 1
\end{pmatrix}$ , $\displaystyle A^{-1} =  {1 \over {1+k}} \begin{pmatrix}
1 & -k \\
1 & 1
\end{pmatrix}$ and $\displaystyle A^{-1} M A =  \begin{pmatrix}
-1 & 0 \\
0 & k
\end{pmatrix}$

Then $M = A \begin{pmatrix}
-1 & 0 \\
0 & k
\end{pmatrix} A^{-1}$

$\displaystyle \Rightarrow M^n = A \begin{pmatrix}
-1 & 0 \\
0 & k
\end{pmatrix}^n A^{-1}$

$\displaystyle \Rightarrow M^n = A \begin{pmatrix}
(-1)^n & 0 \\
0 & k^n
\end{pmatrix} A^{-1}$

$\displaystyle \Rightarrow M^n ={1 \over {1+k}} \begin{pmatrix}
1 & k \\
-1 & 1
\end{pmatrix} \begin{pmatrix}
(-1)^n & 0 \\
0 & k^n
\end{pmatrix} \begin{pmatrix}
1 & -k \\
1 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow M^n ={1 \over {1+k}} \begin{pmatrix}
(-1)^n & k^{n+1} \\
(-1)^{n+1} & k^n
\end{pmatrix} \begin{pmatrix}
1 & -k \\
1 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow M^n ={1 \over {1+k}} \begin{pmatrix}
(-1)^n+k^{n+1} & (-1)^{n+1}k+ k^{n+1} \\
(-1)^{n+1}+k^n & (-1)^nk+k^n
\end{pmatrix}$

## 12(b)
Let k=2, then $M = \begin{pmatrix}
1 & 2 \\
1 & 0
\end{pmatrix}$

Now $\displaystyle \begin{pmatrix}
x_n \\
x_{n-1}
\end{pmatrix} = \begin{pmatrix}
1 & 2 \\
1 & 0
\end{pmatrix} \begin{pmatrix}
x_{n-1} \\
x_{n-2}
\end{pmatrix}$ for $n \geq 3$

$\displaystyle \Rightarrow \begin{pmatrix}
x_n \\
x_{n-1}
\end{pmatrix} = M^{n-2} \begin{pmatrix}
x_2 \\
x_1
\end{pmatrix}$ for $n \geq 3$

$\displaystyle \Rightarrow \begin{pmatrix}
x_n \\
x_{n-1}
\end{pmatrix} = {1 \over {1+k}} \begin{pmatrix}
(-1)^{n-2}+k^{n-1} & (-1)^{n-1}k+ k^{n-1} \\
(-1)^{n-1}+k^{n-2} & (-1)^{n-2}k+k^{n-2}
\end{pmatrix} \begin{pmatrix}
x_2 \\
x_1
\end{pmatrix}$ for $n \geq 3$

$\displaystyle \Rightarrow x_n ={1 \over {1+k}} [\ ((-1)^{n-2}+k^{n-1}) x_2 + ((-1)^{n-1}k+ k^{n-1}) x_1\ ]$ for $n \geq 3$

$\displaystyle \Rightarrow x_n = {1 \over 3}[\ ((-1)^{n-2}+2^{n-1}) (1)+ ((-1)^{n-1}2+ 2^{n-1}) (0)\ ]$ for $n \geq 3$

$\displaystyle \Rightarrow x_n = {1 \over 3} ((-1)^{n-2}+2^{n-1})$ for $n \geq 3$