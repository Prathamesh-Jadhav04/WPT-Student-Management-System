# Student Management System

**Assignment 1 — Web Programming Technologies (WPT)**

A Node.js-based Student Management System that reads, validates, processes, and updates student records stored in a JSON file. The project demonstrates JavaScript ES Modules, array operations, file handling, data validation, and error handling.

## Features

- Display all student records.
- Search for a student by ID.
- Filter students by department and semester.
- Calculate average marks across subjects.
- Identify students with attendance below 75%.
- Find students scoring above 80 in every subject.
- Sort students by average marks in descending order.
- Add new student records with duplicate-ID protection.
- Update existing student information.
- Delete student records.
- Validate student data before saving.
- Read and write JSON files with error handling.
- Save updates using a temporary file and rename operation.

## Technology Stack

- **Runtime:** Node.js
- **Language:** JavaScript (ES Modules)
- **Data Storage:** JSON
- **File Handling:** Node.js File System Promises API
- **Code Quality:** ESLint

## Project Structure

```text
student-management/
├── data/
│   └── students.json
├── src/
│   ├── main.js
│   ├── studentService.js
│   └── validation.js
├── eslint.config.js
├── package.json
└── README.md
```

## Prerequisites

- Node.js installed on your system.
- npm (included with Node.js).
- A terminal or Visual Studio Code.

Check the installed versions:

```bash
node -v
npm -v
```

## Installation and Execution

1. Open a terminal in the `student-management` directory.
2. Install the project dependencies:

   ```bash
   npm install
   ```

3. Run the application:

   ```bash
   npm start
   ```

4. To check code quality, run:

   ```bash
   npm run lint
   ```

5. To run the available automated tests:

   ```bash
   npm test
   ```

## Data Storage

Student records are stored in `data/students.json`. The application validates the loaded records before processing them and checks updated records before saving.

The data file must contain valid JSON and follow the schema defined in `src/validation.js`.

## Implementation Highlights

- Uses ES Module imports and exports.
- Uses array methods such as `filter()`, `find()`, `map()`, `reduce()`, and `sort()`.
- Uses asynchronous file operations with `async/await`.
- Handles invalid JSON, missing files, invalid records, and duplicate student IDs.
- Uses a temporary file followed by a rename operation when saving student data.

## Learning Outcomes

This project demonstrates practical knowledge of JavaScript, Node.js, JSON data management, modular programming, array manipulation, validation, asynchronous programming, and error handling.

## Author

**Name:** Prathamesh Jadhav
**Roll Number:** 16
**Course:** Web Programming Technologies (WPT)

---

*Developed as part of the Web Programming Technologies assignment.*
