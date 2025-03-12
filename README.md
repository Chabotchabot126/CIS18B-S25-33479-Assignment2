Library Management System
This is a Java application that simulates a simple library management system. It demonstrates the use of object-oriented programming (OOP) principles, including classes, inheritance, polymorphism, encapsulation, and design patterns like Singleton and Factory.

Requirements
Java Development Kit (JDK) installed on your system.

How to Compile and Run the Program
1. Clone the Repository
Clone this repository to your local machine using the following command:

bash
Copy
git clone https://github.com/<your-username>/CIS18B-S25-33479-Assignment2.git
2. Navigate to the Project Directory
Change to the project directory:

bash
Copy
cd CIS18B-S25-33479-Assignment2
3. Compile the Java Files
Compile all the Java files in the project:

bash
Copy
javac *.java
4. Run the Program
Run the LibraryTest class, which contains the main method:

bash
Copy
java LibraryTest
How to Use the Program
The program will display a list of available items in the library.

You will be prompted to borrow a book by entering its title.

After borrowing, the program will display the updated list of available items.

You can return a book by entering its title when prompted.

The program will confirm the return and display the updated list of available items.

Example Output
Copy
Available Items:
The Great Gatsby (1925)
1984 (1949)
National Geographic (2023)

Enter the title of the book you want to borrow:
1984
1984 has been borrowed by John Doe

Available Items after borrowing:
The Great Gatsby (1925)
National Geographic (2023)

Enter the title of the book you want to return:
1984
1984 has been returned by John Doe

Available Items after returning:
The Great Gatsby (1925)
1984 (1949)
National Geographic (2023)
Files in the Project
Item.java: Base class for library items.

Book.java: Subclass for books, implements the IBorrowable interface.

Magazine.java: Subclass for magazines.

IBorrowable.java: Interface for borrowable items.

Library.java: Singleton class to manage the library collection.

LibraryItemFactory.java: Factory class for creating library items.

LibraryTest.java: Main class to test the library system.

Troubleshooting
Compilation Errors: Ensure all .java files are in the same directory and there are no typos in the code.

Runtime Errors: Verify that you are entering valid titles when prompted.

Author
Enzo fiore

