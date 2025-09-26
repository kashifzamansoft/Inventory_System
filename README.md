# Inventory Management System

This project is a **web-based Inventory Management System** developed in PHP and MySQL. It allows businesses to manage their products, categories, suppliers, and sales efficiently. The system provides features such as stock tracking, sales reporting, user management, and more. It is designed for small to medium-sized businesses that need a straightforward solution to maintain inventory records.

---

## Key Features

- **User Authentication**
  - Secure login and logout system
  - Change and reset password options
- **Product Management**
  - Add, update, and delete product details
  - Organize products by categories
  - Manage suppliers and their information
- **Inventory Control**
  - Monitor stock levels in real-time
  - Update product quantity after sales or purchases
- **Sales Management**
  - Create and manage sales records
  - Generate invoices for customer transactions
- **Reporting**
  - Daily, monthly, and custom reports
  - Sales and inventory statistics
  - Exportable report options
- **User Management**
  - Create and manage multiple user accounts
  - Role-based access for system security

---

## Project Structure

The repository contains the following files and directories:

```
Inventory_System/
│
├── includes/                # Common PHP files (database connection, configurations)
├── layouts/                 # Reusable layout files (header, footer, sidebar, etc.)
├── LOGIN DETAILS & PROJECT INFO.txt  # Default login credentials and project notes
│
├── add_account.php          # Add new user accounts
├── add_category.php         # Add product categories
├── add_customer.php         # Add customer records
├── add_product.php          # Add new products
├── add_sales.php            # Add new sales transactions
├── add_supp.php             # Add supplier records
│
├── change_password.php      # Change password functionality
├── config.php               # Database configuration
├── dashboard.php            # Admin dashboard
│
├── delete_account.php       # Delete user accounts
├── delete_category.php      # Delete categories
├── delete_customer.php      # Delete customers
├── delete_product.php       # Delete products
├── delete_sales.php         # Delete sales records
│
├── edit_account.php         # Edit user account details
├── edit_category.php        # Edit product category details
├── edit_customer.php        # Edit customer details
├── edit_product.php         # Edit product details
├── edit_sales.php           # Edit sales records
│
├── group.php                # User groups or categories
├── index.php                # Main login page
├── login.php                # Login script
├── logout.php               # Logout script
│
├── monthly_sales.php        # Monthly sales report
├── product.php              # View products list
├── profile.php              # User profile
├── sales.php                # Sales history
├── sales_report_process.php # Sales report generation logic
├── stock.php                # Stock availability and reports
├── users.php                # Manage user accounts
│
├── EXTRAFILE                # Placeholder or additional notes
├── LICENSE                  # MIT License
└── README.md                # Documentation
```

---

## Technology Stack

- **Backend**: PHP (Core PHP, procedural style)
- **Frontend**: HTML5, CSS3, JavaScript
- **Database**: MySQL
- **Server**: Apache (XAMPP, WAMP, or LAMP)

---

## Installation Guide

Follow these steps to set up the project on your local machine:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/kashifzamansoft/Inventory_System.git
   ```

2. **Move Project Files**
   - Copy the project folder into your server directory:
     - For XAMPP: `htdocs`
     - For WAMP: `www`
     - For LAMP: `/var/www/html`

3. **Create Database**
   - Open **phpMyAdmin**
   - Create a new database (example: `inventory_system`)
   - Import the provided SQL file (if included inside the project)

4. **Configure Database Connection**
   - Open `includes/config.php`
   - Update the database credentials:
     ```php
     $host = "localhost";
     $user = "root"; // default for XAMPP/WAMP
     $pass = "";     // default empty
     $db   = "inventory_system";
     ```

5. **Run the Project**
   - Start Apache and MySQL in XAMPP/WAMP
   - Visit `http://localhost/Inventory_System/` in your browser

---

## Default Login Credentials

You can find login details in the file:  
`LOGIN DETAILS & PROJECT INFO.txt`

(Default credentials may be something like: `admin/admin123`)

---

## Usage

- **Admin Panel**: Manage categories, products, suppliers, users, and sales.
- **Reports Section**: Generate detailed sales and stock reports.
- **User Accounts**: Add staff with different levels of access.

---

## License

This project is licensed under the **MIT License** – see the [LICENSE](./LICENSE) file for details.

---

## Contribution

Contributions are welcome. To contribute:

1. Fork the repository
2. Create a new branch (`feature/your-feature`)
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

---

## Author

**Kashif Zaman**  
Copyright © 2025  
