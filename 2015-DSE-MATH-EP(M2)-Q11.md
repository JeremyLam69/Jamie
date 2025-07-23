## 11(a)(i)
$\displaystyle M^2$
$\displaystyle = \begin{pmatrix}
\lambda & 1 \\
\lambda-\mu+1 & \mu
\end{pmatrix} \begin{pmatrix}
\lambda & 1 \\
\lambda-\mu+1 & \mu
\end{pmatrix}$

$\displaystyle = \begin{pmatrix}
\lambda^2+\lambda-\mu+1 & \lambda + \mu \\
(\lambda-\mu+1)(\lambda+\mu) & \mu^2+\lambda-\mu+1
\end{pmatrix}$

-----
$\displaystyle AB$
$\displaystyle = {1 \over {\lambda - \mu +2}}(I - \mu I + M) \cdot {1 \over {\lambda - \mu +2}}(I + \lambda I - M)$

$\displaystyle = {1 \over {(\lambda - \mu +2)^2}}(I - \mu I + M) (I + \lambda I - M)$

$\displaystyle = {1 \over {(\lambda - \mu +2)^2}}(\ (1-\mu)(1+\lambda)I + (\lambda + \mu)M - M^2\ )$

$\displaystyle = {1 \over {(\lambda - \mu +2)^2}}[\ (1-\mu)(1+\lambda)\begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix}+ (\lambda + \mu)\begin{pmatrix}
\lambda & 1 \\
\lambda-\mu+1 & \mu
\end{pmatrix} - \begin{pmatrix}
\lambda^2+\lambda-\mu+1 & \lambda + \mu \\
(\lambda-\mu+1)(\lambda+\mu) & \mu^2+\lambda-\mu+1
\end{pmatrix}\ ]$

$\displaystyle = {1 \over {(\lambda - \mu +2)^2}}[\ \begin{pmatrix}
(1-\mu)(1+\lambda) & 0 \\
0 & (1-\mu)(1+\lambda)
\end{pmatrix}+ \begin{pmatrix}
(\lambda + \mu)\lambda & (\lambda + \mu) \\
(\lambda + \mu)(\lambda-\mu+1) & \mu(\lambda + \mu)
\end{pmatrix} - \begin{pmatrix}
\lambda^2+\lambda-\mu+1 & \lambda + \mu \\
(\lambda-\mu+1)(\lambda+\mu) & \mu^2+\lambda-\mu+1
\end{pmatrix}\ ]$

$\displaystyle = {1 \over {(\lambda - \mu +2)^2}}[\ \begin{pmatrix}
1-\mu+\lambda+\lambda^2 & \lambda + \mu \\
(\lambda + \mu)(\lambda-\mu+1) & 1-\mu+\lambda+\mu^2
\end{pmatrix} - \begin{pmatrix}
\lambda^2+\lambda-\mu+1 & \lambda + \mu \\
(\lambda-\mu+1)(\lambda+\mu) & \mu^2+\lambda-\mu+1
\end{pmatrix}\ ]$

$= 0$

-----
$\displaystyle BA$
$\displaystyle = {1 \over {\lambda - \mu +2}}(I + \lambda I - M)\cdot {1 \over {\lambda - \mu +2}}(I - \mu I + M)$

$\displaystyle = {1 \over {(\lambda - \mu +2)^2}}(I + \lambda I - M) (I - \mu I + M)$

$\displaystyle = {1 \over {(\lambda - \mu +2)^2}}(\ (1-\mu)(1+\lambda)I + (\lambda + \mu)M - M^2\ )$

$= 0$

-----
$\displaystyle A + B$
$\displaystyle = {1 \over {\lambda - \mu +2}}(I - \mu I + M) + {1 \over {\lambda - \mu +2}}(I + \lambda I - M)$

$\displaystyle = {1 \over {\lambda - \mu +2}}(I - \mu I + M + I + \lambda I - M)$

$\displaystyle = {1 \over {\lambda - \mu +2}}(2 - \mu + \lambda) I$

$= I$

## 11(a)(ii)
$A + B = I$
$\Rightarrow (A+B)A = A$  and  $(A+B)B = B$
$\Rightarrow A^2+BA = A$  and  $AB+B^2 = B$
$\Rightarrow A^2+0 = A$  and  $0+B^2 = B$
$\Rightarrow A^2 = A$  and  $B^2 = B$

## 11(a)(iii)
Let P(n) be the statement that $M^n = (\lambda+1)^nA + (\mu-1)^n B$ for all positive integers n.

When n = 1, 
$(\lambda+1)^1 A + (\mu-1)^1 B$

$= (\lambda+1) A + (\mu-1) B$

$\displaystyle = (\lambda+1) {1 \over {\lambda - \mu +2}}(I - \mu I + M) + (\mu-1) {1 \over {\lambda - \mu +2}}(I + \lambda I - M)$

$\displaystyle =  {1 \over {\lambda - \mu +2}}[\ (\lambda+1)(I - \mu I + M) + (\mu-1)(I + \lambda I - M)\ ]$

$\displaystyle =  {1 \over {\lambda - \mu +2}}[\ (\lambda+1)(1-\mu)I + (\lambda+1)M + (\mu-1)(1+\lambda)I - (\mu-1)M)\ ]$

$\displaystyle =  {1 \over {\lambda - \mu +2}}(\lambda-\mu+2)M$

$= M$
Therefore P(1) is true.

Assume P(k) is true for some positive integer $k \geq 1$. Then,
$M^{k+1} = M^k \cdot M$
$= [\ (\lambda+1)^k A + (\mu-1)^k B\ ] [\ (\lambda+1) A + (\mu-1) B\ ]$
$= (\lambda+1)^{k+1} A^2 + (\lambda+1)^k(\mu-1)AB + (\mu-1)^k(\lambda+1) BA + (\mu-1)^{k+1} B^2$
$= (\lambda+1)^{k+1} A^2 + (\lambda+1)^k(\mu-1)(0) + (\mu-1)^k(\lambda+1)(0) + (\mu-1)^{k+1} B^2$
$= (\lambda+1)^{k+1} A^2 + (\mu-1)^{k+1} B^2$
$= (\lambda+1)^{k+1} A + (\mu-1)^{k+1} B$
Therefore P(k+1) is true. By mathematical induction P(n) is true.

## 11(b)
Let $\lambda = 2$ , $\mu = 3$ such that $\mu-\lambda=1\neq 2$. Then,
$\displaystyle M = \begin{pmatrix}
2 & 1 \\
0 & 3
\end{pmatrix}$ , $\displaystyle A = M - 2I = \begin{pmatrix}
0 & 1 \\
0 & 1
\end{pmatrix}$ and $\displaystyle B = 3I - M = \begin{pmatrix}
1 & -1 \\
0 & 0
\end{pmatrix}$

Therefore,
$\displaystyle \begin{pmatrix}
4 & 2 \\
0 & 6
\end{pmatrix}^{315}$

$\displaystyle = (2 \begin{pmatrix}
2 & 1 \\
0 & 3
\end{pmatrix})^{315}$

$\displaystyle = 2^{315} M^{315}$

$\displaystyle = 2^{315}( 3^{315}A + 2^{315}B )$

$\displaystyle = 2^{315}(\ (3^{315}-2^{315})A + 2^{315}A +3^{315}B\ )$

$\displaystyle = 2^{315}(\ (3^{315}-2^{315})A + 2^{315}(A+B)\ )$

$\displaystyle = 2^{315}(\ (3^{315}-2^{315})A + 2^{315}I\ )$

$\displaystyle = 2^{315} \begin{pmatrix}
2^{315} & 3^{315}-2^{315} \\
0 & 3^{315}
\end{pmatrix}$