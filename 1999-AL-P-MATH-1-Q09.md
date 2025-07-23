## 9(a)
Let P(n) be the statement that $\displaystyle (A + B)^n = A^n + B^n$ for any positive integer n

When n = 1,
L.H.S. = $(A + B)^1 = A + B$
R.H.S. = $A^1 + B^1 = A + B$
$\displaystyle \Rightarrow$ L.H.S. = R.H.S.
Therefore P(1) is true. 

Assume P(k) is true for some integer k $\geq$ 1, then,
$(A + B)^{k+1} = (A + B)^k (A + B)$
$\displaystyle \Rightarrow (A + B)^{k+1} = (A^k + B^k) (A + B)$
$\displaystyle \Rightarrow (A + B)^{k+1} = A^{k+1} + A^k B + B^k A + B^{k+1}$ 
$\displaystyle \Rightarrow (A + B)^{k+1} = A^{k+1} + A^{k-1} A B + B^{k-1} B A + B^{k+1}$ 
$\displaystyle \Rightarrow (A + B)^{k+1} = A^{k+1} + A^{k-1} 0 + B^{k-1} 0 + B^{k+1}$ 
$\displaystyle \Rightarrow (A + B)^{k+1} = A^{k+1} + B^{k+1}$
Therefore, P(k+1) is true.

By mathematical induction, P(n) is true

## 9(b)

^680885

Note that :
$\displaystyle AB = \begin{pmatrix}
a & b \\
0 & 0
\end{pmatrix} \begin{pmatrix}
p & q \\
r & s
\end{pmatrix} = \begin{pmatrix}
ap+br & aq+bs \\
0 & 0
\end{pmatrix}$ and

$\displaystyle BA = \begin{pmatrix}
p & q \\
r & s
\end{pmatrix} \begin{pmatrix}
a & b \\
0 & 0
\end{pmatrix} = \begin{pmatrix}
ap & bp \\
ar & br
\end{pmatrix}$

if $\displaystyle AB =0$ and $BA = 0$
$\displaystyle \Rightarrow \begin{pmatrix}
ap+br & aq+bs \\
0 & 0
\end{pmatrix} = \begin{pmatrix}
0 & 0 \\
0 & 0
\end{pmatrix}$ and $\begin{pmatrix}
ap & bp \\
ar & br
\end{pmatrix} = \begin{pmatrix}
0 & 0 \\
0 & 0
\end{pmatrix}$

$\Rightarrow$ aq+bs=0 and ap=0 and ar=0
$\Rightarrow$ aq+bs=0 and p=0 and r=0 ($\because a \neq 0$)

On the other hand, if aq+bs=0 and p=0 and r=0,

$\displaystyle \Rightarrow AB = \begin{pmatrix}
ap+br & aq+bs \\
0 & 0
\end{pmatrix} = \begin{pmatrix}
a \cdot 0+b \cdot 0 & 0 \\
0 & 0
\end{pmatrix} = \begin{pmatrix}
0 & 0 \\
0 & 0
\end{pmatrix}$ and $\displaystyle BA = \begin{pmatrix}
ap & bp \\
ar & br
\end{pmatrix} = \begin{pmatrix}
a \cdot 0 & b \cdot 0 \\
a \cdot 0 & b \cdot 0
\end{pmatrix} = \begin{pmatrix}
0 & 0 \\
0 & 0
\end{pmatrix}$

$\displaystyle \Rightarrow AB = BA = 0$

## 9(c)
Let a = x , $\displaystyle b = {xy \over {x-z}}$ , p = r = 0 , $\displaystyle q = -{yz \over {x-z}}$ and s = z so that 
$\displaystyle aq + bs = x \cdot  (-{yz \over {x-z}}) + {xy \over {x-z}} \cdot z = 0$ and 
$\displaystyle b + q = {xy \over {x-z}} -{yz \over {x-z}} = {y(x-z) \over {x-z}} = y$

Now let

$\displaystyle D = \begin{pmatrix}
a & b \\
0 & 0
\end{pmatrix}$ and $\displaystyle E = \begin{pmatrix}
0 & q \\
0 & s
\end{pmatrix}$

$\displaystyle \Rightarrow D = \begin{pmatrix}
x & {xy \over {x-z}} \\
0 & 0
\end{pmatrix}$ and $\displaystyle E = \begin{pmatrix}
0 & -{yz \over {x-z}} \\
0 & z
\end{pmatrix}$

$\displaystyle \Rightarrow C = D+ E$ and $DE = ED = 0$ (by 9(b))

## 9(d)
Let x=2, y=5, z=1, and also let

$C = \begin{pmatrix}
2 & 5 \\
0 & 1
\end{pmatrix},\ D =  \begin{pmatrix}
2 & 10 \\
0 & 0
\end{pmatrix},\ E =  \begin{pmatrix}
0 & -5 \\
0 & 1
\end{pmatrix}$ so that C = D + E and DE=ED=0

$\displaystyle \Rightarrow \begin{pmatrix}
2 & 5 \\
0 & 1
\end{pmatrix}^n = C^n = (D + E)^n$

$\displaystyle \Rightarrow \begin{pmatrix}
2 & 5 \\
0 & 1
\end{pmatrix}^n = (D + E)^n = D^n + E^n$ (by 9(a))

$\displaystyle \Rightarrow \begin{pmatrix}
2 & 5 \\
0 & 1
\end{pmatrix}^n =  \begin{pmatrix}
2 & 10 \\
0 & 0
\end{pmatrix}^n +  \begin{pmatrix}
0 & -5 \\
0 & 1
\end{pmatrix}^n$

$\displaystyle \Rightarrow \begin{pmatrix}
2 & 5 \\
0 & 1
\end{pmatrix}^n =  \begin{pmatrix}
2^n & 5 \cdot 2^n \\
0 & 0
\end{pmatrix} +  \begin{pmatrix}
0 & -5 \\
0 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
2 & 5 \\
0 & 1
\end{pmatrix}^n =  \begin{pmatrix}
2^n & 5 \cdot (2^n - 1) \\
0 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
2 & 5 \\
0 & 1
\end{pmatrix}^{99} =  \begin{pmatrix}
2^{99} & 5 \cdot (2^{99} - 1) \\
0 & 1
\end{pmatrix}$
