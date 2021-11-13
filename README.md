# GrimmModlets

Various KSP mini mods.

Installation: Unless noted otherwise below, each folder can be placed anywhere within your KSP installation's GameData folder.

Use at your own risk, generally **no support provided**. Please feel free to submit pull requests or open issues though.

Dependencies: No hard dependencies. The patches activate and become useful when their respective dependencies are met, use common sense (ie a patch that adds B9PartSwitch features to Malemute obviously requires both B9PartSwitch and Malemute to be installed).

## Contents (GameData)

+ AkitaUntooled - Removes dependency on USI Tools from the Akita rover (this will disable the ground tether functionality).
+ BDBContractsFix - Increases max simultaneous contracts in BDB, so that the Apollo mission and others reliably appear.
+ BDBKerbalismUpdate - A series of patches to bridge the gap between Kerbalism and Bluedog Design Bureau. This complements Kerbalism's own existing BDB patch by porting many of the newer science experiments, adding missing animations to science experiments, adding sensible HDD data/sample capacity upgrade paths to probe cores, and adding radioactivity to BDB RTGs.
+ KFLateRepulsors - moves Kerbal Foundries repulsors to a new 4000 science node in Community Tech Tree
+ ShowAllTechTreeNodes - Always displays all tech tree nodes, regardless of other mods' configs.
+ USIB9TankTypes - B9PartSwitch tank types for USI mods. Work in progress, currently only tanks relevant to Malemute are implemented.
+ USIMalemuteB9Patch - B9 tanks for Malemute rover. **Depends on USIB9TankTypes.**
+ USIMalemuteWheels - Updates behaviour of Malemute rover's wheels to use the new KSP 1.12 wheel mechanics.


## Contents (Extras)

+ BDBCryoTanks - replaces BDB boiloff with CryoTanks boiloff. This is included in BDB's extras on the main branch, but can be useful if you're playing with the Apollo revamp.
+ CNCJNSQStations - adds CommNetConstellation ground station definitions for JNSQ. Now part of JNSQ. Known issues: 1) Do not change default Ground Station enable/disable settings in base/KK settings pages as it bugs out CNC. 2) Stock Kerbin DSN names appear in flight for some stations, this is just a visual issue and has no gameplay consequences.
+ Historian - my config for Historian (needs Historian, merge with its folder)
+ JNSQUSIWarpDrive - adds scaling to USI WarpDrive for JNSQ
+ KPBSMKSCentrifuge - changes Kerbal Planetary Base Systems nuclear centrifuge to behave like the one in MKS


## TODO

1. fix JNSQUSIWarpDrive patch activation conditions
2. add MKS tank types for B9
3. convert remaining USI mods from FS to B9PS
4. add emitters for RTG
