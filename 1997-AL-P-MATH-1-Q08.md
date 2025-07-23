## 8(a)
(S) has infinitely many solutions
$\Rightarrow \Delta = 0$

$\displaystyle \Rightarrow \begin{vmatrix}
a+1 & 2 & -2 \\
1 & a & 2 \\
3 & -1 & a-7
\end{vmatrix} = 0$

$\displaystyle \Rightarrow (a+1)[a(a-7)+2] -2(a-7-6) -2(-1-3a) = 0$
$\displaystyle \Rightarrow (a+1)(a^2-7a+2) -2a+26 +2+6a = 0$
$\displaystyle \Rightarrow a^3-7a^2+2a+a^2-7a+2 +4a+28= 0$
$\displaystyle \Rightarrow a^3-6a^2-a+30= 0$
$\displaystyle \Rightarrow (a+2)(a^2-8a+15)= 0$
$\displaystyle \Rightarrow (a+2)(a-3)(a-5)= 0$
$\displaystyle \Rightarrow a=-2$ or $a=3$ or $a=5$
-----
When a=-2,
(S) : $\begin{cases}
x - 2y + 2z = 0 \\
3x - y - 9z =0
\end{cases}$

Consider augmented matrix,
$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & -2 & 2 & 0 \\
3 & -1 & -9 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & -2 & 2 & 0 \\
0 & 5 & -15 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & -2 & 2 & 0 \\
0 & 1 & -3 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 0 & -4 & 0 \\
0 & 1 & -3 & 0
\end{array} \right]$

$\Rightarrow$ Solutions are $x=4t$, $y=3t$, $z=t \in R$

-----
When a=3,
(S) : $\begin{cases}
4x - 2y + 2z = 0 \\
x + 3y + 2z =0
\end{cases}$

Consider augmented matrix,
$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
4 & -2 & 2 & 0 \\
1 & 3 & 2 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
0 & -14 & -6 & 0 \\
1 & 3 & 2 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 3 & 2 & 0 \\
0 & 7 & 3 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 3 & 2 & 0 \\
0 & 1 & {3 \over 7} & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 0 & {5 \over 7} & 0 \\
0 & 1 & {3 \over 7} & 0
\end{array} \right]$

$\Rightarrow$ Solutions are $\displaystyle x=-{5 \over 7}t$, $\displaystyle y=-{3 \over 7}t$, $z=t \in R$

-----
When a=5,
(S) : $\begin{cases}
6x + 2y - 2z = 0 \\
x + 5y + 2z =0 \\
3x - y - 2z = 0
\end{cases}$

Consider augmented matrix,
$\displaystyle \left[ \begin{array}{ccc|c} 
6 & 2 & -2 & 0 \\
1 & 5 & 2 & 0 \\
3 & -1 & -2 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 5 & 2 & 0 \\
3 & -1 & -2 & 0 \\
6 & 2 & -2 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 5 & 2 & 0 \\
3 & -1 & -2 & 0 \\
3 & 1 & -1 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 5 & 2 & 0 \\
3 & -1 & -2 & 0 \\
0 & 2 & 1 & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 5 & 2 & 0 \\
0 & -16 & -8 & 0 \\
0 & 1 & {1 \over 2} & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 5 & 2 & 0 \\
0 & 2 & 1 & 0 \\
0 & 1 & {1 \over 2} & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 0 & -{1 \over 2} & 0 \\
0 & 0 & 0 & 0 \\
0 & 1 & {1 \over 2} & 0
\end{array} \right]$

$\displaystyle \Rightarrow  \left[ \begin{array}{ccc|c} 
1 & 0 & -{1 \over 2} & 0 \\
0 & 1 & {1 \over 2} & 0
\end{array} \right]$

$\Rightarrow$ Solutions are $\displaystyle x={1 \over 2}t$, $\displaystyle y=-{1 \over 2}t$, $z=t \in R$

## 8(b)
The smallest value of a is -2.
(T) : $\begin{cases}
-x + 2y - 2z = 6 \\
x - 2y + 2z =5b-1 \\
3x - y - 9z = 1-b
\end{cases}$

(T) is consistent.
$\Rightarrow \Delta_x = 0$ and $\Delta_y = 0$ and $\Delta_z = 0$

$\Rightarrow \begin{vmatrix} 
6 & 2 & -2 \\
5b-1 & -2 & 2 \\
1-b & -1 & -9
\end{vmatrix} = 0$ and $\begin{vmatrix} 
-1 & 6 & -2 \\
1 & 5b-1 & 2 \\
3 & 1-b & -9
\end{vmatrix} = 0$ and $\begin{vmatrix} 
-1 & 2 & 6 \\
1 & -2 & 5b-1 \\
3 & -1 & 1-b
\end{vmatrix} = 0$

$\Rightarrow 108+4(1-b)+2(5b-1)+12+18(5b-1)-4(1-b)=0$ and $9(5b-1)+36-2(1-b)+2(1-b)+54+6(5b-1) = 0$ and $2(1-b)+6(5b-1)-6-(5b-1)-2(1-b)+36=0$

$\Rightarrow 120+4-4b+10b-2+90b-18-4+4b=0$ and $45b-9+90-2+2b+2-2b+30b-6 = 0$ and $2-2b+30b-6-5b+1-2+2b+30=0$

$\Rightarrow 100+100b=0$ and $75b+75 = 0$ and $25b+25=0$

$\Rightarrow b = -1$

-----
When a = -2 , b = -1,
(T) : $\begin{cases}
-x + 2y - 2z = 6 \\
x - 2y + 2z =-6 \\
3x - y - 9z = 2
\end{cases}$

$\Rightarrow$ (T) : $\begin{cases}
x - 2y + 2z =-6 \\
3x - y - 9z = 2
\end{cases}$

Consider augmented matrix,
$\displaystyle \left[ \begin{array}{ccc|c} 
1 & -2 & 2 & -6 \\
3 & -1 & -9 & 2
\end{array} \right]$

$\displaystyle \Rightarrow \left[ \begin{array}{ccc|c} 
1 & -2 & 2 & -6 \\
0 & 5 & -15 & 20
\end{array} \right]$

$\displaystyle \Rightarrow \left[ \begin{array}{ccc|c} 
1 & -2 & 2 & -6 \\
0 & 1 & -3 & 4
\end{array} \right]$

$\displaystyle \Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & -4 & 2 \\
0 & 1 & -3 & 4
\end{array} \right]$

$\Rightarrow$ Solutions are $\displaystyle x=2+4t$, $\displaystyle y=4+3t$, $z=t \in R$

## 8(c)
Using result in (b), the solution of the top 3 equations are :
$x=2+4t$, $\displaystyle y=4+3t$, $z=\sqrt{t}$ where t is any non-negative real number

To satisfy the fourth equation ,
$3x - 4y - z = -11$
$\Rightarrow 3(2+4t) - 4(4+3t) - \sqrt{t} = -11$
$\Rightarrow 6+12t - 16 -12t - \sqrt{t} = -11$
$\Rightarrow \sqrt{t} = 1$
$\Rightarrow t = 1$
$\Rightarrow x=6,\ y=7,\ z = 1$