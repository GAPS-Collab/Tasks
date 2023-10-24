# Installation Instructions for UMB Reinforcement Member

This document defines the installation instructions for the UMB
reinforcement member, `GAPS-FRM-MEC-061`.

## Documents

* [PDF schematic for `GAPS-FRM-MEC-061`](https://gaps1.astro.ucla.edu/nextcloud/index.php/f/7333)

## Components

[98023A029]: https://www.mcmaster.com/98023A029/
[98023A114]: https://www.mcmaster.com/98023A114/
[92620A564]: https://www.mcmaster.com/92620A564/
[92979A154]: https://www.mcmaster.com/92979A154/

| Component            | QTY |    Links    | Notes                                     |
|:---------------------|:---:|:-----------:|:------------------------------------------|
| `GAPS-FRM-MEC-061`   |  2  |             | reinforcement member                      |
| `GAPS-FRM-MEC-104`   |  8  |             | 3D printed spacer                         |
| `GAPS-FRM-MEC-105`   | 12  |             | Al spacer                                 |
|                      |     |             |                                           |
| WASHER, FOR 1/4"     | 24  | [98023A029] | SAE, GRADE 8, ZINC YELLOW CHROMATE PLATED |
| WASHER, FOR NO. 10   | 12  | [98023A114] | SAE, GRADE 8, ZINC YELLOW CHROMATE PLATED |
| SCREW, 1/4-28 X 1" L | 24  | [92620A564] | GRADE 8, ZINC YELLOW-CHROMATED PLATED     |
| SCREW, 10-32 X 1" L  | 12  | [92979A154] | GRADE 5, ZINC-PLATED                      |

## Installation Instructions

1. If not done already, remove the 10-32 screws from the ATLAS nuts on
   the main frame member `GAPS-FRM-MEC-510`.  To remove the screw, first
   score the powder coating along the seam where the screw head mates
   to the ATLAS nut.  Now, using a heat gun heat the fastener, with a
   focus on heating the surrounding area (i.e. ATLAS nut) and not the
   screw.  When hot enough the screw should just spin out.  Repeat the
   scoring and heating until the screw loosens.  With the screw removed,
   sand any remaining powder coating until it is smooth.  It does not
   need to be completely removed, just smooth.
2. Push the 3D printed spacers `-104` into the reinforcement members
   `-061`.  This should be a tight fit.  If the spacers do not press
   into the reinforcement member, then the 3D printed spacers can be
   sanded to fit.  You can also first cool the spacers in a fridge or
   freeze to get them to shrink a little.  Just do a test batch first
   to ensure they will not crack.
3. Remove the 6x 1/4-28 bolts at the tip of the main gondola screw
   plate `GAPS-FRM-MEC-047`.  This will require a similar methodology
   as described in \#1. You will need a 7/16" wrench or socket.  The
   main gondola member `-510` will remain attached to `-047` since there
   are two separate nut plates securing it.
4. Place the aluminum spacers `-105` on top of the ATLAS nuts that are
   installed in the main gondola member.  Make sure the ATLAS nut sits
   inside the counterbore of the spacer.  The spacer itself should not
   touch the main gondola member and only rest on the ATLAS nut (See 
   reason in step \#8 on torquing).
5. Place the reinforcement member onto the gondola, be careful NOT to
   knock the `-105` spacers out of place.
6. Using a hardware stack of a 1/4-28 x 1" screw ([92620A564]) and washer
   [98023A029], bolt the reinforcement member to the main gondola
   screwplate `-047`.  At this stage do NOT tighten any of the bolts,
   just make them finger tight and then back them off 1/4 to 1/2 a turn.
   This will give you enough freedom to move the part and get all
   fasteners in place.
7. Using a hardware stack of a 10-32 x 1" screw ([92979A154]) and washer
   [98023A114], fasten the reinforcement member to the ATLAS nuts
   installed in the main gondola member `-510`.  If any of the aluminum
   washers `-105` slipped out of place, then you should be able to push
   them back, assuming you did NOT tight during step \#6.
8. Assuming everything looks good, now you can torque.
     * Start with the 1/4"-28 bolts and torque to **160 in-lbs**.  Do
       this in 3 progressive steps reaching the final torque on the 3rd
       step.  Every bolt should be torqued at each step before moving
       to the next torque value.
     * The 10-32 screws can now be torqued to **42 in-lbs**.  Creep up on
       this torque spec to ensure the ATLAS nut does not start spinning.
       If the aluminum spacer `-105` was position correctly, then it
       should be clamped against the ATLAS nut and an approximate .015" gap
       will remain between the spacer and frame member `-510`.  If this
       is not the case, then the ATLAS nut will start spinning at a much
       lower torque value.
9. Repeat steps 1-8 for the second reinforcement member.
