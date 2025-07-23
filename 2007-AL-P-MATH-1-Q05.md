## 5(a)
$M^2 = \lambda M + \mu I$
$\displaystyle \Rightarrow P^{-1}Q^2P = \lambda P^{-1}QP + \mu I$
$\displaystyle \Rightarrow P^{-1}Q^2P = \lambda P^{-1}QP + \mu P^{-1}IP$
$\displaystyle \Rightarrow P^{-1}Q^2P = P^{-1}(\lambda Q)P + P^{-1}(\mu I)P$
$\displaystyle \Rightarrow P^{-1}Q^2P = P^{-1}(\lambda Q + \mu I)P$
$\displaystyle \Rightarrow Q^2 = \lambda Q + \mu I$

$\displaystyle \Rightarrow \begin{pmatrix}
\alpha^2 & 0 \\
0 & \beta^2
\end{pmatrix} = \begin{pmatrix}
\lambda \alpha + \mu & 0 \\
0 & \lambda \beta + \mu
\end{pmatrix}$

$\displaystyle \Rightarrow \alpha^2 = \lambda \alpha + \mu$ and $\beta^2 = \lambda \beta + \mu$
$\displaystyle \Rightarrow \lambda = \alpha + \beta$ and $\mu = -\alpha \beta$

## 5(b)
$det\ M = det (P^{-1}QP)$
$= (det\ P^{-1}) (det\ Q) (det\ P)$
$= (det\ Q)(det\ P^{-1})(det\ P)$
$= det\ Q$
$= \alpha \beta$

Now, $det\ (M^2 + \alpha \beta I)$
$= det\ (\lambda M + \mu I + \alpha \beta I)$
$= det\ ((\alpha + \beta) M -\alpha \beta I + \alpha \beta I)$
$= det\ ((\alpha + \beta) M)$
$= (\alpha + \beta)^2 det\ M$ $(\because M$ is 2x2)
$= (\alpha + \beta)^2 \alpha \beta$
