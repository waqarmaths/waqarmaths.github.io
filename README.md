<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Waqar Ali | Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.8;
            background: linear-gradient(135deg, #004466, #003f5c, #1f3b4d);
            color: #e0f7fa;
            padding-top: 80px;
        }

        header {
            background: rgba(0, 36, 68, 0.9);
            color: #e0f7fa;
            padding: 15px 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        nav ul {
            list-style: none;
        }

        nav ul li {
            display: inline-block;
            margin: 0 15px;
        }

        nav ul li a {
            color: #e0f7fa;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #80deea;
        }

        #home {
            text-align: center;
            color: #fff;
            background: url('background.jpg') no-repeat center center/cover;
            padding: 100px 20px;
        }

        #home img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            border: 5px solid #fff;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #80deea;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.3);
        }

        ul {
            list-style: none;
            text-align: left;
            display: inline-block;
            width: 70%;
        }

        ul li {
            margin-bottom: 10px;
            font-size: 1.1em;
        }

        a.github {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            font-size: 1.2em;
            font-weight: bold;
            color: #e0f7fa;
            background: linear-gradient(135deg, #003f5c, #1f3b4d);
            text-decoration: none;
            border-radius: 8px;
            transition: background 0.3s, color 0.3s;
        }

        a.github:hover {
            background: #80deea;
            color: #003f5c;
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: rgba(0, 36, 68, 0.9);
            color: #e0f7fa;
            margin-top: 40px;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#biography">Biography</a></li>
                <li><a href="#research">Research</a></li>
                <li><a href="#certifications">Certifications</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#awards">Awards</a></li>
                <li><a href="#extra">Volunteer Work</a></li>
                <li><a href="#languages">Languages</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <img src="IMG-20230815-WA0003.jpg" alt="Profile Picture">
        <h1>Waqar Ali</h1>
        <h3>Mathematics Enthusiast | Researcher | Aspiring Scholar</h3>
    </section>

    <section id="biography">
        <h2>📜 Biography</h2>
        <p>I am <strong>Waqar Ali</strong>, a passionate mathematics enthusiast and researcher. 
        I am pursuing my <strong>MSc in Applied Mathematics</strong> with a specialization in stochastic processes at Budapest University of Technology and Economics (BUTE), Hungary. I also hold a <strong>B.E. in Civil Engineering</strong> from Mehran University of Engineering and Technology, Pakistan.</p>
        <p>My research is driven by a passion for stochastic modeling and its integration with machine learning, aiming to develop predictive models for complex systems.</p>
    </section>

    <section id="research">
        <h2>📊 Research and Projects</h2>
        <ul>
            <li><strong>Flowers Classification Project:</strong> Pre-trained model evaluation, feature concatenation, and ensemble modeling for high accuracy.</li>
            <li><strong>Gaussian Copula:</strong> Developed and visualized stochastic models for risk assessment using Python.</li>
            <li><strong>Vector Autoregression (VAR):</strong> Bayesian priors estimation, data truncation, forecasting, and impulse response analysis.</li>
        </ul>
    </section>

    <section id="certifications">
        <h2>📜 Certifications</h2>
        <ul>
            <li>Machine Learning Techniques in MATLAB from MathWorks</li>
            <li>Google Data Analytics Professional Certification</li>
            <li>MATLAB Programming for Engineers and Scientists</li>
            <!-- Additional certifications restored -->
        </ul>
    </section>

    <section id="skills">
        <h2>💻 Technical Skills</h2>
        <ul>
            <li>Machine Learning (Intermediate)</li>
            <li>Data Analysis (Intermediate)</li>
            <li>MATLAB (Intermediate)</li>
        </ul>
    </section>

    <section id="contact">
        <h2>📧 Contact</h2>
        <p>Email: <a href="mailto:waqar.soomro124@gmail.com">waqar.soomro124@gmail.com</a></p>
        <p>GitHub: <a href="https://github.com/waqarmaths" class="github">Visit my GitHub</a></p>
        <p>LinkedIn: <a href="http://www.linkedin.com/in/waqaralimaths">linkedin.com/in/waqaralimaths</a></p>
        <p>Website: <a href="https://waqarmaths.github.io">waqarmaths.github.io</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Waqar Ali | All Rights Reserved</p>
    </footer>
</body>
</html>
