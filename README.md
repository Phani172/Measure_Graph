# Measure_Graph

The C++ project to find the graph measurements like - Length, Eccentricity, Radius, Diameter, Centre of Graph

Length – Length of the graph is defined as the number of edges contained in the graph.
![image](https://github.com/Phani172/Measure_Graph/assets/93365533/309e9695-d6f2-44ee-b136-b98764bfede6)


Eccentricity of graph – It is defined as the maximum distance of one vertex from other vertex. The maximum distance between a vertex to all other vertices is considered as the eccentricity of the vertex. It is denoted by e(V).
![image](https://github.com/Phani172/Measure_Graph/assets/93365533/463a6dd7-8e67-4b8b-9d87-7ca17f5c6717)


     Eccentricity from:
    (A, A) = 0
    (A, B) = 1
    (A, C) = 2
    (A, D) = 1
        Maximum value  is 2, So Eccentricity is 2
Radius of graph – A radius of the graph exists only if it has the diameter. The minimum among all the maximum distances between a vertex to all other vertices is considered as the radius of the Graph G. It is denoted as r(G). It can also be found by finding the minimum value of eccentricity from all the vertices.

![image](https://github.com/Phani172/Measure_Graph/assets/93365533/9225552d-3351-4653-b822-6c5a7e655d44)


  Radius: 2
     All available minimum radius: 
     BC → CF,
     BC → CE,
     BC → CD,
     BC → CA
Diameter of graph – The diameter of graph is the maximum distance between the pair of vertices. It can also be defined as the maximal distance between the pair of vertices. Way to solve it is to find all the paths and then find the maximum of all. It can also be found by finding the maximum value of eccentricity from all the vertices.

![image](https://github.com/Phani172/Measure_Graph/assets/93365533/0b8cd6c6-d964-4133-a24f-9dc0d8e2c9d9)


  Diameter: 3
  BC → CF → FG  
 Here the eccentricity of the vertex B is 3 since (B,G) = 3. (Maximum Eccentricity of Graph)
Centre of graph – It consists of all the vertices whose eccentricity is minimum. Here the eccentricity is equal to the radius. For example, if the school is at the center of town it will reduce the distance buses has to travel. If eccentricity of two vertex is same and minimum among all other both of them can be the center of the graph.

![image](https://github.com/Phani172/Measure_Graph/assets/93365533/ba3594f7-fb64-41ff-bd7e-92599fee39c5)


  Centre: A  
  Inorder to find the center of the graph, we need to find the eccentricity of each vertex and
  find the minimum among all of them. The minimum eccentricity vertex will be considered as the center.
