The radius of a sphere is measured to be $r = (6.20 \pm 0.05)\text{ cm}$. Calculate the volume of the sphere and its associated uncertainty.

---

To find the volume of the sphere and its associated uncertainty, we use the formula for the volume of a sphere and apply the rules of **error propagation** (specifically, the power rule for independent uncertainties).

### 1. Calculate the Volume ($V$)

The formula for the volume of a sphere is:

$$V = \frac{4}{3}\pi r^3$$

Using the measured radius $r = 6.20\text{ cm}$:

$$V = \frac{4}{3}\pi (6.20)^3$$

$$V \approx \frac{4}{3}\pi (238.328)$$

$$V \approx 998.306\text{ cm}^3$$

---

### 2. Calculate the Uncertainty in Volume ($\Delta V$)

When a variable is raised to a power ($V \propto r^3$), its relative (fractional) uncertainty is multiplied by the absolute value of that power:

$$\frac{\Delta V}{V} = 3 \frac{\Delta r}{r}$$

Now, solve for the absolute uncertainty $\Delta V$:

$$\Delta V = 3 \cdot \left(\frac{\Delta r}{r}\right) \cdot V$$

Substitute the known values ($r = 6.20\text{ cm}$, $\Delta r = 0.05\text{ cm}$, and $V \approx 998.306\text{ cm}^3$):

$$\Delta V = 3 \cdot \left(\frac{0.05}{6.20}\right) \cdot 998.306$$

$$\Delta V = 3 \cdot (0.0080645) \cdot 998.306$$

$$\Delta V \approx 24.153\text{ cm}^3$$

---

### 3. Rounding according to Significant Figures

* Experimental uncertainties are traditionally rounded to **one significant figure** (or two, if the leading digit is a 1). Here, $\Delta V \approx 24\text{ cm}^3$ rounds to **$20\text{ cm}^3$** (or **$24\text{ cm}^3$** if keeping two figures for high precision). Let's stick to the standard convention of matching the decimal place of the measurement's final significant digit.
* Since the uncertainty dominates at the tens/ones place, we match the precision of the volume:

$$V \approx 1000\text{ cm}^3 \quad \text{and} \quad \Delta V \approx 20\text{ cm}^3$$

---

### Final Result:

The volume of the sphere with its propagated uncertainty is:

$$V = (1000 \pm 20)\text{ cm}^3$$


*(Alternatively written as $(9.98 \pm 0.24) \times 10^2\text{ cm}^3$ if preserving the original precision layout).*
