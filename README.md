# Selection Sort Implementation

This repository contains the implementation of the **Selection Sort** algorithm, a straightforward sorting technique suitable for educational purposes and small datasets.

## Overview
Selection Sort is a simple sorting algorithm with the following key characteristics:

- **Time Complexity:**
  - Best Case: O(n^2)
  - Average Case: O(n^2)
  - Worst Case: O(n^2)
- **Space Complexity:** O(1) (in-place sorting)
- **Algorithm Type:** Comparison-based, not stable

## Features
- Implemented in **C++**.
- Supports sorting arrays/lists of integers, floats, or other comparable data types.

## File Structure
- `SelectionSort.cpp`: Contains the implementation of Selection Sort.
- `README.md`: Documentation for the repository.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/selection-sort.git
   ```
2. Navigate to the repository folder:
   ```bash
   cd selection-sort
   ```
3. Compile the code:
   ```bash
   g++ -o selection_sort SelectionSort.cpp
   ```
4. Run the executable:
   ```bash
   ./selection_sort
   ```

## Algorithm Steps
1. Divide the array into a sorted and unsorted section.
2. Find the smallest element in the unsorted section.
3. Swap it with the first element in the unsorted section.
4. Move the boundary between sorted and unsorted sections by one.
5. Repeat steps 2–4 until the array is sorted.

## Example Input and Output
### Input
```plaintext
Array: [4, 10, 3, 5, 1]
```
### Output
```plaintext
Sorted Array: [1, 3, 4, 5, 10]
```

## Contributing
Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## About Me
I am Abdallah Naser, a backend developer, frontend developer using React.js, and a skilled WordPress Designer/Developer with extensive experience in creating and customizing websites using WordPress, Elementor, and WooCommerce.

---

For any questions or feedback, please feel free to contact me!
