To describe a series RLC circuit, we apply Kirchhoff’s Voltage Law (KVL), which states that the sum of the voltages across the components must equal the source voltage $V(t)$.

### 1. The Differential Equation

The voltage drops across the resistor, inductor, and capacitor are given by $V_R = IR$, $V_L = L \frac{dI}{dt}$, and $V_C$ respectively. The relationship between current and the voltage across the capacitor is $I(t) = C \frac{dV_C}{dt}$.

Substituting these into the KVL equation ($V_L + V_R + V_C = V$) and expressing everything in terms of $V_C(t)$, we obtain a second-order linear differential equation:

$$LC \frac{d^2V_C(t)}{dt^2} + RC \frac{dV_C(t)}{dt} + V_C(t) = V(t)$$

Dividing by $LC$ provides the standard form:


$$\frac{d^2V_C}{dt^2} + \frac{R}{L} \frac{dV_C}{dt} + \frac{1}{LC} V_C = \frac{V(t)}{LC}$$

---

### 2. Comparison to a Damped Harmonic Oscillator

The motion of a damped harmonic oscillator (such as a mass on a spring with friction) is governed by the equation:


$$m \frac{d^2x}{dt^2} + b \frac{dx}{dt} + kx = F(t)$$

Where:

* **$m$** is the mass.
* **$b$** is the damping coefficient (friction).
* **$k$** is the spring constant.
* **$x$** is the displacement.
* **$F(t)$** is the external driving force.

---

### 3. Analogies Between the Two Systems

The mathematical structure of these equations is identical, leading to the following physical analogies:

| RLC Circuit Term | Mechanical Oscillator Term | Physical Role |
| --- | --- | --- |
| **Inductance ($L$)** | **Mass ($m$)** | Represents inertia (resistance to change in state). |
| **Resistance ($R$)** | **Damping Coefficient ($b$)** | Represents the dissipation of energy. |
| **Reciprocal Capacitance ($1/C$)** | **Spring Constant ($k$)** | Represents the "stiffness" or restorative property. |
| **Voltage ($V$)** | **Driving Force ($F$)** | The external input driving the system. |
| **Charge ($q$) or Voltage ($V_C$)** | **Displacement ($x$)** | The primary variable describing the state. |
| **Current ($I$)** | **Velocity ($v$)** | The rate of change of the primary variable. |

