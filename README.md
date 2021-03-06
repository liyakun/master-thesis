# master-thesis

##### Description
My master thesis topic is Frequent Subtree Mining From Locally Easy Graphs.

This repository contains the source code of my implementation.

It is part of another framework so you cannot compile it only with these codes.

The compiled program [subgraph](https://github.com/liyakun/master-thesis/blob/master/subgraph) is provided.

##### Help
`subgraph -h`

##### Example

###### Subtree Isomorphism Check
`./subgraph -u isomorphic ./data/isomorphic_example.txt`

###### Frequent Subtree Mining

`./subgraph -u mining -m levelwise -i iterative -s 1 -v 5 -c prefix ./data/mining_example.txt`


---
References:

- id: mining
  - title: On the Complexity of Frequent Subtree Mining in Very Simple Structures
  - author: Pascal Welke, Tamas Horvath, Stefan Wrobel
  - book-title: Inductive Logic Programming: 24th International Conference, ILP 2014, Nancy, France, September 14-16, 2014, Revised Selected Papers
  - URL: 'http://dx.doi.org/10.1007/978-3-319-23708-4_14'
  - DOI: 10.1007/978-3-319-23708-4_14
  - publisher: Springer International Publishing
  - page: 194--209
  - issued:
    year: 2015

- id: isomorphism
  - title: Subtree Isomorphism in Graphs with Locally Polynomial Spanning Trees
  - author: Pascal Welke, Tamas Horvath, Stefan Wrobel
  - type: unpublished

- id: fast isomorphism
  - title: Fast Subtree Isomorphism in Graph Databases with Locally Polynomial Spanning Trees
  - author: Pascal Welke
  - type: unpublished
  
---
