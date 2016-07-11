This is an example for Schematic 

There are two heterogenity files in this example generated from "seed-19.aml".

a) "seed-19-Schematic-1.aml"
b) "seed-19-Schematic-0.aml"

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


15: pair (InternalElement("Conveyor3",ID),(InternalElement("Conveyor3",ID))

16: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

17: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

18: pair(RoleRequirements ,RoleRequirements)


19: pair (InternalElement("Conveyor4",ID),(InternalElement("Conveyor4",ID))

20: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

21: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

22: pair(InternalElement("Conveyor4",InternalLink ),InternalElement("Connection",InternalLink)

23: pair(RoleRequirements ,RoleRequirements)


21: pair (InternalElement("Conveyor5",ID),(InternalElement("Conveyor5",ID))

22: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

23: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

24: pair(RoleRequirements ,RoleRequirements)


25: pair (InternalElement("Conveyor6",ID),(InternalElement("Conveyor6",ID))

26: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

27: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

28: pair(InternalElement("Conveyor6",InternalLink ),InternalElement("Connection",InternalLink)

29: pair(RoleRequirements ,RoleRequirements)


In conflict 9 ,19 and 28 we show that "seed-19-Schematic-1.aml":Internal Elemen("Conveyor2","Conveyor4","Conveyor6", internalLink) equals "seed-19-Schematic-0.aml":Internal Element("Connection",Internal Link). 

If such conflict exist then this a schematic heterogeneity.