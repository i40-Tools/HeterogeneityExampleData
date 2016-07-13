This is an example for Schematic 

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-Schematic-1.aml"
b) "seed-Schematic-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)


1: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

2: pair(Attribute("Max.load capacity") , (Attribute("Max.load capacity"))

 - pair (RefSemantic,RefSemantic)


3: pair(InternalElement("Conveyor1") ,(InternalElement("Conveyor1"))
 
 - pair (RoleRequirement,RoleRequirement).


4: pair(InternalElement("Conveyor2") ,(InternalElement("Conveyor2"))
 
 - pair (RoleRequirement,RoleRequirement).

5: pair(InternalLink("PortLink"),(InternalLink("PortLink"))
  