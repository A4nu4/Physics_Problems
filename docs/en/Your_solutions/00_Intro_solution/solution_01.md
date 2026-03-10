To solve these vector algebra problems, we will use the components of the given vectors:
$\vec{a} = 2\hat{i} + 1\hat{j} - 3\hat{k}$

$\vec{b} = 4\hat{i} - 2\hat{j} + 1\hat{k}$

---

### a) Magnitude of Each Vector

The magnitude (length) of a vector $\vec{v} = [x, y, z]$ is calculated using the formula:


$$|\vec{v}| = \sqrt{x^2 + y^2 + z^2}$$

**Magnitude of $\vec{a}$:**


$$|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14}$$

$$|\vec{a}| \approx \mathbf{3.74}$$

**Magnitude of $\vec{b}$:**


$$|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21}$$

$$|\vec{b}| \approx \mathbf{4.58}$$

---

### b) Dot Product $\vec{a} \cdot \vec{b}$

The dot product is a scalar value calculated by summing the products of the corresponding components:


$$\vec{a} \cdot \vec{b} = (a_x \cdot b_x) + (a_y \cdot b_y) + (a_z \cdot b_z)$$

$$\vec{a} \cdot \vec{b} = (2 \cdot 4) + (1 \cdot -2) + (-3 \cdot 1)$$

$$\vec{a} \cdot \vec{b} = 8 - 2 - 3 = \mathbf{3}$$

---

### c) Cross Product $\vec{a} \times \vec{b}$

The cross product results in a new vector that is perpendicular to both $\vec{a}$ and $\vec{b}$. It is calculated using the determinant of a $3 \times 3$ matrix:

$$\vec{a} \times \vec{b} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix}$$

$$\mathbf{\hat{i} \begin{vmatrix} 1 & -3 \\ -2 & 1 \end{vmatrix}}$$

$$-\mathbf{\hat{j} \begin{vmatrix} 2 & -3 \\ 4 & 1 \end{vmatrix}}$$

$$\mathbf{+\hat{k} \begin{vmatrix} 2 & 1 \\ 4 & -2 \end{vmatrix}}$$

Expanding by the first row:

* **$\hat{i}$ component:** $(1 \cdot 1) - (-3 \cdot -2) = 1 - 6 = \mathbf{-5}$
* **$\hat{j}$ component:** $-(2 \cdot 1 - (-3 \cdot 4)) = -(2 + 12) = \mathbf{-14}$
* **$\hat{k}$ component:** $(2 \cdot -2) - (1 \cdot 4) = -4 - 4 = \mathbf{-8}$


* **$\vec{a} \times \vec{b}$ result:** $-5\hat{i} - 14\hat{j} - 8\hat{k}$


---

### d) Angle Between Vectors $\vec{a}$ and $\vec{b}$

We use the geometric definition of the dot product: $\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos(\theta)$.
Rearranging for $\theta$:


$$\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}$$

Substitute the values found in parts (a) and (b):


$$\cos(\theta) = \frac{3}{\sqrt{14} \cdot \sqrt{21}} = \frac{3}{\sqrt{294}}$$

$$\cos(\theta) \approx \frac{3}{17.146} \approx 0.175$$

Taking the inverse cosine:


$$\theta = \arccos(0.175) \approx \mathbf{79.92^\circ}$$

---

### Summary Table

| Operation | Result |
| --- | --- |
| **Magnitude**  | $\sqrt{14}$ |
| **Magnitude**  | $\sqrt{21}$ |
| **Dot Product $\vec{a} \cdot \vec{b}$** | $3$ |
| **Cross Product $\vec{a} \times \vec{b}$** | $[-5, -14, -8]$ |
| **Angle $\theta$** | $\approx 79.92^\circ$ |

