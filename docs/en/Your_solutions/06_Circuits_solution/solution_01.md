Calculating the equivalent resistance and current for these circuits involves applying Ohm's Law and the fundamental rules for series and parallel configurations.

---

## 1. Series Configuration

In a series circuit, the total resistance is simply the sum of all individual resistances. The same current flows through every component.

### Equivalent Resistance ($R_{eq}$)

$$R_{eq} = R_1 + R_2 + R_3$$

$$R_{eq} = 15\,\Omega + 30\,\Omega + 50\,\Omega = \mathbf{95\,\Omega}$$

### Total Current ($I_{total}$)

Using Ohm's Law ($V = IR$):


$$I = \frac{V}{R_{eq}} = \frac{12\,\text{V}}{95\,\Omega} \approx \mathbf{0.126\,\text{A} \text{ (or 126 mA)}}$$

---

## 2. Parallel Configuration

In a parallel circuit, the voltage across each resistor is the same (12 V), and the total equivalent resistance is always less than the smallest individual resistor.

### Equivalent Resistance ($R_{eq}$)

The reciprocal of the total resistance is the sum of the reciprocals of each resistance:


$$\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}$$

$$\frac{1}{R_{eq}} = \frac{1}{15} + \frac{1}{30} + \frac{1}{50}$$

Finding a common denominator (150):


$$\frac{1}{R_{eq}} = \frac{10}{150} + \frac{5}{150} + \frac{3}{150} = \frac{18}{150}$$

$$R_{eq} = \frac{150}{18} \approx \mathbf{8.33\,\Omega}$$

### Total Current ($I_{total}$)

$$I = \frac{V}{R_{eq}} = \frac{12\,\text{V}}{8.33\,\Omega} = \mathbf{1.44\,\text{A}}$$

---

### Summary Table

| Connection | Total Resistance ($R_{eq}$) | Total Current ($I$) |
| --- | --- | --- |
| **Series** | $95\,\Omega$ | $0.126\,\text{A}$ |
| **Parallel** | $8.33\,\Omega$ | $1.44\,\text{A}$ |

Notice how the parallel connection significantly decreases the total resistance, which allows a much higher current to flow from the battery compared to the series connection.
