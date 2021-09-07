# VAWT #

<p align="center">
  <img width="500" height="1000" src="https://user-images.githubusercontent.com/75654428/132063026-0ff7e066-e732-4965-addc-4b3541979ebd.png" width="500" height="900">
</p>

## What is a VAWT? ##

"A vertical-axis wind turbine (VAWT) is a type of wind turbine where the main rotor shaft is set transverse to the wind (but not necessarily vertically) while the main components 
are located at the base of the turbine. This arrangement allows the generator and gearbox to be located close to the ground, facilitating service and repair. VAWTs do not need to 
be pointed into the wind, which removes the need for wind-sensing and orientation mechanisms. Major drawbacks for the early designs (Savonius, Darrieus and giromill) 
included the significant torque variation or "ripple" during each revolution, and the large bending moments on the blades. Later designs addressed the torque ripple issue by
sweeping the blades helically (Gorlov type). Savonius vertical-axis wind turbines (VAWT) are not widespread, but their simplicity and better performance in disturbed 
flow-fields, compared to small horizontal-axis wind turbines (HAWT) make them a good alternative for distributed generation devices in urban environment." - Wikipedia


This wind turbine is specifically a Savonius wind turbine

"The Savonius turbine is one of the simplest turbines. Aerodynamically, it is a drag-type device, consisting of two or three scoops. Looking down on the rotor from above, a two-scoop machine might resemble the letter "S" in cross section. Because of the curvature, the scoops experience less drag when moving against the wind than when moving with the wind. The differential drag causes the Savonius turbine to spin. Because they are drag-type devices, Savonius turbines extract much less of the wind's power than other similarly-sized lift-type turbines. In practice, much of the swept area of a Savonius rotor may be near the ground if it has a short mount without an extended post, making the overall energy extraction less effective due to the lower wind speeds found at lower heights." - Wikipedia

## Project ##

I am trying to create a single-stage Savonius VAWT out of 3D-printed parts and recycled soda cans. 

## Design CAD files ##

Design is stored in A360: https://a360.co/2UapfG3

Download Fusion 360 for free: https://www.autodesk.com/products/fusion-360/personal-form?

## Turbine Blades ##

I am attempting to reach a final design for the turbine core (axle, part that holds the axle, and generator), but the rotor will be interchangeable, which allows for experimentation.

Due to the interchangeable nature of the rotor, it is also possible to create a different kind of VAWT, not just Savonius. Any other type of VAWT rotor can be attached to the shaft of the turbine.

## Parts Needed ##

Turbine Core (Non-Printed)

- 1" diameter (inner diameter) PVC pipe, 15cm+ length
- 3x M3 x 12mm machine screws
- 3x M3 x 6mm machine screws
- Nema 17 Stepper motor (non-specific for now)
- 2x 608 ball bearings
- 1x 1/4" diameter aluminum rods, preferably 1m in length

Turbine Core (Printed)

- 1x pipeEndCap
- 2x bearingSleeve
- 1x stepperMount
- 1x motorToAxleCoupler

Rotor (Non-Printed)

- 24x soda cans (large rotor) || 6x soda cans (small rotor)
- Aluminum Tape

Rotor (Printed)

- 3x large...RibSplit (large rotor) || 2x small...Rib (small rotor)

Other Electronics
  
- 4x 1N5822 DO-201 AD diodes
- 2x 50V capacitor (specific uF doesn't really matter)

## Blade Creation ##

Create blades by cutting soda cans into flat sheets and taping them together with aluminum tape. 

## Assembly ##

Most assembly can be figured out by looking at the CAD files. For parts that aren't attached together with screws, hot glue/superglue/high friction materials need to be used. I personally used a lot of hot glue, but that may not be the most effective.

## Electronics ##

In order for the generator to be effective, a bridge rectifier is needed. 
Details for its creation can be found in this video: https://www.youtube.com/watch?v=-zCTggoh994
