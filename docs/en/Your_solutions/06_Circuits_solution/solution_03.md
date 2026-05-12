### 1. Identify the Internal Series Branches

Looking at the diagram, there are two vertical branches where resistors are clearly in a single line (series):

* **The Left-Inner Branch:** Two resistors are in series.
* $R_{series1} = 5\,\Omega + 5\,\Omega = 10\,\Omega$


* **The Far-Right Branch:** Two resistors are in series.
* $R_{series2} = 5\,\Omega + 5\,\Omega = 10\,\Omega$



### 2. Identify the Parallel Group

The middle-left section of the circuit consists of two parallel paths. One path is the single horizontal resistor on the far left (top), and the other is the vertical series branch we just calculated ($10\,\Omega$). However, looking closer at the nodes:

* The top-left loop has three resistors ($5\,\Omega$ top, $5\,\Omega$ left, $5\,\Omega$ bottom) essentially forming a loop around the $10\,\Omega$ branch.
* Actually, a simpler way to view this is that the **entire left section** and the **entire right section** are branches connected to the main horizontal line.

Let's re-examine the nodes from the input terminals (left to right):

1. **Leftmost Loop:** The three resistors on the left (top, left, bottom-inner) are in series with each other ($15\,\Omega$).
2. **Central Branch:** This $15\,\Omega$ loop is in parallel with the inner vertical branch ($10\,\Omega$).
* $\frac{1}{R_{left\_block}} = \frac{1}{15} + \frac{1}{10} = \frac{2+3}{30} = \frac{5}{30} \implies R_{left\_block} = 6\,\Omega$.


3. **Rightmost Branch:** The two resistors on the far right ($10\,\Omega$ total) are in parallel with the rest of the circuit.
4. **Bottom Resistor:** There is a final $5\,\Omega$ resistor on the bottom wire between the two main nodes.

### 3. Final Calculation

The circuit simplifies to the left block ($6\,\Omega$) in parallel with the far-right branch ($10\,\Omega$), and that combination is in parallel with the single bottom resistor ($5\,\Omega$).

$$\frac{1}{R_{eq}} = \frac{1}{6} + \frac{1}{10} + \frac{1}{5}$$

$$\frac{1}{R_{eq}} = \frac{5}{30} + \frac{3}{30} + \frac{6}{30} = \frac{14}{30}$$

$$R_{eq} = \frac{30}{14} \approx \mathbf{2.14\,\Omega}$$

---

**Summary of Steps:**

* Combine vertical series pairs first ($10\,\Omega$ each).
* Identify parallel nodes to group the left, center, and right sections.
* Calculate the final reciprocal sum for the parallel arrangement.
