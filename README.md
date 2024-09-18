Healthcare Service API
A simple API built using Node.js, Express, and MongoDB to manage healthcare services. It provides endpoints to add, retrieve, update, and delete services.
-------------------------------------------------------------------------------------------------
Features
Add new healthcare services
Retrieve a list of services
Update existing services
Delete services
-----------------------------------------------------------------------------------------


Technologies Used
Node.js
Express.js
MongoDB (with Mongoose)
dotenv for environment management
--------------------------------------------------------------------------------

API Endpoints

1. Get all services
Method: GET
Endpoint:  /api/services/ getAllServices

2. Get a service by ID
Method: GET
Endpoint: /api/services/ getAllServices/:id

3. Add a new service
Method: POST
Endpoint: /api/services/ addService

4. Update a service
Method: PUT
Endpoint: /api/services/ updateService/:id

6. Delete a service
Method: DELETE
Endpoint: /api/services/ deleteService/:id
---------------------------------------------------------------------------------
