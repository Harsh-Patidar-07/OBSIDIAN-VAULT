- Moving **along** the electric field → potential decreases.
    
- Moving **opposite** to the electric field → potential increases.
    
- Moving **perpendicular** to the electric field → potential remains constant.


---

# Permittivity trap
### 1. The Symbol Trap (FixThis First)

In electrostatics, the letter **"k"** is overloaded. Separate these two permanently:

| **Symbol**                             | **Name**                                        | **Value**                                                          | **What it represents**                                                                                         |
| -------------------------------------- | ----------------------------------------------- | ------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------- |
| **$k$** (lowercase)                    | **Coulomb's Constant**                          | $9 \times 10^9 \text{ N}\cdot\text{m}^2/\text{C}^2$                | Just a shorthand for $\frac{1}{4\pi\varepsilon_0}$ in vacuum/air.                                              |
| **$\varepsilon_0$**                    | **Permittivity of Free Space**                  | $8.85 \times 10^{-12} \text{ C}^2/\text{N}\cdot\text{m}^2$         | How much empty space "permits" electric field lines to pass through.                                           |
| **$K$ or $\varepsilon_r$** (uppercase) | **Dielectric Constant** (Relative Permittivity) | Dimensionless number ($\ge 1$)                                     | The **shielding factor** of a medium compared to vacuum. (Vacuum = $1$, Water $\approx 80$, Metal = $\infty$). |
| **$\varepsilon$**                      | **Absolute Permittivity** of the medium         | $\varepsilon = \varepsilon_0 \varepsilon_r$ (or $\varepsilon_0 K$) | The total permittivity of that specific material.                                                              |

> **Golden Rule:** Never write $k$ when a medium is involved. Always write out **$\frac{1}{4\pi\varepsilon_0 K}$** explicitly so you never confuse Coulomb's constant ($9 \times 10^9$) with the Dielectric Constant ($K$).

### 2. The Physical Intuition: What Does a Medium Actually Do?

Imagine two charges $q_1$ and $q_2$ sitting in empty space, pulling or pushing on each other.

Now, submerge them in oil or water (a dielectric medium with constant $K$). The molecules of the medium are tiny dipoles. When placed in the electric field of $q_1$ and $q_2$, these medium molecules align themselves **against** the external electric field, creating an internal opposing field.

**The net result:** The medium **weakens** the interaction between the two charges by a factor of $K$.

Think of $K$ as a **"weakening multiplier"**:

- **Force in vacuum ($F_0$):**
    
    $$F_0 = \frac{1}{4\pi\varepsilon_0} \frac{q_1 q_2}{r^2}$$
    
- **Force in a medium ($F_m$):**
    
    $$F_m = \frac{1}{4\pi\varepsilon} \frac{q_1 q_2}{r^2} = \frac{1}{4\pi(\varepsilon_0 K)} \frac{q_1 q_2}{r^2} = \frac{F_0}{K}$$
    

Because $K$ is always greater than $1$ for any material medium, **the net force and net electric field between two isolated charges ALWAYS decrease when placed in a medium.**

### 3. The 3 Standard Problem Archetypes (How to Solve Every Time)

Whenever you see a medium question in JEE/BITSAT, identify which of these three traps the examiner is setting:

#### Type A: "Force ON a charge" vs. "NET Force between charges"

- **Force exerted _by_ $q_1$ _on_ $q_2$ directly:** Does **NOT** change! Charge $q_1$ still pulls $q_2$ with $F_0$.
    
- **NET force acting on $q_2$:** **Decreases** to $\frac{F_0}{K}$ because the polarized medium pushes back against $q_1$.
    
- _Exam tip:_ Unless a question specifically asks for "the force due to $q_1$ alone," **"force between two charges in a medium"** always means the **net force** ($\frac{F_0}{K}$).
    

#### Type B: Equivalent Air Distance (Partially Filled Medium)

Sometimes a medium of thickness $t$ and dielectric constant $K$ sits between two charges separated by total distance $r$ (with air in the remaining $r - t$ space).

Do not try to integrate anything. Just convert the slab of medium into an **equivalent thickness of air**:

$$\text{Thickness } t \text{ of medium } K \equiv \text{Thickness } t\sqrt{K} \text{ of air}$$

Why $\sqrt{K}$? Because $K$ sits outside $r^2$ in the denominator: $K r^2 = (r\sqrt{K})^2$.

So the effective air distance $r_{\text{eff}}$ becomes:

$$r_{\text{eff}} = (r - t) + t\sqrt{K}$$

And the force is simply:

$$F = \frac{1}{4\pi\varepsilon_0} \frac{q_1 q_2}{\left[(r - t) + t\sqrt{K}\right]^2}$$

#### Type C: Constant Charge vs. Constant Potential (Capacitors / Plates)

When a dielectric slab of constant $K$ is inserted into a parallel plate capacitor, check what stays constant before touching any formula:

| **Quantity**                   | **Battery Disconnected (Q is constant)**       | **Battery Connected (V is constant)**         |
| ------------------------------ | ---------------------------------------------- | --------------------------------------------- |
| **Capacitance ($C$)**          | Increases ($K C_0$)                            | Increases ($K C_0$)                           |
| **Charge ($Q$)**               | **Stays $Q_0$**                                | Increases ($K Q_0$)                           |
| **Potential ($V = Q/C$)**      | Decreases ($V_0 / K$)                          | **Stays $V_0$**                               |
| **Electric Field ($E = V/d$)** | Decreases ($E_0 / K$)                          | **Stays $E_0$**                               |
| **Stored Energy ($U$)**        | Decreases ($U_0 / K$) — _use $\frac{Q^2}{2C}$_ | Increases ($K U_0$) — _use $\frac{1}{2}CV^2$_ |

### 4. Quick Checklist Before Submitting Your Answer

1. **Replace $\varepsilon_0$ with $\varepsilon_0 K$** in your formula.
    
2. Check if the medium fills the **entire space** (divide $F_0$ or $E_0$ by $K$) or only a **slab of thickness $t$** (use $r_{\text{eff}} = r - t + t\sqrt{K}$).
    
3. Sanity-check your final number: If the charges are fixed and a medium was added, is your new force/field **smaller** than the vacuum value? If it got bigger, you multiplied by $K$ instead of dividing.


---

# Sphere drama

### Table 1: Conducting Solid, Conducting Hollow, & Non-Conducting Hollow

_(All three behave identically because 100% of the charge sits on the outer surface)_

|**Position**|**Electric Field (E)**|**Electric Potential (V)**|**What Stays Constant / Key Note**|
|---|---|---|---|
|**Inside** ($r < R$)|$0$|$\frac{kQ}{R}$|**$E$ is zero**; **$V$ stays constant** everywhere inside at the surface value.|
|**Surface** ($r = R$)|$\frac{kQ}{R^2}$|$\frac{kQ}{R}$|**Maximum** value for both $E$ and $V$.|
|**Outside** ($r > R$)|$\frac{kQ}{r^2}$|$\frac{kQ}{r}$|Behaves like a point charge at the center ($E \propto \frac{1}{r^2}$, $V \propto \frac{1}{r}$).|

### Table 2: Non-Conducting Solid Sphere

_(Charge is distributed uniformly throughout the entire volume)_

| **Position**            | **Electric Field (E)** | **Electric Potential (V)**    | **What Stays Constant / Key Note**                                                              |
| ----------------------- | ---------------------- | ----------------------------- | ----------------------------------------------------------------------------------------------- |
| **At Center** ($r = 0$) | $0$                    | $\frac{3}{2}\frac{kQ}{R}$     | **$V$ is maximum at the center** ($1.5 \times V_{\text{surface}}$).                             |
| **Inside** ($r < R$)    | $\frac{kQr}{R^3}$      | $\frac{kQ}{2R^3}(3R^2 - r^2)$ | **$E \propto r$** (grows linearly); **$V$ decreases** parabolically from center to surface.     |
| **Surface** ($r = R$)   | $\frac{kQ}{R^2}$       | $\frac{kQ}{R}$                | **$E$ is maximum** at the surface.                                                              |
| **Outside** ($r > R$)   | $\frac{kQ}{r^2}$       | $\frac{kQ}{r}$                | Behaves like a point charge at the center ($E \propto \frac{1}{r^2}$, $V \propto \frac{1}{r}$). |

---


