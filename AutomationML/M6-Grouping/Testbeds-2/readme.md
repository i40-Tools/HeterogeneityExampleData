This is an example for Grouping and Aggregation

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-Grouping-1.aml"
b) "seed-Grouping-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)


1: pair(SystemUnitClassLib("Conveyor"), (SystemUnitClassLib("Conveyor"))

2: pair (SystemUnitClass("BASIC_36-12-04-01 Conveyor"),(SystemUnitClass("BASIC_36-12-04-01 Conveyor"))

3: pair(Attribute(eClassVersion) , (Attribute(eClassVersion))

4: pair(Attribute(eClassClassificationClass) , (Attribute(eClassClassificationClass))

5: pair(Attribute(eClassIRDI) , (Attribute(eClassIRDI)


6: pair (InternalElement("Conveyor1",ID),(InternalElement("Conveyor1",ID))

7: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

8: pair(RoleRequirements ,RoleRequirements)

9: pair(InternalElement("Conveyor1"), (InternalElement("ConveyorGroup"(InternalElement("Conveyor1"))))


10: pair (InternalElement("Conveyor2",ID),(InternalElement("Conveyor2",ID))

11: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

12: pair(RoleRequirements ,RoleRequirements)

13: pair(InternalElement("Conveyor2"), (InternalElement("ConveyorGroup"(InternalElement("Conveyor2"))))

optional

14: pair(sum ("Conveyor1"(Attribute("maxConveyingSpeed") ("Conveyor2"(Attribute("maxConveyingSpeed")) , ("ConveyorGroup"(Attribute("maxConveyingSpeed")))



In conflict 9 we show that "seed-Grouping-1.aml":InternalElement("conveyor1") equals "seed-Grouping-0.aml":InternalElement("ConveyorGroup"(InternalElement("Conveyor1")). 

In conflict 13 we show that "seed-Grouping-1.aml":InternalElement("conveyor2") equals "seed-Grouping-0.aml":InternalElement("ConveyorGroup"(InternalElement("Conveyor2")). 


If such conflict exist then this a schematic heterogeneity.