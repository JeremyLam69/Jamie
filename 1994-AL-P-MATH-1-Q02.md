$\Delta = \begin{vmatrix}
4-\lambda & 3 &1 \\
3 & -4-\lambda & 7 \\
1 & 7 & -6-\lambda
\end{vmatrix}$

$= (4-\lambda)(-4-\lambda)(-6-\lambda)+21+21-49(4-\lambda)-9(-6-\lambda)-(-4-\lambda)$
$= (4-\lambda)(4+\lambda)(6+\lambda)+42-49(4-\lambda)+9(6+\lambda)+(4+\lambda)$
$= (16-\lambda^2)(6+\lambda)+42-196+49\lambda+54+9\lambda+4+\lambda$
$= (-\lambda^3-6\lambda^2+16\lambda+96)-96+59\lambda$
$= -\lambda^3-6\lambda^2+75\lambda$
$= -\lambda(\lambda^2+6\lambda-75)$
$= -\lambda(\lambda+3+2\sqrt{21})(\lambda+3-2\sqrt{21})$ 

(\*) has nontrivial solutions
$\Rightarrow \Delta = 0$
$\Rightarrow -\lambda(\lambda+3+2\sqrt{21})(\lambda+3-2\sqrt{21})=0$ 
$\Rightarrow \lambda=0$ or $\lambda=-3-2\sqrt{21}$ or $\lambda=-3+2\sqrt{21}$
$\Rightarrow \lambda=0$ ($\because \lambda$ is an integer)

When $\lambda=0$, we have x + 7y - 6z = 0 and 3x - 4 + 7z = 0, 
Consider the augmented matrix :

$\left[ \begin{array}{ccc|c} 
1 & 7 & -6 & 0 \\ 
3 & -4 & 7 & 0
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 7 & -6 & 0 \\ 
0 & -25 & 25 & 0
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 7 & -6 & 0 \\ 
0 & 1 & -1 & 0
\end{array} \right]$

Therefore, the solution is,
y = t which is any real number
z = t 
x = 6z - 7y = -t