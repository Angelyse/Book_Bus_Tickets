# Book_Bus_Tickets
Book_Bus_Tickets
The Bus Booking System is a USSD-based application that allows users to book bus tickets, view bus schedules and manage their accounts

Introduction The Bus Booking System is a web-based application that allows users to book bus tickets, view bus schedules and manage their accounts. Additionally, the system provides an alternative interface for users to interact via USSD (Unstructured Supplementary Service Data) messages, catering to users who may not have access to the internet or prefer a simpler interface.

Features 
User Registration: Users can register their accounts by providing their name, phone number, and password. Admin login: admin can log in using their username and password. Login: Registered users can log in using their phone number and password. Account Management: Users can view their account details, update their password, and view their booked tickets. Bus Schedule Management: Admins can add, update, and delete bus schedules, including route, departure time, and ticket price. Ticket Booking: Users can select a bus route, specify the number of tickets, and confirm the booking.

USSD Workflow
User Registration: User sends an SMS containing their name and password in Africa’s talking. The system checks if the user is already registered. If not, it registers the user and sends a confirmation SMS. Account Management: Users interact with the USSD menu to view account details, update password, or view booked tickets. The system processes user selections and provides relevant options. Bus Route Selection: Users select a bus route from the available options. They specify the number of tickets and confirm the booking and make payment of booked tickets.

Instructions for Running the Application: 
Requirements: Web Server: e.g., Apache, Nginx. PHP:version 7 or above recommended. MySQL Databas, Africa’s talking Account, Ngrok , Postman

STEPS for Running the Application:
1.Download codes
2.Database Configuration: Import the provided SQL file (database.sql) into your MySQL database to create the necessary tables. Update the database connection parameters in server.php and menu.php to match your MySQL database configuration.
3. Configure SMS Functionality in postman and africa’s talking: If you intend to use SMS functionality for user registration, update the SMS API integration in message.php with your postman API credentials.
4. Set Up Web Server: Configure your web server to serve the application files (PHP files) from the appropriate directory. Ensure proper permissions are set for files and directories to enable read/write access as needed.
5. Run the Application: Access the application through your web browser by entering the appropriate URL. If testing the USSD functionality, ensure that your USSD service provider is configured to forward requests to the ussd.php endpoint. Usage: Register a user account via the postman or SMS (if SMS functionality is enabled). Log in with the registered credentials to access the main features such as booking tickets, managing account details, and View available buses. Explore the different functionalities provided by the web interface and USSD menu options.
