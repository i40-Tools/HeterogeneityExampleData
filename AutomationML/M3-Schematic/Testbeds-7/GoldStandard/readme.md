This is an example for Schematic 

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-Schematic-1.aml"
b) "seed-Schematic-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)

1: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

2: pair(Attribute("Max.load capacity") , (Attribute("Max.load capacity"))

 - pair (RefSemantic,RefSemantic)


3: pair(Attribute("Min. speed of the drive") , (Attribute("Min. speed of the drive"))

  - pair (RefSemantic,RefSemantic)

4: pair(Attribute("maxTransportationWeight") , (Attribute("maxTransportationWeight"))

  - pair (RefSemantic,RefSemantic)


5: pair (InternalElement("Conveyor1",ID),(InternalElement("Conveyor1",ID))

  - pair(RoleRequirements ,RoleRequirements)


6: pair (InternalElement("Conveyor2",ID),(InternalElement("Conveyor2",ID))

   - pair(RoleRequirements ,RoleRequirements)


7: pair (InternalElement("Conveyor3",ID),(InternalElement("Conveyor3",ID))

   - pair(RoleRequirements ,RoleRequirements)


8: pair (InternalElement("Conveyor4",ID),(InternalElement("Conveyor4",ID))

   - pair(RoleRequirements ,RoleRequirements)