# 🗳️ Polling API Project

## 🚀 Overview
A backend API project to create, vote, and manage polls using Node.js, Express, and MongoDB. This project provides a RESTful API for creating polls, adding options, voting on options, viewing poll details, and deleting polls or options, with proper validation to ensure data integrity.

---

## 📌 Features
- **Create Polls**: Add new polls with a title and multiple options.
- **Vote on Options**: Cast votes on poll options with a single API call.
- **View Polls**: Retrieve poll details along with options and vote counts.
- **Delete Polls/Options**: Remove polls or options (with restrictions if votes exist).
- **RESTful API**: Follows REST principles for CRUD operations.
- **Error Handling**: Proper validation and error messages for invalid requests.

---

## 🛠️ Tech Stack
- **Node.js**: JavaScript runtime for building the backend.
- **Express.js**: Web framework for creating RESTful APIs.
- **MongoDB**: NoSQL database for storing poll data.
- **Mongoose**: ODM library for MongoDB to manage schemas and models.
- **Postman**: Tool for testing API endpoints.
- **dotenv**: For managing environment variables.
## 📂 Project Structure

---

## ⚙️ Setup Instructions
Follow these steps to run the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ashutoshkri/Polling_API.git
   Polling_API/
├── controllers/         # Logic for handling API requests
│   ├── optionsController.js
│   └── questionsController.js
├── models/              # Mongoose schemas for data models
│   ├── Option.js
│   └── Question.js
├── routes/              # API route definitions
│   ├── options.js
│   └── questions.js
├── .env.example         # Example environment variables
├── .gitignore           # Files/folders to ignore in Git
├── index.js             # Main server file
├── package-lock.json    # Dependency lock file
├── package.json         # Project metadata and dependencies
└── README.md            # Project documentation
