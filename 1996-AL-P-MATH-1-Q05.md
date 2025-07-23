## 5(a)
Consider augmented matrix of the system: 

$\left[ \begin{array}{ccc|c} 
1 & 1 & 0 & a \\ 
1 & 0 & 1 & b \\
0 & 1 & 1 & c
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 0 & a \\ 
0 & -1 & 1 & b-a \\
0 & 1 & 1 & c
\end{array} \right]$

$\Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 0 & a \\ 
0 & -1 & 1 & b-a \\
0 & 0 & 2 & b+c-a
\end{array} \right]$

$\displaystyle \Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 0 & a \\ 
0 & 1 & -1 & a-b \\
0 & 0 & 1 & {{b+c-a} \over 2}
\end{array} \right]$

$\displaystyle \Rightarrow \left[ \begin{array}{ccc|c} 
1 & 1 & 0 & a \\ 
0 & 1 & 0 & {{a-b+c} \over 2} \\
0 & 0 & 1 & {{b+c-a} \over 2}
\end{array} \right]$

$\displaystyle \Rightarrow \left[ \begin{array}{ccc|c} 
1 & 0 & 0 & {{a+b-c} \over 2} \\ 
0 & 1 & 0 & {{a-b+c} \over 2} \\
0 & 0 & 1 & {{b+c-a} \over 2}
\end{array} \right]$

$\displaystyle \Rightarrow X = {{-a+b+c} \over 2},\ Y = {{a-b+c} \over 2},\ Z = {{a+b-c} \over 2}$

## 5(b)
Let Z = xy, Y = xz, X = yz
By result in 5(a),

$\displaystyle X = {{-a+b+c} \over 2},\ Y = {{a-b+c} \over 2},\ Z = {{a+b-c} \over 2}$

$\displaystyle \Rightarrow yz = {{-a+b+c} \over 2},\ xz = {{a-b+c} \over 2},\ xy = {{a+b-c} \over 2}$

$\displaystyle \Rightarrow yz = {{-a+b+c} \over 2},\ xz = {{a-b+c} \over 2},\ xy = {{a+b-c} \over 2},\ {y \over x} = {{-a+b+c} \over {a-b+c}},\ {z \over y} = {{a-b+c} \over {a+b-c}},\ {x \over z} = {{a+b-c} \over {-a+b+c}}$

$\displaystyle \Rightarrow y \cdot {{a-b+c} \over {a+b-c}} \cdot y = {{-a+b+c} \over 2},\ z \cdot {{a+b-c} \over {-a+b+c}} \cdot z = {{a-b+c} \over 2},\ x \cdot {{-a+b+c} \over {a-b+c}} \cdot x = {{a+b-c} \over 2}$

$\displaystyle \Rightarrow y^2 = {{(a+b-c)(-a+b+c)} \over {2(a-b+c)}},\ z^2 = {{(a-b+c)(-a+b+c)} \over {2(a+b-c)}},\ x^2 = {{(a+b-c)(a-b+c)} \over {2(-a+b+c)}}$

$\displaystyle \Rightarrow  x^2 = {{(a+b-c)(a-b+c)} \over {2(-a+b+c)}},\ y^2 = {{(a+b-c)(-a+b+c)} \over {2(a-b+c)}},\ z^2 = {{(a-b+c)(-a+b+c)} \over {2(a+b-c)}}$

$\displaystyle \Rightarrow  x^2 = {{(a+b-c)(a-b+c)} \over {2(-a+b+c)}},\ y^2 = {{(a+b-c)(-a+b+c)} \over {2(a-b+c)}},\ z^2 = {{(a-b+c)(-a+b+c)} \over {2(a+b-c)}}$

$\displaystyle \Rightarrow x = \sqrt{{(a+b-c)(a-b+c)} \over {2(-a+b+c)}},\ y = \sqrt{{(a+b-c)(-a+b+c)} \over {2(a-b+c)}},\ z = \sqrt{{(a-b+c)(-a+b+c)} \over {2(a+b-c)}}$
or
$\displaystyle x = -\sqrt{{(a+b-c)(a-b+c)} \over {2(-a+b+c)}},\ y = -\sqrt{{(a+b-c)(-a+b+c)} \over {2(a-b+c)}},\ z = -\sqrt{{(a-b+c)(-a+b+c)} \over {2(a+b-c)}}$