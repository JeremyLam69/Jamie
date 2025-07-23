## 3(a)
Consider : $\displaystyle \begin{pmatrix}
1 & 2 & 1 \\
1 & 1 & 2 \\
0 & -1 & q^2
\end{pmatrix}  \begin{pmatrix}
x \\
y \\
z
\end{pmatrix} =  \begin{pmatrix}
1 \\
2 \\
q
\end{pmatrix}$

$\displaystyle \Delta = \begin{vmatrix}
1 & 2 & 1 \\
1 & 1 & 2 \\
0 & -1 & q^2
\end{vmatrix}$

$= 1 \cdot 1 \cdot q^2 + 2 \cdot 2 \cdot 0 + 1 \cdot 1 \cdot (-1) - 1 \cdot 2 \cdot (-1) - 2 \cdot 1 \cdot q^2 - 1 \cdot 1 \cdot 0$
$= q^2 - 1 + 2 - 2q^2$
$= 1 - q^2$
$= (1-q)(1+q)$


$\displaystyle \Delta_x = \begin{vmatrix}
1 & 2 & 1 \\
2 & 1 & 2 \\
q & -1 & q^2
\end{vmatrix}$

$= 1 \cdot 1 \cdot q^2 + 2 \cdot 2 \cdot q + 1 \cdot 2 \cdot (-1) - 1 \cdot 2 \cdot (-1) - 2 \cdot 2 \cdot q^2 - 1 \cdot 1 \cdot q$
$= q^2 + 4q -2 + 2 - 4q^2 - q$
$= -3q^2 + 3q = -3q(q-1)$


$\displaystyle \Delta_y = \begin{vmatrix}
1 & 1 & 1 \\
1 & 2 & 2 \\
0 & q & q^2
\end{vmatrix}$

$= 1 \cdot 2 \cdot q^2 + 1 \cdot 2 \cdot 0 + 1 \cdot 1 \cdot q - 1 \cdot 2 \cdot q - 1 \cdot 1 \cdot q^2 - 1 \cdot 2 \cdot 0$
$= 2q^2 + q - 2q - q^2$
$= q^2 - q = q(q-1)$


$\displaystyle \Delta_z = \begin{vmatrix}
1 & 2 & 1 \\
1 & 1 & 2 \\
0 & -1 & q
\end{vmatrix}$

$= 1 \cdot 1 \cdot q + 2 \cdot 2 \cdot 0 + 1 \cdot 1 \cdot (-1) - 1 \cdot 2 \cdot (-1) - 2 \cdot 1 \cdot q - 1 \cdot 1 \cdot 0$
$= q - 1 + 2 - 2q$
$= -q + 1$

If the system has no solution
$\Rightarrow \Delta = 0$ and \[ $\Delta_x \neq 0$ or $\Delta_y \neq 0$ or $\Delta_z \neq 0$ ]
$\Rightarrow (1-q)(1+q)=0$ and \[ $-3q(q-1) \neq 0$ or $q(q-1) \neq 0$ or $-q + 1 \neq 0$   ]
$\Rightarrow (q = -1\ or\ q = 1)$ and \[ $(q \neq 0\ and\ q \neq 1)$ or $(q \neq 0\ and\ q \neq 1)$ or $q \neq 1$ ]  
$\Rightarrow q = -1$ 



## 3(b)
If the system has no solution
$\Rightarrow  \Delta =  \Delta_x =  \Delta_y =  \Delta_z = 0$
$\Rightarrow (1-q)(1+q)=0$ and $-3q(q-1)=0$ and $q(q-1)=0$ and $-q + 1=0$
$\Rightarrow (q=1\ or\ q=-1)$ and $(q=0\ or\ q=1)$ and $(q=0\ or\ q=1)$ and $q=1$
$\Rightarrow q = 1$