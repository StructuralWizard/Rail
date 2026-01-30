<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# Lesson: Permanent Way Engineering – Design, Construction, and Standards

## 1. Definition of Track: Types, Functions, and Parts

The railway track (permanent way) acts as a guideway for trains, absorbing and distributing static and dynamic loads to the subsoil. It is a composite system divided into two main parts:

* **Superstructure:** Rails, fastenings, sleepers (ties), and ballast (or slab).
* **Substructure:** Sub-ballast (protective layers), formation (earthworks), and subgrade.


### Perspectives on Track Types

* **Network Rail (UK):** Classifies track into Categories (1A to 6) based on tonnage and speed. Category 1A represents high-speed/tonnage lines requiring the highest standards (e.g., CEN60 rail, 300mm ballast depth).[^1]
* **HS2 (High Speed 2):** Demands a specific "System" approach. The track is not just components but an integrated system designed for high speeds (360 km/h) and high cumulative tonnage, favoring slab track for stability and reduced maintenance, with ballasted track used in specific sections.[^2]
* **ADIF (Spain):** Distinguishes between "Red Convencional" (Ballasted, 1668mm gauge) and "Alta Velocidad" (Standard gauge 1435mm, often slab track in tunnels/viaducts or high-quality ballast). ADIF standardizes slab track types like Rheda 2000 for high-speed zones.[^3]


## 2. Forces and Calculation

### Static and Dynamic Forces

* **Vertical Forces:** Derived from axle loads (Static).
    * *HS2:* Designed for 250 kN static axle loads, but dynamic forces can reach 350 kN (P2 force) or occasional 500 kN impacts due to wheel defects.[^1]
    * *Theory:* The **Dynamic Amplification Factor (DAF)** increases static load with speed. Eisenmann’s formula is often used to calculate the quasi-static wheel load: $Q_{dyn} = Q_{stat} \cdot (1 + t \cdot \bar{s})$, where $t$ is a statistical confidence factor and $\bar{s}$ is the coefficient of variation.[^4]
* **Lateral Forces:** Caused by curving (centrifugal force), wind, and hunting oscillation (sinusoidal movement).
    * *Network Rail:* Design for 100 kN lateral force over 2m.[^1]
    * *Limit:* The Prud'homme limit is often cited for lateral resistance: $\Sigma Y_{lim} = \alpha (10 + \frac{P}{3})$.[^4]
* **Longitudinal Forces:** Arise from acceleration, braking (up to 1200 kN per rail on HS2/NR), and thermal expansion/contraction in Continuously Welded Rail (CWR).[^1]


### Calculation Considering Dynamic Effects

Modern calculation treats the track as a beam on an elastic foundation (Zimmermann method).

* **Track Stiffness (k):** A critical parameter.
    * *Ballasted:* Stiffness varies (approx. 50-100 kN/mm).
    * *Slab Track:* High stiffness (>60 kN/mm) requires elastic pads to mimic ballast elasticity (aiming for ~22.5 kN/mm system stiffness for high speed to reduce vibration).[^2]
* **Dynamic Settlement:** Settlement is a function of dynamic force cycles. The rate of settlement $s$ is proportional to $\log(N)$ (number of cycles).


## 3. Track Resistance and Deformation

* **Lateral Displacement Resistance (LDR):** The resistance of sleepers to moving sideways in ballast.
    * *Factors:* Ballast shoulder width, sleeper weight, and bottom friction.
    * *Values:* Concrete sleepers provide ~5-9 kN resistance (unconsolidated) vs. ~13 kN (stabilized).
    * *NR Requirement:* 450mm ballast shoulder for CWR on curves <2000m radius to ensure stability.[^1]
    * *HS2 Requirement:* 1100mm shoulder width for high-speed stability.[^2]
* **Longitudinal Resistance:** Resistance to rail creeping and CWR breathing. Provided by fastenings (>7 kN creep resistance ) and sleeper-ballast friction.[^5]
* **Deformation Modes:**
    * *Vertical:* Settlement (voiding).
    * *Lateral:* Buckling (sun kink) due to thermal compression.


## 4. Rails

### Requirements and Types

* **Profiles:**
    * **HS2:** Specifies **CEN60 E2** (60 kg/m) profile, inclined at 1:20.[^2]
    * **Network Rail:** Uses **CEN60** for Cat 1A/1 lines; **CEN56** (113A) permitted for lower categories.[^1]
    * **ADIF:** Standardizes **UIC60** (60 E1) for high-speed and **UIC54** for conventional lines.[^3]
* **Steel Grades:**
    * **R260 (Mn):** Standard grade (min 260 HB hardness).
    * **R350HT (Head Hardened):** Heat-treated for high wear resistance, used in tight curves and high-speed lines to resist Rolling Contact Fatigue (RCF).
* **Lengths:**
    * *HS2:* Supplied in 108m lengths, factory welded to **216m** strings.[^2]
    * *NR:* Typically 108m or 216m delivered strings.


### Defects and Treatment

* **Defects:**
    * *Squats:* Surface-breaking cracks caused by high contact stresses.
    * *Head Checking:* Fine cracks on the gauge corner in curves (RCF).
    * *Tache Ovale:* Internal fatigue flaw (kidney fracture) from hydrogen embrittlement (mostly eliminated in modern steel).
* **Treatment:**
    * *Grinding:* Preventive grinding removes micro-cracks before they propagate. HS2 mandates regular acoustic grinding for noise control.
    * *Ultrasonic Testing (UT):* Used by measuring trains (e.g., Sperry cars) to detect internal flaws.


### Welding

* **Flash Butt Welding (FBW):** Preferred for plain line (no foreign material, forged grain structure). HS2 requires FBW for all plain line.[^2]
* **Aluminothermic (Thermit):** Molten metal cast. Used for closing welds or where FBW is impossible. Lower fatigue limit than FBW.


## 5. Rail Fastenings

### Standards and Design

* **CEN Standards:** EN 13481 series defines categories (fastening systems for sleepers, slab track, etc.).
* **Rigid vs. Elastic:**
    * *Rigid (e.g., spikes, dog spikes):* Obsolete for main lines; lose clamping force over time.
    * *Elastic (e.g., Pandrol, Vossloh):* Maintain "toe load" (clamping force) even under vibration.
* **Types:**
    * **Pandrol Fastclip (FE):** Pre-assembled, captive system. Standard on NR and HS2 concrete sleepers.[^5]
    * **Vossloh SKL:** Tension clamp (screw-dowel). Common in ADIF and slab track systems (Rheda).
* **Rail Pads:** Critical for load distribution and electrical insulation.
    * *Stiffness:* HS2/Slab track requires "soft" pads (low stiffness) to compensate for the rigid concrete base and prevent rail corrugation.[^2]


## 6. Sleepers

* **Concrete:**
    * *Mono-block:* Standard for high speed (HS2, NR, ADIF). Heavy (>300kg) for stability.
        * *HS2:* Bespoke design, C50/60 concrete, **Under Sleeper Pads (USP)** cast-in to reduce ballast degradation.[^2]
    * *Twin-block:* Two blocks connected by a tie bar (common in France/old ADIF lines), higher lateral resistance but more complex handling.
* **Steel:** Used by NR in secondary lines (Cat 2-6) but **prohibited** in 3rd rail areas or curves <400m without spades. Not used on HS2.[^1]
* **Timber:** Hardwood (Jarrah/Azobé) used by NR in S\&C and heritage, but phased out for plain line due to sustainability and life-cycle costs.[^5]
* **Spacing:**
    * *HS2:* **600mm** (mainline) / 650mm (depots).[^2]
    * *Network Rail:* **650mm** standard.[^1]


## 7. Ballast and Ballast Bed

### Requirements

* **Material:** Crushed igneous rock (Granite/Trap rock).
    * *HS2:* **Category A** (EN 13450), 31.5-50mm size, Los Angeles Coefficient <14 (very hard).[^2]
    * *ADIF:* Type 1 Granite, specific hardness and shape index (polyhedral).
* **Dimensions:**
    * *Depth:* Minimum **300mm** below sleeper soffit for high quality (HS2, NR Cat 1A) to distribute pressure to <0.3 MN/m² on formation.[^1][^2]
    * *Profile:* Shoulders are critical for LDR. HS2 requires heaped shoulders or 1100mm width.[^2]
* **Cleaning:** Mechanical ballast cleaners remove "fines" (broken ballast/mud). "Fouling Index" determines need for renewal.


## 8. Track Formation (Earthworks)

* **Bearing Capacity:**
    * *Ev2 (Deformation Modulus):* Critical parameter measured by Plate Load Test.
    * *HS2/ADIF Requirement:* Ev2 > 60 MN/m² (or higher for slab track bases).
    * *Stiffness:* NR requires 45 MN/m² stiffness for new formation.[^1]
* **Drainage:** The single most important factor. Formation must have a crossfall (typically 1:25 or 1:30) to shed water to side drains.
* **Protective Layers (PSS):** "Blanket" of sand/gravel or asphalt (HS2 uses asphalt sub-ballast) to prevent subgrade erosion and protect against frost.[^2]


## 9. Ballasted Track: Specifics

* **Properties:** Elastic, adjustable, lower initial cost, familiar maintenance (tamping).
* **Critical Speed:** As train speed approaches the Rayleigh wave speed of the soil, "critical velocity" effects cause massive rail deflection. High-speed lines require stiff formation to push this critical speed >400 km/h.[^4]
* **Fines:** "Ballast attrition" creates fines. If fines >30% by mass, drainage fails (fouled ballast), causing "wet beds" and pumping sleepers.
* **High Speed:** HS2 uses ballasted track in open routes but specifies **Under Sleeper Pads (USP)** to increase contact area and reduce ballast contact stress, extending maintenance cycles.[^2]


## 10. Slab Track (Ballastless)

### Properties and Requirements

* **Rigidity:** High structural stiffness requires elastic layers (fastenings/pads/USPs) to provide compliance.
* **Life Cycle:** Higher initial cost (1.3-1.5x ballast) but very low maintenance. Design life ~60 years.[^3]
* **Slab Track Types:**
    * **Cast-in-place (Monolithic):** e.g., **Rheda 2000** (Standard on ADIF/HS2 tunnels). Sleepers embedded in fresh concrete.
    * **Prefabricated:** e.g., **Bögl** (Precast slabs coupled together), **Shinkansen** (Slabs on cement-asphalt mortar).[^3]
    * **Booted Sleepers (LVT/Resilient):** Concrete blocks in rubber "boots" cast into tunnel invert. Used by HS2 in tunnels for vibration isolation.[^2]
    * **Embedded Rail:** Rail encased in polymer/cork (e.g., **Edilon**). Used in stations/depots for flush cleaning and noise reduction.[^3]


### Comparison: Ballasted vs. Slab

| Feature | Ballasted Track | Slab Track |
| :-- | :-- | :-- |
| **Cost** | Low Initial, High Maintenance | High Initial, Low Maintenance |
| **Adjustability** | High (Tamping/Lining) | Low (Shim plates/Grout only) |
| **Stability** | Good (prone to buckling if disturbed) | Excellent (Lateral/Longitudinal) |
| **Noise** | Lower (Ballast absorbs sound) | Higher (Reflective surface) - needs absorbent panels |
| **Use Case** | Open route, embankments (settlement prone) | Tunnels, Viaducts, High Speed (>300km/h) |

### Design "Perspectives"

* **HS2:** Mandates slab track in tunnels and on viaducts (to reduce dead load). Uses **precast slab** methodology for speed/quality.[^2]
* **ADIF:** Extensive use of **Rheda 2000** and **Contec** in high-speed tunnels. Strict "transition zones" (zones of varying stiffness) required between slab and ballast.[^3]
* **Network Rail:** Generally ballasted, but uses slab track (e.g., **PACT**, **Sonneville**) in tunnels (e.g., Thameslink, Crossrail) or where clearance is tight (slab is thinner than ballast).[^1]
<span style="display:none">[^6][^7]</span>

<div align="center">⁂</div>

[^1]: NR_L2_TRK_2102-Design-and-Construction-of-Track-former.pdf

[^2]: HS2-HS2-RT-STD-000-000004-P06-Technical-Standard-General-Track-Specification-tra.pdf

[^3]: 11.0-Via-en-placa.pdf

[^4]: TrackCompendium_2StructureTrack-Compendium.pdf

[^5]: TrackCompendium_4FasteningsTrack-Compendium.pdf

[^6]: ET03.360.161.8_ED3Carril.pdf

[^7]: ET03.360.004.0_ED1M1Balasto.pdf

