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
- Always creep up on a torque spec!!  **WHEN IN DOUBT, STOP TORQUING AND
  GET A SECOND OPINION FOR SOMEONE WITH EXPERIENCE.**  We do NOT have
  spares for UMB mounts, so a stripped tap or broken screw will set us
  back for a significant period of time.

### Assembly Schematics

[Panel 10 & 13 PDF]: 
[Panel 8 & 11 PDF]:
[Panel 9 & 12 PDF]: 
[Panel 7 PDF]: 

I've generated assembly/BOM documents for each mounting variations.  These
documents have exploded views of the mounts, list of components, and
torque specs.  All the documents are on the GAPS NextCloud, and I'm linking
them below:

* [Panel 10 & 13 PDF]
* [Panel 8 & 11 PDF]:
* [Panel 9 & 12 PDF]: 
* [Panel 7 PDF]:

### Hardware

[washer no 10 .688 OD]: https://www.mcmaster.com/90313A103/
[washer no 10 .75 OD]: https://www.mcmaster.com/90313A400/
[washer no 10 .354 OD 1x]: https://www.mcmaster.com/5360N124/
[washer no 10 .354 OD 2x]: https://www.mcmaster.com/5360N125/

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
https://track.sendcutsend.com/sz9v7qkbybgw

**NOTE:** Currently we only have QTY 24 of the load spreaders `TOF-PAN-011`.  I have
another QTY 24 in production and scheduled to ship on 10/30
([track](https://track.sendcutsend.com/sz9v7qkbybgw)).  Until all the load
spreaders arrive, reserve what we have for inboard mounts and panel 7 mounts.
It won't be difficult to replace outboard mounts before the whole frame is lifted.

1. Before installing any panels, attach the mounting bars to the gondola.
   * This needs to be done first, since some bars have never been mounted and we
     need to ensure that all tapped holes are deep enough to accept the hardware.
   * You don't need to torque the fasteners in this step, just make them hand
     tight.
   * If a tapped hole does NOT have enough threads, then it needs to be tapped
     further.  Take a BOTTOM/BUTT tap and cut a few more threads.  A FLUTE tap
     will likely not work for this step, but a PLUG tap might work.
   * If tapping still does not work, then use either a
     [5360N124][washer no 10 .354 OD 1x] or
     [5360N125][washer no 10 .354 OD 2x], with the latter being the
     thicker one.  Use only one washer and side with using the thinner one.
