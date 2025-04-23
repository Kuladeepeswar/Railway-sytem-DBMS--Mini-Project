# Railway-sytem-DBMS--Mini-Project

🚆 Railway Reservation System – DBMS Project
📋 Project Overview
This project simulates a Railway Reservation System using a relational database. It is designed to manage various aspects of a railway network such as stations, trains, routes, coaches, classes, schedules, passengers, bookings, and seat availability.

🛠 Technologies Used
DBMS: MySQL

Language: SQL

Tools: Any SQL-compatible IDE (e.g., MySQL Workbench)

🗂️ Database Schema
The database consists of the following tables:

Station – Stores information about railway stations.

Train – Contains train-specific data including types and schedule details.

Route – Maps the stations that a train passes through in sequence.

Class – Defines class types like Sleeper, AC, General, etc.

Coach – Associates trains with specific coaches and their types.

Schedule – Specifies train departure/arrival times and frequencies.

Passenger – Contains passenger details.

Booking – Manages booking transactions including seat allocations and status.

Seat – Tracks individual seat availability and type.

BookingStatus – Maintains metadata for various booking statuses like CNF, RAC, WL, etc.

🧪 Sample Data
Sample data is provided for:

57 railway stations

3 trains

Detailed routes for each train

Class types with fare per km

Coaches and associated seat details

Booking entries for multiple passengers

Seat allocations and availability

Booking statuses

✅ Key Features
Real-time seat allocation simulation

Route planning and stop timing for trains

Different booking statuses and quotas (General, Tatkal, Senior Citizen, etc.)

Integration of train types and classes for dynamic pricing

Logical relationships with appropriate foreign key constraints

📦 How to Use
Create a database in your SQL environment.

Execute the main.txt script to set up the tables and insert data.

You can now perform queries such as:

Get available seats for a train.

Find the route of a specific train.

Check booking status for a passenger.

List all trains operating between two stations.
