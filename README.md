# Pineapple-Inc

Pineapple Inc. - Your Next PC Starts Here!


Overview
Pineapple Inc. is an online platform designed for computer enthusiasts to easily browse, select, and purchase pre-built desktop computers. Our website offers a user-friendly interface to explore a diverse catalog of systems, view detailed specifications, manage a shopping cart, and securely complete orders. We also provide user account management and information about our team and mission.

Key Features
- Extensive Product Catalog: Browse a wide selection of pre-built desktop computers.
- Detailed Product Information: View comprehensive specifications and pricing for each product.
- Easy Online Ordering: Add products to your cart and complete the checkout process.
- View and Manage Cart: Review and modify your shopping cart before ordering.
- Secure Checkout: A straightforward process to finalize your purchase.
- User Account Management: Create and manage your account for order history and more.
- Informative "About Us" Section: Learn about the team behind Pineapple Inc.
- Comprehensive FAQs: Find answers to common questions.
- Special Offers: Discover discounted products.
- User-Friendly Search: Quickly find specific computers.

System Requirements
- A modern web browser (e.g., Chrome, Firefox, Safari, Edge).
- A stable internet connection.
- For local development: A web server environment with PHP (e.g., XAMPP, MAMP, WAMP).


Database Configuration:
- Navigate to the includes directory and open database.php.
- Update the database connection details (hostname, username, password, database name) according to your local setup. You might need to create the database in your MySQL server.
- Access the website: Open your web browser and navigate to http://localhost/[your_project_folder_name]/www/ or the appropriate URL for your local server setup.

Usage
- Homepage: Displays featured products and introductory information.
- Products: Browse the full catalog of available computers.
- Product Details: Click on a product to view detailed specifications and pricing.
- Cart: Review and manage items added to your shopping cart.
- Login/Sign up: Create a new account or log in to an existing one.
- About: Learn more about the Pineapple Inc. team.
- FAQs: Find answers to frequently asked questions.
- Specials: View discounted products and special offers.

Project Structure

Pineapple-Inc/
├── admin/
│   ├── includes/
│   │   ├── database.php
│   │   ├── footer.php
│   │   ├── functions.php
│   │   └── header.php
│   ├── add_products.php
│   ├── edit_products.php
│   ├── index.php
│   ├── login.php
│   ├── orders.php
│   └── products.php
├── includes/
│   ├── database.php
│   ├── footer.php
│   ├── functions.php
│   └── header.php
├── www/
│   ├── about.php
│   ├── account.php
│   ├── add_cart.php
│   ├── cart.php
│   ├── create.php
│   ├── faqs.php
│   ├── index.php
│   ├── login.php
│   ├── productdetails.php
│   ├── products.php
│   ├── searchresults.php
│   └── specials.php
├── style.css
└── newcss.css
- admin/: Contains files for the administrative backend to manage products and orders.
- includes/ (root and admin): Contains reusable PHP scripts for database interaction, header, footer, and common functions.
- www/: Contains the public-facing website files.
- style.css and newcss.css: Stylesheet files for the website's appearance.

Screenshots


Author
Mario Garcilazo
