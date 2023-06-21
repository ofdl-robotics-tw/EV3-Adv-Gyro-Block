# Advanced Gyro Block for EV3-G

![image](https://github.com/ofdl-robotics-tw/EV3-Adv-Gyro-Block/assets/17724013/3dd9f512-745f-4761-ab84-f015d8261908)

You can download ev3b file from release page：[Latest](https://github.com/ofdl-robotics-tw/EV3-Adv-Gyro-Block/releases)

This is a Advanced version of Gyro block, you can use Gyro as compass sensor, or read out the TILT value, or using our special made reset function to avoid the drift issues!

For Example, here is the Reset program to avoid gyro drift issue, it's useful for FLL and WRO RoboSports:

![image](https://github.com/ofdl-robotics-tw/EV3-Adv-Gyro-Block/assets/17724013/64ce7d01-10ff-4f43-a556-73343c36c90e)


This Block made By OFDL Taiwan. Any Question? Please contact us [OFDL
Facebook Page](https://www.facebook.com/cljhofdl)

It is recommended that the EV3 Firmware is always updated to the latest
version released from LEGO®. (1.09E recommended)

Adv Gyro Block is not officially supported by the LEGO® Group.

* * * * *

Modes
-----
### ・Gyro As Compass
![image](https://github.com/ofdl-robotics-tw/EV3-Adv-Gyro-Block/assets/17724013/80a94a9a-e850-4b03-8f64-eec3e6da374f)

#### -- Measure Heading
Emulate the HT Compass style, will return the Relative Heading and Absolute Heading (The North (or 0°) depends on when you reset the gyro).
The offset allow you to dynamic adjust the gyro error and adjust the zero degrees. (Offset value should in -360 ~ 360)

#### -- Measure Heading and Rate
Emulate the HT Compass style, will return the Relative Heading and Absolute Heading and Rate.

### ・Measure TILT Value
#### -- Measure Tilt Rate
Measure the Tilt rate (not every gyro sensor have TILT mode)

#### -- Measure Tilt Angle
Measure the Tilt angle (not every gyro sensor have TILT mode)

### ・Gyro Reset
#### -- Reset (Software)
Reset the Gyro Angle/Heading to Zero. (As same as LEGO Gyro Reset block)

#### -- Reset (Hardware)
Hardware level reset the Gyro sensor, it will take up to 2 sec to Reset. (like unplug the wire and replug)

#### -- Reset Result Check
Check the reset is working or not.

* * * * *

[Original Flipped Digital Lab](https://www.facebook.com/cljhofdl), OFDL Taiwan © 2023
