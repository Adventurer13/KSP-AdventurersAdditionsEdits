# Adventurer's Additions and Edits
  
## About
While I was working on additional patches through [my fork](https://github.com/Adventurer13/VABOrganizer-Sheepdog_AdventurersAdditions) for [VABOrganizer-Sheepdog](https://github.com/Sheepdog2142/VABOrganizer-Sheepdog), I came across odd choices in various mods. This is a collection of [ModuleManger](https://github.com/sarbian/ModuleManager) patches to modify these as I come across them for others to use. This also contains any additions I use while playing [Kerbal Space Program](http://kerbalspaceprogram.com/) (KSP). Many of these modifications and additions are intended to be used with [VAB Organizer](https://github.com/post-kerbin-mining-corporation/VABOrganizer), but it isn't required. Some of these also work with [Filter Extensions](https://github.com/linuxgurugamer/FilterExtension) as well as stock KSP for example. Feel free to pick and choose, modify, or use all of these.

## Features  
  
### [Modular Computer Package Revived (aka ChromaWorks)](https://github.com/linuxgurugamer/ChromaWorks)
- Switches the category for a few parts to a different category based on its purpose.
- Hides a couple of deprecated parts (for SCANSat and Kerbal Engineer) from showing.
- Adds a VAB Organizer configuration and [**PCB**] bulkhead tag for the circuit boards.

### [Cryo Tanks](https://github.com/post-kerbin-mining-corporation/CryoTanks)
- Adds the `bulkheadProfile` for 10m to the 10m-sized hydrogen tank part.

### [DMagic Orbital Science](https://github.com/DMagic1/Orbital-Science)
- Switches the *Intelligence Sat* and *Soil Moisture* parts to be a `DIRECT` antenna rather than act as a `RELAY`.

### [Global Construction (aka Ground Construction)](https://github.com/allista/GroundConstruction)
- Modifies `bulkheadProfiles` of the *Orbital Assembly Line*, *Orbital Workshop*, and *Inline Workshop* to a more appropiate size.

### [Heat Control](https://github.com/post-kerbin-mining-corporation/HeatControl) and [System Heat](https://github.com/post-kerbin-mining-corporation/SystemHeat)
- Fixes VAB Organizer subcategory assignment for *System Heat* parts.
- When using [VAB Organizer - Jade](https://github.com/JadeOfMaar/VABOrganizer-Jade), assigns parts to renamed **Heat Exchangers** subcategory from Heat Sinks.

### [JX2Antenna](https://github.com/KSPSnark/JX2Antenna)
- Modifies `bulkheadProfiles` of the *JU1 Medium Deployable Antenna* to a more appropiate size.

### [Kerbal Actuators](https://github.com/Angel-125/KerbalActuators)
- Adds `bulkheadProfiles` to its parts based upon its size when folded.

### [Kerbal Attachment System (aka KAS)](https://github.com/ihsoft/KAS)
- Modifies `bulkheadProfiles` of a few parts to a more appropriate size.
- Adds a VAB Organizer configuration—including a **Tools** subcategory for both its and stock KSP parts and switching the category for a few of its parts.

### [Kerbal Engineer Redux](https://github.com/jrbudda/KerbalEngineer)
- Switches the category for its parts to "**Command and Control**" from "Science".

### [Kerbal Inventory System](https://github.com/ihsoft/KIS)
- Switches the `mediumCargoContainer` to use [Restock](https://github.com/PorktoberRevolution/ReStocked)'s model and its variants.
- Adds a VAB Organizer configuration—including a **Tools** subcategory for its and stock KSP parts and switching the category for its parts to better fit with KSP's organization.

### [Kerbal Planetary Base Systems (KPBS)](https://github.com/Nils277/KerbalPlanetaryBaseSystems)
- Adds surface attach capability to the landing gear.
- Switches the category for a few parts to a different category.
- Modifies `bulkheadProfiles` of a few parts to better sizes.
- Makes the two deprecated legacy storage parts more obvious that they are deprecated.
- Modifies the cost of various mod-dependent parts when used with Umbra Space Industries (USI) to be more comparable in prices to those in USI.
- Adds Global Construction compatibility (at a lesser efficiency) to the Workshop added when USI-MKS is used as well.
- Adds VAB Organizer [**KPBS-G**] bulkhead tag for the Garage parts.

### [Kerbal Space Program](http://kerbalspaceprogram.com/)
- Modifies `bulkheadProfiles` of a few parts to a more appropriate size.
- Switches the category for the Mk1-sized *Structural Fuselage* to "**Aerodynamics**" from "Structural".
- Switches the category for the *Turboshaft Engines* to "**Engines**" from "Robotics".
- Switches the category for the *Holding Tanks* to "**Payload**" from "Fuel Tanks".
- When using VAB Organizer, assigns more parts and better assigns others to subcategories.

### [Konstruction (includes Akita and Konstruction)](https://github.com/UmbraSpaceIndustries/Konstruction)
- Modifies `bulkheadProfiles` of a few parts in *Akita* and *Konstruction* to a better size.

### [Near Future Launch Vehicles](https://github.com/post-kerbin-mining-corporation/NearFutureLaunchVehicles)
- Switches the category for the engine mounts containing fuel to use the "**Fuel Tanks**" category instead of "Structural".
- When using VAB Organizer, assigns the added RCS parts to use the **RCS** subcategory instead of Miscellaneous.

### ['Project Orion' Nuclear Pulse Engine (aka Nuclear Rockets)](https://github.com/UmbraSpaceIndustries/NuclearRockets)
- Modifies `bulkheadProfiles` of its parts to a more appropriate size.

### [ReStock+](https://github.com/PorktoberRevolution/ReStocked)
- Switches the category for the *Holding Tanks* to "**Payload**" from "Fuel Tanks".

### [SCANsat](https://github.com/S-C-A-N/SCANsat)
- Raises the max altitude the *Been There Done That* can be used to 5000 from 2000.

### [Sterling Electrics](https://github.com/JadeOfMaar/SterlingSystems)
- Modifies battery capacities to comparable amounts in Restock+/stock KSP.

### [Sterling Thermals](https://github.com/JadeOfMaar/SterlingSystems)
- Modifies `bulkheadProfiles` of a few parts to a more appropriate size.
- Minor edit to names of sub-100m sized *Film Radiators* for better alphanumeric sorting.

### [Stockalike Station Parts Expansion Redux](https://github.com/ChrisAdderley/StationPartsExpansionRedux)
- Modifies `bulkheadProfiles` of a few parts to better sizes.
- Switches the category for the *Extensible Stairway* to "**Utility**" to be with the telescopic vertical stairs instead of "Ground".
- Better compatibility with [Extended information about scientific experiments in VAB (aka SituationModuleInfo)](https://github.com/linuxgurugamer/SituationModuleInfo)—hopefully will be addressed by the maintainer of SituationModuleInfo in time, so this won't be needed.

### [Universal Storage 2](https://github.com/linuxgurugamer/universal-storage-2)
- Modifies `bulkheadProfiles` of a few parts to a more appropriate size.

### [Umbra Space Industries (USI) Core (includes Kontainers and ReactorPack)](https://github.com/UmbraSpaceIndustries/USI_Core)
- Adds and modifies `bulkheadProfiles` of some of its parts to a better size.

### [USI Exploration Pack (includes ExpPack, SrvPack, and SubPack)](https://github.com/UmbraSpaceIndustries/ExplorationPack)
- Fixes the *Safety Light* model directory, so it appears in the VAB/SPH.
- Modifies `bulkheadProfiles` of some parts in *ExpPack/PackRat* and *SubPack* to better sizes.
- Adds surface attach capability to more parts in *ExpPack/PackRat*.
- Switches the category for the *Storage Box* in *SrvPack* to "**Cargo**" from "Utility".
- Switches the category for *ExpPack/PackRat* parts to various appropriate categories than only "Utility". Optional patch to remove it from default categories altogether and solely use [Community Category Kit](https://github.com/UmbraSpaceIndustries/CommunityCategoryKit)'s "**Rovers**" category instead similar to other USI-mods added rover (Akita and Karibou) parts.
- Adds a VAB Organizer **Bouyancy** subcategory and renames **Parachutes** to **Airbags & Parachutes**. A few parts within *SrvPack* and *SubPack* are assigned where appropriate to these subcategories.

### [USI Freight Transport Technologies (FTT)](https://github.com/UmbraSpaceIndustries/FTT)
- Modifies `bulkheadProfiles` of a few parts to a more appropriate size.
- Switches the category for the *'Honeybadger' Cargo Bay* and *'Honeybadger' Cargo Pods* to "**Payload**" from "Utility".

### [USI Kolonization Systems (includes Karibou, MKS, and WOLF)](https://github.com/UmbraSpaceIndustries/MKS)
- Modifies `bulkheadProfiles` of some *Karibou*, *MKS*, and *WOLF* parts to a better size.
- Adds the *'Ranger' Battery Pack* and *'Ranger' Thermal Control System* to USI's "**Kolonization**" category.

### [USI Life Support](https://github.com/UmbraSpaceIndustries/USI-LS)
- Modifies `bulkheadProfiles` of a few parts to a more appropriate size.

### [VAB Organizer](https://github.com/post-kerbin-mining-corporation/VABOrganizer)
- Renames **Nosecones** to **Nose & Tail Cones**, which the KSP (Squad) patch uses to assign the *Tail Connectors*.
- Adds VAB Organizer bulkhead tags for 
  - [**11m**] (`size11m`) — used by USI Core patch
  - [**15m**] (`size15m`) — used by USI Core and USI Kolonization Systems patches
  - [**20m**] (`size20m`) — used by USI Kolonization Systems patch
  - [**30m**] (`size30m`) — not used here, but added anyway

### [zTheme](https://github.com/zapSNH/ZTheme)
- Replaces NavBall_BG_Baked with a solid fill for the red- and green-colored parts as seen below:  
![NavBall_BG_Baked_Solid](</Source/ZTheme/PluginData/flight/Replacement Textures/NavBall_BG_Baked.png>)

---
## For Creators of KSP Mods
If there is anything in this collection you do not want or have integrated into your own mod—that I specifically patch or add—feel free to let me know *respectfully*. I have no problem removing such when reasonable.
