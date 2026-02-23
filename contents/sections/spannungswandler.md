% todo Bild von Spannungswandlervarianten
Einen Spannungswandler benötigen wir immer dann, wenn wir eine Spannung umwandeln müssen. In unserem Hobby kann das z.B. eine $\qty{5}{\volt}$ Spannung für einen Microcontroller aus $\qty{13,8}{\volt}$ sein oder aus einer Batterie mit $\qty{12}{\volt}$ eine Versorgungsspannung für einen Laptop mit $\qty{19}{\volt}$ zu generieren. Hierbei sprechen wir von DC/DC Wandlern als Step-UP (Hochsetzsteller) oder Step-DOWN (Tiefsetzsteller).
Durch die Spannungswandlung entstehen auch Verluste. Das Verhältnis der abgegebenen Leistung zur zugeführten Leistung nennt man Wirkungsgrad. Dieser berechnet sich aus $\eta = \frac{P_{\mathrm{ab}}}{P_{\mathrm{zu}}}$.

Ein Spannungswandler setzt $U_{\mathrm{in}} = \qty{12}{\volt}$ auf $U_{\mathrm{out}} = \qty{5}{\volt}$ um. Er nimmt $I_{\mathrm{in}} = \qty{2}{\ampere}$ auf und gibt $I_{\mathrm{out}} = \qty{3}{\ampere}$ ab. Wie groß ist sein Wirkungsgrad? Dazu benötigen wir die Leistungen $P_{\mathrm{zu}}$ und $P_{\mathrm{ab}}$. Diese berechnen sich wie bereits gelernt mit $P = U \cdot I$.
In unserem Beispiel also wie folgt:  
$P_{\mathrm{zu}} = U_{\mathrm{in}} \cdot I_{\mathrm{in}} = \qty{12}{\volt} \cdot \qty{2}{\ampere} = \qty{24}{\watt}$
$P_{\mathrm{ab}} = U_{\mathrm{out}} \cdot I_{\mathrm{out}} = \qty{5}{\volt} \cdot \qty{3}{\ampere} = \qty{15}{\watt}$

somit ergibt sich:
$\eta = \frac{P_{\mathrm{ab}}}{P_{\mathrm{zu}}} = \frac{\qty{15}{\watt}}{\qty{24}{\watt}} = \num{0,625}$
Um nun $\eta$ in $\%$ anzugeben, wird $\eta \cdot \qty{100}{\percent}$ genommen und somit ist der Wirkungsgrad $\eta = \qty{62,5}{\percent}$

[question:AB213]
[question:AB214]
<indepth>
[photo:299:StepUpDownWandler: Abwärts- (Buck) Aufwärts- (Boost) Wandler]
Dieser Buck-Boost Converter kann von $\qty{0,5}{\volt}$ bis $\qty{25}{\volt}$ am Ausgang eingestellt werden. Die maximale Leistung beträgt $\qty{25}{\watt}$. Da der Wirkungsgrad sehr hoch ist, kommen die Schalttransistoren ohne Kühlkörper aus.  Die Betriebsart Abwärtswandler (Step Down = Buck Mode) oder Aufwärtswandler (Step Up = Boost Mode) kann mit dem rechten Minischalter aktiviert werden.
[photo:300:StepUpWandler: Aufwärtsspannungswandler von $\qty{7,2}{\volt}$ auf $\qty{24}{\volt}$]
</indepth>
  
<margin>
  Lösungshilfe
  AB 214: $\qty{80}{\percent}$
</margin>
