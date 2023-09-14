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

#### Full Components

|    Foam Component    |    Where?     |  QTY  |  QTY   |  QTY  | Notes                                          |
|:--------------------:|:-------------:|:-----:|:------:|:-----:|:-----------------------------------------------|
|                      |               | Exact | Spares | TOTAL |                                                |
|  `GAPS-TKR-MEC-204`  |      All      |  252  |        |       | "Locating Dowel, Large"                        |
|  `GAPS-TKR-MEC-205`  |      All      |  40   |        |       | "Locating Dowel, Small"                        |
|  `GAPS-TKR-MEC-301`  |      BEL      |  24   |        |       | "Center Section, Even Layers, Tracker"         |
| `GAPS-TKR-MEC-302-A` | BEL, BOL, BL0 |   9   |        |       | "Outer Section 1, Mid Layers, Tracker, A Half" |
| `GAPS-TKR-MEC-302-B` | BEL, BOL, BL0 |   9   |        |       | "Outer Section 1, Mid Layers, Tracker, B Half" |
| `GAPS-TKR-MEC-303-A` | BEL, BOL, BL0 |   9   |        |       | "Outer Section 2, Mid Layers, Tracker, A Half" |
| `GAPS-TKR-MEC-303-B` | BEL, BOL, BL0 |   9   |        |       | "Outer Section 2, Mid Layers, Tracker, B Half" |
|  `GAPS-TKR-MEC-304`  |      BOL      |  24   |        |       | "Center Section, Odd Layers, Tracker"          |
|  `GAPS-TKR-MEC-305`  |      BL0      |   6   |        |       | "Center Section, Layer 10 Bot, Tracker"        |
|  `GAPS-TKR-MEC-306`  |      BL0      |   6   |        |       | "Center Section, Layer 10 Top, Tracker"        |
|  `GAPS-TKR-MEC-401`  |      AL0      |   6   |        |       | "Center Section, Layer 11 Bot, Tracker"        |
| `GAPS-TKR-MEC-402-A` |      AL0      |   1   |        |       | "Outer Section 1, Layer 11, Tracker, A Half"   |
| `GAPS-TKR-MEC-402-B` |      AL0      |   1   |        |       | "Outer Section 1, Layer 11, Tracker, B Half"   |
| `GAPS-TKR-MEC-403-A` |      AL0      |   1   |        |       | "Outer Section 2, Layer 11, Tracker, A Half"   |
| `GAPS-TKR-MEC-403-B` |      AL0      |   1   |        |       | "Outer Section 2, Layer 11, Tracker, B Half"   |
|  `GAPS-TKR-MEC-404`  |      AL0      |   6   |        |       | "Center Section, Layer 11 Upper, Tracker"      |
|  `GAPS-TKR-MEC-501`  |      AL0      |   1   |        |       | "Section 1, Layer 12, Tracker"                 |
|  `GAPS-TKR-MEC-502`  |      AL0      |   1   |        |       | "Section 2, Layer 12, Tracker"                 |

#### Waterjet Cut Components

- `305-W` and `306-W` are identical
- `402-W` and `403-W` are identical
- `401-W` and `502-W` are identical

|    Foam Component     |    Where?     |  QTY  |  QTY   |  QTY  | Notes                                                   |
|:---------------------:|:-------------:|:-----:|:------:|:-----:|:--------------------------------------------------------|
|                       |               | Exact | Spares | TOTAL |                                                         |
|  `GAPS-TKR-MEC-204`   |      All      |  253  |        |       | "Locating Dowel, Large"                                 |
|  `GAPS-TKR-MEC-205`   |      All      |  40   |        |       | "Locating Dowel, Small"                                 |
| `GAPS-TKR-MEC-301-W`  |      BEL      |  24   |        |       | "Center Section, Even Layers, Tracker"                  |
| `GAPS-TKR-MEC-302-AW` | BEL, BOL, BL0 |   9   |        |       | "Outer Section 1, Mid Layers, Tracker, A Half Waterjet" |
| `GAPS-TKR-MEC-302-BW` | BEL, BOL, BL0 |   9   |        |       | "Outer Section 1, Mid Layers, Tracker, B Half Waterjet" |
| `GAPS-TKR-MEC-303-AW` | BEL, BOL, BL0 |   9   |        |       | "Outer Section 2, Mid Layers, Tracker, A Half Waterjet" |
| `GAPS-TKR-MEC-303-BW` | BEL, BOL, BL0 |   9   |        |       | "Outer Section 2, Mid Layers, Tracker, B Half Waterjet" |
| `GAPS-TKR-MEC-304-W`  |      BOL      |  24   |        |       | "Center Section, Odd Layers, Tracker, Waterjet"         |
| `GAPS-TKR-MEC-305-W`  |      BL0      |  12   |        |       | "Center Section, Layer 10 Bot, Tracker, Waterjet"       |
| `GAPS-TKR-MEC-306-W`  |      BL0      |  --   |   --   |  --   | "Center Section, Layer 10 Top, Tracker, Waterjet"       |
| `GAPS-TKR-MEC-401-W`  |      AL0      |   6   |        |       | "Center Section, Layer 11 Bot, Tracker"                 |
| `GAPS-TKR-MEC-402-W`  |      AL0      |   4   |        |       | "Outer Section 1, Layer 11, Tracker, Waterjet Half"     |
| `GAPS-TKR-MEC-403-W`  |      AL0      |  --   |   --   |  --   | "Outer Section 2, Layer 11, Tracker, Waterjet Half"     |
| `GAPS-TKR-MEC-404-W`  |      AL0      |   6   |        |       | "Center Section, Layer 11 Upper, Tracker"               |
| `GAPS-TKR-MEC-501-W`  |      AL0      |   2   |        |       | "Section 1, Layer 12, Tracker"                          |
| `GAPS-TKR-MEC-502-W`  |      AL0      |  --   |   --   |  --   | "Section 2, Layer 12, Tracker"                          |

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
| Top Cap  | `GAPS-TKR-MEC-500` | "Layer Assy 12, Tracker"   |

### Layer 9

- Interface boards face radiator side

|   Foam Component   |    QTY    |  QTY  | Notes                               |
|:------------------:|:---------:|:-----:|:------------------------------------|
|                    | per Layer | TOTAL |                                     |
| `GAPS-TKR-MEC-201` |     6     |   6   | "Center Section, Layer 1, Tracker"  |
| `GAPS-TKR-MEC-202` |     1     |   1   | "Outer Section 1, Layer 1, Tracker" |
| `GAPS-TKR-MEC-203` |     1     |   1   | "Outer Section 2, Layer 1, Tracker" |
