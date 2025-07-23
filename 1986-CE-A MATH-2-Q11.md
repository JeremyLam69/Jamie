## 11(a)(i)
Let $x = 2\ sin \theta$
$\displaystyle \Rightarrow {{dx} \over {d \theta}} = 2\ cos \theta$

Also, 
- When x=1, $\displaystyle sin \theta = {1 \over 2} \Rightarrow \theta = {\pi \over 6}$
- When x=2, $\displaystyle sin \theta = 1 \Rightarrow \theta = {\pi \over 2}$
- $\sqrt{4-x^2} = \sqrt{4-4\ sin^2 \theta} = 2cos \theta$

Then $\displaystyle \int_{1}^{2} \sqrt{4-x^2}\ dx$

$\displaystyle = \int_{\pi \over 6}^{\pi \over 2} (2\ cos \theta)(2\ cos \theta) \ d \theta$

$\displaystyle = \int_{\pi \over 6}^{\pi \over 2} 4\ cos^2 \theta \ d \theta$

$\displaystyle = \int_{\pi \over 6}^{\pi \over 2} 2\ (1+cos\ 2 \theta) \ d \theta$

$\displaystyle = \int_{\pi \over 3}^{\pi} (1+cos\ \beta) \ d (\beta)$ where $\beta = 2 \theta$

$\displaystyle = \pi + sin \pi - {\pi \over 3} - sin {\pi \over 3}$

$\displaystyle = {2 \pi \over 3} - {\sqrt{3} \over 2}$

## 11(a)(ii)
$\displaystyle 3 + 2x - x^2$
$\displaystyle = 4 - 1 + 2x - x^2$
$\displaystyle = 4 - (1 - 2x + x^2)$
$\displaystyle = 2^2 - (x-1)^2$

Let $x - 1 = 2\ sin \theta$
- $\displaystyle {{dx} \over {d \theta}} = 2\ cos \theta$
- $\displaystyle \sqrt{3 + 2x - x^2} = \sqrt{2^2 - (x-1)^2} =  \sqrt{2^2-2^2\ sin^2 \theta} = 2 cos \theta$
- when x=0, $\displaystyle sin \theta = - {1 \over 2} \Rightarrow \theta = - {\pi \over 6}$
- when x=1, $\displaystyle sin \theta = 0 \Rightarrow \theta = 0$

Then $\displaystyle \int_{0}^{1} \sqrt{3 + 2x - x^2}\ dx$
$\displaystyle = \int_{-{\pi \over 6}}^{0} 4\ cos^2 \theta \ d \theta$
$\displaystyle = \int_{-{\pi \over 3}}^{0} (1+cos\ \beta) \ d (\beta)$
$\displaystyle = 0 + sin 0 - (-{\pi \over 3}) - sin (-{\pi \over 3})$
$\displaystyle = {\pi \over 3} + {\sqrt{3} \over 2}$

## 11(b)(i)
P(x, y) is on $C_2$
$\displaystyle \Rightarrow (x-1)^2+(y-\sqrt{3})^2=4$
$\displaystyle \Rightarrow (y-\sqrt{3})^2 = 4-(x-1)^2$
$\displaystyle \Rightarrow y-\sqrt{3} = - \sqrt{4-(x-1)^2}$ ($\because$ P is below the centre, therefore, $y-\sqrt{3} < 0$)
$\displaystyle \Rightarrow y = \sqrt{3} - \sqrt{4-(x-1)^2}$
$\displaystyle \Rightarrow y = \sqrt{3} - \sqrt{3 + 2x - x^2}$

## 11(b)(ii)
Area of the shaded region
$\displaystyle = \int_{0}^{1} [\ \sqrt{3x} - (\sqrt{3} - \sqrt{3 + 2x - x^2})\ ] dx + \int_{1}^{2} [\ \sqrt{4-x^2} - (\sqrt{3} - \sqrt{3 + 2x - x^2})\ ]\ dx$

$\displaystyle = \sqrt{3} \int_{0}^{1} x dx - \sqrt{3} \int_{0}^{1} dx + \int_{0}^{1} \sqrt{3 + 2x - x^2} dx + \int_{1}^{2} \sqrt{4-x^2} dx - \sqrt{3}\int_{1}^{2} dx + \int_{1}^{2} \sqrt{3 + 2x - x^2}\ dx$

$\displaystyle = \sqrt{3} \int_{0}^{1} x dx - \sqrt{3} \int_{0}^{2} dx + \int_{0}^{2} \sqrt{3 + 2x - x^2} dx + \int_{1}^{2} \sqrt{4-x^2} dx$

$\displaystyle = {\sqrt{3} \over 2} - 2\sqrt{3} + \int_{-{\pi \over 3}}^{\pi \over 3} (1+cos\ \beta) \ d (\beta) + {2 \pi \over 3} - {\sqrt{3} \over 2}$

$\displaystyle = {\sqrt{3} \over 2} - 2\sqrt{3} + {2\pi \over 3} + \sqrt{3} + {2 \pi \over 3} - {\sqrt{3} \over 2}$

$\displaystyle = {4\pi \over 3}- \sqrt{3}$