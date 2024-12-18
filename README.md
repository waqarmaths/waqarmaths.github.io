<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Waqar Ali Soomro | Portfolio</title>
    <style>
        /* Reset some browser defaults */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f7ff;
            color: #333;
        }

        /* Navigation Bar */
        header {
            background-color: #002244;
            color: #fff;
            padding: 10px 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: #f39c12;
        }

        /* Sections */
        section {
            padding: 60px 20px;
            text-align: center;
        }

        #home {
            background: url('images/background.jpg') no-repeat center center/cover;
            color: #fff;
            padding: 100px 20px;
        }

        #home img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 4px solid #fff;
        }

        h1, h3 {
            margin: 20px 0;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 10px;
            background-color: #002244;
            color: #fff;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#biography">Biography</a></li>
                <li><a href="#research">Research</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home">
        <img src="images/profile.jpg" alt="Profile Picture">
        <h1>Waqar Ali Soomro</h1>
        <h3>Mathematics Enthusiast | Researcher | Aspiring Scholar</h3>
    </section>

    <!-- Biography Section -->
    <section id="biography">
        <h2>📜 Biography</h2>
        <p>I am <strong>Waqar Ali Soomro</strong>, a passionate mathematics enthusiast.  
            Though I completed my <strong>Bachelor's in Civil Engineering</strong>, my love for mathematics led me to pursue a  
            <strong>Master's in Applied Mathematics</strong> at <strong>NED University, Karachi, Pakistan</strong>.</p>
    </section>

    <!-- Research and Projects Section -->
    <section id="research">
        <h2>📊 Research and Projects</h2>
        <p><strong>Forecasting using Bayesian VAR Model</strong></p>
        <p><strong>Gaussian Copula</strong></p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>📧 Contact</h2>
        <p><strong>Email</strong>: <a href="mailto:waqar.soomro124@gmail.com">waqar.soomro124@gmail.com</a></p>
        <p><strong>LinkedIn</strong>: <a href="#" target="_blank">Your LinkedIn Profile</a></p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Waqar Ali Soomro | All Rights Reserved</p>
    </footer>
</body>
</html>
