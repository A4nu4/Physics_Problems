To analyze the one-dimensional force $F(x) = -kx$, we treat it as a linear restoring force, characteristic of a simple harmonic oscillator.

### Given Starting Values:
* **Force ($F$):** $-kx$
* **Mass ($m$):** $m$
* **Spring Constant ($k$):** $k$ (a positive constant)
* **Initial Position ($x_0$):** $x(0)$
* **Initial Velocity ($v_0$):** $0$ (released from rest)

---

### 1. Equation of Motion and Solution
Using Newton's Second Law ($F = ma$):
$$m \frac{d^2x}{dt^2} = -kx$$

Rearranging into the standard differential equation for simple harmonic motion:
$$\frac{d^2x}{dt^2} + \frac{k}{m}x = 0$$

Let $\omega^2 = \frac{k}{m}$, where $\omega$ is the angular frequency. The equation becomes:
$$\ddot{x} + \omega^2 x = 0$$

The general solution is:
$$x(t) = A \cos(\omega t + \phi)$$

For a mass released from rest at $x_0$ at $t=0$, the specific solution is:
$$x(t) = x_0 \cos\left(\sqrt{\frac{k}{m}} \cdot t\right)$$

---

### 2. Work Done from $0$ to $x_0$
The work $W$ done by the force $F(x)$ during a displacement from $x = 0$ to $x = x_0$ is calculated by integrating the force over the distance:
$$W = \int_{0}^{x_0} F(x) \, dx$$
$$W = \int_{0}^{x_0} (-kx) \, dx$$
$$W = \left[ -\frac{1}{2}kx^2 \right]_0^{x_0}$$
$$W = -\frac{1}{2}kx_0^2$$

The work done by the restoring force is **negative** because the force acts in the opposite direction of the displacement.

---

### 3. Interpretation as Potential Energy
Potential energy $U(x)$ is defined such that the change in potential energy is the negative of the work done by the conservative force:
$$\Delta U = -W$$
$$U(x) - U(0) = - \int_{0}^{x} (-kx') \, dx'$$
$$U(x) - U(0) = \frac{1}{2}kx^2$$

By setting the reference point $U(0) = 0$ at the equilibrium position, we obtain:
$$U(x) = \frac{1}{2}kx^2$$

This shows that the energy stored in the system increases quadratically as the object is moved away from the equilibrium point.

---

### 4. Verifying the Relationship $F = -\frac{dU}{dx}$
We take the negative derivative of the potential energy function with respect to $x$:
$$-\frac{dU}{dx} = -\frac{d}{dx}\left(\frac{1}{2}kx^2\right)$$
$$-\frac{dU}{dx} = -(k \cdot x)$$
$$-\frac{dU}{dx} = -kx$$

Since this result is identical to our original force equation $F(x) = -kx$, the relationship is verified.

---

### 5. Description of the Graphs
* **Force $F(x)$:** This is a linear function with a negative slope ($-k$). It passes through the origin $(0,0)$. For positive $x$, $F$ is negative; for negative $x$, $F$ is positive. This visualizes the "restoring" nature of the force.
* **Potential Energy $U(x)$:** This is a parabola opening upward, centered at the origin. Regardless of whether $x$ is positive or negative, $U(x)$ remains positive, representing energy stored by the displacement.
