VID6606_595 KiCad projects
===========

the VID6606_595 schema and PCB

Download and compile KiCad by using KiCad_Winbuilder below to open files because the component footprint used in this project has been migrated to the new .pretty format.
https://launchpad.net/kicad-winbuilder

Now KiCad default build has no footprint libraries attached but the libraries were released on github, 
https://www.github.com/KiCad
you MUST do this step so KiCad can read the libraries from github directly:
copy this file
   d:\kicad-winbuilder-3.4\kicad\share\template\fp-lib-table.for-github
to this place, ( remove ".for-github" from the file name )
   %userprofile%\appdata\roaming\kicad\fp-lib-table
This will tell KiCad-CvPCB to read the footprint (modules) from github.
   
   
If you don't want to mess with the schema or the PCB design you can just go to gerber folder and send the files to PCB manufactures to build the sample board.

