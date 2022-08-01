# CRUD Inventory Tracking System
It uses Express, Node.js and MySQL for the backend and React for the frontend! :scream::scream:

<img src="https://i.imgur.com/PgzqHk0.gif" width="600" height="800" />

## Installation
1. Clone the repository locally.
```
git clone https://github.com/abenav4/Shopify-Backend-Challenge-2022.git
```
2. To install relevant dependencies (in both /server/ and /client/)
```
npm install
```
3. To run node server (within /server/ in console:

```
node index.js
```
4. To start application (in /client/)
```
npm start
```
5. Open http://localhost:3000 to view the app in your browser.


For items and data to persist, you must use the MySQL database.
Connecting that database to the project is as simple as editing the values in lines 14-17 of /server/index.js with your respective database information.

Here is the relevant code for that:
```
const db = mysql.createConnection({
    user: 'root',
    host: 'localhost',
    password: 'password',
    database: 'itemSystem'
});
```
## Thank you for checking it out! :metal:&#127999;
