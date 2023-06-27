# DBFFS
Demand Based Feeding of Fishes , A project that aims to automate the feeding process for fishes in a tank based on their demand. The system utilizes computer vision techniques with an overhead camera to detect and measure the average speed of fishes swimming in the tank and open the feeder when a threshold is crossed.

# Fish Feeding System

This project implements a demand-based feeding system for fishes using an overhead camera. The system measures the average speed of all fishes in a tank and triggers a feeder when an arbitrary speed threshold is crossed.

## Features

- Real-time fish speed detection using computer vision techniques
- Calculation of average speed of fishes in the tank
- Servo motor control for opening the feeder
- Demand-based feeding triggered by the average speed crossing a threshold
- Serial communication with an Arduino board

## Requirements

- Python 3.x
- OpenCV
- NumPy
- PySerial


## Features:


- Real-time fish speed detection using computer vision techniques

- Calculation of average speed of fishes in the tank

- Servo motor control for opening the feeder

- Demand-based feeding triggered by the average speed crossing a threshold

- Serial communication with an Arduino board

## Installation:


1. Clone the repository:
   git clone https://github.com/abhishek-sharma05/fish-feeding-system.git

2. Install the required packages:
   pip install opencv-python numpy pyserial

## Usage:


1. Connect the camera and the Arduino board to the system.

2. Open the main.py file and modify the following variables according to your setup:
   
- ser: Serial port and baudrate for Arduino
   
- threshold_speed: Speed threshold for triggering the feeder
   
- camera_index: Index of the camera (0 for default, 1 for second camera, etc.)
   
- roi: Region of interest coordinates (x, y, width, height)

3. Run the script:
   python main.py

## Contributing:

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: feature/your-feature
3. Make your changes and commit them: git commit -m "Add your feature"
4. Push the changes to your branch: git push origin feature/your-feature
5. Create a pull request.

## License:

This project is licensed under the MIT License 
- see the LICENSE file for details.
