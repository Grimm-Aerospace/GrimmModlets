# GrimmModlets

Various KSP mini mods.

Installation: Unless noted otherwise below, each folder can be placed anywhere within your KSP installation's GameData folder.

Use at your own risk, generally **no support provided**. Please feel free to submit pull requests or open issues though.

Dependencies: No hard dependencies. The patches activate and become useful when their respective dependencies are met, use common sense (ie a patch that adds B9PartSwitch features to Malemute obviously requires both B9PartSwitch and Malemute to be installed).

## Contents (GameData)

+ AkitaUntooled - Removes dependency on USI Tools from the Akita rover (this will disable the ground tether functionality).
+ BDBContractsFix - Increases max simultaneous contracts in BDB, so that Apollo mission and others reliably appear.
+ BDBKerbalismScienceUpdate - An update for Kerbalism BDB definitions. Adds missing science experiments and adapts some experiments to make more sense. KeyHole sample returns and GATV samples work as intended in BDB. 
+ KFLateRepulsors - moves Kerbal Foundries repulsors to a new 4000 science node in Community Tech Tree
+ ShowAllTechTreeNodes - Make sure to show all tech nodes regardless of other mods configs.
+ USIB9TankTypes - B9PartSwitch tank types for USI mods. WIP.
+ USIMalemuteB9Patch - B9 tanks for Malemute rover.
+ USIMalemuteWheels - 1.12+ wheels patch for Malemute rover.


## Contents (Extras)

+ BDBCryoTanks - replaces BDB boiloff with CryoTanks boiloff (now part of BDB master branch)
+ CNCJNSQStations - adds CommNetConstellation ground station definitions for JNSQ. Now part of JNSQ. Known issues: 1) Do not change default Ground Station enable/disable settings in base/KK settings pages as it bugs out CNC. 2) Stock Kerbin DSN names appear in flight for some stations, this is just a visual issue and has no gameplay consequences.
+ Historian - my config for Historian (needs Historian, merge with its folder)
+ JNSQUSIWarpDrive - adds scaling to USI WarpDrive for JNSQ
+ KPBSMKSCentrifuge - changes Kerbal Planetary Base Systems nuclear centrifuge to behave like the one in MKS


## TODO

1. add HDD/sample slot upgrades for BDB/Kerbalism
2. fix JNSQUSIWarpDrive patch activation conditions
3. add MKS tank types for B9
4. convert remaining USI mods from FS to B9PS
5. finish adding remaining HDD upgrades starting with ProbeExpansion
