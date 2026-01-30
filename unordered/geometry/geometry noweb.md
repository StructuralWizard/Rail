<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# using all your references could you create a lesson explaining how the geometry of the railway track is designed. Please, provide an introduction, explain the general concepts of centrifugal force and acceleration, cant, cant deficiency and excess. Explain the design parameters (speed, safety and comfort) as per ADIF, Network Rail and HS2 as per their standards.

Explain plan alignment design, the different math formula and minimum, maximum and preferred parameters for the different standards, speeds, etc,
Explain vertical alignment design, inclination and acceleration limits, sudden changes of vertical acceleration, etc
Explains the limits for interoperability of all these parameters.

I'll now create a comprehensive lesson on railway track geometry design using the references provided.

# Railway Track Geometry Design Lesson

## Introduction

Railway track geometry design is a fundamental discipline in permanent way engineering that determines the spatial position and alignment of the track in three dimensions. The geometry directly influences train performance, passenger comfort, safety, and infrastructure maintenance costs. This lesson explores the principles, parameters, and standards that govern track geometry design, drawing from ADIF, Network Rail, and HS2 standards.[^1][^2][^3]

Railway track geometry consists of two primary components:

- **Plan alignment (horizontal geometry)**: defines the track position in the horizontal plane through straights, curves, and transitions
- **Vertical alignment (profile)**: defines the track elevation through gradients and vertical curves


## General Concepts of Centrifugal Force and Acceleration

### Centrifugal Force

When a train exits a straight alignment and enters a circular curve, a lateral force is generated called **centrifugal force** (Fc):[^4]

$$
F_c = m \cdot a_c = m \cdot \frac{V^2}{R}
$$

Where:

- m = mass of the train
- V = train velocity (m/s)
- R = radius of the circular curve (m)
- ac = centrifugal acceleration (m/s²)


### Centrifugal Acceleration

The centrifugal acceleration is given by:

$$
a_c = \frac{V^2}{R}
$$

For example, for a train traveling at 100 km/h on a curve with R = 350 m, the centrifugal acceleration equals 2.2 m/s². The maximum acceleration accepted for passenger comfort is approximately 1 m/s².[^4]

### Effects of Centrifugal Force

**On rolling stock**:[^4]

- Transverse stresses and wheel-rail impact at curve entry/exit
- Hunting motion potentially causing derailment or overturning at high speeds
- Excessive work on vehicle suspension systems increasing maintenance costs

**On track**:[^4]

- Unequal wear on both rails
- Lateral track displacement (track shifting)
- Excessive work on fastenings
- Tendency for outer rail to overturn

**On passengers and freight**:[^4]

- Passenger discomfort
- Potential cargo displacement during freight transport


## Cant (Superelevation)

### Cant Definition and Purpose

To counteract centrifugal force effects, the outer rail is elevated relative to the inner rail, creating **cant** (superelevation). This positions the resultant force of centrifugal force and weight perpendicular to the track plane, eliminating lateral acceleration disturbing train operation.[^4]

Cant can be expressed as:[^4]

- **Superelevation**: vertical difference (z) between inner and outer rails (mm)
- **Transverse inclination**: angle θ (degrees or radians)


### Theoretical Cant

For a vehicle at speed V on a curve of radius R, the theoretical cant that completely balances centrifugal force is:[^4]

$$
z = \frac{a \cdot V^2}{g \cdot R}
$$

Where:

- z = cant (m)
- a = track gauge (m)
- V = speed (m/s)
- g = gravitational acceleration (9.81 m/s²)
- R = curve radius (m)

For Spanish Iberian gauge (1.668 m) with UIC 60 rail: a ≈ 1.740 m
For standard gauge (1.435 m) with UIC 60 rail: a ≈ 1.507 m

**Simplified formulas**:[^4]

For Iberian gauge: $z = 13.7 \frac{V^2}{R}$ (z in mm, V in km/h, R in m)

For standard gauge: $z = 11.8 \frac{V^2}{R}$ (z in mm, V in km/h, R in m)

### Cant Deficiency

**Cant deficiency (I)** is the difference between theoretical cant and applied cant when the applied cant does not fully compensate centrifugal force:[^4]

$$
I = z_t - z_p
$$

This creates an uncompensated lateral acceleration:

$$
a_{sc} = \frac{I \cdot g}{a}
$$

### Cant Excess

**Cant excess (E)** occurs when trains travel slower than the design speed, creating uncompensated acceleration directed toward the curve interior:[^4]

$$
E = z_p - z_t
$$

This causes:

- Shift of rolling axis toward curve interior
- Undulatory wear and increased rail wear
- Greater stress on inner rail


## Design Parameters: Speed, Safety, and Comfort

### Speed Parameters[^3][^4]

**Nominal Speed**: Maximum speed achievable under optimal track conditions, dependent on vehicle type and track category.

**Maximum Design Speed**: Speed for which a track element is designed under specific safety and comfort conditions.

**Minimum Design Speed**: Minimum speed to ensure acceptable cant excess limits.

**Operating Speed**: Average speed over a route section excluding stops.

### ADIF Standards

**Cant Limits**:[^3]


| Parameter | Reference | Normal | Exceptional |
| :-- | :-- | :-- | :-- |
| Maximum cant (existing lines) | 150 mm | 150 mm | 180 mm |
| Maximum cant (platforms) | 110 mm | 110 mm | 130 mm |
| Maximum cant (stopped trains) | - | 160 mm | - |

**Cant Deficiency - Uncompensated Acceleration**:[^3]


| Speed Range | Reference | Normal | Exceptional |
| :-- | :-- | :-- | :-- |
| v ≤ 230 km/h | 0.65 m/s² | 1.00 m/s² | 1.00 m/s² |
| 230 < v ≤ 300 km/h | 0.52 m/s² | 0.85 m/s² | 1.00 m/s² |
| 300 < v ≤ 350 km/h | 0.39 m/s² | 0.52 m/s² | 0.65 m/s² |

**Cant Deficiency Values (Standard Gauge)**:[^3]


| Speed Range | Reference | Normal | Exceptional |
| :-- | :-- | :-- | :-- |
| v ≤ 230 km/h | 100 mm | 153 mm | 153 mm |
| 230 < v ≤ 300 km/h | 80 mm | 130 mm | 153 mm |
| 300 < v ≤ 350 km/h | 60 mm | 80 mm | 100 mm |

**Cant Excess**:[^3]


| Gauge | Reference | Normal | Exceptional |
| :-- | :-- | :-- | :-- |
| Standard (1435 mm) | 90 mm | 100 mm | 120 mm |
| Iberian (1668 mm) | 104 mm | 115 mm | 138 mm |

### Network Rail Standards

**Cant Limits**:[^1]


| Parameter | Normal | Maximum | Exceptional |
| :-- | :-- | :-- | :-- |
| Cant on existing lines | 150 mm | 150 mm | 180 mm |
| Cant in platforms | 110 mm | 110 mm | 130 mm |
| Cant excess | - | 110 mm | 110 mm |

**Cant Deficiency (Plain Line)**:[^1]


| Track Type | Normal | Maximum | Exceptional |
| :-- | :-- | :-- | :-- |
| Jointed track | 90 mm | 90 mm | 110 mm |
| CWR (Permissible Speed) | 110 mm | 110 mm | 150 mm |
| CWR (Enhanced Permissible Speed, R ≥ 700m) | 265 mm | 265 mm | 300 mm |
| CWR (Enhanced Permissible Speed, 400-699m) | 150 mm | 225 mm | - |
| CWR (Enhanced Permissible Speed, R < 400m) | 110 mm | 110 mm | 150 mm |

**Rate of Change of Cant Deficiency**:[^1]


| Condition | Normal | Maximum | Exceptional |
| :-- | :-- | :-- | :-- |
| Permissible speed | 35 mm/s | 55 mm/s | 70 mm/s |
| Enhanced permissible speed | 35 mm/s | 110 mm/s | 150 mm/s |

### HS2 Standards

**Cant Limits**:[^2]


| Parameter | Desirable | Limiting | Exceptional |
| :-- | :-- | :-- | :-- |
| Maximum cant | 140 mm | 160 mm | 180 mm |
| Cant at platforms | 0 mm | 0 mm | - |

**Cant Deficiency**:[^2]


| Speed Range | Desirable | Limiting |
| :-- | :-- | :-- |
| V ≤ 100 km/h | 110 mm (0.72 m/s²) | 110 mm (0.72 m/s²) |
| 100 < V ≤ 250 km/h | 100 mm (0.65 m/s²) | 110 mm (0.72 m/s²) |
| 250 < V ≤ 300 km/h | 80 mm (0.52 m/s²) | 100 mm (0.65 m/s²) |
| V > 300 km/h | 60 mm (0.39 m/s²) | 80 mm (0.52 m/s²) |

**Cant Excess**:[^2]


| Parameter | Desirable | Limiting | Exceptional |
| :-- | :-- | :-- | :-- |
| Maximum cant excess | 50 mm | 90 mm | 110 mm |

**Cant Application Ratio**:[^2]

- For speeds 250-360 km/h: E/(E+D) = 65-70%
- For speeds below 250 km/h: E/(E+D) = 55-60%
- For V > 360 km/h: ratio may exceed 65-75%


## Plan Alignment Design

### Horizontal Curve Elements

Track horizontal alignment consists of:[^1][^2][^3]

- **Straight sections**
- **Circular curves** (constant radius)
- **Transition curves** (clothoid/spiral) connecting straights to circular curves


### Transition Curves (Clothoids)

Transition curves allow gradual change in curvature and cant application. The **clothoid** is most commonly used, with linear curvature variation:[^4]

$$
R \cdot L = A^2
$$

Where:

- R = radius at any point (m)
- L = length from inflection point to point of radius R (m)
- A = clothoid parameter (m)


### Mathematical Formulas

**Cant Requirement Formula**:[^2]

$$
E + D = 11.8 \frac{V^2}{R}
$$ (standard gauge)

$$
E + D = 13.7 \frac{V^2}{R}
$$ (Iberian gauge)

Where:

- E = applied cant (mm)
- D = cant deficiency (mm)
- V = speed (km/h)
- R = radius (m)


### Minimum Radius Requirements

**ADIF Standards**:[^3]


| Line Type | Reference | Normal | Exceptional |
| :-- | :-- | :-- | :-- |
| Standard \& Iberian gauge | 250 m | 190 m | 150 m |
| Metric gauge | 200 m | 100 m | 90 m |

**Network Rail Standards**:[^1]


| Line Type | Normal | Exceptional |
| :-- | :-- | :-- |
| Passenger lines | 200 m | 150 m |
| Non-passenger lines | 150 m | 125 m |

**HS2 Standards**:[^2]


| Application | Desirable | Limiting |
| :-- | :-- | :-- |
| Station approaches | 600 m | 400 m |
| Depot reception tracks | 600 m | 400 m |
| Depot tracks | 400 m | 300 m |
| Platforms | Straight | Straight |

### Cant Gradient (Cant Ramp)

The **cant gradient** (dD/ds) is the rate of change of cant with distance:[^1][^2][^3]

$$
\frac{dD}{ds} = \frac{\Delta D}{L_D}
$$

**ADIF Standards**:[^3]


| Speed Range | Reference | Normal | Exceptional |
| :-- | :-- | :-- | :-- |
| V ≤ 50 km/h (Std) | 1.85 mm/m | 2.50 mm/m | 3.00 mm/m |
| V ≤ 50 km/h (Iberian) | 2.15 mm/m | 2.65 mm/m | 3.35 mm/m |
| 50 < V ≤ 350 km/h (Std) | 1.00 mm/m | 2.00 mm/m | 2.50 mm/m |
| 50 < V ≤ 350 km/h (Iberian) | 1.15 mm/m | 2.30 mm/m | 2.65 mm/m |

**Network Rail Standards**:[^1]


| Speed Range | Normal | Maximum | Exceptional |
| :-- | :-- | :-- | :-- |
| 0-60 mph | 1:600 | 1:500 | 1:400 |
| 65-95 mph | 1:800 | 1:600 | 1:400 |
| ≥100 mph | 1:1000 | 1:800 | 1:400 |
| Minimum | 1:1500 | 1:2500 | - |

**HS2 Standards**:[^2]


| Speed Range | Desirable | Limiting |
| :-- | :-- | :-- |
| V ≤ 60 km/h | 1.0 mm/m (1:1000) | 2.0 mm/m (1:500) |
| 60 < V ≤ 100 km/h | 1.0 mm/m (1:1000) | 1.33 mm/m (1:750) |
| 100 < V ≤ 250 km/h | 0.8 mm/m (1:1250) | 1.0 mm/m (1:1000) |
| V > 250 km/h | 0.5 mm/m (1:2000) | 1.0 mm/m (1:1000) |
| Minimum | 0.25 mm/m (1:4000) | - |

### Rate of Change of Cant (RoCC)

The **rate of change of cant** in time is:[^3]

$$
\frac{dD}{dt} = \frac{\Delta D \cdot V}{3.6 \cdot L_D}
$$

**ADIF Standards**:[^3]


| Gauge | Reference | Normal | Exceptional |
| :-- | :-- | :-- | :-- |
| Standard | 50 mm/s | 50 mm/s | 60 mm/s |
| Iberian | 58 mm/s | 58 mm/s | 69 mm/s |
| Metric | - | 35 mm/s | 45 mm/s |

**Network Rail Standards**:[^1]


| Speed Range | Normal | Maximum | Exceptional |
| :-- | :-- | :-- | :-- |
| Permissible speed | 35 mm/s | 55 mm/s | 85 mm/s |
| Enhanced permissible speed | 35 mm/s | 75 mm/s | 95 mm/s |

**HS2 Standards**:[^2]


| Speed Range | Desirable | Limiting | Exceptional |
| :-- | :-- | :-- | :-- |
| V ≤ 250 km/h | 30-35 mm/s | 45 mm/s | 55 mm/s |
| V > 250 km/h | 30-35 mm/s | 45-55 mm/s | - |

### Rate of Change of Cant Deficiency (RoCD)

The **rate of change of cant deficiency** is:[^3]

$$
\frac{dI}{dt} = \frac{\Delta I \cdot V}{3.6 \cdot L_k}
$$

**ADIF Standards**:[^3]


| Speed Range | Reference | Normal | Exceptional |
| :-- | :-- | :-- | :-- |
| V ≤ 220 km/h (Std) | 55 mm/s | 55 mm/s | 100 mm/s |
| 220 < V ≤ 300 km/h (Std) | 55 mm/s | 55 mm/s | 75 mm/s |
| V > 300 km/h (Std) | 30 mm/s | 50 mm/s | 55 mm/s |

**HS2 Standards**:[^2]


| Speed Range | Desirable | Limiting | Exceptional |
| :-- | :-- | :-- | :-- |
| All speeds | 30-35 mm/s | 45 mm/s | 55 mm/s |

### Abrupt Change of Cant Deficiency

In station areas and through switches without transition curves, abrupt changes in cant deficiency occur.[^3]

**ADIF Standards (Standard Gauge)**:[^3]


| Speed Range | Reference | Normal | Exceptional |
| :-- | :-- | :-- | :-- |
| V ≤ 60 km/h | 80 mm | 100 mm | 130 mm |
| 60 < V ≤ 200 km/h | 40 mm | 100 mm | 125 mm |
| 200 < V ≤ 230 km/h | 30 mm | 40 mm | 85 mm |
| V > 230 km/h | 0 mm | 0 mm | 25 mm |

### Minimum Element Lengths

**HS2 Standards**:[^2]

Horizontal elements:

- V ≤ 100 km/h: Desirable = V × 1.5 m, Limiting = V × 2 m
- 100 < V ≤ 300 km/h: Desirable = V × 1.5 m, Limiting = V × 2 m
- V > 300 km/h: Desirable = V × 1.16 m, Limiting = V × 1.5 m

Vertical elements:

- Desirable = V × 1.5 m
- Limiting = V × 1.8 m
- Absolute minimum (ballasted track) = 30 m

**Network Rail Standards**:[^1]
Minimum element length: 2 seconds at maximum line speed (unless agreed by RAM Track)

## Vertical Alignment Design

### Gradient Elements

Vertical alignment consists of:[^1][^2][^4]

- **Uniform gradients**: constant inclination
- **Vertical curves**: parabolic curves connecting gradients


### Maximum Gradients

**ADIF Standards**:[^3]

Maximum gradient depends on:

- Adhesion (wheel-rail): limits to ~70‰
- Traction capacity: passenger trains up to 50‰, freight trains up to 20‰
- Train performance, braking capacity

**Network Rail Standards**:[^1]


| Application | Normal | Maximum | Exceptional |
| :-- | :-- | :-- | :-- |
| New construction | 12.5‰ (1:80) | - | - |
| New construction (passenger only, ≤3 km) | - | 35‰ (1:28.6) | 35‰ (1:28.6) |
| New construction (≤0.5 km, no stops) | - | - | 35‰ (1:28.6) |

**HS2 Standards**:[^2]


| Application | Desirable | Limiting | Exceptional |
| :-- | :-- | :-- | :-- |
| General | 1.5% | 2.5% | 3.5% |
| Tunnels | 1.5% | 2.5% | - |
| Platforms | - | 0.25% | - |
| Minimum (tunnels) | 0.5% | 0.3% | 0.2% |
| Minimum (cuttings) | 0.5% | 0.2% | - |

### Vertical Curve Radii

Vertical curves limit vertical acceleration. The minimum radius is determined by:[^4]

$$
R_{min} = \frac{V^2}{3.6 \times 3.6 \times 0.01 \times a_v \times g}
$$

Where:

- Rmin = minimum vertical radius (m)
- V = design speed (km/h)
- av = maximum vertical acceleration (% of g)
- g = 9.81 m/s²

**ADIF Standards**:[^3]

Maximum vertical acceleration:

- Normal: 0.3 m/s²
- Maximum: 0.5 m/s²
- Exceptional: 0.65 m/s²

**Network Rail Standards**:[^1]


| Parameter | Normal | Exceptional |
| :-- | :-- | :-- |
| Minimum radius | 1000 m | 600 m (convex), 900 m (concave) |
| Maximum vertical acceleration | 0.06g (0.59 m/s²) | - |

**HS2 Standards**:[^2]


| Parameter | Desirable | Limiting | Exceptional |
| :-- | :-- | :-- | :-- |
| Vertical acceleration | 2.25% g | 3.25% g | 4.25% g |
| Minimum radius | 1000 m | - | - |
| Maximum radius | - | 56,000 m | 80,000 m |
| Platforms | Constant gradient | - | - |

For HS2 at 360 km/h with av = 2.25% g:

$$
R_{min} = \frac{360^2}{3.6^2 \times 0.01 \times 2.25 \times 9.81} \approx 45,714 \text{ m}
$$

### Vertical Curve Parameter

The vertical curve parameter is:[^4]

$$
K_v = \frac{L}{\Delta i}
$$

Where:

- L = vertical curve length (m)
- Δi = algebraic difference of gradients (‰)

If gradients are in ‰, then: $K_v = 1000 \cdot L / \Delta i$

### Sudden Changes in Vertical Acceleration

When two vertical curves are connected without intermediate constant gradient, acceleration jumps are superimposed, causing:[^4]

- Rapid suspension discharge (concave to convex transition)
- Heavy suspension loading (convex to concave transition)
- Vertical acceleration jumps affecting passenger comfort

**Minimum separation between vertical curves**:

**ADIF Standards**: Minimum gradient length = 0.4V to 0.5V (where V is speed in km/h)[^4]

**Network Rail Standards**: Minimum 30 m constant gradient between reverse vertical curves when radii < 1000 m[^1]

**HS2 Standards**: Minimum 50 m separation between tangent points of consecutive horizontal and vertical elements (when exceptional values used)[^2]

### Combined Horizontal and Vertical Alignment

**HS2 Standards**:[^2]

For V > 160 km/h, vertical/horizontal combinations permitted without restrictions when:

- Horizontal and vertical elements meet desirable values
- Horizontal elements meet desirable values AND vertical elements meet limiting values
- No other exceptional values exist over combined elements

Otherwise: minimum 50 m separation between tangent points required

For V ≤ 160 km/h: requirements may be relaxed to 30 m separation

**Network Rail Standards**: Changes in horizontal alignment shall not be coincidental with changes in vertical alignment[^1]

### Vertical Alignment at Switches \& Crossings

**HS2 Standards**:[^2]

- S\&C shall be located on constant gradient
- S\&C should not be on vertical curves
- Simple S\&C: maximum gradient 2.5% (desirable 0.5%)
- Complex S\&C: maximum gradient 0.5% (desirable 0%)
- Minimum distance from vertical curve tangent to switch toe/crossing: 20-30 m

**Network Rail Standards**:[^1]

- Each S\&C unit should sit on continuous gradient extending ≥20 m beyond last bearer
- Gradient changes should not be within S\&C
- By exception: within through bearers with vertical curve radius ≥10,000 m
- Switches should be on continuous gradient; may be on concave curves by exception
- Switches should not be on convex curves


## Interoperability Limits

### European Technical Specifications for Interoperability (TSI INF)

The TSI for Infrastructure subsystem establishes mandatory requirements for interoperability across the European rail network.[^2][^3][^1]

**Key TSI Requirements Referenced in Standards**:

**Cant**:

- Maximum cant: Generally 180 mm (exceptional)
- Platform areas: 130 mm maximum

**Cant Deficiency**:

- Speeds align with ADIF/HS2 standards
- Special provisions for tilting trains

**Gradients**:

- Maximum: 35‰
- Average gradient over 10 km: ≤25‰
- Maximum continuous length at 35‰: 6 km

**Vertical Acceleration**:

- TSI-compliant limits incorporated in national standards

**Minimum Radii**:

- Manoeuvring areas: minimum 150 m design, 125 m in operation


### Cross-Border Compatibility

For international traffic, alignment parameters must ensure:[^3]

- Compatibility with gauging requirements (EN 15273 series)
- Compliance with structural gauge limits
- Accommodation of international rolling stock dynamics
- Track gauge maintenance within TSI tolerances (1435 mm ±0/-3 mm)


### Gauge Widening on Curves

For tight radius curves, gauge widening may be required to accommodate wheelset geometry. This affects:[^1]

- Minimum flangeway clearances (60 mm nominal)
- Check rail positioning
- Platform stepping distances

**Network Rail**: Gauge widening values shall be added to standard gauge tolerances on sharp curves[^1]

## Summary

Railway track geometry design integrates multiple interrelated parameters to ensure safe, comfortable, and efficient train operation. The key principles are:

1. **Centrifugal force management** through cant application balancing speed, radius, and passenger comfort
2. **Cant deficiency and excess limits** controlling uncompensated lateral acceleration for different train types and speeds
3. **Transition curve design** ensuring gradual curvature and cant change through clothoids
4. **Rate of change limits** (RoCC, RoCD) managing passenger comfort through time-based acceleration constraints
5. **Vertical alignment coordination** limiting vertical accelerations and avoiding sudden changes
6. **Interoperability compliance** meeting TSI requirements for cross-border operations

The three standards examined—ADIF, Network Rail, and HS2—show consistent fundamental principles while adapting specific parameter values to:

- Operating speed ranges (conventional vs. high-speed)
- Traffic types (passenger, freight, mixed)
- Geographic constraints (new construction vs. upgrades)
- Design philosophy (reference/normal/exceptional value structure)

Successful track geometry design requires iterative optimization balancing these parameters within standard limits to achieve the lowest whole-life cost while meeting safety, performance, comfort, and maintainability objectives.

<div align="center">⁂</div>

[^1]: NR_L2_TRK_2102-Design-and-Construction-of-Track-former.pdf

[^2]: HS2-HS2-RT-STD-000-000001-P04-Technical-Standard-Track-Alignment-Design.pdf

[^3]: NAP1210_ED2-diseno-trazado-ferroviario.pdf

[^4]: 9.0-Geometria-y-Trazado.pdf

