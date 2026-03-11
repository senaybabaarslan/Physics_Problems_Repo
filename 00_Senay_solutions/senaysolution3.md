## Problem 3 – Integration of Motion

### A) From Velocity to Position
Given $\vec v(t) = (2t, 3, -e^{-t})$ and $\vec r(0) = (0, 1, 2)$:
1. $\vec r(t) = (0, 1, 2) + \int_0^t (2\tau, 3, -e^{-\tau}) d\tau = (0, 1, 2) + [\tau^2, 3\tau, e^{-\tau}]_0^t$
   $$\vec r(t) = \mathbf{(t^2, 3t + 1, e^{-t} + 1)}$$
2. $\vec a(t) = \frac{d\vec v}{dt} = \mathbf{(2, 0, e^{-t})}$

### B) From Acceleration to Position
Given $\vec a(t) = (4, -\sin t, 0)$, $\vec v(0) = (1, 0, 2)$, and $\vec r(0) = (0, 0, 0)$:
1. $\vec v(t) = (1, 0, 2) + \int_0^t (4, -\sin \tau, 0) d\tau = \mathbf{(4t + 1, \cos t - 1, 2)}$
2. $\vec r(t) = (0, 0, 0) + \int_0^t (4\tau + 1, \cos \tau - 1, 2) d\tau = \mathbf{(2t^2 + t, \sin t - t, 2t)}$
