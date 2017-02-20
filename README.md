# Delta Effector for E3Dv6, Magnetic Mounts, and BLTouch Probe

This is an evolved design originally created by grainiac. I redesigned it to accommodate male magnetic ball joints and a BLTouch probe, along with a few other tweaks. While it was originally designed for a Kossel Pro, it should work fine for any delta printer.

## Offsets

With the effector oriented in the printer as shown in the (frontal)photo, the (XYZ) offsets for the probe are:

-47.06,-26.736,0

**NOTE:**  I'm using Smoothieware and am still in the process of configuring everything for proper auto-calibration routines. There exists the *possibility* that you'll need a different Z-offset. As I learn more, I'll update.

## Built With

* [Pre-built magnetic rods and ball joints](http://amzn.to/2merlxV)
* [E3Dv6 hotend (Bowden)](http://amzn.to/2kZOzrf)
* [Thermoset inserts](http://amzn.to/2meEw23)

**NOTE:**  The rods linked above are sold as 304mm and come with a sticker identifying the precise length from ball center to ball center. (Mine were labeled 304.20) I ended up having to set my rod length in Smoothieware to 283, however, in order to get parts to print at the correct dimensions. Being new to Smoothieware, I'm not sure why that discrepancy exists, but if you use the length labeled on the rods and your parts are coming out undersized, be aware of this.

## Acknowledgments

* Hat tip to grainiac for the original design.# Delta-Effector-E3Dv6-Magnetic-BLTouch
Design files (stl) for a delta effector
