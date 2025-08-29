🏨 Hotel Room Booking System (Java) : 
This project is a simple console-based Hotel Room Booking System implemented in Java using two-dimensional arrays.
It allows users to view available and booked rooms, book a room, and exit the system.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🔹 Features
View all rooms (Available = A, Booked = B)
Book a room by selecting a floor and room number
Prevents booking of already reserved rooms
Handles invalid input for floor/room numbers
Menu-driven interface for easy interaction
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🔹 How It Works
The hotel is represented using a 2D boolean array:
false → Room is Available
true → Room is Booked
Users interact with a simple menu:
View Rooms
Book a Room
Exit
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🔹 Example Run
--- Hotel Room Booking System ---
1. View Rooms
2. Book a Room
3. Exit
Enter your choice: 1

Room Status (A = Available, B = Booked):
Floor 1: A A A A A
Floor 2: A A A A A
Floor 3: A A A A A

Enter your choice: 2
Enter floor number (1-3): 2
Enter room number (1-5): 3
Room booked successfully!

Enter your choice: 1
Floor 1: A A A A A
Floor 2: A A B A A
Floor 3: A A A A A
