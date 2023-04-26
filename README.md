# DesmosRendering
Equation for rendering any 3d point, with controls for pitch, yaw, roll, perspective, and vertical and horizonatal compressions and shifts


$$
g\left(x_{c},y_{c},z_{c}\right)=\frac{\left(\left(\left(a\sqrt{x_{c}^{2}+y_{c}^{2}}\cos\left(\arctan\left(y_{c},x_{c}\right)+x_{r}\right)\right)\cdot\cos\left(z_{r}\right)d_{camz}-\left(\left(\sqrt{x_{c}^{2}+y_{c}^{2}}\sin\left(\arctan\left(y_{c},x_{c}\right)+x_{r}\right)\cdot\sin\left(y_{r}\right)+z_{c}b\cos\left(y_{r}\right)\right)\cdot\sin\left(z_{r}\right)d_{camz\right)\right)+d_{camx}\right)o_{pticaldistortion}^{u},o_{pticaldistortion}^{u}\left(d_{camy}+\left(\left(a\sqrt{x_{c}^{2}+y_{c}^{2}}\cos\left(\arctan\left(y_{c},x_{c}\right)+x_{r}\right)\right)\sin\left(z_{r}\right)d_{camz}+d_{camz}\cos\left(z_{r}\right)\left(\left(\sqrt{x_{c}^{2}+y_{c}^{2}}\sin\left(\arctan\left(y_{c},x_{c}\right)+x_{r}\right)\cdot\sin\left(y_{r}\right)+z_{c}b\cos\left(y_{r}\right)\right)\right)\right)\right)\right)}{\left(o_{pticaldistortion}^{u}-\left(\left(\sin\left(\arctan\left(y_{c},x_{c}\right)+x_{r}\right)\cos\left(y_{r}\right)\sqrt{x_{c}^{2}+y_{c}^{2}}-\sin\left(y_{r}\right)z_{c}\right)\right)\right)^{u}}\ \left\{o_{pticaldistortion}^{u}-\left(\left(\sin\left(\arctan\left(y_{c},x_{c}\right)+x_{r}\right)\cos\left(y_{r}\right)\sqrt{x_{c}^{2}+y_{c}^{2}}-\sin\left(y_{r}\right)z_{c}\right)\right)+-1000u+1000>0\right\}
$$




