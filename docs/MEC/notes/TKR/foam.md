# Notes on Tracker Foam

## Foam at Each Layer

- The selected foam for the 2nd Tracker build (2023-present) is
  [Owens Corning Foamular NGX 250](https://dcpd6wotaa0mb.cloudfront.net/mdms/dms/EIS/43522/43522-FOAMULAR-250-XPS-Insulation-Product-Data-Sheet.pdf?v=1664703006000).
- Referenced drawing and files can be found on the
  [GAPS Nextcloud](https://gaps1.astro.ucla.edu/nextcloud/index.php/f/7163).
  For access to the Nextclould refer to the instructions on the
  [GAPS wiki](https://gaps1.astro.ucla.edu/wiki/gaps/index.php?title=Nextcloud).

### The Parts

- Any part whose PN is appended with a `-W` is a version of the primary
  PN for waterjet cutting.
- BL9 = Below Layer 9
- BEL = Below Even Layers
- BOL = Below Odd Layers
- BL0 = Below Layer 0
- AL0 = Above Layer 0
- Even Layers = Layers 8, 6, 4, and 2
- Odd Layers = Layers 7, 5, 3, and 1

|   Foam Component   | Where? |  QTY  |  QTY   |  QTY  | Notes                    |
|:------------------:|:------:|:-----:|:------:|:-----:|:-------------------------|
|                    |        | Exact | Spares | TOTAL |                          |
| `GAPS-TKR-MEC-204` |  All   |  240  |        |       | "Locating Dowel, Large"  |
| `GAPS-TKR-MEC-205` |  All   |  40   |        |       | "Locating Dowel, Small"  |

### Layer Assemblies

- Assemblies include the detector layer and the foam below the detector
  layer.

| Layer(s) |    SW Assembly     | Notes                      |
|:--------:|:------------------:|:---------------------------|
|    9     | `GAPS-TKR-MEC-200` | "Layer Assy 1, Tracker"    |
|   Even   | `GAPS-TKR-MEC-300` | "Layer Assy Even, Tracker" |
|   Odd    | `GAPS-TKR-MEC-310` | "Layer Assy Odd, Tracker"  |
|    0     | `GAPS-TKR-MEC-350` | "Layer Assy 10, Tracker"   |
|   Top    | `GAPS-TKR-MEC-400` | "Layer Assy 11, Tracker"   |

### Layer 9

- Interface boards face radiator side

|   Foam Component   |    QTY    |  QTY  | Notes                               |
|:------------------:|:---------:|:-----:|:------------------------------------|
|                    | per Layer | TOTAL |                                     |
| `GAPS-TKR-MEC-201` |     6     |   6   | "Center Section, Layer 1, Tracker"  |
| `GAPS-TKR-MEC-202` |     1     |   1   | "Outer Section 1, Layer 1, Tracker" |
| `GAPS-TKR-MEC-203` |     1     |   1   | "Outer Section 2, Layer 1, Tracker" |


### Even Layers (8, 6, 4, & 2)

- Interface boards face non-boom side

|   Foam Component   |    QTY    |  QTY  | Notes                                  |
|:------------------:|:---------:|:-----:|:---------------------------------------|
|                    | per Layer | TOTAL |                                        |
| `GAPS-TKR-MEC-301` |     6     |  24   | "Center Section, Even Layers, Tracker" |
| `GAPS-TKR-MEC-302` |     1     |   4   | "Outer Section 1, Mid Layers, Tracker" |
| `GAPS-TKR-MEC-303` |     1     |   4   | "Outer Section 2, Mid Layers, Tracker" |


### Odd Layers (7, 5, 3, & 1)

- Interface boards face radiator side

|   Foam Component   |    QTY    |  QTY  | Notes                                  |
|:------------------:|:---------:|:-----:|:---------------------------------------|
|                    | per Layer | TOTAL |                                        |
| `GAPS-TKR-MEC-304` |     6     |  24   | "Center Section, Odd Layers, Tracker"  |
| `GAPS-TKR-MEC-302` |     1     |   4   | "Outer Section 1, Mid Layers, Tracker" |
| `GAPS-TKR-MEC-303` |     1     |   4   | "Outer Section 2, Mid Layers, Tracker" |


### Layer 0 (Top Detector Layer)

- Interface boards face non-boom side

|   Foam Component   |    QTY    |  QTY  | Notes                                   |
|:------------------:|:---------:|:-----:|:----------------------------------------|
|                    | per Layer | TOTAL |                                         |
| `GAPS-TKR-MEC-305` |     6     |   6   | "Center Section, Layer 10 Bot, Tracker" |
| `GAPS-TKR-MEC-306` |     6     |   6   | "Center Section, Layer 10 Top, Tracker" |
| `GAPS-TKR-MEC-302` |     1     |   1   | "Outer Section 1, Mid Layers, Tracker"  |
| `GAPS-TKR-MEC-303` |     1     |   1   | "Outer Section 2, Mid Layers, Tracker"  |


### Above Layer 0


|   Foam Component   |    QTY    |  QTY  | Notes                                     |
|:------------------:|:---------:|:-----:|:------------------------------------------|
|                    | per Layer | TOTAL |                                           |
| `GAPS-TKR-MEC-401` |     6     |   6   | "Center Section, Layer 11 Bot, Tracker"   |
| `GAPS-TKR-MEC-402` |     1     |   1   | "Outer Section 1, Layer 11, Tracker"      |
| `GAPS-TKR-MEC-403` |     1     |   1   | "Outer Section 2, Layer 11, Tracker"      |
| `GAPS-TKR-MEC-404` |     6     |   6   | "Center Section, Layer 11 Upper, Tracker" |
