Here’s how I set up and hosted my TaskMaster project using Render for both the frontend and backend:

1. Backend:

I built the backend with Node.js and Express.js to handle APIs for user authentication (JWT) and task management (CRUD operations).

I connected the backend to a MongoDB Atlas database for storing user and task data.

The backend was deployed on Render as a Web Service, with environment variables like JWT_SECRET and DATABASE_URL configured.



2. Frontend:

I developed the frontend using HTML, CSS, and JavaScript, creating a user-friendly interface.

I used Fetch API for making API calls to the backend.

The frontend was also deployed on Render as a Static Site, ensuring seamless integration with the backend.



3. Integration:

The frontend communicates with the backend lunched but on hosting in render, the backend failed to stand everytime.


[TaskMaster Frontend](https://task-frontend-t25m.onrender.com/)


