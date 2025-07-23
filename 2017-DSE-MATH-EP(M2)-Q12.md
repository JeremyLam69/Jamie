## 12(a)
Let P(n) be the statement that $\displaystyle A^n = 3^n I + 3^{n-1} n \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix}$ for all positive integers n.

When n = 1,
R.H.S.
$\displaystyle = 3^n I + 3^{n-1} n \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix}$

$\displaystyle = 3 I + \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix}$

$\displaystyle = \begin{pmatrix}
3 & 1 \\ 
0 & 3 \end{pmatrix}$
$\displaystyle = A = A^1 = L.H.S.$
Therefore, P(1) is true.

Assume P(k) is true for some positive integer $k \geq 1$. Then
$\displaystyle A^{k+1}$
$\displaystyle = A^k A$
$\displaystyle = [\ 3^k I + 3^{k-1} k \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix}]\ A$

$\displaystyle = 3^k A + 3^{k-1} k \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix} A$

$\displaystyle = \ 3^k \begin{pmatrix}
3 & 1 \\ 
0 & 3 \end{pmatrix} + 3^{k-1} k \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix} \begin{pmatrix}
3 & 1 \\ 
0 & 3 \end{pmatrix}$

$\displaystyle = 3^k \begin{pmatrix}
3 & 1 \\ 
0 & 3 \end{pmatrix} + 3^{k-1} k \begin{pmatrix}
0 & 3 \\ 
0 & 0 \end{pmatrix}$

$\displaystyle = 3^k \begin{pmatrix}
3 & 0 \\ 
0 & 3 \end{pmatrix} + 3^k \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix} + 3^{k-1} k \begin{pmatrix}
0 & 3 \\ 
0 & 0 \end{pmatrix}$

$\displaystyle = 3^{k+1} \begin{pmatrix}
1 & 0 \\ 
0 & 1 \end{pmatrix} + 3^k \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix} + 3^k k \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix}$

$\displaystyle = 3^{k+1} I + 3^k \begin{pmatrix}
0 & k+1 \\ 
0 & 0 \end{pmatrix}$

$\displaystyle = 3^{k+1} I + 3^k (k+1) \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix}$

$\displaystyle = 3^{k+1} I + 3^{(k+1)-1} (k+1) \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix}$
Therefore, P(k+1) is true and by mathematical induction P(n) is true.

## 12(b)(i)
$\displaystyle P^{-1} B P$
$\displaystyle = P^{-1} \begin{pmatrix}
5 & 1 \\ 
-4 & 1 \end{pmatrix} \begin{pmatrix}
-1 & 0 \\ 
2 & -1 \end{pmatrix}$

$\displaystyle = P^{-1} \begin{pmatrix}
-3 & -1 \\ 
6 & -1 \end{pmatrix}$

$\displaystyle = \begin{pmatrix}
-1 & 0 \\ 
-2 & -1 \end{pmatrix} \begin{pmatrix}
-3 & -1 \\ 
6 & -1 \end{pmatrix}$

$\displaystyle = \begin{pmatrix}
3 & 1 \\ 
0 & 3 \end{pmatrix}$

$= A$

## 12(b)(ii)
$\displaystyle P^{-1} B P = A$
$\displaystyle \Rightarrow B = PAP^{-1}$
$\displaystyle \Rightarrow B^n = PA^nP^{-1}$
$\displaystyle \Rightarrow B^n = P\ [\ 3^n I + 3^{n-1} n \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix}\ ]\ P^{-1}$

$\displaystyle \Rightarrow B^n = PA^nP^{-1}$

$\displaystyle \Rightarrow B^n = 3^n PIP^{-1} + 3^{n-1} n P \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix}\ P^{-1}$

$\displaystyle \Rightarrow B^n = 3^n I + 3^{n-1} n \begin{pmatrix}
-1 & 0 \\ 
2 & -1 \end{pmatrix} \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix} \begin{pmatrix}
-1 & 0 \\ 
-2 & -1 \end{pmatrix}$

$\displaystyle \Rightarrow B^n = 3^n I + 3^{n-1} n \begin{pmatrix}
0 & -1 \\ 
0 & 2 \end{pmatrix} \begin{pmatrix}
-1 & 0 \\ 
-2 & -1 \end{pmatrix}$

$\displaystyle \Rightarrow B^n = 3^n I + 3^{n-1} n \begin{pmatrix}
2 & 1 \\ 
-4 & -2 \end{pmatrix}$

## 12(b)(iii)
For all positive integers m, $A^m - B^m$

$\displaystyle = 3^m I + 3^{m-1} m \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix} - 3^m I - 3^{m-1} m \begin{pmatrix}
2 & 1 \\ 
-4 & -2 \end{pmatrix}$

$\displaystyle = 3^{m-1} m\ [ \begin{pmatrix}
0 & 1 \\ 
0 & 0 \end{pmatrix} -  \begin{pmatrix}
2 & 1 \\ 
-4 & -2 \end{pmatrix}\ ]$

$\displaystyle = 3^{m-1} m\begin{pmatrix}
-2 & 0 \\ 
4 & 2 \end{pmatrix}$

Therefore,
$\displaystyle \begin{vmatrix} A^m - B^m \end{vmatrix}$

$\displaystyle = (3^{m-1} m)^2\begin{vmatrix}
-2 & 0 \\ 
4 & 2 \end{vmatrix}$

$\displaystyle = -4 \cdot (3^{m-1}m)^2$

$\displaystyle = -4 \cdot 3^{2m-2}m^2$

$\displaystyle = -3^{2m-2}(4m^2) < 0 < 4m^2$

Therefore, $\begin{vmatrix} A^m - B^m \end{vmatrix} \neq 4m^2$