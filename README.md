These files are based on https://github.com/Andrik45719/ZY-M100 Sensor patching, to make the Sensors less spammy. 
These are patched to silence DP 104 ("none or exist", currently not even handled by home assistant) and DP 255 which is also not handled by HA.
One of the 2 mods also silences the illuminance packets, in case you don't need them.

So the 2 versions for the TZE204_ya4ft0w4:
1) TZE204_ya4ft0w4_extra_Silent_WithLightSensorEnabled.bin: Andrik's version without DP104 and DP255
1) TZE204_ya4ft0w4_extra_Silent_No_light_sensing.bin: Same as 2 but without illuminance.

Now also support for sensor TZE200_gkfbdvyx in 3 versions:
1) TZE200_gkfbdvyx Less often Spam.bin: Andrik45719 type patch, so less often spam
2) TZE200_gkfbdvyx_EvenlessSpam_without_DP104_And_DP255.bin: Same as 1 but without DP 104 and DP 255
3) TZE200_gkfbdvyx_LeastSpam_without_DP104_And_DP255_And_illuminance.bin: Same as 2 but without illuminance

Please refer to Andrik45719's Github for instructions on how to flash.

A Big thank you to Andrik45719 for his work!!
