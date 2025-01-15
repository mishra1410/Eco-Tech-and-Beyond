## Eco-Tech-and-Beyond
## Blog API Project

### Project Overview

The Blog API project demonstrates a fully functional backend API for managing a blog. The API supports CRUD operations (Create, Read, Update, Delete) for blog posts and integrates seamlessly with a basic front-end interface. This project is designed to showcase RESTful API development using Node.js and Express, emphasizing efficient routing and middleware usage.

### Features

- **GET**: Retrieve all blog posts or a specific post by ID.
- **POST**: Create new blog posts with title, content, author, and creation date.
- **PATCH**: Update specific fields of an existing post.
- **DELETE**: Remove blog posts by ID.
- Middleware for parsing request bodies and handling errors.
- Basic front-end integration for real-time display and interaction.

### Tech Stack

- **Backend**: Node.js, Express
- **Middleware**: Body-parser
- **Front-end (Demo)**: Basic HTML, CSS, EJS
- **Tools**: Nodemon, Git, VS Code

### Installation and Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/blog-api-project.git
   cd blog-api-project
2. **Install Dependencies:**
    ```bash
    npm i
4. **Run the Servers:**
   ```bash
   node server.js
6. **Start the API server:**
   ``` bash
   nodemon server.js

7. **Access the Application:**

API: http://localhost:4000

Front-end: http://localhost:3000

## Routes

- **GET** `/posts`: Fetch all posts.
- **GET** `/posts/:id`: Fetch a specific post by ID.
- **POST** `/posts`: Create a new post.
- **PATCH** `/posts/:id`: Update a post by ID.
- **DELETE** `/posts/:id`: Delete a post by ID.

the website should look like this:
![image](https://github.com/user-attachments/assets/b82ba76a-3ddf-49e8-bd0d-334b2c1c8ee1)

the newpost page:
![image](https://github.com/user-attachments/assets/e99f6320-67b8-4ce7-ac04-5757b16033d8)

the edit-post page:
![image](https://github.com/user-attachments/assets/5204d488-27ab-46f4-ba4c-133dc3b3c085)


