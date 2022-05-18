#hps-kicad-library

The contents of the library directory are the following:

- symbols    : Schematic symbols
- footprints : PCB footprints
- packages3d : 3D models for the component footprints

In order to access and use the schematic symbols open KiCAD and select Preferences->Manage Symbol Libraries... and add the HPS.kicad_sym file
contained in the 'symbols" directory to the "Global Libraries" list (second button from left).

In order to access and use the PCB footprints open the PCB editor and select Preferences->Manage Footprint Libraries... and add the 'footprints"
directory to the "Global Libraries" list (second button from left). The nickname of this library must be 'footprints'. The nickname 'footprints" is
hardcoded in some of the schematic symbols that have their PCB footprints pre-assigned.

In order to use the 3D features you must define a KICAD environment variable to point to the packages3d directory of this library. From the KiCad
main window select Preferences->Configure Paths... and add a variable with the name HPS3DMOD and the path must point to the packages3d directory.
The path must include the 'packages3d' directory. The 'HPS3DMOD' environment variable is hardcoded in each footprint as part of it path to the
corresponding 3D file.


Inquiries to matthew@
