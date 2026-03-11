## Problem 1 – Vectors and Linear Transformations

**Goal:** We have two vectors $\vec a = (2,-1,3)$ and $\vec b = (1,4,-2)$. We will calculate their properties step-by-step.

### 1. Vector Lengths (The Distance from Zero)
To find the length, we square each number, add them up, and take the square root.
* **Length of $\vec a$:**
  $|\vec a| = \sqrt{2^2 + (-1)^2 + 3^2} = \sqrt{4 + 1 + 9} = \mathbf{\sqrt{14}}$
* **Length of $\vec b$:**
  $|\vec b| = \sqrt{1^2 + 4^2 + (-2)^2} = \sqrt{1 + 16 + 4} = \mathbf{\sqrt{21}}$

### 2. Normalized Vector (Unit Vector)
This means making the vector's length exactly "1" without changing its direction. We just divide the original vector by its length.
* $\hat a = \frac{(2, -1, 3)}{\sqrt{14}} = \mathbf{\left(\frac{2}{\sqrt{14}}, -\frac{1}{\sqrt{14}}, \frac{3}{\sqrt{14}}\right)}$

### 3. Dot Product and Angle
The dot product tells us how much vectors point in the same direction.
* **Calculation:** $(2 \times 1) + (-1 \times 4) + (3 \times -2) = 2 - 4 - 6 = \mathbf{-8}$
* **The Angle:** We use the formula $\cos \theta = \frac{\text{Dot Product}}{\text{Length } a \times \text{Length } b}$
  $\cos \theta = \frac{-8}{\sqrt{14}\sqrt{21}} \implies \theta \approx \mathbf{117.8^\circ}$

### 4. Cross Product (The Perpendicular Vector)
This creates a new vector that is at a 90-degree angle to both $\vec a$ and $\vec b$.
$$\vec a \times \vec b = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & -1 & 3 \\ 1 & 4 & -2 \end{vmatrix} = \mathbf{(-10, 7, 9)}$$
* **Area of the Parallelogram:** It is just the length of this new vector!
  $\text{Area} = \sqrt{(-10)^2 + 7^2 + 9^2} = \mathbf{\sqrt{230}}$



### 5. Matrix Transformation
* **Multiply Matrix A by vector a:** We multiply rows of A by the column of $\vec a$.
  $A\vec a = \begin{pmatrix} 2 & 1 & 0 \\ 0 & 1 & -1 \\ 1 & 0 & 1 \end{pmatrix} \begin{pmatrix} 2 \\ -1 \\ 3 \end{pmatrix} = \mathbf{\begin{pmatrix} 3 \\ -4 \\ 5 \end{pmatrix}}$
* **Determinant of A:** This tells us if the space stretches or flips.
  $\det A = 2(1-0) - 1(0+1) + 0 = \mathbf{1}$.
  Since it's positive (+1), the orientation is **preserved** (not flipped).
