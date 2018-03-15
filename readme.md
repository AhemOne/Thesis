**By: Jesse Falzon**

**Supervisor: Dr. C. Menictas**

University of New South Wales, Sydney. Year started: 2018

| **Contents** |
|--------------|
| 1. [Thesis](readme.md#1-thesis) |
| 1.1 [Chassis](readme.md#11-chassis) |
| 1.2 [Steering and Suspension](readme.md#12-steering-and-suspension) |
| 1.2.1 [Steering](readme.md#121-steering) |
| 1.2.1.1 [Actuation system](readme.md#1211-actuation-system) |
| 1.2.1.2 [Linkages](readme.md#1212-linkages) |
| 1.2.1.3 [Damping](readme.md#1213-damping) |
| 1.2.2 [Front Suspension](readme.md#122-front-suspension) |
| 1.2.2.1 [Spring](readme.md#1221-spring) |
| 1.2.2.2 [Damper](readme.md#1222-damper) |
| 1.2.2.3 [Linkages](readme.md#1223-linkages) |
| 1.2.3 [Rear Suspension](readme.md#123-rear-suspension) |
| 1.2.3.1 [Spring](readme.md#1231-spring) |
| 1.2.3.2 [Damper](readme.md#1232-damper) |
| 1.2.3.3 [Linkages](readme.md#1233-linkages) |
| 1.3 [Drivetrain](readme.md#13-drivetrain) |
| 1.3.1 [Motor](readme.md#131-motor) |
| 1.3.2 [Gearing](readme.md#132-gearing) |
| 1.3.3 [Rotational transmission](readme.md#133-rotational-transmission) |
| 1.4 [Brakes](readme.md#14-brakes) |
| 1.4.1 [Mechanical braking](readme.md#141-mechanical-braking) |
| 1.4.2 [Aerodynamic braking](readme.md#142-aerodynamic-braking) |
| 1.5 [Outer Shell](readme.md#15-outer-shell) |
| 1.5.1 [Shell](readme.md#151-shell) |
| 1.5.2 [Undercarriage](readme.md#152-undercarriage) |
| 1.5.3 [Active](readme.md#153-active) |
| 1.6 [Electrical systems](readme.md#16-electrical-systems) |
| 1.6.1 [Energy Source](readme.md#161-energy-source) |
| 1.6.2 [Wiring loom](readme.md#162-wiring-loom) |
| 1.6.3 [Motor controller](readme.md#163-motor-controller) |
| 1.6.4 [Steering controller](readme.md#164-steering-controller) |
| 1.6.5 [Active system controls](readme.md#165-active-system-controls) |
| 1.6.6 [Sensors](readme.md#166-sensors) |
| 1.6.7 [Processing](readme.md#167-processing) |
| 1.6.8 [Telemetrics](readme.md#168-telemetrics) |

# Gantt Chart

|  Semester 1 objectives |  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 | 10 | 11 | 12 | 13 | MSB |
|------------------------|----|----|----|----|----|----|----|----|----|----|----|----|----|-----|
| 1. Thesis              | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  | x   |
| 1.1                    | x  | x  |    |    |    |    |    |    |    |    |    |    |    |     |

|  Semester 2 objectives | MSB | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 |
|------------------------|-----|----|----|----|----|----|----|----|----|----|----|----|----|----|
| 1. Thesis              | x   | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |

note:
- _MSB = Mid-semester break_
- _Semester 2 starts with week 14_

#     1. Thesis

The current state of the art:
- [Current record holder](http://www.guinnessworldrecords.com/world-records/fastest-battery-powered-remote-controlled-model-car-(rc))
- [Internals](https://wheels.blogs.nytimes.com/2011/07/18/remotely-hobbyist-takes-control-of-a-tiny-200-m-p-h-super-car/)
- [Small info. nuggets](https://www.rcgroups.com/forums/showthread.php?2038871-New-Guinness-World-Record%C2%97FASTEST-BATTERY-POWERED-RC-CAR)
- [nuggets 2](http://www.redrc.net/2009/10/guinness-certifies-nic-case’s-speed-record/)

This can be summarised as:
- Record speed: 325 km/h
- streamlined body, based off [Team Associated](https://www.teamassociated.com) TC3 chassis (now discontinuted)
  - body was lengthened
  - TC => Touring Car
  
Full size [record holders](https://www.livescience.com/32882-worlds-fastest-vehicles.html)
- ThrustSSC - Land speed record holder
  - 1,227.986 kph
  - [Information from the makers](http://www.thrustssc.com/thrustssc/contents_frames.html)
  - [BloodhoundSSC](http://www.bloodhoundssc.com/education) - next iteration from ThrustSSC
  
- The Bugatti Veyron Super Sport - Fastest production car
  - 267.81 mph (431.072 kph). Set in 2010.

- BUB - Lucky 7 Streamliner - Fastest motorcycle (official)
  - 367.382 mph (591.244 kph). Set at Bonneville Speedway, Utah in 2009.

- Top Oil-Ack Attack streamliner - Fastest motorcycle (unofficial)
  - 376.363 mph (605.697 kph). Set at Bonneville Speedway, Utah in 2010.

- Spirit of Australia speedboat - Fastest boat
  - 317.596 mph (511.13 kph). Set in 1970.

- Westland Lynx 800 G-Lynx - Fastest helicopter
  - 249.1 mph (401 kph). Set in 1986.

##    1.1 Chassis

  The Chassis is designed to support all parts 

##    1.2 Steering and Suspension
###   1.2.1 Steering
####  1.2.1.1 Actuation system

The functional requirements of steering actuation:
- withstanding the forces applied without changing the positioning
- have enough force to push against the the aforementioned forces to change positioning when required
- light enough not to impose a large weight penalty to the vehicle
- small enough not to intrude into the air space around the vehicle
- large changes at low speed to minimise turning radius at low speeds
- small changes at high speed to maximise stability and positional accuracy

####  1.2.1.2 Linkages

The functional requirements of the linkages are:
- light enough as to not impose a weight penalty to the vehicle
- strong enough to withstand the applied forces
- any exposed parts must be as aerodynamic as possible to minimise drag losses

####  1.2.1.3 Damping

The functional requirements of the steering damping are:
- must reduce the impact upon the linkages/actuators such that they are not damaged by bumps
- must not impede the steering actuators from changing position quickly

###   1.2.2 Front Suspension
####  1.2.2.1 Spring
####  1.2.2.2 Damper
####  1.2.2.3 Linkages
###   1.2.3 Rear Suspension
####  1.2.3.1 Spring
####  1.2.3.2 Damper
####  1.2.3.3 Linkages
##    1.3 Drivetrain
###   1.3.1 Motor

Jaycar motor:
- Standard RC540 size motor (36mm x 50mm)
- Brushless motor - 3300 rpm/Volt
- Shaft Diameter - 3.175mm (1/8)

Electronic Speed Controller Specifications:
- Low battery voltage cut-off to protect LiPO batteries from damage
- Over temperature protection
- Max current - 75A
- Battery Input - 7.2V Ni-MH, or 7.4V Li-Po

Castle Creations motor:
- [2028 extreme](http://www.castlecreations.com/en/2028-extreme-800kv-motor-060-0054-00)

###   1.3.2 Gearing
###   1.3.3 Rotational transmission
- Driveshafts
- Belts
- differential
##    1.4 Brakes
###   1.4.1 Mechanical braking
###   1.4.2 Aerodynamic braking
##    1.5 Outer Shell
###   1.5.1 Shell
###   1.5.2 Undercarriage
###   1.5.3 Active
##    1.6 Electrical systems
###   1.6.1 Energy Source
###   1.6.2 Wiring loom
###   1.6.3 Motor controller
###   1.6.4 Steering controller
###   1.6.5 Active system controls
###   1.6.6 Sensors
###   1.6.7 Processing
###   1.6.8 Telemetrics
