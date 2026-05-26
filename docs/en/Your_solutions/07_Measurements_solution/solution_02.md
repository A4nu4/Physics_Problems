The length and width of a rectangular plate are measured to be $L = (15.3 \pm 0.1)\text{ cm}$ and $W = (8.4 \pm 0.1)\text{ cm}$. Calculate the area of the plate and its uncertainty.

---

Here is the complete, step-by-step solution integrating the full breakdown of how uncertainty propagates geometrically, analytically, and statistically.


## 1. Calculating the Nominal Area

The nominal area ($A$) is the primary calculation using the measured values of length ($L$) and width ($W$):

$$A = L \times W$$

$$A = 15.3\text{ cm} \times 8.4\text{ cm} = 128.52\text{ cm}^2$$

---

## 2. Breaking Down the Uncertainty ($\Delta A$)

To calculate how the errors $\Delta L = 0.1\text{ cm}$ and $\Delta W = 0.1\text{ cm}$ affect the total area, we look at the problem through three complementary perspectives:

### Perspective A: Geometric Expansion

If we expand the area to its maximum limits, the boundary becomes:


$$A_{\text{max}} = (L + \Delta L)(W + \Delta W) = L \cdot W + L \cdot \Delta W + W \cdot \Delta L + \Delta L \cdot \Delta W$$

* **$L \cdot W$** is our starting nominal area ($128.52\text{ cm}^2$).
* **$L \cdot \Delta W$** is the error strip along the top edge ($15.3 \times 0.1 = 1.53\text{ cm}^2$).
* **$W \cdot \Delta L$** is the error strip along the side edge ($8.4 \times 0.1 = 0.84\text{ cm}^2$).
* **$\Delta L \cdot \Delta W$** is the tiny corner piece ($0.1 \times 0.1 = 0.01\text{ cm}^2$).

Because the corner piece is so small ($0.01\text{ cm}^2$) relative to the rest of the plate, it is dropped from the calculation, leaving the linear absolute uncertainty formula:


$$\Delta A \approx L \cdot \Delta W + W \cdot \Delta L$$

### Perspective B: Calculus (The Total Differential)

Using partial derivatives, we track how sensitive the total area function $A(L,W) = L \cdot W$ is to small changes in its variables:


$$\Delta A = \left| \frac{\partial A}{\partial L} \right| \Delta L + \left| \frac{\partial A}{\partial W} \right| \Delta W$$

* $\frac{\partial A}{\partial L} = W$ (Sensitivity to changes in length)
* $\frac{\partial A}{\partial W} = L$ (Sensitivity to changes in width)

Substituting these gives the exact same linear worst-case error formula:


$$\Delta A = W \cdot \Delta L + L \cdot \Delta W$$

$$\Delta A = (8.4 \times 0.1) + (15.3 \times 0.1) = 0.84 + 1.53 = 2.37\text{ cm}^2$$

### Perspective C: Statistical Independence (Quadrature)

Because it is statistically unlikely that both the length and width measurements are maxed out in error in the same direction simultaneously, standard laboratory practice combines independent fractional errors in **quadrature**:

$$\frac{\Delta A}{A} = \sqrt{\left(\frac{\Delta L}{L}\right)^2 + \left(\frac{\Delta W}{W}\right)^2}$$

Let's compute this statistical value:


$$\frac{\Delta A}{128.52} = \sqrt{\left(\frac{0.1}{15.3}\right)^2 + \left(\frac{0.1}{8.4}\right)^2}$$

$$\frac{\Delta A}{128.52} = \sqrt{(0.00653)^2 + (0.01190)^2} = \sqrt{0.0000427 + 0.0014172} = \sqrt{0.0014599} \approx 0.03821$$

$$\Delta A = 128.52 \times 0.03821 \approx 1.75\text{ cm}^2$$

---

## 3. Final Formatted Answers

Depending on the specific grading criteria of your course, the answer can be reported in two ways:

### Standard Statistical Reporting (Quadrature)

1. **Uncertainty Value:** $\Delta A \approx 1.75\text{ cm}^2$ (rounded to two significant figures).
2. **Matched Nominal Precision:** Since our uncertainty is certain up to the tenths place, we match the nominal area to the tenths place ($128.52 \rightarrow 128.52$).

$$\mathbf{A = (128.52 \pm 1.75)\text{ cm}^2}$$

### Worst-Case Reporting (Linear Sum / Partial Derivatives)

1. **Uncertainty Value:** $\Delta A \approx 2.37\text{ cm}^2$ (rounded to two significant figures).
2. **Matched Nominal Precision:** We round the nominal area to the tenths place to match the uncertainty profile ($128.52$).

$$\mathbf{A = (128.52 \pm 2.37)\text{ cm}^2}$$
