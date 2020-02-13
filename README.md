# FBLA Community Service Application
This repository is to host my 2019-2020 school year FBLA Community Service Tracker App.
In here you will find all the files necessary to run the application such as the DLLs are in this repository.
Removing or altering any of the files in this repository may cause the app to stop fuctioning or malfunction.

# Database
This app uses a relational database which operates on SQLite. The reason this app operates on SQLite and not SQL, is that on my small budget, I can't afford to buy a server and host an SQL Database on it. SQL only works with a server, where as SQLite is a lightweight version of SQL that works as package plugin to Visual Studio so it runs on a DLL and a local database file.

# Usage
To use the app, you simply open the app, and click the button according to what you're trying to log in as, wether it be admin or student. From there you type in your log in information and it will take you to the appropriate screen.

The default login information is as follows:

Admin
Username: admin
Password: admin

Student
Username: eddyj
Password: password

When you log in as a student, you get taken to the "Student Information" screen where the student can see their own information.
When you log in as an admin, you get taken to the "Admin Panel" screen where you have elevated priviledges and you have access to adding users, seeing a list of all students as well as double clicking and accessing every students "Student Information" screen. As an admin, you can also generate reports.

# Generating Reports
Admins can generate a report of all the student's current hours. This report will be generated as a pdf and saved on the computer as "[month]-[day]-[year]-FBLA-Hours-Report.
