## 9(a)
Consider augmented matrix of the system: 

$\left[ \begin{array}{ccc|c} 
1 & 2 & -1 & 3 \\ 
1 & 1 & 2 & 4
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 2 & -1 & 3 \\ 
0 & -1 & 3 & 1
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 2 & -1 & 3 \\ 
0 & 1 & -3 & -1
\end{array} \right]$

$\Rightarrow x=-5t+5, y=3t-1, z=t$ for any $t \in R$

## 9(b)
xy + yz + zx = 2
$\Rightarrow (-5t+5)(3t-1) + (3t-1)t + t(-5t+5) = 2$
$\Rightarrow -15t^2 + 20t - 5 + 3t^2 - t - 5t^2 + 5t = 2$
$\Rightarrow -17t^2 + 24t - 7 = 0$
$\Rightarrow 17t^2 - 24t + 7 = 0$
$\Rightarrow (17t-7)(t-1) = 0$
$\displaystyle \Rightarrow t={7 \over 17}$ or $t=1$

$\displaystyle \Rightarrow x = {50 \over 17},\ y={4 \over 17},\ z={7 \over 17}$
or 
$\displaystyle x = 0,\ y=2,\ z=1$

## 9(c)
$\Delta = \begin{vmatrix}
1 & 2 & -1 \\
1 & 1 & 2 \\
a & 1 & 1
\end{vmatrix} = 1 + 4a -1 - 2 - 2 + a = 5a-4$

$\Delta_x = \begin{vmatrix}
3 & 2 & -1 \\
4 & 1 & 2 \\
\lambda & 1 & 1
\end{vmatrix} = 3 + 4\lambda - 4 - 6 - 8 + \lambda = 5\lambda - 15$

$\Delta_y = \begin{vmatrix}
1 & 3 & -1 \\
1 & 4 & 2 \\
a & \lambda & 1
\end{vmatrix} = 4 + 6a - \lambda - 2\lambda - 3 + 4a = 10a - 3\lambda + 1$

$\Delta_z = \begin{vmatrix}
1 & 2 & 3 \\
1 & 1 & 4 \\
a & 1 & \lambda
\end{vmatrix} = \lambda + 8a + 3 - 4 - 2\lambda - 3a = 5a - \lambda -1$

When the system is solvable,
**Case 1** : it has unique solution, then
$\Delta \neq 0$ and $\lambda$ is any real number

$\Rightarrow 5a-4 \neq 0$ and $\lambda$ is any real number

$\displaystyle \Rightarrow a \neq {4 \over 5}$ and $\lambda$ is any real number

**Case 2** : it has infinitely many solutions, then
$\Delta = 0$ and $\Delta_x = 0$ and $\Delta_y = 0$ and $\Delta_z = 0$

$\displaystyle \Rightarrow a = {4 \over 5}$ and $5\lambda - 15 = 0$ and $10a - 3\lambda + 1 = 0$ and $5a - \lambda -1 = 0$

$\displaystyle \Rightarrow a = {4 \over 5}$ and $\lambda = 3$

## 9(d)
**Case 1** : $\displaystyle a \neq {4 \over 5}$ and $\lambda$ is any real number and  $\displaystyle x = {50 \over 17},\ y={4 \over 17},\ z={7 \over 17}$

$\displaystyle \Rightarrow ax + y + z = \lambda$ and $\displaystyle a \neq {4 \over 5}$

$\displaystyle \Rightarrow a \cdot {50 \over 17} + {4 \over 17} + {7 \over 17} = \lambda$ and $\displaystyle a \neq {4 \over 5}$

$\displaystyle \Rightarrow a \cdot {50 \over 17} = \lambda - {4 \over 17} - {7 \over 17}$ and $\displaystyle a \neq {4 \over 5}$

$\displaystyle \Rightarrow a = {{17\lambda - 11} \over 50}$ and $\displaystyle a \neq {4 \over 5}$

$\displaystyle \Rightarrow a = {{17\lambda - 11} \over 50}$ and $\displaystyle {{17\lambda - 11} \over 50} \neq {4 \over 5}$

$\displaystyle \Rightarrow a = {{17\lambda - 11} \over 50}$ and $\displaystyle 17\lambda - 11 \neq 40$

$\displaystyle \Rightarrow a = {{17\lambda - 11} \over 50}$ and $\displaystyle \lambda \neq {51 \over 17} = 3$

Therefore, $\displaystyle a = {{17\lambda - 11} \over 50}$ and $\displaystyle \lambda \neq 3$ and $\displaystyle x = {50 \over 17},\ y={4 \over 17},\ z={7 \over 17}$ fulfill ALL the four equations.

-----
**Case 2** : $\displaystyle a \neq {4 \over 5}$ and $\lambda$ is any real number and $\displaystyle x = 0,\ y=2,\ z=1$

$\displaystyle \Rightarrow ax + y + z = \lambda$ and $\displaystyle a \neq {4 \over 5}$

$\displaystyle \Rightarrow a(0) + 2 + 1 = \lambda$ and $\displaystyle a \neq {4 \over 5}$

$\displaystyle \Rightarrow \lambda = 3$ and $\displaystyle a \neq {4 \over 5}$

Therefore $\displaystyle a \neq {4 \over 5}$ and $\lambda = 3$ and $x = 0,\ y=2,\ z=1$ fulfil ALL the four equations.

-----
**Case 3** : $\displaystyle a = {4 \over 5}$ and $\lambda = 3$  and  $\displaystyle x = {50 \over 17},\ y={4 \over 17},\ z={7 \over 17}$

Then $\displaystyle ax + y + z$

$\displaystyle = {4 \over 5} \cdot {50 \over 17} + {4 \over 17} + {7 \over 17}$

$\displaystyle = {{40+4+7} \over 17}$

$\displaystyle = {51 \over 17}$

$\displaystyle = 3 = \lambda$

Therefore, $\displaystyle a = {4 \over 5}$ and $\lambda = 3$  and  $\displaystyle x = {50 \over 17},\ y={4 \over 17},\ z={7 \over 17}$ fulfil ALL the four equations

-----
**Case 4** : $\displaystyle a = {4 \over 5}$ and $\lambda = 3$  and $\displaystyle x = 0,\ y=2,\ z=1$

Then $\displaystyle ax + y + z$

$\displaystyle = {4 \over 5} \cdot (0) + 2 + 1$

$\displaystyle = 3 = \lambda$

Therefore, $\displaystyle a = {4 \over 5}$ and $\lambda = 3$  and $\displaystyle x = 0,\ y=2,\ z=1$ fulfil ALL the four equations

-----
Hence, 
when $\lambda \neq 3$, $\displaystyle a = {{17\lambda - 11} \over 50}$ (case 1)
when $\lambda = 3,\ a$ can be any real numbers. (cases 2,3,4)