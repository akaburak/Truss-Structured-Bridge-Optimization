# Truss-Structured-Bridge-Optimization
Truss Structured Bridge Optimization shapes a user defined bridge to its perfect configuration.
First, stress and displacement analysis is done on the bridge. According to the total displacement of the nodes and the weight of the bridge, a score is assigned to the structure.
Second, user chooses between the options on whether it will be an elementwise operation or a two node optimization operation.
After that, the optimization is done by checking the structure if it has a better score than before. In the node operation, if the lenght between the nodes should be longer to get a higher score, then the nodes are elongated. In the element operation, if the structure has a higher score when an element is removed, then that element is removed.
As an alternative option, there is an optimize all button. This button goes over all the nodes with respect to each other, and adjusts the lenght in between to get the highest score.
