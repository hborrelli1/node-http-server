## Mod 4 Prework Exercise

### Create a Node HTTP Server
For this mod 4 prework exercise the goal was to create a node HTTP server. The server contains both GET and POST commands.

### Installation Instructions
- Clone down repo.
- Run `npm install`
- Run `nodemon server.js`

### Usage Instructions
Use [Postman](https://www.postman.com/) for requests.  
- GET Request:
  - In Postman create a 'GET' request to `http://localhost:3000`
- POST Request:
  - In Postman create a 'POST' request to `http://localhost:3000`
  - Set the header to `{ "Content-Type": "application/json" }`
  - Set the body to `{ "user": "your-name-here", "message": "Your-message-here" }`
