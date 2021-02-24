# Project Abstract:
![diagram](https://user-images.githubusercontent.com/70305543/108156565-e693d300-70ae-11eb-94fc-6bbf9a57a80f.png)


The library management system is an open-source project and is designed based on the characteristics of JAVA object-oriented programming. The library management system can complete the basic functions of borrowing and returning books. There are four important classes in this project:

Borrower: The main functions are to search for books by subject and author, and check the current borrowing list
Checkout Clerk: Renew the borrower, update the borrower information, add new borrowers, sign for borrowed books, etc., check-in (waiting for implement), check-out (waiting for implement)
Librarian: classify books (waiting for implement), with the function of borrower and Checkout Clerk, check-in (waiting for implement), check-out (waiting for implement)
Administrator: Staff management, check book usage records, check books in the library, fine management (waiting for implement)

By connecting to the Java DB (Derby) Database of NetBeans to obtain the database for book management. (waiting for implement)

# Project Relevance:
The library management system is a beginner friendly open-source project, which is very suitable for beginners who try to contribute to an open-source project for the first time. The learning goals of this project include understanding how to access the database, implementing new functions on the basic borrowing, and returning functions using Object Oriented Design.

# Proposed Contribution:
Conceive new functions for each class according to the existing logical architecture. For example, the introduction of check-in, check-out to the employee's class to record working time as a performance appraisal. Provides e-book rental services for borrowers and can send connections to the borrowers’ electronic devices.
In addition, try to establish an employee management system, implement meeting functions, and weekly schedules. Using the database to provide a more complete user experience for borrowers, including providing a wish list, a recommended list, and a reminder function for returning books.
# How to Run
1- Install these:

Java SE Development Kit 8 (JDK 8)
After installing JDK 8, install NetBeans IDE

2- Open NetBeans IDE. Click on File -> Open Project and browse to the downloaded folder named "Project" and select it. It will load the NetBeans project.

3- Now everything is setup except the Java DB (Derby) Database of NetBeans. So, follow these steps to setup the database:

Step 1: In the Netbeans Window, there is a tab named "Services" on the left. Select it. Then right click on JavaDB > Properties and change database location to "Database" folder downloaded with this repository (its placed besides the "Project" folder).

Step 2: After that a database named LMS will show up under JavaDB tab. Now Right Click Databases > New Connection and select Java DB Network and click Next.


Step 3: Provide the following database crendentials in the next popup and click Next.

Host: localhost
Port: 1527
Database: LMS
User Name: haris
Password: 123
step3

Step 4: Now just click Next for the rest of the windows. After all this the database connection is made. Make sure that you connect with the database before running the project by right clicking on the connection and selecting connect. Now you are ready to run the project!



# URL:
Java SE Development Kit 8 (JDK 8)
NetBeans IDE
Java DB (Derby) Database of NetBeans
https://github.com/OSSpk/Library-Management-System-JAVA.git
