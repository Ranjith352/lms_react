## Title

React-Firebase-Course-Website

## Description

Developed a web application for showcasing a list of courses and their details using React. Implemented the course listing page, a course details page, and a student dashboard to display enrolled courses. Implemented course like feature

## Features

- This is a project for a Course Website which allows user to enroll for courses and user can see their enrolled courses in "My Courses" section. 

- Used React.js and Tailwind CSS to create user friendly interface 

- Used Firebase for authentication and fetching & updating courses from the firestore. Also implemented course like feature.

- Used Redux for managing state of application. Implemented redux in user authentication and course enrollment.
 
## View Website

Here is the deployed link to the website: [Deployed Link:](https://react-firebase-course-bice.vercel.app/)

# Installation

To install and run this project locally, add the following commands in your terminal, follow these steps:

1. Clone the repository from GitHub:

```bash
    `git clone https://github.com/omkargade04/react-firebase-course.git`

```

2. Navigate into the project directory:

```bash
   `cd react-firebase-course`
```

## Important

4. Ensure that the version of `Node.js` and `npm` you're using is compatible with the dependencies you're installing. Some dependencies may require specific Node.js versions.

```bash
   `npm install -g npm@latest`
```

5. Install `dependencies` (assuming you have `Node.js` and `npm` installed):

```bash
   `npm install`
```

6. Create a .env file in the directory and add your **firebase** credentials accordingly

7. In your firestore database create two collections named **courses** and **users** and add dummy courses to use locally

8. Run the below command to start the project

```bash
   `npm run dev`
```

8. Open `http://localhost:5173` on your browser to view the project locally
