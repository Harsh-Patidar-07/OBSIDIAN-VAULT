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

| **Position**          | **Electric Field (E)** | **Electric Potential (V)** | **What Stays Constant / Key Note**                                                              |
| --------------------- | ---------------------- | -------------------------- | ----------------------------------------------------------------------------------------------- |
| **Inside** ($r < R$)  | $0$                    | $\frac{kQ}{R}$             | **$E$ is zero**; **$V$ stays constant** everywhere inside at the surface value.                 |
| **Surface** ($r = R$) | $\frac{kQ}{R^2}$       | $\frac{kQ}{R}$             | **Maximum** value for both $E$ and $V$.                                                         |
| **Outside** ($r > R$) | $\frac{kQ}{r^2}$       | $\frac{kQ}{r}$             | Behaves like a point charge at the center ($E \propto \frac{1}{r^2}$, $V \propto \frac{1}{r}$). |

### Table 2: Non-Conducting Solid Sphere

_(Charge is distributed uniformly throughout the entire volume)_

| **Position**            | **Electric Field (E)** | **Electric Potential (V)**    | **What Stays Constant / Key Note**                                                              |
| ----------------------- | ---------------------- | ----------------------------- | ----------------------------------------------------------------------------------------------- |
| **At Center** ($r = 0$) | $0$                    | $\frac{3}{2}\frac{kQ}{R}$     | **$V$ is maximum at the center** ($1.5 \times V_{\text{surface}}$).                             |
| **Inside** ($r < R$)    | $\frac{kQr}{R^3}$      | $\frac{kQ}{2R^3}(3R^2 - r^2)$ | **$E \propto r$** (grows linearly); **$V$ decreases** parabolically from center to surface.     |
| **Surface** ($r = R$)   | $\frac{kQ}{R^2}$       | $\frac{kQ}{R}$                | **$E$ is maximum** at the surface.                                                              |
| **Outside** ($r > R$)   | $\frac{kQ}{r^2}$       | $\frac{kQ}{r}$                | Behaves like a point charge at the center ($E \propto \frac{1}{r^2}$, $V \propto \frac{1}{r}$). |

---


# A important question with concept

> Three large parallel plates have uniform surface charge densities as shown in the figure (top plate at $z = a$ has $+\sigma$, middle plate at $z = -a$ has $-2\sigma$, bottom plate at $z = -2a$ has $-\sigma$; point P lies between the top and middle plates). Find out electric field intensity at point P.

![[Pasted image 20261116144042.png]]

> - **(A)** $-\frac{4\sigma}{\varepsilon_0}\hat{k}$
>     
> - **(B)** $\frac{4\sigma}{\varepsilon_0}\hat{k}$
>     
> - **(C)** $-\frac{2\sigma}{\varepsilon_0}\hat{k}$
>     
> - **(D)** $\frac{2\sigma}{\varepsilon_0}\hat{k}$
>     

- **Concept:** An infinite charged sheet produces a **uniform** electric field $\frac{\vert{}\sigma\vert{}}{2\varepsilon_0}$ that does **not depend on distance** from the sheet—it points away from positive sheets and toward negative sheets. Note carefully that these are **thin charged plates/sheets** (given single surface charge density $\sigma$ per sheet), so each sheet contributes $\frac{\sigma}{2\varepsilon_0}$.
    
- **Standard Formula:**
    
    $$E_{\text{sheet}} = \frac{\vert{}\sigma\vert{}}{2\varepsilon_0}$$
    
- **Step-by-Step Solution:**
    
    1. Point P lies **below** the top plate ($+\sigma$) and **above** the middle ($-2\sigma$) and bottom ($-\sigma$) plates. The unit vector $\hat{k}$ points upward ($+z$).
        
    2. **Field due to top plate ($+\sigma$, above P):**
        
        - Positive sheet pushes away (downward, $-\hat{k}$):
            
            $$\vec{E}_1 = -\frac{\sigma}{2\varepsilon_0}\hat{k}$$
            
    3. **Field due to middle plate ($-2\sigma$, below P):**
        
        - Negative sheet pulls toward itself (downward, $-\hat{k}$):
            
            $$\vec{E}_2 = -\frac{2\sigma}{2\varepsilon_0}\hat{k}$$
            
    4. **Field due to bottom plate ($-\sigma$, below P):**
        
        - Negative sheet pulls toward itself (downward, $-\hat{k}$):
            
            $$\vec{E}_3 = -\frac{\sigma}{2\varepsilon_0}\hat{k}$$
            
    5. **Add all three vectors at P:**
        
        $$\vec{E}_P = \vec{E}_1 + \vec{E}_2 + \vec{E}_3 = \left(-\frac{\sigma}{2\varepsilon_0} - \frac{2\sigma}{2\varepsilon_0} - \frac{\sigma}{2\varepsilon_0}\right)\hat{k} = -\frac{4\sigma}{2\varepsilon_0}\hat{k} = -\frac{2\sigma}{\varepsilon_0}\hat{k}$$
        
- **Correct Option:** **(C)**


---

# Partial derivation of Potential to get Electric field

Assume coeff's of y and z as constants ( basically 0 ) when differentiating wrt x 

**Standard Formulas:**

$$E_x = -\frac{\partial V}{\partial x}, \qquad E_y = -\frac{\partial V}{\partial y}, \qquad E_z = -\frac{\partial V}{\partial z}$$

$$\vert{}\vec{E}\vert{} = \sqrt{E_x^2 + E_y^2 + E_z^2}$$


---

# Nice concept of Perpendicular to electric field

**Concept:** Moving **perpendicular** to an electric field requires zero electrostatic work, meaning every line perpendicular to $\vec{E}$ is an **equipotential line** ($\Delta V = 0$).


---

![[Pasted image 20261117135538.png]]![[Pasted image 20261117135551.png]]![[Pasted image 20261117135610.png]]![[Pasted image 20261117135620.png]]


---

- **Concept:** A 2D vector field $\vec{E} = E_x\hat{i} + E_y\hat{j}$ is conservative only if $\frac{\partial E_x}{\partial y} = \frac{\partial E_y}{\partial x}$ (meaning it can be derived from a potential function $V$). Also, the differential equation of a field line is $\frac{dy}{dx} = \frac{E_y}{E_x}$.
    
- **Standard Formulas:**
    
    - Conservative condition: $\frac{\partial E_x}{\partial y} = \frac{\partial E_y}{\partial x}$
        
    - Equation of field lines: $\frac{dy}{dx} = \frac{E_y}{E_x}$


---

# Dipole concept

> Four charges are placed each at a distance $a$ from origin (top $+3q$ at $(0, a)$, bottom $+q$ at $(0, -a)$, left $-2q$ at $(-a, 0)$, right $-2q$ at $(a, 0)$). The dipole moment of configuration is:
> 
> - **(A)** $2qa\hat{j}$
>     
> - **(B)** $3qa\hat{j}$
>     
> - **(C)** $2qa[\hat{i} + \hat{j}]$
>     
> - **(D)** None
>     

- **Concept:** For any neutral system of charges (notice $+3q + q - 2q - 2q = 0$), the net electric dipole moment is simply the vector sum $\vec{p} = \sum q_i \vec{r}_i$ (or equivalently, we can split $+3q$ into $+2q + q$ and pair up opposite charges into standard dipoles pointing from negative to positive!).
    
- **Standard Formula:**
    
    $$\vec{p} = \sum q_i \vec{r}_i$$
    
- **Step-by-Step Solution:**
    
    1. Write the position vector $\vec{r}_i$ of each charge from the origin:
        
        - Top charge ($+3q$): $\vec{r}_1 = +a\hat{j}$
            
        - Bottom charge ($+q$): $\vec{r}_2 = -a\hat{j}$
            
        - Left charge ($-2q$): $\vec{r}_3 = -a\hat{i}$
            
        - Right charge ($-2q$): $\vec{r}_4 = +a\hat{i}$
            
    2. Sum $q_i \vec{r}_i$ for all four charges:
        
        $$\vec{p} = (+3q)(a\hat{j}) + (+q)(-a\hat{j}) + (-2q)(-a\hat{i}) + (-2q)(a\hat{i})$$
        
    3. Combine the $\hat{i}$ terms and $\hat{j}$ terms separately:
        
        $$\vec{p} = (2qa\hat{i} - 2qa\hat{i}) + (3qa\hat{j} - qa\hat{j}) = 0\hat{i} + 2qa\hat{j} = 2qa\hat{j}$$
        
- **Correct Option:** **(A)**


---

