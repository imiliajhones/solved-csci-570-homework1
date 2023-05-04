Download Link: https://assignmentchef.com/product/solved-csci-570-homework1
<br>
<ol>

 <li>Arrange the following functions in increasing order of growth rate with <em>g</em>​​(<em>n</em>​​) following <em>f</em>​​(<em>n</em>​​) in your list if and only if</li>

</ol>

<em>f</em>​(<em>n</em>​​) <em>=</em>​ ​O(<em>g</em>​​(<em>n</em>​​))

2<em>logn</em> ,   <em>logn</em> , <em>n</em>(<em>logn</em>)3, <a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>√2<em>logn</em>, 22<em>n</em> , <em>nlogn </em>, 2<em>n</em>2




<a href="#_ftnref1" name="_ftn1">[1]</a> <sup>√2<em>logn </em></sup>reduces to √2<em>logn</em>  after taking log on both sides of the equation hence it is the function that has smaller growth than the rest.

<ol start="2">

 <li>Given a linear time algorithm based on BFS to detect whether a given undirected graph contains a cycle. If the graph​ contains a cycle, then your algorithm should output one. It should not output all cycles in the graph, just one of them. You are NOT allowed to modify BFS, but rather use it as a black box. Explain why your algorithm has a linear time runtime complexity.</li>

 <li>Let ​ <em>G </em>​ ​= (<em>V</em>​ ​, <em>E</em>​ ​) be a connected undirected graph and let <em>v </em>​ ​be a vertex in <em>G</em>​ ​. Let <em>T </em>​ ​be the depth-first search tree of <em>G</em>​ starting from <em>v</em>​​, and let <em>U </em>​ ​be the breadth-first search tree of G starting from <em>v</em>​​. Prove that the height of <em>T </em>​ ​is at least as great as the height of <em>U</em>​ ​.</li>

 <li>A binary tree is a rooted tree in which each node has at most two children. Show by <em>induction </em>​ ​that in any nonempty binary tree the number of nodes with two children is exactly one less than the number of leaves.</li>

 <li>Prove that a complete graph <em>K</em><sub>5</sub> is not a planar graph. You can use facts regarding planar graphs proven in the textbook.</li>

 <li>Suppose we perform a sequence of <em>n </em>​ ​operations on a data structure in which the <em>ith </em>​ ​operation costs <em>i </em>​ ​if <em>i </em>​ ​is an exact power of 2, and 1 otherwise. Use aggregate analysis to determine the amortized cost per operation.</li>

 <li>We have argued in the lecture that if the table size is doubled when it’s full, then the amortized cost per insert is acceptable. Fred Hacker claims that this consumes too much space. He wants to try to increase the size with every insert by just two over the previous size. What is the amortized cost per insertion in Fred’s table?</li>

 <li>You are given a weighted graph G, two designated vertices <em>s </em>​ ​and <em>t</em>​​. Your goal is to find a path from <em>s </em>​ ​to <em>t </em>​ ​in which the minimum edge weight is maximized i.e. if there are two paths with weights 10→1→5 and 2→7→3 then the second path is considered better since the minimum weight (2) is greater than the minimum weight of the first (1). Describe an efficient algorithm to solve this problem and show its complexity.</li>

 <li>When we have two sorted lists of numbers in non-descending order, and we need to merge them into one sorted list,​ we can simply compare the first two elements of the lists, extract the smaller one and attach it to the end of the new list, and repeat until one of the two original lists become empty, then we attach the remaining numbers to the end of the new list and it’s done. This takes linear time. Now, try to give an algorithm using O(<em>n </em>​ ​log <em>k</em>​​) time to merge <em>k </em>​ ​sorted lists (you can also assume that they contain numbers in non-descending order) into one sorted list, where <em>n </em>​ ​is the total number of elements in all the input lists. Use a binary heap for <em>k</em>​​- way merging.</li>

</ol>





