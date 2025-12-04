# CineMovie-TecStar
CineMovie TecStar:
Project Description:
CineMovie is a basic application for managing a movie theater, specifically focused on ticket and concession sales. The goal is to create a simple and efficient tool for box office personnel to manage the sale of movie tickets and concession products. The application provides a clear and functional user interface, allowing staff to securely log in and manage the sales of tickets and concession orders, generating a summary of the total purchase.

Screens:

Window 1: Login
The system has a login screen. This screen includes User and Password text fields where you must enter your pre-established username and password. It also has buttons to proceed to the next window or exit the program. The login uses pre-established data (for example, user: cajero (cashier) or the assigned person's name, and password: 12345). A database is not required for implementation. Upon entering the correct username and password and clicking the "Next" button, the second window will open.

Window 2: Box Office
The second window features a design that displays the schedule for 4 movies (e.g., Coraline, The Conjuring 4, The Leopard...). Each of these movies has 3 available showtimes to select from. The theater room number is pre-established based on the movie you select. It also includes a counter box where you enter the quantity of Adult tickets ($90 price) and Minor tickets ($80 price) you wish to purchase. Upon finalizing the ticket selection, the system displays a summary of the tickets acquired, the movie, the room number, the showtime, and calculates the Box Office subtotal. It then asks if the customer accepts the purchase, with a "Yes" click leading to the third window.

Window 3: Concessions (Dulcería)
The third window shows the employee a new screen for concession sales. It displays the available combos with their price, contents, and related images: básico (basic), familiar (family), pareja (couple), and yumi. The system also allows the sale of individual products, using counters to manage the quantity of each selected item. Upon finalizing the selection of combos or individual treats, the system displays a summary of the concession purchase and asks if the customer wishes to proceed with the purchase, with a "Yes" click leading to the fourth and final window.

Window 4: Purchase and Cost
The fourth window includes a purchase summary: the total from the "Box Office" section with the selected movie, the purchases from the "Concessions" section, the selected date and time, the subtotal for each, and the Grand Total, which is the sum of the box office and concession purchases.

Technologies Used:
The application was designed using the following technologies:
wxGlade: Used for creating the graphical interface design.
Visual Studio Code: Used to view the code and execute it with Python libraries.
Python: Its libraries were used to make the application functional.

Team Members:
Campos Emili Yoana Role: Product Owner (PO)
Rosas Yaretzi Llamileh Role: Scrum Master (SM)
Morales Adilene Role: UI/UX Designer
Valle Mariana Joseline Role: Analyst

Instructions to Run the Project:
To run the project, you must have Python (the version your PC accepts), Visual Studio Code, and wxGlade installed. Once installed, follow these steps:
Step 1: Open Visual Studio Code.
Step 2: Open your project by clicking on File, which will display a list of options.
Step 3: Select the Open Folder option, which will display your list of files.
Step 4: Select the folder where your project is located. After selecting it, press the Select Folder option, which will open your project.
Step 5: In Visual Studio Code, locate and select your project folder (named as you saved it). Your code will then appear, ready to be executed.
Step 6: Locate and select the Run Python file button (shaped like a small triangle) in the upper right corner. Your project will immediately execute.
Step 7: On the Login screen, enter your correct username and password, click "Next," and it will take you to the next window.
Step 8: On the Box Office window, select the quantity of adult and minor tickets.
Step 9: Select the movie and the showtime, click "Next," and confirm the purchase of tickets at the box office.
Step 10: On the Concessions window, select the combos or individual products for purchase, click "Next," and confirm the purchase.
Step 11: The Ticket window will display your purchase summary. Click "Accept," and the program will terminate.


