## 2(a)
Let P(n) be the statement that $\displaystyle 1^3+2^3+3^3+\cdots+n^3={1 \over 4} n^2 (n+1)^2$ for any positive integer n.

When n=1,
L.H.S. $= 1^3 = 1$
R.H.S. $\displaystyle = {1 \over 4} 1^2 (1+1)^2 = {1 \over 4} (4)=1$
L.H.S. = R.H.S., therefore, P(1) is true.

Assume that P(k) is true for an positive integer $k \geq 1$. 
When n = k+1,
$\displaystyle 1^3+2^3+3^3+\cdots+k^3+(k+1)^3$
$\displaystyle = {1 \over 4} k^2 (k+1)^2+(k+1)^3$
$\displaystyle = (k+1)^2 [\ {1 \over 4} k^2 + (k+1)\ ]$
$\displaystyle = {1 \over 4} (k+1)^2 [\  k^2 + 4k + 4)\ ]$
$\displaystyle = {1 \over 4} (k+1)^2 (k+2)^2$
$\Rightarrow$ P(k+1) is true.

Therefore, by mathematical induction, P(n) is true.
