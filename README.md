# Library-Management-System
Library Management System using Angular
Objective:
To create a simple Library Management System (LMS) using Angular where participants
can be assigned books. The system should allow participants to view available books
and borrow or return books.
Requirements:
1. Book Management:
Create a model for Book with fields such as:
id : number
title : string
author : string
availableCopies : number (to track how many copies are available
for borrowing)
Implement functionality to add new books and view available books.
Include validations to ensure a book cannot be added without a title,
author, or initial available copies.
2. Participant Management:
Create a model for Participant with fields such as:
id : number
name : string
email : string
assignedBooks : array of books borrowed
Implement functionality to register participants and view the list of
registered participants.
3. Borrow and Return Books:
Participants should be able to:
Borrow a book if copies are available.
Return a borrowed book.
A participant cannot borrow the same book multiple times unless it has
been returned.
Decrease the number of available copies when a book is borrowed and
increase it when returned.
4. UI/UX:
Use Angular Material for a simple, responsive interface.
Create a clean layout that allows users to easily navigate between
managing books and participants.
Bonus Features:
Implement search functionality for books and participants.
Include a feature to display a history of borrowed and returned books.
Guidelines:
1. Project Structure:



Use components like BookListComponent , ParticipantListComponent , and
BookAssignmentComponent .
Manage the state using services ( LibraryService ).

Proper use of Angular concepts (components, services, data binding).
Functionalities (adding books, assigning books to participants,
borrowing/returning logic).
Bonus features and enhancements.
