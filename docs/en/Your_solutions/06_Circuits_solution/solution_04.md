### 1. Simplify the Bottom Branch

The bottom branch of the parallel section contains a parallel sub-combination followed by a series resistor.

* **Parallel Sub-combination:** There are two resistors in parallel at the bottom right.
* $R_{p1} = \frac{10 \times 10}{10 + 10} = 5\,\Omega$


* **Series Addition:** This $5\,\Omega$ combination is in series with the $10\,\Omega$ resistor to its left.
* $R_{bottom} = 10\,\Omega + 5\,\Omega = 15\,\Omega$



### 2. Simplify the Top Branch

The top branch of the parallel section consists of two resistors connected in series.

* $R_{top} = 10\,\Omega + 10\,\Omega = 20\,\Omega$

### 3. Calculate the Main Parallel Block

Now, we find the equivalent resistance of the top and bottom branches that are in parallel with each other.

* $\frac{1}{R_{parallel}} = \frac{1}{R_{top}} + \frac{1}{R_{bottom}} = \frac{1}{20} + \frac{1}{15}$
* Common denominator is 60: $\frac{1}{R_{parallel}} = \frac{3}{60} + \frac{4}{60} = \frac{7}{60}$
* $R_{parallel} = \frac{60}{7} \approx 8.57\,\Omega$

### 4. Final Series Resistor

The entire parallel block is in series with the final $10\,\Omega$ resistor on the far right.

* $R_{eq} = R_{parallel} + 10\,\Omega$
* $R_{eq} = 8.57\,\Omega + 10\,\Omega = \mathbf{18.57\,\Omega}$

---

### Summary Table

| Component | Calculation | Resistance |
| --- | --- | --- |
| **Bottom Parallel Pair** | $10 \parallel 10$ | $5\,\Omega$ |
| **Bottom Branch Total** | $10 + 5$ | $15\,\Omega$ |
| **Top Branch Total** | $10 + 10$ | $20\,\Omega$ |
| **Main Parallel Block** | $20 \parallel 15$ | $8.57\,\Omega$ |
| **Total Equivalent** | $8.57 + 10$ | **$18.57\,\Omega$** |
