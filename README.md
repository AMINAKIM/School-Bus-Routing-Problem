# School-Bus-Routing-Problem

The school bus routing problem is a classic NP-complete problem. For N bus stops (houses) that the school bus must visit, there are 2(N-1)! possible routes. 
For example, with only 10 houses, there are 181,440 possible solutions, and the goal is to find one or more routes that minimize the distance traveled. Therefore, we need to develop an algorithm that can find an approximate solution in a reasonable time. One of the methods used to solve such problems is genetic algorithms.

# Project Objective

The objective of this project is to develop a Python application that uses genetic algorithms to find the shortest distance for the school bus route in the school bus routing problem. We assume that there is a CSV file containing the names, surnames, and addresses of all the students who need school bus transportation. We will use a geolocation API to retrieve the coordinates of the students based on their addresses.

# Usage

1- Ensure you have Python installed on your system.
2- Install the required dependencies using ``pip install -r requirements.txt.``
3- Prepare a CSV file with student information.
4- Configure the geolocation API settings in the ``config.py file``.
5- Run the application: ``python school_bus_routing.py``.
6- View the optimized bus routes and minimum distances.


# Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/AMINAKIM/School-Bus-Routing-Problem.git
    ```

## Contributing
We welcome contributions from the community. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: git checkout -b feature-name
3. Commit your changes: git commit -m 'Add new feature'
4. Push to your branch: git push origin feature-name
5. Create a pull request.

## Author
- BIKANIMINE Amina (@AMINAKIM)

