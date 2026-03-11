## Problem 1 – Vectors and Linear Transformations

**Given vectors:**
$\vec a = (2, -1, 3)$
$\vec b = (1, 4, -2)$

### 1. Lengths of the vectors
* $|\vec a| = \sqrt{2^2 + (-1)^2 + 3^2} = \sqrt{4 + 1 + 9} = \mathbf{\sqrt{14}}$
* $|\vec b| = \sqrt{1^2 + 4^2 + (-2)^2} = \sqrt{1 + 16 + 4} = \mathbf{\sqrt{21}}$

### 2. Normalized vector $\hat a$
$$\hat a = \frac{\vec a}{|\vec a|} = \frac{(2, -1, 3)}{\sqrt{14}} = \mathbf{\left(\frac{2}{\sqrt{14}}, -\frac{1}{\sqrt{14}}, \frac{3}{\sqrt{14}}\right)}$$

### 3. Dot product and the angle between the vectors
* $\vec a \cdot \vec b = (2)(1) + (-1)(4) + (3)(-2) = 2 - 4 - 6 = \mathbf{-8}$
* $\cos \theta = \frac{\vec a \cdot \vec b}{|\vec a||\vec b|} = \frac{-8}{\sqrt{14}\sqrt{21}} = \frac{-8}{7\sqrt{6}}$
* $\theta = \arccos\left(\frac{-8}{7\sqrt{6}}\right) \approx \mathbf{117.8^\circ}$

### 4. Cross product and the area of the parallelogram
* $\vec a \times \vec b = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & -1 & 3 \\ 1 & 4 & -2 \end{vmatrix} = \mathbf{i}(2-12) - \mathbf{j}(-4-3) + \mathbf{k}(8+1) = \mathbf{(-10, 7, 9)}$
* $\text{Area} = |\vec a \times \vec b| = \sqrt{(-10)^2 + 7^2 + 9^2} = \mathbf{\sqrt{230}}$
