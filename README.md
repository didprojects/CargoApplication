# Cargo Loading Application
A small application for calculating the number count of trolleys required. Trolleys can hold a maximum of 2000kg of cargo. 

* Max single cargo item weight is 200kg
* Max single cargo item size is 2m^3 
* Max cargo trolley weight is 2000kg
* Calculate the number of trolleys needed for a haul of cargo items
* Create tests for your application

(optional) take a cargo manifest cargo.yaml:
```
10223:
    mass: 193.0
    volume: [0.2, 1.2, 2.3]
10224:
   mass: 9.2
   volume: [0, 0, 0]
```
## Language
Python

## Dependency
Before using this application, ensure you have PyYAML installed.
```bash
pip install PyYAML
```

## Filess
* `cargoApp.py` - The main application file for calculating the needed number of trolleys.
* `cargoData.yaml` - A YAML file containing cargo data.
* `cargoAppTest.py` - Unit tests for the application.

## Usage
To run the cargo loading application, execute the following command:
```bash
python cargoApp.py
```
To execute the unit tests, run:
```bash
python cargoAppTest.py
```