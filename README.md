# Fun assignments from some CS classes at school

CS 3450: Algorithms
CS 3451: Advanced Data Structures

# graph_scissors
This notebook is focused on graph analysis and visualization using the NetworkX library. Here's a summary of its key components and functionality:

1. Core Functions:
   - `create_graph_from_file()`: Reads a text file containing node connections (in format "node: connected_nodes") and creates an undirected graph
   - `plot_graph()`: Visualizes a graph using matplotlib with custom styling (light blue nodes, spring layout)
   - `disconnect_graph()`: Creates subgraphs by removing specified edges
   - `partition_graph_kl()`: Implements the Kernighan-Lin algorithm for graph bisection

2. Main Workflow:
   - Reads graph structure from 'input.txt'
   - Creates and displays the original graph visualization
   - Removes specific edges ('tbg'-'ljh', 'mnh'-'qnv', 'ffv'-'mfs') to disconnect the graph
   - Visualizes each resulting disconnected component
   - Includes commented-out code for Kernighan-Lin partitioning

3. Notable Features:
   - Uses spring layout for graph visualization
   - Implements both manual graph disconnection and algorithmic partitioning
   - Preserves the original graph when creating disconnected components by working with a copy

The code appears to be designed for analyzing network structures and exploring different ways of partitioning or disconnecting them. It would be helpful to see the structure of the input.txt file to better understand the specific network being analyzed.
