# Hotel Management System

## Overview

This Python program manages hotel data by providing functionalities to sort and filter hotel information based on different criteria such as name, rating, and room availability. It also handles user data related to hotel bookings.

## Features

- **Sort Hotels**: Sorts hotels by name, rating, or room availability.
- **Filter Hotels**: Displays hotels in a specific location.
- **Display User Data**: Shows user details along with their associated hotel bookings.

## Requirements

- Python 3.x

## Usage

1. **Clone the Repository**

    ```bash
    git clone https://github.com/username/hotel-management-System.git
    cd hotel-management-System


2. **Run the Script**

    Execute the script to manage hotel and user data:

    ```bash
    python hotel_management_System.ipynb
    ```
    This will initialize hotel and user data, perform sorting and filtering operations, and display the results.

## Functionality

- **Hotel Class**: Represents hotel data with attributes for name, available rooms, location, rating, and price per room. Provides methods to sort hotels based on different parameters.
- **User Class**: Represents user data with attributes for username, user ID, and booking cost.
- **PrintHotelData(hotels)**: Prints the details of a list of hotels.
- **SortHotelByName(hotels)**: Sorts and prints hotels by name.
- **SortHotelByRating(hotels)**: Sorts and prints hotels by rating.
- **PrintHotelBycity(city, hotels)**: Filters and prints hotels by location.
- **SortByRoomAvailable(hotels)**: Sorts and prints hotels by room availability.
- **PrintUserData(userName, userId, bookingCost, hotels)**: Prints user data and their associated hotel bookings.
- **HotelManagement(...)**: Main function that initializes data and calls the various operations.

## Example

When you run the script, it will output sorted and filtered hotel data, along with user data linked to their bookings.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. For major changes, please open an issue first to discuss what you want to change.\

## Contact

For any questions or feedback, please reach out to <rastogikunal19@gmail.com>.
