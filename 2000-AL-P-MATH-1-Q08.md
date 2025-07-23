## 8(a)
(S) has an unique solution.
$\Rightarrow \Delta \neq 0$

$\displaystyle \Rightarrow \begin{vmatrix}
1 & -1 & -1 \\
2 & \lambda & -2 \\
1 & 2 \lambda + 3 & \lambda^2
\end{vmatrix} \neq 0$

$\displaystyle \Rightarrow \lambda^3+2(2\lambda+3)+2\lambda^2+2-2(2\lambda+3)+\lambda \neq 0$
$\displaystyle \Rightarrow \lambda^3+2\lambda^2+\lambda+2 \neq 0$
$\displaystyle \Rightarrow (\lambda^2+1)(\lambda+2) \neq 0$
$\displaystyle \Rightarrow \lambda+2 \neq 0$
$\displaystyle \Rightarrow \lambda \neq -2$

On the other hand, 
$\displaystyle \lambda \neq -2$
$\Rightarrow \Delta = (\lambda^2+1)(\lambda+2) \neq 0$
$\Rightarrow$ (S) has an unique solution.

Hence, (S) has an unique solution if and only if $\displaystyle \lambda \neq -2$.

-----
When $\lambda = -1$, then

$\Delta = (\lambda^2+1)(\lambda+2)$ and  $\Delta_x = \begin{vmatrix}
a & -1 & -1 \\
b & \lambda & -2 \\
c & 2 \lambda + 3 & \lambda^2
\end{vmatrix}$ and $\Delta_y = \begin{vmatrix}
1 & a & -1 \\
2 & b & -2 \\
1 & c + 3 & \lambda^2
\end{vmatrix}$ and $\Delta_z = \begin{vmatrix}
1 & -1 & a \\
2 & \lambda & b \\
1 & 2 \lambda + 3 & c
\end{vmatrix}$

$\displaystyle \Rightarrow \Delta = 2$ and $\Delta_x = \begin{vmatrix}
a & -1 & -1 \\
b & -1 & -2 \\
c & 1 & 1
\end{vmatrix}$ and $\Delta_y = \begin{vmatrix}
1 & a & -1 \\
2 & b & -2 \\
1 & c + 3 & 1
\end{vmatrix}$ and $\Delta_z = \begin{vmatrix}
1 & -1 & a \\
2 & -1 & b \\
1 & 1 & c
\end{vmatrix}$

$\displaystyle \Rightarrow \Delta = 2$ and $\Delta_x = a + c$ and $\Delta_y = -4a + 2b$ and $\Delta_z = 3a - 2b + c$

$\displaystyle \Rightarrow x = {\Delta_x \over \Delta}$ and $\displaystyle y = {\Delta_y \over \Delta}$ and $\displaystyle z = {\Delta_z \over \Delta}$

$\displaystyle \Rightarrow x = {{a + c} \over 2}$ and $\displaystyle y = {{-4a + 2b} \over 2}$ and $\displaystyle z = {{3a - 2b + c} \over 2}$

$\displaystyle \Rightarrow x = {{a + c} \over 2}$ and $\displaystyle y = -2a + b$ and $\displaystyle z = {{3a - 2b + c} \over 2}$

## 8(b)(i)
When $\lambda=-2$ (i.e. $\Delta=0$) and (S) has infinitely many solutions
$\Rightarrow \Delta_x = \Delta_y = \Delta_z = 0$

$\Rightarrow \begin{vmatrix}
a & -1 & -1 \\
b & \lambda & -2 \\
c & 2 \lambda + 3 & \lambda^2
\end{vmatrix} = 0$ and $\begin{vmatrix}
1 & a & -1 \\
2 & b & -2 \\
1 & c + 3 & \lambda^2
\end{vmatrix}=0$ and $\begin{vmatrix}
1 & -1 & a \\
2 & \lambda & b \\
1 & 2 \lambda + 3 & c
\end{vmatrix}= 0$

$\Rightarrow \begin{vmatrix}
a & -1 & -1 \\
b & -2 & -2 \\
c & -1 & 4
\end{vmatrix} = 0$ and $\begin{vmatrix}
1 & a & -1 \\
2 & b & -2 \\
1 & c + 3 & 4
\end{vmatrix}=0$ and $\begin{vmatrix}
1 & -1 & a \\
2 & -2 & b \\
1 & -1 & c
\end{vmatrix}= 0$

$\Rightarrow -10a+5b = 0$ and $-10a+5b=0$ and $0= 0$
$\Rightarrow -10a+5b = 0$
$\Rightarrow b = 2a$

## 8(b)(ii)
When $\lambda=-2$, a=-1, b=-2, c=3 (<span style="color:red"> c = -3 is wrong</span> )
(S) $\begin{cases}
x - y - z = -1 \\
2x -2y - 2z = -2 \\
x -y + 4z = 3
\end{cases}$

$\Rightarrow$ (S) $\begin{cases}
x - y - z = -1 \\
x -y + 4z = 3
\end{cases}$

$\Rightarrow$ (S) $\begin{cases}
x - y - z = -1 \\
5z = 4
\end{cases}$

$\Rightarrow$ (S) $\displaystyle \begin{cases}
\displaystyle x - y = -{1 \over 5} \\
\displaystyle z = {4 \over 5}
\end{cases}$

$\Rightarrow$ The solutions are $\displaystyle x = t - {1 \over 5}$, $y = t \in R$, $\displaystyle z = {4 \over 5}$

## 8(c)
(T) $\begin{cases}
x - y - z + 3\mu - 5 = 0 \\
2x -2y - 2z + 2\mu - 2 = 0 \\
x -y + 4z - \mu - 1 = 0
\end{cases}$

$\Rightarrow$ (T) $\begin{cases}
x - y - z  = 5-3\mu \\
2x -2y - 2z = 2-2\mu \\
x -y + 4z = \mu + 1
\end{cases}$

(T) is equivalent to (S) where $\lambda = -2$, $a =  5-3\mu$, $b = 2-2\mu$ and $c = \mu + 1$

According to (b)(i), (T) is consistent when
$b = 2a$
$\Rightarrow 2-2\mu = 2(5-3\mu)$
$\Rightarrow \mu = 2$
$\Rightarrow a =  5-3\mu$, $b = 2-2\mu$ and $c = \mu + 1$
$\Rightarrow a =  -1$, $b = -2$ and $c = 3$
According (b)(ii), the solutions are $\displaystyle x = t - {1 \over 5}$, $y = t \in R$, $\displaystyle z = {4 \over 5}$

On the other hand, when $\mu \neq 2$, (T) is inconsistent.