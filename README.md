---

# Air Ticket Booking System

This Java project implements an Air Ticket Booking system where users can book, cancel, and print ticket details for different flights.
Its a compiler project.

## Features

- Booking: Users can book tickets for available flights.
- Cancellation: Users can cancel tickets and receive a refund amount.
- Printing: Ticket details and flight information can be printed.
- Flight Management: Each flight has a unique ID, ticket price, and number of available tickets.
- Passenger Management: Passenger details such as ID, ticket count, and total cost are stored for each ticket.

## Getting Started

### Prerequisites

Make sure you have the following software installed on your machine:

- Java Development Kit (JDK)
- Java Runtime Environment (JRE)

### Installation

1. Clone this repository to your local machine using the following command:

   ```shell
   git clone https://github.com/your-username/air-ticket-booking.git
   ```

### Usage

1. Navigate to the cloned repository's directory:

   ```shell
   cd air-ticket-booking
   ```

2. Compile the Java source code:

   ```shell
   javac Main.java
   ```

3. Run the program:

   ```shell
   java Main
   ```

## Class Descriptions

### Air_Ticket Class

- `flight_id`: An integer representing the ID of the flight.
- `ticket_price`: An integer representing the price of a ticket.
- `available_tickets`: An integer representing the number of available tickets for the flight.
- `passenger_id`: An array of integers to store passenger IDs.
- `passenger_count`: An array of integers to store passenger counts per ticket.
- `total_cost`: An array of integers to store the total cost per ticket.
- `cancel_passenger_id`: An integer to track the number of persons booked per ticket.
- `i`: An integer to note passenger IDs.

### functions Class

The `functions` class extends the `Air_Ticket` class and provides the following methods:

- `Book_ticket()`: Allows users to book tickets for a specific flight.
- `Cancel_ticket()`: Allows users to cancel tickets and receive a refund amount.
- `Print_details()`: Prints ticket details for a specific flight.
- `show_flight_details()`: Displays the flight details, including the flight ID, remaining tickets, and ticket price.
- `show_ticket()`: Displays the ticket details for a specific passenger.
- `updateAdd()`: Updates the ticket and flight details after booking tickets.
- `updateMinus()`: Updates the ticket and flight details after canceling tickets.

### Main Class

The `Main` class handles user interactions and executes the Air Ticket Booking system. Users can book, cancel, and print ticket details for different flights.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your forked repository.
5. Open a pull request and provide a detailed description of your changes.

---
