# C++ Assembly Line Simulation Project

## Overview
This repository hosts the complete project for a C++ Assembly Line Simulation developed as part of an advanced Object-Oriented Programming course. The project showcases a simulation of an assembly line, demonstrating key OOP concepts like inheritance, polymorphism, encapsulation, and dynamic memory management.

## Project Description
The simulation models a production line where customer orders are processed through various workstations. Each workstation is responsible for adding a specific part to an order. The project effectively represents real-world manufacturing processes in a software environment, highlighting the principles of object-oriented design and C++ programming.

## How It Works
- **Assembly Line Setup**: The simulation sets up an assembly line with multiple workstations. Each workstation has a specific task and inventory.
- **Order Processing**: Customer orders are processed through the line. Each order consists of several items that are filled at the respective workstations.
- **Dynamic Flow**: The orders dynamically move along the line, with each workstation handling its part of the order based on available inventory.

## Key Modules
1. **Utilities**: Parses input data and assists in setting up the simulation environment.
2. **Station**: Represents a single station in the assembly line.
3. **CustomerOrder**: Manages individual customer orders, tracking items and completion status.
4. **Workstation**: Inherits from Station, adding functionality to process orders.
5. **LineManager**: Oversees the entire assembly line, managing the flow of orders and linking workstations.

## Usage
1. **Clone the Repository**: 
