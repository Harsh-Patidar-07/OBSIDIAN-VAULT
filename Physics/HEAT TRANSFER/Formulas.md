# Heat Transfer — BITSAT Physics Formula Sheet

## 1. Thermal Expansion

### Linear Expansion

$$  
\Delta L = L_0 \alpha \Delta T  
$$

### Area Expansion

$$  
\Delta A = A_0 \beta \Delta T  
$$

For isotropic solids:

$$  
\beta \approx 2\alpha  
$$

### Volume Expansion

$$  
\Delta V = V_0 \gamma \Delta T  
$$

For isotropic solids:

$$  
\gamma \approx 3\alpha  
$$

### Thermal Stress

For a rod whose expansion is completely prevented:

$$  
\boxed{\text{Thermal stress} = Y\alpha\Delta T}  
$$

Here, $Y$ is Young's modulus. The magnitude applies to both heating and cooling; the stress is compressive on heating and tensile on cooling.

---

## 2. Calorimetry

### Heat Required to Change Temperature

$$  
\boxed{Q = mc\Delta T}  
$$

### Heat Capacity

$$  
Q = C\Delta T  
$$

$$  
C = mc  
$$

### Latent Heat

Melting or freezing:

$$  
Q = mL_f  
$$

Boiling or condensation:

$$  
Q = mL_v  
$$

### Principle of Calorimetry

For an isolated system:

$$  
\boxed{\text{Heat lost} = \text{Heat gained}}  
$$

Equivalently:

$$  
\sum Q = 0  
$$

Use signed heat quantities: heat gained is positive and heat lost is negative.

---

## 3. Conduction

### 3.1 Steady-State Conduction Through a Slab

Heat transfer rate:

$$  
\boxed{H = \frac{kA(T_1-T_2)}{L}}  
$$

Total heat transferred in time $t$:

$$  
\boxed{Q = Ht = \frac{kA(T_1-T_2)}{L}t}  
$$

Heat flux:

$$  
q'' = \frac{H}{A} = \frac{k(T_1-T_2)}{L}  
$$

### 3.2 Thermal Resistance

$$  
\boxed{R_{\text{th}} = \frac{L}{kA}}  
$$

$$  
\boxed{H = \frac{\Delta T}{R_{\text{th}}}}  
$$

Analogy with electricity:

$$  
I = \frac{\Delta V}{R}  
$$

Temperature difference corresponds to voltage difference, and heat transfer rate corresponds to electric current.

### 3.3 Composite Slabs in Series

For $n$ slabs with the same cross-sectional area:

$$  
\boxed{R_{\text{eq}} = \sum_{i=1}^{n}\frac{L_i}{k_iA}}  
$$

$$  
\boxed{H = \frac{T_{\text{hot}}-T_{\text{cold}}}{R_{\text{eq}}}}  
$$

Equivalently:

$$  
\boxed{  
H = \frac{A(T_{\text{hot}}-T_{\text{cold}})}  
{\displaystyle\sum_{i=1}^{n}\frac{L_i}{k_i}}  
}  
$$

At steady state, the heat transfer rate is identical through every layer.

### 3.4 Slabs in Parallel

For separate heat-flow paths between the same temperatures:

$$  
\boxed{H = \sum_i \frac{k_iA_i\Delta T}{L_i}}  
$$

Equivalent thermal resistance:

$$  
\boxed{\frac{1}{R_{\text{eq}}} = \sum_i\frac{1}{R_i}}  
$$

### 3.5 Hollow Cylindrical Shell

For inner radius $r_i$, outer radius $r_o$, length $L$, and constant thermal conductivity:

$$  
\boxed{  
H = \frac{Q} T= \frac{2\pi kL(T_i-T_o)}  
{\ln(r_o/r_i)}  
}  
$$

Thermal resistance:

$$  
R_{\text{cyl}} = \frac{\ln(r_o/r_i)}{2\pi kL}  
$$

### 3.6 Hollow Spherical Shell

$$  
\boxed{  
H = \frac{Q} T = \frac{4\pi k r_i r_o(T_i-T_o)}  
{r_o-r_i}  
}  
$$

Thermal resistance:

$$  
\boxed{  
R_{\text{sph}} = \frac{r_o-r_i}{4\pi k r_i r_o}  
}  
$$

> Ri = Inner radius, Ro = Outer radius of the Sphere

**Priority:** Master slab conduction, thermal resistance, and composite slabs first. Cylindrical and spherical conduction are lower-priority extensions for BITSAT.

---

## 4. Convection and Newton's Law of Cooling

### 4.1 Newton's Law of Cooling

For a body cooling in surroundings at constant temperature:

$$  
\boxed{-\frac{dT}{dt}=k_c(T-T_s)}  
$$

Here $k_c$ is the cooling constant and $T_s$ is the surroundings' temperature.

Integrated form:

$$  
\boxed{T-T_s=(T_0-T_s)e^{-k_ct}}  
$$

Time taken to cool from $T_1$ to $T_2$:

$$  
\boxed{  
t = \frac{1}{k_c}  
\ln\left(\frac{T_1-T_s}{T_2-T_s}\right)  
}  
$$

This is an approximate law, particularly useful when the temperature difference between the body and its surroundings is relatively small.

### 4.2 Convective Heat Transfer

$$  
\boxed{H = hA(T_{\text{surface}}-T_{\infty})}  
$$

Total heat transferred when the rate is constant:

$$  
Q = Ht  
$$

Here $h$ is the convective heat-transfer coefficient and $T_{\infty}$ is the fluid temperature away from the surface.

---

## 5. Radiation

### 5.1 Stefan–Boltzmann Law

Power radiated by a black body:

$$  
\boxed{P = \sigma AT^4}  
$$

For a real body:

$$  
P = \varepsilon\sigma AT^4  
$$

Stefan–Boltzmann constant:

$$  
\sigma = 5.67\times10^{-8}\ \mathrm{W,m^{-2},K^{-4}}  
$$

### 5.2 Net Radiation Heat Transfer

For a body exchanging radiation with large surroundings:

$$  
\boxed{  
H = \varepsilon\sigma A(T^4-T_s^4)  
}  
$$

Total heat transferred in time $t$, if the rate remains constant:

$$  
Q = Ht  
$$

**Use absolute temperature in kelvin.**

