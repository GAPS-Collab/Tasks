# Umbrella Installation Instructions

* [TOF Hookup scheme](https://gaps1.astro.ucla.edu/wiki/gaps/images/gaps/9/94/TOF_Hookup_Scheme.pptx)
* [TOF Cabling](https://gaps1.astro.ucla.edu/wiki/gaps/index.php?title=TOF_Cabling)

There are 4 main components to installing the Umbrella.

1. Installing the RATs
2. Installing the TOF panels
3. Routing cables from Panels to RATs
4. Routing RAT to TOF-SYS "umbilical" cables through the Umbrella

I recommend installing RATs before any of the TOF panels, and the
remaining major components (2-4) should be installed in an order where
the installer still has access.  Typically one would mount the TOF panel
and then route all the relevant cables from the panel to the associated
RAT.  The umbilical cables need to routed across the UMB frame and
down the diagonals of the UMB frame.

The Umbrella is composed of 6 RATs numbered 1-6 and 7 TOF panels
numbered 7 - 13, see image below.  The image also show which paddles
in which panels get connect to which RAT.  For example, paddle 79 in
panel 09 get connected to RAT 05.

![img.png](umb_layout_and_hookup.png)

## Installing RATs

## Installing TOF Panels

[standoff 10-32 x .281 L]: https://www.mcmaster.com/91780A450/
[standoff 10-32 x .313 L]: https://www.mcmaster.com/91780A453/
[standoff 10-32 x .344 L]: https://www.mcmaster.com/91780A456/

- The UMB TOF panels do not all sit in the same plane, so the order of
  installation matters.  In fact, the umbrella is staggered in 4 layers:

  1. **Top Layer** - Panels 10 & 13
  2. **T - 1** - Panels 8 & 11
  3. **T - 2** - Panels 9 & 12
  4. **T - 3** - Panels 7

- All the listed aluminum nuts/standoffs for mounting panels are .313" L
  ([91780A453][standoff 10-32 x .313 L]), but you can use 9/32" L
  (.281" - [91780A450][standoff 10-32 x .281 L]) and 11/32" L 
  (.344" - [91780A456][standoff 10-32 x .344 L]) standoffs in their place.
- **WHENEVER YOU'RE TIGHTENING A FASTENER NEXT TO A PADDLE DO NOT USE A
  WRENCH, INSTEAD USE A SOCKET.**  This could be a 5/16" socket on a
  driver or a ratchet.  If you have to deal with a threaded road or a
  long screw, then use the [pass-through wrench](https://a.co/d/jaLb467).

### Hardware

[washer no 10 .688 OD]: https://www.mcmaster.com/90313A103/
[washer no 10 .75 OD]: https://www.mcmaster.com/90313A400/

|           Component           |    QTY    | Description & Notes               |
|:-----------------------------:|:---------:|:----------------------------------|
|                               | per panel |                                   |
|      **Panels 10 & 13**       |           |                                   |
|      `GAPS-UMB-MEC-107`       |     1     | Mounting Bar, Inboard             |
|      `GAPS-UMB-MEC-114`       |     1     | Mounting Bar, Outboard            |
|      `GAPS-UMB-MEC-115`       |     6     | Shoulder Washer, Outboard         |
|      `GAPS-UMB-MEC-121`       |     6     | Shoulder Washer, Inboard          |
| WASHER, FOR NO. 10 X .688" OD |    12     | [90313A103][washer no 10 .688 OD] |
| WASHER, FOR NO. 10 X .75" OD  |    12     | [90313A400][washer no 10 .75 OD]  |


### Installation Instructions

