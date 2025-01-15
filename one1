<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>University Details</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
    }
    h1 {
      text-align: center;
      color: #444;
    }
    .container {
      max-width: 600px;
      margin: 0 auto;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    label {
      display: block;
      margin-bottom: 10px;
      font-weight: bold;
    }
    input[type="text"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      display: block;
      width: 100%;
      padding: 10px;
      background-color: #5cb85c;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover {
      background-color: #4cae4c;
    }
    .details {
      margin-top: 20px;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 5px;
      background-color: #f9f9f9;
    }
    .details h3 {
      margin: 0;
    }
  </style>
</head>
<body>
  <h1>University Details Finder</h1>
  <div class="container">
    <label for="universityName">Enter University Name:</label>
    <input type="text" id="universityName" placeholder="e.g., Harvard University">
    <button onclick="getUniversityDetails()">Get Details</button>

    <div id="details" class="details" style="display: none;">
      <h3>University Details</h3>
      <p id="universityInfo"></p>
    </div>
  </div>

  <script>
    const universityData = {
      "Harvard University": "Located in Cambridge, Massachusetts, Harvard is one of the most prestigious universities in the world, known for its law, business, and medical programs.",
      "Stanford University": "Located in Stanford, California, Stanford is renowned for its engineering, business, and computer science programs.",
      "University of Oxford": "Located in Oxford, England, Oxford is one of the oldest universities in the world, famous for its humanities and sciences.",
      "MIT": "Located in Cambridge, Massachusetts, MIT is world-famous for its cutting-edge research and education in engineering and technology."
    };

    function getUniversityDetails() {
      const universityName = document.getElementById('universityName').value;
      const detailsDiv = document.getElementById('details');
      const infoParagraph = document.getElementById('universityInfo');

      if (universityName in universityData) {
        infoParagraph.textContent = universityData[universityName];
        detailsDiv.style.display = 'block';
      } else {
        infoParagraph.textContent = "Sorry, we couldn't find details for that university. Please try another name.";
        detailsDiv.style.display = 'block';
      }
    }
  </script>
</body>
</html>
