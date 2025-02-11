<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Join Our Leadership Network</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #004aad;
            color: white;
            text-align: center;
            padding: 20px 10px;
        }
        .container {
            max-width: 800px;
            margin: 30px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        h1, h2 {
            color: #333;
        }
        .image-section {
            text-align: center;
            margin: 20px 0;
        }
        .image-section img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            color: #555;
        }
        input, textarea, button {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background-color: #004aad;
            color: white;
            font-size: 16px;
            cursor: pointer;
            border: none;
        }
        button:hover {
            background-color: #003b87;
        }
        .footer {
            text-align: center;
            margin-top: 20px;
            color: #777;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Join Our Leadership Network</h1>
    </header>
    <div class="container">
        <h2>Become a Leader with Maniraya</h2>
        <p>We are looking for passionate and motivated leaders to join our team. Grow your network, earn competitive rewards, and make a difference in the world with our world-class products in cosmetics, healthcare, and agriculture.</p>
        <div class="image-section">
            <img src="your-image-url.jpg" alt="Leadership Opportunity">
        </div>
        <form action="/submit-form" method="POST">
            <div class="form-group">
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required>
            </div>
            <div class="form-group">
                <label for="message">Why are you interested in joining?</label>
                <textarea id="message" name="message" rows="4" required></textarea>
            </div>
            <button type="submit">Join Now</button>
        </form>
    </div>
    <div class="footer">
        <p>&copy; 2025 Maniraya. All Rights Reserved.</p>
    </div>
</body>
</html>
