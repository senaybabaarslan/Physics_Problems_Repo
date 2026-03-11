## Problem 3 – Integration (Going Backwards)

### Part A: We have velocity, find position.
$\vec v(t) = (2t, 3, -e^{-t})$ and we start at $(0, 1, 2)$.
* Integrate $2t \to t^2$
* Integrate $3 \to 3t$
* Integrate $-e^{-t} \to e^{-t}$
* Add the starting point: $\vec r(t) = \mathbf{(t^2, 3t+1, e^{-t}+1)}$

### Part B: We have acceleration, find velocity then position.
$\vec a(t) = (4, -\sin t, 0)$, $\vec v(0)=(1,0,2)$, $\vec r(0)=(0,0,0)$.
1. **Velocity:** $\int \vec a = (4t, \cos t, 0)$. Add starting velocity $(1,0,2) \to \mathbf{(4t+1, \cos t - 1, 2)}$
2. **Position:** $\int \text{Velocity} = \mathbf{(2t^2+t, \sin t - t, 2t)}$
