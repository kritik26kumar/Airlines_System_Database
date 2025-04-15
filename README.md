# ✈️ Airlines System Database
A comprehensive SQL Server database system designed to manage airline operations including flight scheduling, passenger bookings, employee and pilot records, and ticketing.

🚀 Overview
This project is a relational database built using Microsoft SQL Server to manage various operations of an airline reservation system. It covers all essential modules including flight management, passenger booking, employee records, and pilot assignments.

📂 Features
- Stores and manages details for passengers, flights, bookings, employees, and pilots.
- Handles ticket booking, flight scheduling, and seat availability tracking.
- Normalized to 3NF for optimal data integrity and minimal redundancy.
- Includes a comprehensive ER diagram and relational schema.
- Designed to support integration with web-based or desktop airline reservation applications.

🛠️ Tech Stack
- Database: MS SQL Server
- Language: T-SQL (Transact-SQL)
- Tools: SSMS (SQL Server Management Studio)

🧰 How to Run the Project
1. Clone or download this repository.
2. Open `Airlines_Database.sql` in SQL Server Management Studio (SSMS).
3. Execute the script to create the database and all related tables.
4. Use SQL queries or your application backend to interact with the database.

📸 Screenshots / ER Diagram
> ![image](https://github.com/user-attachments/assets/914412b0-1e48-484c-8d62-baf6df7182df)
> ![image](https://github.com/user-attachments/assets/6bbfc09f-64cb-4602-ab8a-bcdc8028d0d5)
> ![image](https://github.com/user-attachments/assets/7add534b-fd3b-4395-a28e-7b8c0b9e43c0)



📌 Entities Included
COUNTRY
STATES
CITY
REGION
CITY
ADDRESS
BANK
CUSTOMER PERSONAL
CUSTOMER EMERGENCY
PARENTS
CUSTOMER ACCOUNT
CUSTOMER MAIN
AIRLINE
AIRPORT
AIRCRAFT
AIRLINE AIRCRAFT REL.
JOURNEY
SCHEDULE
PILOT PERSONAL
PILOT EMG
PILOT ACCOUNT
PILOT MAIN
FLIGHT DETAILS
FLIGHT CLASS
CUSTOMER TRANSACTION
RESERVATION
BORADING PASS
BAGGAGE
DEPARTMENT
DESIGNATION
EMPLOYEE
EMPLOYEE PERSONAL
EMPLOYEE EDUCATION
EMPLOYEE PARENTS
EMPLOYEE MEDICAL
EMPLOYEE EMERGENCY
EMPLOYEE LEAVE
EMPLOYEE ATTENDANCE
EMPLOYEE PERFORMANCE
EMPLOYEE SALARY
EMPLOYEE AIRPORT(AIRPORT,DEPT,DESIG,EMP)

✍️ Author
- [Kritik Kumar]([(https://github.com/kritik26kumar/Airlines_System_Database)])
