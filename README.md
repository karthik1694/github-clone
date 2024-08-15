# GitHub-Like Website

This is a web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) that mimics the core features of GitHub. It includes secure user authentication and integration with the GitHub API, allowing users to interact with repositories and manage their profiles.

## Features

- **User Authentication**: Secure login and registration with GitHub OAuth.
- **GitHub API Integration**: Fetch and display user repositories and other data from GitHub.
- **MongoDB Database**: Efficient storage and management of user data and application state.
- **Interactive UI**: A responsive and user-friendly interface built with React.js.

### Prerequisites
Node.js (v14 or higher)
MongoDB (Local or Atlas)

## Installation

Clone the repository:
```bash
git clone https://github.com/karthik1694/github-clone.git)
```
Navigate into the project directory:
```bash
cd github-clone
```
Install the server-side dependencies:
```bash
cd backend
npm install
```
Install the client-side dependencies:
```bash
cd frontend
npm install
```
## Usage
### Run the development server:
```bash
npm start
```
Configure environment variables. Create a .env file in the server directory with the following content:
```bash
MONGO_URI=your_mongodb_connection_string
GITHUB_CLIENT_ID=your_github_client_id
GITHUB_CLIENT_SECRET=your_github_client_secret
```
Start the server:
```bash
npm run dev
```
Start the client
```bash
npm run dev
```
Visit http://localhost:3000 in your browser to explore.

![image](https://github.com/user-attachments/assets/c15240ac-d8ab-4c14-a177-cfa3f56f9203)

