# Online-Shopping
This is an Online Shopping System built using JavaScript, CSS, XML, ASP.NET, and the .NET Framework with SQL Server as the database. This project provides a comprehensive platform for users to browse, search, and purchase products online, while offering an admin panel for managing the system.

Features
User Features:
User Registration and Login: Secure authentication system for users to create accounts and log in.
Product Catalog: Browse products by categories, search functionality, and product details page.
Shopping Cart: Add products to the cart, view the cart, update quantities, and remove items.
Checkout Process: Secure checkout process, including shipping details, payment gateway integration, and order summary.
Order History: Users can view their past orders and track current orders.
User Profile Management: Update personal details, change password, and manage addresses.
Admin Features:
Admin Login: Secure authentication for administrators.
Product Management: Add, update, delete, and manage products and categories.
Order Management: View and manage customer orders, update order statuses.
User Management: View and manage registered users.
Reports: Generate sales reports, customer activity, and inventory levels.
Technologies Used
Frontend:
HTML, CSS, JavaScript
XML for data interchange
Backend:
ASP.NET using the .NET Framework
Database:
SQL Server
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/online-shopping-system.git
cd online-shopping-system
Setup Database:

Restore the provided SQL Server database backup (.bak) file to your SQL Server instance.
Update the connection string in the web.config file with your SQL Server credentials.
Build the Project:

Open the solution file (.sln) in Visual Studio.
Build the project to restore NuGet packages and compile the code.
Run the Application:

Start the application from Visual Studio (F5).
The application will be hosted on http://localhost:<port>/.
Access the Admin Panel:

Navigate to /admin and log in with the default admin credentials provided in the database.
Usage
Users can browse products, add them to the cart, and proceed with the checkout process.
Admins can manage the product catalog, view orders, and handle administrative tasks.
Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch: git checkout -b feature/your-feature-name.
Commit your changes: git commit -m 'Add some feature'.
Push to the branch: git push origin feature/your-feature-name.
Submit a pull request.
