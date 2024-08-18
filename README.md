# html file
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Landing Page</title>
    <link rel="stylesheet" href="style1.css">
</head>
<body>
    <header class="main-header">
        <nav>
            <h1>My Landing Page</h1>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h2>Welcome to Our Website</h2>
            <p>This is an example of a landing page built with HTML and CSS.</p>
            <a href="#" class="cta-btn">Get Started</a>
        </div>
    </section>

    <section class="features">
        <div class="feature-box">
            <h3>Feature 1</h3>
            <p>Describe an important feature here.</p>
        </div>
        <div class="feature-box">
            <h3>Feature 2</h3>
            <p>Highlight another cool feature.</p>
        </div>
        <div class="feature-box">
            <h3>Feature 3</h3>
            <p>Include more details about your offerings.</p>
        </div>
    </section>

    <footer class="main-footer">
        <p>&copy; 2024 My Landing Page. All rights reserved.</p>
    </footer>
</body>
</html>


# css file
/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

a {
    text-decoration: none;
    color: #fff;
}

/* Header */
.main-header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

.main-header nav ul {
    list-style: none;
    padding: 0;
}

.main-header nav ul li {
    display: inline;
    margin: 0 15px;
}

.main-header nav ul li a {
    color: #fff;
    font-weight: bold;
}

/* Hero Section */
.hero {
    background-color: #5cb85c;
    color: #fff;
    padding: 100px 0;
    text-align: center;
}

.hero-content h2 {
    font-size: 3rem;
}

.hero-content p {
    font-size: 1.2rem;
    margin: 20px 0;
}

.cta-btn {
    background-color: #333;
    padding: 10px 20px;
    border-radius: 5px;
    font-weight: bold;
}

/* Features Section */
.features {
    display: flex;
    justify-content: space-around;
    padding: 50px 0;
    background-color: #fff;
}

.feature-box {
    background-color: #f4f4f4;
    padding: 20px;
    text-align: center;
    border-radius: 5px;
    width: 30%;
}

.feature-box h3 {
    margin-bottom: 10px;
    font-size: 1.5rem;
}

/* Footer */
.main-footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
    position: relative;
    bottom: 0;
    width: 100%;
}


