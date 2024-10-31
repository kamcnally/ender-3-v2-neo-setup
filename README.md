# ender-3-v2-neo-setup

## Current settings
```
Send: M503
Recv: echo:; Linear Units:
Recv: echo:  G21 ; (mm)
Recv: echo:; Temperature Units:
Recv: echo:  M149 C ; Units in Celsius
Recv: echo:; Filament settings (Disabled):
Recv: echo:  M200 S0 D1.75
Recv: echo:; Steps per unit:
Recv: echo:  M92 X161.10 Y80.50 Z400.00 E138.95
Recv: echo:; Max feedrates (units/s):
Recv: echo:  M203 X500.00 Y500.00 Z10.00 E50.00
Recv: echo:; Max Acceleration (units/s2):
Recv: echo:  M201 X1000.00 Y1000.00 Z100.00 E5000.00
Recv: echo:; Acceleration (units/s2) (P<print-accel> R<retract-accel> T<travel-accel>):
Recv: echo:  M204 P1500.00 R5000.00 T1500.00
Recv: echo:; Advanced (B<min_segment_time_us> S<min_feedrate> T<min_travel_feedrate> J<junc_dev>):
Recv: echo:  M205 B20000.00 S0.00 T0.00 J0.20
Recv: echo:; Unified Bed Leveling:
Recv: echo:  M420 S1 Z10.00 ; Leveling ON
Recv: 
Recv: Unified Bed Leveling System v1.01 active
Recv: echo:Active Mesh Slot 0
Recv: echo:EEPROM can hold 6 meshes.
Recv: 
Recv: echo:; Material heatup parameters:
Recv: echo:  M145 S0 H210.00 B60.00 F128
Recv: echo:  M145 S1 H240.00 B90.00 F128
Recv: echo:  M145 S2 H230.00 B80.00 F128
Recv: echo:  M145 S3 H190.00 B50.00 F128
Recv: echo:; Bed PID:
Recv: echo:  M304 P211.76 I41.36 D722.81
Recv: echo:; Display Sleep:
Recv: echo:  M255 S5 ; (minutes)
Recv: echo:; LCD Brightness:
Recv: echo:  M256 B127
Recv: echo:; Power-loss recovery:
Recv: echo:  M413 S0 ; OFF
Recv: echo:; Retract (S<length> F<feedrate> Z<lift>):
Recv: echo:  M207 S5.00 W13.00 F2400.00 Z0.20
Recv: echo:; Recover (S<length> F<feedrate>):
Recv: echo:  M208 S0.00 W0.00 F2400.00
Recv: echo:; Z-Probe Offset:
Recv: echo:  M851 X-40.40 Y-11.40 Z-2.54 ; (mm)
Recv: echo:; Input Shaping:
Recv: echo:  M593 X F29.14 D0.15
Recv: echo:  M593 Y F29.14 D0.15
Recv: echo:; Hotend Idle Timeout:
Recv:   M86 B0 E0 S600 T170
Recv: echo:; Linear Advance:
Recv: echo:  M900 K0.00
Recv: echo:; Filament load/unload:
Recv: echo:  M603 L0.00 U100.00 ; (mm)
Recv: echo:; Filament runout sensor:
Recv: echo:  M412 S0 D25.00 ; Sensor OFF
Recv: echo:; Model predictive control:
Recv: echo:  M306 E0 P40.00 C14.11 R0.1842 A0.1214 F0.1442 H0.0056
Recv: echo:; Physical minimums:
Recv: echo:  C100 X-2 Y0
Recv: echo:; Physical maximums:
Recv: echo:  C101 X242 Y230 Z227
Recv: echo:; Bed size:
Recv: echo:  C102 X230 Y230
Recv: echo:; Mesh Insets and leveling settings:
Recv: echo:  C29 L28.40 R201.60 F28.40 B201.60 N5 T60 V1 ; 5x5 T=60 C
Recv: echo:; Max Extruder temperature:
Recv: echo:  C104 T275
Recv: echo:; Park Head:
Recv: echo:  C125 X240 Y221 Z20
Recv: echo:; Filament runout sensor:
Recv: echo:  C412 M0 ; Active mode: LOW
Recv: echo:; Invert Extruder:
Recv: echo:  C562 E0 ; No inverted
Recv: echo:; Probe Z Fix, Speed and Multiple Probing:
Recv: echo:  C851 F0.00000 S480 M0
Recv: ok P15 B15
```
