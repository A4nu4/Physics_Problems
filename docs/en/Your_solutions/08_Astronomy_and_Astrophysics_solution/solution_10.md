A medieval astronomer in Al-Andalus, Al-Zarqali (Arzachel) (1029–1087 AD), attempted to estimate the height of the Earth’s atmosphere using a geometric method based on sunset timing. He measured the interval between sunset and the moment when faint stars first became visible, assuming that this corresponds to the Sun reaching a true geometric depression angle $\phi$ below the horizon. A chronicle reports that on a clear evening the time between sunset and the first appearance of faint stars was $t = 40$ minutes.


Assume:
- Earth radius $R_E = 6370\,\text{km}$,
- Earth’s rotation rate: full rotation in 24 hours (i.e., $360^\circ$ in 24 hours),
- A simple “sharp-edge atmosphere” model in which a Sun ray reaches the observer by just grazing the top of the atmosphere, giving

$$\cos\phi = \frac{R_E}{R_E+h}.$$

Find:

1. The solar depression angle $\phi$ (in degrees) implied by the measured time $t$.
  
2. The atmospheric height $h$ in km.

---

To solve Al-Zarqali's atmospheric height estimation, we can translate the time interval into a geometric angle of rotation, and then apply his right-triangle atmospheric model.

---

### 1. Calculate the Solar Depression Angle ($\phi$)

The Earth rotates a full $360^\circ$ every 24 hours. We need to determine how many degrees the Earth turns during the $t = 40\text{ minutes}$ it takes for the faint stars to appear.

#### Conversion Factor:

First, let's find the Earth's rotation rate in degrees per minute:

$$\text{Rotation Rate} = \frac{360^\circ}{24\text{ hours}} = \frac{360^\circ}{24 \times 60\text{ minutes}} = \frac{360^\circ}{1440\text{ minutes}} = 0.25^\circ\text{ per minute}$$

#### Calculate $\phi$:

Multiplying the rate by the measured time interval ($t = 40\text{ min}$):

$$\phi = 40\text{ minutes} \times 0.25^\circ/\text{minute}$$

$$\phi = 10.0^\circ$$

The implied solar depression angle is **$\phi = 10.0^\circ$**.

---

### 2. Calculate the Atmospheric Height ($h$)

Using Al-Zarqali's "sharp-edge" geometric model, the line of sight to the horizon or a grazing sun ray forms a right triangle where the hypotenuse is the distance from the center of the Earth to the top of the atmosphere ($R_E + h$).

#### Rearrange the Model Formula:

$$\cos\phi = \frac{R_E}{R_E + h}$$

Rearranging to isolate $h$:


$$R_E + h = \frac{R_E}{\cos\phi}$$

$$h = \frac{R_E}{\cos\phi} - R_E$$

#### Final Calculation:

Given Earth's radius $R_E = 6370\text{ km}$ and our calculated angle $\phi = 10.0^\circ$:

$$h = \frac{6370}{\cos(10.0^\circ)} - 6370$$

$$h = \frac{6370}{0.9848077} - 6370$$

$$h \approx 6468.27 - 6370$$

$$h \approx 98.27\text{ km}$$

---

### Final Result:

1. The solar depression angle is **$10.0^\circ$**.
2. The calculated atmospheric height is approximately **$98.3\text{ km}$**.

*(Historical Note: This elegant geometric approach yields a value remarkably close to the modern definition of the edge of space—the Kármán line at $100\text{ km}$—even though atmospheric refraction slightly alters the actual path of light near the horizon).*
