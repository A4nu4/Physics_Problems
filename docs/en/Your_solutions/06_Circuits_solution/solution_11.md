To determine the power dissipation and energy consumption for this resistor, we can utilize several fundamental relationships between voltage, current, resistance, and time.

---

### 1. Power Dissipation ($P$)

Power is the rate at which electrical energy is converted into another form, such as heat. There are two common ways to calculate this depending on which values are available.

#### Method A: Using Voltage and Resistance

When you have the voltage ($V$) and resistance ($R$), you can use the following relationship:


$$P = \frac{V^2}{R}$$

* **Voltage ($V$):** $50\text{ V}$
* **Resistance ($R$):** $100\,\Omega$
* **Calculation:** $P = \frac{50^2}{100} = \frac{2500}{100} = \mathbf{25\text{ W}}$

#### Method B: Using Current and Resistance

Alternatively, we can use the current ($I$) flowing through the resistor. First, find the current using Ohm's Law ($I = V/R$):


$$I = \frac{50\text{ V}}{100\,\Omega} = 0.5\text{ A}$$

Then, apply the formula for power based on current:


$$P = R \cdot I^2$$

* **Calculation:** $P = 100\,\Omega \cdot (0.5\text{ A})^2 = 100 \cdot 0.25 = \mathbf{25\text{ W}}$

---

### 2. Energy Consumed ($E$)

Energy represents the total work done over a specific duration. To ensure the result is in Joules (J), time must be converted to seconds.

* **Time ($t$):** $5\text{ minutes} = 5 \times 60 = 300\text{ seconds}$

The formula for energy is the product of power and time:


$$E = P \cdot t$$

* **Calculation:** $E = 25\text{ W} \cdot 300\text{ s} = \mathbf{7500\text{ J}}$

The total energy consumed in 5 minutes is **7.5 kJ**.

---

### Summary of Results

| Parameter | Formula Used | Value |
| --- | --- | --- |
| **Current ($I$)** | $V / R$ | $0.5\text{ A}$ |
| **Power ($P$)** | $V^2 / R$ or $R \cdot I^2$ | **$25\text{ W}$** |
| **Energy ($E$)** | $P \cdot t$ | **$7.5\text{ kJ}$** |
