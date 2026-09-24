# Library Book Tracker

## Project Description

Library Book Tracker is a dynamic web application for managing books and tracking their availability.

The application allows users to:
- View available books
- Add new books
- Search books by title or author
- Issue books
- Return books
- View book statistics

## Technologies Used

- Node.js
- Express.js
- HTML
- CSS
- JavaScript
- Node.js built-in test runner
- ESLint
- Docker
- GitHub Actions
- Render

## Project Structure

```text
Library-Book-Tracker/
├── .github/
│   └── workflows/
│       └── ci-cd.yml
├── public/
│   └── index.html
├── test/
│   └── app.test.js
├── .gitignore
├── app.js
├── server.js
├── package.json
├── package-lock.json
├── eslint.config.js
├── Dockerfile
└── README.md


This helps someone understand where the important files are.

---

# Step 6 — Add local setup instructions

Add:

```markdown
## How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/sudiptaa11/library-book-tracker.git
cd library-book-tracker


---

# Step 7 — Add testing instructions

Add:

```markdown
## Testing

Run the automated tests using:

```bash
npm test


---

# Step 8 — Add API endpoints

Your README should document the API routes you've created.

Add:

```markdown
## API Endpoints

| Method | Route | Description |
|---|---|---|
| GET | `/` | Displays the Library Book Tracker |
| GET | `/api/books` | Returns all books |
| POST | `/api/books` | Adds a new book |
| POST | `/api/books/:id/issue` | Issues a book |
| POST | `/api/books/:id/return` | Returns a book |
| GET | `/health` | Returns application health status |

## CI/CD Pipeline

The project uses GitHub Actions for continuous integration and deployment.

The pipeline follows:

```text
Git Push
   ↓
Lint
   ↓
Test
   ↓
Docker Build
   ↓
Deploy
   ↓
Live Site


This matches the required pipeline flow in your assignment. :contentReference[oaicite:1]{index=1}

---

# Step 10 — Add Docker instructions

Add:

```markdown
## Docker

Build the Docker image:

```bash
docker build -t library-book-tracker .


---

# Step 11 — Add project features

Finally, add:

```markdown
## Features

- Add books with validation
- Search books by title or author
- Track available copies
- Issue books
- Return books
- View book statistics
- Health check endpoint
- Automated tests
- ESLint validation
- Docker containerization
- GitHub Actions CI/CD

## CI/CD Pipeline

Git push
   ↓
Lint + Test
   ↓
Docker Build
   ↓
Deploy
   ↓
Render
   ↓
Live Application

Tests and linting run automatically.
Docker is built only after successful tests.
Deployment occurs only after a successful Docker build.