# Task Management Website 
This website embodies the idea and exemplifies the use of a proper project file system. Furthermore, it implements the standard for project architecture using the MVC model.Also practices the use of the latest technology in database integration and manipulation.

**Table of Contents**
- Introduction
- Features
- Getting Started
  - Prerequisites
  - Installation
- Usage
- Technologies
- Contributing
- License

## Introduction

This web application allows users to manage tasks, including creating, viewing details, and deleting tasks. It's built using MongoDB, Express.js, and Node.js, following the MVC (Model-View-Controller) architectural pattern.

## Features

- View tasks on the home page.
- Create new tasks.
- View detailed information about a task.
- Delete tasks.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:
- Node.js and npm installed on your machine.
- MongoDB set up with a database for storing tasks.

### Installation

1. **Clone the repository:**
git clone [https://github.com/AyhanAllahverdiyev/Tasks_Website.git](https://github.com/AyhanAllahverdiyev/Tasks_Website)


2. **Install dependencies:**


3. **Configure environment variables:**
Create a `.env` file in the root of the project and add the following:
PORT=3000 # Set your desired port number and a connection string for your own mongodb database.(can't provide my own connection string because of obvious reasons and limited database access)
![image](https://github.com/AyhanAllahverdiyev/Tasks_Website/assets/115575562/568b1996-1086-49e7-8912-7551d58b7c7f)

Replace `your-database` with your MongoDB database name.


5. **Start the server:**
npm start


6. **Access the application:**
Open your web browser and go to `http://localhost:3000` (or the port you specified).

## Usage

1. **Home Page:**
Access the home page to view all tasks. You can create a new task by clicking on the "Create Task" button.
![image](https://github.com/AyhanAllahverdiyev/Tasks_Website/assets/115575562/6a81c94f-c3f0-43b4-882d-19b3b0dd5e0e)

2. **Create a Task:**
Click on "Create Task" and fill in the required details. Click "Submit" to create a new task.
![image](https://github.com/AyhanAllahverdiyev/Tasks_Website/assets/115575562/85cd17b7-5ab5-4398-8172-5a8f716d8f76)
![image](https://github.com/AyhanAllahverdiyev/Tasks_Website/assets/115575562/9fb3d926-265f-48b8-980b-1e6708b0084c)

3. **Task Details:**
Click on a task to view its detailed information. From here, you can choose to delete the task.
![image](https://github.com/AyhanAllahverdiyev/Tasks_Website/assets/115575562/36a77352-1e93-44f6-afa8-6815df74607c)

4. **Delete a Task:**
In the task details page, click on "Delete Task" to remove the task.
![image](https://github.com/AyhanAllahverdiyev/Tasks_Website/assets/115575562/feeca5bc-e750-43ae-bcac-3d6c513555c7)
Accessing the MongoDB database and deleting the corresponding document.This was easily done because we used modelling,making the contents of the data highly accessible
![image](https://github.com/AyhanAllahverdiyev/Tasks_Website/assets/115575562/b9d481f7-df90-4627-aca0-b50692c096a7)
5. **About a Tasks**
![image](https://github.com/AyhanAllahverdiyev/Tasks_Website/assets/115575562/52c5a17a-5019-4040-8c5b-7e793e42ace6)

## Technologies

- MongoDB: A NoSQL database used to store task information.
- Express.js: A backend framework for handling HTTP requests, routes, and middleware.
- Node.js: A JavaScript runtime environment used for building server-side applications.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License.

---

