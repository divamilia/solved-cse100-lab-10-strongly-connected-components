Download Link: https://assignmentchef.com/product/solved-cse100-lab-10-strongly-connected-components
<br>
<h1>Strongly Connected Components</h1>

<strong>Description </strong>A strongly connected component (SCC) of a directed graph <em>G </em>= (<em>V,E</em>) is defined as a maximal set of vertices <em>C </em>⊆ <em>V </em>such that for every pair of vertices <em>u </em>and <em>v </em>in <em>C</em>, the two vertices are reachable from each other. In this lab assignment, you are asked to decompose a given directed graph <em>G </em>= (<em>V,E</em>) into a collection of SCCs.

<strong>Input </strong>The input will have the following format. The first integer refers to the number of vertices, |<em>V </em>|. The second integer is the number of edges, |<em>E</em>|. Vertices are indexed by 0, 1, …, |<em>V </em>| − 1. Then, two numbers <em>u v </em>appearing in each line means an edge (<em>u,v</em>). See the example given below.

<strong>Output </strong>Output the SCC ID of every vertex. A SCC’s ID is defined as the smallest index of any vertex in the SCC. In other words, you have to output, for each vertex <em>v</em>, the ID of the unique SCC the vertex <em>v </em>belongs to. You must output the ID for each vertex, considering vertices in the order of 0, 1, …, |<em>V </em>| − 1.

<strong>Examples of input and output</strong>

<em>Input</em>

8

13

<ul>

 <li>1</li>

 <li>2</li>

</ul>

1 4

<ul>

 <li>5</li>

 <li>3</li>

 <li>6</li>

 <li>2</li>

 <li>7</li>

 <li>0</li>

 <li>5</li>

 <li>6</li>

 <li>5</li>

</ul>

6 7

<em>Output for problem 2</em>

0

0

2

2

0

5

5

7

What this answer implies is that the graph is decomposed into four SCCs, {0<em>,</em>1<em>,</em>4}<em>,</em>{2<em>,</em>3}<em>,</em>{5<em>,</em>6}<em>,</em>{7}. Note that all vertices in the same SCC have the same label, which is equal to the smallest index of all vertices in the same component. For example, vertices 0,1 and 4 are all labeled with 0.

See the lab guidelines for submission/grading, etc., which can be found in Files/Labs.