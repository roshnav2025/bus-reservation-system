# bus-reservation-system
abstract summary of the code:

Main Menu: The program starts with a main menu where users can choose from various options, including viewing the list of available buses, booking tickets, canceling bookings, checking the status of the buses, and exiting the system.

Bus List: Users can view a list of available bus services. The bus information is stored in an array.

Booking Tickets: Users can book tickets for a specific bus by selecting the bus number and entering the number of tickets they want to book. The program then tracks the available seats and stores the passenger details, including names and seat numbers, in separate text files for each bus.

Cancellation: Users can cancel a booking by specifying the bus number and the seat number they want to cancel. The program returns the booking amount and updates the seat status as "Empty."

Status Board: Users can check the status of a specific bus, which displays the seat layout and the names of passengers who have booked those seats. This information is read from the text files created during booking.

Login System: The program also includes a basic login system for user authentication. The default username and password are "user." Users have a limited number of login attempts.

File Handling: The code utilizes file handling to read and write information related to bus bookings, seat availability, and passenger details.

User Interface: The program provides a simple command-line interface with menus and prompts for user interactions.

run code in command prompt
