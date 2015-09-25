#Awesome Programming Problems

##Chinese Postman Problem

The Chinese postman problem is a mathematical problem of graph theory. It is also known as route inspection problem. Suppose there is a mailman who needs to deliver mail to a certain neighbourhood. The mailman is unwilling to walk far, so he wants to find the shortest route through the neighbourhood, that meets the following criteria:

* It is a closed circuit (it ends at the same point it starts).
* He needs to go through every street at least once.

###Solution

* Step 1: Find all the nodes of odd order.

* Step 2: For each pair of odd nodes find the connecting path of minimum weight.

* Step 3: Pair up all the odd nodes so that the sum of the weights of the connecting paths from Step 2 is minimised.

* Step 4: In the original graph, duplicate the minimum weight paths found in Step 3.

* Step 5:  Find a trail containing every arc for the new (Eulerian) Graph.

###Code

The link to the code is [here](https://github.com/hackerkid/LightOJ-Solutions/blob/master/1086-Jogging-Trails.cpp)