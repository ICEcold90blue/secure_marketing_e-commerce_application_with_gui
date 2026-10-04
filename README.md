# Wizardly - A secure marketing & e-commerce desktop application

This university project teaches us to incoporate relevant programming constructs and techniques such as functions to develop features to host advertisements and promotions for items, generate QR codes for sharing specific items or application in general, display items, checkout features, enable basic user authentication and validation techniques using password hashing, user-friendly navigation and many more [2024].

Original Documentation -> https://github.com/user-attachments/files/33031552/SEMESTER1.WIZARD_REPORT.pdf <br></br>
Grade: 2:1 (Upper Second Class)<br></br>

New Documentation (2026) -> 


# UPDATE
It is 2026 and I want to improve this desktop program for it to become a true secure marketing and e-commerce application, utilising a graphical user interface using Python PyQt5 instead of Tkinter with the SQLite database. The program should follow all old requirements (listed below) along with new ones. For example, users should view item advertisement and promotions displayed within Wizardly, click on it and redirect them to the item which they can potentially add to basket and checkout. Another mandatory features includes generating QR codes for users to scan and access additional information on specific items, tracking interactions with items (number of clicks on a specific item by a certain customer). One new feature is accumulating points when watching videos, clicking promotions or generating QR codes. In the future, I will continously improve this project and many more, practicing my technical coding skills for better software development.


# Requirements:
1. Graphical User Interface: You will need to develop a GUI for the application using Python programming language. The GUI should be user-friendly and visually appealing, with at least the following features to include search bar, promotion categories, and a QR code scanner.

2. User Authentication: The system should have a secure user authentication process, requiring users to provide their login credentials to access their personal information and view promotions. Passwords must be hashed and stored securely in the SQLite database.

3. QR Code Generator and Scanner: The system should be able to generate and scan QR codes and retrieve additional information about promotions, such as product details or discounts. You will need to implement a QR code generator and scanner in the application. QR codes generated should be saved in the local directory.

4. SQLite Database: You will need to create a SQLite database to store promotion and user information. The database should have at least three tables: one for promotions, one for user registration, and another for storing user interactions with promotions.

5. SQL Injection Prevention: The system should be protected against SQL injection attacks. You must ensure that all user inputs are sanitized and validated before being passed to the SQLite database. For this application, any user’s age under 18 is considered as an attack and details should be rejected and not saved in the database.
<br></br>


