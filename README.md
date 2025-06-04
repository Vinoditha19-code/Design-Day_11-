# Design-Day_11-


01. This code effectively demonstrates how to use MATLAB's graph functionalities to analyze node connections. It shows that the graph is undirected and sparse, and each node's adjacent connections (neighbors) are clearly retrieved and displayed. Such analysis is useful in network analysis, pathfinding algorithms, and connectivity checks.
 
![adjecancy](https://github.com/user-attachments/assets/7f9c1349-d309-44e9-aa38-effc3a32bc5d)

02.The matrix A shows how nodes are connected (adjacency matrix).
A(i,j) = 1 means there is a link between node i and node j.
The graph has 3 nodes:
      Node 1 is connected to Node 2
      Node 2 is connected to Nodes 1 and 3
      Node 3 is connected to Node 2
graph(A) creates the graph using the matrix.
plot(G) draws the graph.
The graph is undirected and connected.
This method is useful for small networks or simple graph analysis.

![Adjacency](https://github.com/user-attachments/assets/4d6f7fa9-786c-458f-9115-517bba416783)

03. A graph G is created with 5 nodes and edges from s to t.
Each node is given a different color (red, green, blue, yellow, magenta).
plot(G, ...) draws the graph with colored nodes and thicker edges (LineWidth = 1.5).
This helps clearly visualize the graph and distinguish each node.

![ColorsNode](https://github.com/user-attachments/assets/b87c46a1-045c-483b-a025-a525124672bf)

04.
A directed graph (digraph) is created with 12 nodes and weighted edges.
weights represent the cost or distance for each connection.
The graph is plotted with:
    Edge labels showing the weights.
    'force' layout, which automatically arranges nodes in a neat and spaced-out manner.
This helps to:
    Clearly see the direction of connections.
    Easily understand weights on each edge.
    Visually analyze the structure of the network.

   ![sahpe](https://github.com/user-attachments/assets/4f394b54-4dab-43e2-bc96-3b103336e9e2)

05.
A directed graph is created using nodes from vectors s to t with specific weights.
Each edge has a weight showing the cost or value of that connection.
The graph is plotted with:
    Red nodes ('NodeColor','r'),
    Edge labels displaying weights.
This helps to:
    Understand the direction and strength of each connection,
    Clearly visualize the network flow using colors and labels.

   ![nodecolor](https://github.com/user-attachments/assets/50a2d1ce-2e5b-4727-8175-505f9a56ea10)

06.
A graph G is created with node 1 connected to nodes 2 to 6.
plot(G, 'Layout', 'force') draws the graph using a clear layout.
highlight(...) is used to:
    Make nodes 1 and 3 red,
    Make the edge between 1 and 3 magenta.
This helps to visually emphasize specific nodes and edges for better understanding or presentation.

![highlights](https://github.com/user-attachments/assets/dba44f7e-f7f1-47b4-8fd8-0607ff81ed61)

07. Exersice_01
A graph G is created using two sets of connections (s to t).
The graph includes a cycle or loop among nodes 1 to 10 (they form a closed ring).
All nodes from 1 to 10 are also connected to node 11, forming a hub.
plot(G, 'Layout', 'force') arranges the graph neatly using the force layout.
This structure shows a ring with a central hub, which is useful in network design (like hybrid topologies).

![exersice_01](https://github.com/user-attachments/assets/fef2731c-3670-46a2-b8b5-653b7ec8d159)

 
