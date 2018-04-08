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
| 1.3.4 [Wheels](readme.md#134-wheels) |
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

The Gantt chart is left deliberately open, this is due to the synergistic design required by all the parts of the car. Instead major milestones have instead been marked such that they reflect the completion dates imposed on the project. Ultimately it is expected that a number of completed parts will require revision at times to increase their efficacy as the vehicle moves towards testing phases. While the design attempts to segment and remove as many dependencies as possible between subsections, it is impossible to treat these parts entirely as black boxes outside of taking each part down to a component level. This is somewhat possible on many of the pre-built items used in the project because there is no major design considerations placed upon these parts which warrant their inclusion.

- acceleration
- deceleration
- steering
- aerodynamics

|  Semester 1 objectives | _1_ | _2_ | _3_ | *4* |  5  |  6  |  7  |  8  |  9  | 10  | 11  | 12  | 13  | MSB  |
|------------------------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|------|
| 1. Thesis              | x   |  x  |  x  |  x  |  x  |  x  |  x  |  x  |  x  |  x  |  x  |  x  |  x  |  x   |
| 1.1 Chassis            |     |     |     |  x  |  x  |  x  |  x  |  x  |     |     |     |     |     |      |
| 1.1.1 R and D          |     |     |  x  |  x  |  x  |     |     |     |     |     |     |     |     |      |
| 1.2 Steering/Suspension|     |     |     |     |     |     |     |     |  x  |     |     |     |     |      |
| 1.3 Drivetrain         |     |     |     |     |     |     |     |     |     |  x  |     |     |     |      |
| 1.4 Brakes             |     |     |     |     |     |     |     |     |     |     |     |     |     |      |
| 1.5 Outer shell        |     |     |     |     |     |     |     |     |     |     |     |     |     |      |
| 1.6 Electrical Systems |     |     |     |     |     |     |  x  |  x  |  x  |  x  |  x  |  x  |  x  |  x   |
| _motor controller_     |     |     |     |     |     |     |  x  |  x  |  x  |     |     |     |     |      |
| _brake controller_     |     |     |     |     |     |     |     |  x  |  x  |  x  |     |     |     |      |
| _steering controller_  |     |     |     |     |     |     |     |     |  x  |  x  |     |     |     |      |


|  Semester 2 objectives | MSB | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 |
|------------------------|-----|----|----|----|----|----|----|----|----|----|----|----|----|----|
| 1. Thesis              | x   | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  | x  |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1.                     |     |    |    |    |    |    |    |    |    |    |    |    |    |    |

note:
- _Weeks marked in italic have passed_
- _MSB = Mid-semester break_
- _Semester 2 starts with week 14_

Major aims include
1) to have a running chassis by the end of semester 1 such that the frame may be driven by remote control. This includes:
   - design and assembly of the structural components making the frame of the body
   - the motor mounted and running by a self designed motor controller
   - the drivetrain and suspension has been assembled and tested, excluding designs for the high speed wheels
   - the steering is working satisfactorily enough to allow safe on-road testing
   - the associated telemetry is at a stage which allows the remote control of the aforementioned aspects

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
  
(from wiki, find refs.)
  George Poteet	Speed Demon streamliner	IC
turbocharged Chevrolet Small Block [15]	439.562	707.408

Don Vesco	Vesco Turbinator	Turboshaft	458.196	737.395	458.444	737.794

because of the great scope of the project, an entire car will not be designed from the ground up. The following components will be reused:
 - suspension
 - steering
 - differentials

The following modifications will be made to a Traxxas XO-1 RC car:
- custom chassis
  - lengthened from original car to accomodate extra batteries, motor controllers
  - space for larger wheels
- front and rear motors, separately feeding diffs
  - 2028 Extreme 800 kV driving rear wheels
  - Mamba big-block 1717 1660 kW driving front wheels
  - top speed gear ratio is 3.855:1, use direct drive gives 2.85:1
- front and read wheels are (approx.) 4.3 inch (from forum, to measure later) - approx 110 mm
  - larger wheels
  - steel belted tyres?
    - standard rc tyres cannot handle the stress
- custom telemetry and remote control link
  
**note: you need a log book**

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

#### 1.3.2.1 Differentials

front and rear differentials of the XO-1 will be utilised
they have a set ratio of 2.85:1

###   1.3.3 Rotational transmission

The gearing should aim to have the top speed at the maximum power point of the motor, theoretically this exists at half the maximum speed for a perfect motor (this needs to be tested for the motors). Given the motor is 800 KV, this implies at 8 cells (8S = 28.8 VDC, LiPo) ~23000 rpm maximum speed, therefore maximum power exists at ~11500 rpm. 

maximum speed = 250 MPH = ~400 km/h = ~112 m/s (rounded up)

| Wheel diameter (mm) | rpm, wheel | rpm, diff | reduction ratio |
|---------------------|------------|-----------|-----------------|
|110 (standard size)  | 19500      | 55500     | 4.83            |
|200 (possible size)  | 10700      | 30500     | 2.65            |



###   1.3.4 Wheels

Wheels convert torque from the drivetrain to force applied to the ground
Wheels must not deliver more force than the (µ.static * mass * g) force (i.e. must not break the static friction) doing so will cause the wheels to spin;
  - shreds tyres
  - µ.kinetic is lower, less force will be transmitted unless the wheels can spin proportionally faster
  - wastes power as heat


##    1.4 Brakes

The braking components of the design form the most important safety feature of all and so therefore must be given heavy consideration. The brakes must be capable of slowing the car down in a controlled manner from the top speed of the vehicle. Given the kinetic energy of a vehicle moving at speed is taken as KE = 1/2 mv^2 ; for an approximately 15 kg vehicle travelling at 100 m/s, there is 75 kJ of energy requiring dissipation to stop. As the aim of the vehicle is to provide a most aerodynamic model so there should be limited aerodynamic drag. This means there must be specific braking mechanisms in place to stop the vehicle. 

Consider a vehicle travelling at 100 m/s, dissipating 75 kJ of energy to its braking system under emergency conditions (therefore the aim is to apply as much braking force as possible). To avoid lock-up conditions the brake force cannot exceed (µ.static * mass * g) force.

at 5 m/s/s, 100 ^ 2 = 2 * a * s => 10000 = 2 * 5 * s => s = 1000/1 = 1000 m
            15 * 5 = 75 N over 20 s, 3750 W

###   1.4.1 Mechanical braking

Mechanical braking options:
- disk brake, such as seen in IC model engines which lack the ability for engine braking
- motor brake, removing energy by using the motor as a generator and sending the energy to a dump load

###   1.4.2 Aerodynamic braking

- flaps which stand proud to increase the drag on the vehicle
- closing duct orifices used to lower the pressure differential between front and back
- parachute
- must not significantly (or at all) increase lift - this may lead to the vehicle taking off

##    1.5 Outer Shell
###   1.5.1 Shell

The outer shell is largely dominated by two factors:
- containing the inner components to provide protection from weather conditions and windborne particulates
- provide an aerodynamic advantage that is lost of open designs as the high speed wind causes turbulent drag as it passes around the inner components
- provide weight (downforce) to increase traction and stability

It is 


###   1.5.2 Undercarriage

The undercarriage is largely in place to ensure predictable ground effects are in place.

###   1.5.3 Active
##    1.6 Electrical systems
###   1.6.1 Energy Source

Energy will be sourced from lithium based batteries, further comment when it is known what is available to use, dimensions, etc.

###   1.6.2 Wiring loom
###   1.6.3 Motor controller
###   1.6.4 Steering controller
###   1.6.5 Active system controls
###   1.6.6 Sensors
###   1.6.7 Processing
###   1.6.8 Telemetrics
