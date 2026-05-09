<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Simple Website</title>
    <style>
        /* Reset some default styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            background-color: #f4f4f4;
        }

        /* Header */
        header {
            background: #007bff;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        /* Navigation */
        nav {
            background: #0056b3;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Main Content */
        .container {
            width: 80%;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 40px 20px;
        }

        .hero h2 {
            color: #333;
            margin-bottom: 10px;
        }

        .hero p {
            color: #666;
            margin-bottom: 20px;
        }

        .btn {
            display: inline-block;
            background: #007bff;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }

        .btn:hover {
            background: #0056b3;
        }

        /* About Section */
        .about {
            margin-top: 30px;
        }

        .about h3 {
            margin-bottom: 10px;
            color: #333;
        }

        /* Footer */
        footer {
            text-align: center;
            background: #333;
            color: white;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>My Website</h1>
        <p>Welcome to my simple website</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <!-- Main Content -->
    <div class="container">

        <!-- Hero Section -->
        <section class="hero">
            <h2>Hello, World!</h2>
            <p>This is a basic website created using HTML and CSS.</p>
            <a href="#" class="btn">Learn More</a>
        </section>

        <!-- About Section -->
        <section class="about">
            <h3>About Us</h3>
            <p>
                This website template is perfect for beginners who want to learn
                how to create a simple and responsive website using HTML and CSS.
            </p>
        </section>

    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 My Website. All Rights Reserved.</p>
    </footer>

</body>
</html>



