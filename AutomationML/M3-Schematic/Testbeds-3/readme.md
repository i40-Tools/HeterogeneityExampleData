This is an example for Schematic 

There are two heterogenity files in this example generated from "seed-12.aml".

a) "seed-12-Schematic-1.aml"
b) "seed-12-Schematic-0.aml"



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

8: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

9: pair(RoleRequirements ,RoleRequirements)


10: pair (InternalElement("Conveyor2",ID),(InternalElement("Conveyor2",ID))

11: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

12: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

13: pair(InternalElement("Conveyor2",InternalLink ),InternalElement("Connection",InternalLink)

14: pair(RoleRequirements ,RoleRequirements)



In conflict 13 we show that "seed-3-Schematic-1.aml":Internal Elemen("conveyor 2", internalLink) equals "seed-3-Schematic-0.aml":Internal Element("Connection",Internal Link). 

If such conflict exist then this a schematic heterogeneity.