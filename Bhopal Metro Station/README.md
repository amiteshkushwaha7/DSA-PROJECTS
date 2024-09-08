# 🚉 Bhopal Metro Station Distance Finder Using Dijkstra's Algorithm 

This project implements Dijkstra's algorithm to find the shortest path (in terms of distance) between a source station and all other stations in a city metro system. The graph represents metro stations, where each station is connected to neighboring stations by a fixed distance.

## 📋 Project Overview

•⁠  ⁠**Language:** C++

•⁠  ⁠**Graph Representation:** Adjacency list using vectors

•  **Algorith used**: Dijkstra’s Algorithm

•⁠  ⁠**Total Stations:** 53

•⁠  **Distance between Stations**: Fixed (1 km)


The program allows a user to input a source station and displays the shortest distance from the source to all other stations in the metro system.


## ⚙️ Features

•⁠  ⁠Calculates the shortest path from the source station to all other stations.

•⁠  ⁠Displays the distances in a user-friendly format with station names and distances.

•⁠  ⁠Efficiently handles multiple connections using a priority queue (implemented via ⁠ set ⁠ in C++).

•⁠  ⁠Handles unreachable stations.


## 🛠 How It Works

**1.Input:** The user selects the source station from the list of 53 available stations.

**2.Dijkstra's Algorithm:** The algorithm computes the shortest distance from the source station to all connected stations.

**3.Output**: Displays the distance of all stations from the source.


## 📍 Metro Station Network

The graph is built using an adjacency list, where each node represents a station, and edges between nodes represent a 1 km distance between connected stations.

**Example of a few station connections:**
```
graph[0] = {{1, 1}};
graph[1] = {{0, 1}, {2, 1}};
graph[2] = {{1, 1}, {3, 1}};
```

## 🏁 Usage
**1.Clone the repository:**
```
git clone https://github.com/your-username/repo-name.git
```

**2.Compile the program:**
```
g++ repo-name.cpp -o repo-name
```

**3.Run the executable:**
```
./repo-name
```


## 🔧 Technologies Used
**Language:** C++

**Standard Library:** Vectors, Pairs, Sets


## 🤝 Contributing
Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvement. Contributions are always welcome!


## Connect with Me
 If you have any questions, suggestions, or just want to connect, feel free to reach out:

**Email**: amiteshkushwaha2020@gmail.com

**Linedin**: https://www.linkedin.com/in/amiteshkushwaha

**X**: https://x.com/Amitesh037

**GitHub**: https://github.com/amiteshkushwaha7
