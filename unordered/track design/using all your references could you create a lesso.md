<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# using all your references could you create a lesson explaining the following topics:

Ballasted track:

- Thicknesses of ballast and subballast layer layer
- Ballast sections and its parts
- Ballast properties:
    * material
    * properties
    * requirements
    * tests
    * cleaning
- Sleepers:
    * wooden vs steel vs composite vs concrete sleepers,
    * purpose,
    * calculation,
    * lateral and longitudinal resistance
- Fasteners:
    * Functions
    * Types (rigid and elastic ) and models
    * Elements

Now I'll create the comprehensive lesson using all the references from the provided files and search results.

# Ballasted Track Engineering: A Comprehensive Technical Lesson

## 1. Ballasted Track: Layer Thicknesses

### 1.1 Ballast Layer Thickness

The ballast thickness—measured as the distance between the lower surface of the sleeper and the subsoil—should be as large as possible. The pressure distribution lines should intersect; otherwise, the subsoil would be pressed up between the sleepers.[^1]

**Standard thickness requirements:**

- **Minimum ballast bed thickness:** At least 30 cm for axle loads of 220 kN, with a sleeper spacing of 60 cm and a sleeper width of 28 cm[^1]
- **High-speed lines:** A thickness of 40 cm is advisable[^1]
- **Sleeper end ballast:** 45 to 50 cm of ballast at the sleeper ends is essential to guarantee significant resistance to lateral displacement[^1]

**Thickness variation by line type:**[^1]


| Line Type | Speed (km/h) | Standard Thickness (cm) | Frost Area Requirements (cm) |
| :-- | :-- | :-- | :-- |
| High-speed (HGV 300) | 300 | 70 | 70-70 |
| Upgraded passenger lines | 160-230 | 50-60 | 60-70 |
| Commuter traffic | 80-120 | 30-40 | 40-50 |
| Goods traffic | ≤50 | 20-40 | 20-30 |

### 1.2 Subballast (Formation Protective) Layer

```
The formation protective layer enables gradual transition of the moduli of elasticity from ballast to subsoil. **The minimum thickness is 20 cm**, but when the bearing capacity of the earth formation is very low (E<sub>ef</sub> ≤ 10 MN/m²), soil replacement should be considered.[^2]
```

**Functions of the formation protective layer:**[^2]

- Transmits track forces onto a larger area, reducing and evening stress on the formation
- Protects frost-sensitive soils when used as a frost protective layer
- Acts as a filter layer preventing ballast from mixing with substructure
- Provides gradual transition of moduli of elasticity from ballast to subsoil
- Improves drainage of surface waters

**Dimensioning requirements:**[^2]

- Cross fall: at least 1:20 or 5% with a tolerance of ±0.5%
- Formation deviation: not more than 2 cm from design position
- Longitudinal levelness: within 2 cm over a 4 m basis

***

## 2. Ballast Sections and Parts

### 2.1 Cross-Sectional Components

**Standard ballast bed cross-section dimensions:**[^1]

- **Ballast width at sleeper ends:**
    - 0.4 m at v ≤ 160 km/h
    - 0.5 m at v > 160 km/h
    - 0.45 m for B75 sleepers (sleeper length 2.8 m)
- **Ballasting height:** Up to the upper edge of the sleeper[^1]
- **Inclination of ballast shoulder:**
    - Designed: 1:1.5
    - Implemented: 1:1.25
- **Cross fall of formation:** 1:20[^1]


### 2.2 Ballast Bed Structure

The ballast bed consists of three grain types that develop over the service life:[^1]

1. **Skeleton grain:** Primary load-bearing particles (new ballast consists almost entirely of skeleton grain)
2. **Distance grain:** Particles sized 15-30 mm that improve resistance to shearing (optimum percentage: up to 15%)[^1]
3. **Filler grain:** Fine material that develops over time, enclosing skeleton grain and reducing the angle of internal friction[^1]

***

## 3. Ballast Properties

### 3.1 Material Requirements

**Suitable materials:**[^1]

- Hard ballast: **basalt, diabase, granite** (most suitable)
- Soft rocks: limestone, dolomite, sedimentary rocks (usually less suitable)

**Raw material requirements:**[^1]

- Resistance to weather influences (determined by freeze-thaw test)
- High toughness (determined in rotary drum grinder)
- High resistance to pressure (determined by pressure and impact tests)
- No loam or earth content
- Rocks should break into sharp-edged cubes


### 3.2 Physical Properties

**Grain size and distribution:**[^1]

- **Main-line tracks:** Crushed ballast 25-60 mm
- **Secondary tracks:** 15-30 mm
- **Grain size:** 22.4-63 mm with undersize part <22.4 mm not exceeding:
    - 3% when sampled at factory
    - 5% when sampled on site

**Grain shape requirements:**[^1]

- Sharp-edged grains of irregular shape
- Share of grains with ratio ≥3:1 must be between 5-30% by weight

```
- Degree of irregularity >15 (U = d<sub>60</sub>/d<sub>10</sub>)[^2]
```


### 3.3 Mechanical Properties

**Shearing behavior:**[^1]
The angle of internal friction (φ) is the most important parameter. Typical values:


| Ballast Type | Share of Toothed-Surface Contact (C) | Angle of Internal Friction (φ) |
| :-- | :-- | :-- |
| New recycled ballast | 9.2 N/cm² | 65.2° |
| Cleaned ballast | 5.34 N/cm² | 59.9° |
| Round gravel | 4.2 N/cm² | 57.4° |
| Contaminated ballast | 5.77 N/cm² | 53.9° |

**Pressure distribution angle:**[^1]

- New sharp-edged ballast: 42°
- Used ballast: 39° (calculated value)
- Contaminated ballast: 30°


### 3.4 Performance Requirements

**Technical conditions for supply:**[^1]


| Property | Requirement |
| :-- | :-- |
| Resistance to weathering | Must pass boiling in saline solution test |
| Water absorption | ≤0.5% by weight |
| Fines through 22.4 mm sieve | <2% by weight |
| Impact resistance (SD<sub>10</sub>) | ≤18% by weight (≤14% for high-speed lines) |
| Los Angeles abrasion | ≤16% by weight |
| Elutriable components (≤0.063 mm) | ≤1% by weight |

### 3.5 Testing Methods

**Los Angeles test (LA):**[^1]

- Specimen: ~10 kg in cylinder with steel balls
- Process: 1000 revolutions at 33 rpm
- Screening: 1.6 mm screen
- Formula: LA = (m/M) × 100
- **Lower LA value = higher abrasion resistance**

**Aggregate Impact Value (AIV):**[^1]

- Specimen: Surface-dried standard grain (10-14 mm)
- Dynamic load: 14 kg dropped 15 times from 380 mm height
- Screening: 2 mm screen
- Formula: AIV = (m/M) × 100
- **Lower AIV = higher impact resistance**

**Deval test (DH):**[^1]

- Used by SNCF and other railways
- Test specimen: grain size 25-50 mm, weight 7 kg
- Process: 10,000 revolutions in inclined cylinders with steel balls and water
- Screening: 1.6 mm screen
- Formula: DH = 2800/m

**Typical ballast material parameters:**[^1]


| Material | LA | AIV | Impact Resistance | DH |
| :-- | :-- | :-- | :-- | :-- |
| Basalt | 8.7-9.5 | 10 | 10.2-11.7 | 10.3-13.8 |
| Porphyry | 10.3 | 10 | 11.9 | 11.1 |
| Sandstone | 12.5 | 11 | 14 | 9.8 |
| Limestone | 13.7-23 | 15-20 | 16.3-21.3 | 5.9 |

### 3.6 Ballast Cleaning

**When to clean:**[^3][^1]
According to ORE study, ballast requires cleaning when contamination (measured as undersize passing through 22.4 mm sieve) reaches **30% by weight**. When track recording car measurements or visual inspections show that tamping cannot durably improve track geometry quality, ballast cleaning is necessary.[^3][^1]

**Cleaning methods:**[^1]

1. **Shoulder cleaning only:** Provides limited improvement but can bridge time until full track renewal[^1]
2. **Full ballast bed cleaning:**[^1]
    - Excavation with excavation chain
    - Screening on multiple vibration screens
    - Immediate elimination of oversize and undersize particles
    - Return of cleaned ballast to excavation site

**Performance:**[^1]

- Latest cleaning machines: 300-700 m/h (500-1000 m/h)
- Annual performance: ~150 km
- After cleaning, track allows train passage at 70 km/h immediately after work completion

**Restoration technology after cleaning:**[^1]

1. First consolidation by tamping machine (tines applied twice) and stabilizer
2. Insert ballast in ~10 cm layers
3. Lift, align, tamp and stabilize track again
4. Final ballasting and third operation
5. After 0.7-1 million tons operational load, treat again with maintenance train

***

## 4. Sleepers

### 4.1 Purpose of Sleepers

Sleepers serve multiple critical functions:[^1]

- Establish and maintain track gauge
- Distribute and transmit forces to the ballast bed (perpendicular axle loads, horizontal centrifugal forces, longitudinal forces)
- Hold rails in position (height, lateral direction, longitudinal direction)
- Secure track under construction, after rail breakage, and after derailment
- Dampen rail vibration and reduce sound/impact waves on environment


### 4.2 Comparison: Wooden vs. Steel vs. Composite vs. Concrete

#### 4.2.1 Wooden Sleepers

**Specifications:**[^1]

- Standard dimensions (Europe): 16-26 × 260 cm (hard wood), 18-23 × 240-270 cm (various species)
- Service life: 25-45 years depending on wood quality and impregnation
- Common species: European oak, beech, pine, Douglas fir, larch, tropical hardwoods (Azob, Ekki, Bangkirai)

**Advantages:**[^1]

- Lower ballast pressure (only 1/3 of concrete sleepers)[^1]
- Better damping behavior against dynamic stress
- More adaptable contact surface (softer than concrete/steel)
- Service life comparable to concrete under proper conditions

**Disadvantages:**[^1]

- Susceptible to weathering and external influences
- Lower resistance to lateral displacement (15% lower than concrete)[^1]
- Not suitable for high-speed lines >160 km/h
- Requires impregnation treatment (creosote)

**Treatment:**[^1]

- Air-dried for 1-2 years
- Pressure impregnation with hot tar oil (Creosote)
- Full impregnation: up to 500 kg tar oil/m³ wood
- Röping method (economic): up to 150 kg tar oil/m³


#### 4.2.2 Steel Sleepers

**Technical data (Sw9 example):**[^1]


| Parameter | Value |
| :-- | :-- |
| Weight | 28.85 kg/m |
| Cross-section area | 36.75 cm² |
| Moment of inertia | 344 cm⁴ |
| Section modulus | 51 cm³ |

**Steel qualities:**[^1]

```
- Tensile strength R<sub>m</sub>: 380-620 N/mm²
```

- Elongation at rupture: 18-24% minimum

**Advantages:**[^1]

- Lower weight (easier handling)
- Lower overall height (less ballast needed)
- Long service life (40-60 years)
- Resistant to termites

**Disadvantages:**[^1]

- Undamped shocks cause heavy ballast wear
- Lower resistance to lateral displacement than concrete sleepers
- Rubbed-off particles cause ballast grains to glue together
- Track lining more difficult (especially British design with drawn-down front sheets)


#### 4.2.3 Y-Steel Sleepers (Special Form)

**Design:**[^1]

- Two hot-rolled wide-flanged I-beams bent in S-shape
- Two straight beam sections
- Connected by welded top and bottom bars
- **Three rail supports** arranged in pairs (vs. traditional two supports)

**Dimensions:**[^1]

- Length: 2.3 m
- Height: 9.5 cm
- Number per km: 803 sleepers (vs. 1667 for conventional)

**Advantages:**[^1]

- Triangular cross-bracing with double support
- High resistance to lateral and longitudinal displacement
- Small overall height
- High torsional and frame stiffness
- Good recycling properties
- Ballast saving: **~30% reduction** (requires only 30 cm ballast at ends)[^1]

**Disadvantages:**[^1]

- Special tamping machines required
- Higher price (70% more than B70 concrete sleeper)
- Difficult correction of major lateral alignment defects


#### 4.2.4 Concrete Sleepers

**Twin-block sleepers:**[^1]


| Type | U41 | U31 | U20 | VSP |
| :-- | :-- | :-- | :-- | :-- |
| Total length (mm) | 2415 | 2252 | 2240 | 2240 |
| Concrete body length (mm) | 840 | 680 | 680 | 680 |
| Width (mm) | 290 | 290 | 290 | 290 |
| Depth (mm) | 220 | 229 | 170 | 170 |
| Weight (kg) | 230 | 200 | 170 | 160 |
| Max speed (km/h) | 300 | 200 | 140 | 50 |
| Axle load (t) | 32 | 22.5 | 22.5 | 22.5 |

**Advantages:**[^1]

- Long service life (50 years)
- More cost-effective than hardwood sleepers
- Lower maintenance of fastenings
- Higher resistance to lateral displacement (due to greater weight)

**Disadvantages:**[^1]

- Susceptible to shock and impact
- Difficult handling (greater weight)
- Maintenance of longitudinal level somewhat more difficult

**Monoblock concrete sleepers:**[^1]

- Service life: 50 years
- Used in Germany, Austria, Canada, Australia, USA, China, Italy, England, Japan, Sweden, India, South Africa, Switzerland, Russia
- Manufactured with 20-40 prestressed wires
- Compressive strength: ~6 kN/cm²
- Bending tensile strength: 0.065 kN/cm² (minimum 5.5 N/mm² for DB AG)
- Prestress target: 320-325 kN → final prestress 260 kN at rail support[^1]

**Design requirements (DB AG B58/B70):**[^1]


| Moment Type | B58 (kN·m) | B70 (kN·m) |
| :-- | :-- | :-- |
| Design moment | 12-16 | 12 |
| Moment of incipient crack | 17-21 | 13 |
| Moment of crack (0.10) | 21-26 | 17 |
| Moment of crack (0.05) | 27-34 | 23 |
| Moment of fracture | 39-48 | 26 |

**Special concrete sleeper types:**[^1]

1. **Wing sleepers:** Features wing-shaped beams below rails; resistance to lateral displacement ~2× higher than B70; allows continuous welded track in radii as narrow as 190 m[^1]
2. **Frame sleepers:** High rigidity with four rail fastenings at corners; resistance to lateral displacement 60 kN at 1 mm displacement; suitable for narrow curves (proven in R=176 m)[^1]
3. **Wide sleepers:** Width 57 cm, length 2.4 m; supporting surface 80% larger than B70; ballast pressure 36% lower[^1]
4. **Soled sleepers:** Elastic material lining at sleeper base; stiffness 10-80 kN/mm (modern: 50-70 kN/mm); contact surface increased by 20-35%; average ballast pressure reduced by 15-35%[^4]

### 4.3 Sleeper Calculation

**Design wheel load calculation:**[^1]

Q = (nominal wheel load) × (dynamic factors)

Dynamic factors:

- **1.75:** Dynamic increase due to vertical track profile defects at v ≥ 200 km/h
- **1.5:** Dynamic increase at v < 200 km/h
- **0.5:** Load distribution factor
- **1.35:** Dynamic increase of sleeper reaction due to cavities
- **1.6:** Dynamic increase of bending moment due to irregularities in longitudinal sleeper support

**Bending tensile strength requirements:**[^1]

- Concrete: ≤3 N/mm²
- Prestressing force: ≤12 N/mm²
- Bending tensile strength after 7 days: ≥6.5 N/mm²
- Compressive strength when prestressing applied: ≥45 N/mm²

**Load distribution:**[^1]
Under a 20-ton axle, typical load distribution to sleepers:

- Central sleeper: 40%
- Two neighboring sleepers: 50% (combined)
- Two following sleepers: 10% (combined)


### 4.4 Lateral and Longitudinal Resistance

#### 4.4.1 Resistance to Lateral Displacement

**Definition:** The force required to displace the sleeper by 2 mm[^1]

**Typical values (per sleeper):**[^1]


| Track Condition | Wooden Sleepers (N) | Concrete Sleepers (N) |
| :-- | :-- | :-- |
| Freely lying, unballasted | 800 | 1200 |
| Loosely ballasted (after cleaning) | 1500 | 2500 |
| Tamped and lined | 2850 | 5100 |
| Dynamically stabilized (DTS) | 3900 | 7900 |
| Well ballasted and fully stabilized | 4800 | 9000 |

**Composition of lateral resistance:**[^1]

- **Bottom friction:** 45-50%
- **Sleeper end resistance:** 35-40%
- **Sleeper shoulder resistance:** 10-15%

**Note:** Bottom friction develops immediately, while sleeper end resistance builds up only after displacement/pressure against ballast[^1]

**Influencing factors:**[^1]


| Factor | Influence Level |
| :-- | :-- |
| Sleeper weight | Very good |
| Sleeper width | Very good |
| Sleeper height | Good |
| Ballast grain size | Minor to good |
| Lateral ballast shoulder height | Good |
| Ballast bed height below sleeper | Good |
| Dynamic track stabilization | Very good |
| Tamping | Poor (reduces resistance by ~40%) |
| Cleaning | Poor (reduces resistance by ~50%) |

**Effect of maintenance:**[^5]

- **Tamping:** Reduces lateral displacement resistance by ~40%[^5]
- **Dynamic Track Stabiliser (DTS):** Increases resistance by 30-50%, returning track to safe operational range[^5]
- **Ballast consolidation in sleeper cribs:** Increases resistance by ~7%[^5]
- **Ballast consolidation at sleeper ends:** Increases resistance by ~4%[^5]


#### 4.4.2 Resistance to Longitudinal Displacement

The longitudinal displacement resistance is approximately the same magnitude as lateral displacement resistance.[^1]

**Typical values (per cm of track length, clean unconsolidated ballast):**[^1]

- Concrete sleepers: ~50 N/cm
- Wooden sleepers: ~40 N/cm
- Steel sleepers: ~70 N/cm

**Effect of stabilization:** Dynamic Track Stabiliser increases values by 30-50%[^1]

**Effect of operational influence:** Values rise by up to 100% due to traffic load[^1]

**Rail creep resistance:** Approximately 12 kN/mm; depends on rail fastening effectiveness and friction between rail foot and rib base plate[^5]

***

## 5. Fasteners

### 5.1 Functions of Rail Fastenings

Rail fastenings serve critical purposes:[^6]

- Maintain track gauge
- Transmit forces acting on and in rails to sleepers
- Provide damped vertical movement (upward and downward)
- Electrically insulate rail against sleeper (for concrete sleepers)
- Resist vertical, lateral, and longitudinal forces

**Required creep force:** Not less than 7 kN[^6]

### 5.2 Types: Rigid vs. Elastic

#### 5.2.1 Rigid Fastenings

**Characteristics:**[^6]

- No elastic compensation for deformations
- Minor temporary deformations reduce firmness of rail restraint
- Permanent deformation completely eliminates holding-down force and creep resistance
- Spike or screw support gradually loosened by impacts from sagging/tilting rail movements
- **Not suitable for long welded tracks**[^6]

**Examples:**

- Spike fastening (USA standard)
- Direct fastening to steel sleepers (with holes in sleeper top)


#### 5.2.2 Elastic Fastenings

**Principle:**[^6]
Screws tightened to develop initial tension via elastic clip or spring washers. Initial tension maintains force influence even when spring compressed further due to wheel load. Force takes pulsating course fluctuating around initial tension value.

**Types by mounting method:**

**A. Direct fastening to wooden sleepers:**[^6]

- Rails fastened directly with spikes or screws
- Simple but limited performance

**B. Indirect fastening to wooden sleepers:**[^6]

1. **Vossloh KS permanent way with Skl12 clip:**
    - Two free spring arms provide ~13 kN tension at 14.5 mm deflection per clip
    - Central loop damps tilting movements
    - Fastening elements can be pre-assembled in sleeper factory
2. **K permanent way:**
    - Uses coach screws
    - Disadvantage: coach screws subject to bending stress

**C. Direct fastening to concrete sleepers:**[^6]

1. **FIST fastening (Swedish design):**
    - Various designs differing mainly in rubber base plate arrangement
    - Can use steel or HDPE base plates
    - FIST BTR (with HDPE plates) is standard in South Africa
    - FIST FY includes additional integrated rubber plate
2. **Pandrol fastclip:**
    - Can be mounted in sleeper factory
    - Minimal components (clip, pad, insulator)
3. **Pandrol e-clip:**
    - Very few elements
    - Components: middle part insulator pad, spring clip, rail foot
    - Holds rail even under vibration
4. **Vossloh W14 with Skl14 clip:**
    - Can be mounted in sleeper factory
    - Tension force ~10 kN at 13 mm spring deflection per clip
    - Central loop damps tilting movements
5. **Vossloh 300 with Skl15 clip:**
    - Used mainly on ballastless track but suitable for ballasted high-speed track
    - Highly elastic rail pad (spring rate 27 kN/mm)
    - Pressure distribution steel plate for better load distribution
    - Synthetic angular guide plates maintain lateral rail position
    - Adjustment: +30 mm upward, +20 mm in track gauge
6. **Nabla fastening (SNCF, France):**
    - Triangular clip form (Greek Nabla symbol)
    - Initial tension force: 25 kN
    - Spring deflection during installation: 5 mm
    - Creep resistance: 20 kN
    - Natural frequency: 2700 Hz
    - Rail deviation under test load: 3 mm
7. **Elastic spike fastening:**
    - Common types: single (Sna), double (Dna)
    - Inexpensive but limited durability
    - Service life: 3-20 years depending on location (tunnels: 3-4 years, curves R<700m: 4-6 years, straight track: 7-10 years)

**D. Indirect fastening to concrete sleepers:**[^6]

- Uses intermediate base plates for force distribution


### 5.3 Elements of Rail Fastening Systems

#### 5.3.1 Rail Pads

**Purpose:**[^6]

- Elastic damping element for vibration decoupling
- Load distribution over several sleepers through rail settlement
- Critical component determining track elasticity

**Classification (prEN13481-2):**[^6]


| Type | Stiffness Range |
| :-- | :-- |
| Soft | <80 kN/mm |
| Medium | 80-150 kN/mm |
| Hard | >150 kN/mm |

**Performance requirements (DB AG):**[^6]

- Static stiffness: 50-70 kN/mm
- Dynamic rigidity: 50-130 kN/mm between 3-5 Hz

**Typical rail pad properties (e.g., Saargummi Sylomer/Sylodyne):**[^6]

- Very high elasticity
- Low temperature dependence of spring rate
- Low dynamic stiffening
- Good structure-borne noise insulation
- Good aging and weather resistance
- Low water absorption
- Excellent UV and ozone resistance

**Example performance data:**[^6]


| Pad Type | C<sub>stat</sub> 25°C 10 Hz (kN/mm) | C<sub>dyn</sub> 25°C (kN/mm) | C<sub>dyn</sub> -30 to 70°C 5-30 Hz (kN/mm) |
| :-- | :-- | :-- | :-- |
| Zw700a | 53 | 51-64 | 71-77 |
| Zw900a | 56 | 53-68 | 75-83 |
| Zwp104 | 27 | 26-29 | 40-42 |
| Zw1000NT | 42 | 42-41 | 57-61 |

**Benefits of softer pads (e.g., Zw900 vs. Zw687a):**[^6]

- Sleeper vibration reduced by ~50%
- Track vibration on bridges reduced by 20-50%
- Interior ICE sound level reduced
- Track stiffness decreased by ~30% (from 166 to 111 kN/mm)


#### 5.3.2 Clips and Tensioning Elements

**Spring clips:**[^6]

- Provide constant holding-down force through elastic deformation
- Typical initial tension: 10-25 kN depending on design
- Allow rail movement while maintaining restraint

**Coach screws/bolts:**

- Used in various fastening systems
- Must withstand dynamic loading
- Require proper torque specification


#### 5.3.3 Guide Plates and Insulators

**Functions:**

- Maintain lateral rail position
- Provide electrical insulation
- Transfer lateral forces to sleeper
- Materials: synthetic (HDPE, polyamide) or steel with insulating pads


#### 5.3.4 Base Plates (for indirect fastenings)

**Purpose:**

- Distribute rail foot pressure
- Protect sleeper surface
- Provide mounting surface for clips
- Materials: steel, cast iron, or high-density polyethylene (HDPE)


### 5.4 Testing and Quality Control

**Laboratory tests required (EN13481):**[^6]

1. **Rail creep force:** ≥7 kN
2. **Torsional test:** Rail twisted by 1.5° at 300 mm lever length
3. **Damping test:** Impact load damping categorized as low (<15%), mean (15-30%), or high (>30%)
4. **Permanent load test:** 3×10⁶ load alternations
    - Variation limits: longitudinal guidance ±20%, vertical rigidity ±25%, clamping power ±20%

**Field testing:**[^6]

- GRMS track recording car (America): measures loaded/unloaded track gauge at 60 km/h
- Applies vertical force (85 kN) and horizontal force (70 kN)
- Identifies defective/missing fastenings or damaged sleepers


### 5.5 Degradation and Maintenance

**Fastening degradation factors:**[^7][^8]

- Repeated dynamic loading causing fatigue
- Environmental exposure (UV, moisture, temperature cycling)
- Ballast particle impact and abrasion
- Chemical degradation of elastic elements
- Loosening due to vibration

**Rail pad degradation:**[^9]

- Aging reduces elastic properties
- Typical service life: 10 years for conventional rail pads[^10]
- Under-sleeper pads (USPs) can experience delamination problems and hydraulic abrasion[^10]
- Wear accelerates under moisture entrapment

**Maintenance considerations:**[^11][^6]

- Visual inspection for missing/damaged clips
- Torque checking of bolts/screws
- Rail pad condition assessment
- Replacement of worn/degraded components
- Typical tamping machine maintenance: thorough disassembly, cleaning, and re-oiling every 100 working hours[^11]

**Anti-creep devices:**[^6]

- Attached every 2nd or 4th sleeper
- Double-track lines: front surface only (direction of train movement)
- Single-track lines: both sides (trains move in both directions)
- Attached and loosened by hammer striking

***

## Summary and Key Takeaways

This comprehensive lesson has covered the essential aspects of ballasted track design and maintenance:

1. **Layer thicknesses** are critical for load distribution and track stability, with minimum ballast thickness of 30 cm (40 cm for high-speed) and formation protective layer minimum 20 cm.
2. **Ballast sections** require proper cross-sectional geometry with adequate shoulder width (0.4-0.5 m) and correct inclinations to ensure drainage and lateral stability.
3. **Ballast properties** must meet stringent requirements for material type (preferably hard rocks like basalt or granite), grain size (22.4-63 mm), shape (sharp-edged), and mechanical performance (LA ≤16%, AIV ≤18%).
4. **Testing protocols** (LA, AIV, Deval tests) ensure ballast quality, while **cleaning** is required when contamination reaches 30% by weight, with modern machines achieving 300-700 m/h performance.
5. **Sleeper types** each offer distinct advantages:
    - **Wooden:** Best damping, lowest ballast pressure, but limited to ≤160 km/h
    - **Steel/Y-steel:** Lightweight, durable (40-60 years), high lateral resistance
    - **Concrete:** Longest service life (50 years), highest lateral resistance, industry standard for high-speed lines
6. **Sleeper calculations** consider dynamic wheel loads with factors up to 1.75, load distribution across 5-7 sleepers, and bending moments requiring concrete strength ≥5.5 N/mm².
7. **Lateral resistance** ranges from 1200 N (freely lying) to 9000 N (fully stabilized concrete sleepers), with Dynamic Track Stabilizer increasing resistance by 30-50% after maintenance reduces it by 40-50%.
8. **Fastener functions** include maintaining gauge, transmitting forces, providing damping, and electrical insulation, with required creep force ≥7 kN.
9. **Fastener types** divide into:
    - **Rigid:** Not suitable for long welded rail
    - **Elastic:** Maintain constant restraint through spring action (10-25 kN initial tension)
    - **Modern systems:** Pandrol, Vossloh (W14, 300), FIST, Nabla with spring rates 27-70 kN/mm
10. **Fastener elements** include rail pads (classified as soft <80, medium 80-150, hard >150 kN/mm), clips providing 10-25 kN tension, guide plates, and base plates for load distribution.
11. **Testing requirements** ensure quality through rail creep force (≥7 kN), torsional tests (1.5°), damping assessment, and permanent load testing (3×10⁶ cycles).
12. **Degradation management** requires regular inspection, with rail pad service life typically 10 years and maintenance including torque checking, component replacement, and periodic machine servicing every 100 working hours.

This knowledge foundation enables permanent way engineers to design, construct, and maintain ballasted track systems that safely and efficiently support modern railway operations while optimizing life-cycle costs and performance.
<span style="display:none">[^12][^13][^14][^15][^16][^17][^18][^19][^20][^21][^22][^23][^24][^25][^26]</span>

<div align="center">⁂</div>

[^1]: TrackCompendium_5Sleepers6BallastTrack-Compendium.pdf

[^2]: TrackCompendium_7FormationTrack-Compendium.pdf

[^3]: https://adortech.com/blog/railway-ballast-maintenance

[^4]: TrackCompendium_9Ballasted-trackTrack-Compendium.pdf

[^5]: TrackCompendium_2StructureTrack-Compendium.pdf

[^6]: TrackCompendium_4FasteningsTrack-Compendium.pdf

[^7]: https://tecnica-vialibre.es/documentos/Articulos/360AV05_4.9.SolMorenoRubio.pdf

[^8]: https://rdso.indianrailways.gov.in/works/uploads/File/IRTMM 2019 CHAPTER 3.pdf

[^9]: https://www.sciencedirect.com/science/article/abs/pii/S1350630724009828

[^10]: https://www.ioa.org.uk/system/files/proceedings/p_sengsri_c_ngamkhanong_s_kaewunruen_life_cycle_and_sustainability_assessment_of_under_sleeper_pads_for_railway_vibration_and_suppression.pdf

[^11]: https://railway-maintenance.com/info-detail/maintenance-of-tamping-machine

[^12]: TrackCompendium_10SlabtrackTrack-Compendium.pdf

[^13]: https://pmc.ncbi.nlm.nih.gov/articles/PMC8539330/

[^14]: https://eprintspublications.npl.co.uk/1791/1/CMMT251.pdf

[^15]: https://ascelibrary.org/doi/10.1061/(ASCE)GT.1943-5606.0002904

[^16]: https://railroadrails.com/rail-maintenance-equipment/ballast-cleaner/

[^17]: https://journals.sagepub.com/doi/10.1177/09544062241291793

[^18]: https://www.networkrail.co.uk/our-work/looking-after-the-railway/track/

[^19]: https://extranet.artc.com.au/docs/eng/track-civil/guidelines/ballast/ETH-04-01.pdf

[^20]: https://vb.nweurope.eu/media/15798/accelerated-ageing-test-on-dowel-type-fasteners-holzforschung.pdf

[^21]: https://www.stnd-machinery.com/knowledge/maintenance-of-way-ballast-tamper

[^22]: https://adortech.com/blog/railway-sleepers-replacement-process

[^23]: https://www.sciencedirect.com/science/article/abs/pii/S0167844224001381

[^24]: https://www.sciencedirect.com/science/article/pii/S2666789423000521

[^25]: https://technology.plassertheurer.com/en/bettungsreinigung/wann-muss-gereinigt-werden

[^26]: https://inis.iaea.org/records/8bn1v-t5124/files/31047796.pdf?download=1

