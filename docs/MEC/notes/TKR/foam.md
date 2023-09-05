# Notes on Tracker Foam

## Foam at Each Layer

### Layer 9

- Governing CAD model is `GAPS-TKR-MEC-200 Layer Assy 1, Tracker. sldasm`
- Model includes Layer 9 detectors and lower foam
- Interface boards face radiator side

|   Foam Component   | QTY | Notes                                |
|:------------------:|:---:|:-------------------------------------|
| `GAPS-TKR-MEC-201` |  6  | "Center Section, Layer 1, Tracker"   |
| `GAPS-TKR-MEC-202` |  1  | "Outer Section 1, Layer 1, Tracker"  |
| `GAPS-TKR-MEC-203` |  1  | "Outer Section 2, Layer 1, Tracker"  |
| `GAPS-TKR-MEC-204` | 24  | "Locating Dowel, Large"              |
| `GAPS-TKR-MEC-205` |  4  | "Locating Dowel, Small"              |

### Even Layers (8, 6, 4, & 2)

- Governing CAD model is `GAPS-TKR-MEC-300 Layer Assy Even, Tracker. sldasm`
- Model includes the foam below the detector layer and the detector modules
- Model reference is for even layers (8, 6, 4, and 2)
- Interface boards face non-boom side

|   Foam Component   |    QTY    |  QTY  | Notes                                  |
|:------------------:|:---------:|:-----:|:---------------------------------------|
|                    | per Layer | TOTAL |                                        |
| `GAPS-TKR-MEC-301` |     6     |  24   | "Center Section, Even Layers, Tracker" |
| `GAPS-TKR-MEC-302` |     1     |   4   | "Outer Section 1, Mid Layers, Tracker" |
| `GAPS-TKR-MEC-303` |     1     |   4   | "Outer Section 2, Mid Layers, Tracker" |
| `GAPS-TKR-MEC-204` |    24     |  96   | "Locating Dowel, Large"                |
| `GAPS-TKR-MEC-205` |     4     |  16   | "Locating Dowel, Small"                |

### Odd Layers (7, 5, 3, & 1)

- Governing CAD model is `GAPS-TKR-MEC-310 Layer Assy Odd, Tracker. sldasm`
- Model includes the foam below the detector layer and the detector modules
- Model reference is for odd layers (7, 5, 3, and 1)
- Interface boards face radiator side

|   Foam Component   |    QTY    |  QTY  | Notes                                  |
|:------------------:|:---------:|:-----:|:---------------------------------------|
|                    | per Layer | TOTAL |                                        |
| `GAPS-TKR-MEC-304` |     6     |  24   | "Center Section, Odd Layers, Tracker"  |
| `GAPS-TKR-MEC-302` |     1     |   4   | "Outer Section 1, Mid Layers, Tracker" |
| `GAPS-TKR-MEC-303` |     1     |   4   | "Outer Section 2, Mid Layers, Tracker" |
| `GAPS-TKR-MEC-204` |    24     |  96   | "Locating Dowel, Large"                |
| `GAPS-TKR-MEC-205` |     4     |  16   | "Locating Dowel, Small"                |

### Layer 0 (Top Layer)

- Governing CAD model is `GAPS-TKR-MEC-350 Layer Assy 10, Tracker. sldasm`
- Model includes the foam below the detector layer and the detector modules
- Model reference is for Layer 0
- Interface boards face non-boom side

|   Foam Component   |    QTY    |  QTY  | Notes                                   |
|:------------------:|:---------:|:-----:|:----------------------------------------|
|                    | per Layer | TOTAL |                                         |
| `GAPS-TKR-MEC-305` |     6     |   6   | "Center Section, Layer 10 Bot, Tracker" |
| `GAPS-TKR-MEC-306` |     6     |   6   | "Center Section, Layer 10 Top, Tracker" |
| `GAPS-TKR-MEC-302` |     1     |   1   | "Outer Section 1, Mid Layers, Tracker"  |
| `GAPS-TKR-MEC-303` |     1     |   1   | "Outer Section 2, Mid Layers, Tracker"  |
| `GAPS-TKR-MEC-204` |    24     |  24   | "Locating Dowel, Large"                 |
| `GAPS-TKR-MEC-205` |     4     |   4   | "Locating Dowel, Small"                 |
