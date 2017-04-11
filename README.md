# mHub Shop Bot Tool Crib #
### Written by Jon Komperda ###

The purpose of this repo is to keep an up-to-date tool crib for the Shop Bot CNC router located at mHub in Chicago, Illinois.

The repo contains tool cribs for Solidworks HSMWorks, Autodesk Fusion 360, and a tab delimited format if you'd like to attempt to import into other software.

## Cutter Assumptions ##
There are a few assumptions made about the defaults in this file:
1. Feeds and speeds are calculated using GWizard. All feeds and speeds are optimized for minimal tool deflection of 0.001" (rough cutting).
2. Since feeds and speeds are calculated and not tested, it is possible to break a tool. Use these defaults at your own risk.
3. Tool holder is based on approximate measurements. There is no gaurantee you will not crash based on simulations performed in CAM software. Give yourself clearance/height when machining.

## Cutting Depth Table ##
Feed and speed calculations are based on the following table:

Diameter | Depth of Cut (DoC)
-------------|--------------
0.5" | 0.5"
0.25" | 0.25"
0.125" | 0.06"
