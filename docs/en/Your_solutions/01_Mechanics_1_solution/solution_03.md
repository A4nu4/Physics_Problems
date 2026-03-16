To determine if Alice and Bob collide or how close they get, we need to analyze their positions $A(t)$ and $B(t)$ over time.

### 1. Do the paths intersect?

An intersection of **paths** means there exist times $t_1$ and $t_2$ such that $A(t_1) = B(t_2)$. For a **collision**, we must have $t_1 = t_2 = t$. Let's check for a collision first by setting the coordinates equal for the same time $t$:

**Horizontal position ($x$):**


$$2 + t = 2t - 1 \implies t = 3$$

**Vertical position ($y$):**


$$8 - 3t = 2t + 2 \implies 5t = 6 \implies t = 1.2$$

Since the times required for the $x$ and $y$ coordinates to match are different ($3 \neq 1.2$), **Alice and Bob do not collide.**

---

### 2. Determine the Minimum Distance

To find the minimum distance, we look at the displacement vector between them at any time $t$:


$$D(t) = B(t) - A(t)$$

$$D(t) = ((2t - 1) - (2 + t), (2t + 2) - (8 - 3t))$$

$$D(t) = (t - 3, 5t - 6)$$

The square of the distance $f(t) = d^2$ is:


$$f(t) = (t - 3)^2 + (5t - 6)^2$$


Expanding the terms:


$$f(t) = (t^2 - 6t + 9) + (25t^2 - 60t + 36)$$

$$f(t) = 26t^2 - 66t + 45$$

---

### 3. Minimize the Distance Function

To find when the distance is at its minimum, we take the derivative of $f(t)$ and set it to zero:


$$f'(t) = 52t - 66$$


Setting $f'(t) = 0$:


$$52t = 66 \implies t = \frac{66}{52} = \frac{33}{26} \approx \mathbf{1.27 \text{ s}}$$

---


### Revised Step 4: Calculate the Minimum Distance

Using the positions $A(t) = (2+t, 8-3t)$ and $B(t) = (2t-1, 2t+2)$, we first find the difference in their coordinates:

* $\Delta x = (2t - 1) - (2 + t) = t - 3$
* $\Delta y = (2t + 2) - (8 - 3t) = 5t - 6$

Now, apply the **squared distance formula**:


$$d^2 = (t - 3)^2 + (5t - 6)^2$$


Expanding this gives the quadratic function we minimized earlier:


$$f(t) = 26t^2 - 66t + 45$$

Finally, substitute the time of closest approach $t = \frac{33}{26}$ back into this formula:

$$d^2 = 26\left(\frac{33}{26}\right)^2 - 66\left(\frac{33}{26}\right) + 45$$

$$d^2 = \frac{1089}{26} - \frac{2178}{26} + \frac{1170}{26}$$

$$d^2 = \frac{81}{26} \approx 3.115$$

Taking the square root to find the actual minimum distance:

$$d = \sqrt{\frac{81}{26}} = \frac{9}{\sqrt{26}} \approx \mathbf{1.765 \text{ units}}$$

### Summary

* **Collision:** No.
* **Time of closest approach:** $t \approx 1.27 \text{ s}$
* **Minimum distance:** $\approx 1.765 \text{ units}$
