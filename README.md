# Farm-Central
Varsity College - Programming 7311

System Functionality
The Farm Central Stock Management System offers the following functionality: 

1. User Roles and Authentication
o The system supports two user roles: Farmer and Employee.
o Users are required to log in to access user-specific information.
o User authentication is implemented using ASP.NET Core Identity, ensuring secure access to the system. 

2. Farmer and Product Management
o Employees can add new farmers to the database by providing their email, farm name, and address.
o Farmers can add new products to their profile, including product name, description, price, quantity in stock, and product type.
o Existing products can be viewed, edited, and deleted by farmers. 

3. Product Listing and Filtering
o Employees can view a list of all the products supplied by a specific farmer. o The displayed product list can be filtered based on date range or product type, providing flexible searching options. 

4. User Interface
o The website features a visually appealing and user-friendly interface. o Consistent styling and branding have been applied across all pages,enhancing the overall appearance.

System Requirements
To build and run the Farm Central Stock Management System locally, ensure you have the following requirements installed:
• Visual Studio
• .NET Core SDK
• Azure SQL Database

Getting Started
To set up the system and run it locally, follow these steps:
1. Open the solution file (FarmCentral.sln) in Visual Studio.
2. Ensure that the connection string in the appsettings.json file points to your Azure SQL Database or your preferred database.
3. Build the solution in Visual Studio.
4. Run the application using the built-in Visual Studio debugger or by pressing Ctrl+F5.

Sample Data
The Farm Central Stock Management System comes with pre-populated sample data for demonstration purposes. The database includes one employee and four farmers, each with three unique products. Additionally, product types have been pre-populated to provide a comprehensive demo experience.

Additional Notes
• The system utilizes DataTables for table functionality, allowing sortable columns and search capabilities.
• The user interface has been designed with simplicity and ease of use in mind, featuring a clean layout, intuitive navigation, and a pleasant color scheme.

Support
If you encounter any issues or have any questions regarding the Farm Central Stock Management System, please feel free to contact our support team at st10081821@vcconnect.edu.za. We are here to assist you and ensure a smooth experience with our application.
Thank you for using the Farm Central Stock Management System!
