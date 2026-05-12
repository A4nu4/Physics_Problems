When using exactly three $1\,\Omega$ resistors, there are four distinct circuit topologies you can construct, each leading to a unique equivalent resistance.

---

### 1. All in Series

The resistors are connected end-to-end in a single line. The total resistance is the sum of the individual values.

* **Formula:** $R_{eq} = R_1 + R_2 + R_3$
* **Calculation:** $1\,\Omega + 1\,\Omega + 1\,\Omega = \mathbf{3\,\Omega}$

### 2. All in Parallel

The resistors are connected across the same two common nodes, providing three parallel paths for current.

* **Formula:** $\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}$
* **Calculation:** $\frac{1}{R_{eq}} = 1 + 1 + 1 = 3 \implies R_{eq} = \mathbf{\frac{1}{3}\,\Omega}$ (approx. $0.33\,\Omega$)

### 3. Combination: Two in Parallel, One in Series

Two resistors are connected in parallel to form a single block, and that block is then connected in series with the third resistor.

* **Step 1 (Parallel pair):** $R_p = \frac{R \times R}{R + R} = \frac{1 \times 1}{1 + 1} = 0.5\,\Omega$
* **Step 2 (Series addition):** $R_{eq} = 0.5\,\Omega + 1\,\Omega = \mathbf{1.5\,\Omega}$ (or $\frac{3}{2}\,\Omega$)

### 4. Combination: Two in Series, One in Parallel

Two resistors are connected in series to form a single block, and the third resistor is connected in parallel across that entire block.

* **Step 1 (Series pair):** $R_s = R + R = 1\,\Omega + 1\,\Omega = 2\,\Omega$
* **Step 2 (Parallel with third):** $R_{eq} = \frac{R_s \times R_3}{R_s + R_3} = \frac{2 \times 1}{2 + 1} = \mathbf{\frac{2}{3}\,\Omega}$ (approx. $0.67\,\Omega$)

---

### Summary of Unique Values

The four possible unique equivalent resistances are:

* **0.33 $\Omega$** ($\frac{1}{3}\,\Omega$)
* **0.67 $\Omega$** ($\frac{2}{3}\,\Omega$)
* **1.5 $\Omega$** ($\frac{3}{2}\,\Omega$)
* **3.0 $\Omega$**
