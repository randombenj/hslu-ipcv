# Bildverbesserung

Mehr Informationen aus einem Bild herausholen

## Sharpening

Bei einem Übergang zwischen Dunkel und hell bei einem
Unscharfen bild geht Langsam sonst habe ich einen
hohen Kontrast also einen schnelleren Übergang.

Ein Bild ist Unscharf wenn über die Farbwerte gemittelt wird.
`f(x)` = Helligkeit des Bildes:

\\[f'(x) = \frac{f(x) - f(x + 1)}{1}\\]

Beispiel:

\\[f_0=f_b-(c\delta t) f_b''\\]

| \\(f_b\\)   | 10 | 10 | 9 | 8  | 6  | 2 | 0  | 0  | 2  | 3 |
|-------|----|----|---|----|----|---|----|----|----|---|
| \\(f_b''\\) | -  | -1 | 0 | -1 | -2 | 2 | 2  | 2  | -1 | - |
|       | 10 | 11 | 9 | 9  | 8  | 0 | -2 | -2 | 3  | 3 |
