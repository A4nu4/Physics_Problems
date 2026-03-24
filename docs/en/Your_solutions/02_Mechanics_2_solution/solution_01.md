To solve these problems, we use the formula for the period of a simple pendulum:

$$T = 2\pi \sqrt{\frac{L}{g}}$$

Where:
* **$T$** is the period (seconds)
* **$L$** is the length of the pendulum (meters)
* **$g$** is the acceleration due to gravity (approx. **9.81 m/s²** on Earth)

---

### 1. Period of the Pendulum on the Moon

#### Given Starting Values:
* **Period on Earth ($T_E$):** $4 \text{ s}$
* **Gravity on Moon ($g_M$):** $\frac{1}{6} g_E$

#### Step-by-Step Solution:
The relationship between the period and gravity is an inverse square root: $T \propto \frac{1}{\sqrt{g}}$. We can set up a ratio between the Moon ($M$) and Earth ($E$):

$$\frac{T_M}{T_E} = \frac{2\pi \sqrt{L/g_M}}{2\pi \sqrt{L/g_E}} = \sqrt{\frac{g_E}{g_M}}$$



Substitute $g_M = \frac{g_E}{6}$:
$$\frac{T_M}{T_E} = \sqrt{\frac{g_E}{g_E/6}} = \sqrt{6}$$

Now, solve for $T_M$:
$$T_M = T_E \cdot \sqrt{6}$$
$$T_M = 4 \cdot \sqrt{6} \approx 4 \cdot 2.449$$
$$T_M \approx 9.80 \text{ s}$$

**Result:** The period on the Moon would be approximately **9.80 seconds**. Since gravity is weaker, the pendulum swings much more slowly.

---

### 2. Required Length for a 1-Second Period on Earth

#### Given Starting Values:
* **Desired Period ($T$):** $1 \text{ s}$
* **Gravity ($g$):** $9.81 \text{ m/s}^2$

#### Step-by-Step Solution:
We rearrange the period formula to solve for the length $L$:
$$T = 2\pi \sqrt{\frac{L}{g}} \implies T^2 = 4\pi^2 \frac{L}{g}$$
$$L = \frac{g \cdot T^2}{4\pi^2}$$

Substitute the values:
$$L = \frac{9.81 \cdot (1)^2}{4 \cdot \pi^2}$$
$$L \approx \frac{9.81}{39.478}$$
$$L \approx 0.248 \text{ m}$$

**Result:** To have a period of exactly 1 second on Earth, the pendulum must be approximately **24.8 cm** long.
