|**Object / Shape**|**Dimension**|**Distance from Base / Center (ycm​)**|**Mnemonic / Memory Hack**|
|---|---|---|---|
|**Semicircular Ring**|1D (Wire)|$\frac{2R}{\pi}$|Denominator has $\pi$ for curved line/wire|
|**Semicircular Disc**|2D (Area)|$\frac{4R}{3\pi}$|Pair with ring: $2 \times$ numerator, $3 \times$ denominator|
|**Hollow Hemisphere**|2D (Shell)|$\frac{R}{2}$|Exactly halfway up|
|**Solid Hemisphere**|3D (Volume)|$\frac{3R}{8}$|"3 over 8" (smaller than hollow shell's $0.5R$)|
|**Hollow Cone**|2D (Open base)|$\frac{h}{3}$|Exactly at centroid level ($1/3$ from base)|
|**Solid Cone**|3D (Solid)|$\frac{h}{4}$|$1/4$ from flat base|
|**Triangular Lamina**|2D (Plate)|$\frac{h}{3}$|Centroid of triangle ($h/3$ from flat base)|

### High-Yield Exam Tricks

**1. Symmetrical Curved Shapes: General Sector Formula**

If BITSAT asks for an arbitrary circular arc or sector of total angle $2\alpha$ subtended at the center:

- **Circular Arc of angle $2\alpha$:**
    
    $$y_{cm} = \frac{R \sin\alpha}{\alpha}$$
    
    _(Put $\alpha = \pi/2$ for semicircular ring $\to \frac{2R}{\pi}$)_
    
- **Circular Sector of angle $\alpha$:**
    
    $$y_{cm} = \frac{4R \sin(alpha/2)}{3\alpha}$$
    
    _(Put $\alpha = \pi/2$ for semicircular disc $\to \frac{4R}{3\pi}$)_
    

**2. Negative Mass Method (Cavity / Cut-Out Problems)**

When a portion is removed from a symmetrical body:

$$X_{cm} = \frac{M_{orig} X_{orig} - M_{rem} X_{rem}}{M_{orig} - M_{rem}}$$

- **1D (Wires):** Mass $\propto$ Length ($L$)
    
- **2D (Plates/Discs):** Mass $\propto$ Area ($A \propto R^2$)
    
- **3D (Spheres/Cylinders):** Mass $\propto$ Volume ($V \propto R^3$)
    

_Example Shortcut (Circular disc of radius $R$ with a circular hole of diameter $R$ tangent to edge):_

- Original disc: $A_1 = \pi R^2$ at $x_1 = 0$
    
- Removed circle: $A_2 = \pi (R/2)^2 = \frac{A_1}{4}$ at $x_2 = R/2$
    
- Shift = $\frac{0 - (A_1/4)(R/2)}{A_1 - A_1/4} = -\frac{R}{6}$ (moves $R/6$ away from the cavity center).
    

**3. Shift in COM ($\Delta X_{cm}$) When a Part is Moved**

If mass $m$ is displaced by distance $\Delta x$:

$$\Delta X_{cm} = \frac{m \cdot \Delta x}{M_{total}}$$

- _Application:_ A person of mass $m$ walks from one end of a boat of mass $M$ (length $L$) to the other on frictionless water. Since no external horizontal force acts, $\Delta X_{cm} = 0$:
    
    $$\Delta x_{boat} = -\frac{m L}{M + m}$$
    

**4. Two-Particle Distance Trick**

For two masses $m_1$ and $m_2$ separated by distance $d$:

- Distance of COM from $m_1$: $r_1 = \left(\frac{m_2}{m_1 + m_2}\right) d$
    
- Distance of COM from $m_2$: $r_2 = \left(\frac{m_1}{m_1 + m_2}\right) d$
    

_Shortcut:_ Distance from any mass is proportional to the **other** mass. If $m_1 \gg m_2$, the COM lies virtually inside $m_1$.