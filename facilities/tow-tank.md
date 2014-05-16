---
layout: page
title: "Tow and wave tank"
description: ""
group: facilities
---
{% include JB/setup %}

![Tow/wave tank](/assets/images/tow_tank_overview.jpg)

Our tow/wave tank, located at the Jere A. Chase Ocean Engineering Laboratory, was constructed
in 1996, and its linear motion, control, and data aquisition systems were redesigned and
renovated in 2012. 

The tank is also home to our [turbine test bed](turbine-test-bed.html).

Specifications summary
----------------------

| Width, depth, length | 3.66 m, 2.44 m, 36 m |
| Max tow speed        | 3 m/s |
| Max acceleration     | 2 m/s<sup>2</sup> |
| Max drag force       | 5400 N |
| Positioning accuracy | &plusmn;0.5 mm |
| Speed accuracy[^1]   | &plusmn;0.2 mm/s at 1 m/s |
| Wave spectra         | Regular, JONSWAP, Bretschneider, Pierson--Moskowitz |
| Max wave height      | 0.4 m |
| Wave period range    | 1--4 s |
{: class="table table-condensed" rules="groups"}

[^1]: Note: this is a mean value taken while towing the UNH-RVAT turbine at a tip speed ratio $$\lambda=1.9$$.


Linear motion and control
-------------------------
Along the length of the tank are two 1.25 inch diameter 440C stainless steel linear shafts, 
guiding the motion of the
main tow and YZ traversing carriage. The carriage motion is actuated by a permanent magnet servo motor,
driving an ATL20 timing belt. Servo drives for the carriage, [turbine test bed](turbine-test-bed.html),
and YZ traverse motors
are all controlled by an EtherCAT master real time controller, providing precise synchronization between
all components.

Data acquisition and on-board accessories
-----------------------------------------
The data acquisition (DAQ) system is based around a Natioal Instruments 9188 CompactDAQ Ethernet chassis. 
Various modules are available for sampling analog voltage, bridge-based measurements, and digital measurements,
including sampling carriage position from the 10 &mu;m resolution linear encoder. 

Data collection from motion control devices is also possible through the main motion controller, 
and from up to 8 serial devices simultaneously. 

There is enough AC power available on board the carriage to operate a high frame rate particle image velocimetry 
(HFR-PIV) system.
An additional servo drive on the carriage is used to provide precise control of turbine RPM when operating the
[turbine test bed](turbine-test-bed.html). There is also a 2-axis stepper drive, mainly used to control the y- 
and z-location of a Nortek Vectrino acoustic Doppler velocimeter (ADV).

---
