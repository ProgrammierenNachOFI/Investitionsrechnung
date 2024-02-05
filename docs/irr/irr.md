# Der interne Zinssatz

Der interne Zinssatz (Internal Rate of Return, IRR) entspricht jenem
(kalkulatorischen) Zinssatz bei dem der Nettobarwert einer Investition
gerade Null ist. Für die Berechnung des internen Zinssatzes muss damit
die Gleichung 

$$0 = \sum_{t=0}^{n} \frac{cf_t}{(1+i)^t} \; -I$$

nach $i$ aufgelöst werden.

Beim Vergleich mehrerer Varianten ist jener der Vorzug zu geben, die für
$i$ den höchsten Wert aufweist.

Wie dafür vorzugehen ist, wird in diesem 
[Arbeitsblatt](https://colab.research.google.com/github/ProgrammierenNachOFI/Investitionsrechnung/blob/main/docs/irr/irr_sus.ipynb)
erläutert. Eine Musterlösung findet sich im entsprechenden GitHub Repository.