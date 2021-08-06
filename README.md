kicad6 library used by devguard hardware

 - clone the repo
 - Preferences -> Configure Paths
 - add a variable called DGLIB with the path to your clone


for example to add the rpi lib

 - Preferences -> Manage Footprint Libraries
 - you can use the file dialog which should create an entry like
 - dg_rpi , ${DGLIB}/footprints/dg_rpi.pretty
 - Preferences -> Manage Symbol Libraries
 - you can use the file dialog which should create an entry like
 - dg_rpi , ${DGLIB}/symbols/dg_rpi.kicad_sym

