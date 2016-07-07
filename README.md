# HeterogeneityExampleData
Example of Heterogeneity data for different standards (AutomationML, OPC UA, ect)

AutomationML Heterogeneity are generated through GoldStandard tool. The examples contains AML gold Standard for validation purpose.
AutomationML generated heterogeneity examples are classified in the following catagories:

#### M1.1: String processing
* This type of mapping requires using special functions on string values, e.g., “concat”, “substring”, “regex”.

#### M1.2: Data type transformation
* Semantically the same entities can be modeled using different data types. 

#### M1.3: Math functions
* A mappings processing can be specified by some mathematical or physical formula. 

#### M1.4: External function calls
* This mapping type comprises functions that are not supported by the used technology, but must be additionally implemented. Therefore, it must be possible to call an external function (implemented, e.g., in Java) that will generate a value for a specific object in a target model.

#### M2: Granularity
* This mapping type is required if the same real-life objects were modeled on different levels of detail. 

#### M3: Schematic differences
* This type of mappings implies that there are substantial differences in the way how the same semantics is represented in the source and target models. 

#### M4: Conditional mappings
* This mapping type is needed if a relation between the entities in source and target models exists if and only if a certain condition (or a set of conditions) holds on the source side. 

#### M5: Bidirectional mappings
* An important characteristic of mappings is that they are directional [6], i.e., usually they are specified in a direction from source to target and the data flow cannot occur in the opposite direction. 

#### M6: Grouping and aggregation
* In some cases it is important to group or/and aggregate objects on the source side in order to set the relation to the target model.

#### M7: Restrictions on values
* In some cases it can be important to define that a certain property value is mandatory, i.e., this property must always have a value.
