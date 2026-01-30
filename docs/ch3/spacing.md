---
title: Train spacing
layout: default
parent: Signalling
nav_order: 1
---

# Spacing trains

Train separation is about ensuring trains never get close enough to collide while still making good use of line capacity. In both the UK and continental Europe the same basic physics and theory apply, but the “how” differs in terms of legacy practice and the degree of deployment of ERTMS/ETCS and cab signalling.

## Core theory of train separation

At the highest level, separation is about guaranteeing that a following train can always brake to a stand before reaching the last assured position of the train in front, for all permitted speeds and worst‑case braking performance.  Three theoretical modes are usually distinguished:[^1][^2]

- **Time interval**: early railways relied on dispatching trains at fixed time intervals, with no technical verification of the line being clear; this is now essentially obsolete for main line operation because it cannot assure protection if the leading train stops unexpectedly.[^1]
- **Fixed spatial separation** (fixed block / absolute block): the line is divided into consecutive sections (“blocks”), and only one train is allowed to occupy a block (or a set of blocks) at a time; signals or movement authorities enforce this rule.[^2][^1]
- **Relative or absolute braking distance** (moving block / variable block): the safe distance is defined directly as a function of braking distance and speeds, so that the protection boundary effectively “moves” with the train rather than being tied to fixed trackside block limits.[^3][^2][^1]

In practice, almost all mixed‑traffic mainline railways worldwide still use fixed blocks with conservative assumptions about braking, while metros and some advanced train control concepts use relative or absolute braking‑distance based separation to reduce headways.[^2][^3][^1]

## Train control principles

“Train control” is the combination of how the movement authority (permission to move and where to stop) is generated, transmitted and supervised.[^2]

Key dimensions are:

- Mode of transmitting movement authority:
    - **Lineside signals**: authority is encoded in signal aspects at discrete points; drivers read and obey them.[^10][^2]
    - **Cab signalling / ETCS**: authority is transmitted continuously or quasi‑continuously to the cab (via balises, radio), with an on‑board system supervising speed and braking profiles against the permitted envelope.[^2]
- Track release logic:
    - **Section‑based track circuits / axle counters**: a block section is reported occupied or clear; the control system uses this to allow or prevent new movements into the section.[^1][^2]
    - **Continuous position reporting**: the train transmits its exact position and integrity status, allowing finer‑grained release than a fixed block permits and enabling moving‑block concepts in principle.[^1][^2]

From these elements, standard mainline practice is:

- Fixed block, lineside signals, train‑borne speed supervision only through driver observation (traditional UK and many continental lines).[^4][^10][^2]
- Fixed block with cab signalling and automatic train protection (ETCS Level 1/2, national systems such as the German LZB or French TVM on high‑speed lines).[^2]
- Emerging moving‑block / relative braking‑distance systems with continuous communications and train integrity verification (ETCS Level 3 concepts and “virtual coupling”), mostly in research or limited deployment.[^3][^1][^2]


## Block control principles

Block control is the concrete implementation of spatial separation on the open line.  Two classic forms are:[^1][^2]

- **Absolute Block** (and token systems):
    - A line is divided into long block sections between signal boxes or token instruments; only one train at a time may occupy each section.[^6][^4][^1]
    - Communication between adjacent signal boxes (or token instruments on single lines) ensures that a second train cannot be admitted until the first is confirmed clear of the section.[^4][^6]
- **Track‑circuit block / multiple‑aspect signalling**:
    - The route is divided into shorter track‑circuit or axle‑counter blocks, each protected by a signal, typically with 3 or 4‑aspect signals to provide advance warning and “braking distance spread” over multiple blocks.[^10][^4]
    - A high‑speed train will be kept several blocks behind a stop signal (e.g. double yellow, single yellow, red), while slower trains can run with fewer clear blocks ahead, implicitly encoding braking curves in the signalling layout.[^4][^10]

On stations and junctions, interlockings implement the route principle: a route is only set and locked for one train, and conflicting routes cannot be set simultaneously, which prevents head‑on and flank collisions in addition to rear‑end collisions.  Modern interlockings are relay‑based, electronic or computer‑based but apply the same core safety logic.[^4][^1]

## How it is done in the UK

The UK network combines strong historical legacy (absolute block, mechanical boxes) with large‑scale track‑circuit block and multi‑aspect colour light signalling, plus a growing overlay of ETCS.[^6][^10][^4]

Main characteristics:

- **Traditional methods**:
    - Absolute Block is still used on many secondary double‑track lines, with each direction worked as a distinct line between signal boxes, controlled by block instruments and bell codes.[^6]
    - Single lines frequently use Electric Token Block or similar token‑based systems to ensure only one train occupies the single line at a time.[^6]
- **Modern mainline practice**:
    - Track‑circuit block with 3‑ or 4‑aspect colour light signals is standard on main routes, particularly high‑density mixed‑traffic corridors and high‑speed routes like the East Coast and West Coast Main Lines.[^10][^4]
    - Movement authority is traditionally lineside‑signal based, with AWS and TPWS providing enforcement of signal observance and over‑speed protection, rather than continuous speed supervision.[^10]
- **ETCS and digital railway direction**:
    - The UK is rolling out ETCS, especially on key corridors and for new stock, moving toward cab signalling with continuous or semi‑continuous movement authority and more precise braking supervision.[^3][^10][^2]
    - Research agendas such as the UK Railway Technical Strategy explicitly consider future concepts like “virtual coupling” or ERTMS Level 4, which would move toward relative braking‑distance based separation to increase capacity.[^3]

Overall, UK practice still centres on fixed blocks with conservative margins and strong procedural overlays, but with an active programme to move selected corridors onto ETCS‑based train control aligned with European practice.[^3][^10][^2]

## How it is done on the continent

“Continental” Europe is diverse, but there is a common shift toward ERTMS/ETCS for interoperability, on top of strong national traditions in signalling and train control.[^2]

Common features:

- **Fixed‑block signalling with national train control systems**:
    - Many networks use fixed blocks with colour light signals and various automatic train protection systems (e.g. Germany’s PZB/LZB, France’s KVB/TVM, Italy’s SCMT/RS, Spain’s ASFA/ERTMS overlay), often providing continuous or semi‑continuous supervision of speed profiles.[^2]
    - High‑speed lines in particular make extensive use of cab signalling (such as TVM or LZB) rather than lineside signals, due to the high speeds and long braking distances involved.[^2]
- **ETCS deployment**:
    - ETCS Levels 1 and 2 are being widely deployed on new or modernised corridors across continental Europe, creating an interoperable layer above national systems and allowing cab signalling with dynamic movement authorities.[^2]
    - Conceptually, ETCS Level 2 still uses fixed blocks but transmits movement authority and speed profiles via radio to the cab; Level 3 introduces possibilities for moving block and relative braking‑distance separation, though large‑scale mixed‑traffic deployment remains limited due to train integrity challenges.[^1][^2]
- **Capacity and closer running**:
    - Continental research initiatives such as Shift2Rail and related programmes have explored “train convoying” and virtual coupling, where trains with similar braking performance run with relative braking‑distance separation, potentially under ETCS extensions, to increase capacity while maintaining safety.[^3][^1][^2]

In broad terms, continental Europe is further along in mainstream cab signalling and ETCS deployment, especially on high‑speed and core corridors, whereas the UK retains more legacy lineside‑signal‑based operation but is converging through digital railway projects.[^10][^3][^2]
<span style="display:none">[^5][^7][^8][^9]</span>

<div align="center">⁂</div>

[^1]: [Railway Signalling.info (n.d.). *Train Separation*.](https://railway-signalling.info/functions/trainseparation/)
[^2]: [Maschek, U. (2015). *Railway Signalling & Interlocking - International Compendium*.](https://leopard.tu-braunschweig.de/servlets/MCRFileNodeServlet/dbbs_derivate_00047453/eBook_RSP.pdf)
[^3]: [Rail Engineer (2018). *Closer running – is it feasible?*.](https://www.railengineer.co.uk/closer-running-is-it-feasible/)
[^4]: [Railway Technical (n.d.). *The Development and Principles of UK Signalling*.](http://www.railway-technical.com/archive/the-development-and-princip.pdf)
[^5]: [Kuraoka, F. (2008). *Signalling System for High Speed Railway*.](https://etheses.whiterose.ac.uk/682/3/fumiofinal081112.pdf)
[^6]: [Railsigns.uk (n.d.). *Absolute Block*.](https://www.railsigns.uk/info/ablock1.html)
[^7]: [ScienceDirect (2015). *Train separation*.](https://www.sciencedirect.com/science/article/abs/pii/S221097061530010X)
[^8]: [RSSB (2021). *GERT8000-TW1 Preparation and movement of trains*.](https://consultations.rssb.co.uk/_entity/sharepointdocumentlocation/eda0ea01-c2c7-ec11-a7b6-0022489f4736/2ab10dab-d681-4911-b881-cc99413f07b6?file=09_b_GERT8000_TW1_compressed.pdf)
[^9]: [Wikipedia (n.d.). *Grade separation*.](https://en.wikipedia.org/wiki/Grade_separation)
[^10]: [Wikipedia (n.d.). *UK railway signalling*.](https://en.wikipedia.org/wiki/UK_railway_signalling)



