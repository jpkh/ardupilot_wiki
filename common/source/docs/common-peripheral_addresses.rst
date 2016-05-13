.. _common-peripheral_addresses:

==============================
Peripheral Addresses
==============================


.. note::

    Collection of well known Ardupilot project related devices and their known
    addresses. 


The rest of the article provides an overview of some of the devices used on ArduPilot project.


I2C devices
===========

Internal devices
----------------

Internal devices are mostly IC's mounted on autopilot hardware such as compasses, pressure sensors and so on

 - HMC5883 Compass 0x1E


External devices
----------------

External devices such as Tri color leds, power modules, compasses, smart batteries, speed sensors and so on.

- Solo LEDs: 0x68, 0x69, 0x6A, 0x6B
- IRLock: 0x54
- RGB Led: 0x55
- Smart battery: 0x0B
- Smart charger: 0x12



[copywiki destination="copter,plane,rover,planner,planner2,antennatracker,dev,ardupilot"]
