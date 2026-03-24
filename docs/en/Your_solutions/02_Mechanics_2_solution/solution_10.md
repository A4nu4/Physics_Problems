To find the time-dependent physical quantities for the particle, we perform successive differentiations of the position vector $\vec{r}(t)$ with respect to time $t$.

### Given Starting Values:
* **Mass ($m$):** $0.5 \text{ kg}$
* **Position Vector:** $\vec{r}(t) = (5t^2 - t) \hat{i} + (2t^3) \hat{j} + (-3t + 2) \hat{k}$

---

### 1. Velocity $\vec{v}(t)$
Velocity is the first derivative of position with respect to time:
$$\vec{v}(t) = \frac{d\vec{r}}{dt} = \frac{d}{dt}(5t^2 - t) \hat{i} + \frac{d}{dt}(2t^3) \hat{j} + \frac{d}{dt}(-3t + 2) \hat{k}$$
$$\vec{v}(t) = (10t - 1) \hat{i} + (6t^2) \hat{j} - 3 \hat{k} \text{ (m/s)}$$

### 2. Momentum $\vec{p}(t)$
Momentum is the product of mass and velocity:
$$\vec{p}(t) = m \cdot \vec{v}(t) = 0.5 \cdot [(10t - 1) \hat{i} + 6t^2 \hat{j} - 3 \hat{k}]$$
$$\vec{p}(t) = (5t - 0.5) \hat{i} + 3t^2 \hat{j} - 1.5 \hat{k} \text{ (kg}\cdot\text{m/s)}$$

### 3. Acceleration $\vec{a}(t)$
Acceleration is the derivative of velocity with respect to time:
$$\vec{a}(t) = \frac{d\vec{v}}{dt} = \frac{d}{dt}(10t - 1) \hat{i} + \frac{d}{dt}(6t^2) \hat{j} + \frac{d}{dt}(-3) \hat{k}$$
$$\vec{a}(t) = 10 \hat{i} + 12t \hat{j} + 0 \hat{k} \text{ (m/s}^2\text{)}$$

### 4. Force $\vec{F}(t)$
According to Newton's Second Law, force is the product of mass and acceleration:
$$\vec{F}(t) = m \cdot \vec{a}(t) = 0.5 \cdot (10 \hat{i} + 12t \hat{j})$$
$$\vec{F}(t) = 5 \hat{i} + 6t \hat{j} \text{ (N)}$$

### 5. Power $P(t)$
Power is the scalar (dot) product of the force vector and the velocity vector:
$$P(t) = \vec{F}(t) \cdot \vec{v}(t)$$
$$P(t) = (5 \hat{i} + 6t \hat{j}) \cdot [(10t - 1) \hat{i} + 6t^2 \hat{j} - 3 \hat{k}]$$
$$P(t) = 5(10t - 1) + (6t)(6t^2) + (0)(-3)$$
$$P(t) = 50t - 5 + 36t^3$$
Rearranging in standard polynomial form:
$$P(t) = 36t^3 + 50t - 5 \text{ (W)}$$

---

### Summary Table
| Quantity | Time Dependence Expression |
| :--- | :--- |
| **Velocity** | $(10t - 1) \hat{i} + 6t^2 \hat{j} - 3 \hat{k}$ |
| **Momentum** | $(5t - 0.5) \hat{i} + 3t^2 \hat{j} - 1.5 \hat{k}$ |
| **Acceleration** | $10 \hat{i} + 12t \hat{j}$ |
| **Force** | $5 \hat{i} + 6t \hat{j}$ |
| **Power** | $36t^3 + 50t - 5$ |

