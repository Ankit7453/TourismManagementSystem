# TourismManagementSystem
 Project Overview
Tourism Management System (TMS) is a C-based console application designed to simplify the travel booking process. This system enables users to register, book travel packages, print tickets, manage accounts, and cancel reservations with ease. The project efficiently utilizes file handling to store user details and booking information, ensuring data persistence even after closing the program.
This project serves as a basic travel booking system that can be further enhanced with additional features like an interactive GUI or database integration.

🎯 Features
✅ User Authentication & Account Management
Secure user registration & login system.
Ability to change passwords for account security.

✅ Travel Package Browsing
Displays a list of available travel packages with pricing details.
Allows users to explore and select destinations.

✅ Booking System
Users can book travel packages by specifying the destination and number of tickets.
The system calculates total cost and confirms the booking.

✅ Print & Manage Tickets
Users can view & print booked tickets.
Option to cancel a booking if needed.

✅ Data Storage & Security
Uses file handling to securely store user details and booking records.
Ensures data persistence, even after program termination.

🏗️ Project Structure
📂 TourismManagementSystem
│── 📜 TourismManagementNew.c   # Main program file  
│── 📜 users.txt                # Data storage for user records  
│── 📜 README.md                # Project documentation  

🛠️ Technologies Used
Programming Language: C
Data Storage: File Handling (Text Files)
Development Environment: GCC, Turbo C, Code::Blocks, or any C compiler

🏃‍♂️ How to Run the Project
🔹 Prerequisites
Ensure you have a C compiler installed (e.g., GCC).

🔹 Steps to Run
1️⃣ Clone the Repository
git clone https://github.com/yourusername/TourismManagementSystem.git

2️⃣ Navigate to the Project Directory
cd TourismManagementSystem

3️⃣ Compile the Code
gcc TourismManagementNew.c -o tourism

4️⃣ Run the Program
./tourism
