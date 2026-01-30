<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# - Joints:

    * reason
    * position
    * types clasification
    * working mechanisim and fishplates
    - Continuous Welded Rail:
    * restrained expansion
    * breaking
    * anchoring
    * welding
    * stress free temperature
    * CWR failures

make sure that you use the files that you have in Spanish as well

Based on the provided documents, here is the report on Joints and Continuous Welded Rail (CWR).

### **1. Joints**

Rail joints are the weakest points in the track structure due to the discontinuity in stiffness and the dynamic impact forces they generate.[^1]

* **Reason**
    * **Thermal Expansion:** Joints provide a gap (cala) to allow the rail to expand and contract with temperature changes without inducing excessive internal stresses.[^1]
    * **Manufacturing Limitations:** Rails are manufactured in limited lengths (e.g., 18m "elementary bars") due to rolling mill and transport constraints. Joints are necessary to connect these segments if they are not welded.[^1]
* **Position**
    * **Relative to Sleepers:**
        * **Suspended (Suspendida):** The joint is positioned between two sleepers (traviesas de junta). This is the most common method (used by Adif) as it provides elasticity and avoids the "anvil effect".[^1]
        * **Supported (Apoyada):** The joint rests directly on a sleeper. This often leads to sleeper instability (rocking) and ballast pulverization.[^1]
        * **Semi-suspended:** A compromise where long fishplates reach the adjacent sleepers.[^1]
    * **Relative to Parallel Rail:**
        * **Square (Concordantes):** Joints on left and right rails are aligned. This is preferred for stability and maintenance.[^1]
        * **Staggered (Alternadas):** Joints are offset. This can reduce noise but may induce rolling motion in vehicles.[^1]
* **Types Classification**
Joints are classified by their electrical insulation and assembly method:[^1]
    * **Non-Insulating (No Aislantes):** Used for mechanical continuity.
        * *Ordinary Joint:* Standard fishplated connection.
        * *Butt Joint (A Tope):* Robust joint with zero gap, often used in switches.
        * *Quick Assembly (Embridado rápido):* Uses C-clamps instead of bolts for emergency repairs.[^1]
    * **Insulating (Aislantes):** Used to separate electrical track circuits.
        * *Non-Glued:* Uses insulating liners (bakelite, fiberglass) but relies on bolts.
        * *Glued (Encolada - JAE):* The most robust type for CWR. Assembled in workshops or in-situ using high-strength epoxy to create a rigid, monolithic joint.[^1]
* **Working Mechanism and Fishplates**
    * **Fishplates (Bridas):** Metal plates that connect rail ends. They are designed to fit between the rail head and foot (fishing surfaces).[^1]
    * **Mechanism:** They transmit vertical and lateral loads (shear and bending) across the joint, acting similarly to a beam. They allow longitudinal movement (expansion) within the bolt holes, which are oval-shaped or larger than the bolt diameter to permit sliding.[^1]

***

### **2. Continuous Welded Rail (CWR)**

CWR (Barras Largas Soldadas - BLS) eliminates joints to create a smoother, lower-maintenance track.[^1]

* **Restrained Expansion (Dilatación Restringida)**
    * In CWR, the rail is not free to expand. Expansion is **restrained** by the friction of the fastenings and ballast.
    * According to Hooke's Law, because the rail cannot expand ($\Delta L = 0$), the thermal strain is converted into internal stress ($\sigma = E \cdot \alpha \cdot \Delta T$). This results in significant compressive or tensile forces (e.g., ~52 tons for a 30°C change in UIC-60 rail).[^1]
    * The central zone of a CWR string remains stationary; only the ends move.[^1]
* **Breathing (Breaking)** *(Note: Interpreted as "Breathing" based on context)*
    * The **Breathing Zone (Zona de respiración)** is the length at the ends of a CWR string where the rail *does* move.
    * In this zone, the cumulative friction force from sleepers is not yet enough to fully overcome the thermal force.
    * The length of this zone ($Z$) depends on the temperature change (\$ \Delta T$), rail cross-section ($S$), Young's modulus ($E$), and longitudinal resistance ($r\$). For a UIC-60 rail with concrete sleepers, this zone can be ~60–80 meters depending on temperature.[^1]
* **Anchoring**
    * Anchoring is achieved through the **longitudinal resistance** provided by:

1. **Fastenings:** High-toes load elastic clips (e.g., Vossloh SKL, Pandrol) tightly grip the rail to the sleeper.[^1]
2. **Ballast:** The friction between the sleeper and the ballast bed prevents the sleeper from moving. Concrete sleepers offer higher resistance (approx 1000 kg/m) compared to wood (500 kg/m) due to their weight and surface friction.[^1]
* **Welding**
Two main methods join rails into CWR:[^2][^1]
    * **Electric Flash-Butt Welding (Soldadura eléctrica):** Uses high current to melt rail ends without filler material. It produces high-quality, homogenous welds with fewer defects. Used in workshops to make long bars (e.g., 288m) or by mobile machines.[^2][^1]
    * **Aluminothermic Welding (Soldadura aluminotérmica):** Chemical reaction (exothermic) between aluminum and iron oxide creates molten steel poured into a mould. Used *in-situ* to join long bars. It is cheaper and portable but has a wider Heat Affected Zone (HAZ) and lower mechanical properties than flash-butt welds.[^2][^1]
* **Stress Free Temperature (Temperatura de Neutralización)**
    * This is the temperature at which the rail has zero internal stress.
    * **Formula:** $T_n = \frac{T_{max} + T_{min}}{2} + 5^\circ C$. In Spain (Adif), it typically ranges between 25°C and 38°C depending on the region.[^1]
    * **Process:** "Neutralization" (stressing) involves unclipping the rail, cutting it to the correct length (or stretching it with tensors) to match the theoretical length at $T_n$, and re-clipping it to "lock in" this stress-free state.[^1]
* **CWR Failures**
    * **Buckling (Pandeo):** Occurs in hot weather when compressive forces exceed the track's lateral resistance. The track snaps out of alignment laterally. This is a critical safety risk.[^1]
    * **Rail Breaks (Roturas) / Pull-aparts:** Occur in cold weather when tensile forces exceed the rail's ultimate strength or, more commonly, trigger a fracture at a weak point (like a weld or defect). CWR fractures are most frequent at low temperatures.[^2][^1]
<span style="display:none">[^3]</span>

<div align="center">⁂</div>

[^1]: 7.0-Sujeciones-y-juntas.pdf

[^2]: TrackCompendium_3RailsTrack-Compendium.pdf

[^3]: 6.0-Carril_traviesas.pdf

