To show that the maximum range is achieved at $45^\circ$, we start with the range formula and apply calculus to find its maximum value.

### Given Values:

* **Initial Velocity:** $v_0$
* **Acceleration due to gravity:** $g$
* **Launch Angle:** $\theta$
* **Range Formula:** $R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$

---

### Analytical Proof

#### 1. The Condition for a Maximum

To find the angle $\theta$ that maximizes the range $R$, we must find the derivative of $R$ with respect to $\theta$ and set it to zero:


$$\frac{dR}{d\theta} = 0$$

#### 2. Differentiating the Range Equation

The terms $v_0$ and $g$ are constants for this problem. We apply the chain rule to the trigonometric function $\sin(2\theta)$:


$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot \frac{d}{d\theta}(\sin(2\theta))$$

$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot \cos(2\theta) \cdot 2$$

$$\frac{dR}{d\theta} = \frac{2v_0^2 \cos(2\theta)}{g}$$

#### 3. Solving for $\theta$

Set the derivative equal to zero to find the critical point:


$$\frac{2v_0^2 \cos(2\theta)}{g} = 0$$

Since $\frac{2v_0^2}{g}$ cannot be zero (otherwise there is no motion), we must have:


$$\cos(2\theta) = 0$$

The cosine function is zero at $90^\circ$ (or $\frac{\pi}{2}$ radians) within the physical limits of a projectile launch:


$$2\theta = 90^\circ$$

$$\theta = 45^\circ$$

#### 4. Verification (Second Derivative Test)

To ensure this is a maximum and not a minimum, we check the second derivative:


$$\frac{d^2R}{d\theta^2} = -\frac{4v_0^2 \sin(2\theta)}{g}$$


At $\theta = 45^\circ$, $\sin(90^\circ) = 1$, so:


$$\frac{d^2R}{d\theta^2} = -\frac{4v_0^2}{g}$$


Since the second derivative is **negative**, the point $\theta = 45^\circ$ is indeed a **local maximum**.

---

### Conclusion

Analytically, the maximum range of a projectile (ignoring air resistance) occurs at **$45^\circ$**. At this angle, the factor $\sin(2\theta)$ reaches its maximum possible value of **$1$**, resulting in:


$$R_{max} = \frac{v_0^2}{g}$$



