const fs = require('fs');

// Read the file asynchronously
fs.readFile('image-processing.js', 'utf8', (err, data) => {
  if (err) {
    console.error('Error reading file:', err);
    return;
  }

  // Log the content of the file
  console.log(data);
});
