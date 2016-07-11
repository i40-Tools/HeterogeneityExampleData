This is an example for Schematic 

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-Schematic-1.aml"
b) "seed-Schematic-0.aml"

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



In conflict 9  we show that "seed-Schematic-1.aml":InternalElement("Conveyor2", InternalLink) equals "seed-Schematic-0.aml":InternalElement("Connection",InternalLink). 

In conflict 19  we show that "seed-Schematic-1.aml":InternalElement("Conveyor2", InternalLink) equals "seed-Schematic-0.aml":InternalElement("Station",InternalLink). 


If such conflict exist then this a schematic heterogeneity.