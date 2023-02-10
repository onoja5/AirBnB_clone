# The AirBnB Clone Project

![AirBnB Logo](https://www.pngitem.com/pimgs/m/132-1322125_transparent-background-airbnb-logo-hd-png-download.png)

### Contents

- [Description](#Description)
- [Environment](#Environment)
- [Further Information](#Furtherinformation)
- [Requirements](#Requirements)
- [Repo Contents](#FileContents)
- [Installation](#Installation)
- [Usage](#Usage)
- [Built with](#Built-with)
- [Acknowledgements](#Acknowledgements)

## Description :Description:
We are currently in the first phase of the AirBnB Clone project , where we are developing a command line interpreter to access objects that will store user data. The console allows users to create objects, update object attributes, remove objects, list all objects, and store and read data from.json files.

## Environment :computer:
The console was developed in Ubuntu 20.04 LTS using python3 (version 3.8.5)

### Further information :bookmark_tabs:
For further information on python version, and documentation visit [python.org](https://www.python.org/), (https://docs.python.org/3.4/tutorial/modules.html#packages), (https://www.airbnb.com/).

## Requirements :memo:
Knowledge of python3, command line interpreter, Ubuntu Operating system, python3 and pep style corrector.

## Repo Contents :clipboard:
This repository constains the following files:

|   **File**   |   **Description**   |
| -------------- | --------------------- |
|[AUTHORS](./AUTHORS) | Contains information about the project's authors. |
|[base_model.py](./models/base_model.py) | This defines Class that defines all common attributes|
|[user.py](./models/user.py) | User class that inherits from BaseModel |
|[amenity.py](./models/amenity.py) | Amenity class that inherits from BaseModel |
|[city.py](./models/city.py)| City class that inherits from BaseModel |
|[place.py](./models/place.py)| Place class that inherits from BaseModel |
|[review.py](./models/review.py) | Review class that inherits from BaseModel |
|[state.py](./models/state.py) | State class that inherits from BaseModel |
|[file_storage.py](./models/engine/file_storage.py) | lass that serializes instances to a JSON file and deserializes JSON file to instances |
|[console.py](./console.py) | creates object, retrieves object from file, does operations on objects, updates attributes of object and destroys object |
|[test_base_model.py](./tests/test_models/test_base_model.py) | unittests for base_model |
|[test_user.py](./tests/test_models/test_user.py) | unittests for user |
|[test_amenity.py](./tests/test_models/test_amenity.py) | unittests for amenity |
|[test_city.py](./tests/test_models/test_city.py) | unittests for city |
|[test_place.py](./tests/test_models/test_place.py) | unittests for place |
|[test_review.py](./tests/test_models/test_review.py) | unittests for review |
|[test_state.py](./tests/test_models/test_state.py) | unittests for state |
|[test_file_storage.py](./tests/test_models/test_engine/test_file_storage.py) | unittests for file_storage |
|[test_console.py](./tests/test_console.py) | unittests for console |


## Installation :hammer_and_wrench:
Clone the repository and run the console.py
```
$ git clone https://github.com/------/AirBnB_clone.git
```

## Usage :wrench:

|   **Method**   |   **Description**   |
| -------------- | --------------------- |
|[create](./console.py) | Creates object for the given class |
|[show](./console.py) | Prints the string representation of an instance based on the class name and `id` |
|[all](./console.py) | Prints all string representation of all instances based or not on the class name |
|[update](./console.py) | Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file) |
|[destroy](./console.py)| Deletes an instance based on the class name and id (save the change into the JSON file) |
|[count](./console.py)| Retrieve the number of instances of a class |
|[help](./console.py)| Prints information about specific command |
|[quit/ EOF](./console.py)| Exit the program |


## Built with :bookmark_tabs:
python3 (3.8.5)

### Version :pushpin:
HBnB -AirBnB version

### Authors :peers:
* Michael Onoja - @onoja5
* Lydia Nwaizu - @Lydiva

