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
```





## Configuration
The simulation uses two configuration files:

1. `simulation_config.txt` - Defines parameters such as the region layout file, time steps, and refresh rate.
2. `region_layout.csv` - Provides the initial layout of the region with zones like residential, industrial, commercial, etc.

## How to Run
To run the simulation, follow the instructions below.

1. **Clone the repository**:
    ```bash
    git clone [https://gitlab.com/your-username/city-growth-simulation.git](https://github.com/bring-nirachornkul/Project1.git)
    ```

2. **Navigate to the project directory**:
    ```bash
    cd city-growth-simulation
    ```

3. **Build the project**:
    ```bash
    make
    ```

4. **Run the simulation**:
    ```bash
    ./simulation config/simulation_config.txt
    ```

## Building
To compile the project manually:

```bash
g++ -o simulation src/main.cpp src/resident.cpp src/commercial.cpp src/industrial.cpp src/cell.cpp
```

The output binary `simulation` can be executed using the provided configuration file.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
**Phongsiri Nirachornkul**

For more information, feel free to reach out via GitLab or email.
```

You can paste this directly into your `README.md` file for a clean and professional look.
