# Anycubic_Chiron_Klipper
This is the klipper config file for a Anycubic Chiron with a Biqu H2 direct extruder.

Please consider this config file as a starting point and not a working copy and paste solution.

- The hotend heater and parts fan are not connected to the default pins, i needed to change them, so please change it to your needs.
- change MCU serial to yours
- BE CAREFUL with the stepper_z position_endstop value, the one here is for my mashine, you need to calibrate your bed and setting this value before you can use your printer
- pressure_advance is set to zero in thtis config file, change it to your needs
