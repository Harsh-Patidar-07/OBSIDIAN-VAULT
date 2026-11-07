# SHM (Oscillations) — Complete Formula Sheet | BITSAT

# PART 1 — GENERAL SHM KINEMATICS

## 1. Basic SHM Equation

The displacement of a particle executing SHM is:

$$
x=A\sin(\omega t+\phi)
$$

Alternatively:

$$
x=A\cos(\omega t+\phi)
$$

Where:

- $A$ = Amplitude
- $\omega$ = Angular frequency
- $t$ = Time
- $\phi$ = Initial phase
- $x$ = Displacement from mean position

The sine and cosine forms describe the same motion with different initial conditions.

---

## 2. Time Period, Frequency and Angular Frequency

$$
f=\frac{1}{T}
$$

$$
T=\frac{1}{f}
$$

$$
\omega=2\pi f
$$

$$
\omega=\frac{2\pi}{T}
$$

$$
T=\frac{2\pi}{\omega}
$$

Where:

- $T$ = Time period
- $f$ = Frequency
- $\omega$ = Angular frequency

---

## 3. Velocity in SHM

Velocity is the first derivative of displacement with respect to time.

For:

$$
x=A\sin(\omega t+\phi)
$$

Velocity:

$$
v=A\omega\cos(\omega t+\phi)
$$

Maximum velocity:

$$
\boxed{v_{\max}=A\omega}
$$

Velocity at displacement $x$:

$$
\boxed{v=\pm\omega\sqrt{A^2-x^2}}
$$

Important:

- At mean position: Speed is maximum.
- At extreme positions: Velocity is zero.

---

## 4. Acceleration in SHM

Acceleration is the second derivative of displacement with respect to time.

$$
a=-A\omega^2\sin(\omega t+\phi)
$$

Since $x=A\sin(\omega t+\phi)$:

$$
\boxed{a=-\omega^2x}
$$

Maximum acceleration:

$$
\boxed{a_{\max}=A\omega^2}
$$

Important:

Acceleration is always directed towards the mean position.

---

## 5. Restoring Force

Using Newton's second law:

$$
F=ma
$$

Therefore:

$$
F=-m\omega^2x
$$

Comparing with Hooke's law:

$$
F=-kx
$$

We get:

$$
\boxed{k=m\omega^2}
$$

And:

$$
\boxed{\omega=\sqrt{\frac{k}{m}}}
$$

---

## 6. Velocity–Displacement Relation

One of the most important SHM formulas:

$$
\boxed{v^2=\omega^2(A^2-x^2)}
$$

Or:

$$
\boxed{v=\pm\omega\sqrt{A^2-x^2}}
$$

Another form:

$$
\boxed{\frac{x^2}{A^2}+\frac{v^2}{A^2\omega^2}=1}
$$

This relation helps calculate velocity at any displacement without knowing time.

---

## 7. Energy in SHM

### Total Energy

$$
\boxed{E=\frac{1}{2}m\omega^2A^2}
$$

### Potential Energy

$$
\boxed{U=\frac{1}{2}m\omega^2x^2}
$$

### Kinetic Energy

$$
\boxed{K=\frac{1}{2}m\omega^2(A^2-x^2)}
$$

### Conservation of Energy

$$
\boxed{E=K+U}
$$

At mean position ($x=0$):

$$
K_{\max}=E
$$

$$
U=0
$$

At extreme position ($x=\pm A$):

$$
K=0
$$

$$
U_{\max}=E
$$

---

## 8. Phase and Phase Difference

Phase:

$$
\boxed{\theta=\omega t+\phi}
$$

Phase difference between two SHMs:

$$
\boxed{\Delta\phi=\omega\Delta t}
$$

Or:

$$
\boxed{\Delta\phi=\frac{2\pi}{T}\Delta t}
$$

Important conversions:

| Phase Difference | Time Difference |
|---|---|
| $90^\circ$ or $\pi/2$ | $T/4$ |
| $180^\circ$ or $\pi$ | $T/2$ |
| $270^\circ$ or $3\pi/2$ | $3T/4$ |
| $360^\circ$ or $2\pi$ | $T$ |

### Phase Relationships

- Velocity and displacement are $90^\circ$ out of phase.
- Acceleration and displacement are $180^\circ$ out of phase.
- Velocity and acceleration are $90^\circ$ out of phase.

---

## 9. Important Time Intervals

For a particle starting from an extreme position:

| Motion | Time Taken |
|---|---|
| Extreme to mean | $T/4$ |
| Mean to opposite extreme | $T/4$ |
| One extreme to opposite extreme | $T/2$ |
| Complete oscillation | $T$ |

For motion starting from the mean position, the first extreme is reached after $T/4$.

---

## 10. Displacement, Velocity and Acceleration at Important Positions

| Position | Displacement | Speed | Acceleration Magnitude |
|---|---|---|---|
| Mean | $0$ | $A\omega$ | $0$ |
| Extreme | $A$ | $0$ | $A\omega^2$ |
| $x=A/2$ | $A/2$ | $\frac{\sqrt{3}}{2}A\omega$ | $\frac{A\omega^2}{2}$ |
| $x=A/\sqrt{2}$ | $A/\sqrt{2}$ | $\frac{A\omega}{\sqrt{2}}$ | $\frac{A\omega^2}{\sqrt{2}}$ |

---

## 11. Average Values in SHM

Over one complete oscillation:

Average velocity:

$$
\boxed{v_{\text{avg}}=0}
$$

Average speed:

$$
\boxed{\text{Average speed}=\frac{4A}{T}}
$$

Mean kinetic energy:

$$
\boxed{\langle K\rangle=\frac{E}{2}}
$$

Mean potential energy:

$$
\boxed{\langle U\rangle=\frac{E}{2}}
$$

---

## 12. SHM Graphs

Remember these relationships:

- Displacement-time graph: Sinusoidal.
- Velocity-time graph: Sinusoidal, shifted by $90^\circ$.
- Acceleration-time graph: Sinusoidal, opposite in phase to displacement.

Important phase relationships:

$$
v \text{ leads } x \text{ by } 90^\circ
$$

$$
a \text{ is opposite in phase to } x
$$

---

# PART 2 — SPECIAL SHM SYSTEMS

## 13. Spring Pendulum (Mass-Spring System)

For a mass $m$ attached to a spring of spring constant $k$:

### Time Period

$$
\boxed{T=2\pi\sqrt{\frac{m}{k}}}
$$

### Angular Frequency

$$
\boxed{\omega=\sqrt{\frac{k}{m}}}
$$

### Frequency

$$
\boxed{f=\frac{1}{2\pi}\sqrt{\frac{k}{m}}}
$$

### Vertical Spring — Static Extension

$$
\boxed{x_0=\frac{mg}{k}}
$$

Important:

- Horizontal spring: Same time-period formula.
- Vertical spring: Same time-period formula.
- Gravity shifts the equilibrium position but does not change the time period.

### Springs in Combination

**Parallel Combination:**

$$
\boxed{k_{\text{eq}}=k_1+k_2}
$$

**Series Combination:**

$$
\boxed{\frac{1}{k_{\text{eq}}}=\frac{1}{k_1}+\frac{1}{k_2}}
$$

For $n$ identical springs:

Parallel:

$$
\boxed{k_{\text{eq}}=nk}
$$

Series:

$$
\boxed{k_{\text{eq}}=\frac{k}{n}}
$$

---

## 14. Simple Pendulum

For a bob of mass $m$, string length $L$, and small angular displacement:

### Time Period

$$
\boxed{T=2\pi\sqrt{\frac{L}{g}}}
$$

### Angular Frequency

$$
\boxed{\omega=\sqrt{\frac{g}{L}}}
$$

### Frequency

$$
\boxed{f=\frac{1}{2\pi}\sqrt{\frac{g}{L}}}
$$

Important:

- Independent of bob mass.
- Independent of amplitude for small oscillations.
- Depends on length and gravitational acceleration.

### Simple Pendulum in an Accelerating Lift

| Lift Condition | Effective Gravity |
|---|---|
| Accelerating upward with $a$ | $g+a$ |
| Accelerating downward with $a$ | $g-a$ |
| Free fall | $0$ |

General formula:

$$
\boxed{T=2\pi\sqrt{\frac{L}{g_{\text{eff}}}}}
$$

---

## 15. Compound Pendulum

**BITSAT: MUST KNOW**

For a rigid body oscillating about a horizontal axis:

### Time Period

$$
\boxed{T=2\pi\sqrt{\frac{I}{mgd}}}
$$

Where:

- $I$ = Moment of inertia about the pivot.
- $m$ = Mass of the body.
- $d$ = Distance between pivot and centre of mass.
- $g$ = Acceleration due to gravity.

Using the parallel-axis theorem:

$$
I=I_{\text{cm}}+md^2
$$

Therefore:

$$
\boxed{T=2\pi\sqrt{\frac{I_{\text{cm}}+md^2}{mgd}}}
$$

### Equivalent Length of Simple Pendulum

$$
\boxed{L_{\text{eq}}=\frac{I}{md}}
$$

And:

$$
T=2\pi\sqrt{\frac{L_{\text{eq}}}{g}}
$$

---

## 16. Bar Pendulum

**BITSAT: GOOD TO KNOW — Application of Compound Pendulum**

A uniform bar of length $L$, pivoted at one end:

Moment of inertia about one end:

$$
I=\frac{mL^2}{3}
$$

Distance of centre of mass from pivot:

$$
d=\frac{L}{2}
$$

Using the compound pendulum formula:

$$
T=2\pi\sqrt{\frac{I}{mgd}}
$$

Therefore:

$$
\boxed{T=2\pi\sqrt{\frac{2L}{3g}}}
$$

---

## 17. Mass Suspended from an Elastic Wire

For a wire having:

- Length = $L$
- Cross-sectional area = $A$
- Young's modulus = $Y$
- Suspended mass = $m$

From Young's modulus:

$$
Y=\frac{\text{Stress}}{\text{Strain}}
$$

$$
Y=\frac{F/A}{x/L}
$$

Rearranging:

$$
F=\frac{YA}{L}x
$$

Comparing with Hooke's law:

$$
F=kx
$$

Effective spring constant:

$$
\boxed{k=\frac{YA}{L}}
$$

### Time Period

$$
\boxed{T=2\pi\sqrt{\frac{mL}{YA}}}
$$

### Angular Frequency

$$
\boxed{\omega=\sqrt{\frac{YA}{mL}}}
$$

### Static Extension

$$
\boxed{x_0=\frac{mgL}{YA}}
$$

Important:

The wire behaves like a spring, with its elasticity providing the restoring force.

---

## 18. Liquid Oscillations in a U-Tube

**GOOD TO KNOW — Additional Application**

For a uniform U-tube containing liquid:

- Total liquid-column length = $L$
- Cross-sectional area = $A$
- Liquid density = $\rho$

If liquid is displaced vertically by $x$ in one arm, the level difference becomes $2x$.

Restoring acceleration:

$$
a=-\frac{2g}{L}x
$$

Therefore:

### Angular Frequency

$$
\boxed{\omega=\sqrt{\frac{2g}{L}}}
$$

### Time Period

$$
\boxed{T=2\pi\sqrt{\frac{L}{2g}}}
$$

Important:

$L$ represents the total length of the liquid column, not the height of one arm.

---

## 19. Liquid Oscillations in a V-Tube

**LOW PRIORITY — GOOD TO KNOW, NOT GENERALLY ASKED AS A STANDALONE BITSAT QUESTION**

For an ideal V-shaped tube with uniform cross-section:

- Total liquid-column length = $L$
- Left arm inclination = $\alpha$ with horizontal.
- Right arm inclination = $\beta$ with horizontal.

Angular frequency:

$$
\boxed{\omega=\sqrt{\frac{g(\sin\alpha+\sin\beta)}{L}}}
$$

Time period:

$$
\boxed{T=2\pi\sqrt{\frac{L}{g(\sin\alpha+\sin\beta)}}}
$$

For a symmetric V-tube, with each arm making angle $\theta$ with the horizontal:

$$
\boxed{T=2\pi\sqrt{\frac{L}{2g\sin\theta}}}
$$

---

## 20. Floating Body Slightly Pressed and Released

**LOW PRIORITY — GOOD TO KNOW, NOT GENERALLY ASKED AS A STANDALONE BITSAT QUESTION**

For a floating body:

- Mass = $m$
- Liquid density = $\rho$
- Horizontal cross-sectional area at the liquid surface = $A$

If the body is pressed down by a small distance $x$:

Extra displaced volume:

$$
\Delta V=Ax
$$

Extra buoyant force:

$$
F=\rho gAx
$$

This force acts upward, opposite to the displacement.

Effective spring constant:

$$
\boxed{k_{\text{eff}}=\rho gA}
$$

### Angular Frequency

$$
\boxed{\omega=\sqrt{\frac{\rho gA}{m}}}
$$

### Time Period

$$
\boxed{T=2\pi\sqrt{\frac{m}{\rho gA}}}
$$

Assumptions:

- Small vertical oscillations.
- Body remains floating.
- Cross-sectional area at the waterline remains approximately constant.
- Fluid resistance is neglected.

---

## 21. Ball Oscillating Inside a Smooth Bowl

**LOW PRIORITY — GOOD TO KNOW, NOT GENERALLY ASKED AS A STANDALONE BITSAT QUESTION**

For a point-like ball sliding inside a smooth spherical bowl of radius $R$:

The ball behaves like a simple pendulum of effective length $R$ for small oscillations.

### Time Period

$$
\boxed{T=2\pi\sqrt{\frac{R}{g}}}
$$

### Angular Frequency

$$
\boxed{\omega=\sqrt{\frac{g}{R}}}
$$

Assumption:

The ball slides without friction, and oscillations are small.

If the ball has appreciable size, use the radius of the path traced by its centre.

If it rolls instead of sliding, rotational inertia must also be considered.

---

## 22. Ball Moving Through a Tunnel Through Earth

**LOW PRIORITY — GOOD TO KNOW, NOT GENERALLY ASKED AS A STANDALONE BITSAT QUESTION**

Assume:

- Earth has uniform density.
- Earth radius = $R_E$.
- Tunnel is straight and frictionless.

At a distance $x$ from Earth's centre:

$$
g_x=\frac{g}{R_E}x
$$

Restoring acceleration:

$$
a=-\frac{g}{R_E}x
$$

### Angular Frequency

$$
\boxed{\omega=\sqrt{\frac{g}{R_E}}}
$$

### Time Period

$$
\boxed{T=2\pi\sqrt{\frac{R_E}{g}}}
$$

The same time period applies to an ideal straight tunnel along any chord of a uniform-density Earth.

---

## 23. Conical Pendulum

**GOOD TO KNOW — Circular Motion Application, NOT SHM**

A bob of mass $m$ moves in a horizontal circle with a string of length $L$, making angle $\theta$ with the vertical.

### Vertical Force Balance

$$
\boxed{\mathcal{T}\cos\theta=mg}
$$

### Horizontal Component Provides Centripetal Force

$$
\boxed{\mathcal{T}\sin\theta=\frac{mv^2}{r}}
$$

Where $\mathcal{T}$ is tension.

### Radius of Circular Path

$$
\boxed{r=L\sin\theta}
$$

### Angular Speed

$$
\boxed{\omega=\sqrt{\frac{g}{L\cos\theta}}}
$$

### Time Period of Circular Motion

$$
\boxed{T=2\pi\sqrt{\frac{L\cos\theta}{g}}}
$$

### Frequency

$$
\boxed{f=\frac{1}{2\pi}\sqrt{\frac{g}{L\cos\theta}}}
$$

Remember:

A conical pendulum executes uniform circular motion, not SHM.

---

# PART 3 — DAMPED AND FORCED OSCILLATIONS

## 24. Damped Oscillations

For a damped oscillator with damping force proportional to velocity:

$$
F_d=-bv
$$

The amplitude decreases exponentially:

$$
\boxed{A=A_0e^{-\frac{bt}{2m}}}
$$

Where:

- $A_0$ = Initial amplitude.
- $b$ = Damping constant.
- $m$ = Mass.
- $t$ = Time.

For an underdamped oscillator:

$$
\boxed{\omega_d=\sqrt{\omega_0^2-\frac{b^2}{4m^2}}}
$$

Where:

$$
\omega_0=\sqrt{\frac{k}{m}}
$$

is the natural angular frequency without damping.

---

## 25. Forced Oscillations and Resonance

When an external periodic force acts on an oscillator, it undergoes forced oscillations.

### Resonance

Resonance occurs when the driving frequency matches the natural frequency.

For an ideal undamped oscillator:

$$
\boxed{f_{\text{driving}}=f_{\text{natural}}}
$$

Or:

$$
\boxed{\omega_{\text{driving}}=\omega_0}
$$

At resonance, amplitude becomes maximum in the ideal undamped case.

With damping, the resonance amplitude remains finite.

---

# PART 4 — BITSAT PRIORITY SUMMARY

| Topic | Priority | Preparation |
|---|---|---|
| SHM Kinematics | MUST KNOW | Master all formulas |
| Time Period, Frequency, Angular Frequency | MUST KNOW | Master |
| Velocity and Acceleration | MUST KNOW | Master |
| Energy in SHM | MUST KNOW | Master |
| Phase and Phase Difference | MUST KNOW | Master |
| Spring-Mass System | MUST KNOW | Master |
| Simple Pendulum | MUST KNOW | Master |
| Compound Pendulum | MUST KNOW | Know general formula and applications |
| Bar Pendulum | GOOD TO KNOW | Learn as a compound pendulum application |
| Elastic Wire | GOOD TO KNOW | Understand derivation |
| U-Tube Liquid Oscillation | GOOD TO KNOW | Know standard derivation |
| V-Tube Liquid Oscillation | LOW PRIORITY | Understand basic idea; rarely asked standalone |
| Floating Body | LOW PRIORITY | Know formula and restoring-force logic |
| Ball in a Bowl | LOW PRIORITY | Know the simple-pendulum analogy |
| Ball Through Earth Tunnel | LOW PRIORITY | Know standard result |
| Conical Pendulum | GOOD TO KNOW | Learn force equations and time period |
| Damped Oscillations | MUST KNOW | Understand amplitude decay and frequency |
| Forced Oscillations | MUST KNOW | Understand driving frequency |
| Resonance | MUST KNOW | Understand condition and effects |

---

# PART 5 — GENERAL METHOD FOR UNFAMILIAR SHM SYSTEMS

If you encounter an unfamiliar oscillating system, use this approach:

1. Displace the object slightly by a distance $x$ from equilibrium.
2. Identify the restoring force.
3. Write the restoring force in the form:

$$
F=-kx
$$

4. Apply Newton's second law:

$$
ma=-kx
$$

5. Compare with the standard SHM equation:

$$
a=-\omega^2x
$$

6. Identify angular frequency:

$$
\boxed{\omega=\sqrt{\frac{k}{m}}}
$$

7. Calculate time period:

$$
\boxed{T=\frac{2\pi}{\omega}}
$$

The central idea:

**If the restoring acceleration is directly proportional to displacement and directed towards equilibrium, the motion is SHM.**

You can derive many unfamiliar SHM time periods using this method instead of memorising dozens of separate formulas.