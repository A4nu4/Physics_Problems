The length and width of a rectangular plate are measured to be $L = (15.3 \pm 0.1)\text{ cm}$ and $W = (8.4 \pm 0.1)\text{ cm}$. Calculate the area of the plate and its uncertainty.

---

To find the area of the rectangular plate and its associated uncertainty, we use the formula for the area of a rectangle and apply the standard rules of **error propagation** for independent variables.


### 1. Calculate the Area ($A$)

The formula for the area of a rectangle is:


$$A = L \times W$$

Using the measured values $L = 15.3\text{ cm}$ and $W = 8.4\text{ cm}$:


$$A = 15.3 \times 8.4 = 128.52\text{ cm}^2$$

---

### 2. Calculate the Uncertainty in Area ($\Delta A$)

Since the length and width are independent measurements, their uncertainties combine in quadrature (using the root-sum-of-squares of the fractional uncertainties):

$$\frac{\Delta A}{A} = \sqrt{\left(\frac{\Delta L}{L}\right)^2 + \left(\frac{\Delta W}{W}\right)^2}$$

Solving directly for the absolute uncertainty $\Delta A$:


$$\Delta A = A \cdot \sqrt{\left(\frac{\Delta L}{L}\right)^2 + \left(\frac{\Delta W}{W}\right)^2}$$

Substitute the known values ($L = 15.3\text{ cm}$, $\Delta L = 0.1\text{ cm}$, $W = 8.4\text{ cm}$, $\Delta W = 0.1\text{ cm}$, and $A = 128.52\text{ cm}^2$):

$$\Delta A = 128.52 \cdot \sqrt{\left(\frac{0.1}{15.3}\right)^2 + \left(\frac{0.1}{8.4}\right)^2}$$

$$\Delta A = 128.52 \cdot \sqrt{(0.006536)^2 + (0.011905)^2}$$

$$\Delta A = 128.52 \cdot \sqrt{0.00004272 + 0.00014173}$$

$$\Delta A = 128.52 \cdot \sqrt{0.00018445}$$

$$\Delta A = 128.52 \cdot 0.013581 \approx 1.75\text{ cm}^2$$

---

### 3. Rounding to Proper Significant Figures

Following standard scientific measurement conventions:

* The uncertainty $\Delta A \approx 1.75\text{ cm}^2$ is typically rounded to one or two significant figures. Since it begins with a 1, keeping two figures is standard practice: $\Delta A \approx 1.7\text{ cm}^2$.
* The value of the area is then rounded to match the same decimal place (the tenths place): $128.5\text{ cm}^2$.

*(Note: If your course strictly rounds all uncertainties to a single significant digit, it would be $\Delta A \approx 2\text{ cm}^2$, making the final area $129\text{ cm}^2$.)*

---

### Final Result:

The area of the plate with its propagated uncertainty is:


$$A = (128.52 \pm 1.75)\text{ cm}^2$$

