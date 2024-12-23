<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fundraising Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        .container {
            padding: 2em;
        }
        .about-section {
            background-color: #ffffff;
            padding: 2em;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-bottom: 2em;
        }
        .donate-section {
            text-align: center;
        }
        .donate-section button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 1em 2em;
            border-radius: 5px;
            font-size: 1em;
            cursor: pointer;
        }
        .donate-section button:hover {
            background-color: #45a049;
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #333;
            color: white;
        }
        footer a {
            color: #4CAF50;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>Support Our Cause</h1>
    <p>Help us make a difference in the world.</p>
</header>

<div class="container">
    <div class="about-section">
        <h2>About Us</h2>
        <p>We are dedicated to [brief mission statement, e.g., providing clean water to communities in need, supporting education, or any cause].
           Your contribution will help us achieve our goals and change lives for the better.</p>
    </div>

    <div class="donate-section">
        <h2>Make a Donation</h2>
        <p>Every donation makes a difference. Click the button below to support our mission.</p>
        <button onclick="window.location.href='https://www.paypal.com/donate'">Donate Now</button>
    </div>
</div>

<footer>
    <p>&copy; 2024 Your Organization Name. All rights reserved.</p>
    <p><a href="#">Privacy Policy</a> | <a href="#">Contact Us</a></p>
</footer>

</body>
</html>
