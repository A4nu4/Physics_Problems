Satellites in geostationary orbit remain above the same point on Earth. What must their orbital period be? Calculate the altitude of a geostationary orbit above the Earth's surface.
---

### 1. Required Orbital Period

For a satellite to remain fixed over the same point on Earth's equator, its orbital period must exactly match the rotational period of the Earth.

To prevent the satellite from drifting over time, this must be equal to one **sidereal day** (the time it takes for Earth to rotate $360^\circ$ relative to the distant stars), rather than a standard $24\text{-hour}$ solar day.

* **Required Period ($T$):** $23\text{ hours, } 56\text{ minutes, and } 4.09\text{ seconds} = 86,164\text{ s}$

---

### 2. Calculating the Altitude ($h$)

A satellite in a stable circular orbit relies on gravitational force to provide the necessary centripetal acceleration:

$$F_g = F_c \implies \frac{G M_E m}{r^2} = \frac{m v^2}{r}$$

Since linear orbital speed is related to the period by $v = \frac{2\pi r}{T}$, we substitute this into the equation to yield Kepler's Third Law:

$$r^3 = \frac{G M_E T^2}{4\pi^2}$$

#### Given Constants:

* **Gravitational Constant ($G$):** $6.674 \times 10^{-11} \text{ N}\cdot\text{m}^2/\text{kg}^2$
* **Mass of the Earth ($M_E$):** $5.972 \times 10^{24} \text{ kg}$
* **Mean Radius of the Earth ($R_E$):** $6,371 \text{ km} = 6.371 \times 10^6 \text{ m}$

#### Step-by-Step Evaluation:

1. **Calculate the total orbital radius ($r$):**

$$r^3 = \frac{(6.674 \times 10^{-11}) \cdot (5.972 \times 10^{24}) \cdot (86,164)^2}{4\pi^2}$$


$$r^3 = \frac{(3.9856 \times 10^{14}) \cdot (7.4242 \times 10^9)}{39.4784}$$


$$r^3 = \frac{2.9590 \times 10^{24}}{39.4784} \approx 7.4952 \times 10^{22} \text{ m}^3$$


$$r = \sqrt[3]{7.4952 \times 10^{22}} \approx 4.2242 \times 10^7 \text{ m} = 42,242 \text{ km}$$


2. **Subtract Earth's radius to find altitude ($h$):**
The orbital radius is measured from the center of the Earth. To find the altitude above the surface:

$$h = r - R_E$$


$$h = 42,242 \text{ km} - 6,371 \text{ km} = 35,871 \text{ km}$$



---

### Final Result:

The orbital period must be **$23\text{ hours } 56\text{ minutes } 4\text{ seconds}$**, and the precise altitude of a geostationary orbit above Earth's surface is approximately **$35,800 \text{ km}$** (or $22,236 \text{ miles}$).


