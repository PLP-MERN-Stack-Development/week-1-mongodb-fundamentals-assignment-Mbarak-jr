[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19667370&assignment_repo_type=AssignmentRepo)

# MongoDB Fundamentals Assignment

This assignment focuses on learning MongoDB fundamentals including setup, CRUD operations, advanced queries, aggregation pipelines, and indexing.

---

## Assignment Overview

You will:
1. Set up a MongoDB database
2. Perform basic CRUD operations
3. Write advanced queries with filtering, projection, and sorting
4. Create aggregation pipelines for data analysis
5. Implement indexing for performance optimization

---

## Getting Started

1. Accept the GitHub Classroom assignment invitation
2. Clone your personal repository that was created by GitHub Classroom
3. Install MongoDB locally or set up a MongoDB Atlas account
4. Run the provided `insert_books.js` script to populate your database
5. Complete the tasks in the assignment document

---

## Files Included

- `Week1-Assignment.md`: Detailed assignment instructions
- `insert_books.js`: Script to populate your MongoDB database with sample book data
- `queries.js`: Contains all MongoDB queries for CRUD, advanced queries, aggregation, and indexing

---

## My Setup Instructions

- **MongoDB version**: `6.0.x` (Local installation)
- **Mongo Shell**: `mongosh`
- **Database Used**: `plp_bookstore`
- **Collection Used**: `books`
- Populated the database using `insert_books.js` via `mongosh`
- Performed all query tasks using `queries.js` in the shell

### Running Scripts

```bash
mongosh
use plp_bookstore
load("insert_books.js")
load("queries.js")

Requirements
Node.js (v18 or higher)

MongoDB (local installation or Atlas account)

MongoDB Shell (mongosh) or MongoDB Compass

Screenshot
📸 Screenshot of MongoDB database (Both Compass and Termnal output)


Submission Checklist ✅
 Completed all tasks in the assignment

 Added queries.js with all required queries

 Uploaded screenshot of MongoDB database

 Updated README.md with setup and usage instructions

Resources
MongoDB Documentation

MongoDB University

MongoDB Node.js Driver