<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rate Our Website</title>
  <style>
    body {
      background: url('https://www.google.com/url?sa=i&url=https%3A%2F%2Funsplash.com%2Fs%2Fphotos%2Fwebsite-background&psig=AOvVaw0Ku0pKkhS9DlRlfikomcHC&ust=1706071866294000&source=images&cd=vfe&ved=0CBMQjRxqFwoTCJDqi5fb8oMDFQAAAAAdAAAAABAE') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
      font-family: Arial, sans-serif;
    }
    form {
      max-width: 400px;
      margin: 50px auto;
      padding: 20px;
      background: rgba(0, 0, 0, 0.7);
      border-radius: 8px;
    }
    label {
      display: block;
      margin-bottom: 8px;
    }
    input, select {
      width: 100%;
      padding: 8px;
      margin-bottom: 16px;
      box-sizing: border-box;
    }
    button {
      background-color: #4CAF50;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <form action="mailto:adarshkumar44u@gmail.com" method="post" enctype="text/plain">
    <h2>RATE OUR WEBSITE</h2>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="phone">Phone Number:</label>
    <input type="tel" id="phone" name="phone" required>

    <label for="gender">Gender:</label>
    <select id="gender" name="gender" required>
      <option value="male">Male</option>
      <option value="female">Female</option>
      <option value="others">Others</option>
    </select>

    <label for="state">State:</label>
    <select id="state" name="state" required>
      <option value="UP">Uttar Pradesh</option>
      <option value="MP">Madhya Pradesh</option>
      <option value="others">Others</option>
    </select>

    <label for="feedback">Tell us more for improvement for our website:</label>
    <textarea id="feedback" name="feedback" rows="4" required></textarea>

    <button type="submit">Submit</button>
  </form>

</body>
</html>
