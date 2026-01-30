<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# Compare ADIF Network Rail and HS2 cant limits by speed

ADIF, Network Rail and HS2 all work with broadly similar cant envelopes, but HS2 applies them explicitly by speed bands while ADIF varies mainly cant *deficiency* with speed and keeps cant itself nearly speed‑independent.[^1][^2][^3]

## Key concepts for comparison

- **Cant limit** = maximum applied cant (peralte) D in mm.
- **Cant deficiency limit by speed** = maximum permitted unbalanced cant (I) for each speed band.
- **Cant excess limit** = maximum over‑cant experienced by slow trains.

The comparison below focuses on main‑line, non‑tilting passenger design; freight and special tilting envelopes can be higher.[^2][^3][^1]

## ADIF (NAP 1‑2‑1.0) – by speed

ADIF defines a *single* cant envelope by gauge, and then speed‑dependent cant‑deficiency limits, expressed both as acceleration and as I in mm.[^2]

- **Maximum cant in plain line (standard / Iberian gauge)**
    - Reference: 140–150 mm (gauge‑dependent).
    - Normal: 160 mm.
    - Exceptional: 180 mm (with additional conditions and only on high‑performance track).[^2]
- **Cant deficiency by speed – standard gauge (non‑tilt design envelope)**
Values below are for line design (not specific rolling stock types):
    - $v \le 230$ km/h: reference I ≈100 mm; normal 153 mm; exceptional 153 mm.[^4][^2]
    - $230 < v \le 300$ km/h: reference I ≈80 mm; normal ≈130 mm; exceptional 153 mm.[^2]
    - $300 < v \le 350$ km/h: reference I ≈60 mm; normal ≈80 mm; exceptional 100 mm.[^2]

These correspond to lateral uncompensated accelerations reducing from about 0.65 m/s² at ≤230 km/h to ≈0.39–0.52 m/s² at 300–350 km/h.[^4][^2]
- **Cant excess (standard gauge)**
    - Reference E = 90 mm; normal 100 mm; exceptional 120 mm.[^2]

ADIF’s speed dependence is therefore strong for *cant deficiency* but not for cant itself: higher speeds require lower I (and so larger radii or higher D), but D is capped by the same 140–180 mm range for all speeds.[^2]

## HS2 – explicit limits by speed

HS2’s track alignment presentations include a clear table of cant, cant excess and cant deficiency bands by speed.[^1]

- **Maximum cant (all speeds)**
    - Main line: 160 mm.
    - At platforms: 0 mm.[^1]
- **Cant excess (all speeds)**
    - Maximum 50 mm on more restrictive alignment; up to 90 mm on the less restrictive envelope.[^1]
- **Cant deficiency by speed (non‑tilting HS2 train)**[^1]
    - $V \le 100$ km/h: I_max = 110 mm.
    - $100 < V \le 250$ km/h: I_max = 100–110 mm (two design envelopes shown).
    - $250 < V \le 300$ km/h: I_max = 80–100 mm.
    - $V > 300$ km/h: I_max = 60–80 mm.

In practice this is almost identical in philosophy to ADIF: about 100–110 mm at conventional speeds, dropping progressively to 60–80 mm above 300 km/h, with a fixed 160 mm cant cap.[^1][^2]

## Network Rail – typical GB limits

Network Rail standards distribute the detail across several documents, but typical values for non‑tilting passenger on main lines are documented in PWI/technical guidance and NR standards.[^5][^6][^3]

- **Maximum cant**
    - Typical maximum cant on plain line: ≈150 mm, with lower limits (≈110 mm) where platforms or structure gauge constrain crossfall.[^6][^3]
    - In practice, design cant is often 80–130 mm on mixed‑traffic routes to limit cant excess for slow freight.[^3][^5]
- **Cant deficiency by speed**
NR does not publish a single simple table like HS2, but the ETCS/GB operational categories and NR guidance imply:
    - Freight‑oriented / low‑speed: I ≈75–90 mm.[^5]
    - Main passenger category: I ≈110 mm (often quoted GB “passenger” value).[^5]
    - Tilting categories: I ≈185 mm and 265 mm for specific tilt fleets (not general design).[^5]

These values apply broadly across the conventional speed range (up to about 200–225 km/h); at higher speeds the available radius or cant tends to govern before formal I caps change with speed.[^6][^3]
- **Cant excess**
On mixed‑traffic lines, NR practice is to keep cant excess for slow freight typically within about 60–80 mm, similar to ADIF freight guidance, to protect the low rail.[^7][^3]


## Side‑by‑side summary by speed band (non‑tilting passenger)

Approximate envelopes, focusing on design values for plain line (not platforms), and standard/normal limits rather than extremes:[^3][^5][^1][^2]


| Speed band | Administration | Max cant (plain line) | Typical max cant deficiency I | Typical max cant excess E |
| :-- | :-- | :-- | :-- | :-- |
| Up to ~100 km/h | ADIF | 140–160 mm (ref/normal) [^2] | Up to ~153 mm allowed, but comfort usually governs at ≈100–115 mm [^2] | 90–100 mm (ref/normal) [^2] |
|  | HS2 | 160 mm [^1] | 110 mm [^1] | 50–90 mm [^1] |
|  | Network Rail | ≈150 mm (often ≤130 mm in practice) [^3] | ≈90–110 mm depending on traffic mix [^3][^5] | ≈60–80 mm on mixed‑traffic routes [^3] |
| 100–250 km/h | ADIF | 140–160 mm [^2] | Up to about 100–130 mm reference/normal (standard gauge) [^2] | 90–100 mm [^2] |
|  | HS2 (100–250) | 160 mm [^1] | 100–110 mm [^1] | 50–90 mm [^1] |
|  | Network Rail (≤200–225) | ≈150 mm [^3] | ≈110 mm “passenger” category [^5][^6] | ≈60–80 mm typical [^3] |
| 250–300 km/h | ADIF (high‑speed) | 140–160 mm (≤180 mm exceptional) [^2] | Reference ≈80 mm; normal up to ≈130 mm; exceptional 153 mm [^2] | 90–100 mm [^2] |
|  | HS2 (250–300) | 160 mm [^1] | 80–100 mm [^1] | 50–90 mm [^1] |
| Above 300 km/h | ADIF (up to 350) | 140–160 mm (≤180 mm exceptional) [^2] | Reference ≈60 mm; normal ≈80 mm; exceptional 100 mm [^2] | 90–100 mm [^2] |
|  | HS2 (>300) | 160 mm [^1] | 60–80 mm [^1] | 50–90 mm [^1] |
|  | Network Rail (not above 300) | n/a – GB conventional speeds lower [^3] | n/a (HS2 covers GB high‑speed) | n/a |

In practical design, all three administrations:

- Cap cant for main‑line, non‑platform curves at about 150–160 mm.[^3][^1][^2]
- Allow around 100–110 mm cant deficiency at conventional speeds, reducing to 60–80 mm at ≥300 km/h (ADIF and HS2).[^1][^2]
- Keep cant excess for slow traffic typically in the 60–100 mm range to control inner‑rail loading.[^3][^2]
<span style="display:none">[^10][^11][^12][^13][^14][^15][^16][^17][^18][^19][^20][^21][^22][^23][^8][^9]</span>

<div align="center">⁂</div>

[^1]: https://www.thepwi.org/wp-content/uploads/2022/10/2022-10-18_HS2-Track-engineering-design_Phil-Edwards.pdf

[^2]: NAP1210_ED2-diseno-trazado-ferroviario.pdf

[^3]: https://railwaytrackblog.com/2016/04/11/track-design-limits-of-vertical-acceleration/

[^4]: https://es.scribd.com/document/535887958/NAP-1-2-1-0-Metodologia-Para-El-Diseno-Del-Trazado-Ferroviario

[^5]: https://www.railengineer.co.uk/etcs-implementation-issues/

[^6]: https://railwaytrackblog.com/2015/10/29/11-82_cant-deficiency-un-compensated-acceleration-pway/

[^7]: 9.0-Geometria-y-Trazado.pdf

[^8]: https://learninglegacy.hs2.org.uk/document/an-automated-digital-method-for-the-assessment-of-crosswind-safety-for-the-hs2-route/

[^9]: https://pedestrianobservations.com/2021/04/22/tilting-trains-and-technological-dead-ends/

[^10]: https://www.railforums.co.uk/threads/how-are-speed-limits-set.262183/page-2

[^11]: https://www.thepwi.org/wp-content/uploads/2021/02/Journal-202001-Vol138-Pt1-HS2-Gauging.pdf

[^12]: https://jekay.com/understanding-cant-deficiency-ensuring-railway-safety-and-stability/

[^13]: https://www.uic.org/IMG/pdf/mixed_uic_handbook_dec_2020-final_03.pdf

[^14]: https://en.wikipedia.org/wiki/Cant_deficiency

[^15]: https://www.adif.es/documents/20124/25584321/PropModif_NAP1210_ED1_M1_FC1.pdf/ed6310a0-b7c4-7e81-4842-a9f863e79d1c?t=1700228880134

[^16]: https://railroads.dot.gov/sites/fra.dot.gov/files/2022-07/Arup Aero-A.pdf

[^17]: https://www.adif.es/documents/20124/26526320/PropModif_NAP1201_ED6_FC1.pdf/025388d5-aef6-f13e-8c50-55df2491881c?t=1701780342758

[^18]: https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/794108/HS2-HS2-RR-SPE-000-000007_P11_TTS_Main_Body__External_.pdf

[^19]: https://www.linkedin.com/pulse/understanding-cant-railway-projects-ayman-sayed-pmp-vma-bnqvf

[^20]: https://www.studocu.com/es/document/universidad-politecnica-de-madrid/ferrocarriles/04-trazado-ffcc-adif-nap1210-unlocked/118281163

[^21]: https://en.wikipedia.org/wiki/High_Speed_2

[^22]: https://www.networkrail.co.uk/wp-content/uploads/2025/08/Challenges-Issue-August-2025-Current-Standard-Challenges.pdf

[^23]: https://es.scribd.com/document/593943713/Nap-1-2-0-1-m1-m2-indice-Tipo-y-Contenido

