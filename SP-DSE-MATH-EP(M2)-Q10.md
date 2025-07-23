## 10(a)
Let P(n) be the statement that
$\displaystyle A^n = \begin{pmatrix}
cos\ n\theta & -sin\ n\theta \\
sin\ n\theta & cos\ n\theta
\end{pmatrix}$ for all positive integers n.

When n = 1,
$\displaystyle A^1 = A = \begin{pmatrix}
cos\ \theta & -sin\ \theta \\
sin\ \theta & cos\ \theta
\end{pmatrix} = \begin{pmatrix}
cos\ 1\theta & -sin\ 1\theta \\
sin\ 1\theta & cos\ 1\theta
\end{pmatrix}$
Therefore, P(1) is true.

Assume P(k) is true for some positive integer $k \geq 1$, then
$\displaystyle A^{k+1} = A^k A$

$\displaystyle = \begin{pmatrix}
cos\ k\theta & -sin\ k\theta \\
sin\ k\theta & cos\ k\theta
\end{pmatrix} \begin{pmatrix}
cos\ \theta & -sin\ \theta \\
sin\ \theta & cos\ \theta
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
cos\ k\theta \ cos\ \theta -sin\ k\theta \ sin\ \theta & -cos\ k\theta \ sin\ \theta -sin\ k\theta \ cos\ \theta \\
sin\ k\theta \ cos\ \theta + cos\ k\theta \ sin\ \theta & -sin\ k\theta \ sin\ \theta + cos\ k\theta \ cos\ \theta
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
cos\ (k\theta + \theta) & -sin\ (\theta + k\theta) \\
sin\ (k\theta + \theta) & cos\ (k\theta + \theta)
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
cos\ (k+1) \theta & -sin\ (k+1) \theta \\
sin\ (k+1)\theta & cos\ (k+1) \theta
\end{pmatrix}$

Therefore, P(k+1) is true. By mathematical induction P(n) is true.

## 10(b)
$sin\ 3\theta + sin\ 2\theta + sin \theta = 0$
$\displaystyle \Rightarrow 2sin({{3\theta + \theta} \over 2}) cos({{3\theta - \theta} \over 2}) + sin 2\theta = 0$
$\displaystyle \Rightarrow 2sin\ 2\theta \ cos \theta + sin 2\theta = 0$
$\displaystyle \Rightarrow sin\ 2\theta \ (2\ cos \theta + 1) = 0$
$\displaystyle \Rightarrow sin\ 2\theta = 0$ or $\displaystyle cos\ \theta = - {1 \over 2}$
$\displaystyle \Rightarrow \theta = {\pi \over 2}$ or $\displaystyle \theta = {2\pi \over 3}$

## 10(c)
$\displaystyle A^3 + A^2 + A = \begin{pmatrix}
a & 0\\
0 & a
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
cos\ 3\theta & -sin\ 3\theta \\
sin\ 3\theta & cos\ 3\theta
\end{pmatrix} + \begin{pmatrix}
cos\ 2\theta & -sin\ 2\theta \\
sin\ 2\theta & cos\ 2\theta
\end{pmatrix} + \begin{pmatrix}
cos\ \theta & -sin\ \theta \\
sin\ \theta & cos\ \theta
\end{pmatrix} = \begin{pmatrix}
a & 0\\
0 & a
\end{pmatrix}$

$\displaystyle \Rightarrow \begin{pmatrix}
cos\ 3\theta + cos\ 2\theta + cos\ \theta & -sin\ 3\theta - sin\ 2\theta - sin\ \theta \\
sin\ 3\theta + sin\ 2\theta + sin\ \theta & cos\ 3\theta + cos\ 2\theta + cos\ \theta
\end{pmatrix} = \begin{pmatrix}
a & 0\\
0 & a
\end{pmatrix}$

$\displaystyle \Rightarrow cos\ 3\theta + cos\ 2\theta + cos\ \theta = a$ and $\displaystyle sin\ 3\theta + sin\ 2\theta + sin\ \theta =0$
$\displaystyle \Rightarrow cos\ 3\theta + cos\ 2\theta + cos\ \theta = a$ and ($\displaystyle \theta ={\pi \over 2}$ or $\displaystyle \theta ={2\pi \over 3}$)
$\displaystyle \Rightarrow a = cos\ 3{\pi \over 2} + cos\ 2{\pi \over 2} + cos\ {\pi \over 2}$ or $\displaystyle cos\ 3{2\pi \over 3} + cos\ 2{2\pi \over 3} + cos\ {2\pi \over 3}$
$\displaystyle \Rightarrow a = 0 - 1 + 0$ or $= 1 - {1 \over 2} - {1 \over 2}$
$\displaystyle \Rightarrow a = -1$ or $0$