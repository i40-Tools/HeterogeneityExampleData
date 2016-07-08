This is an example for Schematic 

There are two heterogenity files in this example generated from "seed-18.aml".

a) "seed-18-Schematic-1.aml"
b) "seed-18-Schematic-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)

1: pair(InstanceHierarchy("ConveyorSystem"), pair(InstanceHierarchy("ConveyorSystem"))

2: pair (InternalElement("Conveyor1",ID),(InternalElement("Conveyor1",ID))

3: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

4: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

5: pair(RoleRequirements ,RoleRequirements)


6: pair (InternalElement("Conveyor2",ID),(InternalElement("Conveyor2",ID))

7: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

8: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

9: pair(InternalElement("Conveyor2",InternalLink ),InternalElement("Connection",InternalLink)

10: pair(RoleRequirements ,RoleRequirements)


12: pair (InternalElement("Conveyor3",ID),(InternalElement("Conveyor3",ID))

13: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

14: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

15: pair(RoleRequirements ,RoleRequirements)



16: pair (InternalElement("Conveyor4",ID),(InternalElement("Conveyor4",ID))

17: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

18: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

19: pair(InternalElement("Conveyor4",InternalLink ),InternalElement("Connection",InternalLink)

20: pair(RoleRequirements ,RoleRequirements)


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


In conflict 9 ,19 and 28 we show that "seed-18-Schematic-1.aml":Internal Elemen("Conveyor2","Conveyor4","Conveyor6", internalLink) equals "seed-18-Schematic-0.aml":Internal Element("Connection",Internal Link). 

If such conflict exist then this a schematic heterogeneity.