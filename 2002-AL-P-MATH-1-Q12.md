## 12(a)(i)
$A^3+A^2+A+I=0$
$\displaystyle \Rightarrow A(A^2+A+I)+I=0$ and $(A^2+A+I)A+I=0$
$\displaystyle \Rightarrow A(-A^2-A-I)=I$ and $(-A^2-A-I)A=I$
$\displaystyle \Rightarrow$ There exist $X = -A^2-A-I$ such that $AX = XA = I$
$\displaystyle \Rightarrow A^{-1}(equals\ X)$ exists

## 12(a)(ii)
$A^3+A^2+A+I=0$
$\displaystyle \Rightarrow A(A^3+A^2+A+I)=0$
$\displaystyle \Rightarrow A^4+A^3+A^2+A=0$
$\displaystyle \Rightarrow A^4=0-A^3-A^2-A$
$\displaystyle \Rightarrow A^4=(A^3+A^2+A+I)-A^3-A^2-A$
$\displaystyle \Rightarrow A^4=I$

## 12(a)(iii)
$A^3+A^2+A+I=0$
$\displaystyle \Rightarrow (A^{-1})^3(A^3+A^2+A+I)=0$
$\displaystyle \Rightarrow (A^{-1})^3A^3+(A^{-1})^3A^2+(A^{-1})^3A+(A^{-1})^3I=0$
$\displaystyle \Rightarrow (A^{-1})^3A^3+A^{-1}(A^{-1})^2A^2+(A^{-1})^2A^{-1}A+(A^{-1})^3=0$
$\displaystyle \Rightarrow (A^{-1}A)^3+A^{-1}(A^{-1}A)^2+(A^{-1})^2(A^{-1}A)+(A^{-1})^3=0$
$(\because A,\ A^{-1}$ are commutative i.e.$AA^{-1} = A^{-1}A)$
$\displaystyle \Rightarrow I+A^{-1}+(A^{-1})^2+(A^{-1})^3=0$
$\displaystyle \Rightarrow (A^{-1})^3+(A^{-1})^2+A^{-1}+I=0$

## 12(a)(iv)
Let $B = I$, then
$B^3+B^2+B^3+I$
$= I^3+I^2+I^3+I$
$= 4I \neq 0$

## 12(b)(i)
$X^2 = \begin{pmatrix}
1 & 1 & 1 \\
-1 & -1 & 0 \\
-1 & 0 & -1
\end{pmatrix}  \begin{pmatrix}
1 & 1 & 1 \\
-1 & -1 & 0 \\
-1 & 0 & -1
\end{pmatrix} = \begin{pmatrix}
-1 & 0 & 0 \\
0 & 0 & -1 \\
0 & -1 & 0
\end{pmatrix}$

$X^3 = X^2 X = \begin{pmatrix}
-1 & 0 & 0 \\
0 & 0 & -1 \\
0 & -1 & 0
\end{pmatrix} \begin{pmatrix}
1 & 1 & 1 \\
-1 & -1 & 0 \\
-1 & 0 & -1
\end{pmatrix} = \begin{pmatrix}
-1 & -1 & -1 \\
1 & 0 & 1 \\
1 & 1 & 0
\end{pmatrix}$

Therefore, 
$X^3+X^2+X+I = \begin{pmatrix}
-1 & -1 & -1 \\
1 & 0 & 1 \\
1 & 1 & 0
\end{pmatrix} +  \begin{pmatrix}
-1 & 0 & 0 \\
0 & 0 & -1 \\
0 & -1 & 0
\end{pmatrix} +  \begin{pmatrix}
1 & 1 & 1 \\
-1 & -1 & 0 \\
-1 & 0 & -1
\end{pmatrix} +  \begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix} = 0$

$\Rightarrow X^{-1} = -X^2-X-I$ (by (a)(i))

$\Rightarrow X^{-1} = X^3 = \begin{pmatrix}
-1 & -1 & -1 \\
1 & 0 & 1 \\
1 & 1 & 0
\end{pmatrix}$

## 12(b)(ii)
- For $n = 4k$ where k is an positive integer
	$X^n = X^{4k} = (X^4)^k = I$

- For $n = 4k-1$ where k is an positive integer
	$X^n = X^{4k-1} = X^{4k}X^{-1} = I X^3 = X^3 =  \begin{pmatrix}
-1 & -1 & -1 \\
1 & 0 & 1 \\
1 & 1 & 0
\end{pmatrix}$

- For $n = 4k-2$ where k is an positive integer
	$X^n = X^{4k-2} = X^{4k-1}X^{-1} = X^3 X^{-1} = X^2 =  \begin{pmatrix}
	-1 & 0 & 0 \\
	0 & 0 & -1 \\
	0 & -1 & 0
	\end{pmatrix}$

- For $n = 4k-3$ where k is an positive integer
	$X^n = X^{4k-3} = X^{4k-2}X^{-1} = X^2 X^{-1} = X =  \begin{pmatrix}
	1 & 1 & 1 \\
	-1 & -1 & 0 \\
	-1 & 0 & -1
	\end{pmatrix}$

## 12(b)(iii)
Let $Y = X^3$, then
$Y^3+Y^2+Y+I$
$= (X^3)^3+(X^3)^2+X^3+I$
$= X^9+X^6+X^3+I$
$= X^{12-3}+X^{8-2}+X^3+I$
$= X+X^2+X^3+I$
$= X^3+X^2+X+I$
$= 0$

Also, let $Z = -I$, then
$Z^3+Z^2+Z+I$
$=(-I)^3+(-I)^2-I+I$
$=-I+I-I+I$
$= 0$


