## 8(a)
$PM=MQ$ and $\begin{vmatrix} M \end{vmatrix} = 1$

$\displaystyle \Rightarrow \begin{pmatrix} 
-5 & -2 \\
15 & 6
\end{pmatrix} \begin{pmatrix} 
1 & a \\
b & c
\end{pmatrix} = \begin{pmatrix} 
1 & a \\
b & c
\end{pmatrix} \begin{pmatrix} 
1 & 0 \\
0 & 0
\end{pmatrix}$ and  $-ab+c = 1$

$\displaystyle \Rightarrow \begin{pmatrix} 
-2b-5 & -5a-2c \\
6b+15 & 15a+6c
\end{pmatrix} = \begin{pmatrix} 
1 & 0 \\
b & 0
\end{pmatrix}$ and  $-ab+c = 1$

$\displaystyle \Rightarrow a=-{22 \over 25}$ , $b=-3$ and $\displaystyle c={11 \over 5}$

## 8(b)(i)
$\displaystyle M = \begin{pmatrix} 
1 & a \\
b & c
\end{pmatrix} = \begin{pmatrix} 
1 & -{22 \over 25} \\
-3 & {11 \over 5}
\end{pmatrix} = {1 \over 25} \begin{pmatrix} 
25 & -22 \\
-75 & 55
\end{pmatrix}$

$\displaystyle M^{-1} = -{1 \over 11} \begin{pmatrix} 
55 & 22 \\
75 & 25
\end{pmatrix}$

$M^{-1}RM$

$\displaystyle = -{1 \over 11} \begin{pmatrix} 
55 & 22 \\
75 & 25
\end{pmatrix} \begin{pmatrix} 
6 & 2 \\
-15 & -5
\end{pmatrix} \cdot {1 \over 25} \begin{pmatrix} 
25 & -22 \\
-75 & 55
\end{pmatrix}$

$\displaystyle = -{1 \over 275} \begin{pmatrix} 
55 & 22 \\
75 & 25
\end{pmatrix} \begin{pmatrix} 
6 & 2 \\
-15 & -5
\end{pmatrix} \begin{pmatrix} 
25 & -22 \\
-75 & 55
\end{pmatrix}$

$\displaystyle = -{1 \over 275} \begin{pmatrix} 
0 & 0 \\
75 & 25
\end{pmatrix} \begin{pmatrix} 
25 & -22 \\
-75 & 55
\end{pmatrix}$

$\displaystyle = -{1 \over 275} \begin{pmatrix} 
0 & 0 \\
0 & -275
\end{pmatrix}$

$\displaystyle = \begin{pmatrix} 
0 & 0 \\
0 & 1
\end{pmatrix}$

## 8(b)(ii)
Now $PM = MQ$ and $M^{-1}RM = \begin{pmatrix} 
0 & 0 \\
0 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow P = MQM^{-1}$ and $\displaystyle R = M \begin{pmatrix} 
0 & 0 \\
0 & 1
\end{pmatrix} M^{-1}$

$\displaystyle \Rightarrow P = M \begin{pmatrix} 
1 & 0 \\
0 & 0
\end{pmatrix} M^{-1}$ and $\displaystyle R = M \begin{pmatrix} 
0 & 0 \\
0 & 1
\end{pmatrix} M^{-1}$

$\displaystyle \Rightarrow \alpha P = M \begin{pmatrix} 
\alpha & 0 \\
0 & 0
\end{pmatrix} M^{-1}$ and $\displaystyle \beta R = M \begin{pmatrix} 
0 & 0 \\
0 & \beta
\end{pmatrix} M^{-1}$

$\displaystyle \Rightarrow \alpha P + \beta R = M \begin{pmatrix} 
\alpha & 0 \\
0 & \beta
\end{pmatrix} M^{-1}$

$\displaystyle \Rightarrow (\alpha P + \beta R)^{99} = M \begin{pmatrix} 
\alpha^{99} & 0 \\
0 & \beta^{99}
\end{pmatrix} M^{-1}$

$\displaystyle \Rightarrow (\alpha P + \beta R)^{99} = M \begin{pmatrix} 
\alpha^{99} & 0 \\
0 & 0
\end{pmatrix} M^{-1} + M \begin{pmatrix} 
0 & 0 \\
0 & \beta^{99}
\end{pmatrix} M^{-1}$

$\displaystyle \Rightarrow (\alpha P + \beta R)^{99} = \alpha^{99} M \begin{pmatrix} 
1 & 0 \\
0 & 0
\end{pmatrix} M^{-1} + \beta^{99} M \begin{pmatrix} 
0 & 0 \\
0 & 1
\end{pmatrix} M^{-1}$

$\displaystyle \Rightarrow (\alpha P + \beta R)^{99} = \alpha^{99} P + \beta^{99} R$

