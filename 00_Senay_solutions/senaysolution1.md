# Problem 1 – Vector Length and Interaction

---

## Step-by-Step Logic

### Step 01: Calculate the Length (Magnitude)
To find how "long" a vector is, we use the **3D Pythagorean theorem**. We square each coordinate, add them together, and take the **square root** ($\sqrt{x}$).

**Formula:**
$$|\vec{a}| = \sqrt{x^2 + y^2 + z^2}$$

**Substitution for Vector a (2, -1, 3):**
* Square of 2 is **four** (4)
* Square of -1 is **one** (1)
* Square of 3 is **nine** (9)
* Sum: $4 + 1 + 9 = 14$

**Result:**
The length of **vector a** (magnitude of a, $|\vec{a}|$) is the **square root of fourteen** ($\mathbf{\sqrt{14}}$).

---

### Step 02: Calculate the Dot Product
The **dot product** (scalar product, $\cdot$) shows us how much two vectors "agree" or point in the same direction. We multiply the matching parts (x with x, y with y, z with z) and sum them up.

**Formula:**
$$\vec{a} \cdot \vec{b} = (a_x \times b_x) + (a_y \times b_y) + (a_z \times b_z)$$

**Substitution:**
* Multiply x: $2 \times 1 = 2$
* Multiply y: $(-1) \times 4 = -4$
* Multiply z: $3 \times (-2) = -6$
* Sum: $2 + (-4) + (-6) = -8$

**Result:**
The **dot product** ($\vec{a} \cdot \vec{b}$) is **negative eight** (**-8**).

---

### Step 03: Determine the Angle
Now, we use the results from **Step 01** and **Step 02** to find the **angle** (theta, $\theta$) between the two vectors.

**Formula:**
$$\cos \theta = \frac{\text{Dot Product}}{\text{Length a} \times \text{Length b}}$$

**Substitution:**
$$\cos \theta = \frac{-8}{\sqrt{14} \times \sqrt{21}} \approx -0.466$$

**Result:**
The **angle** ($\theta$) is **one hundred seventeen point eight degrees** ($\mathbf{117.8^\circ}$).

---

## Final Result Summary

| Component | Mathematical Result |
| :--- | :--- |
| **Length of a** ($|\vec{a}|$) | $\sqrt{14}$ |
| **Length of b** ($|\vec{b}|$) | $\sqrt{21}$ |
| **Dot Product** ($\vec{a} \cdot \vec{b}$) | $-8$ |
| **Angle** ($\theta$) | $117.8^\circ$ |

---

## Interpretation
The **magnitude** ($|\vec{a}|$) represents the distance of the vector from the origin. The **dot product** ($\cdot$) being negative tells us that the vectors are pointing away from each other. Specifically, because the **angle** ($\theta$) is greater than **ninety degrees** (90°), we call this an **obtuse angle**. This is a classic example of using basic algebra to understand the geometry of 3D space.
