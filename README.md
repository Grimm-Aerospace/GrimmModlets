# Grimm Modlets

Various KSP mini mods that I use in my own playthroughs.

**Installation**: Copy the files from Contents/GameData to your KSP's GameData. Then go into GameData\GrimmAerospace\GrimmModlets and delete the folders of the modlets you do not want, keeping in mind their dependencies below.

Use at your own risk, generally **no support provided**. Please feel free to submit pull requests or open issues though.

**Dependencies**: Module Manager is a hard dependency for all of these. Various additional dependencies are listed below. All explicitly listed dependencies are understood to be at minimum the latest version at the time of writing.

**Download**: [Github](https://github.com/Grimm-Aerospace/GrimmModlets/releases).

**Source**: [Github](https://github.com/Grimm-Aerospace/GrimmModlets).

**License**: MIT. See included [LICENSE](https://github.com/Grimm-Aerospace/GrimmModlets/blob/main/LICENSE) file for details. Some parts may be under a different license, if so then this is explicitly stated in the source.

## Contents

### AkitaUntooled 

+ **What?** - Removes dependency on USI Tools from the Akita rover (this will disable the ground tether functionality).

+ **Why?** - In case you want to use Akita rover without USI Tools and are OCD about warning messages. 

+ **Dependencies** - USI Akita rover


### BDBContractsFix

+ **What?** - Increases max simultaneous contracts in BDB, so that the Apollo mission and others reliably appear.

+ **Why?** - To take one small step for Kerbalkind.

+ **Dependencies** - Bluedog Design Bureau, Contract Configurator


### BDBKerbalismUpdate

+ **What?** - A series of patches to bridge the gap between Kerbalism and Bluedog Design Bureau. This complements Kerbalism's own existing BDB patch by porting many of the newer science experiments, adding missing animations to science experiments, adding (hopefuly) sensible HDD data/sample capacity upgrade paths to command modules, and adding radioactivity emission and unloaded simulation to RTGs.

+ **Why?** - Because the Kerbalism BDB patch is out of date as of writing.

+ **Dependencies** - Bluedog Design Bureau, Kerbalism, Kerbalism Default profile


### JNSQUSIWarpDrive

+ **What?** - Adds scaling to USI WarpDrive for JNSQ. Untested.

+ **Why?** - USI WarpDrive scales with Sigma Dimensions, but JNSQ does not use Sigma Dimensions.

+ **Dependencies** - JNSQ, USI WarpDrive


### KFLateRepulsors

+ **What?** - Moves Kerbal Foundries repulsors to a new 4000 science node in Community Tech Tree.

+ **Why?** - Early repulsors feel like too much cheating.

+ **Dependencies** - Community Tech Tree, Kerbal Foundries, ShowAllTechTreeNodes (see below)


### KPBSKerbalismUpdate

+ **What?** - Fixes NRE spam (see KPBS PR 128), converts greenhouse to Kerbalism experiment, adds Kerbalism lab experiments to labs, fixes some habitat values, etc. The PR version has more content but until the PR is processed you can use this version if desired.

+ **Why?** - Compatibility patch for out of date configs. 

+ **Dependencies** - Kerbal Planetary Base Systems, Kerbalism


### KPBSMKSCentrifuge

+ **What?** - Changes Kerbal Planetary Base Systems nuclear centrifuge to behave like the one in MKS

+ **Why?** - Compatibility patch. Not heavily tested.

+ **Dependencies** - Kerbal Planetary Base Systems, USI MKS


### ShowAllTechTreeNodes

+ **What?** - Always displays all tech tree nodes, regardless of other mods' configs.

+ **Why?** - Fixes inconsistent behavior across mods in tech tree.

+ **Dependencies** - None.

 
### B9TankTypes

+ **What?** - B9PartSwitch tank types primarily for USI mods. 

+ **Why?** - B9PS is more modern and user friendly than Firespitter.

+ **Dependencies** - B9 Part Switch


### USIKontainersB9Patch

+ **What?** - Replaces USI Kontainers tank selection backing with B9 Part Switch.

+ **Why?** - B9PS is more modern and user friendly than Firespitter.

+ **Dependencies** - USI Kontainers, B9 Part Switch, USIB9TankTypes (see above)

 
### USIMalemuteB9Patch

+ **What?** - Replaces Malemute rover tank selection backing with B9 Part Switch.

+ **Why?** - B9PS is more modern and user friendly than Firespitter.

+ **Dependencies** - USI Malemute rover, B9 Part Switch, USIB9TankTypes (see above)



### USIMalemuteWheels

+ **What?** - Updates behaviour of Malemute rover's wheels to use the new KSP 1.12 wheel mechanics.

+ **Why?** - Minor change to wheel behavior to keep Malemute wheels relevant in KSP 1.12

+ **Dependencies** - Malemute, KSP version >= 1.12.0


## Extras

You probably won't need these and they are not installed by default but are located in the Content/Extras folder.

### BDBCryoTanks

+ **What?** - Replaces BDB boiloff with CryoTanks boiloff. This is included in BDB's extras on the main branch, but can be useful if you're playing with the Apollo revamp.

+ **Why?** - Having two separate boiloff mechanics in the same save is weird. Note that CryoTanks boiloff is easy mode while BDB boiloff is "mission impossible."

+ **Dependencies** - Bluedog Design Bureau, CryoTanks

### CNCJNSQStations

+ **What?** - Adds CommNetConstellation ground station definitions for JNSQ. Now part of JNSQ. Known issues: 1) Do not change default Ground Station enable/disable settings in base/KK settings pages as it bugs out CNC. 2) Stock Kerbin DSN names appear in flight for some stations, this is just a visual issue and has no gameplay consequences.

+ **Why?** - Because stock CommNet is boring and RealAntennas has no support for NFX reflectors.

+ **Dependencies** - CommNetConstellation, JNSQ


### GrimmHistorian

+ **What?** - Historian profile that I use in all my screenshots.

+ **Why?** - Why not.

+ **Dependencies** - Historian.



