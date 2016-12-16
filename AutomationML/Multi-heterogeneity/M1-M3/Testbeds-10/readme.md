This is an example for M1-M3

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-M1-M3-1.aml"
b) "seed-M1-M3-0.aml"

It contains the following conflicts:

1: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

2: pair(Attribute("Max.load capacity") , (Attribute("Max.load capacity"))

 - pair (RefSemantic,RefSemantic)


3: pair(InternalElement("Conveyor1") ,(InternalElement("Conveyor1"))
 
 - pair (RoleRequirement,RoleRequirement).


4: pair(InternalElement("Conveyor2") ,(InternalElement("Conveyor2"))
 
 - pair (RoleRequirement,RoleRequirement).

5: pair(RoleClass) , pair(RoleClass))

6: pair(Attribute(eClassVersion) , (Attribute(eClassVersion))

7: pair(Attribute(eClassClassificationClass) , (Attribute(eClassClassificationClass))

8: pair(Attribute(eClassIRDI) , (Attribute(eClassIRDI))
  
9: pair (ManufactureDate),(ManufactureDate)
Different datatype date and datetime