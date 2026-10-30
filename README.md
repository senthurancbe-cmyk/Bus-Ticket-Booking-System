# Bus Ticket Booking System

**Project by: Senthuran A**

## Project Overview

The **Bus Ticket Booking System** is a console-based application
developed in the C programming language. It provides a simple interface
for users to sign up or log in, view bus options, book seats, cancel
bookings, and check bus status.

The project demonstrates the use of C programming concepts such as
structures, arrays, functions, conditional statements, loops, file
handling, and date/time functions.

## Features

-   **User Sign-up:** Collects the user's name, email address, phone
    number, and password.
-   **User Login:** Allows users to enter their email address and
    password.
-   **Seat Availability:** Displays the availability status of 21 seats.
-   **Seat Booking:** Allows users to select and book an available seat.
-   **Bus Selection:** Provides the following bus options:
    -   Sri Mathi
    -   SETC Bus
    -   Ragul Dragon Bus
-   **Bus Types and Fare:**
    -   AC -- ₹500
    -   Non-AC -- ₹300
    -   Sleeper Coach -- ₹400
-   **Booking Cancellation:** Allows a user to cancel a booked seat.
-   **Bus Status:** Displays the bus status message configured in the
    program.
-   **Bill Generation:** Displays a receipt with the ticket fare, GST
    amount, and final bill amount.
-   **Date and Time:** Uses the C time library to display the current
    date and time.

## Technologies Used

-   **Programming Language:** C
-   **Header Files:** `stdio.h`, `string.h`, `stdlib.h`, `time.h`
-   **Compiler:** GCC or another C compiler

## Project Structure

``` text
Bus-Ticket-Booking-System/
├── BUS TICKET PROJECT (1).c
├── demo.txt                 # Created when a user signs up
└── README.md
```

## How to Run

### 1. Install a C compiler

Install GCC (for example, through MinGW on Windows) and make sure the
compiler is available from your terminal.

### 2. Open the project folder

Open a terminal or command prompt in the folder containing the C source
file.

### 3. Compile the program

``` bash
gcc "BUS TICKET PROJECT (1).c" -o bus_ticket
```

### 4. Run the program

On Windows:

``` bash
bus_ticket.exe
```

On Linux or macOS:

``` bash
./bus_ticket
```

> The source code includes a Windows console command (`chcp 65001`). The
> program is primarily written with a Windows console environment in
> mind.

## How the System Works

1.  Start the application.
2.  Choose **Login** or **Sign Up**.
3.  Enter the requested account details.
4.  Use the menu to choose ticket booking, booking cancellation, or bus
    status.
5.  For booking, enter the source and destination, select a bus, and
    choose an available seat.
6.  Select the bus type and enter the journey date and time.
7.  View the generated ticket receipt.

## Concepts Demonstrated

-   Structures for storing user information
-   Arrays for maintaining seat status
-   Functions for separating program operations
-   String comparison using `strcmp()`
-   File handling using `fopen()`, `fprintf()`, and `fclose()`
-   Conditional statements and `switch` cases
-   Date and time handling using `time.h`

## Current Scope and Limitations

-   The program manages 21 seats.
-   Bus names and the bus-status message are predefined in the source
    code.
-   The sign-up details are written to `demo.txt`; the current login
    flow does not read saved accounts from that file.
-   Account details are stored as plain text, including the password.
    This is a learning project and is not suitable for real user
    credentials.
-   Seat bookings are maintained in program memory and are not saved
    permanently.
-   The entered route, date, and time are collected by the program, but
    the source code does not verify actual schedules or route
    availability.
-   Fare and GST values are fixed in the source code.

## Future Enhancements

-   Store and retrieve user accounts securely.
-   Add password hashing and input validation.
-   Save bookings and seat availability permanently using files or a
    database.
-   Add route-wise bus schedules and real-time availability.
-   Generate individual tickets with booking IDs.
-   Improve cancellation and refund calculations.
-   Add a graphical user interface.

## Author

**Senthuran A**

------------------------------------------------------------------------

*This project is intended for learning and demonstrating fundamental C
programming concepts.*
