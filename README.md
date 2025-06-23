
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ziapesa Login</title>
</head>
<body>
  <h2>Welcome to Ziapesa</h2>
  <form action="dashboard.html" method="GET">
    <label>Phone Number:</label><br />
    <input type="text" name="phone" placeholder="07XXXXXXXX" required /><br />
    <label>Enter Code:</label><br />
    <input type="text" name="otp" value="1234" readonly /><br />
    <button type="submit">Login</button>
  </form>
</body>
</html>
