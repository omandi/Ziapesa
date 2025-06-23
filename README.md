
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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Ziapesa Dashboard</title>
</head>
<body style="font-family:sans-serif; text-align:center; padding:40px;">
  <h1>Ziapesa Dashboard</h1>
  <p>Welcome, your phone login was successful!</p>
  <p><strong>Wallet Balance:</strong> KES 0 (Demo)</p>
  <p><strong>Referral Code:</strong> ZIA123</p>

  <h3>Investment Packages</h3>
  <ul style="list-style:none; padding:0;">
    <li>KES 1,500 → Profit KES 1,000 in 10 Days</li>
    <li>KES 3,000 → Profit KES 2,000 in 10 Days</li>
    <li>KES 7,000 → Profit KES 4,000 in 10 Days</li>
  </ul>

  <button>Invest</button>
  <button>Withdraw to M-Pesa</button>
</body>
</html>
https://github.com/YOURUSERNAME/ziapesa.git
