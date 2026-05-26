The resistance R is calculated using Ohm's Law, $R = V/I$. If the voltage is measured as $V = (10.0 \pm 0.2)\text{ V}$ and the current as $I = (2.00 \pm 0.05)\text{ A}$, what is the calculated resistance and its uncertainty?

---

To find the resistance and its associated uncertainty, we use Ohm's Law and apply the rules of **error propagation** for division.

### 1. Calculate the Resistance ($R$)

Using the central measured values for voltage ($V = 10.0\text{ V}$) and current ($I = 2.00\text{ A}$):

$$R = \frac{V}{I}$$

$$R = \frac{10.0\text{ V}}{2.00\text{ A}} = 5.00\ \Omega$$

---

### 2. Calculate the Uncertainty in Resistance ($\Delta R$)

When two independent quantities are multiplied or divided, their fractional (relative) uncertainties combine in quadrature:

$$\frac{\Delta R}{R} = \sqrt{\left(\frac{\Delta V}{V}\right)^2 + \left(\frac{\Delta I}{I}\right)^2}$$

Solving for the absolute uncertainty $\Delta R$:

$$\Delta R = R \cdot \sqrt{\left(\frac{\Delta V}{V}\right)^2 + \left(\frac{\Delta I}{I}\right)^2}$$

Substitute the given values ($V = 10.0\text{ V}$, $\Delta V = 0.2\text{ V}$, $I = 2.00\text{ A}$, $\Delta I = 0.05\text{ A}$, and $R = 5.00\ \Omega$):

$$\Delta R = 5.00 \cdot \sqrt{\left(\frac{0.2}{10.0}\right)^2 + \left(\frac{0.05}{2.00}\right)^2}$$

$$\Delta R = 5.00 \cdot \sqrt{(0.02)^2 + (0.025)^2}$$

$$\Delta R = 5.00 \cdot \sqrt{0.0004 + 0.000625}$$

$$\Delta R = 5.00 \cdot \sqrt{0.001025}$$

$$\Delta R = 5.00 \cdot 0.032016 \approx 0.1601\ \Omega$$

---

### 3. Rounding to Proper Significant Figures

* The uncertainty $\Delta R \approx 0.16\ \Omega$ naturally begins with a 1, so keeping two significant figures is standard practice.
* We match the decimal precision of our calculated resistance to the hundredths place to match the uncertainty.

---

### Final Result:

The resistance with its propagated uncertainty is:

$$R = (5.00 \pm 0.16)\ \Omega$$
