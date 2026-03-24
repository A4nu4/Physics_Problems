To analyze the vertical motion of a projectile under linear air resistance (Stokes' drag), we solve the differential equation derived from Newton's Second Law.

### Given Starting Values:
* **Mass ($m$):** $m$
* **Initial Velocity ($v_0$):** $v(0)$
* **Initial Position ($x_0$):** $10 \text{ m}$
* **Gravity ($g$):** $9.81 \text{ m/s}^2$
* **Drag Coefficient ($k$):** $k$

---

### 1. Analytical Solution

#### Velocity $v(t)$
The equation of motion is:
$$m\frac{dv}{dt} = -mg - kv$$

We separate variables and integrate:
$$\int_{v_0}^{v} \frac{dv}{g + \frac{k}{m}v} = -\int_{0}^{t} dt$$

Solving for $v(t)$ yields:
$$v(t) = \left(v_0 + \frac{mg}{k}\right)e^{-\frac{k}{m}t} - \frac{mg}{k}$$

As $t \to \infty$, the velocity approaches the **terminal velocity**: $v_{term} = -\frac{mg}{k}$.

#### Position $x(t)$
Integrating the velocity function with respect to time, using the initial condition $x(0) = 10$:
$$x(t) = 10 + \int_{0}^{t} \left[\left(v_0 + \frac{mg}{k}\right)e^{-\frac{k}{m}t'} - \frac{mg}{k}\right] dt'$$
$$x(t) = 10 + \frac{m}{k}\left(v_0 + \frac{mg}{k}\right)\left(1 - e^{-\frac{k}{m}t}\right) - \frac{mg}{k}t$$

---

### 2. Determine the Maximum Height
The projectile reaches its maximum height $H$ when the velocity is zero ($v(t_{max}) = 0$).

**Step 1: Find the time to reach peak ($t_{max}$)**
$$0 = \left(v_0 + \frac{mg}{k}\right)e^{-\frac{k}{m}t_{max}} - \frac{mg}{k}$$
$$t_{max} = \frac{m}{k} \ln\left(1 + \frac{kv_0}{mg}\right)$$

**Step 2: Calculate Maximum Height ($H$)**
Substitute $t_{max}$ back into the position equation:
$$H = 10 + \frac{mv_0}{k} - \frac{m^2g}{k^2} \ln\left(1 + \frac{kv_0}{mg}\right)$$

---

### 3. Comparison with the Case Without Drag ($k=0$)

In a vacuum, the motion follows standard kinematic equations:
* **Velocity:** $v(t) = v_0 - gt$
* **Height:** $x(t) = 10 + v_0t - \frac{1}{2}gt^2$
* **Max Height:** $H_{vac} = 10 + \frac{v_0^2}{2g}$

#### Key Observations:
* **Height:** $H_{drag}$ is always lower than $H_{vac}$ because the drag force performs negative work, dissipating mechanical energy as heat.
* **Symmetry:** In a vacuum, the time to rise is equal to the time to fall to the same level. With drag, the upward trip is faster than the downward trip because gravity and drag act together on the way up, but oppose each other on the way down.
* **Terminal Velocity:** In the vacuum case, speed increases linearly forever. With drag, the object eventually stops accelerating and falls at a constant speed.
