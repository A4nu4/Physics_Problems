To find the rectangle with the maximum area under the curve $y = 3 - x^2$, we define the area as a function of $x$ and then use calculus to find its maximum value.

### Task Conditions and Values

* **Function:** $y = 3 - x^2$
* **Constraint:** The rectangle must be in the **first quadrant**.
* **Vertices:** * One vertex at the origin $(0, 0)$.
* One vertex on the $x$-axis at $(x, 0)$.
* One vertex on the $y$-axis at $(0, y)$.
* One vertex on the curve at $(x, y)$, where $y = 3 - x^2$.


* **Goal:** Find the dimensions ($x$ and $y$) that maximize the area $A$.

---

### Step-by-Step Solution

**Step 1: Express the Area as a function of $x$**
The area $A$ of a rectangle is $\text{width} \times \text{height}$. In this case:

* $\text{Width} = x$
* $\text{Height} = y = 3 - x^2$

$$A(x) = x(3 - x^2)$$


$$A(x) = 3x - x^3$$



**Step 2: Find the derivative $A'(x)$**
To find the maximum area, we take the derivative of $A$ with respect to $x$:


$$A'(x) = 3 - 3x^2$$

**Step 3: Solve for the critical points**
Set the derivative equal to zero:


$$3 - 3x^2 = 0$$

$$3x^2 = 3$$

$$x^2 = 1$$


Since the rectangle is in the first quadrant, $x$ must be positive:


$$x = 1$$

**Step 4: Verify it is a maximum**
Using the second derivative test:


$$A''(x) = -6x$$


At $x = 1$, $A''(1) = -6$, which is less than zero. This confirms that $x = 1$ provides the **maximum area**.

**Step 5: Calculate the corresponding $y$ dimension**
Substitute $x = 1$ back into the curve equation:


$$y = 3 - (1)^2$$

$$y = 2$$

---

### Final Answer

The dimensions of the rectangle with the maximum area are:

* **Width ($x$):** $1$
* **Height ($y$):** $2$

The maximum area is $A = 1 \times 2 = 2$ square units.

