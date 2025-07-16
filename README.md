# 🗺️ Map Navigation System

An interactive map-based application to visualize shortest path algorithms like **Dijkstra's Algorithm** and **A* (A-Star) Search** in real time on a randomly generated graph of cities/nodes.

## 🚀 Features

- 📍 Random graph generation with named cities
- 🔍 Pathfinding using **Dijkstra** and **A\*** algorithms
- 🧭 Turn-by-turn navigation instructions
- 🧠 Heuristic-based optimization for faster routing (A\*)
- 🖼️ Smooth visualizations with direction arrows and styled nodes
- 📊 Real-time stats: Total distance, nodes visited, computation time
- 🎛️ Dynamic legend and path highlights
- 📱 Responsive canvas scaling and grid visualization

## 🧠 Algorithms Used

| Algorithm      | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| Dijkstra       | Finds the shortest path from a source to all other nodes (guaranteed optimal) |
| A* Search      | Enhances Dijkstra using heuristics (Euclidean distance) for faster convergence |

## 🛠️ Getting Started

### 📦 Prerequisites

- A modern browser (Chrome, Firefox, etc.)
- No external dependencies or libraries required

### 🧪 Running the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/Ashmit-A-Rawat/MapNavigationSystem.git
2. Open index.html in your browser. Optionally, use a live server extension in VS Code for better local development experience. 

###🧭 How to Use ------------- 
1. Click “Generate Graph” to create a new map.
2. Select start and destination cities.
3. Choose an algorithm (Dijkstra or A*). C
4. Click “Find Route” to compute and display the path.
5. View stats and turn-by-turn directions.
6. Click “Clear Route” to reset the simulation.

###📐 Technical Highlights ----------------------- 
- HTML5 <canvas> drawing with dynamic resizing
- Object-oriented JS design: • MapNavigationSystem class • PriorityQueue class for algorithmic efficiency
- Bidirectional edge creation between nearby nodes
- Euclidean distance calculations for realistic paths
- Directional logic for instructions (bearing + turns)
- Visual indicators: start, destination, route, and visited nodes 

