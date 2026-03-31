To find the resulting standing wave, we apply the **Principle of Superposition**, which states that the net displacement is the algebraic sum of the individual displacements of the two waves.



### Given Starting Values:
* **Wave 1 (Right-moving):** $y_1(x, t) = A \sin(kx - \omega t)$
* **Wave 2 (Left-moving):** $y_2(x, t) = A \sin(kx + \omega t)$
* **Amplitude ($A$):** $A$
* **Wave Number ($k$):** $k = \frac{2\pi}{\lambda}$
* **Angular Frequency ($\omega$):** $\omega = 2\pi f$

---

### 1. Derive the Standing Wave Equation

We sum the two wave functions:


$$y_{net} = y_1 + y_2 = A \sin(kx - \omega t) + A \sin(kx + \omega t)$$


Using the trigonometric identity $\sin(\alpha) + \sin(\beta) = 2 \sin\left(\frac{\alpha + \beta}{2}\right) \cos\left(\frac{\alpha - \beta}{2}\right)$, we let:
* $\alpha = kx + \omega t$
* $\beta = kx - \omega t$

Substituting these into the identity:


$$\frac{\alpha + \beta}{2} = \frac{(kx + \omega t) + (kx - \omega t)}{2} = kx$$


$$\frac{\alpha - \beta}{2} = \frac{(kx + \omega t) - (kx - \omega t)}{2} = \omega t$$


**The Resulting Standing Wave Equation:**


$$y(x, t) = [2A \sin(kx)] \cos(\omega t)$$

---

### 2. Identify the Positions of the Nodes

Nodes are positions where the displacement is always zero ($y = 0$) for all values of $t$. This occurs when the spatial part of the equation, $\sin(kx)$, equals zero.


$$\sin(kx) = 0$$


This condition is met when the argument $kx$ is an integer multiple of $\pi$:


$$kx = n\pi \quad \text{where } n = 0, \pm 1, \pm 2, \dots$$


Substitute $k = \frac{2\pi}{\lambda}$ to find the positions $x$:


$$\left(\frac{2\pi}{\lambda}\right)x = n\pi$$


$$x = n \frac{\lambda}{2}$$


**Result:** Nodes occur at intervals of half a wavelength: **$x = 0, \frac{\lambda}{2}, \lambda, \frac{3\lambda}{2}, \dots$**



---

### 3. Identify the Positions of the Antinodes (Optional)

Antinodes are positions where the amplitude is maximum ($|y| = 2A$). This occurs when $|\sin(kx)| = 1$:


$$kx = \left(n + \frac{1}{2}\right)\pi$$


$$x = \left(n + \frac{1}{2}\right)\frac{\lambda}{2}$$


**Result:** Antinodes occur midway between the nodes: **$x = \frac{\lambda}{4}, \frac{3\lambda}{4}, \frac{5\lambda}{4}, \dots$**

