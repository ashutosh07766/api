Simple Express API
This is a very simple API built with Express.js to store and retrieve data.

Features
Store Data: Store data by passing it as a URL parameter.
Retrieve Data: Retrieve all stored data .

Installation:
1.Clone the repositary
git clone https://github.com/yourusername/simple-express-api.git

2.Change the directory:
cd api

3:Install dependencies:
npm install

4.Run the server:
node app.js

5.Store data:
curl -X POST http://localhost:3000/storing/yourData

6.Retrieve data:
curl http://localhost:3000/data
