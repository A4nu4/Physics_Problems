
To determine which functions describe a traveling wave, we test whether they satisfy the linear wave equation:

$$\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}$$

A general property of the wave equation is that any function of the form $f(x - vt)$ or $f(x + vt)$ is a valid solution, representing a wave traveling at speed $v$ in the positive or negative $x$-direction, respectively.



---

### a) $y(x,t) = A \cos(kx^2 - \omega t)$

First, let's find the second derivatives:


$$\frac{\partial y}{\partial x} = -2Akx \sin(kx^2 - \omega t)$$


$$\frac{\partial^2 y}{\partial x^2} = -2Ak \sin(kx^2 - \omega t) - 4Ak^2x^2 \cos(kx^2 - \omega t)$$


Now for the time derivatives:


$$\frac{\partial y}{\partial t} = A\omega \sin(kx^2 - \omega t)$$


$$\frac{\partial^2 y}{\partial t^2} = -A\omega^2 \cos(kx^2 - \omega t)$$


If we substitute these into the wave equation, the terms do not cancel out because of the $x$ and $x^2$ factors in the spatial derivative. Also, the argument $(kx^2 - \omega t)$ cannot be factored into the form $(x \pm vt)$.

**Result:** Function (a) **cannot** describe a traveling wave.

---

### b) $y(x,t) = A(x-vt)^2$

This function is already in the form $f(x - vt)$ where $f(u) = Au^2$. Let's verify with the wave equation:


$$\frac{\partial y}{\partial x} = 2A(x-vt)$$


$$\frac{\partial^2 y}{\partial x^2} = 2A$$


Now for time:


$$\frac{\partial y}{\partial t} = -2Av(x-vt)$$


$$\frac{\partial^2 y}{\partial t^2} = 2Av^2$$


Check the wave equation:


$$\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2} \implies 2A = \frac{1}{v^2} (2Av^2) = 2A$$


**Result:** Function (b) **can** describe a traveling wave.

---

### c) $y(x,t) = A \log(x+vt)$

This function is in the form $f(x + vt)$ where $f(u) = A \log(u)$.


$$\frac{\partial y}{\partial x} = \frac{A}{x+vt}$$


$$\frac{\partial^2 y}{\partial x^2} = -\frac{A}{(x+vt)^2}$$


Now for time:


$$\frac{\partial y}{\partial t} = \frac{Av}{x+vt}$$


$$\frac{\partial^2 y}{\partial t^2} = -\frac{Av^2}{(x+vt)^2}$$


Check the wave equation:


$$\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \left( -\frac{Av^2}{(x+vt)^2} \right) = -\frac{A}{(x+vt)^2}$$


**Result:** Function (c) **can** describe a traveling wave.

---

### Summary
Functions **(b)** and **(c)** can describe traveling waves because they satisfy the wave equation and follow the general form $f(x \pm vt)$. Function **(a)** fails because its phase depends on $x^2$, causing the wave to change shape as it moves (it is dispersive).
