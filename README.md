==============================
Weighted rich-club coefficient
==============================


  -Computes a version of the rich-club coefficient, first described in (1), that takes into account the weights of graph edges. It uses tools from the NetworkX graph theory package.

  -Instead of calculating the coefficient for different levels of k, the algorithm takes as an argument a priori list of "rich-club" nodes.

  -We normalize the value of the coefficient by comparing it to the average weighted rich-club coefficent of 100 randomly generated graphs of comparable size.
