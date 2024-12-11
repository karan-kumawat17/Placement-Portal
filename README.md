# Placement Portal

This project is a **Placement Portal** developed using PHP, MySQL, HTML, and CSS. It allows users to browse placement-related data with a functional and easy-to-navigate interface.

## Features
- User-friendly interface for students and administrators.
- Dynamic data retrieval from MySQL database.
- Responsive design using HTML and CSS.

## Prerequisites
To run this project, ensure you have the following installed:

- **XAMPP** (for Apache and MySQL servers)

## How to Run the Project

Follow these steps to set up and run the Placement Portal on your local machine:

1. **Install XAMPP**  
   Download and install XAMPP from [apachefriends.org](https://www.apachefriends.org/).

2. **Place the Project Files**  
   Copy the entire project folder into the `xampp/htdocs/` directory on your system.

3. **Start XAMPP Servers**  
   - Open XAMPP Control Panel.
   - Start the **Apache** server.
   - Start the **MySQL** server.

4. **Import the Database**  
   - Open your web browser and go to `http://localhost/phpmyadmin`.
   - Click on the "Import" tab.
   - Choose the `placement.sql` file provided in the project folder.
   - Click "Go" to import the database structure and data.

5. **Access the Portal**  
   - In your web browser, navigate to: `http://localhost/Placement-Portal/student/index.php`.
   - Browse and interact with the portal as needed.

6. **Explore the Code**  
   To view or modify the code, you can explore the files in the `xampp/htdocs/Placement-Portal/` directory.

## Directory Structure
```
Placement-Portal/
├── student/
│    ├── index.php
│    └── ...
├── admin/
│    ├── ...
├── sql/
├──  ├── placement.sql
└── assets/
     ├── css/
     ├── images/
└── ...
```


## Thank You
Thank you for using the Placement Portal! Feel free to explore and modify the project to suit your needs.
