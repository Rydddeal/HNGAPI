HNG12API

Develop a public api to retrieve simple points

features 
created an index.js file that handles simple endpoint that
Returns JSON data with email, datetime, and  my GitHub URL."

This API is designed to be publicly accessible, and it can be deployed on platforms like Vercel, Heroku, or run locally.


## Setup Instructions

Node.js and npm (Node Package Manager) should be installed on your local machine. If you don't have these, download and install them from nodejs.org.

-Clone the Repo

-Install Dependencies
npm install express and cors
This will install Express and CORS libraries, which are used to build the API and handle Cross-Origin Resource Sharing.

-Run the Project Locally
Once the dependencies are installed, you can run the project locally by executing:

npm start
This will start the server, and it will be running at http://localhost:3000/.

(Optional) Run with nodemon (for development)
If you want to automatically restart the server whenever you make changes to the code, you can install nodemon and run the project with it:

Install nodemon as a development dependency:


npm install --save-dev nodemon
Update your package.json to add a "dev" script under "scripts":

"scripts": {
  "start": "node index.js",
  "dev": "nodemon index.js"
}
Now, you can run the project with:
npm run dev

Access the API
Once the server is running, you can access the API by navigating to http://localhost:3000/ in your browser or via tools like Postman

API Documentation
Endpoint URL
GET http://localhost:3000/
This is the root endpoint that returns the required information in JSON format.
Request Format
Method: GET
URL: http://localhost:3000/ 
Response Format
The API responds with a JSON object containing the following info in json format

{
  "email": "bayq80@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/Rydddeal/HNG12API.git"
}








