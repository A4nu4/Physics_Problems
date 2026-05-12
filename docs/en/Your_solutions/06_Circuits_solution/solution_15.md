To find the equivalent resistance $R_{eq}$ between two opposite corners (the body diagonal) of a resistor cube, we can use the principle of **symmetry** and **equipotential nodes**.

### 1. Visualizing the Current Flow

Imagine a current $I$ entering one corner (Node A) and exiting the opposite corner (Node B).

* **At Node A:** The current splits equally into the **3 edges** connected to it because the path to the opposite corner is symmetrical for all three. Each edge carries a current of $I/3$.
* **At the Next Set of Nodes:** Each of those 3 currents reaches a junction where it splits into **2 more edges**. This means these 6 edges each carry a current of $I/6$.
* **At Node B:** The currents recombine. The 3 edges connected directly to the exit node each carry $I/3$ to form the total current $I$ again.

---

### 2. Calculating Total Voltage Drop

The total voltage $V$ across the opposite corners is the sum of the voltage drops along any single path from A to B. Let’s follow one path:

1. **First segment:** $V_1 = \frac{I}{3} \cdot R$
2. **Second segment:** $V_2 = \frac{I}{6} \cdot R$
3. **Third segment:** $V_3 = \frac{I}{3} \cdot R$

The total voltage $V_{total}$ is:


$$V_{total} = \left( \frac{1}{3}IR \right) + \left( \frac{1}{6}IR \right) + \left( \frac{1}{3}IR \right)$$


To add these, find a common denominator (6):


$$V_{total} = \left( \frac{2}{6} + \frac{1}{6} + \frac{2}{6} \right) IR = \frac{5}{6} IR$$

---

### 3. Finding Equivalent Resistance

Using Ohm's Law ($V = I \cdot R_{eq}$), we set the total voltage equal to the equivalent resistance:


$$I \cdot R_{eq} = \frac{5}{6} IR$$

Dividing both sides by $I$:


$$R_{eq} = \frac{5}{6}R$$

### Summary of Resistance by Connection Type

While the opposite corners (body diagonal) is the most common problem, the resistance changes depending on where you connect the battery:

| Connection Points | Equivalent Resistance ($R_{eq}$) |
| --- | --- |
| **Opposite Corners (Body Diagonal)** | $\frac{5}{6}R$ |
| **Face Diagonal (Across one side)** | $\frac{3}{4}R$ |
| **Adjacent Corners (One edge)** | $\frac{7}{12}R$ |
