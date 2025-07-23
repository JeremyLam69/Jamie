## 5(a)
$cos(x+1)+cos(x-1)=k\ cos\ x$

$\displaystyle \Rightarrow 2\ cos({ {(x+1)+(x-1)} \over 2})\ cos({ {(x+1)-(x-1)} \over 2}) = k\ cos\ x$
$\displaystyle \Rightarrow 2\ cos\ x\ cos(1) = k\ cos\ x$
$\displaystyle \Rightarrow k = 2\ cos(1)$

## 5(b)
Consider following determinant for any real numbers $a_1,\ a_2,\ b_1,\ b_2,\ c_1,\ c_2$

$\begin{vmatrix}
a_1 & a_1+a_2 & a_2 \\
b_1 & b_1+b_2 & b_2 \\
c_1 & c_1+c_2 & c_2
\end{vmatrix}$

$= a_1(b_1+b_2)c_2 + (a_1+a_2)b_2c_1 + a_2b_1(c_1+c_2) - a_1b_2(c_1+c_2) - (a_1+a_2)b_1c_2-a_2(b_1+b_2)c_1$

$= a_1b_1c_2 + a_1b_2c_2 + a_1b_2c_1 + a_2b_2c_1 + a_2b_1c_1 + a_2b_1c_2 - a_1b_2c_1 - a_1b_2c_2 - a_1b_1c_2 - a_2b_1c_2 - a_2b_1c_1 - a_2b_2c_1$

$= a_1b_1c_2 - a_1b_1c_2 + a_1b_2c_2 - a_1b_2c_2 + a_1b_2c_1 - a_1b_2c_1 + a_2b_2c_1 - a_2b_2c_1 + a_2b_1c_1 - a_2b_1c_1 + a_2b_1c_2 - a_2b_1c_2$

$=0$

Also, from 5(a), we have 

$\displaystyle cos\ 2 = {{cos\ 3 + cos\ 1} \over k}$ , $\displaystyle cos\ 5 = {{cos\ 6 + cos\ 4} \over k}$ and $\displaystyle cos\ 8 = {{cos\ 9 + cos\ 7} \over k}$

Therefore,

$\displaystyle \begin{vmatrix}
cos\ 1 & cos\ 2 & cos\ 3 \\
cos\ 4 & cos\ 5 & cos\ 6 \\
cos\ 7 &  cos\ 8 & cos\ 9
\end{vmatrix} = {1 \over k} \begin{vmatrix}
cos\ 1 & cos\ 1 + cos\ 3 & cos\ 3 \\
cos\ 4 & cos\ 4 + cos\ 6 & cos\ 6 \\
cos\ 7 &  cos\ 7 + cos\ 9 & cos\ 9
\end{vmatrix} = 0$