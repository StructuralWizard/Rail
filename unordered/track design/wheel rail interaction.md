<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# using all your references could you create a lesson explaining wheel rail interaction

- dynamics of vehicle movement
- contact between wheel and rail
- vehicle defects
- rail vehicle noise
- tilting trains
- vehicle monitoring

Now I'll create a comprehensive lesson on wheel-rail interaction based on all the references gathered.

# Wheel-Rail Interaction: A Comprehensive Lesson on Railway Vehicle Dynamics

## 1. Dynamics of Vehicle Movement

### 1.1 Starting Forces and Tractive Effort

The dynamics of vehicle movement comprise the dynamic properties of rolling stock, forces developing during running, calculation of running times, and determination of work and energy consumption.[^1]

The **maximum starting force** is determined by the frictional weight (total loads of powered axles) and the coefficient of adhesion. The tractive force for starting is given by:

$$
Z_t = \mu \cdot \Sigma Q
$$

where:

- $Z_t$ = tractive force for starting (kN)
- $\mu$ = coefficient of friction (0.1-0.35)
- $\Sigma Q$ = axle load (kN)

An increase in running speed causes vehicle vibration to increase and the usable coefficient of adhesion to be reduced. According to Curtius-Kniffler, the coefficient varies with speed.[^1]

### 1.2 Vehicle Resistances

**Starting Resistance (wa)**: When a train starts up, a break-loose resistance must be overcome during the stretching period when wagons start moving one after another. This depends on the structural type of traction vehicle.[^1]

**Gradient Resistance (ws)**: The gradient resistance equals the line gradient. For a gradient of 1 in n:

$$
w_s = 1000 \cdot \sin(\alpha) \approx 1000 \cdot \tan(\alpha) = 1000/n \text{ (kg/t)}
$$

**Curvature Resistance (wk)**: Calculated according to radius R (m):[^1]

- R ≤ 350 m: k = 650/R
- R ≤ 300 m: k = 530/R
- R ≤ 200 m: k = 500/R

**Running Resistance (wr)**: Comprises frictional resistance (speed-dependent) and air resistance (speed-squared dependent):

$$
w_r = K_0 + K_1 \cdot v + K_2 \cdot v^2
$$

where v = speed (km/h) and coefficients vary by vehicle type.[^1]

**Air Resistance**: Expressed by:

$$
w_a = \frac{1}{2} c_w \cdot A \cdot \rho \cdot v^2
$$

where $c_w$ is the drag coefficient, A is vehicle cross-section (m²), $\rho$ is air density (kg/m³), and v is relative speed.[^1]

**Acceleration Resistance (wa)**: Required to accelerate the train mass:

$$
w_a = \frac{\lambda \cdot a \cdot 10^2}{g}
$$

where $\lambda$ = coefficient of rotating masses (typically 1.05), a = acceleration (m/s²), g = gravity.[^1]

### 1.3 Equivalent Conicity

The rolling radii of left and right wheels are not usually the same. The difference between radii as a function of lateral displacement is called the δ-function. This influences vehicle behavior in tangent track and forces in curves.[^1]

**Equivalent conicity** describes the wheelset-rail pairing as an imaginary conical profile:

$$
\tan(\gamma_e) = \frac{\Delta r}{2y}
$$

where $\Delta r$ is the difference in rolling radii and y is lateral displacement.[^2][^1]

Equivalent conicity depends on rail inclination and track gauge. Values should remain below 0.4 for good running stability. High conicity causes high exciting frequency of the wheelset, calculated using Klingel's formula:[^1]

$$
f = \frac{v}{2\pi} \sqrt{\frac{2r\gamma}{S}}
$$

where r = wheel radius, γ = cone angle, S = wheel contact base (≈1.500-1.505 m).[^1]

## 2. Contact Between Wheel and Rail

### 2.1 Contact Mechanics Fundamentals

The wheel-rail contact is at the core of all vehicle-track interaction research. This tiny interface governs the dynamic performance of railway systems.[^3][^4][^5][^6]

When rolling, the wheel not only rolls on the rail but also slides. The contact surface divides into **adhesion areas** (where surfaces stick) and **sliding areas** (where they slip).[^7][^1]

### 2.2 Hertzian Contact Theory

In 1880, Hertz described the wheel-rail contact area as elliptical. The contact between wheel and rail in normal direction is very stiff – deformations add up to only 1/10 or 2/10 mm, while the contact area is approximately 1-2 cm², transmitting loads of about 10 tons.[^5][^7][^1]

**Maximum surface pressure** at the center of the contact ellipse:

$$
\sigma_{max} = \frac{3N}{2\pi ab}
$$

where N = normal force, and a, b = semi-axes of the contact ellipse.[^1]

The sections a and b depend on the radii of contacting surfaces, elastic modulus of materials, and normal forces.[^1]

**Typical contact conditions**:[^1]


| Vehicle Type | Wheel Radius (mm) | Load N (kN) | a (mm) | b (mm) | σmax (N/mm²) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Locomotive | 620 | 100 | 7.1 | 8.1 | 830 |
| Passenger wagon | 460 | 60 | 5.2 | 7.2 | 760 |
| Goods wagon | 460 | 80 | 5.7 | 7.9 | 850 |

Peak pressures in normal tread contact reach 700-1000 MPa, while wheel flange-rail gauge corner contact can reach 1200-1800 MPa during active steering.[^5]

### 2.3 Kalker Contact Theory

Kalker developed theory describing the connection between force/deformation and relative movements at wheel-rail contact. For elastic half-spaces, the linearized connection between force and slip is:[^1]

$$
\begin{bmatrix} T_L \\ T_Q \\ M_B \end{bmatrix} = \begin{bmatrix} C_{11} & 0 & 0 \\ 0 & C_{22} & C_{23} \\ 0 & C_{23} & C_{33} \end{bmatrix} \begin{bmatrix} v_L \\ v_Q \\ \omega_B \end{bmatrix}
$$

where:

- T = tangent forces (longitudinal L, lateral Q)
- M = drilling moment
- C = Kalker coefficients
- v = velocities/creepages
- ω = angular velocities


### 2.4 Friction and Adhesion

The **frictional connection-slip curve** shows how tangent force increases linearly with slip then saturates. Traditional theory assumes constant friction independent of slip, but measurements show transferable tangent force reduces with increasing slip due to temperature-dependent friction coefficients.[^4][^1]

The coefficient of friction between wheel and rail varies between **0.1 and 0.4**, exhibiting non-linear behavior and saturation. Environmental conditions (water, leaves, sand, temperature, humidity) significantly affect wheel-rail adhesion.[^4][^7]

**Temperature increase** in the contact area from frictional power:

$$
\Delta T \approx \frac{P_{friction}}{4 \cdot a \cdot b \cdot \rho \cdot c \cdot v_0} \cdot 25
$$

Temperature rises in the tiny contact area can reach 200-300°C, creating thermal stresses comparable to mechanical stresses.[^1]

## 3. Vehicle Defects

### 3.1 Non-Circular Wheels

Wheel defects along the perimeter are classified as:[^8][^1]

**Individual defects**: Flattened spots (flats), ovals

**Periodic defects**: Polygons with 3-6 corners (passenger wagons) or 14-22 corners (traction vehicles)

**Combined defects**: Superposition of periodic and individual defects, wheel cracks

### 3.2 Wheel Flats

Wheel flats are the most common local surface defect, caused by wheel slipping events during braking. When wheels slide on rails, heat generation combined with rapid cooling can lead to brittle martensite formation on the wheel tread.[^9][^10][^8]

**Causes of wheel flats**:[^8][^9]

- Emergency brake application
- Low wheel-rail adhesion (leaves, grease on track)
- Faulty brakes or wheelset bearings
- Slip and slide conditions

**Consequences**:

- High tensile stresses (400-800 N/mm²) compared to normal rail tension
- Discomfort to passengers
- Damage to bearings, journals, rails, and track
- Rapid deterioration of vehicle and infrastructure components
- In extreme cases, axle breakage and derailment[^9]


### 3.3 Dynamic Forces from Wheel Flats

Flats cause high dynamic forces. According to Schramm, for speeds below 100 km/h, the load factor is:[^1]

$$
\phi_1 = 1 + 0.33v \times 10^{-4}
$$

For speeds above 100 km/h:

$$
\phi_2 = 1 + 4.5v \times 10^{-5} + 1.5v^2 \times 10^{-7}
$$

where v is speed in km/h.

### 3.4 Rail Joint Dynamics

Dynamic stress in rail joints creates peak forces. The force P₂ when passing a joint angle θ:[^1]

$$
P_2 = P_0 + \sqrt{M \cdot K} \cdot v \cdot \theta
$$

where:

- P₀ = static axle load
- M = unsprung mass
- K = equivalent track stiffness
- v = running speed
- θ = angle of inclination to joint


### 3.5 Out-of-Round Wheels and Polygonalization

Wheel polygonalization is a phenomenon where wheels develop periodic irregularities around the circumference. This results from complex interactions between wheel-rail dynamics and wear processes. Non-circular wheels cause fluctuation of normal force, particularly on hard subsoil.[^11][^1]

**Critical frequency range**: 50-150 Hz from non-circular wheels is important for permanent way stress. Frequencies between 25-100 Hz are most critical for ballast bed dynamic stability.[^1]

### 3.6 Detection and Monitoring

**Wayside detection systems** include:[^8]

- Strain gauges on rails
- Accelerometers
- Impact load detectors (LQM - long Q-force measuring points)
- Devices to detect non-circular wheels (DafuR)
- Ultrasonic methods

These systems record contact forces between wheel and rail over several sleepers to identify defective wheels requiring maintenance.[^8][^1]

## 4. Rail Vehicle Noise

### 4.1 Noise Sources

Sound becomes noise when undesirable, disturbing, or harmful. Railway noise primarily comes from passing trains.[^1]

**Main noise sources by speed**:[^12][^1]

- **0-40 km/h**: Propulsion/traction noise dominates
- **40-250 km/h**: Rolling noise dominates (most traffic)
- **Above 250 km/h**: Aerodynamic noise dominates


### 4.2 Rolling Noise Mechanism

Rolling noise is the major source of railway noise, originating from vibrations caused by roughness-induced dynamic contact forces. The process is similar for road and rail vehicles.[^12]

**Key factors influencing rolling noise**:[^12][^1]

1. **Wheel roughness** - depends on brake type:
    - Disk brakes: minimum coarseness
    - Grey cast iron blocks: maximum coarseness
    - Sinter blocks: intermediate
2. **Rail roughness** - defects include:
    - Corrugation (wavelength 3-6 cm, amplitude 0.1-0.4 mm)
    - Slip waves (wavelength 8-30 cm, amplitude 0.3-1 mm)
    - Head checks, Squats, periodic indentations
3. **Running speed** - rolling noise increases linearly with speed
4. **Contact surface characteristics**
5. **Wheel-rail material properties** (stiffness, damping, geometry)

### 4.3 Sound Radiation

Both wheel and rail are efficient sound radiators:[^12][^1]

- **Wheels**: Dominate above 1500 Hz, low structural damping leads to high vibration amplitudes at resonance
- **Rails**: Radiate broadband sound in 250-1250 Hz range
- **Sleepers**: Main contributors below 400 Hz

The structural wavelengths are larger than acoustic wavelengths for most frequencies, making wheels efficient loudspeakers.[^12]

### 4.4 Noise Reduction Measures

**Rail grinding/planing**: Increases rail surface quality, significantly reducing noise levels. Well-maintained rail surfaces can reduce noise by 5-10 dB.[^1]

**Wheel maintenance**: Regular turning/reprofiling removes flats and maintains smooth profiles.

**Brake system choice**: Composite brake blocks produce less wheel roughness than cast iron blocks.

**Rail dampers and absorbers**: Reduce rail vibration and sound radiation.

**Track isolation**: Floating slab track, resilient rail fasteners, ballast mats.

## 5. Tilting Trains

### 5.1 Technology Principles

Tilting trains allow speed increases in curves of up to 40% (up to 40 km/h faster) by tilting the car body toward the inside of the curve, compensating for centrifugal force felt by passengers. This enables use of existing tracks without expensive line upgrading.[^13][^14][^15][^1]

**Advantages**:[^1]

- Significantly increased comfort in curves (reduce lateral acceleration on passengers)
- Shortened running times
- No need for new track infrastructure
- Can tilt up to 8° (Class 390 Pendolino) or 8-9° (ETR 460)[^13]

**Maximum speed calculation** for tilting trains:[^1]

$$
v_{max} = \sqrt{11.8 \cdot R \cdot (u_{adm} + \frac{u}{150})}
$$

where:

- R = curve radius (m)
- u = superelevation (mm)
- uadm = admissible cant deficiency (150-300 mm)


### 5.2 Active vs. Passive Tilting Systems

**Active control systems** (e.g., Pendolino, Fiat-SIG):[^14][^13][^1]

- Vehicle body tilted by pneumatic or hydraulic cylinders (6-8°)
- Electronic control with sensor equipment (gyroscopes, accelerometers)
- Tiltronix control unit processes sensor data from bogies
- Anticipative systems use trackside transponder balises (TASS system) to overcome sensor lag[^16][^13]

**Components of Pendolino Tiltronix**:[^14][^13]

- Gyroscopes detect deviations from horizontal
- Accelerometers measure centrifugal forces
- Onboard computer calculates and activates tilt actuators
- Hydraulic tilting bogies with tilting rods
- Active lateral air suspension centers bodyshell
- Tilting pantographs remain centered when train tilts

**Passive control systems** (e.g., Talgo Pendular):[^1]

- Pendulous suspension with pivot above center of gravity
- Centrifugal force causes body to swing outward (1.2-3.5°)
- Simpler, no active control required
- Lower tilt angles than active systems


### 5.3 Infrastructure Requirements

To adapt infrastructure for tilting trains:[^1]

- Signaling equipment changes
- Possible catenary modifications
- Level crossing removal
- Bridge strengthening
- Transition curve and superelevation ramp adaptation

**Track stress increases**: Higher speed leads to increased track forces, requiring better track geometry maintenance, particularly in curves.[^1]

**Vehicle requirements**:[^1]

- Low unsprung vehicle mass
- Running gears with laterally elastic wheel guiding
- Radially adjustable axles
- Reduced axle loads (Pendolino: 12-14 MN, TGV Pendulaire: 18 MN, ICE-T: 16 MN)


### 5.4 Economic Considerations

**Additional costs**:[^1]

- Vehicle purchase: 5-12% higher
- Vehicle maintenance: 3-5% higher
- Infrastructure adaptation costs
- Enhanced track maintenance due to higher speeds

**Benefits**:

- Reduced journey times without new infrastructure
- Better utilization of existing conventional lines
- Competitive with high-speed rail on routes with many curves
- Lower overall investment than new high-speed line construction


## 6. Vehicle Monitoring

### 6.1 Measurement of Vehicle Reactions

Railways have found that vehicles with poor running properties and defective wheels highly stress the track, leading to increased maintenance. Monitoring systems measure this stress to identify problematic vehicles.[^17][^18][^19][^1]

**Key parameters monitored**:[^1]

- Total lateral force Y (limit: typically 0.85 of admissible)
- Vertical wheel load Q (limit: 170 kN for dynamic force, 170-225 kN for static depending on line)
- Coefficient of derailment Y/Q
- Passenger comfort accelerations


### 6.2 Track Recording Methods

**DB AG SR Method** (Störgrößen-Reaktionen):[^1]

- Permanent-way recording car (OMWE) measures track geometry
- Special assessment method extrapolates reactions of various train configurations
- Results include defects plus chronological development assessment
- Based on linear vehicle model (vehicle body on two bogies)

**NS VRA System** (Vehicle Response Analysis):[^1]

- Calculates forces and accelerations for three representative vehicles at five speeds
- Real-time calculation from track geometry measurements
- Provides dynamic vehicle force predictions


### 6.3 Track Monitoring Systems

Modern track monitoring employs:[^18][^19][^20][^17]

**Automated Measurement Total Stations (AMTS)**:

- Rail-clip prisms installed at regular intervals
- Monitor spatial position and report changes from baseline
- Solar-powered, wireless communications
- Multiple systems optically networked for long track spans

**Shape Arrays**:

- Inclinometer-like instruments for settlement/heave profiles
- Installed parallel to rails
- Wireless data transmission

**Dynamic Deflection Sensors (FLX-Rail)**:

- Record maximum vertical rail deflection under passing trains
- Optical sensors monitoring rail plate to ballast distance
- Sample at 350 Hz, store and transmit maximum deflection

**MEMS Track Monitoring**:

- Accelerometer sensors mounted longitudinally along track
- Monitor settlement and twist
- Typical spacing 2-3 meters
- Compatible with data loggers and management software[^18]

**Tiltmeters**:

- Monitor rotation of track ties
- Measure crosslevel changes
- Wireless transmission to cloud servers
- Automated alerts when thresholds exceeded[^17]


### 6.4 Vehicle-Mounted Monitoring

**Long Q-force measuring points (LQM)** and **devices to detect non-circular wheels (DafuR)**:[^1]

- Record contact force between wheel and rail over several sleepers
- Identify vehicles requiring maintenance withdrawal
- Continuous monitoring during operation

**Wheel-rail interaction assessment**:[^1]

- Forces measured with dynamometers on wheels
- Accelerometers on axle boxes and bogie frames
- Data analyzed for hunting motion detection[^21]


### 6.5 Hunting Oscillation Detection

Hunting is a self-excited vibration combining lateral and yaw movements of wheelsets and bogies, occurring at high speeds above critical speed.[^22][^23][^24][^21]

**Detection algorithms**:[^21]

- Based on accelerometer data from bogies
- Analyze geometric characteristics of hunting motion
- Index of Hunting Oscillation (IHO) calculated from sensor signals
- Can detect hunting even with low amplitudes (<3-8 m/s²)
- Utilize phase and amplitude information of lateral and yaw modes

**Typical hunting frequencies**: 0.8-3.0 Hz depending on vehicle type.[^1]

**Critical speed factors**:[^25][^23]

- Primary suspension stiffness and damping
- Yaw damper characteristics and blow-off behavior
- Equivalent conicity
- Wheelbase and axle spacing
- Vehicle mass distribution

***

## Summary

Wheel-rail interaction is fundamental to railway operation, governing vehicle dynamics, safety, comfort, and maintenance requirements. Understanding the complex interplay between vehicle movement forces, contact mechanics, vehicle and infrastructure defects, noise generation, and monitoring systems enables:

1. **Optimized vehicle design** with proper suspension, wheel profiles, and running gear
2. **Enhanced track maintenance** through condition monitoring and targeted interventions
3. **Improved passenger comfort** via technologies like active tilting and vibration damping
4. **Increased safety** through defect detection and hunting stability assessment
5. **Reduced lifecycle costs** by preventing damage progression and optimizing maintenance cycles

The evolution from simple empirical approaches to sophisticated measurement systems, advanced contact models (Hertzian, Kalker), and active control technologies continues to push the boundaries of railway performance while maintaining the critical safety margins required for reliable operations.

***

## References

Track Compendium: Interaction between wheel and rail (File: TrackCompendium_11InteractionWheelRailTrack Compendium.pdf)[^1]

Track Compendium: Structure (File: TrackCompendium_2StructureTrack-Compendium.pdf)[^2]

Mecánica vertical y transversal de la vía (File: 10.0 Mecanica vertical y transversal de la via.pdf)[^26]

A Review of Wheel-Rail Contact Mechanics for Railway Vehicles (2023)[^3]

Wheel-rail contact and friction models: A review of recent advances (2023)[^4]

Out-of-round railway wheels—study of wheel polygonalization (2005)[^11]

Understanding Hertzian Stress in Railway Wheels and Rails[^5]

Hunting Oscillation Detection Algorithm for Railway Vehicles (2024)[^21]

Rolling noise in road and rail transportation systems[^12]

The Wheel-Rail Contact (Heckmann, 2014)[^7]

Numerical Investigation into Critical Speed and Hunting Frequency (2019)[^25]

R.0418 Hunting - The Contact Patch[^22]

Wheel-Rail Contact Modelling in Vehicle Dynamics (Shahzamanian Sichani, 2013)[^6]

Hunting oscillation - Wikipedia[^23]

Pendolino Tilting Train, Italy - Railway Technology[^13]

Recent Advances in Wayside Railway Wheel Flat Detection (Fu et al., 2023)[^8]

Track Monitoring Systems - GEO Instruments[^17]

Tilting trains – another idea for speed - Global Railway Review[^14]

Track Monitoring System (MEMS) - RST Instruments[^18]

How tilting trains work - YouTube[^16]

Detecting wheel flats and more - Rail Engineer[^9]

Instrumentation and monitoring - Rail Engineer[^19]

Pendolino - Wikipedia[^15]

Identifying and interpreting railway wheel defects - NRC Publications[^10]
<span style="display:none">[^27][^28][^29][^30][^31][^32][^33][^34][^35][^36][^37][^38][^39][^40][^41][^42][^43][^44][^45][^46][^47][^48][^49][^50][^51][^52][^53][^54][^55][^56][^57][^58][^59][^60][^61][^62][^63][^64][^65][^66][^67][^68][^69][^70][^71][^72][^73][^74][^75][^76][^77][^78]</span>

<div align="center">⁂</div>

[^1]: TrackCompendium_11InteractionWheelRailTrack-Compendium.pdf

[^2]: TrackCompendium_2StructureTrack-Compendium.pdf

[^3]: https://yanthrika.com/eja/index.php/ijvss/article/view/2648

[^4]: https://journals.sagepub.com/doi/10.1177/09544097231156730

[^5]: https://jekay.com/understanding-hertzian-stress-in-railway-wheels-and-rails-a-beginners-guide/

[^6]: https://www.diva-portal.org/smash/get/diva2:646708/FULLTEXT01.pdf

[^7]: https://elib.dlr.de/88522/1/WheelRailContact.pdf

[^8]: https://pmc.ncbi.nlm.nih.gov/articles/PMC10144077/

[^9]: https://www.railengineer.co.uk/detecting-wheel-flats-and-more/

[^10]: https://nrc-publications.canada.ca/eng/view/fulltext/?id=99071dbf-48a1-4b41-bd27-14c0730bdc0e

[^11]: http://www.tandfonline.com/doi/abs/10.1080/00423110500184649

[^12]: https://www.sea-acustica.es/INTERNOISE_2019/Fchrs/Proceedings/PL.01.pdf

[^13]: https://www.railway-technology.com/projects/pendolino-train/

[^14]: https://www.globalrailwayreview.com/article/2851/tilting-trains-another-idea-for-speed/

[^15]: https://en.wikipedia.org/wiki/Pendolino

[^16]: https://www.youtube.com/watch?v=HYQJI8VeN5Q

[^17]: https://www.geo-instruments.com/technology/track-monitoring-systems/

[^18]: https://rstinstruments.com/product/track-monitoring-system/

[^19]: https://www.railengineer.co.uk/instrumentation-and-monitoring/

[^20]: https://www.hbm.com/9874/railway-infrastructure-monitoring/

[^21]: https://journals.sagepub.com/doi/10.1177/16878132241296265

[^22]: https://www.thecontactpatch.com/rail/r0418-hunting

[^23]: https://en.wikipedia.org/wiki/Hunting_oscillation

[^24]: https://re.public.polimi.it/bitstream/11311/800319/5/Evaluation of the hunting behaviour of a railway vehicle in a curve_11311-800319_Mazzola.pdf

[^25]: https://onlinelibrary.wiley.com/doi/10.1155/2019/7163732

[^26]: 10.0-Mecanica-vertical-y-transversal-de-la-via.pdf

[^27]: https://link.springer.com/10.1007/s42417-025-02070-7

[^28]: https://journals.sagepub.com/doi/10.1177/09544097241296382

[^29]: http://www.journal-itm.dp.ua/ENG/Publishing/09-02-2023_eng.html

[^30]: http://www.journal-itm.dp.ua/ENG/Publishing/12-04-2021_eng.html

[^31]: https://www.tandfonline.com/doi/full/10.1080/00423114.2015.1137956

[^32]: https://asmedigitalcollection.asme.org/IMECE/proceedings/IMECE2023/87585/V001T01A023/1195537

[^33]: https://cjme.springeropen.com/articles/10.1186/s10033-025-01328-1

[^34]: https://pp.bme.hu/me/article/download/7229/6398

[^35]: https://www.matec-conferences.org/articles/matecconf/pdf/2017/31/matecconf_rsp2017_00108.pdf

[^36]: https://www.extrica.com/article/23813/pdf

[^37]: https://pmc.ncbi.nlm.nih.gov/articles/PMC11779948/

[^38]: https://www.matec-conferences.org/articles/matecconf/pdf/2024/02/matecconf_eot24_04009.pdf

[^39]: http://mechanika.ktu.lt/index.php/Mech/article/download/13779/8653

[^40]: http://eprints.whiterose.ac.uk/142450/8/ASME JoT 2019 Wheel-rail Dynamic Ultrasonic Array Measurements ARC.pdf

[^41]: https://www.matec-conferences.org/articles/matecconf/pdf/2019/03/matecconf_mms18_01015.pdf

[^42]: https://www.uic.org/IMG/pdf/noise_from_parked_and_stationary_trains.pdf

[^43]: https://www.sciencedirect.com/science/article/abs/pii/S0022460X77800837

[^44]: https://academic.oup.com/iti/article/doi/10.1093/iti/liae021/7926465

[^45]: https://www.unlv.edu/sites/default/files/media/document/2024-10/RailTeam-FinalReport-ManagingVehicle-RailInterface.pdf

[^46]: https://nrc-publications.canada.ca/fra/voir/td/?id=90e3ed55-f82f-44ea-8ffe-15a1e9f61dee

[^47]: https://archive.wheel-rail-seminars.com/archives/2022/pc-papers/presentations/PC01 WRI 2022 Principles - Magel Contact Mechanics 09JUN22.pdf

[^48]: https://www.sciencedirect.com/science/article/abs/pii/S0022460X25004730

[^49]: https://reference-global.com/pdf/10.2478/cee-2022-0037

[^50]: https://www.sciencedirect.com/science/article/abs/pii/B9781845694128500033

[^51]: https://ui.adsabs.harvard.edu/abs/2024NonDy.11211993Y/abstract

[^52]: https://www.semanticscholar.org/paper/1801c32d6e641f53b1fa28ffb47cf3bde6522cd8

[^53]: https://pubs.acs.org/doi/10.1021/acs.jpcc.3c03377

[^54]: https://www.semanticscholar.org/paper/ae71147dc560f93384e89f27dd4fe60388547c3a

[^55]: https://www.intechopen.com/books/intelligent-and-efficient-transport-systems-design-modelling-control-and-simulation/modelling-and-control-of-narrow-tilting-vehicle-for-future-transportation-system

[^56]: https://www.semanticscholar.org/paper/726c5946b93a14904cdd4841495e9c0d21842602

[^57]: https://www.jstage.jst.go.jp/article/tetsutohagane/107/2/107_TETSU-2020-091/_article/-char/ja/

[^58]: https://www.semanticscholar.org/paper/51e8466f89ec696511e2dbd357d2ff0277b9ad52

[^59]: https://www.tandfonline.com/doi/full/10.1080/00423114.2014.901540

[^60]: https://www.taylorfrancis.com/books/9781420004892

[^61]: https://www.semanticscholar.org/paper/be4a02795108196d7c8d40fba79d045a77b1531e

[^62]: https://www.tandfonline.com/doi/pdf/10.1080/21642583.2016.1275990?needAccess=true

[^63]: http://www.scirp.org/journal/PaperDownload.aspx?paperID=44050

[^64]: http://www.scirp.org/journal/PaperDownload.aspx?paperID=36379

[^65]: https://www.mdpi.com/2227-7390/11/14/3057/pdf?version=1689052390

[^66]: https://iieta.org/download/file/fid/116508

[^67]: https://papers.phmsociety.org/index.php/ijphm/article/download/2664/1616

[^68]: https://www.matec-conferences.org/articles/matecconf/pdf/2019/03/matecconf_mms18_03009.pdf

[^69]: https://dapp.orvium.io/api/v1/deposits/63fe2c902f198c184a58ee9b/pdf

[^70]: https://rskr.irimee.in/sites/default/files/WHEELS.pdf

[^71]: https://rollingstockworld.com/passenger-cars/body-tilting-system-in-pendolino-emus-by-alstom/

[^72]: https://adortech.com/blog/the-different-types-of-railway-wheel-failures

[^73]: https://sisgeo.com/products/railway-monitoring-instrumentation/

[^74]: https://www.thecontactpatch.com/rail/r0410-tilting-trains

[^75]: https://eprints.hud.ac.uk/id/eprint/17785/1/Railway_Wheel_Flat_and_Rail_Surface_Defect_Modelling_and_Time-Frequency_Analysis.pdf

[^76]: https://www.mobility.siemens.com/global/en/portfolio/digital-solutions-software/digital-services/measurement-monitoring.html

[^77]: https://www.kth.se/polopoly_fs/1.206364.1600689418!/Menu/general/column-content/attachment/Tilting%20trains%20-%20technology%20benefits%20and%20motion%20sickness.pdf

[^78]: https://www.youtube.com/watch?v=tqkwr_iu48E

