# Math formulas
## Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²

## Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a

## Usage (Python 3)

Run Python from the repository root so that it can import `circle.py` and
`square.py`. These modules use only the Python standard library.

```python
import circle
import square

print(square.area(3))       # 9
print(square.perimeter(3))  # 12
print(round(circle.area(2), 2))       # 12.57
print(round(circle.perimeter(2), 2))  # 12.57
```

The arguments are the circle radius or square side length, in a consistent
unit. Areas are returned in squared units; perimeters use the original unit.
The functions do not validate their arguments, so supply non-negative lengths.

Rectangle formulas above are reference formulas; the `main` branch currently
contains implementations for circles and squares only.
