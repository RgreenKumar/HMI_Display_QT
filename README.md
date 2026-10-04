# EV HMI Dashboard

## About the Project

This is a simple Electric Vehicle (EV) HMI Dashboard project developed using Qt and C++ for the frontend and Python for the backend. The main aim of this project is to display vehicle information through a graphical dashboard and understand how the frontend and backend communicate with each other.

## Technologies Used

* Qt 6
* Python
* UART Serial Communication
* CMake
* Ubuntu Linux

## Features

* Graphical dashboard for displaying vehicle information.
* Python backend for simulating vehicle data.
* Serial communication between Qt and Python.
* Virtual UART ports for testing without physical hardware.

## How It Works

The Qt application displays the dashboard, while the Python backend handles the simulated vehicle data. Both parts communicate through UART serial ports. Virtual serial ports can be created using `socat` on Linux for testing.

## Future Improvements

* Connect real vehicle sensors.
* Add more vehicle parameters.
* Improve the dashboard design.
* Add warning indicators for vehicle conditions.

## Project Status

This project is developed for learning and understanding EV dashboard design, Qt GUI development, Python programming, and UART communication.
