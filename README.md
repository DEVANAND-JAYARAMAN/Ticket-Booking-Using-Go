# Ticket-Booking-Using-Go
🚀 Project Overview
This application allows users to:

Enter their personal details (first name, last name, email).

Book a specific number of tickets for a conference.

View the first names of users who have already booked tickets.

Receive confirmation messages after booking.

It continues to run until all the tickets are booked.

📦 Features
Input validation for:

First and last names (minimum 2 characters)

Email format (must contain @)

Ticket count (must be positive and within available range)

Uses Go maps and slices to store and manage bookings.

Keeps track of remaining tickets.

Displays the first names of all people who have booked.

Clean, modular code using reusable functions.

🛠️ Technologies Used
Go (Golang) – Core language

Built-in packages:

fmt for console I/O

strconv for converting ticket count to string

strings for email validation

Run the Application:

go run main.go
Follow the Prompts:

Enter your first name, last name, email, and number of tickets.

Booking confirmation will be displayed.

The application continues until all tickets are sold.

🧾 Code Structure Description
main(): Entry point that calls greeting, handles user input and logic loop.

greetUsers(): Greets the users and shows available tickets.

getUserInput(): Collects input from the user.

validateUserInput(): Validates names, email, and ticket number.

bookTicket(): Updates remaining tickets and stores booking details in a map.

printFirstNames(): Prints the list of first names of people who booked tickets.
