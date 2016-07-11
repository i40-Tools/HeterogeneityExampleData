This is an example for Schematic 

There are two heterogenity files in this example generated from "seed-4.aml".

a) "seed-4-Schematic-1.aml"
b) "seed-4-Schematic-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)

1: pair(InstanceHierarchy("ConveyorSystem"), pair(InstanceHierarchy("ConveyorSystem"))

2: pair (InternalElement("Conveyor1",ID),(InternalElement("Conveyor1",ID))

3: pair (InternalElement("Inport",ID),(InternalElement("Inport",ID))

4: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

5: pair(RoleRequirements ,RoleRequirements)


6: pair (InternalElement("Conveyor2",ID),(InternalElement("Conveyor2",ID))

7: pair (InternalElement("Inport2",ID),(InternalElement("Inport2",ID))

8: pair(ExternalInterface("ConnectionPoint") , (ExternalInterface("ConnectionPoint"))

9: pair(InternalElement("Inport2",InternalLink ),InternalElement("Connection",InternalLink)

10: pair(RoleRequirements ,RoleRequirements)



In conflict 9 we show that "seed-4-Schematic-1.aml":Internal Elemen("Inport2", internalLink) equals "seed-4-Schematic-0.aml":Internal Element("Connection",Internal Link). 

If such conflict exist then this a schematic heterogeneity.