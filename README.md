# nodejs-mysql-crud
Node js application to handle create,read,update and delete functionalities

# Run Project
- start server : node server.js or nodemon server.js
- Run : npm start //for server to autoreload
- Run the app : http://localhost:5000/

# API Endpoints
- GET /api/v1/employees: will give all employees stored in database
- GET /api/v1/employees/<employee_id>: will give a specific employee with employee_id.
- POST /api/v1/employees : create a employee
- PATCH /api/v1/employees/<employee_id>: update a employee partially
- DELETE /api/v1/employees/<employee_id>: delete a employee
- PUT /api/v1/employees/<employee_id>: update a employee completely

