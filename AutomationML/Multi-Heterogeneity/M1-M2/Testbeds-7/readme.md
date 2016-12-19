This is an example for Value Transformation and Granularity

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-String-1.aml"
b) "seed-String-0.aml"

It contains the following conflicts:

1: pair (MeasurementRangeStart),(MeasurementRange)

2: pair (MeasurementRangeEnd),(MeasurementRange)

3: pair (InterfaceClass("BASIC_27-03-14-02 Single-phase distribution transformer (oil-cooled)"),(InterfaceClass("BASIC_27-03-14-02 Single-phase distribution transformer (oil-cooled)")

4: pair(Attribute(eClassVersion) , (Attribute(eClassVersion))

5: pair(Attribute(eClassClassificationClass) , (Attribute(eClassClassificationClass))

6: pair(Attribute(eClassIRDI) , (Attribute(eClassIRDI))

7: pair(Attribute("GTIN") , (Attribute("GTIN"))
  
 - pair(RefSemantic,RefSemantic)
 
8: pair(Attribute("Manufacturer name") , (Attribute("Manufacturer name"))

 - pair(RefSemantic,RefSemantic)


One file has Range defined with start and end where as other has the range concatinated.