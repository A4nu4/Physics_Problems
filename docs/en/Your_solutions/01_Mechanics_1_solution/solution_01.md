To solve for the projectile's motion, we define a coordinate system where the origin $(0, 0)$ is the launch point, $x$ is horizontal, and $y$ is vertical (upward positive).

### 1. Components of Initial Velocity

First, we resolve the initial velocity $v_0 = 100 \text{ m/s}$ into horizontal and vertical components:

* $v_{0x} = v_0 \cos(37^\circ) \approx 100 \times 0.7986 = 79.86 \text{ m/s}$
* $v_{0y} = v_0 \sin(37^\circ) \approx 100 \times 0.6018 = 60.18 \text{ m/s}$

---

### 2. Derivation of the Differential Equations of Motion

Applying Newton's Second Law ($F = m a$):

**Horizontal Direction ($x$):**
There are no horizontal forces (ignoring air resistance).


$$F_x = m \frac{d^2x}{dt^2} = 0$$

$$\frac{d^2x}{dt^2} = 0$$


Integrating once with initial condition $v_x(0) = v_{0x}$:


$$\frac{dx}{dt} = v_{0x}$$


Integrating again with initial condition $x(0) = 0$:


$$x(t) = v_{0x} t$$

**Vertical Direction ($y$):**
The only force is gravity acting downward.


$$F_y = m \frac{d^2y}{dt^2} = -mg$$

$$\frac{d^2y}{dt^2} = -g$$


Integrating once with initial condition $v_y(0) = v_{0y}$:


$$\frac{dy}{dt} = v_{0y} - gt$$


Integrating again with initial condition $y(0) = 0$:


$$y(t) = v_{0y} t - \frac{1}{2}gt^2$$

---

### 3. Determine the Time of Flight ($T$)

The projectile returns to the ground when $y(t) = 0$:


$$v_{0y} T - \frac{1}{2}gT^2 = 0$$

$$T \left(v_{0y} - \frac{1}{2}gT\right) = 0$$


Solving for $T$ (ignoring $T=0$):


$$T = \frac{2 v_{0y}}{g}$$


Using $g = 9.8 \text{ m/s}^2$ and $v_{0y} \approx 60.18 \text{ m/s}$:


$$T = \frac{2 \times 60.18}{9.8} \approx \mathbf{12.28 \text{ s}}$$

---

### 4. Determine the Maximum Height ($H$)

Maximum height occurs when the vertical velocity is zero ($\frac{dy}{dt} = 0$):


$$v_{0y} - gt_h = 0 \implies t_h = \frac{v_{0y}}{g}$$


Substitute $t_h$ into the equation for $y(t)$:


$$H = v_{0y} \left(\frac{v_{0y}}{g}\right) - \frac{1}{2}g \left(\frac{v_{0y}}{g}\right)^2 = \frac{v_{0y}^2}{2g}$$

$$H = \frac{(60.18)^2}{2 \times 9.8} \approx \mathbf{184.79 \text{ m}}$$

---

### 5. Determine the Range ($R$)

The range is the horizontal distance traveled during the total time of flight $T$:


$$R = x(T) = v_{0x} \times T$$

$$R = 79.86 \times 12.28 \approx \mathbf{980.88 \text{ m}}$$

---

### Summary Table

| Parameter | Value |
| --- | --- |
| **Initial Velocity ($v_0$)** | $100 \text{ m/s}$ |
| **Launch Angle ($\theta$)** | $37^\circ$ |
| **Time of Flight ($T$)** | $\approx 12.28 \text{ s}$ |
| **Maximum Height ($H$)** | $\approx 184.79 \text{ m}$ |
| **Range ($R$)** | $\approx 980.88 \text{ m}$ |




