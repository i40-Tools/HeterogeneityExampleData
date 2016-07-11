This is an example for Grouping and Aggregation

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-Grouping-1.aml"
b) "seed-Grouping-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)

1: pair(InstanceHierarchy("AssemblySystem"), pair(InstanceHierarchy("AssemblySystem"))

2: pair (InternalElement("LiftUpGate",ID),(InternalElement("LiftUpGate",ID))

3: pair(InternalElement("LiftUpGate"), (InternalElement("ConveyorGroup"(InternalElement("LiftUpGate"))))


4: pair (InternalElement("TransferToSubAssembly",ID),(InternalElement("TransferToSubAssembly",ID))

5: pair(InternalElement("TransferToSubAssembly"), (InternalElement("ConveyorGroup"(InternalElement("TransferToSubAssembly"))))


6: pair (InternalElement("TransferToMainAssembly",ID),(InternalElement("TransferToMainAssembly",ID))

7: pair(InternalElement("TransferToMainAssembly"), (InternalElement("ConveyorGroup"(InternalElement("TransferToMainAssembly"))))


8: pair (InternalElement("EndStop",ID),(InternalElement("EndStop",ID))

9: pair(InternalElement("EndStop"), (InternalElement("ConveyorGroup"(InternalElement("EndStop"))))




In conflict 3 we show that "seed-Grouping-1.aml":InternalElement("LiftUpGate") equals "seed-Grouping-0.aml":InternalElement("ConveyorGroup"(InternalElement("LiftUpGate")). 

In conflict 5 we show that "seed-Grouping-1.aml":InternalElement("TransferToSubAssembly") equals "seed-Grouping-0.aml":InternalElement("ConveyorGroup"(InternalElement("TransferToSubAssembly")). 

In conflict 7 we show that "seed-Grouping-1.aml":InternalElement("TransferToMainAssembly") equals "seed-Grouping-0.aml":InternalElement("ConveyorGroup"(InternalElement("TransferToMainAssembly")). 

In conflict 9 we show that "seed-Grouping-1.aml":InternalElement("EndStop") equals "seed-Grouping-0.aml":InternalElement("ConveyorGroup"(InternalElement("EndStop")). 


If such conflict exist then this a schematic heterogeneity.