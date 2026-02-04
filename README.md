# adv-fullstack-268

Repository for Fullstack Development code examples using Node.js and Express.

## Project Structure

This project contains several examples of RESTful APIs:

- **src/index.js**: A basic Express server setup.
- **src/CRUDBookNoDB.js**: A Book CRUD API implementation using in-memory data storage (array).
- **src/SequlizeSQLiteCRUDBook.js**: A Book CRUD API implementation using Sequelize ORM with SQLite database.

## Getting Started

### Prerequisites

- Node.js installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PatcharaphonKoosomsarp/adv-fullstack-268.git
   ```
2. Navigate to the project directory:
   ```bash
   cd adv-fullstack-268
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
   *Note: For the SQLite example, you may need to install additional dependencies if they are not already included:*
   ```bash
   npm install sequelize sqlite3
   ```

### Running the Project

To run the main server (Basic Hello World):
```bash
npm start
```
Or for development mode (with Nodemon):
```bash
npm run dev
```

To run the In-Memory CRUD example:
```bash
node src/CRUDBookNoDB.js
```

To run the Sequelize + SQLite CRUD example:
```bash
node src/SequlizeSQLiteCRUDBook.js
```

## Features

- RESTful API endpoints for managing Books.
- Examples of CRUD operations (Create, Read, Update, Delete).
- Comparison between in-memory storage and database persistence (SQLite).
