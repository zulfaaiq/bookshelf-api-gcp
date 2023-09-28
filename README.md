# Bookshelf API - GCP

This project serves as the submission for the "Belajar Membuat Aplikasi Back-End untuk Pemula dengan Google Cloud" class on Dicoding. The API, written in JavaScript, meets the specified criteria for the project submission and has received a 5-star review.

## Project Overview

The project involves the creation of a back-end API for managing a bookshelf. It meets the following criteria:

**Port Configuration:**
- The application is configured to run on port 9000.

**Run Command:**
- The application can be started using the command `npm run start`.

**API Functionality:**
- The API can store books.
- The API can display a list of all books.
- The API can display details of a specific book.
- The API can update book data.
- The API can delete books.

**Query Parameters in GET /books:**
- `?name`: Displays books containing the specified name (case-insensitive).
- `?reading`: Values 0 or 1. If 0, displays books that are not currently being read (reading: false). If 1, displays books that are currently being read (reading: true).
- `?finished`: Values 0 or 1. If 0, displays books that have not been finished (finished: false). If 1, displays books that have been finished (finished: true).

**Coding Standards:**
- ESLint and a selected style guide are used to maintain consistent JavaScript code formatting. Running `npx eslint .` does not produce any errors.
