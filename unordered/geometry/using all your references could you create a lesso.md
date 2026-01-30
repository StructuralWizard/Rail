<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# using all your references could you create a lesson explaining how the geometry of the railway track is designed. Please, provide an introduction,  explain the general concepts of centrifugal force and acceleration,  cant, cant deficiency and excess. Explain the design parameters (speed, safety and comfort) as per ADIF, Network Rail and HS2 as per their standards.

Explain plan alignment design, the different math formula and minimum, maximum and preferred parameters for the different standards, speeds, etc,
Explain vertical alignment design, inclination and acceleration limits, sudden changes of vertical acceleration, etc
Explains the limits for interoperability of all these parameters.

Railway track geometry is designed to control the forces and accelerations that trains experience so that safety, capacity and passenger comfort are all maintained at the target design speed.[^1][^2][^3]

## Basic dynamics: centrifugal force, acceleration and cant

When a train negotiates a horizontal curve of radius $R$ at speed $V$, it experiences a lateral centrifugal force $F_c = m V^2 / R$, which produces a lateral (centripetal) acceleration $a_c = V^2 / R$.  If the plane of the track is horizontal, this force acts fully sideways on the wheel–rail interface, increasing derailment risk, rail wear and passenger discomfort.[^2]

To reduce this effect, the outer rail is raised relative to the inner rail by a cant (peralte) $D$ so that the resultant of weight and centrifugal force lies closer to the normal to the track plane.  The theoretical equilibrium cant $D_{eq}$ is that which makes the lateral acceleration in the plane of the track zero, and for standard-gauge design is commonly written in the form $D_{eq} = q_e V^2 / R$ with $q_e$ depending on the distance between rolling circles.[^3][^2]

## Cant, cant deficiency and cant excess

- Cant $D$ is the actual rail height difference between low and high rail (in mm), or equivalently the crossfall angle of the track plane.[^2][^3]
- Cant deficiency $I = D_{eq} - D$ is the shortfall of applied cant with respect to equilibrium cant; it produces a lateral “uncompensated” acceleration towards the low rail.[^3]
- Cant excess $E = D - D_{eq}$ occurs when the actual cant exceeds the equilibrium value for a given speed, giving lateral acceleration towards the high rail and higher loads on the inner rail.[^2][^3]

The uncompensated lateral acceleration $a_i$ in the plane of the track can be written, for a given speed and curve, as a function of $D$ and $R$; ADIF explicitly uses $a_i = \frac{V^2}{12.96\,R} - \frac{g D}{e}$ and defines $I$ so that $a_i$ and $I$ are directly proportional.  Passenger comfort is primarily controlled by limiting $a_i$ (or equivalently $I$), while freight loading and wheel–rail forces are controlled by limiting both $I$ and $E$.[^3][^2]

## Design drivers: speed, safety and comfort

For ADIF, the basic design parameters are grouped as speed (nominal, specific and project speeds), safety (against derailment and overturning) and passenger comfort (lateral and vertical accelerations).[^2][^3]

- Speed: NAP 1‑2‑1.0 distinguishes nominal speed, specific element speed and project speed, and requires the project maximum speed to be no higher than the minimum of all element-specific maximum speeds.[^3][^2]
- Safety: horizontal curves must satisfy limits on cant deficiency, cant excess and track lateral resistance so that lateral forces remain below the minimum lateral resistance $R_L$ of the track (e.g. for high-speed slab or high-quality ballasted track).[^2][^3]
- Comfort: ADIF links limits on $a_i$, vertical acceleration $a_v$ and their rates of change to UIC / EN 13803 and TSI values, typically around 0.65 m/s² as a comfort reference for non-tilting trains, with reductions at higher speeds.[^3]

Network Rail standards (e.g. NR/L2/TRK/2049 and NR/L2/TRK/2102) use similar concepts, typically limiting vertical accelerations in vertical curves to around 2.25%g in normal cases and up to 3.25–4.25%g in hollows and humps, with an absolute safe limit around 6%g; these values are reflected in PWI and track design guidance.  HS2 design adopts more restrictive normal limits, for example vertical acceleration limits around 2.25%g (reference) and 3.25%g (maximum) in vertical curves and strict limits on cant and cant excess to maintain high comfort at up to 360 km/h.[^4][^5][^1]

### Typical numerical limits for cant, deficiency and excess

The table below summarises key envelope values from ADIF NAP 1‑2‑1.0, HS2 track alignment requirements (PWI presentation) and typical Network Rail practice (non-tilting passenger at up to 125–140 mph).[^1][^4][^3]


| Parameter | ADIF (standard / Iberian) | ADIF (standard) high-speed specific | HS2 main line | Network Rail typical main line |
| :-- | :-- | :-- | :-- | :-- |
| Max cant in plain line | 140–150 mm reference, 160 mm normal, 180 mm exceptional (gauge dependent) [^3] | For standard gauge, 140–160 mm (up to 180 mm exceptional) [^3] | 160 mm maximum, 0 mm at platforms [^1] | Around 150 mm typical maximum, lower at platforms (≈110 mm) [^4] |
| Max cant deficiency (non-tilt) | Reference lateral acc. 0.65 m/s² up to 230 km/h; decreasing to 0.39 m/s² at 300–350 km/h (values expressed as I in mm by tables) [^3] | For standard gauge: I_ref 100 mm, I_normal 153 mm at v ≤ 230 km/h; reducing to I_ref 60 mm at 300–350 km/h [^3] | Max I varies with speed: ≈110 mm up to 250 km/h, reducing to 80 mm above 300 km/h [^1] | Comfort-based limits give I of roughly 100–130 mm for non-tilt passenger, with higher values only in exceptional conditions [^4] |
| Max cant excess | For standard gauge: E_ref 90 mm, E_normal 100 mm, E_excep 120 mm [^3] | For Iberian gauge: E_ref 104 mm, E_normal 115 mm, E_excep 138 mm [^3] | Max cant excess 50 mm at lower speeds and up to 90 mm in some high-speed cases [^1] | Freight-dominated lines typically limit E to about 60–80 mm to control inner rail wear [^2][^6] |
| Vertical acceleration (design) | For vertical curves, reference ≈0.22–0.31 m/s² (convex/concave) at v ≤ 220 km/h, with normal limits up to ≈0.51–0.59 m/s²; exceptional up to ≈0.44 m/s² convex and 0.44 m/s² overall combinations constrained when lateral $a_i$ > 0.65 m/s². [^3] | Same envelope, with normal practice to work within reference values on new high-speed lines. [^3] | Max vertical acceleration 2.25%g (≈0.22 m/s²) reference and 3.25%g (≈0.32 m/s²) maximum; vertical curve radii 1 000–56 000 m. [^1] | NR guidance uses 2.25%g as a normal design limit, 3.25%g as maximum in hollows, 4.25%g in humps, with 6%g as an absolute safety cap. [^4] |

These values illustrate that all three administrations work in broadly similar ranges, but HS2 and ADIF high-speed standards push towards the lower comfort accelerations and larger radii appropriate to 300–360 km/h.[^1][^3]

## Horizontal alignment: elements and equations

### Geometric model in plan

Track in plan is modelled as a succession of:

- Tangent (straight) alignments.
- Transition curves (usually clothoids) where curvature and cant are varied progressively.
- Constant-radius circular curves.

ADIF NAP 1‑2‑1.0 adopts the clothoid with intrinsic equation $R = A^2 / L$, with $A$ the clothoid parameter and $L$ the length along the curve from its origin; curvature varies linearly, which matches a linear cant ramp and gives near-constant rate of change of lateral acceleration.[^2][^3]

### Cant and transition design

ADIF defines:

- Cant ramp $dD/ds = D / L_D$ with limits depending on speed and gauge; for standard and Iberian gauge the reference ramp is 1.0 mm/m for v ≥ 50 km/h, with normal limits up to 2.0–2.3 mm/m and exceptional up to 2.5–2.65 mm/m.[^3]
- Rate of change of cant with time $dD/dt = 3.6 D v / L_D$ limited to e.g. 50 mm/s reference (standard gauge) with normal limits of 50–58 mm/s and exceptional up to 60–69 mm/s depending on gauge.[^3]
- Rate of change of cant deficiency $dI/dt$ and associated lateral acceleration change, with reference limits typically 55–63 mm/s for standard and Iberian gauges at v ≤ 220 km/h and reduced values at higher speeds.[^3]

Clothoid length $L_k$ must satisfy simultaneously:

1. Cant ramp limit ($dD/ds$).
2. Cant rate limit ($dD/dt$).
3. Cant-deficiency rate limit ($dI/dt$ or $da_i/dt$).[^3]

The minimum transition length is the maximum of the three computed lengths, with a practical lower bound of about 20 m, and can be omitted in very low-speed manoeuvre tracks if the resulting “step” in $I$ remains within the allowable sudden change limits.[^3]

### Minimum radii and straight lengths

ADIF sets absolute minimum horizontal radii for general lines, independent of speed:

- Standard and Iberian: R_ref 250 m, R_normal 190 m, R_excep 150 m.[^3]
- Metric: R_ref 200 m, R_normal 100 m, R_excep 90 m.[^3]

Above these absolute minima, the effective minimum radius for a given speed is found from cant-deficiency and cant-excess limits, using values derived from the NAP tables.  For high-speed lines (v ≥ 250–300 km/h), typical design radii are several thousand metres (e.g. HS2 uses minimum radii of 4 000–7 000 m depending on design speed and environment).[^7][^1][^3]

Straight length requirements between curves are defined for both dynamic reasons (damping of car body roll) and to avoid buffer-locking in opposite curves:

- Between curves of opposite sense, ADIF requires a minimum straight length proportional to speed (typically between 0.4v and 0.55v in metres, with reductions allowed in exceptional cases and specific formulas when checking buffer interference based on vehicle length and bogie spacing).[^2][^3]
- Between curves of the same sense, minimum straight length may be zero; designers may use compound curves or back-to-back clothoids.[^3]


### Sudden changes of cant deficiency

In stations and historic layouts without transitions, or in crossovers, changes of curvature can cause sudden jumps in $I$.  ADIF therefore sets speed-dependent limits on the sudden change of cant deficiency (ΔI) at tangency points; if successive tangency points are closer than a threshold distance, ΔI for the whole combination must satisfy the same limits.  For standard gauge, ΔI reference limits vary from 80–40 mm at low and medium speeds down to 0 mm above 230 km/h, while exceptional limits allow up to 130 mm at low speed and 25 mm at high speed.  These values are chosen such that the discomfort at turnouts (where additional disturbances already exist) remains within acceptable limits, and that plain line with comparable geometry is not worse than turnouts.[^3]

## Vertical alignment: gradients, vertical curves and accelerations

### Elements and gradient limits

Vertical alignment consists of:

- Constant gradient sections (ramps or sags) with slope $i$ in ‰.
- Vertical curves (parabolic, second degree) with radius $R_v$.

ADIF restricts maximum gradients based on traction, braking and operating pattern:

- Passenger high-speed lines may use up to about 30–35 ‰ in some European practice, but ADIF references ETI Infrastructure limits of 35 ‰ maximum, with average ≤ 25 ‰ over 10 km and maximum continuous 35 ‰ length of 6 000 m.[^2]
- Mixed-traffic and freight-dominated lines are limited to lower gradients, typically no more than about 20 ‰ for freight.[^2]

ADIF also defines the concept of “rampa ficticia” (equivalent gradient including curve resistance) and uses a “rampa característica” (characteristic gradient) as the controlling value for freight capacity and braking calculations, with rules on how often steeper gradients may occur and their cumulative length.[^3]

### Vertical curves and vertical acceleration

Vertical curves are designed to limit vertical acceleration $a_v = V^2 / R_v$ (in suitable units) to comfortable values.  ADIF, based on UIC and SNCF practice, notes that passengers do not perceive 0.045g in simulations, while around 0.06g becomes detectable, and adopts reference limits for high-speed design around 0.22–0.31 m/s² with normal limits up to about 0.51–0.59 m/s² depending on convex/concave and speed.  This leads to minimum $R_v$ values that increase with speed; for standard and Iberian gauges, ADIF defines vertical radii tables with typical reference values (e.g. R_v ≥ 2 000 m convex, ≥ 500 m concave as absolute minima, with higher values at high speeds).[^2][^3]

HS2 uses similar vertical acceleration design limits (2.25%g reference, 3.25%g maximum) with vertical curve radii up to 56 000 m and minimum around 1 000 m as indicated in its alignment design presentations.  Network Rail guidance (PWI) aligns with traditional British practice of normal 2.25%g, maximum 3.25–4.25%g and absolute limit 6%g, again expressed via R_v–V relationships.[^4][^1]

### Sudden changes of vertical acceleration

Parabolic vertical curves cause a step in vertical acceleration at their tangency points (because curvature changes abruptly), which excites vehicle suspension and can be uncomfortable.  To avoid superposition of these effects:[^2]

- ADIF limits the minimum length of vertical curves and of constant-gradient sections between consecutive curves, typically to values between V/3 and V/2 (in metres) depending on speed, with an absolute minimum of 20 m.[^3]
- The combination of vertical curve radius, speed and separation between curves must ensure that the combined change in vertical acceleration does not exceed comfort limits and does not coincide with high lateral $a_i$ values (e.g. convex vertical curves with $a_v > 0.44$ m/s² must not coincide with lateral $a_i > 0.65$ m/s²).[^3]

These principles for managing “jerk” (rate of change of acceleration) in the vertical plane are analogous to the way HS2 and NR limit vertical acceleration and jerk in their high-speed vertical alignment standards.[^4][^1]

## Interoperability and alignment of limits

ADIF explicitly states that its exceptional limits for cant, cant deficiency, cant excess, vertical acceleration and other key geometric parameters are always equal to or more restrictive than those in UNE‑EN 13803, the Infrastructure TSI and the national interface documents (IFI, IFG).  For mixed-gauge networks (Iberian and standard gauges), ADIF uses a consistent reference of distance between rolling circles and cant limits so that both gauges remain interoperable within EU standards up to 350 km/h.[^3]

HS2, as a UK high-speed project, is designed to comply with TSI Infrastructure and EN 13803 as well, and therefore its limits on cant deficiency, vertical acceleration and curve radii are compatible with continental high-speed lines.  Network Rail’s legacy standards (e.g. NR/L2/TRK/2102 and NR/L2/TRK/2049) are being progressively aligned with TSI/EN requirements, especially for international routes, so that key parameters like maximum gradient, cant, cant deficiency and vertical accelerations do not conflict with European interoperability envelope values.[^5][^1][^4]

In practice, interoperability across ADIF, HS2 and Network Rail on high-speed corridors is achieved by:

- Working within EN 13803 and TSI Infrastructure envelopes for cant, cant deficiency and cant excess, including higher allowances only for specially approved tilt trains.[^1][^3]
- Harmonising vertical acceleration and vertical curve radius limits to within the 0.2–0.3 m/s² “comfort” band, with exceptional cases allowed only where justified and not coincident with high lateral accelerations.[^4][^1][^3]
- Ensuring minimum radii and maximum gradients on interoperable routes satisfy both local standards and TSI Infrastructure requirements (e.g. 35 ‰ maximum with average 25 ‰ over 10 km and limited continuous length).[^2][^3]

Overall, the design of track geometry is a coordinated process where horizontal and vertical alignments, cant, transitions and gradients are all chosen so that, at the design speed, lateral and vertical accelerations and their rates of change remain within ADIF, Network Rail and HS2 limits which themselves conform to common European interoperability standards.[^1][^4][^2][^3]
<span style="display:none">[^10][^11][^12][^13][^14][^15][^16][^17][^18][^19][^20][^21][^22][^8][^9]</span>

<div align="center">⁂</div>

[^1]: https://www.thepwi.org/wp-content/uploads/2022/10/2022-10-18_HS2-Track-engineering-design_Phil-Edwards.pdf

[^2]: 9.0-Geometria-y-Trazado.pdf

[^3]: NAP1210_ED2-diseno-trazado-ferroviario.pdf

[^4]: https://railwaytrackblog.com/2016/04/11/track-design-limits-of-vertical-acceleration/

[^5]: https://standards.transport.nsw.gov.au/_entity/annotation/b31de737-48b8-f011-bbd2-000d3ad25307

[^6]: https://railroads.dot.gov/sites/fra.dot.gov/files/2020-02/Cant Excess_Freight_Shared%20Track.pdf

[^7]: https://www.thecontactpatch.com/rail/r1604-track-alignment

[^8]: https://hsr.ca.gov/wp-content/uploads/docs/programs/eir_memos/Proj_Guidelines_TM2_1_2R00.pdf

[^9]: https://learninglegacy.hs2.org.uk/document/an-automated-digital-method-for-the-assessment-of-crosswind-safety-for-the-hs2-route/

[^10]: https://es.scribd.com/document/535887958/NAP-1-2-1-0-Metodologia-Para-El-Diseno-Del-Trazado-Ferroviario

[^11]: https://iricen.gov.in/iricen/ipwe_seminar/2012/2012/2.2.pdf

[^12]: https://www.thepwayengineer.com/post/railway-vertical-alignment-design-key-concepts-every-engineer-must-know

[^13]: https://www.adif.es/documents/20124/25515389/PropModif_NAP2001_ED1M1_FC1.pdf/bbfc4cfb-a32a-d299-139c-4c474d71eb92?version=1.0\&t=1700057534597\&download=true

[^14]: https://www.scribd.com/document/235921582/1-Alignment-Design-Criteria-for-Dedicated-High-Speed-Railway-Lines-Arbind-Kumar-Amrendra-Jha-RITE

[^15]: https://www.networkrail.co.uk/wp-content/uploads/2022/11/Vertical-Circulation.pdf

[^16]: https://www.adif.es/documents/20124/25584321/PropModif_NAP1210_ED1_M1_FC1.pdf/ed6310a0-b7c4-7e81-4842-a9f863e79d1c?t=1700228880134

[^17]: https://www.uic.org/IMG/pdf/mixed_uic_handbook_dec_2020-final_03.pdf

[^18]: https://www.adif.es/documents/20124/26526320/PropModif_NAP1201_ED6_FC1.pdf/025388d5-aef6-f13e-8c50-55df2491881c?t=1701780342758

[^19]: https://democracy.solihull.gov.uk/Data/Overview and Scrutiny Management Board/201107051000/Agenda/Appendix B - HS2 Route Engineering Report (6M bytes) - att30286.pdf

[^20]: https://www.networkrail.co.uk/wp-content/uploads/2025/03/Asset-Protection-The-Developers-Handbook.pdf

[^21]: https://www.studocu.com/es/document/universidad-politecnica-de-madrid/ferrocarriles/04-trazado-ffcc-adif-nap1210-unlocked/118281163

[^22]: https://assets.publishing.service.gov.uk/media/5a78d7b040f0b62b22cbd3ac/hs2-review-of_technical-specification.pdf

