# Book-Review-Management-System
Objective
Build a simple application that connects:
Frontend + Backend + MySQL
The application should allow users to add, view, update, and delete book reviews.Frontend
Create a form with:
Book Name
Author
Reviewer Name
Rating (1–5)
Review
Display all reviews in a table.
Implement:
Add Review
View Reviews
Edit Review
Delete Review
Use JavaScript fetch() to communicate with the backend APIs.Backend
Create the following REST APIs:
Method Endpoint
Purpose
POST /reviews --> Add a review
GET /reviews --> Get all reviews
GET /reviews/{id} ---> Get review by ID
PUT /reviews/{id} --> Update a review
DELETE /reviews/{id} ---> Delete a reviewDatabase

Create a MySQL database and a book_reviews table.
Apply appropriate constraints, including:
Primary Key
NOT NULL
CHECK
