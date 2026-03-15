To show analytically that the maximum range is achieved at $45^\circ$, we start with the derivation of the range formula and then apply calculus to find its maximum value.

### 1. The Range Equation

The horizontal range $R$ of a projectile launched from the ground with an initial velocity $v_0$ at an angle $\theta$ is given by:


$$R = \frac{v_0^2 \sin(2\theta)}{g}$$

This formula is derived from the horizontal distance $x(t) = v_0 \cos(\theta) t$ and the total time of flight $T = \frac{2v_0 \sin(\theta)}{g}$. Substituting $T$ into the distance equation yields:


$$R = v_0 \cos(\theta) \left( \frac{2v_0 \sin(\theta)}{g} \right) = \frac{2v_0^2 \sin(\theta) \cos(\theta)}{g}$$


Using the trigonometric identity $2 \sin(\theta) \cos(\theta) = \sin(2\theta)$, we arrive at the standard range formula.

---

### 2. Analytical Optimization

To find the angle $\theta$ that maximizes the range $R(\theta)$, we take the derivative of the range with respect to $\theta$ and set it to zero.

**Step 1: Differentiate $R$ with respect to $\theta$**


$$\frac{dR}{d\theta} = \frac{d}{d\theta} \left( \frac{v_0^2 \sin(2\theta)}{g} \right)$$


Since $v_0$ and $g$ are constants for a given launch:


$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot \frac{d}{d\theta} (\sin(2\theta))$$


Applying the chain rule:


$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot 2 \cos(2\theta)$$

**Step 2: Set the derivative to zero**
To find the critical point, we set $\frac{dR}{d\theta} = 0$:


$$\frac{2v_0^2 \cos(2\theta)}{g} = 0$$


Since $\frac{2v_0^2}{g} \neq 0$, we must have:


$$\cos(2\theta) = 0$$

**Step 3: Solve for $\theta$**
The cosine function is zero when the argument is $90^\circ$ (or $\frac{\pi}{2}$ radians):


$$2\theta = 90^\circ$$

$$\theta = 45^\circ$$

---

### 3. Verification (Second Derivative Test)

To confirm this critical point is a maximum, we check the second derivative:


$$\frac{d^2R}{d\theta^2} = \frac{d}{d\theta} \left( \frac{2v_0^2 \cos(2\theta)}{g} \right) = -\frac{4v_0^2 \sin(2\theta)}{g}$$


At $\theta = 45^\circ$:


$$\frac{d^2R}{d\theta^2} = -\frac{4v_0^2 \sin(90^\circ)}{g} = -\frac{4v_0^2}{g}$$


Since the second derivative is **negative**, the range $R$ reaches its **maximum** value at $\theta = 45^\circ$.

### Conclusion

At $45^\circ$, the term $\sin(2\theta)$ reaches its maximum possible value of **1**. Therefore:


$$R_{\text{max}} = \frac{v_0^2}{g}$$



