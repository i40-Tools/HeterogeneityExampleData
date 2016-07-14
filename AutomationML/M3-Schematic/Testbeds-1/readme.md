This is an example for Schematic 

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-Schematic-1.aml"
b) "seed-Schematic-0.aml"

It contains the following conflicts:

Representation: Pair(File a, File b)


1: pair(Attribute(maxConveyingSpeed) , (Attribute(maxConveyingSpeed))

 - pair (RefSemantic,RefSemantic)

2: pair(Attribute("Max.load capacity") , (Attribute("Max.load capacity"))

<<<<<<< HEAD
 - pair (RefSemantic,RefSemantic)
  
=======
 - pair (RefSemantic,RefSemantic) 
>>>>>>> ee82618f6e4537e9ee6d8acdf7b26244d978fba8
