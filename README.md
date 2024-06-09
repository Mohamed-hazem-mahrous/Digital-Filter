# Digital Filter Designer App

## Table of Contents

- [Introduction](#introduction)
- [Team Members](#Team-Members)
- [Features](#features)
- [Video Demonstration](#video-demonstration)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction
The Digital Filter Designer app is a powerful tool for designing digital filters using a graphical interface. Users can add, move, and remove zeros and poles in the Z-plane, visualize the filter response, and apply real-time filtering to input signals.

## Team Members
The following team members have contributed to this project:
- [Mohamed Hazem Yehya](https://github.com/Mohamed-hazem-mahrous)
- [Assem Hussein](https://github.com/RushingBlast)
- [Kyrolos Emad](https://github.com/kyrillos-emad)
- [Arsany Maged](https://github.com/Arsany07)


## Features

The Digital Filter Designer app offers the following key features:

1. **Interactive Z-Plane Plotting**: Users can add, move, and remove zeros and poles in the Z-plane, providing a graphical representation of the filter design.

2. **Real-time Filter Response**: The app allows users to visualize the real-time response of the filter as zeros and poles are manipulated.

3. **All Pass Filter Design**: Users can design all-pass filters by adding coefficients and observe their impact on the filter response.

4. **Magnitude and Phase Response Plots**: The app generates interactive plots for magnitude and phase responses based on the designed filter.

5. **Animation**: Users can animate the filter response to observe changes over time.

6. **Import and Export Zeros/Poles**: The app supports importing and exporting zeros and poles data in CSV format.

7. **Signal Filtering**: Users can apply real-time filtering to input signals using the designed filter.

8. **Mouse Generated Signal**: The app includes a plot for the mouse input where the users can draw a signal on that pad using the movement of the mouse to be the shape of the signal and see the signal drawing and its filtered signal.

## Video Demonstration
[App Demo](https://github.com/Mohamed-hazem-mahrous/Digital-Filter/assets/94749599/66b9111b-48f6-4ef7-ba6a-9aea59b4e48c)

## Requirements
List the dependencies and requirements needed to run the application.
- PyQt5
- NumPy
- SciPy
- Pandas
- Pyqtgraph
- Matplotlib

## Installation

Install the required dependencies using pip

```bash
pip install PyQt5 numpy scipy pandas pyqtgraph matplotlib
```


## Usage
Run the application:
```bash
python DigitalFilter.py
```
Use Ctrl+h to open the Help of the app
1. **Z-Plane Interaction**: Use the left mouse button + ctrl button to add zeros or poles and left click on zero or pole to move it. Right-click to remove a point.

2. **All Pass Filter**: Design all-pass filters by adding coefficients and observing their impact on the filter response.

3. **Real-time Filtering**: Load a signal and observe its real-time response as the filter is manipulated.

4. **Import/Export**: Use the "Import" and "Export" options to load and save zeros and poles configurations.

5. **Animation**: Toggle animation to observe the real-time response of the filter over time.

6. **Unit Circle Visualization**: The unit circle is provided for a better understanding of the filter design in the Z-plane.

7. **Mouse Generated Signal**: Use the mouse pad to draw signal and filter it



## Contributing
Contributions to Digital Filter Designer App are welcome! If you encounter any issues or have suggestions for improvements, please create a new issue or submit a pull request.

When contributing, please ensure that you follow the existing coding style and include clear commit messages to maintain a well-documented project history.
