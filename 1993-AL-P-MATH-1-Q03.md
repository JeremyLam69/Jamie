## 1(a)
Consider augmented matrix of the system: 
$\left[ \begin{array}{ccc|c} 
a & b & c & 1 \\ 
b & c & a & 1 \\
c & a & b & 1 \\
1 & 1 & 1 & 3
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 1 & 3 \\
a & b & c & 1 \\ 
b & c & a & 1 \\
c & a & b & 1
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 1 & 3 \\
0 & b-a & c-a & 1-3a \\ 
0 & c-b & a-b & 1-3b \\
0 & a-c & b-c & 1-3c
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 1 & 3 \\
0 & b-a & c-a & 1-3a \\ 
0 & c-b & a-b & 1-3b \\
0 & b-c & b-a & 2-3a-3c
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 1 & 3 \\
0 & b-a & c-a & 1-3a \\ 
0 & c-b & a-b & 1-3b \\
0 & 0 & 0 & 3-3a-3b-3c
\end{array} \right]$

$\Rightarrow 3-3a-3b-3c = 0$
$\Rightarrow a+b+c = 1$

## 1(b)
Consider the augmented matrix and the fact that a+b+c=0
$\left[ \begin{array}{ccc|c} 
1 & 1 & 1 & 3 \\
0 & b-a & c-a & 1-3a \\ 
0 & c-b & a-b & 1-3b \\
0 & 0 & 0 & 3-3a-3b-3c
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 1 & 3 \\
0 & b-a & c-a & 1-3a \\ 
0 & c-b & a-b & 1-3b \\
0 & 0 & 0 & 0
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 1 & 3 \\
0 & b-a & c-a & 1-3a \\ 
0 & c-b & a-b & 1-3b
\end{array} \right]$

When the system (\*) has a unique solution,
$\displaystyle \Rightarrow \begin{vmatrix}
1 & 1 & 1 \\
0 & b-a & c-a \\ 
0 & c-b & a-b
\end{vmatrix} \neq 0$

$\displaystyle \Rightarrow (b-a)(a-b) - (c-a)(c-b) \neq 0$
$\displaystyle \Rightarrow -a^2-b^2+2ab - (c^2-bc-ac+ab) \neq 0$
$\displaystyle \Rightarrow -a^2-b^2+2ab - c^2+bc+ac-ab \neq 0$
$\displaystyle \Rightarrow -a^2 - b^2 - c^2 + bc + ac + ab \neq 0$

$\displaystyle \Rightarrow -{a^2 \over 2}-{a^2 \over 2} - {b^2 \over 2}- {b^2 \over 2} - {c^2 \over 2} - {c^2 \over 2} + bc + ac + ab \neq 0$

$\displaystyle \Rightarrow -{1 \over 2}(a^2+a^2+b^2+b^2+c^2+c^2- 2bc - 2ac - 2ab) \neq 0$

$\displaystyle \Rightarrow a^2- 2ab+b^2+a^2- 2ac+c^2+b^2- 2bc+c^2 \neq 0$
$\displaystyle \Rightarrow (a-b)^2+(a-c)^2+(b-c)^2 \neq 0$
$\displaystyle \Rightarrow a \neq b$ or $a \neq c$ or $b \neq c$
$\displaystyle \Rightarrow$ a , b and c are NOT all equal

On the other hand, when a , b and c are NOT all equal
$\displaystyle \Rightarrow a \neq b$ or $a \neq c$ or $b \neq c$
$\displaystyle \Rightarrow (a-b)^2+(a-c)^2+(b-c)^2 \neq 0$
$\displaystyle \Rightarrow -a^2 - b^2 - c^2 + bc + ac + ab \neq 0$
$\displaystyle \Rightarrow (b-a)(a-b) - (c-a)(c-b) \neq 0$

$\displaystyle \Rightarrow \begin{vmatrix}
1 & 1 & 1 \\
0 & b-a & c-a \\ 
0 & c-b & a-b
\end{vmatrix} \neq 0$

$\displaystyle \Rightarrow$ The system (\*) has a unique solution.

Hence the system (\*) has a unique solution if and only if a , b and c are NOT all equal.

## 1(c)
if a = b = c,
$\displaystyle \Rightarrow$ 3a = 1 (due to result (a) a+b+c=1)
$\displaystyle \Rightarrow$ a = b = c = $\displaystyle 1 \over 3$

The system (\*) has only one equation x + y + z = 3. Therefore, the solution is :
x = m which is any real number,
y = n which is any real number and
z = 3 - m - n