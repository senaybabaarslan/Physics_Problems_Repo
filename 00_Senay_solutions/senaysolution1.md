# Problem 1 – Deep Dive into Vectors and Linear Transformations

This solution breaks down how vectors interact in 3D space, moving from basic lengths to complex spatial transformations.

---

## Step-by-Step Logic

### Step 01: Calculate the Length (Magnitude)
The **magnitude** (length of vector, $|\vec{a}|$) is the actual "physical" length of the arrow in 3D space. We find this using the **3D Pythagorean Theorem**.

**Formula:**
$$|\vec{a}| = \sqrt{x^2 + y^2 + z^2}$$

**Substitution for Vector a (2, -1, 3):**
* Square the components: $2^2 = 4$, $(-1)^2 = 1$, $3^2 = 9$.
* Sum them up: $4 + 1 + 9 = 14$.
* **Result:** $|\vec{a}| = \mathbf{\sqrt{14}}$ (approximately **3.74** units).

**Substitution for Vector b (1, 4, -2):**
* Square the components: $1^2 = 1$, $4^2 = 16$, $(-2)^2 = 4$.
* Sum them up: $1 + 16 + 4 = 21$.
* **Result:** $|\vec{b}| = \mathbf{\sqrt{21}}$ (approximately **4.58** units).

---

### Step 02: Determine the Normalized Vector (Direction)
A **normalized vector** (unit vector, $\hat{a}$) has a length of exactly **one** (1). It represents the **pure direction** of the original vector without its size.

**Logic:**
We take the original vector and divide every part of it by its total length.

**Substitution:**
$$\hat{a} = \frac{\vec{a}}{|\vec{a}|} = \frac{(2, -1, 3)}{\sqrt{14}}$$
**Result:**
$$\hat{a} = \mathbf{\left( \frac{2}{\sqrt{14}}, \frac{-1}{\sqrt{14}}, \frac{3}{\sqrt{14}} \right)}$$

---

### Step 03: Calculate the Dot Product (Interaction)
The **dot product** (scalar product, $\vec{a} \cdot \vec{b}$) tells us how much the two vectors "agree" with each other. 

**Formula:**
Multiply matching coordinates and sum them: $(x_a \cdot x_b) + (y_a \cdot y_b) + (z_a \cdot z_b)$

**Substitution:**
* $x: 2 \times 1 = 2$
* $y: -1 \times 4 = -4$
* $z: 3 \times -2 = -6$
* Sum: $2 - 4 - 6 = -8$

**Result:**
The **dot product** is **negative eight** (**-8**). 
**Interpretation:** Since the result is negative, we know the vectors are pointing away from each other (the angle is wide).

---

### Step 04: Find the Angle ($\theta$)
Now we use the **Dot Product** and the **Lengths** to find the exact **angle** (theta, $\theta$) between the two arrows.

**Formula:**
$$\cos \theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \times |\vec{b}|}$$

**Substitution:**
$$\cos \theta = \frac{-8}{\sqrt{14} \times \sqrt{21}} \approx -0.466$$
**Result:**
$$\theta = \arccos(-0.466) \approx \mathbf{117.8^\circ}$$
(This is an **obtuse angle** because it is greater than 90 degrees).



---

### Step 05: Cross Product and Area
The **cross product** (vector product, $\vec{a} \times \vec{b}$) creates a new vector that is **perpendicular** (at a 90-degree angle) to both original vectors.

**Substitution (Matrix Determinant):**
$$\vec{a} \times \vec{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & -1 & 3 \\ 1 & 4 & -2 \end{vmatrix} = \mathbf{(-10, 7, 9)}$$

**Area Calculation:**
The magnitude of this cross product is exactly equal to the **area of the parallelogram** formed by $\vec{a}$ and $\vec{b}$.
$$\text{Area} = \sqrt{(-10)^2 + 7^2 + 9^2} = \mathbf{\sqrt{230}} \approx \mathbf{15.17 \text{ units}^2}$$

---

### Step 06: Matrix Transformation and Determinant
We apply a **linear transformation** to vector $\vec{a}$ using **Matrix A**.

**1. Multiply Matrix A by Vector a ($A\vec{a}$):**
$$\begin{pmatrix} 2 & 1 & 0 \\ 0 & 1 & -1 \\ 1 & 0 & 1 \end{pmatrix} \begin{pmatrix} 2 \\ -1 \\ 3 \end{pmatrix} = \mathbf{\begin{pmatrix} 3 \\ -4 \\ 5 \end{pmatrix}}$$
*Meaning:* The original position $(2, -1, 3)$ has been moved to a new position $(3, -4, 5)$.

**2. Calculate the Determinant ($\det A$):**
The **determinant** tells us how the transformation scales the volume of space.
$$\det A = 2(1 - 0) - 1(0 - (-1)) + 0 = 2 - 1 = \mathbf{1}$$

**Final Interpretation:**
Because the **determinant** is exactly **plus one** (+1):
1.  **Volume is preserved:** The space is not stretched or compressed.
2.  **Orientation is preserved:** The space is not flipped (it doesn't look like a mirror image)
