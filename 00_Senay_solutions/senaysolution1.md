## Problem 1: Vectors and Matrix Transformations

**Given Vectors:** $\vec a = (2, -1, 3)$ and $\vec b = (1, 4, -2)$

### 1.1 Calculating Lengths (Magnitudes)
To find the length, we use the Pythagorean theorem in 3D: $\sqrt{x^2 + y^2 + z^2}$.
* **Length of $\vec a$:** $|\vec a| = \sqrt{2^2 + (-1)^2 + 3^2} = \sqrt{4 + 1 + 9} = \mathbf{\sqrt{14}}$
* **Length of $\vec b$:** $|\vec b| = \sqrt{1^2 + 4^2 + (-2)^2} = \sqrt{1 + 16 + 4} = \mathbf{\sqrt{21}}$

### 1.2 Normalized Vector $\hat a$
A unit vector has a length of 1. We divide the vector by its own length.
$$\hat a = \frac{\vec a}{|\vec a|} = \frac{(2, -1, 3)}{\sqrt{14}} = \mathbf{\left( \frac{2}{\sqrt{14}}, -\frac{1}{\sqrt{14}}, \frac{3}{\sqrt{14}} \right)}$$

### 1.3 Dot Product and Angle
* **Dot Product:** Multiply matching components and add them:
  $\vec a \cdot \vec b = (2 \times 1) + (-1 \times 4) + (3 \times -2) = 2 - 4 - 6 = \mathbf{-8}$
* **Angle ($\theta$):** Use the formula $\cos \theta = \frac{\vec a \cdot \vec b}{|\vec a||\vec b|}$
  $\cos \theta = \frac{-8}{\sqrt{14}\sqrt{21}} = \frac{-8}{\sqrt{294}} \approx -0.466$
  $\theta = \arccos(-0.466) \approx \mathbf{117.8^\circ}$

### 1.4 Cross Product and Area
The cross product creates a vector perpendicular to both.
$$\vec a \times \vec b = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & -1 & 3 \\ 1 & 4 & -2 \end{vmatrix}$$
* $\mathbf{i}: (-1)(-2) - (3)(4) = 2 - 12 = -10$
* $\mathbf{j}: -[(2)(-2) - (3)(1)] = -[-4 - 3] = 7$
* $\mathbf{k}: (2)(4) - (-1)(1) = 8 + 1 = 9$
* **Result:** $\vec a \times \vec b = \mathbf{(-10, 7, 9)}$
* **Area of Parallelogram:** Magnitude of the cross product: $\sqrt{(-10)^2 + 7^2 + 9^2} = \sqrt{100+49+81} = \mathbf{\sqrt{230}}$



### 1.5 Matrix Operations
* **Matrix-Vector Multiplication $A\vec a$:**
  $$\begin{pmatrix} 2 & 1 & 0 \\ 0 & 1 & -1 \\ 1 & 0 & 1 \end{pmatrix} \begin{pmatrix} 2 \\ -1 \\ 3 \end{pmatrix} = \begin{pmatrix} (2 \times 2) + (1 \times -1) + (0 \times 3) \\ (0 \times 2) + (1 \times -1) + (-1 \times 3) \\ (1 \times 2) + (0 \times -1) + (1 \times 3) \end{pmatrix} = \mathbf{\begin{pmatrix} 3 \\ -4 \\ 5 \end{pmatrix}}$$
* **Determinant ($\det A$):**
  $\det A = 2(1-0) - 1(0 - (-1)) + 0 = 2 - 1 = \mathbf{1}$
* **Orientation:** Since $\det A = 1$ (which is positive), the transformation **preserves** the orientation.

---
