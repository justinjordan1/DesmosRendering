# DesmosRendering
Equation for rendering any 3d point, with controls for pitch, yaw, roll, perspective, and vertical and horizonatal compressions and shifts
https://www.desmos.com/calculator/z3ylx7qgke

$$
g\left(x_{c},y_{c},z_{c}\right)=\frac{\left(\left(\left(a\sqrt{x_{c}^{2}+y_{c}^{2}}\cos\left(\arctan\left(y_{c},x_{c}\right)+x_{r}\right)\right)\cdot\cos\left(z_{r}\right)d_{camz}-\left(\left(\sqrt{x_{c}^{2}+y_{c}^{2}}\sin\left(\arctan\left(y_{c},x_{c}\right)+x_{r}\right)\cdot\sin\left(y_{r}\right)+z_{c}b\cos\left(y_{r}\right)\right)\cdot\sin\left(z_{r}\right)d_{camz}\right)+d_{camx}\right)o_{pticaldistortion}^{u},o_{pticaldistortion}^{u}\left(d_{camy}+\left(\left(a\sqrt{x_{c}^{2}+y_{c}^{2}}\cos\left(\arctan\left(y_{c},x_{c}\right)+x_{r}\right)\right)\sin\left(z_{r}\right)d_{camz}+d_{camz}\cos\left(z_{r}\right)\left(\left(\sqrt{x_{c}^{2}+y_{c}^{2}}\sin\left(\arctan\left(y_{c},x_{c}\right)+x_{r}\right)\cdot\sin\left(y_{r}\right)+z_{c}b\cos\left(y_{r}\right)\right)\right)\right)\right)\right)}{\left(o_{pticaldistortion}^{u}-\left(\left(\sin\left(\arctan\left(y_{c},x_{c}\right)+x_rightright)\cos\left(y_rightright)\sqrt{x_c^2+y_c^2}-sin(y_rightright)z_c \right) \right) \right)^u } \ \{ o_pticaldistortion^u - \left( \sin(arctan(y_c,x_c)+x_rightright) \cos(y_rightright) \sqrt{x_c^2+y_c^2}-sin(y_rightright)z_c \right) + -1000u + 1000 > 0 \}
$$

equation for a spirograph with a z axis using the above renderer 

$$
g\left(\left(R_{s}-r_{s}\right)\sin\left(\frac{r_{s}t}{R_{s}}\right)+d_{s}\sin\left(\left(1-\frac{r_{s}}{R_{s}}\right)t\right),-\left(R_{s}-r_{s}\right)\cos\left(\frac{r_{s}t}{R_{s}}\right)+d_{s}\cos\left(\left(1-\frac{r_{s}}{R_{s}}\right)t\right),a_{mplitude}\cos\left(z_{s}t+s_{shift}\right)\right)
$$

equation for a line drawn parametric sphere

$$
g\left(\sin\left(l_{ista}t\right)\cos\left(l_{istb}t\right),\sin\left(l_{istb}t\right)\sin\left(l_{ista}t\right),\cos l_{ista}t\right)
$$

equation for a torus 

$$ 
g\left(\cos\left(t\right)\left(\cos\left(t_{u}\right)+t_{orus2}\right),\sin\left(t\right)\left(\cos\left(t_{u}\right)+t_{orus2}\right),\sin\left(t_{u}\right)\right)
$$

equation for a parametric, line drawn, funky cube

$$
g\left(\sin\left(e_{1}t\right),\sin\left(e_{2}t\right),\sin\left(e_{3}t\right)\right)
$$
