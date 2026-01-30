<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# Calculate maximum allowable speed for a given curve radius and cant for each network

For all three networks, the maximum allowable speed on a curve of radius $R$ with cant $D$ is obtained from the same basic cant‑deficiency relationship; only the allowable cant deficiency $I_{\max}$ differs between ADIF, HS2 and Network Rail.[^1][^2][^3]

## General formula (standard / Iberian gauge)

Using the EN 13803 / ADIF formulation for distance between rolling circles $e$ and equilibrium cant coefficient $q_e$, the cant deficiency is:

$$
D_{eq} = q_e \frac{V^2}{R}, \quad I = D_{eq} - D
$$

with $V$ in km/h, $R$ in m, $D$ and $I$ in mm.[^1]

For standard gauge, $q_e = 11.8$ mm·m/km²; for Iberian gauge, $q_e \approx 13.6$ mm·m/km².[^1]

Solving for the maximum speed $V_{\max}$ allowed by a specified cant $D$, curve radius $R$ and network‑specific cant deficiency limit $I_{\max}$:

$$
V_{\max} = \sqrt{\frac{(D + I_{\max})\,R}{q_e}}
$$

with units as above.[^1]

This formula is valid for ADIF, HS2 and Network Rail; only $I_{\max}$ (and, for Iberian gauge, the value of $q_e$) changes by network and speed band.[^2][^3][^1]

## ADIF

For line design (non‑tilting passenger, standard gauge), ADIF NAP 1‑2‑1.0 gives by‑speed cant deficiency limits; typical “normal” design values are:[^1]

- $v \le 230$ km/h: $I_{\max} \approx 153$ mm.
- $230 < v \le 300$ km/h: $I_{\max} \approx 130$–153 mm.
- $300 < v \le 350$ km/h: $I_{\max} \approx 80$–100 mm.

Design procedure for maximum speed on a given curve:

1. Choose the appropriate $I_{\max}$ for the design speed band.
2. Use $q_e = 11.8$ mm·m/km² (standard gauge) or 13.6 (Iberian).[^1]
3. Compute $V_{\max} = \sqrt{\dfrac{(D + I_{\max})R}{q_e}}$.

Example (ADIF, standard gauge, “normal” limit, curve $R = 2000$ m, cant $D = 150$ mm, speed band ≤230 km/h, so $I_{\max} = 153$ mm):

$$
V_{\max} = \sqrt{\frac{(150 + 153)\cdot 2000}{11.8}} \approx \sqrt{\frac{603000}{11.8}} \approx \sqrt{51102} \approx 226\; \text{km/h}.
$$

This is within the intended band and below ADIF’s 350 km/h global line limit.[^1]

## HS2

HS2 uses essentially the same relationship, but with HS2‑specific cant‑deficiency limits by speed:[^2]

- $V \le 100$ km/h: $I_{\max} = 110$ mm.
- $100 < V \le 250$ km/h: $I_{\max} = 100$–110 mm (two envelopes).
- $250 < V \le 300$ km/h: $I_{\max} = 80$–100 mm.
- $V > 300$ km/h: $I_{\max} = 60$–80 mm.

Using standard gauge $q_e = 11.8$:[^1]

$$
V_{\max,\mathrm{HS2}} = \sqrt{\frac{(D + I_{\max,\mathrm{HS2}})\,R}{11.8}}.
$$

For the same geometric example as above ($R = 2000$ m, $D = 150$ mm, high‑speed envelope, say $I_{\max,\mathrm{HS2}} = 80$ mm for $>300$ km/h):

$$
V_{\max,\mathrm{HS2}} = \sqrt{\frac{(150 + 80)\cdot 2000}{11.8}} = \sqrt{\frac{460000}{11.8}} \approx \sqrt{38983} \approx 197\; \text{km/h}.
$$

The lower HS2 cant‑deficiency limit at very high speeds gives a lower allowable speed for the same curve and cant than an ADIF “normal” envelope would.[^2][^1]

## Network Rail

UK conventional (non‑HS2) design typically uses the same EN relationships, often expressed via the “11.82” factor:[^3]

$$
D_{eq} = \frac{11.82 V^2}{R},\quad I = D_{eq} - D.
$$

This is numerically equivalent to $q_e \approx 11.8$.[^3][^1]

Typical maximum cant deficiency for non‑tilting passenger routes in GB is about 110 mm; freight or mixed‑traffic lines may use lower values (e.g. 75–90 mm).[^4][^3]

So, for Network Rail:

$$
V_{\max,\mathrm{NR}} = \sqrt{\frac{(D + I_{\max,\mathrm{NR}})\,R}{11.8}},
$$

with $I_{\max,\mathrm{NR}}$ chosen according to route category (e.g. 110 mm for a passenger‑priority main line, 90 mm for a freight‑heavy route).[^4][^3]

For the same example ($R = 2000$ m, $D = 150$ mm, passenger route with $I_{\max,\mathrm{NR}} = 110$ mm):

$$
V_{\max,\mathrm{NR}} = \sqrt{\frac{(150 + 110)\cdot 2000}{11.8}} = \sqrt{\frac{520000}{11.8}} \approx \sqrt{44068} \approx 210\; \text{km/h}.
$$

## How to apply in practice

1. **Select the network and line type** (ADIF, HS2 or NR; high‑speed, mixed‑traffic, freight, etc.).[^4][^2][^1]
2. **Take the correct cant‑deficiency limit $I_{\max}$** for that network, speed band and line type (from NAP 1‑2‑1.0 for ADIF, HS2 alignment standard, or NR route category tables).[^2][^4][^1]
3. **Use the general formula** $V_{\max} = \sqrt{\dfrac{(D + I_{\max})R}{q_e}}$ with $q_e = 11.8$ (standard gauge) or 13.6 (Iberian) as appropriate.[^3][^1]

If you provide specific values for $R$, $D$ and the network/line type (e.g. ADIF high‑speed vs HS2), the calculation can be done directly using these formulas.

<div align="center">⁂</div>

[^1]: NAP1210_ED2-diseno-trazado-ferroviario.pdf

[^2]: https://www.thepwi.org/wp-content/uploads/2022/10/2022-10-18_HS2-Track-engineering-design_Phil-Edwards.pdf

[^3]: https://railwaytrackblog.com/2015/10/29/11-82_cant-deficiency-un-compensated-acceleration-pway/

[^4]: https://www.railengineer.co.uk/etcs-implementation-issues/

