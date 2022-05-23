# My submission for Shopify's backend challenge for Fall.
It uses Express, Node.js and MySQL for the backend and React for the frontend. 

<img src="https://i.imgur.com/PgzqHk0.gif)" width="1440" height="1920" />

For items and data to persist, you must use the MySQL database.
Connecting that database to the project is as simple as editing the values in lines 14-17 of /server/index.js with your respective database information.

Here is the relevant code for that:

const db = mysql.createConnection({
    user: 'root',
    host: 'localhost',
    password: 'password',
    database: 'itemSystem'
});
