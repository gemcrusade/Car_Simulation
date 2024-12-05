# Car_Simulation
An innovative car simulation project showcasing advanced features and performance metrics, designed to compete with Tesla's cutting-edge automotive technology.


# About this Project

This project simulates the movement of cars based on commands entered by the user. Each car can move forward, backward, or rotate left or right. The simulation checks for collisions between cars, and if a collision occurs, the simulation stops.

## Project Structure

The project is divided into the following key parts:

- **`car_simulation/`**: Contains the refactored code that can be used for unit testing. This code contains the core logic for simulating cars.
- **`production_copy/`**: Contains the original script (`production_script.py`), which is intended for user interaction. This is the script you can run directly.
- **`tests/`**: Contains the unit tests for testing the simulation logic and verifying correctness.
  
## Features

- Simulate the movement of multiple cars.
- Car movements include moving forward, moving backward, turning left, and turning right.
- The simulation detects collisions between cars and stops if a collision occurs.
- The user can input car details (name, position, direction) and commands (move or turn).


# Car Simulation Project

This project simulates the movement of cars based on commands entered by the user. Each car can move forward, backward, or rotate left or right. The simulation checks for collisions between cars, and if a collision occurs, the simulation stops.

## Project Structure

The project is divided into the following key parts:

- **`car_simulation/`**: Contains the refactored code that can be used for unit testing. This code contains the core logic for simulating cars.
- **`production_copy/`**: Contains the original script (`production_script.py`), which is intended for user interaction. This is the script you can run directly.
- **`tests/`**: Contains the unit tests for testing the simulation logic and verifying correctness.

## Features

- Simulate the movement of multiple cars.
- Car movements include moving forward, moving backward, turning left, and turning right.
- The simulation detects collisions between cars and stops if a collision occurs.
- The user can input car details (name, position, direction) and commands (move or turn).

## Installation

1. **Create a Virtual Environment**:
   It's recommended to use a virtual environment to isolate the dependencies for this project.

   ```bash
   python3 -m venv venv
   ```


## Activate the Virtual Environment: On Linux/Mac:

source venv/bin/activate

## On Windows:

venv\Scripts\activate



# Install Dependencies: 

After activating the virtual environment, you can install the required dependencies:

pip install -r requirements.txt




## Usage

### 1. Run the Original Script
To run the original script, navigate to the `production_copy` folder and execute the script.

Example in Linux Ubuntu environment:

```bash
cd ~/car_simulation_project/production_copy

python3 production_script.py
```



2. Run Unit Tests

Unit tests are located in the tests/ directory. The tests ensure that:

    Cars move correctly according to the commands.
    Collisions are properly detected.
    The simulation handles different scenarios, such as multiple cars and different commands.

To run the test script, navigate to the `tests` folder and run the following command:

Example in Linux Ubuntu environment:

```bash
cd ~/car_simulation_project/tests

python3 -m unittest test_simulation
```



License

This project is licensed under the MIT License.
Notes

If you wish to modify or extend the functionality of the simulation, please ensure that any changes are tested by adding or updating the unit tests in the tests/ folder.

The project simulates car movements in a grid, so be mindful of any edge cases when testing or running the simulation.
