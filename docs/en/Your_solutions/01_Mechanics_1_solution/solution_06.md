To find the position and acceleration, we use the relationships between position, velocity, and acceleration through calculus.

### Given Values:

* **Velocity Function:** $v(t) = t^2 + 2t - 5$
* **Initial Position:** $x(0) = 4$
* **Target Time:** $t = 3$

---

### Step 1: Find the Acceleration at $t=3$

Acceleration $a(t)$ is the first derivative of velocity with respect to time:


$$a(t) = \frac{dv}{dt}$$

Differentiating $v(t) = t^2 + 2t - 5$:

* $a(t) = 2t + 2$

Now, substitute $t = 3$:

* $a(3) = 2(3) + 2$
* $a(3) = 8$

**Acceleration Result:** $8 \text{ units/s}^2$

---

### Step 2: Find the Position Function $x(t)$

Position $x(t)$ is the integral of the velocity function:


$$x(t) = \int v(t) \, dt$$

$$x(t) = \int (t^2 + 2t - 5) \, dt$$

$$x(t) = \frac{1}{3}t^3 + t^2 - 5t + C$$

To find the constant $C$, we use the initial condition $x(0) = 4$:

* $4 = \frac{1}{3}(0)^3 + (0)^2 - 5(0) + C$
* $C = 4$

So, the position function is:


$$x(t) = \frac{1}{3}t^3 + t^2 - 5t + 4$$

---

### Step 3: Find the Position at $t=3$

Substitute $t = 3$ into the position function:

* $x(3) = \frac{1}{3}(3)^3 + (3)^2 - 5(3) + 4$
* $x(3) = \frac{1}{3}(27) + 9 - 15 + 4$
* $x(3) = 9 + 9 - 15 + 4$
* $x(3) = 7$

**Position Result:** $7 \text{ units}$

---

### Final Results at $t=3$:

* **Acceleration:** $8 \text{ units/s}^2$
* **Position:** $7 \text{ units}$

