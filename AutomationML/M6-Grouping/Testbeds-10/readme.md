This is an example for Grouping and Aggregation

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-Grouping-1.aml"
b) "seed-Grouping-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)

1: pair(SystemUnitClassLib("AssembleSystem"), (SystemUnitClassLib("AssembleSystem"))

2: pair (SystemUnitClass("BASIC_36-12-04-01 Conveyor"),(SystemUnitClass("BASIC_36-12-04-01 Conveyor"))

3: pair(Attribute(eClassVersion) , (Attribute(eClassVersion))

4: pair(Attribute(eClassClassificationClass) , (Attribute(eClassClassificationClass))

5: pair(Attribute(eClassIRDI) , (Attribute(eClassIRDI)



6: pair (InternalElement("LiftUpGate",ID),(InternalElement("LiftUpGate",ID))

7: pair(InternalElement("LiftUpGate"), (InternalElement("ConveyorGroup"(InternalElement("LiftUpGate"))))


8: pair (InternalElement("TransferToSubAssembly",ID),(InternalElement("TransferToSubAssembly",ID))

9: pair(InternalElement("TransferToSubAssembly"), (InternalElement("ConveyorGroup"(InternalElement("TransferToSubAssembly"))))


10: pair (InternalElement("SubAssembly",ID),(InternalElement("SubAssembly",ID))

11: pair(InternalElement("SubAssembly"), (InternalElement("AssemblyStationGroup"(InternalElement("SubAssembly"))))


12: pair (InternalElement("MainAssemblyStation",ID),(InternalElement("MainAssemblyStation",ID))

13: pair(InternalElement("MainAssemblyStation"), (InternalElement("AssemblyStationGroup"(InternalElement("EndStop"))))


14: pair (InternalElement("Robot",ID),(InternalElement("Robot",ID))

15: pair(InternalElement("Robot"), (InternalElement("RobotGroup"(InternalElement("Robot"))))


16: pair (InternalElement("PLC1",ID),(InternalElement("PLC1",ID))

17: pair(InternalElement("PLC1"), (InternalElement("RobotGroup"(InternalElement("PLC1"))))






In conflict 7 we show that "seed-Grouping-1.aml":InternalElement("LiftUpGate") equals "seed-Grouping-0.aml":InternalElement("ConveyorGroup"(InternalElement("LiftUpGate")). 

In conflict 9 we show that "seed-Grouping-1.aml":InternalElement("TransferToSubAssembly") equals "seed-Grouping-0.aml":InternalElement("ConveyorGroup"(InternalElement("TransferToSubAssembly")). 

In conflict 11 we show that "seed-Grouping-1.aml":InternalElement("SubAssembly") equals "seed-Grouping-0.aml":InternalElement("AssemblyStationGroup"(InternalElement("SubAssembly")). 

In conflict 13 we show that "seed-Grouping-1.aml":InternalElement("MainAssemblyStation") equals "seed-Grouping-0.aml":InternalElement("AssemblyStationGroup"(InternalElement("MainAssemblyStation")). 

In conflict 15 we show that "seed-Grouping-1.aml":InternalElement("Robot") equals "seed-Grouping-0.aml":InternalElement("RobotGroup"(InternalElement("Robot")). 

In conflict 17 we show that "seed-Grouping-1.aml":InternalElement("PLC1") equals "seed-Grouping-0.aml":InternalElement("RobotGroup"(InternalElement("PLC1")). 




If such conflict exist then this a schematic heterogeneity.