# Statistics — Complete Notes (BITSAT 2027)

> [!abstract] Overview
> **Coverage**: Fundamentals $\to$ Measures of Central Tendency $\to$ Dispersion $\to$ Variance & Standard Deviation $\to$ Grouped and Continuous Distributions $\to$ Combined Statistics $\to$ Properties & Shortcuts.  
> **Preparation Target**: BITSAT level. Prioritise understanding standard formulas, properties of transformations, and high-speed direct numerical evaluation.

---

## 1. Introduction to Statistics

Statistics deals with collecting, organising, analysing, and interpreting data.

### 1.1 Basic Terminology

* **Data**: A collection of numerical observations.
* **Observation ($x_i$)**: An individual value within the dataset.
* **Frequency ($f_i$)**: The number of times an observation $x_i$ occurs.
* **Total Frequency ($N$)**: Total number of observations:
$$N = \sum_{i=1}^{n} f_i$$

> [!example] Frequency Distribution Example
> Consider the data: $2, 3, 3, 4, 4, 4, 5$
> 
> | Observation ($x_i$) | Frequency ($f_i$) |
> | :---: | :---: |
> | $2$ | $1$ |
> | $3$ | $2$ |
> | $4$ | $3$ |
> | $5$ | $1$ |
> 
> Total observations:
> $$N = 1 + 2 + 3 + 1 = 7$$

### 1.2 Types of Data Distributions

* **Individual Data**: Every observation is listed separately.  
  *Example*: $2, 4, 6, 8$
* **Discrete Frequency Distribution**: Distinct values paired with explicit frequencies.
  
  | Value ($x_i$) | Frequency ($f_i$) |
  | :---: | :---: |
  | $2$ | $3$ |
  | $4$ | $5$ |
  | $6$ | $2$ |

* **Continuous Frequency Distribution**: Data organized into continuous class intervals.
  
  | Class Interval | Frequency ($f_i$) |
  | :---: | :---: |
  | $0 - 10$ | $4$ |
  | $10 - 20$ | $8$ |
  | $20 - 30$ | $6$ |

---

## 2. Arithmetic Mean

The arithmetic mean represents the central tendency or average of all values in a dataset.

### 2.1 Mean of Individual Observations

$$\bar{x} = \frac{\sum x_i}{N}$$

> [!example]
> Find the mean of $2, 4, 6, 8$:
> $$\bar{x} = \frac{2 + 4 + 6 + 8}{4} = \frac{20}{4} = 5$$

### 2.2 Mean of a Frequency Distribution

$$\bar{x} = \frac{\sum f_i x_i}{\sum f_i} = \frac{\sum f_i x_i}{N}$$

| $x_i$ | $f_i$ | $f_i x_i$ |
| :---: | :---: | :---: |
| $2$ | $2$ | $4$ |
| $4$ | $3$ | $12$ |
| $6$ | $1$ | $6$ |
| **Total** | **$N = 6$** | **$\sum f_i x_i = 22$** |

$$\bar{x} = \frac{22}{6} = \frac{11}{3}$$

### 2.3 Weighted Mean

$$\bar{x}_w = \frac{\sum w_i x_i}{\sum w_i}$$

Where $w_i$ denotes the respective weight assigned to value $x_i$.

> [!example]
> A student scores $80$ on a test with weight $2$, and $90$ on a test with weight $3$:
> $$\bar{x}_w = \frac{80(2) + 90(3)}{2 + 3} = \frac{160 + 270}{5} = \frac{430}{5} = 86$$

### 2.4 Properties of Arithmetic Mean

1. **Sum of Deviations from Mean is Zero**:
$$\sum (x_i - \bar{x}) = 0 \quad \text{and} \quad \sum f_i (x_i - \bar{x}) = 0$$

2. **Shift of Origin (Adding/Subtracting a constant)**:  
   If $y_i = x_i \pm a$, then:
$$\bar{y} = \bar{x} \pm a$$

3. **Change of Scale (Multiplying/Dividing by a constant)**:  
   If $y_i = a x_i$, then:
$$\bar{y} = a \bar{x}$$

4. **General Linear Transformation**:  
   If $y_i = a x_i + b$, then:
$$\bar{y} = a \bar{x} + b$$

5. **Combined Mean**:  
   For two groups of sizes $n_1, n_2$ with means $\bar{x}_1, \bar{x}_2$:
$$\bar{x}_{12} = \frac{n_1 \bar{x}_1 + n_2 \bar{x}_2}{n_1 + n_2}$$

---

## 3. Median

The median represents the positional middle value when the data is sorted in ascending or descending order. It is robust to extreme outliers.

### 3.1 Median of Individual Observations

Arrange data in ascending order:

* **Case 1: $N$ is odd**
$$\text{Median} = \left(\frac{N + 1}{2}\right)^{\text{th}} \text{ observation}$$

* **Case 2: $N$ is even**
$$\text{Median} = \frac{1}{2} \left[ \left(\frac{N}{2}\right)^{\text{th}} + \left(\frac{N}{2} + 1\right)^{\text{th}} \right] \text{ observations}$$

### 3.2 Median of Discrete Frequency Distribution

Construct the cumulative frequency ($cf$) column to locate the middle index.

| $x_i$ | $f_i$ | Cumulative Frequency ($cf$) |
| :---: | :---: | :---: |
| $2$ | $2$ | $2$ |
| $4$ | $3$ | $5$ |
| $6$ | $4$ | $9$ |
| $8$ | $1$ | $10$ |

Total $N = 10$ (even). The median is the average of the $5^{\text{th}}$ and $6^{\text{th}}$ values:
* $5^{\text{th}}$ value falls in $cf = 5 \implies x_i = 4$
* $6^{\text{th}}$ value falls in $cf = 9 \implies x_i = 6$
$$\text{Median} = \frac{4 + 6}{2} = 5$$

### 3.3 Median of Continuous Frequency Distribution

$$\text{Median} = l + \left( \frac{\frac{N}{2} - cf}{f} \right) \cdot h$$

Where:
* $l$ = Lower boundary of the median class
* $N = \sum f_i$ = Total frequency
* $cf$ = Cumulative frequency of the class **preceding** the median class
* $f$ = Simple frequency of the median class
* $h$ = Class width of the median class

> [!tip] Identifying the Median Class
> 1. Calculate $\frac{N}{2}$.
> 2. Locate the first class interval whose cumulative frequency is $\ge \frac{N}{2}$.

> [!example]
> | Class Interval | $f_i$ | $cf$ |
> | :---: | :---: | :---: |
> | $0 - 10$ | $4$ | $4$ |
> | $10 - 20$ | $8$ | $12$ |
> | $20 - 30$ | $8$ | $20$ |
> 
> $N = 20 \implies \frac{N}{2} = 10$.  
> First $cf \ge 10$ is $12 \implies \text{Median Class} = [10, 20]$.  
> Here: $l = 10, cf = 4, f = 8, h = 10$.
> $$\text{Median} = 10 + \left(\frac{10 - 4}{8}\right) \cdot 10 = 10 + \frac{60}{8} = 17.5$$

---

## 4. Mode

The mode is the value that occurs with maximum frequency.

### 4.1 Classifications

* **Unimodal**: Exactly one peak mode.
* **Bimodal**: Two distinct values sharing highest frequency.
* **Multimodal**: More than two distinct modes.
* **No Mode**: All observations have identical frequencies.

### 4.2 Empirical Relation (Moderately Skewed Distributions)

$$\text{Mode} \approx 3\,\text{Median} - 2\,\text{Mean}$$

Rearrangements:
$$\text{Mean} \approx \frac{3\,\text{Median} - \text{Mode}}{2}$$
$$\text{Median} \approx \frac{\text{Mode} + 2\,\text{Mean}}{3}$$

### 4.3 Mode of Continuous Frequency Distribution

$$\text{Mode} = l + \left( \frac{f_1 - f_0}{2f_1 - f_0 - f_2} \right) \cdot h$$

Where:
* Modal Class = Class interval with the highest frequency
* $l$ = Lower limit of modal class
* $f_1$ = Frequency of modal class
* $f_0$ = Frequency of class preceding modal class
* $f_2$ = Frequency of class succeeding modal class
* $h$ = Class width

> [!example]
> | Class | $f_i$ |
> | :---: | :---: |
> | $0 - 10$ | $4$ |
> | $10 - 20$ | $10$ |
> | $20 - 30$ | $6$ |
> 
> Highest frequency is $10 \implies \text{Modal Class} = [10, 20]$.  
> $l = 10, f_1 = 10, f_0 = 4, f_2 = 6, h = 10$.
> $$\text{Mode} = 10 + \left(\frac{10 - 4}{2(10) - 4 - 6}\right) \cdot 10 = 10 + \left(\frac{6}{10}\right) \cdot 10 = 16$$

---

## 5. Measures of Dispersion

Measures of dispersion quantify the extent of variation, scatter, or spread in a dataset around its central value.

### 5.1 Range

$$\text{Range} = L - S$$

Where $L$ is the largest observation and $S$ is the smallest observation.

* **Coefficient of Range (Relative Measure)**:
$$\text{Coefficient of Range} = \frac{L - S}{L + S}$$

---

## 6. Mean Deviation (MD)

The average of the absolute differences between each value and a chosen central point $A$.

### 6.1 General Definition

* **Individual Data**:
$$\text{MD}(A) = \frac{\sum |x_i - A|}{N}$$

* **Discrete / Grouped Frequency Data**:
$$\text{MD}(A) = \frac{\sum f_i |x_i - A|}{\sum f_i}$$

### 6.2 Specific Forms

* **About Mean ($\bar{x}$)**:
$$\text{MD}(\bar{x}) = \frac{\sum |x_i - \bar{x}|}{N}$$

* **About Median ($M$)**:
$$\text{MD}(M) = \frac{\sum |x_i - M|}{N}$$

> [!important] Minimisation Property
> $\text{MD}(A)$ is **minimised** when deviations are taken about the **Median** ($A = M$).

> [!example] Mean Deviation About the Mean
> Find $\text{MD}(\bar{x})$ for $2, 4, 6, 8$:  
> $\bar{x} = \frac{2 + 4 + 6 + 8}{4} = 5$.
> 
> | $x_i$ | $|x_i - \bar{x}|$ |
> | :---: | :---: |
> | $2$ | $|2 - 5| = 3$ |
> | $4$ | $|4 - 5| = 1$ |
> | $6$ | $|6 - 5| = 1$ |
> | $8$ | $|8 - 5| = 3$ |
> 
> $$\text{MD}(\bar{x}) = \frac{3 + 1 + 1 + 3}{4} = \frac{8}{4} = 2$$

### 6.3 Coefficients of Mean Deviation

* **About Mean**:
$$\text{Coefficient of MD}(\bar{x}) = \frac{\text{MD}(\bar{x})}{\bar{x}}$$

* **About Median**:
$$\text{Coefficient of MD}(M) = \frac{\text{MD}(M)}{M}$$

---

## 7. Variance ($\sigma^2$)

Variance measures the mean of the squared deviations taken exclusively from the arithmetic mean.

### 7.1 Formulas for Individual Data

* **Standard Definition**:
$$\sigma^2 = \frac{\sum (x_i - \bar{x})^2}{N}$$

* **Computational Shortcut Formula (Mean of Squares minus Square of Mean)**:
$$\sigma^2 = \frac{\sum x_i^2}{N} - (\bar{x})^2$$

> [!example] Verification via Both Methods
> Data: $2, 4, 6, 8 \implies \bar{x} = 5$.
> 
> 1. **Definition**:
>    $$\sum (x_i - \bar{x})^2 = (2-5)^2 + (4-5)^2 + (6-5)^2 + (8-5)^2 = 9 + 1 + 1 + 9 = 20$$
>    $$\sigma^2 = \frac{20}{4} = 5$$
> 2. **Shortcut**:
>    $$\sum x_i^2 = 2^2 + 4^2 + 6^2 + 8^2 = 4 + 16 + 36 + 64 = 120$$
>    $$\sigma^2 = \frac{120}{4} - (5)^2 = 30 - 25 = 5$$

### 7.2 Formulas for Frequency Distributions

* **Standard**:
$$\sigma^2 = \frac{\sum f_i (x_i - \bar{x})^2}{N}$$

* **Shortcut**:
$$\sigma^2 = \frac{\sum f_i x_i^2}{N} - (\bar{x})^2 \quad \text{where } N = \sum f_i$$

---

## 8. Standard Deviation ($\sigma$)

Standard deviation is the positive square root of the variance:

$$\sigma = +\sqrt{\sigma^2} = \sqrt{\frac{\sum x_i^2}{N} - (\bar{x})^2}$$

It restores the measure of dispersion to the original measurement units of the data.

### 8.1 Properties of Variance and Standard Deviation Under Transformations

Let $Y = aX + b$, where $a$ and $b$ are real constants:

| Property | Transformation Rule | Note |
| :--- | :--- | :--- |
| **Change of Origin** ($b$) | Independent of origin shift | Adding/subtracting $b$ leaves $\sigma^2$ and $\sigma$ unaltered. |
| **Change of Scale** ($a$) | Dependent on scale multiplier | Multiply variance by $a^2$; multiply SD by $\|a\|$. |
| **Linear Combination** | $\sigma_Y^2 = a^2 \sigma_X^2$ | $\sigma_Y = \|a\| \sigma_X$ |

> [!example] Transformation Problem
> If $\text{Var}(X) = 4$, find $\text{Var}(-3X + 7)$:
> $$\text{Var}(-3X + 7) = (-3)^2 \cdot \text{Var}(X) = 9 \cdot 4 = 36$$
> $$\text{SD}(-3X + 7) = |-3| \cdot \text{SD}(X) = 3 \cdot 2 = 6$$

---

## 9. Coefficient of Variation (CV)

The coefficient of variation is a unitless, relative measure of dispersion expressing standard deviation as a percentage of the mean:

$$\text{CV} = \frac{\sigma}{\bar{x}} \times 100\%$$

> [!tip] Consistency Principle (BITSAT Favourite)
> * **Lower CV** $\implies$ Higher consistency, stability, and uniformity.
> * **Higher CV** $\implies$ Greater variability and lower consistency.
> * Always compare consistency using **CV**, never by absolute standard deviations when means differ.

> [!example]
> | Group | Mean ($\bar{x}$) | Standard Deviation ($\sigma$) |
> | :---: | :---: | :---: |
> | **A** | $50$ | $5$ |
> | **B** | $80$ | $12$ |
> 
> $$\text{CV}_A = \frac{5}{50} \times 100 = 10\%$$
> $$\text{CV}_B = \frac{12}{80} \times 100 = 15\%$$
> Since $\text{CV}_A < \text{CV}_B$, **Group A is more consistent**.

---

## 10. Grouped Frequency Distributions: Terminology

* **Class Width ($h$)**:
$$h = \text{Upper Limit} - \text{Lower Limit}$$

* **Class Mark / Midpoint ($x_i$)**:
$$x_i = \frac{\text{Lower Limit} + \text{Upper Limit}}{2}$$

* **Cumulative Frequency ($cf$)**: The running sum of successive class frequencies.

---

## 11. Inclusive vs. Exclusive Class Intervals

* **Exclusive (Continuous)**: $0-10, 10-20, 20-30 \dots$ (Upper boundary of class $k$ equals lower boundary of class $k+1$). Directly usable.
* **Inclusive (Discontinuous)**: $10-19, 20-29, 30-39 \dots$ Gap exists between consecutive limits.
$$\text{Correction Factor} = \frac{\text{Gap}}{2} = \frac{20 - 19}{2} = 0.5$$
  *Adjusted Boundaries*: Subtract $0.5$ from Lower Limits, Add $0.5$ to Upper Limits:
$$[9.5 - 19.5], [19.5 - 29.5], [29.5 - 39.5]$$

---

## 12. Computation Methods for Grouped Data

### 12.1 Direct Method
$$\bar{x} = \frac{\sum f_i x_i}{N}$$

### 12.2 Assumed Mean Method
Let $d_i = x_i - A$, where $A$ is an assumed central value:
$$\bar{x} = A + \frac{\sum f_i d_i}{N}$$

### 12.3 Step-Deviation Method
Let $u_i = \frac{x_i - A}{h}$, where $h$ is the uniform class width:
$$\bar{x} = A + h \cdot \left(\frac{\sum f_i u_i}{N}\right)$$
$$\sigma^2 = h^2 \left[ \frac{\sum f_i u_i^2}{N} - \left(\frac{\sum f_i u_i}{N}\right)^2 \right]$$

---

## 13. Combined Variance

Given two datasets:
* Group 1: size $n_1$, mean $\bar{x}_1$, variance $\sigma_1^2$
* Group 2: size $n_2$, mean $\bar{x}_2$, variance $\sigma_2^2$

### 13.1 General Formula
$$\bar{x}_{12} = \frac{n_1 \bar{x}_1 + n_2 \bar{x}_2}{n_1 + n_2}$$
$$\sigma_{12}^2 = \frac{n_1 \left[\sigma_1^2 + d_1^2\right] + n_2 \left[\sigma_2^2 + d_2^2\right]}{n_1 + n_2}$$
Where $d_1 = \bar{x}_1 - \bar{x}_{12}$ and $d_2 = \bar{x}_2 - \bar{x}_{12}$.

### 13.2 Rapid Shortcut Formula
$$\sigma_{12}^2 = \frac{n_1 \sigma_1^2 + n_2 \sigma_2^2}{n_1 + n_2} + \frac{n_1 n_2}{(n_1 + n_2)^2} (\bar{x}_1 - \bar{x}_2)^2$$

> [!example]
> Group A: $n_1 = 4, \bar{x}_1 = 10, \sigma_1^2 = 4$  
> Group B: $n_2 = 6, \bar{x}_2 = 20, \sigma_2^2 = 9$  
> 
> $$\sigma_{12}^2 = \frac{4(4) + 6(9)}{10} + \frac{4 \cdot 6}{10^2} (10 - 20)^2$$
> $$\sigma_{12}^2 = \frac{16 + 54}{10} + \frac{24}{100}(100) = 7 + 24 = 31$$
> Combined Standard Deviation $\sigma_{12} = \sqrt{31}$.

---

## 14. Essential Mathematical Theorems & Properties

1. **Non-negativity**: $\sigma^2 \ge 0$. ($\sigma^2 = 0 \iff$ all observations are identical).
2. **Least Squares Property**:
$$\sum (x_i - \bar{x})^2 \le \sum (x_i - A)^2 \quad \forall A \in \mathbb{R}$$
   The sum of squared deviations is minimal when evaluated about the **arithmetic mean**.
3. **Least Absolute Deviations Property**:
$$\sum |x_i - M| \le \sum |x_i - A| \quad \forall A \in \mathbb{R}$$
   The sum of absolute deviations is minimal when evaluated about the **median**.
4. **Fundamental Identity for Sum of Squares**:
$$\sum x_i^2 = N (\sigma^2 + \bar{x}^2)$$

---

## 15. Correcting / Altering Observations

Use the identities $\sum x_i = N \bar{x}$ and $\sum x_i^2 = N(\sigma^2 + \bar{x}^2)$.

### 15.1 Adding an Observation ($a$)
$$\bar{x}_{\text{new}} = \frac{N\bar{x} + a}{N + 1}$$
$$\sigma_{\text{new}}^2 = \frac{N(\sigma^2 + \bar{x}^2) + a^2}{N + 1} - (\bar{x}_{\text{new}})^2$$

### 15.2 Removing an Observation ($a$)
$$\bar{x}_{\text{new}} = \frac{N\bar{x} - a}{N - 1}$$
$$\sigma_{\text{new}}^2 = \frac{N(\sigma^2 + \bar{x}^2) - a^2}{N - 1} - (\bar{x}_{\text{new}})^2$$

---

## 16. Covariance & Variance of Sums (Supplementary)

$$\text{Cov}(X, Y) = \frac{1}{N} \sum (x_i - \bar{x})(y_i - \bar{y}) = E[(X - E[X])(Y - E[Y])]$$

* **General Sum/Difference Variance**:
$$\text{Var}(X \pm Y) = \text{Var}(X) + \text{Var}(Y) \pm 2\,\text{Cov}(X, Y)$$

* **For Independent Variables ($\text{Cov}(X, Y) = 0$)**:
$$\text{Var}(X + Y) = \text{Var}(X) + \text{Var}(Y)$$
$$\text{Var}(X - Y) = \text{Var}(X) + \text{Var}(Y)$$

---

## 17. Master Formula Cheat Sheet

### Central Tendency

| Measure | Formula |
| :--- | :--- |
| **Individual Mean** | $\bar{x} = \frac{\sum x_i}{N}$ |
| **Grouped Mean** | $\bar{x} = \frac{\sum f_i x_i}{N}$ |
| **Combined Mean** | $\bar{x} = \frac{n_1 \bar{x}_1 + n_2 \bar{x}_2}{n_1 + n_2}$ |
| **Median (Continuous)** | $\text{Median} = l + \left(\frac{\frac{N}{2} - cf}{f}\right)h$ |
| **Mode (Empirical)** | $\text{Mode} \approx 3\,\text{Median} - 2\,\text{Mean}$ |
| **Mode (Continuous)** | $\text{Mode} = l + \left(\frac{f_1 - f_0}{2f_1 - f_0 - f_2}\right)h$ |

### Dispersion & Variability

| Measure | Formula |
| :--- | :--- |
| **Range** | $\text{Range} = L - S$ |
| **Coefficient of Range** | $\frac{L - S}{L + S}$ |
| **Mean Deviation** | $\text{MD}(A) = \frac{\sum f_i |x_i - A|}{N}$ |
| **Variance (Shortcut)** | $\sigma^2 = \frac{\sum x_i^2}{N} - (\bar{x})^2$ |
| **Frequency Variance** | $\sigma^2 = \frac{\sum f_i x_i^2}{N} - (\bar{x})^2$ |
| **Standard Deviation** | $\sigma = \sqrt{\sigma^2}$ |
| **Coefficient of Variation** | $\text{CV} = \frac{\sigma}{\bar{x}} \times 100\%$ |
| **Combined Variance** | $\sigma^2 = \frac{n_1 \sigma_1^2 + n_2 \sigma_2^2}{n_1 + n_2} + \frac{n_1 n_2}{(n_1 + n_2)^2}(\bar{x}_1 - \bar{x}_2)^2$ |

### Transformation Cheat Sheet

| Transformation | Mean | Variance | Standard Deviation |
| :---: | :---: | :---: | :---: |
| $X + c$ | $\bar{x} + c$ | $\sigma^2$ | $\sigma$ |
| $aX$ | $a\bar{x}$ | $a^2 \sigma^2$ | $|a|\sigma$ |
| $aX + b$ | $a\bar{x} + b$ | $a^2 \sigma^2$ | $|a|\sigma$ |

---

## 18. Common Pitfalls & Traps to Avoid

> [!danger] High-Probability Exam Errors
> 1. **Unsorted Median**: Calculating positional medians before arranging individual observations in strict ascending order.
> 2. **Cumulative Frequency Predecessor**: In the continuous median formula, using the $cf$ of the *median class* instead of the class **preceding** it.
> 3. **Linear Shift on Spread**: Applying $+b$ to variance or standard deviation during linear transformations. (Spread is invariant to translation!).
> 4. **Negative Multiplier in SD**: Writing $\text{SD}(-aX) = -a\,\text{SD}(X)$. Standard deviation is always strictly positive: $\text{SD}(-aX) = |-a|\,\text{SD}(X) = a\,\text{SD}(X)$.
> 5. **Consistency Metric**: Choosing the group with the lower standard deviation as "more consistent" when the means differ. Always determine consistency via $\text{CV} = \frac{\sigma}{\bar{x}} \times 100\%$.
> 6. **Discontinuous Boundaries**: Using inclusive classes ($10-19, 20-29$) directly without converting them to continuous limits ($9.5-19.5, 19.5-29.5$).
