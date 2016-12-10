# topology_inferense
All files are implemented in the Python programming language. The topology_inference.py file is the main file. Where received by parameter a file containing the values of the TTL's collected from the network that want to make the inference and the amount of nodes present in the network.
The bfs.py file is fired by topology_inference.py to calculate the distance from a node x to a node y. After calculating this value it is then compared to the file that was received by parameter. If all calculated distances are equal to all the distances contained in the TTL's file, the topology is then classified as a candidate.
The TTL-example-file file is an example of the TTL's collected and could be Passed by parameter to the topology_inference.py algorithm.

RUNNING THE PROGRAM
To run the program simply type the command at a command prompt. $ python topology_inference.py TTL-example-file 15
After the execution, the algorithm generates the image of the trees classified as candidates in png format. For this it is necessary to install graphviz and of dot.
