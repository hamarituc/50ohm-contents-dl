## Maschen- und Knotenregel

*Maschenregel*: In jedem geschlossenen Stromkreis (Masche) ist die Summe der Spannungen gleich null.
*Knotenregel*: In jedem Knotenpunkt ist die Summe der zufließenden Ströme gleich der Summe der abfließenden Ströme.

<note>
Kirchhoff'sche Gesetze
</note>
---
[question:AD106]
---
#### Lösungsweg
* gegeben: $R_1 = R_2 = R_3 = 10kΩ$
* gegeben: $I_3 = I_2 = 1mA$
* gesucht: $U$

<fragment>
$R_{ges} = R_1 + \frac{R_1 \cdot R_2}{R_1 + R_2} = 10kΩ + \frac{10kΩ \cdot 10kΩ}{10kΩ + 10kΩ} = 15kΩ$
</fragment>
<fragment>
$I = I_2 + I_3 = 1mA + 1mA = 2mA$
</fragment>
<fragment>
$U = R_{ges} \cdot I_{ges} = 15kΩ \cdot 2mA = 30V$
</fragment>
---
[question:AD107]
---
#### Lösungsweg
* gegeben: $R_1 = R_2 = R_3 = 10kΩ$
* gegeben: $U=15V$
* gesucht: $I_3$

<fragment>
$R_{ges} = R_1 + \frac{R_1 \cdot R_2}{R_1 + R_2} = 10kΩ + \frac{10kΩ \cdot 10kΩ}{10kΩ + 10kΩ} = 15kΩ$
</fragment>
<fragment>
$\frac{U_3}{U} = \frac{R_{2\parallel 3}}{R_{ges}} \Rightarrow U_3 = \frac{R_{2\parallel 3}}{R_{ges}} \cdot U = \frac{5kΩ}{15kΩ} \cdot 15V = 5V$
</fragment>
<fragment>
$I_3 = \frac{U_3}{R_3} = \frac{5V}{10kΩ} = 0,5mA$
</fragment>
---
[question:AD108]
---
#### Lösungsweg
* gegeben: $R_1 = R_2 = R_3 = 10kΩ$
* gegeben: $U=15V$
* gesucht: $P_2$

<fragment>
$\frac{U_2}{U} = \frac{R_{2\parallel 3}}{R_{ges}} \Rightarrow U_2 = \frac{R_{2\parallel 3}}{R_{ges}} \cdot U = \frac{5kΩ}{15kΩ} \cdot 15V = 5V$
</fragment>
<fragment>
$P_2 = \frac{U_2^2}{R_2} = \frac{(5V)^2}{10kΩ} = 2,5mW$
</fragment>
---
[question:AD109]
---
#### Lösungsweg
<left>
* gegeben: $R = 0\dots 1kΩ$
* gegeben: $R_1 = 200Ω$
</left>
<right>
* gegeben: $R_2 = 100Ω$
* gegeben: $R_3 = 200Ω$
</right>

<fragment>
$R_{ges} = R_1 + \frac{R_2 \cdot (R_3 + R)}{R_2 + (R_3 + R)}$
</fragment>
<fragment>
Bei $R = 0Ω$:
$R_{ges} = 200Ω + \frac{100Ω \cdot (200Ω + 0Ω)}{100Ω + 200Ω +0Ω} \approx 267Ω$
</fragment>
<fragment>
Bei $R = 1kΩ$:
$R_{ges} = 200Ω + \frac{100Ω \cdot (200Ω + 1kΩ)}{100Ω + 200Ω +1kΩ} \approx 292Ω$
</fragment>
---
[question:AD110]
---
#### Lösungsweg
* gegeben: $R_1 = R_3 = 2,2kΩ$
* gegeben: $R_2 = R_4 = 220Ω$
* gesucht: $R_{ges}$

<fragment>
$\begin{split} R_{ges} &= \frac{(R_1 + R_2) \cdot (R_3 + R_4)}{(R_1 + R_2) + (R_3 + R_4)}\\ &= \frac{(2,2kΩ + 220Ω) \cdot (2,2kΩ + 220Ω)}{2,2kΩ + 220Ω + 2,2kΩ + 220Ω}\\ &= 1210Ω\end{split}$
</fragment>
---
[question:AD114]
---
#### Lösungsweg
<left>
* gegeben: $R_1 = 10kΩ$
* gegeben: $R_2 = 2,2kΩ$
* gegeben: $R_L = 8,2kΩ$
</left>
<right>
* gegeben: $U_B = 12V$
* gesucht: $U_2$
</right>

<fragment>
$\frac{U_2}{U_B} = \frac{R_{2\parallel L}}{R_{ges}}$
$R_{2\parallel L} = \frac{R_2 \cdot R_L}{R_2 + R_L} = \frac{2,2kΩ \cdot 8,2kΩ}{2,2kΩ + 8,2kΩ} = 1,74kΩ$
$R_{ges} = R_1 + R_{2\parallel L} = 10kΩ + 1,74kΩ = 11,74kΩ$
</fragment>
<fragment>
$U_2 = \frac{R_{2\parallel L}}{R_{ges}} \cdot U_B = \frac{1,74kΩ}{11,74kΩ} \cdot 12V \approx 1,8V$
</fragment>