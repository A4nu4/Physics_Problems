To find the magnetic force on a proton moving through a magnetic field, we use the magnetic part of the **Lorentz Force** equation. Since the velocity and magnetic field are given as vectors, we must calculate the cross product $\vec{v} \times \vec{B}$.



### Given Starting Values:
* **Charge of a proton ($q$):** $1.602 \times 10^{-19} \text{ C}$
* **Velocity ($\vec{v}$):** $(2\hat{i} - 4\hat{j} + \hat{k}) \text{ m/s}$
* **Magnetic Field ($\vec{B}$):** $(\hat{i} + 2\hat{j} - \hat{k}) \text{ T}$

---

### 1. Calculate the Cross Product ($\vec{v} \times \vec{B}$)
The cross product is calculated using the determinant of a $3 \times 3$ matrix:

$$\vec{v} \times \vec{B} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ 2 & -4 & 1 \\ 1 & 2 & -1 \end{vmatrix}$$

Expanding the determinant:
* **$\hat{i}$ component:** $(-4)(-1) - (1)(2) = 4 - 2 = 2$
* **$\hat{j}$ component:** $-[(2)(-1) - (1)(1)] = -[-2 - 1] = 3$
* **$\hat{k}$ component:** $(2)(2) - (-4)(1) = 4 + 4 = 8$

$$\vec{v} \times \vec{B} = (2\hat{i} + 3\hat{j} + 8\hat{k})$$

---

### 2. Calculate the Magnitude of the Cross Product
Now we find the magnitude $|\vec{v} \times \vec{B}|$:

$$|\vec{v} \times \vec{B}| = \sqrt{2^2 + 3^2 + 8^2}$$
$$|\vec{v} \times \vec{B}| = \sqrt{4 + 9 + 64}$$
$$|\vec{v} \times \vec{B}| = \sqrt{77} \approx 8.775 \text{ T}\cdot\text{m/s}$$

---

### 3. Calculate the Magnetic Force ($F_B$)
The magnitude of the force is given by $F_B = q |\vec{v} \times \vec{B}|$:

$$F_B = (1.602 \times 10^{-19} \text{ C}) \cdot \sqrt{77}$$
$$F_B = (1.602 \times 10^{-19}) \cdot 8.775$$
$$F_B \approx 1.41 \times 10^{-18} \text{ N}$$

---

### Final Result:
The magnitude of the magnetic force is approximately **$1.41 \times 10^{-18} \text{ N}$**.

