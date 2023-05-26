# PocketPal
Project Based on Asp.Net Core MVC
PocketPal Expense Tracker
PocketPal Logo

PocketPal is a web-based expense tracking application built using ASP.NET Core MVC. It allows users to conveniently track their day-to-day expenses, helping them gain insights into their spending habits and manage their personal finances effectively.

Features
User Registration and Authentication: Users can create an account and securely log in to the application to access their expense records.
Expense Management: Users can add, view, edit, and delete their expenses, categorize them, and add additional details such as date, description, and payment method.
Expense Filtering and Sorting: Users can filter and sort their expenses based on various criteria, such as date, category, and amount, to gain better visibility into their spending patterns.
Dashboard: The application provides an intuitive dashboard that displays summary statistics and charts to help users analyze their expenses over time.
Budget Tracking: Users can set monthly or weekly budgets, and the application will notify them when they are nearing or exceeding their defined budget limits.
Reports: PocketPal generates detailed reports that allow users to visualize their expenses, identify trends, and make informed financial decisions.
User Profile: Users can manage their profile information, including their name, email address, and profile picture.
Technologies Used
ASP.NET Core MVC: A powerful and flexible framework for building web applications using the Model-View-Controller architectural pattern.
Entity Framework Core: An object-relational mapper (ORM) that provides a convenient way to interact with the database and perform data operations.
Razor Pages: Razor syntax and Razor Page templates are used to define the application's user interface.
HTML/CSS/JavaScript: The frontend of the application is built using these standard web technologies.
Bootstrap: A popular CSS framework that ensures a responsive and visually appealing user interface.
SQL Server: The application uses SQL Server as the database management system to store and retrieve expense data.
Getting Started
To run the PocketPal Expense Tracker application locally, follow these steps:

Prerequisites:

Install the latest version of .NET Core SDK.
Ensure you have SQL Server installed on your machine or have access to a SQL Server instance.
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/pocketpal.git
Configure the Database:

Open the appsettings.json file and modify the connection string to match your SQL Server instance.

Run the following commands to create and apply the database migrations:

bash
Copy code
cd pocketpal/PocketPal.Data
dotnet ef database update
Run the application:

Navigate to the project directory:

bash
Copy code
cd pocketpal/PocketPal.Web
Run the following command to start the application:

arduino
Copy code
dotnet run
Access the application:

Open a web browser and navigate to http://localhost:5000.
Contributing
Thank you for considering contributing to PocketPal! If you have any bug reports, feature requests, or suggestions, please open an issue on the GitHub repository.

If you'd like to contribute code to the project, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix: git checkout -b feature-name.
Make your changes and commit them: git commit -m 'Add some feature'.
Push the branch to your forked repository: git push origin feature-name.
Open a pull request on the
