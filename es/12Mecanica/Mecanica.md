---
layout: home
title: 12. Mecanica de via
lang: es
permalink: /es/12Mecanica/
nav_order: 12
parent: Inicio
---

# Fundamentos de la Mecánica Ferroviaria: Análisis de Comportamiento Vertical y Transversal de la Infraestructura

---
<details open markdown="block">
<summary>
Índice de contenidos
</summary>
{: .text-delta }
1. TOC
{:toc}
</details>

---
## Capítulo I. Elasticidad de la via

En los materiales granulares como el balasto, así como en las capas del terreno natural que lo soportan, y de manera general en cualquier medio formado por partículas discretas, cuando se aplica una carga por primera ocasión se genera una deformación de naturaleza irreversible conocida como deformación plástica. Sin embargo, cuando estas solicitaciones se repiten de forma consecutiva durante un número considerablemente elevado de ciclos, el comportamiento mecánico del material transita hacia un estado de verdadera elasticidad, caracterizado por respuestas similares a las que experimentan los sólidos monolíticos y homogéneos.

Para cuantificar y caracterizar adecuadamente esta propiedad elástica presente en la estructura de la vía ferroviaria, se recurre a la utilización de diversos parámetros matemáticos y modelos de comportamiento que capturan los aspectos más relevantes de esta respuesta.

### I.1. MODULO DE LA VÍA K

Considerando que $\boldsymbol{q}(\boldsymbol{t} / \boldsymbol{m})$ representa una carga distribuida uniformemente a lo largo de la longitud de un carril, e identificando como el asiento o hundimiento vertical que se produce en el carril como resultado de la aplicación de dicha carga.

Desde una perspectiva del significado físico: este parámetro representa la magnitud de carga que, cuando actúa de manera uniforme y continuada sobre el carril, genera en éste un desplazamiento vertical de magnitud unitaria.

Este módulo es particularmente empleado en contextos de ingeniería ferroviaria americanos y canadienses. Cuando la unidad de asiento considerada es de 1 centímetro, el módulo de la vía K típicamente se encuentra dentro del rango comprendido entre 8 y 22 toneladas por metro lineal
![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-04.jpg?height=508&width=959&top_left_y=2028&top_left_x=1308)

### I.2. COEFICIENTE DE REACCIÓN DE LA TRAVIESA R

Este parámetro fue propuesto inicialmente por el investigador y profesor Timoshenko en el año 1915 como parte de su trabajo fundamental en mecánica de estructuras. En este contexto, $\boldsymbol{R}$ se define como la reacción vertical que emerge en la traviesa, siendo evaluada específicamente por cada uno de los hilos o carriles de apoyo, en tanto que $\boldsymbol{y}$ representa el asentamiento o desplazamiento vertical producido en ese punto de evaluación (medido en toneladas por milímetro).

$$
r=\frac{R}{y}
$$

Puede establecerse una relación de equivalencia entre el módulo de la vía K y el coeficiente r si se introduce la distancia d correspondiente al espaciamiento entre dos traviesas sucesivas:

$$
r=\frac{R}{y}=R \cdot \frac{K}{r}=d \cdot r \cdot \frac{K}{r}=K \cdot d
$$

De donde se desprendem las siguientes relaciones: $K=\frac{r}{y}$ y $R=r \cdot d$

Conviene señalar que esta relación constituye una aproximación a la realidad, ya que en su formulación se ha omitido el efecto de influencia mutua que ejercen las traviesas adyacentes y vecinas entre sí.

### I.3. COEFICIENTE DE BALASTO C

$$
C=\frac{r}{S}
$$

Este coeficiente fue propuesto por Winkler en 1867 y representa la relación entre la reacción elástica y el área de contacto. En esta expresión, $\boldsymbol{S}$ corresponde a la superficie de apoyo que presenta la traviesa en su interfaz con el balasto. Si representamos mediante P (en k/cm²) la presión promedio que se transmite sobre la zona de apoyo $S$ de la traviesa:

$$
C=\frac{r}{S}=\frac{R}{y \cdot S}=\frac{P}{y}
$$

A partir de esta formulación, el coeficiente de balasto puede interpretarse físicamente como la presión unitaria que, cuando se aplica sobre el material del balasto, produce en éste una depresión o asentamiento de exactamente 1 centímetro. Para ilustrar este concepto mediante un ejemplo práctico: consideremos una traviesa apoyada sobre balasto que transmite una presión de $\mathbf{2}$ K/cm² y genera un asiento de $\mathbf{0,05}$ cm; en este caso, el coeficiente de balasto resultante sería:

$$
C=\frac{P}{y}=\frac{2 \mathrm{k} / \mathrm{cm}^{2}}{0,05 \mathrm{~cm}}=40 \mathrm{k} / \mathrm{cm}^{3}
$$

Este parámetro cambia notablemente con el proceso de bateo (apisonamiento) del balasto. De acuerdo con la práctica y la experiencia en diseño de infraestructuras ferroviarias, el coeficiente de balasto debe mantenerse típicamente dentro del intervalo de $5-10$ K/cm³.

### I.4. COEFICIENTE DE ELASTICIDAD

La infraestructura de la vía férrea está compuesta por un sistema integrado de múltiples capas y materiales, cada uno de los cuales presenta características elásticas individuales diferenciadas (plataforma de apoyo, capa de balasto, traviesas, carriles, fijaciones, etc.). Para cada uno de estos componentes constitutivos, es posible asignar un coeficiente de elasticidad específico denotado como $\boldsymbol{r}_{\boldsymbol{n}}$, el cual se establece por definición de la siguiente manera:

$$
r_{n}=\frac{R}{y_{n}}
$$

Considerando que y representa el asentamiento o deformación vertical acumulada total resultante de la superposición de todas las deformaciones individuales de cada componente:

$$
y=\sum_{n} y_{n}=\sum_{n} \frac{R}{r_{n}}=R \cdot \sum_{n} \frac{1}{r_{n}}=\frac{R}{r}
$$

De conformidad con diversos estudios y registros experimentales obtenidos en proyectos de ingeniería ferroviaria, los coeficientes de elasticidad típicos para cada elemento estructural de la vía son:

Traviesa de hormigón : $1200-1500 \mathrm{t} / \mathrm{mm}$
Traviesa de madera: $50-80 \mathrm{t} / \mathrm{mm}$
Alma de carril: $5000-10000 \mathrm{t} / \mathrm{mm}$
Balasto bateado: $10-30 \mathrm{t} / \mathrm{mm}$ - aumenta con el espesor y disminuye con el tiempo.
Plataforma rocosa: $2-8 \mathrm{t} / \mathrm{mm}$
Plataforma arcillosa: $1,5-2 \mathrm{t} / \mathrm{mm}$
Plataforma pantanosa: $0,5-1,5 \mathrm{t} / \mathrm{mm}$

### I.5. COEFICIENTE DE ELASTICIDAD

Desde una perspectiva del comportamiento global de la estructura de la vía, son precisamente el balasto y la plataforma de apoyo los elementos que ejercen la influencia más determinante sobre las características elásticas del conjunto completo de la infraestructura ferroviaria.

$$
y=\sum_{n} y_{n}=\sum_{n} \frac{R}{r_{n}}=R \cdot \sum_{n} \frac{1}{r_{n}}=\frac{R}{r}
$$

El coeficiente de reacción consolidado que representa toda la estructura puede fluctuar dentro de un rango bastante amplio comprendido entre $\mathbf{1 , 5 - 1 0}$ t/mm, dependiendo esencialmente de las características y propiedades del material de balasto empleado y de la naturaleza y composición geológica de la plataforma subyacente. El valor más comúnmente encontrado en proyectos de ingeniería ferroviaria convencional es de aproximadamente $\mathbf{3}$ t/mm.

En contextos especiales, como es el caso de estructuras construidas sobre obras de fábrica, puentes u otras obras de arte, se obtienen valores notablemente más elevados dentro del rango $12-15$ t/mm, evidenciando una diferencia significativa en las propiedades de rigidez.

Debe resaltarse que la plataforma es el componente que presenta el coeficiente elástico más bajo en la cadena de transmisión de cargas, motivo por el cual la presión específica ejercida a nivel de esta plataforma se convierte en el parámetro que condiciona de forma determinante el asentamiento total de la vía. Esta presión sobre la plataforma resulta tanto más reducida cuanto mayor sea el espesor de la capa de balasto interpuesta entre ésta y la estructura superior.

### I.6. Clasificación de cargas

La infraestructura ferroviaria constituye un sistema sometido a un conjunto heterogéneo de solicitaciones mecánicas de naturaleza diversa. Estas cargas pueden ser clasificadas según su dirección y sentido de aplicación en las siguientes categorías principales:

- Cargas Verticales
- Cargas Transversales
- Cargas Longitudinales

Excluyendo los eventos extraordinarios como pueden ser fenómenos sísmicos, es importante recalcar que la totalidad de las fuerzas y solicitaciones dinámicas que actúan sobre la vía ferroviaria son generadas y transmitidas por el material rodante que circula sobre la infraestructura (cargas derivadas del tráfico).

**Cargas Verticales:** Estas se aplican en la superficie de rodadura del carril y se transmiten hacia las capas inferiores del terreno a través de la cadena de componentes estructurales de la vía, incluyendo traviesas, balasto y plataforma.

**Cargas Transversales:** Se transfieren inicialmente desde el contacto rueda-carril hacia los carriles, pudiendo efectuarse únicamente a través de la superficie de rodadura (cuando no existe contacto de las pestañas de las ruedas con el carril) o bien involucrando simultáneamente la superficie de rodadura y principalmente las pestañas de las ruedas (cuando el movimiento lateral causa contacto de pestañas). Posteriormente, estas cargas se propagan hacia las estructuras inferiores mediante los componentes intermedios como son fijaciones, placas de apoyo y traviesas.

**Cargas Longitudinales:** Se aplican tangencialmente sobre la superficie de rodadura del carril y se transmiten a las capas inferiores de forma análoga a las cargas transversales, empleando la misma ruta de distribución de fuerzas.

De acuerdo con la naturaleza temporal de su aplicación, las cargas que actúan sobre la vía se subdividen además en las siguientes categorías:

- Cargas estáticas
- Cargas semiestáticas o cuasiestáticas
- Cargas dinámicas

**Cargas estáticas:** Son aquellas resultantes del peso propio inherente del material rodante y sus componentes. Estas cargas se ejercen de forma permanente e ininterrumpida sobre la vía, independientemente de si el material rodante se encuentra estacionado o en movimiento.

**Cargas semiestáticas o cuasiestáticas:** Estas solicitaciones se transmiten al material rodante y consecuentemente a la vía durante intervalos temporales específicos y determinados. Una vez que cesa la causa que las origina, desaparecen de manera inmediata. Ejemplos representativos incluyen la fuerza centrífuga residual no compensada completamente y las fuerzas generadas por los vientos transversales.

**Cargas dinámicas:** Se originan y generan como consecuencia de múltiples factores concurrentes:
- Irregularidades y defectos presentes en la geometría y alineación de la vía, así como la variabilidad o heterogeneidad en la rigidez vertical de la estructura.
- Discontinuidades y cambios abruptos en la geometría de la superficie de rodadura (tales como juntas de carril, zonas de agujas, cruzamientos, etc.).
- Desgaste progresivo de la superficie de rodadura tanto en carriles como en las pestañas de las ruedas del material rodante.
- Características del sistema de suspensión de los vehículos y asimetrías inherentes al diseño y construcción del material rodante.

### I.7. Cargas Verticales

Complementando las tres categorías descritas anteriormente, es igualmente relevante considerar y analizar de forma específica una categoría adicional de solicitaciones verticales que puede denominarse como "cargas características" que definen el comportamiento de la vía. Esta subcategoría engloba los siguientes componentes:

- La carga por eje Q
- El tráfico ficticio diario equivalente $T_{f}$
- La carga vertical de proyecto por rueda $Q_{d}$

Una característica distintiva y fundamental de todas estas cargas características, las cuales pueden presentar tanto naturaleza estática como dinámica, es que ejercen una influencia determinante sobre los procesos de dimensionamiento y diseño de la infraestructura ferroviaria, así como sobre las estrategias y políticas de mantenimiento preventivo y correctivo que deben implementarse a lo largo de la vida útil de la vía.

#### I.7.1. Cargas Verticales Estáticas

##### Carga por eje

El término "carga por eje" se utiliza para designar la magnitud de carga vertical de naturaleza estática Q que transmite y transfiere cada eje componente de un vehículo ferroviario, y en un sentido más amplio de un tren completo, hacia los carriles a través de sus ruedas de contacto.

Bajo la hipótesis fundamental de que la carga se distribuye de manera simétrica en las distintas partes constitutivas del vehículo, la magnitud de la carga por eje se expresa matemáticamente como el cociente entre el peso total de la unidad vehicular y el número total de ejes que componen el tren.

En el caso particular de un vehículo equipado con bogies convencionales que poseen dos ejes cada uno, la carga por eje se calcula aplicando la siguiente expresión matemática:

$$
Q=\left(\frac{\bar{M}}{4}+\frac{M^{\prime}}{2}+m\right) \cdot g
$$

donde los términos se definen como:
Q: Magnitud de la carga transferida por cada eje.
$\bar{M}$ : Masa de la estructura de la carrocería del vehículo.
$\mathrm{M}^{\prime}$ : Masa de cada uno de los bogies.
m: Masa de un conjunto completo de eje ferroviario, incluyendo el eje, las ruedas, y todos los componentes asociados como cajas de grasa.
g: Aceleración causada por la gravedad terrestre.

La Unión Internacional de Ferrocarriles (UIC) ha establecido una clasificación sistemática de las vías ferroviarias en función de la capacidad máxima de carga permitida por cada eje, dividiéndolas en cuatro categorías o niveles de servicio: A, B, C y D:

| Track category | Axle load $(t)$ |
| :--- | :---: |
| A | 16 |
| B | 18 |
| C | 20 |
| D | 22.5 |

Source: Adapted from UIC. 1989, Fiche 714R, Classification des voies des
lignes au point de vue de la maintenance de la voie.

Es importante reconocer que la carga máxima permitida por eje varía considerablemente de un país ferroviario a otro, e incluso dentro de un mismo país pueden existir variaciones significativas de una línea ferroviaria a otra.

Un aspecto de considerable relevancia práctica es que el incremento del ancho de vía (vía ancha) permite y facilita el aumento significativo de la carga transferida por cada eje. Adicionalmente, las cargas por eje superiores a $Q>16-17$ t se consideran en general como prohibitivas o incompatibles con el desarrollo de velocidades de circulación muy elevadas (superiores a $V \geq 250$ km/h) por razones de seguridad y confort.

##### Carga por rueda

El término "carga por rueda" se refiere a la magnitud de la carga vertical de naturaleza estática $\mathbf{Q}_{\mathbf{o}}$ que transmite cada rueda individual del vehículo hacia su punto de contacto correspondiente sobre el carril.

Considerando condiciones de carga simétricamente distribuida en la unidad vehicular, la carga por rueda se obtiene mediante la siguiente relación matemática:

$$
Q_{o}=\frac{Q}{2}
$$

En contextos prácticos reales, particularmente cuando el vehículo circula en trayectorias curvilíneas, se observa que las cargas transmitidas por las dos ruedas de un mismo eje no son idénticas entre sí, presentando una distribución desigual.

La carga individual de cada rueda, junto con especial énfasis en la distribución diferencial del peso entre ambas ruedas, mantiene una relación directa y significativa con los fenómenos críticos de descarrilamiento y posible vuelco de los vehículos ferroviarios.

##### Trafico ficticio diario

La determinación de la cantidad y características del tráfico que circula sobre una vía se realiza típicamente mediante la introducción del concepto de tráfico ficticio diario $\boldsymbol{T}_{\boldsymbol{f}}$ (expresado en toneladas). Este parámetro constituye una de las denominadas "cargas características" más importantes. Mediante la evaluación del valor total de este tráfico ficticio diario, es posible clasificar las vías ferroviarias en diferentes categorías, permitiendo de esta forma normalizar y estandarizar los criterios de dimensionamiento estructural y los programas de mantenimiento preventivo de las infraestructuras.

Para llevar a cabo el cálculo sistemático de $\boldsymbol{T}_{\boldsymbol{f}}$, la organización internacional UIC ha propuesto y recomendado dos formulaciones matemáticas distintas que pueden emplearse según las características específicas de cada infraestructura:

1. $T_{f}=T_{p} \cdot \frac{V_{\text {max }}}{100}+T_{g} \cdot \frac{Q_{D_{o}}}{18 \cdot D_{o}}$
donde:

| Track category | Total daily traffic load $(t)$ |
| :--- | :--- |
| I | $T_{\mathrm{f}}>40,000$ |
| II | $40,000 \geq T_{\mathrm{f}}>20,000$ |
| III | $20,000 \geq T_{\mathrm{f}}>10,000$ |
| IV | $10,000 \geq T_{\mathrm{f}}$ |

$T_{f}$ : Trafico ficticio diario (en t).
$T_{p}$ : Tráfico de trenes de viajeros (en t ).
$T_{g}$ : Tráfico de trenes de mercancías (en t).
$V_{\text {max }}$ : Velocidad máxima de circulación (en km/h).
$D_{0}$ : Diámetro mínimo de rueda de los trenes que circulan por la línea (en m ).
$Q_{D o}$ : Carga máxima por eje pasante (ruedas de diámetro Do) (en t).

| Track category | Total daily traffic load ( $T_{p}$ ) |
| :--- | :--- |
| UIC I | $130,000 \mathrm{t}<\mathrm{T}_{6}$ |
| UIC 2 | $80,000 \mathrm{t}<\mathrm{T}_{\mathrm{r}} \leq 130,000 \mathrm{t}$ |
| UIC 3 | $40,000 \mathrm{t}<\mathrm{T}_{\mathrm{f}} \leq 80,000 \mathrm{t}$ |
| UIC 4 | $20,000 \mathrm{t}<\mathrm{T}_{\mathrm{f}} \leq 40,000 \mathrm{t}$ |
| UIC 5 | $5,000 \mathrm{t}<\mathrm{T}_{1} \leq 20,000 \mathrm{t}$ |
| UIC 6 | $\mathrm{T}_{4} \leq 5,000 \mathrm{t}$ |

Source: Adapted from UIC. 1989, Fiche 714R, Classification des voies des lignes au point de vue de la maintenance de la voie.
2. $T_{f}=S_{v} \cdot\left(T_{V}+K_{t}+T_{t v}\right)+S_{m} \cdot\left(K_{m} \cdot T_{m}+K_{t} \cdot T_{t m}\right)$
donde:
$T_{f}$ : Trafico ficticio diario (en t).
Tv: Trafico medio diario de coches de viajeros remolcados (en t).
$T_{m}$ : Trafico medio diario de vagones de mercancías (en t).
$T_{t v}$ : Trafico medio diario de locomotoras de pasajeros (en t).
Ttm: Trafico medio diario de locomotoras de mercancías (en t).
$K_{m}$ : Coeficiente con valores que varían entre 1,15 (valor estándar) y 1,45 (cuando > $50 \%$ del tráfico es con vehículos con carga por eje $\mathrm{Q}=22,5 \mathrm{t}$ o cuando $75 \%$ del tráfico es con vehículos de carga por eje $\mathrm{Q} \geq 20 \mathrm{t}$ ).
$K_{t}$ : Coeficiente que depende de las condiciones de rodadura de los ejes de las locomotoras sobre la vía. Suele ser igual a 1,40.
$S_{v}, S_{m}$ : Coeficientes cuyos valores dependen de la velocidad de los trenes de viajeros (con la mayor velocidad) y de mercancías (con la menor velocidad), respectivamente, que circulan por la vía.

#### I.7.2. Cargas Verticales Cuasiestáticas

Carga vertical de la rueda debida a los vientos transversales

Las solicitaciones atmosféricas ejercen influencias significativas sobre el comportamiento dinámico de los vehículos ferroviarios. La carga vertical inducida por los vientos transversales $\mathbf{Q}_{\boldsymbol{w}}$ representa la redistribución de cargas verticals entre las ruedas de un mismo eje, resultado de la acción de fuerzas transversales del viento sobre la carrocería del vehículo. Esta carga se cuantifica mediante la expresión matemática presentada en la siguiente ecuación (Esveld, 2001):
$\pm Q_{w}=H_{w} \cdot \frac{q_{o}}{a}$
![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-19.jpg?height=1094&width=1087&top_left_y=123&top_left_x=2410)
En esta expresión, los parámetros se definen como sigue:
$H_{w}$ : Fuerza transversal del viento aplicada en el centro geométrico de la superficie lateral de la carrocería
$q_{o}$ : Distancia vertical entre el centro geométrico de la superficie lateral de la carrocería y la superficie de rodadura del carril.
a: Distancia entre el eje vertical de simetría de los dos carriles.

El mecanismo de distribución de cargas funciona de forma tal que, cuando la fuerza horizontal del viento $H_{w}$ se dirige desde la rueda 2 hacia la rueda 1, la carga soportada por la rueda 1 se incrementa en la cantidad $Q_{w}$, en tanto que simultáneamente la carga de la rueda 2 experimenta una disminución de idéntica magnitud. Esta característica revela el carácter redistributivo de los esfuerzos transversales.

Desde una perspectiva temporal, la carga originada por los vientos transversales se manifiesta únicamente durante el movimiento del vehículo, tanto en segmentos de vía recta como en tramos curvos, manteniéndose mientras persistan las condiciones de viento. Una vez que cesan dichas condiciones climáticas, la solicitación desaparece, retornando el sistema a su estado de carga estática inicial.

Carga vertical de la rueda debida a la fuerza centrífuga no compensada

En el contexto del movimiento en curvas, la compensación incompleta de la aceleración centrífuga a través del peralte de la vía genera una fuerza residual que se transmite a la estructura de la vía. La carga vertical inducida por esta fuerza centrífuga no compensada $Q_{s c}$ se expresa matemáticamente según se indica en la siguiente ecuación, que establece la relación entre la fuerza residual y la redistribución vertical de cargas (véase la figura adjunta):
$\pm Q_{s c}=\frac{F_{s c} \cdot h_{k B}}{a}=\frac{Q \cdot I \cdot h_{k B}}{a^{2}}$
Los términos que integran esta formulación se definen de la siguiente manera:
$F_{s c}$ : Fuerza centrífuga no compensada.
I: Insuficiencia de peralte.
$h_{\text {кв }}$ : Distancia entre el centro de gravedad del vehículo $\mathrm{G}^{\prime}$ y la
![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-20.jpg?height=1181&width=1254&top_left_y=601&top_left_x=2265)
superficie de rodadura del carril.
$z_{p}$ : Peralte de la vía.
$\delta_{p}$ : Ángulo del peralte.

La magnitud de la carga cuasiestática derivada de la insuficiencia centrífuga presenta características particulares: se activa exclusivamente durante el desplazamiento del vehículo en tramos curvos de la infraestructura, y típicamente adopta valores comprendidos en el intervalo del $\mathbf{1 0 - 2 5 \%}$ de la carga estática nominal de la rueda, dependiendo de los parámetros geométricos y dinámicos de la curva. Respecto a la distribución transversal, la rueda que circula por el carril exterior experimenta un incremento de carga de magnitud $Q_{s c}$, mientras que la rueda interior registra simultáneamente una disminución proporcional de idéntica cuantía, estableciéndose así un equilibrio redistributivo en el sistema de carga de ejes.

#### I.7.3. Cargas Verticales Dinámicas

La interacción entre el material rodante y la infraestructura ferroviaria genera fenómenos dinámicos complejos que introducen solicitaciones fluctuantes superpuestas a las cargas estáticas y cuasiestáticas previamente analizadas. Estas cargas dinámicas constituyen la manifestación de mecanismos de vibración e impacto que derivan tanto de las características constructivas del vehículo como de las irregularidades geométricas presentes en la vía.

La carga vertical dinámica total por rueda $\left(\mathbf{Q}_{\text {dyn }}\right)$ es suma de:

- las masas suspendidas del vehículo ( $\mathbf{Q}_{\text {dyn1 }}$ ): Caja vehículo
- las masas semisuspendidas del vehículo ( $Q_{\text {dyn2). }}$ Bogies
- las masas no suspendidas del vehículo ( $Q_{\text {dyn3). Ejes }}$
- las masas debida a las oscilaciones de las partes elásticas del sistema de fijación carril-traviesa ( $Q_{\text {dyn4 }}$ ).


La naturaleza de las fuerzas dinámicas ejercidas sobre la vía durante la interacción con el material rodante es predominantemente aleatoria, no determinística. Esta característica fundamenta la necesidad de un tratamiento probabilístico y estadístico en su análisis.

Mediante la aplicación de la hipótesis de linealidad en la respuesta estructural, el estudio de los fenómenos dinámicos puede subdividirse en diferentes rangos de frecuencia, según el mecanismo específ ico de oscilación en cuestión, la causa originante de la vibración, y el componente estructural o del vehículo participante en el movimiento oscilatorio.

Consecuentemente, la carga dinámica vertical total por rueda $\boldsymbol{Q}_{\boldsymbol{d} \boldsymbol{y}}$ se obtiene mediante la suma ponderada de todas las categorías de fuerzas dinámicas identificadas:

$$
Q_{d y n j}=Q_{d y n 1 j}+Q_{d y n 2 j}+Q_{d y n 3 j}+Q_{d y n 4 j}
$$


En esta expresión:
$\mathrm{j}=1,2$ : Subíndice indicativo de cada una de las dos ruedas que componen un eje de rodaje.

La evolución histórica de los sistemas ferroviarios ha demostrado que velocidades cada vez más elevadas, combinadas con incrementos progresivos del peso de los vehículos y mayor rigidez de los componentes de la infraestructura, generan un aumento sustancial en la magnitud de los efectos dinámicos, resultando en un incremento significativo de las solicitaciones transmitidas a la superestructura de la vía, la plataforma de asiento y los componentes del vehículo.

Desde una perspectiva metodológica, el cálculo preciso de las fuerzas dinámicas continúa siendo un problema de considerable complejidad analítica, frecuentemente intratable mediante métodos puramente analíticos. En la práctica profesional, la mayoría de los análisis se limitan a aproximaciones cuasiestáticas simplificadas. Sin embargo, el enfoque predominante en ingeniería moderna consiste en la adopción de metodologías empíricas fundamentadas en datos de medición experimental (Giannakos, 2014, 2016).

La magnitud de la carga dinámica adicional puede alcanzar valores tan elevados como el $50 \%$ de la carga estática nominal de la rueda (Alias, 1977). Conforme a la literatura técnica especializada (Profillidis, 1995; Zicha, 1989), en el rango de velocidades hasta 200 $\mathrm{km} / \mathrm{h}$, el coeficiente de impacto dinámico típicamente fluctuá entre 1,35 y 1,6. Por este motivo, para velocidades que no excedan 200 $\mathrm{~km} / \mathrm{h}$, se recomienda la adopción de un coeficiente de impacto dinámico de 1,5 en diseño. Para velocidades superiores a $200 \mathrm{~km} / \mathrm{h}$, es prudente realizar estudios analíticos detallados fundamentados en datos experimentales específicos de la infraestructura en estudio.

#### I.7.5. Carga vertical total de la rueda

La cuantificación integral de la solicitación vertical transmitida por el material rodante hacia la estructura de la vía requiere la consideración conjunta de todos los componentes de carga identificados en secciones precedentes. La carga vertical total de la rueda $Q_{t}$ representa la envolvente de solicitaciones, expressándose como la composición algebraica de las cargas verticales estáticas nominales, las adiciones cuasiestáticas derivadas de efectos ambientales y de curvatura, y las fluctuaciones dinámicas aleatorias:

$$
Q_{t j}=Q_{o j} \pm Q_{w j} \pm Q_{s c j} \pm Q_{d y n j}
$$

Esta expresión integral proporciona el marco de referencia para la evaluación de la respuesta estructural de la vía ante el paso del tráfico ferroviario.

#### I.7.6. Carga vertical de proyecto por rueda

La metodología de diseño de infraestructuras ferroviarias requiere el establecimiento de un parámetro de solicitación representativo que encapsule la probabilidad estadística de no ser excedido durante la vida útil de la vía. Este parámetro se denomina "carga vertical de proyecto por rueda" $\mathbf{Q}_{\boldsymbol{d}}$, y representa el valor característico de la solicitación vertical que, desde una perspectiva probabilística, está asociado a la máxima probabilidad teórica de no ser superado en condiciones reales de operación a lo largo del ciclo de vida completo de la infraestructura.

La formulación de la carga vertical de proyecto incorpora un tratamiento estadístico riguroso que reconoce la naturaleza aleatoria de los fenómenos dinámicos. La carga de proyecto $\boldsymbol{Q}_{\boldsymbol{d}}$ se calcula como la suma integrada de la componente estática nominal, la contribución cuasiestática (derivada de condiciones ambientales y geométricas), y un término que representa la dispersión estadística de las fuerzas dinámicas, ponderado por un factor de probabilidad. Esta ponderación estadística garantiza un margen de seguridad probabilístico frente a excedencias de carga en condiciones operacionales. La formulación matemática que expresa este concepto proviene de la literatura especializada (Esveld, 2001; Giannakos, 2002) y se presenta a continuación:

$$
Q_{d j}=Q_{o j}+Q_{H j}+n_{p} \cdot \sqrt{\sigma\left(Q_{d y n 3 i}\right)^{2}+\sigma\left(Q_{d y n 1 i}+Q_{d y n 2 i}\right)^{2}}
$$

Los términos que integran esta ecuación se definen según se especifica a continuación:
$\mathrm{Q}_{\mathrm{d}}$ : Carga vertical de proyecto por rueda.
Qo: Componente estática de la carga vertical por rueda.
$Q_{H}$ : Componente cuasiestática de la carga vertical por rueda.
$\sigma\left(Q_{\mathrm{dyn}}\right)$ : Desviación típica (o estándar) de las fuerzas dinámicas verticales asociadas a las masas no suspendidas del vehículo.
$\sigma$ ( $Q_{\text {dyn1 }}, Q_{\text {dyn2) }}$ : Desviación típica de las fuerzas dinámicas verticales correspondientes a las masas suspendidas y semisuspendidas del vehículo.
$\mathrm{n}_{\mathrm{p}}$ : Coeficiente multiplicador que amplifica el valor cuadrático medio de las desviaciones típicas dinámicas, asegurando la cobertura de la probabilidad estadística de no excedencia durante la vida útil de la infraestructura. Este coeficiente adopta típicamente un valor de 5,00 (Demiridis y Pyrgidis, 2010). $\mathrm{j}=1,2$ : Índice subscript indicativo de cada una de las dos ruedas del mismo juego de ruedas de un eje.

### I.8. Cargas Transversales

Las solicitaciones transversales constituyen un aspecto crítico para la evaluación de la seguridad operacional del sistema ferroviario. Estas fuerzas están directamente vinculadas tanto a la seguridad cinética de la circulación ferroviaria como al confort dinámico percibido por los pasajeros, siendo capaces de desencadenar el fenómeno crítico del descarrilamiento.

Las fuerzas transversales pueden clasificarse en dos categorías fundamentales según su mecanismo de origen:

#### I.8.1. Fuerzas provocadas por la interacción rueda-carril

Esta categoría comprende un conjunto de fuerzas derivadas de la dinámica de interacción entre los elementos de rodadura del vehículo y la infraestructura. Incluye: las fuerzas gravitatorias o restauradoras derivadas de la conicidad de las ruedas, las fuerzas de guía que emerge n ante el contacto de las pestañas de las ruedas con los carriles, las fuerzas de rozamiento tanto transversales como longitudinales resultantes del deslizamiento relativo en el punto de contacto, y las fuerzas dinámicas asociadas a las oscilaciones del vehículo. Las fuerzas de rozamiento se subdividen adicionalmente en componentes transversales y longitudinales.

Una segunda categoría de fuerzas transversales es originada por efectos exogénos a la dinámica de circulación convencional. Esta categoría, denominada "fuerzas debidas a otras causas", abarca la fuerza centrífuga no compensada derivada del movimiento en curvas con insuficiencia de peralte, así como la fuerza transversal del viento atmosférico.

#### I.8.2. Fuerzas Gravitatorias

En el punto de contacto rueda-carril, la reacción normal global $\boldsymbol{R}_{\mathbf{o}}$ puede descomponerse en dos componentes ortogonales: una componente vertical $\boldsymbol{Q}_{\mathbf{o}}$ (la carga de la rueda) y una componente transversal $\boldsymbol{S}_{\boldsymbol{p o}}$ (véase la figura de referencia). La componente transversal $\mathrm{S}_{\mathrm{po}}$, denominada "fuerza gravitatoria", "fuerza restauradora" o "rigidez gravitatoria", constituye un mecanismo de recentraje que actúa para mantener el eje de ruedas en su posición de equilibrio sobre la vía. Esta fuerza es causada exclusivamente por la geometría cónica de la banda de rodadura de la rueda, transmitiéndose a través del eje hacia la superficie de rodadura del carril.

Se considera una fuerza de naturaleza dinámica y se expresa matemáticamente según:
$S_{p o}=Q_{o} \cdot \tan \gamma_{o}$
en la que:
![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-26.jpg?height=915&width=682&top_left_y=1333&top_left_x=2703)

Qo: Carga estática de la rueda.
$\gamma_{o}$: Ángulo de inclinación de la superficie de rodadura respecto al plano horizontal en la posición central de equilibrio de la rueda.

![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-27.jpg?height=446&width=340&top_left_y=42&top_left_x=3027)

En el caso de un eje de ruedas conv encional, cada una de las dos ruedas genera su propia fuerza gravitatoria ( $\boldsymbol{S}_{\boldsymbol{p} j,} \mathrm{j}=1,2$ ), como se ilustra esquemáticamente en la figura adjunta.

Cuando se produce un desplazamiento transversal del eje de ruedas, simbolizado por "y", la distribución asimétrica del contacto rueda-carril origina variaciones en las fuerzas gravitatorias individuales. Las expresiones matemáticas que describen este comportamiento son:
$S_{p 1}=Q_{1} \cdot \tan \gamma_{1}=Q_{1} \cdot \gamma_{1}$
$S_{p 2}=Q_{2} \cdot \tan \gamma_{2}=Q_{2} \cdot \gamma_{2}$
donde:
![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-27.jpg?height=598&width=1257&top_left_y=1260&top_left_x=2044)
$Q_{1}$, $Q_{2}$ : Componentes verticales de las reacciones $R_{1}$ y $R_{2}$ en los puntos de contacto $\mathrm{I}_{1}$ e $\mathrm{I}_{2}$, respectivamente.
$\gamma_{1}$, $\gamma_{2}$ : Ángulos formados por el plano horizontal y los planos tangentes en los puntos de contacto $\mathrm{l}_{1}$ e $\mathrm{l}_{2}$, respectivamente (como $\gamma_{1}$, $\gamma_{2}$ son cantidades muy pequeñas, se aplica $\tan \gamma_{1}=\gamma_{1}$ y $\tan \gamma_{2}=\gamma_{2}$ ).


La determinación rigurosa de las relaciones anteriores se obtiene mediante el análisis geométrico de la interacción rueda-carril, asumiendo que: (i) la rueda posee una forma cónica con una inclinación de curvatura de radio constante, y (ii) la cabeza del carril presenta una superficie esférica de curvatura complementaria. A partir de esta resolución geométrica, se derivan las siguientes ecuaciones lineales que caracterizan el comportamiento dinámico (Pyrgidis, 1990):
$\gamma_{1}=\gamma_{o}+\frac{\gamma_{e}}{R \cdot \gamma_{o}} \cdot y$
$\gamma_{2}=-\gamma_{0}+\frac{\gamma_{e}}{R \cdot \gamma_{0}} \cdot y$
![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-28.jpg?height=808&width=1706&top_left_y=1093&top_left_x=1738)
$\gamma_{e}=\frac{R \cdot \gamma_{o}}{R-R^{\prime}}$

R = Radio de curvatura de la banda de rodadura de la rueda
$R^{\prime}$= Radio de curvatura de la superficie de rodadura de la cabeza de carril
$\gamma_{o}$: Ángulo de inclinación en la posición central de equilibrio.

Considerando una distribución simétrica de la carga entre ambas ruedas, se obtiene la fuerza gravitatoria total resultante mediante:

$S_{p}=S_{p 1}+S_{p 2}=2 Q_{o} \cdot \frac{\gamma_{e} \cdot y}{R \cdot \gamma_{o}}$

Alternativamente, expresada en términos de los parámetros de curvatura:

#### I.8.3. Fuerzas de rozamiento

##### Circulación en línea recta

Las fuerzas de rozamiento que emergen en la interfaz rueda-carril constituyen un mecanismo fundamental de interacción dinámica entre el vehículo y la infraestructura. Las componentes longitudinales de estas fuerzas de rozamiento son responsables de múltiples efectos perjudiciales: promueven el desgaste progresivo de la banda de rodadura tanto del vehículo como del carril, generan fatiga cíclica en los materiales constitutivos de la zona de contacto, producen emisiones acústicas significativas (ruido de rodadura), e inducen oscilaciones longitudinales del vehículo.

Para caracterizar las fuerzas de rozamiento resultantes de la dinámica de una rueda convencional circulando por una trayectoria recta, se aplica la teoría lineal de Kalker, que proporciona las siguientes expresiones analíticas:
$X_{1}=-c_{11} \cdot\left(\frac{X^{\prime}}{V}-\frac{a}{2 \cdot V} \cdot \alpha^{\prime}-\frac{\gamma_{e}}{r_{o}} \cdot y\right)$
$T_{1}=-c_{22} \cdot\left(\frac{y^{\prime}}{V}-\alpha\right)-c_{23} \cdot\left(\frac{\alpha^{\prime}}{V}-\frac{\gamma_{o}}{r_{o}}-\frac{\gamma_{e} \cdot y}{R \cdot \gamma_{o} \cdot r_{o}}\right)$
$M_{1}=-c_{23} \cdot\left(\frac{y^{\prime}}{V}-\alpha\right)-c_{33} \cdot\left(\frac{\alpha^{\prime}}{V}-\frac{\gamma_{o}}{r_{o}}-\frac{\gamma_{e} \cdot y}{R \cdot \gamma_{o} \cdot r_{o}}\right)$

$$
\begin{aligned}
& X_{2}=-c_{11} \cdot\left(\frac{X^{\prime}}{V}+\frac{a}{2 \cdot V} \cdot \alpha^{\prime}+\frac{\gamma_{e}}{r_{o}} \cdot y\right) \\
& T_{2}=-c_{22} \cdot\left(\frac{y^{\prime}}{V}-\alpha\right)-c_{23} \cdot\left(\frac{\alpha^{\prime}}{V}+\frac{\gamma_{o}}{r_{o}}-\frac{\gamma_{e} \cdot y}{R \cdot \gamma_{o} \cdot r_{o}}\right) \\
& M_{2}=-c_{23} \cdot\left(\frac{y^{\prime}}{V}-\alpha\right)-c_{33} \cdot\left(\frac{\alpha^{\prime}}{V}+\frac{\gamma_{o}}{r_{o}}-\frac{\gamma_{e} \cdot y}{R \cdot \gamma_{o} \cdot r_{o}}\right)
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-30.jpg?height=965&width=1413&top_left_y=1700&top_left_x=2005)
donde:
$\mathrm{X}_{1}, \mathrm{X}_{2}$ : Fuerzas de rozamiento longitudinales aplicadas en ambas ruedas.
$\mathrm{T}_{1}, \mathrm{~T}_{2}$ : Fuerzas de rozamiento laterales aplicadas en ambas ruedas.
$\mathrm{M}_{1}, \mathrm{M}_{2}$ : Momento de giro en ambas ruedas.
ro: radio de la rueda en su posición central de equilibrio
R: Radio de curvatura de la banda de rodadura de la rueda
x: Desplazamiento longitudinal del eje de ruedas.
y : Desplazamiento lateral del eje de ruedas.
$\alpha$ : Ángulo de ataque del eje de ruedas.
$\varphi$ : Ángulo de giro de las ruedas y del juego de ruedas.
$\mathrm{x}^{\prime}, \mathrm{y}^{\prime}, \alpha^{\prime}, \varphi^{\prime}$ : Derivadas de los desplazamientos $\mathrm{x}, \mathrm{y}$,
del ángulo de ataque $\alpha$, y del ángulo de giro $\varphi$.
$\mathrm{c}_{11}$ : Coeficiente longitudinal de Kalker.
c22: Coeficiente transversal de Kalker.
$\mathrm{c}_{23}, \mathrm{c}_{33}$ : Coeficientes de giro del Kalker.

##### Circulación en curvas

En el contexto de movimiento en curvatura de la vía, los mecanismos de fricción experimentan modificaciones significativas respecto al caso de línea recta. Para un eje convencional transitando por una sección curvada de la infraestructura, la teoría lineal de Kalker proporciona las siguientes expresiones analíticas corregidas para capturar los efectos de la curvatura horizontal:

$$
\begin{aligned}
& X_{1}=-c_{11} \cdot\left(-\frac{\gamma_{e}}{r_{o}} \cdot y-\frac{a}{2 \cdot V} \cdot \alpha^{\prime}+\frac{a}{2 \cdot R_{c}}\right) \\
& X_{2}=-c_{11} \cdot\left(+\frac{\gamma_{e}}{r_{o}} \cdot y+\frac{a}{2 \cdot V} \cdot \alpha^{\prime}-\frac{a}{2 \cdot R_{c}}\right) \\
& T_{1}=-c_{22} \cdot\left(\frac{y^{\prime}}{V}-\alpha\right)-c_{23} \cdot\left(\frac{\alpha^{\prime}}{V}-\frac{1}{R_{c}}-\frac{\gamma_{o}}{r_{o}}-\frac{\gamma_{e} \cdot y}{R \cdot \gamma_{o} \cdot r_{o}}\right) \\
& T_{2}=-c_{22} \cdot\left(\frac{y^{\prime}}{V}-\alpha\right)-c_{23} \cdot\left(\frac{\alpha^{\prime}}{V}-\frac{1}{R_{c}}+\frac{\gamma_{o}}{r_{o}}-\frac{\gamma_{e} \cdot y}{R \cdot \gamma_{o} \cdot r_{o}}\right) \\
& M_{1}=-c_{23} \cdot\left(\frac{y^{\prime}}{V}-\alpha\right)-c_{33} \cdot\left(\frac{\alpha^{\prime}}{V}-\frac{\gamma_{o}}{r_{o}}-\frac{1}{R_{c}}-\frac{\gamma_{e} \cdot y}{R \cdot \gamma_{o} \cdot r_{o}}\right) \\
& M_{2}=-c_{23} \cdot\left(\frac{y^{\prime}}{V}-\alpha\right)-c_{33} \cdot\left(\frac{\alpha^{\prime}}{V}+\frac{\gamma_{o}}{r_{o}}-\frac{1}{R_{c}}-\frac{\gamma_{e} \cdot y}{R \cdot \gamma_{o} \cdot r_{o}}\right)
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-31.jpg?height=1119&width=1578&top_left_y=1216&top_left_x=1905)

Rc: radio de curvatura de la alineación horizontal.

En el régimen particular de movimiento en curvas de radio pequeño, donde la velocidad de circulación se aproxima a la velocidad de equilibrio correspondiente a ese radio, el comportamiento dinámico puede simplificarse significativamente. En tales condiciones, las fuerzas de inercia y amortiguación resultan despreciables comparadas con las fuerzas de rigidez elástica de la vía. Adicionalmente, cuando se ignora el efecto de giro del eje, las ecuaciones se reducen a las formas siguientes, que capturan los aspectos esenciales del comportamiento sin excesiva complejidad matemática:

$$
\begin{aligned}
& X_{1}=-c_{11} \cdot\left(-\frac{\gamma_{e}}{r_{o}} \cdot y+\frac{a}{2 \cdot R_{c}}\right) \\
& X_{2}=-c_{11} \cdot\left(+\frac{\gamma_{e}}{r_{o}} \cdot y-\frac{a}{2 \cdot R_{c}}\right) \\
& T_{1}=T_{2}=-c_{22} \cdot\left(\frac{y^{\prime}}{V}\right)
\end{aligned}
$$


Como se evidencia en el análisis esquemático presentado, las fuerzas de rozamiento longitudinales generan rotación horizontal del eje de ruedas, que en combinación con las fuerzas de rozamiento laterales activa el fenómeno de oscilación sinusoidal (hunting) en los ejes de los bogies, provocando vibraciones y oscilaciones laterales persistentes.

Fundamentalmente, las fuerzas de rozamiento se originan como respuesta a desviaciones entre la dirección de rodadura de las ruedas y el desplazamiento real del eje. Tales desviaciones ocurren tanto ante desplazamientos transversales "y" del eje como ante variaciones en el ángulo de ataque "a" respecto a la posición de equilibrio. Por consiguiente, para mitigar las fuerzas de rozamiento resulta imprescindible enfocarse en los parámetros causantes: las irregularidades geométricas de la vía.

Las medidas mitigadoras que contribuyen a la reducción de las fuerzas de rozamiento incluyen:

A. El perfilado y rotación de las ruedas a intervalos regulares, asegurando la mantención de geometrías óptimas.

B. La selección cuidadosa de características constructivas fundamentales de los bogies: perfilado específico de la rueda, diámetro nominal de rodadura, rigidez de la suspensión primaria, y espaciamiento entre ejes del bogie.

C. La adopción de tecnologías modernas de bogies concordantes con las exigencias operacionales de la red ferroviaria.

Aspectos técnicos especializados de las fuerzas de rozamiento:

- La presencia o ausencia de componentes longitudinales y laterales de rozamiento depende fundamentalmente del modo de conexión entre la rueda y el eje.
- La generación de momentos de giro está condicionada por la relación geométrica entre el plano de rodadura de la rueda y su eje de rotación.

La siguiente tabla sintetiza el repertorio de fuerzas contacto rueda-carril para distintas tecnologías de ejes ferroviarios (materializadas o propuestas teóricamente) (Frederich, 1985):

| Tecnologia | Representación esquemática | Sp | T | x | M |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Ejes convencionales - Ruedas de conicidad variable | ![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-34.jpg?height=160&width=231&top_left_y=1016&top_left_x=1952) | Si | Si | Si | Si |
| Ejes con ruedas que ruedan de forma independiente Ruedas de conicidad variable | ![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-34.jpg?height=166&width=231&top_left_y=1193&top_left_x=1952) | Si | Si | No | Si |
| Ejes articulados - Ruedas de conicidad variable | ![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-34.jpg?height=167&width=231&top_left_y=1376&top_left_x=1952) | Si | No | Si | Si |
| Ejes convencionales - Ruedas cilíndricas | ![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-34.jpg?height=139&width=231&top_left_y=1559&top_left_x=1952) | No | Si | Si | No |
| Ejes convencionales - Ruedas de conicidad constante | ![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-34.jpg?height=164&width=227&top_left_y=1725&top_left_x=1952) | No | Si | Si | Si |
| Ruedas que ruedan de forma independiente - Ruedas de conicidad variable | ![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-34.jpg?height=153&width=227&top_left_y=1912&top_left_x=1952) | Si | No | No | Si |
| Ejes con ruedas que ruedan de forma independiente Ruedas inclinadas de conicidad variable | ![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-34.jpg?height=149&width=220&top_left_y=2089&top_left_x=1959) | Si | No | No | No |
| Ejes convencionales - Ruedas inclinadas de conicidad variable | ![](https://cdn.mathpix.com/cropped/aa60068f-bc7e-44ba-9a68-6c5e8aec8794-34.jpg?height=153&width=220&top_left_y=2265&top_left_x=1959) | Si | Si | Si | No |
| Frederich, F. 1985, Possibilités inconnues et inutilisées du contact rail-roue, Rail International, Brussels, November 1985 pp. 33-40 |  |  |  |  |  |

Un aspecto tecnológico relevante para reducir los efectos desfavorables de las fuerzas de rozamiento longitudinales consiste en eliminar el acoplamiento rígido que tradicionalmente une las dos ruedas de un mismo eje. Esta modificación permite que cada rueda pueda girar a una velocidad angular independiente, mientras se mantiene la condición cinemática de que ambas ruedas circulen sin deslizamiento relativo respecto a sus respectivas líneas de contacto:

$$
\omega_{1} \cdot r_{1}=\omega_{2} \cdot r_{2}=V
$$

donde:
$\omega_{1}, \omega_{2}$ : Velocidades angulares de las dos ruedas. $r_{1}, r_{2}$ : Sus radios de rodadura.

Esto garantiza la rodadura de las dos ruedas sin rozamiento y la eliminación de las fuerzas de rozamiento longitudinales. La tecnología de bogies con ruedas de rotación independiente se basa en esta lógica.

#### I.8.4. Fuerzas de viento transversal

La acción de los vientos atmosféricos constituye una solicitación ambiental de significancia en la operación de sistemas ferroviarios, especialmente en viaductos, zonas montañosas y áreas costeras expuestas. Cuando prevalecen vientos transversales de magnitud considerable, se transmite una fuerza lateral $\boldsymbol{H}_{\boldsymbol{w}}$ a través de la carrocería y estructura del vehículo hacia los ejes de ruedas, y de estos hacia la superficie de rodadura del carril. Esta fuerza se caracteriza como cuasiestática en su naturaleza, adoptando una dirección coincidente con la del viento prevaleciente. El punto de aplicación inicial se ubica en el centro geométrico de la proyección lateral de la carrocería. La expresión de cálculo que cuantifica esta solicitación proviene de la aerodinámica vehicular (Hibino et al., 2010):
$H_{w}=\frac{1}{2} \cdot \rho \cdot S_{2} \cdot V_{w}^{2} \cdot K_{2}$
especificándose los parámetros como sigue:
$\mathrm{H}_{\mathrm{w}}$ : Magnitud de la fuerza transversal ejercida por el viento (expresada en Newtons)
$\mathrm{V}_{\mathrm{w}}$ : Velocidad del viento (expresada en metros por segundo)
$\rho$ : Densidad volumétrica del aire (expresada en kilogramos por metro cúbico)
$\mathrm{S}_{2}$ : Área de la proyección lateral del vehículo perpendicular al flujo de viento (expresada en metros cuadrados)
$\mathrm{K}_{2}$ : Coeficiente aerodinámico de fuerza lateral (parámetro adimensional dependiente de la geometría externa de la carrocería)

La fuerza transversal del viento $H_{w}$ representa una solicitación indeseable, generando múltiples efectos perjudiciales: promueve desplazamientos transversales excesivos de los ejes de ruedas hacia el lado de barlovento, incrementa el riesgo de contacto entre las pestañas de las ruedas y los carriles, y fundamentalmente amplifica el potencial de activación del mecanismo de vuelco del vehículo.

Para contrarrestar los efectos de los vientos transversales intensos, se pueden implementar las siguientes medidas de mitigación:

- Instalación de sistemas de barreras o pantallas cortaviento en secciones de vía particularmente expuestas a meteorología severa
- Restricciones operacionales: reducción de velocidad o interrupción temporal de la circulación en zonas de alta exposición a vientos transversales extremos

#### I.8.5. Fuerza Centrifuga no compensada

Cuando un vehículo de masa $\boldsymbol{m}$ circula a una velocidad $\boldsymbol{V}$ en una curva cuyo radio de curvatura es $\boldsymbol{R}$, el centro de gravedad del vehículo genera la fuerza centrífuga $\boldsymbol{F}_{\boldsymbol{c}}$, que empuja el vehículo hacia el lado exterior de la curva (figura):

$$
F_{c}=m \cdot \alpha_{c}=\frac{m \cdot V^{2}}{R}
$$

Debido al peralte de la vía $\mathbf{z}_{\boldsymbol{p}}$, actúan simultáneamente la componente transversal del peso (en dirección opuesta) y la la fuerza centrífuga. Siendo: $\quad I=\alpha_{s c} \cdot \frac{a}{g}$
La diferencia entre estas fuerzas es la fuerza centrífuga no compensada $\boldsymbol{F}_{\boldsymbol{n} \boldsymbol{c}}$. A nivel de los ejes de ruedas y, por consiguiente, de la superficie de rodadura del carril, se aplica lo siguiente:

$$
F_{c, S C}=m \cdot \alpha_{S C}=\frac{Q}{g} \cdot \alpha_{S C}=\frac{Q}{g} \cdot\left(\frac{V^{2}}{R}-\frac{g \cdot z_{p}}{a}\right)=\frac{Q \cdot I}{a}
$$

El aumento de la velocidad $\boldsymbol{V}$ del vehículo, así como la disminución del radio de curvatura $\boldsymbol{R}$ y la disminución del peralte $\mathbf{z}_{\boldsymbol{p}}$ contribuyen al aumento de la aceleración centrífuga residual.

La $\boldsymbol{F}_{\boldsymbol{c}, \boldsymbol{s} \boldsymbol{c}}$ se considera una fuerza cuasiestática y siempre es indeseable, ya que no sólo provoca el desplazamiento de los ejes de las ruedas (riesgo de contacto de las pestañas), sino también problemas de confort transversal dinámico de los pasajeros. Además, ayuda al mecanismo de descarrilamiento del vehículo. Sin embargo, razones de tráfico como la coexistencia de trenes de baja y alta velocidad en la misma vía y el riesgo de deslizamiento transversal del eje de ruedas hacia el carril interior hacen indispensable la adopción de un peralte inferior al peralte de equilibrio (peralte teórico), lo que provoca la aparición de una aceleración centrífuga residual.

Por ejemplo, cuando $Q=18 t, V=150 \mathrm{~km} / \mathrm{h}, R=1.500 \mathrm{~m}, g=9,81 \mathrm{~m} / \mathrm{s}^{2}$, $a= 1,50 m$ y $z_{p}=130 m m$, entonces $F_{c, s c}=5,6 k N$ y $\alpha_{s c}=0,307 m / s^{2}$.

Para reducir la fuerza centrífuga residual, pueden aplicarse las siguientes medidas:

- Elección racional de los datos geométricos de la curva (insuficiencia y exceso de peralte).
- Utilización de trenes basculantes.

#### I.8.6. Fuerzas transversal total transmitida del vehículo al carril

Según Alias (1977) y Profillidis (1995), la fuerza transversal total H (en t) transmitida del vehículo al carril se calcula aplicando la siguiente fórmula empírica:

$$
H=H_{o}+H_{a}=a_{i} \cdot\left(\frac{Q \cdot I}{a}\right)+\left(\frac{Q \cdot V}{1.000}\right)
$$

donde:
I: Insuficiencia de peralte (en caso de movimiento a lo largo de tramos curvos de vía) o defecto o torsión transversal de vía (en caso de movimiento en trayectoria recta) (en mm).
Q: Carga por eje (en t).
V: Velocidad de marcha (en km/h).
a: distancia entre ejes de carriles en mm .
$a_{i}$ : Coeficiente que indica el reparto desigual de la fuerza centrífuga entre los dos ejes de un bogie (valores 1-1,1) (Montagné, 1975).

El primer término de la ecuación se refiere a las fuerzas cuasiestáticas y, concretamente, a la fuerza centrífuga residual.
El segundo término se refiere a las fuerzas dinámicas aleatorias derivadas de las irregularidades de la alineación de la vía y de los movimientos del propio vehículo, o de sus bogies, que provocan inestabilidad por encima de una velocidad crítica (fuerzas debidas a las oscilaciones del vehículo, fuerzas de rozamiento, fuerzas gravitatorias, etc.) (Montagné, 1975).

#### I.8.7. Fuerzas debida a alas oscilaciones del vehículo

Estas cargas dinámicas transversales $P_{\text {dyn, cuyas causas son similares a }}$ las de las cargas dinámicas verticales, confieren aceleraciones transversales suplementarias a las distintas partes del vehículo. Para resolver el problema, es preciso eliminar los defectos de la vía y aplicar el rectificado de carriles.

#### I.8.8. Fuerzas de guía

Cuando el desplazamiento transversal de un juego de ruedas de ferrocarril alcanza una magnitud igual a la holgura nominal $\boldsymbol{J}$ disponible entre la pestaña de la rueda y los carriles vecinos, la zona saliente lateral de la pestaña de la rueda entra en contacto directo con la cara interna de los carriles (véanse las figuras esquemáticas de referencia). En el punto de contacto de pestaña-carril, actúan cargas dinámicas transversales de magnitud generalmente considerable. Estas fuerzas se denominan "fuerzas de guía" $\boldsymbol{F}_{\boldsymbol{j}}$ ( $\mathrm{j}=1$ ó 2, en referencia a cada una de las dos ruedas del eje).

Las consecuencias operacionales de la existencia de fuerzas de guía constituyen un conjunto de impactos negativos significativos que afectan simultáneamente a pasajeros, material rodante e infraestructura ferroviaria:

- Degradación marcada del confort dinámico percibido por los viajeros, manifestada mediante incrementos de aceleraciones transversales y "sacudidas" laterales perceptibles
- Generación de ruido de rodadura considerable, con impacto ambiental en zonas urbanas adyacentes
- Promoción del desgaste acelerado de las superficies de rodadura tanto de ruedas como de carriles (abrasión de pestañas y cabezas de carril)
- Incremento significativo de fatiga estructural en los componentes del bogie
- Potencial de desencadenamiento de descarrilamiento por deslizamiento lateral de la vía bajo cargas repetidas de guía
- Riesgo de descarrilamiento por remonte o subida de las ruedas sobre la cabeza de carril cuando las fuerzas de guía alcanzan magnitudes críticas

Consecuentemente, desde la perspectiva de la ingeniería de seguridad ferroviaria, es de máxima importancia evitar, siempre que sea posible técnicamente viable, el contacto de las pestañas de las ruedas con los carriles durante la operación normal de los vehículos.

Para minimizar y controlar la magnitud de las fuerzas de guía, se pueden adoptar varias categorías de medidas mitigadoras:

- Selección cuidadosa y racional de los parámetros de diseño fundamentales de los bogies: perfil geométrico específico de la rueda, diámetro nominal de rodadura, rigidez y características de amortiguamiento de la suspensión primaria del bogie, y distancia de separación entre ejes del bogie
- Adopción de tecnologías modernas y avanzadas de bogies que optimicen el comportamiento dinámico y sea n concordantes con las características operacionales de la red ferroviaria específica
- Ampliación controlada de la holgura lateral $J$ en segmentos de vía curvada de radio muy pequeño ( $Rc<150-200 \mathrm{~m}$ ), permitiendo mayor libertad transversal antes de contacto
- Aplicación de lubricación de alto rendimiento en la cara interior de los carriles en segmentos curvos, reduciendo el rozamiento de la pestaña y las fuerzas laterales transmitidas

Desde una perspectiva analítica y metodológica, la fuerza de guía $F$ presenta características estadísticas (naturaleza estocástica), lo cual implica que su magnitud instantánea varía de forma aleatoria en el tiempo (Profillidis, 2014). La magnitud de esta fuerza depende de numerosos parámetros que interaccionan de forma no lineal. En consecuencia, para la mayoría de aplicaciones prácticas el cálculo preciso de su valor se logra mediante aproximaciones numéricas, predominantemente a través de metodologías de simulación dinámica:

a) Mediciones in situ a lo largo del carril utilizando dinamómetros especializados montados en las ruedas de vehículos instrumentados
b) Modelos de simulación computacional, de los cuales existe una variedad en el mercado profesional (SIMPACK, UMLAB, Vampire Pro, Adams/Rail, etc.), ampliamente utilizados tanto por la industria como por la comunidad investigadora.

Las fuerzas de guía $F_{j}$ se derivan como resultado de la combinación algebráica de todas las componentes individuales de fuerza transversal que interactúan en el eje de ruedas (cada componente se obtiene del modelo de simulación):

$$
F_{j}= \pm\left(T_{1}+T_{2}\right) \pm S_{p} \pm F_{s c} \pm F_{r e s}
$$

Los términos integrantes de esta relación se definen como sigue:
$\mathrm{T}_{1}, \mathrm{~T}_{2}$ : Componentes laterales de las fuerzas de rozamiento aplicadas en los puntos de contacto de cada rueda respectivamente
$\mathrm{S}_{\mathrm{p}}$ : Fuerza gravitatoria (restauradora) total resultante de ambas ruedas
$\mathrm{F}_{\mathrm{nc}}$ : Fuerza centrífuga no compensada transmitida al eje de ruedas
Fres: Fuerzas laterales de reacción producidas por los elementos elásticos (muelles) de la suspensión primaria del bogie.

Para el caso particular de descarrilamiento de un eje de ruedas, cuando el ángulo de ataque del juego de ruedas alcanza magnitudes muy significativas ( $\alpha \geq 5$ rad), se aplica la siguiente relación simplificada:

$$
F_{1}=H+Y_{2}
$$

donde los parámetros se definen como sigue:
$F_{1}$ : Fuerza de guía aplicada en el punto de contacto pestaña-carril de la rueda en estado crítico de descarrilamiento
H: La fuerza lateral total transmitida del vehículo al carril (cuantificada a nivel del eje de ruedas)

$$
Y_{2}=Q_{2} \cdot \tan \left(\gamma_{2}+\rho_{2}\right)
$$

Q2: Carga vertical estática de la rueda 2
$\gamma_{2}$ : Ángulo de contacto rueda-carril (i.e., ángulo entre la generatriz de rodadura de la rueda 2 y el plano horizontal)
$\rho_{2}$ : Ángulo de fricción estática en la interfaz rueda-carril de la rueda 2

La expresión empeírica que relaciona el ángulo de friccción con el radio de curvatura de la vía es (Amans y Sauvage, 1969; Joly, 1983):

$$
\tan \left(\gamma_{2}+\rho_{2}\right)=\frac{135}{(150+R)}
$$

El valor numérico de $\tan \rho_{2}$ varía en función de las condiciones climáticas y ambientales prevalentes, adopta ndo típicamente valores en el rango 0,15 a 1,25 (Amans y Sauvage, 1969).
Para el caso estándar de carriles con inclinación 1:40 se tiene $\gamma_{2}=0,02$ rad.

Esta relación puede reescribirse aproximadamente como:

$$
\frac{135}{\left(150+R_{c}\right)} \approx \mu
$$

donde $\mu$ representa el coeficiente adimensional de adherencia (Joly, 1983).

Rc: Radio de alineación horizontal de la curva (expresado en metros).

## Capítulo II. Descarrilamiento

Concepto fundamenta: El término "descarrilamiento" constituye la descripción de un evento crítico que caracteriza la pérdida irreversible de contacto entre al menos una rueda del vehículo ferroviario y la superficie de trabajo o rodadura de la cabeza del carril, resultando en la salida no intencional del material rodante de su trayectoria designada.

Los descarrilamientos de vehículos ferroviarios pueden originarse y manifestarse como consecuencia de tres mecanismos físicos diferenciados:

- El desplazamiento o corrimiento lateral involuntario de la vía misma
- El vuelco e inclinación incontrolada del vehículo
- El remonte o subida de una o varias ruedas sobre la cabeza del carril

En términos de clasificación por origen, las causas que provocan descarrilamientos pueden ser:

- De naturaleza interna al sistema (fuerzas excesivas generadas por el vehículo sobre la infraestructura, circulación a velocidades superiores a las permitidas, deterioro de la calidad del material rodante, deficiencias en el diseño geométrico de la vía, erosión o colapso de terraplenes, etc.) o
- De naturaleza externa al sistema (errores en operación y conducción, eventos climatológicos adversos como vientos extremos, presencia de obstáculos, sabotaje, etc.).

#### II.0.1. Descarrilamiento debido al vuelco del vehículo

El fenómeno del descarrilamiento inducido por vuelco del vehículo constituye un mecanismo de pérdida de contacto que puede manifestarse tanto durante la circulación en segmentos de vía curvada como durante el movimiento en secciones rectilíneas de la infraestructura ferroviaria.

**Verificación del descarrilamiento por vuelco en segmentos de vía curvada**

El vuelco puede producirse siguiendo dos trayectorias distintas: hacia el lado exterior de la curva o hacia el lado interior de la misma.

**Vuelco dirigido hacia el exterior de la curva** (Esveld, 2001) puede deberse a múltiples factores concurrentes:

- Insuficiencia significativa del peralte con respecto a la velocidad de paso Vp y al radio de curvatura de la trayectoria, produciendo un incremento en la magnitud de la fuerza centrífuga residual lateral Fnc.
- Presencia de fuerzas aerodinámicas generadas por vientos transversales Hw dirigidas hacia el lado exterior de la curva.
- Distribución desigual de la masa vertical del vehículo entre sus dos ruedas laterales, particularmente cuando existe una sobrecarga en el lado exterior (Q1 > Q2). Todos estos factores combinados generan momentos desestabilizadores que impulsan el vuelco del vehículo hacia el carril exterior.

**Vuelco dirigido hacia el interior de la curva** puede deberse a:

- Fuerzas aerodinámicas generadas por vientos transversales $\mathrm{H}_{\mathrm{w}}$ que se dirigen hacia el lado interior de la curva.
- Inmovilidad o parada completa del vehículo ( $V=0$ ) ubicado en un segmento de vía curvada con peralte $\mathrm{z}_{\mathrm{p}}$ elevado.
- Cargas por eje reducidas o insuficientes.
- Desplazamiento o migración de la masa vehicular hacia el lado interior de la curva.

En estos casos, se generan momentos de fuerzas que impulsan el vuelco del vehículo hacia el carril interior, lo que finalmente precipita el descarrilamiento.

La evaluación y comprobación del riesgo de descarrilamiento por vuelco puede llevarse a cabo mediante dos enfoques: formulaciones analíticas rigurosas o metodologías empíricas basadas en experiencia.

#### II.0.2. Utilización de relaciones analíticas

El procedimiento de evaluación se basa en el análisis riguroso de los momentos de todas las fuerzas que actúan sobre el vehículo, considerando su rotación alrededor del punto de contacto crítico ubicado en la cabeza del carril donde se inicia el vuelco (ver figura de referencia). Para esta evaluación se aplica la ecuación fundamental propuesta por Rivier (Rivier, 1984/85):

$$V_{\text {der }, o v}^{2}=\frac{R \cdot g \cdot\left(\frac{z_{p}}{a}+\frac{a}{2 h_{K B}}\right)}{1-\left(\frac{z_{p}}{a} \cdot \frac{a}{2 h_{K B}}\right)}$$

donde se definen los parámetros:
$V_{\text {der.ov:}}$ Velocidad crítica a partir de la cual se produce el descarrilamiento por vuelco.
$h_{\mathrm{kB}}$ : Altura o distancia vertical entre el centro de gravedad de la masa del vehículo y la superficie de contacto del carril.
g: Aceleración de la gravedad terrestre.
a: Distancia transversal entre los ejes verticales de simetría de ambos carriles.

#### II.0.3. Descarrilamiento debido al vuelco del vehículo

**Utilización de formulaciones empíricas**

Este método de evaluación es aplicable únicamente cuando la altura del centro de gravedad satisface la condición $h_{\mathrm{kB}}>2,25$ m y se restringe exclusivamente a los casos en los cuales el vuelco se orienta hacia el exterior de la infraestructura vial (Amans y Sauvage, 1969).

Para que ocurra el fenómeno del descarrilamiento por vuelco debe cumplirse la siguiente condición límite:
$$\alpha_{s c, \max }>\frac{g}{3}$$

donde: $\alpha_{s c, m a x}$ : Aceleración lateral máxima sin compensar que el vehículo puede soportar.

Adicionalmente, se aplican las siguientes relaciones matemáticas:
$$\alpha_{s c}=\frac{V^{2}}{R}-\frac{g \cdot z_{p}}{a} \quad \alpha_{s c}=g \cdot \frac{I}{a} \quad I=\frac{a \cdot V^{2}}{g \cdot R}-z_{p}$$

A partir del análisis de estas ecuaciones se puede deducir que para la ocurrencia de un descarrilamiento dirigido hacia el exterior de la vía por efecto de vuelco debe satisfacerse la siguiente condición fundamental:

$$\alpha_{s c}=g \cdot \frac{I}{a}>\frac{g}{3} \rightarrow I>\frac{a}{3} \rightarrow V>V_{d e r, o v}=\sqrt{R \cdot g \cdot\left(\frac{1}{3}+\frac{z_{p}}{a}\right)}$$

#### II.0.4. Comprobación de descarrilamiento por vuelco - movimiento en segmentos de vía rectos

En el contexto del movimiento de vehículos en alineaciones horizontales rectas de la infraestructura, este tipo específico de descarrilamiento puede manifestarse únicamente bajo condiciones de fuerzas aerodinámicas transversales extremadamente severas, siendo siempre la dirección del desplazamiento concordante con la dirección del viento actuante.

#### II.0.5. Utilizando relaciones analíticas

Este procedimiento de verificación se fundamenta en el análisis equilibrado de todos los momentos actuantes:
A. El momento generado por la fuerza aerodinámica del viento transversal, y
B. El momento resultante del peso total del vehículo, ambos considerados respecto al punto crítico de contacto en la cabeza del carril alrededor del cual ocurriría el vuelco.

Para esta evaluación se emplean las siguientes ecuaciones matemáticas fundamentales:
$$M_{t} \cdot g \cdot \frac{a}{2}=q_{o}^{*} \cdot H_{w} \quad H_{w}=\frac{1}{2} \cdot \rho \cdot S_{2} \cdot V_{w}^{2} \cdot K_{2}$$

$$V_{w}=\sqrt{\frac{M_{t} \cdot g \cdot a}{q_{o}^{*} \cdot \rho \cdot S_{2} \cdot K_{2}}}$$

donde se especifican los significados de los parámetros:
Mt: Masa total de la estructura y contenido del vehículo ferroviario (expresada en kilogramos).
$\mathrm{H}_{\mathrm{w}}$ : Magnitud de la fuerza aerodinámica transversal o lateral generada por el viento (expresada en Newtons).
$\mathrm{V}_{\mathrm{w}}$ : Velocidad del viento atmosférico en m/seg.
$\rho$ : Densidad volumétrica del aire (kg/m³).
$\mathrm{S}_{2}$ : Área de proyección lateral del vehículo expuesta a las fuerzas aerodinámicas (expresada en m²).
$\mathrm{K}_{2}$ : Coeficiente adimensional de resistencia aerodinámica lateral (parámetro dependiente de la geometría de la superficie lateral del vehículo).
$\mathrm{q}^{*} \circ\left(=1,25 \mathrm{q}_{o}\right)$ : Altura efectiva compensada del punto de aplicación de la fuerza aerodinámica transversal, medida desde la superficie de rodadura de los carriles (expresada en metros).

#### II.0.6. Descarrilamiento por desplazamiento lateral de la vía

En el mecanismo de descarrilamiento asociado al desplazamiento lateral de la vía, el conjunto de elementos estructurales que conforman la superestructura vial (carriles, traviesas, sistemas de fijación) experimenta un movimiento lateral involuntario de magnitud significativa bajo la influencia de fuerzas transversales excesivas, lo que finalmente precipita el descarrilamiento de uno o múltiples vehículos que circulan en el tren.

El descarrilamiento por desplazamiento lateral de la vía ocurre cuando se cumple la siguiente condición:
$$H>H_{R}$$

donde:
H: Fuerza lateral total que se transfiere y transmite desde el vehículo hacia el carril.
$\mathrm{H}_{\mathrm{R}}$ : Capacidad de resistencia lateral de la estructura completa de la vía.

Este tipo específico de descarrilamiento es atribuible exclusivamente a causas y factores internos del sistema ferroviario, constituyendo el mecanismo de descarrilamiento más frecuentemente observado en la práctica operativa.

La fuerza lateral total H (expresada en toneladas) puede calcularse mediante la aplicación de la siguiente fórmula empírica consolidada:
$$H=H_{o}+H_{a}=a_{i} \cdot\left(\frac{Q \cdot I}{a}\right)+\left(\frac{Q \cdot V}{1.000}\right)$$

#### II.0.7. Descarrilamiento por desplazamiento lateral de la vía - Cálculo de resistencia

Respecto al cálculo sistemático de la resistencia lateral de la infraestructura $\mathrm{H}_{\mathrm{R}}$ se han desarrollado y propuesto múltiples formulaciones matemáticas en la literatura especializada (ORE, 1984; Amans y Sauvage, 1969; Prud'homme, 1967). A título de referencia y aplicación práctica, se presentan a continuación las formulaciones más utilizadas (la $\mathrm{H}_{\mathrm{R}}$ se calcula en toneladas):

##### Criterio de resistencia de Prud'homme

$$H_{R}=0,85 \cdot\left(1+\frac{Q}{3}\right)$$

donde:
$\mathrm{H}_{\mathrm{R}}$ : Capacidad de resistencia lateral de la vía (expresada en toneladas).
Q: Magnitud de la carga vertical por eje ferroviario (en toneladas).

Esta ecuación (aplicada con el factor corrector 0,85) incorpora de forma implícita el efecto de la alineación horizontal de la vía y las tensiones térmicas que actúan sobre los elementos de carril, aunque asume implícitamente una vía que no ha sido plenamente estabilizada mediante consolidación.

**Descarrilamiento por desplazamiento lateral de la vía: Fórmulas empíricas alternativas**

**Para infraestructuras con traviesas de hormigón:**
$$H_{R}=0,6 \cdot(Q+6) \cdot\left(1-0,4 \cdot e^{\frac{T_{t}}{60.000}}\right)$$

donde:
Q: Carga vertical aplicada por eje (en toneladas).
Tt: Volumen acumulado de tráfico que ha circulado (en toneladas).

Para una vía que ha sido completamente estabilizada mediante tráfico ($\mathrm{T}_{\mathrm{t}}=\infty, e^{\frac{T_{t}}{60.000}}=0$) la ecuación anterior se reduce a:
$$H_{R}=0,6 \cdot Q+3,6$$

Para una vía que aún no ha sido estabilizada ($\mathrm{T}_{\mathrm{t}}=0, e^{\frac{T_{t}}{60.000}}=1$) la ecuación se transforma en:
$$H_{R}=0,36 \cdot Q+2,16$$

**Para infraestructuras con traviesas de madera:**
$$H_{R}=0,5 \cdot(Q+4) \cdot\left(1-0,4 \cdot e^{\frac{T_{t}}{60.000}}\right)$$

Para vía completamente estabilizada ($\mathrm{T}_{\mathrm{t}}=\infty$):
$$H_{R}=0,5 \cdot Q+2$$

Para vía sin estabilizar ($\mathrm{T}_{\mathrm{t}}=0$):
$$H_{R}=0,3 \cdot Q+1,2$$

#### II.0.8. Descarrilamiento por desplazamiento lateral de la vía - Aplicación de fórmulas

Si se incorporan las relaciones siguientes en el análisis: $\quad z_{t, \text { max }}(mm)=11,8 \cdot \frac{V_{\text {max }}^{2}(Km/h)}{R(m)} \quad$ e $\quad I=z_{t, \text { max }}-z_{p}$

Y considerando las expresiones matemáticas:
$$H_{R}=0,6 \cdot(Q+6) \cdot\left(1-0,4 \cdot e^{\frac{T_{t}}{60.000}}\right) \quad H_{R}=0,5 \cdot Q+2 \quad H=a_{i} \cdot\left(\frac{Q \cdot I}{a}\right)+\left(\frac{Q \cdot V}{1.000}\right)$$

Junto con la hipótesis de distribución uniforme de fuerzas centrífugas entre los dos ejes del bogie ( $\mathrm{a}_{\mathrm{i}}=1$ y $\mathrm{a}=1500$mm), es posible establecer, basándose en la condición crítica $\mathrm{H}>\mathrm{H}_{\mathrm{R}}$, que la velocidad crítica de descarrilamiento $\mathrm{V}_{\text {der.dis }}$ a partir de la cual ocurre el descarrilamiento por desplazamiento lateral (para traviesas de hormigón o madera en vía plenamente estabilizada) viene dada por las ecuaciones polinómicas:

**Vía con traviesas de hormigón:**
$$\left(11,8 \cdot \frac{Q}{R}\right) \cdot V_{\text {der,dis }}^{2}+1,5 \cdot Q \cdot V_{\text {der,dis }}-Q \cdot\left(z_{p}+900\right)-5400=0$$

**Vía con traviesas de madera:**
$$\left(11,8 \cdot \frac{Q}{R}\right) \cdot V_{\text {der,dis }}^{2}+1,5 \cdot Q \cdot V_{\text {der,dis }}-Q \cdot\left(z_{p}+750\right)-3000=0$$

donde: $Q(t), R(m), \mathrm{z}_{\mathrm{p}}(\mathrm{mm})$, y $V_{\text {der.dis }}(\mathrm{km} / \mathrm{h})$

En alineaciones horizontales rectas de la vía, donde el peralte es ausente, el parámetro I (que representa insuficiencia de peralte) se asimila al defecto transversal o torsión de la alineación. En condiciones ideales donde el defecto transversal es nulo, teóricamente no existe riesgo de descarrilamiento por desplazamiento lateral. Si igualamos $\mathrm{I}=0$, las ecuaciones anteriores se transforman:

**Vía con traviesas de hormigón:**
$$V_{\text {der,dis }}=600+\frac{3600}{Q}$$

**Vía con traviesas de madera:**
$$V_{\text {der,dis }}=500+\frac{2000}{Q}$$

Para una carga estándar de $Q=22,5$ t, se requiere $V_{\text {der.dis }} \geq 760$ km/h (para traviesas de hormigón) y $V_{\text {der.dis }} \geq 589$ km/h (para traviesas de madera) para que ocurra un descarrilamiento por desplazamiento lateral.

Tomando en consideración el análisis expuesto, para minimizar y reducir efectivamente el riesgo de descarrilamiento por desplazamiento lateral de la vía, deben adoptarse estrategias que apunten a:

A. Reducir la magnitud de la fuerza lateral H que se transfiere desde el vehículo hacia la infraestructura o
B. Incrementar la capacidad de resistencia transversal de la vía $\mathrm{H}_{\mathrm{R}}$ o
C. Implementar medidas combinadas que aborden ambos aspectos simultáneamente.

Respecto a la fuerza H, los parámetros que la afectan se derivan de manera directa o indirecta de la ecuación fundamental:

$$H=a_{i} \cdot\left(\frac{Q \cdot I}{a}\right)+\left(\frac{Q \cdot V}{1.000}\right)$$

Con relación a la resistencia transversal $\mathrm{H}_{\mathrm{R}}$, los siguientes parámetros de diseño y construcción incrementan significativamente su valor:

- Uso de traviesas de hormigón prefabricado de masa elevada
- Empleo de carriles soldados continuos de elevada masa por unidad de longitud
- Sistemas de fijación con componentes elásticos
- Vía plenamente estabilizada mediante tráfico consolidado
- Infraestructuras en vía en placa
- Subestructura del lecho de vía en excelente estado

En el caso particular de infraestructuras con balasto:

- Amplitud considerable de la zona de apoyo lateral del balasto
- Espesor generoso de la capa de balasto
- Alto grado de compactación y dureza del material granular
- Ciclos de bateo poco frecuentes que preservan la consolidación

#### II.0.9. Descarrilamiento por remonte de la pestaña de la rueda

Para que sea posible la ocurrencia de descarrilamiento por remonte de la pestaña es necesario que previamente se haya producido el contacto entre la pestaña y la cara interior del carril, generándose consecuentemente fuerzas de guiado (F) que impulsen el remonte.

En el punto de contacto entre la pestaña de la rueda y la cara interior del carril (ver figuras de referencia), la rueda ejerce una fuerza de guiado $F_{1}$ sobre el carril, junto con la carga vertical de la rueda $Q_{1}$. A su vez, el carril reacciona con una fuerza vertical $N_{1}$ y una fuerza de rozamiento lateral $\mathrm{T}_{1}$ (que durante el deslizamiento adquiere el valor de la fuerza de fricción de Coulomb).

En la práctica operativa, el descarrilamiento por remonte de la pestaña se produce cuando la resultante de todas las proyecciones de fuerzas sobre el eje vertical de acción (eje de la fuerza de descarrilamiento) se orienta hacia arriba, y el tiempo durante el cual actúa esta fuerza resultante es suficientemente prolongado para permitir que la rueda ascienda y supere la altura de la cabeza del carril.

El descarrilamiento puede ocurrir cuando existe una descarga vertical significativa de la rueda que va a descarrilar simultáneamente con una sobrecarga vertical de la rueda opuesta del mismo eje.

Este fenómeno se observa típicamente durante circulación a baja velocidad en curvas de pequeño radio de curvatura que presentan elevados valores de peralte y torsión de la vía.

Normalmente esta modalidad de descarrilamiento se produce por causas externas al sistema (mal funcionamiento y desajuste de agujas de cambio de vía, etc.). La mayoría de los descarrilamientos en zonas de agujas y cruzamientos obedecen a múltiples causas concurrentes. El descarrilamiento puede manifestarse en desvíos cuando la fuerza centrífuga desarrollada alcanza magnitudes muy significativas (en desvíos rectos no existe peralte en la alineación) y simultáneamente la resistencia lateral de la vía es alta (generando descarrilamientos súbitos) (Centre for Advanced Maintenance Technology, 1998).

El riesgo de descarrilamiento por remonte de pestaña aumenta significativamente cuando concurren:

- Incremento de la magnitud de la fuerza de guiado
- Mayor duración temporal de aplicación de la fuerza de guiado
- Aumento del coeficiente de fricción rueda-carril (en condiciones de lluvia el riesgo es menor)
- Mayor ángulo de inclinación del juego de ruedas
- Disminución del ángulo de contacto entre el carril y la pestaña de la rueda
- Descarga vertical importante de la rueda descarrilada simultáneamente con sobrecarga de la rueda opuesta

Se requiere un tiempo específico durante el cual la rueda descarrilada recorre una cierta distancia sobre la vía, típicamente algunos metros. Esta distancia se denomina "distancia de remonte de pestaña" y se define como la distancia recorrida desde el instante en que actúa el valor total de la fuerza de guiado hasta el momento en que el ángulo de contacto entre la pestaña y el carril alcanza los $26,6°$ (Dos Sandos et al., 2010).

Para llevar a cabo la verificación y evaluación del riesgo de descarrilamiento por remonte de la pestaña pueden emplearse las siguientes metodologías y criterios técnicos:

**Criterios basados en la evaluación de la relación $F_{1}$ / $Q_{1}$**

El descarrilamiento se evita cuando se cumple la siguiente condición fundamental:

$$\frac{F_{1}}{Q_{1}}<K_{d}$$

donde:
$\mathrm{K}_{\mathrm{d}}$ : Factor crítico de descarrilamiento (relacionado específicamente con el remonte de pestaña).
Q1: Carga vertical estática de la rueda que está siendo evaluada bajo riesgo de descarrilamiento (asumiendo la rueda 1).
$\mathrm{F}_{1}$ : Magnitud de la fuerza de guiado aplicada.

Los criterios técnicos que evalúan esta relación se encuentran ampliamente documentados en la literatura especializada (FP7, 2011; Iwnicki, 2006; Ishida y Matsuo, 1999; Alias, 1977; Profillidis, 2005) e incluyen de forma no exhaustiva los siguientes:

- Criterio de Nadal (presupone que el ángulo de ataque rueda-carril no es exactamente cero)
- Criterio de Weinstock
- Criterio de Chartet (aplicable para ángulos de ataque de $\alpha>1°$)
- Criterio de descarrilamiento para ángulos de ataque elevados ($\alpha>5$ mrad)

De conformidad con los datos reportados en la bibliografía especializada (FP7, 2011; Iwnicki, 2006; Ishida y Matsuo, 1999; Umdrucke zur Grundvorlesung, 2002/2003):

- En Japón y Europa Occidental se emplea típicamente $\mathrm{K}_{\mathrm{d}}=0,8$
- En países sudamericanos se adopta $\mathrm{K}_{\mathrm{d}}=1,0$
- En China el valor límite se considera $\mathrm{K}_{\mathrm{d}}=1,0$ mientras que el límite de riesgo corresponde a $\mathrm{K}_{\mathrm{d}}=1.2$

**Fórmula empírica para cálculo de velocidad crítica de descarrilamiento por remonte**

Mediante la igualación de las siguientes expresiones (Rivier, 1984/85):
$$F_{C, S C}=\frac{Q}{4} \quad F_{C, S C}=\frac{Q}{g} \cdot\left[\frac{V^{2}}{R}-\frac{g \cdot z_{p}}{a}\right]$$

Se obtiene la expresión:
$$V_{\text {der }, wcl}=\sqrt{R \cdot g \cdot\left(\frac{z_{p}}{a}+\frac{1}{4}\right)}$$

donde:
$V_{\text {der.wcl:}}$ Velocidad crítica a partir de la cual se produce el descarrilamiento por remonte de pestaña.

Las expresiones $F_{c, S c}=\frac{Q}{4}$ y $\mathrm{V}_{\text {der.wcl }}$ fueron propuestas por el Profesor Rivier de la Escuela Politécnica Federal de Lausana, fundamentándose en evidencia experimental pura. Estas expresiones corresponden a las condiciones más desfavorables y críticas para la ocurrencia de descarrilamiento por remonte de pestaña.

#### II.0.10. Descarrilamiento por incremento del ancho de vía o vuelco lateral del carril

En este mecanismo de descarrilamiento, la interacción de grandes fuerzas laterales transmitidas por las ruedas sobre los carriles en segmentos curvos de la infraestructura puede generar desplazamientos laterales significativos de ambos carriles y/o el vuelco de la cabeza del carril, lo que frecuentemente resulta en la caída de la rueda que no ha descarrilado entre las dos cabezas de carril (ver figuras de referencia) (Iwnicki, 2006; Blader, 1990).

El desgaste longitudinal del ancho de vía constituye otra de las causas que contribuyen al incremento del espacio entre carriles.

Para llevar a cabo la verificación del riesgo de descarrilamiento causado por incremento del ancho de vía se utiliza la siguiente formulación (ver figuras):
$$G \geq B+e+w_{wh}$$

donde:
G: Ancho de vía medido entre las cabezas interiores de los carriles.
e: Espesor de la pestaña de la rueda.
B: Distancia entre ruedas (medida entre superficies interiores de ambas ruedas).
$w_{wh}$ : Anchura de la rueda en su banda de rodadura.

Para la verificación del riesgo de descarrilamiento causado por vuelco de la cabeza del carril se aplica la siguiente formulación (Iwnicki, 2006):
$$F>Q \cdot \frac{d_{i}}{h_{r}}$$

donde:
$\mathrm{h}_{\mathrm{r}}$ : Altura total de la sección del carril.
d: Distancia máxima medida desde el borde del patín (base) del carril hasta el punto de aplicación de la resultante de todas las cargas verticales totales que actúan sobre el carril.

#### II.0.11. Descarrilamiento en desvíos y cambios de vía

En los desvíos rectos y específicamente en la sección circular del desvío, no se proporciona peralte en la alineación de la vía ( $\mathrm{z}_{\mathrm{p}}=0$), ni se implementa sobreancho de vía, ni existen curvas de transición suave.

En el evento de que un tren ingresa a un desvío con una velocidad considerablemente superior a la permitida por el radio de curvatura de la alineación horizontal del mismo, el incremento resultante de la fuerza centrífuga puede precipitar un descarrilamiento por remonte de la pestaña.

En los desvíos rectos se aplica la siguiente relación fundamental:
$$z_{p}=z_{t}-I=0 \quad \text{siendo:} \quad z_{t}=11,8 \cdot \frac{V^{2}}{R}$$

donde:
$\mathrm{z}_{\mathrm{t}}$ : Peralte teórico o de equilibrio $=11,8 V^2 / R$ (en mm)
I: Insuficiencia de peralte (expresada en mm)
V: Velocidad de paso del tren a través del desvío (en km/h)
$\mathrm{Z}_{\mathrm{p}}$ : Peralte real de la vía en el desvío (en mm)
R: Radio de curvatura de la trayectoria del desvío (en metros)

A partir de la sustitución de las dos ecuaciones anteriores se concluye:
$$V=0,29 \cdot \sqrt{R \cdot I}$$

Sobre la base de lo anterior y asumiendo $\mathrm{Z}_{p}=0$, es posible calcular la velocidad crítica de descarrilamiento para diversos mecanismos de descarrilamiento, transformándose de la siguiente manera:

**Descarrilamiento por vuelco del vehículo:**
$$V_{der,ov}>\sqrt{R \cdot \frac{g}{3}} \quad V_{der,ov}>\sqrt{\frac{R \cdot g \cdot a}{2 \cdot h_{K B}}}$$

**Descarrilamiento por desplazamiento lateral de la vía:**

Para una vía plenamente estabilizada con traviesas de hormigón:
$$\left(11,8 \cdot \frac{Q}{R}\right) \cdot V_{\text {der,dis }}^{2}+1,5 \cdot Q \cdot V_{\text {der,dis }}-Q \cdot 900-5400=0$$

Para una vía plenamente estabilizada con traviesas de madera:
$$\left(11,8 \cdot \frac{Q}{R}\right) \cdot V_{\text {der,dis }}^{2}+1,5 \cdot Q \cdot V_{\text {der,dis }}-Q \cdot 750-3000=0$$

**Descarrilamiento por remonte de pestaña:**
$$V_{\text {der }, wcl}=\sqrt{\frac{R \cdot g}{4}}$$

Específicamente en contextos de desvíos y cruzamientos, el valor del factor crítico de descarrilamiento $K_{d}>F_{1} / Q_{1}$ debe ser sustancialmente reducido. De conformidad con datos de literatura especializada (Amans y Sauvage, 1969; Profillidis, 1995) debe adoptarse un valor de $K_d = 0,4$. Finalmente, de acuerdo con observaciones y datos experimentales reportados (Franklin, 2018), la evidencia empírica indica que, por consideraciones de seguridad operativa, el cociente $F/Q$ en desvíos y cruzamientos debe limitarse a un valor aproximado de $0,8$.

## Capítulo III. Referencias Bibliográficas y Fuentes Consultadas

- Pyrgidis, C.N. (2022) *Railway Transportation Systems. Design, Construction and Operation*. Second Edition. CRC Press.
- Profillidis, V.A. (2022) *Railway Planning Management and Engineering*. Routledge.
- García Díaz-de-Villegas, J.M. (2007) *Ferrocarriles*. Publicaciones de la E.T.S. Ingenieros de Caminos, Santander.
- López Pita, A. (2006) *Infraestructuras ferroviarias*. Edición UPC.

