#Simple Express API

This is a very simple API built with Express.js to store and retrieve data.

Features
Store Data: Store data by passing it as a URL parameter.
Retrieve Data: Retrieve all stored data .

Installation:
1.Clone the repositary
git clone https://github.com/yourusername/simple-express-api.git

2:Install dependencies:
npm install

3.Run the server:
node app.js or npm start

4.Store data:
curl -X POST http://localhost:3000/storing/yourData

5.Retrieve data:
curl http://localhost:3000/data
