### 1. Displacement ($x$)

The general kinematic equation for simple harmonic motion about the mean position ($x = 0$) is:

$$x(t) = A \sin(\omega t + \phi_0)$$

- **$A$**: Amplitude (maximum displacement from mean position).
    
- **$\omega$**: Angular frequency ($\omega = \frac{2\pi}{T} = 2\pi f = \sqrt{\frac{k}{m}}$).
    
- **$\phi_0$**: Initial phase constant (epoch), determined strictly by initial boundary conditions at $t = 0$.
    

**Boundary Conditions & Initial Phase ($\phi_0$):**

- Starts at **mean position moving right ($+x$)**: $x(0) = 0, v > 0 \implies \phi_0 = 0 \implies x(t) = A \sin(\omega t)$
    
- Starts at **positive extreme**: $x(0) = +A, v = 0 \implies \phi_0 = \frac{\pi}{2} \implies x(t) = A \cos(\omega t)$
    
- Starts at **negative extreme**: $x(0) = -A, v = 0 \implies \phi_0 = \frac{3\pi}{2} \text{ or } -\frac{\pi}{2} \implies x(t) = -A \cos(\omega t)$
    
- Starts at **mean position moving left ($-x$)**: $x(0) = 0, v < 0 \implies \phi_0 = \pi \implies x(t) = -A \sin(\omega t)$


---

### 2. Velocity ($v$)

Obtained by differentiating displacement with respect to time:

$$v(t) = \frac{dx}{dt} = A\omega \cos(\omega t + \phi_0) = v_{\max} \sin\left(\omega t + \phi_0 + \frac{\pi}{2}\right)$$

As a function of position $x$:

$$v(x) = \pm \omega \sqrt{A^2 - x^2}$$

- **Maximum Velocity ($v_{\max}$):** At the mean position ($x = 0$), $v_{\max} = \omega A$.
    
- **Minimum Velocity:** At extreme positions ($x = \pm A$), $v = 0$.
    
- **Phase Lead:** Velocity leads displacement by a phase angle of $\frac{\pi}{2}\text{ rad}$ ($90^\circ$).

**Trajectory / Graph in Phase Space:**

- Rearranging $v(x)$ gives:
    
    $$\frac{x^2}{A^2} + \frac{v^2}{(\omega A)^2} = 1$$
    
- The **$v$ vs $x$ graph** is an **ellipse** with semi-major/minor axes $A$ and $\omega A$.
    
- The area of this ellipse is $\pi A (\omega A) = \pi \omega A^2$.
    
- If plotted as $\frac{v}{\omega}$ vs $x$, the graph is a **circle** of radius $A$.

---

### 3. Acceleration ($a$)

Obtained by differentiating velocity with respect to time:

$$a(t) = \frac{dv}{dt} = -A\omega^2 \sin(\omega t + \phi_0) = a_{\max} \sin(\omega t + \phi_0 + \pi)$$

As a function of position $x$ (defining equation of SHM):

$$a(x) = -\omega^2 x$$

- **Maximum Acceleration ($a_{\max}$):** At extreme positions ($x = \pm A$), $\vert{}a_{\max}\vert{} = \omega^2 A$.
    
- **Minimum Acceleration:** At the mean position ($x = 0$), $a = 0$.
    
- **Direction:** Always directed toward the mean position (opposite to displacement vector).
    
- **Phase Lead:**
    
    - Acceleration leads displacement by $\pi\text{ rad}$ ($180^\circ$, exact opposite phase).
        
    - Acceleration leads velocity by $\frac{\pi}{2}\text{ rad}$ ($90^\circ$).
        

**Trajectory / Graph:**

- The **$a$ vs $x$ graph** is a **straight line passing through the origin** with a negative slope:
    
    $$\text{Slope} = -\omega^2$$
    
- The **$a$ vs $v$ graph** is an **ellipse**:
    
    $$\frac{v^2}{(\omega A)^2} + \frac{a^2}{(\omega^2 A)^2} = 1$$

---

![[Pasted image 20261106114133.png]]


---

# Circular projection of SHM

### 1. Parameter Equivalence (UCM $\leftrightarrow$ SHM)

|**Uniform Circular Motion (Reference Circle)**|**Simple Harmonic Motion (Linear Projection)**|
|---|---|
|**Radius of circle ($R$)**|**Amplitude ($A$)**|
|**Center of circle $(0,0)$**|**Mean position ($x = 0$)**|
|**Angular speed ($\omega = \text{const}$)**|**Angular frequency ($\omega = \sqrt{k/m}$)**|
|**Initial angular position at $t=0$ ($\phi_0$)**|**Epoch / Initial phase constant ($\phi_0$)**|
|**Instantaneous angle $\theta(t) = \omega t + \phi_0$**|**Phase at time $t$**|
|**Time period of one revolution ($T = \frac{2\pi}{\omega}$)**|**Time period of one oscillation ($T = \frac{2\pi}{\omega}$)**|

### 2. Kinematic Derivations via Vector Components

Take a reference circle of radius $A$ in the $xy$-plane with counter-clockwise rotation, where the instantaneous angle with the $+x$ axis is $\theta = \omega t + \phi_0$.

#### Displacement ($x$)

The position vector of particle $P$ is:

$$\vec{r} = A\cos(\omega t + \phi_0)\,\hat{i} + A\sin(\omega t + \phi_0)\,\hat{j}$$

Projecting onto the **x-axis**:

$$x(t) = A\cos(\omega t + \phi_0)$$

_(If projecting onto the **y-axis**, the equation is $y(t) = A\sin(\omega t + \phi_0)$)._

#### Velocity ($v$)

In UCM, linear speed is purely tangential with constant magnitude $v_c = \omega A$:

- Direction of tangential velocity vector makes an angle $(\theta + 90^\circ)$ with the $+x$ axis.
    
- Component along the $x$-axis:
    
    $$v_x = v_c \cos\left(\theta + \frac{\pi}{2}\right) = -\omega A \sin(\omega t + \phi_0)$$
    
- In terms of position: $\sin\theta = \sqrt{1 - \cos^2\theta} = \frac{\sqrt{A^2 - x^2}}{A}$
    
    $$v(x) = \pm \omega \sqrt{A^2 - x^2}$$
    

#### Acceleration ($a$)

In UCM, acceleration is purely centripetal (directed radially inward toward origin $O$) with magnitude $a_c = \omega^2 A$:

- The inward radial vector makes an angle of $(\theta + 180^\circ)$ with the $+x$ axis.
    
- Component along the $x$-axis:
    
    $$a_x = a_c \cos\theta \cdot (-\hat{i}) = -(\omega^2 A)\cos(\omega t + \phi_0) = -\omega^2 x$$
    

This matches the defining differential equation of SHM: $\frac{d^2x}{dt^2} + \omega^2 x = 0$.


---



