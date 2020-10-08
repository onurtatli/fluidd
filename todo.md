# TODO [fluidd]

## Next Up
- Config file list / editing
- move to mdi svg icons, and reduce overall size
- dynamic favicon that looks like the percent finished ring
- impl quick print button
- expand current print metadata (with bigger thumb?)

## Known Bugs:
- multi line gcodes not having a Send: prefix after the first line
- if you complete a print, then delete the original gcode;
  - then you can still attempt to reprint something that's no longer there and;
  - the metadata load fails because the file is no longer there.

## General Improvements
- draggable dashboard panels
- allow contraction and expansion of dashboard panels
- implement new console history
- add console.log wrapper for dev vs prod
- add a throttle to temp updates, print timers, position trackers.
- Performance / memory heap checks
- add status of heater_fans (extruder fan and controller fan)
- allow theme change dark / light
- stick git version in the footer somewhere for klipper, moonraker and fluidd
- filter out temp waits from console
- cancel and pause really need a confirm dialog

## Filesystem Improvements:
- file expand details for metadata
- ability to move folder / files
- better place for print thumbs

## [Page] UI Settings
- temp presets (needs config)
- rotate camera
- power control module

## [Page] Printer Configuration
- add widget for setting z offset during configuration
- add a widget to configure ztilt
- machine limits (set velocity, accel, decel and square corner velocity)

## User wants
- Dry run. (print without extruding)
- Cancel object, cancel area,
- gcode viewer that works with more than 25mb
- timelapses
- plugins for raise cloud, astroprint and alike
- to remote access without vpn and shit
- more secure