---
layout: page
title: "Turbine test bed"
description: ""
group: facilities
---
{% include JB/setup %}

<img style="float:right" src="/assets/images/turbine_test_bed.jpg" width="45%" padding="20px">

The UNH-CORE turbine test bed was originally designed and built in 2010, then upgraded in 2012 along
with the [tow tank's](tow-tank.html) motion, control, and data acquisition systems. The turbine test bed provides
infrastructure for measuring the performance and near-wake flows of turbines at moderate Reynolds number
To date, the system has mainly been used with vertical-axis
(cross-flow) turbines, though it has also been used to test FloDesign's Mixer-Ejector axial-flow hydrokinetic
turbine.

Specifications summary
----------------------

<img style="float:right" src="/assets/images/test_bed_cross_section.png" width="45%">

| Turbine frontal area (nominal) | 1 m<sup>2</sup> |
| Max power dissipation          | 1 kW |
| Max RPM                        | 300 |
| Cont. stall torque             | 240 Nm |
| Peak stall torque              | 818 Nm |
| Max measured torque            | 200 Nm |
| Max measured drag              | 4400 N |
{: class="table table-half table-condensed" rules="groups"}

Loading and control
-------------------
The turbine is loaded via a Kollmorgen AKM62Q servo motor, powered by a Kollmorgen AKD servo drive and 
controlled by the tow tank's main motion controller over the EtherCAT network. Loading the turbine in 
this way provides precise control over the turbine tip speed ratio. By default, the turbine is commanded 
to “jog” at a constant speed by the controller. However, open-loop, or “torque mode” operation is also possible.

Instrumentation
---------------
The main frame is constructed from extruded aluminum NACA 0020 hydrofoil sections, and 
mounted to two drag slide assemblies, each of which can measure up to 500 lbf drag force. 
An Interface T8 200 Nm inline torque transducer is used to measure torque. Additionally, the turbine servo 
motor is mounted on a slewing ring bearing, such that its moment loading is transferred to a load cell mounted 
at a known fixed distance, providing redundancy in torque measurement.

Software
--------
See <a href="https://github.com/petebachant/TurbineDAQ" target="_blank">TurbineDAQ</a> for a desktop GUI 
application used to operated the system.

{::comment}
Related publications
--------------------
The following is a list of publications in which the turbine test bed was used

Related data sets
-----------------

{:/comment}

