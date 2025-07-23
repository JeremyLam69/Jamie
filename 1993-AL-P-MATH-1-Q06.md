## 6(a)
$\displaystyle Let\ A = \begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{13} \\
\end{pmatrix}$

$A^T = -\ A$
$\displaystyle \Rightarrow A^T + A = 0$

$\displaystyle \Rightarrow \begin{pmatrix}
2a_{11} & a_{12}+a_{21} & a_{13}+a_{31} \\
a_{12}+a_{21} & 2a_{22} & a_{23}+a_{32} \\
a_{13}+a_{31} & a_{23}+a_{32} & 2a_{13} \\
\end{pmatrix} = 0$

$\displaystyle \Rightarrow a_{11} = 0,\ a_{22} = 0,\ a_{33} = 0,\ a_{12}=-a_{21},\ a_{13}=-a_{31},\ a_{23}=-a_{32}$

$\displaystyle \Rightarrow A = \begin{pmatrix}
0 & a_{12} & a_{13} \\
-a_{12} & 0 & a_{23} \\
-a_{13} & -a_{23} & 0 \\
\end{pmatrix}$

$\displaystyle \Rightarrow det\ A = 0\ \begin{vmatrix} 0 & a_{23} \\ -a_{23} & 0 \end{vmatrix}-a_{12} \begin{vmatrix} -a_{12} & a_{23} \\ -a_{13} & 0 \end{vmatrix} + a_{13} \begin{vmatrix} -a_{12} & 0 \\ -a_{13} & -a_{23} \end{vmatrix}$ 

$\displaystyle \Rightarrow det\ A = 0\ \cdot 0 - a_{12} \cdot a_{13} \cdot a_{23} + a_{12} \cdot a_{13} \cdot a_{23}$

$\displaystyle \Rightarrow det\ A = 0$

## 06(b)
$\displaystyle I - B =\ \begin{pmatrix}
1 & 0 & 0\\
0 & 1 & 0\\
0 & 0 & 1
\end{pmatrix} - \begin{pmatrix}
1 & -2 & 74\\
2 & 1 & -67\\
-74 & 67 & 1
\end{pmatrix}$

$\displaystyle \Rightarrow  I - B =\ \begin{pmatrix}
0 & -2 & 74\\
2 & 0 & -67\\
-74 & 67 & 0
\end{pmatrix}$

$\displaystyle \Rightarrow  (I - B)^T =\ \begin{pmatrix}
0 & 2 & -74\\
-2 & 0 & 67\\
74 & -67 & 0
\end{pmatrix} = - (I - B)$

$\displaystyle \Rightarrow det\ (I - B) = 0$

Also $I - B^4 = (I + B^2)(I - B^2) = (I + B^2)(I + B)(I - B)$
$\displaystyle \Rightarrow det\ (I - B^4) = det\ (I + B^2) \cdot det\ (I + B) \cdot det\ (I - B)$
$\displaystyle \Rightarrow det\ (I - B^4) = det\ (I + B^2) \cdot det\ (I + B) \cdot 0$
$\displaystyle \Rightarrow det\ (I - B^4) = 0$
