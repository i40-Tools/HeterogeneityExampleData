This is an example for Value Transformation and Granularity

There are two heterogenity files in this example generated from "seed.aml".

a) "seed-String-1.aml"
b) "seed-String-0.aml"

It contains the following conflicts:

1: pair (OperatorDisplayName),(OperatorDisplayName)

2: pair (LimitValueType),(OperatorDisplayName)

3: pair (LimitValue),(OperatorDisplayName)

4: pair (LimitValueHysteresis),(OperatorDisplayName)

5: pair(Attribute("maxTransportationWeight") , (Attribute("maxTransportationWeight"))
   
 - pair(RefSemantic,RefSemantic)

6: pair(Attribute("paperType") , (Attribute("paperType"))
   
 - pair(RefSemantic,RefSemantic)
  


One file has OperatorDisplayName is defined with LimitValueType,LimitValue and LimitValueHysteresis where as other has the  concatinated.