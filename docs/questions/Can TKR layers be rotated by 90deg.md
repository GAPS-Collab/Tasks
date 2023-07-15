# Can TKR layers be rotated by 90deg?

Ref. Issue/PR: GAPS-Collab/Tasks#181

## Outline

Can the TKR rows be rotated by 90degs such that even
layers (including layer 0) can be integrated parallel
to the OHP and odd layers perpendicular to the OHP.
This is requested to make construction of Layers 0
easier and less risky.

## Answer

# Answer

**Yes, but it requires redesign and modification to
existing components.**  The is predominately due to
the fact that the OHP is not symmetric about the
central vertical axis of the Tracker and the foam
layers were designed with this in mind.

### 1st Layer of Foam

The first layer of foam (i.e. below Tracker Layer 9)
would need to be redesigned.  With a 90deg rotation
the OHP thru holes no longer lineup with the OHP.  In
the end this is not a hard modification and can be 
done before machining the new set of foam.

![Image](https://github.com/GAPS-Collab/Tasks/assets/29869348/16162af2-a66b-4398-875d-1fc8ec54bd79)


### Even and Odd Foam Layers are Different

In the original setup the foam strips (`GAPS-TKR-MEC-301`) 
used under the even Tracker layers is different than
the foam strip (`GAPS-TKR-MEC-304`) under the odd Tracker
layers.  As a result, if a layer is rotated, then you'd
have to use the foam variation that corresponds to the
new orientation and not the foam strip that was originally
used for the layer.  That is, the odd layer foam strips
would become the even layer foam strips, and visa versa.

In the image below left is `TKR-301` and right is `TKR-304`.
Note the strips look almost identical except for the placement
of the pass-throughs for the OHP.  This is what makes the
two parts unique. It would be difficult to make one universal
foam strip due to the asymmetric pattern of the OHPs.  The
universal foam strip would need OHP pass-thrus up and down 
both sides of the strip, as well as interface board cutouts
on each end.

![image](https://github.com/GAPS-Collab/Tasks/assets/29869348/edbbd788-af5b-457b-8ceb-aa6d6059f9d2)

## Layer 0 Foam Strips (below layer)

The foam strips below Layer 0 are a special a special split 
design of `TKR-301`, with the thin strip `GAPS-TKR-MEC-306`
stacked on top of `GAPS-TKR-MED-305` to make an equivalent 
strip to `TKR-301`.  When rotating the layer the strips will
now need to be based off of `TKR-304`.  Again, this is due
to the asymmetry of the OHPs.

In the image below left is `TKR-305` and right is `TKR-306`.

![image](https://github.com/GAPS-Collab/Tasks/assets/29869348/0c808652-87ce-4b1d-bef8-398d98366a75)

## Layer 0 DET Modules

As Gabe rightfully pointed out, the cooling collar will need
to be relocated the opposite location.  This will also require
the screw holes in that location to be bored out to make 
enough room for the cooling collar mounting screw to pass-through.

## Foam Above Layer 0

There is a three layer stack of foam above Layer 0: 
`GAPS-TKR-MEC-401` which sits on top of the detector modules,
`GAPS-TKR-MEC-404` which sits between `TKR-401` and the OHP to
support the OHP, and `GAPS-TKR-MEC-500` which sits between the
OHP and TOF panel.  While I don't think the later two foam 
layers will need to be modified to rotate the Tracker layers,
`TKR-401` definitely needs to be modified to account for purge
tube routing.

