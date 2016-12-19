This is an example for Value Transformation and Granularity

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-String-1.aml"
b) "seed-String-0.aml"

It contains the following conflicts:

1: pair (CardType),(CardType)

2: pair (CardType),(CardTerminalPlus)

3: pair (CardType),(CardTerminalMinus)

4: pair (SystemUnitClass("BASIC_36-12-04-01 Conveyor"),(SystemUnitClass("BASIC_36-12-04-01 Conveyor"))

5: pair(Attribute(eClassVersion) , (Attribute(eClassVersion))

6: pair(Attribute(eClassClassificationClass) , (Attribute(eClassClassificationClass))

7: pair(Attribute(eClassIRDI) , (Attribute(eClassIRDI))

8: pair(Attribute("Combustibility class") , (Attribute("Combustibility class"))

 - pair(Attribute(RefSemantic), (Attribute(RefSemantic))
 
9: pair(Attribute("Rated voltage") , (Attribute("Rated voltage"))

 - pair(Attribute(RefSemantic), (Attribute(RefSemantic))

One file has CardType defined with CardType ,CardTerminalPlus and CardTerminalMinus where other has the value concatinated.