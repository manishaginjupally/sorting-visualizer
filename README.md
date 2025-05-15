# Sorting Algorithm Visualizer (C++ with SDL2)

This project is a visual representation of sorting algorithms implemented in C++ using SDL2. The program generates a set of random integers and visually displays the sorting process using vertical bars on the screen. Each sorting algorithm highlights current comparisons and swaps using color codes for better understanding.

#  Features

* Real-time visualization of popular sorting algorithms:

  *  Bubble Sort
  *  Selection Sort
  *  Insertion Sort
  *  Merge Sort
  *  Quick Sort
* Color-coded comparisons:

  * 🔴 Red: current index being processed
  * 🔵 Blue: index being compared
  * ⚪ White: other elements
* Fullscreen window using SDL2 for clear viewing
* Adjustable rendering speed using `SDL_Delay`

# Requirements

* C++ Compiler (e.g., g++)
* SDL2 Library installed on your system

# Installation

# Linux (Ubuntu):

```bash
sudo apt-get install libsdl2-dev
g++ sorting_visualizer.cpp -lSDL2 -o sorting_visualizer
./sorting_visualizer
```

# Windows:

1. Install [SDL2](https://www.libsdl.org/download-2.0.php).
2. Link SDL2 libraries in your IDE or compiler settings.
3. Compile and run the code.

# How to Run

Upon execution:

1. The program generates 50 random integers.
2. You'll be prompted to select one of the sorting algorithms:

   ```
   1 : BUBBLE
   2 : SELECTION
   3 : INSERTION
   4 : MERGE
   5 : QUICK
   ```
3. The selected sorting algorithm will visualize its process in a fullscreen SDL window.

# Screenshots

*Add screenshots here showing the sorting visualizations in progress.*

# Code Structure

* `vis()`: Renders the current state of the array with color codes.
* Sorting Functions:

  * `bubble()`
  * `selection()`
  * `insertion()`
  * `mergesort()`, `merge()`
  * `quick()`, `quicksort()`

# Learning Outcomes

* Understand the working of different sorting algorithms.
* Get hands-on experience with SDL2 rendering.
* See sorting logic in real-time for better conceptual understanding.

# Notes

* The sorting speed can be adjusted by changing `SDL_Delay()` values.
* The fullscreen window resolution depends on the number of elements and scaling factor set via `SDL_RenderSetScale()`.

# License

This project is open-source. Feel free to use and modify it for learning or educational purposes.
