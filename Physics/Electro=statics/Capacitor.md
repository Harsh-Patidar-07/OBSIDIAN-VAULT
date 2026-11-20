### 1. Charge ($Q$) vs. Potential ($V$) in Series and Parallel

#### **In Series (Two capacitors in a single unbroken line)**

- **Constant quantity:** **Charge ($Q$)** is the **same** on both capacitors ($Q_1 = Q_2 = Q$), assuming they started uncharged before being connected.
    
    - _Why?_ The inner plates connecting the two capacitors form an **isolated metal island** with no wire leading to the battery. Because total charge on that island must stay zero, pulling $+Q$ onto the first plate forces $-Q$ onto its facing plate, which leaves $+Q$ on the next plate. Charge cannot accumulate or vanish mid-line.
        
- **Divided quantity:** **Potential ($V$)** splits across them—and it is **not** equally distributed unless $C_1 = C_2$. Since $V = \frac{Q}{C}$ and $Q$ is identical:
    
    $$V_1 : V_2 = \frac{1}{C_1} : \frac{1}{C_2}$$
    
    The **smaller** capacitor takes the **larger** voltage drop, and $V_{\text{total}} = V_1 + V_2$._(Edge case: If the capacitors were pre-charged before being connected in series, the **change** in charge $\Delta Q$ on each is identical, rather than their total $Q$.)_
    

#### **In Parallel (Capacitors connected between the same two junctions)**

- **Constant quantity:** **Potential difference ($V$)** is the **same** across each capacitor ($V_1 = V_2 = V$) because both ends are wired to the same two equipotential nodes.
    
- **Divided quantity:** **Charge ($Q$)** splits across the branches—again, **not** equally unless $C_1 = C_2$. Since $Q = CV$ and $V$ is identical:
    
    $$Q_1 : Q_2 = C_1 : C_2$$
    
    The **larger** capacitor stores the **larger** charge, and $Q_{\text{total}} = Q_1 + Q_2$.


---


### 2. Charging and Discharging of an RC Circuit

Where:

- $E$ = Battery EMF (or initial voltage across the capacitor before discharging)
    
- $R$ = Resistance, $C$ = Capacitance
    
- $\tau = RC$ = Time constant
    
- $Q_0 = CE$ = Maximum (or initial) charge
    
- $I_0 = \frac{E}{R}$ = Initial peak current at $t = 0$
    

![[Pasted image 20261120210844.png]]

|**Topic / Parameter**|**Charging**|**Discharging**|
|---|---|---|
|**Setup & Mechanism**|Capacitor, resistor ($R$), battery ($V$), and key ($S$) connected in series; key is closed.|Charged capacitor, resistor ($R$), and key ($S$) connected in series; stored energy circulates current.|
|**Circuit Loop Equation**|$V = V_C + V_R = \dfrac{Q}{C} + IR = \dfrac{Q}{C} + \dfrac{dQ}{dt}R$|$V_C + V_R = 0$|
|**Charge at any instant ($Q$)**|$Q = CV\left(1 - e^{-t/RC}\right) = Q_0\left(1 - e^{-t/RC}\right)$|$Q = Q_0 e^{-t/RC}$|
|**Value at $t = \tau = RC$ (Time Constant)**|$Q = Q_0\left(1 - e^{-1}\right) = 0.632\,Q_0$<br><br>  <br>  <br><br>_Charge increases to **63.2%** of maximum charge $Q_0$ in time $\tau$._|$Q = Q_0 e^{-1} = 0.368\,Q_0$<br><br>  <br>  <br><br>_Charge decreases to **36.8%** of initial charge $Q_0$ in time $\tau$._|
|**Current at any instant ($i$)**|$i = \dfrac{dQ}{dt} = i_0 e^{-t/RC} \quad \left\{i_0 = \dfrac{Q_0}{RC} = \dfrac{V}{R}\right\}$|$i = \dfrac{dQ}{dt} = -i_0 e^{-t/RC} \quad \left\{i_0 = \dfrac{Q_0}{RC} = \dfrac{V_0}{R}\right\}$|
|**Potential across Capacitor ($V_C$)**|$V_C = V\left(1 - e^{-t/RC}\right)$|$V_C = V_0 e^{-t/RC}$|

_(Note: At $t = \tau = RC$, $e^{-1} \approx 0.37$, meaning a charging capacitor reaches **63%** of $Q_0$, while a discharging capacitor drops to **37%** of $Q_0$.)_


---

