To calculate the electric potential at the center of the square, we use the principle of superposition. Electric potential ($V$) is a **scalar** quantity, meaning we simply add the individual potentials from each charge together without needing to worry about vector directions.



### Given Starting Values:
* **Charges ($q_1, q_2, q_3, q_4$):** $+1 \text{ C}, -2 \text{ C}, +3 \text{ C}, -4 \text{ C}$
* **Side length ($s$):** $1.0 \text{ m}$
* **Coulomb's constant ($k$):** $\approx 8.99 \times 10^9 \text{ N}\cdot\text{m}^2/\text{C}^2$


---

### Step 1: Calculate the distance ($r$) from corners to center

The distance from any corner to the center of a square is half of the diagonal. Using the Pythagorean theorem for a square with side $s$:

$$\text{Diagonal} = s\sqrt{2} = 1.0 \cdot \sqrt{2} \text{ m}$$

The distance $r$ is:

$$r = \frac{s\sqrt{2}}{2} = \frac{\sqrt{2}}{2} \text{ m} \approx 0.707 \text{ m}$$

Since the geometry is a square, the distance $r$ is the same for all four charges.

---

### Step 2: Sum the individual potentials

The total electric potential ($V_{net}$) at the center is given by the sum:

$$V_{net} = V_1 + V_2 + V_3 + V_4$$

Using the formula for the potential of a point charge $V = \frac{kq}{r}$:

$$V_{net} = \frac{k q_1}{r} + \frac{k q_2}{r} + \frac{k q_3}{r} + \frac{k q_4}{r}$$

We can factor out the constant terms $\frac{k}{r}$:

$$V_{net} = \frac{k}{r} (q_1 + q_2 + q_3 + q_4)$$

---

### Step 3: Final Calculation

Substitute the charges and the distance into the factored equation:

$$V_{net} = \frac{8.99 \times 10^9}{\sqrt{2}/2} (1 - 2 + 3 - 4)$$

$$V_{net} = \frac{8.99 \times 10^9}{0.707} (-2)$$

$$V_{net} \approx (1.27 \times 10^{10}) \cdot (-2)$$

$$V_{net} \approx -2.54 \times 10^{10} \text{ V}$$

---

### Final Result:
The electric potential at the center of the square is **$-2.54 \times 10^{10} \text{ V}$**.



Notice how much simpler this is than calculating the electric field! Because potential is a scalar, the "order" of the charges doesn't change the final result, as long as they are all the same distance from the center. Would you like to see how the **electric field** (the vector sum) would differ for this specific arrangement?
