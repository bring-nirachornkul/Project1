# City Growth Simulation

This project is a C++ implementation that simulates the growth of a city over time, focusing on residential, commercial, and industrial zones. The simulation accounts for factors such as population growth and pollution spread and allows for analysis of specific areas within the simulated region.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [File Structure](#file-structure)
- [Configuration](#configuration)
- [How to Run](#how-to-run)
- [Building](#building)
- [License](#license)
- [Author](#author)

## Overview
The City Growth Simulation models the expansion of various zones within a city, adhering to a set of predefined rules that govern the population growth of residential, industrial, and commercial zones. The simulation also tracks the impact of pollution and allows users to analyze specific areas of the region.

## Features
- **Residential, Commercial, and Industrial Zone Simulation**
  - Dynamic population growth based on predefined rules.
- **Pollution Tracking**
  - Tracks pollution spread from industrial zones and its impact on adjacent zones.
- **Detailed Output**
  - Outputs the region’s state at each time step, showing population and pollution.
- **User-Defined Area Analysis**
  - Allows users to select a specific area of the city for in-depth analysis.

## File Structure
```plaintext
├── config/
│   ├── simulation_config.txt  # Configuration file for the simulation
│   └── region_layout.csv      # Initial layout of the region
├── src/
│   ├── main.cpp               # Main entry point of the program
│   ├── resident.cpp           # Handles Residential zone logic
│   ├── commercial.cpp         # Handles Commercial zone logic
│   ├── industrial.cpp         # Handles Industrial zone logic
│   ├── cell.cpp               # Handles Cell data and operations
│   └── common.h               # Header files for common utilities
├── README.md                  # Project documentation
