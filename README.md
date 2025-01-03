<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fast Earn - Watch, Engage, and Earn!</title>
    <style>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

header nav ul li {
    margin-left: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

/* Hero Section */
#hero {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 50px 20px;
}

#hero .btn {
    display: inline-block;
    background-color: white;
    color: #4CAF50;
    padding: 10px 20px;
    margin-top: 20px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}

/* Section Styles */
.section {
    padding: 40px 20px;
    text-align: center;
}

.section:nth-child(even) {
    background-color: #f1f1f1;
}

.section h2 {
    margin-bottom: 20px;
    color: #4CAF50;
}

/* Form Styles */
form {
    max-width: 400px;
    margin: 0 auto;
    text-align: left;
}

form label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
}

form input {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    width: 100%;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 4px;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
}

form button:hover {
    background-color: #45a049;
}

/* Footer Styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}

footer p {
    margin: 0;
}
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Fast Earn</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#features">Features</a></li>
                    <li><a href="#register">Register</a></li>
                    <li><a href="#login">Login</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="container">
            <h2>Earn Real Money by Watching, Subscribing, and Engaging!</h2>
            <p>Join Fast Earn today and start earning while you engage with content and promote your own social media!</p>
            <a href="#register" class="btn">Get Started</a>
        </div>
    </section>

    <section id="about" class="section">
        <div class="container">
            <h2>About Fast Earn</h2>
            <p>Fast Earn is a platform where users can watch videos, subscribe to YouTube channels, and engage with content to earn real money. Additionally, users can advertise and promote their own social media accounts to grow their audience.</p>
        </div>
    </section>

    <section id="features" class="section">
        <div class="container">
            <h2>Features</h2>
            <ul>
                <li>Watch videos and earn rewards</li>
                <li>Subscribe to channels and leave comments</li>
                <li>Promote your social media through ads</li>
                <li>Secure withdrawal options</li>
                <li>Referral system for extra earnings</li>
            </ul>
        </div>
    </section>

    <section id="register" class="section">
        <div class="container">
            <h2>Register Now</h2>
            <form action="/register" method="post">
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>

                <button type="submit" class="btn">Register</button>
            </form>
        </div>
    </section>

    <section id="login" class="section">
        <div class="container">
            <h2>Login</h2>
            <form action="/login" method="post">
                <label for="login-email">Email:</label>
                <input type="email" id="login-email" name="email" required>

                <label for="login-password">Password:</label>
                <input type="password" id="login-password" name="password" required>

                <button type="submit" class="btn">Login</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Fast Earn. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>

