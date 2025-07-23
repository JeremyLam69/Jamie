## 3(a)
(\*) has nontrivial solutions
$\Rightarrow \Delta = 0$

$\Rightarrow \begin{vmatrix}
\lambda & k & 0 \\
0 & -\lambda & 1 \\
1 & k & 1
 \end{vmatrix} = 0$

$\displaystyle \Rightarrow \lambda(-\lambda-k)-k(-1)=0$

$\displaystyle \Rightarrow -\lambda^2-k\lambda+k=0$

$\displaystyle \Rightarrow \lambda^2+k\lambda-k=0$

## 3(b)
Quadratic equations in $\lambda$ in (a) has equal roots
$\displaystyle \Rightarrow \sqrt{k^2+4k}=-\sqrt{k^2+4k}$
$\displaystyle \Rightarrow 2\sqrt{k^2+4k}=0$
$\displaystyle \Rightarrow k^2+4k=0$
$\displaystyle \Rightarrow k(k+4)=0$
$\displaystyle \Rightarrow k=0$ or $k=-4$
-----
When k=0,
$\displaystyle \Rightarrow \lambda^2=0$
$\displaystyle \Rightarrow \lambda=0$

$\displaystyle \Rightarrow (*) \begin{cases}
z = 0 \\
x + z = 0
\end{cases}$

$\Rightarrow$ Solution of (*) is : $\displaystyle\begin{cases}
x = 0 \\
y = t\ \in R \\
z = 0
\end{cases}$

-----
When k=-4,
$\displaystyle \Rightarrow \lambda^2 - 4\lambda +4=0$
$\displaystyle \Rightarrow (\lambda-2)^2=0$
$\displaystyle \Rightarrow \lambda=2$

$\displaystyle \Rightarrow (*) \begin{cases}
2x - 4y = 0 \\
-2y + z = 0 \\
x - 4y + z = 0
\end{cases}$

$\displaystyle \Rightarrow (*) \begin{cases}
x - 4y + z = 0 \\
2x - 4y = 0 \\
-2y + z = 0
\end{cases}$

Consider the augmented matrix

$\displaystyle  \left[ \begin{array}{ccc|c} 
1 & -4 & 1 & 0 \\
2 & -4 & 0 & 0 \\
0 & -2 & 1 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & -4 & 1 & 0 \\
1 & -2 & 0 & 0 \\
0 & -2 & 1 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & -4 & 1 & 0 \\
0 & 2 & -1 & 0 \\
0 & -2 & 1 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & -4 & 1 & 0 \\
0 & 2 & -1 & 0 \\
0 & 0 & 0 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & -4 & 1 & 0 \\
0 & 2 & -1 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 0 & -1 & 0 \\ 
0 & 1 & -{1 \over 2} & 0 
\end{array} \right]$

$\Rightarrow$ Solution of (\*) is $\displaystyle x = t,\ y= {1 \over 2}t,\ z=t \in R$