Eleven students received the following scores on a test: 88, 92, 79, 85, 95, 81, 86, 90, 83, 77, 89. What is the mean $\bar{x}=\frac{1}{N} \sum_{i=1}^N x_i
$ and standard deviation $\sigma=\sqrt{\frac{1}{N-1} \sum_{i=1}^N (x_i - \bar{x})^2}
$ of these test scores? If the highest and lowest scores are removed, what are the new mean and standard deviation of the remaining scores?

---

Here is the step-by-step breakdown to find the statistical metrics for both the full and adjusted data sets.


### Part 1: Calculation for All 11 Students

**The Data Set ($N = 11$):** $88, 92, 79, 85, 95, 81, 86, 90, 83, 77, 89$

#### 1. Calculate the Mean ($\bar{x}$)

Sum all the test scores and divide by the total number of students ($N = 11$):

$$\sum_{i=1}^{11} x_i = 88 + 92 + 79 + 85 + 95 + 81 + 86 + 90 + 83 + 77 + 89 = 945$$

$$\bar{x} = \frac{945}{11} \approx 85.91$$

#### 2. Calculate the Standard Deviation ($\sigma$)

We find the squared differences from the mean, sum them up, divide by $N - 1 = 10$, and take the square root:

| Score ($x_i$) | Deviation ($x_i - \bar{x}$) | Squared Deviation $(x_i - \bar{x})^2$ |
| --- | --- | --- |
| 88 | $2.09$ | $4.37$ |
| 92 | $6.09$ | $37.10$ |
| 79 | $-6.91$ | $47.74$ |
| 85 | $-0.91$ | $0.83$ |
| 95 | $9.09$ | $82.64$ |
| 81 | $-4.91$ | $24.10$ |
| 86 | $0.09$ | $0.01$ |
| 90 | $4.09$ | $16.74$ |
| 83 | $-2.91$ | $8.46$ |
| 77 | $-8.91$ | $79.37$ |
| 89 | $3.09$ | $9.55$ |
| **Sum:** |  | **$310.91$** |

$$\sigma = \sqrt{\frac{310.91}{10}} = \sqrt{31.091} \approx 5.58$$

---

### Part 2: Calculation with Outliers Removed

* **Lowest score removed:** $77$
* **Highest score removed:** $95$

**The New Data Set ($N = 9$):** $79, 81, 83, 85, 86, 88, 89, 90, 92$

#### 1. Calculate the New Mean ($\bar{x}_{new}$)

$$\sum_{i=1}^{9} x_i = 945 - 77 - 95 = 773$$

$$\bar{x}_{new} = \frac{773}{9} \approx 85.89$$

#### 2. Calculate the New Standard Deviation ($\sigma_{new}$)

We recalculate the squared deviations from our new mean ($85.89$) and divide by $N - 1 = 8$:

$$\sum_{i=1}^{9} (x_i - \bar{x}_{new})^2 \approx 47.45 + 23.90 + 8.35 + 0.79 + 0.01 + 4.46 + 9.68 + 16.90 + 37.35 = 148.89$$

$$\sigma_{new} = \sqrt{\frac{148.89}{8}} = \sqrt{18.611} \approx 4.31$$

---

### Final Comparison Summary:

| Data Metric | Full Data Set ($N=11$) | Trimmed Data Set ($N=9$) |
| --- | --- | --- |
| **Mean ($\bar{x}$)** | **$85.91$** | **$85.89$** |
| **Standard Deviation ($\sigma$)** | **$5.58$** | **$4.31$** |

Removing the extreme scores had very little impact on the central mean (since the drop at the top balanced the drop at the bottom), but it significantly **reduced the standard deviation**, indicating that the remaining scores are clustered much closer together.
