---
layout: home
title: 10. Tracción y Adherencia
lang: es
permalink: /es/10Traccion/
nav_order: 10
parent: Inicio
---


# Sistemas de Tracción Ferroviaria y Análisis de Adherencia

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

## Capítulo I Dinámica longitudinal

- Dinámica longitudinal
- Cálculo de perfiles de velocidad
- Cálculo de tiempos de viaje
- Cálculo de energía consumida

### I.1. Introducción

La dinámica longitudinal constituye un campo fundamental en la ingeniería ferroviaria que se ocupa del análisis y la comprensión de las interacciones entre las diferentes fuerzas que actúan sobre un tren durante su movimiento. Estas fuerzas incluyen el esfuerzo de tracción generado por los motores, las fuerzas de frenado, los efectos gravitatorios causados por la topografía, y las fuerzas de inercia asociadas con cambios en la velocidad. Es importante destacar que este análisis se refiere específicamente al movimiento en la dirección longitudinal del tren, diferenciándose claramente de la dinámica vertical que considera movimientos perpendiculares a la dirección de viaje.

El estudio de la dinámica longitudinal permite identificar y desarrollar tres áreas clave de investigación y aplicación práctica en el transporte ferroviario. En primer lugar, es posible calcular con precisión los perfiles de velocidad y los tiempos de viaje en diferentes tramos de línea, considerando las limitaciones técnicas y de infraestructura. En segundo lugar, permite determinar las cargas máximas que pueden ser remolcadas por una locomotora manteniendo los estándares de seguridad establecidos. Finalmente, proporciona las herramientas necesarias para estimar el consumo de energía requerido en diferentes escenarios operativos.
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-004.jpg?height=913&width=1601&top_left_y=668&top_left_x=1895)
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-004.jpg?height=928&width=1644&top_left_y=1685&top_left_x=1895)

### I.2. Planteamiento general

Durante el movimiento de un tren a lo largo de una línea ferroviaria, se presentan simultáneamente distintos tipos de fuerzas que actúan en diferentes direcciones. Podemos clasificarlas en dos categorías principales según su efecto sobre el movimiento del tren. En primer lugar, existen fuerzas que favorecen y contribuyen al desplazamiento del tren en la dirección deseada. El esfuerzo de tracción proporcionado por los motores de tracción constituye la fuerza motriz fundamental que impulsa al tren hacia adelante. Cuando el tren transita por tramos en descenso, la componente gravitatoria también actúa de manera favorable al movimiento, facilitando la aceleración sin requerir esfuerzo del motor.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-005.jpg?height=559&width=1854&top_left_y=2063&top_left_x=883)

Por el contrario, existe un conjunto de fuerzas que se oponen y se resisten al movimiento del tren, limitando su velocidad y su aceleración. El esfuerzo de frenado, que puede ser dinámico o continuo, es controlado por el maquinista para regular la velocidad y lograr detenciones seguras. La resistencia al avance, resultante de múltiples factores como el rozamiento en las ruedas y los elementos mecánicos, la resistencia aerodinámica, y otros, actúa constantemente en contra del movimiento. Adicionalmente, cuando el tren asciende por rampas, la componente gravitatoria actúa como una fuerza resistiva que se opone al avance.

La relación fundamental que describe el movimiento del tren en estas condiciones se expresa mediante la segunda ley de Newton adaptada al contexto ferroviario. Para que la circulación de un vehículo o conjunto de vehículos sea posible, el elemento motor debe proporcionar un esfuerzo de tracción que sea capaz de superar las resistencias que se oponen al movimiento. Esta relación fundamental del movimiento viene dada por la expresión:

$$
E-R=\frac{P}{g} \cdot \gamma
$$

Siendo $P$ el peso de la composición ferroviaria y $\gamma$ la aceleración que el esfuerzo E produciría en la misma.
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-006.jpg?height=559&width=1849&top_left_y=2063&top_left_x=888)

### I.3. Tracción

El esfuerzo de tracción constituye la fuerza motriz fundamental que origina el movimiento del tren, generada por el motor de tracción y posteriormente transmitida a las ruedas motoras a través del sistema de transmisión. En un nivel conceptual más profundo, el par motor que actúa sobre cada eje se convierte en una fuerza horizontal aplicada en la llanta, la cual interactúa con el carril generando una reacción de magnitud igual pero de sentido contrario de acuerdo con la tercera ley de Newton. Es precisamente esta reacción del carril sobre la llanta la que proporciona la tracción necesaria para impulsar la locomotora y toda la composición hacia adelante.

La relación entre potencia, fuerza y velocidad constituye una relación fundamental en el análisis de sistemas mecánicos, incluyendo las locomotoras. Esta relación se expresa mediante la siguiente ecuación:

$$
\operatorname{Pot}(\text { watt })=F(\text { Newton }) \cdot v(m / s)
$$

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-007.jpg?height=1147&width=3540&top_left_y=1518&top_left_x=4)

En la práctica del transporte ferroviario, se utilizan diferentes unidades de medida que se han normalizado a lo largo de la historia del ferrocarril. En relación a la potencia, se emplea habitualmente el kilovatio (kW), siendo el rango típico para la potencia total de las locomotoras de entre 3100 kW y 5600 kW aproximadamente, aunque históricamente también se utilizan caballos de vapor (CV), donde la equivalencia es de 1 CV = 750 W. Para el esfuerzo de tracción o fuerza, las unidades más comunes son los decanewtonios (daN) o kilogramos-fuerza (Kg), con la equivalencia de 1 Kg = 1 daN (aproximadamente 9,8 N). La velocidad se expresa comúnmente en kilómetros por hora (km/h), siendo la equivalencia con el sistema internacional 1 km/h = (1/3.6) m/s.

Para facilitar los cálculos prácticos en las operaciones ferroviarias, se han desarrollado relaciones directas entre estas magnitudes en las unidades de uso corriente:

$$
\begin{gathered}
F(d a N)=100 \cdot 3,6 \cdot \operatorname{Pot}(k W) / v(k m / h) \\
F(K g)=270 \cdot \operatorname{Pot}(C V) / v(k m / h)
\end{gathered}
$$

- El diagrama esfuerzo-velocidad constituye una herramienta gráfica de enorme utilidad que permite visualizar y analizar la capacidad de tracción disponible de un tren en función de su velocidad. A partir de este diagrama, es posible comprender las limitaciones operacionales y diseñar estrategias de conducción óptimas.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-009.jpg?height=1706&width=3120&top_left_y=907&top_left_x=276)

- Las características fundamentales de este diagrama muestran que el esfuerzo de tracción disponible presenta un comportamiento variable según las condiciones operacionales. El esfuerzo de tracción alcanza sus valores máximos cuando el tren se encuentra a bajas velocidades, lo cual es especialmente relevante durante las fases de arranque y aceleración inicial. Por el contrario, con el incremento de la velocidad, el esfuerzo disponible disminuye de forma inversamente proporcional, siendo limitado principalmente por la potencia disponible en el motor de tracción. Adicionalmente, cuando se reduce el número de motores disponibles en la composición, la potencia total y por tanto los esfuerzos máximos que pueden alcanzarse también se ven significativamente reducidos.

Considérese como ejemplo la máquina 252 equipada con un único grupo motor de 2.800 kW:
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-010.jpg?height=922&width=2016&top_left_y=1576&top_left_x=802)

### I.4. Adherencia

La adherencia constituye un concepto fundamental en la ingeniería ferroviaria que describe la capacidad de las ruedas del tren para mantener contacto con el carril sin deslizamiento. Esta propiedad es crítica para la operación segura y eficiente de los trenes, especialmente durante las maniobras de arranque, aceleración y frenado. Es importante destacar que el esfuerzo máximo de tracción que puede ser transmitido desde la locomotora al carril no puede superar el que provocaría el patinado de las llantas sobre el carril.

El fenómeno de la adherencia se basa en el principio de que existe una interacción entre la rueda y el carril que genera una fuerza de fricción. Este apoyo sin que exista deslizamiento de la rueda sobre el carril constituye la adherencia, que presenta una característica importante: será tanto mayor cuanto mayor sea el peso que apoya sobre el carril. De esta forma, la adhesión está directamente relacionada con la masa de los ejes motores de la locomotora.

Para que se mantenga la adherencia, debe cumplirse la siguiente condición:

$$F \leq \phi \cdot P_{a d h}$$

donde $\phi$ es el llamado coeficiente de adherencia y $P_{a d h}$ es el peso adherente, es decir, el peso de los ejes motores de la locomotora.

Si durante la operación se produce la condición $F > \phi \cdot P_{a d h}$, se interrumpe la adherencia y la rueda comienza a deslizar sobre el carril. En esta situación, el coeficiente de fricción disminuye a un valor inferior $\phi' < \phi$, aumentando la aceleración de la rotación del eje y de las masas giratorias asociadas. Este fenómeno se conoce como patinado, y es un evento indeseable en la operación ferroviaria que reduce la eficiencia y puede causar daños.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-011.jpg?height=2146&width=1343&top_left_y=496&top_left_x=2182)

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-012.jpg?height=1955&width=3425&top_left_y=574&top_left_x=65)

La variación del coeficiente de adherencia con la velocidad es un aspecto que ha sido ampliamente estudiado en la literatura ferroviaria. La norma habitualmente utilizada por RENFE, basada en investigaciones extensas, tiene la expresión:

$$
\phi_{v}=\phi_{0} \cdot\left[0.2155+\frac{33}{v+42}\right]
$$

Una expresión alternativa, más sencilla y de uso generalizado en la práctica moderna, es la siguiente:

$$
\phi_{v}=\phi_{0} \cdot \frac{1}{1+0.01 \cdot v}
$$

donde $\phi_{0}$ es la adherencia con el tren parado (condición inicial) y $v$ la velocidad en $\mathrm{km} / \mathrm{h}$.

El esfuerzo máximo de tracción que puede ejercer una locomotora viene limitado por la adherencia disponible. Esta limitación se calcula como el producto del peso adherente por el coeficiente de adherencia:

$$
E_{a d h}=P_{a d h} \cdot \phi_{v}
$$

### I.5. Tracción y adherencia

En el análisis del comportamiento dinámico de una locomotora, es fundamental considerar simultáneamente tanto las limitaciones impuestas por la potencia disponible como las limitaciones impuestas por la adherencia entre las ruedas y el carril. Estos dos factores se comportan de manera distinta con la velocidad y, por tanto, generan diferentes restricciones operacionales en distintos rangos de velocidad.

Cuando se representa gráficamente la relación esfuerzo-velocidad de una locomotora, considerando únicamente la limitación de potencia, la curva resultante no es asintótica al eje de abscisas en las cercanías del origen. Esta observación indica que el esfuerzo de tracción no puede alcanzar valores infinitos a velocidades bajas, como podría parecer teóricamente a partir de la ecuación de potencia. La razón física de esta limitación es que la adherencia disponible entre ruedas y carril proporciona un techo máximo al esfuerzo que puede transmitirse.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-014.jpg?height=1697&width=3225&top_left_y=916&top_left_x=281)

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-015.jpg?height=1697&width=3244&top_left_y=916&top_left_x=281)

En la práctica operacional del tren, es frecuente encontrar zonas de funcionamiento donde el desempeño se ve limitado, no por la potencia disponible sino por la adherencia disponible. Del mismo modo, existen zonas de funcionamiento donde la limitación es principalmente debida a la potencia del motor de tracción. La representación gráfica de estas dos limitaciones en un mismo diagrama esfuerzo-velocidad proporciona claridad operacional.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-016.jpg?height=1706&width=3206&top_left_y=907&top_left_x=281)

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-017.jpg?height=1711&width=3216&top_left_y=902&top_left_x=276)

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-018.jpg?height=1706&width=3211&top_left_y=907&top_left_x=281)

La potencia disponible constituye un compromiso entre dos magnitudes físicas fundamentales: la fuerza de arrastre y la velocidad de movimiento. Sin embargo, para lograr obtener una fuerza de tracción significativa durante maniobras criticas, es necesario disponer de una adherencia suficiente, la cual únicamente puede conseguirse incrementando la masa de los ejes motores de la locomotora. Esta relación entre potencia, fuerza y masa ilustra los compromisos fundamentales en el diseño de locomotoras.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-019.jpg?height=1706&width=3249&top_left_y=907&top_left_x=276)

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-020.jpg?height=1697&width=3244&top_left_y=916&top_left_x=281)

**Interacción entre tracción y adherencia**

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-021.jpg?height=398&width=383&top_left_y=276&top_left_x=1571)

El coeficiente de adherencia ($\phi$) constituye uno de los factores más relevantes y críticos en la operación de transporte de mercancías, donde generalmente se requieren fuerzas de tracción elevadas para remolcar cargas significativas. Para ilustrar la importancia de este parámetro, considérese un ejemplo comparativo: dos locomotoras con idéntica potencia disponible, pero con masas diferentes, presentarán capacidades de remolque significativamente distintas. Específicamente, una locomotora con una masa de 120 toneladas posee una capacidad de remolque de aproximadamente un 50% superior a otra con una masa de 80 toneladas, a pesar de tener ambas la misma potencia nominal.

$$
E_{a d h}=P_{a d h} \cdot \phi_{v}
$$

Un concepto importante que surge de este análisis es que una máquina con mayor masa puede ejercer un esfuerzo de tracción superior a bajas velocidades en comparación con otra máquina que dispone de más potencia pero tiene menos masa. Esta capacidad es especialmente crítica durante las fases de arranque y en condiciones de pendientes pronunciadas.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-021.jpg?height=1147&width=1849&top_left_y=1361&top_left_x=1232)

Se presentan dos ejemplos prácticos de locomotoras en servicio que ilustran esta relación:

- **Máquina 251**: Potencia de 4.650 kW, masa de 138 toneladas
- **Máquina 252**: Potencia de 5.600 kW, masa de 92 toneladas

Estos ejemplos demuestran cómo, a pesar de que la máquina 252 dispone de mayor potencia, la máquina 251 con mayor masa puede lograr esfuerzos de tracción superiores en ciertos rangos de velocidad debido a su mayor peso adherente.

### I.6. Resistencias al avance

El movimiento de un tren a lo largo de una línea ferroviaria se ve obstaculizado por la presencia de múltiples fuerzas resistivas. Históricamente, se ha identificado que los orígenes de estas resistencias residen en características específicas del material rodante y de la infraestructura de la línea, siendo su magnitud susceptible de ser influenciada por condiciones meteorológicas variables. En lo que respecta a las características de los vehículos, las resistencias tienen su origen en múltiples fuentes: el rozamiento existente en los cojinetes y cajas de grasa, la resistencia al movimiento rotatorio de las ruedas sobre el carril, la resistencia debida a la deformación del carril bajo el peso del tren, y las pérdidas por fricción en diversos elementos mecánicos. Adicionalmente, no puede obviarse la resistencia del aire, la cual presenta una dependencia explícita respecto a la velocidad relativa entre el tren y el viento exterior.

La experiencia práctica demuestra consistentemente que la suma de las resistencias individuales calculadas de forma independiente no proporciona un resultado coincidente con la resistencia total al avance medida experimentalmente. Por esta razón, en la práctica ingenieril las diferentes resistencias se combinan mediante expresiones empíricas de naturaleza parabólica, las cuales presentan dependencia respecto a la velocidad. Para el caso de material motor, se adoptan expresiones donde aparecen términos lineales y cuadráticos en velocidad:

$$
r_{a}(d a N / t)=a+b \cdot v+c \cdot v^{2}
$$

Para el caso de vehículos remolcados, ya sean coches de viajeros o vagones de mercancías, la resistencia específica generalmente se evalúa a partir de una expresión general sin término lineal en velocidad:

$$
r_{a}(d a N / t)=a+c \cdot v^{2}
$$

Los componentes de la resistencia al avance pueden clasificarse en tres categorías principales según su origen físico:

- **Resistencias mecánicas (a)**: Esta categoría engloba la resistencia a la rodadura, incluyendo la fricción con el carril, la deformación del carril bajo carga, y otros efectos de rodadura, así como la resistencia debida a los rozamientos internos del sistema, especialmente en las cajas de grasa y otros cojinetes.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-024.jpg?height=464&width=1080&top_left_y=635&top_left_x=2273)

- **Resistencias debidas a la entrada de aire (b)**: El movimiento del tren a través de la atmósfera requiere desplazar el aire que se encuentra en su camino, generando una resistencia adicional.

- **Resistencias aerodinámicas (c)**: Estas incluyen la resistencia de presión resultante del choque del frontal del tren y la succión aerodinámica en la cola, así como la resistencia de fricción generada por el flujo de aire sobre la superficie del tren.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-024.jpg?height=631&width=1319&top_left_y=1743&top_left_x=2206)

La resistencia específica total al avance se expresa entonces como:

$$
r_{a}(d a N / t)=a+b \cdot v+c \cdot v^{2}
$$

| TREN | Masa t | a | b | c |
| :--- | :--- | :--- | :--- | :--- |
| Locomotora BB | 80 | 1,25 | 0,01 | $3,75 \cdot 10^{-4}$ |
| Locomotora CC | 120 | 1,2 | 0,01 | $2,50 \cdot 10^{-4}$ |
| 2 locomotoras +6 coches | 400 | 1,15 | 0,00975 | $2,87 \cdot 10^{-4}$ |
| Clásico viajeros | Variable | 1,5-2 | 0 | $2,22 \cdot 10^{-4}$ |
| Mercancías de bogies | Variable | 1,5-2 | 0 | $2,50 \cdot 10^{-4}$ |
| Clásico mercancías | Variable | 1,5-2 | 0 | $6,25 \cdot 10^{-4}$ |
| Alaris | 177 | 1,5-2 | 0 | $6,25 \cdot 10^{-4}$ |
| TGV SudEst | 418 | 0,562 | 0,00739 | $1,28 \cdot 10^{-4}$ |
| TGV Duplex | 424 | 0,637 | 0,00755 | $1,26 \cdot 10^{-4}$ |
| ICE 3 Regional | 231 | 0,735 | 0,00654 | $1,47 \cdot 10^{-4}$ |

Resistencias al avance

$$
r_{a}(d a N / t)=a+b \cdot v+c \cdot v^{2}
$$

| TREN | Masa t | a | b | c |
| :--- | :--- | :--- | :--- | :--- |
| S100 | 421 | 0,603 | $8 \cdot 10^{-3}$ | $1,120 \cdot 10^{-4}$ |
| S102 | 341 | 0,846 | $10 \cdot 10^{-3}$ | $1,149 \cdot 10^{-4}$ |
| S103 | 485 | 0,736 | $7 \cdot 10^{-3}$ | $1,112 \cdot 10^{-4}$ |
| S104 | 245 | 1,337 | $10 \cdot 10^{-3}$ | $1,204 \cdot 10^{-4}$ |
| S120 | 275 | 0,819 | $3 \cdot 10^{-3}$ | $1,164 \cdot 10^{-4}$ |
| S130 | 343 | 0,831 | $7 \cdot 10^{-3}$ | $1,161 \cdot 10^{-4}$ |
| S730 (eléctrico) | 354 | 0,903 | $6 \cdot 10^{-3}$ | $1,553 \cdot 10^{-4}$ |
| S730 (diésel) | 354 | 0,903 | $1,4 \cdot 10^{-2}$ | $1,508 \cdot 10^{-4}$ |

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-027.jpg?height=1498&width=2828&top_left_y=772&top_left_x=400)

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-028.jpg?height=1789&width=2660&top_left_y=732&top_left_x=422)

**Resistencias por características de la infraestructura ferroviaria**

La influencia de la vía en la generación de resistencias al avance se concretiza fundamentalmente en las características del trazado geométrico de la línea, siendo especialmente significativa la presencia de tramos curvos y de rampas o pendientes. Estos elementos de infraestructura generan resistencias adicionales que deben ser consideradas en los cálculos de dinámica longitudinal.

**Resistencia debida a las curvas:**

La resistencia originada por el paso del tren a través de secciones curvas de la línea se genera como resultado de tres mecanismos principales: la solidaridad de las ruedas y los ejes, que obliga a los vehículos a seguir la curvatura de la vía; el paralelismo de los ejes de los distintos vehículos, que genera fuerzas de fricción adicionales contra el carril; y la fuerza centrífuga derivada de la cinemática del movimiento circular. La expresión general que describe esta resistencia es:

$$
F_{c}(d a N / t)=a \cdot f \cdot \frac{P}{R}+\frac{P \cdot f}{2 \cdot R} \cdot \sqrt{a^{2}+b^{2}}+\frac{P \cdot f}{R \cdot g} \cdot\left(V^{2}-V_{0}^{2}\right)
$$

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-029.jpg?height=560&width=727&top_left_y=1800&top_left_x=66)

En la práctica operacional española, la administración de infraestructuras (Adif) emplea expresiones simplificadas específicas para el cálculo de resistencias en curvas, diferenciando según el ancho de vía:

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-029.jpg?height=426&width=870&top_left_y=1929&top_left_x=907)

$$
r_{c}(d a N / t)=\frac{600}{R(m)} \quad \text{(ancho estándar)} \quad r_{c}(d a N / t)=\frac{800}{R(m)} \quad \text{(ancho ibérico)}
$$

**Resistencia debida a las rampas:**

Cuando un tren debe circular por un tramo inclinado hacia arriba (rampa), debe realizarse trabajo adicional para incrementar la energía potencial del tren. Considerando el esquema habitual que representa una rampa de pendiente $i=\operatorname{tg}(\alpha)$, es posible deducir analíticamente el esfuerzo suplementario que dicha rampa genera durante la circulación de un vehículo. La deducción de esta resistencia es inmediata a partir de consideraciones de equilibrio de fuerzas:

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-030.jpg?height=658&width=1222&top_left_y=1365&top_left_x=513)

$$
r(d a N / t)=\frac{P \cdot i}{P}=i$$

Por otro lado, en aplicaciones prácticas de cálculo, se utiliza el concepto de perfil ficticio (L') o rampa ficticia equivalente, que realiza la consideración conjunta de la resistencia en curva y la resistencia en rampa. Esta magnitud viene dada por la expresión:

$$
L^{\prime}=\frac{800}{R(m)}+i$$

Esta formulación simplificada permite realizar análisis unificados de las características del trazado geométrico, facilitando el cálculo computacional.

Resistencias al avance
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-031.jpg?height=1166&width=3229&top_left_y=582&top_left_x=143)

| $\mathrm{i}(\mathrm{mm} / \mathrm{m})$ | $\mathrm{r}(\mathrm{daN} / \mathrm{t})$ |
| :---: | :---: |
| 2 | 2 |
| 12 | 12 |
| 20 | 20 |
| 35 | 35 |

$$
r(d a N / t)=\frac{P \cdot i}{P}=i
$$

**Resistencia total a velocidad constante:**

Cuando un tren circula a velocidad constante, la resistencia específica total que debe vencerse constituye la suma de todas las resistencias parciales previamente descritas:

$$
r_{t}(k g / t)=r_{a}+r_{c}+r_{i} \rightarrow R_{t}(k g)=R_{a}+R_{c}+R_{i}
$$

**Resistencia de inercia:**

La resistencia de inercia constituye una resistencia que se opone a todo cambio de velocidad del tren, independientemente de su sentido (aceleración o deceleración). Esta resistencia presenta una característica fundamental: su magnitud depende directamente de la masa total del tren y de la magnitud de la aceleración (o deceleración) que se intenta lograr. Matemáticamente, si se define $a$ como la aceleración expresada en cm/s², la resistencia específica de inercia se calcula mediante la siguiente relación:

$$
\begin{aligned}
R_{i n}=\frac{P}{g} \cdot \frac{d v}{d t}=\frac{P(\mathrm{~kg})}{g\left(\mathrm{~cm} / \mathrm{sg}^{2}\right)} \cdot a\left(\mathrm{~cm} / \mathrm{sg}^{2}\right)=P \cdot a(\mathrm{~kg}) \\
r_{i n}=\frac{R_{i n}}{P}=\frac{P \cdot a}{P}=a(\mathrm{~kg} / \mathrm{t})
\end{aligned}
$$

Cuando se integran todos estos efectos resistivos en un diagrama esfuerzo-velocidad que representa el comportamiento del tren bajo diferentes condiciones de operación, se obtiene una representación completa del desempeño dinámico disponible:

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-033.jpg?height=1706&width=3115&top_left_y=907&top_left_x=281)

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-034.jpg?height=1711&width=3115&top_left_y=902&top_left_x=281)

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-035.jpg?height=1711&width=3115&top_left_y=902&top_left_x=281)

### I.7. Curva de tracción

El proceso de movimiento de un tren desde condiciones de reposo constituye un proceso dinámico complejo en el cual se producen transiciones entre diferentes regímenes de funcionamiento. Inicialmente, el movimiento comienza a velocidad nula desde el punto A, evolucionando a lo largo de la curva de adherencia disponible conforme el tren aumenta progresivamente su velocidad, y alcanzando el punto B donde la limitación transitoria es la adherencia. Posteriormente, la velocidad continúa aumentando siguiendo la curva de limitación por potencia disponible, transitando desde el punto B hacia el punto C. En el punto C, la curva de esfuerzo disponible (tanto por adherencia como por potencia) intersecta con la curva de resistencia global del tren que incluye todos los términos resistivos. En este punto de intersección, el tren alcanza su velocidad máxima posible para las condiciones operacionales dadas.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-036.jpg?height=1644&width=3134&top_left_y=974&top_left_x=276)

### I.8. Dinámica en rampas y pendientes

El comportamiento dinámico de un tren en un trazado montañoso presenta características significativamente diferentes a las del movimiento en una vía horizontal. La presencia de pendientes y rampas introduce modificaciones en el balance de fuerzas que afectan fundamentalmente al desempeño operacional del tren.

**Comportamiento en rampas (movimiento ascendente):**

Cuando un tren circula hacia arriba por una rampa, la componente gravitatoria del peso actúa de manera directamente opuesta al movimiento, comportándose como una fuerza resistiva adicional que se suma a la resistencia al avance natural del tren. Consecuentemente, para mantener una velocidad constante en una rampa, el tren requiere un esfuerzo de tracción significativamente mayor que el necesario en un tramo horizontal equivalente.

La velocidad de equilibrio para una rampa determinada se define como la máxima velocidad que puede alcanzarse en esa rampa específica, manteniendo un esfuerzo de tracción igual a la resistencia total (incluyendo la componente gravitatoria). El concepto de rampa crítica es especialmente importante: se define como la mayor pendiente en la cual el tren es capaz de alcanzar su velocidad máxima teórica. Para rampas superiores a la rampa crítica, la velocidad máxima alcanzable será inferior a la velocidad máxima nominal del tren.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-037.jpg?height=1620&width=2265&top_left_y=921&top_left_x=1227)

**Comportamiento en pendientes (movimiento descendente):**

En contraste con las rampas, cuando un tren circula hacia abajo por una pendiente, la componente gravitatoria del peso actúa en la misma dirección del movimiento, comportándose efectivamente como una fuerza motriz adicional. Esta circunstancia reduce significativamente el requerimiento de esfuerzo de tracción necesario para mantener una velocidad determinada.

El concepto de pendiente de equilibrio tiene particular importancia operacional: se define como aquella pendiente en la cual el tren en una condición de marcha sin tracción (en deriva) mantiene precisamente su velocidad máxima. En pendientes superiores a la pendiente de equilibrio, el tren tiende a acelerar, requiriendo el empleo de frenos para mantener la velocidad máxima autorizada. En pendientes inferiores a la pendiente de equilibrio, el tren requiere tracción adicional para mantener la velocidad máxima.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-038.jpg?height=1839&width=2107&top_left_y=807&top_left_x=1232)

### I.9. Resistencias en el arranque

En la operación práctica del tren, la fase de arranque desde el reposo presenta características significativamente distintas a las del movimiento en marcha normal. Si se aplicaran únicamente las expresiones estándar de resistencia al avance evaluadas en velocidad cero (v=0), los valores resultantes no representarían la realidad experimental observada. Empíricamente, la resistencia requerida para iniciar el movimiento de un tren es notablemente mayor que la predicha por tales modelos teóricos.

Se ha determinado mediante estudios prácticos que para arrancar un vehículo ferroviario es necesario un esfuerzo del orden de 10 Kg/t, significativamente superior al valor típico de 1-1.5 Kg/t que se requiere cuando el tren ya se encuentra circulando en condiciones normales. A esta resistencia de arranque debe añadirse el esfuerzo requerido para imprimir la aceleración inicial al tren (denominada resistencia de inercia), cuya magnitud varía según el tipo de tren considerado:

| Tipo de Tren | Aceleración mínima de arranque |
| :--- | :--- |
| Trenes de mercancías | 2 a 5 cm/s² |
| Trenes de pasajeros convencionales | 8 a 10 cm/s² |
| Automotores y unidades múltiples | 50 a 100 cm/s² |
| Trenes de Alta Velocidad (AVE) | 80 a 100 cm/s² |
| Sistemas de Metro | 110 a 120 cm/s² |

La administración de infraestructuras ferroviaria (Adif) adopta valores estándar para el cálculo de resistencias en el arranque. Para una línea horizontal y recta, la resistencia específica estándar es de 7 daN/t. Esta cifra se compone de dos componentes: 4 daN/t corresponden al esfuerzo mínimo necesario para vencer la resistencia estática e iniciar el movimiento, mientras que los 3 daN/t restantes representan el esfuerzo acelerador requerido para lograr un arranque en tiempo operacionalmente aceptable.

La fase de arranque en rampa constituye el escenario más crítico desde el punto de vista operacional, ya que requiere vencer simultáneamente la resistencia de arranque, la resistencia de inercia y la componente gravitatoria de la rampa. Para facilitar el cálculo práctico y el dimensionamiento de material rodante, se han establecido valores normativos que relacionan la resistencia específica de arranque con la magnitud de la pendiente:

| Resistencia específica al arranque (daN/t) | Pendiente (mm/m) |
| :--- | :--- |
| 7 | <15 |
| 8 | 15-20 |
| 9 | 21-25 |
| 10 | 26-29 |
| 11 | 30-33 |
| 12 | 34-37 |
| 13 | 38-41 |
| 14 | 42-45 |
| 15 | >45 |

Es importante notar que conforme aumenta la magnitud de la rampa, se incrementa proporcionalmente la resistencia específica requerida. Este fenómeno se debe a que los enganches y acopladores entre coches o vagones experimentan mayores tensiones estructurales, generando resistencias adicionales asociadas a la deformación elástica de estos elementos.

La adherencia disponible en el arranque constituye una limitación física fundamental que no puede ser excedida sin producir patinado de las ruedas. Esta limitación se expresa mediante:

$$
E_{\phi_{0}}(k g) \leq 1000 \cdot \phi_{0} \cdot P_{\text {locomotora }}(t)
$$

Simultáneamente, el esfuerzo total que debe vencerse para superar todas las resistencias en el arranque viene determinado por:

$$
E(k g)=\left(P_{l o c}+P_{r e m o l}\right) \cdot\left(r_{a}+i\right)
$$

Para garantizar que el arranque pueda realizarse sin producir patinado, es imprescindible que se verifique:

$$
\left(P_{l o c}+P_{r e m o l}\right) \cdot\left(r_{a}+i\right) \leq 1000 \cdot \phi_{0} \cdot P_{l o c}(t)
$$

A través de esta condición es posible calcular la carga máxima remolcable por cualquier locomotora en condiciones críticas de arranque.

| CUADRO 9.2 CARGA REMOLCABLE EN EL ARRANQUE PARA DOS SITUACIONES DE REFERENCIA |  |  |
| :--- | :--- | :--- |
| Datos | Tren de viajeros | Tren de mercancías |
| Locomotora | BB (corriente continua) | BB (monofísica) |
|  | de 80 t | de 84 t |
| Rampa | 8\% | 10\% |
| Radio de curva |  | 400 m |
| Resistencia |  |  |
| especifica al arranque |  |  |
|  | 2da N/t | $1,5 \mathrm{da} \mathrm{N} / \mathrm{t}$ |
| Aceleración | $8 \mathrm{~cm} / \mathrm{seg}^{2}$ | $2 \mathrm{~cm} / \mathrm{seg}^{2}$ |
| Coeficiente de |  |  |
| Cálculos |  |  |
| Esfuerzo máximo al arranque | $80 \mathrm{t} \times 0,2=16.000 \mathrm{daN}$ | $84 \mathrm{t} \times 0,35=29.400 \mathrm{daN}$ |
|  |  |  |
| Esfuerzo especifico al arranque <br> t | 2 (arranque) + |  |
|  |  | $\begin{gathered} 1,5 \text { (arranque) + } \\ 2 \text { (aceleración) + } \\ 10 \text { (rampa) + } 2 \text { (curva) } \\ =15,5 \text { da N/t } \end{gathered}$ |
|  |  |  |
| Carga total al arranque (Q + L) (material remolcado | $(\mathrm{Q}+\mathrm{L})=\frac{16.000}{18} \approx 880 t$ | $(\mathrm{Q}+\mathrm{L})=\frac{29.400}{15,5}=1.896 \mathrm{t}$ |
| + locomotora) |  |  |
| Carga arrancable (Q) por la locomotora |  |  |
|  | $\mathrm{Q}=880-80 \mathrm{t}=800 \mathrm{t}$ | $Q=1.896-84=\sim 1.800 t$ |

### I.10. Esfuerzo en gancho

En el contexto de la dinámica ferroviaria, el esfuerzo en gancho se define técnicamente como la fuerza neta disponible en el gancho de acoplamiento de una locomotora. Esta magnitud se calcula como el esfuerzo total proporcionado por el motor de tracción, menos la cantidad de esfuerzo que la locomotora necesita para superar las resistencias que actúan sobre su propia estructura considerada como un vehículo adicional en la composición.

Los vehículos ferroviarios están provistos de enganches o acoples diseñados para su interconexión mecánica. Estos sistemas de acoplamiento presentan limitaciones de resistencia estructural determinadas por criterios de ingeniería. La resistencia característica de estos enganches oscila típicamente entre 70 y 85 toneladas. Para evitar exceder el límite elástico del material y asegurar una vida útil adecuada, se adoptan coeficientes de seguridad de 2.4 en el diseño. Consecuentemente, los esfuerzos admisibles en tracción que pueden ser aplicados de forma sostenida son:

- Para enganches nominales de 70 toneladas: esfuerzo admisible de 30 toneladas
- Para enganches nominales de 85 toneladas: esfuerzo admisible de 36 toneladas

Para garantizar que los enganches no se rompan durante la operación, debe cumplirse la siguiente condición en el momento del arranque:

$$
30 \mid 36 \cdot 10^{3} \geq P_{\text {remol }} \cdot\left(r_{a}+i\right)
$$

### I.11. Carga remolcable

El dimensionamiento de las composiciones ferroviarias requiere conocer la capacidad de remolque máxima de las locomotoras disponibles. Esta capacidad es función de múltiples variables, incluyendo el tipo de vehículos remolcados, la masa unitaria, la longitud de los mismos y su velocidad máxima permitida. En el contexto del transporte de mercancías, estos parámetros adquieren importancia crítica, especialmente cuando se consideran condiciones de arranque en rampas pronunciadas. Se presentan a continuación las características técnicas de los diferentes tipos de vagones, seguidas de las capacidades de remolque específicas para diferentes locomotoras bajo distintas condiciones de operación (pendiente del 12‰ y del 18‰):

**MERCANCÍAS (12 \%o)**

| LOCOM. | v. мáх. | PESO | LONG. | MÁX. CARGA REMOLCADA | ABIERTOS | CERRADOS | PLATAFORMAS |  |  | TOLVAS | CISTERNAS |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
|  |  |  |  |  |  |  | NORMALES | COCHES | CONTENEDORES |  |  |
| 601.E | 120 | 130 | 22,41 | 2125 | 371 | 509 | 642 | 1318 | 470 | 421 | 398 |
| 601.D | 120 | 130 | 22,41 | 2159 | 377 | 517 | 653 | 1340 | 478 | 427 | 405 |
| 335 | 120 | 123 | 23,02 | 1890 | 332 | 454 | 572 | 1171 | 420 | 376 | 356 |
| 269.85 | 100 | 176 | 17,27 | 2220 | 374 | 516 | 652 | 1345 | 476 | 425 | 403 |
| 252 | 220 | 90 | 20,40 | 1200 | 214 | 291 | 365 | 741 | 269 | 242 | 229 |
| 253 | 140 | 87 | 18,90 | 1530 | 271 | 371 | 467 | 956 | 343 | 307 | 291 |

MERCANCÍAS $(18 \%)$

| LOCOM. | v. MÁx. | PESO | LONG. | MÁX. CARGA REMOLCADA | ABIERTOS | CERRADOS | PLATAFORMAS |  |  | TOLVAS | CISTERNAS |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
|  |  |  |  |  |  |  | NORMALES | COCHES | CONTENEDORES |  |  |
| 601.E | 120 | 130 | 22,41 | 1517 | 264 | 361 | 453 | 923 | 334 | 299 | 283 |
| 601.D | 120 | 130 | 22,41 | 1522 | 265 | 362 | 455 | 926 | 335 | 300 | 284 |
| 335 | 120 | 123 | 23,02 | 1340 | 235 | 320 | 401 | 814 | 296 | 266 | 252 |
| 269.85 | 100 | 176 | 17,27 | 1580 | 262 | 360 | 453 | 929 | 332 | 297 | 282 |
| 252 | 220 | 90 | 20,40 | 880 | 158 | 213 | 265 | 533 | 197 | 178 | 169 |
| 253 | 140 | 87 | 18,90 | 1080 | 192 | 261 | 327 | 664 | 242 | 217 | 206 |

Índice

- Dinámica longitudinal
- Cálculo de perfiles de velocidad
- Cálculo de tiempos de viaje
- Cálculo de energía consumida

## Capítulo II Cálculo de perfiles de velocidad

La velocidad real de recorrido de un tren a lo largo de una línea ferroviaria resulta de la combinación de múltiples factores interconectados. Entre los más significativos se encuentran la capacidad aceleración y frenado disponibles en el material rodante, el tipo específico de tren considerado, la tecnología de tracción empleada (diésel, eléctrica de corriente alterna o continua), las características geométricas del trazado (pendientes, curvas, radio de curvatura), las condiciones meteorológicas, y las restricciones reglamentarias. 

Bajo condiciones operacionales ideales, el maquinista responsable del tren dispone de ciertos márgenes de flexibilidad operativa que le permiten modular la marcha del tren. Estos márgenes pueden ser explotados de manera estratégica para optimizar el consumo de energía, balanceando velocidades, aceleraciones y deceleraciones de forma inteligente. Sin embargo, es necesario considerar que existen limitaciones de velocidad imperativas que deben ser respetadas bajo todas las circunstancias operacionales. Estas limitaciones se establecen en aparatos de vía especiales, túneles de secciones reducidas (para evitar efectos aerodinámicos adversos como el efecto émbolo), puentes metálicos con restricciones, y zonas con obstáculos próximos a la infraestructura ferroviaria.
Una herramienta fundamental e imprescindible en la ingeniería ferroviaria moderna es el diagrama de velocidades o perfiles de velocidad. Estos diagramas se representan habitualmente en coordenadas velocidad-espacio, donde el eje de abscisas representa la distancia recorrida a lo largo de la línea ferroviaria y el eje de ordenadas representa la velocidad del tren en cada punto. Estos diagramas adquieren especial utilidad cuando se emplean conjuntamente con un diagrama adicional que muestra las pendientes y rampas del trazado, permitiendo visualizar la influencia mutua entre la topografía y el perfil de velocidades.

A partir del análisis cuidadoso de los diagramas de velocidades es posible estudiar y predecir múltiples parámetros de interés operacional y de confort. Entre estos se encuentran los esfuerzos transmitidos a la infraestructura ferroviaria por el paso del tren bajo diferentes regímenes dinámicos, así como parámetros de confort para los viajeros relacionados con las aceleraciones y deceleraciones producidas. El análisis subsecuente describe en detalle los elementos constitutivos de un diagrama de velocidades representativo:

### II.1. Perfiles de velocidad

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-048.jpg?height=2015&width=2752&top_left_y=597&top_left_x=476)

En el diagrama representado es posible identificar los siguientes elementos estructurales y características técnicas:

1. El eje horizontal del diagrama representa la distancia recorrida expresada en kilómetros.
2. El eje vertical del primer gráfico muestra la velocidad del tren en kilómetros por hora, con una escala secundaria en metros por segundo.
3. El eje vertical del segundo diagrama subordinado representa la inclinación del trazado expresada en milésimas (mm/m), siendo los valores positivos indicadores de rampas (ascensos) y los negativos indicadores de pendientes (descensos).
4. La velocidad máxima nominal del tren considerado es de 160 km/h.
5. El límite de velocidad de la vía presenta variaciones a lo largo del recorrido, comenzando en 100 km/h, incrementándose posteriormente a 140 km/h y luego a 200 km/h en diferentes segmentos.
6. En el kilómetro 15 se localiza una estación ferroviaria donde la velocidad de entrada reglamentaria es de 60 km/h. En esta simplificación del problema, la velocidad de acercamiento es independiente de la vía específica utilizada dentro de la estación.
7. La velocidad de salida de la estación es de 40 km/h.
8. En el kilómetro 28 existe una restricción especial que limita la velocidad a 80 km/h.
9. En el diagrama de pendientes se pueden identificar dos tramos de pendiente descendente con inclinaciones de 5 y 8 milésimas respectivamente. Dependiendo de la capacidad de frenado disponible, estas pendientes pueden imponer restricciones adicionales de velocidad.
10. Existen dos tramos con rampa ascendente de 40 milésimas cada uno.

**Análisis de las fases del movimiento en el diagrama:**

11. En la fase inicial, el tren acelera desde velocidad nula hasta alcanzar el límite de velocidad reglamentario de 100 km/h impuesto por la vía.
12. Una vez alcanzado el límite, el tren mantiene velocidad constante durante un segmento.
13. Cuando la limitación de velocidad de la vía se incrementa, el tren vuelve a acelerar hasta el nuevo límite de 140 km/h. Es importante notar que la aceleración comienza después del punto de limitación debido a que este limite se aplica a la totalidad del tren (representado por la cabeza del mismo). El maquinista debe esperar hasta que la cola del tren haya rebasado completamente el punto de cambio de limitación antes de iniciar la aceleración.
14. El tren circula nuevamente a velocidad constante durante el siguiente segmento.
15. En este tramo, el tren acelera hasta alcanzar su límite de velocidad nominal de 160 km/h, que es inferior al límite de velocidad de la vía.
16. Se mantiene nuevamente el movimiento a velocidad constante.
17. En este punto inicia el proceso de frenado. La ubicación exacta de este punto depende de varios factores que se analizan posteriormente.
18. En el punto de entrada a un tramo donde debe reducirse la velocidad, el tren debe estar circulando a la velocidad requerida para ese nuevo segmento. Para lograrlo, debe calcularse adecuadamente el punto de inicio del frenado mediante la intersección de la curva de deceleración con el perfil de velocidades.

19. El tren continúa a velocidad constante durante este segmento posterior.
20. El tren ejecuta una deceleración hasta alcanzar velocidad de parada (aquí se debería incluir el tiempo de espera programado en la estación).
21. Tras la parada, el tren acelera nuevamente a la velocidad de salida autorizada de la estación.
22. Se mantiene una velocidad constante durante el segmento subsecuente.
23. El tren vuelve a acelerar hasta alcanzar su límite de velocidad nominal, manteniendo luego esta velocidad constante.
24. En el segmento de subida (rampa), el tren experimenta una disminución de velocidad porque el esfuerzo de tracción disponible no es suficiente para compensar la suma de la resistencia al avance más la componente gravitatoria de la rampa. Este efecto es gradual hasta alcanzar una velocidad de equilibrio estable.
25. Cuando finaliza la rampa, el tren puede acelerar nuevamente.
26. Al final del recorrido, el tren reduce su velocidad nuevamente debido a limitaciones de velocidad impuestas por la configuración de la vía en esa zona.

#### II.1.1. Proceso de aceleración

Durante los segmentos de aceleración de un viaje típico, el tren utiliza la totalidad de las fuerzas tractoras disponibles proporcionadas por el motor de tracción. Simultáneamente, todas las resistencias que se han analizado anteriormente (resistencia al avance, resistencias en curvas, resistencias inerciales) trabajan en contra de este esfuerzo de tracción, reduciendo la aceleración neta resultante.

Un aspecto crítico del análisis es que tanto el esfuerzo de tracción como la aceleración resultante no permanecen constantes durante el proceso. El esfuerzo de tracción varía con la velocidad (limitado tanto por potencia como por adherencia), y la resistencia también varía, principalmente como función cuadrática de la velocidad. Esta variabilidad continua implica que la aplicación de la formulación clásica de Newton para aceleraciones constantes sería inapropiada. El problema requiere, por tanto, ser formulado y resuelto mediante ecuaciones diferenciales que capturen adecuadamente la naturaleza variable de estas fuerzas.

Una consideración adicional importante es que el tren no puede ser tratado como una masa puntual simple. El tren contiene en su interior una cantidad significativa de masas giratorias, incluyendo las ruedas, ejes, y rotores de motor en los vehículos motorizado. Estas masas giratorias contribuyen a una inercia efectiva superior a la masa simple del material rodante considerado como estructura. Esta inercia adicional se captura mediante la introducción de un factor correctivo denominado "masa ficticia":

$$
M^{\prime}=M \cdot f_{p}
$$

El factor $f_p$ presenta valores típicos entre 1.10 y 1.30 para material motor (vehículos con propulsión), y entre 1.02 y 1.09 para material remolcado (vehículos pasivos sin propulsión).

La ecuación fundamental del movimiento, modificada para incorporar la masa ficticia, se expresa como:

$$
F-R=\frac{P}{g} \cdot \gamma \rightarrow F(v)-R(v)=M^{\prime} \cdot \frac{d v}{d t} \rightarrow F(v)-R(v)=M \cdot f_{p} \cdot \frac{d v}{d t}
$$

Asumiendo el tren como un objeto puntual cuya masa se concentra en un único punto, y realizando transformaciones matemáticas apropiadas, la ecuación anterior se puede reformular:

$$
\frac{(F(v)-R(v))}{v}=M \cdot f_{p} \cdot \frac{d v}{d t} \cdot \frac{d t}{d s} \rightarrow \frac{(F(v)-R(v))}{v}=M \cdot f_{p} \cdot \frac{d v}{d s}
$$

Esta ecuación diferencial se puede transformar adicionalmente para obtener relaciones que permitan calcular el tiempo y la distancia requeridos para pasar de una velocidad inicial a una final:

$$
\frac{d t}{d v}=M \cdot f_{p} \cdot \frac{1}{F(v)-R(v)} \quad \frac{d s}{d v}=v \cdot M \cdot f_{p} \cdot \frac{1}{F(v)-R(v)}
$$

Mediante la integración de estas expresiones diferenciales entre la velocidad inicial $v_0$ y la velocidad final $v_1$, es posible obtener el tiempo y la distancia requeridos para la transición entre estos estados:

$$
t=\int_{v_{0}}^{v_{1}} M \cdot f_{p} \cdot \frac{1}{F(v)-R(v)} \mathrm{d} v \quad s=\int_{v_{0}}^{v_{1}} v \cdot M \cdot f_{p} \cdot \frac{1}{F(v)-R(v)} \mathrm{d} v
$$

En la práctica operacional e ingenieril, estas integrales analíticas no siempre pueden resolverse de forma cerrada. Por ello, se adopta un enfoque numérico que divide el intervalo de velocidad total en múltiples sub-intervalos (típicamente de 1 m/s o menor), calculando para cada sub-intervalo los parámetros requeridos. La metodología es la siguiente:
- **Paso 1**: Se calcula la velocidad media del sub-intervalo.
- **Paso 2**: Utilizando esta velocidad media, se determinan el esfuerzo adherente disponible y la resistencia total.
- **Paso 3**: La diferencia entre el esfuerzo de tracción y la resistencia proporciona la fuerza neta disponible para acelerar el tren.
- **Paso 4**: Empleando la formulación de Newton con los valores calculados, se resuelve cada sub-intervalo de manera iterativa.

#### II.1.2. Proceso de aceleración: ejemplo práctico

Para ilustrar la aplicación de estos conceptos, se considera un caso práctico de un tren de la serie 7000 del Metro de Madrid, con los siguientes parámetros técnicos:

- Peso total del tren en condición cargada: 298.340 daN
- Peso de los ejes motores (peso adherente): 207.120 daN
- Potencia total disponible: 3168 kW (equivalente a 3.168.000 julios por segundo)
- Rendimiento mecánico en llanta: 90% (considerando pérdidas en la transmisión)
- Coeficiente de adherencia inicial (tren parado): $\phi_{0}=0.3$
- Factor de inercia ficticia: $f_{p}=1.07$

La expresión para la resistencia al avance específica para este tipo de material es:

$$
r_{a}(d a N / t)=1.5+0.01 \cdot v+3 \cdot 10^{-4} \cdot v^{2}
$$

El problema propuesto consiste en determinar el tiempo necesario para que el tren, partiendo desde el reposo, alcance los 100 km/h, así como la distancia recorrida durante esta aceleración.
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-055.jpg?height=194&width=2278&top_left_y=2010&top_left_x=1234)
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-055.jpg?height=380&width=1877&top_left_y=2225&top_left_x=1435)

- En primer lugar se calculan los puntos A y B del diagrama esfuerzo-velocidad:
- Punto A: Esfuerzo de arranque
- Punto B: Punto límite de adherencia
- En el arranque:

$$
E_{a d h}=P_{a d h} \cdot \phi_{0} \rightarrow 207.120 \cdot 0,3=62.136 d a N
$$

- Límite adherencia: intersección de las curvas de adherencia con la de potencia de la locomotora

$$
\begin{aligned}
& E_{a d h}=P_{a d h} \cdot \phi_{v} \rightarrow P_{a d h} \cdot \phi_{0} \cdot \frac{1}{1+0.01 \cdot v} \rightarrow 207.120 \cdot 0,3 \cdot \frac{1}{1+0,01 \cdot v} \\
& F(d a N)=100 \cdot 3,6 \cdot \operatorname{Pot}(\mathrm{~kW}) / \mathrm{v}(\mathrm{~km} / \mathrm{h}) \rightarrow 100 \cdot 3,6 \cdot 3168 \cdot 0,9 / \mathrm{v} \\
& E_{a d h}=F \rightarrow v v_{B}=19,8 \mathrm{~km} / \mathrm{h}=5,5 \mathrm{~m} / \mathrm{s}
\end{aligned}
$$

**Resolución del problema:**

El primer paso en la resolución es la identificación de los puntos críticos en el diagrama esfuerzo-velocidad. El punto A corresponde a la condición de arranque (velocidad cero), donde el esfuerzo limitado por adherencia es máximo. El punto B representa el límite entre la región controlada por adherencia y la región controlada por potencia.

**Cálculo del esfuerzo de arranque (Punto A):**

$$
E_{a d h}=P_{a d h} \cdot \phi_{0} \rightarrow 207.120 \cdot 0.3=62.136 \text{ daN}
$$

**Determinación del punto limite de adherencia (Punto B):**

El punto B se identifica donde las curvas de adherencia y potencia se intersectan. En este punto:

$$
E_{a d h}=P_{a d h} \cdot \phi_{0} \cdot \frac{1}{1+0.01 \cdot v} = F(daN)=100 \cdot 3.6 \cdot Pot(kW) / v(km/h)
$$

Resolviendo esta ecuación se obtiene: $v_B = 19.8 \text{ km/h} = 5.5 \text{ m/s}$

**Discretización numérica del proceso de aceleración (fase de control por adherencia):**

El proceso se discretiza en intervalos de 1 m/s desde el punto A (v=0) hasta el punto B (v=19.8 km/h). Como ejemplo ilustrativo, se desarrolla el cálculo del primer sub-intervalo (de 0 a 1 m/s):

$$
\begin{aligned}
E_{adh} &= 207.120 \cdot 0.3 \cdot \frac{1}{1+0.01 \cdot 1.8}\\
R &= (1.5+0.01 \cdot 1.8+3 \cdot 10^{-4} \cdot 1.8^{2}) \cdot 298.340 \cdot 10 / 9.8\\
F_{util} &= E_{adh} - R = 60.575 \text{ daN}\\
a &= \frac{F_{util} \cdot 10}{M \cdot f_p} = 1.860 \text{ m/s}^2\\
t &= \frac{\Delta v}{a} = 0.54 \text{ s}\\
l &= v_0 \cdot t + \frac{1}{2} \cdot a \cdot t^2 = 0.27 \text{ m}\\
Energia &= E_{adh} \cdot l = 164,113 \text{ N·m}
\end{aligned}
$$

**Fase de control por adherencia (tabla acumulativa):**

Los cálculos para el intervalo completo desde velocidad cero hasta el punto B se presentan en la siguiente tabla:

| Vel. Inicial (m/s) | Vel. Final (m/s) | Vel. Media (m/s) | Vel. Media (km/h) | Esf. Adh. (daN) | Resist. (daN) | Esf. Util. (daN) | Acel. (m/s²) | Tiempo (s) | Distancia (m) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 0 | 1 | 0.5 | 1.8 | 61037 | 462.4 | 60575 | 1.860 | 0.54 | 0.27 |
| 1 | 2 | 1.5 | 5.4 | 58953 | 475.7 | 58477 | 1.795 | 0.56 | 0.84 |
| 2 | 3 | 2.5 | 9 | 57006 | 491.4 | 56514 | 1.735 | 0.58 | 1.44 |
| 3 | 4 | 3.5 | 12.6 | 55183 | 509.5 | 54673 | 1.678 | 0.60 | 2.09 |
| 4 | 5.5 | 4.75 | 17.1 | 53062 | 535.4 | 52527 | 1.613 | 0.93 | 4.42 |
| **TOTALES FASE I** | | | | | | | | **3.20** | **9.05** |

**Transición a la fase de control por potencia:**

A partir de la velocidad del punto B (5.5 m/s o 19.8 km/h), la limitación cambia desde adherencia a potencia. Para verificar que la velocidad final de 100 km/h es alcanzable, se verifica la condición $F \geq R$:

$$
F(daN) = 100 \cdot 3.6 \cdot Pot(kW) / v(km/h) = 100 \cdot 3.6 \cdot 3168 \cdot 0.9 / 100 = 10,263 \text{ daN}
$$

$$
R = (1.5+0.01 \cdot 100+3 \cdot 10^{-4} \cdot 100^{2}) \cdot 298.340 \cdot 10 / 9.8 = 1,674.5 \text{ daN}
$$

Como $F > R$, la velocidad de 100 km/h es alcanzable. Se procede entonces con una nueva tabla reemplazando el esfuerzo limitado por adherencia con el esfuerzo limitado por potencia:

| Vel. Inicial (m/s) | Vel. Final (m/s) | Vel. Media (m/s) | Vel. Media (km/h) | Esf. Trac. (daN) | Resist. (daN) | Esf. Util. (daN) | Acel. (m/s²) | Tiempo (s) | Distancia (m) | Energía (N·m) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5.5 | 10 | 7.75 | 27.9 | 36790 | 612.7 | 36177 | 1.111 | 4.05 | 31.40 | 1,155,252 |

| v0 $\mathrm{m} / \mathrm{s}$ | v1 $\mathrm{m} / \mathrm{s}$ | vmedia $\mathrm{m} / \mathrm{s}$ | vmedia km/h | Ftrac daN | Resist daN | Futil daN | aceleración m/s2 | tiempo s | longitud m | Energía N.m |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 5,5 | 10 | 7,75 | 27,9 | 36790 | 612,7 | 36177 | 1,111 | 4,05 | 31,40 | 1155252 |
| 10 | 15 | 12,5 | 45 | 22810 | 778,6 | 22031 | 0,676 | 7,39 | 92,41 | 2107814 |
| 15 | 20 | 17,5 | 63 | 16293 | 1010,9 | 15282 | 0,469 | 10,66 | 186,51 | 3038760 |
| 20 | 25 | 22,5 | 81 | 12672 | 1302,4 | 11370 | 0,349 | 14,33 | 322,31 | 4084351 |
| 25 | 27,78 | 26,39 | 95,004 | 10804 | 1570,2 | 9234 | 0,283 | 9,81 | 258,80 | 2796118 |
| Total |  |  |  |  |  |  |  | 46,23 | 891,44 | 13182296 |

- Por lo tanto, el tren alcanza los $100 \mathrm{~km} / \mathrm{h}$ en 49 sg y recorre 892 metros.

| v0 m/s | v1 m/s | vmedia m/s | vmedia km/h | Fadh daN | Resist daN | Futil daN | a m/s2 | tiempo s | longitud m |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
|  |  |  |  |  |  |  |  |  |  |
| 0 | 1 | 0,5 | 1,8 | 61037 | 462,4 | 60575 | 1,860 | 0,54 | 0,27 |
|  |  |  |  |  |  |  |  |  |  |
| 1 | 2 | 1,5 | 5,4 | 58953 | 475,7 | 58477 | 1,795 | 0,56 | 0,84 |
| 2 | 3 | 2,5 | 9 | 57006 | 491,4 | 56514 | 1,735 | 0,58 | 1,44 |
| 3 | 4 | 3,5 | 12,6 | 55183 | 509,5 | 54673 | 1,678 | 0,60 | 2,09 |
| 4 | 5,5 | 4,75 | 17,1 | 53062 | 535,4 | 52527 | 1,613 | 0,93 | 4,42 |
|  |  |  |  |  |  | Total |  | 3,20 | 9,05 |

| v0 $\mathrm{m} / \mathrm{s}$ | v1 $\mathrm{m} / \mathrm{s}$ | vmedia $\mathrm{m} / \mathrm{s}$ | vmedia km/h | Ftrac daN | Resist daN | Futil daN | aceleración m/s2 | tiempo s | longitud m |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 5,5 | 10 | 7,75 | 27,9 | 36790 | 612,7 | 36177 | 1,111 | 4,05 | 31,40 |
| 10 | 15 | 12,5 | 45 | 22810 | 778,6 | 22031 | 0,676 | 7,39 | 92,41 |
| 15 | 20 | 17,5 | 63 | 16293 | 1010,9 | 15282 | 0,469 | 10,66 | 186,51 |
| 20 | 25 | 22,5 | 81 | 12672 | 1302,4 | 11370 | 0,349 | 14,33 | 322,31 |
| 25 | 27,78 | 26,39 | 95,004 | 10804 | 1570,2 | 9234 | 0,283 | 9,81 | 258,80 |
| Total |  |  |  |  |  |  |  | 46,23 | 891,44 |

Perfil de velocidades
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-060.jpg?height=832&width=1734&top_left_y=738&top_left_x=61)

⟶ Curva de aceler ación - Curva del MRUA
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-060.jpg?height=1043&width=1660&top_left_y=1502&top_left_x=1791)

#### II.1.3. Movimiento a velocidad constante

Cuando un tren ha alcanzado su velocidad límite operacional establecida por restricciones de la vía o del material rodante, y accede a un segmento donde puede mantener esta velocidad, el movimiento se caracteriza por una aceleración nula. En estas condiciones, la aplicación directa de las leyes clásicas de Newton es válida, siempre que el esfuerzo de tracción disponible menos las resistencias se mantengan en un valor positivo o nulo. La relación fundamental para el movimiento a velocidad constante es:

$$
s=v \cdot t
$$

Sin embargo, existen consideraciones prácticas importantes en ciertos escenarios. Cuando el tren entra en una rampa pronunciada, las resistencias pueden incrementarse significativamente (suma de resistencia al avance más componente gravitatoria). En estas circunstancias, el esfuerzo disponible podría ser insuficiente para mantener la velocidad, resultando en una deceleración. En tal caso, la sección debe ser analizada como una sección de aceleración con magnitud negativa (deceleración). Conversamente, en tramos con pendiente descendente significativa, el tren tiende a acelerar bajo la influencia de la componente gravitatoria favorable. Para mantener la velocidad máxima autorizada, es frecuentemente necesario emplear los sistemas de frenado de forma continua o modulada. En ciertos análisis simplificados, el movimiento a velocidad nominalmente constante se aproxima como una sucesión alternada de breves aceleraciones y segmentos de marcha sin propulsión activa.

#### II.1.4. Proceso de frenado

En el análisis simplificado del frenado con deceleración constante, se pueden emplear ecuaciones analíticas directas. Bajo la hipótesis de una deceleración $\gamma$ constante durante la maniobra de frenado, la distancia requerida para desacelerar desde una velocidad inicial $v_0$ hasta la parada es:

$$
s=\frac{1}{2} \cdot \frac{v_{0}^{2}}{\gamma}
$$

En la operación ferroviaria práctica, los valores de deceleración $\gamma$ utilizados en los cálculos vienen predeterminados para diferentes tipos de frenado, considerando el confort de los viajeros y la capacidad técnica de los sistemas de frenado disponibles:

- Trenes suburbanos (frenado estándar): $\gamma = 0.525 \text{ m/s}^2$
- Trenes de viajeros de largo recorrido (frenado confortable): $\gamma = 0.375 \text{ m/s}^2$
- Trenes de mercancías (frenado conservador): $\gamma = 0.225 \text{ m/s}^2$

Para el dimensionamiento correcto de los perfiles de velocidad en un recorrido, es esencial conocer la máxima velocidad permitida en el segmento de línea subsecuente. Esta velocidad futura determina la velocidad máxima de salida permitida en la sección actual, influyendo en las maniobras de frenado requeridas.

La distancia de frenado necesaria para transitar desde la velocidad máxima de la sección actual hasta la velocidad máxima de la sección siguiente se calcula mediante:

$$
s_{b}=\frac{v_{\max }^{2}}{2 \cdot \gamma}-\frac{v_{exit}^{2}}{2 \cdot \gamma}
$$

**Casos operacionales en el frenado:**

Si la distancia de frenado requerida $s_b$ es inferior a la longitud total de la sección, entonces la sección se puede descomponer en dos partes: una primera parte circulando a velocidad máxima constante, seguida de una segunda parte aplicando la curva de frenado desde $v_{max}$ hasta $v_{exit}$, con longitud exacta de $s_b$.

Si, por el contrario, la distancia de frenado $s_b$ es igual o superior a la longitud total de la sección $s_{sec}$, entonces no es posible mantener la velocidad máxima durante la sección. En este caso, debe determinarse la velocidad máxima de entrada a la sección $v_{entr}$ que permita alcanzar la velocidad requerida de salida respetando los límites de deceleración:

$$
v_{entr}=\sqrt{2 \cdot \gamma \cdot s_{sec}+v_{exit}^{2}}
$$

Es importante destacar que si la velocidad máxima permitida en la sección actual $v_{max}$ resulta ser mayor que la velocidad de entrada calculada $v_{entr}$, entonces la velocidad máxima de salida de la sección anterior debe igualarse a $v_{entr}$. 

Debido a estas interdependencias, es práctica estándar en ingeniería ferroviaria determinar los perfiles de frenado trabajando en orden inverso a la dirección de marcha: iniciando desde la última sección del recorrido y avanzando progresivamente hacia atrás. Este enfoque asegura que las restricciones aguas arriba se ajusten correctamente a los requerimientos aguas abajo.
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-064.jpg?height=956&width=3425&top_left_y=1490&top_left_x=62)

**CASO 1: Sección con velocidad máxima constante alcanzada en dicha sección**

En este escenario operacional, la sección de línea considerada es suficientemente larga para que el tren pueda acelerar desde la velocidad de entrada y alcanzar la velocidad máxima permitida, manteniéndola posteriormente durante una porción del segmento. El perfil de velocidades en este caso consta de tres fases: aceleración desde $v_{entrada}$ hasta $v_{max}$, movimiento a velocidad constante $v_{max}$, y finalmente frenado desde $v_{max}$ hasta $v_{salida}$.

**CASO 2: Velocidad de salida menor que la máxima; distancia de aceleración superior a la longitud de la sección**

En este caso, la sección de línea no es lo suficientemente larga para permitir que el tren alcance su velocidad máxima. Esto ocurre cuando la distancia requerida para acelerar desde la velocidad de entrada hasta la velocidad máxima excede la longitud total disponible de la sección. Como resultado, el tren acelera continuamente durante toda la sección sin alcanzar la velocidad máxima, llegando a una velocidad intermedia de salida menor que $v_{max}$.

**CASO 3: Sección de frenado con intersección de curvas**

En este escenario, la sección constituye primariamente un segmento de frenado. El tren ingresa a la sección con una cierta velocidad y debe reducir su velocidad para cumplir con los requisitos de velocidad máxima de la siguiente sección. Las curvas de aceleración/deceleración se intersectan dentro de la sección, lo que significa que el tren ejecuta una maniobra de frenado modulada para alcanzar la velocidad requerida exactamente en el punto de transición con la siguiente sección.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-065.jpg?height=696&width=3424&top_left_y=1435&top_left_x=0)

**Tiempo necesario para acelerar y frenar (minutos)**

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-066.jpg?height=821&width=3494&top_left_y=735&top_left_x=0)

**Distancia necesaria para acelerar y frenar (metros)**
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-066.jpg?height=814&width=3552&top_left_y=1813&top_left_x=0)

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-067.jpg?height=1918&width=3546&top_left_y=647&top_left_x=8)

### II.2. Velocidades máximas

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-068.jpg?height=2020&width=2940&top_left_y=611&top_left_x=297)

Índice

- Dinámica longitudinal
- Cálculo de perfiles de velocidad
- Cálculo de tiempos de viaje
- Cálculo de energía consumida

## Capítulo III Cálculo de tiempos de viaje - Marcha base

La "marcha base" constituye un concepto fundamental en la planificación y operación ferroviaria. Se define como el tiempo mínimo teóricamente posible para recorrer una sección específica de una línea ferroviaria transportando una carga determinada. Este cálculo se realiza bajo un conjunto de condiciones estándar que representan operación nominal y confiable. Específicamente, la marcha base incorpora:

- La conducción óptima del tren por parte del maquinista, asumiendo manejo profesional y estandarizado
- Las prestaciones técnicas intrínsecas del material motor empleado
- Las características del sistema de alimentación de energía de tracción (voltaje, intensidad, etc.)
- La capacidad de adherencia entre ruedas y carril bajo condiciones normales
- La resistencia al avance presentada tanto por el material remolcado como por la infraestructura (rampas, curvas, etc.)
- Los límites de velocidad permitidos por el trazado geométrico e infraestructura

El cálculo de la marcha base es absolutamente imprescindible para el diseño de horarios y la programación de servicios ferroviarios. Para obtener cálculos precisos es necesario disponer de información detallada de las velocidades máximas permitidas en cada tramo de la línea, información que a su vez determina los tiempos de viaje requeridos en cada sección.

### III.1. Marcha tipo

Conforme a la ficha de especificaciones UIC 451-1 (2000), el concepto de "Tiempo de marcha-tipo" se define como el intervalo temporal requerido entre dos puntos determinados para establecer el horario operativo de un tren. Este parámetro constituye la suma de tres componentes críticos: el tiempo derivado del cálculo de marcha base, adicionado con márgenes de regularidad y márgenes suplementarios incorporados según los requisitos operacionales de la línea.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-071.jpg?height=1486&width=1992&top_left_y=1170&top_left_x=850)

El margen de regularidad constituye un tiempo adicional incorporado al tiempo base de recorrido calculado anteriormente, con el propósito de compensar de manera sistemática los retrasos operacionales que se originan por diversas causas. Estas incluyen las tareas periódicas de conservación y mantenimiento de las instalaciones ferroviarias, que aunque planificables, requieren modulación operativa. Igualmente, se contemplan los posibles tiempos perdidos derivados de incidentes técnicos de explotación, condiciones meteorológicas desfavorables, o estacionamientos prolongados en estaciones por saturación de afluencia de viajeros.

El margen suplementario, en contraste, representa un incremento temporal reservado específicamente para compensar los retrasos originados por trabajos mayores en las instalaciones durante períodos prolongados. Este margen también incorpora los retrasos que ocurren sistemáticamente en grandes nudos ferroviarios complejos, principalmente causados por operaciones de maniobra extensas que resultan de la configuración y complejidad de la infraestructura disponible.

**Margen de regularidad:**

**A) TRENES DE VIAJEROS NO AUTOMOTORES**

- Un mínimo de 1,5 minutos $/ 100 \mathrm{~km}$ mayorado en base al siguiente criterio
V. limite $\leq 140 \mathrm{~km} / \mathrm{h} \quad 141-160 \mathrm{~km} / \mathrm{h} \quad 161-200 \mathrm{~km} / \mathrm{h} \quad>200 \mathrm{~km} / \mathrm{h}$ Tonelaje

| $\leq 300 \mathrm{t}$ | 3\% | 3\% | 4\% | 5\% |
| :--- | :--- | :--- | :--- | :--- |
| 301-500 t | 4\% | 4\% | 5\% | \% |
| 501-700 t | 4\% | 5\% | 6\% | \% |
| $>700 \mathrm{t}$ | 5\% | 5\% | 6\% | 7\% |

- Un mínimo de al menos 3,5 minutos $/ 100 \mathrm{~km}$

**B) TRENES DE VIAJEROS AUTOMOTORES**

- Un mínimo de 1 minuto por cada 100 km, mayorado según criterios específicos que dependen de la velocidad máxima de operación. Esta estructura permite que trenes más rápidos dispongan de márgenes temporales adicionales para mantener su regularidad operacional.

En sistemas de alta velocidad donde solamente circulan unidades autopropulsadas, se permite flexibilidad regulatoria: el porcentaje suplementario respecto al tiempo de recorrido puede oscilar entre 3% y 7% para velocidades superiores a 200 km/h, permitiendo así una optimización según las características específicas de cada línea y servicio.

**C) TRENES DE MERCANCÍAS**

El cálculo de márgenes de regularidad para trenes de carga presenta una estructura diferenciada según el rango de velocidades de operación. Para velocidades hasta 120 km/h, se ofrece flexibilidad operacional con tres alternativas equivalentes disponibles: un margen de 1 minuto por cada 100 km mayorado al 3%, un margen fijo de 3 minutos por cada 100 km, o un porcentaje global del 4%. Esta multiplicidad de opciones permite a los operadores seleccionar el criterio que mejor se adapte a sus condiciones específicas de explotación. Para velocidades superiores a 120 km/h, los trenes de mercancías se rigen por los mismos criterios establecidos para los trenes de viajeros no automotores, asimilando así trenes rápidos de carga a los estándares de transporte de pasajeros. El cálculo resultante se expresa como: 1 minuto por cada 100 km más un porcentaje X del tiempo de marcha base.

El margen suplementario se diferencia fundamentalmente del margen de regularidad tanto en su naturaleza como en su cálculo. A diferencia de este último, no se calcula como un porcentaje del tiempo de viaje sino como un intervalo temporal fijo aplicado a cada sección específica de línea considerada. Cuando este margen se debe a la complejidad operacional de un nudo ferroviario importante, es recomendable que no exceda los 3 minutos para mantener la eficiencia del sistema. Su aplicación se limita estrictamente a circunstancias no habituales de explotación, preservando así su carácter de mecanismo de excepción para situaciones operacionales excepcionales.

Los tiempos de espera programados constituyen adiciones al tiempo de viaje que se incorporan por razones de coordinación operacional superior. Estos tiempos se añaden para sincronizar convenientemente los horarios de diferentes líneas de viajeros en puntos nodales de intercambio modal, para coordinar la programación de múltiples expediciones dentro de un horario maestro integrado, o para permitir maniobras operativas como cruces y adelantamientos en tramos de vía específicos dentro de la sección.

### III.2. Libro de horarios/itinerarios

**renfe <br> Dirección de Viajeros Urbanos e Interurbanos**

**EJEMPLO LIBRO HORARIO**

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-075.jpg?height=1759&width=1265&top_left_y=836&top_left_x=452)
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-075.jpg?height=1740&width=1268&top_left_y=855&top_left_x=1986)

Índice

- Dinámica longitudinal
- Cálculo de perfiles de velocidad
- Cálculo de tiempos de viaje
- Cálculo de energía consumida

### III.3. Cálculo de la energía consumida

La evaluación del consumo energético en trenes durante su movimiento puede abordarse mediante dos metodologías complementarias, cada una con propósitos y aplicaciones específicas. El primer enfoque consiste en integrar instantáneamente el consumo energético bajo cada condición operacional específica: movimiento a velocidad uniforme en secciones horizontales, comportamiento en subidas y bajadas, procesos transitorios de reducción y aumento de velocidad, entre otros. Este método resulta especialmente valioso para la toma de decisiones operacionales "instantáneas" tales como optimización de conducción económica o retorno controlado de energía a la red de distribución, aunque tiene la limitación de que no revela explícitamente las causas subyacentes del consumo observado.

El segundo enfoque examina el balance energético integral del tren considerando la totalidad de un recorrido determinado, típicamente calculado entre dos puntos donde el tren se encuentra en reposo y a la misma altitud. Esta metodología resulta particularmente útil para cálculos de alcance global tales como el diseño de infraestructura, especificación de nuevos vehículos ferroviarios, o programación de servicios operacionales. Su ventaja fundamental radica en que permite desagregar y explicitar las causas específicas del consumo energético: qué porción se atribuye a las curvas, qué parte a los túneles, cuánta energía se disipa por entrada de aire y resistencias aerodinámicas, etc.

### III.4. Introducción

Para ilustrar el enfoque instantáneo de cálculo energético, considérese el ejemplo anterior de análisis de aceleración. El consumo de energía se obtiene multiplicando la fuerza de tracción aplicada en cada intervalo por la distancia recorrida durante ese intervalo. Las dos tablas siguientes presentan el desglose detallado del consumo energético durante dos fases distintas de aceleración:

| v0 $\mathrm{m} / \mathrm{s}$ | v1 $\mathrm{m} / \mathrm{s}$ | vmedia $\mathrm{m} / \mathrm{s}$ | vmedia km/h | Fadh daN | Resist daN | Futil daN | a m/s2 | tiempo s | longitud m | Energía $\mathrm{N} \cdot \mathrm{m}$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 0 | 1 | 0,5 | 1,8 | 61037 | 462,4 | 60575 | 1,860 | 0,54 | 0,27 | 164113 |
| 1 | 2 | 1,5 | 5,4 | 58953 | 475,7 | 58477 | 1,795 | 0,56 | 0,84 | 492583 |
| 2 | 3 | 2,5 | 9 | 57006 | 491,4 | 56514 | 1,735 | 0,58 | 1,44 | 821428 |
| 3 | 4 | 3,5 | 12,6 | 55183 | 509,5 | 54673 | 1,678 | 0,60 | 2,09 | 1150709 |
| 4 | 5,5 | 4,75 | 17,1 | 53062 | 535,4 | 52527 | 1,613 | 0,93 | 4,42 | 2344544 |
| Total |  |  |  |  |  |  |  | 3,20 | 9,05 | 4973377 |

| v0 $\mathrm{m} / \mathrm{s}$ | v1 $\mathrm{m} / \mathrm{s}$ | vmedia $\mathrm{m} / \mathrm{s}$ | vmedia km/h | Ftrac daN | Resist daN | Futil daN | aceleración m/s2 | tiempo s | longitud m | Energía $\mathrm{N} \cdot \mathrm{m}$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 5,5 | 10 | 7,75 | 27,9 | 36790 | 612,7 | 36177 | 1,111 | 4,05 | 31,40 | 11552520 |
| 10 | 15 | 12,5 | 45 | 22810 | 778,6 | 22031 | 0,676 | 7,39 | 92,41 | 21078135 |
| 15 | 20 | 17,5 | 63 | 16293 | 1010,9 | 15282 | 0,469 | 10,66 | 186,51 | 30387605 |
| 20 | 25 | 22,5 | 81 | 12672 | 1302,4 | 11370 | 0,349 | 14,33 | 322,31 | 40843513 |
| 25 | 27,78 | 26,39 | 95,004 | 10804 | 1570,2 | 9234 | 0,283 | 9,81 | 258,80 | 27961182 |
| Total |  |  |  |  |  |  |  | 46,23 | 891,44 | 131822956 |

- Según esto, la energía consumida de tracción en el trayecto es de 136,8 •106 $\mathrm{N} \cdot \mathrm{m}$, esto es 38 kWh .

- La energía para acelerar el tren puede proceder:
- del motor de tracción
- de la pérdida de energía potencial (al bajar una pendiente).
- Cuando se reduce la energía cinética (se decelera el tren) la energía puede emplearse:
- en vencer la resistencia al avance;
- en subir una rampa;
- disiparse en el freno (ésta es la que verdaderamente se pierde).

- Si el tren pudiera almacenar energía sin restricciones, el consumo de energía en llantas sería sólo el necesario para vencer la resistencia al avance, porque:
- Toda la energía consumida para acelerar el tren se almacenaría al reducir la velocidad.
- La totalidad de la $E_{\text {pot }}$ recibida en las subidas se podría recuperar en las bajadas: no habría consumo neto de energía exterior por este concepto.
- Si no se pudiese almacenar, ni aprovechar nada de la $E_{\text {cin }}$ ni de la $E_{\text {pot }}$, el consumo de energía de un tren sería:
- energía para vencer la resistencia al avance $\left(R_{\text {av }}\right)+$
-     + energía para acelerarlo todas las veces en que deba aumentar su $V+$
-     + energía para subir todas las rampas del recorrido.

El conocimiento indirecto de la energía que ha entrado en el tren se obtiene mediante la aplicación del principio fundamental de conservación de la energía. La formulación básica establece que la energía entrada en el sistema es equivalente a la suma de la energía que sale del mismo, más la energía que se acumula dentro del tren en forma de potencial gravitatorio o cinético, considerando además las pérdidas inherentes al rendimiento de los sistemas mecánicos y eléctricos.

La energía que sale del tren se descompone en tres categorías principales: la empleada para superar la resistencia al avance durante toda la sección (que incluye componentes de resistencia mecánica por curvas, resistencia asociada a la entrada de aire en el vehículo, y resistencias aerodinámicas de presión y fricción); la disipada o regenerada a través del sistema de frenado, que puede emplearse para decelerar el tren en paradas o puntos de reducción de velocidad, o para prevenir aceleración indeseada en pendientes muy pronunciadas; y finalmente la consumida por los servicios auxiliares del tren (climatización, iluminación, sistemas de control, etc.).

Para obtener la energía final requerida en el pantógrafo o punto de carga, es necesario incorporar a los consumos útiles del vehículo las pérdidas asociadas al rendimiento de la locomotora y de los equipos auxiliares. Posteriormente, considerando las pérdidas en el transporte de energía eléctrica y en los procesos de conversión en subestaciones, se obtiene la energía eléctrica total que debe ser comprada al sistema. Finalmente, incorporando las pérdidas inherentes a los procesos de producción del vector energético en las centrales generadoras, se llega a la cuantificación de la energía primaria consumida, que representa el consumo total de recursos energéticos asociado al movimiento del tren.

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-084.jpg?height=1957&width=3007&top_left_y=608&top_left_x=297)

### III.5. Pérdidas en transporte y conversión

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-085.jpg?height=1787&width=3182&top_left_y=711&top_left_x=205)

### III.6. Energía que sale del tren

- Energía por resistencia mecánica al avance

$$
\begin{aligned}
& \text { en recta: } \\
& E_{\text {rAvance } R}(k W h)=A(d a N) \cdot L\left(k m_{\text {linea }}\right) \cdot \frac{1}{360} \\
& \text { donde: } \quad A(d a N)=\left(M_{\text {carg }}(t) \cdot 0,25\right)+\left(N_{\text {ejes }} \cdot 7\right)
\end{aligned}
$$

- Energía por resistencia en curvas de radio R:

$$
E_{r A v a n c e C u r v}(k W h)=L\left(k m_{l i n e a}\right) \cdot M(t) \cdot a_{c u r} \cdot \frac{1}{360}
$$

donde:

$$
a_{c u r}(d a N / t)=\frac{1}{L_{l i n e a}(m)} \cdot \sum_{c}\left(l_{c}(m) \cdot \frac{600 o 800}{R_{c}(m)}\right)
$$

| Longitud del tramo considerado (m) |  |  |  |
| ---: | ---: | ---: | ---: |
| Radio(m) | Longitud(m) | Lon. ac. (m) | Coef. Curva |
| 1.076 | 300 | 251 | 447,21 |
| 863 | 100 | 201 | 349,02 |
| 690 | 600 | 216 | 897,39 |
| 500 | 250 | 258 | 919,20 |

**Energía por entrada de aire**

La circulación de aire a través de los sistemas de climatización y ventilación del tren genera una resistencia adicional que debe superarse durante el movimiento. Este consumo energético es proporcional tanto al volumen de aire procesado como a la velocidad de circulación del tren. La energía requerida viene expresada mediante:

$E_{\text{entradaaire}}(kWh)=B(daN/km/h) \cdot V(km/h) \cdot L_{\text{linea}}(km) \cdot \frac{1}{360}$

donde el coeficiente B se determina por:

$B(daN/km/h)=Q(m^{3}/s) \cdot \rho \cdot \frac{1}{36} \approx 0,034 \cdot Q(m^{3}/s)$

**Ejemplo práctico: Tren 103 Madrid-Barcelona**

Considérese el caso de un servicio de tracción de alta velocidad Madrid-Barcelona, que presenta un consumo energético total de aproximadamente 11.561 kWh. En este recorrido, el sistema de entrada de aire (con caudal volumétrico de 99,70 m³/s) supone una energía consumida de:

$$
3,39 \text{ daN}/(km/h) \times 198 \text{ km/h} \times 620 \text{ km} \times 1/360 = 1.155 \text{ kWh (9,99\%)}
$$

Este resultado evidencia que la resistencia aerodinámica por entrada de aire representa aproximadamente el 10% del consumo total en este servicio específico.

Energía que sale del tren
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-088.jpg?height=565&width=3445&top_left_y=275&top_left_x=87)

$$
E_{\text {aAbierto }}(k W h)=C\left(d a N /(k m / h)^{2}\right) \cdot\left(V_{\text {media }}^{2}+\sigma(V)^{2}\right)(k m / h)^{2} \cdot L_{\text {linea }}(k m) \cdot \frac{1}{360}
$$

donde:

$$
C\left(d a N /(k m / h)^{2}\right) \cong c_{p} \cdot S_{f}\left(m^{2}\right)+c_{f} \cdot p_{m o j}(m) \cdot L_{t r e n}(m)
$$

- Energía para vencer resistencia aerodinámica adicional en túnel:

$$
E_{\text {tunel }}=E_{\text {adbierto }}(k W h) \cdot \frac{L_{\text {tunel }}}{L_{\text {linea }}} \cdot\left(T_{f}-1\right)
$$

|  | $\mathrm{C}_{\mathrm{p}}$ | $\mathrm{C}_{\mathrm{f}}$ |
| :---: | :---: | :---: |
| AV | 0,00096 | 0,000021 |
| Convencional | 0,0022 | 0,0003 |

**Energía para vencer resistencia aerodinámica debida al viento exterior**

Cuando el tren se desplaza en condiciones de viento lateral o frontal significativo, la resistencia aerodinámica se incrementa proporcionalmente al cuadrado de la velocidad relativa entre el tren y el aire circundante. Esta energía adicional debe ser suministrada por el sistema de tracción para mantener la velocidad operacional programada. La formulación es:

$$E_{\text{viento}}=C \cdot (V_{\text{viento}} \cdot 0,43)^{2} \cdot L_{\text{linea}}(km) \cdot \frac{1}{360}$$

Energía que sale del tren
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-089.jpg?height=909&width=3445&top_left_y=262&top_left_x=87)

**Energía disipada en el proceso de frenado**

Debe considerarse también la energía que debe restarse al balance: aquella que fue consumida originalmente para vencer la resistencia al avance durante los tramos de deceleración antes de cada parada. Esta energía es recuperable teóricamente mediante sistemas de frenado regenerativo, pero en la práctica se disipa parcialmente en el sistema de frenado mecánico. La cuantificación es:

$$E_{\text{ravd}}(kWh)=N_{\text{paradas}} \cdot \left[\frac{A \cdot V_{op}^{2}}{2 \cdot \gamma}+\frac{B \cdot V_{op}^{3}}{3 \cdot \gamma}+\frac{C \cdot V_{op}^{4}}{4 \cdot \gamma}\right] \cdot \frac{1}{3,6^{3} \cdot 10^{5}}$$

**Paradas equivalentes y reducciones de velocidad**

Dentro del análisis del consumo energético, no solo cuentan las paradas comerciales (en estaciones) y técnicas (por mantenimiento), sino también todas aquellas reducciones de velocidad causadas por las limitaciones de velocidad máxima del perfil de la línea. Cada reducción de velocidad que no corresponde a parada comercial o técnica se contabiliza como una "fracción de parada" con equivalencia energética. El cálculo total de paradas equivalentes para fines de consumo energético es:

$$N^{\circ}_{\text{paradas equiv}} = N^{\circ}_{\text{paradas comerciales}} + 1_{\text{(parada final)}} + N^{\circ}_{\text{paradas técnicas}} + \sum_{\text{reducciones}} \text{fracciones de paradas equivalentes}$$

Este análisis permite desagregar el consumo total entre estaciones: qué energía se consume en acelerar desde parada, qué energía se disipa en frenados, y qué energía representa la circulación en los tramos de velocidad constante.

Vel. Máx $200 \mathrm{~km} / \mathrm{h}$
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-091.jpg?height=1223&width=1991&top_left_y=772&top_left_x=113)

|  | km | Velocidades N (max 300km/h) | Reducciones (max300km/h) |
| :--- | :--- | :--- | :--- |
| Madrid P. Atocha | 0,000 | 30 | 0,0000 |
|  | 1,000 | 60 | 0,0000 |
|  | 1,500 | 90 | 0,0000 |
|  | 2,800 | 100 | 0,0000 |
|  | 4,400 | 140 | 0,0000 |
|  | 5,700 | 200 | 0,0000 |
|  | 13,100 | 230 | 0,0000 |
|  | 20,300 | 270 | 0,0000 |
|  | 99,300 | 290 | 0,0000 |
|  | 103,400 | 300 | 0,0000 |
|  | 112,000 | 290 | 0,0656 |
|  | 115,100 | 270 | 0,1244 |
|  | 170,200 | 190 | 0,4089 |
| Ciudad Real | 170,500 | 190 | 0,0000 |
|  | 173,100 | 240 | 0,0000 |
|  | 178,100 | 270 | 0,0000 |
|  | 206,800 | 200 | 0,3656 |
|  | 208,800 | 80 | 0,3733 |
| Puertollano | 209,400 | 70 | 0,0167 |

Paradas equivalentes por reducción de velocidad
Paradas comerciales equivalentes

1,3544
0,4556

Energía que sale del tren

Energía que sale del tren

- Energía potencial disipada por el freno en
pendientes:

$$
E_{\text {potF }}(k W h)=M_{\text {carg }}(t) \cdot 9,81 \cdot \text { excPend } \cdot L(k m) \cdot \frac{1}{3600}
$$

- Pendiente de equilibrio: Para una velocidad es aquella en la que la fuerza de la gravedad se iguala (en valor absoluto) a la fuerza resistente y el tren está en equilibrio.

$$
\text { excPend }=\frac{\sum\left(p_{\text {real }}-\text { pequilibrio }\right) \cdot l_{\text {pendiente }}}{L_{\text {linea }}}
$$

- Si el valor anterior es positivo, es el exceso de pendiente. Si es negativo, se toma 0 como exceso de pendiente (no se frena)

- Energía cinética disipada por el freno en pendientes:

Mecánica y en curvas

Entrada de aire

Aerodinámica

Exceso de altura (mm/km)|

Pendiente de equilibrio
| km inicio | Valor (mm) |
| ---: | ---: |
| 0,000 | $-1,46$ |
| 0,266 | $-2,99$ |
| 0,505 | $-0,59$ |
| 0,556 | $-8,05$ |
| 0,826 | $-14,02$ |
| 1,113 | $-9,99$ |
| 1,388 | $-10,05$ |
| 1,755 | $-7,71$ |
| 1,815 | $-10,09$ |
| 1,920 | $-12,36$ |
| 1,985 | $-8,83$ |
| 2,472 | $-9,19$ |
| 3,823 | $-1,13$ |
| 4,097 | $-11,99$ |
| 4,546 | 11,7 |
| 5,075 | $-6,14$ |
| 5,756 | 9,17 |
| 6,122 | $-12,46$ |

| ![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-093.jpg?height=330&width=843&top_left_y=1042&top_left_x=215) | (1) Si $\mathrm{p}<\mathrm{pe}_{\mathrm{V}_{\text {max }}}=\mathrm{a}+\mathrm{bV}_{\text {max }}+\mathrm{cV}_{\text {max }}^{2}$ <br> Es necesario traccionar para mantener $\mathrm{V}_{\text {max }}$ |
| :--- | :--- |
| ![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-093.jpg?height=372&width=739&top_left_y=1473&top_left_x=276) | $\text { (2) Si } \mathrm{p}=\mathrm{pe}_{\mathrm{V}_{\text {max }}}=\mathrm{a}+\mathrm{bV}_{\text {max }}+\mathrm{cV}_{\text {max }}^{2}$ <br> Mantiene $\mathrm{V}_{\text {max }}$ sin traccionar ni frenar |
| ![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-093.jpg?height=432&width=728&top_left_y=1953&top_left_x=283) | (3) Si $\mathrm{p}>\mathrm{pe}_{\mathrm{V}_{\text {max }}}=\mathrm{a}+\mathrm{bV}_{\text {max }}+\mathrm{cV}_{\text {max }}^{2}$ <br> Es necesario frenar para no rebasar $\mathrm{V}_{\max .} \rightarrow$ Entonces se pierde energía |

Energía que sale del tren

**Energía potencial consumida por diferencia de altitud**

Cuando los puntos inicial y final del recorrido están a altitudes diferentes, existe una diferencia de energía potencial que debe ser considerada en el balance energético total. Si el origen está más bajo que el destino, el tren debe consumir energía adicional para ganar altura; si por el contrario el destino es más bajo, se puede recuperar parte de esta energía mediante frenado regenerativo. La energía potencial consumida (o recuperable) se calcula como:

$$E_{\text{potExt}}(kWh)=M_{\text{carg}}(t) \cdot 9,81 \cdot \text{difAlturas}(m) \cdot \frac{1}{3600}$$

**Energía consumida por sistemas auxiliares técnicos**

Los sistemas de climatización, iluminación, sistemas de control, bombas de agua, compresores de aire y otros equipos técnicos del tren requieren potencia eléctrica continua durante todo el viaje. Esta energía se considera como consumo de operación y debe incorporarse al balance total. La cuantificación típica es:

$$E_{\text{auxTecnicos}}=\text{pot}_{\text{AuxTec}} \cdot T_{\text{viaje}} \cdot 0,7$$

donde el factor 0,7 representa un coeficiente de operación que contempla que no todos los auxiliares operan con máxima potencia continuamente durante todo el viaje.

**Energía consumida por servicios comerciales**

Los servicios comerciales a bordo del tren (iluminación, climatización, y otros servicios al pasajero) representan un consumo energético que varía según las dimensiones del vehículo y sus características de acondicionamiento. La energía consumida por estos servicios se estima mediante:

$$E_{\text{auxcom}}=[0,3 \text{ a } 0,45] \cdot S_{\text{util}}(m^{2}) \cdot t_{\text{trenencendido}}(h)$$

Un aspecto fundamental es que el consumo total en un recorrido determinado disminuye significativamente con la velocidad media de operación. Este fenómeno se debe a que aunque la potencia requerida es relativamente constante, la duración total del viaje se reduce drásticamente con velocidades superiores, compensando así el consumo adicional de tracción.

Considérese un ejemplo práctico: en un tren de 300 plazas con consumo característico de auxiliares comerciales de 200 kWh/h. Si el recorrido Madrid-Barcelona se realiza a velocidad convencional en 5 horas, el consumo auxiliar es 200 × 5 + 200 × 0,75 (período de rotación) = 1.150 kWh. Si el mismo recorrido se realiza en alta velocidad con duración de 2,5 horas, el consumo desciende a 200 × 2,5 + 200 × 0,75 = 650 kWh, representando un ahorro de 500 kWh en servicios comerciales por la simple reducción de tiempo de operación.

### III.7. Ejemplo: línea de alta velocidad Madrid-Barcelona

|  |  | AVE MPA-BAR 300 | AVE MPA-BAR 250 | AVE MPA-BAR 120 |
| :--- | :--- | :--- | :--- | :--- |
| Características de la línea |  |  |  |  |
| Longitud | km | 621,00 | 621,00 | 621,00 |
| Longitud de túneles | km | 47,45 | 47,45 | 47,45 |
| Factor de túnel (Tf) |  | 1,50 | 1,50 | 1,50 |
| Tensión de alimentación | kV | $2 \times 25 \mathrm{kV}$ CA | $2 \times 25 \mathrm{kV}$ CA | $2 \times 25 \mathrm{kV}$ CA |
| Diferencia del altitud (Hd-Ho) | m | 0,00 | 0,00 | 0,00 |
| Coeficiente de curvas | daN/t | 0,12 | 0,12 | 0,12 |
| Exceso específico pendientes | $\mathrm{mm} / \mathrm{km}$ | 1240,97 | 1824,75 | 4510,86 |
| Velocidad media del viento exterior | km/h | 10 | 10 | 10 |
| Características del servicio |  |  |  |  |
| Velocidad máxima (sin paradas) | km/h | 300,00 | 250,00 | 120,00 |
| Tiempo de viaje en el recorrido | min | 158,00 | 189,60 | 395,00 |
| Velocidad media (sin paradas) | km/h | 235,82 | 196,52 | 94,33 |
| \% aprovechamiento s/plazas estándar | \% | 0,65 | 0,65 | 0,65 |
| Densidad de plazas y servicios |  | 1,00 | 1,00 | 1,00 |
| Paradas comerciales (sin contar la final) | $N^{\circ}$ | 0,00 | 0,00 | 0,00 |
| Paradas comerciales equivalentes |  | 1,00 | 1,00 | 1,00 |
| Paradas técnicas programadas | $N^{\circ}$ | 0,00 | 0,00 | 0,00 |
| Paradas técnicas no programadas | $N^{\circ}$ | 0,10 | 0,10 | 0,10 |
| Paradas equivalentes por reducción de | $N^{\circ}$ | 0,10 | 0,00 | 0,00 |
| Tiempo medio parada comercial | min | 2,00 | 2,00 | 2,00 |
| Velocidad origen de las paradas |  | 258,28 | 215,24 | 103,31 |

| Denominación del tren |  | s103 | s130 | s465 (Civia) |
| :--- | :--- | :--- | :--- | :--- |
| Velocidad máxima | km/h | 350 | 250 | 120 |
| Potencia total del tren | kW | 8800 | 4800 | 2200 |
| Masa en vacío | $t$ | 425 | 312 | 157,3 |
| Masas rotativas equivalentes | $t$ | 40,05 | 15,41 | 11,01 |
| Tensión de funcionamiento | kV | $2 \times 25 \mathrm{kV}$ CA | $2 \times 25 \mathrm{kV}$ CA | $2 \times 25 \mathrm{kV}$ CA |
| Plazas reales | plazas | 404 | 298 | 997 |
| Coeficiente A (resistencia mecánica) | daN | 337,0762 | 222,6758 | 126,55 |
| Coeficiente B (resistencia entrada de aire) | daN/(km/h) | 3,7603 | 2,4039 | 1,5314 |
| Coeficiente C (resistencia aerodinámica) | daN/(km/h)2 | 0,056361 | 0,0482798 | 0,021696 |
| Superficie útil bruta | m2 | 525,09 | 359,68 | 254,05 |
| Tipo de motor | 0 | Asíncrono AC | Asíncrono AC | Asíncrono AC |
| Potencia de cada motor eléctrico de tracción | $k W$ | 550 | 632 | 320 |
| Deceleración del freno de servicio | $\mathrm{m} / \mathrm{s} 2$ | 0,54 | 0,6 | 0,6 |
| Rendimiento cadena de tracción | kWhs/kWhe | 0,87 | 0,87 | 0,87 |
| Rendimiento de auxiliares | kWhs/kWhe | 0,85 | 0,85 | 0,85 |
| Procedencia de la alimentación de auxiliares |  | Catenaria | Catenaria | Catenaria |
| Tiene aire acondicionado? | booleano | 1 | 1 | 1 |
| Coeficiente de transmisión de calor (K) | $\mathrm{W} / \mathrm{m} 2^{\circ} \mathrm{C}$ | 1,6 | 1,6 | 1,6 |
| Consumo iluminación | kWh/h m2 | 0,05 | 0,05 | 0,05 |
| Consumo climatización | kWh/h m2 | 0,2 | 0,2 | 0,2 |
| Potencia auxiliares técnicos | $k W$ | 50 | 50 | 50 |
| Masa cargado | toneladas | 446,008 | 327,496 | 209,144 |

|  |  | AVE MPA-BAR 300 | AVE MPA-BAR 250 | AVE MPA-BAR 120 |
| :--- | :--- | :--- | :--- | :--- |
| Consumo directo de energía final |  | s103 | s130 | s465 (Civia) |
| Energía para vencer resistencia mecánica al avance en recta | kWh | 581,46 | 384,12 | 218,30 |
| Energía para vencer la resistencia adicional al avance en curvas | $k W h$ | 88,94 | 65,31 | 41,71 |
| Energía para vencer la resistencia de la entrada aire | $k W h$ | 1.529,67 | 814,91 | 249,19 |
| Energía para vencer la resistencia aerodinámica en cielo abierto | kWh | 6.485,83 | 3.858,24 | 399,47 |
| Energía adicional para vencer la resistencia aerodinámica en túnel | kWh | 247,78 | 147,40 | 15,26 |
| Energía adicional para vencer la resistencia aerodinámica debida al viento exterior | kWh | 1,80 | 1,54 | 0,69 |
| Energía cinética | kWh | 416,13 | 187,27 | 27,70 |
| Energía cinética empleada en vencer la resistencia al avance | kWh | 45,41 | 15,35 | 0,73 |
| Energía cinética disipada en reducciones de velocidad (-empleada resistencia al avance) sin conduccion econonomica | kWh | 370,71 | 171,92 | 26,97 |
| Energía potencial disipada en el freno en pendientes sin conducción económica | kWh | 936,62 | 1.011,27 | 1.596,48 |
| Energía potencial consumida por dif. de altitud entre extremos | $k W h$ | 0,00 | 0,00 | 0,00 |
| Energía consumida por los aux. comerciales (iluminación) | kWh | 69,14 | 56,83 | 83,62 |
| Energía consumida por los aux. comerciales (climatización) | kWh | 276,55 | 227,32 | 334,50 |
| Energia consumida por los auxiliares técnicos | $k W h$ | 92,17 | 110,60 | 230,42 |
| Energía (útil) consumida en llantas y auxiliares | $\boldsymbol{k W h}$ | 10.680,65 | 6.849,46 | 3.196,61 |
| Perdidas en la locomotora tracción (por rendimiento) | kWh | 1.530,53 | 964,50 | 380,75 |
| Pérdidas en la alimentacion de auxiliares | kWh | 77,27 | 69,66 | 114,45 |
| Energía (final) importada en pantógrafo (o boca entrada depósito gasóleo) | kWh | 12.288,45 | 7.883,61 | 3.691,80 |

### III.8. Consumo energético

**Consumo y emisiones por tren y kilómetro**

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-099.jpg?height=1656&width=3188&top_left_y=825&top_left_x=127)

Consumo y emisiones por plaza real a los 100 km
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-100.jpg?height=1734&width=3254&top_left_y=808&top_left_x=127)

**Desglose de la energía importada**

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-101.jpg?height=1437&width=3251&top_left_y=958&top_left_x=161)

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-102.jpg?height=715&width=954&top_left_y=547&top_left_x=633)
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-102.jpg?height=687&width=1051&top_left_y=569&top_left_x=1914)
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-102.jpg?height=710&width=965&top_left_y=1377&top_left_x=650)
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-102.jpg?height=721&width=982&top_left_y=1366&top_left_x=1894)

Resistencias mecánicas
Energía disipada en el freno (no devuelta)
\$ Energía que se puede devolver por el freno regenerativo

- Resistencia aerodinámica
- Consumo de auxiliares

![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-103.jpg?height=1521&width=948&top_left_y=677&top_left_x=625)
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-103.jpg?height=657&width=879&top_left_y=694&top_left_x=1919)
![](https://cdn.mathpix.com/cropped/59785712-3b00-4356-b1ea-15b3f9594535-103.jpg?height=701&width=871&top_left_y=1494&top_left_x=1944)

- Resistencias mecánicas
- Energfa disipada en el freno (no devuelta)
- Energfa que se puede devolver por el freno regenerativo

Resistencia aerodinámica
Consumo de auxiliares

Los análisis de consumo y emisiones energéticas presentan una variabilidad significativa según el tipo de vehículo ferroviario y el perfil de servicio considerado. Esta variabilidad refleja las diferentes características técnicas, velocidades operacionales, perfiles de carga de viajeros, y configuraciones de línea. Para poder establecer comparaciones significativas entre diferentes servicios ferroviarios y evaluar su eficiencia relativa, es imprescindible homogenizar previamente tanto la capacidad nominal de transporte como la distancia recorrida por cada vehículo. 

Un aspecto fundamental en estos análisis es que el peso relativo de cada componente del consumo total (resistencia mecánica, resistencia aerodinámica, energía disipada en frenado, auxiliares técnicos y comerciales) varía considerablemente en función del tipo de tren y del servicio específico. Por ejemplo, un tren de alta velocidad en línea plana presenta un perfil de consumo muy diferente al de un tren convencional en línea montañosa, o al de un tren de carga en recorrido mixto. Esta diferencia de composición del consumo total requiere análisis individualizado para cada servicio y permite identificar oportunidades específicas de mejora operacional y eficiencia energética.

## Capítulo IV Bibliografía

- Díaz de Villegas, J.M. (2003) Ferrocarriles. Apuntes de clase. E.T.S. Ing. Caminos, Canales y Puertos Santander.
- García Álvarez, A. (2022) Manual de ferrocarriles. El sistema ferroviario español. Ed. Garceta.
- M. Melis y F. Gonzalez, Ferrocarriles metropolitanos. Tranvías, metros ligeros y metros convencionales. $3^{\mathrm{a}} \mathrm{Ed}$., Colegio de Ingenieros de Caminos, Canales y Puertos., 2008.
- Proyecto ElecRail. [En línea]. Available: http://www.investigacionffe.es/elecrail_publicaciones.asp.
- Gonzalez Franco, I. (2021) Apuntes de Dinámica del ferrocarril: Esfuerzos de tracción y resistencias al avance. Modelos de Cálculo de Energía Consumida. Máster en Ingeniería Ferroviaria UC-Mafex.

