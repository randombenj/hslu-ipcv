# Chapter 1

## Punktbildfunktioen

Sind funktionen welche den Wert eines Pixels verändern,


## Morphologische Operationen

Werden auf *Binäre Bilder* angewendet, beispielsweise
`dilate` und `erode`:

```python
image = cv2.imread('image.png')

cv2.dilate(image, (5,5))
```