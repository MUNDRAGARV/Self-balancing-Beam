# Self-balancing-Beam
## Description

This project was a part of the Measurements, Instrumentation and Control (ME2400) course. We created a self-balancing beam with a brushless DC motor on one side providing thrust to lift the beam and get it to a required angle between -40 degrees to +40 degrees. The system was also able to maintain the beam at any given angle between -30 to +30 degrees.

The project utilizes a PID controller and an MPU6050 gyroscopic sensor to display the angle output, which is used to fine-tune the system. The accompanying Jupyter Notebook file contains a theta vs time graph for calculating the values of the Ultimate Cycle method for tuning.

## Installation

To run the Arduino code, you will need the Arduino IDE installed. For the Jupyter Notebook file, you will need Jupyter Notebook installed along with the necessary Python libraries

## Usage

1. Upload the Arduino code to your Arduino board.
2. Open the Jupyter Notebook file to analyze the theta vs time graph and calculate the values of the Ultimate Cycle method for tuning.
