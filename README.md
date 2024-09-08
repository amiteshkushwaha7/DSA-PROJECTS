# 🚉 Metro Station Distance Finder Using Dijkstra's Algorithm 

This project implements Dijkstra's algorithm to find the shortest path (in terms of distance) between a source station and all other stations in a city metro system. The graph represents metro stations, where each station is connected to neighboring stations by a fixed distance.

## 📋 Project Overview

- **Language:** C++
- **Graph Representation:** Adjacency list using vectors
- **Algorithm Used:** Dijkstra’s Algorithm
- **Total Stations:** 53
- **Distance Between Stations:** Fixed (1 km)

The program allows a user to input a source station and displays the shortest distance from the source to all other stations in the metro system.

## ⚙️ Features

- Calculates the shortest path from the source station to all other stations.
- Displays the distances in a user-friendly format with station names and distances.
- Efficiently handles multiple connections using a priority queue (implemented via `set` in C++).
- Handles unreachable stations.

## 🛠 How It Works

1. **Input:** The user selects the source station from the list of 53 available stations.
2. **Dijkstra's Algorithm:** The algorithm computes the shortest distance from the source station to all connected stations.
3. **Output:** Displays the distance of all stations from the source.

## 📍 Metro Station Network

The graph is built using an adjacency list, where each node represents a station, and edges between nodes represent a 1 km distance between connected stations.

**Example of a few station connections:**

```cpp
graph[0] = {{1, 1}};
graph[1] = {{0, 1}, {2, 1}};
graph[2] = {{1, 1}, {3, 1}};
```

## 🏁 Usage
**1.Clone the repository:**
```
git clone https://github.com/your-username/metro-station-distance-finder.git
```

**2.Compile the program:**
```
g++ metro_distance_finder.cpp -o metro_distance_finder
```

**3.Run the executable:**
```
./metro_distance_finder
```

## 🗺 List of Metro Stations
Here are some example stations from the metro network:

0: Gandhi Nagar

1: Karond

2: Berasia

3: Budhwar

4: Jahangirabad

...

For the full list, refer to the program output.


## 🔧 Technologies Used
**Language:** C++

**Standard Library:** Vectors, Pairs, Sets


## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.


## 🤝 Contributing
Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvement. Contributions are always welcome!


## Connect with Me
 If you have any questions, suggestions, or just want to connect, feel free to reach out:

**Email**: amiteshkushwaha2020@gmail.com

**Linedin**: https://www.linkedin.com/in/amiteshkushwaha

**X**: https://x.com/Amitesh037

**GitHub**: https://github.com/amiteshkushwaha7
   
