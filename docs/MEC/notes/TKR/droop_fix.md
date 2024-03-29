# Notes on Tracker Droop Fix

**Dated:** October 2023

### New Components for Fix

- Schematics and CAD files for all the componets can be found on the
  GAPS NextCloud, [here](https://gaps1.astro.ucla.edu/nextcloud/index.php/f/7827).
  For access just sign in with the TOF account, instructions can be found on our wiki.

#### Frame Members

- Frame members area the aluminum sq. tubes that make up the general frame.
- [NextCloud folder for Frame Members.](https://gaps1.astro.ucla.edu/nextcloud/index.php/f/7833)

|      Component       |  QTY  |  QTY   |  QTY  | Description                       |
|:--------------------:|:-----:|:------:|:-----:|:----------------------------------|
|                      | Exact | Spares | TOTAL |                                   |
|  `GAPS-FRM-MEC-025`  |   1   |   -    |   1   | Frame member 14, E-bay            |
|  `GAPS-FRM-MEC-049`  |   1   |   -    |   1   | Frame member 25, E-bay            |
|  `GAPS-FRM-MEC-101`  |   1   |   -    |   1   | Frame member 34, E-bay            |
|  `GAPS-FRM-MEC-102`  |   1   |   -    |   1   | Frame member 35, E-bay            |
|  `GAPS-FRM-MEC-609`  |   4   |   -    |   4   | Frame member 36, TKR diag support |
| * `GAPS-TKR-MEC-101` |   1   |   -    |   1   | Frame Member 1, Tracker           |
| * `GAPS-TKR-MEC-102` |   1   |   -    |   1   | Frame Member 2, Tracker           |

\* Second batch of parts

#### Screwplates

- Screwplates are the exterior plates used to connect adjacent frame members, these are
  used in conjunction with the interior nutplates.
- [NextCloud folder for Screwplates.](https://gaps1.astro.ucla.edu/nextcloud/index.php/f/7834)

|      Component       |  QTY  |  QTY   |  QTY  | Description                                    |
|:--------------------:|:-----:|:------:|:-----:|:-----------------------------------------------|
|                      | Exact | Spares | TOTAL |                                                |
| `GAPS-FRM-MEC-601-1` |   4   |   1    |   5   | Screwplate 41, Frame, Upper Half               |
| `GAPS-FRM-MEC-601-2` |   4   |   1    |   5   | Screwplate 41, Frame, Lower Half               |
| `GAPS-FRM-MEC-601-3` |   4   |   4    |   8   | Screwplate 41, Frame, Bridge Half              |
| *`GAPS-FRM-MEC-602`  |   4   |   1    |   5   | Screwplate 46, Frame                           |
| `GAPS-FRM-MEC-606-1` |   4   |   1    |   5   | Screwplate 42, TKR diag support bracket, Inner |
| `GAPS-FRM-MEC-606-2` |   4   |   1    |   5   | Screwplate 42, TKR diag support bracket, Outer |
|  `GAPS-FRM-MEC-607`  |   8   |   2    |  10   | Screwplate 43, TKR diag support bracket        |
| `GAPS-FRM-MEC-608-1` |   4   |   1    |   5   | Screwplate 44, TKR diag support bracket, Inner |
| `GAPS-FRM-MEC-608-2` |   4   |   1    |   5   | Screwplate 44, TKR diag support bracket, Outer |
|  `GAPS-FRM-MEC-610`  |   2   |   2    |   4   | Screwplate 45, TKR diag support bracket        |

\* Second batch of parts

#### Nutplates

- Nutplates are the interior plates used to connect adjacent frame
  members, these are used in conjunction with the exterior screwplates.
- An "ASSY Nutplate" is just a version of a "BASE Nutplate" with PEM
  nuts installed.  For example, `GAPS-FRM-MEC-051` is the base nutplate
  for assembly nutplates `GAPS-FRM-MEC-050` and `GAPS-FRM-MEC-060`.
- For instructions/schematics of the "ASSY Nutplates", look to the
  schematics of the BASE nutplate.
- [NextCloud folder for Nutplates.](https://gaps1.astro.ucla.edu/nextcloud/index.php/f/7835)

|      Component       |  Base  |  QTY  |  QTY   |  QTY  | Description                              |
|:--------------------:|:------:|:-----:|:------:|:-----:|:-----------------------------------------|
|                      |        | Exact | Spares | TOTAL |                                          |
|    BASE Nutplates    |        |       |        |       |                                          |
|  `GAPS-FRM-MEC-051`  |        |   8   |   2    |  10   | Nutplate 1, Frame                        |
|  `GAPS-FRM-MEC-056`  |        |  14   |   2    |  16   | Nutplate 14, Frame                       |
|  `GAPS-FRM-MEC-076`  |        |  13   |   2    |  15   | Nutplate 16, Frame                       |
|  `GAPS-FRM-MEC-181`  |        |  32   |   4    |  36   | Nutplate 13, Frame                       |
|  `GAPS-FRM-MEC-186`  |        |  12   |   2    |  14   | Nutplate 26, Frame                       |
|  `GAPS-FRM-MEC-604`  |        |  10   |   2    |  12   | Nutplate 35, Frame                       |
|                      |        |       |        |       |                                          |
|    ASSY Nutplates    |        |       |        |       |                                          |
|  `GAPS-FRM-MEC-050`  | `-051` |   -   |   4    |   4   | Nutplate 1 Assy, Frame                   |
|  `GAPS-FRM-MEC-060`  | `-051` |   -   |   4    |   4   | Nutplate 2 Assy, Frame                   |
|  `GAPS-FRM-MEC-055`  | `-056` |   8   |   1    |   9   | Nutplate 14 Assy, Frame                  |
|  `GAPS-FRM-MEC-065`  | `-056` |   4   |   1    |   5   | Nutplate 15 Assy, Frame                  |
|  `GAPS-FRM-MEC-075`  | `-076` |  12   |   1    |  13   | Nutplate 16 Assy, Frame                  |
|  `GAPS-FRM-MEC-180`  | `-181` |   8   |   4    |  12   | Nutplate 13 Assy, Frame                  |
|  `GAPS-FRM-MEC-190`  | `-181` |  16   |   4    |  20   | Nutplate 10 Assy, Frame                  |
|  `GAPS-FRM-MEC-185`  | `-186` |   -   |   6    |   6   | Nutplate 26 Assy, Frame                  |
|  `GAPS-FRM-MEC-195`  | `-186` |   -   |   6    |   6   | Nutplate 27 Assy, Frame                  |
| `GAPS-FRM-MEC-605-1` | `-604` |   4   |   1    |   5   | Nutplate 35 Assy, Frame, PEM Variation 1 |
| `GAPS-FRM-MEC-605-2` | `-604` |   4   |   1    |   5   | Nutplate 35 Assy, Frame, PEM Variation 2 |

- Nut plates associated with `GAPS-FRM-MEC-051` AND `GAPS-FRM-MEC-186`
  are not needed for the droop fix.  However, they are being included
  since they are the nutplates that see a lot of wear from gondola
  separations.  I've already seen some damage to the existing nutplates,
  so these will be replacements/spares going forward.

#### Remaining Components

- Ths section contains all the additional droop fix components that
  do not fall under the above categories.

|      Component       |  QTY  |  QTY   |  QTY  | Description                                                  |
|:--------------------:|:-----:|:------:|:-----:|:-------------------------------------------------------------|
|                      | Exact | Spares | TOTAL |                                                              |
|  `GAPS-FRM-MEC-612`  |   8   |   4    |  12   | Resting block nutplate, TKR diag support                     |
|  `GAPS-FRM-MEC-613`  |   4   |   2    |   6   | Resting block base, TKR diag support                         |
|  `GAPS-FRM-MEC-615`  |   8   |   8    |  16   | Screwplate 46 arm, Frame                                     |
|  `GAPS-TKR-MEC-104`  |   2   |   -    |   2   | Support, Bot TOF, Tracker                                    |
| `GAPS-TKR-MEC-105-1` |   4   |   2    |   6   | Spacer Block, Tracker, Variation 1, anchor and lower threads |
| `GAPS-TKR-MEC-105-2` |   4   |   4    |   8   | Spacer Block, Tracker, Variation 2, all threads              |
|  `GAPS-TKR-MEC-108`  |   4   |   4    |   8   | nutplate, tracker spacer block                               |
|  `GAPS-TKR-MEC-625`  |   5   |   -    |   5   | Rib 1 Inner, Tracker Base                                    |
|  `GAPS-TKR-MEC-629`  |   2   |   -    |   2   | Rib 4 Inner, Tracker Base                                    |
