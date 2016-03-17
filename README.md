==============================
Weighted rich-club coefficient
==============================


*Computes a version of the rich-club coefficient, described in (1), that takes into account the weights of graph edges. It uses tools from the NetworkX graph theory package.
*Instead of calculating the coefficient for different levels of k, the algorithm takes as an argument a priori list of "rich-club" nodes.
*We normalize the value of the coefficient by comparing it to the average weighted rich-club coefficent of 100 randomly generated graphs of comparable size.

Citations
=========
(1) Julian J. McAuley, Luciano da Fontoura Costa, and Tibério S. Caetano, “The rich-club phenomenon across complex network hierarchies”, Applied Physics Letters Vol 91 Issue 8, August 2007. http://arxiv.org/abs/physics/0701290
