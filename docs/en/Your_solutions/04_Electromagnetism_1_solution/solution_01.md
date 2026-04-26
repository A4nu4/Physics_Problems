To determine the net electric force on the central charge, we use **Coulomb's Law** and the principle of **Superposition**. By analyzing the symmetry of the system, we can determine the magnitude and direction of the total force.



### Given Starting Values:
* **Corner charges ($q$):** $+1.0 \text{ C}$
* **Central charge ($Q$):** $-2.0 \text{ C}$
* **Side length ($s$):** $1.0 \text{ m}$
* **Coulomb's constant ($k$):** $\approx 8.99 \times 10^9 \text{ N}\cdot\text{m}^2/\text{C}^2$

---

### Step 1: Determine the distance ($r$) from corners to center
The distance from any corner to the center of a square is half the length of the diagonal. Using the Pythagorean theorem for a square with side $s$:
$$\text{Diagonal} = s\sqrt{2} = 1.0 \cdot \sqrt{2} \text{ m}$$

The distance $r$ is:
$$r = \frac{s\sqrt{2}}{2} = \frac{1.0 \cdot \sqrt{2}}{2} \approx 0.707 \text{ m}$$

---

### Step 2: Calculate the force from a single corner charge
Each positive corner charge exerts an attractive force ($F_{ind}$) on the negative central charge. Using Coulomb's Law:
$$F = k \frac{|qQ|}{r^2}$$

Substituting the values:
$$F_{ind} = (8.99 \times 10^9) \frac{|(1.0)(-2.0)|}{(0.707)^2}$$
$$F_{ind} = (8.99 \times 10^9) \frac{2}{0.5}$$
$$F_{ind} = 35.96 \times 10^9 \text{ N}$$

---

### Step 3: Apply Vector Superposition
The force from each corner charge is a vector pointing from the center toward that specific corner.

1.  **Opposite Corners:** Consider the charge at the top-left corner and the charge at the bottom-right corner. Both are $+1.0 \text{ C}$. They both pull the central $-2.0 \text{ C}$ charge toward themselves with equal magnitude ($F_{ind}$).
2.  **Cancellation:** Because these two forces are equal in magnitude but exactly opposite in direction, they cancel each other out.
    $$\vec{FTL} + \vec{FBR} = 0$$
3.  **Remaining Corners:** The same logic applies to the top-right and bottom-left corners. Their forces also cancel each other out.
    $$\vec{FTR} + \vec{FBL} = 0$$



---

### Final Result:
The magnitude of the net electric force on the central charge is **$0 \text{ N}$**. Since the magnitude is zero, there is **no direction**.

The symmetry of the arrangement ensures that the central charge is in a state of electrostatic equilibrium. Would you like to see how the net force changes if we replace one of the corner charges with a negative charge?
