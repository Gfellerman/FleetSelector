# FleetSelector

FleetSelector is a vehicle selection software designed to help organizations optimize their fleet management by selecting the most suitable vehicles based on capacity, cost, and other criteria.

## Features

- Selects vehicles to meet required capacity at minimum cost
- Easily configurable vehicle data (JSON format)
- Simple, extensible Python codebase
- Ready for further enhancements (e.g., advanced optimization, UI, reporting)

## Project Structure

- `fleet_selector.py` — Main program logic for vehicle selection
- `vehicles.json` — Sample data file with vehicle information
- `README.md` — Project documentation

## Setup

1. Clone the repository:
git clone https://github.com/Gfellerman/FleetSelector.git
cd FleetSelector

2. Make sure you have Python 3 installed.

## Usage

1. Edit `vehicles.json` to reflect your fleet data.
2. Run the main program:
python fleet_selector.py

3. Enter the required capacity when prompted.
4. The program will display the selected vehicles.

## Example

Sample `vehicles.json`:
```json
[
 {"id": "V1", "type": "Truck", "capacity": 1000, "cost_per_km": 5},
 {"id": "V2", "type": "Van", "capacity": 500, "cost_per_km": 3},
 {"id": "V3", "type": "Car", "capacity": 200, "cost_per_km": 1},
 {"id": "V4", "type": "Truck", "capacity": 1200, "cost_per_km": 6}
]
Contributing
Feel free to fork the repo and submit pull requests for improvements or new features!
