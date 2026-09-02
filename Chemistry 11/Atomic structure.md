### Hydrogen Spectral Lines: Finding $n_2$

Use the formula:
$$n_2 = n_1 + k$$

#### 1. Determine $n_1$ (Series Name)
| Series | $n_1$ | Region |
| :--- | :---: | :--- |
| **Lyman** | $1$ | Ultraviolet (UV) |
| **Balmer** | $2$ | Visible |
| **Paschen** | $3$ | Near Infrared (IR) |
| **Brackett** | $4$ | Infrared (IR) |
| **Pfund** | $5$ | Far Infrared (IR) |
| **Humphreys** | $6$ | Far Infrared (IR) |

#### 2. Determine $k$ (Line Number)
* **$1^{\text{st}}$ line** ($\alpha$-line / first member) $\rightarrow k = 1$
* **$2^{\text{nd}}$ line** ($\beta$-line / second member) $\rightarrow k = 2$
* **$3^{\text{rd}}$ line** ($\gamma$-line / third member) $\rightarrow k = 3$
* **$k^{\text{th}}$ line** $\rightarrow k$

> **Edge Case:**
> * **Limiting line / Series limit / Last line / Shortest $\lambda$:** $n_2 = \infty$
> * **First line / Longest $\lambda$:** $k = 1 \implies n_2 = n_1 + 1$

---

#### Quick Cheatsheet
* **$2^{\text{nd}}$ line of Balmer:** $n_1 = 2$, $k = 2 \implies n_2 = 2 + 2 = \mathbf{4}$
* **$3^{\text{rd}}$ line of Paschen:** $n_1 = 3$, $k = 3 \implies n_2 = 3 + 3 = \mathbf{6}$
* **$1^{\text{st}}$ line of Lyman:** $n_1 = 1$, $k = 1 \implies n_2 = 1 + 1 = \mathbf{2}$
* **Balmer series limit:** $n_1 = 2$, $n_2 = \boldsymbol{\infty}$


---

$$E_{\text{photon}} = \frac{hc}{\lambda}, \quad P_{\text{useful}} = \eta P, \quad n = \frac{P_{\text{useful}} \times t}{E_{\text{photon}}}$$


---

$$r_n \propto n^2 \implies \frac{r_1}{r_2} = \frac{n_1^2}{n_2^2} = \frac{4}{1} \implies \frac{n_1}{n_2} = \frac{2}{1}$$
    
- **Intuition & Fact:** Bohr orbits expand quadratically. Any pair where the principle quantum number ratio is $2:1$ will give a radius ratio of $4:1$:
    
    - $L$ ($n=2$) and $K$ ($n=1$) $\implies 2^2 : 1^2 = 4:1$ (Option B)
        
    - $N$ ($n=4$) and $L$ ($n=2$) $\implies 4^2 : 2^2 = 16:4 = 4:1$ (Option C)


---

**Intuition & Fact:** Be careful with naming conventions:

- "Third excited state" $= n = 4$
    
- "First excited state" $= n = 2$
    
- Jump is from $n=4$ to $n=2$ (the Balmer $H_\beta$ line):
    
    $$\Delta E = E_4 - E_2 = -0.85\text{ eV} - (-3.4\text{ eV}) = 2.55\text{ eV}$$

---

- Watch out for the wording: "which **excited level**".
    
    - Ground state: $n = 1$
        
    - $1^{\text{st}}$ excited state: $n = 2$
        
    - $2^{\text{nd}}$ excited state: $n = 3$
        
- Since $n=3$ is the **$2^{\text{nd}}$ excited state**


---

A "quantum of energy" simply means **one single photon**. Whenever an electron transitions directly from any upper state to any lower state in one shot (like $4 \to 2$, $3 \to 1$, or $4 \to 1$), it releases the entire energy difference as exactly one photon.


---

$$\text{Binding Energy} = \frac{13.6 \times Z^2}{n^2}$$


---

