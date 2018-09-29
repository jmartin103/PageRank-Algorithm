# PageRank-Algorithm

A Python implementation of the PageRank algorithm, using PySpark and Spark Configuration. The program reads a text file, containing nodes which link to each other. It then initializes the ranks of each page (node) by dividing 1 by the number of nodes determined. The PageRank values are calculated with thirty iterations, and the results, accumulations, and contributions are calculated before each final value.
