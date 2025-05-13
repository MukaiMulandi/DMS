Library Management System
Description
This project implements a Library Management System using MySQL. It allows managing authors, books, library members, and book loans. The system supports relationships such as one-to-many between authors and books, and many-to-many between books and members.

Features:
Authors Table: Stores information about authors.
Books Table: Stores information about books, including their authors.
Members Table: Stores information about library members.
BookLoans Table: Tracks which books are borrowed by which members.

Database Structure
The database consists of four main tables:
Authors - Contains information about authors.
Books - Contains information about books and their corresponding authors.
Members - Contains information about library members.
BookLoans - Records which books are borrowed by which members.

Relationships:
One-to-Many: Between Authors and Books (An author can write multiple books).
Many-to-Many: Between Books and Members (A book can be borrowed by many members, and a member can borrow many books).
