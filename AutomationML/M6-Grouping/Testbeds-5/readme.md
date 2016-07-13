This is an example for Grouping and Aggregation

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-Grouping-1.aml"
b) "seed-Grouping-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)


1: pair (InternalElement("LiftUpGate",ID),(InternalElement("LiftUpGate",ID))

 - pair(RoleRequirements ,RoleRequirements)


2: pair(InternalElement("LiftUpGate"), (InternalElement("ConveyorGroup"(InternalElement("LiftUpGate"))))

 - pair(RoleRequirements ,RoleRequirements)



3: pair (InternalElement("TransferToSubAssembly",ID),(InternalElement("TransferToSubAssembly",ID))

 - pair(RoleRequirements ,RoleRequirements)


4: pair(InternalElement("TransferToSubAssembly"), (InternalElement("ConveyorGroup"(InternalElement("TransferToSubAssembly"))))

 - pair(RoleRequirements ,RoleRequirements)



5: pair (InternalElement("SubAssembly",ID),(InternalElement("SubAssembly",ID))

 - pair(RoleRequirements ,RoleRequirements)


6: pair(InternalElement("SubAssembly"), (InternalElement("AssemblyStationGroup"(InternalElement("SubAssembly"))))

 - pair(RoleRequirements ,RoleRequirements)


7: pair (InternalElement("MainAssemblyStation",ID),(InternalElement("MainAssemblyStation",ID))

 - pair(RoleRequirements ,RoleRequirements)


8: pair(InternalElement("MainAssemblyStation"), (InternalElement("AssemblyStationGroup"(InternalElement("EndStop"))))

 - pair(RoleRequirements ,RoleRequirements)
