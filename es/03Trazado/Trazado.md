---
layout: home   # or 'Inicio', or 'home', whatever your main index uses
title: 3. Trazado    # Spanish title
lang: es          # <--- THIS IS THE KEY PART
permalink: /es/03Trazado/   # Fixed to avoid conflict
nav_order: 3
parent: Inicio
---

# Diseño Geométrico y Trazado de Vías Férreas

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

## Capítulo I Generalidades

### I.1 Fuerza Centrifuga:

Cuando una composición ferroviaria transita desde un segmento rectilíneo hacia una trayectoria curva, experimenta la acción de una fuerza transversal conocida como **fuerza centrífuga** ( $$\boldsymbol{F}_{\mathbf{c}}$$ ), cuya magnitud se expresa mediante la siguiente relación fundamental.

$$
F_{c}=m \cdot \alpha_{c}=\frac{m \cdot V^{2}}{R} \quad \text { donde: } \quad \alpha_{c}=\frac{V^{2}}{R}
$$

En esta formulación matemática, la variable m representa la masa total del tren, V designa la velocidad instantánea de desplazamiento y R corresponde al valor del radio de curvatura del elemento geométrico circular. La aceleración centrífuga $$\left(\alpha_{c}\right)$$ constituye un parámetro determinante que permite cuantificar la intensidad del efecto dinámico transversal.

Desde una perspectiva práctica, cuando una composición se desplaza a 100 km/h a través de una curva cuyo radio de curvatura es de 350 metros, la aceleración centrífuga resultante alcanza aproximadamente 2,2 m/s². Considerando los criterios de confort establecidos en la ingeniería ferroviaria, el valor máximo de aceleración que un viajero puede tolerar sin experimentar molestias significativas se sitúa en torno a 1 m/s².

Para mitigar los efectos perjudiciales de esta aceleración sin compensar, la solución técnica contempla la implementación estratégica del **peralte de la vía** y la incorporación de **curvas de transición** que permiten una variación gradual de la curvatura.

### I.2 Aceleración Centrifuga

Cuando una composición ferroviaria transita por una trayectoria curva bajo la influencia de **aceleraciones no compensadas**, se generan una serie de efectos adversos sobre múltiples componentes del sistema ferroviario.

En relación con el comportamiento dinámico del material rodante, la presencia de aceleraciones transversales sin compensar ocasiona la generación de esfuerzos dinámicos considerables en las **interfaces rueda-carril**, especialmente en los puntos de tangencia de entrada y salida de los elementos curvos. Estos esfuerzos, combinados con los fenómenos oscilatorios inherentes al movimiento del material rodante, pueden bajo determinadas circunstancias de velocidad elevada originar situaciones de inestabilidad que potencialmente pueden derivar en fenómenos de descarrilamiento o incluso vuelco de la composición. Adicionalmente, la demanda excesiva impuesta a los sistemas de suspensión de los vehículos genera incrementos significativos en los costos de mantenimiento y conservación.

La infraestructura vial experimenta también efectos perjudiciales derivados de estas aceleraciones sin compensar. Se produce un patrón de desgaste diferencial entre ambas cabezas de carril, con mayor intensidad en el carril exterior de la curva. Aparecen fenómenos de degradación transversal de la estructura de la vía, incremento en la carga de trabajo de los sistemas de sujeción y tendencia al volcamiento del carril situado en la parte exterior de la curva.

Desde la perspectiva del usuario del transporte ferroviario, estos efectos generan consecuencias negativas directas tales como sensaciones de incomodidad, mareos y percepción de movimientos laterales desagradables. En contextos de transporte de carga, estos fenómenos pueden ocasionar el desplazamiento no deseado de las mercancías transportadas dentro de los vehículos de carga.

{: .highlight }
Para neutralizar estos efectos desfavorables sobre la seguridad operacional y el confort de los usuarios, se implementa una estrategia geométrica consistente en **elevar progresivamente el carril** situado en la parte exterior de la curva respecto al carril interior. Esta inclinación transversal de la plataforma genera una reorientación de la resultante de fuerzas actuantes sobre la masa del vehículo, produciéndose su alineación respecto a la perpendicular al plano de la vía. Como consecuencia de esta configuración geométrica, la aceleración lateral perturbadora desaparece efectivamente, mejorando simultáneamente las condiciones de seguridad y confort en la circulación.

## Capítulo II Peralte

La implementación del peralte en la geometría de las vías ferroviarias constituye una variable fundamental de diseño que puede ser cuantificada y expresada mediante dos enfoques metodológicos alternativos, cada uno con sus particularidades y aplicaciones específicas en contextos operacionales distintos.
**sobreelevación**, es decir, la diferencia de cota vertical existente entre la cabeza del carril situado en la parte interior de la curva y la cabeza del carril ubicado en la parte exterior. Esta magnitud se mide habitualmente en milímetros y constituye la metodología tradicional empleada históricamente en España. La adopción de este criterio presenta ciertas limitaciones operacionales, ya que requiere la definición de valores diferenciados de sobreelevación máxima, insuficiencia de peralte y exceso de peralte en función específica del ancho de vía disponible. En contextos donde se implementa un tercer carril para permitir la circulación de composiciones con dos anchos de vía distintos, esta metodología obliga a establecer dos valores de sobreelevación diferenciados para cada ancho, lo que complica el diseño operacional. Cuando se incorporan incrementos de sección transversal (sobreanchos) en determinados tramos para mejorar la geometría de la curva, es necesario aumentar proporcionalmente el valor de sobreelevación para mantener la inclinación transversal que compensa efectivamente la fuerza centrífuga. En estas situaciones, los valores admisibles de peralte serán inferiores a aquellos empleados sin sobreancho, particularmente en trazados curvos de pequeño radio que demandan peralte máximo. Desde una perspectiva de documentación técnica y representación gráfica, la sobreelevación siempre adopta un valor numérico positivo, por lo que es necesario incorporar información adicional en listados y diagramas para indicar explícitamente la dirección de la inclinación de la vía.

El segundo enfoque describe el peralte mediante la **inclinación transversal**
El segundo enfoque describe el peralte mediante la inclinación transversal expresada en porcentaje. Este criterio presenta la ventaja significativa de ser independiente del ancho de vía específico, permitiendo la aplicación de criterios unificados de insuficiencia, exceso y valor máximo de peralte independientemente del ancho de vía con el que se esté trabajando. La asignación de signo al peralte sigue criterios de orientación: se considera positivo cuando el radio de curvatura es positivo, es decir, cuando la curva se desarrolla hacia la derecha en el sentido de avance; será negativo en el caso contrario. Desde una perspectiva técnica comparativa, el enfoque español basado en sobreelevaciones presenta desventajas en la coherencia de criterios, por lo que la adopción de la inclinación transversal como variable fundamental constituiría una mejora significativa. Sin embargo, la necesidad de mantener homogeneidad con estándares internacionales vigentes, donde predomina el uso de sobreelevaciones, limita la implementación de este cambio metodológico.

En términos de configuración geométrica práctica de la vía, cuando las dos cabezas de carril se encontraran situadas en un mismo plano horizontal, la fuerza centrífuga actuaría impulsar la composición hacia el exterior de la curva, originando una distribución heterogénea de las cargas entre ambas cabezas de carril. Esta situación generaría condiciones de riesgo de descarrilamiento, movimiento inestable de rodadura, aceleraciones laterales de considerable magnitud y deficiencias significativas en los niveles de confort para pasajeros y carga. La solución técnica contempla la inclinación del plano de la vía hacia el interior de la curva, modificando la orientación de la resultante de las fuerzas que actúan sobre la masa vehicular. Esta resultante debe situarse idealmente lo más cercana posible al eje longitudinal de la vía, manteniendo siempre su punto de aplicación entre las áreas de apoyo de las ruedas. Esta configuración permite que la reacción del carril exterior resista el momento de vuelco potencial.


![ec5f2b6b1cc2209cf7b710419368d3cc_MD5]({{ site.baseurl }}/assets/images/ec5f2b6b1cc2209cf7b710419368d3cc_MD5.webp){: width="263" height="297"}

![7ff5894a80602f37fddd5f1305dbdc43_MD5]({{ site.baseurl }}/assets/images/7ff5894a80602f37fddd5f1305dbdc43_MD5.webp){: width="280" height="292"}

[Ferrocarriles metropolitanos: tranvías, metros ligeros y metros convencionales. Manuel Melis](https://www.casadellibro.com/libro-ferrocarriles-metropolitanos-tranvias-metros-ligeros-y-metros-c-onvencionales/9788438002155/834727?srsltid=AfmBOoqHTSmWcrQ8IAJo9HKfczQIgJ63ibvgMAugypBX2CqleJAaC4pz)


### II.1 Peralte Teórico

{: .highlight }
El peralte se define operativamente como el desnivel vertical $$\boldsymbol{z}$$ entre las dos cabezas de carril, siendo esta diferencia de cota medida en una sección perpendicular al eje de la vía. Cuando se implementa un valor de peralte que compensa íntegramente la manifestación de la fuerza centrífuga, la resultante $$\boldsymbol{R}$$ de la composición de la fuerza centrífuga $$\boldsymbol{F}_{\mathbf{c}}$$ y el peso gravitatorio $$\boldsymbol{W}$$ adquiere una orientación normal respecto al plano definido por la vía. Esta configuración específica se designa como **peralte teórico** o **peralte ideal**.

Mediante consideraciones geométricas y dinámicas, se puede establecer la relación entre la tangente del ángulo de inclinación del plano de la vía:
$$\tan \alpha=\frac{F_{c}}{W}=\frac{m \cdot \frac{V^{2}}{R}}{m \cdot g}=\frac{V^{2}}{g \cdot R}$$

De forma simultánea, la geometría del peralte permite expresar:

$$
\sin \alpha=\frac{z}{a} \rightarrow \tan \alpha=\frac{z}{\sqrt{a^{2}-z^{2}}}
$$

![65f0e2b9bb95c5013a69de0923012a03_MD5]({{ site.baseurl }}/assets/images/65f0e2b9bb95c5013a69de0923012a03_MD5.webp){: width="506" height="478"}

[Ferrocarriles metropolitanos: tranvías, metros ligeros y metros convencionales. Manuel Melis](https://www.casadellibro.com/libro-ferrocarriles-metropolitanos-tranvias-metros-ligeros-y-metros-c-onvencionales/9788438002155/834727?srsltid=AfmBOoqHTSmWcrQ8IAJo9HKfczQIgJ63ibvgMAugypBX2CqleJAaC4pz)

En sistemas ferroviarios españoles bajo la administración de RENFE, operando con carriles UIC 60 que presentan una anchura de cabeza de 72 milímetros, el ancho de vía resulta ser:

$$
a=1,668+0,072=1,740 \mathrm{~m}
$$

Para sistemas de transporte urbano tipo metro con ancho de vía de 1,445 metros y empleando carriles UIC 54 con anchura de cabeza de 70 milímetros:

$$
a=1,445+0,070=1,515 m
$$

Estableciendo la igualdad entre las dos expresiones derivadas del análisis del polígono de fuerzas y de la geometría del peralte, se obtiene la expresión matemática que proporciona el valor exacto del peralte requerido por una composición circulando a velocidad V en una trayectoria curva de radio R para anular completamente la manifestación de la fuerza centrífuga:

$$
\frac{V^{2}}{g \cdot R}=\frac{z}{\sqrt{a^{2}-z^{2}}} \rightarrow z=\frac{a \cdot V^{2}}{\sqrt{g^{2} \cdot R^{2}+V^{4}}}
$$

Para ilustrar la aplicación práctica de estas relaciones fundamentales, consideremos el caso específico de un tren de alta velocidad (AVE) circulando a la velocidad nominal de 300 km/h (equivalente a 83,3 m/s), atravesando una trayectoria curva cuyo radio de curvatura es de 7000 metros. Empleando el ancho de vía internacional estándar de 1,435 metros más la anchura de carril de 0,072 metros, el peralte teórico necesario resulta ser:

$$
z=\frac{a \cdot V^{2}}{\sqrt{g^{2} \cdot R^{2}+V^{4}}}=\frac{1,507 \cdot(83,3)^{2}}{\sqrt{(9,8)^{2} \cdot 7000^{2}+(83,3)^{4}}}=0,1516 m
$$

El ángulo de inclinación transversal resultante se calcula mediante:

$$
\sin \alpha=\frac{z}{a}=\frac{0,1516}{1,507}=0,1006 \rightarrow \alpha=5,77^{\circ}
$$

Históricamente, en desarrollos anteriores de la ingeniería ferroviaria se realizaba una aproximación simplificadora donde se asimilaba el seno del ángulo a la tangente del mismo, lo que facilitaba los cálculos antes de la era computacional:

$$
\sin \alpha \cong \tan \alpha=\frac{z}{a} \rightarrow \frac{z}{a}=\frac{V^{2}}{g \cdot R} \rightarrow z=\frac{a \cdot V^{2}}{g \cdot R} \rightarrow z_{t, \max }=\frac{a \cdot V_{\max }^{2}}{g \cdot R}
$$

A partir de esta aproximación se derivaron las expresiones matemáticas simplificadas que han sido aplicadas históricamente en España para el cálculo práctico, siendo las variables expresadas en unidades de: z en milímetros, a en metros, g en m/s², V en km/h y R en metros:

$$
\begin{gathered}
\frac{z}{1000}=\frac{a}{g} \cdot\left(\frac{1000}{3600}\right)^{2} \cdot \frac{V^{2}}{R} \\
z=13,7 \cdot \frac{V^{2}}{R} \text { ancho RENFE } \quad(a=1,668+0,070) \\
z=11,8 \cdot \frac{V^{2}}{R} \text { ancho UIC } \quad(a=1,435+0,070)
\end{gathered}
$$

### II.2 Aceleración sin compensar
**aceleración sin compensar** varía en función de la velocidad específica de circulación. Esta variabilidad implica que ciertas composiciones ferroviarias experimentarán una insuficiencia en la magnitud del peralte implementado, mientras que otras soportarán un exceso del mismo. Para ilustrar esta problemática, consideremos una curva de 1.000 metros de radio desarrollada en una vía de ancho RENFE con dimensiones $$(\mathrm{a}=1,668+0,072=1,740 \mathrm{~m})$$:

| Tipo de composición | Velocidad | Peralte requerido |
| :--- | :--- | :--- |
| TALGO | 160 km/h | 350 mm |
| Tren de mercancías | 80 km/h | 88 mm |

Esta situación heterogénea evidencia la necesidad de implementar un **peralte de compromiso**
Esta situación heterogénea evidencia la necesidad de implementar un peralte de compromiso que no satisface completamente los requerimientos de ninguno de los tipos de composición, pero que representa una solución técnica equilibrada.

Desde el punto de vista del análisis de fuerzas, supongamos que una composición requiere un ángulo de peralte $$\alpha$$ (correspondiente a un desnivel z), pero la vía implementa únicamente un ángulo $$\beta$$ (desnivel $$\boldsymbol{z}_{\boldsymbol{p}}$$). En este análisis, la fuerza centrífuga total se representa mediante el segmento AC, mientras que el peralte implementado compensa solamente una porción de dicha fuerza, correspondiente al segmento AB que representa la fuerza centrífuga parcialmente compensada $$(\mathbf{F}_{\mathbf{c}})$$.

![a3ba82dc74052ffa54d333f6cc7c4007_MD5]({{ site.baseurl }}/assets/images/a3ba82dc74052ffa54d333f6cc7c4007_MD5.webp){: width="459" height="416"}

[Ferrocarriles metropolitanos: tranvías, metros ligeros y metros convencionales. Manuel Melis](https://www.casadellibro.com/libro-ferrocarriles-metropolitanos-tranvias-metros-ligeros-y-metros-c-onvencionales/9788438002155/834727?srsltid=AfmBOoqHTSmWcrQ8IAJo9HKfczQIgJ63ibvgMAugypBX2CqleJAaC4pz)

La fuerza centrífuga que permanece sin compensación se designa como $$\boldsymbol{F}_{\boldsymbol{c}, \mathbf{s c}}$$ y corresponde al segmento BC del diagrama de fuerzas. Mediante análisis vectorial podemos establecer las siguientes relaciones:

$$F_{c, S c}=B C=A C-A B=W \cdot \tan \alpha-W \cdot \tan \beta$$

Expandiendo esta expresión en función de los parámetros físicos fundamentales:

$$F_{c, s c}=W \cdot\left[\frac{F_{c}}{W}-\frac{z_{p}}{a}\right]=m \cdot g \cdot\left[\frac{m \cdot V^{2}}{m \cdot g \cdot R}-\frac{z_{p}}{a}\right]=m \cdot\left[\frac{V^{2}}{R}-\frac{g \cdot z_{p}}{a}\right]$$

Por consiguiente, la aceleración sin compensar $$\alpha_{s c}$$ que experimenta la composición puede expresarse como:

$$\alpha_{s c}=\frac{V^{2}}{R}-\frac{g \cdot z_{p}}{a}$$

![b1b2f06c7c6b23a7140abe6c56460302_MD5]({{ site.baseurl }}/assets/images/b1b2f06c7c6b23a7140abe6c56460302_MD5.webp)

### II.3 Insuficiencia de peralte
{: .highlight }
Cuando la vía se encuentra provista de un peralte $$\boldsymbol{z}_{\boldsymbol{p}}$$ cuya magnitud es insuficiente para compensar íntegramente la acción de la fuerza centrífuga, se define la **insuficiencia de peralte**
Cuando la vía se encuentra provista de un peralte $$\boldsymbol{z}_{\boldsymbol{p}}$$ cuya magnitud es insuficiente para compensar íntegramente la acción de la fuerza centrífuga, se define la insuficiencia de peralte (designada como I) como la diferencia dimensional entre el peralte teórico requerido z y el peralte implementado $$\boldsymbol{z}_{\boldsymbol{p}}$$.

Mediante consideraciones geométricas y dinámicas, podemos establecer que:
$$\tan \alpha=\frac{F}{W}=\frac{m \cdot \frac{V^{2}}{R}}{m \cdot g}=\frac{V^{2}}{g \cdot R}$$

La geometría del peralte implementado con insuficiencia se expresa mediante:
$$\sin \alpha=\frac{z_{p}+I}{a} \approx \tan \alpha$$ (cuando $$\alpha$$ es un ángulo pequeño)

![f4fafd23747f45cae48bcc1dbd9efe2f_MD5]({{ site.baseurl }}/assets/images/f4fafd23747f45cae48bcc1dbd9efe2f_MD5.webp)

Igualando ambas expresiones para ángulos pequeños, donde la aproximación $$\tan \alpha \approx \sin \alpha$$ es válida:

$$
\frac{z_{p}+I}{a} \approx \frac{V^{2}}{g \cdot R}
$$

Desarrollando algebraicamente para obtener el valor de la insuficiencia de peralte:

$$
I=\frac{a \cdot V^{2}}{g \cdot R}-z_{p}=z_{t, \max }-z_{p}
$$

Considerando la relación fundamental entre la aceleración sin compensar y la insuficiencia de peralte:

$$
\alpha_{s c}=\frac{V^{2}}{R}-\frac{g \cdot z_{p}}{a}
$$

Multiplicando esta expresión por el cociente entre el ancho de vía y la gravedad:

$$
I=\alpha_{S C} \cdot \frac{a}{g}
$$

![6cf709c43555374bcdad6dd82fb22357_MD5]({{ site.baseurl }}/assets/images/6cf709c43555374bcdad6dd82fb22357_MD5.webp)

### II.4 Exceso de peralte

Contrariamente al caso de insuficiencia, cuando el peralte implementado supera el valor requerido teóricamente para una velocidad específica de circulación, el fenómeno se designa como exceso de peralte y se denota mediante la variable E. En esta situación, siendo E el exceso de peralte:

$$
\frac{z-E}{a}=\frac{V^{2}}{g \cdot R}
$$

El exceso de peralte genera una aceleración transversal sin compensar dirigida hacia el interior de la curva, que se expresa mediante:

$$
E=\frac{\alpha_{S C} \cdot a}{g}
$$

![11cf9b19467aec1f535870c97f984899_MD5]({{ site.baseurl }}/assets/images/11cf9b19467aec1f535870c97f984899_MD5.webp)

Es conveniente señalar que en contextos operacionales prácticos, las composiciones de movimiento lento, particularmente los trenes de transporte de carga, constituyen tipos de tráfico para los cuales no es necesario imponer limitaciones estrictas en la aceleración sin compensar, ya que el confort de los pasajeros no constituye una consideración determinante.

### II.5 Peralte practico

#### II.5.1 Trafico heterogéneo

Cuando la infraestructura ferroviaria se encuentra sujeta a la circulación de múltiples categorías de composiciones con características operacionales heterogéneas, la solución de diseño requiere la adopción de un peralte de compromiso que equilibre los requerimientos conflictivos de los diferentes tipos de tráfico.

Esta estrategia de compromiso debe fundamentarse en consideraciones técnicas profundas respecto de la composición específica del tráfico que se opera sobre la línea en cuestión. El objetivo es implementar un peralte que minimice los efectos adversos tanto para el comportamiento dinámico de las composiciones como para la integridad de la infraestructura, mientras simultáneamente se respetan los criterios de confort y seguridad de los usuarios del transporte.

En la práctica española, la metodología tradicionalmente aplicada ha consistido en establecer el peralte práctico mediante la relación:

$$
z_{p}=\frac{2}{3} \cdot z_{t}
$$

Existen diversos criterios metodológicos alternativos para determinar el peralte de compromiso:

1. Implementación directa del criterio de los dos tercios: $$z_{p}=\frac{2}{3} \cdot z_{t}$$, lo que genera $$z=13,7 \cdot \frac{V_{\text {max }}^{2}}{R} \cdot \frac{2}{3} \approx 9 \cdot \frac{V_{\text {max }}^{2}}{R}$$ para ancho RENFE y $$z=11,8 \cdot \frac{V_{\text {max }}^{2}}{R} \cdot \frac{2}{3} \approx 8 \cdot \frac{V_{\text {max }}^{2}}{R}$$ para ancho UIC.

2. Cálculo del peralte para una velocidad reducida: $$z_{p}$$ determinado para $$V=0,8 \cdot V_{\text {max }}$$

3. Utilización de una velocidad media ponderada: $$z_{p}$$ obtenida para $$V=\sqrt{\frac{V_{\text {max }}^{2}+V_{\text {min }}^{2}}{2}}$$

4. Aplicación de una velocidad media ponderada por frecuencia de circulación: $$V=\sqrt{\frac{\sum_{m} V_{m}^{2} \cdot N_{m}}{\sum_{m} N_{m}}}$$

Donde $$V_{m}$$ representa la velocidad de circulación característica de cada categoría específica de tren m, y $$N_{m}$$ designa el número de composiciones pertenecientes a cada categoría m que utilizan la infraestructura durante un período de referencia.

### II.6 Limitaciones de los valores del peralte

En el establecimiento de los límites permisibles para los valores de peralte que pueden implementarse en una línea ferroviaria, se observa que las restricciones más rigurosas provienen de consideraciones relacionadas con la comodidad del usuario del transporte de viajeros. Afortunadamente, las limitaciones derivadas de potenciales problemas en los vehículos o en la infraestructura de la vía son menos restrictivas.

En cuanto a la clasificación del material rodante ferroviario, la normativa vigente establece diferentes categorías que se caracteriza por los máximos valores admisibles de aceleración transversal sin compensar:

- Tipo "Normal": Aceleración máxima de $$0,65 \mathrm{~m} / \mathrm{s}^{2}$$ (designación sin letra de complemento adicional para la velocidad máxima).
- Tipo A: Aceleración máxima de $$1 \mathrm{~m} / \mathrm{s}^{2}$$.
- Tipo B: Aceleración máxima de $$1,2 \mathrm{~m} / \mathrm{s}^{2}$$.
- Tipo C: Aceleración máxima de $$1,5 \mathrm{~m} / \mathrm{s}^{2}$$.
- Tipo D: Aceleración máxima de $$1,8 \mathrm{~m} / \mathrm{s}^{2}$$.

#### II.6.1 Trenes rápidos

La investigación experimental realizada en el ámbito de la ingeniería ferroviaria ha demostrado de forma consistente que el criterio limitante fundamental es el confort del pasajero, siendo más restrictivo que los criterios de seguridad estructural que limitan el potencial vuelco del material rodante. Cuando se implementan diseños que respetan íntegramente los estándares de confort de los viajeros, los coeficientes de seguridad respecto del vuelco adquieren valores considerablemente elevados, típicamente en el rango de 6 a 10.

La percepción de confort durante la circulación por trayectorias curvas se encuentra directamente condicionada por la magnitud de la aceleración sin compensar experimentada por el pasajero.

Para evaluar adecuadamente la aceleración efectivamente soportada por los pasajeros, es imprescindible considerar los efectos dinámicos del sistema de suspensión del vehículo. El sistema de suspensión está específicamente diseñado para atenuar los efectos adversos de vibraciones transitorias y aceleraciones de carácter aleatorio.

Sin embargo, durante la circulación en trayectorias curvas, el sistema de suspensión introduce complicaciones dinámicas. El efecto de la aceleración transversal provoca la compresión de los amortiguadores situados en el lado exterior de la curva, mientras simultáneamente alarga los amortiguadores del lado interior. Este proceso de deformación diferencial reduce de manera significativa la efectividad del peralte implementado, generando una aceleración sin compensar que supera la que teóricamente debería ocurrir.

Para cuantificar matemáticamente estos efectos de flexibilidad del sistema de suspensión, se introduce el parámetro denominado "coeficiente de flexibilidad" designado como s. La normativa vigente de la UIC establece un límite máximo de $$\boldsymbol{s}=\mathbf{0,4}$$ para clasificar vehículos con suspensión blanda. Históricamente, vehículos fabricados en períodos anteriores presentaban valores de este coeficiente de hasta 0,6, y ejemplares de estas características aún circulan en numerosas redes ferroviarias a nivel mundial.

Las composiciones de diseño moderno, cuando operan a plena capacidad de carga, presentan típicamente un coeficiente de flexibilidad de suspensión en el orden de 0,4.

Aplicando estos principios a casos específicos de operación, pueden determinarse valores representativos de insuficiencia de peralte que son tolerables según las prácticas de distintas administraciones ferroviarias. La expresión matemática general que engloba estos criterios es:

$$
\alpha_{s c} \cdot(1+s)=\frac{V^{2}}{R}-\frac{g \cdot z_{p}}{a} \cdot(1+s)<\alpha_{s c, \text { viajero }}
$$

La normativa técnica ADIF establece los siguientes límites máximos para la aceleración sin compensar permitida según la categoría de tren:

Para composiciones clasificadas como Trenes Normales se especifica una aceleración sin compensar máxima permisible de $$\alpha_{s c} \mathbf{= 0,65} \boldsymbol{m/s^{2}}$$.

Para composiciones clasificadas como Trenes Tipo A se especifica una aceleración sin compensar máxima permisible de $$\mathbf{1,00 ~m/s^{2}}$$.

Para Trenes Tipo B (TALGO pendular), la aceleración sin compensar máxima admisible es de $$\mathbf{1 , 2 0 ~ m} / \mathbf{s}^{\mathbf{2}}$$.

- Normativa para la máxima insuficiencia de peralte admisible:

El valor máximo de insuficiencia de peralte admitido es de I $$=115 \mathrm{~mm}$$.

Para Trenes Tipo A se admite una insuficiencia de peralte máxima de 175 mm (los valores con $$\mathrm{I}=175 \mathrm{~mm}$$ deberán estar aplicados a un máximo del 15\% de las curvas de cada trayecto).

Para Trenes Tipo B (TALGO pendular), la insuficiencia de peralte máxima admisible es de 210 mm .

- Normativa para la máxima insuficiencia de peralte admisible:

Norma europea ENV 13803-1: Se establecen los siguientes valores máximos:

| MÁXIMA INSUFICIENCIA DE PERALTE I (mm) - ENV 13803-1 |  |  |  |  |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Categorías de tráfico |  | Ancho de vía 1,435 m |  |  |  | Ancho de vía 1,668 m |  |  |  |
|  |  | Valores máximos recomendados (1) |  | Valores máximos permitidos |  | Valores máximos recomendados (1) |  | Valores máximos permitidos |  |
|  |  | Mercancías | Viajeros | Mercancías | Viajeros | Mercancías | Viajeros | Mercancías | Viajeros |
| I: Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 80 y $$120 \mathrm{Km} / \mathrm{h}$$. | $$\mathrm{R}<650 \mathrm{~m}$$ | 110 | 130 | 130 | 160 | 125 | 150 | 150 | 185 |
|  | $$\mathrm{R}=650 \mathrm{~m}$$ | 110 | 150 | 130 | 165 | 125 | 170 | 150 | 190 |
| lla: Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 120 y $$160 \mathrm{Km} / \mathrm{h}$$. |  | 110 | 150 | $$160{ }^{(4)}$$ | 165 | 125 | 170 | 185 | 190 |
| llb: Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 160 y $$200 \mathrm{Km} / \mathrm{h}$$. |  | 110 | 150 | $$160{ }^{(4)}$$ | 165 | 125 | 170 | 185 | 190 |

| MÁXIMA INSUFICIENCIA DE PERALTE I (mm) - ENV 13803-1 |  |  |  |  |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Categorías de tráfico |  | Ancho de vía $$1,435 \mathrm{~m}$$ |  |  |  | Ancho de vía 1,668 m |  |  |  |
|  |  | Valores máximos recomendados (1) |  | Valores máximos permitidos |  | Valores máximos recomendados (1) |  | Valores máximos permitidos |  |
|  |  | Mercancias | Viajeros | Mercancias | Viajeros | Mercandias | Viajeros | Mercancias | Viajeros |
| III: Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 200 y $$300 \mathrm{Km} / \mathrm{h}$$. | $$200<\mathrm{v} \leq 250$$ | 100 | 100 | $$150{ }^{(4)}$$ | 150 | 115 | 115 | $$170^{(4)}$$ | 170 |
|  | $$250<v \leq 300$$ | 80 | 80 | $$130^{(3)}$$ | $$130^{(3)}$$ | 90 | 90 | $$150{ }^{(3)}$$ | $$150^{(3)}$$ |
| IV: Líneas de tráfico mixto, con trenes de pasajeros con velocidades hasta $$230 \mathrm{Km} / \mathrm{h}$$ (o $$250 \mathrm{Km} / \mathrm{h}$$ en las mejores lineas) con vehículos incorporando características técnicas especiales. | $$\mathrm{v} \leq 160$$ | 110 | $$160{ }^{(2)}$$ | $$160{ }^{(4)}$$ | $$180^{(2)}$$ | 125 | $$185{ }^{(2)}$$ | $$185{ }^{(4)}$$ | $$205^{(2)}$$ |
|  | $$160<\mathrm{v} \leq 200$$ | - | 140 | - | 160 | - | 160 | -- | 185 |
|  | $$200<\mathrm{v} \leq 230$$ | - | 120 | - | 160 | - | 135 | -- | 185 |
|  | $$230<\mathrm{v} \leq 250$$ | 一 | 100 | - | 150 | - | 115 | -- | 170 |
| V: Lineas de tráfico de viajeros con velocidades máximas comprendidas entre 250 y $$300 \mathrm{Km} / \mathrm{h}$$. | $$\mathrm{v}=250$$ | - | 100 | - | 150 | - | 115 | -- | 170 |
|  | $$\mathrm{v}>250$$ | - | 80 | - | $$130^{(3)}$$ | - | 90 | -- | $$150^{(3)}$$ |

**NOTAS:**

- Al definir el trazado se deberá intentar mantener la insuficiencia de peralte 20 mm ( 25 mm con ancho 1,668 $$\mathrm{m})$$ por debajo del valor máximo recomendado en ancho $$1,435 \mathrm{~m}$$.
- Estos valores sólo son aplicables para situaciones con variaciones progresivas de la insuficiencia de peralte, en las que no haya discontinuidades, con velocidades superiores a $$80 \mathrm{~km} / \mathrm{h}$$.
(1) En vía con juntas, los valores de insuficiencia del peralte serán los especificados en el contrato.
(2) Estos valores sólo se aplicarán a vehículos con características mecánicas especiales.
(3) Se puede utilizar una insuficiencia de peralte de 150 mm ( 170 mm con ancho $$1,668 \mathrm{~m}$$ ) en vía sin balasto para velocidades superiores a $$250 \mathrm{Km} / \mathrm{h}$$.
(4) Estos valores sólo se aplicarán a vagones de mercancías con características mecánicas especiales, similares a las de los vehículos de viajeros.

#### II.6.2 Trenes lentos

El proceso de determinación del exceso de peralte admisible requiere previamente el conocimiento de la velocidad mínima operacional a la que las composiciones lentas circulan a través de las curvas. Una vez conocido este parámetro, se determina el máximo exceso de peralte que puede tolerarse sin comprometer los criterios de seguridad y operacionalidad.

Desde la perspectiva del equilibrio de fuerzas, si existiera una distribución estadísticamente equiparable entre composiciones lentas y rápidas y si sus efectos dinámicos sobre la infraestructura fueran análogos, la estrategia óptima consistiría en igualar el exceso de peralte con la insuficiencia de peralte (E = I). Esta configuración garantizaría un equilibrio completo de esfuerzos transversales y produciría patrones de desgaste simétricos en ambas cabezas de carril.

Sin embargo, históricamente, la realidad operacional ha presentado una distribución desequilibrada, con predominancia de composiciones lentas sobre composiciones rápidas. En tales circunstancias, si se utilizaran valores de $$\mathrm{I}=\mathrm{E}=115 \mathrm{~mm}$$, los efectos perjudiciales sobre el carril interior se verían significativamente amplificados. Por esta razón, las administraciones ferroviarias han establecido límites máximos más restrictivos para el exceso de peralte, típicamente en el rango de 60 a 100 milímetros, con el objetivo de equilibrar adecuadamente el patrón de desgaste entre ambas cabezas de carril.

La situación operacional actual se caracteriza por una tendencia progresiva hacia el predominio del tráfico de viajeros en muchas redes ferroviarias, lo que modifica las consideraciones históricas que fundamentaban los límites anteriores.

- Normativa para el máximo

- exceso de peralte admisible:

| MÁXIMO EXCESO DE PERALTE E(mm) - N.R.V. 0-2-0.0. ( $$\mathrm{T}=$$ Mles de TKBR/Dia y Via) |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- |
| VELOCIDAD DE PROYECTO ( $$\mathrm{Km} / \mathrm{h}$$ ) |  | $$\mathrm{V}=140$$ | 140<v-160 | $$160<v-200$$ | $$200<v-250$$ |
| NUEVAS LINEAS Y DESDOBLAMIENTO DE LINEAS ACTUALES CON MODIFICACION DEL TRAZADO | $$\mathrm{T}>45$$ | 80 | 80 | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 60$$ Mercanclas: 80 | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 60$$ Mercanclas: 80 |
|  | $$25<\mathrm{T} \leq 45$$ | 90 | 90 | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 70$$ Mercanclas: 90 | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 70$$ Mercanclas: 90 |
|  | $$10<\mathrm{T} \leq 25$$ | 100 | 100 | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 90$$ Mercanclas: 100 | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 90$$ Mercanclas: 100 |
|  | $$\mathrm{T} \leq 10$$ | 110 | 110 | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 90$$ Mercanclas: 110 | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 90$$ Mercanclas: 110 |
| MEJORA DE LINEAS ACTUALES POR OBRAS <br> (Renovaciones y rehabilliaciones de via) | $$\mathrm{T}>45$$ | 80 | 80 | Vlajeros: 60 Mercanclas: 80 | - |
|  | $$25<\mathrm{T} \leq 45$$ | 90 | 90 | Viajeros: 70 Mercanclas: 90 | - |
|  | $$10<\mathrm{T} \leq 25$$ | 100 | 100 | Vlajeros: 90 Mercanclas: 100 | - |
|  | $$\mathrm{T} \leq 10$$ | 110 | 110 | Vlajeros: 90 Mercanclas: 110 | - |

| VELOCIDAD DE PROYECTO ( $$\mathrm{Km} / \mathrm{h}$$ ) |  | $$\mathrm{V}=140$$ | $$140<v-160$$ | 160<v-180 | 180<v-200 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| ADAPTACIÓN DE LINEAS ACTUALES PARA CIRCULACION DE TRENES TIPO A SIN LIMITACION DE VELOCIDAD |  |  |  |  |  |
|  | $$\mathrm{T}>45$$ | Máxlmo: 80 Excepc: 105 | Maximo: 80 Excepc: 105 |  |  |
|  |  |  |  | Maximo: 80 Excepcional: 105 Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 60$$ | Maximo: 80 Excepcional: 105 Vlajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 60$$ |
|  |  |  |  | Maximo: 90 | Maximo: 90 |
|  | $$25<\mathrm{T} \leq 45$$ | Máxlmo: 90 | Ехсерс: 115 | Excepcional: 115 | Excepcional: 115 |
|  |  |  |  | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 70$$ | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 70$$ |
|  |  |  |  | Maximo:100 | Maximo:100 |
|  | $$10<\mathrm{T} \leq 25$$ | Maximo:100 | Maximo:100 | Excepcional: 125 | Excepcional: 125 |
|  |  | Excepc: 125 | Ехсерс: 125 | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 90$$ | Vlajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 90$$ |
|  |  | Maximo:110 |  | Maximo:110 | Maximo:110 |
|  | $$\mathrm{T} \leq 10$$ | Excepc: 135 | Maximo:110 | Excepcional: 135 | Excepcional: 135 |
|  |  |  |  | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 90$$ | Viajeros $$\leq 160 \mathrm{~km} / \mathrm{h}: 90$$ |
| Expresion a utillzar: $$\mathrm{E}=116-0,58-\mathrm{T}$$ |  |  |  |  |  |

#### II.6.3 Trenes lentos

b) Norma europea ENV 13803-1

El marco normativo europeo ENV 13803-1 establece los siguientes valores límite máximos para el exceso de peralte en vías con ancho estándar de 1,435 metros:

- Valor máximo recomendado para exceso de peralte: 110 mm.
- Valor máximo permitido excepcional para exceso de peralte: 130 mm.
- Para composiciones de transporte de viajeros se restringe el valor máximo permitido a 110 mm.

Cuando una composición ferroviaria se encuentra en estado de reposo, los pasajeros no experimentan variaciones dinámicas de aceleración, lo que permite la tolerancia de valores más elevados de aceleración sin compensar, llegando a ser admisibles valores de $$\alpha_{s c} \leq 1,5 \mathrm{~m} / \mathrm{s}^{2}$$ bajo esta condición.

Adicionalmente, estudios experimentales han demostrado que no surgen limitaciones operacionales en la generación de fuerzas de fricción suficientes para garantizar el arranque de una composición parada, siempre que la aceleración sin compensar teórica permanezca por debajo de $$\mathbf{1 \,m/s^{2}}$$.

Por consiguiente, el peralte máximo implementable $$\mathbf{z}_{\text{Máx}}$$ debe satisfacer la siguiente condición:

$$
\alpha_{s c}=\frac{g \cdot z_{\max }}{a}-\frac{V^{2}}{R}<1 m/s^{2}
$$

Cuando la composición se encuentra parada ($$V=0$$):

$$
z_{\max }=\frac{a}{g}
$$

Aplicando esta formulación para vías con ancho de $$\mathbf{1,668}$$ metros, se obtiene un valor máximo teóricamente admisible de $$\mathbf{z}_{\text{max}} = \mathbf{178}$$ mm.

Una práctica generalizada en las administraciones ferroviarias consiste en establecer la regla de que el peralte implementado no debe exceder la décima parte del ancho de vía.

Normativa para el peralte máximo admisible:

a) Normativa ADIF

La administración ADIF ha establecido un límite máximo para el peralte implementable de $$\mathbf{160 \,mm}$$. Esta limitación es más restrictiva que la aplicada típicamente por otras administraciones ferroviarias internacionales, proporcionando mayor protección a la integridad estructural del carril.

Trenes parados

b) Norma europea ENV 13803-1

El marco normativo europeo ENV 13803-1 establece los siguientes valores límite máximos para situaciones específicas:

En instalaciones ferroviarias donde la vía corre adyacente a plataformas de embarque de pasajeros se recomienda no exceder valores de $$\mathbf{110 \,mm}$$ de peralte con ancho estándar de 1,435 metros (o $$\mathbf{125}$$ mm con ancho de 1,668 metros).

| PERALTE MÁXIMO ADMISIBLE $$\mathrm{Z}_{\text {Máx }}$$ (mm) - ENV 13803-1 |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- |
| Categorías de tráfico | Ancho $$1,435 \mathrm{~m}$$ |  | Ancho $$1,668 \mathrm{~m}$$ |  |
|  | Valores máximos recomendados | Valores máximos permitidos | Valores máximos recomendados | Valores máximos permitidos |
| I: Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 80 y $$120 \mathrm{Km} / \mathrm{h}$$. | 160 | 180 | 185 | 205 |
| Ila: Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 120 y $$160 \mathrm{Km} / \mathrm{h}$$. | 160 | 180 | 185 | 205 |
| llb : Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 160 y $$200 \mathrm{Km} / \mathrm{h}$$. | 160 | 180 | 185 | 205 |
| III: Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 200 y $$300 \mathrm{Km} / \mathrm{h}$$. | 160 | 180 | 185 | 205 |
| IV: Líneas de tráfico mixto, con trenes de pasajeros con velocidades hasta 230 $$\mathrm{Km} / \mathrm{h}$$ (o $$250 \mathrm{Km} / \mathrm{h}$$ en las mejores lineas) con vehículos incorporando características técnicas especiales. | 160 | 180 | 185 | 205 |
| V: Líneas de tráfico de viajeros con velocidades máximas comprendidas entre 250 y $$300 \mathrm{Km} / \mathrm{h}$$. | 160 | 200 | 185 | 230 |
| Para evitar el riesgo de descarrilamiento en curvas de radio reducido se recomienda que el peralte quede restringido al siguiente valor. <br> Ancho de vía 1,435 m: $$\quad z_{\operatorname{Max}}=\frac{R-50}{1,5} ; \quad$$ Ancho de vía 1,668 m: $$\quad z_{\operatorname{Max}}=\frac{R-50}{0,9}$$ |  |  |  |  |

### II.7 Peralte a utilizar

Para el establecimiento del peralte deben aplicarse las condiciones relativas a los dos tipos de trenes extremos (el más rápido de viajeros y el más lento de mercancías), que han de cumplirse conjuntamente:

Tren mas rapido de viajeros: $$\left[\frac{V_{\text {max }}^{2}}{R}-\frac{g \cdot z}{a}\right] \cdot(1+s)<\alpha_{s c, \text { viajero }}$$

Tren mas lento de mercancias: $$\frac{g \cdot z}{a}-\frac{V_{\text {min }}^{2}}{R}<\frac{g \cdot E}{a}$$

Con este sistema de inecuaciones se puede acotar el valor $$\boldsymbol{z}$$, ó los valores de R y z cuando $$R$$ sea desconocida, (tomando 1/R $$=\mathrm{y}$$, todo se reduce a resolver un sistema lineal).

### II.7 Peralte a utilizar

El proceso de establecimiento del peralte específico a implementar en una infraestructura ferroviaria requiere la aplicación simultánea de dos condiciones de contorno que deben verificarse para los tipos de composición que representan los extremos operacionales del espectro. Específicamente, deben satisfacerse simultáneamente las limitaciones impuestas por la composición más rápida de transporte de viajeros y la composición más lenta de transporte de mercancías.

Para la composición más rápida de viajeros, la inecuación de control es:

$$
\left[\frac{V_{\text{max}}^{2}}{R}-\frac{g \cdot z}{a}\right] \cdot(1+s)<\alpha_{s c, \text { viajero}}
$$

Para la composición más lenta de mercancías, la inecuación de control es:

$$
\frac{g \cdot z}{a}-\frac{V_{\text{min}}^{2}}{R}<\frac{g \cdot E}{a}
$$

Mediante este sistema de inecuaciones simultáneas se puede acotar el rango admisible del valor z, o alternativamente, cuando el radio de curvatura R sea desconocido inicialmente, es posible resolver el sistema estableciendo la sustitución $$1/R = y$$, lo que reduce el problema a la solución de un sistema lineal de desigualdades.

Es imperativo que se respete invariablemente la limitación normativa que establece el peralte máximo permitido para cada línea específica o red ferroviaria. Si se dispusiera de información detallada sobre la distribución estadística exacta del tráfico y su contribución específica a los procesos de deterioro de la infraestructura vial, sería posible determinar con precisión el valor óptimo de peralte que garantizaría un equilibrio perfecto en los efectos dinámicos sobre ambas cabezas de carril, asegurando simultáneamente el cumplimiento de todas las exigencias técnicas relativas a seguridad y confort de los pasajeros.

## Capítulo III Parámetros básicos del trazado

La definición geométrica del trazado ferroviario se fundamenta en la consideración sistemática de tres categorías principales de parámetros, que integran criterios de operacionalidad, seguridad estructural y percepción del usuario:

1. Velocidad de circulación
2. Seguridad operacional
3. Comodidad del viajero

### III.1 VELOCIDAD

La ingeniería de trazados ferroviarios requiere la distinción cuidadosa entre diversos conceptos asociados al término velocidad, ya que cada uno de ellos constituye un parámetro fundamental que condiciona las decisiones de proyecto. La velocidad de circulación de los trenes representa un factor determinante en la definición de la geometría del trazado.

Se establecen las siguientes categorías de velocidad:

#### III.1.1 VELOCIDAD NOMINAL

Se define como velocidad nominal de una composición ferroviaria a la máxima velocidad que teóricamente puede alcanzar bajo las condiciones más favorables de configuración geométrica de la infraestructura vial. Esta magnitud está determinada fundamentalmente por características propias del material rodante, tales como la tipología de la composición (ferrocarriles de viajeros o ferrocarriles de carga) y el estándar técnico específico de la línea sobre la cual opera.

#### III.1.2 VELOCIDAD ESPECIFICA MAXIMA

Se designa como velocidad específica máxima a la velocidad máxima que puede tolerarse para la circulación segura a través de un elemento geométrico específico del trazado, respetando criterios técnicos establecidos de seguridad operacional y confort del usuario.

Es técnicamente deseable que la velocidad específica máxima sea lo más uniforme posible en todos los elementos que constituyen un tramo ferroviario determinado, evitando de esta forma transiciones bruscas que obliguen a reducciones significativas de velocidad cuando las composiciones transitan de un elemento geométrico al siguiente.

Los factores que pueden imponer limitaciones a la velocidad específica máxima incluyen:

- La máxima insuficiencia de peralte admisible en las trayectorias curvas
- Los aparatos de vía que pueden limitar velocidades tanto en vía directa como en vía desviada
- Los túneles, donde intervienen consideraciones de resistencia al avance y variaciones de presión atmosférica dinámica
- Los puentes, con sus limitaciones estructurales específicas
- El galibo cinemático disponible, considerando la proximidad de obstáculos fijos

Simultáneamente, debe definirse una velocidad específica mínima para las trayectorias curvas, de forma que se permita la circulación de composiciones lentas con un exceso de peralte dentro de los márgenes admisibles. Esta configuración mejora significativamente las condiciones de seguridad y confort para las composiciones que operan a velocidades reducidas.

#### III.1.3 VELOCIDAD DE PROYECTO

Se define como velocidad de proyecto a la velocidad de referencia fundamental establecida en base a criterios integrados de seguridad operacional y confort del usuario del transporte.

La velocidad máxima de proyecto debe ser menor o igual a la velocidad específica mínima registrada en cualquiera de los elementos geométricos que integran el tramo en consideración.

Desde una perspectiva económica, es importante señalar que el incremento de la velocidad de proyecto resulta generalmente en aumento de los costos de construcción de la infraestructura y en ampliación del impacto ambiental asociado a la obra de ingeniería.

Es posible que la velocidad nominal de una composición ferroviaria supere la velocidad máxima de proyecto establecida para la línea. En tales circunstancias, se implementan restricciones operacionales que limitan la velocidad real en los tramos afectados.

La velocidad mínima de proyecto se define igualmente en base a criterios de seguridad y confort, debiendo ser mayor o igual a la máxima velocidad específica mínima requerida en cualquiera de los elementos del tramo.

Es también posible que la velocidad nominal de ciertas composiciones sea inferior a la velocidad mínima de proyecto establecida.

#### III.1.4 VELOCIDAD DE RECORRIDO

La velocidad de recorrido se define como la velocidad media que alcanza una composición ferroviaria al recorrer un trayecto determinado, sin considerar en el cálculo las paradas programadas o excepcionales.

Cuando la configuración geométrica del trazado incluye numerosas trayectorias curvas con radios reducidos, la velocidad de recorrido resultante será significativamente inferior a las velocidades nominales de las composiciones. Adicionalmente, resulta problemático recuperar el tiempo perdido en estos tramos mediante incrementos de velocidad en los segmentos rectilíneos, ya que la longitud de estos últimos es limitada.

$$
V_{r}=\frac{\sum_{i=1}^{n} L_{i}}{\sum_{i=1}^{n} \frac{L_{i}}{V_{i}}}
$$

Un análisis detallado revela que un pequeño incremento de velocidad en el segmento más lento del trayecto puede producir mejoras en el tiempo total de recorrido equivalentes a incrementos más significativos de velocidad en los segmentos más rápidos.

Seguridad operacional

La operación segura de composiciones ferroviarias constituye un requisito fundamental e insoslayable en el diseño de cualquier infraestructura ferroviaria. Los criterios de seguridad que deben considerarse en el establecimiento del trazado incluyen:

1. Garantizar márgenes de seguridad adecuados frente a potenciales fenómenos de descarrilamiento de composiciones
2. Establecer márgenes de seguridad suficientes contra el fenómeno de vuelco de material rodante en trayectorias curvas

### III.2 COMODIDAD DEL VIAJERO

La comodidad percibida por el pasajero durante el trayecto constituye un indicador fundamental de calidad del servicio ferroviario. El parámetro más comúnmente utilizado para cuantificar objetivamente esta magnitud es la aceleración experimentada por el pasajero. El pasajero experimenta de forma simultánea dos componentes de aceleración de naturaleza diferente:

1. Aceleraciones sin compensar $$(\alpha_{s c})$$ generadas por insuficiencias o excesos de peralte en las trayectorias curvas
2. Aceleraciones originadas por deficiencias geométricas de la infraestructura $$(\alpha_{d})$$, incluyendo problemas de nivelación longitudinal y transversal, deficiencias de alineación horizontal, características constructivas inadecuadas y movimientos de lazo

$$
\alpha_{v}=\alpha_{s c}+\alpha_{d}
$$

El valor máximo admisible para la aceleración total experimentada por el pasajero $$\alpha_{v}$$ depende de múltiples factores contextuales:

1. La duración total del trayecto: En desplazamientos de larga duración, el pasajero sufre mayor fatiga y estrés derivados de la exposición sostenida a aceleraciones
2. La tipología y características del usuario del transporte: Es necesario considerar la capacidad de tolerancia del pasajero con menor resistencia física, incluyendo ancianos y personas con discapacidades
3. La variabilidad temporal de la aceleración sin compensar: En trayectorias donde experimentan múltiples variaciones bruscas de aceleración, el estrés psicofísico puede incrementarse considerablemente

Es importante señalar que los niveles de aceleración tolerables varían significativamente dependiendo de la postura del pasajero, siendo diferente para pasajeros sentados que para aquellos que viajan de pie.

También resulta fundamental distinguir entre aceleraciones verticales y aceleraciones transversales, cada una con características de tolerancia distintas.

Aceleraciones verticales: Se admiten magnitudes significativamente menores en comparación con aceleraciones transversales de igual magnitud. Las aceleraciones continuas de baja frecuencia en el plano vertical afectan directamente al sistema vestibular y pueden inducir fenómenos de mareo. La percepción negativa es más intensa cuando la aceleración se dirige hacia arriba comparativamente con direcciones hacia abajo.

Aceleraciones transversales: Aunque afectan principalmente a la estabilidad postural del pasajero, generan menor incomodidad comparativamente, a igualdad de magnitud de aceleración, que sus homólogas verticales.

El marco normativo de la SNCF francesa ha establecido criterios específicos para evaluar la comodidad percibida en relación con aceleraciones transversales:

| CRITERIOS DE COMODIDAD EN LA SNCF RESPECTO A LA ACELERACIÓN TRANSVERSAL ADMISIBLE POR EL VIAJERO |  |  |  |
| :--- | :--- | :--- | :--- |
| NIVEL DE COMODIDAD | Aceleración transversal sobre el viajero $$\alpha_{\text{nc, viajero}}\left(\mathrm{m} / \mathrm{s}^{2}\right)$$ |  | Variación de la aceleración transversal sobre el viajero $$\mathrm{d} \alpha_{\mathrm{nc}, \text{viajero}} / \mathrm{dt}\left(\mathrm{m} / \mathrm{s}^{3}\right)$$ |
|  | SENTADO | DE PIÉ |  |
| Muy bueno | 1,0 | 0,85 | 0,30 |
| Bueno | 1,2 | 1,0 | 0,45 |
| Aceptable | 1,4 | 1,2 | 0,70 |
| Aceptable excepcionalmente | 1,5 | 1,4 | 0,85 |

## Capítulo IV Trazado en planta

El perfil en planta de una línea ferroviaria se desarrolla mediante una sucesión ordenada de alineaciones de diferente tipología geométrica:
- Curva de transición y
- Curva circular

Que se representan a través de un eje.

- Vía sencilla: el eje coincide con el eje de la vía
- Vía doble: el eje del trazado coincide con el eje intermedio entre ambos ejes de las vía contiguas.
- Vías de estación: se usa el de la vía general, aunque en estaciones grandes se tratan por separado los diferentes haces de vía.

- Recta
- Curva de transición
- Curva circular

Que se representan a través de un eje que define la geometría de la línea ferroviaria. En vías de carril sencillo, este eje coincide con el eje longitudinal de la vía. En infraestructuras de carril doble, el eje del trazado se corresponde con el eje intermedio entre los dos ejes geométricos de las vías contiguas. En contextos de estaciones ferroviarias complejas, cada haz de vías es tratado como una entidad geométrica independiente, aunque generalmente se utiliza la vía general como referencia.

La orientación del radio de curvatura se define mediante una convención de signos: se asigna signo positivo cuando la curvatura se desarrolla hacia la derecha respecto al sentido de avance del tren, y signo negativo cuando la curvatura se desarrolla hacia la izquierda.

Múltiples parámetros que caracterizan la definición geométrica del trazado se encuentran limitados normativamente con el propósito de cumplir simultáneamente con exigencias de seguridad operacional, comodidad del usuario y conservación de la infraestructura vial. La normativa establece una jerarquía de valores límite:

- Valor recomendable: Es el valor que no debe ser excedido durante la circulación a velocidades máxima o mínima dentro del rango recomendado. Constituye el valor que debe implementarse en la fase conceptual del proyecto.
- Valor límite normal: Es el valor que no debe ser superado cuando la operación ocurre en condiciones normales a velocidades máxima o mínima dentro del rango admisible.
- Valor límite excepcional: Representa una magnitud más desfavorable que el valor límite normal, que puede utilizarse únicamente cuando concurren circunstancias excepcionales debidamente justificadas.

El valor recomendable constituye un parámetro de referencia para condiciones ordinarias de explotación operacional, no siendo un valor de cumplimiento vinculante en todos los casos.

La geometría final del trazado se condiciona fundamentalmente mediante los valores límite normal y excepcional.

### IV.1 CURVAS DE TRANSICION

Entre alineaciones rectilíneas y arcos circulares se implementan curvas de transición geométrica que facilitan la variación gradual tanto de la curvatura como del peralte implementado. En los puntos terminales de estas curvas de transición deben satisfacerse condiciones matemáticas específicas de tangencia y continuidad de la curvatura con las alineaciones rectilínea y circular adyacentes.

La curva de transición más ampliamente utilizada en la ingeniería de trazados ferroviarios es la clotoide (espiral de Euler), caracterizada por una variación lineal de la curvatura en función de la longitud del arco. La ecuación intrínseca que define matemáticamente la clotoide es:

$$
r \cdot s=A^{2} \rightarrow R \cdot L=A^{2}
$$

Donde:
- $$R=$$ Radio de curvatura en cualquier punto del arco de transición
- $$L=$$ Longitud medida del arco de transición desde su punto de inflexión (donde $$R=\infty$$) hasta el punto donde el radio adquiere el valor $$R$$
- $$A=$$ Parámetro característico de la clotoide específica (con dimensiones de longitud)

### IV.2 RADIOS MINIMOS

#### IV.2.1 Limitación por comodidad de los viajeros

Cuando una composición ferroviaria circula a través de una trayectoria curva, la aceleración centrífuga no compensada no debe alcanzar magnitudes que causen incomodidad o malestar excesivo a los pasajeros. Esta consideración requiere la fijación de valores mínimos admisibles para los radios de curvatura implementables en el proyecto.

Es importante recordar que la aceleración sin compensar se encuentra directamente condicionada por la magnitud del peralte implementado en la curva.

#### IV.2.2 Limitación por esfuerzos dinámicos transversales sobre la vía

La infraestructura ferroviaria se somete a esfuerzos dinámicos transversales $$\boldsymbol{H}$$ generados por la circulación de composiciones ferroviarias. Estos esfuerzos pueden descomponerse en dos componentes de naturaleza diferente:

- Un componente cuasi estático $$H_o$$ originado por la porción no compensada de la fuerza centrífuga, cuya magnitud es proporcional a la insuficiencia de peralte I (o exceso en su caso, medida en mm), al ancho de vía a (en mm) y a la carga por eje Q (en toneladas):

$$
H_{o}=\frac{Q \cdot I}{a}
$$

Se ha observado experimentalmente que la distribución de este esfuerzo no es uniforme entre los dos ejes del mismo bastidor, por lo que habitualmente se aplica un factor de mayoración del 20%:

$$
H_{o}=1,20 \cdot \frac{Q \cdot I}{a}
$$

- Un componente aleatorio $$\boldsymbol{H}_{\boldsymbol{a}}$$ que depende de características intrínsecas del vehículo tales como su estabilidad dinámica, de parámetros relativos a la calidad geométrica de la infraestructura y de características mecánicas de los componentes. La cuantificación de este término requiere validación experimental. Para vías convencionales, la organización ORE (Office de Recherches et d'Essais) ha establecido la siguiente relación empírica, siendo V la velocidad expresada en km/h:

$$
H_{a}=\frac{Q \cdot V}{1.000}
$$

- Verificación de la resistencia transversal de la vía:

Los esfuerzos laterales totales $$\boldsymbol{H}$$ que genera el paso de un vehículo deben ser inferiores a la resistencia lateral mínima que la vía puede proporcionar:

$$
H=H_{o}+H_{a}<R_{L}
$$

La resistencia lateral de la vía se encuentra influenciada por múltiples factores operacionales e infraestructurales:

- Velocidad de circulación del vehículo
- Magnitud de la carga transportada por eje
- Condiciones termales (dilatación térmica)
- Grado de consolidación y estabilización de la vía
- Características de la estructura de la vía (balasto, sujeciones, traviesas)

La determinación del valor de resistencia lateral de la vía debe realizarse mediante validación experimental mediante ensayos in situ sobre la infraestructura. Para líneas de alta velocidad, la formulación propuesta por Prud'Homme establece que el valor mínimo de $$\mathrm{R}_{\mathrm{L}}$$ en kN es:

$$
R_{L}=24+0,47^{*} Q
$$

A modo de ilustración, consideremos una situación hipotética donde la carga por eje es $$Q=170 \mathrm{kN}$$. La resistencia lateral resultante sería $$R_{L}=104 \mathrm{kN}$$. Si la componente aleatoria $$H_{a}$$ no sobrepasa el 60% de esta resistencia (lo que resulta en 62,4 kN), quedan disponibles 41,6 kN para absorber la componente cuasi estática $$H_{0}$$.

$$
H_{o}=1,20 \cdot \frac{Q \cdot I}{1.500}=1,20 \cdot \frac{170 \cdot I}{1.500} \leq 41,6 \mathrm{kN} \rightarrow I<305,88 \mathrm{~mm}
$$


En un análisis de las limitaciones de resistencia transversal de la vía, puede concluirse que bajo condiciones operacionales normales la resistencia lateral de la infraestructura no constituye el factor limitante al momento de determinar radios mínimos en curvas, siendo la insuficiencia de peralte invariablemente menor a 305 mm.

#### IV.2.3 Limitación por barra larga soldada

Conforme a las regulaciones técnicas de ADIF relativas a la instalación y mantenimiento de infraestructura ferroviaria sin juntas, se especifican los siguientes radios mínimos admisibles en función de la tipología de traviesa:

- Traviesas construidas en hormigón de tipo monobloque: Radio mínimo de 250 metros.
- Traviesas tipo bibloque RS: Radio mínimo de 300 metros.
- Traviesas fabricadas en madera con altura de 16 centímetros: Radio mínimo de 435 metros.

En zonas de túneles no pueden emplearse traviesas bibloque RS debido al ambiente de humedad extrema que causa deterioro por oxidación de los arriostradores metálicos. Consecuentemente, en estos escenarios deben implementarse traviesas de madera o traviesas monobloque, respetando los radios mínimos correspondientes.

Aunque la presencia de radios tan pequeños es inusual, determinadas líneas ferroviarias del sistema español han históricamente incorporado radios inferiores a 250 metros.

#### IV.2.4 Limitación en vías de maniobra

En infraestructuras destinadas exclusivamente a operaciones de maniobra donde las velocidades de circulación son muy reducidas, es viable adoptar configuraciones de trazado con radios mínimos de hasta 160 metros para ancho RENFE, prescindiendo de la necesidad de implementar curvas de transición geométrica.

La magnitud del radio mínimo admisible se reduce proporcionalmente a medida que disminuye el ancho de vía disponible. En trazados que incorporan alternancia rápida de curvas y contracurvas con radios muy reducidos, es fundamental establecer alineaciones rectilíneas intermedias adecuadamente dimensionadas para evitar el enganche de los dispositivos de tope de defensa entre vehículos contiguos, lo que podría provocar fenómenos de descarrilamiento.

- Normativa:
a) Especificación técnica de interoperabilidad relativa al subsistema infraestructura del sistema ferroviario transeuropeo de alta velocidad:

En las vías donde sólo se realizan maniobras a pequeña velocidad (vías de estación y vías de apartado, vías de depósito y de estacionamiento), el radio mínimo de diseño de las vías no debe ser inferior a $$150 \boldsymbol{m}$$ para una curva aislada. En explotación, teniendo en cuenta las variaciones de trazado que puedan producirse, el radio mínimo efectivo no debe ser inferior a 125 m . Estos radios límite se definen para ancho de vía UIC.

### IV.3 LONGITUD MINIMA DE ALINEACIONES RECTAS Y CIRCULARES

Se establecen longitudes mínimas en curvas circulares y en alineaciones rectas entre clotoides, para permitir una amortiguación suficiente del balanceo de la caja de los vehículos.

- Normativa:
a) Normativa ADIF: Las limitaciones establecidas para las alineaciones de curvatura constante son las siguientes:

Longitud mínima entre curvas de sentido opuesto:

- Si $$\vee>100 \mathrm{~km} / \mathrm{h}$$, la longitud mínima oscila entre $$0,4^{*} \mathrm{v}$$ y $$0,55^{*} \mathrm{v}$$. Excepcionalmente puede llegarse a $$\mathrm{L}_{\text {Mín }}= 0,35^{*} \mathrm{v}$$
- Si $$\mathrm{v}<100 \mathrm{~km} / \mathrm{h}: \mathrm{L}_{\text {Min }}=\operatorname{Max}\left(\mathrm{v}^{2} / 500 ; 0,1^{*} \mathrm{v}\right)$$

Longitud mínima entre curvas del mismo sentido: Cero.

a) Normativa ADIF: Las limitaciones establecidas para las alineaciones de curvatura constante son las siguientes:

| MÍNIMA LONGITUD DE ALINEACIONES RECTAS O CIRCULARES (m) - N.R.V. 0-2-0.0. |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- |
| VELOCIDAD DE PROYECTO ( $$\mathrm{Km} / \mathrm{h}$$ ) | $$\mathrm{V}=140$$ | $$140<\mathrm{v}=160$$ | $$160<v=200$$ | $$200<v=250$$ |
| NUEVAS LÍNEAS Y DESDOBLAMIENTO DE LÍNEAS ACTUALES CON MODIFICACIÓN DEL TRAZADO | NORMAL: 80 MÍNIMA: 60 | NORMAL: 90 MÍNIMA: 65 | NORMAL: 110 MÍNIMA: 80 | NORMAL: 140 MÍNIMA: 100 |
| MEJORA DE LÍNEAS ACTUALES POR OBRAS (Renovaciones y rehabilitaciones de vía) | 70 | 80 | 100 | - |

| VELOCIDAD DE PROYECTO (Km/h) | $$\mathrm{V}=140$$ | $$140<\mathrm{v}=160$$ | $$160<\mathrm{v}=180$$ | $$180<\mathrm{v}=200$$ |
| :--- | :---: | :---: | :---: | :---: |
| ADAPTACIÓN DE LÍNEAS ACTUALES PARA <br> CIRCULACIÓN DE TRENES TIPO A SIN <br> LIMITACIÓN DE VELOCIDAD | 56 | 64 | 72 | 80 |

## Capítulo V Trazado en alzado

En la definición del trazado en alzado se considerarán prioritarias la seguridad en la circulación y la comodidad de los viajeros.

El perfil longitudinal se define mediante los dos siguientes tipos de rasante:

- Rasante uniforme, en la que la inclinación $$i=d z / d s$$ es constante. La rasante uniforme es una rampa si la inclinación es creciente con el avance, y es una pendiente si disminuye.
- Acuerdo vertical, en el que se realiza progresivamente un cambio de inclinación. El tipo de acuerdo a utilizar es la parábola de segundo grado de eje vertical.

Dado que las pendientes admisibles en ferrocarriles son pequeñas, se expresan siempre en tanto por mil ‰.


Ecuación del acuerdo vertical parabólico y parámetros característicos:

Ecuación del acuerdo vertical parabólico: $$\mathrm{z}=\mathrm{A}+\mathrm{B}^{*} \mathrm{~s}+\mathrm{C}^{*} \cdot \mathrm{~s}^{2}$$

Imponiendo las condiciones de tangencia a la entrada y a la salida de la parábola se obtiene:

$$
\frac{d z}{d s}=B+2 \cdot C \cdot s=i \quad\left\{\begin{array}{l}
\left(\frac{d z}{d s}\right)_{e}=B+2 \cdot C \cdot s_{T E}=i_{E} \\
\left(\frac{d z}{d s}\right)_{s}=B+2 \cdot C \cdot s_{T S}=i_{S}
\end{array}\right\} \Rightarrow\left\{\begin{array}{l}
B=i_{E}-\frac{i_{E}-i_{S}}{s_{T E}-s_{T S}} \cdot s_{T E}=i_{S}-\frac{i_{E}-i_{S}}{s_{T E}-s_{T S}} \cdot s_{T S} \\
C=\frac{i_{E}-i_{S}}{2 \cdot\left(s_{T E}-s_{T S}\right)}
\end{array}\right.
$$

Valores característicos del acuerdo vertical:

- Longitud del acuerdo: $$\mathrm{L}=\mathrm{S}_{\mathrm{TS}}-\mathrm{S}_{\mathrm{TE}}$$
- Variación de inclinación de la rasante en el acuerdo: $$\theta=\mathrm{i}_{\mathrm{S}}-\mathrm{i}_{\mathrm{E}}$$
- Parámetro del acuerdo vertical: $$\mathrm{K}_{\mathrm{V}}=\mathrm{L} / \theta$$
- Si $$\mathrm{i}_{\mathrm{E}}$$, $$\mathrm{i}_{\mathrm{S}}$$ y $$\theta$$ se miden en \%o entonces: $$\mathrm{K}_{\mathrm{V}}=1000^{*} \mathrm{~L} / \theta$$
$$\mathrm{K}_{\mathrm{v}}$$ es positivo en un acuerdo cóncavo, y negativo en uno convexo.

Propiedades del acuerdo vertical parabólico:
![3f1cef6dba25769ab878c652668ed18c_MD5]({{ site.baseurl }}/assets/images/3f1cef6dba25769ab878c652668ed18c_MD5.webp)

La distribución geométrica de los puntos de tangencia de entrada y salida respecto del vértice del acuerdo vertical es completamente simétrica, cumpliéndose que: $$T = L/2$$.

### V.1 INCLINACIÓN MÁXIMA DE LA RASANTE

La selección de la pendiente máxima a implementar en la rasante requiere consideración sistemática de diversos factores técnicos y operacionales:

- Limitaciones por adherencia rueda-carril: El coeficiente de fricción disponible en la interfaz rueda-carril establece un límite práctico en la magnitud de la pendiente del orden de $$70\%$$.
- Capacidades técnicas del material rodante ferroviario:
  - Para composiciones de transporte de viajeros: Bajo circunstancias excepcionales pueden tolerarse rampas de hasta $$50\%$$.
  - Para composiciones de transporte de carga: La inclinación no debe exceder $$20\%$$.
- Naturaleza y composición del tráfico que opera la línea (tráfico especializado versus tráfico heterogéneo).
- Capacidad de arranque en rampa, que se manifiesta en distancias muy cortas (longitud típica de las composiciones).
- Capacidad de frenado de emergencia, que interviene en distancias mayores, típicamente en el rango de 4 a 6 km para operaciones de alta velocidad.

Consideraciones especiales para vías de estacionamiento de composiciones:

La configuración longitudinal ideal en infraestructuras de estación es la horizontal, ya que esta geometría elimina complicaciones operacionales asociadas al control de composiciones paradas.

Si fuera imposible implementar una rasante perfectamente horizontal, debe optarse por una rasante uniforme con pendientes limitadas entre $$1,5$$ y $$3\%$$. En caso necesario de implementar acuerdos verticales, el parámetro $$K_V$$ debe ser superior a 5.000 m.

De conformidad con la Especificación Técnica de Interoperabilidad relativa a infraestructuras del sistema ferroviario transeuropeo de alta velocidad, las vías de apartadero dedicadas al estacionamiento de composiciones no deben tener pendientes que excedan $$2\%$$.

Estas vías de estacionamiento deben estar dimensionadas para acomodar composiciones ferroviarias de hasta 400 metros de longitud.

Limitaciones por rampas de longitud extendida:

Resulta técnicamente indeseable la incorporación de tramos extensos caracterizados por pendientes elevadas continuas, ya que estas configuraciones generan:

- Reducción significativa de las velocidades de circulación de composiciones durante el ascenso.
- Incremento de distancias de frenado durante el descenso, lo que impacta negativamente en la seguridad operacional.
- Aumento de costos de explotación derivados de mayor consumo energético y ampliación de tiempos de recorrido.
- Incremento de costos de mantenimiento y conservación de la infraestructura vial.

INCLINACIÓN MÁXIMA DE LA RASANTE

- Normativa:
a) Normativa ADIF. Los valores de rampas máximas establecidos por esta norma son:

| RAMPAS MÁXIMAS (\%) - N.R.V. 0-2-0.0. |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- |
| VELOCIDAD DE PROYECTO ( $$\mathrm{Km} / \mathrm{h}$$ ) |  | $$\mathrm{V}=140$$ | $$140<\mathrm{v}=160$$ | $$160<\mathrm{v}=200$$ | $$200<\mathrm{v}=250$$ |
| NUEVAS LÍNEAS Y DESDOBLAMIENTO DE LÍNEAS ACTUALES CON MODIFICACIÓN DEL TRAZADO | NORMAL | 20 | 15 | 12,5 | 12,5 |
|  | EXCEPCIONA L | - | 20 | 15 | - |

- TRÁFICO PURO DE VIAJEROS PARA $$\mathrm{V}>250 \mathrm{~km} / \mathrm{h}$$ : RAMPA MÁXIMA DEL $$35 \%$$. 
- ESTACIONES: RAMPA MÁXIMA DEL $$2,5 \%$$.

**Normativa:**

b) Especificación Técnica de Interoperabilidad relativa al subsistema infraestructura del sistema ferroviario transeuropeo de alta velocidad:

El valor máximo de rampas y pendientes podrá alcanzar el $$35 \%$$, siempre que se respeten las condiciones siguientes:

- La pendiente media de la rasante en una longitud de 10 km deberá ser menor o igual a $$25 \%$$.
- La longitud máxima en rampa o pendiente continua del $$35 \%$$ no deberá superar 6.000 m .
c) IOS-98:

Las rampas máximas admisibles en túneles son:

- Líneas de tráfico mixto: $$12,5 \%$$.
- Líneas de tráfico exclusivo de viajeros: $$30 \%$$.

### V.2 ACELERACION ADMISIBLE EN ACUERDOS VERTICALES

Cuando un vehículo recorre a velocidad "v" un acuerdo vertical de radio $$\mathrm{R}_{\mathrm{V}}$$, se ve sometido a una aceleración centrífuga:

$$
a_{v}=\frac{v^{2}}{R_{v}}
$$

Para respetar la comodidad del viajero esta aceleración se limita a valores que oscilan entre el $$\mathbf{1}$$ y el $$\mathbf{4 \%}$$ de " $$\boldsymbol{g}$$ " (valor de la gravedad).

### V.2 ACELERACION ADMISIBLE EN ACUERDOS VERTICALES

Cuando una composición ferroviaria transita a velocidad v a través de un acuerdo vertical de radio $$R_V$$, se ve sometida a una aceleración centrífuga vertical caracterizada por:

$$
a_{v}=\frac{v^{2}}{R_{v}}
$$

Para asegurar el cumplimiento de criterios de confort del pasajero, esta aceleración vertical debe ser limitada a valores que típicamente oscilan entre el 1 y el 4% de la aceleración gravitatoria (g).

El valor del radio $$R_V$$ tiene implicaciones significativas en la configuración de las explanaciones y en los costos de construcción. La administración francesa SNCF realizó investigaciones específicas para el proyecto TGV Sur-Este, procediendo a ensayos de simulación utilizando aviones en vuelo.

Estos ensayos experimentales fueron realizados por el Centro de Ensayos en Vuelo de Brétigny, utilizando un avión que en vuelo programado describía trayectorias sinusoidales verticales controladas. Un grupo de pasajeros anotaba sus percepciones subjetivas en función de la magnitud de las aceleraciones y su espaciamiento temporal. Los pasajeros más sensibles reportaron no percibir aceleraciones de $$0,045 \cdot g$$, mientras que aceleraciones de $$0,06 \cdot g$$ eran claramente percibidas, especialmente en acuerdos de configuración cóncava.

Basándose en estos ensayos experimentales, la SNCF estableció los siguientes límites normativos para operaciones de alta velocidad:

|  | Valor normal | Valor excepcional |
| :---: | :---: | :---: |
| Acuerdo cóncavo | $$a_v = 0,045 \, g$$ | $$a_v = 0,06 \, g$$ |
| Acuerdo convexo | $$a_v = 0,045 \, g$$ | $$a_v = 0,05 \, g$$ |

Estos límites de aceleración se traducen en los siguientes radios de acuerdo vertical mínimos:

|  |  | Valor normal | Valor excepcional |
| :--- | :--- | :--- | :--- |
| $$V = 300 \, \text{km/h}$$ | Acuerdo cóncavo | $$R_V = 16.000 \, \text{m}$$ | $$R_V = 12.000 \, \text{m}$$ |
|  | Acuerdo convexo | $$R_V = 16.000 \, \text{m}$$ | $$R_V = 14.000 \, \text{m}$$ |
| $$V = 350 \, \text{km/h}$$ | Acuerdo cóncavo | $$R_V = 19.000 \, \text{m}$$ | $$R_V = 18.500 \, \text{m}$$ |
|  | Acuerdo convexo | $$R_V = 19.000 \, \text{m}$$ | $$R_V = 21.000 \, \text{m}$$ |

El límite de aceleración de $$0,22 \, \text{m/s}^2$$ establecido en la norma europea ENV 13803-1 parece representar un valor excesivamente restrictivo desde la perspectiva de la práctica operacional.

Un valor de $$0,3 \, \text{m/s}^2$$ constituye un mínimo razonable, considerando que la línea francesa TGV Norte de Europa, proyectada para $$350 \, \text{km/h}$$, implementa como valor normal un radio de acuerdo de 25.000 m, correspondiente a una aceleración de $$0,38 \, \text{m/s}^2$$.

- Normativa:
a) Normativa ADIF. La máxima aceleración admisible en acuerdos verticales que fija la norma es:

| MÁXIMA ACELERACIÓN ADMISIBLE EN ACUERDOS VERTICALES $$\mathrm{a}_{\mathrm{v}} \mathbf{( m} \mathbf{s}^{\mathbf{2}} \boldsymbol{)}$$ - N.R.V. 0-2-0.0 |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- |
| VELOCIDAD DE PROYECTO ( $$\mathrm{Km} / \mathrm{h}$$ ) |  | $$\mathrm{V}=140$$ | $$140<\mathrm{v}=160$$ | $$160<\mathrm{v}=200$$ | $$200<\mathrm{v}=250$$ |
| NUEVAS LÍNEAS Y DESDOBLAMIENTO DE LÍNEAS ACTUALES CON MODIFICACIÓN DEL TRAZADO | NORMAL | $$\leq 0,30$$ | $$\leq 0,30$$ | $$\leq 0,20$$ | $$\leq 0,20$$ |
|  | EXCEPCIONAL | 0,40 | 0,40 | 0,30 | 0,30 |


Comentarios: Si el acuerdo vertical coincide con una curva en planta: $$\mathrm{a}_{\mathrm{v}} \leq 0,20$$ 

| VELOCIDAD DE PROYECTO ( $$\mathrm{Km} / \mathrm{h}$$ ) |  | $$\mathrm{V}=140$$ | $$140<\mathrm{v}=160$$ | $$160<\mathrm{v}=200$$ | $$200<\mathrm{v}=250$$ |
| :--- | :--- | :--- | :--- | :--- | :--- |
| MEJORA DE LÍNEAS ACTUALES POR OBRAS (Renovaciones y rehabilitaciones de vía) | NORMAL | $$\leq 0,30$$ | $$\leq 0,30$$ | $$\leq 0,30$$ | - |
|  | EXCEPCIONAL | 0,45 | 0,45 | 0,40 | - |


Comentarios: Máximo en acuerdos convexos: 0,40 <br> Si el acuerdo vertical coincide con una curva en planta: $$\mathrm{a}_{\mathrm{v}} \leq 0,20$$

| VELOCIDAD DE PROYECTO (Km/h) |  | $$\mathrm{V}=140$$ | $$140<\mathrm{v}=160$$ | $$160<\mathrm{v}=180$$ | $$180<\mathrm{v}=200$$ |
| :--- | :--- | :---: | :---: | :---: | :---: |
| ADAPTACIÓN DE LÍNEAS ACTUALES <br> PARA CIRCULACIÓN DE TRENES TIPO A <br> SIN LIMITACIÓN DE VELOCIDAD | CÓNCAVOS: | 0,50 | 0,50 | 0,45 | 0,45 |
|  | CONVEXOS: | 0,40 | 0,40 | 0,40 | 0,40 |

- Normativa:
- a) Normativa ADIF. Como consecuencia, resultan los siguientes parámetros mínimos para los acuerdos verticales:

| RADIO MINIMO DEL ACUERDO VERTICAL $$\mathbf{R}_{\mathbf{V}}(\mathbf{m})$$ - N.R.V. 0-2-0.0. |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- |
| VELOCIDAD DE PROYECTO ( $$\mathrm{Km} / \mathrm{h}$$ ) |  | $$\mathrm{V}=140$$ | $$140<\mathrm{v}=160$$ | $$160<\mathrm{v}=200$$ | $$200<\mathrm{v}=250$$ |
| NUEVAS LÍNEAS Y DESDOBLAMIENTO DE LÍNEAS ACTUALES CON MODIFICACIÓN DEL TRAZADO | NORMAL | 5.100 | 6.600 | 16.000 | 24.000 |
|  | EXCEPCIONA L | 3.800 | 4.900 | 10.000 | 16.000 |
| MEJORA DE LÍNEAS ACTUALES POR OBRAS (Renovaciones y rehabilitaciones de vía) | NORMAL | 5.100 | 6.600 | 10.000 | - |
|  | EXCEPCIONA L | 3.400 | 4.400 | 7.700 | - |

PARÁMETRO MÍNIMO EN ACUERDOS CONVEXOS: 3.000 m PARÁMETRO MÍNIMO EN ACUERDOS CÓNCAVOS: 2.000 m SI EL ACUERDO VERTICAL COINCIDE CON UNA CURVA EN PLANTA EL PARÁMETRO MÍNIMO SERÁ DE 5.000 m 

| VELOCIDAD DE PROYECTO $$(\mathrm{Km} / \mathrm{h})$$ | $$\mathrm{V}=140$$ | $$140<\mathrm{v}=160$$ | $$160<\mathrm{v}=180$$ | $$180<\mathrm{v}=200$$ |
| :--- | :---: | :---: | :---: | :---: |
| ADAPTACIÓN DE LÍNEAS ACTUALES PARA CIRCULACIÓN <br> DE TRENES TIPO A SIN LIMITACIÓN DE VELOCIDAD | 3.100 | 4.000 | 5.000 | 6.900 |

- Normativa:
b) Norma europea ENV 13803-1

| RADIO MINIMO DEL ACUERDO VERTICAL $$\mathrm{R}_{\mathrm{v}}(\mathrm{m})$$ - ENV 13803-1 |  |  |
| :--- | :--- | :--- |
| Categorías de tráfico | Valores máximos recomendados ( $$\mathrm{V}_{\text {Máx }}$$ en km/h) | Valores máximos permitidos ( $$\mathrm{V}_{\text {Máx }}$$ en $$\mathrm{km} / \mathrm{h}$$ ) |
| I: Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 80 y $$120 \mathrm{Km} / \mathrm{h}$$. | $$0,35 \cdot \mathrm{~V}_{\text {Máx }}{ }^{2}$$ (2) | $$0,25 \cdot \mathrm{~V}_{\text {Máx }}{ }^{2}$$ (3) |
| lia: Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 120 y $$160 \mathrm{Km} / \mathrm{h}$$. | $$0,35 \cdot \mathrm{~V}_{\text {Máx }}{ }^{2}$$ | $$0,25 \cdot \mathrm{~V}_{\text {Máx }}{ }^{2}$$ (3) |
| lib: Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 160 y $$200 \mathrm{Km} / \mathrm{h}$$. | $$0,35 \cdot \mathrm{~V}_{\text {Máx }}{ }^{2}$$ | $$0,25 \cdot \mathrm{~V}_{\text {Máx }}{ }^{2}$$ (3) |
| III: Líneas de tráfico mixto, con trenes de pasajeros con velocidades máximas comprendidas entre 200 y $$300 \mathrm{Km} / \mathrm{h}$$. | $$0,35 \cdot \mathrm{~V}_{\text {Máx }}{ }^{2}$$ | $$0,175 \cdot \bigvee_{\text {Máx }}{ }^{2}$$ (1) |
| IV: Líneas de tráfico mixto, con trenes de pasajeros con velocidades hasta $$230 \mathrm{Km} / \mathrm{h}$$ (o $$250 \mathrm{Km} / \mathrm{h}$$ en las mejores líneas) con vehículos incorporando características técnicas especiales. | $$0,35 \cdot \mathrm{~V}_{\text {Máx }}{ }^{2}$$ | $$0,25 \cdot \bigvee_{\text {Máx }^{2}}{ }^{2}$$ (3) |
| V: Líneas de tráfico de viajeros con velocidades máximas comprendidas entre 250 y $$300 \mathrm{Km} / \mathrm{h}$$. | $$0,35 \cdot \mathrm{~V}_{\text {Máx }}{ }^{2}$$ | $$0,175 \cdot \bigvee_{\text {Máx }}{ }^{2}$$ (1) |

(1) Con una tolerancia de $$+10 \%$$ en acuerdo convexo y $$+30 \%$$ en acuerdo cóncavo. <br> (2) En líneas donde puede que los viajeros circulen de pié, se recomienda $$\mathrm{R}_{\mathrm{v}} \leq 0,77 \cdot \mathrm{~V}_{\operatorname{Máx}^{2}}{ }^{2}$$ <br> (3) Sin bajar de radios de 2.000 m .

### V.3 VARIACIONES BRUSCAS DE ACELERACIÓN VERTICAL

Los acuerdos verticales se definen geométricamente mediante parábolas con eje vertical, características que implican la ausencia de curvas de transición entre los segmentos de rasante uniforme y el acuerdo vertical propiamente dicho. Esta configuración genera un cambio discontinuo en la aceleración vertical en los puntos terminales del acuerdo, originando oscilaciones en los sistemas de suspensión de los vehículos y produciendo sensaciones desagradables de incomodidad en los pasajeros.

Cuando se acoplen consecutivamente dos acuerdos verticales de signo opuesto sin intercalar un tramo de rasante uniforme, los saltos de aceleración vertical asociados a cada acuerdo se superponen, produciendo efectos dinámicos adversos significativos.

Esta configuración de acuerdos consecutivos genera los siguientes fenómenos:

- Descarga rápida de los elementos de suspensión durante la transición desde configuración cóncava a convexa.
- Carga pronunciada de los elementos de suspensión durante la transición desde configuración convexa a cóncava.
- Saltos de aceleración vertical experimentados por los pasajeros, cuya magnitud efectiva se modifica gradualmente por la amortiguación de la suspensión.

Existen dos estrategias de diseño para mitigar los saltos de aceleración vertical:

- Incrementar el valor del parámetro del acuerdo ($$K_V$$), lo que aumenta el radio de curvatura.
- Diseñar el acuerdo vertical incorporando curvas de transición geométrica.

Ambas alternativas resultan en incrementos considerables de la longitud total del acuerdo vertical.

La solución adoptada actualmente en la práctica de la ingeniería ferroviaria es la primera, implementando las siguientes restricciones:
- Establecer longitudes mínimas para acuerdos verticales
- Establecer longitudes mínimas para rasantes de inclinación uniforme

Justificación de la longitud mínima del acuerdo vertical:

Es imperativo que transcurra un intervalo temporal suficiente entre un salto de aceleración vertical y el siguiente, permitiendo la amortiguación completa de la suspensión del vehículo y evitando la superposición de efectos dinámicos que podría provocar oscilaciones estructurales significativas.

Consecuentemente, se establecen limitaciones sobre las longitudes mínimas permitidas tanto para rasantes uniformes como para acuerdos verticales.

Justificación de la longitud mínima de rasante con pendiente uniforme:

Es factible diseñar un acuerdo parabólico donde el salto de aceleración vertical generado en el punto de tangencia sea individualmente admisible. Sin embargo, cuando se colocan dos acuerdos verticales de forma inmediata, los saltos de aceleración se duplican, alcanzando magnitudes considerablemente mayores.

Por esta razón se establece una longitud mínima obligatoria para los segmentos de rasante uniforme ubicados entre dos acuerdos verticales consecutivos, garantizando que los saltos de aceleración vertical no se superpongan. Esta configuración evita efectos negativos sobre los sistemas de suspensión de los vehículos y garantiza condiciones aceptables de confort para los pasajeros.

Caso ilustrativo:

Consideremos una línea de alta velocidad operando a $$v = 350 \, \text{km/h}$$ con un parámetro de acuerdo vertical de $$K_V = 45.000 \, \text{m}$$. En esta configuración, el salto de aceleración vertical en el punto de tangencia resulta ser $$\Delta a_v = 0,21 \, \text{m/s}^2$$, valor considerado admisible. Sin embargo, si se acopla inmediatamente otro acuerdo vertical sin rasante intermedia, el salto total de aceleración resultante sería $$\Delta a_v = 0,42 \, \text{m/s}^2$$ (equivalente al 4,2% de g), representando un valor de aceleración considerable e inaceptable.

Limitaciones según normativa ADIF:

La normativa técnica de ADIF especifica que la longitud mínima admisible para una rasante de inclinación uniforme debe estar comprendida entre el producto de $$0,4$$ por la velocidad de proyecto y el producto de $$0,5$$ por la misma velocidad.

| LONGITUD MÍNIMA DE RASANTE UNIFORME (m) - N.R.V. 0-2-0.0. |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- |
| VELOCIDAD DE PROYECTO ( $$\mathrm{Km} / \mathrm{h}$$ ) | $$\mathrm{V}=140$$ | $$140<\mathrm{v}=160$$ | $$160<\mathrm{v}=200$$ | $$200<\mathrm{v}=250$$ |
| NUEVAS LÍNEAS Y DESDOBLAMIENTO DE LÍNEAS ACTUALES CON MODIFICACIÓN DEL TRAZADO | 70 | 80 | 100 | 100 |
| MEJORA DE LÍNEAS ACTUALES POR OBRAS (Renovaciones y rehabilitaciones de vía) | 70 | 80 | 100 | - |

## Preguntas de repaso

<div class="flashcard-container">
{% include flashcard.html
   question="¿Qué función principal cumple el peralte en una curva ferroviaria?"
   answer="Elevar el carril exterior respecto al interior para reorientar la resultante de fuerzas y eliminar la aceleración lateral."
%}
{% include flashcard.html
   question="¿Qué nombre recibe la configuración donde la resultante de la fuerza centrífuga y el peso es perpendicular a la vía?"
   answer="Se denomina **peralte teórico** o **peralte ideal** (compensa íntegramente la fuerza centrífuga)."
%}
{% include flashcard.html
   question="¿Cómo se define la insuficiencia de peralte (I)?"
   answer="Es la diferencia entre el **peralte teórico** (necesario para compensar la centrífuga) y el **peralte real** implementado en la vía."
%}
{% include flashcard.html
   question="¿Qué criterio de confort limita la aceleración transversal no compensada para un viajero según el texto?"
   answer="El valor máximo tolerable sin molestias significativas se sitúa en torno a **1 m/s²**."
%}
{% include flashcard.html
   question="¿Qué parámetro clasifica los tipos de trenes (Normal, A, B, C, D) según la normativa?"
   answer="Se clasifican según los **valores máximos admisibles de aceleración transversal sin compensar** que pueden soportar."
%}
</div>

## Bibliografía

- Ferrocarriles. Apuntes de Clase. Jose Manuel Garcia Díaz de Villegas
- Infraestructuras Ferroviarias. Andrés López Pita
- Geometría y Calidad de la vía. Manuel Losada
- La geometría en el trazado de ferrocarriles

