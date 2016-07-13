This is an example for Grouping and Aggregation

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-Grouping-1.aml"
b) "seed-Grouping-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)

1: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

2: pair(Attribute("Max.load capacity") , (Attribute("Max.load capacity"))

 - pair (RefSemantic,RefSemantic)


3: pair (InternalElement("Conveyor1",ID),(InternalElement("Conveyor1",ID))

  - pair(RoleRequirements ,RoleRequirements)


4: pair (InternalElement("Conveyor2",ID),(InternalElement("Conveyor2",ID))

  - pair(RoleRequirements ,RoleRequirements)


The pairs are also matched in the Grouping section.


5: pair (InternalElement("Conveyor1",ID),((InternalElement("ConveyorGroup"(InternalElement("Conveyor1",ID))

  - pair(RoleRequirements ,RoleRequirements)


6: pair (InternalElement("Conveyor2",ID),((InternalElement("ConveyorGroup"(InternalElement("Conveyor2",ID))

  - pair(RoleRequirements ,RoleRequirements)

