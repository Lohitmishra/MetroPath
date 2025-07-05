# 🚇 MetroPath: Smart Route Finder using Graph Algorithms

An interactive console-based Metro Navigation App that helps users find the shortest, fastest, and most efficient routes between metro stations — built entirely using Java, Graphs, and Heaps.

## 🌟 Key Features :

🔍 1. Smart Route Finder
Calculate the shortest distance and minimum travel time between any two metro stations using Dijkstra’s algorithm, BFS, and DFS.
Real-time pathfinding considering station interchanges and corridor connections.

💰 2. Dynamic Fare Estimation
Fare is computed based on distance, incorporating additional costs for interchanges or longer travel durations.

🗺️ 3. Metro Map Navigation
View the complete Delhi Metro Map with all current stations, lines, and their interconnections.
Stations displayed along with unique station codes for easier identification.

🛤️ 4. Interchange Detection
Automatically highlights station interchanges across different metro corridors (e.g., Blue ↔ Yellow ↔ Orange).

🎛️ 5. User-Friendly Interface
Multiple input options: station name, code, or serial number.

Clear menu-driven interaction with real-time feedback on route, distance, and estimated travel time.

## 🧠 Core Concepts & Data Structures :

🔹 Graph
Vertices represent metro stations, including name and corridor identifier (e.g., Rajiv Chowk~BY).
Edges represent bi-directional connections between stations with distances.

🔹 Heap (Min Priority Queue)
Custom-built Heap class to efficiently implement Dijkstra’s algorithm for shortest path calculations.

🔹 DFS & BFS
Used to traverse the graph and find all possible paths or validate connectivity between stations.

## File	Description:

Graph_metro.java - Contains all graph logic, pathfinding algorithms, and the console menu UI.
Heap.java -	Implements a generic heap (priority queue) used for Dijkstra’s algorithm.

## 🔧 Technologies Used:

Java – Core logic, data structures, and console interface.
Custom Graph Implementation – Used to model the metro network.
Custom Heap (Priority Queue) – For efficient shortest path lookup.
OOP & Collections – Utilizes HashMap, ArrayList, LinkedList for optimized operations.

## 🧪 Sample Functionalities:

✅ Display all stations with their codes
✅ Print the entire metro map
✅ Calculate shortest distance or fastest route
✅ Display number of interchanges
✅ Support inputs by name, serial number, or code

## 📚 How to Run:

Clone the repository or download the source code.
Compile both Graph_metro.java and Heap.java.
Run the Graph_metro main method from your IDE or terminal.
