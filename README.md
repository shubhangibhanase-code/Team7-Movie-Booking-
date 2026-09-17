Movie Booking & Seat Booking System
1. Requirements
Functional Requirements
The system should include the following functional requirements:
Customer Details -- Add and manage customer name, mobile number and other basic details.
Movie Details -- Add and display movie name, language, duration and other movie information.
Theatre Details -- Store and display theatre name, location and screen details.
Show Details -- Manage show date, time and movie-theatre information.
Seat Availability -- Display available and booked seats.
Seat Selection -- Allow the customer to select available seats.
Seat Booking -- Book the selected seats and store booking details.
Booking Confirmation -- Generate and display confirmation after successful booking.
Non-Functional Requirements
Easy to use -- Simple and user-friendly interface.
Performance -- System should respond quickly.
Security -- Customer and booking data should be protected.
Reliability -- Booking information should be stored correctly.
Accuracy -- Avoid duplicate seat bookings.
Maintainability -- System should be easy to update and maintain.
Hardware Requirements
Computer/Laptop
Minimum 4 GB RAM
Minimum 20 GB free storage
Keyboard and Mouse
Internet connection (if required)
Software Requirements
Operating System: Windows/Linux
Frontend: HTML, CSS, JavaScript
Backend: PHP / Java / Python
Database: MySQL
IDE: VS Code / Eclipse / any suitable IDE
Web Browser: Chrome / Edge / Firefox
2. Algorithm
Start
Enter Customer Details.
Select Movie.
Select Theatre.
Select Show Date and Time.
Display Available Seats.
Select the required Seat.
Check Seat Availability.
If the seat is not available, select another seat.
If the seat is available, confirm the seat.
Calculate the Ticket Amount.
Confirm the Booking.
Display Booking Confirmation.
Stop.
3. Flowchart
Create a neat and easy-to-understand flowchart for the complete booking process.
Flow
Start
↓
Enter Customer Details
↓
Select Movie
↓
Select Theatre
↓
Select Show Date & Time
↓
Display Available Seats
↓
Select Seat
↓
Is Seat Available?
No → Select Another Seat → Return to Select Seat
Yes → Confirm Seat → Calculate Ticket Amount → Confirm Booking → Display Booking Confirmation → End
Standard Flowchart Symbols
Oval = Start / End
Rectangle = Process
Parallelogram = Input / Output
Diamond = Decision
Arrow = Flow direction
4. ER Diagram
Create a clear ER diagram for the Movie Booking System.
Entities and Attributes
CUSTOMER
Customer_ID (PK)
Customer_Name
Mobile_No
Email
MOVIE
Movie_ID (PK)
Movie_Name
Language
Duration
THEATRE
Theatre_ID (PK)
Theatre_Name
Location
SHOW
Show_ID (PK)
Show_Date
Show_Time
Movie_ID (FK)
Theatre_ID (FK)
SEAT
Seat_ID (PK)
Seat_Number
Seat_Type
Theatre_ID (FK)
BOOKINGMovie Booking & Seat Booking System
1. Requirements
Functional Requirements
The system should include the following functional requirements:
Customer Details -- Add and manage customer name, mobile number and other basic details.
Movie Details -- Add and display movie name, language, duration and other movie information.
Theatre Details -- Store and display theatre name, location and screen details.
Show Details -- Manage show date, time and movie-theatre information.
Seat Availability -- Display available and booked seats.
Seat Selection -- Allow the customer to select available seats.
Seat Booking -- Book the selected seats and store booking details.
Booking Confirmation -- Generate and display confirmation after successful booking.
Non-Functional Requirements
Easy to use -- Simple and user-friendly interface.
Performance -- System should respond quickly.
Security -- Customer and booking data should be protected.
Reliability -- Booking information should be stored correctly.
Accuracy -- Avoid duplicate seat bookings.
Maintainability -- System should be easy to update and maintain.
Hardware Requirements
Computer/Laptop
Minimum 4 GB RAM
Minimum 20 GB free storage
Keyboard and Mouse
Internet connection (if required)
Software Requirements
Operating System: Windows/Linux
Frontend: HTML, CSS, JavaScript
Backend: PHP / Java / Python
Database: MySQL
IDE: VS Code / Eclipse / any suitable IDE
Web Browser: Chrome / Edge / Firefox
2. Algorithm
Start
Enter Customer Details.
Select Movie.
Select Theatre.
Select Show Date and Time.
Display Available Seats.
Select the required Seat.
Check Seat Availability.
If the seat is not available, select another seat.
If the seat is available, confirm the seat.
Calculate the Ticket Amount.
Confirm the Booking.
Display Booking Confirmation.
Stop.
3. Flowchart
Create a neat and easy-to-understand flowchart for the complete booking process.
Flow
Start
↓
Enter Customer Details
↓
Select Movie
↓
Select Theatre
↓
Select Show Date & Time
↓
Display Available Seats
↓
Select Seat
↓
Is Seat Available?
No → Select Another Seat → Return to Select Seat
Yes → Confirm Seat → Calculate Ticket Amount → Confirm Booking → Display Booking Confirmation → End
Standard Flowchart Symbols
Oval = Start / End
Rectangle = Process
Parallelogram = Input / Output
Diamond = Decision
Arrow = Flow direction
4. ER Diagram
Create a clear ER diagram for the Movie Booking System.
Entities and Attributes
CUSTOMER
Customer_ID (PK)
Customer_Name
Mobile_No
Email
MOVIE
Movie_ID (PK)
Movie_Name
Language
Duration
THEATRE
Theatre_ID (PK)
Theatre_Name
Location
SHOW
Show_ID (PK)
Show_Date
Show_Time
Movie_ID (FK)
Theatre_ID (FK)
SEAT
Seat_ID (PK)
Seat_Number
Seat_Type
Theatre_ID (FK)
BOOKING
Booking_ID (PK)
Booking_Date
Amount
Customer_ID (FK)
Show_ID (FK)
Seat_ID (FK)
Relationships / Cardinality
Customer 1 : M Booking
Movie 1 : M Show
Theatre 1 : M Show
Theatre 1 : M Seat
Show 1 : M Booking
Seat 1 : M Booking
PK = Primary Key
FK = Foreign Key
Project Summary
The Movie Booking & Seat Booking System manages customer details, movie details, theatre details, show details, seat availability, seat selection and seat booking. The system checks seat availability before confirming a booking and stores the booking information.
Booking_ID (PK)
Booking_Date
Amount
Customer_ID (FK)
Show_ID (FK)
Seat_ID (FK)
Relationships / Cardinality
Customer 1 : M Booking
Movie 1 : M Show
Theatre 1 : M Show
Theatre 1 : M Seat
Show 1 : M Booking
Seat 1 : M Booking
PK = Primary Key
FK = Foreign Key
Project Summary
The Movie Booking & Seat Booking System manages customer details, movie details, theatre details, show details, seat availability, seat selection and seat booking. The system checks seat availability before confirming a booking and stores the booking information.
