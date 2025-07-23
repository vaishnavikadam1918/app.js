# app.js

const express = require('express');
const app = express();
const port = 80; // Use port 80 for web traffic

app.get('/', (req, res) => {
  res.send('WELCOME TO MY WEBSITE!');
});

app.listen(port, () => {
  console.log(`App listening at http://localhost:${port}`);
});
