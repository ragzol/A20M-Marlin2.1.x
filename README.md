# A20M-Marlin2.1.x
Geeetech A20M 3D printer Marlin-bugfix-2.1.x firmware
with ZsYong 2 in 1 Hotend

Features:

ATMEGA2560 Boards:
Baud 250000
Drivers:
X,Y,Z,E2: TMC2208_Standalone
E0,E1: LV8729

Pid Autotune Menu with Manual Editing (Hotend and bed)
Accel/feedrate/junction deviation tuning
S curve acceleration
Custom preheat profiles (adjustable in config)
Nozzle parking
Improved LCD knob responsiveness
New buzzer frequency (2028hz)
Mutable buzzer
LCD Bed Leveling Menu
5x5 Manual Mesh Bed Warping Compensation
Comprehensive tramming menu
New progress bar logic
Babystepping menu
Power loss resume (finer resume)
Filament runout detection
Custom SD abort and finish codes
Auto report SD status
Linear Advance (Enabled but set to 0 for those who don't use it)
Arc Weld support
Quick homing
Advanced print pausing
improved filament change
BL Touch ABL specifics:
Z homing uses probe only
Faster and accurate probing pattern (5x5 still)
High Speed Mode
M48 repeatability test
Billinear Mesh w/grid extrapolation and 3x subdivision
Safe Homing w/broken endstop detection
Assisted Tramming
Babystepping combined with probe offset

Dual Z driver - E2
Z stepper align
