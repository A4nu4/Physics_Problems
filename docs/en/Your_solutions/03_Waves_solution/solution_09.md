To analyze the behavior of a **Damped Harmonic Oscillator**, we examine the linear second-order differential equation that balances inertial, resistive, and restoring forces.



### Given Starting Values:
* **Mass ($m$):** $m$
* **Damping coefficient ($b$):** $b$
* **Spring constant ($k$):** $k$
* **Equation of Motion:** $m \ddot{x} + b \dot{x} + kx = 0$

---

### 1. General Solution
We assume a solution of the form $x(t) = e^{rt}$. Substituting this into the differential equation yields the characteristic equation:
$$mr^2 + br + k = 0$$

Using the quadratic formula, the roots are:
$$r_{1,2} = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}$$

Let $\gamma = \frac{b}{2m}$ (damping factor) and $\omega_0 = \sqrt{\frac{k}{m}}$ (undamped natural frequency). The roots become:
$$r_{1,2} = -\gamma \pm \sqrt{\gamma^2 - \omega_0^2}$$

---

### 2. Classification of Damping Cases
The behavior of the system is determined by the discriminant $\Delta = b^2 - 4mk$:

| Case | Condition | Root Type | Physical Behavior |
| :--- | :--- | :--- | :--- |
| **Underdamped** | $b^2 < 4mk$ | Complex Conjugate | Oscillates with decaying amplitude. |
| **Critically Damped** | $b^2 = 4mk$ | Real and Repeated | Returns to equilibrium fastest without oscillation. |
| **Overdamped** | $b^2 > 4mk$ | Real and Distinct | Returns to equilibrium slowly without oscillation. |



---

### 3. Numerical Solution (RK4)
To solve this numerically using the **Runge-Kutta 4th Order (RK4)** method, we reduce the second-order ODE to a system of two first-order ODEs:
1.  $\frac{dx}{dt} = v$
2.  $\frac{dv}{dt} = -\frac{b}{m}v - \frac{k}{m}x$

Given a state vector $\mathbf{y} = [x, v]^2$, the derivative is $\mathbf{f}(t, \mathbf{y}) = [v, -\frac{b}{m}v - \frac{k}{m}x]^2$. We then iteratively calculate:
* $k_1 = h \cdot f(t_n, y_n)$
* $k_2 = h \cdot f(t_n + \frac{h}{2}, y_n + \frac{k_1}{2})$
* $k_3 = h \cdot f(t_n + \frac{h}{2}, y_n + \frac{k_2}{2})$
* $k_4 = h \cdot f(t_n + h, y_n + k_3)$
* $y_{n+1} = y_n + \frac{1}{6}(k_1 + 2k_2 + 2k_3 + k_4)$

---

### 4. Effect of Parameter $b$
* **Increasing $b$ (Underdamped range):** Increases the rate of decay ($e^{-\gamma t}$) and decreases the frequency of oscillation $\omega_d = \sqrt{\omega_0^2 - \gamma^2}$.
* **At $b = 2\sqrt{mk}$:** The system transitions to critical damping, where the "swing" is perfectly suppressed.
* **Increasing $b$ (Overdamped range):** The "viscous" resistance dominates. The system becomes "sluggish," taking more time to reach $x=0$ as $b$ increases.

---

### 5. Graph of $x(t)$ and 6. Phase Portrait
* **$x(t)$ Graph:** Underdamped cases show a sine wave bounded by an exponential envelope. Overdamped cases look like a decaying exponential.
* **Phase Portrait ($v$ vs $x$):** * **Underdamped:** An inward spiral toward the origin $(0,0)$.
    * **Overdamped/Critical:** A direct curve toward the origin without circling it.

