const express = require('express');
const app = express();
const PORT = 3000;

app.get('/', (req, res) => {
  res.send('<h1>Microportal is Running on AKS!</h1>');
});

app.listen(PORT, () => {
  console.log(`Microportal server started on port ${PORT}`);
});
