---
title: Signalling
layout: default
nav_order: 2
---

# Signalling

Railway signalling is the set of technical systems and operating rules that keep trains separated, protect conflicts at junctions, and optimise capacity and speed.  Conventional lines mostly rely on fixed blocks and lineside signals, while modern high‑speed lines in Europe and the UK are moving to cab signalling and ETCS under the ERTMS framework. [^1] [^2] [^3] [^4]

Signalling has to ensure:

- Trains do not collide, derail at switches, or exceed infrastructure limits (speed, braking, electrification).[^3]
- Infrastructure capacity is used efficiently by minimising headways while staying within braking and block constraints.[^3]

It achieves this through three key concepts:

- **Blocks and block sections**: The line is divided into sections that can only be occupied by one train at a time under normal rules.[^3]
- **Movement authority (MA)**: The formal “limit of permission” to proceed, either displayed on a signal or in‑cab.[^2][^4]
- **Interlocking**: A safety‑critical system that ensures points (switches) and signals are set so that conflicting routes cannot be cleared simultaneously.[^3]


## Train detection and block systems

Conventional and high‑speed lines use similar basic detection but apply it differently:

- **Track circuits**: Electrical circuits in the rails; a train’s axles short the circuit and de‑energise a relay, indicating occupancy. Widely used in UK and European conventional signalling.[^5][^6][^3]
- **Axle counters**: Electronic devices at section boundaries that count axles in and out to determine occupancy, increasingly used in UK and Europe, especially where track circuits are problematic (poor ballast, long viaducts, tunnels).[^1][^3]
- **Fixed block**: Traditional model; each block section has a protecting signal and is either “occupied” or “clear”. Headway is driven by block length and braking distance.[^3]
- **Moving block**: Conceptual underpinning of ETCS Level 3 and CBTC; separation is calculated dynamically from train position and braking curves rather than fixed block lengths, but full Level 3 is not yet deployed on mainline high‑speed in Europe.[^2]


## Interlockings and control centres

Historically, points and signals were worked by mechanical lever frames with mechanical locking.  Modern systems use:[^5][^3]

- **Relay interlockings** (route relay interlocking, RRI): Hard‑wired relay logic enforces interlocking rules; widely installed from mid‑20th century.[^5][^3]
- **Electronic/computer‑based interlockings (CBI)**: Software‑driven, SIL‑4 certified systems that handle complex node logic, interface to ETCS/RBCs, and are the norm for high‑speed and major resignalling in Europe.[^7][^2]
- **Control centres**: Large integrated control centres replace many local boxes, giving centralised control and automatic route setting; this is standard on European high‑speed networks and on major UK corridors.[^8][^1]


## Lineside signalling on conventional lines (UK focus)

On UK conventional main lines up to about 125 mph (~200 km/h), signalling is predominantly lineside with aspects viewed from the cab.  Key UK features:[^8][^1]

- **Signal types**:
    - Semaphore signals remain on some secondary lines.[^6][^8]
    - Colour light signals (2, 3, or 4 aspect) dominate the modern network.[^1][^8]
- **Aspect sequences**:
    - Two‑aspect: red (stop) / green (clear).
    - Three‑aspect: green, single yellow, red.
    - Four‑aspect: double yellow, single yellow, green, red, providing progressive braking information to support shorter headways and higher speeds.[^1]
- **Junction signalling**:
    - Route indicators (“feathers”) or theatre indicators show which diverging route is set, combined with approach control (holding a signal at restrictive aspect until a train is close) to manage speed over low‑speed turnouts.[^5][^1]
- **Permissive signals \& shunt aspects**: Subsidiary aspects (e.g. two white lights at 45°) allow restricted‑speed moves into occupied sections for platforming or shunting, under strict rules.[^6][^1]

Network Rail publishes detailed standards for signal design, sighting, overlaps, and control logic in a multi‑tier standard system, referenced in its standards catalogue.[^9][^7]

## Automatic protection on conventional lines (ATP, TPWS)

To mitigate driver error, conventional lines add train protection layers:

- **Automatic Warning System (AWS)** in the UK provides in‑cab audible and visual warnings reflecting the aspect or speed restriction ahead; the driver must acknowledge adverse indications.[^8][^1]
- **Train Protection \& Warning System (TPWS)** enforces speed and stop compliance at selected signals and speed restrictions using track‑mounted loops and onboard receivers; it can automatically brake if a train passes a red or approaches too fast.[^8][^1]
- Several European countries developed national ATP systems (e.g. Germany’s PZB/LZB, Italy’s SCMT, France’s KVB/TVM) prior to ETCS.[^2][^3]

These systems are essential “bridges” between pure lineside signalling and full ETCS.[^2]

## Why high‑speed lines need different signalling

At high speeds, especially above about 200–220 km/h, lineside‑only signalling becomes problematic:

- Reading and reacting to signals at long sighting distances is difficult and constrains alignment and headway.[^1][^2]
- Braking distances for 300+ km/h operation are so long that fixed aspects every few kilometres are inefficient.[^2]

As a result, European and UK high‑speed lines use **cab signalling** with continuous speed supervision, typically via:

- **ETCS Level 1 with infill** or national cab systems such as TVM‑430 (France) or LZB (Germany) on some legacy HSLs.[^2]
- **ETCS Level 2** on newer high‑speed and upgraded main lines, providing continuous movement authorities over radio.[^10][^4][^2]


## ERTMS / ETCS in Europe and UK

The **European Rail Traffic Management System (ERTMS)** combines:

- **ETCS (European Train Control System)**: standardised cab signalling and ATP.[^2]
- **GSM‑R** radio (and successors): dedicated digital radio for train‑ground communication.[^4][^2]

Key ETCS levels (simplified):

- **Level 1**:
    - Movement authorities and speed profiles transmitted via Eurobalises (passive transponders) overlaid on conventional signalling and fixed blocks.[^2]
    - Lineside signals usually retained; trainborne equipment enforces speed/braking.[^2]
- **Level 2**:
    - Continuous bi‑directional communication between trains and a Radio Block Centre (RBC) via GSM‑R.[^4][^2]
    - Trackside detection (track circuits/axle counters) remains, but lineside signals can be reduced or removed; movement authority and target speed are shown on a Driver Machine Interface (DMI) in the cab.[^4][^2]
    - Widely adopted on European high‑speed lines, including in Italy, Spain, Switzerland, Belgium, the Netherlands, Sweden and others.[^10][^2]
- **Level 3 (conceptual / pilot)**:
    - Potential for moving block if trains can reliably report their integrity and position, minimising trackside detection; not yet standard on open‑access European HSR.[^2]

The EU has made ETCS mandatory on EU‑funded new or upgraded signalling projects, driving network‑wide migration over time.[^2]

In the UK, ETCS Level 2 is being deployed on:

- Core Thameslink routes and the Great Western Main Line as part of digital railway programmes.[^4]
- Other corridors and future high‑speed and intensive routes as part of long‑term Network Rail signalling renewals.[^7][^4]


## Typical high‑speed line signalling architecture (Europe)

A modern European high‑speed line (250–350 km/h) typically features:

- **ETCS Level 2** as primary control, with:
    - Eurobalises for precise position reference and linking.[^10][^2]
    - Track circuits or axle counters for occupancy, feeding CBIs and RBC.[^10][^3]
    - RBC generating movement authorities and speed profiles based on route set, track conditions, and train characteristics.[^10][^2]
- **Electronic interlockings** at junctions, stations, and crossovers, integrated with RBC.[^10][^2]
- **Centralised traffic control centre** with automatic route setting and conflict detection tools.[^10][^2]

Older high‑speed deployments in France and Germany use national cab systems (TVM‑430 on LGV, LZB/ETCS mixes in Germany) but are progressively migrating to ETCS for interoperability.[^2]

## UK vs continental practice

Although technical building blocks are similar, there are cultural and historic differences:


| Aspect | UK conventional \& upgrades | Continental high‑speed / mainline |
| :-- | :-- | :-- |
| Primary display | Lineside colour lights up to ~125 mph; AWS/TPWS as overlay. [^1][^8] | Cab signalling (ETCS, TVM, LZB) above ~200 km/h; lineside often supplementary or absent. [^2] |
| Block concept | Fixed block, 2–4 aspect signals, overlaps, approach control. [^1][^3] | Fixed blocks for ETCS L1; virtual blocks under ETCS L2, moving toward shorter blocks and higher capacity. [^10][^2] |
| Interlocking | Mix of mechanical, relay, and CBI; national rules and legacy layouts. [^5][^3][^7] | Predominantly CBI on HSL; designed from outset for high speed and ETCS integration. [^10][^2] |
| ATP | AWS/TPWS, some legacy ATP, gradual ETCS fitment. [^1][^4] | National ATP systems pre‑ETCS; now ETCS baseline on new HSLs and TEN‑T corridors. [^2] |
| Policy driver | Asset life and brownfield complexity; digital railway overlay on mixed‑traffic network. [^7][^4] | Cross‑border interoperability and dedicated HSL corridors under EU policy. [^10][^2] |

## Standards and reference material

For deeper technical detail (block design, overlap lengths, braking curves, etc.) useful sources include:

- **General signalling theory**: “Railway Signalling Principles” by J. Pachl, which sets out block, interlocking, and route principles in a system‑agnostic way.[^3]
- **UK practice and rules**:
    - Network Rail’s public “Signals explained” introduction and associated technical overviews.[^8]
    - Network Rail standards catalogue, listing detailed standards for signalling design, control systems, and operations.[^9][^7]
- **ETCS / ERTMS documentation**:
    - Public introductions to the ETCS/ERTMS signalling system with examples from Italian and other European high‑speed lines.[^10][^2]
    - Specialist explanations of ETCS levels and UK deployments, e.g. on professional signalling training sites.[^4]

If you want to go deeper, follow‑up topics that fit your background would be: braking‑curve computation in ETCS, dimensioning of block lengths and overlaps for 300+ km/h, interface of track‑bridge interaction with axle counters and track circuits, or specific UK digital railway schemes.

<div align="center">⁂</div>

[^1]: https://en.wikipedia.org/wiki/UK_railway_signalling

[^2]: https://en.wikipedia.org/wiki/European_Train_Control_System

[^3]: http://www.joernpachl.de/eBook RSP.pdf

[^4]: https://digisigrail.co.uk/exploring-the-different-levels-of-etcs/

[^5]: https://www.lmssociety.org.uk/monographs/M02.pdf

[^6]: https://www.rttrainingsolutions.co.uk/wp-content/uploads/2018/06/GB-online-Railway-100-Basic-Principles.pdf

[^7]: https://www.networkrail.co.uk/wp-content/uploads/2023/09/Catalogue-of-Network-Rail-Standards-Issue-129.pdf

[^8]: https://www.networkrail.co.uk/stories/signals-explained/

[^9]: https://www.networkrail.co.uk/wp-content/uploads/2022/03/Catalogue-of-NR-Standards-Issue-123.pdf

[^10]: https://www.railwaysignalling.eu/wp-content/uploads/2016/09/ERTMS_ETCS_signalling_system_revF.pdf

