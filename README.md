<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Local 701 - Grievance Machine Theme</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-color: #2e2e2e;
            color: #e0e0e0;
            font-family: 'Arial', sans-serif;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .header {
            text-align: center;
            padding: 50px;
            background: linear-gradient(to right, #3a3a3a, #1e1e1e);
            color: #f0f0f0;
            border-bottom: 2px solid #ff9000;
        }
        .header h1 {
            font-size: 4rem;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 4px;
        }
        .hero {
            background: url('gears_background.jpg') no-repeat center center/cover;
            padding: 100px;
            color: #fff;
            text-align: center;
            box-shadow: inset 0 0 100px rgba(0,0,0,0.5);
        }
        .hero h2 {
            font-size: 2.5rem;
        }gears_background.jpg
        .hero p {
            font-size: 1.2rem;
            margin-top: 10px;
        }
        .cta-button {
            margin-top: 30px;
            background-color: #ff9000;
            color: #fff;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.4);
            transition: all 0.3s ease;
        }
        .cta-button:hover {
            background-color: #ffb142;
            box-shadow: 0 6px 8px rgba(0, 0, 0, 0.6);
        }
        .features {
            display: flex;
            justify-content: space-between;
            margin-top: 50px;
        }
        .feature-box {
            background-color: #3a3a3a;
            border: 2px solid #1e1e1e;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.4);
            flex-basis: 30%;
            text-align: center;
        }
        .feature-box h3 {
            color: #ff9000;
            font-size: 1.8rem;
            margin-bottom: 10px;
        }
        .feature-box p {
            font-size: 1rem;
        }
        footer {
            margin-top: 50px;
            padding: 20px;
            text-align: center;
            background-color: #1e1e1e;
            border-top: 2px solid #ff9000;
            color: #b0b0b0;
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>Grievance Machine</h1>
            <p>Strong. United. Resilient.</p>
        </header>

        <section class="hero">
            <h2>Welcome to Local 701</h2>
            <p>Your rights are our mission. Together, we stand strong against all challenges.</p>
            <a href="#" class="cta-button">Join Us</a>
        </section>

        <section class="features">
            <div class="feature-box">
                <h3>Track Your Grievances</h3>
                <p>Our grievance tracker helps you stay up-to-date on the status of your filed concerns.</p>
            </div>
            <div class="feature-box">
                <h3>Get Support</h3>
                <p>Resources and guidance to help you understand your rights and take action.</p>
            </div>
            <div class="feature-box">
                <h3>Union Forum</h3>
                <p>Engage with other members and discuss important issues that affect us all.</p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 AFGE Local 701. All Rights Reserved.</p>
    </footer>
</body>
</html>
