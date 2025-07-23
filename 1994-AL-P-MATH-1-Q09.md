## 9(a)(i)
If (I) has a unique solution
$\Rightarrow$ This unique solution is the trivial solution (x, y, z) = (0, 0, 0)
$\Rightarrow$ The trivial solution (x, y, z) = (0, 0, 0) is the unique solution of (I)

Also, (II) is a particular case of (I) where z=1
$\Rightarrow$ (II) has NO solution otherwise (I) has a non-trivial solution where z=1.

## 9(a)(ii)
**(1) When (u, v) is a solution of (II)**
$\Rightarrow \begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33} \\
\end{pmatrix} \begin{pmatrix}
u \\
v \\
1 \\
\end{pmatrix} =  \begin{pmatrix}
0 \\
0 \\
0 \\
\end{pmatrix}$ 

$\Rightarrow t \begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33} \\
\end{pmatrix} \begin{pmatrix}
u \\
v \\
1 \\
\end{pmatrix} =  \begin{pmatrix}
0 \\
0 \\
0 \\
\end{pmatrix}$ for any real number t

$\Rightarrow \begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33} \\
\end{pmatrix} \begin{pmatrix}
ut \\
vt \\
t \\
\end{pmatrix} =  \begin{pmatrix}
0 \\
0 \\
0 \\
\end{pmatrix}$ for any real number t

$\Rightarrow$ (ut, vt, t) are solutions of (I) for any real number t.

**(2) When (ut, vt, t) are solutions of (I) for any real number t,**

$\Rightarrow \begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33} \\
\end{pmatrix} \begin{pmatrix}
ut \\
vt \\
t \\
\end{pmatrix} =  \begin{pmatrix}
0 \\
0 \\
0 \\
\end{pmatrix}$

$\Rightarrow t \begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33} \\
\end{pmatrix} \begin{pmatrix}
u \\
v \\
1 \\
\end{pmatrix} =  \begin{pmatrix}
0 \\
0 \\
0 \\
\end{pmatrix}$

$\Rightarrow \begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33} \\
\end{pmatrix} \begin{pmatrix}
u \\
v \\
1 \\
\end{pmatrix} =  \begin{pmatrix}
0 \\
0 \\
0 \\
\end{pmatrix}$ ($\because$ t can be any real number otherwise t must be 0 only)

$\Rightarrow$ (u, v) is a solution of (II)

From results (1) and (2), (u, v) is a solution of (II) if and only if (ut, vt, t) are solutions of (I) for all real number t.

## 9(a)(iii)
Let (u, v, w) be a non-trivial solution of (I).

$\Rightarrow$ w must be 0 otherwise ($\displaystyle {u \over w},\ {v \over w},\ 1$) is a solution of (I) and (II)  has a solution ($\displaystyle {u \over w},\ {v \over w}$)

(I) becomes :
$a_{11}x + a_{21}y = 0\ --- L1$
$a_{21}x + a_{22}y = 0\ --- L2$
$a_{31}x + a_{32}y = 0\ --- L3$

They are equations of 3 lines which must all represent the same single line otherwise they intercept at only (0,0) and does NOT have non-trivial solutions.

Therefore, the solutions of (I) is actually the solutions of any L1 or L2 or L3.

## 9(b)(i)
For (III),
$\Delta = \begin{vmatrix}
-(3+k) & 1 & -1 \\
-7 & 5-k & -z \\
-6 & 6 & k-2
\end{vmatrix}$

$= -(3+k)(5-k)(k-2) + 1(-1)(-6) + (-1)(-7)(6) + (3+k)(-1)(6) - (1)(-7)(k-2) + (5-k)(-6)$
$= (k+3)(k-5)(k-2) + 6 + 42 - 6(k+3) + 7(k-2) + 6(k-5)$
$= (k+3)(k^2-7k+10) + 48 - 6k - 18 + 7k - 14 + 6k - 30$
$=(k^3 -7k^2 +10k + 3k^2 - 21k +30) - 14 + 7k$
$= k^3 -4k^2 - 4k + 16$
$= k^2(k-4) - 4(k -4)$
$= (k^2-4)(k-4)$
$= (k+2)(k-2)(k-4)$

When (III) has non-trivial solutions, $\Delta = 0$
$\Rightarrow (k+2)(k-2)(k-4)=0$
$\Rightarrow k=-2$ or $k=2$ or $k=4$

**When k = -2**, (III) becomes:
-x + y - z =0
-7x + 7y - z = 0
-6x + 6y - 4z = 0

Consider the augmented Matrix 
$\left[ \begin{array}{ccc|c} 
-1 & 1 & -1 & 0 \\ 
-7 & 7 & -1 & 0 \\
-6 & 6 & -4 & 0
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & -1 & 1 & 0 \\ 
-7 & 7 & -1 & 0 \\
-6 & 6 & -4 & 0
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & -1 & 1 & 0 \\ 
0 & 0 & 6 & 0 \\
0 & 0 & 2 & 0
\end{array} \right]$

$\Rightarrow x=y$ and $z=0$

$\Rightarrow$ the solution is $(t,t,0)$ for any $t \in R$


**When k = 2**, (III) becomes:
-5x + y - z =0
-7x + 3y - z = 0
-6x + 6y = 0

$\Rightarrow x=y$ and $\displaystyle x= -{z \over 4}$

$\Rightarrow$ the solution is $\displaystyle (t,\ t,\ -4t)$ for any $t \in R$

**When k = 4**, (III) becomes:
-7x + y - z = 0
-3x + 3y + z = 0

$\displaystyle \Rightarrow y={5 \over 2}x$ and $\displaystyle z= -{9 \over 2}x$

$\Rightarrow$ the solution is $\displaystyle (t,\ {5 \over 2}t,\ -{9 \over 2}t)$ for any $t \in R$

## 9(b)(ii)
Note that (IV) is a particular case of (III) where z=1.

When (IV) is consistent,
$\Rightarrow$ the solutions of (IV) are also solutions of (III) where z=1
$\Rightarrow$ ( k=2 when $\displaystyle t=-{1 \over 4}$ ) or ( k=4 when $\displaystyle t=-{2 \over 9}$ )
$\Rightarrow$ ( k=2 and solution is $\displaystyle x=-{1 \over 4},\ y=-{1 \over 4}$ ) or ( k=4 and solution is $\displaystyle x=-{2 \over 9},\ y=-{5 \over 9}$ )

## 9(b)(iii)
According to results in 9(a)(i),

**When k = -2**, the solution is $(t,t,0)$ for any $t \in R$
**When k = 2**, the solution is $\displaystyle (t,\ t,\ -4t)$ for any $t \in R$
**When k = 4**, the solution is $\displaystyle (t,\ {5 \over 2}t,\ -{9 \over 2}t)$ for any $t \in R$
