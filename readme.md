# Voting Management System Installation Guide

This is a guide on how to install and set up the Voting Management System on XAMPP. Follow the steps below to get started.

## Prerequisites

1. XAMPP: If you don't have XAMPP installed already, download it from the official website and install it on your computer. XAMPP is a cross-platform web server solution that includes Apache, MySQL, and PHP.

2. Text Editor: You'll need a text editor to edit the files. Notepad++ and Sublime Text 3 are some popular options.

## Installation

1. Download the zip file or download WinRAR: You can download the Voting Management System zip file from the official website.

2. Extract the file: After downloading the file, extract it using your preferred archive manager. You should see a folder named "voting management system".

3. Copy the folder: Copy the "votesystem" folder to the root directory where you installed XAMPP. This is usually located in the C:/ drive under the htdocs folder. ( For xample: <b><i> C:\xampp\htdocs </b></i>)

4. Open PHPMyAdmin: Start XAMPP and open the PHPMyAdmin interface by visiting http://localhost/phpmyadmin.

5. Create a new database: In PHPMyAdmin, click on the "Databases" tab and create a new database with the name "votesystem".

6. Import the SQL file: Inside the extracted folder, you should find a folder named "SQL file". Import the "votesystem.sql" file into the "votesystem" database that you created earlier. This will create the necessary tables and data for the system to work.

7. Run the script: Now, you can run the system by visiting http://localhost/voting management system in your web browser. You should see a login screen where you can enter the following credentials:

   - Username: prazol
   - Password: password

<b>That's it! You should now be able to use the Voting Management System.</b>
