# mHub Shop Bot Tool Crib #
### Written by Jon Komperda ###

The purpose of this repo is to keep an up-to-date tool crib for the Shop Bot CNC router located at mHub in Chicago, Illinois.

The repo contains tool cribs for Solidworks HSMWorks, Autodesk Fusion 360, and a tab delimited format if you'd like to attempt to import into other software.

## Table of Contents ##
1. [Cutter Assumptions](#cutter-assumptions)
2. [Cutting Depth Table](#cutting-depth-table)
3. [Installation Instructions](#installation-instructions)
   1. [HSMWorks](#solidworks-hsmworks)
   2. [Fusion 360](#fusion-360)

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

## Installation Instructions ##
### Solidworks HSMWorks ###
1. Go to the CAM tab
2. Select "Tool Library"
3. Expand "My Libraries"
4. Right-click "My Libraries" and select "New Library"
![New Library](/docs/images/hsm-newlib.png)
5. Name the library "mHub Shopbot"
6. Right-click the newly created "mHub Shopbot" library and select "Import Tools from Library..."
![Import Library](/docs/images/hsm-importtool.png)
7. Go to the downloaded files and navigate to the HSMWorks folder and select the tool library file.

### Fusion 360 ###
(coming soon)
