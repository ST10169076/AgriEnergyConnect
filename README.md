AgriEnergyConnect Web Application
Welcome to AgriEnergyConnect! This application helps streamline the management of agricultural products and farmer information. Below, you'll find instructions on how to use the various features of the application.

Getting Started
Prerequisites
Ensure you have the following installed:

.NET Core SDK
A web browser (for accessing the application)
An active internet connection

By default, the application will use the settings defined in the appsettings.json file located in the project's root directory. You can modify this file to change the configuration settings such as database connection strings, logging levels, and more.

Using Visual Studio
If you prefer using an IDE, you can open the project in Visual Studio:

Open the Project:
Launch Visual Studio and open the .sln file located in the project directory.

Restore Dependencies:
Visual Studio will automatically restore the necessary NuGet packages when you open the solution.

Build the Solution:
Build the solution by selecting Build > Build Solution from the top menu.

When opening this project please open the package Manager Console and run "Update-Database"
Then go to the server explorer and refresh it so that the database is created the data will fall into "aspnet-WebApplica71d6221"

Run the Application:
Start the application by pressing F5 or by selecting Debug > Start Debugging.

Troubleshooting
If you encounter any issues while building or running the application, check the following:

Ensure that all dependencies are correctly restored.
Verify that the .NET Core SDK is installed and configured properly.
Check the output logs for any error messages that can help diagnose the problem.

Default Users
You can log in using the following default user credentials:

Admin
Email/Username: Admin@admin.com
Password: Admin@123

Employee 1
Email/Username: Employee1@gmail.com
Password: Emp@123

Employee 2
Email/Username: Employee2@gmail.com
Password: Emp@123

Navigation
The application provides different functionalities based on user roles. Below are the key pages and their functions:

Home Page
Accessible by all users, this page provides an overview of the application and its purpose.

About Us
Accessible by all users, this page provides information about the organization behind the application.

Add Farmer
Accessible by users with the "Employee" or "Superadmin" roles. This page allows adding new farmers to the system.

Navigate to Employees/AddFarmer to access this page.
Fill in the required information and click "Save".
Add Product
Accessible by users with the "Farmer" or "Superadmin" roles. This page allows adding new products.

Navigate to Employees/AddProducts to access this page.
Fill in the required information and click "Save".
Search Products
Accessible by users with the "Employee" or "Superadmin" roles. This page allows searching for products based on various criteria.

Navigate to Employees/SearchProducts to access this page.
Enter the search criteria and click "Search".
User Interface
The layout and design of the application are simple and intuitive, with a navigation bar at the top for easy access to different sections. The application uses Bootstrap for styling to ensure a responsive and user-friendly interface.
