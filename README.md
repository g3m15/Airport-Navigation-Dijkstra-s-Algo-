# Airport-Navigation-Dijkstra-s-Algo-

This project is a basic airport navigation system built using Python, Tkinter, and NetworkX. It provides a graphical user interface (GUI) that helps users find the shortest path between various locations in an airport, such as gates, restaurants, and other facilities. The application includes real-time clock updates and a countdown timer for boarding.

## Features

- **Interactive GUI**: User-friendly interface built with Tkinter.
- **Shortest Path Calculation**: Finds the most efficient route between two locations using Dijkstra's algorithm.
- **Real-Time Clock**: Displays the current time.
- **Boarding Time Countdown**: Shows a real-time countdown to the user-defined boarding time.
- **Optimized Layout**: Efficient pathfinding to avoid unnecessary long routes within the airport.
- **Visual Path Highlighting**: Highlights the shortest path on the airport map.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/airport-navigation-system.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd airport-navigation-system
   ```
3. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the application**:
   ```bash
   python airport_navigation.py
   ```

## Usage

1. **Launch the application**.
2. **Select the source and destination locations** from the dropdown menus.
3. **Click "Find Shortest Path"** to calculate and display the route on the map.
4. **Enter your boarding time** to see the countdown timer until boarding.
5. **View the current time** and the time remaining to board on the GUI.

## Code Description

- **`airport_navigation.py`**: The main script for the application.
  - **Imports**: Required libraries including `tkinter`, `networkx`, `matplotlib`, and `datetime`.
  - **Graph Definition**: Defines nodes (e.g., gates, restaurants) and edges with distances.
  - **GUI Implementation**: Uses Tkinter to create the interface, including buttons, labels, and input fields.
  - **Pathfinding**: Implements Dijkstra's algorithm to find and display the shortest path.
  - **Real-Time Features**: Updates the current time and calculates the countdown to the boarding time.


