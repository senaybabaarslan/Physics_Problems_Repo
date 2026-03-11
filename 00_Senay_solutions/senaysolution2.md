## Problem 2: Velocity and Acceleration from Trajectory

**Given:** $\vec r(t) = (t^2, \sin t, 5)$

* **Velocity $\vec v(t)$:** Take the first derivative.
  $v_x = \frac{d}{dt}(t^2) = 2t$
  $v_y = \frac{d}{dt}(\sin t) = \cos t$
  $v_z = \frac{d}{dt}(5) = 0$
  $\vec v(t) = \mathbf{(2t, \cos t, 0)}$

* **Acceleration $\vec a(t)$:** Take the second derivative.
  $a_x = \frac{d}{dt}(2t) = 2$
  $a_y = \frac{d}{dt}(\cos t) = -\sin t$
  $a_z = \frac{d}{dt}(0) = 0$
  $\vec a(t) = \mathbf{(2, -\sin t, 0)}$

* **Speed at $t=1$:** $|\vec v(1)| = \sqrt{(2 \times 1)^2 + \cos^2(1)} = \sqrt{4 + 0.29} \approx \mathbf{2.07}$
* **Dot Product $\vec v \cdot \vec a$:** $(2t)(2) + (\cos t)(-\sin t) = \mathbf{4t - \sin t \cos t}$
* **Cross Product $\vec v \times \vec a$:** $\mathbf{(0, 0, -2t \sin t - 2 \cos t)}$ (Only the Z-component survives).



---
