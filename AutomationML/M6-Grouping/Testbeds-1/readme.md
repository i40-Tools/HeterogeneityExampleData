This is an example for Grouping and Aggregation

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-Grouping-1.aml"
b) "seed-Grouping-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)

1: pair(InstanceHierarchy("ConveyorSystem"), pair(InstanceHierarchy("ConveyorSystem"))

2: pair (InternalElement("Conveyor1",ID),(InternalElement("Conveyor1",ID))

3: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

4: pair(RoleRequirements ,RoleRequirements)

5: pair(InternalElement("Conveyor1"), (InternalElement("ConveyorGroup"(InternalElement("Conveyor1"))))


6: pair (InternalElement("Conveyor2",ID),(InternalElement("Conveyor2",ID))

7: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

8: pair(RoleRequirements ,RoleRequirements)

9: pair(InternalElement("Conveyor2"), (InternalElement("ConveyorGroup"(InternalElement("Conveyor2"))))

optional

10: pair(sum ("Conveyor1"(Attribute("maxConveyingSpeed") ("Conveyor2"(Attribute("maxConveyingSpeed")) , ("ConveyorGroup"(Attribute("maxConveyingSpeed")))



In conflict 5 we show that "seed-Grouping-1.aml":InternalElement("conveyor1") equals "seed-5-Grouping-0.aml":InternalElement("ConveyorGroup"(InternalElement("Conveyor1")). 

In conflict 9 we show that "seed-Grouping-1.aml":InternalElement("conveyor2") equals "seed-5-Grouping-0.aml":InternalElement("ConveyorGroup"(InternalElement("Conveyor2")). 

for aggregation

If such conflict exist then this a schematic heterogeneity.