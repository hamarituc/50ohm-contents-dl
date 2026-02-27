<left>
[picture:807:spiegelfrequenzen_mischen1:Mischvorgang mit Empfangsfrequenz $f_\text{e}$, Oszillatorfrequenz $f_\text{o}$ und der Zwischenfrequenz $f_\text{ZF}$]

$f_\text{ZF} = \left|f_\text{e} \pm f_\text{o}\right|$
</left>
<right>  
Im Mischprozess zur $f_\text{ZF}$ werden prinzipbedingt immer zwei Empfangsfrequenzen ausgewählt
</right>

---
<left>
[picture:806:spiegelfrequenzen_fe1_fe2:Empfangsfrequenzen die beide zur selben $f_\text{ZF}$ führen]
</left>
<right>
* Gewünschte Empfangsfrequenz $f_\text{e1}$ &rarr; Spiegelfrequenz $f_\text{e2}$
* Abstand zwischen gewünschter Empfangsfrequenz und Spiegelfrequenz &rarr; ${2 \cdot f_\text{ZF}}$
</right>
---
<left>
Oszillator schwingt oberhalb der Empfangsfrequenz<br/>
&darr;<br/>
Spiegelfrequenz bei ${2 \cdot f_\text{ZF}}$ oberhalb der Empfangsfrequenz
</left>
<right>
Oszillator schwingt unterhalb der Empfangsfrequenz<br/>
&darr;<br/>
Spiegelfrequenz bei ${2 \cdot f_\text{ZF}}$ unterhalb der Empfangsfrequenz
</right>

---

$f_\text{S} = 2 \cdot f_\text{OSZ}\,-\,f_\text{E} =\\ \begin{cases}f_\text{OSZ}\,+\,f_\text{ZF} = f_\text{E}\,+\,2 \cdot f_\text{ZF} &\text{wenn } f_\text{E} \lt f_\text{OSZ} \\ f_\text{OSZ}\,-\,f_\text{ZF} = f_\text{E}\,-\,2 \cdot f_\text{ZF} &\text{wenn } f_\text{E} \gt f_\text{OSZ} \end{cases}$

---
## Spiegelfrequenzunterdrückung

<left>
[picture:808:spiegelfrequenzen_mischen2:Zusätzlicher Bandpassfilter zur Spiegelfrequenzunterdrückung]
</left>
<right>
* Ohne Unterdrückung kann die Spiegelfrequenz zu Empfangsstörungen führen
* Vermeidung: Gewünschte Frequenz wird durch einen Bandpassfilter selektiert
* Spiegelfrequenz wird möglichst maximal unterdrückt
</right>
---
Maßnahme für eine möglichst hohe Unterdrückung:
* Abstand zwischen gewünschter Empfangsfrequenz und Spiegelfrequenz durch eine hohe ZF möglichst groß wählen
* Bei einem großen Abstand kann ein hochwertiges Bandpassfilter leichter realisiert werden

---
[question:AF201]
---
[question:AF202]
---
#### Lösungsweg
* gegeben: $f_\text{OSZ} = \qty{134,9}{\mega\hertz}$
* gegeben: $f_\text{E} = \qty{145,6}{\mega\hertz}$
* gesucht: $f_\text{S}$

<fragment>
$\begin{split}f_\text{S} &= 2 \cdot f_\text{OSZ} - f_\text{E}\\ &= 2 \cdot \qty{134,9}{\mega\hertz} - \qty{145,6}{\mega\hertz}\\ &= \qty{124,2}{\mega\hertz}\end{split}$
</fragment>
---
[question:AF203]
---
#### Lösungsweg
* gegeben: $f_\text{OSZ} = \qty{39}{\mega\hertz}$
* gegeben: $f_\text{E} = \qty{28,3}{\mega\hertz}$
* gesucht: $f_\text{S}$

<fragment>
$\begin{split}f_\text{S} &= 2 \cdot f_\text{OSZ} - f_\text{E}\\ &= 2 \cdot \qty{39}{\mega\hertz} - \qty{28,3}{\mega\hertz}\\ &= \qty{49,7}{\mega\hertz}\end{split}$
</fragment>
---
[question:AF204]
---
[question:AF106]
---
[question:AF107]
---
#### Lösungsweg
* gegeben: $f_\text{OSZ} = \qty{24,94}{\mega\hertz}$
* gegeben: $f_\text{E} = \qty{14,24}{\mega\hertz}$
* gesucht: $f_\text{S}$

<fragment>
$\begin{split}f_\text{S} &= 2 \cdot f_\text{OSZ} - f_\text{E}\\ &= 2 \cdot \qty{24,94}{\mega\hertz} - \qty{14,24}{\mega\hertz}\\ &= \qty{35,64}{\mega\hertz}\end{split}$
</fragment>
---
[question:AF108]
---
#### Lösungsweg
* gegeben: $f_\text{ZF} = \qty{10,7}{\mega\hertz}$
* gegeben: $f_\text{E} = \qty{28,5}{\mega\hertz}$
* gesucht: $f_\text{S}$

<fragment>
Bei $f_\text{E} < f_\text{OSZ}$:
$\begin{split}f_\text{S} &= f_\text{E} + 2 \cdot f_\text{ZF}\\ &= \qty{28,5}{\mega\hertz} + 2 \cdot \qty{10,7}{\mega\hertz}\\ &= \qty{49,9}{\mega\hertz}\end{split}$
</fragment>
---
[question:AF109]
---
[question:AF110]
---
[question:AF111]
