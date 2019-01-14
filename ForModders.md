# Info For Modders

Incorporate your mod into the Community Tech Tree via noninvasive ModuleManager patches!
Simply create a `.cfg` file to be packaged with your mod (call it anything you like, I suggest `ModNameCTTPatch.cfg`), and include entries as follows:

```
@PART[panel-static01]:NEEDS[CommunityTechTree]
{
  @TechRequired = advSolarTech
}
```

This assigns the part `panel-static01` to the Advanced Solar Tech (`advSolarTech`) node, and will only run in the presence of the Community Tech Tree.

The following is a list of all the new nodes in the Community Tech Tree, and the names by which they should be identified in the `TechRequired` field.
#### Nuclear Technology
```
nuclearPower                Nuclear Power
nuclearFuelSystems          Nuclear Fuel Systems
largeNuclearPower           Improved Nuclear Power
advNuclearPower             High Energy Nuclear Power
expNuclearPower             Experimental Nuclear Power
exoticNuclearPower          Exotic Nuclear Power
fusionPower                 Fusion Power
advFusionReactions          Advanced Fusion Reactions
quantumReactions            High Density Fusion Reactions
exoticReactions             Exotic Fusion Reactions
antimatterPower             Antimatter Power
unifiedFieldTheory          Unified Field Theory
ultraHighEnergyPhysics      Ultra High Energy Physics
```
#### Nuclear Propulsion
```
improvedNuclearPropulsion   Improved Nuclear Propulsion
advNuclearPropulsion        High Efficiency Nuclear Propulsion
expNuclearPropulsion        Experimental Nuclear Propulsion
exoticNuclearPropulsion     Exotic Nuclear Propulsion
fusionRockets               Fusion Rockets
```
#### Heavy Rocketry
```
experimentalRocketry        Experimental Rocketry
giganticRocketry            Gigantic Rocketry
colossalRocketry            Colossal Rocketry
```
#### Fuel Storage
```
specializedFuelStorage      Specialized Fuel Storage
exoticFuelStorage           Exotic Fuel Storage
extremeFuelStorage          Extreme Fuel Storage
```
#### Construction
```
exoticAlloys                Exotic Alloys
offworldManufacturing       Off-World Robotics
orbitalMegastructures       Orbital Megastructures
orbitalAssembly             Orbital Assembly
```
#### Robotics
```
advActuators                Advanced Actuators
experimentalActuators       Experimental Actuators
```
#### Atmospheric Technology
```
subsonicFlight              Subsonic Flight
efficientFlightSystems      Efficient Flight Systems
specializedFlightSystems    Specialized Flight Systems
expAircraftEngines          Experimental Aircraft Engines
aerospaceComposites         Aerospace Composites
advAerospaceEngineering     Advanced Aerospace Engineering
```
#### Command Modules
```
enhancedSurvivability       Enhanced Survivability
simpleCommandModules        Simple Command Modules
heavyCommandModules         Heavy Command Modules
specializedCommandModules   Specialized Command Modules
heavyCommandCenters         Heavy Command Centers
heavyLanders Heavy          Landers
specializedCommandCenters   Specialized Command Centers
specializedLanders          Specialized Landers
```
####  Mining
```
advOffworldMining           Advanced Off-World Mining
resourceExploitation        Resource Exploitation
```
#### Science
```
specializedScienceTech      Specialized Science Tech
longTermScienceTech         Long Term Science Tech
scientificOutposts          Scientific Outposts
highEnergyScience           High Energy Science
appliedHighEnergyPhysics    Applied High Energy Physics
mechatronics                Mechatronics
artificialIntelligence      Artificial Intelligence
```
#### Electric Propulsion
```
advIonPropulsion            Advanced Ion Propulsion
plasmaPropulsion            Plasma Propulsion
advEMSystems                Advanced Plasma Propulsion
specializedPlasmaGeneration Specialized Plasma Propulsion
exoticPlasmaPropulsion      Exotic Plasma Propulsion
advGriddedThrusters         Advanced Electrostatic Thrusters
expGriddedThrusters         Experimental Electrostatic Thrusters
```
#### Solar Panels
```
advSolarTech                Advanced Solar Technology
advPVMaterials              Advanced Photovoltaic Materials
cuttingEdgeSolarTech        Cutting-Edge Solar Technology
exoticSolarTech             Exotic Solar Technology
```
#### Electrical Systems
```
highTechElectricalSystems     High Tech Electrical Systems
highPowerElectricalSystems    High Power Electrical Systems
experimentalElectricalSystems Experimental Electrical Systems
exoticElectricalSystems       Exotic Electrical Systems
microwavePowerTransmission    Microwave Power Transmission
```
#### Thermal Systems
```
heatManagementSystems         Heat Management Systems
advHeatManagement             Advanced Heat Management
specializedRadiators          Specialized Radiators
exoticRadiators               Exotic Radiators
```
#### Habitation and Colonization
```
recycling                     Recycling
hydroponics                   Hydroponics
shortTermHabitation           Short Term Habitation
longTermHabitation            Long Term Habitation
colonization                  Colonization
advColonization               Advanced Colonization
```
#### Logistics
```
storageTech                   Storage Technology
logistics                     Logistics
advLogistics                  Advanced Logistics
```
