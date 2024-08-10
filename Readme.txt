# Online Car Rental Platform

This project is an online car rental platform built using Object-Oriented Programming in Python. It allows customers to rent cars on an hourly, daily, or weekly basis, and generates an automated bill when the cars are returned.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Usage](#usage)
- [Example Output](#example-output)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Car Inventory Management**: View available cars for rent.
- **Flexible Rental Options**: Rent cars on an hourly, daily, or weekly basis.
- **Automated Billing**: Calculate and generate bills based on the rental period and number of cars.
- **Discounts**: Apply a discount for renting 3 to 5 cars.

## Project Structure




## Installation



 **Install Dependencies**:
    This project does not require any external Python libraries. It uses Python’s built-in `datetime` module.

## How to Run

1. **Run the Module**: Ensure the `car_rental.py` module is in the same directory as the Jupyter Notebook.
2. **Open the Jupyter Notebook**: Start Jupyter Notebook and open `car_rental_project.ipynb`.
3. **Run the Notebook**: Execute the cells to interact with the car rental platform.

## Usage

- **Display Available Cars**: Check the number of cars currently available for rent.
- **Rent Cars**: Choose to rent cars on an hourly, daily, or weekly basis.
- **Return Cars**: Return the rented cars and receive a bill based on the rental duration.

### Example Usage in Jupyter Notebook

```python

def main():
    rental_company = CarRental(100)
    customer = Customer()

    # Interact with the platform through a simple menu
    # Display available cars, request a car, or return a car
    # The program will automatically calculate and print the bill
    # when cars are returned.



====== Car Rental Shop =======
1. Display available cars
2. Request a car on hourly basis $5
3. Request a car on daily basis $20
4. Request a car on weekly basis $60
5. Return a car
6. Exit
Enter your choice: 2
How many cars would you like to rent? 3
Rented 3 car(s) on an hourly basis at 14 hours.
