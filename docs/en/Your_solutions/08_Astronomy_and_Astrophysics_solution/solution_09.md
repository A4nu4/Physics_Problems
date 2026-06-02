Aristarchus from Samos (310–230 BC) was an ancient Greek astronomer who attempted to determine the relative distances and sizes of the Sun and the Moon using geometric methods based on observations of lunar phases.

At the exact half-Moon phase (dichotomy), the Earth–Moon–Sun system forms a right triangle with the right angle at the Moon. The angular separation between the Sun and the Moon observed from Earth at that moment is $\theta = 89.85^\circ$. The apparent angular diameter of both the Sun and the Moon is $\alpha = 0.53^\circ$. The average Earth–Moon distance is $d_{EM} = 3.84 \times 10^5\,\text{km}$.

Calculate:

1. The Earth–Sun distance $d_{ES}$ in km.

2. The true diameter of the Sun $D_S$ in km (use the small-angle approximation $\alpha \approx D/d$, with $\alpha$ in radians).

3. The ratio of true diameters $\frac{D_M}{D_S}$.

4. How much the value of $d_{ES}$ changes if $\theta = 89.75^\circ$ (a historically quoted value attributed to Aristarchus from Samos) is used instead of $89.85^\circ$. Briefly comment on the sensitivity of the result to the angle measurement and what this implies for Aristarchus’ method.

---

To solve these astronomical calculations based on Aristarchus' geometric methods, we will work step-by-step through the right-triangle relationships of the Earth-Moon-Sun system.

---

### 1. Calculate the Earth–Sun distance ($d_{ES}$)

At the exact half-Moon phase, the angle at the Moon is exactly $90^\circ$. Therefore, the Earth–Moon distance ($d_{EM}$) is the adjacent side to the observed angle $\theta$, and the Earth–Sun distance ($d_{ES}$) is the hypotenuse.

Using basic trigonometry:


$$\cos(\theta) = \frac{d_{EM}}{d_{ES}} \implies d_{ES} = \frac{d_{EM}}{\cos(\theta)}$$

Given $d_{EM} = 3.84 \times 10^5\,\text{km}$ and $\theta = 89.85^\circ$:


$$d_{ES} = \frac{3.84 \times 10^5\,\text{km}}{\cos(89.85^\circ)}$$

$$d_{ES} = \frac{3.84 \times 10^5}{0.00261799} \approx \mathbf{1.467 \times 10^8\,\text{km}}$$

---

### 2. Calculate the true diameter of the Sun ($D_S$)

First, we convert the apparent angular diameter $\alpha = 0.53^\circ$ into radians:


$$\alpha_{\text{rad}} = 0.53^\circ \times \frac{\pi}{180^\circ} \approx 0.0092502\,\text{rad}$$

Using the small-angle approximation $\alpha \approx \frac{D_S}{d_{ES}}$, we solve for the physical diameter of the Sun ($D_S$):


$$D_S = \alpha_{\text{rad}} \cdot d_{ES}$$

$$D_S = 0.0092502 \times (1.467 \times 10^8\,\text{km}) \approx \mathbf{1.357 \times 10^6\,\text{km}}$$

---

### 3. Calculate the ratio of true diameters ($\frac{D_M}{D_S}$)

Because the Sun and the Moon have the exact same apparent angular diameter ($\alpha = 0.53^\circ$) when viewed from Earth, their physical diameters are directly proportional to their distances from Earth:


$$\alpha = \frac{D_M}{d_{EM}} = \frac{D_S}{d_{ES}} \implies \frac{D_M}{D_S} = \frac{d_{EM}}{d_{ES}}$$

Substitute the distances into the ratio:


$$\frac{D_M}{D_S} = \frac{3.84 \times 10^5\,\text{km}}{1.467 \times 10^8\,\text{km}} \approx \mathbf{0.00262} \quad \left(\text{or roughly } \frac{1}{382}\right)$$

---

### 4. Sensitivity analysis with Aristarchus' historical value ($\theta = 89.75^\circ$)

Let's recalculate the Earth–Sun distance using the historical value:


$$d_{ES,\text{hist}} = \frac{3.84 \times 10^5\,\text{km}}{\cos(89.75^\circ)}$$

$$d_{ES,\text{hist}} = \frac{3.84 \times 10^5}{0.0043633} \approx \mathbf{8.801 \times 10^7\,\text{km}}$$

#### Change in value ($\Delta d_{ES}$):

$$\Delta d_{ES} = 1.467 \times 10^8\,\text{km} - 8.801 \times 10^7\,\text{km} \approx \mathbf{5.87 \times 10^7\,\text{km}}$$

#### Comment on Sensitivity and Methodology:

A tiny measurement discrepancy of just $0.10^\circ$ causes the calculated distance to drop by nearly **58.7 million kilometers** (a massive $40\%$ reduction).

Because $\theta$ is incredibly close to $90^\circ$, the value of $\cos(\theta)$ approaches zero, where the derivative of the secant function explodes. This makes Aristarchus' method **exceedingly sensitive** to minute experimental errors.

In antiquity, without telescopes, timing the *exact* moment of perfect dichotomy (half-Moon) and measuring angles to within fractions of a degree was impossible. Aristarchus actually estimated $\theta \approx 87^\circ$, leading him to conclude the Sun was only 19 times further away than the Moon (instead of the true value of $\sim 390$ times). While his numerical results were highly inaccurate due to this geometric sensitivity, his mathematical logic was entirely flawless and laid the groundwork for heliocentric thinking.
