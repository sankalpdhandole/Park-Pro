# Park-Pro
Aim: It is a QR Scanner App in which helps in solving the Traffic problems
Blocked Parking Solution
Overview
This project presents a comprehensive solution for addressing the issue of blocked parking using a server-client relationship model. The system leverages web interfaces, QR code technology, and automated communication to facilitate seamless interaction between individuals encountering blocked parking situations and the respective vehicle owners.

Features
User Registration: Secure user registration with unique registration numbers.
QR Code Generation: Dynamic QR code generation based on the unique registration number.
Database Integration: Efficient storage and retrieval of user information using MongoDB.
QR Code Scanning: Easy scanning of QR codes affixed to vehicles, directing users to a web interface with communication options.
Automated Communication: Integration with Twilio for predefined voice messages and SMS for quick and efficient resolution of parking issues.
Technologies Used
MongoDB: For secure storage and management of user information.
Express.js: Backend framework for handling HTTP requests and responses.
Node.js: Runtime environment for server-side logic.
HTML, CSS, JavaScript: For creating a user-friendly and responsive web interface.
Twilio: For handling messaging and calling functionalities.
Project Structure
/public: Contains static assets like HTML, CSS, and JavaScript files.
/routes: Defines the various routes for user registration, login, and QR code scanning.
/models: Contains the database schemas and models.
/controllers: Handles the logic for each route.
/config: Contains configuration files, including Twilio API credentials.
server.js: Entry point for the Node.js server.

Usage
Register a user:

Access the registration page and fill in the required information.
Upon successful registration, a unique QR code will be generated.
Print and affix the QR code to the vehicle.
Login:

Use the login form to access the system with the registered username and password.
QR Code Scanning:

Scan the QR code affixed to a parked vehicle.
The scanner is directed to a web page with options to call or message the vehicle owner.
Choose the preferred communication method to resolve the blocked parking issue.
Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature/your-feature).
Open a pull request.

Acknowledgements
Special thanks to the developers and contributors of MongoDB, Express.js, Node.js, and Twilio for their powerful tools and services.
