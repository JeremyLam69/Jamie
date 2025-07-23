## 13(a)(i)
$\displaystyle MN = \begin{pmatrix}
a & b \\
c & d
\end{pmatrix} \begin{pmatrix}
e & f \\
g & h
\end{pmatrix} = \begin{pmatrix}
ae+bg & af+bh \\
ce+dg & cf+dh
\end{pmatrix}$

$\displaystyle \Rightarrow tr(MN) = ae+bg+cf+dh$

Also $\displaystyle NM = \begin{pmatrix}
e & f \\
g & h
\end{pmatrix} \begin{pmatrix}
a & b \\
c & d
\end{pmatrix}= \begin{pmatrix}
ae+cf & be+df \\
ag+ch & bg+dh
\end{pmatrix}$

$\displaystyle \Rightarrow tr(NM) = ae+bg+cf+dh$

Therefore $tr(MN) = tr(NM)$

## 13(a)(ii)
$\displaystyle B A B^{-1} = \begin{pmatrix}
1 & 0 \\
0 & 3
\end{pmatrix}$

$\displaystyle \Rightarrow A = B^{-1} \begin{pmatrix}
1 & 0 \\
0 & 3
\end{pmatrix} B$

$\displaystyle \Rightarrow tr(A) = tr( B^{-1} \begin{pmatrix}
1 & 0 \\
0 & 3
\end{pmatrix} B )$

$\displaystyle \Rightarrow tr(A) = tr( B B^{-1} \begin{pmatrix}
1 & 0 \\
0 & 3
\end{pmatrix} )$

$\displaystyle \Rightarrow tr(A) = tr( I \begin{pmatrix}
1 & 0 \\
0 & 3
\end{pmatrix} )$

$\displaystyle \Rightarrow tr(A) = tr( \begin{pmatrix}
1 & 0 \\
0 & 3
\end{pmatrix} )$

$\displaystyle \Rightarrow tr(A) = 1+3 = 4$

## 13(a)(iii)
$\displaystyle B A B^{-1} = \begin{pmatrix}
1 & 0 \\
0 & 3
\end{pmatrix}$

$\displaystyle \Rightarrow A = B^{-1} \begin{pmatrix}
1 & 0 \\
0 & 3
\end{pmatrix} B$

$\displaystyle \Rightarrow \begin{vmatrix} A \end{vmatrix} = \begin{vmatrix} B^{-1} \begin{pmatrix}
1 & 0 \\
0 & 3
\end{pmatrix} B \end{vmatrix}$

$\displaystyle \Rightarrow \begin{vmatrix} A \end{vmatrix} = \begin{vmatrix} B^{-1} \end{vmatrix} \begin{vmatrix}
1 & 0 \\
0 & 3
\end{vmatrix} \begin{vmatrix} B \end{vmatrix}$

$\displaystyle \Rightarrow \begin{vmatrix} A \end{vmatrix} = \begin{vmatrix} B \end{vmatrix} \begin{vmatrix} B^{-1} \end{vmatrix} \begin{vmatrix}
1 & 0 \\
0 & 3
\end{vmatrix}$

$\displaystyle \Rightarrow \begin{vmatrix} A \end{vmatrix} = \begin{vmatrix}
1 & 0 \\
0 & 3
\end{vmatrix} = 3$

## 13(b)(i)
$\displaystyle C \begin{pmatrix}  
x \\
y
\end{pmatrix} = \lambda_1 \begin{pmatrix}  
x \\
y
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
p & q \\
r & s
\end{pmatrix} \begin{pmatrix}  
x \\
y
\end{pmatrix} = \lambda_1 \begin{pmatrix}  
x \\
y
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
px + qy \\
rx + sy
\end{pmatrix} = \begin{pmatrix}  
\lambda_1 x \\
\lambda_1 y
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
(p-\lambda_1)x + qy \\
rx + (s-\lambda_1)y
\end{pmatrix} = \begin{pmatrix}  
0 \\
0 
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
(p-\lambda_1) & q \\
r & (s-\lambda_1)
\end{pmatrix} \begin{pmatrix}  
x \\
y
\end{pmatrix}= \begin{pmatrix}  
0 \\
0 
\end{pmatrix}$

Since $\begin{pmatrix}  
x \\
y
\end{pmatrix}$ is non-zero. Consider $\begin{pmatrix}  
kx \\
ky
\end{pmatrix} \neq \begin{pmatrix}  
x \\
y
\end{pmatrix}$ for any $k \neq 0$. Then

$\displaystyle \begin{pmatrix}
(p-\lambda_1) & q \\
r & (s-\lambda_1)
\end{pmatrix} \begin{pmatrix}  
kx \\
ky
\end{pmatrix} = k \begin{pmatrix}
(p-\lambda_1) & q \\
r & (s-\lambda_1)
\end{pmatrix} \begin{pmatrix}  
x \\
y
\end{pmatrix}= \begin{pmatrix}  
0 \\
0 
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
(p-\lambda_1) & q \\
r & (s-\lambda_1)
\end{pmatrix} \begin{pmatrix}  
x \\
y
\end{pmatrix}= \begin{pmatrix}  
0 \\
0 
\end{pmatrix}$ has infinitely many solutions.

Hence $\displaystyle \begin{vmatrix}
(p-\lambda_1) & q \\
r & (s-\lambda_1)
\end{vmatrix} = 0$ 

Similarly,
$\displaystyle C \begin{pmatrix}  
x \\
y
\end{pmatrix} = \lambda_2 \begin{pmatrix}  
x \\
y
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
(p-\lambda_2) & q \\
r & (s-\lambda_2)
\end{pmatrix} \begin{pmatrix}  
x \\
y
\end{pmatrix}= \begin{pmatrix}  
0 \\
0 
\end{pmatrix}$ which has infinitely many solutions $k \begin{pmatrix}  
x \\
y
\end{pmatrix}$ for any $k \neq 0$

Hence $\displaystyle \begin{vmatrix}
(p-\lambda_2) & q \\
r & (s-\lambda_2)
\end{vmatrix} = 0$ 

## 13(b)(ii)
Now $\displaystyle \begin{vmatrix}
(p-\lambda_1) & q \\
r & (s-\lambda_1)
\end{vmatrix} = 0$ and $\displaystyle \begin{vmatrix}
(p-\lambda_2) & q \\
r & (s-\lambda_2)
\end{vmatrix} = 0$

$\displaystyle \Rightarrow (p-\lambda_1)(s-\lambda_1)-qr =0$ and $(p-\lambda_2)(s-\lambda_2)-qr =0$

$\displaystyle \Rightarrow \lambda_1^2 - (p+s) \lambda_1 + ps-qr =0$ and $\lambda_2^2 - (p+s) \lambda_2 + ps-qr =0$

$\displaystyle \Rightarrow \lambda_1^2 - tr(C) \cdot \lambda_1 + \begin{vmatrix} C \end{vmatrix}  =0$ and $\lambda_2^2 - tr(C) \cdot \lambda_2 + \begin{vmatrix} C \end{vmatrix} =0$

$\displaystyle \Rightarrow \lambda_1$ , $\lambda_2$ are roots of $\lambda^2 - tr(C) \cdot \lambda + \begin{vmatrix} C \end{vmatrix} =0$

## 13(c)
Now let C = A. Then
tr(C) = tr(A) = 4 and $\begin{vmatrix} C \end{vmatrix}=\begin{vmatrix} A \end{vmatrix}=3$

The two values of $\lambda$ are the roots of $\lambda^2 - tr(C) \cdot \lambda + \begin{vmatrix} C \end{vmatrix} =0$ or $\lambda^2 - 4 \lambda + 3 =0$

Now, $\lambda^2 - 4 \lambda + 3 =0$
$\Rightarrow (\lambda - 1) (\lambda - 3) =0$
$\Rightarrow \lambda = 1$ or $\lambda = 3$