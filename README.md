# allturf-auction-test
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Allturf Auction Test</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 50px;
      background: #f4f4f4;
    }
    form {
      background: white;
      padding: 20px;
      border-radius: 10px;
      max-width: 400px;
      margin: auto;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    }
    input, button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      background: #007BFF;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background: #0056b3;
    }
    .success {
      color: green;
      text-align: center;
    }
    .error {
      color: red;
      text-align: center;
    }
  </style>
</head>
<body>
  <form id="auctionForm">
    <h2>Allturf Auction Test</h2>
    <input type="text" id="name" placeholder="Your Name" required>
    <input type="email" id="email" placeholder="Your Email" required>
    <input type="number" id="quantity" placeholder="Bid Quantity" required min="1">
    <input type="number" id="amount" placeholder="Bid Amount per Item" required min="0">
    <button type="submit" disabled>Submit Bid</button>
    <p class="success" id="successMsg"></p>
    <p class="error" id="errorMsg"></p>
    <p style="font-size:small; color:#666;">* Bid submission demo not connected to backend *</p>
  </form>
</body>
</html>
