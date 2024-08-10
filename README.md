# Sorting Visualizer

Welcome to the Sorting Visualizer project! This application provides a visual representation of the bubble sort algorithm using Python's `tkinter` library. The visualizer allows you to watch the sorting process in real-time.

## Features

- Visual representation of the bubble sort algorithm
- Dynamic updates of sorting progress
- Adjustable sorting speed

## Installation

To use the Sorting Visualizer, you need to have Python installed on your system. You can download Python from the [official website](https://www.python.org/downloads/).

### Dependencies

This project uses `tkinter`, which is included with Python's standard library. No additional installations are required.

## Usage

1. Clone the repository or download the `sorting_visualizer.py` file.
2. Run the script using Python:

   ```bash
   python sorting_visualizer.py
   ```

3. The Sorting Visualizer window will open, and the bubble sort algorithm will start sorting randomly generated data.

## Code Overview

- **`SortVisualizer` Class**: Inherits from `tk.Tk` and creates a GUI application to visualize the sorting process.
  - **`__init__`**: Initializes the application window and canvas.
  - **`create_bars`**: Creates visual bars representing data.
  - **`update_bars`**: Updates the bars' positions and heights based on the current data.
  - **`bubble_sort`**: Implements the bubble sort algorithm as a generator.
  - **`start_sorting`**: Starts the sorting process if it's not already running.
  - **`animate`**: Continuously updates the visualization during sorting.

- **`main` Function**: Generates random data, creates an instance of `SortVisualizer`, and starts the sorting process after a short delay.

## Customization

- **Data Size and Range**: Modify the `data` generation logic in the `main` function to change the size and range of the data.
- **Sorting Speed**: Adjust the delay in the `self.after()` calls to change the sorting speed.

## Contributing

Feel free to contribute to the project by submitting issues or pull requests. Improvements and enhancements are always welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Python**: For the `tkinter` library used to create the GUI.
- **Bubble Sort Algorithm**: For educational purposes and demonstration of sorting.


