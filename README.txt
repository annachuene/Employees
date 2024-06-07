Employee Management Application
Overview
This Angular application serves as an employee management system, allowing users to add new employees to the database. It provides a user-friendly interface for managing employee data efficiently.

Functionality
The application offers the following key features:

Add Employee: Users can easily add new employees by filling out a form with essential details such as name, email, department, etc.

Validation: Form fields are validated to ensure that the required information is provided and in the correct format.

Error Handling: Comprehensive error handling is implemented to provide users with informative feedback in case of any issues during the employee addition process.

Confirmation: Upon successful addition of an employee, users receive confirmation messages to acknowledge the completion of the operation.

Getting Started

To use the application, follow these steps:

Clone the folder to your local machine.

Install Dependencies: Navigate to the project directory and run npm install to install all necessary dependencies.

Navigate to EmployeeApp folder on the CLI and run this command: json-server --watch db.json (This will JSON Server started on PORT :3000)

Endpoints:
http://localhost:3000/employees

Run the Application: Use the command ng serve to start the development server. Navigate to http://localhost:4200/ in your web browser to access the application.

Press CTRL-C to stop

Start Adding Employees: Once the application is running, you can start adding employees by filling out the provided form with their details.

Technologies Used
Angular: Frontend framework for building the user interface and application logic.
TypeScript: Programming language used to write Angular code.
HTML/CSS/Bootstrap: Markup and styling languages for structuring and designing the user interface.
JSON Server: Simulated REST API server for storing and retrieving employee data during development.


