# Farbe

Farben sind elektromagnetische wellen in bestimmten frequenzen.
Sie können als *RGB* dargestellt werden. Dies da
das menschliche Auge rot, grün und blau aufnehmen kann.
Es können auch mehrere Frequenzen eine Farbe bilden,
so ist beispielswese Weiss alle Frequenzen miteinander.

![elektromagnetismus](../images/elektromagnetisches-spektrum.png)

Das auge nimmt rot, grün und blau wahr, blau wird jedoch
am wenigsten sark wahrgenommen.

![farbwahrnehmung](../images/farbwahrnehmung.png)

Mit *RGB* können jedoch nicht alle Farben dargestellt werden,
beispielsweise brauntöne. Theoretisch könnten Farben subtrahiert
werden um alle Farben darstellen zu können.

Mit dem *CIE* Farbsystem kann man alle Farben darstellen.
Das system ist durch Spektralwertkurven deffiniert.

Wie häufig kommt eine frequenz vor:

\\[ X = k\int P(\lambda) \bar{x}_\lambda d\lambda \\]

\\[ Y = k\int P(\lambda) \bar{y}_\lambda d\lambda \\]

\\[ Z = k\int P(\lambda) \bar{z}_\lambda d\lambda \\]

X, Y und Z sind hypothetische Grundfarben, sie können also
nicht dargestellt werden:

![cie colors](../images/cie-colors.png)

Wenn ich Zwei punkte im *CIE Farbspektrum* einzeichne,
kann ich all die Farbe welche auf der Verbindungslinie
sind aus den beiden Punktfarben mischen.
Die Farben auf der Purpurlinie (gerade unten am Diagram)
kann ich nicht aus zwei anderen Farben mischen.
Diese gaben auch Probleme im *RGB* spektrum.

Wir nehmen nicht alle Farbänderungen gleich wahr:

![farbaenderung](../images/farbaenderung.png)

Dies kann beispielsweise ein Problem sein, falls
ein Arzt visuell Diagnosen stellen soll.

RGB to CMY

\\[
  \begin{bmatrix}
  C &
  M &
  Y
  \end{bmatrix}
\\]

CMYK für Drucker (schwarz sepparat), beispiel CMY: (0.5, )

\\[ K = min(C, M, Z) \\]

\\[ C' = C - K \\]

## HSV (Hue Satturation, Value)

![hsv](../images/hsv.png)

