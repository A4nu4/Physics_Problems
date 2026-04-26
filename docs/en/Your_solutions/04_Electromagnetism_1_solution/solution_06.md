To find the electric field produced by two point charges, we use the principle of superposition. The total electric field $\vec{E}$ at any point is the vector sum of the fields from each charge.



### Given Starting Values:
* **Charge 1 ($q_1$):** $+q$ at $\vec{r}_1 = (-a, 0)$
* **Charge 2 ($q_2$):** $+2q$ at $\vec{r}_2 = (a, 0)$
* **Coulomb's constant:** $k = \frac{1}{4\pi\epsilon_0}$

---

### 1. Determination of the Field Vectors

The general formula for the electric field from a point charge is $\vec{E} = \frac{kq}{r^2} \hat{r} = \frac{kq}{r^3} \vec{r}$.

#### General Field $\vec{E}(x, y)$
For an arbitrary point $P(x, y)$, the displacement vectors from the charges are:
$\vec{r}_{P1} = (x + a) \hat{i} + y \hat{j}$ with magnitude $r_1 = \sqrt{(x+a)^2 + y^2}$
$\vec{r}_{P2} = (x - a) \hat{i} + y \hat{j}$ with magnitude $r_2 = \sqrt{(x-a)^2 + y^2}$

$$\vec{E}(x, y) = kq \left[ \frac{(x+a)\hat{i} + y\hat{j}}{((x+a)^2 + y^2)^{3/2}} + \frac{2((x-a)\hat{i} + y\hat{j})}{((x-a)^2 + y^2)^{3/2}} \right]$$

#### Field on the y-axis $\vec{E}(0, y)$
Substitute $x = 0$. Note that $r_1 = r_2 = \sqrt{a^2 + y^2}$.
$$\vec{E}(0, y) = \frac{kq}{(a^2 + y^2)^{3/2}} \left[ (a\hat{i} + y\hat{j}) + 2(-a\hat{i} + y\hat{j}) \right]$$
$$\vec{E}(0, y) = \frac{kq}{(a^2 + y^2)^{3/2}} \left[ -a\hat{i} + 3y\hat{j} \right]$$

#### Field on the x-axis $\vec{E}(x, 0)$
Substitute $y = 0$:
$$\vec{E}(x, 0) = kq \left[ \frac{x+a}{|x+a|^3} + \frac{2(x-a)}{|x-a|^3} \right] \hat{i}$$

---

### 2. Conditions for $E_x = 0$, $E_y = 0$, and $\vec{E} = 0$

* **$E_y = 0$:** This occurs when $y = 0$. On the x-axis, the field has no vertical component.
* **$E_x = 0$:** Looking at the general formula, this requires $\frac{x+a}{r_1^3} + \frac{2(x-a)}{r_2^3} = 0$. On the y-axis ($x=0$), $E_x \neq 0$ because the $+2q$ charge is stronger than the $+q$ charge at equal distances.
* **$\vec{E} = 0$ (Stagnation Point):** This must occur on the x-axis ($y=0$) between the charges (where $-a < x < a$).
    $$\frac{1}{(x+a)^2} = \frac{2}{(a-x)^2}$$
    Taking the square root: $\frac{1}{x+a} = \frac{\sqrt{2}}{a-x} \implies a - x = \sqrt{2}x + \sqrt{2}a$
    $$x = a \frac{1-\sqrt{2}}{1+\sqrt{2}} = a(2\sqrt{2}-3) \approx -0.17a$$

---

### 3. Calculation for Specific Values
**Given:** $a = 0.2\,\mathrm{m}$, $y = 0.3\,\mathrm{m}$, $q = 2\,\mu\mathrm{C}$, $x = 0$.
$r = \sqrt{0.2^2 + 0.3^2} = \sqrt{0.13} \approx 0.36\,\mathrm{m}$.

Using the $\vec{E}(0, y)$ formula:
$$E_x = \frac{(8.99 \times 10^9)(2 \times 10^{-6})}{(0.13)^{3/2}} (-0.2) \approx -7.67 \times 10^4\,\mathrm{V/m}$$
$$E_y = \frac{(8.99 \times 10^9)(2 \times 10^{-6})}{(0.13)^{3/2}} (3 \cdot 0.3) \approx 3.45 \times 10^5\,\mathrm{V/m}$$
$$\vec{E} = (-7.67 \times 10^4 \hat{i} + 3.45 \times 10^5 \hat{j})\,\mathrm{V/m}$$

---

### 4. Limit $y \gg a$
When $y$ is much larger than $a$, the separation $a$ becomes negligible. The two charges behave like a single point charge of magnitude $Q_{total} = q + 2q = 3q$ located at the origin.

Mathematically, for $x=0$, as $y \to \infty$:
$$\vec{E}(0, y) \approx \frac{kq}{(y^2)^{3/2}} [ -a\hat{i} + 3y\hat{j} ] \approx \frac{3kq}{y^2} \hat{j}$$

The field becomes purely vertical (along the y-axis) and follows the inverse-square law for a $3q$ charge.
