
# Mgn12c x-rail for voron 0.1 - probably a terrible idea
An idea to replace the x-extrusion and mgn7h rail with a lone mgn12c rail.

## Why
- Wanted to see if moving the carriage to the front helps with ridgity
- Changed to a heavily modified trident carriage to clamp the belts
- Used a mini after sherpa extruder as the hole spacing for mini-ab didn't want to gel with the mgn12c rail
- Klicky for both z-endstop and screw tilt adjust
- But primarily because I'm a tinkerer

![Overview](Images/Overview.png)

## Status
- Printed and fitted to my v0.1
- Subsequent change to m3x35 bolts to hold cowling

![RailAssembly](Images/RailAssembly.png)

## Likely issues
- Reduced hot-end airflow
- Heavier - not by as much as you'd think
- Rail guides are exactly the size of the mgn12 rail - should there be some allowance?
- Had to move the X idlers 1mm forward to create space for the rail support bolts

![RailAssemblyRear](Images/RailAssemblyRear.png)

## Bodges
- Ugly end-stop bumpers
- The m3x30 rail support bolts protrude creating tight clearance with the relocated x-endstop
- X-endstop is relocated to the rail (update your [homing](https://github.com/richardjm/voron0pi-klipper-backup) routines)
- Multiple minor cad cleanups to cowling (e.g. extra room for belt surplus)

![RailSupport](Images/RailSupport.png)

Discord: Whistlinric