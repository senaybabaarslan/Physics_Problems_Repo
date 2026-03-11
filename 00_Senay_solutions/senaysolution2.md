## Problem 3: Integration of Motion

### 3.1 Part A: Velocity to Position
$\vec v(t) = (2t, 3, -e^{-t})$ and $\vec r(0) = (0, 1, 2)$.
* Integrate $v_x = 2t \to t^2 + C_1$. Since $x(0)=0, C_1=0$.
* Integrate $v_y = 3 \to 3t + C_2$. Since $y(0)=1, C_2=1$.
* Integrate $v_z = -e^{-t} \to e^{-t} + C_3$. Since $z(0)=2, e^0 + C_3 = 2 \to 1 + C_3 = 2 \to C_3 = 1$.
* **Position:** $\vec r(t) = \mathbf{(t^2, 3t+1, e^{-t}+1)}$
* **Acceleration:** $\frac{d}{dt} \vec v(t) = \mathbf{(2, 0, e^{-t})}$

### 3.2 Part B: Acceleration to Position
$\vec a(t) = (4, -\sin t, 0)$ with $\vec v(0)=(1,0,2)$ and $\vec r(0)=(0,0,0)$.
1. **Velocity:** Integrate $\vec a \to (4t, \cos t, 0)$. Add constants to match $\vec v(0)$:
   $\vec v(t) = \mathbf{(4t+1, \cos t - 1, 2)}$
2. **Position:** Integrate $\vec v \to (2t^2+t, \sin t - t, 2t)$. Since $\vec r(0)=0$:
   $\vec r(t) = \mathbf{(2t^2+t, \sin t - t, 2t)}$
