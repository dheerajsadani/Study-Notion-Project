# StudyNotion

StudyNotion is a full-stack EdTech platform where students can explore and enroll in courses, while instructors can create and manage courses.

## Features

* Student and Instructor accounts
* User authentication with email verification and password recovery
* Browse courses by category
* Course details and enrollment
* Shopping cart and course purchases
* Razorpay payment integration
* Instructor dashboard
* Create, edit and manage courses
* Course sections and video content
* Course progress tracking
* Ratings and reviews
* Profile and account management
* Cloudinary integration for media uploads

## Tech Stack

**Frontend**

* React.js
* Redux Toolkit
* React Router
* Tailwind CSS
* Axios

**Backend**

* Node.js
* Express.js
* REST APIs
* JWT
* Nodemailer

**Database**

* MongoDB
* Mongoose

**Other**

* Cloudinary
* Razorpay

## Project Structure

```text
Study-Notion-Project/
├── public/
├── src/
├── server/
├── package.json
└── tailwind.config.js
```

## Usage

### 1. Clone the repository

```bash
git clone https://github.com/dheerajsadani/Study-Notion-Project.git
cd Study-Notion-Project
```

### 2. Install dependencies

```bash
npm install
cd server
npm install
cd ..
```

### 3. Configure environment variables

Create a `.env` file inside the `server` folder and add the required configuration for MongoDB, Cloudinary, JWT, Razorpay and email services.

### 4. Start the application

Run both frontend and backend together:

```bash
npm run dev
```

Or run them separately:

**Frontend**

```bash
npm start
```

**Backend**

```bash
cd server
npm run dev
```

Frontend runs on `http://localhost:3000` and the backend runs on port `4000` by default.

## Contribution

StudyNotion was developed as a **group project by a team of four members**. The project involved collaborative work across frontend development, backend development, database management, authentication, course management and third-party service integrations.
