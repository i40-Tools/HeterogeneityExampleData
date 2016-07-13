This is an example for Grouping and Aggregation

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-Grouping-1.aml"
b) "seed-Grouping-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)

1: pair (SystemUnitClass("BASIC_36-12-04-01 Conveyor"),(SystemUnitClass("BASIC_36-12-04-01 Conveyor"))

2: pair(Attribute(eClassVersion) , (Attribute(eClassVersion))

3: pair(Attribute(eClassClassificationClass) , (Attribute(eClassClassificationClass))

4: pair(Attribute(eClassIRDI) , (Attribute(eClassIRDI)



5: pair (InternalElement("LiftUpGate",ID),(InternalElement("LiftUpGate",ID))

  - pair(RoleRequirements ,RoleRequirements)

6: pair(InternalElement("LiftUpGate"), (InternalElement("ConveyorGroup"(InternalElement("LiftUpGate"))))

  - pair(RoleRequirements ,RoleRequirements)


7: pair (InternalElement("TransferToSubAssembly",ID),(InternalElement("TransferToSubAssembly",ID))

  - pair(RoleRequirements ,RoleRequirements)

8: pair(InternalElement("TransferToSubAssembly"), (InternalElement("ConveyorGroup"(InternalElement("TransferToSubAssembly"))))

  - pair(RoleRequirements ,RoleRequirements)


9: pair (InternalElement("SubAssembly",ID),(InternalElement("SubAssembly",ID))

  - pair(RoleRequirements ,RoleRequirements)


10: pair(InternalElement("SubAssembly"), (InternalElement("AssemblyStationGroup"(InternalElement("SubAssembly"))))

  - pair(RoleRequirements ,RoleRequirements)


11: pair (InternalElement("MainAssemblyStation",ID),(InternalElement("MainAssemblyStation",ID))

  - pair(RoleRequirements ,RoleRequirements)

12: pair(InternalElement("MainAssemblyStation"), (InternalElement("AssemblyStationGroup"(InternalElement("EndStop"))))

  - pair(RoleRequirements ,RoleRequirements)


13: pair (InternalElement("Robot",ID),(InternalElement("Robot",ID))

  - pair(RoleRequirements ,RoleRequirements)


14: pair(InternalElement("Robot"), (InternalElement("RobotGroup"(InternalElement("Robot"))))

  - pair(RoleRequirements ,RoleRequirements)


15: pair (InternalElement("PLC1",ID),(InternalElement("PLC1",ID))

  - pair(RoleRequirements ,RoleRequirements)


16: pair(InternalElement("PLC1"), (InternalElement("RobotGroup"(InternalElement("PLC1"))))

  - pair(RoleRequirements ,RoleRequirements)