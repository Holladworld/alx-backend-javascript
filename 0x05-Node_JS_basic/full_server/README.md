Set up a complex HTTP server using Express

Create a directory structure for the server under full_server with controllers and routes directories. In full_server/utils.js, implement a function named readDatabase to read the database asynchronously and return a promise. In full_server/controllers/AppController.js, define a class AppController with a static method getHomepage to return a 200 status and the message 'Hello Holberton School!'. In full_server/controllers/StudentsController.js, create a class StudentsController with static methods getAllStudents and getAllStudentsByMajor to handle different endpoints related to students. Implement routing in full_server/routes/index.js to link the routes /, /students, and /students/:major to the respective controllers. Write a small Express server in full_server/server.js to utilize the created routes and listen on port 1245.

Changes:
- Organize the server structure into directories controllers and routes.
- Implement functionality to read the database asynchronously in full_server/utils.js.
- Define AppController and StudentsController with static methods to handle different endpoints.
- Set up routing in full_server/routes/index.js to link routes to the controllers.
- Create a small Express server in full_server/server.js to utilize the routes and listen on port 1245.

Start the server with 'npm run dev' and test the endpoints using curl commands in terminal.


